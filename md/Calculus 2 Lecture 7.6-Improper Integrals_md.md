-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ７．６－Ｉｍｐｒｏｐｅｒ Ｉｎｔｅｇｒａｌｓ**---------------------------------







Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:00](https://www.youtube.com/watch?v=g-M8FHslgdk&t=0). Introduction to improper integrals and conditions for existence. [📷image](../img/Calculus 2 Lecture 7.6/[0-00]-01.png)
     ◉ [0:39](https://www.youtube.com/watch?v=g-M8FHslgdk&t=39). Fundamental requirement:
          ○ Usual conditions for a definite integral 
               ■  ∫ [𝒂,𝒃] 𝒇(𝒙) 𝒅𝒙, 𝒇(𝒙) must be bounded and finite on [𝒂,𝒃].
     ◉ [1:17](https://www.youtube.com/watch?v=g-M8FHslgdk&t=77). Visual definition:
          ○ Improper integrals arise when the region extends infinitely.
          ○ Or when the integrand is not bounded on the interval.




          

Ｆｕｎｄａｍｅｎｔａｌ　Ｃａｓｅｓ

● [2:14](https://www.youtube.com/watch?v=g-M8FHslgdk&t=134). Classification of the two fundamental cases. [📷image](../img/Calculus 2 Lecture 7.6/[2-14]-01.png)
     ◉ Informal idea:
          ○ An improper integral appears when the usual conditions for a definite integral fail.
          ○ That typically happens because:
               ■ the interval is infinite,
               ■ or the function is unbounded on the interval.
     ◉ **Case 1**:
          ○ The interval of integration is infinite.
          ○ It starts at 𝒂 but extends without bound.
     ◉ **Case 2**:
          ○ The interval [𝒂,𝒃] is finite,
          ○ but the function 𝒇(𝒙) is unbounded (has an infinite discontinuity) at an endpoint or at some point inside the interval.
    




          

Ｃａｓｅ　1　—　Ｉｎｆｉｎｉｔｅ　Ｉｎｔｅｒｖａｌｓ

● [8:12](https://www.youtube.com/watch?v=g-M8FHslgdk&t=492). 🧩 Example 1 — Evaluate the integral ∫[1, ∞] 1/𝒙² 𝒅𝒙. [📷image](../img/Calculus 2 Lecture 7.6/[8-12]-01.png)
     ◉ 1. Identify why the integral is improper.
          ○ The function 1/𝒙² is defined for every 𝒙 ≥ 1.
          ○ There is no infinite discontinuity on [1, ∞).
          ○ The improper behavior comes from the interval extending to infinity.
          ○ So this is **Case 1**: an infinite interval.
          ○ But if we changed the interval to [−1, ∞], then at 𝒙 = 0 the function would be undefined.
               ■ It would have an infinite discontinuity there.
               ■ In that situation, a vertical asymptote appears.
               ■ So **Case 2** would also be present.
     ◉ 2. Replace the infinite upper limit with a variable.
          ○ Consider ∫[1, 𝒃] 1/𝒙² 𝒅𝒙, where 𝒃 > 1.
          ○ We do this because we cannot substitute ∞ directly into the integral.
     ◉ 3. Visual interpretation.
          ○ This represents the area under 1/𝒙² from 𝒙 = 1 to 𝒙 = 𝒃.
          ○ Then we study what happens as 𝒃 grows without bound.
     ◉ 4. Evaluate the finite integral first.
          ○ ∫[1, 𝒃] 1/𝒙² 𝒅𝒙
          ○ = ∫[1, 𝒃] 𝒙⁻² 𝒅𝒙
          ○ = [𝒙⁻¹ / (−1)]_[1,𝒃]
          ○ = [−1/𝒙]_[1,𝒃]
          ○ = −1/𝒃 − (−1/1)
          ○ = −1/𝒃 + 1
     ◉ [15:53](https://www.youtube.com/watch?v=g-M8FHslgdk&t=953). Use a limit to recover the improper integral.
          ○ The way we handle “plugging in infinity” is with a limit.
          ○ lim_(𝒃 → ∞) ∫[1, 𝒃] 1/𝒙² 𝒅𝒙
          ○ = lim_(𝒃 → ∞) (−1/𝒃 + 1)
          ○ = 0 + 1
          ○ = 1
     ◉ Final evaluation.
          ○ The integral converges.
          ○ ∫[1, ∞] 1/𝒙² 𝒅𝒙 = 1



          

Ｃｏｎｖｅｒｇｅｎｃｅ　Ａｎｄ　Ｎｏｔａｔｉｏｎ

● [18:34](https://www.youtube.com/watch?v=g-M8FHslgdk&t=1114). General notation and definitions of convergence. [📷image](../img/Calculus 2 Lecture 7.6/[18-34]-01.png)
     ◉ Formal notation:
          ○ ∫[𝒂, ∞] 𝒇(𝒙) ⋅ 𝒅𝒙 = lim_(𝒃 → ∞) ∫[𝒂, 𝒃] 𝒇(𝒙) ⋅ 𝒅𝒙
          ○ ∫[−∞, 𝒃] 𝒇(𝒙) ⋅ 𝒅𝒙 = lim_(𝒂 → −∞) ∫[𝒂, 𝒃] 𝒇(𝒙) ⋅ 𝒅𝒙
     ◉ [21:55](https://www.youtube.com/watch?v=g-M8FHslgdk&t=1315). Definitions:
          ○ **Convergence**:
               ■ the limit exists and is finite
          ○ **Divergence**:
               ■ the limit does not exist, or is infinite



               

Ｅｘａｍｐｌｅｓ　Ｏｎ　Ｉｎｆｉｎｉｔｅ　Ｉｎｔｅｒｖａｌｓ

● [25:35](https://www.youtube.com/watch?v=g-M8FHslgdk&t=1535). 🧩 Example 2 — Evaluate the integral ∫[1, ∞] 3/𝒙 ⋅ 𝒅𝒙. [📷image](../img/Calculus 2 Lecture 7.6/[25-35]-01.png)
     ◉ Identify why the integral is improper.
          ○ The function 3/𝒙 is defined for every 𝒙 ≥ 1.
               ■ There is no infinite discontinuity on [1, ∞).
          ○ The improper behavior comes from the interval extending to infinity.
          ○ So this is **Case 1**: an infinite interval.
     ◉ Replace the infinite upper limit with a variable.
          ○ Consider ∫[1, 𝒃] 3/𝒙 ⋅ 𝒅𝒙, where 𝒃 > 1.
     ◉ Rewrite the improper integral as a limit.
          ○ lim_(𝒃 → ∞) ∫[1, 𝒃] 3/𝒙 ⋅ 𝒅𝒙
     ◉ Evaluate the antiderivative first.
          ○ lim_(𝒃 → ∞) [3 ln|𝒙|] | [1,𝒃]
     ◉ Simplify the expression.
          ○ lim_(𝒃 → ∞) 3[ln(𝒃) − ln(1)]
          ○ = lim_(𝒃 → ∞) 3[ln(𝒃) − 0]
     ◉ Analyze the limit.
          ○ As 𝒃 → ∞, ln(𝒃) → ∞.
          ○ Therefore the expression grows without bound.
     ◉ Final conclusion.
          ○ The integral is **divergent**.

● [31:10](https://www.youtube.com/watch?v=g-M8FHslgdk&t=1870). 🧩 Example 3 — **Generalization for power integrals (p-integrals)**: ∫[1, ∞] 1/𝒙ⁿ ⋅ 𝒅𝒙. [📷image-1](../img/Calculus 2 Lecture 7.6/[31-10]-01.png)  [📷image-2](../img/Calculus 2 Lecture 7.6/[31-10]-02.png)
     ◉ Goal:
          ○ Study the general behavior of improper integrals of the form ∫[1, ∞] 1/𝒙ⁿ ⋅ 𝒅𝒙.
     ◉ Rewrite the improper integral as a limit.
          ○ ∫[1, ∞] 1/𝒙ⁿ ⋅ 𝒅𝒙 = lim_(𝒃 → ∞) ∫[1, 𝒃] 1/𝒙ⁿ ⋅ 𝒅𝒙
          ○ = lim_(𝒃 → ∞) ∫[1, 𝒃] 𝒙⁻ⁿ ⋅ 𝒅𝒙
     ◉ Important precondition.
          ○ The formal antiderivative used below is valid only for 𝒏 ≠ 1.
          ○ So the case 𝒏 = 1 must be treated separately.
          ○ If 𝒏 = 1, then
               ■ ∫ 1/𝒙 𝒅𝒙 = ln|𝒙|
     ◉ Integrate formally for 𝒏 ≠ 1.
          ○ lim_(𝒃 → ∞) [𝒙⁻ⁿ⁺¹ / (−𝒏 + 1)] | [1, 𝒃]
          ○ = lim_(𝒃 → ∞) [𝒃⁻ⁿ⁺¹ / (1 − 𝒏) − 1 / (1 − 𝒏)]
          ○ = lim_(𝒃 → ∞) (𝒃⁻ⁿ⁺¹ − 1) / (1 − 𝒏)
     ◉ Rewrite the exponent to study the limit.
          ○ −𝒏 + 1 = −(𝒏 − 1)
          ○ so 𝒃⁻ⁿ⁺¹ = 1 / 𝒃ⁿ⁻¹
          ○ Hence:
               ■ ∫[1, ∞] 1/𝒙ⁿ ⋅ 𝒅𝒙 = 1 / (1 − 𝒏) ⋅ lim_(𝒃 → ∞) [1 / 𝒃ⁿ⁻¹ − 1]
     ◉ Analyze the limit.
          ○ If 𝒏 > 1,
               ■ then 𝒏 − 1 > 0
               ■ so 1 / 𝒃ⁿ⁻¹ → 0
               ■ and the integral converges.
          ○ If 𝒏 = 1,
               ■ the integral becomes ∫[1, ∞] 1/𝒙 ⋅ 𝒅𝒙
               ■ which diverges, as shown in the previous example.
          ○ If 𝒏 < 1,
               ■ then 𝒏 − 1 < 0
               ■ so 𝒃⁻ⁿ⁺¹ grows without bound
               ■ and the integral diverges.
     ◉ **Final p-integral criterion.**
          ○ ∫[1, ∞] 1/𝒙ⁿ ⋅ 𝒅𝒙 **converges if 𝒏 > 1**
          ○ ∫[1, ∞] 1/𝒙ⁿ ⋅ 𝒅𝒙 **diverges if 𝒏 ≤ 1**      


● [43:46](https://www.youtube.com/watch?v=g-M8FHslgdk&t=2626). 🧩 Example 4 — Evaluate the improper integral ∫[1, ∞] e⁻²𝒙 ⋅ 𝒅𝒙. [📷image](../img/Calculus 2 Lecture 7.6/[43-46]-01.png)
     ◉ Rewrite the improper integral as a limit.
          ○ ∫[1, ∞] e⁻²𝒙 ⋅ 𝒅𝒙 = lim_(𝒃 → ∞) ∫[1, 𝒃] e⁻²𝒙 𝒅𝒙
     ◉ [46:39](https://www.youtube.com/watch?v=g-M8FHslgdk&t=2799). Use substitution.
          ○ Let:
               ■ 𝒖 = −2𝒙
               ■ 𝒅𝒖 = −2 𝒅𝒙
               ■ 𝒅𝒖 / (−2) = 𝒅𝒙
     ◉ Rewrite the integral using 𝒖.
          ○ lim_(𝒃 → ∞) ∫[1, 𝒃] e⁻²𝒙 𝒅𝒙
          ○ = lim_(𝒃 → ∞) ∫ eᵘ ⋅ 𝒅𝒖 / (−2)
          ○ = −(1/2) lim_(𝒃 → ∞) [eᵘ] | [1, 𝒃]
          ○ = −(1/2) lim_(𝒃 → ∞) [e⁻²𝒙] | [1, 𝒃]
     ◉ Evaluate the limit.
          ○ = −(1/2) lim_(𝒃 → ∞) [e⁻²𝒃 − e⁻²]
          ○ = −(1/2) lim_(𝒃 → ∞) [1/e²ᵇ − 1/e²]
          ○ Since 1/e²ᵇ → 0 as 𝒃 → ∞,
               ■ the expression becomes −(1/2)(0 − 1/e²)
     ◉ Final result.
          ○ ∫[1, ∞] e⁻²𝒙 ⋅ 𝒅𝒙 = 1 / (2e²)
     ◉ Conclusion.
          ○ The improper integral converges.

● [54:14](https://www.youtube.com/watch?v=g-M8FHslgdk&t=3254). 🧩 Example 5 — Evaluate the improper integral ∫[0, ∞] sin(𝒙) ⋅ 𝒅𝒙. [📷image](../img/Calculus 2 Lecture 7.6/[54-14]-01.png)
     ◉ Rewrite the improper integral as a limit.
          ○ ∫[0, ∞] sin(𝒙) 𝒅𝒙 = lim_(𝒃 → ∞) ∫[0, 𝒃] sin(𝒙) 𝒅𝒙
     ◉ Evaluate the antiderivative.
          ○ = lim_(𝒃 → ∞) [−cos(𝒙)] | [0, 𝒃]
     ◉ Substitute the bounds.
          ○ = lim_(𝒃 → ∞) [−cos(𝒃) − (−cos(0))]
          ○ = lim_(𝒃 → ∞) [−cos(𝒃) + cos(0)]
     ◉ Analyze the limit.
          ○ cos(0) = 1
          ○ but cos(𝒃) does not approach a single value as 𝒃 → ∞
          ○ it keeps oscillating between −1 and 1
     ◉ Conclusion.
          ○ lim_(𝒃 → ∞) [−cos(𝒃) + 1] does not exist
          ○ so ∫[0, ∞] sin(𝒙) ⋅ 𝒅𝒙 diverges

● [1:00:30](https://www.youtube.com/watch?v=g-M8FHslgdk&t=3630). 🧩 Example 6 — Evaluate the improper integral ∫[-∞, 0] 𝒙eˣ ⋅ 𝒅𝒙. [📷image](../img/Calculus 2 Lecture 7.6/[1-00-30]-01.png)
     ◉ Identify why the integral is improper.
          ○ This is **Case 1**: an infinite interval.
          ○ The interval extends to −∞.
          ○ There is no infinite discontinuity in the integrand 𝒙eˣ on (−∞, 0].
     ◉ Rewrite the improper integral as a limit.
          ○ ∫[-∞, 0] 𝒙eˣ ⋅ 𝒅𝒙 = lim_(𝒂 → −∞) ∫[𝒂, 0] 𝒙eˣ ⋅ 𝒅𝒙
     ◉ Use integration by parts.
          ○ Choose:
               ■ 𝒖 = 𝒙
               ■ 𝒅𝓥 = eˣ 𝒅𝒙
          ○ Then:
               ■ 𝒅𝒖 = 𝒅𝒙
               ■ 𝓥 = eˣ
     ◉ Apply the integration by parts formula.
          ○ lim_(𝒂 → −∞) [𝒙eˣ − ∫ eˣ 𝒅𝒙] | [𝒂, 0]
          ○ = lim_(𝒂 → −∞) [𝒙eˣ − eˣ] | [𝒂, 0]
          ○ = lim_(𝒂 → −∞) [eˣ(𝒙 − 1)] | [𝒂, 0]
     ◉ Evaluate the bounds.
          ○ = lim_(𝒂 → −∞) [e⁰(0 − 1) − eᵃ(𝒂 − 1)]
          ○ = lim_(𝒂 → −∞) [−1 − 𝒂eᵃ + eᵃ]
     ◉ [1:11:14](https://www.youtube.com/watch?v=g-M8FHslgdk&t=4274). Key issue:
          ○ Resolve the indeterminate behavior in the term 𝒂eᵃ.
          ○ Rewrite:
               ■ 𝒂eᵃ = 𝒂 / e⁻ᵃ
          ○ Then apply L'Hôpital's Rule to the limit:
               ■ lim_(𝒂 → −∞) 𝒂eᵃ
               ■ = lim_(𝒂 → −∞) 𝒂 / e⁻ᵃ
               ■ = lim_(𝒂 → −∞) 1 / (−e⁻ᵃ)
               ■ = lim_(𝒂 → −∞) (−1 / e⁻ᵃ)
               ■ Since 𝒂 → −∞, we have −𝒂 → ∞, so e⁻ᵃ → ∞
               ■ Therefore, −1 / e⁻ᵃ → 0
               ■ Hence:
                    ▣ lim_(𝒂 → −∞) 𝒂eᵃ = 0
     ◉ Final result.
          ○ lim_(𝒂 → −∞) [−1 − 𝒂eᵃ + eᵃ] = −1 − 0 + 0
          ○ = −1
     ◉ Conclusion.
          ○ The integral converges.
          ○ ∫[-∞, 0] 𝒙eˣ ⋅ 𝒅𝒙 = −1

● [1:17:15](https://www.youtube.com/watch?v=g-M8FHslgdk&t=4635). 🧩 Example 7 — **Integrals over the entire real line**: ∫[-∞, ∞] eˣ/(1 + e²ˣ) ⋅ 𝒅𝒙 [📷image-1](../img/Calculus 2 Lecture 7.6/[1-17-15]-01.png) [📷image-2](../img/Calculus 2 Lecture 7.6/[1-17-15]-02.png)
     ◉ 1. Identify why the integral is improper.
          ○ The function eˣ/(1 + e²ˣ) is defined everywhere.
          ○ There is no infinite discontinuity on [-∞, ∞].
          ○ The improper behavior comes from the interval extending to infinity.
          ○ So this is **Case 1**: an infinite interval.
     ◉ General form:
          ○ ∫[-∞, ∞] 𝒇(𝒙) ⋅ 𝒅𝒙
     ◉ [1:20:03](https://www.youtube.com/watch?v=g-M8FHslgdk&t=4803). Additivity property:
          ○ Split the integral at 𝒙 = 0.
          ○ ∫[-∞, ∞] eˣ/(1 + e²ˣ) ⋅ 𝒅𝒙
          ○ = ∫[-∞, 0] eˣ/(1 + e²ˣ) ⋅ 𝒅𝒙 + ∫[0, ∞] eˣ/(1 + e²ˣ) ⋅ 𝒅𝒙
     ◉ Rewrite both pieces as limits.
          ○ lim_(𝒂 → −∞) ∫[𝒂, 0] eˣ/(1 + e²ˣ) ⋅ 𝒅𝒙
          ○ + lim_(𝒃 → ∞) ∫[0, 𝒃] eˣ/(1 + e²ˣ) ⋅ 𝒅𝒙
     ◉ Substitution for the integrand.
          ○ Let 𝒖 = eˣ
          ○ Then 𝒅𝒖 = eˣ 𝒅𝒙
          ○ So:
               ■ ∫ eˣ/(1 + e²ˣ) ⋅ 𝒅𝒙 = ∫ 1/(1 + 𝒖²) ⋅ 𝒅𝒖
               ■ = tan⁻¹(𝒖)
               ■ = tan⁻¹(eˣ)
     ◉ Apply the antiderivative to both improper pieces.
          ○ lim_(𝒂 → −∞) [tan⁻¹(eˣ)] | [𝒂,0]
          ○ + lim_(𝒃 → ∞) [tan⁻¹(eˣ)] | [0,𝒃]
     ◉ Evaluate each limit.
          ○ First piece:
               ■ lim_(𝒂 → −∞) [tan⁻¹(e⁰) − tan⁻¹(eᵃ)]
               ■ = tan⁻¹(1) − tan⁻¹(0)
               ■ = π/4 − 0
          ○ Second piece:
               ■ lim_(𝒃 → ∞) [tan⁻¹(eᵇ) − tan⁻¹(e⁰)]
               ■ = tan⁻¹(∞) − tan⁻¹(1)
               ■ = π/2 − π/4
     ◉ Final result:
          ○ ∫[-∞, ∞] eˣ/(1 + e²ˣ) ⋅ 𝒅𝒙 = π/4 + (π/2 − π/4)
          ○ = π/2
     ◉ Conclusion:
          ○ The improper integral **converges**
          ○ and its value is π/2.  





               

Ｃａｓｅ　2　—　Ｉｎｆｉｎｉｔｅ　Ｄｉｓｃｏｎｔｉｎｕｉｔｉｅｓ

● [1:33:31](https://www.youtube.com/watch?v=g-M8FHslgdk&t=5611). 🧩 Example 6 — Analysis of Case 2: Infinite discontinuities: ∫ [0, 9] 𝒙⁻¹ᐟ² ⋅ 𝒅𝒙. [📷image](../img/Calculus 2 Lecture 7.6/[1-33-31]-01.png)
     ◉ 1. Identify why the integral is improper.
          ○ The function 𝒙⁻¹ᐟ² = 1/√𝒙 is undefined at 𝒙 = 0.
          ○ There is a vertical asymptote at 𝒙 = 0.
          ○ So the improper behavior comes from the function itself, not from an infinite interval.
     ◉ 2. Replace the problematic endpoint with an intermediate value.
          ○ Because we cannot plug 𝒙 = 0 directly into the integral, we replace the lower limit 0 with 𝒄, where 0 < 𝒄 < 9.
          ○ This gives:
               ■ ∫ [𝒄, 9] 𝒙⁻¹ᐟ² ⋅ 𝒅𝒙
          ○ This parallels Case 1:
               ■ in Case 1 we replaced ∞ with a variable 𝒃,
               ■ here we replace the problematic endpoint 0 with a variable 𝒄.
     ◉ 3. Use a one-sided limit.
          ○ Since the discontinuity is at the left endpoint, we approach from the right:
               ■ 𝒄 → 0⁺
          ○ So the improper integral is rewritten as:
               ■ lim_(𝒄 → 0⁺) ∫ [𝒄, 9] 𝒙⁻¹ᐟ² ⋅ 𝒅𝒙
     ◉ 4. Evaluate the integral first.
          ○ ∫ [𝒄, 9] 𝒙⁻¹ᐟ² ⋅ 𝒅𝒙 = [2𝒙¹ᐟ²] | [𝒄, 9]
          ○ = 2√9 − 2√𝒄
     ◉ 5. Take the limit.
          ○ lim_(𝒄 → 0⁺) [2√9 − 2√𝒄]
          ○ = 6 − 0
          ○ = 6
     ◉ Final result.
          ○ lim_(𝒄 → 0⁺) ∫ [𝒄, 9] 𝒙⁻¹ᐟ² ⋅ 𝒅𝒙 = 6
          ○ Therefore, the improper integral converges.
     
● [1:43:08](https://www.youtube.com/watch?v=g-M8FHslgdk&t=6188). **Types Of Infinite Discontinuities.** [📷image](../img/Calculus 2 Lecture 7.6/[1-43-08]-01.png)
     ◉ The discontinuity can occur at the upper endpoint.
          ○ If 𝒇(𝒙) blows up at 𝒙 = 𝒃, then the improper integral
               ■ ∫ [𝒂, 𝒃] 𝒇(𝒙) 𝒅𝒙
          ○ is defined by approaching 𝒃 from the left:
               ■ lim_(𝒄 → 𝒃⁻) ∫ [𝒂, 𝒄] 𝒇(𝒙) 𝒅𝒙
     ◉ [1:46:35](https://www.youtube.com/watch?v=g-M8FHslgdk&t=6395). The discontinuity can occur at the lower endpoint.
          ○ If 𝒇(𝒙) blows up at 𝒙 = 𝒂, then the improper integral
               ■ ∫ [𝒂, 𝒃] 𝒇(𝒙) 𝒅𝒙
          ○ is defined by approaching 𝒂 from the right:
               ■ lim_(𝒄 → 𝒂⁺) ∫ [𝒄, 𝒃] 𝒇(𝒙) 𝒅𝒙
     ◉ [1:50:01](https://www.youtube.com/watch?v=g-M8FHslgdk&t=6601). The discontinuity can occur at an interior point.
          ○ If 𝒇(𝒙) blows up at some point 𝒙 = 𝒄 with 𝒂 < 𝒄 < 𝒃,
          ○ then the integral must be split into two improper integrals:
               ■ ∫ [𝒂, 𝒃] 𝒇(𝒙) 𝒅𝒙 = ∫ [𝒂, 𝒄] 𝒇(𝒙) 𝒅𝒙 + ∫ [𝒄, 𝒃] 𝒇(𝒙) 𝒅𝒙
          ○ and each part is defined separately:
               ■ lim_(𝒕 → 𝒄⁻) ∫ [𝒂, 𝒕] 𝒇(𝒙) 𝒅𝒙
               ■ + lim_(𝒔 → 𝒄⁺) ∫ [𝒔, 𝒃] 𝒇(𝒙) 𝒅𝒙
          ○ Both one-sided improper integrals must converge for the original integral to converge.
    ◉ NOTE:
          ○ A removable discontinuity does not create area by itself, because changing or removing the value of a function at isolated points does not change the value of the integral.
          ○ Having many removable discontinuities does not necessarily prevent the area from being computed, because isolated point changes do not affect the value of the integral.





          

Ｅｘａｍｐｌｅｓ　Ｏｎ　Ｉｎｆｉｎｉｔｅ　Ｄｉｓｃｏｎｔｉｎｕｉｔｉｅｓ

● [1:55:11](https://www.youtube.com/watch?v=g-M8FHslgdk&t=6911). 🧩 Example 7 — Discontinuity at the upper limit: ∫ [1, 4] 1/(4 − 𝒙)²ᐟ³ ⋅ 𝒅𝒙. [📷image](../img/Calculus 2 Lecture 7.6/[1-55-11]-01.png)
     ◉ 1. Identify why the integral is improper.
          ○ The interval [1, 4] is finite.
          ○ The problem is not an infinite interval.
          ○ The integrand 1/(4 − 𝒙)²ᐟ³ blows up at 𝒙 = 4.
          ○ So the improper behavior comes from an infinite discontinuity at the **upper endpoint**.
     ◉ 2. Replace the problematic endpoint with a variable.
          ○ ∫ [1, 4] 1/(4 − 𝒙)²ᐟ³ ⋅ 𝒅𝒙 = lim_(𝒄 → 4⁻) ∫ [1, 𝒄] (4 − 𝒙)⁻²ᐟ³ ⋅ 𝒅𝒙
     ◉ 3. Use substitution.
          ○ Let 𝒖 = 4 − 𝒙
          ○ Then 𝒅𝒖 = −𝒅𝒙
          ○ So −𝒅𝒖 = 𝒅𝒙
     ◉ 4. Integrate.
          ○ lim_(𝒄 → 4⁻) ∫ [1, 𝒄] (4 − 𝒙)⁻²ᐟ³ ⋅ 𝒅𝒙
          ○ = lim_(𝒄 → 4⁻) −∫ 𝒖⁻²ᐟ³ ⋅ 𝒅𝒖
          ○ = lim_(𝒄 → 4⁻) −[3𝒖¹ᐟ³] | [1, 𝒄]
          ○ = −3 lim_(𝒄 → 4⁻) [(4 − 𝒙)¹ᐟ³] | [1, 𝒄]
     ◉ 5. Evaluate the limit.
          ○ −3 lim_(𝒄 → 4⁻) [(4 − 𝒄)¹ᐟ³ − (4 − 1)¹ᐟ³]
          ○ = −3 [0 − 3¹ᐟ³]
          ○ = 3 · 3¹ᐟ³
     ◉ Final result.
          ○ The integral **converges**.
          ○ ∫ [1, 4] 1/(4 − 𝒙)²ᐟ³ ⋅ 𝒅𝒙 = 3 · 3¹ᐟ³

● [2:03:43](https://www.youtube.com/watch?v=g-M8FHslgdk&t=7423). 🧩 Example 8 — Lower endpoint. Evaluate the logarithmic improper integral: ∫ [0, 1] ln(𝒙) ⋅ 𝒅𝒙. [📷image](../img/Calculus 2 Lecture 7.6/[2-03-43]-01.png)
     ◉ 1. Identify why the integral is improper.
          ○ The interval [0, 1] is finite.
          ○ The problem is not an infinite interval.
          ○ The integrand ln(𝒙) is not defined at 𝒙 = 0.
          ○ In fact, ln(𝒙) → −∞ as 𝒙 → 0⁺.
          ○ So this is **Case 2**: an infinite discontinuity at the lower endpoint.
     ◉ 2. First find the antiderivative of ln(𝒙).
          ○ Use integration by parts:
               ■ 𝒖 = ln(𝒙)
               ■ 𝒅𝓥 = 𝒅𝒙
               ■ 𝒅𝒖 = 1/𝒙 ⋅ 𝒅𝒙
               ■ 𝓥 = 𝒙
          ○ Then:
               ■ ∫ ln(𝒙) 𝒅𝒙 = 𝒙 ln(𝒙) − ∫ 𝒙 · (1/𝒙) 𝒅𝒙
               ■ = 𝒙 ln(𝒙) − 𝒙 + 𝑪
     ◉ 3. Rewrite the improper integral as a limit.
          ○ ∫ [0, 1] ln(𝒙) ⋅ 𝒅𝒙 = lim_(𝒄 → 0⁺) ∫ [𝒄, 1] ln(𝒙) ⋅ 𝒅𝒙
     ◉ 4. Evaluate with the antiderivative.
          ○ lim_(𝒄 → 0⁺) [𝒙 ln(𝒙) − 𝒙] | [𝒄, 1]
          ○ = lim_(𝒄 → 0⁺) [(1 ln(1) − 1) − (𝒄 ln(𝒄) − 𝒄)]
          ○ = lim_(𝒄 → 0⁺) [−1 − 𝒄 ln(𝒄) + 𝒄]
     ◉ 5. Handle the difficult limit.
          ○ Since 𝒄 → 0⁺, we have 𝒄 → 0.
          ○ So it remains to evaluate:
               ■ lim_(𝒄 → 0⁺) 𝒄 ln(𝒄)
          ○ Rewrite it as:
               ■ lim_(𝒄 → 0⁺) ln(𝒄) / (1/𝒄)
          ○ Apply L'Hôpital's Rule:
               ■ lim_(𝒄 → 0⁺) [(1/𝒄) / (−1/𝒄²)]
               ■ = lim_(𝒄 → 0⁺) (−𝒄)
               ■ = 0
          ○ Hence:
               ■ lim_(𝒄 → 0⁺) 𝒄 ln(𝒄) = 0
               ■ and lim_(𝒄 → 0⁺) 𝒄 = 0
     ◉ 6. Final result.
          ○ ∫ [0, 1] ln(𝒙) ⋅ 𝒅𝒙 = −1
          ○ So the integral **converges**.
          
● [2:14:40](https://www.youtube.com/watch?v=g-M8FHslgdk&t=8080). 🧩 Example 9 — **Discontinuity at an interior point of the interval**: ∫[-1, 1] 1/𝒙² ⋅ 𝒅𝒙. [📷image](../img/Calculus 2 Lecture 7.6/[2-14-40]-01.png)
     ◉ 1. Identify why the integral is improper.
          ○ The interval [-1, 1] is finite.
          ○ The integrand 1/𝒙² is not defined at 𝒙 = 0.
          ○ There is a vertical asymptote at the interior point 𝒙 = 0.
          ○ So this is **Case 2**: an infinite discontinuity at an interior point.
     ◉ 2. Split the integral at the discontinuity.
          ○ ∫[-1, 1] 1/𝒙² ⋅ 𝒅𝒙
          ○ = ∫[-1, 0] 1/𝒙² ⋅ 𝒅𝒙 + ∫[0, 1] 1/𝒙² ⋅ 𝒅𝒙
          ○ Key idea:
               ■ When the discontinuity is at an interior point,
                    ▣ the improper integral must be separated into **two improper integrals**
                    ▣ one on each side of the discontinuity.
               ■ Convergence requirement.
                    ▣ The original integral converges **only if both pieces converge**.
                    ▣ If either side diverges,
                         ▢ then the whole integral diverges.
    ◉ 3. Evaluate the left-hand side.
         ○ lim_(𝒄 → 0⁻) ∫[-1, 𝒄] 𝒙⁻² ⋅ 𝒅𝒙
         ○ = lim_(𝒄 → 0⁻) [−1/𝒙] | [-1, 𝒄]
         ○ = lim_(𝒄 → 0⁻) (−1/𝒄 − 1)
         ○ Since 𝒄 → 0⁻, we have −1/𝒄 → +∞
         ○ Therefore the left-hand integral **diverges**.
   ◉ 5. Evaluate the right-hand side.
         ○ lim_(𝒄 → 0⁺) ∫[𝒄, 1] 𝒙⁻² ⋅ 𝒅𝒙
         ○ = lim_(𝒄 → 0⁺) [−1/𝒙] | [𝒄, 1]
         ○ = lim_(𝒄 → 0⁺) (−1 + 1/𝒄)
         ○ Since 𝒄 → 0⁺, we have 1/𝒄 → +∞
         ○ Therefore the right-hand integral **diverges**.
   ◉ 6. Final conclusion.
         ○ Both one-sided improper integrals diverge.
         ○ So the original integral ∫[-1, 1] 1/𝒙² ⋅ 𝒅𝒙 **diverges**.

● [2:16:32](https://www.youtube.com/watch?v=g-M8FHslgdk&t=8192). 🧩 Example 10 — Combined-case: ∫[0, ∞] e⁻√𝒙 / √𝒙 ⋅ 𝒅𝒙. [📷image-1](../img/Calculus 2 Lecture 7.6/[2-16-32]-01.png) [📷image-2](../img/Calculus 2 Lecture 7.6/[2-16-32]-02.png)
     ◉ 1. Identify why the integral is improper.
          ○ The interval extends to ∞.
          ○ The integrand e⁻√𝒙 / √𝒙 is also unbounded at 𝒙 = 0 because of the factor 1/√𝒙.
          ○ So this example combines:
               ■ **Case 1**: an infinite interval
               ■ **Case 2**: an infinite discontinuity at the lower endpoint
     ◉ 2. Strategy.
          ○ Split the integral at 𝒙 = 1 so each issue is handled separately.
          ○ ∫[0, ∞] e⁻√𝒙 / √𝒙 ⋅ 𝒅𝒙
          ○ = ∫[0, 1] e⁻√𝒙 / √𝒙 ⋅ 𝒅𝒙 + ∫[1, ∞] e⁻√𝒙 / √𝒙 ⋅ 𝒅𝒙
     ◉ 3. Rewrite both pieces as limits.
          ○ lim_(𝒄 → 0⁺) ∫[𝒄, 1] e⁻√𝒙 / √𝒙 ⋅ 𝒅𝒙
          ○ + lim_(𝒃 → ∞) ∫[1, 𝒃] e⁻√𝒙 / √𝒙 ⋅ 𝒅𝒙
     ◉ 4. Use the same substitution in both parts.
          ○ Let 𝒖 = −√𝒙
          ○ Then 𝒅𝒖 = −1/(2√𝒙) ⋅ 𝒅𝒙
          ○ So 𝒅𝒙 = −2√𝒙 ⋅ 𝒅𝒖
          ○ Hence:
               ■ ∫ e⁻√𝒙 / √𝒙 ⋅ 𝒅𝒙 = −2∫ e^𝒖 𝒅𝒖 = −2e^𝒖 = −2e⁻√𝒙
     ◉ 5. Evaluate the first improper piece.
          ○ lim_(𝒄 → 0⁺) [−2e⁻√𝒙] | [𝒄, 1]
          ○ = lim_(𝒄 → 0⁺) [−2e⁻¹ + 2e⁻√𝒄]
          ○ = −2/e + 2
     ◉ 6. Evaluate the second improper piece.
          ○ lim_(𝒃 → ∞) [−2e⁻√𝒙] | [1, 𝒃]
          ○ = lim_(𝒃 → ∞) [−2e⁻√𝒃 + 2e⁻¹]
          ○ = 0 + 2/e
     ◉ 7. Add both results.
          ○ (−2/e + 2) + (2/e) = 2
     ◉ Final result.
          ○ The integral **converges**.
          ○ ∫[0, ∞] e⁻√𝒙 / √𝒙 ⋅ 𝒅𝒙 = 2
    





Ｃｏｍｐａｒｉｓｏｎ　Ｔｈｅｏｒｅｍ

● [2:27:00](https://www.youtube.com/watch?v=g-M8FHslgdk&t=8820). Comparison Theorem for improper integrals. [📷image](../img/Calculus 2 Lecture 7.6/[2-27-00]-01.png)
     ◉ Setup:
          ○ Assume 0 ≤ 𝒈(𝒙) ≤ 𝒇(𝒙) on [𝒂, ∞).
          ○ So 𝒇(𝒙) is above 𝒈(𝒙) on the interval.
     ◉ Fundamental comparison:
          ○ If ∫[𝒂, ∞] 𝒇(𝒙) ⋅ 𝒅𝒙 converges,
          ○ then ∫[𝒂, ∞] 𝒈(𝒙) ⋅ 𝒅𝒙 also converges.
          ○ Intuition:
               ■ if the bigger area is finite,
               ■ then the smaller area must also be finite.
     ◉ Reverse comparison:
          ○ If ∫[𝒂, ∞] 𝒈(𝒙) ⋅ 𝒅𝒙 diverges,
          ○ then ∫[𝒂, ∞] 𝒇(𝒙) ⋅ 𝒅𝒙 also diverges.
          ○ Intuition:
               ■ if the smaller area is already infinite,
               ■ then the bigger area must also be infinite.
     ◉ Important conditions:
          ○ The comparison is stated for nonnegative functions.
          ○ That is why we require 0 ≤ 𝒈(𝒙) ≤ 𝒇(𝒙).
     ◉ Important warning:
          ○ The implications only work in these directions.
          ○ You may conclude:
               ■ bigger converges ⇒ smaller converges
               ■ smaller diverges ⇒ bigger diverges
          ○ But you may not conclude:
               ■ smaller converges ⇒ bigger converges
               ■ bigger diverges ⇒ smaller diverges
     ◉ Main idea:
          ○ Instead of integrating a difficult function directly,
          ○ compare it with a simpler function whose improper behavior is already known.
     



          

Ｅｘａｍｐｌｅ　Ｏｆ　Ｔｈｅ　Ｃｏｍｐａｒｉｓｏｎ　Ｔｅｓｔ

● [2:35:00](https://www.youtube.com/watch?v=g-M8FHslgdk&t=9300). 🧩 Example 11 — Comparison test: ∫[1, ∞] 1/(𝒙 + sin² 𝒙) ⋅ 𝒅𝒙 [📷image](../img/Calculus 2 Lecture 7.6/[2-35-00]-01.png)
     ◉ Goal:
          ○ Apply the Comparison Test to determine whether
               ■ ∫[1, ∞] 1/(𝒙 + sin² 𝒙) ⋅ 𝒅𝒙
               ■ converges or diverges.
     ◉ Comparison function:
          ○ Compare it with
               ■ ∫[1, ∞] 1/(1 + 𝒙) ⋅ 𝒅𝒙
     ◉ Key inequality:
          ○ Since sin(𝒙) ≤ 1,
               ■ then sin²(𝒙) ≤ 1
          ○ Adding 𝒙 to both sides gives:
               ■ 𝒙 + sin²(𝒙) ≤ 𝒙 + 1
          ○ Taking reciprocals reverses the inequality:
               ■ 1/(𝒙 + sin² 𝒙) ≥ 1/(1 + 𝒙)
     ◉ Why this is useful:
          ○ The integrand is nonnegative.
          ○ It is bigger than a simpler function whose improper integral is already known.
     ◉ Check the comparison integral:
          ○ ∫[1, ∞] 1/(1 + 𝒙) ⋅ 𝒅𝒙
          ○ = lim_(𝒃 → ∞) ∫[1, 𝒃] 1/(1 + 𝒙) ⋅ 𝒅𝒙
          ○ = lim_(𝒃 → ∞) [ln|1 + 𝒙|] | [1, 𝒃]
          ○ = lim_(𝒃 → ∞) [ln(1 + 𝒃) − ln(2)]
          ○ = ∞
     ◉ Conclusion by comparison:
          ○ Because
               ■ 1/(𝒙 + sin² 𝒙) ≥ 1/(1 + 𝒙)
          ○ and
               ■ ∫[1, ∞] 1/(1 + 𝒙) ⋅ 𝒅𝒙 diverges,
          ○ it follows from the Comparison Test that
               ■ ∫[1, ∞] 1/(𝒙 + sin² 𝒙) ⋅ 𝒅𝒙 also diverges.
     ◉ Final result:
          ○ The integral is **divergent**.
     ◉ NOTE:
          ○ Recall the algebra of inequalities for positive quantities:
               ■ If 0 < 𝒇(𝒙) ≤ 𝒈(𝒙), then 1/𝒇(𝒙) ≥ 1/𝒈(𝒙).
          ○ In words:
               ■ a smaller positive denominator gives a larger fraction,
               ■ and a larger positive denominator gives a smaller fraction.
          ○ This is why, from
               ■ 𝒙 + sin²(𝒙) ≤ 1 + 𝒙,
          ○ we may conclude that
               ■ 1/(𝒙 + sin² 𝒙) ≥ 1/(1 + 𝒙).     






Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Improper Integrals
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/3-7-improper-integrals)
● Comparison Tests
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/5-4-comparison-tests)
● Basic Functions and Identities
     ◉ [openstax🌐](https://openstax.org/books/precalculus-2e/pages/a-basic-functions-and-identities)
