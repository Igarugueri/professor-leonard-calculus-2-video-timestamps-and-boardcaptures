-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ９．８： Ｒｅｐｒｅｓｅｎｔａｔｉｏｎ ｏｆ Ｆｕｎｃｔｉｏｎｓ ｂｙ Ｔａｙｌｏｒ Ｓｅｒｉｅｓ ａｎｄ Ｍａｃｌａｕｒｅｎ Ｓｅｒｉｅｓ**----------------------------------






１ - Ｔａｙｌｏｒ　ａｎｄ　Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ:　Ｔｈｅｏｒｙ

● [0:00]. Introduction — Representing functions with power series.
     ◉ Main idea:
          ○ we want to represent a function using a power series.
     ◉ Instead of only studying whether a series converges,
          ○ now we use series to build functions.
     ◉ Big goal:
          ○ take a function 𝒇(𝒙),
          ○ and write it as an infinite polynomial-like expression.

● [0:19]. Suppose 𝒇 has a power series representation.
     ◉ Basic assumption:
          ○ 𝒇 can be represented by a power series around a center 𝑪.
     ◉ In other words:
          ○ we assume that 𝒇 behaves like an infinite polynomial centered at 𝑪.
     ◉ This means:
          ○ the function is built from powers of (𝒙 - 𝑪).
     ◉ The center 𝑪 is the point around which the series is organized.


１．１ - Ｐｏｗｅｒ　Ｓｅｒｉｅｓ　Ｒｅｐｒｅｓｅｎｔａｔｉｏｎ

● [0:52]. General power series representation.
     ◉ Form:
          ○ 𝒇(𝒙) = ∑[𝒏=0,∞] 𝒂ₙ(𝒙 - 𝑪)ⁿ
     ◉ Expanded form:
          ○ 𝒇(𝒙) = 𝒂₀ + 𝒂₁(𝒙 - 𝑪) + 𝒂₂(𝒙 - 𝑪)² + 𝒂₃(𝒙 - 𝑪)³ + ... + 𝒂ₙ(𝒙 - 𝑪)ⁿ + ...
     ◉ Meaning:
          ○ 𝑪 is the center.
          ○ 𝒂ₙ are the coefficients.
          ○ (𝒙 - 𝑪)ⁿ gives the power-series structure.
     ◉ Important:
          ○ this looks like a polynomial,
          ○ but it has infinitely many terms.
     ◉ Each coefficient 𝒂ₙ controls:
          ○ the size of the term with power 𝒏.
     ◉ Each power (𝒙 - 𝑪)ⁿ measures:
          ○ how far 𝒙 is from the center 𝑪.


１．２ - Ｅｘｉｓｔｅｎｃｅ　ｏｆ　Ｄｅｒｉｖａｔｉｖｅｓ

● [1:40]. Requirement of differentiability.
     ◉ If 𝒇 has a power series representation,
          ○ then all the way to the 𝒏-th derivative of 𝒇 must exist at 𝑪.
     ◉ Symbolically:
          ○ 𝒇⁽ⁿ⁾(𝑪) exists.
     ◉ Reason:
          ○ a power series contains powers of (𝒙 - 𝑪).
     ◉ Since powers can be differentiated repeatedly,
          ○ the function represented by the power series must also allow repeated differentiation.
     ◉ Key idea:
          ○ if the series has terms up to power 𝒏,
          ○ then taking derivatives up to order 𝒏 makes sense.
     ◉ Therefore:
          ○ Taylor series are deeply connected to derivatives.


１．３ - Ｆｉｎｄｉｎｇ　ｔｈｅ　Ｃｏｅｆｆｉｃｉｅｎｔｓ　𝒂ₙ

● [5:05]. Goal — determine the coefficients 𝒂ₙ.
     ◉ We want:
          ○ a formula for 𝒂ₙ in terms of derivatives of 𝒇.
     ◉ Why:
          ○ if we can find every 𝒂ₙ,
          ○ then we can build the whole power series for 𝒇.
     ◉ The coefficients are not random:
          ○ they are determined by the values of 𝒇 and its derivatives at the center 𝑪.

● [5:35]. Start from the expanded power series.
     ◉ Write:
          ○ 𝒇(𝒙) = 𝒂₀ + 𝒂₁(𝒙 - 𝑪) + 𝒂₂(𝒙 - 𝑪)² + 𝒂₃(𝒙 - 𝑪)³ + ... + 𝒂ₙ(𝒙 - 𝑪)ⁿ + ...
     ◉ This allows us to see:
          ○ what happens to each term when we differentiate.
     ◉ The key is to track:
          ○ which term becomes a constant after enough derivatives.

● [7:40]. Take derivatives term by term.
     ◉ First derivative:
          ○ 𝒇'(𝒙) = 𝒂₁ + 2𝒂₂(𝒙 - 𝑪) + 3𝒂₃(𝒙 - 𝑪)² + ... + 𝒏𝒂ₙ(𝒙 - 𝑪)ⁿ⁻¹ + ...
     ◉ Second derivative:
          ○ 𝒇''(𝒙) = 2⋅1𝒂₂ + 3⋅2𝒂₃(𝒙 - 𝑪) + ... + 𝒏(𝒏 - 1)𝒂ₙ(𝒙 - 𝑪)ⁿ⁻² + ...
     ◉ Third derivative:
          ○ 𝒇'''(𝒙) = 3⋅2⋅1𝒂₃ + ... + 𝒏(𝒏 - 1)(𝒏 - 2)𝒂ₙ(𝒙 - 𝑪)ⁿ⁻³ + ...
     ◉ Pattern:
          ○ every derivative lowers the power by 1.
          ○ every derivative brings down one more factor.
     ◉ Therefore:
          ○ the 𝒏-th derivative eventually brings down all factors from 𝒏 to 1.

● [12:19]. Factorial pattern.
     ◉ Repeated differentiation produces:
          ○ 𝒏(𝒏 - 1)(𝒏 - 2)...3⋅2⋅1
     ◉ This is:
          ○ 𝒏!
     ◉ Meaning:
          ○ factorials appear naturally because derivatives keep bringing down powers.
     ◉ Example idea:
          ○ differentiating (𝒙 - 𝑪)ⁿ once gives 𝒏(𝒙 - 𝑪)ⁿ⁻¹.
          ○ differentiating again gives 𝒏(𝒏 - 1)(𝒙 - 𝑪)ⁿ⁻².
          ○ after 𝒏 derivatives, the power becomes 0:(𝒙 - 𝑪)ⁿ⁻ⁿ
     ◉ Since:
          ○ (𝒙 - 𝑪)⁰ = 1
     ◉ The remaining coefficient is:
          ○ 𝒏!𝒂ₙ

● [13:50]. What happens to the 𝒏-th term.
     ◉ Start with the 𝒏-th term:
          ○ 𝒂ₙ(𝒙 - 𝑪)ⁿ
     ◉ After one derivative:
          ○ 𝒏𝒂ₙ(𝒙 - 𝑪)ⁿ⁻¹
     ◉ After two derivatives:
          ○ 𝒏(𝒏 - 1)𝒂ₙ(𝒙 - 𝑪)ⁿ⁻²
     ◉ After three derivatives:
          ○ 𝒏(𝒏 - 1)(𝒏 - 2)𝒂ₙ(𝒙 - 𝑪)ⁿ⁻³
     ◉ After 𝒏 derivatives:
          ○ 𝒏!𝒂ₙ
     ◉ Important:
          ○ the 𝒏-th term becomes a constant after exactly 𝒏 derivatives.

● [16:50]. Evaluate at the center 𝑪.
     ◉ When 𝒙 = 𝑪:
          ○ every term containing (𝒙 - 𝑪) becomes 0.
     ◉ Reason:
          ○ 𝑪 - 𝑪 = 0
     ◉ Therefore:
          ○ all terms that still contain a positive power of (𝒙 - 𝑪) vanish.
     ◉ The only surviving term is:
          ○ 𝒏!𝒂ₙ
     ◉ This is the key trick:
          ○ differentiating enough times isolates 𝒂ₙ.
     ◉ Therefore:
          ○ 𝒇⁽ⁿ⁾(𝑪) = 𝒏!𝒂ₙ

● [18:17]. Solve for the coefficient.
     ◉ From:
          ○ 𝒇⁽ⁿ⁾(𝑪) = 𝒏!𝒂ₙ
     ◉ Divide by 𝒏!:
          ○ 𝒂ₙ = 𝒇⁽ⁿ⁾(𝑪) / 𝒏!
     ◉ This is the central result:
          ○ every coefficient 𝒂ₙ is determined by the 𝒏-th derivative of 𝒇 at the center.
     ◉ Meaning:
          ○ the derivatives of 𝒇 at 𝑪 encode the whole power series.


１．４ - Ｔａｙｌｏｒ　Ｓｅｒｉｅｓ　Ｆｏｒｍｕｌａ

● [20:46]. Taylor series formula. 
     ◉ Substitute:
          ○ 𝒂ₙ = 𝒇⁽ⁿ⁾(𝑪) / 𝒏!
     ◉ Into:
          ○ 𝒇(𝒙) = ∑[𝒏=0,∞] 𝒂ₙ(𝒙 - 𝑪)ⁿ
     ◉ Taylor series:
          ○ 𝒇(𝒙) = ∑[𝒏=0,∞] [𝒇⁽ⁿ⁾(𝑪) / 𝒏!] (𝒙 - 𝑪)ⁿ
     ◉ Meaning:
          ○ Taylor series rebuilds 𝒇 from its derivatives at 𝑪.
     ◉ Each term uses:
          ○ one derivative value,
          ○ one factorial,
          ○ one power of (𝒙 - 𝑪).

● [21:43]. Expanded Taylor series.
     ◉ First terms:
          ○ 𝒇(𝑪)
          ○ + 𝒇'(𝑪)(𝒙 - 𝑪)
          ○ + (𝒇''(𝑪)·(𝒙 - 𝑪)²)/2!
          ○ + (𝒇'''(𝑪)·(𝒙 - 𝑪)³)/3!
          ○ + ...
     ◉ Interpretation:
          ○ the first term gives the value of the function at the center.
          ○ the second term uses the slope at the center.
          ○ the third term uses curvature information.
          ○ higher terms add more local information about the function.
     ◉ Big idea:
          ○ Taylor series turns derivative information at one point into a full function representation.
          

１．５ - Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　Ｆｏｒｍｕｌａ

● [24:00]. Maclaurin series.
     ◉ A Maclaurin series is:
          ○ a Taylor series centered at 𝑪 = 0.
     ◉ In other words:
          ○ Maclaurin is not a different kind of series.
          ○ it is a special case of the Taylor series.
     ◉ The only change is:
          ○ the center 𝑪 becomes 0.

● [24:38]. Taylor versus Maclaurin.
     ◉ Every Maclaurin series is a Taylor series.
     ◉ But not every Taylor series is a Maclaurin series.
     ◉ Reason:
          ○ Maclaurin is the special case 𝑪 = 0.
     ◉ Analogy:
          ○ every square is a rectangle,
          ○ but not every rectangle is a square.
     ◉ Similarly:
          ○ every Maclaurin series is a Taylor series,
          ○ but only Taylor series centered at 0 are Maclaurin series.

● [25:03]. What changes when 𝑪 = 0.
     ◉ Taylor series:
          ○ 𝒇(𝒙) = ∑[𝒏=0,∞] [𝒇⁽ⁿ⁾(𝑪) / 𝒏!] (𝒙 - 𝑪)ⁿ
     ◉ If:
          ○ 𝑪 = 0
     ◉ Then:
          ○ (𝒙 - 𝑪)ⁿ = (𝒙 - 0)ⁿ
          ○ (𝒙 - 0)ⁿ = 𝒙ⁿ
     ◉ Therefore:
          ○ the formula becomes simpler.

● [25:42]. Maclaurin formula.
     ◉ Since:
          ○ 𝑪 = 0
     ◉ Then:
          ○ 𝒇(𝒙) = ∑[𝒏=0,∞] [𝒇⁽ⁿ⁾(0) / 𝒏!] 𝒙ⁿ
     ◉ Expanded form:
          ○ 𝒇(𝒙) = 𝒇(0)
          ○ + [𝒇'(0) / 1!]𝒙
          ○ + [𝒇''(0) / 2!]𝒙²
          ○ + [𝒇'''(0) / 3!]𝒙³
          ○ + ...
     ◉ Meaning:
          ○ all derivatives are evaluated at 0.
          ○ all powers are powers of 𝒙.
          ○ there is no (𝒙 - 𝑪), because the center is 0.

● N̲O̲T̲E̲ — Main difference.
     ◉ Taylor series:
          ○ centered at any value 𝑪.
     ◉ Maclaurin series:
          ○ centered only at 0.
     ◉ So:
          ○ Taylor uses (𝒙 - 𝑪)ⁿ.
          ○ Maclaurin uses 𝒙ⁿ.






２ - Ｅｘａｍｐｌｅｓ　ｏｆ　Ｔａｙｌｏｒ　ａｎｄ　Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ


２．１ - Ｅｘａｍｐｌｅ 1:　Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　𝓮ˣ

● [28:07]. 🧩 Example 1 — Find the Taylor series for 𝒇(𝒙) = 𝓮ˣ at 𝑪 = 0.
     ◉ Since:
          ○ 𝑪 = 0
     ◉ This is really:
          ○ the Maclaurin series for 𝓮ˣ.

● [29:10]. General method.
     ◉ Steps:
          ○ ❶ Find derivatives of 𝒇 and look for a pattern.
          ○ ❷ Plug in 𝒙 = 𝑪.
          ○ ❸ Set up the series.
          ○ ❹ Find the interval of convergence.

● [30:14]. Step ❶ — Find derivatives.
     ◉ Start with:
          ○ 𝒇(𝒙) = 𝓮ˣ
     ◉ Derivatives:
          ○ 𝒇'(𝒙) = 𝓮ˣ
          ○ 𝒇''(𝒙) = 𝓮ˣ
          ○ 𝒇'''(𝒙) = 𝓮ˣ
          ○ ...
     ◉ Pattern:
          ○ 𝒇⁽ⁿ⁾(𝒙) = 𝓮ˣ
     ◉ Reason:
          ○ every derivative of 𝓮ˣ is still 𝓮ˣ.

● [32:19]. Step ❷ — Plug in 𝒙 = 𝑪.
     ◉ Since:
          ○ 𝑪 = 0
     ◉ Evaluate at 0:
          ○ 𝒇(0) = 𝓮⁰ = 1
          ○ 𝒇'(0) = 𝓮⁰ = 1
          ○ 𝒇''(0) = 𝓮⁰ = 1
          ○ 𝒇'''(0) = 𝓮⁰ = 1
          ○ ...
     ◉ Therefore:
          ○ 𝒇⁽ⁿ⁾(0) = 1

● [34:19]. Step ❸ — Build the Maclaurin series.
     ◉ Maclaurin formula:
          ○ 𝒇(𝒙) = ∑[𝒏=0,∞] [𝒇⁽ⁿ⁾(0) / 𝒏!] 𝒙ⁿ
     ◉ Since:
          ○ 𝒇⁽ⁿ⁾(0) = 1
     ◉ Substitute:
          ○ 𝓮ˣ = ∑[𝒏=0,∞] [1 / 𝒏!] 𝒙ⁿ
     ◉ Therefore:
          ○ 𝓮ˣ = ∑[𝒏=0,∞] 𝒙ⁿ / 𝒏!
     ◉ Expanded form:
          ○ 𝓮ˣ = 1 + 𝒙 + 𝒙²/2! + 𝒙³/3! + 𝒙⁴/4! + ...
     ◉ Meaning:
          ○ each term follows the pattern 𝒙ⁿ/𝒏!.

● [36:35]. Step ❹ — Find the interval of convergence.
     ◉ Use:
          ○ Ratio Test.
     ◉ Reason:
          ○ the series contains 𝒏!.
          ○ factorials usually suggest the Ratio Test.
     ◉ [38:54]. Ratio Test.
          ○ Start with:
               ■ 𝒂ₙ = 𝒙ⁿ/𝒏!
          ○ Then:
               ■ 𝒂ₙ₊₁ = 𝒙ⁿ⁺¹/(𝒏 + 1)!
          ○ Compute:
               ■ 𝑳 = limₙ→∞ |𝒂ₙ₊₁/𝒂ₙ|
          ○ Substitute:
               ■ 𝑳 = limₙ→∞ |[𝒙ⁿ⁺¹/(𝒏 + 1)!] ⋅ [𝒏!/𝒙ⁿ]|
          ○ Simplify:
               ■ 𝒙ⁿ⁺¹/𝒙ⁿ = 𝒙
               ■ 𝒏!/(𝒏 + 1)! = 1/(𝒏 + 1)
          ○ Therefore:
               ■ 𝑳 = limₙ→∞ |𝒙|/(𝒏 + 1)
     ◉ [40:23]. Limit result.
          ○ Since:
               ■ 𝒙 is fixed,
               ■ and 𝒏 + 1 → ∞
          ○ Then:
               ■ |𝒙|/(𝒏 + 1) → 0
          ○ Therefore:
               ■ 𝑳 = 0
          ○ This happens:
               ■ for every real value of 𝒙.
     ◉ [41:15]. Interval of convergence.
          ○ Since:
               ■ 𝑳 = 0 < 1
          ○ By the Ratio Test:
               ■ the series converges for all real 𝒙.
          ○ Therefore:
               ■ interval of convergence is (-∞,∞)
          ○ Radius:
               ■ 𝑹 = ∞

● [42:06]. Final representation.
     ◉ Therefore:
          ○ 𝓮ˣ = ∑[𝒏=0,∞] 𝒙ⁿ/𝒏!
     ◉ On:
          ○ (-∞,∞)
     ◉ Expanded:
          ○ 𝓮ˣ = 1 + 𝒙 + 𝒙²/2! + 𝒙³/3! + 𝒙⁴/4! + ...

● [43:06]. Application — approximating 𝓮².
     ◉ Use:
          ○ 𝓮ˣ = 1 + 𝒙 + 𝒙²/2! + 𝒙³/3! + 𝒙⁴/4! + ...
     ◉ Plug in:
          ○ 𝒙 = 2
     ◉ Then:
          ○ 𝓮² = 1 + 2 + 2²/2! + 2³/3! + 2⁴/4! + ...
     ◉ Meaning:
          ○ the more terms we add,
          ○ the better the approximation of 𝓮².

● N̲O̲T̲E̲ — Why this example is simple.
     ◉ The derivative pattern is immediate:
          ○ every derivative of 𝓮ˣ is 𝓮ˣ.
     ◉ At 𝒙 = 0:
          ○ every derivative equals 1.
     ◉ Therefore:
          ○ the coefficients are especially simple:
               ■ 1/𝒏!


２．２ - Ｅｘａｍｐｌｅ 2:　Ｔａｙｌｏｒ　Ｓｅｒｉｅｓ　ｆｏｒ　Ｌｎ（𝒙）　ｃｅｎｔｅｒｅｄ　ａｔ　𝑪 = 1

● [45:30]. 🧩 Example 2 — Find the Taylor series for 𝒇(𝒙) = Ln(𝒙) centered at 𝑪 = 1.

● [46:41]. Step ❶ — Find derivatives.
     ◉ Start:
          ○ 𝒇(𝒙) = Ln(𝒙)
     ◉ Derivatives:
          ○ 𝒇'(𝒙) = 1/𝒙
          ○ 𝒇''(𝒙) = -1/𝒙²
          ○ 𝒇'''(𝒙) = 2!/𝒙³
          ○ 𝒇⁽⁴⁾(𝒙) = -3!/𝒙⁴
          ○ 𝒇⁽⁵⁾(𝒙) = 4!/𝒙⁵
     ◉ Pattern:
          ○ alternating signs.
          ○ factorial behavior.
          ○ powers of 𝒙 in the denominator.
     ◉ General derivative:
          ○ 𝒇⁽ⁿ⁾(𝒙) = (-1)ⁿ⁻¹(𝒏 - 1)! / 𝒙ⁿ

● [51:59]. Step ❷ — Evaluate at the center 𝑪 = 1.
     ◉ Since:
          ○ 𝒙 = 1
     ◉ The derivative values become:
          ○ 𝒇(1) = 0
          ○ 𝒇'(1) = 1
          ○ 𝒇''(1) = -1!
          ○ 𝒇'''(1) = 2!
          ○ 𝒇⁽⁴⁾(1) = -3!
          ○ 𝒇⁽⁵⁾(1) = 4!
     ◉ Pattern:
          ○ 𝒇⁽ⁿ⁾(1) = (-1)ⁿ⁻¹(𝒏 - 1)!

● [54:59]. Step ❸ — Build and simplify the Taylor series.
     ◉ Taylor formula:
          ○ 𝒇(𝒙) = ∑[𝒏=0,∞] [𝒇⁽ⁿ⁾(𝑪) / 𝒏!] (𝒙 - 𝑪)ⁿ
     ◉ Since:
          ○ 𝑪 = 1
     ◉ Then:
          ○ Ln(𝒙) = ∑[𝒏=1,∞] [𝒇⁽ⁿ⁾(1) / 𝒏!] (𝒙 - 1)ⁿ
     ◉ Substitute:
          ○ 𝒇⁽ⁿ⁾(1) = (-1)ⁿ⁻¹(𝒏 - 1)!
     ◉ Therefore:
          ○ Ln(𝒙) = ∑[𝒏=1,∞] [(-1)ⁿ⁻¹(𝒏 - 1)!(𝒙 - 1)ⁿ] / 𝒏!
     ◉ Simplify:
          ○ (𝒏 - 1)! / 𝒏! = 1/𝒏
     ◉ Final Taylor series:
          ○ Ln(𝒙) = ∑[𝒏=1,∞] [(-1)ⁿ⁻¹(𝒙 - 1)ⁿ] / 𝒏

● [1:00:00]. Step ❹ — Find the interval of convergence.
     ◉ Use:
          ○ Ratio Test.
     ◉ Start with:
          ○ 𝒂ₙ = [(-1)ⁿ⁻¹(𝒙 - 1)ⁿ] / 𝒏
     ◉ Then:
          ○ 𝒂ₙ₊₁ = [(-1)ⁿ(𝒙 - 1)ⁿ⁺¹] / (𝒏 + 1)
     ◉ Compute:
          ○ 𝑳 = limₙ→∞ |𝒂ₙ₊₁/𝒂ₙ|
     ◉ After simplifying:
          ○ 𝑳 = limₙ→∞ [𝒏/(𝒏 + 1)] |𝒙 - 1|
     ◉ Since:
          ○ limₙ→∞ 𝒏/(𝒏 + 1) = 1
     ◉ Therefore:
          ○ 𝑳 = |𝒙 - 1|
     ◉ Apply the Ratio Test condition.
          ○ Ratio Test convergence requires:
               ■ 𝑳 < 1
          ○ Since:
               ■ 𝑳 = |𝒙 - 1|
          ○ We need:
               ■ |𝒙 - 1| < 1
     ◉ Radius and preliminary interval.
          ○ Compare with the standard form:
               ■ |𝒙 - 𝑪| < 𝑹
          ○ Here:
               ■ |𝒙 - 1| < 1
          ○ Therefore:
               ■ center 𝑪 = 1
               ■ radius 𝑹 = 1
          ○ Meaning:
               ■ from the center 1, move 1 unit left and 1 unit right.
          ○ So:
               ■ 1 - 1 < 𝒙 < 1 + 1
               ■ 0 < 𝒙 < 2
          ○ Preliminary interval:
               ■ (0,2)

● [1:06:12]. Endpoint 𝒙 = 0.
     ◉ Plug into the Taylor series:
          ○ ∑[𝒏=1,∞] [(-1)ⁿ⁻¹(0 - 1)ⁿ] / 𝒏
     ◉ Since:
          ○ (0 - 1)ⁿ = (-1)ⁿ
     ◉ Then:
          ○ (-1)ⁿ⁻¹(-1)ⁿ = (-1)²ⁿ⁻¹
     ◉ Since:
          ○ 2𝒏 - 1 is always odd
     ◉ We get:
          ○ (-1)²ⁿ⁻¹ = -1
     ◉ Therefore the series becomes:
          ○ -∑[𝒏=1,∞] 1/𝒏
     ◉ This is:
          ○ the negative harmonic series.
     ◉ Since the harmonic series diverges:
          ○ this endpoint diverges.
     ◉ Therefore:
          ○ 𝒙 = 0 is not included.

● [1:10:30]. Endpoint 𝒙 = 2.
     ◉ Plug into the Taylor series:
          ○ ∑[𝒏=1,∞] [(-1)ⁿ⁻¹(2 - 1)ⁿ] / 𝒏
     ◉ Since:
          ○ (2 - 1)ⁿ = 1ⁿ = 1
     ◉ The series becomes:
          ○ ∑[𝒏=1,∞] (-1)ⁿ⁻¹/𝒏
     ◉ This is:
          ○ the alternating harmonic series.
     ◉ It converges by:
          ○ Alternating Series Test.
     ◉ Therefore:
          ○ 𝒙 = 2 is included.

● [1:12:52]. Final result.
     ◉ Taylor series:
          ○ Ln(𝒙) = ∑[𝒏=1,∞] [(-1)ⁿ⁻¹(𝒙 - 1)ⁿ] / 𝒏
     ◉ Center:
          ○ 𝑪 = 1
     ◉ Radius:
          ○ 𝑹 = 1
     ◉ Interval of convergence:
          ○ (0,2]


２．３ - Ｅｘａｍｐｌｅ 3:　Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　Ｓｉｎｅ　ａｎｄ　Ｃｏｓｉｎｅ

● [1:14:34]. 🧩 Example 3 — Find the Maclaurin series for sin(𝒙) and cos(𝒙)

● [1:15:52]. Step ❶ — Find derivatives.
     ◉ Start:
          ○ 𝒇(𝒙) = Sin(𝒙)
     ◉ Derivatives:
          ○ 𝒇'(𝒙) = Cos(𝒙)
          ○ 𝒇''(𝒙) = -Sin(𝒙)
          ○ 𝒇'''(𝒙) = -Cos(𝒙)
          ○ 𝒇⁽⁴⁾(𝒙) = Sin(𝒙)
     ◉ Pattern:
          ○ the derivatives repeat in a cycle:
               ■ Sin(𝒙)
               ■ Cos(𝒙)
               ■ -Sin(𝒙)
               ■ -Cos(𝒙)
               ■ Sin(𝒙)
          ○ because of this cycle, it is not convenient to write one simple formula for 𝒇⁽ⁿ⁾(𝒙) directly.

● [1:17:53]. Step ❷ — Evaluate at 𝒙 = 0.
     ◉ Since this is a Maclaurin series:
          ○ 𝑪 = 0
     ◉ Evaluate the derivative cycle at 0:
          ○ Sin(0) = 0
          ○ Cos(0) = 1
          ○ -Sin(0) = 0
          ○ -Cos(0) = -1
          ○ Sin(0) = 0
     ◉ Therefore the values repeat as:
          ○ 0, 1, 0, -1, 0, 1, 0, -1, ...
     ◉ Meaning:
          ○ the even-power terms disappear.
          ○ only the odd-power terms survive.

● [1:18:38]. Write out the Maclaurin series terms.
     ◉ Maclaurin formula:
          ○ 𝒇(𝒙) = ∑[𝒏=0,∞] [𝒇⁽ⁿ⁾(0) / 𝒏!] 𝒙ⁿ
     ◉ Expanded:
          ○ Sin(𝒙) = 𝒇(0) + 𝒇'(0)𝒙 + [𝒇''(0)/2!]𝒙² + [𝒇'''(0)/3!]𝒙³ + [𝒇⁽⁴⁾(0)/4!]𝒙⁴ + ...
     ◉ Substitute the values:
          ○ Sin(𝒙) = 0 + 𝒙 + 0 + [(-1)𝒙³]/3! + 0 + 𝒙⁵/5! + 0 + [(-1)𝒙⁷]/7! + ...
     ◉ Therefore:
          ○ Sin(𝒙) = 𝒙 - 𝒙³/3! + 𝒙⁵/5! - 𝒙⁷/7! + ...

● [1:23:57]. Step ❸ — Rewrite the pattern using a new index.
     ◉ The surviving powers are:
          ○ 1, 3, 5, 7, ...
     ◉ These are odd powers.
     ◉ Odd powers can be written as:
          ○ 2𝒌 + 1
     ◉ The signs alternate:
          ○ positive, negative, positive, negative, ...
     ◉ Alternating sign pattern:
          ○ (-1)ᵏ
     ◉ Therefore:
          ○ Sin(𝒙) = ∑[𝒌=0,∞] [(-1)ᵏ𝒙²ᵏ⁺¹] / (2𝒌 + 1)!

● [1:28:18]. Step ❹ — Find the interval of convergence.
     ◉ Use:
          ○ Ratio Test.
     ◉ Start with:
          ○ 𝒂ₖ = [(-1)ᵏ𝒙²ᵏ⁺¹] / (2𝒌 + 1)!
     ◉ Then:
          ○ 𝒂ₖ₊₁ = [(-1)ᵏ⁺¹𝒙²ᵏ⁺³] / (2𝒌 + 3)!
     ◉ Compute:
          ○ 𝑳 = limₖ→∞ |𝒂ₖ₊₁/𝒂ₖ|
     ◉ Simplify the Ratio Test expression.
          ○ Powers of 𝒙:
               ■ 𝒙²ᵏ⁺³ / 𝒙²ᵏ⁺¹ = 𝒙²
          ○ Factorials:
               ■ (2𝒌 + 1)! / (2𝒌 + 3)! = 1 / [(2𝒌 + 3)(2𝒌 + 2)]
          ○ Therefore:
               ■ 𝑳 = limₖ→∞ 𝒙² / [(2𝒌 + 3)(2𝒌 + 2)]
     ◉ Limit result.
          ○ Since:
               ■ 𝒙 is fixed.
               ■ (2𝒌 + 3)(2𝒌 + 2) → ∞
          ○ Then:
               ■ 𝒙² / [(2𝒌 + 3)(2𝒌 + 2)] → 0
          ○ Therefore:
               ■ 𝑳 = 0
          ○ This happens:
               ■ for every real value of 𝒙.
     ◉ Interval of convergence for Sine.
          ○ Since:
               ■ 𝑳 = 0 < 1
          ○ By the Ratio Test:
               ■ the series converges for all real 𝒙.
          ○ Therefore:
               ■ radius of convergence 𝑹 = ∞
               ■ interval of convergence is (-∞,∞)

● [1:34:07]. Final Maclaurin series for Sine.
     ◉ Therefore:
          ○ Sin(𝒙) = ∑[𝒏=0,∞] [(-1)ⁿ𝒙²ⁿ⁺¹] / (2𝒏 + 1)!
     ◉ Expanded:
          ○ Sin(𝒙) = 𝒙 - 𝒙³/3! + 𝒙⁵/5! - 𝒙⁷/7! + ...
     ◉ On:
          ○ (-∞,∞)

● [1:36:17]. Derive Cosine from the Sine series.
     ◉ Since:
          ○ the derivative of Sin(𝒙) is Cos(𝒙)
     ◉ And:
          ○ Sin(𝒙) = 𝒙 - 𝒙³/3! + 𝒙⁵/5! - 𝒙⁷/7! + ...
     ◉ Differentiate both sides term by term:
          ○ Cos(𝒙) = derivative of [𝒙 - 𝒙³/3! + 𝒙⁵/5! - 𝒙⁷/7! + ...]
     ◉ Term-by-term result:
          ○ derivative of 𝒙 is 1
          ○ derivative of -𝒙³/3! is -𝒙²/2!
          ○ derivative of 𝒙⁵/5! is 𝒙⁴/4!
          ○ derivative of -𝒙⁷/7! is -𝒙⁶/6!
     ◉ Therefore:
          ○ Cos(𝒙) = 1 - 𝒙²/2! + 𝒙⁴/4! - 𝒙⁶/6! + ...
     ◉ Final Maclaurin series for Cosine.
          ○ Series notation:
               ■ Cos(𝒙) = ∑[𝒏=0,∞] [(-1)ⁿ𝒙²ⁿ] / (2𝒏)!
          ○ Expanded:
               ■ Cos(𝒙) = 1 - 𝒙²/2! + 𝒙⁴/4! - 𝒙⁶/6! + ...
          ○ Interval of convergence:
               ■ (-∞,∞)

● N̲O̲T̲E̲ — Why Cosine comes from Sine.
     ◉ Leonard does not rebuild the Cosine series from scratch.
     ◉ He uses the Sine series already found.
     ◉ Since:
          ○ Cos(𝒙) is the derivative of Sin(𝒙)
     ◉ Then:
          ○ the Cosine series is obtained by differentiating the Sine series term by term.
     ◉ This lowers:
          ○ each power by 1.
          ○ each factorial by 1.
     ◉ That is why:
          ○ 𝒙³/3! becomes 𝒙²/2!
          ○ 𝒙⁵/5! becomes 𝒙⁴/4!
          ○ 𝒙⁷/7! becomes 𝒙⁶/6!


２．４ - Ｅｘａｍｐｌｅ 4:　Ｂｉｎｏｍｉａｌ　Ｓｅｒｉｅｓ　ｆｏｒ　（１ + 𝒙）ᵏ

● [1:38:58]. 🧩 Example 4 — The Binomial Series: 𝒇(𝒙) = (1 + 𝒙)ᵏ
     ◉ Here:
          ○ 𝒌 is a real number.
     ◉ Goal:
          ○ find the Maclaurin series for (1 + 𝒙)ᵏ.

● [1:39:58]. Step ❶ — Find derivatives.
     ◉ Start with:
          ○ 𝒇(𝒙) = (1 + 𝒙)ᵏ
     ◉ First derivatives:
          ○ 𝒇'(𝒙) = 𝒌(1 + 𝒙)ᵏ⁻¹
          ○ 𝒇''(𝒙) = 𝒌(𝒌 - 1)(1 + 𝒙)ᵏ⁻²
          ○ 𝒇'''(𝒙) = 𝒌(𝒌 - 1)(𝒌 - 2)(1 + 𝒙)ᵏ⁻³
          ○ 𝒇⁽⁴⁾(𝒙) = 𝒌(𝒌 - 1)(𝒌 - 2)(𝒌 - 3)(1 + 𝒙)ᵏ⁻⁴
     ◉ Pattern:
          ○ each derivative brings down one more factor.
          ○ the factors are:
               ■ 𝒌
               ■ 𝒌 - 1
               ■ 𝒌 - 2
               ■ 𝒌 - 3
               ■ ...
     ◉ [1:42:04]. General derivative pattern.
          ○ For the 𝒏-th derivative:
               ■ 𝒇⁽ⁿ⁾(𝒙) = 𝒌(𝒌 - 1)(𝒌 - 2)⋯(𝒌 - 𝒏 + 1)(1 + 𝒙)ᵏ⁻ⁿ
          ○ General factor:
               ■ the 𝒊-th factor is 𝒌 - 𝒊 + 1,
               ■ where 𝒊 = 1,2,...,𝒏.
          ○ Compact product notation:
               ■ 𝒇⁽ⁿ⁾(𝒙) = (∏[𝒊=1,𝒏] (𝒌 - 𝒊 + 1))·(1 + 𝒙)ᵏ⁻ⁿ

● [1:44:20]. Step ❷ — Evaluate at 𝒙 = 0.
     ◉ Since:
          ○ 1 + 0 = 1
     ◉ Then:
          ○ (1 + 0)ᵏ⁻ⁿ = 1
     ◉ Therefore:
          ○ 𝒇⁽ⁿ⁾(0) = 𝒌(𝒌 - 1)(𝒌 - 2)⋯(𝒌 - 𝒏 + 1)
     ◉ Compact notation:
          ○ 𝒇⁽ⁿ⁾(0) = ∏[𝒊=1,𝒏] (𝒌 - 𝒊 + 1)
     ◉ Important:
          ○ for 𝒏 = 0, the product is empty.
          ○ by convention, the empty product is 1.
          ○ this gives the first term of the Maclaurin series.

● [1:45:18]. Step ❸ — Build the Maclaurin series.
     ◉ Maclaurin formula:
          ○ 𝒇(𝒙) = ∑[𝒏=0,∞] [𝒇⁽ⁿ⁾(0) / 𝒏!]𝒙ⁿ
     ◉ Substitute:
          ○ 𝒇⁽ⁿ⁾(0) = 𝒌(𝒌 - 1)(𝒌 - 2)⋯(𝒌 - 𝒏 + 1)
     ◉ Therefore:
          ○ (1 + 𝒙)ᵏ = ∑[𝒏=0,∞] [𝒌(𝒌 - 1)(𝒌 - 2)⋯(𝒌 - 𝒏 + 1) / 𝒏!]𝒙ⁿ
     ◉ [1:47:24]. Expanded Binomial Series.
          ○ The first terms are:
               ■ (1 + 𝒙)ᵏ = 1 + 𝒌𝒙 + [𝒌(𝒌 - 1)/2!]𝒙² + [𝒌(𝒌 - 1)(𝒌 - 2)/3!]𝒙³ + ...
          ○ Meaning:
               ■ the coefficient of 𝒙ⁿ is built from the falling product:
                    ▣ 𝒌(𝒌 - 1)(𝒌 - 2)⋯(𝒌 - 𝒏 + 1)
               ■ divided by:
                    ▣ 𝒏!
     ◉ [1:52:27]. Binomial coefficient notation.
          ○ The coefficient:
               ■ [𝒌(𝒌 - 1)(𝒌 - 2)⋯(𝒌 - 𝒏 + 1)] / 𝒏!
          ○ is called:
               ■ the binomial coefficient.
          ○ It is read as:
               ■ “𝒌 choose 𝒏”
          ○ Standard notation:
               ■ (𝒌 choose 𝒏)
          ○ Meaning:
               ■ it gives the coefficient of 𝒙ⁿ in the binomial series.
          ○ Therefore:
               ■ (1 + 𝒙)ᵏ = ∑[𝒏=0,∞] (𝒌 choose 𝒏)𝒙ⁿ

● [1:53:39]. Step ❹ — Convergence cases for the Binomial Series.
     ◉ C̲a̲s̲e̲ ̲1̲ ̲— 𝒌 is a nonnegative integer:
          ○ 𝒌 ∈ {0,1,2,3,...}
          ○ t̲h̲e̲n̲:
               ■ the binomial series stops after finitely many terms.
               ■ therefore it becomes an ordinary polynomial.
               ■ it converges for all real 𝒙.
               ■ interval of convergence: (-∞,∞)
     ◉ C̲a̲s̲e̲ ̲2̲  — 𝒌 is not a nonnegative integer:
          ○ 𝒌 ∉ {0,1,2,3,...}
          ○ t̲h̲e̲n̲:
               ■ the binomial series is infinite.
               ■ the basic convergence interval is:
                    ▣ -1 < 𝒙 < 1
               ■ radius of convergence:
                    ▣ 𝑹 = 1
               ■ endpoint behavior depends on 𝒌.
     ◉ [1:56:33]. Endpoint cases when 𝒌 ∉ {0,1,2,3,...}.
          ○ i̲f̲ 𝒌 ≤ -1
               ■ t̲h̲e̲n̲:
                    ▣ neither endpoint is included.
                    ▣ interval: (-1,1)
          ○ i̲f̲ -1 < 𝒌 < 0
               ■ t̲h̲e̲n̲:
                    ▣ only 𝒙 = 1 is included.
                    ▣ interval: (-1,1]
          ○ i̲f̲ 𝒌 > 0 and 𝒌 ∉ {0,1,2,3,...}
               ■ t̲h̲e̲n̲:
                    ▣ both endpoints are included.
                    ▣ interval: [-1,1]
               
● N̲O̲T̲E̲ 1 — Binomial coefficients become polynomial coefficients.
     ◉ Main idea:
          ○ when 𝒌 is a nonnegative integer,
               ■ the binomial series stops after finitely many terms.
               ■ therefore it becomes an ordinary polynomial.
          ○ the binomial coefficients become the coefficients of that polynomial.
     ◉ Notation:
          ○ (𝒌 choose 𝒏) means “𝒌 over 𝒏”.
          ○ In standard mathematical notation:
               ■ (𝒌 choose 𝒏) = binomial coefficient.
          ○ It represents:
               ■ [𝒌(𝒌 - 1)(𝒌 - 2)⋯(𝒌 - 𝒏 + 1)] / 𝒏!
          ○ Meaning:
               ■ (𝒌 choose 𝒏) gives the coefficient of 𝒙ⁿ in the binomial expansion.
     ◉ Example:
          ○ let 𝒌 = 4.
          ○ Start from the binomial series:
               ■ (1 + 𝒙)ᵏ = ∑[𝒏=0,∞] (𝒌 choose 𝒏)𝒙ⁿ
          ○ Substitute:
               ■ 𝒌 = 4
          ○ Then:
               ■ (1 + 𝒙)⁴ = ∑[𝒏=0,∞] (4 choose 𝒏)𝒙ⁿ
          ○ But since 𝒌 = 4 is a nonnegative integer,
               ■ the series stops at 𝒏 = 4.
          ○ Therefore:
               ■ (1 + 𝒙)⁴ = ∑[𝒏=0,4] (4 choose 𝒏)𝒙ⁿ
     ◉ Expand the sum term by term:
          ○ (1 + 𝒙)⁴
               ■ = (4 choose 0)𝒙⁰
               ■ + (4 choose 1)𝒙¹
               ■ + (4 choose 2)𝒙²
               ■ + (4 choose 3)𝒙³
               ■ + (4 choose 4)𝒙⁴
     ◉ Compute each binomial coefficient.
          ○ First coefficient:
               ■ (4 choose 0) = 1
               ■ So:
                    ▣ (4 choose 0)𝒙⁰ = 1⋅𝒙⁰ = 1
          ○ Second coefficient:
               ■ (4 choose 1) = 4/1!
               ■ Since:
                    ▣ 1! = 1
               ■ Then:
                    ▣ (4 choose 1) = 4
               ■ So:
                    ▣ (4 choose 1)𝒙¹ = 4𝒙
          ○ Third coefficient:
               ■ (4 choose 2) = [4(4 - 1)]/2!
               ■ Simplify:
                    ▣ (4 choose 2) = [4⋅3]/2!
                    ▣ (4 choose 2) = 12/2
                    ▣ (4 choose 2) = 6
               ■ So:
                    ▣ (4 choose 2)𝒙² = 6𝒙²
          ○ Fourth coefficient:
               ■ (4 choose 3) = [4(4 - 1)(4 - 2)]/3!
               ■ Simplify:
                    ▣ (4 choose 3) = [4⋅3⋅2]/3!
                    ▣ (4 choose 3) = 24/6
                    ▣ (4 choose 3) = 4
               ■ So:
                    ▣ (4 choose 3)𝒙³ = 4𝒙³
          ○ Fifth coefficient:
               ■ (4 choose 4) = [4(4 - 1)(4 - 2)(4 - 3)]/4!
               ■ Simplify:
                    ▣ (4 choose 4) = [4⋅3⋅2⋅1]/4!
                    ▣ (4 choose 4) = 24/24
                    ▣ (4 choose 4) = 1
               ■ So:
                    ▣ (4 choose 4)𝒙⁴ = 𝒙⁴
     ◉ Put all the terms together:
          ○ (1 + 𝒙)⁴ = 1 + 4𝒙 + 6𝒙² + 4𝒙³ + 𝒙⁴
     ◉ Coefficient pattern:
          ○ 1, 4, 6, 4, 1
     ◉ Meaning:
          ○ the binomial coefficients:
               ■ (4 choose 0)
               ■ (4 choose 1)
               ■ (4 choose 2)
               ■ (4 choose 3)
               ■ (4 choose 4)
          ○ become the polynomial coefficients:
               ■ 1, 4, 6, 4, 1
     ◉ Therefore:
          ○ the coefficient of 𝒙ⁿ in (1 + 𝒙)⁴ is:
               ■ (4 choose 𝒏)
     ◉ Final takeaway:
          ○ binomial coefficients are exactly the coefficients that appear when expanding powers like:
               ■ (1 + 𝒙)⁴
          ○ and they match the corresponding row of Pascal's Triangle:
               ■ 1, 4, 6, 4, 1
     ◉ Important:
          ○ for 𝒏 = 0, the product 𝒌(𝒌 - 1)(𝒌 - 2)⋯(𝒌 - 𝒏 + 1) is empty.
          ○ by convention, an empty product equals 1.
          ○ therefore:
               ■ (𝒌 choose 0) = 1
              
● N̲O̲T̲E̲ 2 — Best way to write the binomial coefficient.
     ◉ The cleanest way to express the binomial coefficient is:
          ○ (𝒌 choose 𝒏) = [∏[𝒊=1,𝒏] (𝒌 - 𝒊 + 1)] / 𝒏!
     ◉ Meaning:
          ○ the numerator is a product.
          ○ we multiply all the factors:
               ■ 𝒌 - 𝒊 + 1
          ○ where:
               ■ 𝒊 = 1,2,3,...,𝒏
     ◉ Expanded form:
          ○ (𝒌 choose 𝒏) = [𝒌(𝒌 - 1)(𝒌 - 2)⋯(𝒌 - 𝒏 + 1)] / 𝒏!
     ◉ Why the product notation is better:
          ○ it shows exactly where the product starts.
          ○ it shows exactly where the product ends.
          ○ it avoids confusion when 𝒏 = 0.
     ◉ Important special case:
          ○ if 𝒏 = 0,
               ■ the product ∏[𝒊=1,0] is empty.
               ■ by convention, an empty product equals 1.
               ■ also, 0! = 1.
     ◉ Therefore:
          ○ (𝒌 choose 0) = 1/1 = 1
     ◉ Example:
          ○ (4 choose 0) = 1
          ○ not 5.
     ◉ Reason:
          ○ when 𝒏 = 0, there is no factor 𝒌 - 𝒏 + 1.
          ○ the product is empty.
          ○ so the numerator is 1.

               
２．５ - Ｅｘａｍｐｌｅ 5:　Ｂｉｎｏｍｉａｌ　Ｓｅｒｉｅｓ　ｆｏｒ　√（１ + 𝒙）

● [1:59:18]. 🧩 Example 5 — Binominal Series: √(1 + 𝒙).
     ◉ Start with:
          ○ 𝒇(𝒙) = √(1 + 𝒙)
     ◉ Rewrite the square root as a power:
          ○ √(1 + 𝒙) = (1 + 𝒙)¹ᐟ²
     ◉ Therefore:
          ○ 𝒌 = 1/2
     ◉ Goal:
          ○ use the Binomial Series for (1 + 𝒙)ᵏ.

● [2:00:45]. Substitute 𝒌 = 1/2 into the Binomial Series.
     ◉ General Binomial Series:
          ○ (1 + 𝒙)ᵏ = 1 + 𝒌𝒙 + [𝒌(𝒌 - 1)/2!]𝒙² + [𝒌(𝒌 - 1)(𝒌 - 2)/3!]𝒙³ + ...
     ◉ Substitute:
          ○ 𝒌 = 1/2
     ◉ Then:
          ○ (1 + 𝒙)¹ᐟ²
          ○ = 1 + (1/2)𝒙
          ○ + [(1/2)(1/2 - 1)/2!]𝒙²
          ○ + [(1/2)(1/2 - 1)(1/2 - 2)/3!]𝒙³
          ○ + [(1/2)(1/2 - 1)(1/2 - 2)(1/2 - 3)/4!]𝒙⁴
          ○ + ...

● [2:03:41]. Simplify the coefficients.
     ◉ First term:
          ○ 1
     ◉ Second term:
          ○ (1/2)𝒙
     ◉ Third term:
          ○ [(1/2)(1/2 - 1)/2!]𝒙²
          ○ = [(1/2)(-1/2)/2!]𝒙²
          ○ = -𝒙²/(2!⋅2²)
     ◉ Fourth term:
          ○ [(1/2)(1/2 - 1)(1/2 - 2)/3!]𝒙³
          ○ = [(1/2)(-1/2)(-3/2)/3!]𝒙³
          ○ = [1⋅3𝒙³]/(3!⋅2³)
     ◉ Fifth term:
          ○ [(1/2)(1/2 - 1)(1/2 - 2)(1/2 - 3)/4!]𝒙⁴
          ○ = [(1/2)(-1/2)(-3/2)(-5/2)/4!]𝒙⁴
          ○ = -[1⋅3⋅5𝒙⁴]/(4!⋅2⁴)

● [2:05:51]. Pattern of the series.
     ◉ After simplifying:
          ○ √(1 + 𝒙)
          ○ = 1 + (1/2)𝒙 - 𝒙²/(2!⋅2²) + [1⋅3𝒙³]/(3!⋅2³) - [1⋅3⋅5𝒙⁴]/(4!⋅2⁴) + ...
     ◉ Pattern:
          ○ after the first two terms, the signs alternate.
          ○ the numerator uses odd products:
               ■ 1
               ■ 1⋅3
               ■ 1⋅3⋅5
               ■ 1⋅3⋅5⋅7
               ■ ...
          ○ the denominator uses:
               ■ 𝒏!
               ■ 2ⁿ

● [2:07:22]. Series notation.
     ◉ Separate the first two terms:
          ○ 1
          ○ (1/2)𝒙
     ◉ Then write the remaining pattern as a sum:
          ○ (1 + 𝒙)¹ᐟ² = 1 + (1/2)𝒙 + ∑[𝒏=2,∞] (-1)ⁿ⁺¹ [1⋅3⋅5⋯(2𝒏 - 3)]𝒙ⁿ / [𝒏!⋅2ⁿ]
     ◉ Important:
          ○ the sum starts at 𝒏 = 2.
     ◉ Reason:
          ○ the first two terms:
               ■ 1
               ■ (1/2)𝒙
          ○ do not fit the same odd-product pattern cleanly.
     ◉ Check:
          ○ when 𝒏 = 2:
               ■ 2𝒏 - 3 = 1
               ■ numerator: 1
               ■ sign: (-1)³ = -1
               ■ term: -𝒙²/(2!⋅2²)
          ○ when 𝒏 = 3:
               ■ 2𝒏 - 3 = 3
               ■ numerator: 1⋅3
               ■ sign: (-1)⁴ = 1
               ■ term: [1⋅3𝒙³]/(3!⋅2³)

● [2:10:42]. Interval of convergence.
     ◉ No new convergence test is needed here.
     ◉ Reason:
          ○ this example uses the known Binomial Series rules.
     ◉ Since:
          ○ 𝒌 = 1/2
          ○ 𝒌 > 0
          ○ 𝒌 ∉ {0,1,2,3,...}
     ◉ By the Binomial Series endpoint rules:
          ○ both endpoints are included.
     ◉ Therefore:
          ○ interval of convergence: [-1,1]
     ◉ Meaning:
          ○ the series represents √(1 + 𝒙) on [-1,1].





３ - Ｃｏｍｍｏｎ　Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ

● [2:12:55]. Common Maclaurin series.
     ◉ These are known series that can be reused instead of rebuilding everything from scratch.


３．１ - Ｇｅｏｍｅｔｒｉｃ　Ｓｅｒｉｅｓ　ｆｏｒ　１／（１－𝒙）

● [2:13:17]. Geometric power series.
     ◉ Function:
          ○ 1/(1 - 𝒙)
     ◉ Series:
          ○ 1/(1 - 𝒙) = 1 + 𝒙 + 𝒙² + 𝒙³ + ...
     ◉ Series notation:
          ○ 1/(1 - 𝒙) = ∑[𝒏=0,∞] 𝒙ⁿ
     ◉ Interval:
          ○ (-1,1)


３．２ - Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　𝓮ˣ

● [2:14:02]. Maclaurin series for 𝓮ˣ.
     ◉ Function:
          ○ 𝓮ˣ
     ◉ Series:
          ○ 𝓮ˣ = 1 + 𝒙 + 𝒙²/2! + 𝒙³/3! + ...
     ◉ Series notation:
          ○ 𝓮ˣ = ∑[𝒏=0,∞] 𝒙ⁿ / 𝒏!
     ◉ Interval:
          ○ (-∞,∞)


３．３ - Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　Ｓｉｎｅ

● [2:14:40]. Maclaurin series for Sine.
     ◉ Function:
          ○ Sin(𝒙)
     ◉ Series:
          ○ Sin(𝒙) = 𝒙 - 𝒙³/3! + 𝒙⁵/5! - 𝒙⁷/7! + ...
     ◉ Series notation:
          ○ Sin(𝒙) = ∑[𝒏=0,∞] (-1)ⁿ𝒙²ⁿ⁺¹ / (2𝒏 + 1)!
     ◉ Interval:
          ○ (-∞,∞)


３．４ - Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　Ｃｏｓｉｎｅ

● [2:15:25]. Maclaurin series for Cosine.
     ◉ Function:
          ○ Cos(𝒙)
     ◉ Series:
          ○ Cos(𝒙) = 1 - 𝒙²/2! + 𝒙⁴/4! - 𝒙⁶/6! + ...
     ◉ Series notation:
          ○ Cos(𝒙) = ∑[𝒏=0,∞] (-1)ⁿ𝒙²ⁿ / (2𝒏)!
     ◉ Interval:
          ○ (-∞,∞)


３．５ - Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　Ｌｎ（１ + 𝒙）

● [2:16:08]. Maclaurin series for Ln(1 + 𝒙).
     ◉ Function:
          ○ Ln(1 + 𝒙)
     ◉ Series:
          ○ Ln(1 + 𝒙) = 𝒙 - 𝒙²/2 + 𝒙³/3 - 𝒙⁴/4 + ...
     ◉ Series notation:
          ○ Ln(1 + 𝒙) = ∑[𝒏=1,∞] (-1)ⁿ⁻¹𝒙ⁿ / 𝒏
     ◉ Interval:
          ○ (-1,1]


３．６ - Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　Ｓｉｎ⁻¹（𝒙）

● [2:17:05]. Maclaurin series for Sin⁻¹(𝒙).
     ◉ Function:
          ○ Sin⁻¹(𝒙)
     ◉ Series:
          ○ Sin⁻¹(𝒙) = 𝒙 + 𝒙³/(2⋅3) + (1⋅3)𝒙⁵/(2⋅4⋅5) + ...
     ◉ Series notation:
          ○ Sin⁻¹(𝒙) = ∑[𝒏=0,∞] [(2𝒏)!𝒙²ⁿ⁺¹] / [(2²ⁿ)(𝒏!)²(2𝒏 + 1)]
     ◉ Interval:
          ○ [-1,1]


３．７ - Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　Ｔａｎ⁻¹（𝒙）

● [2:18:20]. Maclaurin series for Tan⁻¹(𝒙).
     ◉ Function:
          ○ Tan⁻¹(𝒙)
     ◉ Series:
          ○ Tan⁻¹(𝒙) = 𝒙 - 𝒙³/3 + 𝒙⁵/5 - 𝒙⁷/7 + ...
     ◉ Series notation:
          ○ Tan⁻¹(𝒙) = ∑[𝒏=0,∞] (-1)ⁿ𝒙²ⁿ⁺¹ / (2𝒏 + 1)
     ◉ Interval:
          ○ [-1,1]


３．８ - Ｂｉｎｏｍｉａｌ　Ｓｅｒｉｅｓ

● [2:19:18]. Binomial series.
     ◉ Function:
          ○ (1 + 𝒙)ᵏ
     ◉ Series:
          ○ (1 + 𝒙)ᵏ = ∑[𝒏=0,∞] (𝒌 choose 𝒏)𝒙ⁿ
     ◉ Basic interval:
          ○ (-1,1)
     ◉ Special cases:
          ○ if 𝒌 ∈ {0,1,2,3,...},
               ■ interval: (-∞,∞)
          ○ if 𝒌 ∉ {0,1,2,3,...},
               ■ endpoint behavior depends on 𝒌.




４ - Ｍａｎｉｐｕｌａｔｉｎｇ　Ｋｎｏｗｎ　Ｓｅｒｉｅｓ

● [2:20:56]. Main strategy.
     ◉ Instead of deriving a Taylor or Maclaurin series from scratch,
          ○ manipulate a known series.
     ◉ Goal:
          ○ make the given function fit one of the known forms.


４．１ - Ｅｘａｍｐｌｅ 6:　Ｔａｙｌｏｒ　Ｓｅｒｉｅｓ　ｆｏｒ　１／（１ + 𝒙）　ｃｅｎｔｅｒｅｄ　ａｔ　𝑪 = 2

● [2:21:34]. 🧩 Example 6 — Find Taylor series for 1/(1 + 𝒙) centered at 𝑪 = 2.
     ◉ Since the center is:
          ○ 𝑪 = 2
     ◉ The series must involve:
          ○ (𝒙 - 2)

● [2:22:54]. Force the center into the expression.
     ◉ Rewrite:
          ○ 1 + 𝒙 = 1 + [(𝒙 - 2) + 2]
          ○ 1 + 𝒙 = 3 + (𝒙 - 2)
     ◉ Therefore:
          ○ 1/(1 + 𝒙) = 1/[3 + (𝒙 - 2)]

● [2:25:02]. Fit the geometric form.
     ◉ Goal:
          ○ make it look like 1/(1 - 𝒖)
     ◉ Factor out 3:
          ○ 1/[3 + (𝒙 - 2)] = (1/3) ⋅ 1/[1 + (𝒙 - 2)/3]
     ◉ Rewrite the plus sign as a minus:
          ○ 1/[1 + (𝒙 - 2)/3] = 1/[1 - (-(𝒙 - 2)/3)]
     ◉ Therefore:
          ○ 1/(1 + 𝒙) = (1/3) ⋅ 1/[1 - (-(𝒙 - 2)/3)]

● [2:28:12]. Substitute into the geometric series.
     ◉ Known series:
          ○ 1/(1 - 𝒖) = 1 + 𝒖 + 𝒖² + 𝒖³ + ...
     ◉ Here:
          ○ 𝒖 = -(𝒙 - 2)/3
     ◉ Substitute:
          ○ 1/(1 + 𝒙) = (1/3)[1 + (-(𝒙 - 2)/3) + (-(𝒙 - 2)/3)² + (-(𝒙 - 2)/3)³ + ...]

● [2:31:35]. Series notation.
     ◉ Start from:
          ○ 1/(1 + 𝒙) = (1/3)∑[𝒏=0,∞] [-(𝒙 - 2)/3]ⁿ
     ◉ Simplify:
          ○ [-(𝒙 - 2)/3]ⁿ = (-1)ⁿ(𝒙 - 2)ⁿ / 3ⁿ
     ◉ Since there is also a factor 1/3 outside:
          ○ (1/3) ⋅ 1/3ⁿ = 1/3ⁿ⁺¹
     ◉ Therefore:
          ○ 1/(1 + 𝒙) = ∑[𝒏=0,∞] (-1)ⁿ(𝒙 - 2)ⁿ / 3ⁿ⁺¹

● [2:34:18]. Interval of convergence.
     ◉ No new convergence test is needed here.
     ◉ Reason:
          ○ this is based on the geometric series.
     ◉ The geometric series requires:
          ○ |𝒖| < 1
     ◉ Here:
          ○ 𝒖 = -(𝒙 - 2)/3
     ◉ Therefore:
          ○ |-(𝒙 - 2)/3| < 1
     ◉ Since absolute value removes the negative sign:
          ○ |𝒙 - 2|/3 < 1
     ◉ Multiply by 3:
          ○ |𝒙 - 2| < 3
     ◉ Radius of convergence.
          ○ Compare with the standard form:
               ■ |𝒙 - 𝑪| < 𝑹
          ○ Here:
               ■ |𝒙 - 2| < 3
          ○ Therefore:
               ■ center 𝑪 = 2
               ■ radius 𝑹 = 3
     ◉ Solve the interval.
          ○ From:
               ■ |𝒙 - 2| < 3
          ○ We get:
               ■ -3 < 𝒙 - 2 < 3
          ○ Add 2:
               ■ -1 < 𝒙 < 5
     ◉ Interval of convergence:
          ○ (-1,5)
     ◉ Meaning:
          ○ the Taylor series represents 1/(1 + 𝒙) centered at 𝑪 = 2 only for -1 < 𝒙 < 5.
          
● N̲O̲T̲E̲ — Meaning of Leonard's “X” in the geometric series.
     ◉ Leonard writes:
          ○ -1 < “X” < 1
     ◉ But here:
          ○ “X” is not the original variable 𝒙.
     ◉ In this example, “X” means the quantity substituted into the geometric series.
     ◉ Since:
          ○ 1/(1 - 𝒖) = ∑[𝒏=0,∞] 𝒖ⁿ
     ◉ and:
          ○ 𝒖 = -(𝒙 - 2)/3
     ◉ Then Leonard's “X” is:
          ○ “X” = -(𝒙 - 2)/3
     ◉ Therefore, the convergence condition:
          ○ -1 < “X” < 1
     ◉ becomes:
          ○ -1 < -(𝒙 - 2)/3 < 1
     ◉ Solve:
          ○ -3 < -(𝒙 - 2) < 3
          ○ 3 > 𝒙 - 2 > -3
          ○ -3 < 𝒙 - 2 < 3
          ○ -1 < 𝒙 < 5
     ◉ Meaning:
          ○ the geometric-series variable is the substituted expression.
          ○ here, that expression is -(𝒙 - 2)/3.
          ○ the original variable 𝒙 must satisfy -1 < 𝒙 < 5.
     ◉ Therefore:
          ○ center 𝑪 = 2
          ○ radius 𝑹 = 3
          ○ interval of convergence: (-1,5)


４．２ - Ｅｘａｍｐｌｅ 7:　Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　𝒙²Ｓｉｎ（２𝒙）

● [2:38:20]. 🧩 Example 7 — Find Maclaurin series for 𝒙²Sin(2𝒙).
     ◉ Goal:
          ○ find a Maclaurin series representation for 𝒙²Sin(2𝒙).
     ◉ Use known series:
          ○ Sin(𝒙)
     ◉ Reason:
          ○ the given function contains Sin(2𝒙).

● [2:38:49]. Start from the known Sine series.
     ◉ Known:
          ○ Sin(𝒙) = 𝒙 - 𝒙³/3! + 𝒙⁵/5! - 𝒙⁷/7! + ...
     ◉ Series notation:
          ○ Sin(𝒙) = ∑[𝒏=0,∞] (-1)ⁿ𝒙²ⁿ⁺¹ / (2𝒏 + 1)!
     ◉ Interval:
          ○ (-∞,∞)

● [2:39:07]. Substitute 2𝒙 into the Sine series.
     ◉ Since:
          ○ Sin(𝒙) = 𝒙 - 𝒙³/3! + 𝒙⁵/5! - ...
     ◉ Replace 𝒙 by 2𝒙:
          ○ Sin(2𝒙) = 2𝒙 - (2𝒙)³/3! + (2𝒙)⁵/5! - ...
     ◉ Simplify powers:
          ○ Sin(2𝒙) = 2𝒙 - 2³𝒙³/3! + 2⁵𝒙⁵/5! - ...
     ◉ Series notation:
          ○ Sin(2𝒙) = ∑[𝒏=0,∞] (-1)ⁿ2²ⁿ⁺¹𝒙²ⁿ⁺¹ / (2𝒏 + 1)!

● [2:42:49]. Multiply by 𝒙².
     ◉ We need:
          ○ 𝒙²Sin(2𝒙)
     ◉ So multiply the whole series by 𝒙²:
          ○ 𝒙²Sin(2𝒙) = 𝒙² · ∑[𝒏=0,∞] (-1)ⁿ2²ⁿ⁺¹𝒙²ⁿ⁺¹ / (2𝒏 + 1)!
     ◉ This raises every power of 𝒙 by 2:
          ○ 𝒙² · 𝒙²ⁿ⁺¹ = 𝒙²ⁿ⁺³

● [2:43:14]. Final series notation.
     ◉ Therefore:
          ○ 𝒙²Sin(2𝒙) = ∑[𝒏=0,∞] (-1)ⁿ2²ⁿ⁺¹𝒙²ⁿ⁺³ / (2𝒏 + 1)!
     ◉ Expanded:
          ○ 𝒙²Sin(2𝒙) = 2𝒙³ - 2³𝒙⁵/3! + 2⁵𝒙⁷/5! - ...

● [2:44:31]. Interval of convergence.
     ◉ No new convergence test is needed here.
     ◉ Reason:
          ○ the original Sine series converges for all real 𝒙.
     ◉ Substituting:
          ○ 𝒙 → 2𝒙
     ◉ and multiplying by:
          ○ 𝒙²
     ◉ do not restrict the interval.
     ◉ Therefore:
          ○ interval of convergence: (-∞,∞)
     ◉ Meaning:
          ○ the Maclaurin series represents 𝒙²Sin(2𝒙) for every real 𝒙.

● [2:45:03]. Meaning of “the series represents the function”.
     ◉ Saying that the series represents the function means:
          ○ both expressions give the same value for every 𝒙 in the interval of convergence.
     ◉ In this example:
          ○ 𝒙²Sin(2𝒙) = ∑[𝒏=0,∞] (-1)ⁿ2²ⁿ⁺¹𝒙²ⁿ⁺³ / (2𝒏 + 1)!
     ◉ Since the interval is:
          ○ (-∞,∞)
     ◉ Then:
          ○ we can substitute any real value of 𝒙 into the original function.
          ○ we can also substitute that same value of 𝒙 into the series.
          ○ both give the same result.
     ◉ Important:
          ○ using infinitely many terms gives the exact value.
          ○ using only a few terms gives an approximation.

          
４．３ - Ｅｘａｍｐｌｅ 8:　Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　Ｓｉｎｈ（𝒙）

● [2:46:25]. 🧩 Example 8 — Find Maclaurin series for Sinh(𝒙).
     ◉ Definition:
          ○ Sinh(𝒙) = (𝓮ˣ - 𝓮⁻ˣ)/2
     ◉ Rewrite:
          ○ Sinh(𝒙) = (1/2)𝓮ˣ - (1/2)𝓮⁻ˣ
     ◉ Use:
          ○ the known Maclaurin series for 𝓮ˣ.

● [2:47:16]. Use the series for 𝓮ˣ.
     ◉ Known:
          ○ 𝓮ˣ = 1 + 𝒙 + 𝒙²/2! + 𝒙³/3! + 𝒙⁴/4! + 𝒙⁵/5! + ...
     ◉ Therefore:
          ○ (1/2)𝓮ˣ = (1/2)[1 + 𝒙 + 𝒙²/2! + 𝒙³/3! + 𝒙⁴/4! + 𝒙⁵/5! + ...]

● [2:48:18]. Build the series for 𝓮⁻ˣ.
     ◉ Substitute:
          ○ 𝒙 → -𝒙
     ◉ Then:
          ○ 𝓮⁻ˣ = 1 - 𝒙 + 𝒙²/2! - 𝒙³/3! + 𝒙⁴/4! - 𝒙⁵/5! + ...
     ◉ Therefore:
          ○ (1/2)𝓮⁻ˣ = (1/2)[1 - 𝒙 + 𝒙²/2! - 𝒙³/3! + 𝒙⁴/4! - 𝒙⁵/5! + ...]

● [2:50:02]. Subtract the two series.
     ◉ Start from:
          ○ Sinh(𝒙) = (1/2)𝓮ˣ - (1/2)𝓮⁻ˣ
     ◉ Substitute the series:
          ○ Sinh(𝒙)
          ○ = (1/2)[1 + 𝒙 + 𝒙²/2! + 𝒙³/3! + 𝒙⁴/4! + 𝒙⁵/5! + ...]
          ○ - (1/2)[1 - 𝒙 + 𝒙²/2! - 𝒙³/3! + 𝒙⁴/4! - 𝒙⁵/5! + ...]
     ◉ Cancellation:
          ○ constant terms cancel:
               ■ 1 - 1 = 0
          ○ even-power terms cancel:
               ■ 𝒙²/2! - 𝒙²/2! = 0
               ■ 𝒙⁴/4! - 𝒙⁴/4! = 0
          ○ odd-power terms add:
               ■ 𝒙 - (-𝒙) = 2𝒙
               ■ 𝒙³/3! - (-𝒙³/3!) = 2𝒙³/3!
               ■ 𝒙⁵/5! - (-𝒙⁵/5!) = 2𝒙⁵/5!

● [2:51:08]. Simplify after multiplying by 1/2.
     ◉ After subtraction:
          ○ Sinh(𝒙) = (1/2)[2𝒙 + 2𝒙³/3! + 2𝒙⁵/5! + ...]
     ◉ Distribute:
          ○ Sinh(𝒙) = 𝒙 + 𝒙³/3! + 𝒙⁵/5! + ...

● [2:52:01]. Final Maclaurin series.
     ◉ Result:
          ○ Sinh(𝒙) = 𝒙 + 𝒙³/3! + 𝒙⁵/5! + 𝒙⁷/7! + ...
     ◉ Series notation:
          ○ Sinh(𝒙) = ∑[𝒏=0,∞] 𝒙²ⁿ⁺¹ / (2𝒏 + 1)!
     ◉ Meaning:
          ○ only odd powers remain.
          ○ all signs are positive.

● [2:53:18]. Interval of convergence.
     ◉ No new convergence test is needed here.
     ◉ Reason:
          ○ this series is built from the Maclaurin series for 𝓮ˣ and 𝓮⁻ˣ.
     ◉ Since:
          ○ 𝓮ˣ converges for all real 𝒙.
          ○ 𝓮⁻ˣ also converges for all real 𝒙.
     ◉ Therefore:
          ○ interval of convergence: (-∞,∞)
     ◉ Meaning:
          ○ the series represents Sinh(𝒙) for every real 𝒙.


４．４ - Ｅｘａｍｐｌｅ 9:　Ｉｎｔｅｇｒａｔｉｎｇ　ｔｈｅ　Ｓｅｒｉｅｓ　ｆｏｒ　𝓮⁻ˣ²

● [2:55:00]. 🧩 Example 9 — Integrate by series: 𝓮⁻ˣ².
     ◉ Goal:
          ○ find a series representation for:
               ■ ∫𝓮⁻ˣ² d𝒙
     ◉ Important:
          ○ ∫𝓮⁻ˣ² d𝒙 cannot be integrated directly using elementary functions.
          ○ therefore, we use a power series.

● [2:55:44]. Start from the Maclaurin series for 𝓮ˣ.
     ◉ Known:
          ○ 𝓮ˣ = 1 + 𝒙 + 𝒙²/2! + 𝒙³/3! + ...
     ◉ Series notation:
          ○ 𝓮ˣ = ∑[𝒏=0,∞] 𝒙ⁿ / 𝒏!
     ◉ Interval:
          ○ (-∞,∞)

● [2:56:00]. Substitute -𝒙² into the series.
     ◉ Since:
          ○ 𝓮ˣ = ∑[𝒏=0,∞] 𝒙ⁿ / 𝒏!
     ◉ Substitute:
          ○ 𝒙 → -𝒙²
     ◉ Then:
          ○ 𝓮⁻ˣ² = ∑[𝒏=0,∞] (-𝒙²)ⁿ / 𝒏!
     ◉ Simplify:
          ○ (-𝒙²)ⁿ = (-1)ⁿ𝒙²ⁿ
     ◉ Therefore:
          ○ 𝓮⁻ˣ² = ∑[𝒏=0,∞] (-1)ⁿ𝒙²ⁿ / 𝒏!

● [2:57:18]. Expanded form of 𝓮⁻ˣ².
     ◉ The series becomes:
          ○ 𝓮⁻ˣ² = 1 - 𝒙² + 𝒙⁴/2! - 𝒙⁶/3! + 𝒙⁸/4! - ...
     ◉ Meaning:
          ○ the powers of 𝒙 are even.
          ○ the signs alternate.
          ○ the denominator keeps the factorial pattern 𝒏!.

● [2:58:35]. Integrate term by term.
     ◉ Since:
          ○ 𝓮⁻ˣ² = ∑[𝒏=0,∞] (-1)ⁿ𝒙²ⁿ / 𝒏!
     ◉ Integrate both sides:
          ○ ∫𝓮⁻ˣ² d𝒙 = ∫∑[𝒏=0,∞] (-1)ⁿ𝒙²ⁿ / 𝒏! d𝒙
     ◉ Move the integral into the series:
          ○ ∫𝓮⁻ˣ² d𝒙 = ∑[𝒏=0,∞] ∫[(-1)ⁿ𝒙²ⁿ / 𝒏!] d𝒙

● [2:59:18]. Result after integration.
     ◉ Constants stay outside the integral:
          ○ (-1)ⁿ/𝒏!
     ◉ Integrate the power:
          ○ ∫𝒙²ⁿ d𝒙 = 𝒙²ⁿ⁺¹/(2𝒏 + 1)
     ◉ Therefore:
          ○ ∫𝓮⁻ˣ² d𝒙 = ∑[𝒏=0,∞] [(-1)ⁿ𝒙²ⁿ⁺¹] / [(2𝒏 + 1)𝒏!] + 𝑪

● [2:59:58]. Expanded integrated series.
     ◉ The integral becomes:
          ○ ∫𝓮⁻ˣ² d𝒙 = 𝒙 - 𝒙³/3 + 𝒙⁵/(5⋅2!) - 𝒙⁷/(7⋅3!) + 𝒙⁹/(9⋅4!) - ... + 𝑪
     ◉ Meaning:
          ○ each term is obtained by adding 1 to the power.
          ○ then dividing by the new power.

● [3:00:46]. Interval of convergence.
     ◉ No new convergence test is needed here.
     ◉ Reason:
          ○ the original series for 𝓮ˣ converges for all real 𝒙.
     ◉ Substituting:
          ○ 𝒙 → -𝒙²
     ◉ and integrating term by term:
          ○ do not restrict the interval of convergence.
     ◉ Therefore:
          ○ interval of convergence: (-∞,∞)
     ◉ Meaning:
          ○ the series representation for ∫𝓮⁻ˣ² d𝒙 is valid for every real 𝒙.


Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Taylor and Maclaurin Series
     ◉ [openstax 🌐](https://openstax.org/books/calculus-volume-2/pages/6-3-taylor-and-maclaurin-series)

● Working with Taylor Series
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/6-4-working-with-taylor-series)