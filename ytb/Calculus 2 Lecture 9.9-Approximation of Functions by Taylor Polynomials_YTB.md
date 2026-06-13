-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ９．９： Ａｐｐｒｏｘｉｍａｔｉｏｎ ｏｆ Ｆｕｎｃｔｉｏｎｓ ｂｙ Ｔａｙｌｏｒ Ｐｏｌｙｎｏｍｉａｌｓ**-----------------------------------






１ - Ｔａｙｌｏｒ　Ｐｏｌｙｎｏｍｉａｌｓ:　Ｔｈｅｏｒｙ

● [0:00]. Introduction — Approximating functions with Taylor polynomials.

● [0:09]. Taylor polynomials are based on Taylor series.
     ◉ Idea:
          ○ use part of a Taylor series.
          ○ approximate a function near a chosen center 𝑪.

● [0:30]. Review of Taylor series.
     ◉ A function can be represented by:
          ○ 𝒇(𝒙) = 𝒇(𝑪) + 𝒇'(𝑪)(𝒙 - 𝑪) + (𝒇''(𝑪)·(𝒙 - 𝑪)²)/2! + ... + (𝒇⁽ⁿ⁾(𝑪)·(𝒙 - 𝑪)ⁿ)/𝒏! + ...
     ◉ This keeps going forever.

● [1:43]. Taylor series versus Maclaurin series.
     ◉ Taylor series:
          ○ centered at any value 𝑪.
     ◉ Maclaurin series:
          ○ special Taylor series centered at 𝑪 = 0.

● [2:20]. Main idea — stop the Taylor series.
     ◉ A Taylor series goes forever.
     ◉ But in practice:
          ○ we stop at a particular term.
     ◉ When we stop at degree 𝒏:
          ○ we get a **Taylor polynomial.**

● [3:18]. Full Taylor series versus stopped Taylor series.
     ◉ Full Taylor series:
          ○ can represent the function exactly.
     ◉ Stopped Taylor series:
          ○ does not represent the function perfectly.
          ○ gives an approximation.

● [4:10]. Definition — nth degree Taylor polynomial.
     ◉ When the Taylor series is stopped at degree 𝒏:
          ○ the result is a polynomial.
     ◉ This is called:
          ○ the 𝒏-th degree Taylor polynomial.

● [5:17]. Remainder and error.
     ◉ A Taylor polynomial is missing the rest of the Taylor series.
     ◉ That missing part is called:
          ○ the remainder.
     ◉ The remainder measures:
          ○ **the error between the Taylor polynomial and the actual function.**

● [6:57]. Function equals Taylor polynomial plus remainder.
     ◉ Main relationship:
          ○ 𝒇(𝒙) = 𝑷ₙ(𝒙) + 𝑹ₙ(𝒙)
     ◉ Meaning:
          ○ Taylor polynomial + error = actual function.

● [7:15]. Formula for the remainder.
     ◉ Remainder formula:
          ○ 𝑹ₙ(𝒙) = (𝒇⁽ⁿ⁺¹⁾(𝒛)·(𝒙 - 𝑪)ⁿ⁺¹)/(𝒏 + 1)!
     ◉ This uses:
          ○ the next derivative after the degree of the polynomial.

● [9:11]. Meaning of 𝒛.
     ◉ 𝒛 is some number between:
          ○ 𝑪, the center.
          ○ 𝒙, the point being approximated.
     ◉ We choose 𝒛 to give the largest possible error.
     ◉ Reason:
          ○ we want to overestimate the error.
          ○ we do not want to underestimate it.






２ - Ｅｘａｍｐｌｅｓ　ｏｆ　Ｔａｙｌｏｒ　Ｐｏｌｙｎｏｍｉａｌ　Ａｐｐｒｏｘｉｍａｔｉｏｎ


２．１ - Ｅｘａｍｐｌｅ 1:　Ａｐｐｒｏｘｉｍａｔｉｎｇ　Ｌｎ（１．１）

● [10:05]. 🧩 Example 1 — Approximate Ln(1.1).
     ◉ Function:
          ○ 𝒇(𝒙) = Ln(𝒙)
     ◉ Goal:
          ○ approximate Ln(1.1)
     ◉ Method:
          ○ use a Taylor polynomial.
          ○ choose a center close to 1.1.

● [11:02]. Choose a nearby center.
     ◉ Approximation point:
          ○ 𝒙 = 1.1
     ◉ Choose:
          ○ 𝑪 = 1
     ◉ Reason:
          ○ 1 is close to 1.1.
          ○ Ln(1) is easy to compute.
     ◉ Therefore:
          ○ the Taylor polynomial will be centered at 𝑪 = 1.
          ○ all powers will involve (𝒙 - 1).

● [12:07]. Use a fourth degree Taylor polynomial.
     ◉ Degree:
          ○ 𝒏 = 4
     ◉ Meaning:
          ○ stop at the fourth derivative.
          ○ build 𝑷₄(𝒙).
     ◉ For the error:
          ○ go one derivative further.
          ○ use the fifth derivative.

● [13:20]. Find derivatives of Ln(𝒙).
     ◉ Start:
          ○ 𝒇(𝒙) = Ln(𝒙)
     ◉ First derivative:
          ○ 𝒇'(𝒙) = 1/𝒙
     ◉ Second derivative:
          ○ 𝒇''(𝒙) = -1/𝒙²
     ◉ Third derivative:
          ○ 𝒇'''(𝒙) = 2/𝒙³
     ◉ Fourth derivative:
          ○ 𝒇⁽⁴⁾(𝒙) = -6/𝒙⁴
     ◉ Fifth derivative:
          ○ 𝒇⁽⁵⁾(𝒙) = 24/𝒙⁵
     ◉ Important:
          ○ derivatives up to 𝒇⁽⁴⁾ are used for the Taylor polynomial.
          ○ 𝒇⁽⁵⁾ is saved for the error.

● [16:03]. Evaluate derivatives at 𝑪 = 1.
     ◉ Since:
          ○ 𝑪 = 1
     ◉ Substitute 𝒙 = 1 into each derivative.
     ◉ Values:
          ○ 𝒇(1) = Ln(1) = 0
          ○ 𝒇'(1) = 1
          ○ 𝒇''(1) = -1
          ○ 𝒇'''(1) = 2
          ○ 𝒇⁽⁴⁾(1) = -6
          ○ 𝒇⁽⁵⁾(1) = 24

● [18:02]. Build the fourth degree Taylor polynomial.
     ◉ General fourth degree Taylor polynomial:
          ○ 𝑷₄(𝒙) = 𝒇(1) + 𝒇'(1)(𝒙 - 1) + (𝒇''(1)·(𝒙 - 1)²)/2! + (𝒇'''(1)·(𝒙 - 1)³)/3! + (𝒇⁽⁴⁾(1)·(𝒙 - 1)⁴)/4!
     ◉ Substitute the values:
          ○ 𝑷₄(𝒙) = 0 + 1(𝒙 - 1) + (-1·(𝒙 - 1)²)/2! + (2·(𝒙 - 1)³)/3! + (-6·(𝒙 - 1)⁴)/4!

● [21:18]. Simplify the Taylor polynomial.
     ◉ Simplify each coefficient:
          ○ 2/3! = 2/6 = 1/3
          ○ -6/4! = -6/24 = -1/4
     ◉ Therefore:
          ○ 𝑷₄(𝒙) = (𝒙 - 1) - (𝒙 - 1)²/2 + (𝒙 - 1)³/3 - (𝒙 - 1)⁴/4
     ◉ Meaning:
          ○ this fourth degree Taylor polynomial approximates Ln(𝒙) around 𝑪 = 1.

● [24:08]. Approximate Ln(1.1).
     ◉ Since:
          ○ 𝒙 = 1.1
     ◉ Then:
          ○ 𝒙 - 1 = 0.1
     ◉ Substitute into the Taylor polynomial:
          ○ Ln(1.1) ≈ 𝑷₄(1.1)
     ◉ Therefore:
          ○ 𝑷₄(1.1) = 0.1 - (0.1)²/2 + (0.1)³/3 - (0.1)⁴/4
     ◉ Approximation:
          ○ Ln(1.1) ≈ 0.095308333...

● [27:41]. Need to measure the error.
     ◉ This is only an approximation.
     ◉ Reason:
          ○ we stopped the Taylor series at degree 4.
          ○ therefore, we do not have the full Taylor series.
     ◉ Question:
          ○ how close is 𝑷₄(1.1) to the real value of Ln(1.1)?

● [28:49]. Remainder for the fourth degree Taylor polynomial.
     ◉ Since:
          ○ 𝒏 = 4
     ◉ The error uses:
          ○ the next derivative.
          ○ the fifth derivative.
     ◉ Remainder formula:
          ○ 𝑹₄(𝒙) = (𝒇⁽⁵⁾(𝒛)·(𝒙 - 𝑪)⁴⁺¹)/(4 + 1)!
     ◉ Since:
          ○ 𝑪 = 1
     ◉ Then:
          ○ 𝑹₄(𝒙) = (𝒇⁽⁵⁾(𝒛)·(𝒙 - 1)⁵)/5!
     ◉ Here:
          ○ 𝒛 is between 1 and 1.1.

● [31:13]. Choose 𝒛 for the largest error.
     ◉ Fifth derivative:
          ○ 𝒇⁽⁵⁾(𝒙) = 24/𝒙⁵
     ◉ Therefore:
          ○ 𝒇⁽⁵⁾(𝒛) = 24/𝒛⁵
     ◉ Since:
          ○ 1 ≤ 𝒛 ≤ 1.1
     ◉ To get the largest error:
          ○ choose the value of 𝒛 that makes 24/𝒛⁵ as large as possible.
     ◉ Since 𝒛 is in the denominator:
          ○ the smaller 𝒛 is,
          ○ the larger 24/𝒛⁵ becomes.
     ◉ Therefore:
          ○ choose 𝒛 = 1.
     ◉ Then:
          ○ 𝒇⁽⁵⁾(1) = 24

● [34:01]. Compute the maximum error.
     ◉ Start from:
          ○𝑹₄(𝒙) = (𝒇⁽⁵⁾(𝒛)·(𝒙 - 1)⁵)/5!
     ◉ Substitute:
          ○ 𝒙 = 1.1
          ○ 𝒛 = 1
          ○ 𝒇⁽⁵⁾(1) = 24
     ◉ Then:
          ○𝑹₄(1.1) = (24·(1.1 - 1)⁵)/5!
     ◉ Since:
          ○ 1.1 - 1 = 0.1
     ◉ Then:
          ○ 𝑹₄(1.1) = (24·(0.1)⁵)/5!
     ◉ Simplify:
          ○ 5! = 120
          ○ 24/120 = 1/5
     ◉ Therefore:
          ○ 𝑹₄(1.1) = (0.1)⁵/5
          ○ 𝑹₄(1.1) = 0.000002
          ○ 𝑹₄(1.1) = 2 × 10⁻⁶

● [35:58]. Final interpretation.
     ◉ Approximation:
          ○ Ln(1.1) ≈ 𝑷₄(1.1)
          ○ 𝑷₄(1.1) ≈ 0.095308333...
     ◉ Error bound:
          ○ |error| ≤ 2 × 10⁻⁶
          ○ |error| ≤ 0.000002
     ◉ Meaning:
          ○ the approximation is within 0.000002 of the real value.
          ○ the fourth degree Taylor polynomial gives a very close approximation.
     ◉ Interval for the real value:
          ○ 0.095308333... - 0.000002 ≤ Ln(1.1) ≤ 0.095308333... + 0.000002
     ◉ In absolute value form:
          ○ |Ln(1.1) - 𝑷₄(1.1)| ≤ 0.000002
     ◉ Key idea:
          ○ exact value = infinite series.
          ○ approximation = Taylor polynomial stopped at degree 4.
          ○ error = difference between the exact value and the approximation.
     ◉ In this problem:
          ○ exact value:
               ■ Ln(1.1)
          ○ approximation:
               ■ 𝑷₄(1.1)
          ○ error:
               ■ |Ln(1.1) - 𝑷₄(1.1)|
     ◉ Therefore:
          ○ |Ln(1.1) - 𝑷₄(1.1)| ≤ 0.000002

● N̲O̲T̲E̲ — Difference between 𝒙 and 𝒛.
     ◉ In the approximation:
          ○ 𝒙 = 1.1
     ◉ But in the error formula:
          ○ 𝒛 is some number between 𝑪 and 𝒙.
     ◉ Here:
          ○ 𝑪 = 1
          ○ 𝒙 = 1.1
          ○ so 1 ≤ 𝒛 ≤ 1.1
     ◉ Important:
          ○ 𝒙 and 𝒛 do not have to be the same number.
     ◉ In this example:
          ○ 𝒙 = 1.1
          ○ 𝒛 = 1
     ◉ Reason:
          ○ 𝒙 is the point we want to approximate.
          ○ 𝒛 is chosen to make the error as large as possible.
          ○ choosing the largest possible error gives a safe error bound.



２．２ - Ｅｘａｍｐｌｅ 2:　Ｔａｙｌｏｒ　Ｐｏｌｙｎｏｍｉａｌ　ｆｏｒ　√𝒙

● [37:37]. 🧩 Example 2 — Taylor polynomial for √𝒙.
     ◉ Function:
          ○ 𝒇(𝒙) = √𝒙
     ◉ Task:
          ○ find the second degree Taylor polynomial.
     ◉ Center:
          ○ 𝑪 = 4
     ◉ Interval for the error:
          ○ [3,5]

● [39:21]. Start with derivatives.
     ◉ Need:
          ○ derivatives up to degree 2.
     ◉ Also need:
          ○ one more derivative for the error.
     ◉ Reason:
          ○ a second degree Taylor polynomial uses 𝒇, 𝒇', and 𝒇''.
          ○ its error uses 𝒇'''.

● [39:31]. Find derivatives of √𝒙.
     ◉ Start:
          ○ 𝒇(𝒙) = √𝒙 = 𝒙¹ᐟ²
     ◉ First derivative:
          ○ 𝒇'(𝒙) = (1/2)𝒙⁻¹ᐟ²
     ◉ Second derivative:
          ○ 𝒇''(𝒙) = -(1/4)𝒙⁻³ᐟ²
     ◉ Third derivative:
          ○ 𝒇'''(𝒙) = (3/8)𝒙⁻⁵ᐟ²
          ○ 𝒇'''(𝒙) = 3/(8𝒙⁵ᐟ²)

● [40:43]. Evaluate derivatives at 𝑪 = 4.
     ◉ Since:
          ○ 𝑪 = 4
     ◉ Values:
          ○ 𝒇(4) = √4 = 2
          ○ 𝒇'(4) = 1/4
          ○ 𝒇''(4) = -1/32
          ○ 𝒇'''(4) = 3/256
     ◉ Important:
          ○ 𝒇'''(4) is not used in 𝑷₂(𝒙).
          ○ it is saved for the error.

● [42:29]. Build the second degree Taylor polynomial.
     ◉ Formula:
          ○ 𝑷₂(𝒙) = 𝒇(4) + 𝒇'(4)(𝒙 - 4) + (𝒇''(4)·(𝒙 - 4)²)/2!
     ◉ Substitute:
          ○ 𝑷₂(𝒙) = 2 + (1/4)(𝒙 - 4) + ((-1/32)·(𝒙 - 4)²)/2!

● [43:06]. Simplify.
     ◉ Since:
          ○ 2! = 2
          ○ (-1/32)/2 = -1/64
     ◉ Result:
          ○ 𝑷₂(𝒙) = 2 + (𝒙 - 4)/4 - (𝒙 - 4)²/64

● [44:20]. Meaning of the polynomial.
     ◉ This polynomial approximates:
          ○ √𝒙
     ◉ Around:
          ○ 𝑪 = 4
     ◉ Meaning:
          ○ values of 𝒙 close to 4 should give good approximations.

● [45:29]. Next step — maximum error.
     ◉ The polynomial can approximate values on:
          ○ [3,5]
     ◉ Need:
          ○ maximum possible error on that interval.

● [48:28]. Remainder for the second degree polynomial.
     ◉ Since:
          ○ 𝒏 = 2
     ◉ The error uses:
          ○ the next derivative.
          ○ the third derivative.
     ◉ Remainder formula:
          ○ 𝑹₂(𝒙) = (𝒇'''(𝒛)·(𝒙 - 4)³)/3!
     ◉ Here:
          ○ 𝒛 is between the center 4 and the value of 𝒙 being approximated.
          ○ since the interval is [3,5], we can take 𝒛 ∈ [3,5] for the maximum-error estimate.

● [50:21]. Substitute the third derivative.
     ◉ Since:
          ○ 𝒇'''(𝒙) = 3/(8𝒙⁵ᐟ²)
     ◉ Then:
          ○ 𝒇'''(𝒛) = 3/(8𝒛⁵ᐟ²)
     ◉ Therefore:
          ○ 𝑹₂(𝒙) = (3/(8𝒛⁵ᐟ²))·((𝒙 - 4)³/3!)

● [51:21]. Choose values for maximum error.
     ◉ On the interval:
          ○ 3 ≤ 𝒙 ≤ 5
     ◉ To maximize |𝒙 - 4|:
          ○ choose an endpoint.
          ○ 𝒙 = 3 or 𝒙 = 5.
     ◉ Leonard chooses:
          ○ 𝒙 = 5
     ◉ Then:
          ○ |𝒙 - 4| = |5 - 4| = 1
     ◉ To maximize:
          ○ 3/(8𝒛⁵ᐟ²)
     ◉ choose the smallest possible 𝒛.
     ◉ Since:
          ○ 𝒛 ∈ [3,5]
     ◉ choose:
          ○ 𝒛 = 3
     ◉ Reason:
          ○ 𝒛 is in the denominator.
          ○ smaller 𝒛 gives a larger fraction.
          ○ larger fraction gives a larger error bound.

● [54:09]. Compute the maximum error.
     ◉ Start from:
          ○ 𝑹₂(𝒙) = (3/(8𝒛⁵ᐟ²))·((𝒙 - 4)³/3!)
     ◉ Substitute:
          ○ 𝒛 = 3
          ○ 𝒙 = 5
     ◉ Then:
          ○ 𝑹₂(𝒙) = (3/(8·3⁵ᐟ²))·((5 - 4)³/3!)
     ◉ Since:
          ○ (5 - 4)³ = 1
          ○ 3! = 3·2·1 = 6
     ◉ Then:
          ○ 𝑹₂(𝒙) = (3/(8·3⁵ᐟ²))·(1/6)
     ◉ Simplify:
          ○ 𝑹₂(𝒙) = 3/(48·3⁵ᐟ²)
          ○ 𝑹₂(𝒙) = 1/(16·3⁵ᐟ²)
     ◉ Approximation:
          ○ 𝑹₂(𝒙) ≈ 0.004

● [56:33]. Final interpretation.
     ◉ Maximum error:
          ○ |error| ≤ 0.004
     ◉ Meaning:
          ○ for any 𝒙 in [3,5],
          ○ the approximation given by 𝑷₂(𝒙)
          ○ is within about 0.004 of the true value √𝒙.
     ◉ In absolute value form:
          ○ |√𝒙 - 𝑷₂(𝒙)| ≤ 0.004
          ○ for 3 ≤ 𝒙 ≤ 5



３ - Ｗｈｅｎ　Ｄｏｅｓ　ａ　Ｆｕｎｃｔｉｏｎ　Ｈａｖｅ　ａ　Ｔａｙｌｏｒ　Ｓｅｒｉｅｓ　Ｒｅｐｒｅｓｅｎｔａｔｉｏｎ？

● [57:51]. New question — When does a function have a Taylor series representation?
     ◉ Question:
          ○ when does a Taylor series actually represent the original function?

● [58:47]. Use the remainder.
     ◉ Main idea:
          ○ a Taylor polynomial has a remainder.
          ○ the remainder measures the error between the polynomial and the function.
     ◉ Therefore:
          ○ if the remainder goes to zero,
          ○ the Taylor series represents the function.

● [59:38]. Key theorem.
     ◉ i̲f̲:
          ○ limₙ→∞ 𝑹ₙ(𝒙) = 0
     ◉ t̲h̲e̲n̲:
          ○ the function can be represented by its Taylor series centered at 𝑪.

● [1:00:39]. Idea of the proof.
     ◉ Start from:
          ○ 𝒇(𝒙) = 𝑷ₙ(𝒙) + 𝑹ₙ(𝒙)
     ◉ Rearrange:
          ○ 𝑷ₙ(𝒙) = 𝒇(𝒙) - 𝑹ₙ(𝒙)
     ◉ i̲f̲:
          ○ 𝑹ₙ(𝒙) → 0
     ◉ t̲h̲e̲n̲:
          ○ 𝑷ₙ(𝒙) → 𝒇(𝒙)

● [1:02:53]. What happens as 𝒏 goes to infinity.
     ◉ As:
          ○ 𝒏 → ∞
     ◉ The Taylor polynomial:
          ○ includes more and more terms.
     ◉ In the limit:
          ○ the Taylor polynomials become the Taylor series.
     ◉ Therefore:
          ○ i̲f̲ 𝑹ₙ(𝒙) → 0,
               ■ t̲h̲e̲n̲ the Taylor series represents the function.

● [1:04:16]. Useful limit.
     ◉ Important limit:
          ○ limₙ→∞ |𝒙|ⁿ/𝒏! = 0
     ◉ Meaning:
          ○ factorial growth eventually beats any fixed power of 𝒙.
     ◉ This will be used:
          ○ to prove that certain remainders go to 0.
          ○ especially in examples involving 𝓮ˣ and Sin(𝒙).





４ - Ｅｘａｍｐｌｅｓ　ｏｆ　Ｐｒｏｖｉｎｇ　Ｔａｙｌｏｒ　Ｓｅｒｉｅｓ　Ｒｅｐｒｅｓｅｎｔａｔｉｏｎ


４．１ - Ｅｘａｍｐｌｅ 3:　Ｓｈｏｗ　ｔｈａｔ　ｔｈｅ　Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　𝓮ˣ　Ｒｅｐｒｅｓｅｎｔｓ　𝓮ˣ

● [1:06:39]. 🧩 Example 3 — Show that the Maclaurin series for 𝓮ˣ represents 𝓮ˣ.
     ◉ Known Maclaurin series:
          ○ 𝓮ˣ = ∑[𝒏=0,∞] 𝒙ⁿ/𝒏!
     ◉ Goal:
          ○ prove that this series actually represents 𝓮ˣ.
     ◉ Method:
          ○ show that the remainder goes to zero.

● [1:08:13]. Do not reinvent the wheel.
     ◉ We already know the Maclaurin series for 𝓮ˣ.
     ◉ We do not need to derive the series again.
     ◉ Instead, we prove:
          ○ limₙ→∞ 𝑹ₙ(𝒙) = 0
     ◉ If the remainder goes to zero:
          ○ the Taylor series represents the function.

● [1:10:12]. Start from the remainder formula.
     ◉ Formula:
          ○ 𝑹ₙ(𝒙) = (𝒇⁽ⁿ⁺¹⁾(𝒛)·(𝒙 - 𝑪)ⁿ⁺¹)/(𝒏 + 1)!
     ◉ Here:
          ○ 𝒛 is between 𝑪 and 𝒙.

● [1:10:55]. Since this is Maclaurin.
     ◉ Center:
          ○ 𝑪 = 0
     ◉ Therefore:
          ○ 𝑹ₙ(𝒙) = (𝒇⁽ⁿ⁺¹⁾(𝒛)·𝒙ⁿ⁺¹)/(𝒏 + 1)!

● [1:11:48]. Derivatives of 𝓮ˣ.
     ◉ Since:
          ○ 𝒇(𝒙) = 𝓮ˣ
     ◉ Every derivative is:
          ○ 𝓮ˣ
     ◉ Therefore:
          ○ 𝒇⁽ⁿ⁺¹⁾(𝒙) = 𝓮ˣ
     ◉ Substitute 𝒛:
          ○ 𝒇⁽ⁿ⁺¹⁾(𝒛) = 𝓮ᶻ

● [1:13:43]. Remainder expression.
     ◉ Substitute into the remainder formula:
          ○ 𝑹ₙ(𝒙) = (𝓮ᶻ·𝒙ⁿ⁺¹)/(𝒏 + 1)!
     ◉ Now we need to show:
          ○ limₙ→∞ 𝑹ₙ(𝒙) = 0

● [1:16:00]. Case ❶ — 𝒙 > 0.
     ◉ Since:
          ○ 𝒛 is between 0 and 𝒙
     ◉ Then:
          ○ 0 < 𝒛 < 𝒙
     ◉ Therefore:
          ○ 𝓮ᶻ < 𝓮ˣ
     ◉ Also:
          ○ 𝑹ₙ(𝒙) = (𝓮ᶻ·𝒙ⁿ⁺¹)/(𝒏 + 1)!
          ○ Since 𝒙 > 0:
               ■ 𝑹ₙ(𝒙) is positive.

● [1:17:43]. Squeeze the remainder for 𝒙 > 0.
     ◉ Bound:
          ○ 0 ≤ 𝑹ₙ(𝒙) ≤ (𝓮ˣ·𝒙ⁿ⁺¹)/(𝒏 + 1)!
     ◉ Since 𝒙 is fixed:
          ○ 𝓮ˣ is a constant.
     ◉ Useful limit:
          ○ limₙ→∞ 𝒙ⁿ⁺¹/(𝒏 + 1)! = 0
     ◉ Therefore:
          ○ limₙ→∞ (𝓮ˣ·𝒙ⁿ⁺¹)/(𝒏 + 1)! = 0
     ◉ By the Squeeze Theorem:
          ○ limₙ→∞ 𝑹ₙ(𝒙) = 0

● [1:21:01]. Case ❷ — 𝒙 < 0.
     ◉ Since:
          ○ 𝒛 is between 𝒙 and 0
     ◉ Then:
          ○ 𝒙 < 𝒛 < 0
     ◉ Therefore:
          ○ 𝒛 < 0
     ◉ So:
          ○ 𝓮ᶻ < 𝓮⁰
          ○ 𝓮ᶻ < 1

● [1:21:39]. Squeeze the absolute value for 𝒙 < 0.
     ◉ Use absolute value:
          ○ |𝑹ₙ(𝒙)| = |(𝓮ᶻ·𝒙ⁿ⁺¹)/(𝒏 + 1)!|
     ◉ Since:
          ○ 𝓮ᶻ < 1
     ◉ Then:
          ○ 0 ≤ |𝑹ₙ(𝒙)| ≤ |𝒙|ⁿ⁺¹/(𝒏 + 1)!
     ◉ Useful limit:
          ○ limₙ→∞ |𝒙|ⁿ⁺¹/(𝒏 + 1)! = 0
     ◉ By the Squeeze Theorem:
          ○ limₙ→∞ |𝑹ₙ(𝒙)| = 0
     ◉ Therefore:
          ○ limₙ→∞ 𝑹ₙ(𝒙) = 0

● [1:25:21]. Conclusion.
     ◉ In both cases:
          ○ 𝒙 > 0
          ○ 𝒙 < 0
     ◉ the remainder goes to zero:
          ○ limₙ→∞ 𝑹ₙ(𝒙) = 0
     ◉ Also:
          ○ if 𝒙 = 0, the result is immediate.
     ◉ Therefore:
          ○ the Maclaurin series for 𝓮ˣ represents 𝓮ˣ.
     ◉ Final statement:
          ○ 𝓮ˣ = ∑[𝒏=0,∞] 𝒙ⁿ/𝒏!

● N̲O̲T̲E̲ — Why this limit goes to 0.
     ◉ Limit:
          ○ limₙ→∞ (𝓮ˣ·𝒙ⁿ⁺¹)/(𝒏 + 1)! = 0
     ◉ At first sight:
          ○ if 𝒙 > 1,
          ○ the numerator grows.
          ○ the denominator also grows.
          ○ so it may look like an ∞/∞ situation.
     ◉ But here:
          ○ 𝒙 is fixed.
          ○ 𝓮ˣ is also fixed.
          ○ the variable going to infinity is 𝒏.
     ◉ Therefore:
          ○ this is best understood as a sequence.
          ○ the clean way is to compare consecutive terms.
     ◉ Let:
          ○ 𝒂ₙ = (𝓮ˣ·𝒙ⁿ⁺¹)/(𝒏 + 1)!
     ◉ Then:
          ○ 𝒂ₙ₊₁ = (𝓮ˣ·𝒙ⁿ⁺²)/(𝒏 + 2)!
     ◉ Compare consecutive terms:
          ○ 𝒂ₙ₊₁/𝒂ₙ
          ○ = ((𝓮ˣ·𝒙ⁿ⁺²)/(𝒏 + 2)!) · ((𝒏 + 1)!)/(𝓮ˣ·𝒙ⁿ⁺¹)
     ◉ Cancel common factors:
          ○ 𝓮ˣ cancels.
          ○ 𝒙ⁿ⁺¹ cancels.
          ○ (𝒏 + 1)!/(𝒏 + 2)! = 1/(𝒏 + 2)
     ◉ Therefore:
          ○ 𝒂ₙ₊₁/𝒂ₙ = 𝒙/(𝒏 + 2)
     ◉ Now:
          ○ limₙ→∞ 𝒙/(𝒏 + 2) = 0
     ◉ Meaning:
          ○ each new term eventually becomes much smaller than the previous one.
          ○ the factorial in the denominator grows faster than the fixed power in the numerator.
     ◉ Therefore:
          ○ 𝒂ₙ → 0
     ◉ So:
          ○ limₙ→∞ (𝓮ˣ·𝒙ⁿ⁺¹)/(𝒏 + 1)! = 0
     ◉ Main idea:
          ○ powers grow by multiplying by the same fixed number 𝒙.
          ○ factorials grow by multiplying by larger and larger numbers.
          ○ therefore, the factorial eventually wins.


４．２ - Ｅｘａｍｐｌｅ 4:　Ｓｈｏｗ　ｔｈａｔ　ｔｈｅ　Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　Ｓｉｎ（𝒙）　Ｒｅｐｒｅｓｅｎｔｓ　Ｓｉｎ（𝒙）

● [1:26:57]. 🧩 Example 4 — Show that the Maclaurin series for Sin(𝒙) represents Sin(𝒙).
     ◉ Known Maclaurin series:
          ○ Sin(𝒙) = ∑[𝒏=0,∞] (-1)ⁿ𝒙²ⁿ⁺¹/(2𝒏 + 1)!
     ◉ Goal:
          ○ prove that this series actually represents Sin(𝒙).
     ◉ Method:
          ○ show that the remainder goes to zero.

● [1:27:42]. Goal.
     ◉ Show:
          ○ limₙ→∞ 𝑹ₙ(𝒙) = 0
     ◉ Meaning:
          ○ if the remainder goes to zero,
          ○ then the Taylor series represents the function.

● [1:28:17]. Start from the remainder formula.
     ◉ Since this is a Maclaurin series:
          ○ 𝑪 = 0
     ◉ Remainder formula:
          ○ 𝑹ₙ(𝒙) = (𝒇⁽ⁿ⁺¹⁾(𝒛)·𝒙ⁿ⁺¹)/(𝒏 + 1)!
     ◉ Here:
          ○ 𝒛 is between 0 and 𝒙.

● [1:28:58]. Derivatives of Sin(𝒙).
     ◉ Derivatives cycle through:
          ○ Sin(𝒙)
          ○ Cos(𝒙)
          ○ -Sin(𝒙)
          ○ -Cos(𝒙)
     ◉ Therefore:
          ○ 𝒇⁽ⁿ⁺¹⁾(𝒛) is always one of:
               ■ ±Sin(𝒛)
               ■ ±Cos(𝒛)

● [1:30:24]. Bound the derivative.
     ◉ Since:
          ○ -1 ≤ Sin(𝒛) ≤ 1
          ○ -1 ≤ Cos(𝒛) ≤ 1
     ◉ Then:
          ○ -1 ≤ 𝒇⁽ⁿ⁺¹⁾(𝒛) ≤ 1
     ◉ In absolute value:
          ○ |𝒇⁽ⁿ⁺¹⁾(𝒛)| ≤ 1

● [1:30:58]. Bound the remainder.
     ◉ Start from:
          ○ 𝑹ₙ(𝒙) = (𝒇⁽ⁿ⁺¹⁾(𝒛)·𝒙ⁿ⁺¹)/(𝒏 + 1)!
     ◉ Take absolute value:
          ○ |𝑹ₙ(𝒙)| = |(𝒇⁽ⁿ⁺¹⁾(𝒛)·𝒙ⁿ⁺¹)/(𝒏 + 1)!|
     ◉ Since:
          ○ |𝒇⁽ⁿ⁺¹⁾(𝒛)| ≤ 1
     ◉ Therefore:
          ○ 0 ≤ |𝑹ₙ(𝒙)| ≤ |𝒙|ⁿ⁺¹/(𝒏 + 1)!

● [1:32:19]. Take the limit.
     ◉ Since:
          ○ limₙ→∞ |𝒙|ⁿ⁺¹/(𝒏 + 1)! = 0
     ◉ By the Squeeze Theorem:
          ○ limₙ→∞ |𝑹ₙ(𝒙)| = 0
     ◉ Therefore:
          ○ limₙ→∞ 𝑹ₙ(𝒙) = 0

● [1:33:01]. Conclusion.
     ◉ Since:
          ○ limₙ→∞ 𝑹ₙ(𝒙) = 0
     ◉ Therefore:
          ○ the Maclaurin series for Sin(𝒙) represents Sin(𝒙).
     ◉ Final statement:
          ○ Sin(𝒙) = ∑[𝒏=0,∞] (-1)ⁿ𝒙²ⁿ⁺¹/(2𝒏 + 1)!


Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Taylor polynomial remainder
     ◉ [Khan Academy 🌐](https://www.khanacademy.org/math/ap-calculus-bc/bc-series-new/bc-10-12/v/error-or-remainder-of-a-taylor-polynomial-approximation)

