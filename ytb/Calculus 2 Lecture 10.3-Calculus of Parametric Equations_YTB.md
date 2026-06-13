-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ １０．３： Ｃａｌｃｕｌｕｓ ｏｆ Ｐａｒａｍｅｔｒｉｃ Ｅｑｕａｔｉｏｎｓ**-------------------------------—





１ - Ｌｏｃａｌ　Ｆｕｎｃｔｉｏｎ　Ｎｅｉｇｈｂｏｒｈｏｏｄ　＆　Ｓｅｔｕｐ　ｆｏｒ　ｔｈｅ　Ｓｌｏｐｅ　Ｆｏｒｍｕｌａ

● [0:00]. Introduction: Calculus with Parametric Equations.
     ◉ Goal:
          ○ Find the slope of a parametric curve at a specific point 𝑷
     ◉ Main idea:
          ○ A parametric curve may fail the vertical line test globally,
          ○ but near a specific point 𝑷, we can cut out a small section where the curve behaves like a function
     ◉ Function neighborhood:
          ○ A small local piece of the curve around 𝑷
          ○ on this small section, the vertical line test is satisfied
     ◉ Important:
          ○ The tangent line is understood locally, on this function neighborhood

● [4:10]. Parametric components of the curve.
     ◉ The curve is given parametrically by:
          ○ 𝒙 = 𝒇(𝑻)
          ○ 𝒚 = 𝒈(𝑻)
     ◉ The parameter varies on a local interval:
          ○ 𝑻 ∈ 𝐈 = [𝒂, 𝒃]
     ◉ Meaning:
          ○ The endpoints of this interval determine the beginning and end of the small section we are studying around 𝑷

● [6:55]. Defining a local rectangular function.
     ◉ On this small section of the curve, we can treat 𝒚 as a function of 𝒙:
          ○ 𝒚 = 𝓕(𝒙)
     ◉ This local function is consistent with the original parametric equations:
          ○ 𝒙 = 𝒇(𝑻)
          ○ 𝒚 = 𝒈(𝑻)
     ◉ Therefore:
          ○ 𝒈(𝑻) = 𝓕(𝒇(𝑻))
     ◉ This is the key setup:
          ○ now we can differentiate using the Chain Rule




２ - Ｄｅｒｉｖａｔｉｏｎ　ｏｆ　ｔｈｅ　Ｆｉｒｓｔ　Ｄｅｒｉｖａｔｉｖｅ　Ｆｏｒｍｕｌａ

● [11:09]. Derivation of the first derivative formula.
     ◉ On the small function neighborhood around 𝑷:
          ○ we can write 𝒚 as a function of 𝒙
          ○ 𝒚 = 𝓕(𝒙)
     ◉ Original parametric equations:
          ○ 𝒙 = 𝒇(𝑻)
          ○ 𝒚 = 𝒈(𝑻)
     ◉ Therefore:
          ○ 𝒈(𝑻) = 𝓕(𝒇(𝑻))
     ◉ Differentiate with respect to 𝑻:
          ○ 𝒅/𝒅𝑻 [𝒈(𝑻)] = 𝒅/𝒅𝑻 [𝓕(𝒇(𝑻))]
     ◉ Apply the Chain Rule:
          ○ 𝒈′(𝑻) = 𝓕′(𝒇(𝑻)) · 𝒇′(𝑻)
     ◉ Since 𝓕′(𝒙) = 𝒅𝒚/𝒅𝒙:
          ○ 𝒈′(𝑻) = (𝒅𝒚/𝒅𝒙) · 𝒇′(𝑻)
     ◉ Solve for the derivative:
          ○ 𝒅𝒚/𝒅𝒙 = 𝒈′(𝑻) / 𝒇′(𝑻)
          ○ 𝒅𝒚/𝒅𝒙 = (𝒅𝒚/𝒅𝑻) / (𝒅𝒙/𝒅𝑻)
     ◉ Meaning:
          ○ the slope of the parametric curve is the ratio of vertical change to horizontal change

● [18:06]. 🧩 Example 1 — Find the equation of the tangent line for 𝒙 = sec(𝑻), 𝒚 = tan(𝑻), at 𝑻 = π/4, with -π/2 < 𝑻 < π/2.
     ◉ ❶ Find the point on the curve.
          ○ at 𝑻 = π/4:
               ■ 𝒙 = sec(π/4) = √2
               ■ 𝒚 = tan(π/4) = 1
          ○ so the point is:
               ■ (√2, 1)
     ◉ ❷ Find the slope.
          ○ use the parametric derivative formula:
               ■ 𝒅𝒚/𝒅𝒙 = (𝒅𝒚/𝒅𝑻) / (𝒅𝒙/𝒅𝑻)
          ○ differentiate:
               ■ 𝒅𝒚/𝒅𝑻 = sec²(𝑻)
               ■ 𝒅𝒙/𝒅𝑻 = sec(𝑻)tan(𝑻)
          ○ substitute:
               ■ 𝒅𝒚/𝒅𝒙 = sec²(𝑻) / [sec(𝑻)tan(𝑻)]
               ■ 𝒅𝒚/𝒅𝒙 = sec(𝑻) / tan(𝑻)
          ○ evaluate at 𝑻 = π/4:
               ■ 𝒎 = sec(π/4) / tan(π/4)
               ■ 𝒎 = √2 / 1 = √2
     ◉ ❸ Use point-slope form.
          ○ 𝒚 - 𝒚₁ = 𝒎(𝒙 - 𝒙₁)
          ○ 𝒚 - 1 = √2(𝒙 - √2)
     ◉ ❹ Simplify.
          ○ 𝒚 - 1 = √2𝒙 - 2
          ○ 𝒚 = √2𝒙 - 1
     ◉ Final result:
          ○ 𝒚 = √2𝒙 - 1





３ -  Ｈｏｒｉｚｏｎｔａｌ　ａｎｄ　Ｖｅｒｔｉｃａｌ　Ｔａｎｇｅｎｔｓ

● [28:46]. Criteria for horizontal and vertical tangents.
     ◉ Horizontal tangent:
          ○ i̲f̲ 𝒅𝒚/𝒅𝒕  = 0 and 𝒅𝒙/𝒅𝒕  ≠ 0
               ■ t̲h̲e̲n̲ 𝒅𝒚/𝒅𝒙 = 0
     ◉ Vertical tangent:
          ○ i̲f̲ 𝒅𝒚/𝒅𝒕  ≠ 0 and 𝒅𝒙/𝒅𝒕  = 0
               ■ t̲h̲e̲n̲ 𝒅𝒚/𝒅𝒙 → ±∞
     ◉ Warning:
          ○ i̲f̲ 𝒅𝒚/𝒅𝒕  = 0 and 𝒅𝒙/𝒅𝒕  = 0
               ■ t̲h̲e̲n̲ the slope is indeterminate
               ■ this requires L’Hôpital’s Rule

● [33:42]. 🧩 Example 2 — Horizontal and vertical tangents: 𝒙 = 𝒕², 𝒚 = 𝒕³ - 3𝒕.
     ◉ ❶ Locate horizontal tangents.
          ○ set 𝒅𝒚/𝒅𝒕 = 0
          ○ 3𝒕² - 3 = 0
          ○ 𝒕 = ±1
          ○ corresponding points:
               ■ 𝒕 = -1  →  (𝒙, 𝒚) = (1, 2)
               ■ 𝒕 = 1   →  (𝒙, 𝒚) = (1, -2)
     ◉ ❷ Locate the vertical tangent.
          ○ set 𝒅𝒙/𝒅𝒕 = 0
          ○ 2𝒕 = 0
          ○ 𝒕 = 0
          ○ corresponding point:
               ■ 𝒕 = 0  →  (𝒙, 𝒚) = (0, 0)
     ◉ ❸ Find the intercepts.
          ○ For the 𝒙-intercepts, set 𝒚 = 0:
               ■ 𝒕³ - 3𝒕 = 0
               ■ 𝒕(𝒕² - 3) = 0
               ■ 𝒕 = 0, ±√3
               ■ corresponding points:
                    ▣ 𝒕 = 0     →  (0, 0)
                    ▣ 𝒕 = √3    →  (3, 0)
                    ▣ 𝒕 = -√3   →  (3, 0)
          ○ For the 𝒚-intercept, set 𝒙 = 0:
               ■ 𝒕² = 0
               ■ 𝒕 = 0
               ■ corresponding point:
                    ▣ (0, 0)
     ◉ ❹ Determine where the curve starts and ends.
          ○ i̲f̲ 𝒕 → -∞,
               ■ t̲h̲e̲n̲ 𝒙 = 𝒕² → ∞ and 𝒚 = 𝒕³ - 3𝒕 → -∞
               ■ so the curve starts in the lower-right part of the plane
          ○ i̲f̲ 𝒕 → ∞,
               ■ t̲h̲e̲n̲ 𝒙 = 𝒕² → ∞ and 𝒚 = 𝒕³ - 3𝒕 → ∞
               ■ so the curve ends in the upper-right part of the plane
     ◉ ❺ Determine the orientation.
          ○ as 𝒕 increases, the curve starts in the lower-right branch
          ○ passes through (3, 0)
          ○ reaches the horizontal tangent at (1, 2)
          ○ moves to the vertical tangent at (0, 0)
          ○ reaches the horizontal tangent at (1, -2)
          ○ passes again through (3, 0)
          ○ and then continues to the upper-right branch
     ◉ Important:
          ○ two different parameter values, 𝒕 = ±√3, give the same point (3, 0)
          ○ so the curve passes through (3, 0) twice
     ◉ Final interpretation:
          ○ the curve has a loop
          ○ it has horizontal tangents at (1, 2) and (1, -2)
          ○ it has a vertical tangent at (0, 0)
          ○ and the direction is determined by the start at 𝒕 → -∞ and the end at 𝒕 → ∞





４  -  Ｓｅｃｏｎｄ　Ｄｅｒｉｖａｔｉｖｅ　ｆｏｒ　Ｐａｒａｍｅｔｒｉｃ　Ｃｕｒｖｅｓ

● [51:32]. Derivation of the second derivative formula.
     ◉ Start with the first derivative formula:
          ○ 𝒅𝒚/𝒅𝒙 = (𝒅𝒚/𝒅𝑻) / (𝒅𝒙/𝒅𝑻)
     ◉ Differentiate with respect to 𝒙:
          ○ 𝒅/𝒅𝒙 [𝒅𝒚/𝒅𝒙] = 𝒅/𝒅𝒙 [(𝒅𝒚/𝒅𝑻) / (𝒅𝒙/𝒅𝑻)]
     ◉ Therefore:
          ○ 𝒅²𝒚/𝒅𝒙² = 𝒅/𝒅𝒙 [𝒅𝒚/𝒅𝒙]
     ◉ Use the parametric derivative rule again:
          ○ 𝒅/𝒅𝒙 [𝔂] = (𝒅/𝒅𝑻 [𝔂]) / (𝒅𝒙/𝒅𝑻)
     ◉ Apply it to 𝔂 = 𝒅𝒚/𝒅𝒙:
          ○ 𝒅²𝒚/𝒅𝒙² = (𝒅/𝒅𝑻 [𝒅𝒚/𝒅𝒙]) / (𝒅𝒙/𝒅𝑻)
     ◉ Final result:
          ○ 𝒅²𝒚/𝒅𝒙² = (𝒅/𝒅𝑻 [𝒅𝒚/𝒅𝒙]) / (𝒅𝒙/𝒅𝑻)
     ◉ Important:
          ○ this is not simply (𝒅²𝒚/𝒅𝑻²) / (𝒅²𝒙/𝒅𝑻²)
     ◉ Meaning:
          ○ this formula is used to study concavity for a parametric curve

● [59:48]. 🧩 Example 3 — Find the concavity for 𝒙 = 𝑻² - 4, 𝒚 = 𝑻³ - 3𝑻.
     ◉ 
     ◉ ❶ Start with the first derivative.
          ○ 𝒅𝒚/𝒅𝒙 = (3𝑻² - 3) / 2𝑻
     ◉ ❷ Differentiate 𝒅𝒚/𝒅𝒙 with respect to 𝑻.
          ○ use the Quotient Rule
          ○ 𝒅/𝒅𝑻 [𝒅𝒚/𝒅𝒙] = 𝒅/𝒅𝑻 [(3𝑻² - 3) / 2𝑻]
          ○ = [2𝑻·6𝑻 - 2(3𝑻² - 3)] / 4𝑻²
          ○ = (12𝑻² - 6𝑻² + 6) / 4𝑻²
          ○ = (6𝑻² + 6) / 4𝑻²
          ○ = (3𝑻² + 3) / 2𝑻²
     ◉ ❸ Divide by 𝒅𝒙/𝒅𝑻.
          ○ 𝒅𝒙/𝒅𝑻 = 2𝑻
          ○ 𝒅²𝒚/𝒅𝒙² = [𝒅/𝒅𝑻 (𝒅𝒚/𝒅𝒙)] / (𝒅𝒙/𝒅𝑻)
          ○ = [(3𝑻² + 3) / 2𝑻²] / 2𝑻
     ◉ Final result:
          ○ 𝒅²𝒚/𝒅𝒙² = (3𝑻² + 3) / 4𝑻³




５．Ａｐｐｌｉｃａｔｉｏｎｓ

５．１ - Ａｒｃ　Ｌｅｎｇｔｈ

● [1:07:09]. Length of a curve (arc length).
     ◉ From Calc 1:
          ○ i̲f̲ 𝒚 = 𝒇(𝒙),
               ■ t̲h̲e̲n̲ the length of the curve from 𝒙 = 𝒂 to 𝒙 = 𝒃 is
                    ▣ 𝑳 = ∫[𝒂,𝒃] √(1 + [𝒇′(𝒙)]²) 𝒅𝒙
     ◉ Parametrically:
          ○ now we do the same idea using 𝒙 and 𝒚 as functions of 𝒕
     ◉ Conditions:
          ○ provided the part of the curve whose length we want to find
               ■ is smooth
               ■ and does not intersect itself
     ◉ Smooth means:
          ○ no gaps
          ○ no sharp points
     ◉ Important:
          ○ the curve should not double back on itself
          ○ otherwise we lose the nice local behavior needed for the formula
     ◉ Goal:
          ○ find the total distance traveled along the parametric curve from 𝒕 = 𝒂 to 𝒕 = 𝒃
     ◉ Formula:
          ○ 𝑳 = ∫[𝒂,𝒃] √((𝒅𝒙/𝒅𝒕)² + (𝒅𝒚/𝒅𝒕)²) 𝒅𝒕
     ◉ Important:
          ○ the bounds 𝒂 and 𝒃 are values of the parameter 𝒕
          ○ the integration is always with respect to 𝒕
     ◉ How to read the formula:
          ○ take 𝒅𝒙/𝒅𝒕 and square it
          ○ take 𝒅𝒚/𝒅𝒕 and square it
          ○ add them
          ○ take the square root
          ○ then integrate over the parameter interval
     ◉ Main idea:
          ○ this looks very similar to the Calc 1 arc-length formula
          ○ and it also resembles the distance formula
     ◉ Meaning:
          ○ integrate the magnitude of the velocity vector over the parameter interval

● [1:13:45]. 🧩 Example 4 — Arc length calculation: 𝒙 = 2𝑻², 𝒚 = 3𝑻³, on 0 ≤ 𝑻 ≤ 1.
     ◉ ❶ Find the derivatives.
          ○ 𝒅𝒙/𝒅𝑻 = 4𝑻
          ○ 𝒅𝒚/𝒅𝑻 = 9𝑻²
     ◉ ❷ Set up the arc length integral.
          ○ 𝑳 = ∫[0,1] √((4𝑻)² + (9𝑻²)²) 𝒅𝑻
     ◉ ❸ Simplify the expression.
          ○ 𝑳 = ∫[0,1] √(16𝑻² + 81𝑻⁴) 𝒅𝑻
          ○ 𝑳 = ∫[0,1] √(𝑻²(16 + 81𝑻²)) 𝒅𝑻
          ○ 𝑳 = ∫[0,1] 𝑻√(16 + 81𝑻²) 𝒅𝑻
     ◉ ❹ Use 𝒖-substitution.
          ○ let 𝒖 = 16 + 81𝑻²
          ○ 𝒅𝒖 = 162𝑻 𝒅𝑻
          ○ (1/162)𝒅𝒖 = 𝑻 𝒅𝑻
          ○ change the bounds:
               ■ 𝑻 = 0  →  𝒖 = 16
               ■ 𝑻 = 1  →  𝒖 = 97
     ◉ ❺ Rewrite and evaluate the integral.
          ○ 𝑳 = (1/162) ∫[16,97] 𝒖¹ᐟ² 𝒅𝒖
          ○ 𝑳 = (1/162) · [𝒖³ᐟ² / (3/2)] [16,97]
          ○ 𝑳 = [𝒖³ᐟ² / 243] [16,97]
          ○ 𝑳 = (97³ᐟ² - 16³ᐟ²) / 243
     ◉ Final result:
          ○ 𝑳 = (97³ᐟ² - 16³ᐟ²) / 243
     ◉ Final interpretation:
          ○ the total distance traveled is approximately 3.67 units



５．２  -  Ｓｕｒｆａｃｅ　Ａｒｅａ　ｏｆ　Ｒｅｖｏｌｕｔｉｏｎ

● [1:26:22]. Surface area of revolution.
     ◉ From Calc 1:
          ○ around the 𝒙-axis:
               ■ 𝓢 = ∫[𝒂,𝒃] 2π 𝒇(𝒙) √(1 + [𝒇′(𝒙)]²) 𝒅𝒙
          ○ around the 𝒚-axis:
               ■ 𝓢 = ∫[𝒂,𝒃] 2π 𝒈(𝒚) √(1 + [𝒈′(𝒚)]²) 𝒅𝒚
     ◉ Parametrically:
          ○ use the same arc-length factor as before
          ○ only the radius of revolution changes depending on the axis
     ◉ Main idea:
          ○ circumference of the circular cross section × arc length element
     ◉ Around the 𝒙-axis:
          ○ the radius is 𝒚
          ○ 𝓢 = ∫[𝒂,𝒃] 2π 𝒚 √((𝒅𝒙/𝒅𝒕)² + (𝒅𝒚/𝒅𝒕)²) 𝒅𝒕
     ◉ Around the 𝒚-axis:
          ○ the radius is 𝒙
          ○ 𝓢 = ∫[𝒂,𝒃] 2π 𝒙 √((𝒅𝒙/𝒅𝒕)² + (𝒅𝒚/𝒅𝒕)²) 𝒅𝒕
     ◉ Important:
          ○ the square-root factor is the same in both formulas
          ○ because the length element of the curve does not change
          ○ only the radius changes:
               ■ around the 𝒙-axis → use 𝒚
               ■ around the 𝒚-axis → use 𝒙




Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Parametric equations, polar coordinates, and vector-valued functions
     ◉ [Khan Academy🌐](https://www.khanacademy.org/math/ap-calculus-bc/bc-advanced-functions-new)

● Parametric Equations and Curves
     ◉ [Paul's Online 🌐](https://tutorial.math.lamar.edu/Classes/CalcII/ParametricEqn.aspx)