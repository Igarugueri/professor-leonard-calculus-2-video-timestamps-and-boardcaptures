-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ９．５： Ｓｈｏｗｉｎｇ Ｃｏｎｖｅｒｇｅｎｃｅ Ｗｉｔｈ ｔｈｅ Aｌｔｅｒｎａｔｉｎｇ Ｓｅｒｉｅｓ Ｔｅｓｔ， Ｆｉｎｄｉｎｇ Ｅｒｒｏｒ ｏｆ Ｓｕｍｓ**----------------------------------





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
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n-1}}{𝒏}$
          $\rule{0pt}{}$
     ◉ Expand the first terms:
          $\rule{0pt}{}$
          ○ $1-\dfrac{1}{2}+\dfrac{1}{3}-\dfrac{1}{4}+\dfrac{1}{5}-\cdots$
          $\rule{0pt}{}$
     ◉ Key observation:
          ○ the signs alternate:
               ■ $+,-,+,-,+,\ldots$
          ○ therefore, this is an alternating series.

● Identifying the alternating factor.
     ◉ The factor that creates the sign change is:
          $\rule{0pt}{}$
          ○ $(-1)^{n-1}$
     ◉ If the series starts with a positive term,
          ○ we often use $(-1)^{n-1}$.
     ◉ If the series starts with a negative term,
          ○ we often use $(-1)^{n}$.
     ◉ Key idea:
          ○ the $(-1)$ factor controls the signs.
          ○ the rest of the expression gives the positive size of each term.

● [3:20](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=200). General structure of an alternating series.
     ◉ Any alternating series can usually be written as:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}(-1)^{n-1}\cdot 𝒂_{n}$
          $\rule{0pt}{}$
     ◉ Here:
          ○ $(-1)^{n-1}$ creates the alternating signs.
          ○ $𝒂_{n}$ represents the positive part of the terms.
     ◉ In this example:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{1}{𝒏}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n-1}}{𝒏}=\sum_{n=1}^{\infty}(-1)^{n-1}\cdot \dfrac{1}{𝒏}$
          $\rule{0pt}{}$
     ◉ Important:
          ○ $𝒂_{n}$ itself is positive.
          ○ the alternating sign is not considered part of $𝒂_{n}$.

● [4:17](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=257). Harmonic Series versus Alternating Harmonic Series.
     ◉ Harmonic Series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{𝒏}$
          $\rule{0pt}{}$
          ○ $=1+\dfrac{1}{2}+\dfrac{1}{3}+\dfrac{1}{4}+\cdots$
          $\rule{0pt}{}$
          ○ diverges.
     ◉ Alternating Harmonic Series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n-1}}{𝒏}$
          $\rule{0pt}{}$
          ○ $=1-\dfrac{1}{2}+\dfrac{1}{3}-\dfrac{1}{4}+\cdots$
          $\rule{0pt}{}$
          ○ converges.
     ◉ Important:
          ○ adding alternating signs can change the convergence behavior.
          ○ the harmonic series diverges,
               ■ but the alternating harmonic series converges.






Ｉｎｔｒｏｄｕｃｔｉｏｎ　Ｅｘａｍｐｌｅ  2

● [📷image](../img/Calculus 2 Lecture 9.5/[5-15]-01.png)

● [5:15](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=315). 🧩 Example 2 — Alternating series $\displaystyle \sum_{n=1}^{\infty}(-1)^{n}\dfrac{𝒏^{2}}{(𝒏+1)!}$
     ◉ Expand the first terms:
          $\rule{0pt}{}$
          ○ $-\dfrac{1}{2!}+\dfrac{4}{3!}-\dfrac{9}{4!}+\dfrac{16}{5!}-\cdots$
          $\rule{0pt}{}$
     ◉ Key observation:
          ○ the signs alternate:
               ■ $-,+,-,+,\ldots$
          ○ therefore, this is an alternating series.

● Identifying the alternating factor.
     ◉ The factor that creates the sign change is:
          $\rule{0pt}{}$
          ○ $(-1)^{n}$
     ◉ Since the series starts with a negative term,
          ○ $(-1)^{n}$ is the natural alternating factor.
     ◉ The positive part of the terms is:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{𝒏^{2}}{(𝒏+1)!}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}(-1)^{n}\dfrac{𝒏^{2}}{(𝒏+1)!}=\sum_{n=1}^{\infty}(-1)^{n}\cdot 𝒂_{n}$

● General structure.
     ◉ This example has the form:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}(-1)^{n}\cdot 𝒂_{n}$
          $\rule{0pt}{}$
     ◉ Here:
          ○ $(-1)^{n}$ creates the alternating signs.
          ○ $𝒂_{n}$ represents the positive size of each term.
     ◉ In this example:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{𝒏^{2}}{(𝒏+1)!}$
          $\rule{0pt}{}$
     ◉ Important:
          ○ $𝒂_{n}$ itself is positive.
          ○ the alternating sign is not considered part of $𝒂_{n}$.





               

Ａｌｔｅｒｎａｔｉｎｇ　Ｓｅｒｉｅｓ　Ｔｅｓｔ  (ＡＳＴ)

● [📷image](../img/Calculus 2 Lecture 9.5/[7-53]-01.png)

● [7:53](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=473). The Alternating Series Test.
     ◉ The Alternating Series Test applies to series of the form:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}(-1)^{n-1}\cdot 𝒂_{n}$
          $\rule{0pt}{}$
          ○ or $\displaystyle \sum_{n=1}^{\infty}(-1)^{n}\cdot 𝒂_{n}$
          $\rule{0pt}{}$
     ◉ Where:
          $\rule{0pt}{}$
          ○ $𝒂_{n}>0$
     ◉ The test checks two things:
          ○ the positive terms $𝒂_{n}$ must be decreasing.
          ○ the positive terms $𝒂_{n}$ must approach $0$.

● [9:24](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=564). Condition 1 — Decreasing sequence.
     ◉ The positive sequence must be decreasing:
          $\rule{0pt}{}$
          ○ $𝒂_{n+1}\le 𝒂_{n}$
     ◉ Meaning:
          ○ each next positive term is less than or equal to the previous one.
     ◉ This is important because:
          ○ the alternating partial sums move back and forth,
          ○ but the jumps get smaller and smaller.

● [10:30](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=630). Condition 2 — Limit of the positive terms.
     ◉ The positive terms must approach $0$:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}𝒂_{n}=0$
          $\rule{0pt}{}$
     ◉ This is like the Divergence Test,
          ○ but applied to the positive part $𝒂_{n}$.
     ◉ Important:
          ○ do not include $(-1)^{n}$ or $(-1)^{n-1}$ when checking this limit.
          ○ only use the positive part $𝒂_{n}$.

● [11:26](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=686). Conclusion of the Alternating Series Test.
$\rule{0pt}{}$
     ◉ i̲f̲  $𝒂_{n+1}\le 𝒂_{n}$  a̲n̲d̲  $\displaystyle \lim_{n\to\infty}𝒂_{n}=0$
     $\rule{0pt}{}$
          ○ t̲h̲e̲n̲ the alternating series $\displaystyle \sum (-1)^{n-1}𝒂_{n}$ converges.
     ◉ In words:
          ○ if the positive terms decrease to $0$,
               ■ then the alternating series converges.

● [11:26](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=686). Recap — How to use the Alternating Series Test.
     ◉ First, verify that the series is alternating.
          ○ the signs must alternate:
               ■ $+,-,+,-,\ldots$
               ■ or $-,+,-,+,\ldots$
          ○ this usually comes from:
               ■ $(-1)^{n}$
               ■ or $(-1)^{n-1}$
     ◉ Then, separate the series into:
          ○ the alternating factor,
          ○ and the positive part $𝒂_{n}$.
     ◉ General form:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum (-1)^{n-1}𝒂_{n}$
          $\rule{0pt}{}$
          ○ or $\displaystyle \sum (-1)^{n}𝒂_{n}$
          $\rule{0pt}{}$
     ◉ Important:
          ○ $𝒂_{n}$ is only the positive part.
          ○ do not include $(-1)^{n}$ or $(-1)^{n-1}$ inside $𝒂_{n}$.
     ◉ Step 1 — Check the limit of the positive terms:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}𝒂_{n}=0$
          $\rule{0pt}{}$
     ◉ Step 2 — Check that the positive terms are decreasing:
          $\rule{0pt}{}$
          ○ $𝒂_{n+1}\le 𝒂_{n}$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ i̲f̲ $𝒂_{n}\to 0$,
          ○ a̲n̲d̲ $𝒂_{n}$ is decreasing,
               ■ t̲h̲e̲n̲ the alternating series converges.
     ◉ Key idea:
          ○ the test is not applied to the whole signed term.
          ○ it is applied to the positive sequence $𝒂_{n}$.
          
● [13:58](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=838). Graphical and conceptual justification.
     ◉ Imagine the partial sums moving back and forth:
          ○ add a positive term,
          ○ subtract a smaller term,
          ○ add an even smaller term,
          ○ subtract an even smaller term,
          ○ and so on.
     ◉ Because the terms are decreasing:
          ○ each jump is smaller than the previous jump.
     ◉ Because the terms approach $0$:
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
          $\rule{0pt}{}$
          ○ $1-\dfrac{1}{2}+\dfrac{1}{3}-\dfrac{1}{4}+\dfrac{1}{5}-\dfrac{1}{6}+\cdots$
          $\rule{0pt}{}$
     ◉ Partial sums:
          $\rule{0pt}{}$
          ○ $S_{1}=1$
          $\rule{0pt}{}$
          ○ $S_{2}=0.5$
          $\rule{0pt}{}$
          ○ $S_{3}\approx 0.833$
          $\rule{0pt}{}$
          ○ $S_{4}\approx 0.583$
          $\rule{0pt}{}$
          ○ $S_{5}\approx 0.783$
          $\rule{0pt}{}$
          ○ $S_{6}\approx 0.616$
     ◉ Even partial sums:
          ○ $S_{2}, S_{4}, S_{6}, \ldots$
          ○ $0.5, 0.583, 0.616, \ldots$
          ○ these are increasing.
     ◉ Odd partial sums:
          ○ $S_{1}, S_{3}, S_{5}, \ldots$
          ○ $1, 0.833, 0.783, \ldots$
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

● [19:00](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=1140). 🧩 Example 1 — Alternating Harmonic Series: $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n-1}}{𝒏}$
     ◉ Identify the positive part:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{1}{𝒏}$
          $\rule{0pt}{}$
     ◉ Important:
          ○ $(-1)^{n-1}$ only creates the alternating signs.
          ○ it is not part of $𝒂_{n}$.

● [21:00](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=1260). ❶ Check the limit condition.
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}𝒂_{n}$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{1}{𝒏}$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{1}{𝒏}=0$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ the limit condition is satisfied.

● [22:00](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=1320). ❷ Check the decreasing condition.
     ◉ We need:
          $\rule{0pt}{}$
          ○ $𝒂_{n+1}\le 𝒂_{n}$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{1}{𝒏}$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $𝒂_{n+1}=\dfrac{1}{𝒏+1}$
          $\rule{0pt}{}$
     ◉ Compare:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{𝒏+1}\le \dfrac{1}{𝒏}$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ $𝒂_{n}$ is decreasing.

● [24:13](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=1453). Conclusion for Example 1.
     ◉ The series is alternating.
     ◉ The positive terms satisfy:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}𝒂_{n}=0$
          $\rule{0pt}{}$
          ○ $𝒂_{n+1}\le 𝒂_{n}$
          $\rule{0pt}{}$
     ◉ Therefore, by the Alternating Series Test:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n-1}}{𝒏}$ converges.
          $\rule{0pt}{}$
     ◉ Important:
          ○ the harmonic series $\displaystyle \sum \dfrac{1}{𝒏}$ diverges.
          ○ the alternating harmonic series $\displaystyle \sum \dfrac{(-1)^{n-1}}{𝒏}$ converges.
          

Ｅｘａｍｐｌｅ  2

● [📷image](../img/Calculus 2 Lecture 9.5/[27-52]-01.png)

● [27:52](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=1672). 🧩 Example 2 — $\displaystyle \sum_{n=1}^{\infty}(-1)^{n}\cdot \dfrac{2𝒏}{4𝒏-1}$.
$\rule{0pt}{}$
     ◉ Identify the positive part:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{2𝒏}{4𝒏-1}$
          $\rule{0pt}{}$
     ◉ The series is alternating because of:
          $\rule{0pt}{}$
          ○ $(-1)^{n}$

● [28:50](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=1730). Checking decreasing behavior.
     ◉ To check decreasing, we need:
          $\rule{0pt}{}$
          ○ $𝒂_{n+1}\le 𝒂_{n}$
          $\rule{0pt}{}$
     ◉ Direct substitution can be messy:
          $\rule{0pt}{}$
          ○ $𝒂_{n+1}=\dfrac{2(𝒏+1)}{4(𝒏+1)-1}$
          $\rule{0pt}{}$
          ○ $𝒂_{n+1}=\dfrac{2𝒏+2}{4𝒏+3}$
          $\rule{0pt}{}$
     ◉ Comparing this directly with:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{2𝒏}{4𝒏-1}$
          $\rule{0pt}{}$
     ◉ can be more work.
     ◉ Easier method:
          ○ model the positive sequence with a function.
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\dfrac{2𝒙}{4𝒙-1}$

● [29:20](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=1760). Using the derivative to show decreasing.
     ◉ Differentiate:
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\dfrac{2𝒙}{4𝒙-1}$
          $\rule{0pt}{}$
     ◉ Using the quotient rule:
          $\rule{0pt}{}$
          ○ $𝒇'(𝒙)=\dfrac{2(4𝒙-1)-4(2𝒙)}{(4𝒙-1)^{2}}$
          $\rule{0pt}{}$
     ◉ Simplify:
          $\rule{0pt}{}$
          ○ $𝒇'(𝒙)=\dfrac{8𝒙-2-8𝒙}{(4𝒙-1)^{2}}$
          $\rule{0pt}{}$
          ○ $𝒇'(𝒙)=\dfrac{-2}{(4𝒙-1)^{2}}$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $(4𝒙-1)^{2}>0$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $𝒇'(𝒙)<0$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ $𝒇(𝒙)$ is decreasing.
          ○ so $𝒂_{n}$ is decreasing.

● [31:42](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=1902). Check the limit condition.
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{2𝒏}{4𝒏-1}$
          $\rule{0pt}{}$
     ◉ Since the numerator and denominator have the same degree:
          ○ compare leading coefficients.
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{2𝒏}{4𝒏-1}=\dfrac{2}{4}=\dfrac{1}{2}$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{2}\ne 0$
          $\rule{0pt}{}$
     ◉ The positive terms do not approach $0$.

● [32:18](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=1938). Conclusion for Example 2.
     ◉ Even though $𝒂_{n}$ is decreasing,
          ○ the limit condition fails.
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}𝒂_{n}\ne 0$
          $\rule{0pt}{}$
     ◉ The series fails the necessary condition for convergence.
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}(-1)^{n}\cdot \dfrac{2𝒏}{4𝒏-1}$ diverges.
          $\rule{0pt}{}$
     ◉ Important:
          ○ for the Alternating Series Test, both conditions are needed:
               ■ $𝒂_{n}$ must be decreasing.
               ■ $\displaystyle \lim_{n\to\infty}𝒂_{n}$ must equal $0$.
          ○ here, the decreasing condition works,
               ■ but the limit condition fails.
          

Ｅｘａｍｐｌｅ  3

●  [📷image-1](../img/Calculus 2 Lecture 9.5/[33-31]-01.png)  [📷image-2](../img/Calculus 2 Lecture 9.5/[33-31]-02.png)

● [33:31](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=2011). 🧩 Example 3 —  $\displaystyle \sum_{n=2}^{\infty}(-1)^{n-1}\cdot \dfrac{\sqrt{𝒏+1}}{𝒏-1}$.
     ◉ Given series: 
          $\rule{0pt}{}$
          ○ $\displaystyle \sum (-1)^{n-1}\cdot \dfrac{\sqrt{𝒏+1}}{𝒏-1}$
          $\rule{0pt}{}$
     ◉ Identify the positive part:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{\sqrt{𝒏+1}}{𝒏-1}$
          $\rule{0pt}{}$
     ◉ The series is alternating because of:
          $\rule{0pt}{}$
          ○ $(-1)^{n-1}$


● [36:23](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=2183). Check the limit condition using L'Hôpital's Rule.
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{\sqrt{𝒏+1}}{𝒏-1}$
          $\rule{0pt}{}$
     ◉ This has the form:
          $\rule{0pt}{}$
          ○ $\infty/\infty$
     ◉ Apply L'Hôpital's Rule:
          ○ derivative of $\sqrt{𝒏+1}=\dfrac{1}{2\sqrt{𝒏+1}}$
          $\rule{0pt}{}$
          ○ derivative of $𝒏-1=1$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{\sqrt{𝒏+1}}{𝒏-1}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{n\to\infty}\dfrac{1}{2\sqrt{𝒏+1}}$
          $\rule{0pt}{}$
          ○ $=0$
     ◉ So:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}𝒂_{n}=0$


● [38:45](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=2325). Check the decreasing condition using the derivative.
     ◉ Define:
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\dfrac{\sqrt{𝒙+1}}{𝒙-1}$
          $\rule{0pt}{}$
     ◉ We use a function because:
          ○ $𝒇(𝒙)$ models the positive sequence $𝒂_{n}$.
     ◉ If:
          $\rule{0pt}{}$
          ○ $𝒇'(𝒙)<0$
     ◉ Then:
          ○ $𝒇(𝒙)$ is decreasing,
          ○ so the sequence $𝒂_{n}$ is decreasing.

● [42:32](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=2552). Showing the derivative is negative.
     ◉ Differentiate:
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\dfrac{\sqrt{𝒙+1}}{𝒙-1}$
          $\rule{0pt}{}$
     ◉ Important domain detail:
          ○ $𝒇(𝒙)$ is not defined at $𝒙=1$,
               ■ because the denominator $𝒙-1$ becomes $0$.
          ○ since the series starts at $𝒏=2$,
               ■ we only need to show decreasing behavior for $𝒙\ge 2$.
     ◉ Using the quotient rule:
          $\rule{0pt}{}$
          ○ $𝒇'(𝒙)=\dfrac{\left(\dfrac{𝒙-1}{2\sqrt{𝒙+1}}\right)-\sqrt{𝒙+1}}{(𝒙-1)^{2}}$
          $\rule{0pt}{}$
     ◉ Combine the numerator:
          $\rule{0pt}{}$
          ○ $𝒇'(𝒙)=\dfrac{𝒙-1-2(𝒙+1)}{2\sqrt{𝒙+1}(𝒙-1)^{2}}$
          $\rule{0pt}{}$
     ◉ Simplify:
          $\rule{0pt}{}$
          ○ $𝒇'(𝒙)=\dfrac{-𝒙-3}{2\sqrt{𝒙+1}(𝒙-1)^{2}}$
          $\rule{0pt}{}$
     ◉ Sign analysis:
          ○ the denominator is positive for $𝒙>1$.
          ○ the numerator $-𝒙-3$ is negative for $𝒙>1$.
          ○ therefore, $𝒇'(𝒙)<0$ for $𝒙>1$.
     ◉ In particular:
          $\rule{0pt}{}$
          ○ $𝒇'(𝒙)<0$ for $𝒙\ge 2$.
     ◉ Therefore:
          ○ $𝒇(𝒙)$ is decreasing on $[2,\infty)$.
          ○ so $𝒂_{n}$ is decreasing for $𝒏\ge 2$.

● [44:18](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=2658). Conclusion for Example 3.
     ◉ The series is alternating.
     ◉ The positive terms satisfy:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}𝒂_{n}=0$
          $\rule{0pt}{}$
          ○ $𝒂_{n}$ is decreasing.
     ◉ Therefore, by the Alternating Series Test:
          ○ the series converges.
     ◉ Note:
          ○ even if the first few terms are problematic,
               ■ adding or removing finitely many terms does not change convergence.




               

Ａｌｔｅｒｎａｔｉｎｇ　Ｓｅｒｉｅｓ　Ｅｒｒｏｒ　Ｅｓｔｉｍａｔｅ

● [📷image-1](../img/Calculus 2 Lecture 9.5/[45-28]-01.png)  [📷image-2](../img/Calculus 2 Lecture 9.5/[45-28]-02.png)

● [45:28](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=2728). Finding error in alternating series.
     ◉ If a series $\displaystyle \sum 𝒂_{n}$ converges, 
          ○ then it has some sum $𝑺$.
     ◉ The sequence of partial sums satisfies:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}𝑺_{n}=𝑺$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}(𝑺-𝑺_{n})=0$
          $\rule{0pt}{}$
     ◉ Meaning:
          ○ if $𝒏$ actually goes to infinity,
               ■ the partial sums approach the exact sum.
          ○ but if we stop at a finite $𝒏$,
               ■ there will be some error between $𝑺$ and $𝑺_{n}$.

● [50:00](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=3000). Defining the error.
     ◉ The error is called:
          $\rule{0pt}{}$
          ○ $𝑹_{n}$
     ◉ Definition:
          $\rule{0pt}{}$
          ○ $𝑹_{n}=𝑺-𝑺_{n}$
     ◉ Meaning:
          ○ error = whole sum - partial sum
     ◉ In words:
          ○ $𝑺$ is the exact infinite sum.
          ○ $𝑺_{n}$ is the partial sum after $𝒏$ terms.
          ○ $𝑹_{n}$ is the difference between them.

● [53:36](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=3216). Alternating Series Estimation Theorem.
     ◉ For alternating series only:
          $\rule{0pt}{}$
          ○ $|𝑹_{n}|=|𝑺-𝑺_{n}|\le 𝒂_{n+1}$
          $\rule{0pt}{}$
     ◉ Meaning:
          ○ the absolute error is less than or equal to the first omitted term.
     ◉ If we stop at $𝑺_{n}$,
          ○ the next positive term is $𝒂_{n+1}$.
     ◉ Therefore:
          ○ the error is no larger than $𝒂_{n+1}$.

● [55:04](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=3304). Why the first omitted term controls the error.
     ◉ Suppose the exact sum is:
          $\rule{0pt}{}$
          ○ $𝑺=𝒂_{1}-𝒂_{2}+𝒂_{3}-\cdots-𝒂_{n}+𝒂_{n+1}-𝒂_{n+2}+\cdots$
          $\rule{0pt}{}$
     ◉ The partial sum is:
          $\rule{0pt}{}$
          ○ $𝑺_{n}=𝒂_{1}-𝒂_{2}+𝒂_{3}-\cdots-𝒂_{n}$
          $\rule{0pt}{}$
     ◉ Therefore, the remaining tail is:
          $\rule{0pt}{}$
          ○ $𝑺-𝑺_{n}=𝒂_{n+1}-𝒂_{n+2}+𝒂_{n+3}-\cdots$
          $\rule{0pt}{}$
     ◉ Since the positive terms are decreasing:
          $\rule{0pt}{}$
          ○ $𝒂_{n+2}\le 𝒂_{n+1}$
          $\rule{0pt}{}$
          ○ $𝒂_{n+3}\le 𝒂_{n+2}$
          ○ and so on.
     ◉ Therefore:
          ○ The remaining terms alternate signs and partially cancel each other, 
          ○ and since their sizes decrease, the total remaining error cannot exceed the first omitted term.
     ◉ So:
          $\rule{0pt}{}$
          ○ $|𝑺-𝑺_{n}|\le 𝒂_{n+1}$
          $\rule{0pt}{}$
          ○ $|𝑹_{n}|\le 𝒂_{n+1}$

● N̲O̲T̲E̲ — Key idea.
     ◉ In an alternating series,
          ○ the terms after $𝑺_{n}$ keep alternating signs.
     ◉ Because the positive terms decrease,
          ○ each new term partially cancels the previous one.
     ◉ Therefore:
          ○ the total error after stopping at $𝑺_{n}$
               ■ is controlled by the first term you did not include.




          

Ｐｒａｃｔｉｃａｌ　Ｅｒｒｏｒ　Ｅｘａｍｐｌｅ

● [📷image-1](../img/Calculus 2 Lecture 9.5/[1-01-24]-01.png)  [📷image-2](../img/Calculus 2 Lecture 9.5/[1-01-24]-02.png)

● [1:01:24](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=3684). 🧩 Example 4 — Practical problem of precision and error: $\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}}{𝒏!}$
     ◉ Goal:
          ○ approximate the sum of the series using a partial sum.
     ◉ Desired accuracy:
          ○ make the error less than $0.0005$.
     ◉ Key idea:
          ○ we first prove that the series converges.
          ○ then we use the error bound to decide how many terms are needed.

● [1:02:42](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=3762). Check convergence first.
     ◉ The series is alternating because of:
          $\rule{0pt}{}$
          ○ $(-1)^{n}$
          $\rule{0pt}{}$
     ◉ Identify the positive part:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{1}{𝒏!}$
          $\rule{0pt}{}$
     ◉ Check the limit:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{1}{𝒏!}=0$
          $\rule{0pt}{}$
     ◉ Check decreasing:
          $\rule{0pt}{}$
          ○ $𝒂_{n+1}=\dfrac{1}{(𝒏+1)!}$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{(𝒏+1)!}\le \dfrac{1}{𝒏!}$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ $𝒂_{n}$ is decreasing.
     ◉ By the Alternating Series Test:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}}{𝒏!}$ converges.


● [1:06:00](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=3960). How error works.
     ◉ For a convergent alternating series:
          $\rule{0pt}{}$
          ○ $|𝑹_{n}|=|𝑺-𝑺_{n}|\le 𝒂_{n+1}$
          $\rule{0pt}{}$
     ◉ In this example:
          $\rule{0pt}{}$
          ○ $𝒂_{n+1}=\dfrac{1}{(𝒏+1)!}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $|𝑹_{n}|\le \dfrac{1}{(𝒏+1)!}$
          $\rule{0pt}{}$
     ◉ Meaning:
          ○ the error after stopping at $𝑺_{n}$
               ■ is no bigger than the first omitted term.
     ◉ Practical interpretation:
          ○ you tell the series how accurate you want to be.
          ○ then use $𝑹_{n}$ to determine how many terms are needed to be that accurate.

● [1:09:50](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=4190). Finding how many terms are needed.
     ◉ We want:
          $\rule{0pt}{}$
          ○ $|𝑹_{n}|<0.0005$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $|𝑹_{n}|\le \dfrac{1}{(𝒏+1)!}$
          $\rule{0pt}{}$
     ◉ It is enough to require:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{(𝒏+1)!}<0.0005$
          $\rule{0pt}{}$
     ◉ This guarantees:
          $\rule{0pt}{}$
          ○ $|𝑹_{n}|<0.0005$


● [1:13:01](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=4381). Solving the inequality.
     ◉ Start with:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{(𝒏+1)!}<0.0005$
          $\rule{0pt}{}$
     ◉ Take reciprocals:
          $\rule{0pt}{}$
          ○ $(𝒏+1)!>\dfrac{1}{0.0005}$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{0.0005}=2000$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $(𝒏+1)!>2000$


● [1:15:11](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=4511). Determining $𝒏$.
     ◉ Check factorials:
          $\rule{0pt}{}$
          ○ $6!=720$
          $\rule{0pt}{}$
          ○ $7!=5040$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $6!<2000$
          $\rule{0pt}{}$
          ○ $7!>2000$
          $\rule{0pt}{}$
     ◉ We need:
          $\rule{0pt}{}$
          ○ $𝒏+1=7$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $𝒏=6$
          $\rule{0pt}{}$
     ◉ Meaning:
          ○ stopping at $𝑺_{6}$ guarantees an error less than $0.0005$.

● [1:15:56](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=4556). Computing the partial sum $𝑺_{6}$.
     ◉ Since the series starts at $𝒏=0$,
          ○ $𝑺_{6}$ includes the terms from $𝒏=0$ through $𝒏=6$.
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $𝑺_{6}=1-\dfrac{1}{1!}+\dfrac{1}{2!}-\dfrac{1}{3!}+\dfrac{1}{4!}-\dfrac{1}{5!}+\dfrac{1}{6!}$
          $\rule{0pt}{}$
     ◉ Rewrite:
          $\rule{0pt}{}$
          ○ $𝑺_{6}=1-1+\dfrac{1}{2}-\dfrac{1}{6}+\dfrac{1}{24}-\dfrac{1}{120}+\dfrac{1}{720}$
          

● [1:18:20](https://www.youtube.com/watch?v=BhYPrQHDrjk&t=4700). Final approximation.
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $𝑺_{6}=0.368$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $𝑺\approx 0.368$
          $\rule{0pt}{}$
     ◉ Important:
          ○ $𝑺_{6}$ is not exactly equal to $𝑺$.
          ○ $𝑺_{6}$ is only a partial sum approximation.
     ◉ But:
          ○ it is a very good approximation.
     ◉ How good?
          ○ the error is less than $0.0005$.
          ○ this means $𝑺_{6}$ is within $0.0005$ of the true sum $𝑺$.
     ◉ In Leonard's words:
          ○ it is not equal to $𝑺$,
               ■ but it is within $5$ ten-thousandths of $𝑺$.
          ○ that is how the error estimate is used.

● N̲O̲T̲E̲:
     ◉ Smaller allowed error ⇒ you need to go further in the series ⇒ you use a partial sum with more terms ⇒ you are closer to the true sum.







Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Alternating Series
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/5-5-alternating-series)