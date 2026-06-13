-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ９．５： Ｓｈｏｗｉｎｇ Ｃｏｎｖｅｒｇｅｎｃｅ Ｗｉｔｈ ｔｈｅ ▲ｌｔｅｒｎａｔｉｎｇ Ｓｅｒｉｅｓ Ｔｅｓｔ， Ｆｉｎｄｉｎｇ Ｅｒｒｏｒ ｏｆ Ｓｕｍｓ**----------------------------------





Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:00](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=0). Introduction to Alternating Series.
     ◉ Main idea:
          ○ an alternating series is a series whose sequential terms alternate signs.
          ○ the signs go:
               ■ positive, negative, positive, negative, ...
          ○ or:
               ■ negative, positive, negative, positive, ...




               

Ｉｎｔｒｏｄｕｃｔｉｏｎ　Ｅｘａｍｐｌｅ  1

● [📷image](../img/Calculus 2 Lecture 9.5/[1-00]-01.png)

● [1:00](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=60). 🧩 Example 1 — Definition of an alternating series. 
     ◉ Given series:
          ○ ∑[𝒏=1,∞] (-1)ⁿ⁻¹/𝒏
     ◉ Expand the first terms:
          ○ 1 - 1/2 + 1/3 - 1/4 + 1/5 - ...
     ◉ Key observation:
          ○ the signs alternate:
               ■ +, -, +, -, +, ...
          ○ therefore, this is an alternating series.

● Identifying the alternating factor.
     ◉ The factor that creates the sign change is:
          ○ (-1)ⁿ⁻¹
     ◉ If the series starts with a positive term,
          ○ we often use (-1)ⁿ⁻¹.
     ◉ If the series starts with a negative term,
          ○ we often use (-1)ⁿ.
     ◉ Key idea:
          ○ the (-1) factor controls the signs.
          ○ the rest of the expression gives the positive size of each term.

● [3:20](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=200). General structure of an alternating series.
     ◉ Any alternating series can usually be written as:
          ○ ∑[𝒏=1,∞] (-1)ⁿ⁻¹ ⋅ 𝒂ₙ
     ◉ Here:
          ○ (-1)ⁿ⁻¹ creates the alternating signs.
          ○ 𝒂ₙ represents the positive part of the terms.
     ◉ In this example:
          ○ 𝒂ₙ = 1/𝒏
     ◉ Therefore:
          ○ ∑[𝒏=1,∞] (-1)ⁿ⁻¹/𝒏 = ∑[𝒏=1,∞] (-1)ⁿ⁻¹ ⋅ 1/𝒏
     ◉ Important:
          ○ 𝒂ₙ itself is positive.
          ○ the alternating sign is not considered part of 𝒂ₙ.

● [4:17](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=257). Harmonic Series versus Alternating Harmonic Series.
     ◉ Harmonic Series:
          ○ ∑[𝒏=1,∞] 1/𝒏
          ○ = 1 + 1/2 + 1/3 + 1/4 + ...
          ○ diverges.
     ◉ Alternating Harmonic Series:
          ○ ∑[𝒏=1,∞] (-1)ⁿ⁻¹/𝒏
          ○ = 1 - 1/2 + 1/3 - 1/4 + ...
          ○ converges.
     ◉ Important:
          ○ adding alternating signs can change the convergence behavior.
          ○ the harmonic series diverges,
               ■ but the alternating harmonic series converges.






Ｉｎｔｒｏｄｕｃｔｉｏｎ　Ｅｘａｍｐｌｅ  2

● [📷image](../img/Calculus 2 Lecture 9.5/[5-15]-01.png)

● [5:15](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=315). 🧩 Example 2 — Alternating series ∑[𝒏=1,∞] (-1)ⁿ 𝒏²/(𝒏 + 1)!
     ◉ Expand the first terms:
          ○ -1/2! + 4/3! - 9/4! + 16/5! - ...
     ◉ Key observation:
          ○ the signs alternate:
               ■ -, +, -, +, ...
          ○ therefore, this is an alternating series.

● Identifying the alternating factor.
     ◉ The factor that creates the sign change is:
          ○ (-1)ⁿ
     ◉ Since the series starts with a negative term,
          ○ (-1)ⁿ is the natural alternating factor.
     ◉ The positive part of the terms is:
          ○ 𝒂ₙ = 𝒏²/(𝒏 + 1)!
     ◉ Therefore:
          ○ ∑[𝒏=1,∞] (-1)ⁿ 𝒏²/(𝒏 + 1)! = ∑[𝒏=1,∞] (-1)ⁿ ⋅ 𝒂ₙ

● General structure.
     ◉ This example has the form:
          ○ ∑[𝒏=1,∞] (-1)ⁿ ⋅ 𝒂ₙ
     ◉ Here:
          ○ (-1)ⁿ creates the alternating signs.
          ○ 𝒂ₙ represents the positive size of each term.
     ◉ In this example:
          ○ 𝒂ₙ = 𝒏²/(𝒏 + 1)!
     ◉ Important:
          ○ 𝒂ₙ itself is positive.
          ○ the alternating sign is not considered part of 𝒂ₙ.





               

Ａｌｔｅｒｎａｔｉｎｇ　Ｓｅｒｉｅｓ　Ｔｅｓｔ  (ＡＳＴ)

● [📷image](../img/Calculus 2 Lecture 9.5/[7-53]-01.png)

● [7:53](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=473). The Alternating Series Test.
     ◉ The Alternating Series Test applies to series of the form:
          ○ ∑[𝒏=1,∞] (-1)ⁿ⁻¹ ⋅ 𝒂ₙ
          ○ or ∑[𝒏=1,∞] (-1)ⁿ ⋅ 𝒂ₙ
     ◉ Where:
          ○ 𝒂ₙ > 0
     ◉ The test checks two things:
          ○ the positive terms 𝒂ₙ must be decreasing.
          ○ the positive terms 𝒂ₙ must approach 0.

● [9:24](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=564). Condition 1 — Decreasing sequence.
     ◉ The positive sequence must be decreasing:
          ○ 𝒂ₙ₊₁ ≤ 𝒂ₙ
     ◉ Meaning:
          ○ each next positive term is less than or equal to the previous one.
     ◉ This is important because:
          ○ the alternating partial sums move back and forth,
          ○ but the jumps get smaller and smaller.

● [10:30](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=630). Condition 2 — Limit of the positive terms.
     ◉ The positive terms must approach 0:
          ○ limₙ→∞ 𝒂ₙ = 0
     ◉ This is like the Divergence Test,
          ○ but applied to the positive part 𝒂ₙ.
     ◉ Important:
          ○ do not include (-1)ⁿ or (-1)ⁿ⁻¹ when checking this limit.
          ○ only use the positive part 𝒂ₙ.

● [11:26](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=686). Conclusion of the Alternating Series Test.
     ◉ i̲f̲  𝒂ₙ₊₁ ≤ 𝒂ₙ  a̲n̲d̲  limₙ→∞ 𝒂ₙ = 0
          ○ t̲h̲e̲n̲ the alternating series ∑ (-1)ⁿ⁻¹𝒂ₙ converges.
     ◉ In words:
          ○ if the positive terms decrease to 0,
               ■ then the alternating series converges.

● [11:26](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=686). Recap — How to use the Alternating Series Test.
     ◉ First, verify that the series is alternating.
          ○ the signs must alternate:
               ■ +, -, +, -, ...
               ■ or -, +, -, +, ...
          ○ this usually comes from:
               ■ (-1)ⁿ
               ■ or (-1)ⁿ⁻¹
     ◉ Then, separate the series into:
          ○ the alternating factor,
          ○ and the positive part 𝒂ₙ.
     ◉ General form:
          ○ ∑ (-1)ⁿ⁻¹𝒂ₙ
          ○ or ∑ (-1)ⁿ𝒂ₙ
     ◉ Important:
          ○ 𝒂ₙ is only the positive part.
          ○ do not include (-1)ⁿ or (-1)ⁿ⁻¹ inside 𝒂ₙ.
     ◉ Step 1 — Check the limit of the positive terms:
          ○ limₙ→∞ 𝒂ₙ = 0
     ◉ Step 2 — Check that the positive terms are decreasing:
          ○ 𝒂ₙ₊₁ ≤ 𝒂ₙ
     ◉ Therefore:
          ○ i̲f̲ 𝒂ₙ → 0,
          ○ a̲n̲d̲ 𝒂ₙ is decreasing,
               ■ t̲h̲e̲n̲ the alternating series converges.
     ◉ Key idea:
          ○ the test is not applied to the whole signed term.
          ○ it is applied to the positive sequence 𝒂ₙ.
          
● [13:58](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=838). Graphical and conceptual justification.
     ◉ Imagine the partial sums moving back and forth:
          ○ add a positive term,
          ○ subtract a smaller term,
          ○ add an even smaller term,
          ○ subtract an even smaller term,
          ○ and so on.
     ◉ Because the terms are decreasing:
          ○ each jump is smaller than the previous jump.
     ◉ Because the terms approach 0:
          ○ the jumps eventually become tiny.
     ◉ Therefore:
          ○ the partial sums settle toward one finite value.
          ○ this is why the alternating series converges.

● [13:58](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=838). Ping-pong model.
     ◉ Think of a ping-pong rally:
          ○ the ball moves from one side to the other.
          ○ each hit travels a shorter distance.
          ○ eventually, the movement gets closer and closer to a central point.
     ◉ Alternating series behave similarly:
          ○ the partial sums jump above and below the final sum.
          ○ the jumps become smaller.
          ○ the sequence of partial sums converges.

● N̲O̲T̲E̲ — Even and odd partial sums in an alternating series.
     ◉ Example:
          ○ 1 - 1/2 + 1/3 - 1/4 + 1/5 - 1/6 + ...
     ◉ Partial sums:
          ○ S₁ = 1
          ○ S₂ = 0.5
          ○ S₃ ≈ 0.833
          ○ S₄ ≈ 0.583
          ○ S₅ ≈ 0.783
          ○ S₆ ≈ 0.616
     ◉ Even partial sums:
          ○ S₂, S₄, S₆, ...
          ○ 0.5, 0.583, 0.616, ...
          ○ these are increasing.
     ◉ Odd partial sums:
          ○ S₁, S₃, S₅, ...
          ○ 1, 0.833, 0.783, ...
          ○ these are decreasing.
     ◉ Key pattern:
          ○ the even partial sums approach the final sum from below.
          ○ the odd partial sums approach the final sum from above.
          ○ both subsequences move toward the same value.
     ◉ Therefore:
          ○ the partial sums bounce around the final sum,
               ■ but each bounce is smaller.
          ○ this is why the alternating series converges.


          

Ｅｘａｍｐｌｅｓ　Ｕｓｉｎｇ　ｔｈｅ　ＡＳＴ

Ｅｘａｍｐｌｅ  1

● [📷image](../img/Calculus 2 Lecture 9.5/[19-00]-01.png)

● [19:00](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=1140). 🧩 Example 1 — Alternating Harmonic Series: ∑[𝒏=1,∞] [(-1)ⁿ⁻¹]/𝒏
     ◉ Identify the positive part:
          ○ 𝒂ₙ = 1/𝒏
     ◉ Important:
          ○ (-1)ⁿ⁻¹ only creates the alternating signs.
          ○ it is not part of 𝒂ₙ.

● [21:00](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=1260). ❶ Check the limit condition.
     ◉ Compute:
          ○ limₙ→∞ 𝒂ₙ
     ◉ Since:
          ○ 𝒂ₙ = 1/𝒏
     ◉ Then:
          ○ limₙ→∞ 1/𝒏 = 0
     ◉ Therefore:
          ○ the limit condition is satisfied.

● [22:00](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=1320). ❷ Check the decreasing condition.
     ◉ We need:
          ○ 𝒂ₙ₊₁ ≤ 𝒂ₙ
     ◉ Since:
          ○ 𝒂ₙ = 1/𝒏
     ◉ Then:
          ○ 𝒂ₙ₊₁ = 1/(𝒏 + 1)
     ◉ Compare:
          ○ 1/(𝒏 + 1) ≤ 1/𝒏
     ◉ Therefore:
          ○ 𝒂ₙ is decreasing.

● [24:13](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=1453). Conclusion for Example 1.
     ◉ The series is alternating.
     ◉ The positive terms satisfy:
          ○ limₙ→∞ 𝒂ₙ = 0
          ○ 𝒂ₙ₊₁ ≤ 𝒂ₙ
     ◉ Therefore, by the Alternating Series Test:
          ○ ∑[𝒏=1,∞] (-1)ⁿ⁻¹/𝒏 converges.
     ◉ Important:
          ○ the harmonic series ∑ 1/𝒏 diverges.
          ○ the alternating harmonic series ∑ (-1)ⁿ⁻¹/𝒏 converges.
          

Ｅｘａｍｐｌｅ  2

● [📷image](../img/Calculus 2 Lecture 9.5/[27-52]-01.png)

● [27:52](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=1672). 🧩 Example 2 — ∑[𝒏=1,∞] (-1)ⁿ ⋅ 2𝒏/(4𝒏 - 1).
     ◉ Identify the positive part:
          ○ 𝒂ₙ = 2𝒏/(4𝒏 - 1)
     ◉ The series is alternating because of:
          ○ (-1)ⁿ

● [28:50](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=1730). Checking decreasing behavior.
     ◉ To check decreasing, we need:
          ○ 𝒂ₙ₊₁ ≤ 𝒂ₙ
     ◉ Direct substitution can be messy:
          ○ 𝒂ₙ₊₁ = 2(𝒏 + 1)/(4(𝒏 + 1) - 1)
          ○ 𝒂ₙ₊₁ = (2𝒏 + 2)/(4𝒏 + 3)
     ◉ Comparing this directly with:
          ○ 𝒂ₙ = 2𝒏/(4𝒏 - 1)
     ◉ can be more work.
     ◉ Easier method:
          ○ model the positive sequence with a function.
          ○ 𝒇(𝒙) = 2𝒙/(4𝒙 - 1)

● [29:20](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=1760). Using the derivative to show decreasing.
     ◉ Differentiate:
          ○ 𝒇(𝒙) = 2𝒙/(4𝒙 - 1)
     ◉ Using the quotient rule:
          ○ 𝒇′(𝒙) = [2(4𝒙 - 1) - 4(2𝒙)]/(4𝒙 - 1)²
     ◉ Simplify:
          ○ 𝒇′(𝒙) = (8𝒙 - 2 - 8𝒙)/(4𝒙 - 1)²
          ○ 𝒇′(𝒙) = -2/(4𝒙 - 1)²
     ◉ Since:
          ○ (4𝒙 - 1)² > 0
     ◉ Then:
          ○ 𝒇′(𝒙) < 0
     ◉ Therefore:
          ○ 𝒇(𝒙) is decreasing.
          ○ so 𝒂ₙ is decreasing.

● [31:42](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=1902). Check the limit condition.
     ◉ Compute:
          ○ limₙ→∞ 2𝒏/(4𝒏 - 1)
     ◉ Since the numerator and denominator have the same degree:
          ○ compare leading coefficients.
     ◉ Therefore:
          ○ limₙ→∞ 2𝒏/(4𝒏 - 1) = 2/4 = 1/2
     ◉ Since:
          ○ 1/2 ≠ 0
     ◉ The positive terms do not approach 0.

● [32:18](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=1938). Conclusion for Example 2.
     ◉ Even though 𝒂ₙ is decreasing,
          ○ the limit condition fails.
     ◉ Since:
          ○ limₙ→∞ 𝒂ₙ ≠ 0
     ◉ The series fails the necessary condition for convergence.
     ◉ Therefore:
          ○ ∑[𝒏=1,∞] (-1)ⁿ ⋅ 2𝒏/(4𝒏 - 1) diverges.
     ◉ Important:
          ○ for the Alternating Series Test, both conditions are needed:
               ■ 𝒂ₙ must be decreasing.
               ■ limₙ→∞ 𝒂ₙ must equal 0.
          ○ here, the decreasing condition works,
               ■ but the limit condition fails.
          

Ｅｘａｍｐｌｅ  3

●  [📷image-1](../img/Calculus 2 Lecture 9.5/[33-31]-01.png)  [📷image-2](../img/Calculus 2 Lecture 9.5/[33-31]-02.png)

● [33:31](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=2011). 🧩 Example 3 —  ∑[𝒏=2,∞] (-1)ⁿ⁻¹ ⋅ √(𝒏 + 1)/(𝒏 - 1).
     ◉ Given series: 
          ○ ∑ (-1)ⁿ⁻¹ ⋅ √(𝒏 + 1)/(𝒏 - 1)
     ◉ Identify the positive part:
          ○ 𝒂ₙ = √(𝒏 + 1)/(𝒏 - 1)
     ◉ The series is alternating because of:
          ○ (-1)ⁿ⁻¹

● [36:23](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=2183). Check the limit condition using L'Hôpital's Rule.
     ◉ Compute:
          ○ limₙ→∞ √(𝒏 + 1)/(𝒏 - 1)
     ◉ This has the form:
          ○ ∞/∞
     ◉ Apply L'Hôpital's Rule:
          ○ derivative of √(𝒏 + 1) = 1/(2√(𝒏 + 1))
          ○ derivative of 𝒏 - 1 = 1
     ◉ Therefore:
          ○ limₙ→∞ √(𝒏 + 1)/(𝒏 - 1)
          ○ = limₙ→∞ 1/(2√(𝒏 + 1))
          ○ = 0
     ◉ So:
          ○ limₙ→∞ 𝒂ₙ = 0

● [38:45](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=2325). Check the decreasing condition using the derivative.
     ◉ Define:
          ○ 𝒇(𝒙) = √(𝒙 + 1)/(𝒙 - 1)
     ◉ We use a function because:
          ○ 𝒇(𝒙) models the positive sequence 𝒂ₙ.
     ◉ If:
          ○ 𝒇′(𝒙) < 0
     ◉ Then:
          ○ 𝒇(𝒙) is decreasing,
          ○ so the sequence 𝒂ₙ is decreasing.

● [42:32](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=2552). Showing the derivative is negative.
     ◉ Differentiate:
          ○ 𝒇(𝒙) = √(𝒙 + 1)/(𝒙 - 1)
     ◉ Important domain detail:
          ○ 𝒇(𝒙) is not defined at 𝒙 = 1,
               ■ because the denominator 𝒙 - 1 becomes 0.
          ○ since the series starts at 𝒏 = 2,
               ■ we only need to show decreasing behavior for 𝒙 ≥ 2.
     ◉ Using the quotient rule:
          ○ 𝒇′(𝒙) = [((𝒙 - 1)/(2√(𝒙 + 1))) - √(𝒙 + 1)]/(𝒙 - 1)²
     ◉ Combine the numerator:
          ○ 𝒇′(𝒙) = (𝒙 - 1 - 2(𝒙 + 1))/(2√(𝒙 + 1)(𝒙 - 1)²)
     ◉ Simplify:
          ○ 𝒇′(𝒙) = (-𝒙 - 3)/(2√(𝒙 + 1)(𝒙 - 1)²)
     ◉ Sign analysis:
          ○ the denominator is positive for 𝒙 > 1.
          ○ the numerator -𝒙 - 3 is negative for 𝒙 > 1.
          ○ therefore, 𝒇′(𝒙) < 0 for 𝒙 > 1.
     ◉ In particular:
          ○ 𝒇′(𝒙) < 0 for 𝒙 ≥ 2.
     ◉ Therefore:
          ○ 𝒇(𝒙) is decreasing on [2,∞).
          ○ so 𝒂ₙ is decreasing for 𝒏 ≥ 2.

● [44:18](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=2658). Conclusion for Example 3.
     ◉ The series is alternating.
     ◉ The positive terms satisfy:
          ○ limₙ→∞ 𝒂ₙ = 0
          ○ 𝒂ₙ is decreasing.
     ◉ Therefore, by the Alternating Series Test:
          ○ the series converges.
     ◉ Note:
          ○ even if the first few terms are problematic,
               ■ adding or removing finitely many terms does not change convergence.




               

Ａｌｔｅｒｎａｔｉｎｇ　Ｓｅｒｉｅｓ　Ｅｒｒｏｒ　Ｅｓｔｉｍａｔｅ

● [📷image-1](../img/Calculus 2 Lecture 9.5/[45-28]-01.png)  [📷image-2](../img/Calculus 2 Lecture 9.5/[45-28]-02.png)

● [45:28](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=2728). Finding error in alternating series.
     ◉ If a series ∑ 𝒂ₙ converges, 
          ○ then it has some sum 𝑺.
     ◉ The sequence of partial sums satisfies:
          ○ limₙ→∞ 𝑺ₙ = 𝑺
     ◉ Therefore:
          ○ limₙ→∞ (𝑺 - 𝑺ₙ) = 0
     ◉ Meaning:
          ○ if 𝒏 actually goes to infinity,
               ■ the partial sums approach the exact sum.
          ○ but if we stop at a finite 𝒏,
               ■ there will be some error between 𝑺 and 𝑺ₙ.

● [50:00](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=3000). Defining the error.
     ◉ The error is called:
          ○ 𝑹ₙ
     ◉ Definition:
          ○ 𝑹ₙ = 𝑺 - 𝑺ₙ
     ◉ Meaning:
          ○ error = whole sum - partial sum
     ◉ In words:
          ○ 𝑺 is the exact infinite sum.
          ○ 𝑺ₙ is the partial sum after 𝒏 terms.
          ○ 𝑹ₙ is the difference between them.

● [53:36](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=3216). Alternating Series Estimation Theorem.
     ◉ For alternating series only:
          ○ |𝑹ₙ| = |𝑺 - 𝑺ₙ| ≤ 𝒂ₙ₊₁
     ◉ Meaning:
          ○ the absolute error is less than or equal to the first omitted term.
     ◉ If we stop at 𝑺ₙ,
          ○ the next positive term is 𝒂ₙ₊₁.
     ◉ Therefore:
          ○ the error is no larger than 𝒂ₙ₊₁.

● [55:04](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=3304). Why the first omitted term controls the error.
     ◉ Suppose the exact sum is:
          ○ 𝑺 = 𝒂₁ - 𝒂₂ + 𝒂₃ - ... - 𝒂ₙ + 𝒂ₙ₊₁ - 𝒂ₙ₊₂ + ...
     ◉ The partial sum is:
          ○ 𝑺ₙ = 𝒂₁ - 𝒂₂ + 𝒂₃ - ... - 𝒂ₙ
     ◉ Therefore, the remaining tail is:
          ○ 𝑺 - 𝑺ₙ = 𝒂ₙ₊₁ - 𝒂ₙ₊₂ + 𝒂ₙ₊₃ - ...
     ◉ Since the positive terms are decreasing:
          ○ 𝒂ₙ₊₂ ≤ 𝒂ₙ₊₁
          ○ 𝒂ₙ₊₃ ≤ 𝒂ₙ₊₂
          ○ and so on.
     ◉ Therefore:
          ○ The remaining terms alternate signs and partially cancel each other, 
          ○ and since their sizes decrease, the total remaining error cannot exceed the first omitted term.
     ◉ So:
          ○ |𝑺 - 𝑺ₙ| ≤ 𝒂ₙ₊₁
          ○ |𝑹ₙ| ≤ 𝒂ₙ₊₁

● N̲O̲T̲E̲ — Key idea.
     ◉ In an alternating series,
          ○ the terms after 𝑺ₙ keep alternating signs.
     ◉ Because the positive terms decrease,
          ○ each new term partially cancels the previous one.
     ◉ Therefore:
          ○ the total error after stopping at 𝑺ₙ
               ■ is controlled by the first term you did not include.




          

Ｐｒａｃｔｉｃａｌ　Ｅｒｒｏｒ　Ｅｘａｍｐｌｅ

● [📷image-1](../img/Calculus 2 Lecture 9.5/[1-01-24]-01.png)  [📷image-2](../img/Calculus 2 Lecture 9.5/[1-01-24]-02.png)

● [1:01:24](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=3684). 🧩 Example 4 — Practical problem of precision and error: ∑[𝒏=0,∞] (-1)ⁿ/𝒏!
     ◉ Goal:
          ○ approximate the sum of the series using a partial sum.
     ◉ Desired accuracy:
          ○ make the error less than 0.0005.
     ◉ Key idea:
          ○ we first prove that the series converges.
          ○ then we use the error bound to decide how many terms are needed.

● [1:02:42](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=3762). Check convergence first.
     ◉ The series is alternating because of:
          ○ (-1)ⁿ
     ◉ Identify the positive part:
          ○ 𝒂ₙ = 1/𝒏!
     ◉ Check the limit:
          ○ limₙ→∞ 1/𝒏! = 0
     ◉ Check decreasing:
          ○ 𝒂ₙ₊₁ = 1/(𝒏 + 1)!
          ○ 1/(𝒏 + 1)! ≤ 1/𝒏!
     ◉ Therefore:
          ○ 𝒂ₙ is decreasing.
     ◉ By the Alternating Series Test:
          ○ ∑[𝒏=0,∞] (-1)ⁿ/𝒏! converges.

● [1:06:00](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=3960). How error works.
     ◉ For a convergent alternating series:
          ○ |𝑹ₙ| = |𝑺 - 𝑺ₙ| ≤ 𝒂ₙ₊₁
     ◉ In this example:
          ○ 𝒂ₙ₊₁ = 1/(𝒏 + 1)!
     ◉ Therefore:
          ○ |𝑹ₙ| ≤ 1/(𝒏 + 1)!
     ◉ Meaning:
          ○ the error after stopping at 𝑺ₙ
               ■ is no bigger than the first omitted term.
     ◉ Practical interpretation:
          ○ you tell the series how accurate you want to be.
          ○ then use 𝑹ₙ to determine how many terms are needed to be that accurate.

● [1:09:50](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=4190). Finding how many terms are needed.
     ◉ We want:
          ○ |𝑹ₙ| < 0.0005
     ◉ Since:
          ○ |𝑹ₙ| ≤ 1/(𝒏 + 1)!
     ◉ It is enough to require:
          ○ 1/(𝒏 + 1)! < 0.0005
     ◉ This guarantees:
          ○ |𝑹ₙ| < 0.0005

● [1:13:01](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=4381). Solving the inequality.
     ◉ Start with:
          ○ 1/(𝒏 + 1)! < 0.0005
     ◉ Take reciprocals:
          ○ (𝒏 + 1)! > 1/0.0005
     ◉ Since:
          ○ 1/0.0005 = 2000
     ◉ Then:
          ○ (𝒏 + 1)! > 2000

● [1:15:11](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=4511). Determining 𝒏.
     ◉ Check factorials:
          ○ 6! = 720
          ○ 7! = 5040
     ◉ Since:
          ○ 6! < 2000
          ○ 7! > 2000
     ◉ We need:
          ○ 𝒏 + 1 = 7
     ◉ Therefore:
          ○ 𝒏 = 6
     ◉ Meaning:
          ○ stopping at 𝑺₆ guarantees an error less than 0.0005.

● [1:15:56](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=4556). Computing the partial sum 𝑺₆.
     ◉ Since the series starts at 𝒏 = 0,
          ○ 𝑺₆ includes the terms from 𝒏 = 0 through 𝒏 = 6.
     ◉ Therefore:
          ○ 𝑺₆ = 1 - 1/1! + 1/2! - 1/3! + 1/4! - 1/5! + 1/6!
     ◉ Rewrite:
          ○ 𝑺₆ = 1 - 1 + 1/2 - 1/6 + 1/24 - 1/120 + 1/720

● [1:18:20](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=4700). Final approximation.
     ◉ Compute:
          ○ 𝑺₆ =  0.368
     ◉ Therefore:
          ○ 𝑺 ≈ 0.368
     ◉ Important:
          ○ 𝑺₆ is not exactly equal to 𝑺.
          ○ 𝑺₆ is only a partial sum approximation.
     ◉ But:
          ○ it is a very good approximation.
     ◉ How good?
          ○ the error is less than 0.0005.
          ○ this means 𝑺₆ is within 0.0005 of the true sum 𝑺.
     ◉ In Leonard's words:
          ○ it is not equal to 𝑺,
               ■ but it is within 5 ten-thousandths of 𝑺.
          ○ that is how the error estimate is used.

● N̲O̲T̲E̲:
     ◉ Smaller allowed error ⇒ you need to go further in the series ⇒ you use a partial sum with more terms ⇒ you are closer to the true sum.






Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Alternating Series
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/5-5-alternating-series)
