-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ９．３： Ｕｓｉｎｇ ｔｈｅ Ｉｎｔｅｇｒａｌ Ｔｅｓｔ ｆｏｒ Ｃｏｎｖｅｒｇｅｎｃｅ／Ｄｉｖｅｒｇｅｎｃｅ ｏｆ Ｓｅｒｉｅｓ， Ｐ－Ｓｅｒｉｅｓ**-----------------------------------






Ｔｈｅｏｒｙ　ａｎｄ　Ｃｏｎｄｉｔｉｏｎｓ

● [0:00](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=0). Fundamental idea of the Integral Test.
     ◉ Main question:
          ○ can we use integrals to test convergence or divergence of a series?
     ◉ Basic intuition:
          ○ an integral adds up infinitely many small areas.
          ○ a series adds up infinitely many terms.
     ◉ Therefore:
          ○ if the terms of a series can be represented by a function,
               ■ then the improper integral of that function can help determine whether the series converges or diverges.

● N̲O̲T̲E̲ 1: Relationship between rectangles and series terms.
     ◉ A series adds:
          ○ 𝒂₁ + 𝒂₂ + 𝒂₃ + ...
     ◉ An integral adds:
          ○ areas under a curve.
     ◉ Conceptual connection:
          ○ the terms of the series can be thought of as rectangle heights.
          ○ the integral adds up the area under the corresponding function.
     ◉ Key idea:
          ○ if the total area is finite,
               ■ the series may also be finite.
          ○ if the total area is infinite,
               ■ the series may also diverge.

● [1:04](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=64). Requirements for applying the Integral Test.
     ◉ Let the sequence terms be represented by a function:
          ○ 𝒂ₙ = 𝒇(𝒏)
     ◉ To apply the Integral Test, 𝒇(𝒙) must be:
          ○ ❶ Continuous
               ■ The function must be continuous on the interval. Meaning:
                    ▣ no breaks.
                    ▣ no jumps.
                    ▣ no vertical asymptotes inside the interval.
          ○ ❷ Positive
               ■ The function must be positive on the interval. Meaning:
                    ▣ 𝒇(𝒙) > 0
               ■ This matches the idea of adding positive terms in the series.
          ○ ❸ Decreasing
               ■ The function must be decreasing on the interval. Meaning:
                    ▣ as 𝒙 increases, 𝒇(𝒙) gets smaller.
               ■ If decreasing is not obvious,
                    ▣ use the first derivative.
               ■ If:
                    ▣ 𝒇′(𝒙) < 0
               ■ Then:
                    ▣ 𝒇(𝒙) is decreasing.
     ◉ These conditions must hold on the interval being tested:
          ○ usually [1,∞)
          ○ or sometimes [𝑵,∞), if the first few terms cause problems.

● [2:39](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=159). Formal statement of the Integral Test. [📷image](../img/Calculus 2 Lecture 9.3/[2-39]-01.png)
     ◉ Suppose:
          ○ 𝒂ₙ = 𝒇(𝒏)
     ◉ If 𝒇(𝒙) is:
          ○ continuous,
          ○ positive,
          ○ and decreasing
     ◉ on [1,∞), then:
          ○ ∑[𝒏=1,∞] 𝒂ₙ and ∫[1,∞] 𝒇(𝒙) ⋅ 𝒅𝑥 have the same convergence behavior.

● N̲O̲T̲E̲ 2: Relationship between the series and the improper integral.
     ◉ i̲f̲   ∫[1,∞] 𝒇(𝒙) ⋅ 𝒅𝑥 converges,
          ○ t̲h̲e̲n̲  ∑[𝒏=1,∞] 𝒂ₙ converges.
     ◉ i̲f̲  ∫[1,∞] 𝒇(𝒙) ⋅ 𝒅𝑥 diverges,
          ○ t̲h̲e̲n̲ ∑[𝒏=1,∞] 𝒂ₙ diverges.
     ◉ Important:
          ○ the series and the integral have the same result only in terms of convergence or divergence.
          ○ they do not necessarily have the same numerical value.

● [4:00](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=240). The integral as a bound for the series.
     ◉ Conceptual idea:
          ○ the improper integral acts as a bound for the series.
     ◉ If the integral converges:
          ○ it gives an upper-bound type idea.
          ○ the series is trapped under a finite amount of total area.
     ◉ If the integral diverges:
          ○ it shows that the accumulated area grows without bound.
          ○ the series also diverges.
     ◉ Practical meaning:
          ○ we use the integral to decide whether the series converges or diverges.



          

Ｃｒｉｔｉｃａｌ　Ｎｏｔｅｓ

● [📷image](../img/Calculus 2 Lecture 9.3/[4-45]-01.png)    

● [4:45](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=285). ✱ The Integral Test does not necessarily give the sum.
     ◉ If ∫[1,∞] 𝒇(𝒙) ⋅ 𝒅𝑥 = 𝑳
          ○ This does not mean ∑[𝒏=1,∞] 𝒂ₙ = 𝑳
          ○ It only means:
               ■ the series converges.
          ○ Therefore:
               ■ the integral value is not necessarily the series sum.

● [7:08](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=428). ✱ Adding or subtracting finitely many terms does not affect convergence.
     ◉ Convergence is not affected by:
          ○ adding finitely many terms.
          ○ subtracting finitely many terms.
          ○ ignoring the first few terms.
     ◉ Important distinction:
          ○ the sum may change.
          ○ but the convergence or divergence does not change.
     ◉ Therefore:
          ○ we may start the Integral Test at a later integer if necessary.

● [8:10](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=490). Adjusting the starting point. [📷image](../img/Calculus 2 Lecture 9.3/[8-10]-01.png)
     ◉ Sometimes 𝒇(𝒙) is not decreasing from 𝒏 = 1.
     ◉ But if 𝒇(𝒙) becomes decreasing after some point,
          ○ we can start the integral at that later point.
     ◉ Example:
          ○ instead of starting at 1,
          ○ we may start at 3, 5, 7, or another suitable integer.
     ◉ Reason:
          ○ removing finitely many terms does not affect convergence.




          

Ｅｘａｍｐｌｅｓ　Ｕｓｉｎｇ　ｔｈｅ　Ｉｎｔｅｇｒａｌ　Ｔｅｓｔ

Ｅｘａｍｐｌｅ   1  

● [📷image](../img/Calculus 2 Lecture 9.3/[10-30]-01.png)

● [10:30](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=630). 🧩 Example 1 — Determining convergence for ∑[𝒏=1,∞] 1/(𝒏² + 1).
     ◉ Given series:
          ○ ∑[𝒏=1,∞] 1/(𝒏² + 1)
     ◉ First check the Divergence Test:
          ○ limₙ→∞ 1/(𝒏² + 1) = 0
     ◉ Since the limit is 0:
          ○ **the Divergence Test is inconclusive.**
          ○ we must use another test.

● [12:22](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=742). Applying the Integral Test to Example 1.
     ◉ Define:
          ○ 𝒇(𝒙) = 1/(𝒙² + 1)
     ◉ Check the conditions on [1,∞):
          ○ 𝒇(𝒙) is positive.
          ○ 𝒇(𝒙) is continuous.
          ○ 𝒇(𝒙) is decreasing.
     ◉ Therefore:
          ○ the Integral Test can be applied.

● [13:40](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=820). Applying the Integral Test to a variant of Example 1: 𝒇(𝒙) = 1/(𝒙² - 1)
     ◉ Check the conditions on [1,∞):
          ○ 𝒇(𝒙) is not continuous at 𝒙 = 1,
               ■ because 𝒙² - 1 = 0 when 𝒙 = 1.
          ○ therefore, we cannot use the interval [1,∞).
     ◉ Can we subtract a finite number of terms?
          ○ Yes.
          ○ convergence is not affected by removing finitely many terms.
     ◉ So we adjust the starting interval:
          ○ instead of [1,∞),
               ■ use [2,∞).
     ◉ Check the conditions on [2,∞):
          ○ 𝒇(𝒙) is positive.
          ○ 𝒇(𝒙) is continuous.
          ○ 𝒇(𝒙) is decreasing.
     ◉ Therefore:
          ○ the Integral Test can be applied on [2,∞).

● [14:22](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=862). Solving the improper integral in Example 1.
     ◉ Set up the integral:
          ○ ∫[1,∞] 1/(𝒙² + 1) ⋅ 𝒅𝑥
     ◉ Rewrite as an improper integral:
          ○ lim_b→∞ ∫[1,b] 1/(𝒙² + 1) ⋅ 𝒅𝑥
     ◉ Antiderivative:
          ○ ∫ 1/(𝒙² + 1) ⋅ 𝒅𝑥 = tan⁻¹(𝒙)

● [16:42](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1002). Evaluating the limit in Example 1.
     ◉ Evaluate:
          ○ lim_b→∞ [tan⁻¹(𝒙)]₁ᵇ
          ○ = lim_b→∞ [tan⁻¹(b) - tan⁻¹(1)]
     ◉ Since:
          ○ lim_b→∞ tan⁻¹(b) = π/2
          ○ tan⁻¹(1) = π/4
     ◉ Then:
          ○ π/2 - π/4 = π/4
     ◉ Therefore:
          ○ the improper integral converges.

● [18:00](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1080). Conclusion for Example 1.
     ◉ Since the limit exists the improper integral converges,
          ○ the series ∑[𝒏=1,∞] 1/(𝒏² + 1) and the integral converge.
     ◉ Important:
          ○ π/4 is the value of the integral.
          ○ it is not necessarily the sum of the series.
          

Ｅｘａｍｐｌｅ   2 

● [📷image](../img/Calculus 2 Lecture 9.3/[19-34]-01.png)

● [19:34](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1174). 🧩 Example 2 — Analyzing ∑[𝒏=1,∞] 3/(2𝒏 - 1).
     ◉ Given series:
          ○ ∑[𝒏=1,∞] 3/(2𝒏 - 1)
     ◉ First check the Divergence Test:
          ○ limₙ→∞ 3/(2𝒏 - 1) = 0
     ◉ Since the limit is 0:
          ○ **the Divergence Test is inconclusive.**
          ○ we must continue.

● [20:12](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1212). Applying the Integral Test to Example 2.
     ◉ Define:
          ○ 𝒇(𝒙) = 3/(2𝒙 - 1)
     ◉ Check the conditions on [1,∞):
          ○ 𝒇(𝒙) is positive.
          ○ 𝒇(𝒙) is continuous.
          ○ 𝒇(𝒙) is decreasing.
     ◉ Therefore:
          ○ the Integral Test can be applied.

● [21:00](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1260). Solving the improper integral in Example 2.
     ◉ Set up:
          ○ ∫[1,∞] 3/(2𝒙 - 1) ⋅ 𝒅𝑥
     ◉ Rewrite as an improper integral:
          ○ lim_b→∞ ∫[1,b] 3/(2𝒙 - 1) ⋅ 𝒅𝑥
     ◉ Use substitution:
          ○ 𝒖 = 2𝒙 - 1
          ○ d𝒖 = 2 ⋅ 𝒅𝑥
          ○ 𝒅𝑥 = d𝒖/2
     ◉ Antiderivative:
          ○ ∫ 3/(2𝒙 - 1) ⋅ 𝒅𝑥 = (3/2) ln|2𝒙 - 1|

● [22:25](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1345). Evaluating the limit in Example 2.
     ◉ Evaluate:
          ○ lim_b→∞ [(3/2) ln(2𝒙 - 1)]₁ᵇ
          ○ = lim_b→∞ [(3/2) ln(2b - 1) - (3/2) ln(1)]
     ◉ Since:
          ○ ln(1) = 0
          ○ ln(2b - 1) → ∞ as b → ∞
     ◉ Therefore:
          ○ the improper integral diverges.

● [25:15](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1515). Conclusion for Example 2.
     ◉ Since the improper integral diverges,
          ○ the series ∑[𝒏=1,∞] 3/(2𝒏 - 1) diverges.
          

Ｅｘａｍｐｌｅ  3

● [📷image-1](../img/Calculus 2 Lecture 9.3/[26-15]-01.png) [📷image-2](../img/Calculus 2 Lecture 9.3/[26-15]-02.png)

● [26:15](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1575). 🧩 Example 3 — The case of ∑[𝒏=1,∞] ln(𝒏)/𝒏.
     ◉ Given series:
          ○ ∑[𝒏=1,∞] ln(𝒏)/𝒏
     ◉ First check the Divergence Test:
          ○ limₙ→∞ ln(𝒏)/𝒏 = 0
     ◉ Since the limit is 0:
          ○ the Divergence Test is inconclusive.
     ◉ Define 𝒇(𝒙) as a model of theseries:
          ○ 𝒇(𝒙) = ln(𝒙)/𝒙

● [28:10](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1690). Checking decreasing behavior for Example 3.
     ◉ To prove decreasing,
          ○ take the derivative.
     ◉ Differentiate:
          ○ d/d𝒙 [ln(𝒙)/𝒙] = (1 - ln(𝒙))/𝒙²
     ◉ We need:
          ○ 𝒇′(𝒙) ≤ 0
     ◉ Since 𝒙² > 0,
          ○ the sign depends on 1 - ln(𝒙).
     ◉ [29:40](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1780). Sign analysis for Example 3.
          ○ The derivative is non-positive when:
               ■ 1 - ln(𝒙) ≤ 0
          ○ This means:
               ■ 1 ≤ ln(𝒙)
               ■ 𝒆 ≤ 𝒙
          ○ Therefore:
               ■ 𝒇(𝒙) is decreasing for 𝒙 ≥ 𝒆.
          ○ Since:
               ■ 3 > 𝒆
          ○ We can use the interval:
               ■ [3,∞)
          ○  N̲O̲T̲E̲ — Strictly decreasing versus non-increasing.
               ■ If 𝒇′(𝒙) < 0
                    ▣ Then 𝒇(𝒙) is strictly decreasing.
                    ▣ This means the function is always going down
               ■ If 𝒇′(𝒙) ≤ 0
                    ▣ Then 𝒇(𝒙) is decreasing / non-increasing.  
                    ▣ This means the function does not go up.
                    ▣ it may go down,
                         ▢ or it may stay flat at isolated points.
               ■ For the Integral Test:
                    ▣ non-increasing behavior is enough.
                    ▣ so using 𝒇′(𝒙) ≤ 0 is valid.
              
● [31:07](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1867). Adjusting the lower limit in Example 3.
     ◉ The original series starts at 𝒏 = 1.
     ◉ But the function is guaranteed to be decreasing from 𝒙 = 3 onward.
     ◉ This is allowed because:
          ○ removing finitely many terms does not affect convergence.
     ◉ Therefore:
          ○ use the integral from 3 to ∞.

● [36:42](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=2202). Solving the improper integral in Example 3.
     ◉ Set up:
          ○ ∫[3,∞] ln(𝒙)/𝒙 ⋅ 𝒅𝑥
     ◉ Rewrite as an improper integral:
          ○ lim_b→∞ ∫[3,b] ln(𝒙)/𝒙 ⋅ 𝒅𝑥
     ◉ Use substitution:
          ○ 𝒖 = ln(𝒙)
          ○ d𝒖 = 1/𝒙 ⋅ 𝒅𝑥
     ◉ Then:
          ○ ∫ ln(𝒙)/𝒙 ⋅ 𝒅𝑥 = [ln(𝒙)]²/2

● [38:41](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=2321). Conclusion for Example 3.
     ◉ Evaluate:
          ○ lim_b→∞ [[ln(𝒙)]²/2]₃ᵇ
          ○ = lim_b→∞ ([ln(b)]²/2 - [ln(3)]²/2)
     ◉ Since:
          ○ ln(b) → ∞ as b → ∞
     ◉ Then:
          ○ [ln(b)]²/2 → ∞
     ◉ Therefore:
          ○ the improper integral diverges.
     ◉ Since the improper integral diverges,
          ○ the series ∑[𝒏=1,∞] ln(𝒏)/𝒏 diverges.



          

𝒑－Ｓｅｒｉｅｓ

● [📷image](../img/Calculus 2 Lecture 9.3/[41-16]-01.png)

● [41:16](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=2476). Introduction to 𝒑-Series.
     ◉ A 𝒑-series has the form:
          ○ ∑[𝒏=1,∞] 1/𝒏ᵖ
     ◉ Here:
          ○ 𝒏 is the changing index.
          ○ 𝒑 is a fixed exponent.

● General form of a 𝒑-series.
     ◉ The series:
          ○ ∑[𝒏=1,∞] 1/𝒏ᵖ
     ◉ Expands as:
          ○ 1 + 1/2ᵖ + 1/3ᵖ + 1/4ᵖ + ...
     ◉ Important:
          ○ 𝒑 does not change.
          ○ only 𝒏 changes.

● [43:25](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=2605). Convergence and divergence rules for 𝒑-Series.
     ◉ 𝒑-series rule:
          ○ ∑[𝒏=1,∞] 1/𝒏ᵖ converges if 𝒑 > 1.
          ○ ∑[𝒏=1,∞] 1/𝒏ᵖ diverges if 𝒑 ≤ 1.
     ◉ Special case:
          ○ when 𝒑 = 1,
               ■ ∑[𝒏=1,∞] 1/𝒏 is **the harmonic series.**
               ■ the harmonic series diverges.

● [49:41](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=2981). 🧩 Example — 𝒑-Series: ∑[𝒏=1,∞] 1/𝒏² [📷image](../img/Calculus 2 Lecture 9.3/[49-41]-01.png)
     ◉ Here:
          ○ 𝒑 = 2
     ◉ Since:
          ○ 2 > 1
     ◉ Therefore:
          ○ ∑[𝒏=1,∞] 1/𝒏² converges.

● [50:55](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=3055). 🧩 Example — 𝒑-Series: ∑[𝒏=1,∞] 1/∛𝒏 [📷image](../img/Calculus 2 Lecture 9.3/[50-55]-01.png)
     ◉ Rewrite:
          ○ ∛𝒏 = 𝒏¹ᐟ³
     ◉ Therefore:
          ○ ∑[𝒏=1,∞] 1/∛𝒏 = ∑[𝒏=1,∞] 1/𝒏¹ᐟ³
     ◉ Here:
          ○ 𝒑 = 1/3
     ◉ Since:
          ○ 1/3 < 1
     ◉ Therefore:
          ○ ∑[𝒏=1,∞] 1/∛𝒏 diverges.

● [52:11](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=3131). 🧩 Example — 𝒑-Series: ∑[𝒏=1,∞] 𝒏^(-𝛑) [📷image](../img/Calculus 2 Lecture 9.3/[52-11]-01.png)
     ◉ Rewrite:
          ○ 𝒏^(-𝛑) = 1/𝒏^𝛑
     ◉ Therefore:
          ○ ∑[𝒏=1,∞] 𝒏^(-𝛑) = ∑[𝒏=1,∞] 1/𝒏^𝛑
     ◉ Here:
          ○ 𝒑 = 𝛑
     ◉ Since:
          ○ 𝛑 > 1
     ◉ Therefore:
          ○ ∑[𝒏=1,∞] 𝒏^(-𝛑) converges.

● [56:33](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=3393). Important note about recognizing 𝒑-Series.
     ◉ A 𝒑-series must have the form:
          ○ constant / 𝒏ᵖ
     ◉ It cannot have extra terms added in the denominator.
     ◉ Example:
          ○ ∑[𝒏=1,∞] 1/(𝒏⁷ + 1)
     ◉ This is not directly a 𝒑-series.
     ◉ However:
          ○ it can later be compared to a 𝒑-series.
     ◉ **This leads to the Comparison Test.**



     

Ａｄｖａｎｃｅｄ　Ｉｎｔｅｇｒａｌ　Ｔｅｓｔ　Ｅｘａｍｐｌｅ

● [57:45](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=3465). 🧩 Advanced Example — :∑[𝒏=1,∞] 𝒆¹ᐟⁿ/𝒏². [📷image](../img/Calculus 2 Lecture 9.3/[57-45]-01.png)
     ◉ Given series:
          ○ ∑[𝒏=1,∞] 𝒆¹ᐟⁿ/𝒏²
     ◉ First check the Divergence Test:
          ○ limₙ→∞ 𝒆¹ᐟⁿ/𝒏² = 0
     ◉ Since the limit is 0:
          ○ the Divergence Test is inconclusive.
     ◉ This is not geometric:
          ○ because the changing variable is not a constant raised to the 𝒏.
     ◉ This is not a 𝒑-series:
          ○ because the numerator is not constant.
     ◉ Therefore:
          ○ try the Integral Test.

● [1:00:25](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=3625). Validating the Integral Test conditions for the advanced example.
     ◉ Define:
          ○ 𝒇(𝒙) = 𝒆¹ᐟˣ/𝒙²
     ◉ Check positivity:
          ○ 𝒆¹ᐟˣ is positive.
          ○ 𝒙² is positive for 𝒙 ≥ 1.
          ○ therefore, 𝒇(𝒙) is positive.
     ◉ Check continuity:
          ○ 𝒆¹ᐟˣ/𝒙² is continuous on [1,∞).
     ◉ Check decreasing:
          ○ use the first derivative.

● [1:01:09](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=3669). Showing decreasing behavior in the advanced example.
     ◉ Differentiate:
          ○ 𝒇(𝒙) = 𝒆¹ᐟˣ/𝒙²
     ◉ Using the quotient rule:
          ○ 𝒇′(𝒙) = [-𝒆¹ᐟˣ ⋅ (1 + 2𝒙)]/𝒙⁴
     ◉ Sign analysis:
          ○ 𝒆¹ᐟˣ > 0
          ○ 1 + 2𝒙 > 0 for 𝒙 ≥ 1
          ○ 𝒙⁴ > 0
     ◉ Because of the negative sign:
          ○ 𝒇′(𝒙) < 0 on [1,∞)
     ◉ Therefore:
          ○ 𝒇(𝒙) is decreasing on [1,∞).

● [1:07:22](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=4042). Solving the integral in the advanced example.
     ◉ Set up:
          ○ ∫[1,∞] 𝒆¹ᐟˣ/𝒙² ⋅ 𝒅𝑥
     ◉ Rewrite as an improper integral:
          ○ lim_b→∞ ∫[1,b] 𝒆¹ᐟˣ/𝒙² ⋅ 𝒅𝑥
     ◉ Use substitution:
          ○ 𝒖 = 1/𝒙
          ○ d𝒖 = -1/𝒙² ⋅ 𝒅𝑥
          ○ -d𝒖 = 1/𝒙² ⋅ 𝒅𝑥
     ◉ Then:
          ○ ∫ 𝒆¹ᐟˣ/𝒙² ⋅ 𝒅𝑥 = -𝒆¹ᐟˣ

● [1:09:48](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=4188). Evaluating the advanced example.
     ◉ Evaluate:
          ○ lim_b→∞ [-𝒆¹ᐟˣ]₁ᵇ
          ○ = lim_b→∞ [-𝒆¹ᐟᵇ - (-𝒆¹)]
     ◉ Since:
          ○ 1/b → 0 as b → ∞
          ○ 𝒆¹ᐟᵇ → 𝒆⁰ = 1
     ◉ Therefore:
          ○ -𝒆¹ᐟᵇ + 𝒆 → -1 + 𝒆
          ○ = 𝒆 - 1
     ◉ The improper integral converges.

● [1:10:22](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=4222). Final conclusion for the advanced example.
     ◉ Since:
          ○ ∫[1,∞] 𝒆¹ᐟˣ/𝒙² ⋅ 𝒅𝑥 = 𝒆 - 1
     ◉ The improper integral converges.
     ◉ Therefore:
          ○ ∑[𝒏=1,∞] 𝒆¹ᐟⁿ/𝒏² converges by the Integral Test.
     ◉ Important:
          ○ 𝒆 - 1 is the value of the integral.
          ○ it is not necessarily the sum of the series.




Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● The 𝒑-Series and The Integral Test
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/5-3-the-divergence-and-integral-tests)