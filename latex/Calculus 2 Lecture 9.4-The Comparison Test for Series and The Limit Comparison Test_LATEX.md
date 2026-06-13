-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ９．４： Ｔｈｅ Ｃｏｍｐａｒｉｓｏｎ Ｔｅｓｔ ｆｏｒ Ｓｅｒｉｅｓ ａｎｄ Ｔｈｅ Ｌｉｍｉｔ Ｃｏｍｐａｒｉｓｏｎ Ｔｅｓｔ**-------------------------------—






Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [📷image](../img/Calculus 2 Lecture 9.4/[0-01]-01.png)

● [0:01](https://www.youtube.com/watch?v=ei8WKMAHky0&t=1). Introduction to Comparison Tests.
     ◉ We will study two comparison tests:
          ○ the Direct Comparison Test.
          ○ the Limit Comparison Test.
     ◉ Main idea:
          ○ compare an unknown series with a known series.
     ◉ Usually, the known series will be:
          ○ a geometric series.
          ○ a 𝒑-series.
          ○ the harmonic series.

● [1:14](https://www.youtube.com/watch?v=ei8WKMAHky0&t=74). Fundamental idea.
     ◉ Compare one series to another series whose convergence or divergence is already known.
     ◉ The goal is to use the known series to decide the behavior of the unknown series.
     ◉ Typical known series:
          ○ geometric series.
          ○ 𝒑-series.
          ○ harmonic series.

● [2:13](https://www.youtube.com/watch?v=ei8WKMAHky0&t=133). Requirement for comparison tests.
     ◉ Suppose we have two series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum 𝒂_{n}$
          $\rule{0pt}{}$
          ○ $\displaystyle \sum 𝒃_{n}$
          $\rule{0pt}{}$
     ◉ **🟩Both series must have positive terms:🟩**
          $\rule{0pt}{}$
          ○ $𝒂_{n}\ge 0$
          $\rule{0pt}{}$
          ○ $𝒃_{n}\ge 0$
          $\rule{0pt}{}$
     ◉ This is essential because the comparison is based on term-by-term size.




     

Ｄｉｒｅｃｔ　Ｃｏｍｐａｒｉｓｏｎ　Ｔｅｓｔ

● [3:06](https://www.youtube.com/watch?v=ei8WKMAHky0&t=186). The Direct Comparison Test.
     ◉ The idea is to compare the terms directly:
          $\rule{0pt}{}$
          ○ $𝒂_{n}\le 𝒃_{n}$
          $\rule{0pt}{}$
     ◉ Meaning:
          ○ every term of $𝒂_{n}$ is less than or equal to the corresponding term of $𝒃_{n}$.
     ◉ There are two useful scenarios:
          ○ proving convergence.
          ○ proving divergence.

● [3:21](https://www.youtube.com/watch?v=ei8WKMAHky0&t=201). Scenario 1 — Proving convergence. [📷image](../img/Calculus 2 Lecture 9.4/[3-21]-01.png)
     ◉ Suppose:
          $\rule{0pt}{}$
          ○ $0\le 𝒂_{n}\le 𝒃_{n}$
          $\rule{0pt}{}$
     ◉  i̲f̲  $\displaystyle \sum 𝒃_{n}$ converges,
     $\rule{0pt}{}$
          ○ t̲h̲e̲n̲ $\displaystyle \sum 𝒂_{n}$ also converges.
          $\rule{0pt}{}$
     ◉ Reason:
          ○ $𝒂_{n}$ is smaller than $𝒃_{n}$ term by term.
          ○  i̲f̲  the larger positive series has a finite sum,
               ■ t̲h̲e̲n̲ the smaller positive series must also have a finite sum.
               
● [4:17](https://www.youtube.com/watch?v=ei8WKMAHky0&t=257). Scenario 1 — Main convergence principle.
     ◉  i̲f̲  the bigger series converges,
          ○ t̲h̲e̲n̲ the smaller series also converges.
     ◉ Symbolically:
          $\rule{0pt}{}$
          ○ $0\le 𝒂_{n}\le 𝒃_{n}$
          $\rule{0pt}{}$
          ○ $\displaystyle \sum 𝒃_{n}$ converges
          $\rule{0pt}{}$
          ○ therefore, $\displaystyle \sum 𝒂_{n}$ converges.

● [5:58](https://www.youtube.com/watch?v=ei8WKMAHky0&t=358). Scenario 1 — Inconclusive convergence case.
     ◉  i̲f̲  $0\le 𝒂_{n}\le 𝒃_{n}$ a̲n̲d̲  $\displaystyle \sum 𝒃_{n}$ diverges,
          ○ t̲h̲e̲n̲ we cannot conclude anything about $\displaystyle \sum 𝒂_{n}$.
     ◉ Reason:
          ○ being smaller than a divergent series does not force convergence or divergence.
          ○ the smaller series could converge or diverge.

● [7:49](https://www.youtube.com/watch?v=ei8WKMAHky0&t=469). Scenario 2 — Proving divergence. [📷image](../img/Calculus 2 Lecture 9.4/[7-49]-01.png)
     ◉ Suppose:
          $\rule{0pt}{}$
          ○ $0\le 𝒃_{n}\le 𝒂_{n}$
          $\rule{0pt}{}$
     ◉  i̲f̲ $\displaystyle \sum 𝒃_{n}$ diverges,
     $\rule{0pt}{}$
          ○ t̲h̲e̲n̲ $\displaystyle \sum 𝒂_{n}$ also diverges.
          $\rule{0pt}{}$
     ◉ Reason:
          ○ $𝒂_{n}$ is larger than $𝒃_{n}$ term by term.
          ○ if the smaller positive series already diverges,
               ■ then the larger positive series must also diverge.

● [8:55](https://www.youtube.com/watch?v=ei8WKMAHky0&t=535). Scenario 2 — Main divergence principle.
     ◉  i̲f̲ the smaller series diverges,
          ○ t̲h̲e̲n̲ the bigger series also diverges.
     ◉ Symbolically:
          $\rule{0pt}{}$
          ○ $0\le 𝒃_{n}\le 𝒂_{n}$
          $\rule{0pt}{}$
          ○ $\displaystyle \sum 𝒃_{n}$ diverges
          $\rule{0pt}{}$
          ○ therefore, $\displaystyle \sum 𝒂_{n}$ diverges.

● [9:33](https://www.youtube.com/watch?v=ei8WKMAHky0&t=573). Scenario 2 — Inconclusive divergence case.
     ◉ i̲f̲  $0\le 𝒃_{n}\le 𝒂_{n}$  a̲n̲d̲  $\displaystyle \sum 𝒃_{n}$ converges,
          ○ t̲h̲e̲n̲ we cannot conclude anything about $\displaystyle \sum 𝒂_{n}$.
     ◉ Reason:
          ○ being bigger than a convergent series does not force convergence or divergence.
          ○ the bigger series could converge or diverge.

● N̲O̲T̲E̲ — Direct Comparison Test summary.
     ◉ To prove convergence:
          ○ compare the given series to a bigger convergent series.
          ○ smaller than convergent ⇒ convergent.
     ◉ To prove divergence:
          ○ compare the given series to a smaller divergent series.
          ○ bigger than divergent ⇒ divergent.
     ◉ Inconclusive cases:
          ○ smaller than divergent ⇒ inconclusive.
          ○ bigger than convergent ⇒ inconclusive.




          

Ｍｅｔｈｏｄｏｌｏｇｙ　ａｎｄ　Ｔｅｓｔ　Ｐｒｏｇｒｅｓｓｉｏｎ

● [10:32](https://www.youtube.com/watch?v=ei8WKMAHky0&t=632). Methodology and progression of tests.
     ◉ First step:
          ○ always check the Divergence Test.
     ◉ Then check whether the series is:
          ○ geometric.
          ○ a 𝒑-series.
          ○ suitable for the Integral Test.
          ○ suitable for the Direct Comparison Test.
          ○ suitable for the Limit Comparison Test.

● [10:44](https://www.youtube.com/watch?v=ei8WKMAHky0&t=644). First essential step — Divergence Test.
     ◉ Always begin by checking:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}𝒂_{n}$
          $\rule{0pt}{}$
     ◉  i̲f̲  $\displaystyle \lim_{n\to\infty}𝒂_{n}\ne 0$
     $\rule{0pt}{}$
          ○ t̲h̲e̲n̲ $\displaystyle \sum 𝒂_{n}$ diverges immediately.
          $\rule{0pt}{}$
     ◉  i̲f̲  $\displaystyle \lim_{n\to\infty}𝒂_{n}=0$
          ○ t̲h̲e̲n̲ the test is inconclusive. Continue with another test.

● [11:22](https://www.youtube.com/watch?v=ei8WKMAHky0&t=682). Choosing between tests.
     ◉ After the Divergence Test:
          ○ check whether the series is geometric.
          ○ check whether the series is a 𝒑-series.
          ○ check whether the Integral Test is practical.
          ○ check whether a comparison test is easier.
     ◉ Main idea:
          ○ do not make the problem harder than necessary.




          

Ｄｉｒｅｃｔ　Ｃｏｍｐａｒｉｓｏｎ　Ｅｘａｍｐｌｅｓ

● [10:32](https://www.youtube.com/watch?v=ei8WKMAHky0&t=632). 🧩 Example 1 — Analyzing $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{𝒏^{2}+2}$. [📷image](../img/Calculus 2 Lecture 9.4/[10-32]-01.png)
     ◉ First check the Divergence Test:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{1}{𝒏^{2}+2}=0$
          $\rule{0pt}{}$
     ◉ Since the limit is $0$:
          ○ the Divergence Test is inconclusive.
          ○ we continue.
     ◉ [11:22](https://www.youtube.com/watch?v=ei8WKMAHky0&t=682). Check whether the Integral Test is practical.
          ○ The Integral Test could be used here,
               ■ but there is an easier way.
          ○ Since the series looks very close to a 𝒑-series,
               ■ Direct Comparison is more convenient.
     ◉ [12:05](https://www.youtube.com/watch?v=ei8WKMAHky0&t=725). Choosing a comparison series for Example 1.
          ○ The expression looks similar to:
               $\rule{0pt}{}$
               ■ $\dfrac{1}{𝒏^{2}}$
               $\rule{0pt}{}$
          ○ Since:
               $\rule{0pt}{}$
               ■ $𝒏^{2}+2>𝒏^{2}$
               $\rule{0pt}{}$
          ○ Then:
               $\rule{0pt}{}$
               ■ $\dfrac{1}{𝒏^{2}+2}<\dfrac{1}{𝒏^{2}}$ for all $n\ge 1$
               $\rule{0pt}{}$
          ○ Therefore:
               ■ $0\le \dfrac{1}{𝒏^{2}+2}\le \dfrac{1}{𝒏^{2}}$ and **🟩 both series have positive terms.🟩**
               $\rule{0pt}{}$
     ◉ Known behavior of the comparison series.
          ○ The comparison series is:
               $\rule{0pt}{}$
               ■ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{𝒏^{2}}$
               $\rule{0pt}{}$
          ○ This is a 𝒑-series with:
               $\rule{0pt}{}$
               ■ $𝒑=2$
               $\rule{0pt}{}$
          ○ Since:
               $\rule{0pt}{}$
               ■ $2>1$
               $\rule{0pt}{}$
          ○ Therefore:
          $\rule{0pt}{}$
               ■ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{𝒏^{2}}$ converges.
               $\rule{0pt}{}$
     ◉ Conclusion for Example 1.
          ○ Since:
               $\rule{0pt}{}$
               ■ $0\le \dfrac{1}{𝒏^{2}+2}\le \dfrac{1}{𝒏^{2}}$
               $\rule{0pt}{}$
          ○ And:
               $\rule{0pt}{}$
               ■ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{𝒏^{2}}$ converges,
               $\rule{0pt}{}$
          ○ By the Direct Comparison Test:
          $\rule{0pt}{}$
               ■ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{𝒏^{2}+2}$ converges.


● [16:55](https://www.youtube.com/watch?v=ei8WKMAHky0&t=1015). 🧩 Example 2 — Analyzing $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{2^{n}+3}$. [📷image](../img/Calculus 2 Lecture 9.4/[16-55]-01.png)
     ◉ First check the Divergence Test:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{1}{2^{n}+3}=0$
          $\rule{0pt}{}$
     ◉ Since the limit is $0$:
          ○ the Divergence Test is inconclusive.
          ○ we continue.
     ◉ [17:35](https://www.youtube.com/watch?v=ei8WKMAHky0&t=1055). Choosing a comparison series.
          ○ The $+3$ in the denominator makes the fraction smaller.
          ○ Since:
               $\rule{0pt}{}$
               ■ $2^{n}+3>2^{n}$
          ○ Then:
               $\rule{0pt}{}$
               ■ $\dfrac{1}{2^{n}+3}<\dfrac{1}{2^{n}}$
               $\rule{0pt}{}$
          ○ Therefore:
          $\rule{0pt}{}$
               ■ $0\le \dfrac{1}{2^{n}+3}\le \dfrac{1}{2^{n}}$ and **🟩both series have positive terms.🟩**
               $\rule{0pt}{}$
     ◉ [20:44](https://www.youtube.com/watch?v=ei8WKMAHky0&t=1244). Comparison with a geometric series.
          ○ Rewrite:
               $\rule{0pt}{}$
               ■ $\dfrac{1}{2^{n}}=\left(\dfrac{1}{2}\right)^{n}$
               $\rule{0pt}{}$
          ○ Therefore:
               $\rule{0pt}{}$
               ■ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{2^{n}}=\sum_{n=1}^{\infty}\left(\dfrac{1}{2}\right)^{n}$
               $\rule{0pt}{}$
          ○ This is a geometric series with:
               $\rule{0pt}{}$
               ■ $𝒓=\dfrac{1}{2}$
               $\rule{0pt}{}$
          ○ Since:
               $\rule{0pt}{}$
               ■ $|𝒓|=\dfrac{1}{2}<1$
               $\rule{0pt}{}$
          ○ The geometric series converges.
     ◉ [23:41](https://www.youtube.com/watch?v=ei8WKMAHky0&t=1421). Conclusion for Example 2.
          ○ Since:
               $\rule{0pt}{}$
               ■ $0\le \dfrac{1}{2^{n}+3}\le \dfrac{1}{2^{n}}$
               $\rule{0pt}{}$
          ○ And:
               $\rule{0pt}{}$
               ■ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{2^{n}}$ converges,
               $\rule{0pt}{}$
          ○ By the Direct Comparison Test:
          $\rule{0pt}{}$
               ■ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{2^{n}+3}$ converges.
               $\rule{0pt}{}$
          ○ Important:
               ■ we do not need the exact sum of the geometric series.
               ■ we only need to know that it converges.

● [25:54](https://www.youtube.com/watch?v=ei8WKMAHky0&t=1554). 🧩 Example 3 — Analyzing $\displaystyle \sum_{n=3}^{\infty}\dfrac{3^{n}}{2^{n}-4}$. [📷image-1](../img/Calculus 2 Lecture 9.4/[25-54]-01.png) [📷image-2](../img/Calculus 2 Lecture 9.4/[25-54]-02.png)
     ◉ Given series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=3}^{\infty}\dfrac{3^{n}}{2^{n}-4}$
          $\rule{0pt}{}$
     ◉ First check positivity:
          ○ the series starts at $𝒏=3$.
          ○ for $𝒏\ge 3$, $2^{n}-4>0$.
          ○ therefore, the terms are positive.
     ◉ Important:
          ○ the starting index matters here.
          ○ if $𝒏=2$, the denominator would be $0$.
     ◉ [28:21](https://www.youtube.com/watch?v=ei8WKMAHky0&t=1701). Comparison with a geometric series.
          ○ Compare:
               $\rule{0pt}{}$
               ■ $\dfrac{3^{n}}{2^{n}-4}$ and $\dfrac{3^{n}}{2^{n}}$
               $\rule{0pt}{}$
          ○ Since:
               $\rule{0pt}{}$
               ■ $2^{n}-4<2^{n}$
               $\rule{0pt}{}$
          ○ Then:
               $\rule{0pt}{}$
               ■ $\dfrac{3^{n}}{2^{n}-4}>\dfrac{3^{n}}{2^{n}}$
               $\rule{0pt}{}$
          ○ Rewrite:
               $\rule{0pt}{}$
               ■ $\dfrac{3^{n}}{2^{n}}=\left(\dfrac{3}{2}\right)^{n}$
               $\rule{0pt}{}$
          ○ Therefore:
               $\rule{0pt}{}$
               ■ $\dfrac{3^{n}}{2^{n}-4}>\left(\dfrac{3}{2}\right)^{n}$
               $\rule{0pt}{}$
     ◉ [29:25](https://www.youtube.com/watch?v=ei8WKMAHky0&t=1765). Known behavior of the comparison series.
          ○ The comparison series is:
               $\rule{0pt}{}$
               ■ $\displaystyle \sum_{n=3}^{\infty}\left(\dfrac{3}{2}\right)^{n}$
               $\rule{0pt}{}$
          ○ This is a geometric series with:
               $\rule{0pt}{}$
               ■ $𝒓=\dfrac{3}{2}$
               $\rule{0pt}{}$
          ○ Since:
               $\rule{0pt}{}$
               ■ $|𝒓|=\dfrac{3}{2}>1$
               $\rule{0pt}{}$
          ○ Therefore:
          $\rule{0pt}{}$
               ■ $\displaystyle \sum_{n=3}^{\infty}\left(\dfrac{3}{2}\right)^{n}$ diverges.
               $\rule{0pt}{}$
● Finite terms do not affect convergence.
          ○ Convergence or divergence is not changed by:
               ■ adding finitely many terms.
               ■ subtracting finitely many terms.
               ■ changing the starting index by a finite amount.
          ○ The sum may change,
               ■ but the convergence behavior does not change.
          ○ Therefore:
               ■ starting at $𝒏=3$ does not affect whether the geometric series converges or diverges.
     ◉ Conclusion.
          ○ Since:
               $\rule{0pt}{}$
               ■ $\dfrac{3^{n}}{2^{n}-4}>\left(\dfrac{3}{2}\right)^{n}$
               $\rule{0pt}{}$
          ○ And:
               $\rule{0pt}{}$
               ■ $\displaystyle \sum_{n=3}^{\infty}\left(\dfrac{3}{2}\right)^{n}$ diverges,
               $\rule{0pt}{}$
          ○ By the Direct Comparison Test:
          $\rule{0pt}{}$
               ■ $\displaystyle \sum_{n=3}^{\infty}\dfrac{3^{n}}{2^{n}-4}$ diverges.
               $\rule{0pt}{}$
     ◉ [35:30](https://www.youtube.com/watch?v=ei8WKMAHky0&t=2130).  Alternative check using the Divergence Test.
          ○ The given term is:
               $\rule{0pt}{}$
               ■ $𝒂_{n}=\dfrac{3^{n}}{2^{n}-4}$
               $\rule{0pt}{}$
          ○ The limit does not go to $0$.
          ○ In fact:
               ■ the dominant behavior is like $\left(\dfrac{3}{2}\right)^{n}$
               ■ and $\left(\dfrac{3}{2}\right)^{n}\to\infty$
               $\rule{0pt}{}$
          ○ Therefore:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{n\to\infty}\dfrac{3^{n}}{2^{n}-4}\ne 0$
               $\rule{0pt}{}$
          ○ So the series also diverges by the Divergence Test.
          ○ Important:
               ■ this should usually be checked first.

● [37:08](https://www.youtube.com/watch?v=ei8WKMAHky0&t=2228). 🧩 Example 4 — The failure of Direct Comparison: $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{\sqrt{𝒏}+1}$. [📷image](../img/Calculus 2 Lecture 9.4/[37-08]-01.png)
     ◉ Given series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{\sqrt{𝒏}+1}$
          $\rule{0pt}{}$
     ◉ First check positivity:
          ○ all terms are positive.
     ◉ Compare with:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{\sqrt{𝒏}}$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\sqrt{𝒏}+1>\sqrt{𝒏}$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{\sqrt{𝒏}+1}<\dfrac{1}{\sqrt{𝒏}}$
          $\rule{0pt}{}$
     ◉ [38:47](https://www.youtube.com/watch?v=ei8WKMAHky0&t=2327). Why Direct Comparison does not conclude divergence here.
          ○ The comparison series is:
               $\rule{0pt}{}$
               ■ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{\sqrt{𝒏}}$
               $\rule{0pt}{}$
          ○ Rewrite:
               $\rule{0pt}{}$
               ■ $\dfrac{1}{\sqrt{𝒏}}=\dfrac{1}{𝒏^{1/2}}$
               $\rule{0pt}{}$
          ○ This is a 𝒑-series with:
               $\rule{0pt}{}$
               ■ $𝒑=\dfrac{1}{2}$
               $\rule{0pt}{}$
          ○ Since:
               $\rule{0pt}{}$
               ■ $\dfrac{1}{2}\le 1$
               $\rule{0pt}{}$
          ○ Therefore:
          $\rule{0pt}{}$
               ■ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{\sqrt{𝒏}}$ diverges.
               $\rule{0pt}{}$
          ○ But we only know:
               $\rule{0pt}{}$
               ■ $\dfrac{1}{\sqrt{𝒏}+1}<\dfrac{1}{\sqrt{𝒏}}$
               $\rule{0pt}{}$
          ○ This means:
               ■ the given series is smaller than a divergent series.
          ○ This is inconclusive:
               ■ smaller than divergent ⇒ inconclusive.




          

Ｌｉｍｉｔ　Ｃｏｍｐａｒｉｓｏｎ　Ｔｅｓｔ ( LCT)

● [📷image-1](../img/Calculus 2 Lecture 9.4/[41-02]-01.png) [📷image-2](../img/Calculus 2 Lecture 9.4/[41-02]-02.png)

● [41:02](https://www.youtube.com/watch?v=ei8WKMAHky0&t=2462). The Limit Comparison Test.
     ◉ i̲f̲ Direct Comparison is inconclusive,
          ○ t̲h̲e̲n̲ try the Limit Comparison Test.
     ◉ Inconclusive cases:
          ○ smaller than divergent ⇒ inconclusive.
          ○ bigger than convergent ⇒ inconclusive.
     ◉ Main idea:
          ○ we compare our given series to a series whose convergence or divergence we already know,
          ○ and then we take a limit.
     ◉ This test is especially useful when two series have similar end behavior.

● Definition of the Limit Comparison Test.
     ◉ Suppose:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum 𝒂_{n}$ and $\displaystyle \sum 𝒃_{n}$ have positive terms.
          $\rule{0pt}{}$
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{𝒂_{n}}{𝒃_{n}}$
          $\rule{0pt}{}$
     ◉ i̲f̲ the limit exists a̲n̲d̲ is a finite positive number: $0<\mathcal{L}<\infty$
     $\rule{0pt}{}$
          ○ t̲h̲e̲n̲  $\displaystyle \sum 𝒂_{n}$ a̲n̲d̲ $\displaystyle \sum 𝒃_{n}$ have the same convergence behavior.
          $\rule{0pt}{}$
     ◉ Meaning:
          ○ they either both converge,
          ○ or they both diverge.

● [43:40](https://www.youtube.com/watch?v=ei8WKMAHky0&t=2620). Meaning of the limit in the LCT.
     ◉ The ratio:
          $\rule{0pt}{}$
          ○ $\dfrac{𝒂_{n}}{𝒃_{n}}$
          $\rule{0pt}{}$
     ◉ measures how close the two series are term by term.
     ◉ If the ratio approaches a finite positive number,
          ○ the terms behave similarly as $𝒏\to\infty$.
     ◉ Therefore:
          ○ one series predicts the behavior of the other.

● [43:40](https://www.youtube.com/watch?v=ei8WKMAHky0&t=2620). Formal proof idea.
$\rule{0pt}{}$
     ◉ i̲f̲  $\displaystyle \lim_{n\to\infty}\dfrac{𝒂_{n}}{𝒃_{n}}=\mathcal{L}$
     $\rule{0pt}{}$
          ○ t̲h̲e̲n̲, by the definition of a limit:
               $\rule{0pt}{}$
               ■ $\left|\dfrac{𝒂_{n}}{𝒃_{n}}-\mathcal{L}\right|<\varepsilon \mathcal{L}$
               $\rule{0pt}{}$
     ◉ Rewrite the absolute value inequality:
          $\rule{0pt}{}$
          ○ $-\varepsilon \mathcal{L}<\dfrac{𝒂_{n}}{𝒃_{n}}-\mathcal{L}<\varepsilon \mathcal{L}$
          $\rule{0pt}{}$
     ◉ Add $\mathcal{L}$ to every part:
          $\rule{0pt}{}$
          ○ $\mathcal{L}-\varepsilon \mathcal{L}<\dfrac{𝒂_{n}}{𝒃_{n}}<\mathcal{L}+\varepsilon \mathcal{L}$
          $\rule{0pt}{}$
     ◉ Factor out $\mathcal{L}$:
          $\rule{0pt}{}$
          ○ $(1-\varepsilon)\mathcal{L}<\dfrac{𝒂_{n}}{𝒃_{n}}<(1+\varepsilon)\mathcal{L}$
          $\rule{0pt}{}$
     ◉ Since $𝒃_{n}>0$, multiply every part by $𝒃_{n}$:
          $\rule{0pt}{}$
          ○ $(1-\varepsilon)\mathcal{L}\cdot 𝒃_{n}<𝒂_{n}<(1+\varepsilon)\mathcal{L}\cdot 𝒃_{n}$
          $\rule{0pt}{}$
     ◉ Key interpretation:
          ○ $𝒂_{n}$ is trapped between two positive constant multiples of $𝒃_{n}$.
          ○ therefore, $𝒂_{n}$ and $𝒃_{n}$ must have the same convergence behavior.

● [47:00](https://www.youtube.com/watch?v=ei8WKMAHky0&t=2820). How the inequality proves convergence.
     ◉ From the right side of the inequality:
          $\rule{0pt}{}$
          ○ $𝒂_{n}<(1+\varepsilon)\mathcal{L}\cdot 𝒃_{n}$
          $\rule{0pt}{}$
     ◉ i̲f̲  $\displaystyle \sum 𝒃_{n}$ converges,
     $\rule{0pt}{}$
          ○ t̲h̲e̲n̲  $\displaystyle \sum (1+\varepsilon)\mathcal{L}\cdot 𝒃_{n}$ also converges,
          $\rule{0pt}{}$
               ■ because multiplying by a positive constant does not change convergence.
     ◉ Since $𝒂_{n}$ is smaller than a convergent positive series,
          ○ $\displaystyle \sum 𝒂_{n}$ also converges.

● [47:00](https://www.youtube.com/watch?v=ei8WKMAHky0&t=2820). How the inequality proves divergence.
     ◉ From the left side of the inequality:
          $\rule{0pt}{}$
          ○ $(1-\varepsilon)\mathcal{L}\cdot 𝒃_{n}<𝒂_{n}$
          $\rule{0pt}{}$
     ◉ i̲f̲  $\displaystyle \sum 𝒃_{n}$ diverges,
     $\rule{0pt}{}$
          ○+ t̲h̲e̲n̲  $\displaystyle \sum (1-\varepsilon)\mathcal{L}\cdot 𝒃_{n}$ also diverges,
          $\rule{0pt}{}$
               ■ because multiplying by a positive constant does not change divergence.
     ◉ Since $𝒂_{n}$ is bigger than a divergent positive series,
          ○ $\displaystyle \sum 𝒂_{n}$ also diverges.

● Practical use of the LCT.
     ◉ $𝒂_{n}$ is the term of the given series.
     ◉ $𝒃_{n}$ is the term of the known comparison series.
     ◉ Usually:
          ○ choose $𝒃_{n}$ from the end behavior of $𝒂_{n}$.
     ◉ Then compute:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{𝒂_{n}}{𝒃_{n}}$
     
● N̲O̲T̲E̲ — Do not misread the LCT.
     ◉ If the LCT limit exists,
          ○ this does not automatically mean the series converges.
     ◉ It means:
          ○ the given series and the comparison series have the same behavior.
     ◉ Therefore:
          ○ if the comparison series converges,
               ■ the given series converges.
          ○ if the comparison series diverges,
               ■ the given series diverges.

● [50:36](https://www.youtube.com/watch?v=ei8WKMAHky0&t=3036). 🧩 Example 4 Continue — Applying the LCT:  $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{\sqrt{𝒏}+1}$ [📷image-1](../img/Calculus 2 Lecture 9.4/[50-36]-01.png) [📷image-2](../img/Calculus 2 Lecture 9.4/[50-36]-02.png)
     ◉ Compare with:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{\sqrt{𝒏}}$
          $\rule{0pt}{}$
     ◉ Let:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{1}{\sqrt{𝒏}+1}$
          $\rule{0pt}{}$
          ○ $𝒃_{n}=\dfrac{1}{\sqrt{𝒏}}$
          $\rule{0pt}{}$
     ◉ [53:37](https://www.youtube.com/watch?v=ei8WKMAHky0&t=3217). Computing the LCT.
          ○ Compute:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{n\to\infty}\left[\dfrac{𝒂_{n}}{𝒃_{n}}\right]$
               $\rule{0pt}{}$
          ○ Substitute:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{n\to\infty}\left[\dfrac{1}{\sqrt{𝒏}+1}\right]\Big/\left[\dfrac{1}{\sqrt{𝒏}}\right]$
               $\rule{0pt}{}$
          ○ Reciprocate and multiply:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{n\to\infty}\dfrac{\sqrt{𝒏}}{\sqrt{𝒏}+1}$
               $\rule{0pt}{}$
          ○ Divide by the largest power in the denominator:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{n\to\infty}\dfrac{1}{1+\dfrac{1}{\sqrt{𝒏}}}$
          ○ Since:
               $\rule{0pt}{}$
               ■ $\dfrac{1}{\sqrt{𝒏}}\to 0$
               $\rule{0pt}{}$
          ○ limit is: $1$
     ◉ [56:15](https://www.youtube.com/watch?v=ei8WKMAHky0&t=3375). Interpretation of the LCT result in Example 4.
          ○ The limit exists:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{n\to\infty}\dfrac{𝒂_{n}}{𝒃_{n}}=1$
               $\rule{0pt}{}$
          ○ Therefore:
               ■ both series have the same convergence behavior.
          ○ Since:
          $\rule{0pt}{}$
               ■ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{\sqrt{𝒏}}$ is a divergent 𝒑-series with $𝒑=\dfrac{1}{2}$,
               $\rule{0pt}{}$
          ○ Therefore:
          $\rule{0pt}{}$
               ■ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{\sqrt{𝒏}+1}$ also diverges.


● N̲O̲T̲E̲ — Key warning.
     ◉ In the Limit Comparison Test,
          ○ the fact that the limit exists does not automatically mean convergence.
     ◉ It only means:
          ○ the given series behaves like the comparison series.
     ◉ Therefore:
          ○ if the comparison series converges,
               ■ the given series converges.
          ○ if the comparison series diverges,
               ■ the given series diverges.



               


Ｔｅｓｔ　Ｄｅｃｉｓｉｏｎ　Ｍａｐ

● [49:03](https://www.youtube.com/watch?v=ei8WKMAHky0&t=2943). Decision map for choosing series tests.
     ◉ Step 1 — Always start with the Divergence Test.
          ○ take the limit of the general term:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{n\to\infty}𝒂_{n}$
               $\rule{0pt}{}$
          ○ i̲f̲ $\displaystyle \lim_{n\to\infty}𝒂_{n}\ne 0$,
               ■ t̲h̲e̲n̲ the series diverges.
               ■ stop immediately.
          ○ i̲f̲ $\displaystyle \lim_{n\to\infty}𝒂_{n}=0$,
               ■ t̲h̲e̲n̲ the test is inconclusive.
               ■ continue with another test.
     ◉ Step 2 — Check the easy known series.
          ○ Is it geometric?
               ■ i̲f̲ yes, use the Geometric Series Test.
          ○ Is it a 𝒑-series?
               ■ i̲f̲ yes, use the 𝒑-Series Test.
          ○ Is it harmonic or similar to harmonic?
               ■ i̲f̲ yes, use the known behavior of the harmonic series.
     ◉ Step 3 — Consider the Integral Test.
          ○ Ask:
               ■ can the terms be represented by a function $𝒇(𝒙)$?
          ○ Check whether $𝒇(𝒙)$ is:
               ■ positive,
               ■ continuous,
               ■ decreasing.
          ○ i̲f̲ these conditions hold,
               ■ t̲h̲e̲n̲ the Integral Test may work well.
     ◉ Step 4 — Try the Direct Comparison Test.
          ○ To prove convergence:
               ■ check whether the given series is smaller than a known convergent series.
               ■ smaller than convergent ⇒ convergent.
          ○ To prove divergence:
               ■ check whether the given series is bigger than a known divergent series.
               ■ bigger than divergent ⇒ divergent.
     ◉ Step 5 — Recognize when Direct Comparison is inconclusive.
          ○ smaller than divergent ⇒ inconclusive.
          ○ bigger than convergent ⇒ inconclusive.
          ○ in these cases,
               ■ Direct Comparison does not give enough information.
     ◉ Step 6 — Try the Limit Comparison Test.
          ○ Use this when the given series has similar end behavior to a known series.
          ○ Choose a known comparison series:
               ■ usually geometric,
               ■ or a 𝒑-series,
               ■ or harmonic-type.
          ○ Compute:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{n\to\infty}\dfrac{𝒂_{n}}{𝒃_{n}}$
               $\rule{0pt}{}$
          ○ i̲f̲ this limit exists and is a finite positive number,
               ■ t̲h̲e̲n̲ both series have the same convergence behavior.
               ■ they both converge or they both diverge.



               
          

Ｓｅｑｕｅｎｃｅｓ　ｖｅｒｓｕｓ　Ｓｅｒｉｅｓ

● [57:32](https://www.youtube.com/watch?v=ei8WKMAHky0&t=3452). Clarification — Sequences versus series.
     ◉ A sequence is a list of terms:
          $\rule{0pt}{}$
          ○ $𝒂_{1}, 𝒂_{2}, 𝒂_{3}, \ldots$
          $\rule{0pt}{}$
     ◉ A series is the sum of those terms:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty} 𝒂_{n}$
          $\rule{0pt}{}$
     ◉ Important:
          ○ the limit of the terms is not the same thing as the sum of the series.

● [58:16](https://www.youtube.com/watch?v=ei8WKMAHky0&t=3496). Difference between a sequence limit and a series sum.
     ◉ The Divergence Test looks at:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}𝒂_{n}$
          $\rule{0pt}{}$
     ◉ But the series is about:
          $\rule{0pt}{}$
          ○ $𝒂_{1}+𝒂_{2}+𝒂_{3}+\cdots$
          $\rule{0pt}{}$
     ◉ i̲f̲  $\displaystyle \lim_{n\to\infty}𝒂_{n}\ne 0$
          ○ t̲h̲e̲n̲ the series diverges.
     ◉  i̲f̲  $\displaystyle \lim_{n\to\infty}𝒂_{n}=0$
          ○ t̲h̲e̲n̲ the series may converge or diverge.

● [1:00:00](https://www.youtube.com/watch?v=ei8WKMAHky0&t=3600). Meaning of convergence as a finite sum.
     ◉ A series converges when:
          ○ the infinite sum approaches a finite number.
     ◉ This does not mean:
          ○ the terms add to $0$.
     ◉ It means:
          ○ the terms become small enough that the total sum stabilizes.
     ◉ Necessary condition:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}𝒂_{n}=0$
          $\rule{0pt}{}$
     ◉ But:
          ○ $\displaystyle \lim_{n\to\infty}𝒂_{n}=0$ does not guarantee convergence.




          

Ｅｎｄ　Ｂｅｈａｖｉｏｒ　Ｓｔｒａｔｅｇｙ

● [1:03:50](https://www.youtube.com/watch?v=ei8WKMAHky0&t=3830). Advanced strategy — End behavior.
     ◉ When using the Limit Comparison Test,
          ○ choose a comparison series based on end behavior.
     ◉ End behavior means:
          ○ **the dominant part of the expression as $𝒏\to\infty$.**
     ◉ For rational expressions:
          ○ keep the leading terms.
     ◉ For radicals:
          ○ keep the dominant term inside the radical.
     ◉ For sums in the numerator:
          ○ keep the fastest-growing term.

● [1:04:30](https://www.youtube.com/watch?v=ei8WKMAHky0&t=3870). Leading terms in rational and radical expressions.
     ◉ Example:
          ○ $2𝒏^{2}+𝒏$ behaves like $2𝒏^{2}$.
     ◉ Example:
          ○ $\sqrt{4𝒏^{7}+3}$ behaves like $\sqrt{4𝒏^{7}}$.
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\dfrac{2𝒏^{2}+𝒏}{\sqrt{4𝒏^{7}+3}}$
          $\rule{0pt}{}$
     ◉ behaves like:
          $\rule{0pt}{}$
          ○ $\dfrac{2𝒏^{2}}{\sqrt{4𝒏^{7}}}$
          $\rule{0pt}{}$
          ○ **Because we are checking whether both series have the same end behavior as $𝒏\to\infty$.**






Ａｄｖａｎｃｅｄ　Ｅｘａｍｐｌｅｓ　Ｗｉｔｈ　ＬＣＴ

Ｅｘａｍｐｌｅ  1

● [📷image-1](../img/Calculus 2 Lecture 9.4/[1-05-20]-01.png) [📷image-2](../img/Calculus 2 Lecture 9.4/[1-05-20]-02.png)

● [1:05:20](https://www.youtube.com/watch?v=ei8WKMAHky0&t=3920). 🧩 Advanced Example 1 — $\displaystyle \sum \dfrac{2𝒏^{2}+𝒏}{\sqrt{4𝒏^{7}+3}}$.
     ◉ First check the Divergence Test:
          ○ the terms tend to $0$.
          ○ so the Divergence Test is inconclusive.
     ◉ Use Limit Comparison based on end behavior.

● [1:06:11](https://www.youtube.com/watch?v=ei8WKMAHky0&t=3971). Finding the comparison series.
     ◉ End behavior of the numerator:
          ○ $2𝒏^{2}+𝒏$ behaves like $2𝒏^{2}$.
     ◉ End behavior of the denominator:
          ○ $\sqrt{4𝒏^{7}+3}$ behaves like $\sqrt{4𝒏^{7}}$.
     ◉ Therefore, compare with:
          $\rule{0pt}{}$
          ○ $\dfrac{2𝒏^{2}}{\sqrt{4𝒏^{7}}}$
          $\rule{0pt}{}$
     ◉ Simplify:
          $\rule{0pt}{}$
          ○ $\dfrac{2𝒏^{2}}{\sqrt{4𝒏^{7}}}=\dfrac{2𝒏^{2}}{2𝒏^{7/2}}$
          $\rule{0pt}{}$
          ○ $=\dfrac{𝒏^{2}}{𝒏^{7/2}}$
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{𝒏^{3/2}}$
          $\rule{0pt}{}$
     ◉ Comparison series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{1}{𝒏^{3/2}}$


● [1:06:35](https://www.youtube.com/watch?v=ei8WKMAHky0&t=3995). Behavior of the comparison series.
     ◉ The comparison series is:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{1}{𝒏^{3/2}}$
          $\rule{0pt}{}$
     ◉ This is a 𝒑-series with:
          $\rule{0pt}{}$
          ○ $𝒑=\dfrac{3}{2}$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\dfrac{3}{2}>1$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{1}{𝒏^{3/2}}$ converges.

● [1:07:44](https://www.youtube.com/watch?v=ei8WKMAHky0&t=4064). Setting up the LCT.
     ◉ Let:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{2𝒏^{2}+𝒏}{\sqrt{4𝒏^{7}+3}}$
          $\rule{0pt}{}$
          ○ $𝒃_{n}=\dfrac{1}{𝒏^{3/2}}$
          $\rule{0pt}{}$
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{𝒂_{n}}{𝒃_{n}}$
          $\rule{0pt}{}$
     ◉ That is:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\left[\dfrac{2𝒏^{2}+𝒏}{\sqrt{4𝒏^{7}+3}}\right]\Big/\left[\dfrac{1}{𝒏^{3/2}}\right]$


● [1:09:18](https://www.youtube.com/watch?v=ei8WKMAHky0&t=4158). Simplifying the LCT expression.
     ◉ Reciprocate and multiply:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{(2𝒏^{2}+𝒏)𝒏^{3/2}}{\sqrt{4𝒏^{7}+3}}$
          $\rule{0pt}{}$
     ◉ Distribute:
          $\rule{0pt}{}$
          ○ $(2𝒏^{2}+𝒏)𝒏^{3/2}=2𝒏^{7/2}+𝒏^{5/2}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{2𝒏^{7/2}+𝒏^{5/2}}{\sqrt{4𝒏^{7}+3}}$


● [1:12:02](https://www.youtube.com/watch?v=ei8WKMAHky0&t=4322). Dividing by the largest power.
     ◉ The largest power in the denominator is:
          $\rule{0pt}{}$
          ○ $\sqrt{𝒏^{7}}=𝒏^{7/2}$
          $\rule{0pt}{}$
     ◉ Divide numerator and denominator by:
          $\rule{0pt}{}$
          ○ $𝒏^{7/2}$
     ◉ We get:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{2+\dfrac{1}{𝒏}}{\sqrt{4+\dfrac{3}{𝒏^{7}}}}$
          $\rule{0pt}{}$
     ◉ As $𝒏\to\infty$:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{𝒏}\to 0$
          $\rule{0pt}{}$
          ○ $\dfrac{3}{𝒏^{7}}\to 0$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ the limit is $\dfrac{2}{\sqrt{4}}=1$

● [1:14:10](https://www.youtube.com/watch?v=ei8WKMAHky0&t=4450). Conclusion for Advanced Example 1.
     ◉ The LCT limit exists:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{𝒂_{n}}{𝒃_{n}}=1$
          $\rule{0pt}{}$
     ◉ Since:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{1}{𝒏^{3/2}}$ converges,
          $\rule{0pt}{}$
     ◉ Then:
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{2𝒏^{2}+𝒏}{\sqrt{4𝒏^{7}+3}}$ also converges.
          

Ｅｘａｍｐｌｅ  2

● [📷image-1](../img/Calculus 2 Lecture 9.4/[1-17-30]-01.png) [📷image-2](../img/Calculus 2 Lecture 9.4/[1-17-30]-02.png)

● [1:17:30](https://www.youtube.com/watch?v=ei8WKMAHky0&t=4650). 🧩 Advanced Example 2 — $\displaystyle \sum \dfrac{\sqrt{𝒏}+\ln(𝒏)}{𝒏^{2}+1}$.
     ◉ First check the Divergence Test:
          ○ the terms tend to $0$.
          ○ so the D ivergence Test is inconclusive.
     ◉ The series is not:
          ○ geometric.
          ○ a simple 𝒑-series.
          ○ convenient for the Integral Test.
     ◉ Use the Limit Comparison Test.

● [1:19:42](https://www.youtube.com/watch?v=ei8WKMAHky0&t=4782). Comparing growth rates: $\sqrt{𝒏}$ versus $\ln(𝒏)$.
     ◉ In the numerator:
          $\rule{0pt}{}$
          ○ $\sqrt{𝒏}+\ln(𝒏)$
          $\rule{0pt}{}$
     ◉ We need the dominant term.
     ◉ Compare:
          $\rule{0pt}{}$
          ○ $\sqrt{𝒏}$
          $\rule{0pt}{}$
          ○ $\ln(𝒏)$
          $\rule{0pt}{}$
     ◉ $\sqrt{𝒏}$ **grows faster** than $\ln(𝒏)$.
          ○ The fastest-growing part is the one that determines the **end behavior as $𝒏\to\infty$.**
     ◉ Therefore:
          ○ the numerator behaves like $\sqrt{𝒏}$.
     ◉ The denominator:
          ○ $𝒏^{2}+1$ behaves like $𝒏^{2}$.
     ◉ Therefore, the whole expression behaves like:
          $\rule{0pt}{}$
          ○ $\dfrac{\sqrt{𝒏}}{𝒏^{2}}$

● [1:20:40](https://www.youtube.com/watch?v=ei8WKMAHky0&t=4840). Using derivatives to compare growth.
     ◉ Let:
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\sqrt{𝒙}$
          $\rule{0pt}{}$
          ○ $𝒈(𝒙)=\ln(𝒙)$
          $\rule{0pt}{}$
     ◉ Derivatives:
          $\rule{0pt}{}$
          ○ $𝒇'(𝒙)=\dfrac{1}{2\sqrt{𝒙}}$
          $\rule{0pt}{}$
          ○ $𝒈'(𝒙)=\dfrac{1}{𝒙}$
          $\rule{0pt}{}$
     ◉ The derivative $\dfrac{1}{𝒙}$ goes to $0$ faster than $\dfrac{1}{2\sqrt{𝒙}}$.
     ◉ Therefore:
          ○ $\ln(𝒙)$ slows down faster.
          ○ $\sqrt{𝒙}$ eventually grows faster.
     ◉ So:
          ○ $\sqrt{𝒏}$ is the dominant numerator term.

● [1:23:20](https://www.youtube.com/watch?v=ei8WKMAHky0&t=5000). Finding the comparison series.
     ◉ The end behavior is:
          $\rule{0pt}{}$
          ○ $\dfrac{\sqrt{𝒏}}{𝒏^{2}}$
          $\rule{0pt}{}$
     ◉ Rewrite:
          $\rule{0pt}{}$
          ○ $\dfrac{\sqrt{𝒏}}{𝒏^{2}}=\dfrac{𝒏^{1/2}}{𝒏^{2}}$
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{𝒏^{3/2}}$
          $\rule{0pt}{}$
     ◉ Therefore, compare with:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{1}{𝒏^{3/2}}$
          $\rule{0pt}{}$
     ◉ This is a convergent 𝒑-series because:
          $\rule{0pt}{}$
          ○ $𝒑=\dfrac{3}{2}>1$

● [1:25:48](https://www.youtube.com/watch?v=ei8WKMAHky0&t=5148). Setting up the LCT for Advanced Example 2.
     ◉ Let:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{\sqrt{𝒏}+\ln(𝒏)}{𝒏^{2}+1}$
          $\rule{0pt}{}$
          ○ $𝒃_{n}=\dfrac{1}{𝒏^{3/2}}$
          $\rule{0pt}{}$
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{𝒂_{n}}{𝒃_{n}}$
          $\rule{0pt}{}$
     ◉ That is:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\left[\dfrac{\sqrt{𝒏}+\ln(𝒏)}{𝒏^{2}+1}\right]\Big/\left[\dfrac{1}{𝒏^{3/2}}\right]$


● [1:26:03](https://www.youtube.com/watch?v=ei8WKMAHky0&t=5163). Simplifying the LCT expression.
     ◉ Reciprocate and multiply:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{(\sqrt{𝒏}+\ln(𝒏))𝒏^{3/2}}{𝒏^{2}+1}$
          $\rule{0pt}{}$
     ◉ Distribute:
          $\rule{0pt}{}$
          ○ $\sqrt{𝒏}\cdot 𝒏^{3/2}=𝒏^{2}$
          $\rule{0pt}{}$
          ○ $\ln(𝒏)\cdot 𝒏^{3/2}=𝒏^{3/2}\ln(𝒏)$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{𝒏^{2}+𝒏^{3/2}\ln(𝒏)}{𝒏^{2}+1}$


● [1:27:07](https://www.youtube.com/watch?v=ei8WKMAHky0&t=5227). Divide by the largest power.
     ◉ The largest power in the denominator is:
          $\rule{0pt}{}$
          ○ $𝒏^{2}$
     ◉ Divide numerator and denominator by:
          $\rule{0pt}{}$
          ○ $𝒏^{2}$
     ◉ We get:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{1+\dfrac{\ln(𝒏)}{\sqrt{𝒏}}}{1+\dfrac{1}{𝒏^{2}}}$


● [1:28:17](https://www.youtube.com/watch?v=ei8WKMAHky0&t=5297). Handling $\dfrac{\ln(𝒏)}{\sqrt{𝒏}}$.
     ◉ The expression:
          $\rule{0pt}{}$
          ○ $\dfrac{\ln(𝒏)}{\sqrt{𝒏}}$
          $\rule{0pt}{}$
     ◉ gives the indeterminate form:
          $\rule{0pt}{}$
          ○ $\infty/\infty$
     ◉ Use L'Hôpital's Rule:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{\ln(𝒏)}{\sqrt{𝒏}}$
          $\rule{0pt}{}$
     ◉ Differentiate numerator and denominator:
          $\rule{0pt}{}$
          ○ $\dfrac{d}{d𝒏}[\ln(𝒏)]=\dfrac{1}{𝒏}$
          $\rule{0pt}{}$
          ○ $\dfrac{d}{d𝒏}[\sqrt{𝒏}]=\dfrac{1}{2\sqrt{𝒏}}$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{\dfrac{1}{𝒏}}{\dfrac{1}{2\sqrt{𝒏}}}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{n\to\infty}\dfrac{2\sqrt{𝒏}}{𝒏}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{n\to\infty}\dfrac{2}{\sqrt{𝒏}}$
          $\rule{0pt}{}$
          ○ $=0$

● [1:31:17](https://www.youtube.com/watch?v=ei8WKMAHky0&t=5477). Final LCT limit for Advanced Example 2.
     ◉ Now:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{1+\dfrac{\ln(𝒏)}{\sqrt{𝒏}}}{1+\dfrac{1}{𝒏^{2}}}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\dfrac{\ln(𝒏)}{\sqrt{𝒏}}\to 0$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{𝒏^{2}}\to 0$
          $\rule{0pt}{}$
     ◉ The limit is:
          $\rule{0pt}{}$
          ○ $\dfrac{1+0}{1+0}=1$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ the LCT limit exists.

● [1:32:01](https://www.youtube.com/watch?v=ei8WKMAHky0&t=5521). Conclusion for Advanced Example 2.
     ◉ Since the LCT limit exists,
          ○ the given series has the same behavior as the comparison series.
     ◉ Since:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{1}{𝒏^{3/2}}$ converges,
          $\rule{0pt}{}$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{\sqrt{𝒏}+\ln(𝒏)}{𝒏^{2}+1}$ also converges.




          

Ｆｉｎａｌ　Ｓｕｍｍａｒｙ　ａｎｄ　Ｄｅｃｉｓｉｏｎ　Ｐｒｏｃｅｓｓ

● [1:33:18](https://www.youtube.com/watch?v=ei8WKMAHky0&t=5598). Final summary for series tests.
     ◉ Step 1:
          ○ always check the Divergence Test.
     ◉  i̲f̲  $\displaystyle \lim_{n\to\infty}𝒂_{n}\ne 0$
          ○ t̲h̲e̲n̲ the series diverges.
     ◉  i̲f̲  $\displaystyle \lim_{n\to\infty}𝒂_{n}=0$
          ○ t̲h̲e̲n̲ continue.

● Check the easy tests first.
     ◉ After the Divergence Test, check:
          ○ geometric series.
          ○ 𝒑-series.
          ○ harmonic series.
     ◉ These are fast and should be recognized immediately.

● Then choose a more advanced test.
     ◉ If the series is not simple:
          ○ consider the Integral Test.
          ○ consider the Direct Comparison Test.
          ○ consider the Limit Comparison Test.
     ◉ Use Direct Comparison when:
          ○ the inequality gives useful information.
          ○ smaller than convergent.
          ○ bigger than divergent.
     ◉ Use Limit Comparison when:
          ○ Direct Comparison is difficult or inconclusive.
          ○ the series has clear end behavior.

● N̲O̲T̲E̲ — Decision diagram.
     ◉ First:
          ○ check $\displaystyle \lim_{n\to\infty}𝒂_{n}$.
     ◉ If $\displaystyle \lim_{n\to\infty}𝒂_{n}\ne 0$:
          ○ Divergence Test ⇒ diverges.
     ◉ If $\displaystyle \lim_{n\to\infty}𝒂_{n}=0$:
          ○ check geometric series.
          ○ check 𝒑-series.
          ○ check Integral Test.
          ○ check Direct Comparison.
          ○ check Limit Comparison.
     ◉ Direct Comparison:
          ○ smaller than convergent ⇒ convergent.
          ○ bigger than divergent ⇒ divergent.
          ○ smaller than divergent ⇒ inconclusive.
          ○ bigger than convergent ⇒ inconclusive.
     ◉ Limit Comparison:
          ○ choose $𝒃_{n}$ from end behavior.
          ○ compute $\displaystyle \lim_{n\to\infty}\dfrac{𝒂_{n}}{𝒃_{n}}$.
          ○ if the limit is finite and positive,
               ■ both series have the same convergence behavior.





Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Comparison Tests 
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/5-4-comparison-tests)