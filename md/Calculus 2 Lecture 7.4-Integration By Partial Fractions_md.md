-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ７．４ - Ｉｎｔｅｇｒａｔｉｏｎ Ｂｙ Ｐａｒｔｉａｌ Ｆｒａｃｔｉｏｎｓ**---------------------------------






Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:00](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=0). Introduction to Section 7.4: Partial Fractions.
     ◉ Guiding question:
          ○ How to integrate rational functions that do not fit directly into substitution, integration by parts, or trig substitution.
     ◉ Central idea:
          ○ Take one complicated rational fraction and decompose it into simpler fractions.
     ◉ Key observation:
          ○ The decomposition depends on the type of factors that appear in the denominator.





          

Ａｌｇｅｂｒａｉｃ　Ｆｏｕｎｄａｔｉｏｎｓ

● [📷image](../img/Calculus 2 Lecture 7.4/[1-07]-01.png)

● [1:07](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=67). Two algebra rules that justify the method: “The how”
     ◉ [1:22](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=82). Rule 1 — Polynomial factorization.
          ○ Every polynomial can be factored as a product of:
               ■ linear factors: 𝒂𝒙 + 𝒃
               ■ and/or irreducible quadratic factors: 𝒂𝒙² + 𝒃𝒙 + 𝒄
                    ▣ Some quadratics cannot be factored over the reals/rationals because their roots are complex.
     ◉ [4:15](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=255). Rule 2 — Proper rational functions.
          ○ If every rational function 𝑹(𝒙)/𝑸(𝒙) satisfies
               ■ degree(𝑹) < degree(𝑸),
          ○ then it can be decomposed into partial fractions.

● [5:41](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=341). Clarification of preliminary concepts using the introductory example.
     ◉ 🧩 Example 1 — Evaluate ∫ (4x² − 4x + 6) / (x³ − x² − 6x) dx.
     ◉ What “polynomial” means.
     ◉ What “rational function” means.
     ◉ What the degree of the numerator and denominator means.
          ○ The degree of 𝑹(𝒙) = 4x² − 4x + 6 is 2.
          ○ The degree of 𝑸(𝒙) = x³ − x² − 6x is 3.
          ○ So degree(𝑹) < degree(𝑸), and partial fraction decomposition is possible.
     ◉ [6:18](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=378). Criterion for improper rational functions.
          ○ If degree(𝑹) ≥ degree(𝑸),
          ○ then
               ■ first perform polynomial long division,
               ■ and then apply partial fractions to the proper remainder.

● [6:57](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=417). Note on division.
     ◉ There is no “magic shortcut” different from long division.
     ◉ Synthetic division only counts as a shortened version when it genuinely applies.





     

Ｃａｓｅ　１　—　Ｄｉｓｔｉｎｃｔ　Ｌｉｎｅａｒ　Ｆａｃｔｏｒｓ

● [8:14](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=494). Case 1: **Distinct** linear factors. [📷image](../img/Calculus 2 Lecture 7.4/[8-14]-01.png)
     ◉ Definition.
          ○ Linear factors are **distinct** when none of them repeats.
          ○ Example of distinct factors:
               ■ (𝒙 + 1)(𝒙 − 1)(𝒙 + 4)
          ○ Example of non-distinct factors:
               ■ (𝒙 + 1)²(𝒙 − 4)
     ◉ Decomposition rule.
          ○ If the denominator has distinct linear factors,
               ■ write one fraction for each linear factor.
     ◉ General model.
          ○ 𝑹(𝒙)/𝑸(𝒙) = 𝑨/(𝒂₁𝒙 + 𝒃₁) + 𝑩/(𝒂₂𝒙 + 𝒃₂) + ⋯
     ◉ Rule for the numerators.
          ○ For linear factors, the numerators are constants.          

● [11:20](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=680). 🧩 Example 1 — Distinct linear factors: ∫ (4𝒙² − 4𝒙 + 6)/(𝒙³ − 𝒙² − 6𝒙) 𝒅𝒙. [📷image-1](../img/Calculus 2 Lecture 7.4/[11-20]-01.png) [📷image-2](../img/Calculus 2 Lecture 7.4/[11-20]-02.png)
     ◉ First step:
          ○ Ignore the numerator for the moment and factor the denominator completely.
     ◉ Complete factorization of the denominator.
          ○ 𝒙³ − 𝒙² − 6𝒙 = 𝒙(𝒙² − 𝒙 − 6)
          ○ = 𝒙(𝒙 − 3)(𝒙 + 2)
     ◉ Identification of the factor type.
          ○ There are three factors.
          ○ All are linear.
          ○ All are distinct.
     ◉ Setup of the decomposition.
          ○ (4𝒙² − 4𝒙 + 6)/[𝒙(𝒙 − 3)(𝒙 + 2)] = 𝑨/𝒙 + 𝑩/(𝒙 − 3) + 𝑪/(𝒙 + 2)
     ◉ Common-denominator idea.
          ○ Once everything is written over the same denominator,
               ■ the numerators must match.
     ◉ “Cover-up” method to build the common numerator.
          ○ Each fraction is multiplied by the factors it is missing.
          ○ 𝑨/𝒙 contributes 𝑨(𝒙 − 3)(𝒙 + 2)
          ○ 𝑩/(𝒙 − 3) contributes 𝑩𝒙(𝒙 + 2)
          ○ 𝑪/(𝒙 + 2) contributes 𝑪𝒙(𝒙 − 3)
     ◉ Equality of numerators.
          ○ 4𝒙² − 4𝒙 + 6 = 𝑨(𝒙 − 3)(𝒙 + 2) + 𝑩𝒙(𝒙 + 2) + 𝑪𝒙(𝒙 − 3)
     ◉ Distribution and regrouping of terms.
          ○ 4𝒙² − 4𝒙 + 6 = (𝑨𝒙² − 𝑨𝒙 − 6𝑨) + (𝑩𝒙² + 2𝑩𝒙) + (𝑪𝒙² − 3𝑪𝒙)
          ○ 4𝒙² − 4𝒙 + 6 = (𝑨 + 𝑩 + 𝑪)𝒙² + (−𝑨 + 2𝑩 − 3𝑪)𝒙 − 6𝑨
     ◉ Comparison of coefficients.
          ○ 4 = 𝑨 + 𝑩 + 𝑪
          ○ −4 = −𝑨 + 2𝑩 − 3𝑪
          ○ 6 = −6𝑨
     ◉ Solving the system.
          ○ From 6 = −6𝑨, we get:
               ■ 𝑨 = −1
          ○ Substitute 𝑨 = −1 into the first equation:
               ■ 4 = −1 + 𝑩 + 𝑪
               ■ 5 = 𝑩 + 𝑪
          ○ Substitute 𝑨 = −1 into the second equation:
               ■ −4 = 1 + 2𝑩 − 3𝑪
               ■ −5 = 2𝑩 − 3𝑪
          ○ Solve the remaining two-equation system:
               ■ 5 = 𝑩 + 𝑪
               ■ −5 = 2𝑩 − 3𝑪
          ○ Multiply the first equation by 2:
               ■ 10 = 2𝑩 + 2𝑪
          ○ Subtract the second equation:
               ■ 15 = 5𝑪
               ■ 𝑪 = 3
          ○ Back-substitute into 5 = 𝑩 + 𝑪:
               ■ 5 = 𝑩 + 3
               ■ 𝑩 = 2
     ◉ Coefficients obtained.
          ○ 𝑨 = −1
          ○ 𝑩 = 2
          ○ 𝑪 = 3
     ◉ [31:31](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=1891). Rewriting the integral.
          ○ ∫ (4𝒙² − 4𝒙 + 6)/(𝒙³ − 𝒙² − 6𝒙) 𝒅𝒙 = ∫ [−1/𝒙 + 2/(𝒙 − 3) + 3/(𝒙 + 2)] 𝒅𝒙
     ◉ Important observation.
          ○ With linear factors, the final integration produces a sum of logarithms.
     ◉ Final integration.
          ○ −ln|𝒙| + 2ln|𝒙 − 3| + 3ln|𝒙 + 2| + 𝑪
     ◉ Warning about coefficients.
          ○ If the denominator were something like 2𝒙 − 3, the extra derivative factor would have to be taken into account when integrating.

● [37:39](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=2259). Shortcut for distinct linear factors. [📷image](../img/Calculus 2 Lecture 7.4/[37-39]-01.png)
     ◉ 🧩 Example 1 — Distinct linear factors: ∫ (4𝒙² − 4𝒙 + 6)/(𝒙³ − 𝒙² − 6𝒙) 𝒅𝒙
     ◉ Instead of distributing everything,
          ○ substitute values of 𝒙 that make specific factors zero.
     ◉ Start from the numerator identity:
          ○ 4𝒙² − 4𝒙 + 6 = 𝑨(𝒙 − 3)(𝒙 + 2) + 𝑩𝒙(𝒙 + 2) + 𝑪𝒙(𝒙 − 3)
     ◉ With 𝒙 = 0:
          ○ 6 = 𝑨(−3)(2)
          ○ 6 = −6𝑨
          ○ 𝑨 = −1
     ◉ With 𝒙 = 3:
          ○ 30 = 𝑩·3·5
          ○ 30 = 15𝑩
          ○ 𝑩 = 2
     ◉ With 𝒙 = −2:
          ○ 30 = 𝑪(−2)(−5)
          ○ 30 = 10𝑪
          ○ 𝑪 = 3
     ◉ Coefficients obtained by the shortcut.
          ○ 𝑨 = −1
          ○ 𝑩 = 2
          ○ 𝑪 = 3
     ◉ Rewritten partial-fraction form.
          ○ −1/𝒙 + 2/(𝒙 − 3) + 3/(𝒙 + 2)
     ◉ Advantage of the shortcut.
          ○ It is much faster when all factors are linear and distinct.
          ○ It avoids distributing and solving the full coefficient-comparison system.
     ◉ Limitation.
          ○ It does not work as well with irreducible quadratics,
               ■ because you cannot usually make them zero with simple real values.

● [45:10](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=2710). 🧩 Example 2 — Long division first: ∫ (𝒙⁴ − 3𝒙² − 3𝒙 − 2)/(𝒙³ − 𝒙² − 2𝒙) 𝒅𝒙. [📷image-1](../img/Calculus 2 Lecture 7.4/[45-10]-01.png) [📷image-2](../img/Calculus 2 Lecture 7.4/[45-10]-02.png) [📷image-3](../img/Calculus 2 Lecture 7.4/[45-10]-03.png)
     ◉ Difference from the previous example.
          ○ The degree of the numerator is greater than the degree of the denominator.
     ◉ Consequence.
          ○ **Long division must be done first**.
     ◉ Beginning of polynomial long division.
          ○ Rewrite the numerator with a placeholder term:
               ■ 𝒙⁴ + 0𝒙³ − 3𝒙² − 3𝒙 − 2
     ◉ Use of placeholders.
          ○ Insert 0𝒙³ so no powers of 𝒙 are skipped during the division.
     ◉ Long-division steps.
          ○ First quotient term:
               ■ 𝒙⁴ ÷ 𝒙³ = 𝒙
          ○ Multiply back:
               ■ 𝒙(𝒙³ − 𝒙² − 2𝒙) = 𝒙⁴ − 𝒙³ − 2𝒙²
          ○ Subtract and simplify:
               ■ (𝒙⁴ + 0𝒙³ − 3𝒙² − 3𝒙 − 2) − (𝒙⁴ − 𝒙³ − 2𝒙²)
               ■ = 𝒙³ − 𝒙² − 3𝒙 − 2
          ○ Second quotient term:
               ■ 𝒙³ ÷ 𝒙³ = 1
          ○ Multiply back again:
               ■ 1(𝒙³ − 𝒙² − 2𝒙) = 𝒙³ − 𝒙² − 2𝒙
          ○ Subtract and simplify:
               ■ (𝒙³ − 𝒙² − 3𝒙 − 2) − (𝒙³ − 𝒙² − 2𝒙)
               ■ = −𝒙 − 2
     ◉ Result of the division.
          ○ Quotient:
               ■ 𝒙 + 1
          ○ Remainder:
               ■ −𝒙 − 2
     ◉ Correct form of the result.
          ○ (𝒙⁴ − 3𝒙² − 3𝒙 − 2)/(𝒙³ − 𝒙² − 2𝒙)
          ○ = 𝒙 + 1 + (−𝒙 − 2)/(𝒙³ − 𝒙² − 2𝒙)
     ◉ Care with the sign of the remainder.
          ○ It is convenient to factor out the negative sign:
               ■ 𝒙 + 1 − (𝒙 + 2)/(𝒙³ − 𝒙² − 2𝒙)
          ○ The instructor isolates this rational piece first before decomposing it.
     ◉ Factorization of the denominator in the remainder.
          ○ 𝒙³ − 𝒙² − 2𝒙 = 𝒙(𝒙² − 𝒙 − 2)
          ○ = 𝒙(𝒙 − 2)(𝒙 + 1)
     ◉ Now the remaining rational part is proper.
     ◉ New partial-fraction decomposition.
          ○ (𝒙 + 2)/[𝒙(𝒙 − 2)(𝒙 + 1)] = 𝑨/𝒙 + 𝑩/(𝒙 − 2) + 𝑪/(𝒙 + 1)
     ◉ Equality of numerators.
          ○ 𝒙 + 2 = 𝑨(𝒙 − 2)(𝒙 + 1) + 𝑩𝒙(𝒙 + 1) + 𝑪𝒙(𝒙 − 2)
     ◉ Quick solution by substituting roots.
          ○ With 𝒙 = 0:
               ■ 2 = 𝑨(−2)(1)
               ■ 2 = −2𝑨
               ■ 𝑨 = −1
          ○ With 𝒙 = 2:
               ■ 4 = 𝑩(2)(3)
               ■ 4 = 6𝑩
               ■ 𝑩 = 2/3
          ○ With 𝒙 = −1:
               ■ 1 = 𝑪(−1)(−3)
               ■ 1 = 3𝑪
               ■ 𝑪 = 1/3
     ◉ Rewriting the full integral.
          ○ ∫ [𝒙 + 1 − (−1/𝒙 + (2/3)/(𝒙 − 2) + (1/3)/(𝒙 + 1))] 𝒅𝒙
          ○ = ∫ [𝒙 + 1 + 1/𝒙 − (2/3)/(𝒙 − 2) − (1/3)/(𝒙 + 1)] 𝒅𝒙
     ◉ Final integration by simple pieces.
          ○ Direct integration of the polynomial part:
               ■ ∫(𝒙 + 1) 𝒅𝒙 = (1/2)𝒙² + 𝒙
          ○ Logarithmic terms:
               ■ ∫ 1/𝒙 𝒅𝒙 = ln|𝒙|
               ■ ∫ (2/3)/(𝒙 − 2) 𝒅𝒙 = (2/3)ln|𝒙 − 2|
               ■ ∫ (1/3)/(𝒙 + 1) 𝒅𝒙 = (1/3)ln|𝒙 + 1|
     ◉ Final result.
          ○ (1/2)𝒙² + 𝒙 + ln|𝒙| − (2/3)ln|𝒙 − 2| − (1/3)ln|𝒙 + 1| + 𝑪




          
          
Ｃａｓｅ　２　—　Ｒｅｐｅａｔｅｄ　Ｌｉｎｅａｒ　Ｆａｃｔｏｒｓ

● [1:05:05](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=3905). 🧩 Example 3 —  Transition to case 2, repeated linear factor: ∫ (2𝒙² + 3𝒙 + 7)/(𝒙³ + 𝒙² − 𝒙 − 1) 𝒅𝒙. [📷image](../img/Calculus 2 Lecture 7.4/[1-05-05]-01.png)
     ◉ First step:
          ○ factor the denominator.
     ◉ Factorization by grouping.
          ○ 𝒙³ + 𝒙² − 𝒙 − 1
          ○ = 𝒙²(𝒙 + 1) − 1(𝒙 + 1)
          ○ = (𝒙 + 1)(𝒙² − 1)
          ○ = (𝒙 − 1)(𝒙 + 1)²
     ◉ Recognition of the new case.
          ○ A repeated linear factor appears.

● [1:10:23](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=4223). Case 2: Repeated linear factors.  [📷image](../img/Calculus 2 Lecture 7.4/[1-10-23]-01.png)
     ◉ If a linear factor is repeated,
          ○ a fraction must be included for each power up to the highest one.
     ◉ General model.
          ○ 𝑨₁/(𝒙 − 𝒂) + 𝑨₂/(𝒙 − 𝒂)² + ⋯ + 𝑨ₙ/(𝒙 − 𝒂)ⁿ

● [1:11:19](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=4279).🧩 Continue Example 3 — Transition to case 2: ∫ (2𝒙² + 3𝒙 + 7)/(𝒙³ + 𝒙² − 𝒙 − 1) 𝒅𝒙 [📷image](../img/Calculus 2 Lecture 7.4/[1-11-19]-01.png)
     ◉ Application to 🧩 Example 3.
          ○ 𝑨/(𝒙 − 1) + 𝑩/(𝒙 + 1) + 𝑪/(𝒙 + 1)²
     ◉ Construction of the common denominator.
          ○ The highest necessary power of the repeated factor is used.
     ◉ [1:10:23](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=4223). What would happen if the denominator also contained 𝒙³? [📷image](../img/Calculus 2 Lecture 7.4/[1-10-23]-02.png)
          ○ Then 𝒙³ would count as another repeated linear factor.
          ○ You would need one fraction for each power:
               ■ 𝑫/𝒙 + 𝑬/𝒙² + 𝑭/𝒙³
          ○ So the setup would become:
               ■ 𝑨/(𝒙 − 1) + 𝑩/(𝒙 + 1) + 𝑪/(𝒙 + 1)² + 𝑫/𝒙 + 𝑬/𝒙² + 𝑭/𝒙³
     ◉ The shortcut still works partially.
          ○ 𝒙 = 1 and 𝒙 = −1 can be used to isolate some constants.
     ◉ Coefficients obtained from the repeated-factor setup.
          ○ With 𝒙 = 1:
               ■ 12 = 𝑨(2)²
               ■ 𝑨 = 3
          ○ With 𝒙 = −1:
               ■ 6 = 𝑪(−2)
               ■ 𝑪 = −3
     ◉ Use of an additional value to find the remaining constant.
          ○ Taking 𝒙 = 0:
               ■ 7 = 𝑨 − 𝑩 − 𝑪
               ■ 7 = 3 − 𝑩 + 3
               ■ 𝑩 = −1
     ◉ Rewriting the integral.
          ○ ∫ [3/(𝒙 − 1) − 1/(𝒙 + 1) − 3/(𝒙 + 1)²] 𝒅𝒙
     ◉ Integration of the repeated term.
          ○ −3/(𝒙 + 1)² is integrated with the power rule, not with ln.
          ○ Let 𝒖 = 𝒙 + 1, then:
               ■ ∫ 3/(𝒙 + 1)² 𝒅𝒙 = 3∫(𝒙 + 1)⁻² 𝒅𝒙 = −3/(𝒙 + 1)
          ○ Because the term in the integral is subtracted,
               ■ the final contribution becomes +3/(𝒙 + 1)
     ◉ Result.
          ○ 3ln|𝒙 − 1| − ln|𝒙 + 1| + 3/(𝒙 + 1) + 𝑪
     ◉ Additional comment.
          ○ The logarithmic part can also be combined as:
               ■ ln|(𝒙 − 1)³/(𝒙 + 1)| + 3/(𝒙 + 1) + 𝑪



          


       

Ｃａｓｅ　３　—　Ｉｒｒｅｄｕｃｉｂｌｅ　Ｑｕａｄｒａｔｉｃ　Ｆａｃｔｏｒｓ

● [1:31:31](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=5491). 🧩 Example 4 — Transition to case 3: ∫ (𝒙² − 𝒙 − 21)/(2𝒙³ − 𝒙² + 8𝒙 − 4) 𝒅𝒙. [📷image](../img/Calculus 2 Lecture 7.4/[1-31-31]-01.png)
     ◉ Exam-style approach.
          ○ First check whether it fits a simpler method.
          ○ Then verify the degree.
          ○ Then factor.
     ◉ Factorization of the denominator.
          ○ 2𝒙³ − 𝒙² + 8𝒙 − 4 = (2𝒙 − 1)(𝒙² + 4)
     ◉ Recognition of an irreducible quadratic.
          ○ 𝒙² + 4 does not factor over the reals.

● [1:35:11](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=5711). Case 3: Irreducible quadratic factors. [📷image](../img/Calculus 2 Lecture 7.4/[1-35-11]-01.png)
     ◉ General rule.
          ○ Each irreducible quadratic gets a linear numerator.
     ◉ Degree rule.
          ○ The numerator must have degree one less than the denominator factor.
          
● [1:36:54](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=5814).🧩 Continue Example 4 — Transition to case 3 ∫ (𝒙² − 𝒙 − 21)/(2𝒙³ − 𝒙² + 8𝒙 − 4) 𝒅𝒙.  [📷image-1](../img/Calculus 2 Lecture 7.4/[1-36-54]-01.png) [📷image-2](../img/Calculus 2 Lecture 7.4/[1-36-54]-02.png) [📷image-3](../img/Calculus 2 Lecture 7.4/[1-36-54]-03.png)
     ◉ Application to the example.
          ○ 𝑨/(2𝒙 − 1) + (𝑩𝒙 + 𝑪)/(𝒙² + 4)
     ◉ Construction of the common denominator.
          ○ 𝒙² − 𝒙 − 21 = 𝑨(𝒙² + 4) + (𝑩𝒙 + 𝑪)(2𝒙 − 1)
     ◉ In this case the shortcut does not solve everything.
          ○ You may try some simple value,
          ○ but in the end you must distribute and compare coefficients.
     ◉ Regrouping by powers of 𝒙.
          ○ 𝒙² − 𝒙 − 21 = (𝑨 + 2𝑩)𝒙² + (−𝑩 + 2𝑪)𝒙 + (4𝑨 − 𝑪)
     ◉ Comparison of coefficients.
          ○ 𝑨 + 2𝑩 = 1
          ○ −𝑩 + 2𝑪 = −1
          ○ 4𝑨 − 𝑪 = −21
     ◉ Final coefficients.
          ○ 𝑨 = −5
          ○ 𝑩 = 3
          ○ 𝑪 = 1
     ◉ Rewriting the integral.
          ○ ∫ [−5/(2𝒙 − 1) + (3𝒙 + 1)/(𝒙² + 4)] 𝒅𝒙
     ◉ Splitting the quadratic term.
          ○ (3𝒙 + 1)/(𝒙² + 4) = 3𝒙/(𝒙² + 4) + 1/(𝒙² + 4)
     ◉ Different techniques are used in each part:
          ○ ln for −5/(2𝒙 − 1)
          ○ substitution for 𝒙/(𝒙² + 4)
          ○ tan⁻¹ for 1/(𝒙² + 4)
     ◉ Integration of the linear-factor term.
          ○ Let 𝒖 = 2𝒙 − 1, so 𝒅𝒖 = 2𝒅𝒙
          ○ Then:
               ■ ∫ −5/(2𝒙 − 1) 𝒅𝒙 = −(5/2)ln|2𝒙 − 1|
     ◉ Substitution for 𝒙/(𝒙² + 4).
          ○ Let 𝒖 = 𝒙² + 4, so 𝒅𝒖 = 2𝒙 𝒅𝒙
          ○ Then:
               ■ 3∫ 𝒙/(𝒙² + 4) 𝒅𝒙 = (3/2)ln|𝒙² + 4|
          ○ Since 𝒙² + 4 > 0,
               ■ this may also be written as (3/2)ln(𝒙² + 4)
     ◉ [1:55:48](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=6948). First method for ∫ 1/(𝒙² + 4) 𝒅𝒙. [📷image](../img/Calculus 2 Lecture 7.4/[1-55-48]-01.png)
          ○ Rewrite it in a form compatible with tan⁻¹.
          ○ Factor out a 4 from the denominator:
               ■ 1/(𝒙² + 4) = 1/[4((𝒙/2)² + 1)]
          ○ Hence:
               ■ ∫ 1/(𝒙² + 4) 𝒅𝒙 = (1/4)∫ 1/((𝒙/2)² + 1) 𝒅𝒙
          ○ Using 𝒖 = 𝒙/2, so 𝒅𝒙 = 2𝒅𝒖:
               ■ ∫ 1/(𝒙² + 4) 𝒅𝒙 = (1/2)tan⁻¹(𝒙/2)
     ◉ [1:56:48](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=7008). Second method for ∫ 1/(𝒙² + 4) 𝒅𝒙. [📷image](../img/Calculus 2 Lecture 7.4/[1-56-48]-01.png)
          ○ Interpret it through trig substitution.
          ○ Use:
               ■ tan(θ) = 𝒙/2
               ■ 𝒙 = 2tan(θ)
               ■ 𝒅𝒙 = 2sec²(θ) 𝒅θ
          ○ Then:
               ■ ∫ 1/(𝒙² + 4) 𝒅𝒙 = ∫ 2sec²(θ)/(4tan²(θ) + 4) 𝒅θ
               ■ = (1/2)∫ sec²(θ)/(tan²(θ) + 1) 𝒅θ
               ■ = (1/2)∫ 1 𝒅θ
               ■ = (1/2)θ
          ○ Returning to 𝒙:
               ■ θ = tan⁻¹(𝒙/2)
               ■ so the result is again (1/2)tan⁻¹(𝒙/2)
     ◉ Final combined result.
          ○ −(5/2)ln|2𝒙 − 1| + (3/2)ln|𝒙² + 4| + (1/2)tan⁻¹(𝒙/2) + 𝑪
          
● [2:01:43](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=7303). 🧩 Example 4 — Explanation: ∫ 1/(𝒙² + 4) 𝒅𝒙. [📷image-1](../img/Calculus 2 Lecture 7.4/[2-01-43]-01.png)  [📷image-2](../img/Calculus 2 Lecture 7.4/[2-01-43]-02.png)




          

Ｃａｓｅ　４　—　Ｒｅｐｅａｔｅｄ　Ｉｒｒｅｄｕｃｉｂｌｅ　Ｑｕａｄｒａｔｉｃｓ

● [2:16:10](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=8170). Case 4: Repeated irreducible quadratics.
     ◉ If an irreducible quadratic factor is repeated,
          ○ write one fraction for each power.
     ◉ Each numerator remains linear.
     ◉ General model:
          ○ (𝑨𝒙 + 𝑩)/(quadratic)
          ○ + (𝑪𝒙 + 𝑫)/(quadratic)²
          ○ + ⋯

● [2:17:02](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=8222). Large structural review 🧩 Example — : (5𝒙⁴ − 3𝒙² − 𝒙 + 1) / (𝒙(𝒙 − 1)²(𝒙² + 1)(𝒙² + 𝒙 + 1)²) [📷image](../img/Calculus 2 Lecture 7.4/[2-17-02]-01.png)
     ◉ 1. Check whether the denominator can be factored any further.
          ○ In this example, the denominator is already completely factored over the reals.
     ◉ 2. Identify the types of factors in the denominator.
          ○ linear factor:
               ■ 𝒙
          ○ repeated linear factor:
               ■ (𝒙 − 1)²
          ○ irreducible quadratic factor:
               ■ 𝒙² + 1
          ○ repeated irreducible quadratic factor:
               ■ (𝒙² + 𝒙 + 1)²
     ◉ 3. Check whether the rational function is proper.
          ○ degree of the numerator = 4
          ○ degree of the denominator = 9
          ○ so degree(numerator) < degree(denominator)
          ○ therefore, no long division is needed.
     ◉ 4. General counting rule.
          ○ Write one fraction for each factor.
          ○ If a factor is repeated, include one fraction for each power up to the highest one.
          ○  /𝒙 + /(𝒙 − 1) + /(𝒙 − 1)² + /(𝒙² + 1) + /(𝒙² + 𝒙 + 1) + /(𝒙² + 𝒙 + 1)²
     ◉ 5. General rule for the numerators.
          ○ Use constants for linear factors.
          ○ Use linear expressions for irreducible quadratic factors.
     ◉ 6. Correct decomposition for this example.
          ○ 𝑨/𝒙 + 𝑩/(𝒙 − 1) + 𝑪/(𝒙 − 1)² + (𝑫𝒙 + 𝑬)/(𝒙² + 1) + (𝑭𝒙 + 𝑮)/(𝒙² + 𝒙 + 1) + (𝑯𝒙 + 𝑰)/(𝒙² + 𝒙 + 1)²
     ◉ Key takeaway.
          ○ This single example combines all the main cases:
               ■ linear factors
               ■ repeated linear factors
               ■ irreducible quadratics
               ■ repeated irreducible quadratics
     ◉ There is no “alternative shortcut.”
          ○ The correct partial-fraction decomposition is exactly this setup.
 

● [2:23:40](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=8620). 🧩 Example 5 — Case 4: Evaluate ∫ (𝒙³ − 2𝒙² + 3𝒙 + 2) / [𝒙(𝒙² + 1)²] 𝒅𝒙. [📷image-1](../img/Calculus 2 Lecture 7.4/[2-23-40]-01.png)  [📷image-2](../img/Calculus 2 Lecture 7.4/[2-23-40]-02.png) [📷image-3](../img/Calculus 2 Lecture 7.4/[2-23-40]-03.png)
     ◉ Correct setup.
          ○ 𝑨/𝒙 + (𝑩𝒙 + 𝑪)/(𝒙² + 1) + (𝑫𝒙 + 𝑬)/(𝒙² + 1)²
     ◉ Construction of the common denominator.
          ○ 𝒙³ − 2𝒙² + 3𝒙 + 2
          ○ = 𝑨(𝒙² + 1)² + (𝑩𝒙 + 𝑪)𝒙(𝒙² + 1) + (𝑫𝒙 + 𝑬)𝒙
     ◉ First useful value.
          ○ Let 𝒙 = 0.
          ○ Then 2 = 𝑨.
     ◉ Since the shortcut is no longer enough,
          ○ the expression must be distributed and regrouped by powers of 𝒙.
     ◉ Expansion and collection of like terms.
          ○ 𝒙³ − 2𝒙² + 3𝒙 + 2
          ○ = (𝑨 + 𝑩)𝒙⁴ + 𝑪𝒙³ + (2𝑨 + 𝑩 + 𝑫)𝒙² + (𝑪 + 𝑬)𝒙 + 𝑨
     ◉ Comparison of coefficients.
          ○ coefficient of 𝒙⁴:
               ■ 𝑨 + 𝑩 = 0
          ○ coefficient of 𝒙³:
               ■ 𝑪 = 1
          ○ coefficient of 𝒙²:
               ■ 2𝑨 + 𝑩 + 𝑫 = −2
          ○ coefficient of 𝒙:
               ■ 𝑪 + 𝑬 = 3
          ○ constant term:
               ■ 𝑨 = 2
     ◉ Step-by-step solution of the coefficients.
          ○ 𝑨 = 2
          ○ 𝑪 = 1
          ○ from 𝑪 + 𝑬 = 3:
               ■ 1 + 𝑬 = 3
               ■ 𝑬 = 2
          ○ from 𝑨 + 𝑩 = 0:
               ■ 2 + 𝑩 = 0
               ■ 𝑩 = −2
          ○ from 2𝑨 + 𝑩 + 𝑫 = −2:
               ■ 2(2) + (−2) + 𝑫 = −2
               ■ 𝑫 = −4
     ◉ Rewriting the integral.
          ○ ∫ [2/𝒙 + (−2𝒙 + 1)/(𝒙² + 1) + (−4𝒙 + 2)/(𝒙² + 1)²] 𝒅𝒙
     ◉ Splitting into several simpler integrals.
          ○ 2∫ 1/𝒙 𝒅𝒙
          ○ −2∫ 𝒙/(𝒙² + 1) 𝒅𝒙
          ○ ∫ 1/(𝒙² + 1) 𝒅𝒙
          ○ −4∫ 𝒙/(𝒙² + 1)² 𝒅𝒙
          ○ 2∫ 1/(𝒙² + 1)² 𝒅𝒙
     ◉ Techniques used.
          ○ Logarithm for 1/𝒙:
               ■ 2∫ 1/𝒙 𝒅𝒙 = 2ln|𝒙|
          ○ Substitution for 𝒙/(𝒙² + 1):
               ■ let 𝒖 = 𝒙² + 1
               ■ 𝒅𝒖 = 2𝒙 𝒅𝒙
               ■ −2∫ 𝒙/(𝒙² + 1) 𝒅𝒙 = −ln|𝒙² + 1|
          ○ Inverse tangent for 1/(𝒙² + 1):
               ■ ∫ 1/(𝒙² + 1) 𝒅𝒙 = tan⁻¹(𝒙)
          ○ Negative-power substitution for 𝒙/(𝒙² + 1)²:
               ■ let 𝒖 = 𝒙² + 1
               ■ 𝒅𝒖 = 2𝒙 𝒅𝒙
               ■ −4∫ 𝒙/(𝒙² + 1)² 𝒅𝒙 = 2/(𝒙² + 1)
          ○ Trig substitution for 1/(𝒙² + 1)²:
               ■ use tan(θ) = 𝒙
               ■ then 𝒅𝒙 = sec²(θ) 𝒅θ
               ■ 2∫ 1/(𝒙² + 1)² 𝒅𝒙 = 2∫ cos²(θ) 𝒅θ
     ◉ Treatment of the last term.
          ○ Use the identity:
               ■ cos²(θ) = (1 + cos(2θ))/2
          ○ Then:
               ■ 2∫ cos²(θ) 𝒅θ = θ + sin(2θ)/2
               ■ = θ + sin(θ)cos(θ)
     ◉ Return from θ to 𝒙.
          ○ θ = tan⁻¹(𝒙)
          ○ sin(θ) = 𝒙/√(𝒙² + 1)
          ○ cos(θ) = 1/√(𝒙² + 1)
          ○ so:
               ■ θ + sin(θ)cos(θ) = tan⁻¹(𝒙) + 𝒙/(𝒙² + 1)
     ◉ Final combination of terms.
          ○ 2ln|𝒙|
          ○ −ln|𝒙² + 1|
          ○ + tan⁻¹(𝒙)
          ○ + 2/(𝒙² + 1)
          ○ + tan⁻¹(𝒙)
          ○ + 𝒙/(𝒙² + 1)
     ◉ Simplified final answer.
          ○ 2ln|𝒙| − ln|𝒙² + 1| + 2tan⁻¹(𝒙) + (𝒙 + 2)/(𝒙² + 1) + 𝑪


          

Ｃｏｎｃｌｕｓｉｏｎ

● [2:55:14](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=10514). Closing of the last example.
     ◉ The hardest part of the method is usually the algebra:
          ○ factor correctly
          ○ set up the decomposition correctly
          ○ compare coefficients without sign errors
     ◉ Once the decomposition is done,
          ○ the integration usually reduces to already-known techniques:
               ■ logarithms
               ■ substitution
               ■ tan⁻¹
               ■ and, in some cases, trig substitution



Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

[openstax🌐](https://openstax.org/books/calculus-volume-2/pages/3-3-trigonometric-substitution)