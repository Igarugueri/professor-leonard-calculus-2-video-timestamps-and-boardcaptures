-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ９．７： Ｐｏｗｅｒ Ｓｅｒｉｅｓ， Ｃａｌｃｕｌｕｓ ｏｆ Ｐｏｗｅｒ Ｓｅｒｉｅｓ， Ｒａｔｉｏ Ｔｅｓｔ ｆｏｒ Ｉｎｔ． ｏｆ Ｃｏｎｖｅｒｇｅｎｃｅ**-------------------------------—






１ - Ｉｎｔｒｏｄｕｃｔｉｏｎ　ｔｏ　Ｐｏｗｅｒ　Ｓｅｒｉｅｓ


● [0:01]. Introduction to power series.
     ◉ Main idea:
          ○ previous sections on series were needed in order to understand power series.
     ◉ A power series is:
          ○ a series with a **variable**,
          ○ usually 𝒙,
          ○ raised to powers depending on 𝒏.

● [0:16]. Definition of a power series.
     ◉ A power series is:
          ○ a series with a **variable 𝒙** raised to some power.
     ◉ The power is usually based on:
          ○ the index 𝒏.
     ◉ General idea:
          ○ instead of having only numerical terms,
          ○ we now have terms involving 𝒙.

● [1:04]. The exponent depends on 𝒏.
     ◉ In a power series:
          ○ the exponent changes as 𝒏 changes.
     ◉ Typical form:
          ○ ∑[𝒏=0,∞] 𝒂ₙ𝒙ⁿ
     ◉ Here:
          ○ 𝒂ₙ gives the coefficient.
          ○ 𝒙ⁿ gives the power part.
     ◉ Important:
          ○ the variable is 𝒙,
          ○ but the exponent is controlled by 𝒏.

● [1:29]. Two main types of power series.
     ◉ Type 1:
          ○ power series centered at the origin.
          ○ centered at 0.
     ◉ Type 2:
          ○ power series centered at a constant 𝑪.
          ○ centered at 𝑪 instead of 0.




１．１ - Ｐｏｗｅｒ　Ｓｅｒｉｅｓ　Ｃｅｎｔｅｒｅｄ　ａｔ　ｔｈｅ　Ｏｒｉｇｉｎ

● [1:35]. Type 1 — Power series centered at zero.
     ◉ General form:
          ○ ∑[𝒏=0,∞] 𝒂ₙ𝒙ⁿ
     ◉ This is centered at:
          ○ 0 (origin)
     ◉ Reason:
          ○ nothing is added to or subtracted from 𝒙.
     ◉ We can think of it as:
          ○ ∑[𝒏=0,∞] 𝒂ₙ(𝒙 - 0)ⁿ

● [2:57]. Expanding the first few terms.
     ◉ Start with:
          ○ ∑[𝒏=0,∞] 𝒂ₙ𝒙ⁿ
     ◉ Plug in 𝒏 = 0:
          ○ 𝒂₀𝒙⁰ = 𝒂₀
     ◉ Plug in 𝒏 = 1:
          ○ 𝒂₁𝒙
     ◉ Plug in 𝒏 = 2:
          ○ 𝒂₂𝒙²
     ◉ Therefore:
          ○ ∑[𝒏=0,∞] 𝒂ₙ𝒙ⁿ = 𝒂₀ + 𝒂₁𝒙 + 𝒂₂𝒙² + 𝒂₃𝒙³ + ...

● N̲O̲T̲E̲ — Why this is centered at 0.
     ◉ The center is the number subtracted from 𝒙.
     ◉ In:
          ○ 𝒙ⁿ
     ◉ we can rewrite:
          ○ 𝒙ⁿ = (𝒙 - 0)ⁿ
     ◉ Therefore:
          ○ the center is 0.



１．２ - Ｐｏｗｅｒ　Ｓｅｒｉｅｓ　Ｃｅｎｔｅｒｅｄ　ａｔ  𝑪

● [5:11]. Type 2 — Power series centered at a constant 𝑪.
     ◉ General form:
          ○ ∑[𝒏=0,∞] 𝒂ₙ(𝒙 - 𝑪)ⁿ
     ◉ This is centered at:
          ○ 𝑪
     ◉ Here:
          ○ 𝑪 is a constant.
          ○ 𝒙 is the variable.

● [5:32]. First few terms of a shifted power series.
     ◉ Start with:
          ○ ∑[𝒏=0,∞] 𝒂ₙ(𝒙 - 𝑪)ⁿ
     ◉ Plug in 𝒏 = 0:
          ○ 𝒂₀(𝒙 - 𝑪)⁰ = 𝒂₀
     ◉ Plug in 𝒏 = 1:
          ○ 𝒂₁(𝒙 - 𝑪)
     ◉ Plug in 𝒏 = 2:
          ○ 𝒂₂(𝒙 - 𝑪)²
     ◉ Therefore:
          ○ 𝒂₀ + 𝒂₁(𝒙 - 𝑪) + 𝒂₂(𝒙 - 𝑪)² + 𝒂₃(𝒙 - 𝑪)³ + ...

● [6:04]. Identifying the center.
     ◉ In:
          ○ (𝒙 - 𝑪)ⁿ
     ◉ the center is:
          ○ 𝑪
     ◉ Example:
          ○ (𝒙 - 3)ⁿ is centered at 3.
     ◉ Example:
          ○ (𝒙 + 2)ⁿ = (𝒙 - (-2))ⁿ
          ○ so it is centered at -2.

● N̲O̲T̲E̲ — The sign changes.
     ◉ The form is always:
          ○ 𝒙 - 𝑪
     ◉ Therefore:
          ○ 𝒙 - 3 means center 3.
          ○ 𝒙 + 3 means center -3.






2 - Ｅｘａｍｐｌｅｓ　ｏｆ　Ｐｏｗｅｒ　Ｓｅｒｉｅｓ

● [7:02]. Examples of power series.
     ◉ Goal:
          ○ recognize the structure.
          ○ identify the center.
          ○ expand the first few terms.
          

2．１ Ｅｘａｍｐｌｅ  １

● [7:23]. 🧩 Example 1 — Alternating power series centered at 0: ∑[𝒏=0,∞] (-1)ⁿ𝒙ⁿ/𝒏!
     ◉ This is a power series because:
          ○ it contains **a variabke 𝒙 raised to powers depending on 𝒏.**
     ◉ It is centered at:
          ○ 0
     ◉ Reason:
          ○ the expression uses 𝒙ⁿ,
          ○ not (𝒙 - 𝑪)ⁿ.

● [9:03]. Expanding.
     ◉ Start with:
          ○ ∑[𝒏=0,∞] (-1)ⁿ𝒙ⁿ/𝒏!
     ◉ Plug in 𝒏 = 0:
          ○ (-1)⁰𝒙⁰/0! = 1
     ◉ Plug in 𝒏 = 1:
          ○ (-1)¹𝒙¹/1! = -𝒙/1!
     ◉ Plug in 𝒏 = 2:
          ○ (-1)²𝒙²/2! = 𝒙²/2!
     ◉ Plug in 𝒏 = 3:
          ○ (-1)³𝒙³/3! = -𝒙³/3!
     ◉ Therefore:
          ○ 1 - 𝒙/1! + 𝒙²/2! - 𝒙³/3! + 𝒙⁴/4! - ...

● N̲O̲T̲E̲ — Pattern in Example 1.
     ◉ The factor:
          ○ (-1)ⁿ
     ◉ creates alternating signs:
          ○ +, -, +, -, ...
     ◉ The power part:
          ○ 𝒙ⁿ
     ◉ makes it a power series.
     ◉ The factorial:
          ○ 𝒏!
     ◉ appears in the denominator.
     

2．2  Ｅｘａｍｐｌｅ  2

● [10:22]. 🧩 Example 2 — Power series centered at π/4: ∑[𝒏=0,∞] (-1)ⁿ(𝒙 - π/4)²ⁿ⁺¹/(2𝒏 + 1)!
     ◉ This is a power series because:
          ○ it contains the variable 𝒙 raised to powers depending on 𝒏.
     ◉ It is centered at:
          ○ π/4
     ◉ Reason:
          ○ the variable part is (𝒙 - π/4).

● [12:30]. Expanding the first few terms.
     ◉ Start with:
          ○ ∑[𝒏=0,∞] (-1)ⁿ(𝒙 - π/4)²ⁿ⁺¹/(2𝒏 + 1)!
     ◉ Plug in 𝒏 = 0:
          ○ (-1)⁰(𝒙 - π/4)¹/1! = (𝒙 - π/4)
     ◉ Plug in 𝒏 = 1:
          ○ (-1)¹(𝒙 - π/4)³/3! = -(𝒙 - π/4)³/3!
     ◉ Plug in 𝒏 = 2:
          ○ (-1)²(𝒙 - π/4)⁵/5! = (𝒙 - π/4)⁵/5!
     ◉ Therefore:
          ○ ∑[𝒏=0,∞] (-1)ⁿ(𝒙 - π/4)²ⁿ⁺¹/(2𝒏 + 1)!
          ○ = (𝒙 - π/4) - (𝒙 - π/4)³/3! + (𝒙 - π/4)⁵/5! - ...

● N̲O̲T̲E̲ — Pattern.
     ◉ The factor:
          ○ (-1)ⁿ
     ◉ creates the alternating signs:
          ○ +, -, +, -, ...
     ◉ The exponent:
          ○ 2𝒏 + 1
     ◉ creates odd powers:
          ○ 1, 3, 5, 7, ...
     ◉ The denominator:
          ○ (2𝒏 + 1)!
     ◉ creates matching odd factorials:
          ○ 1!, 3!, 5!, 7!, ...





3 - Ｐｏｗｅｒ　Ｓｅｒｉｅｓ　ａｓ　Ｆｕｎｃｔｉｏｎｓ

● [14:00]. A++ power series defines a function.
     ◉ A power series contains the variable 𝒙.
     ◉ Therefore:
          ○ it can define a function of 𝒙.
     ◉ General function form:
          ○ 𝒇(𝒙) = ∑[𝒏=0,∞] 𝒂ₙ(𝒙 - 𝑪)ⁿ

● [16:05]. Domain of a power series function.
     ◉ The domain is:
          ○ the set of 𝒙-values for which the series converges.
     ◉ Important:
          ○ not every 𝒙-value necessarily works.
     ◉ For some values of 𝒙:
          ○ the series converges.
     ◉ For other values of 𝒙:
          ○ the series diverges.

● [16:47]. Input and output.
     ◉ Input:
          ○ a value of 𝒙.
     ◉ After plugging in 𝒙:
          ○ the power series becomes an ordinary numerical series.
     ◉ If that numerical series converges:
          ○ its sum becomes the output 𝒇(𝒙).
               ■ this only happens for values of 𝒙 where the series converges.
     ◉ If that numerical series diverges:
          ○ there is no valid output for the function at that 𝒙.

● N̲O̲T̲E̲ — Key interpretation.
     ◉ 𝒙 is the input.
     ◉ The sum of the convergent series is the output.
     ◉ So:
          ○ 𝒇(𝒙) = sum of the power series.
     ◉ But this only works:
          ○ for 𝒙-values inside the interval of convergence.





４ - Ｇｅｏｍｅｔｒｉｃ　Ｓｅｒｉｅｓ　ａｓ　ａ　Ｐｏｗｅｒ　Ｓｅｒｉｅｓ

● [21:46]. The most basic power series: ∑[𝒏=0,∞] 𝒙ⁿ
     ◉ First few terms:
          ○ 1 + 𝒙 + 𝒙² + 𝒙³ + ...
     ◉ This is a power series centered at:
          ○ 0

● [22:23]. Geometric structure.
     ◉ A geometric series has form:
          ○ ∑ 𝒂𝒓ⁿ
     ◉ A geometric series converges when:
          ○ |𝒓| < 1
    
● [24:05]. The variable 𝒙 acts as the common ratio.
     ◉ In the geometric series:
          ○ 𝒓 is the common ratio.
     ◉ Here:
          ○ 𝒓 = 𝒙
     ◉ Therefore:
          ○ the convergence depends on 𝒙.

● [24:35]. Recognizing the geometric structure
     ◉ For:
          ○ ∑[𝒏=0,∞] 𝒙ⁿ
     ◉ we have:
          ○ 𝒂 = 1
          ○ 𝒓 = 𝒙
     ◉ Therefore:
          ○ ∑[𝒏=0,∞] 𝒙ⁿ is a geometric series.
          
● [25:28]. Condition for convergence.
     ◉ A geometric series converges when:
          ○ |𝒓| < 1
     ◉ Since:
          ○ 𝒓 = 𝒙
     ◉ We need:
          ○ |𝒙| < 1
     ◉ Equivalent interval:
          ○ -1 < 𝒙 < 1

● [27:20]. Function representation.
     ◉ Define:
          ○ 𝒇(𝒙) = ∑[𝒏=0,∞] 𝒙ⁿ
     ◉ Then:
          ○ 𝒇(𝒙) = 1/(1 - 𝒙)
     ◉ Domain:
          ○ (-1,1)
     ◉ Therefore:
          ○ the power series represents 1/(1 - 𝒙) only on (-1,1).

● [28:06]. Sum of the geometric power series.
     ◉ Geometric sum formula:
          ○ 𝒂/(1 - 𝒓)
     ◉ Here:
          ○ 𝒂 = 1
          ○ 𝒓 = 𝒙
     ◉ Therefore:
          ○ ∑[𝒏=0,∞] 𝒙ⁿ = 1/(1 - 𝒙)
     ◉ But only when:
          ○ |𝒙| < 1



５ - Ｇｅｎｅｒａｌ　Ｐｏｗｅｒ　Ｓｅｒｉｅｓ：Ｒａｄｉｕｓ　ａｎｄ　Ｉｎｔｅｒｖａｌ　ｏｆ　Ｃｏｎｖｅｒｇｅｎｃｅ

● [33:31]. General power series.
     ◉ General form:
          ○ 𝒇(𝒙) = ∑[𝒏=0,∞] 𝒂ₙ(𝒙 - 𝑪)ⁿ
     ◉ This is centered at:
          ○ 𝑪
     ◉ Important note:
          ○ 𝒇(𝑪) = 𝒂₀
     ◉ Reason:
          ○ if 𝒙 = 𝑪,
               ■ then 𝒙 - 𝑪 = 0.
          ○ so every term after the first one disappears.
          ○ only 𝒂₀ remains.

● [35:08]. Domain is centered at 𝑪.
     ◉ The domain of a power series function:
          ○ is always an interval centered at 𝑪.
     ◉ Reason:
          ○ the expression is built around (𝒙 - 𝑪).
     ◉ The distance from 𝑪 to the endpoints is called:
          ○ the radius of convergence.
     ◉ Therefore:
          ○ the center 𝑪 sits in the middle of the interval of convergence.

● [36:33]. Three possible convergence cases.
     ◉ Case A:
          ○ convergence only at the center.
     ◉ Case B:
          ○ convergence for all real 𝒙.
     ◉ Case C:
          ○ convergence inside a finite interval around the center.

● [37:00]. Case A — Convergence only at the center.
     ◉ The series converges only when:
          ○ 𝒙 = 𝑪
     ◉ Then:
          ○ radius of convergence 𝑹 = 0
     ◉ Meaning:
          ○ there is no interval around 𝑪.
          ○ the only valid point is the center itself.
     ◉ Symbolically:
          ○ 0 ≤ |𝒙 - 𝑪| ≤ 0
     ◉ Therefore:
          ○ 𝒙 = 𝑪 only.

● [38:37]. Case B — Convergence for all real 𝒙.
     ◉ The series converges for:
          ○ every real value of 𝒙.
     ◉ Then:
          ○ radius of convergence 𝑹 = ∞
     ◉ Symbolically:
          ○ -∞ < 𝒙 - 𝑪 < ∞
     ◉ Interval of convergence:
          ○ (-∞,∞)

● [39:35]. Case C — Finite radius of convergence.
     ◉ The series converges when:
          ○ |𝒙 - 𝑪| < 𝑹
     ◉ It diverges when:
          ○ |𝒙 - 𝑪| > 𝑹
     ◉ Here:
          ○ 𝑹 is the radius of convergence.
     ◉ Meaning:
          ○ 𝑹 tells how far we can move left and right from the center 𝑪 while the series still converges.
     ◉ Interval from the radius.
          ○ Start with:
               ■ |𝒙 - 𝑪| < 𝑹
          ○ Equivalent inequality:
               ■ -𝑹 < 𝒙 - 𝑪 < 𝑹
          ○ Add 𝑪:
               ■ 𝑪 - 𝑹 < 𝒙 < 𝑪 + 𝑹
          ○ Therefore:
               ■ the interval is centered at 𝑪.
               ■ the radius is 𝑹.
               ■ the preliminary interval is (𝑪 - 𝑹, 𝑪 + 𝑹).
     ◉ Endpoints must be checked separately.
          ○ The Ratio Test usually gives:
               ■ |𝒙 - 𝑪| < 𝑹
          ○ But it does not decide:
               ■ 𝒙 = 𝑪 - 𝑹
               ■ 𝒙 = 𝑪 + 𝑹
          ○ Therefore:
               ■ plug each endpoint into the original power series.
               ■ test the resulting numerical series separately.
          ○ Use any appropriate convergence test:
               ■ Alternating Series Test.
               ■ 𝒑-Series Test.
               ■ Comparison Test.
               ■ Limit Comparison Test.
               ■ etc.



５．１ - Ｅｘａｍｐｌｅｓ　ｏｆ　Ｉｎｔｅｒｖａｌｓ　ｏｆ　Ｃｏｎｖｅｒｇｅｎｃｅ

５．１．１ - Ｅｘａｍｐｌｅ　１

● [44:18]. 🧩 Example 1 — Convergence only at the center: ∑[𝒏=0,∞] 𝒏!𝒙ⁿ
     ◉ This is a power series centered at:
          ○ 0
     ◉ The factorial suggests:
          ○ use the Ratio Test.
     ◉ Goal:
          ○ determine for which 𝒙-values the power series converges.

● [50:14]. Use the Ratio Test.
     ◉ Let:
          ○ 𝒂ₙ = 𝒏!𝒙ⁿ
     ◉ Then:
          ○ 𝒂ₙ₊₁ = (𝒏 + 1)!𝒙ⁿ⁺¹
     ◉ Compute:
          ○ 𝑳 = limₙ→∞ |𝒂ₙ₊₁/𝒂ₙ|
          ○ = limₙ→∞ |[(𝒏 + 1)!𝒙ⁿ⁺¹]/[𝒏!𝒙ⁿ]|
     ◉ Simplify:
          ○ (𝒏 + 1)!/𝒏! = 𝒏 + 1
          ○ 𝒙ⁿ⁺¹/𝒙ⁿ = 𝒙
     ◉ Therefore:
          ○ 𝑳 = limₙ→∞ (𝒏 + 1)|𝒙|

● [51:47]. Interpreting the Ratio Test result.
     ◉ If 𝒙 ≠ 0:
          ○ |𝒙| is a positive constant.
          ○ limₙ→∞ (𝒏 + 1)|𝒙| = ∞
          ○ ∞ > 1
          ○ the series diverges by the Ratio Test.
     ◉ If 𝒙 = 0:
          ○ limₙ→∞ (𝒏 + 1)|0| = 0
          ○ 0 < 1
          ○ the series converges by the Ratio Test.
     ◉ Therefore:
          ○ the series converges only at 𝒙 = 0.

● [53:25]. Radius and domain.
     ◉ Center:
          ○ 𝑪 = 0
     ◉ Domain:
          ○ 𝒙 = 0
     ◉ Radius of convergence:
          ○ 𝑹 = 0
     ◉ Interpretation:
          ○ the power series represents a function only at the center.

● N̲O̲T̲E̲ — Key idea.
     ◉ The factorial 𝒏! grows so fast that any 𝒙 ≠ 0 makes the series diverge.
     ◉ Only the center survives:
          ○ 𝒙 = 0
     ◉ Therefore:
          ○ the radius of convergence is 𝑹 = 0.



５．１．２ - Ｅｘａｍｐｌｅ　２

● [56:59]. 🧩 Example 2 — Power series converging for all 𝒙: ∑[𝒏=0,∞] (-1)ⁿ𝒙²ⁿ/(2𝒏)!
     ◉ This is a power series centered at:
          ○ 0
     ◉ Since factorials appear:
          ○ use the Ratio Test.
     ◉ Goal:
          ○ determine for which 𝒙-values the power series converges.

● [58:07]. Set up the Ratio Test.
     ◉ Let:
          ○ 𝒂ₙ = (-1)ⁿ𝒙²ⁿ/(2𝒏)!
     ◉ Then:
          ○ 𝒂ₙ₊₁ = (-1)ⁿ⁺¹𝒙²ⁿ⁺²/(2𝒏 + 2)!
     ◉ Compute:
          ○ 𝑳 = limₙ→∞ |𝒂ₙ₊₁/𝒂ₙ|

● [1:00:00]. Build the ratio.
     ◉ Substitute:
          ○ 𝑳 = limₙ→∞ | [(-1)ⁿ⁺¹𝒙²ⁿ⁺²/(2𝒏 + 2)!] / [(-1)ⁿ𝒙²ⁿ/(2𝒏)!] |
     ◉ Reciprocate and multiply:
          ○ 𝑳 = limₙ→∞ | [(-1)ⁿ⁺¹𝒙²ⁿ⁺²/(2𝒏 + 2)!] ⋅ [(2𝒏)!/((-1)ⁿ𝒙²ⁿ)] |

● [1:01:00]. Simplify signs and powers.
     ◉ The absolute value removes the alternating sign:
          ○ |(-1)ⁿ⁺¹/(-1)ⁿ| = 1
     ◉ Simplify the powers of 𝒙:
          ○ 𝒙²ⁿ⁺²/𝒙²ⁿ = 𝒙²
     ◉ Therefore:
          ○ 𝑳 = limₙ→∞ |𝒙² ⋅ (2𝒏)!/(2𝒏 + 2)!|

● [1:02:35]. Factorial simplification.
     ◉ Use:
          ○ (2𝒏 + 2)! = (2𝒏 + 2)(2𝒏 + 1)(2𝒏)!
     ◉ Therefore:
          ○ (2𝒏)!/(2𝒏 + 2)! = 1/[(2𝒏 + 2)(2𝒏 + 1)]
     ◉ So:
          ○ 𝑳 = limₙ→∞ 𝒙²/[(2𝒏 + 2)(2𝒏 + 1)]

● [1:06:44]. Limit result.
     ◉ For any fixed 𝒙:
          ○ 𝒙² is a constant.
          ○ (2𝒏 + 2)(2𝒏 + 1) → ∞.
     ◉ Therefore:
          ○ 𝑳 = limₙ→∞ 𝒙²/[(2𝒏 + 2)(2𝒏 + 1)] = 0
     ◉ This happens for all real 𝒙.

● [1:08:27]. Conclusion for Example 2.
     ◉ Since:
          ○ 𝑳 = 0 < 1
     ◉ By the Ratio Test:
          ○ the power series converges for all 𝒙.
     ◉ Therefore:
          ○ radius of convergence 𝑹 = ∞
          ○ interval of convergence is (-∞,∞)

● N̲O̲T̲E̲ 1 — Key idea.
     ◉ The factorial in the denominator grows fast enough to dominate every fixed power of 𝒙.
     ◉ No matter what real value 𝒙 has:
          ○ the ratio limit becomes 0.
     ◉ Therefore:
          ○ the series converges for all real 𝒙.
          
● N̲O̲T̲E̲ 2 — Why the domain is all real numbers.
     ◉ After applying the Ratio Test, we get:
          ○ 𝑳 = limₙ→∞ 𝒙²/[(2𝒏 + 2)(2𝒏 + 1)]
     ◉ Important:
          ○ 𝒙 is fixed.
          ○ 𝒏 is the variable that goes to infinity.
     ◉ For any fixed real value of 𝒙:
          ○ 𝒙² is just a constant.
          ○ (2𝒏 + 2)(2𝒏 + 1) → ∞.
     ◉ Therefore:
          ○ constant / ∞ = 0
          ○ 𝑳 = 0
     ◉ Since:
          ○ 0 < 1
     ◉ By the Ratio Test:
          ○ the series converges for every real value of 𝒙.
     ◉ Therefore:
          ○ domain = (-∞,∞)
          ○ radius of convergence 𝑹 = ∞
     ◉ Key idea:
          ○ we do not plug infinity into 𝒙.
          ○ 𝒙 stays fixed.
          ○ only 𝒏 goes to infinity.

          

５．１．３ - Ｅｘａｍｐｌｅ　３

● [1:12:28]. 🧩 Example 3 — Finite interval of convergence: ∑[𝒏=1,∞] 𝒙ⁿ/𝒏
     ◉ This is a power series centered at:
          ○ 0
     ◉ Goal:
          ○ find the radius of convergence.
          ○ find the interval of convergence.
     ◉ Use:
          ○ Ratio Test.

● [1:14:19]. Ratio Test setup.
     ◉ Let:
          ○ 𝒂ₙ = 𝒙ⁿ/𝒏
     ◉ Then:
          ○ 𝒂ₙ₊₁ = 𝒙ⁿ⁺¹/(𝒏 + 1)
     ◉ Compute:
          ○ 𝑳 = limₙ→∞ |𝒂ₙ₊₁/𝒂ₙ|

● [1:15:17]. Simplify the ratio.
     ◉ Substitute:
          ○ 𝑳 = limₙ→∞ |[𝒙ⁿ⁺¹/(𝒏 + 1)] / [𝒙ⁿ/𝒏]|
     ◉ Reciprocate and multiply:
          ○ 𝑳 = limₙ→∞ |[𝒙ⁿ⁺¹/(𝒏 + 1)] ⋅ [𝒏/𝒙ⁿ]|
     ◉ Simplify powers:
          ○ 𝒙ⁿ⁺¹/𝒙ⁿ = 𝒙
     ◉ Then:
          ○ 𝑳 = limₙ→∞ |[𝒏/(𝒏 + 1)] ⋅ 𝒙|
     ◉ Since:
          ○ 𝒏/(𝒏 + 1) > 0
     ◉ We can write:
          ○ 𝑳 = limₙ→∞ [𝒏/(𝒏 + 1)] |𝒙|
     ◉ Since:
          ○ limₙ→∞ 𝒏/(𝒏 + 1) = 1
     ◉ Therefore:
          ○ 𝑳 = |𝒙|

● [1:18:17]. Apply the Ratio Test condition.
     ◉ Ratio Test convergence requires:
          ○ 𝑳 < 1
     ◉ Since:
          ○ 𝑳 = |𝒙|
     ◉ We need:
          ○ |𝒙| < 1
     ◉ Therefore:
          ○ -1 < 𝒙 < 1
     ◉ This gives the preliminary interval:
          ○ (-1,1)

● [1:20:18]. Radius of convergence.
     ◉ From:
          ○ |𝒙| < 1
     ◉ Radius:
          ○ 𝑹 = 1
     ◉ Center:
          ○ 𝑪 = 0
     ◉ Meaning:
          ○ the series converges for all 𝒙 inside distance 1 from the center.
          ○ the Ratio Test does not decide the endpoints.

● [1:22:12]. Check the endpoint 𝒙 = -1.
     ◉ Plug into the original power series:
          ○ ∑[𝒏=1,∞] 𝒙ⁿ/𝒏
     ◉ If 𝒙 = -1
          ○ Then ∑[𝒏=1,∞] (-1)ⁿ/𝒏
     ◉ This is the alternating harmonic series.
     ◉ It converges by:
          ○ Alternating Series Test.
     ◉ Therefore:
          ○ 𝒙 = -1 is included.

● [1:25:05]. Check the endpoint 𝒙 = 1.
     ◉ Plug into the original power series:
          ○ ∑[𝒏=1,∞] 𝒙ⁿ/𝒏
     ◉ If:
          ○ 𝒙 = 1
     ◉ Then:
          ○ ∑[𝒏=1,∞] 1/𝒏
     ◉ This is the harmonic series.
     ◉ The harmonic series diverges.
     ◉ Therefore:
          ○ 𝒙 = 1 is not included.

● [1:26:35]. Final interval for Example 3.
     ◉ Radius:
          ○ 𝑹 = 1
     ◉ Center:
          ○ 𝑪 = 0
     ◉ Interval of convergence:
          ○ [-1,1)
     ◉ Meaning:
          ○ the power series converges at -1.
          ○ it diverges at 1.
          ○ it converges for every 𝒙 between -1 and 1.

● N̲O̲T̲E̲ — Key idea.
     ◉ The Ratio Test gives:
          ○ |𝒙| < 1
     ◉ This tells us the open interval:
          ○ (-1,1)
     ◉ But the endpoints must be checked separately.
     ◉ At 𝒙 = -1:
          ○ the series becomes alternating harmonic,
          ○ so it converges.
     ◉ At 𝒙 = 1:
          ○ the series becomes harmonic,
          ○ so it diverges.
     ◉ Therefore:
          ○ left endpoint included.
          ○ right endpoint excluded.



５．１．４ - Ｅｘａｍｐｌｅ　４

● [1:28:30]. 🧩 Example 4 — Power series centered at 2: ∑[𝒏=1,∞] (𝒙 - 2)ⁿ/(𝒏² ⋅ 3ⁿ)
     ◉ Given:
          ○ ∑[𝒏=1,∞] (𝒙 - 2)ⁿ/(𝒏² ⋅ 3ⁿ)
     ◉ This is a power series because:
          ○ it contains (𝒙 - 2) raised to the power 𝒏.
     ◉ Therefore:
          ○ center = 2
               ■ if it converges, the interval of convergence will be centered at 2.
     ◉ Use:
          ○ Ratio Test.

● [1:29:34]. Ratio Test setup.
     ◉ Let:
          ○ 𝒂ₙ = (𝒙 - 2)ⁿ/(𝒏² ⋅ 3ⁿ)
     ◉ Then:
          ○ 𝒂ₙ₊₁ = (𝒙 - 2)ⁿ⁺¹/((𝒏 + 1)² ⋅ 3ⁿ⁺¹)
     ◉ Compute:
          ○ 𝑳 = limₙ→∞ |𝒂ₙ₊₁/𝒂ₙ|

● [1:30:10]. Build the ratio.
     ◉ Substitute:
          ○ 𝑳 = limₙ→∞ |[(𝒙 - 2)ⁿ⁺¹/((𝒏 + 1)² ⋅ 3ⁿ⁺¹)] / [(𝒙 - 2)ⁿ/(𝒏² ⋅ 3ⁿ)]|
     ◉ Reciprocate and multiply:
          ○ 𝑳 = limₙ→∞ |[(𝒙 - 2)ⁿ⁺¹/((𝒏 + 1)² ⋅ 3ⁿ⁺¹)] ⋅ [(𝒏² ⋅ 3ⁿ)/(𝒙 - 2)ⁿ]|

● [1:32:00]. Simplify the ratio.
     ◉ Simplify powers of (𝒙 - 2):
          ○ (𝒙 - 2)ⁿ⁺¹/(𝒙 - 2)ⁿ = 𝒙 - 2
     ◉ Simplify powers of 3:
          ○ 3ⁿ/3ⁿ⁺¹ = 1/3
     ◉ Keep the polynomial factor:
          ○ 𝒏²/(𝒏 + 1)²
     ◉ Therefore:
          ○ 𝑳 = limₙ→∞ |[(𝒙 - 2)𝒏²]/[3(𝒏 + 1)²]|

● [1:33:22]. Separate the 𝒏-part from the 𝒙-part.
     ◉ Rewrite:
          ○ 𝑳 = limₙ→∞ [𝒏²/(𝒏 + 1)²] ⋅ |(𝒙 - 2)/3|
     ◉ Since:
          ○ limₙ→∞ 𝒏²/(𝒏 + 1)² = 1
     ◉ Then:
          ○ 𝑳 = |𝒙 - 2|/3

● [1:34:35]. Apply the Ratio Test.
     ◉ Ratio Test convergence requires:
          ○ 𝑳 < 1
     ◉ Since:
          ○ 𝑳 = |𝒙 - 2|/3
     ◉ We need:
          ○ |𝒙 - 2|/3 < 1
     ◉ Multiply by 3:
          ○ |𝒙 - 2| < 3
     ◉ Therefore:
          ○ radius of convergence 𝑹 = 3

● [1:35:58]. Solve the interval.
     ◉ Start with:
          ○ |𝒙 - 2| < 3
     ◉ Equivalent:
          ○ -3 < 𝒙 - 2 < 3
     ◉ Add 2:
          ○ -1 < 𝒙 < 5
     ◉ Preliminary interval:
          ○ (-1,5)
     ◉ Important:
          ○ this is only the open interval.
          ○ the endpoints must still be checked separately.

● [1:37:17]. Check endpoint 𝒙 = -1.
     ◉ Plug into the original power series:
          ○ ∑[𝒏=1,∞] (𝒙 - 2)ⁿ/(𝒏² ⋅ 3ⁿ)
     ◉ If:
          ○ 𝒙 = -1
     ◉ Then:
          ○ 𝒙 - 2 = -3
     ◉ So:
          ○ ∑[𝒏=1,∞] (-3)ⁿ/(𝒏² ⋅ 3ⁿ)
     ◉ Simplify:
          ○ (-3)ⁿ/3ⁿ = (-1)ⁿ
     ◉ Therefore:
          ○ ∑[𝒏=1,∞] (-1)ⁿ/𝒏²
     ◉ This series converges by:
          ○ Alternating Series Test.
     ◉ Therefore:
          ○ 𝒙 = -1 is included.

● [1:39:36]. Check endpoint 𝒙 = 5.
     ◉ Plug into the original power series:
          ○ ∑[𝒏=1,∞] (𝒙 - 2)ⁿ/(𝒏² ⋅ 3ⁿ)
     ◉ If:
          ○ 𝒙 = 5
     ◉ Then:
          ○ 𝒙 - 2 = 3
     ◉ So:
          ○ ∑[𝒏=1,∞] 3ⁿ/(𝒏² ⋅ 3ⁿ)
     ◉ Simplify:
          ○ 3ⁿ/3ⁿ = 1
     ◉ Therefore:
          ○ ∑[𝒏=1,∞] 1/𝒏²
     ◉ This is a 𝒑-series with:
          ○ 𝒑 = 2
     ◉ Since:
          ○ 2 > 1
     ◉ The series converges.
     ◉ Therefore:
          ○ 𝒙 = 5 is included.

● [1:40:52]. Final interval for Example 4.
     ◉ Radius:
          ○ 𝑹 = 3
     ◉ Center:
          ○ 𝑪 = 2
     ◉ Interval of convergence:
          ○ [-1,5]
     ◉ Check:
          ○ 2 is exactly the midpoint of -1 and 5.
     ◉ Meaning:
          ○ the power series converges from -1 to 5,
          ○ including both endpoints.

● N̲O̲T̲E̲ — Key idea.
     ◉ The Ratio Test gives:
          ○ |𝒙 - 2| < 3
     ◉ This means:
          ○ center = 2
          ○ radius = 3
     ◉ So the open interval is:
          ○ (2 - 3, 2 + 3) = (-1,5)
     ◉ Then we check endpoints:
          ○ at 𝒙 = -1, the series becomes ∑ (-1)ⁿ/𝒏² and converges.
          ○ at 𝒙 = 5, the series becomes ∑ 1/𝒏² and converges.
     ◉ Therefore:
          ○ both endpoints are included.
          ○ final interval = [-1,5].



５．１．５  - Ｅｘａｍｐｌｅ　５

● [1:41:21]. 🧩 Example 5 — Endpoint behavior with square roots: ∑[𝒏=0,∞] (-1)ⁿ2ⁿ𝒙ⁿ/√(𝒏 + 1)
     ◉ Given:
          ○ ∑[𝒏=0,∞] (-1)ⁿ2ⁿ𝒙ⁿ/√(𝒏 + 1)
     ◉ This is a power series centered at:
          ○ 0
     ◉ Goal:
          ○ find the radius of convergence.
          ○ find the interval of convergence.
     ◉ Use:
          ○ Ratio Test.

● [1:43:20]. Ratio Test setup.
     ◉ Let:
          ○ 𝒂ₙ = (-1)ⁿ2ⁿ𝒙ⁿ/√(𝒏 + 1)
     ◉ Then:
          ○ 𝒂ₙ₊₁ = (-1)ⁿ⁺¹2ⁿ⁺¹𝒙ⁿ⁺¹/√(𝒏 + 2)
     ◉ Compute:
          ○ 𝑳 = limₙ→∞ |𝒂ₙ₊₁/𝒂ₙ|

● [1:44:31]. Build the ratio.
     ◉ Substitute:
          ○ 𝑳 = limₙ→∞ |[(-1)ⁿ⁺¹2ⁿ⁺¹𝒙ⁿ⁺¹/√(𝒏 + 2)] / [(-1)ⁿ2ⁿ𝒙ⁿ/√(𝒏 + 1)]|
     ◉ Reciprocate and multiply:
          ○ 𝑳 = limₙ→∞ |[(-1)ⁿ⁺¹2ⁿ⁺¹𝒙ⁿ⁺¹/√(𝒏 + 2)] ⋅ [√(𝒏 + 1)/((-1)ⁿ2ⁿ𝒙ⁿ)]|

● [1:46:25]. Simplify the ratio.
     ◉ The absolute value removes:
          ○ (-1)ⁿ⁺¹/(-1)ⁿ
     ◉ Simplify powers of 2:
          ○ 2ⁿ⁺¹/2ⁿ = 2
     ◉ Simplify powers of 𝒙:
          ○ 𝒙ⁿ⁺¹/𝒙ⁿ = 𝒙
     ◉ Keep the square-root factor:
          ○ √(𝒏 + 1)/√(𝒏 + 2)
     ◉ Therefore:
          ○ 𝑳 = limₙ→∞ |2𝒙 ⋅ √(𝒏 + 1)/√(𝒏 + 2)|

● [1:47:45]. Separate the 𝒏-part from the 𝒙-part.
     ◉ Rewrite:
          ○ 𝑳 = limₙ→∞ √((𝒏 + 1)/(𝒏 + 2)) ⋅ 2|𝒙|
     ◉ Since:
          ○ limₙ→∞ √((𝒏 + 1)/(𝒏 + 2)) = 1
     ◉ Then:
          ○ 𝑳 = 2|𝒙|

● [1:48:34]. Apply Ratio Test condition.
     ◉ Ratio Test convergence requires:
          ○ 𝑳 < 1
     ◉ Since:
          ○ 𝑳 = 2|𝒙|
     ◉ We need:
          ○ 2|𝒙| < 1
     ◉ Divide by 2:
          ○ |𝒙| < 1/2
     ◉ Therefore:
          ○ radius of convergence 𝑹 = 1/2
     ◉ Preliminary interval:
          ○ -1/2 < 𝒙 < 1/2
     ◉ Important:
          ○ the endpoints must still be checked separately.

● [1:50:30]. Check endpoint 𝒙 = -1/2.
     ◉ Plug into the original power series:
          ○ ∑[𝒏=0,∞] (-1)ⁿ2ⁿ𝒙ⁿ/√(𝒏 + 1)
     ◉ If:
          ○ 𝒙 = -1/2
     ◉ Then:
          ○ ∑[𝒏=0,∞] (-1)ⁿ2ⁿ(-1/2)ⁿ/√(𝒏 + 1)
     ◉ Simplify the signs and powers:
          ○ (-1)ⁿ2ⁿ(-1/2)ⁿ = 1
     ◉ Therefore:
          ○ ∑[𝒏=0,∞] 1/√(𝒏 + 1)

● [1:53:00]. Endpoint 𝒙 = -1/2 — Method 1: Limit Comparison Test.
     ◉ Compare:
          ○ ∑[𝒏=0,∞] 1/√(𝒏 + 1)
     ◉ with:
          ○ ∑[𝒏=1,∞] 1/√𝒏 = ∑[𝒏=1,∞] 1/𝒏¹ᐟ²
     ◉ Compute:
          ○ limₙ→∞ [1/√(𝒏 + 1)] / [1/√𝒏]
     ◉ Simplify:
          ○ limₙ→∞ √𝒏/√(𝒏 + 1)
          ○ = limₙ→∞ √(𝒏/(𝒏 + 1))
          ○ = 1
     ◉ Since the limit is finite and positive:
          ○ both series have the same behavior.
     ◉ But:
          ○ ∑[𝒏=1,∞] 1/𝒏¹ᐟ² diverges,
               ■ because it is a 𝒑-series with 𝒑 = 1/2 ≤ 1.
     ◉ Therefore:
          ○ ∑[𝒏=0,∞] 1/√(𝒏 + 1) diverges.

● [1:56:29]. Endpoint 𝒙 = -1/2 — Method 2: Reindexing the series.
     ◉ The series is:
          ○ ∑[𝒏=0,∞] 1/√(𝒏 + 1)
     ◉ Let:
          ○ 𝒌 = 𝒏 + 1
     ◉ When:
          ○ 𝒏 = 0,
          ○ 𝒌 = 1.
     ◉ Therefore:
          ○ ∑[𝒏=0,∞] 1/√(𝒏 + 1)
          ○ = ∑[𝒌=1,∞] 1/√𝒌
     ◉ This is:
          ○ ∑[𝒌=1,∞] 1/𝒌¹ᐟ²
     ◉ Since:
          ○ 𝒑 = 1/2 ≤ 1
     ◉ The 𝒑-series diverges.
     ◉ Therefore:
          ○ 𝒙 = -1/2 is not included.

● [1:59:03]. Check endpoint 𝒙 = 1/2.
     ◉ Plug into the original power series:
          ○ ∑[𝒏=0,∞] (-1)ⁿ2ⁿ𝒙ⁿ/√(𝒏 + 1)
     ◉ If:
          ○ 𝒙 = 1/2
     ◉ Then:
          ○ ∑[𝒏=0,∞] (-1)ⁿ2ⁿ(1/2)ⁿ/√(𝒏 + 1)
     ◉ Simplify:
          ○ 2ⁿ(1/2)ⁿ = 1
     ◉ Therefore:
          ○ ∑[𝒏=0,∞] (-1)ⁿ/√(𝒏 + 1)

● [1:59:40]. Endpoint 𝒙 = 1/2 — Alternating Series Test.
     ◉ Positive part:
          ○ 𝒂ₙ = 1/√(𝒏 + 1)
     ◉ Check the limit:
          ○ limₙ→∞ 1/√(𝒏 + 1) = 0
     ◉ Check decreasing:
          ○ 𝒂ₙ₊₁ = 1/√(𝒏 + 2)
          ○ 1/√(𝒏 + 2) < 1/√(𝒏 + 1) = 𝒂ₙ
     ◉ Therefore:
          ○ 𝒂ₙ is decreasing.
     ◉ By the Alternating Series Test:
          ○ ∑[𝒏=0,∞] (-1)ⁿ/√(𝒏 + 1) converges.
     ◉ Therefore:
          ○ 𝒙 = 1/2 is included.

● [2:01:02]. Final interval for Example 5.
     ◉ Radius:
          ○ 𝑹 = 1/2
     ◉ Center:
          ○ 𝑪 = 0
     ◉ Interval of convergence:
          ○ (-1/2,1/2]
     ◉ Meaning:
          ○ the series diverges at -1/2.
          ○ the series converges at 1/2.
          ○ the series converges for every 𝒙 between -1/2 and 1/2.

● N̲O̲T̲E̲ — Key idea.
     ◉ The Ratio Test gives:
          ○ |𝒙| < 1/2
     ◉ This gives the open interval:
          ○ (-1/2,1/2)
     ◉ At the left endpoint:
          ○ the signs cancel,
          ○ leaving a positive divergent 𝒑-series.
     ◉ At the right endpoint:
          ○ the series remains alternating,
          ○ and converges by the Alternating Series Test.
     ◉ Therefore:
          ○ left endpoint excluded.
          ○ right endpoint included.
          ○ final interval = (-1/2,1/2].






６ - Ｃａｌｃｕｌｕｓ　ｏｆ　Ｐｏｗｅｒ　Ｓｅｒｉｅｓ

● [2:03:14]. Calculus of power series.
     ◉ We can perform calculus operations on power series:
          ○ derivatives.
          ○ integrals.
     ◉ Main idea:
          ○ differentiate or integrate term by term.

● [2:04:24]. Start with a general power series.
     ◉ Suppose:
          ○ 𝒇(𝒙) = ∑[𝒏=0,∞] 𝒂ₙ(𝒙 - 𝑪)ⁿ
     ◉ Expanded:
          ○ 𝒇(𝒙) = 𝒂₀ + 𝒂₁(𝒙 - 𝑪) + 𝒂₂(𝒙 - 𝑪)² + 𝒂₃(𝒙 - 𝑪)³ + ...



６.1 - Ｄｅｒｉｖａｔｉｖｅｓ　ｏｆ　Ｐｏｗｅｒ　Ｓｅｒｉｅｓ

● [2:05:50]. Derivative term by term.
     ◉ Since:
          ○ each 𝒂ₙ is a constant,
     ◉ we can differentiate term by term.
     ◉ The variable part is:
          ○ (𝒙 - 𝑪)ⁿ

● [2:06:39]. Apply the power rule and chain rule.
     ◉ Derivative of the first term:
          ○ 𝒂₀ → 0
     ◉ Derivative of the second term:
          ○ 𝒂₁(𝒙 - 𝑪) → 𝒂₁
     ◉ Derivative of the third term:
          ○ 𝒂₂(𝒙 - 𝑪)² → 2𝒂₂(𝒙 - 𝑪)
     ◉ Derivative of the fourth term:
          ○ 𝒂₃(𝒙 - 𝑪)³ → 3𝒂₃(𝒙 - 𝑪)²

● [2:9:45]. General derivative formula.
     ◉ Starting from:
          ○ 𝒇(𝒙) = ∑[𝒏=0,∞] 𝒂ₙ(𝒙 - 𝑪)ⁿ
     ◉ Then:
          ○ 𝒇′(𝒙) = ∑[𝒏=1,∞] 𝒏𝒂ₙ(𝒙 - 𝑪)ⁿ⁻¹
     ◉ Important:
          ○ the derivative starts at 𝒏 = 1.
     ◉ Reason:
          ○ the 𝒏 = 0 term is constant,
          ○ so its derivative is 0.



６.2 - Ｉｎｔｅｇｒａｌｓ　ｏｆ　Ｐｏｗｅｒ　Ｓｅｒｉｅｓ

● [2:12:35]. Integral term by term.
     ◉ We can integrate a power series term by term.
     ◉ Starting from:
          ○ 𝒇(𝒙) = ∑[𝒏=0,∞] 𝒂ₙ(𝒙 - 𝑪)ⁿ
     ◉ Each term integrates using:
          ○ power rule for integrals.

● [2:14:50]. General integral formula.
     ◉ The integral is:
          ○ ∫ 𝒇(𝒙) ⋅ 𝒅𝑥 = 𝑲 + ∑[𝒏=0,∞] 𝒂ₙ(𝒙 - 𝑪)ⁿ⁺¹/(𝒏 + 1)
     ◉ Important:
          ○ include the constant of integration.
     ◉ The series still starts at:
          ○ 𝒏 = 0

● N̲O̲T̲E̲ — Endpoints may change.
     ◉ Differentiating or integrating a power series:
          ○ keeps the same radius of convergence.
     ◉ But:
          ○ endpoint behavior may change.
     ◉ A derivative can lose endpoints.
     ◉ An integral can gain endpoints.
     ◉ Therefore:
          ○ endpoints must be checked separately when needed.




６. ３  -  Ａｐｐｌｉｃａｔｉｏｎ: Ｐｏｗｅｒ　Ｓｅｒｉｅｓ　Ｆｏｒ　Ｌｎ（１－𝒙）

● [2:17:26]. 🧩 Application — Find a power series representation for Ln(1 - 𝒙).
     ◉ Goal:
          ○ find a power series representation for:
               ■ Ln(1 - 𝒙)
     ◉ Interval:
          ○ -1 < 𝒙 < 1
     ◉ Main idea:
          ○ start from a known power series,
          ○ then integrate term by term to create the logarithm.

● [2:17:49]. Choosing the starting function.
     ◉ We want:
          ○ Ln(1 - 𝒙)
     ◉ Leonard’s strategy:
          ○ look for a simpler function whose integral gives Ln(1 - 𝒙).
     ◉ Since:
          ○ the integral of 1/(1 - 𝒙) is very close to Ln(1 - 𝒙),
     ◉ We start with:
          ○ 1/(1 - 𝒙)
     ◉ Important:
          ○ ∫ 1/(1 - 𝒙) ⋅ 𝒅𝒙 = -Ln(1 - 𝒙)
     ◉ The negative sign appears because:
          ○ the derivative of 1 - 𝒙 is -1.

● [2:18:36]. Why 1/(1 - 𝒙) is useful.
     ◉ The function:
          ○ 1/(1 - 𝒙)
     ◉ is the sum of a geometric power series.
     ◉ Geometric series formula:
          ○ 1/(1 - 𝒓) = 1 + 𝒓 + 𝒓² + 𝒓³ + ...
     ◉ In this case:
          ○ 𝒓 = 𝒙
     ◉ Therefore:
          ○ 1/(1 - 𝒙) = 1 + 𝒙 + 𝒙² + 𝒙³ + ...
     ◉ Series notation:
          ○ 1/(1 - 𝒙) = ∑[𝒏=0,∞] 𝒙ⁿ
          ○ or equivalently:
          ○ 1/(1 - 𝒙) = ∑[𝒏=1,∞] 𝒙ⁿ⁻¹

● [2:21:58]. Why the interval is (-1,1).
     ◉ This interval comes from the geometric series.
     ◉ A geometric series converges when:
          ○ |𝒓| < 1
     ◉ Here:
          ○ 𝒓 = 𝒙
     ◉ Therefore:
          ○ |𝒙| < 1
     ◉ Equivalent:
          ○ -1 < 𝒙 < 1
     ◉ Meaning:
          ○ the power series for 1/(1 - 𝒙) is valid only on (-1,1).
     ◉ Since we are using that power series as our starting point,
          ○ the representation for Ln(1 - 𝒙) is also built on this interval.

● [2:24:49]. Integrate both sides.
     ◉ Start with:
          ○ 1/(1 - 𝒙) = 1 + 𝒙 + 𝒙² + 𝒙³ + ...
     ◉ Integrate both sides:
          ○ ∫ 1/(1 - 𝒙) ⋅ 𝒅𝒙 = ∫(1 + 𝒙 + 𝒙² + 𝒙³ + ...) ⋅ 𝒅𝒙
     ◉ Left side:
          ○ ∫ 1/(1 - 𝒙) ⋅ 𝒅𝒙 = -Ln(1 - 𝒙)
     ◉ Right side:
          ○ ∫(1 + 𝒙 + 𝒙² + 𝒙³ + ...) ⋅ 𝒅𝒙
          ○ = 𝒙 + 𝒙²/2 + 𝒙³/3 + 𝒙⁴/4 + ... + 𝑲

● [2:26:17]. Solve for Ln(1 - 𝒙).
     ◉ We have:
          ○ -Ln(1 - 𝒙) = 𝒙 + 𝒙²/2 + 𝒙³/3 + 𝒙⁴/4 + ... + 𝑲
     ◉ Multiply by -1:
          ○ Ln(1 - 𝒙) = -𝒙 - 𝒙²/2 - 𝒙³/3 - 𝒙⁴/4 - ... - 𝑲

● [2:27:02]. Determine the constant.
     ◉ Plug in:
          ○ 𝒙 = 0
     ◉ Left side:
          ○ Ln(1 - 0) = Ln(1) = 0
     ◉ Right side:
          ○ all terms with 𝒙 become 0.
     ◉ Therefore:
          ○ 0 = -𝑲
     ◉ So:
          ○ 𝑲 = 0

● [2:27:31]. Final power series representation.
     ◉ Therefore:
          ○ Ln(1 - 𝒙) = -𝒙 - 𝒙²/2 - 𝒙³/3 - 𝒙⁴/4 - ...
     ◉ Factor the negative sign:
          ○ Ln(1 - 𝒙) = -(𝒙 + 𝒙²/2 + 𝒙³/3 + 𝒙⁴/4 + ...)
     ◉ Series notation:
          ○ Ln(1 - 𝒙) = -∑[𝒏=1,∞] 𝒙ⁿ/𝒏
     ◉ Valid on:
          ○ (-1,1)

● N̲O̲T̲E̲ 1 — Why this method works.
     ◉ We do not invent the logarithm series from nothing.
     ◉ We start from the geometric power series:
          ○ 1/(1 - 𝒙) = ∑[𝒏=0,∞] 𝒙ⁿ
     ◉ Then we integrate term by term.
     ◉ Integrating 1/(1 - 𝒙) produces:
          ○ -Ln(1 - 𝒙)
     ◉ Integrating the power series produces:
          ○ 𝒙 + 𝒙²/2 + 𝒙³/3 + 𝒙⁴/4 + ...
     ◉ Therefore:
          ○ Ln(1 - 𝒙) = -∑[𝒏=1,∞] 𝒙ⁿ/𝒏

● N̲O̲T̲E̲ 2 — Meaning of the interval.
     ◉ The interval (-1,1) comes from the geometric series.
     ◉ Since:
          ○ 1/(1 - 𝒙) = ∑[𝒏=0,∞] 𝒙ⁿ
     ◉ only when:
          ○ |𝒙| < 1
     ◉ The integrated series representation is valid on the same open interval:
          ○ -1 < 𝒙 < 1
     ◉ Key idea:
          ○ a power series represents a function only where the series converges.