-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ９．６： Ａｂｓｏｌｕｔｅ  Ｃｏｎｖｅｒｇｅｎｃｅ， Ｒａｔｉｏ Ｔｅｓｔ ａｎｄ Ｒｏｏｔ Ｔｅｓｔ Ｆｏｒ Ｓｅｒｉｅｓ**-------------------------------—




1 - Ａｂｓｏｌｕｔｅ　Ｃｏｎｖｅｒｇｅｎｃｅ


● [0:03](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3). Introduction to Absolute Convergence.
     ◉ Previous tests often required positive terms:
          ○ Integral Test:
               ■ positive,
               ■ continuous,
               ■ decreasing.
          ○ Direct Comparison Test:
               ■ positive terms.
          ○ Limit Comparison Test:
               ■ positive terms.
     ◉ Main question:
          ○ how do we deal with series that have negative terms?
     ◉ One case is already known:
          ○ if the signs alternate regularly,
               ■ use the Alternating Series Test.
     ◉ But:
          ○ if the terms are sometimes positive and sometimes negative,
          ○ and they do not alternate regularly,
               ■ we need another idea.

● [0:49](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=49). Absolute convergence idea.
     ◉ If the original series has negative terms,
          ○ take the absolute value of the terms.
     ◉ This turns all terms into positive terms.
     ◉ Then we can try tests that require positive terms:
          ○ Comparison Test.
          ○ Limit Comparison Test.
          ○ Integral Test.
          ○ Ratio Test.
          ○ Root Test.





1.1 - Ｄｅｆｉｎｉｔｉｏｎ　ｏｆ　Ａｂｓｏｌｕｔｅ　Ｃｏｎｖｅｒｇｅｎｃｅ

● [1:31](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=91). **Formal definition of absolute convergence.** [📷image](../img/Calculus 2 Lecture 9.6/[1-31]-01.png)
     ◉ Given a series:
          ○ ∑ 𝒂ₙ
     ◉ Take the absolute value of every term:
          ○ ∑ |𝒂ₙ|
     ◉ i̲f̲  ∑ |𝒂ₙ| converges,
          ○ t̲h̲e̲n̲ ∑ 𝒂ₙ is absolutely convergent.

● [2:03](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=123). Effect of absolute value.
     ◉ The absolute value changes negative terms into positive terms.
     ◉ Example:
          ○ |𝒂₁| + |𝒂₂| + |𝒂₃| + ...
     ◉ There are no negative terms left.
     ◉ Therefore:
          ○ absolute convergence studies the convergence of the positive-size version of the series.

● [4:25](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=265). 🧩 Example —  Use for things like this: ∑[𝒏=1,∞] sin(2𝑥)/𝒏²
     ◉ NOT (Alternating,noneincreasin and positive)

● N̲O̲T̲E̲ — Meaning of absolute convergence.
     ◉ Absolute convergence means:
          ○ the series still converges even after removing all sign cancellations.
     ◉ This is stronger than ordinary convergence.
     ◉ Reason:
          ○ if the positive-size version converges,
               ■ then the original signed series definitely converges.





1.2 -Ｆｉｒｓｔ　Ｅｘａｍｐｌｅ　ｏｆ　Ａｂｓｏｌｕｔｅ　Ｃｏｎｖｅｒｇｅｎｃｅ


● [📷image](../img/Calculus 2 Lecture 9.6/[4-25]-01.png)

● [4:25](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=265). 🧩 Example —  Absolute convergence: ∑[𝒏=1,∞] (-1)ⁿ⁻¹/𝒏²
     ◉ This is an alternating series.
     ◉ It converges by the Alternating Series Test.
     ◉ But now we check whether it converges absolutely.

● [5:03](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=303). Take the absolute value.
     ◉ Consider:
          ○ ∑[𝒏=1,∞] |(-1)ⁿ⁻¹/𝒏²|
     ◉ Since:
          ○ |(-1)ⁿ⁻¹| = 1
     ◉ Then:
          ○ |(-1)ⁿ⁻¹/𝒏²| = 1/𝒏²
     ◉ Therefore:
          ○ ∑[𝒏=1,∞] |(-1)ⁿ⁻¹/𝒏²| = ∑[𝒏=1,∞] 1/𝒏²

● [5:35](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=335). Use the 𝒑-Series Test.
     ◉ The series:
          ○ ∑[𝒏=1,∞] 1/𝒏²
     ◉ is a 𝒑-series with:
          ○ 𝒑 = 2
     ◉ Since:
          ○ 2 > 1
     ◉ Then:
          ○ ∑[𝒏=1,∞] 1/𝒏² converges.

● [6:01](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=361). Conclusion.
     ◉ Since:
          ○ ∑[𝒏=1,∞] |(-1)ⁿ⁻¹/𝒏²| converges,
     ◉ Then:
          ○ ∑[𝒏=1,∞] (-1)ⁿ⁻¹/𝒏² is absolutely convergent.
     ◉ Important:
          ○ we do not only say “convergent.”
          ○ we say “absolutely convergent,” because the absolute value series converges.






2  - Ｃｏｎｄｉｔｉｏｎａｌ　Ｃｏｎｖｅｒｇｅｎｃｅ

● [📷image](../img/Calculus 2 Lecture 9.6/[7-19]-01.png)

● [7:19](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=439). 🧩 Example — Conditional convergence: ∑[𝒏=1,∞] (-1)ⁿ⁻¹/𝒏
     ◉ This is the alternating harmonic series.
     ◉ We already know:
          ○ it converges by the Alternating Series Test.

● [8:24](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=504). Check ordinary convergence.
     ◉ The series is alternating.
     ◉ Positive part:
          ○ 𝒂ₙ = 1/𝒏
     ◉ Check the limit:
          ○ limₙ→∞ 1/𝒏 = 0
     ◉ Check decreasing:
          ○ 1/(𝒏 + 1) ≤ 1/𝒏
     ◉ Therefore, by the Alternating Series Test:
          ○ ∑[𝒏=1,∞] (-1)ⁿ⁻¹/𝒏 converges.
     ◉ Important:
          ○ this proves ordinary convergence,
               ■ not absolute convergence.

● [9:10](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=550). Check absolute convergence.
     ◉ Take the absolute value:
          ○ ∑[𝒏=1,∞] |(-1)ⁿ⁻¹/𝒏|
     ◉ Since:
          ○ |(-1)ⁿ⁻¹| = 1
     ◉ Then:
          ○ ∑[𝒏=1,∞] |(-1)ⁿ⁻¹/𝒏| = ∑[𝒏=1,∞] 1/𝒏

● [10:13](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=613). Harmonic Series.
     ◉ The series:
          ○ ∑[𝒏=1,∞] 1/𝒏
     ◉ is the harmonic series.
     ◉ The harmonic series diverges.
     ◉ Therefore:
          ○ ∑[𝒏=1,∞] |(-1)ⁿ⁻¹/𝒏| diverges.

● [10:48](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=648). Important conclusion.
     ◉ The original alternating harmonic series converges:
          ○ ∑[𝒏=1,∞] (-1)ⁿ⁻¹/𝒏 converges.
     ◉ But its absolute value series diverges:
          ○ ∑[𝒏=1,∞] |(-1)ⁿ⁻¹/𝒏| diverges.
     ◉ Therefore:
          ○ the original series is not absolutely convergent.

● [12:10](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=730). **Definition of conditional convergence.**
     ◉ i̲f̲ the original series ∑ 𝒂ₙ converges, a̲n̲d̲ the absolute value series ∑ |𝒂ₙ| diverges,
          ○ t̲h̲e̲n̲ the series ∑ 𝒂ₙ is conditionally convergent.
     ◉ Symbolically:
          ○ ∑ 𝒂ₙ converges
          ○ but ∑ |𝒂ₙ| diverges
     ◉ Then:
          ○ ∑ 𝒂ₙ is conditionally convergent.

● [13:49](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=829). Conditional convergence for the alternating harmonic series.
     ◉ Since:
          ○ ∑[𝒏=1,∞] (-1)ⁿ⁻¹/𝒏 converges,
     ◉ But:
          ○ ∑[𝒏=1,∞] |(-1)ⁿ⁻¹/𝒏| = ∑[𝒏=1,∞] 1/𝒏 diverges,
     ◉ Then:
          ○ ∑[𝒏=1,∞] (-1)ⁿ⁻¹/𝒏 is conditionally convergent.

● [15:15](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=915). Absolute convergence is stronger than convergence.
     ◉ Absolute convergence is stronger than ordinary convergence.
     ◉ i̲f̲ a series is absolutely convergent,
          ○ t̲h̲e̲n̲ it is definitely convergent.
     ◉ However:
          ○ a series can converge without being absolutely convergent.
     ◉ That case is called:
          ○ conditional convergence.

● N̲O̲T̲E̲ — Three possible outcomes.
     ◉ Divergent:
          ○ the series does not converge.
     ◉ Conditionally convergent:
          ○ ∑ 𝒂ₙ converges,
          ○ but ∑ |𝒂ₙ| diverges.
     ◉ Absolutely convergent:
          ○ ∑ |𝒂ₙ| converges,
          ○ so ∑ 𝒂ₙ also converges.
     ◉ Conceptual hierarchy:
          ○ absolute convergence is the strongest form of convergence.
          ○ conditional convergence is still convergence,
               ■ but it depends on sign cancellation.
          ○ divergence means there is no convergence.





 1.3 - Ａｂｓｏｌｕｔｅ　Ｃｏｎｖｅｒｇｅｎｃｅ　Ｅｘａｍｐｌｅ　ｗｉｔｈ　Ｓｉｎｅ

● [📷image](../img/Calculus 2 Lecture 9.6/[16-45]-01.png)

● [16:45](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1005). 🧩 Example — Absolute convergence example: ∑[𝒏=1,∞] sin(2𝒏)/𝒏².
     ◉ Given series:
          ○ ∑[𝒏=1,∞] sin(2𝒏)/𝒏²
     ◉ First observations:
          ○ it is not always positive.
          ○ it is not alternating in the regular sense.
          ○ sin(2𝒏) oscillates between -1 and 1.
     ◉ Therefore:
          ○ the Alternating Series Test is not appropriate.
          ○ ordinary Comparison Tests cannot be used directly because the terms are not always positive.

● [17:08](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1028). Divergence Test.
     ◉ Check:
          ○ limₙ→∞ sin(2𝒏)/𝒏²
     ◉ Since:
          ○ -1 ≤ sin(2𝒏) ≤ 1
     ◉ And:
          ○ 𝒏² → ∞
     ◉ Then:
          ○ sin(2𝒏)/𝒏² → 0
     ◉ Therefore:
          ○ the Divergence Test is inconclusive.

● [18:25](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1105). Take the absolute value.
     ◉ Consider:
          ○ ∑[𝒏=1,∞] |sin(2𝒏)/𝒏²|
     ◉ Since:
          ○ |sin(2𝒏)/𝒏²| = |sin(2𝒏)|/𝒏²
     ◉ And:
          ○ 0 ≤ |sin(2𝒏)| ≤ 1
     ◉ Then:
          ○ 0 ≤ |sin(2𝒏)|/𝒏² ≤ 1/𝒏²

● [20:00](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1200). Use Direct Comparison.
     ◉ We have:
          ○ 0 ≤ |sin(2𝒏)|/𝒏² ≤ 1/𝒏²
     ◉ The comparison series is:
          ○ ∑[𝒏=1,∞] 1/𝒏²
     ◉ This is a 𝒑-series with:
          ○ 𝒑 = 2
     ◉ Since:
          ○ 2 > 1
     ◉ Then:
          ○ ∑[𝒏=1,∞] 1/𝒏² converges.

● [21:10](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1270). Conclusion by Comparison Test.
     ◉ Since:
          ○ 0 ≤ |sin(2𝒏)|/𝒏² ≤ 1/𝒏²
     ◉ And:
          ○ ∑[𝒏=1,∞] 1/𝒏² converges,
     ◉ Then:
          ○ ∑[𝒏=1,∞] |sin(2𝒏)|/𝒏² converges.

● [22:10](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1330). Final conclusion.
     ◉ Since the absolute value series converges:
          ○ ∑[𝒏=1,∞] |sin(2𝒏)/𝒏²| converges,
     ◉ Therefore:
          ○ ∑[𝒏=1,∞] sin(2𝒏)/𝒏² is absolutely convergent.
     ◉ Important:
          ○ we used absolute convergence because the original series was not always positive and not regularly alternating.





3 -Ｔｈｅ　Ｒａｔｉｏ　Ｔｅｓｔ


● [📷image](../img/Calculus 2 Lecture 9.6/[25-56]-01.png)

● [25:56](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1556). The Ratio Test.
     ◉ The Ratio Test compares:
          ○ the next term 𝒂ₙ₊₁
          ○ with the current term 𝒂ₙ.
     ◉ Main expression:
          ○ limₙ→∞ |𝒂ₙ₊₁/𝒂ₙ|

● [26:24](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1584). Structure of the Ratio Test.
     ◉ Compute:
          ○ 𝑳 = limₙ→∞ |𝒂ₙ₊₁/𝒂ₙ|
     ◉ Important:
          ○ 𝒂ₙ₊₁ goes on top.
          ○ 𝒂ₙ goes on the bottom.
     ◉ Be careful:
          ○ do not invert the ratio.

● [28:15](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1695). Ratio Test  limₙ→∞ |𝒂ₙ₊₁/𝒂ₙ| = 𝑳 outcomes.
     ◉ i̲f̲  𝑳 < 1
          ○ t̲h̲e̲n̲ the series is absolutely convergent.
     ◉  i̲f̲  𝑳 > 1
          ○ t̲h̲e̲n̲ the series diverges.
     ◉  i̲f̲  𝑳 = 1
          ○ t̲h̲e̲n̲ the test is inconclusive.

● N̲O̲T̲E̲ — Why the Ratio Test is powerful.
     ◉ The Ratio Test includes absolute values.
     ◉ Therefore:
          ○ it can prove absolute convergence.
     ◉ It is especially useful for:
          ○ factorials.
          ○ powers involving 𝒏.
          ○ expressions where 𝒂ₙ₊₁/𝒂ₙ simplifies nicely.

● N̲O̲T̲E̲ — Ratio Test versus Divergence Test.
     ◉ Usually, we first check the Divergence Test.
     ◉ But with factorials or complicated powers,
          ○ the Divergence Test may be awkward.
     ◉ The Ratio Test can often detect:
          ○ absolute convergence,
          ○ or divergence,
          ○ without needing a separate Divergence Test first.
     ◉ If the Ratio Test gives 𝑳 = 1,
          ○ then we must try another test.






3.1 - Ｒａｔｉｏ　Ｔｅｓｔ　Ｅｘａｍｐｌｅ　１


● [📷image](../img/Calculus 2 Lecture 9.6/[30-00]-01.png)

● [30:00](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1800). 🧩 Example 1 — Ratio test: ∑[𝒏=1,∞] (-1)ⁿ⁻¹(𝒏² + 1)/2ⁿ.
     ◉ It is alternating because of:
          ○ (-1)ⁿ⁻¹
     ◉ But:
          ○ the Ratio Test can show absolute convergence,
               ■ which is stronger than ordinary convergence.

● [33:00](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1980). Set up the Ratio Test.
     ◉ Positive/absolute term:
          ○ |𝒂ₙ| = (𝒏² + 1)/2ⁿ
     ◉ Next term:
          ○ |𝒂ₙ₊₁| = ((𝒏 + 1)² + 1)/2ⁿ⁺¹
     ◉ Ratio:
          ○ |𝒂ₙ₊₁/𝒂ₙ|
          ○ = [((𝒏 + 1)² + 1)/2ⁿ⁺¹] / [(𝒏² + 1)/2ⁿ]

● [36:16](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=2176). Simplify the ratio.
     ◉ [36:42](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=2202). Discussion about when the absolute value can be removed
     ◉ Reciprocate and multiply:
          ○ [((𝒏 + 1)² + 1)/2ⁿ⁺¹] ⋅ [2ⁿ/(𝒏² + 1)]
     ◉ Since:
          ○ 2ⁿ⁺¹ = 2ⁿ ⋅ 2
     ◉ Then:
          ○ 2ⁿ/2ⁿ⁺¹ = 1/2
     ◉ So the ratio becomes:
          ○ ((𝒏 + 1)² + 1)/(2(𝒏² + 1))

● [39:00](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=2340). Evaluate the limit.
     ◉ Expand:
          ○ (𝒏 + 1)² + 1 = 𝒏² + 2𝒏 + 2
     ◉ Therefore:
          ○ 𝑳 = limₙ→∞ (𝒏² + 2𝒏 + 2)/(2𝒏² + 2)
     ◉ Compare leading terms:
          ○ 𝑳 = 1/2

● [39:43](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=2383). Conclusion for Example 1.
     ◉ Since:
          ○ 𝑳 = 1/2
     ◉ And:
          ○ 1/2 < 1
     ◉ By the Ratio Test:
          ○ ∑[𝒏=1,∞] (-1)ⁿ⁻¹(𝒏² + 1)/2ⁿ is absolutely convergent.






3.2 - Ｒａｔｉｏ　Ｔｅｓｔ　Ｅｘａｍｐｌｅ　２

● [📷image-1](../img/Calculus 2 Lecture 9.6/[43-10]-01.png) [📷image-2](../img/Calculus 2 Lecture 9.6/[43-10]-02.png)

● [43:10](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=2590). 🧩 Example 2 — Ratio test: ∑[𝒏=1,∞] 𝒏!/𝒏ⁿ.
     ◉ This is not:
          ○ geometric,
          ○ a 𝒑-series,
          ○ telescoping.
     ◉ The factorial suggests:
          ○ use the Ratio Test.

● [44:41](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=2681). Set up the Ratio Test.
     ◉ Let:
          ○ 𝒂ₙ = 𝒏!/𝒏ⁿ
     ◉ Then:
          ○ 𝒂ₙ₊₁ = (𝒏 + 1)!/(𝒏 + 1)ⁿ⁺¹
     ◉ Compute:
          ○ 𝑳 = limₙ→∞ |𝒂ₙ₊₁/𝒂ₙ|

● [45:46](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=2746). Build the ratio.
     ◉ Substitute:
          ○ 𝑳 = limₙ→∞ [(𝒏 + 1)!/(𝒏 + 1)ⁿ⁺¹] / [𝒏!/𝒏ⁿ]
     ◉ Reciprocate and multiply:
          ○ 𝑳 = limₙ→∞ [(𝒏 + 1)!/(𝒏 + 1)ⁿ⁺¹] ⋅ [𝒏ⁿ/𝒏!]

● [48:31](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=2911). Factorial simplification.
     ◉ Fundamental property:
          ○ (𝒏 + 1)! = (𝒏 + 1) ⋅ 𝒏!
     ◉ Substitute:
          ○ [(𝒏 + 1) ⋅ 𝒏! ⋅ 𝒏ⁿ]/[(𝒏 + 1)ⁿ⁺¹ ⋅ 𝒏!]
     ◉ Cancel:
          ○ 𝒏!
     ◉ Then:
          ○ [(𝒏 + 1)𝒏ⁿ]/(𝒏 + 1)ⁿ⁺¹

● [50:40](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3040). Exponent manipulation.
     ◉ Since:
          ○ (𝒏 + 1)ⁿ⁺¹ = (𝒏 + 1)ⁿ ⋅ (𝒏 + 1)
     ◉ Cancel:
          ○ 𝒏 + 1
     ◉ We get:
          ○ 𝑳 = limₙ→∞ 𝒏ⁿ/(𝒏 + 1)ⁿ
     ◉ Rewrite:
          ○ 𝑳 = limₙ→∞ [𝒏/(𝒏 + 1)]ⁿ

● [50:26](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3026). Special exponential limit.
     ◉ We reached:
          ○ 𝑳 = limₙ→∞ [𝒏/(𝒏 + 1)]ⁿ
     ◉ Direct substitution gives:
          ○ [𝒏/(𝒏 + 1)]ⁿ → 1^∞
     ◉ This is an indeterminate form:
          ○ 1^∞
     ◉ Rewrite the fraction:
          ○ 𝒏/(𝒏 + 1) = 1 / [(𝒏 + 1)/𝒏]
     ◉ Therefore:
          ○ [𝒏/(𝒏 + 1)]ⁿ = [1 / ((𝒏 + 1)/𝒏)]ⁿ
          ○ = 1 / [((𝒏 + 1)/𝒏)]ⁿ
     ◉ Since:
          ○ (𝒏 + 1)/𝒏 = 1 + 1/𝒏
     ◉ Then:
          ○ [𝒏/(𝒏 + 1)]ⁿ = 1 / (1 + 1/𝒏)ⁿ

● N̲O̲T̲E̲: Evaluating the classic exponential limit.
     ◉ We know the classic limit:
          ○ limₙ→∞ (1 + 1/𝒏)ⁿ = 𝒆
     ◉ Therefore:
          ○ limₙ→∞ 1 / (1 + 1/𝒏)ⁿ = 1/𝒆
     ◉ So:
          ○ limₙ→∞ [𝒏/(𝒏 + 1)]ⁿ = 1/𝒆

● [52:30](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3150). Optional derivation of the classic limit.
     ◉ To justify:
          ○ limₙ→∞ (1 + 1/𝒏)ⁿ = 𝒆
     ◉ Rewrite using exponentials:
          ○ limₙ→∞ (1 + 1/𝒏)ⁿ
          ○ = 𝒆^[limₙ→∞    ln((1 + 1/𝒏)ⁿ)]
     ◉ Bring the exponent down:
          ○ = 𝒆^[limₙ→∞    𝒏 ln(1 + 1/𝒏)]
     ◉ Rewrite as a quotient:
          ○ 𝒏 ln(1 + 1/𝒏) = ln(1 + 1/𝒏)/(1/𝒏)
     ◉ This gives the indeterminate form:
          ○ 0/0
     ◉ Apply L'Hôpital's Rule:
          ○ limₙ→∞ ln(1 + 1/𝒏)/(1/𝒏)
          ○ = limₙ→∞ [(-1/𝒏²)/(1 + 1/𝒏)] / (-1/𝒏²)
          ○ = limₙ→∞ 1/(1 + 1/𝒏)
          ○ = 1
     ◉ Therefore:
          ○ limₙ→∞ (1 + 1/𝒏)ⁿ = 𝒆¹ = 𝒆
     ◉ Hence:
          ○ limₙ→∞ [𝒏/(𝒏 + 1)]ⁿ = 1/𝒆

● [55:13](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3313). Conclusion for Example 2.
     ◉ The Ratio Test limit is:
          ○ 𝑳 = 1/𝒆
     ◉ Since:
          ○ 1/𝒆 < 1
     ◉ By the Ratio Test:
          ○ ∑[𝒏=1,∞] 𝒏!/𝒏ⁿ converges absolutely.
     ◉ Since the terms are already positive:
          ○ absolute convergence is just convergence here,
          ○ but the Ratio Test still proves convergence.





3.3 - Ｒａｔｉｏ　Ｔｅｓｔ　Ｅｘａｍｐｌｅ　３

● [📷image-1](../img/Calculus 2 Lecture 9.6/[59-52]-01.png) [📷image-2](../img/Calculus 2 Lecture 9.6/[59-52]-02.png)

● [59:52](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3592). 🧩 Example 3 — Ratio test: ∑[𝒏=1,∞] (-5)ⁿ⁻¹/(𝒏² ⋅ 3ⁿ).
     ◉ Because of the negative base:
          ○ the signs alternate in some form.
     ◉ The Ratio Test is a good choice because:
          ○ there are exponential powers,
          ○ and the absolute value handles the negative signs.

● [1:00:54](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3654). Set up the Ratio Test.
     ◉ Let:
          ○ 𝒂ₙ = (-5)ⁿ⁻¹/(𝒏² ⋅ 3ⁿ)
     ◉ Then:
          ○ 𝒂ₙ₊₁ = (-5)ⁿ/((𝒏 + 1)² ⋅ 3ⁿ⁺¹)
     ◉ Compute:
          ○ 𝑳 = limₙ→∞ |𝒂ₙ₊₁/𝒂ₙ|

● [1:02:18](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3738). Handle the negative base.
     ◉ Inside the absolute value:
          ○ |(-5)ⁿ| = 5ⁿ
          ○ |(-5)ⁿ⁻¹| = 5ⁿ⁻¹
     ◉ Important:
          ○ the absolute value removes the negative sign,
          ○ but it does not remove the factor 5ⁿ.

● [1:02:00](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3720). Simplify the ratio.
     ◉ Ratio:
          ○ [5ⁿ/((𝒏 + 1)² ⋅ 3ⁿ⁺¹)] ⋅ [(𝒏² ⋅ 3ⁿ)/5ⁿ⁻¹]
     ◉ Simplify powers:
          ○ 5ⁿ/5ⁿ⁻¹ = 5
          ○ 3ⁿ/3ⁿ⁺¹ = 1/3
     ◉ Therefore:
          ○ 𝑳 = limₙ→∞ (5/3) ⋅ [𝒏²/(𝒏 + 1)²]

● [1:04:39](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3879). Evaluate the limit.
     ◉ Since:
          ○ limₙ→∞ 𝒏/(𝒏 + 1) = 1
     ◉ Then:
          ○ limₙ→∞ [𝒏/(𝒏 + 1)]² = 1
     ◉ Therefore:
          ○ 𝑳 = (5/3) ⋅ 1 = 5/3

● [1:05:03](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3903). Conclusion for Example 3.
     ◉ Since:
          ○ 𝑳 = 5/3
     ◉ And:
          ○ 5/3 > 1
     ◉ By the Ratio Test:
          ○ ∑[𝒏=1,∞] (-5)ⁿ⁻¹/(𝒏² ⋅ 3ⁿ) diverges.
     ◉ Important:
          ○ say “diverges,” not “absolutely diverges.”
          ○ there is no category called absolutely divergent.

● N̲O̲T̲E̲ — Correct terminology.
     ◉ The main categories are:
          ○ absolutely convergent,
          ○ conditionally convergent,
          ○ divergent.
     ◉ Do not say:
          ○ absolutely divergent.
     ◉ If the Ratio Test gives 𝑳 > 1,
          ○ the original series diverges.





4 - Ｔｈｅ　Ｒｏｏｔ　Ｔｅｓｔ

● [📷image](../img/Calculus 2 Lecture 9.6/[1-07-08]-01.png)

● [1:07:08](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4028). The Root Test.
     ◉ The Root Test is useful when the terms contain powers of 𝒏.
     ◉ It is especially useful when the whole expression is raised to the 𝒏-th power.
     ◉ It often overlaps with the Ratio Test:
          ○ Ratio Test works well for factorials and 𝒏-th powers.
          ○ Root Test works especially well for 𝒏-th powers.
     ◉ Avoid using the Root Test for factorials:
          ○ Ratio Test is usually better there.

● [1:09:14](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4154). Definition of the Root Test.
     ◉ Compute:
          ○ 𝑳 = limₙ→∞ ⁿ√|𝒂ₙ|
     ◉ There is no ratio here.
     ◉ Unlike the Ratio Test:
          ○ we do not form 𝒂ₙ₊₁/𝒂ₙ.
     ◉ We take:
          ○ the absolute value of 𝒂ₙ,
          ○ then the 𝒏-th root.

● [1:09:45](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4185). Root Test  limₙ→∞ ⁿ√|𝒂ₙ| = 𝑳 outcomes.
     ◉ i̲f̲  𝑳 < 1
          ○ t̲h̲e̲n̲ the series is absolutely convergent.
     ◉ i̲f̲  𝑳 > 1
          ○ t̲h̲e̲n̲ the series diverges.
     ◉ i̲f̲  𝑳 = 1
          ○ t̲h̲e̲n̲ the test is inconclusive.





4.1 - Ｒｏｏｔ　Ｔｅｓｔ　Ｅｘａｍｐｌｅ


● [📷image](../img/Calculus 2 Lecture 9.6/[1-11-45]-01.png)

● [1:11:45](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4305). 🧩 Example —  Root test: ∑[𝒏=1,∞] (-1)ⁿ 2ⁿ⁺³/(𝒏 + 1)ⁿ.
     ◉ It is alternating because of:
          ○ (-1)ⁿ
     ◉ But:
          ○ showing decreasing behavior directly may not be convenient.
     ◉ Since the expression contains 𝒏-th powers,
          ○ the Root Test is a natural choice.

● [1:13:32](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4412). Set up the Root Test.
     ◉ Compute:
          ○ 𝑳 = limₙ→∞ ⁿ√|(-1)ⁿ 2ⁿ⁺³/(𝒏 + 1)ⁿ|
     ◉ The absolute value removes:
          ○ (-1)ⁿ
     ◉ Therefore:
          ○ 𝑳 = limₙ→∞ ⁿ√(2ⁿ⁺³/(𝒏 + 1)ⁿ)

● [1:14:51](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4491). Separate constants and powers.
     ◉ Rewrite:
          ○ 2ⁿ⁺³ = 2³ ⋅ 2ⁿ
     ◉ Then:
          ○ 2ⁿ⁺³/(𝒏 + 1)ⁿ = 2³ ⋅ [2ⁿ/(𝒏 + 1)ⁿ]
     ◉ So:
          ○ 2ⁿ/(𝒏 + 1)ⁿ = [2/(𝒏 + 1)]ⁿ

● [1:16:13](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4573). Apply the 𝒏-th root.
     ◉ We have:
          ○ ⁿ√(2³ ⋅ [2/(𝒏 + 1)]ⁿ)
     ◉ Separate:
          ○ ⁿ√(2³) ⋅ ⁿ√([2/(𝒏 + 1)]ⁿ)
     ◉ Then:
          ○ ⁿ√(2³) = (2³)¹ᐟⁿ
          ○ ⁿ√([2/(𝒏 + 1)]ⁿ) = 2/(𝒏 + 1)

● [1:17:24](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4644). Evaluate the limit.
     ◉ Now:
          ○ 𝑳 = limₙ→∞ (2³)¹ᐟⁿ ⋅ 2/(𝒏 + 1)
     ◉ Since:
          ○ (2³)¹ᐟⁿ → 1
          ○ 2/(𝒏 + 1) → 0
     ◉ Therefore:
          ○ 𝑳 = 1 ⋅ 0 = 0

● [1:17:48](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4668). Conclusion for the Root Test example.
     ◉ Since:
          ○ 𝑳 = 0
     ◉ And:
          ○ 0 < 1
     ◉ By the Root Test:
          ○ ∑[𝒏=1,∞] (-1)ⁿ 2ⁿ⁺³/(𝒏 + 1)ⁿ converges absolutely.






5  - Ｓｔｒａｔｅｇｉｃ　Ｓｕｍｍａｒｙ　ｏｆ　Ｓｅｒｉｅｓ　Ｔｅｓｔｓ


● [📷image-1](../img/Calculus 2 Lecture 9.6/[1-20-17]-01.png) [📷image-2](../img/Calculus 2 Lecture 9.6/[1-20-17]-02.png) [📷image-3](../img/Calculus 2 Lecture 9.6/[1-20-17]-03.png)

● [1:20:17](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4817). Summary of all series tests.
     ◉ Main purpose:
          ○ decide which test to try first.
     ◉ Strategy:
          ○ do not start with the hardest test.
          ○ look for the easiest recognizable structure.

● [1:20:55](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4855). ❶ — Divergence Test.
     ◉ Always check, when practical:
          ○ limₙ→∞ 𝒂ₙ
     ◉ i̲f̲ limₙ→∞ 𝒂ₙ ≠ 0
          ○ t̲h̲e̲n̲ ∑ 𝒂ₙ diverges.
     ◉ i̲f̲ limₙ→∞ 𝒂ₙ = 0
          ○ t̲h̲e̲n̲ the test is inconclusive.
          ○ continue with another test.

● [1:21:40](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4900). ❷ — By type.
     ◉ Geometric Series.
          ○ Geometric form:
               ■ ∑ 𝒂𝒓ⁿ
          ○ i̲f̲ |𝒓| < 1
               ■ It converges
          ○ i̲f̲ |𝒓| ≥ 1
               ■ It diverges 
          ○ i̲f̲ it converges, 
               ■ t̲h̲e̲n̲ the sum is:
                    ▣ 𝒂/(1 - 𝒓)
          ○ Important:
               ■ check convergence before using the sum formula.
     ◉ Telescoping Series.
          ○ Telescoping series often require:
               ■ partial fractions.
          ○ Main idea:
               ■ rewrite the terms so that many terms cancel.
          ○ Then:
               ■ find a formula for the partial sum 𝑺ₙ.
          ○ Finally:
               ■ compute limₙ→∞ 𝑺ₙ.
     ◉ 𝒑-Series.
          ○ 𝒑-series form:
               ■ ∑[𝒏=1,∞] 1/𝒏ᵖ
          ○ i̲f̲ 𝒑 > 1
               ■ It converges
          ○ i̲f̲ 𝒑 ≤ 1
               ■ It diverges
          ○ i̲f̲ 𝒑 = 1 
               ■ gives the harmonic series,
                    ▣ which diverges.

● [1:27:10](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=5230). ❸ — Integral Test.
     ◉ Use the Integral Test when the terms can be modeled by a function:
          ○ 𝒂ₙ = 𝒇(𝒏)
     ◉ The function must be:
          ○ positive,
          ○ continuous,
          ○ decreasing.
     ◉ This only needs to hold from some point onward:
          ○ [𝑵,∞)
     ◉ Then evaluate:
          ○ ∫[𝑵,∞] 𝒇(𝒙) ⋅ 𝒅𝑥
          ○ Meaning of 𝑵:
               ■ 𝑵 is the point from which the final tail of the series is tested.
               ■ the first finitely many terms do not affect convergence or divergence.
               ■ only the infinite tail determines the final behavior.
     ◉ i̲f̲ the integral converges:
          ○ t̲h̲e̲n̲ the series converges.
     ◉ i̲f̲ the integral diverges:
          ○ t̲h̲e̲n̲ the series diverges.

● [1:29:55](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=5395). ❹ — Comparison Tests.
     ◉ Use Comparison Tests when:
          ○ all terms are positive,
          ○ and the series behaves like a known series.
     ◉ Common known series:
          ○ 𝒑-series.
          ○ geometric series.
          ○ harmonic series.
     ◉ Direct Comparison Test.
          ○ To prove convergence:
               ■ compare with a bigger convergent series.
          ○ Symbolically:
               ■ 0 ≤ 𝒂ₙ ≤ 𝒃ₙ
               ■ ∑ 𝒃ₙ converges
               ■ therefore, ∑ 𝒂ₙ converges.
          ○ To prove divergence:
               ■ compare with a smaller divergent series.
          ○ Symbolically:
               ■ 0 ≤ 𝒃ₙ ≤ 𝒂ₙ
               ■ ∑ 𝒃ₙ diverges
               ■ therefore, ∑ 𝒂ₙ diverges.
     ◉ Limit Comparison Test.
          ○ Use when two positive-term series have similar end behavior.
          ○ Compute:
               ■ limₙ→∞ 𝒂ₙ/𝒃ₙ
          ○ i̲f̲ the limit exists and is a finite positive number: 0 < 𝑳 < ∞
               ■ t̲h̲e̲n̲ both series have the same convergence behavior.
                    ▣ they both converge or both diverge.

● [1:34:21](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=5661). ❺ — Alternating Series Test.
     ◉ Use when the series has the form:
          ○ ∑ (-1)ⁿ𝒂ₙ
          ○ or ∑ (-1)ⁿ⁻¹𝒂ₙ
     ◉ Where:
          ○ 𝒂ₙ > 0
     ◉ Check two conditions:
          ○ limₙ→∞ 𝒂ₙ = 0
          ○ 𝒂ₙ₊₁ ≤ 𝒂ₙ
     ◉ i̲f̲ both conditions hold:
          ○ t̲h̲e̲n̲ the alternating series converges.
     ◉ Important:
          ○ this proves ordinary convergence,
          ○ not necessarily absolute convergence.

● [1:36:03](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=5763). ❻ — Ratio Test.
     ◉ Try the Ratio Test for:
          ○ factorials.
          ○ 𝒏-th powers.
     ◉ Compute:
          ○ 𝑳 = limₙ→∞ |𝒂ₙ₊₁/𝒂ₙ|
     ◉ i̲f̲
          ○ 𝑳 < 1
               ■ t̲h̲e̲n̲ absolutely convergent.
          ○ 𝑳 > 1
               ■ t̲h̲e̲n̲ divergent.
          ○ 𝑳 = 1
               ■ t̲h̲e̲n̲ inconclusive.

● [1:37:09](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=5829). ❼ — Root Test.
     ◉ Try the Root Test for:
          ○ 𝒏-th powers.
     ◉ Compute:
          ○ 𝑳 = limₙ→∞ ⁿ√|𝒂ₙ|
     ◉ i̲f̲
          ○ 𝑳 < 1
               ■ t̲h̲e̲n̲ absolutely convergent.
          ○ 𝑳 > 1
               ■ t̲h̲e̲n̲ divergent.
          ○ 𝑳 = 1
               ■ t̲h̲e̲n̲ inconclusive.






6 - Ｑｕｉｃｋ　Ｉｄｅｎｔｉｆｉｃａｔｉｏｎ　Ｇｕｉｄｅ


● [📷image-1](../img/Calculus 2 Lecture 9.6/[1-40-19]-01.png) [📷image-2](../img/Calculus 2 Lecture 9.6/[1-40-19]-02.png)

● [1:40:19](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=6019). ❶ Always start by looking for immediate divergence:
     ◉ if limₙ→∞ 𝒂ₙ ≠ 0,
          ○ stop.
          ○ the series diverges.
     ◉ ⭐ Model Example:
          ○ ∑[𝒏=1,∞] (2𝒏 - 1)/(3𝒏 - 1)
     ◉ Check the general term:
          ○ limₙ→∞ (2𝒏 - 1)/(3𝒏 - 1) = 2/3
     ◉ Since:
          ○ 2/3 ≠ 0
     ◉ Therefore:
          ○ the series diverges by the Divergence Test.

● [1:40:57](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=6057). ❷ Split sums when possible.
     ◉ If a series is written as a sum or difference of recognizable series,
          ○ split it.
     ◉ ⭐ Model Example:
          ○ ∑[𝒏=1,∞] [2/3ⁿ - 1/(𝒏(𝒏 + 1))]
     ◉ Split:
          ○ ∑[𝒏=1,∞] 2/3ⁿ - ∑[𝒏=1,∞] 1/(𝒏(𝒏 + 1))
     ◉ First part:
          ○ ∑[𝒏=1,∞] 2/3ⁿ
          ○ = ∑[𝒏=1,∞] 2(1/3)ⁿ
          ○ geometric series with |𝒓| = 1/3 < 1
          ○ therefore, it converges.
     ◉ Second part:
          ○ ∑[𝒏=1,∞] 1/(𝒏(𝒏 + 1))
          ○ telescoping series.
     ◉ Therefore:
          ○ analyze each part separately.
     ◉ The whole series converges only if all parts converge.

● [1:41:36](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=6096). ❸ Look for 𝒑-Series.
     ◉ If the expression can be rewritten as:
          ○ 1/𝒏ᵖ
     ◉ Then:
          ○ use the 𝒑-Series Test.
     ◉ ⭐ Model Example:
          ○ ∑[𝒏=1,∞] (1/𝒏)ᵉ
     ◉ Rewrite:
          ○ (1/𝒏)ᵉ = 1/𝒏ᵉ
     ◉ This is a 𝒑-series with:
          ○ 𝒑 = 𝒆
     ◉ Since:
          ○ 𝒆 > 1
     ◉ Therefore:
          ○ ∑[𝒏=1,∞] 1/𝒏ᵉ converges.

● [1:42:05](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=6125). ❹ Integral Test versus Comparison.
     ◉ Use the Integral Test when:
          ○ the function is easy to integrate,
          ○ and positive, continuous, decreasing.
     ◉ ⭐ Model Example:
          ○ ∑[𝒏=3,∞] 1/(𝒏√ln(𝒏))
     ◉ Model with:
          ○ 𝒇(𝒙) = 1/(𝒙√ln(𝒙))
     ◉ This suggests the Integral Test because:
          ○ the function is positive for 𝒙 ≥ 3.
          ○ it is continuous for 𝒙 ≥ 3.
          ○ it is decreasing for large 𝒙.
          ○ the integral is manageable by substitution.
     ◉ Integral idea:
          ○ let 𝒖 = ln(𝒙)
          ○ then 𝒅𝒖 = 1/𝒙 ⋅ 𝒅𝑥
     ◉ Therefore:
          ○ use the Integral Test.

● [1:42:38](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=6158). ❺ Direct Comparison for single dominant terms.
     ◉ If the expression has simple single-term behavior,
          ○ Direct Comparison may be easiest.
     ◉ ⭐ Model Example:
          ○ ∑[𝒏=3,∞] ln(𝒏)/𝒏²
     ◉ Single-term comparison idea:
          ○ ln(𝒏) grows slower than √𝒏.
     ◉ So for large 𝒏:
          ○ ln(𝒏) < √𝒏
     ◉ Then:
          ○ ln(𝒏)/𝒏² < √𝒏/𝒏²
     ◉ Simplify:
          ○ √𝒏/𝒏² = 1/𝒏³ᐟ²
     ◉ Since:
          ○ ∑[𝒏=3,∞] 1/𝒏³ᐟ² is a 𝒑-series with 𝒑 = 3/2 > 1
     ◉ Therefore:
          ○ ∑[𝒏=3,∞] 1/𝒏³ᐟ² converges.
     ◉ By Direct Comparison:
          ○ ∑[𝒏=3,∞] ln(𝒏)/𝒏² converges.

● [1:43:23](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=6203). ❻ Limit Comparison for multiple-term expressions.
     ◉ If the numerator or denominator has several terms,
          ○ Direct Comparison may be awkward.
     ◉ Then:
          ○ use leading terms.
     ◉ ⭐ Model Example:
          ○ ∑[𝒏=1,∞] √(𝒏³ - 2)/(𝒏⁴ + 3𝒏² + 1)
     ◉ End behavior:
          ○ √(𝒏³ - 2) behaves like √𝒏³ = 𝒏³ᐟ²
          ○ 𝒏⁴ + 3𝒏² + 1 behaves like 𝒏⁴
     ◉ Therefore:
          ○ √(𝒏³ - 2)/(𝒏⁴ + 3𝒏² + 1) behaves like 𝒏³ᐟ²/𝒏⁴
     ◉ Simplify:
          ○ 𝒏³ᐟ²/𝒏⁴ = 1/𝒏⁵ᐟ²
     ◉ Choose:
          ○ 𝒃ₙ = 1/𝒏⁵ᐟ²
     ◉ Then compute:
          ○ limₙ→∞ 𝒂ₙ/𝒃ₙ
     ◉ Since:
          ○ ∑[𝒏=1,∞] 1/𝒏⁵ᐟ² is a 𝒑-series with 𝒑 = 5/2 > 1
     ◉ Therefore:
          ○ use the Limit Comparison Test.
          ○ the given series converges if the comparison limit is finite and positive.

● [1:44:15](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=6255). ❼ Alternating series.
     ◉ If the series clearly has:
          ○ (-1)ⁿ
          ○ or (-1)ⁿ⁻¹
     ◉ Then:
          ○ try the Alternating Series Test.
     ◉ ⭐ Model Example:
          ○ ∑[𝒏=1,∞] (-1)ⁿ √𝒏/(𝒏² + 1)
     ◉ Positive part:
          ○ 𝒂ₙ = √𝒏/(𝒏² + 1)
     ◉ Check:
          ○ limₙ→∞ 𝒂ₙ = 0
     ◉ Reason:
          ○ √𝒏/(𝒏² + 1) behaves like √𝒏/𝒏² = 1/𝒏³ᐟ²
          ○ and 1/𝒏³ᐟ² → 0
     ◉ Then check decreasing:
          ○ 𝒂ₙ₊₁ ≤ 𝒂ₙ
          ○ or use 𝒇′(𝒙) < 0 for the related function.
     ◉ Therefore:
          ○ try the Alternating Series Test.

● [1:44:33](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=6273). ❽ Ratio Test or Root Test.
     ◉ Use these when:
          ○ other tests are not convenient,
          ○ the expression has factorials,
          ○ or 𝒏-th powers.
     ◉ ⭐ Model Example:
          ○ ∑[𝒏=1,∞] 𝒏/2ⁿ
     ◉ This is not directly geometric:
          ○ because of the extra factor 𝒏 in the numerator.
     ◉ (i) Use the Ratio Test:
          ○ 𝒂ₙ = 𝒏/2ⁿ
          ○ 𝒂ₙ₊₁ = (𝒏 + 1)/2ⁿ⁺¹
     ◉ Compute:
          ○ 𝑳 = limₙ→∞ |𝒂ₙ₊₁/𝒂ₙ|
          ○ = limₙ→∞ [(𝒏 + 1)/2ⁿ⁺¹] ⋅ [2ⁿ/𝒏]
          ○ = limₙ→∞ [(𝒏 + 1)/𝒏] ⋅ 1/2
          ○ = 1/2
     ◉ Since:
          ○ 𝑳 = 1/2 < 1
     ◉ Therefore:
          ○ ∑[𝒏=1,∞] 𝒏/2ⁿ converges by the Ratio Test.
     ◉ (ii) Root Test also works.
     ◉ Given:
          ○ ∑[𝒏=1,∞] 𝒏/2ⁿ
     ◉ Rewrite the numerator:
          ○ 𝒏 = 𝒏¹
          ○ 𝒏¹ = 𝒏ⁿᐟⁿ
          ○ 𝒏ⁿᐟⁿ = (𝒏¹ᐟⁿ)ⁿ
     ◉ Therefore:
          ○ 𝒏/2ⁿ = (𝒏¹ᐟⁿ)ⁿ/2ⁿ
          ○ = (𝒏¹ᐟⁿ/2)ⁿ
     ◉ Apply the Root Test:
          ○ 𝑳 = limₙ→∞ ⁿ√|𝒏/2ⁿ|
          ○ = limₙ→∞ ⁿ√[(𝒏¹ᐟⁿ/2)ⁿ]
          ○ = limₙ→∞ 𝒏¹ᐟⁿ/2
     ◉ Since:
          ○ limₙ→∞ 𝒏¹ᐟⁿ = 1
     ◉ Then:
          ○ 𝑳 = 1/2
     ◉ Since:
          ○ 𝑳 = 1/2 < 1
     ◉ Therefore:
          ○ ∑[𝒏=1,∞] 𝒏/2ⁿ converges by the Root Test.

● [1:45:12](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=6312). ❾ Strategy for trigonometric functions.
     ◉ If the series contains:
          ○ sin(𝒏),
          ○ cos(𝒏),
          ○ sin(2𝒏),
          ○ or similar oscillating terms,
     ◉ Then:
          ○ it may not be positive,
          ○ and may not alternate regularly.
     ◉ ⭐ Model Example:
          ○ ∑[𝒏=1,∞] sin(𝒏)/√(𝒏³ + 1)
     ◉ In that case:
          ○ try absolute value.
     ◉ Take:
          ○ |sin(𝒏)/√(𝒏³ + 1)|
          ○ = |sin(𝒏)|/√(𝒏³ + 1)
     ◉ Since:
          ○ |sin(𝒏)| ≤ 1
     ◉ Then:
          ○ |sin(𝒏)|/√(𝒏³ + 1) ≤ 1/√(𝒏³ + 1)
     ◉ End behavior:
          ○ 1/√(𝒏³ + 1) behaves like 1/𝒏³ᐟ²
     ◉ Since:
          ○ ∑[𝒏=1,∞] 1/𝒏³ᐟ² converges
     ◉ Then:
          ○ use absolute value plus comparison.
     ◉ Therefore:
          ○ the original series is absolutely convergent.

● N̲O̲T̲E̲ — Final strategy.
     ◉ Do not randomly choose a test.
     ◉ First identify the structure:
          ○ nonzero term limit ⇒ Divergence Test.
          ○ geometric form ⇒ Geometric Series Test.
          ○ telescoping cancellation ⇒ Telescoping Series.
          ○ 1/𝒏ᵖ form ⇒ 𝒑-Series.
          ○ positive continuous decreasing function ⇒ Integral Test.
          ○ positive terms like a known series ⇒ Comparison.
          ○ alternating signs ⇒ Alternating Series Test.
          ○ factorials ⇒ Ratio Test.
          ○ 𝒏-th powers ⇒ Root Test.
          ○ trig oscillation ⇒ absolute value plus comparison.






Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Absolute Convergence. Prof. Herbert Gross.
     ◉ [MIT 🌐](https://ocw.mit.edu/courses/res-18-006-calculus-revisited-single-variable-calculus-fall-2010/resources/lecture-3-absolute-convergence/)

● Ratio and Root Tests.
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/5-6-ratio-and-root-tests)