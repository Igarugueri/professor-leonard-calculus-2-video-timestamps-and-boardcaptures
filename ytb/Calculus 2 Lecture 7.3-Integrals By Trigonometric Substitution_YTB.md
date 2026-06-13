-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ７．３ - Ｉｎｔｅｇｒａｌｓ Ｂｙ Ｔｒｉｇｏｎｏｍｅｔｒｉｃ Ｓｕｂｓｔｉｔｕｔｉｏｎ**---------------------------------






Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:01]. Introduction to Section 7.3: Trigonometric Substitution.
     ◉ Standard integration methods do not directly handle certain radical expressions.
     ◉ The method is motivated by the Pythagorean Theorem and right-triangle constructions.




     
🧩 Ｆｉｒｓｔ Ｍｏｄｅｌ Ｅｘａｍｐｌｅ


● [1:12]. Geometric interpretation of radicals.
     ◉ Relate the radical to the Pythagorean Theorem and a right triangle.
     ◉ Rewrite:
          ○ √(1 + 𝒙²) = √(1² + 𝒙²)
     ◉ Determine whether the radical represents the hypotenuse or a leg.
          ○ General classification:
               ■ In a form like √(𝒂² + 𝒙²), the radical is the hypotenuse.
               ■ In a form like √(𝒂² − 𝒙²), the radical is a leg.
               ■ In a form like √(𝒙² − 𝒂²), the radical is also a leg.
               ■ NOTE: The letter 𝒂 is just the constant in the expression. Its role depends on the form of the radical:
                   ▣ if the hypotenuse is the constant term, then 𝒂 is the hypotenuse;
                   ▣ if the variable 𝒙 term is the hypotenuse, then 𝒂 is a leg.
          ○ Using the usual right-triangle notation:
               ■ Form √(𝒂² + 𝓫²): the radical is the hypotenuse 𝓬.
               ■ Form 𝒂 = √(𝓬² − 𝓫²): the radical is a leg.
               ■ Form 𝓫 = √(𝓬² − 𝒂²): the radical is a leg.

● [4:14]. Strategy for constructing the reference triangle.
     ◉ Build the triangle for the model radical √(1 + 𝒙²).
          ○ adjacent side = 1
          ○ opposite side = 𝒙
          ○ hypotenuse = √(1 + 𝒙²)
     ◉ Arrange the triangle so that a basic trig ratio gives 𝒙/𝒂.
     ◉ Trigonometric relation:
          ○ tan(θ) = 𝒙/1
          ○ tan(θ) = 𝒙
     ◉ First substitution model:
          ○ 𝒙 = tan(θ)
     ◉ Rewrite the radical:
          ○ √(1 + 𝒙²) → √(1 + tan²(θ))
     ◉ Differentiate:
          ○ 𝒅𝒙 = sec²(θ) 𝒅θ


● [7:05]. Rewrite the integral using the substitution.
     ◉ Substitute:
          ○ 𝒙 = tan(θ)
          ○ 𝒅𝒙 = sec²(θ) 𝒅θ
     ◉ Transform the radical:
          ○ √(1 + 𝒙²) → √(1 + tan²(θ))

● [9:52]. Trigonometric integral obtained after substitution.
     ◉ Use the identity:
          ○ 1 + tan²(θ) = sec²(θ)
     ◉ Then:
          ○ √(1 + tan²(θ)) = √(sec²(θ)) = sec(θ)
     ◉ The integral becomes:
          ○ ∫ sec³(θ) 𝒅θ
     ◉ Apply the known secant-power result:
          ○ ∫ sec³(θ) 𝒅θ = (1/2)sec(θ)tan(θ) + (1/2)ln|sec(θ) + tan(θ)| + 𝓒

● [14:44]. Return to the original variable using the triangle.
     ◉ Recover the trigonometric functions:
          ○ sec(θ) = √(1 + 𝒙²)
          ○ tan(θ) = 𝒙
     ◉ Substitute back into the antiderivative.

● [17:18]. Final result.
     ◉ The antiderivative is:
          ○ (1/2)𝒙√(1 + 𝒙²) + (1/2)ln|√(1 + 𝒙²) + 𝒙| + 𝓒
               ■ See lecture 7.1





               
Ｔｈｅ Ｔｈｒｅｅ Ｓｔａｎｄａｒｄ Ｃａｓｅｓ

● [18:56]. Classification of the three standard trig-substitution forms. 
     ◉ Case 1: √(𝒂² − 𝒙²)
          ○ Build the triangle associated with sine substitution.
          ○ Use 𝒙 = 𝒂 sin(θ).
     ◉ [27:36]. Case 2: √(𝒂² + 𝒙²)
          ○ Build the triangle associated with tangent substitution.
          ○ Use 𝒙 = 𝒂 tan(θ).
     ◉ [30:40]. Case 3: √(𝒙² − 𝒂²)
          ○ Build the triangle associated with secant substitution.
          ○ Use 𝒙 = 𝒂 sec(θ).





          
Ｅｘａｍｐｌｅｓ — Ｔｒｉｇｏｎｏｍｅｔｒｉｃ Ｓｕｂｓｔｉｔｕｔｉｏｎ

● [36:36]. 🧩 Example 1 — : ∫ 𝒙² / √(9 − 𝒙²) 𝒅𝒙. 
     ◉ Identify the radical as the form √(𝒂² − 𝒙²).
     ◉ Build the reference triangle:
          ○ hypotenuse = 3
          ○ opposite side = 𝒙
          ○ adjacent side = √(9 − 𝒙²)
     ◉ Trigonometric relation:
          ○ sin(θ) = 𝒙/3
     ◉ Substitution:
          ○ 𝒙 = 3 sin(θ)
          ○ 𝒅𝒙 = 3 cos(θ) 𝒅θ
     ◉ Substitute into the integral:
          ○ ∫ (3 sin(θ))² / √(9 − (3 sin(θ))²) · 3 cos(θ) 𝒅θ
     ◉ Simplify the radical:
          ○ √(9 − 9 sin²(θ)) = 3√(1 − sin²(θ))
     ◉ Use the identity:
          ○ 1 − sin²(θ) = cos²(θ)
     ◉ Reduce the integral to:
          ○ 9∫ sin²(θ) 𝒅θ
     ◉ Rewrite sin²(θ) with the half-angle identity:
          ○ sin²(θ) = (1/2)(1 − cos(2θ))
     ◉ Integrate:
          ○ 9∫ (1/2)(1 − cos(2θ)) 𝒅θ
          ○ = (9/2)[θ − (1/2)sin(2θ)] + 𝓒
     ◉ Rewrite in terms of 𝒙:
          ○ θ = sin⁻¹(𝒙/3)
          ○ sin(θ) = 𝒙/3
          ○ cos(θ) = √(9 − 𝒙²)/3
          ○ sin(2θ) = 2 sin(θ)cos(θ)
     ◉ Final result:
          ○ (9/2)sin⁻¹(𝒙/3) − (1/2)𝒙√(9 − 𝒙²) + 𝓒
     
● [54:25]. 🧩 Example 2 — Definite integral: ∫[1, √3] 1 / (1 + 𝒙²)³ᐟ² 𝒅𝒙. 
     ◉ Rewrite the denominator as a radical power:
          ○ 1 / (√(1 + 𝒙²))³
     ◉ Build the reference triangle for √(1 + 𝒙²):
          ○ adjacent side = 1
          ○ opposite side = 𝒙
          ○ hypotenuse = √(1 + 𝒙²)
     ◉ Trigonometric relation:
          ○ tan(θ) = 𝒙
     ◉ Substitution:
          ○ 𝒙 = tan(θ)
          ○ 𝒅𝒙 = sec²(θ) 𝒅θ
     ◉ [1:01:17]. Change the bounds:
          ○ 𝒙 = 1 → θ = π/4
          ○ 𝒙 = √3 → θ = π/3
          ○ Therefore:
               ■ 𝒙 ∈ [1, √3] → θ ∈ [π/4, π/3]
     ◉ Transform the integral:
          ○ ∫[π/4, π/3] sec²(θ) / (√(1 + tan²(θ)))³ 𝒅θ
     ◉ Use the identity:
          ○ 1 + tan²(θ) = sec²(θ)
     ◉ Simplify to the elementary integral:
          ○ ∫[π/4, π/3] cos(θ) 𝒅θ
     ◉ Evaluate:
          ○ sin(θ)|[π/4, π/3]
          ○ = sin(π/3) − sin(π/4)
     ◉ Final result:
          ○ (√3 − √2)/2
          
● [1:10:57]. 🧩 Example 3 —: ∫ √(𝒙² − 4) / 𝒙⁴ 𝒅𝒙. 
     ◉ Identify the standard form:
          ○ √(𝒙² − 𝒂²)
     ◉ Build the reference triangle:
          ○ hypotenuse = 𝒙
          ○ adjacent side = 2
          ○ opposite side = √(𝒙² − 4)
     ◉ Trigonometric relation:
          ○ sec(θ) = 𝒙/2
     ◉ Substitution:
          ○ 𝒙 = 2 sec(θ)
          ○ 𝒅𝒙 = 2 sec(θ)tan(θ) 𝒅θ
     ◉ Transform the integral:
          ○ ∫ √((2 sec(θ))² − 4) / (2 sec(θ))⁴ · 2 sec(θ)tan(θ) 𝒅θ
     ◉ Simplify step by step:
          ○ √(4 sec²(θ) − 4) = 2√(sec²(θ) − 1)
          ○ sec²(θ) − 1 = tan²(θ)
          ○ The integral becomes:
               ■ (1/4) ∫ tan²(θ) / sec³(θ) 𝒅θ
     ◉ Rewrite in sine and cosine:
          ○ tan²(θ) / sec³(θ) = sin²(θ)cos(θ)
          ○ So:
               ■ (1/4) ∫ sin²(θ)cos(θ) 𝒅θ
     ◉ Secondary substitution:
          ○ 𝒖 = sin(θ)
          ○ 𝒅𝒖 = cos(θ) 𝒅θ
     ◉ Resulting polynomial integral:
          ○ (1/4) ∫ 𝒖² 𝒅𝒖
     ◉ Antiderivative:
          ○ (1/12) sin³(θ) + 𝓒
     ◉ Return to the original variable using the triangle:
          ○ sin(θ) = √(𝒙² − 4) / 𝒙
     ◉ Final result:
          ○ (1/12)[√(𝒙² − 4) / 𝒙]³ + 𝓒
          ○ (𝒙² − 4)³ᐟ² / 12𝒙³ + 𝓒
     
● [1:33:13]. 🧩 Example 4 — Evaluate ∫ 1 / (3 − 2𝒙 − 𝒙²)⁵ᐟ² 𝒅𝒙. 
     ◉ Rewrite the denominator as a radical power:
          ○ ∫ 1 / [√(3 − 2𝒙 − 𝒙²)]⁵ 𝒅𝒙
     ◉ Complete the square in the quadratic expression:
          ○ 3 − 2𝒙 − 𝒙²
          ○ = −𝒙² − 2𝒙 + 3
          ○ = −(𝒙² + 2𝒙) + 3
          ○ = −(𝒙² + 2𝒙 + 1) + 3 + 1
          ○ = −(𝒙 + 1)² + 4
          ○ = 4 − (𝒙 + 1)²
     ◉ Substitute this back into the integral:
          ○ ∫ 1 / [√(4 − (𝒙 + 1)²)]⁵ 𝒅𝒙
     ◉ First substitution to standardize the radical:
          ○ 𝒖 = 𝒙 + 1
          ○ 𝒅𝒖 = 𝒅𝒙
     ◉ The integral becomes:
          ○ ∫ 1 / [√(4 − 𝒖²)]⁵ 𝒅𝒖
     ◉ Recognize the form:
          ○ √(2² − 𝒖²)
     ◉ Build the reference triangle:
          ○ hypotenuse = 2
          ○ opposite side = 𝒖
          ○ adjacent side = √(4 − 𝒖²)
     ◉ Trigonometric substitution:
          ○ sin(θ) = 𝒖/2
          ○ 𝒖 = 2 sin(θ)
          ○ 𝒅𝒖 = 2 cos(θ) 𝒅θ
     ◉ Substitute into the integral:
          ○ ∫ 1 / [√(4 − (2 sin(θ))²)]⁵ · 2 cos(θ) 𝒅θ
          ○ = ∫ 1 / [√(4 − 4 sin²(θ))]⁵ · 2 cos(θ) 𝒅θ
          ○ = ∫ 1 / [2√(1 − sin²(θ))]⁵ · 2 cos(θ) 𝒅θ
          ○ = ∫ 2 cos(θ) / 32[√(1 − sin²(θ))]⁵ 𝒅θ
          ○ = (1/16) ∫ cos(θ) / [√(1 − sin²(θ))]⁵ 𝒅θ
     ◉ Use the identity:
          ○ 1 − sin²(θ) = cos²(θ)
     ◉ Then:
          ○ (1/16) ∫ cos(θ) / [√(cos²(θ))]⁵ 𝒅θ
          ○ = (1/16) ∫ cos(θ) / cos⁵(θ) 𝒅θ
          ○ = (1/16) ∫ 1 / cos⁴(θ) 𝒅θ
          ○ = (1/16) ∫ sec⁴(θ) 𝒅θ
     ◉ Rewrite sec⁴(θ):
          ○ (1/16) ∫ sec²(θ) · sec²(θ) 𝒅θ
     ◉ Use the identity:
          ○ sec²(θ) = tan²(θ) + 1
     ◉ So:
          ○ (1/16) ∫ (tan²(θ) + 1) · sec²(θ) 𝒅θ
     ◉ Secondary substitution:
          ○ 𝓦 = tan(θ)
          ○ 𝒅𝓦 = sec²(θ) 𝒅θ
     ◉ The integral becomes:
          ○ (1/16) ∫ (𝓦² + 1) 𝒅𝓦
     ◉ Integrate:
          ○ (1/16) [(1/3)𝓦³ + 𝓦]
          ○ = (1/16) [(1/3)tan³(θ) + tan(θ)]
     ◉ Return from θ to 𝒖 using the triangle:
          ○ tan(θ) = opposite / adjacent
          ○ tan(θ) = 𝒖 / √(4 − 𝒖²)
     ◉ Substitute:
          ○ (1/16) [ (1/3)(𝒖 / √(4 − 𝒖²))³ + 𝒖 / √(4 − 𝒖²) ] + 𝓒
     ◉ Put both terms over the same denominator:
          ○ = (1/16) [ 𝒖³ / 3(√(4 − 𝒖²))³ + 3𝒖(4 − 𝒖²) / 3(√(4 − 𝒖²))³ ] + 𝓒
     ◉ Combine the numerators:
          ○ = (1/16) [ 𝒖³ + 3𝒖(4 − 𝒖²) ] / 3(√(4 − 𝒖²))³ + 𝓒
          ○ = (1/16) [ 𝒖³ + 12𝒖 − 3𝒖³ ] / 3(√(4 − 𝒖²))³ + 𝓒
          ○ = (1/16) [ 12𝒖 − 2𝒖³ ] / 3(√(4 − 𝒖²))³ + 𝓒
          ○ = (1/24) [ 6𝒖 − 𝒖³ ] / (√(4 − 𝒖²))³ + 𝓒
     ◉ Substitute back 𝒖 = 𝒙 + 1:
          ○ = (1/24) [ 6(𝒙 + 1) − (𝒙 + 1)³ ] / (√(4 − (𝒙 + 1)²))³ + 𝓒
     ◉ Expand the numerator:
          ○ 6(𝒙 + 1) = 6𝒙 + 6
          ○ (𝒙 + 1)³ = 𝒙³ + 3𝒙² + 3𝒙 + 1
          ○ 6(𝒙 + 1) − (𝒙 + 1)³
               ■ = 6𝒙 + 6 − (𝒙³ + 3𝒙² + 3𝒙 + 1)
               ■ = 6𝒙 + 6 − 𝒙³ − 3𝒙² − 3𝒙 − 1
               ■ = 5 + 3𝒙 − 3𝒙² − 𝒙³
     ◉ Simplify the denominator:
          ○ 4 − (𝒙 + 1)² = 4 − (𝒙² + 2𝒙 + 1)
          ○ = 3 − 2𝒙 − 𝒙²
     ◉ Final result:
          ○ (1/24) [5 + 3𝒙 − 3𝒙² − 𝒙³] / (√(3 − 2𝒙 − 𝒙²))³ + 𝓒





Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

[openstax🌐](https://openstax.org/books/calculus-volume-2/pages/3-3-trigonometric-substitution)
     


https://www.youtube.com/watch?v=q6JwTGpG8b4&list=PLDesaqWTN6EQ2J4vgsN1HyBeRADEh4Cw-&index=10

Calculus 2 Lecture 7.3: Integrals By Trigonometric Substitution
