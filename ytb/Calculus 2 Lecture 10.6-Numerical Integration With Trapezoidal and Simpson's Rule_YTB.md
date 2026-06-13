-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ １０．６： Ｎｕｍｅｒｉｃａｌ  Ｉｎｔｅｇｒａｔｉｏｎ  Ｗｉｔｈ  Ｔｒａｐｅｚｏｉｄａｌ  ａｎｄ  Ｓｉｍｐｓｏｎ＇ｓ  Ｒｕｌｅ**-----------------------------------






１ - Ｎｕｍｅｒｉｃａｌ Ｉｎｔｅｇｒａｔｉｏｎ


● [0:00]. Introduction to Numerical Integration.
     ◉ Goal:
          ○ approximate definite integrals such as ∫[𝒂,𝒃] 𝒇(𝒙) 𝒅𝒙 when no standard antiderivative formula is known yet
     ◉ Main idea:
          ○ use finite numerical processes to estimate the value of a definite integral
     ◉ Therefore:
          ○ the two main methods introduced here are the Trapezoidal Rule and Simpson’s Rule

● [1:27]. The Trapezoidal Rule. 
     ◉ Goal:
          ○ approximate the area under a curve by dividing the interval into trapezoids
     ◉ Formula:
          ○ ∫[𝒂,𝒃] 𝒇(𝒙) 𝒅𝒙 ≈ (Δ𝒙/2)[𝒇(𝒙₀) + 2𝒇(𝒙₁) + 2𝒇(𝒙₂) + ⋯ + 2𝒇(𝒙ₙ₋₁) + 𝒇(𝒙ₙ)]
     ◉ Important:
          ○ the first term 𝒇(𝒙₀) is not doubled
          ○ the last term 𝒇(𝒙ₙ) is not doubled
          ○ every interior term is multiplied by 2

● [2:52]. Components of the numerical formula.
     ◉ Subinterval width:
          ○ Δ𝒙 = (𝒃 - 𝒂)/𝒏
     ◉ Reason:
          ○ 𝒏 must be finite, since this is a numerical approximation
          ○ i̲f̲ 𝒏 → ∞
               ■ t̲h̲e̲n̲ the process approaches the exact integral rather than a finite approximation
     ◉ Grid points:
          ○ 𝒙ᵢ = 𝒂 + 𝒊Δ𝒙
     ◉ Meaning:
          ○ start at the lower bound 𝒂
          ○ then keep adding Δ𝒙 to generate the sequence 𝒙₀, 𝒙₁, 𝒙₂, …

          
● [4:18]. 🧩 Example — Approximate: ∫[1,2] (1/𝒙) 𝒅𝒙 with 𝒏 = 10.  
     ◉ Goal:
          ○ use the Trapezoidal Rule to estimate the value of the integral
     ◉ Compute the width:
          ○ Δ𝒙 = (2 - 1)/10 = 1/10 = 0.1
     ◉ Generate the grid points:
          ○ 𝒙₀ = 1.0
          ○ 𝒙₁ = 1.1
          ○ 𝒙₂ = 1.2
          ○ 𝒙₃ = 1.3
          ○ …
          ○ 𝒙₉ = 1.9
          ○ 𝒙₁₀ = 2.0
     ◉ Set up the trapezoidal sum:
          ○ ∫[1,2] (1/𝒙) 𝒅𝒙 ≈ (0.1/2)[𝒇(1) + 2𝒇(1.1) + 2𝒇(1.2) + 2𝒇(1.3) + ... + 2𝒇(1.9) + 𝒇(2)]
     ◉ Use the function:
          ○ 𝒇(𝒙) = 1/𝒙
     ◉ Numerical approximation:
          ○ ∫[1,2] (1/𝒙) 𝒅𝒙 ≈ (0.1/2)[1/1 + 2·(1/1.1) + 2·(1/1.2) + 2·(1/1.3) + ... + 2·(1/1.9) + 1/2]
     ◉ Final result:
          ○ numerical approximation ≈ 0.69377
     ◉ Exact value check:
          ○ ∫[1,2] (1/𝒙) 𝒅𝒙 = [ln(𝒙)]₁² = ln(2) - ln(1) = ln(2) ≈ 0.69314
     ◉ Final interpretation:
          ○ the trapezoidal approximation is very close to the exact value
          ○ it is correct to the thousandths place
          ○ the error is about 0.00063
     ◉ Accuracy idea:
          ○ i̲f̲ 𝒏 increases
          ○ t̲h̲e̲n̲ the error decreases because the trapezoids become narrower





２－Ｓｉｍｐｓｏｎ’ｓ Ｒｕｌｅ
          
● [15:19]. Simpson’s Rule.
     ◉ Goal:
          ○ approximate definite integrals with a method that is usually more accurate than the Trapezoidal Rule
     ◉ Main idea:
          ○ use a coefficient pattern based on parabolic fitting rather than trapezoids
     ◉ Formula:
          ○ ∫[𝒂,𝒃] 𝒇(𝒙) 𝒅𝒙 ≈ (Δ𝒙/3)[𝒇(𝒙₀) + 4𝒇(𝒙₁) + 2𝒇(𝒙₂) + 4𝒇(𝒙₃) + ⋯ + 4𝒇(𝒙ₙ₋₁) + 𝒇(𝒙ₙ)]
     ◉ Important:
          ○ the endpoints are not multiplied by anything
          ○ the interior coefficients alternate:
               ■ 4, 2, 4, 2, 4, 2, …
          ○ the lead factor is Δ𝒙/3, not Δ𝒙/2

● [16:18]. **Restriction on 𝒏 for Simpson’s Rule.**
     ◉ Condition:
          ○ i̲f̲ 𝒏 is even
               ■ t̲h̲e̲n̲ Simpson’s Rule can be used
     ◉ Warning:
          ○ Simpson’s Rule does not apply when 𝒏 is odd


● [17:19]. 🧩 Example — Approximate: ∫[0,2] 1/√(𝒙 + 1) 𝒅𝒙 with 𝒏 = 6.  
     ◉ Reason:
          ○ 𝒏 = 6 is even, so Simpson’s Rule is allowed
     ◉ Goal:
          ○ approximate the integral using Simpson’s Rule
     ◉ Procedure:
          ○ Compute the width:
               ■ Δ𝒙 = (2 - 0)/6 = 1/3
          ○ Important:
               ■ keep Δ𝒙 as the fraction 1/3 instead of rounding
               ■ this helps avoid unnecessary rounding error
          ○ Generate the grid points:
               ■ 𝒙₀ = 0
               ■ 𝒙₁ = 1/3
               ■ 𝒙₂ = 2/3
               ■ 𝒙₃ = 1
               ■ 𝒙₄ = 4/3
               ■ 𝒙₅ = 5/3
               ■ 𝒙₆ = 2
          ○ Set up the Simpson sum:
               ■ ∫[0,2] 1/√(𝒙 + 1) 𝒅𝒙 ≈ ((1/3)/3)[𝒇(0) + 4𝒇(1/3) + 2𝒇(2/3) + 4𝒇(1) + 2𝒇(4/3) + 4𝒇(5/3) + 𝒇(2)]
          ○ Use the function:
               ■ 𝒇(𝒙) = 1/√(𝒙 + 1)
          ○ Numerical approximation:
               ■ ≈ 1.46421
     ◉ Exact value check:
          ○ ∫[0,2] 1/√(𝒙 + 1) 𝒅𝒙 = ∫[0,2] (𝒙 + 1)^(-1/2) 𝒅𝒙
          ○ = 2√(𝒙 + 1)│[0,2]
          ○ = 2√3 - 2
          ○ ≈ 1.46410
     ◉ Final interpretation:
          ○ the Simpson approximation is extremely close to the exact value
          ○ the error is only about 0.0001




Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Numerical Integration
     ◉ [Openstax🌐](https://openstax.org/books/calculus-volume-2/pages/3-6-numerical-integration)