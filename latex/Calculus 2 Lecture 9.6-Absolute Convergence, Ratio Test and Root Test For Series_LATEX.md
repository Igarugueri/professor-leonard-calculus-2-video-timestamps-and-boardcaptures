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
          $\rule{0pt}{}$
          ○ $\displaystyle \sum 𝒂_{n}$
          $\rule{0pt}{}$
     ◉ Take the absolute value of every term:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum |𝒂_{n}|$
          $\rule{0pt}{}$
     ◉ i̲f̲  $\displaystyle \sum |𝒂_{n}|$ converges,
     $\rule{0pt}{}$
          ○ t̲h̲e̲n̲ $\displaystyle \sum 𝒂_{n}$ is absolutely convergent.


● [2:03](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=123). Effect of absolute value.
     ◉ The absolute value changes negative terms into positive terms.
     ◉ Example:
          $\rule{0pt}{}$
          ○ $|𝒂_{1}|+|𝒂_{2}|+|𝒂_{3}|+\cdots$
          $\rule{0pt}{}$
     ◉ There are no negative terms left.
     ◉ Therefore:
          ○ absolute convergence studies the convergence of the positive-size version of the series.

● [4:25](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=265). 🧩 Example —  Use for things like this: $\displaystyle \sum_{n=1}^{\infty}\dfrac{\sin(2𝑥)}{𝒏^{2}}$
$\rule{0pt}{}$
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

● [4:25](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=265). 🧩 Example —  Absolute convergence: $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n-1}}{𝒏^{2}}$
     ◉ This is an alternating series.
     ◉ It converges by the Alternating Series Test.
     ◉ But now we check whether it converges absolutely.

● [5:03](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=303). Take the absolute value.
     ◉ Consider:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left|\dfrac{(-1)^{n-1}}{𝒏^{2}}\right|$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $|(-1)^{n-1}|=1$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\left|\dfrac{(-1)^{n-1}}{𝒏^{2}}\right|=\dfrac{1}{𝒏^{2}}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left|\dfrac{(-1)^{n-1}}{𝒏^{2}}\right|=\sum_{n=1}^{\infty}\dfrac{1}{𝒏^{2}}$


● [5:35](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=335). Use the 𝒑-Series Test.
     ◉ The series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{𝒏^{2}}$
          $\rule{0pt}{}$
     ◉ is a 𝒑-series with:
          $\rule{0pt}{}$
          ○ $𝒑=2$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $2>1$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{𝒏^{2}}$ converges.


● [6:01](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=361). Conclusion.
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left|\dfrac{(-1)^{n-1}}{𝒏^{2}}\right|$ converges,
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n-1}}{𝒏^{2}}$ is absolutely convergent.
          $\rule{0pt}{}$
     ◉ Important:
          ○ we do not only say “convergent.”
          ○ we say “absolutely convergent,” because the absolute value series converges.






2  - Ｃｏｎｄｉｔｉｏｎａｌ　Ｃｏｎｖｅｒｇｅｎｃｅ

● [📷image](../img/Calculus 2 Lecture 9.6/[7-19]-01.png)

● [7:19](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=439). 🧩 Example — Conditional convergence: $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n-1}}{𝒏}$
     ◉ This is the alternating harmonic series.
     ◉ We already know:
          ○ it converges by the Alternating Series Test.

● [8:24](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=504). Check ordinary convergence.
     ◉ The series is alternating.
     ◉ Positive part:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{1}{𝒏}$
          $\rule{0pt}{}$
     ◉ Check the limit:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{1}{𝒏}=0$
          $\rule{0pt}{}$
     ◉ Check decreasing:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{𝒏+1}\le \dfrac{1}{𝒏}$
          $\rule{0pt}{}$
     ◉ Therefore, by the Alternating Series Test:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n-1}}{𝒏}$ converges.
          $\rule{0pt}{}$
     ◉ Important:
          ○ this proves ordinary convergence,
               ■ not absolute convergence.

● [9:10](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=550). Check absolute convergence.
     ◉ Take the absolute value:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left|\dfrac{(-1)^{n-1}}{𝒏}\right|$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $|(-1)^{n-1}|=1$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left|\dfrac{(-1)^{n-1}}{𝒏}\right|=\sum_{n=1}^{\infty}\dfrac{1}{𝒏}$


● [10:13](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=613). Harmonic Series.
     ◉ The series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{𝒏}$
          $\rule{0pt}{}$
     ◉ is the harmonic series.
     ◉ The harmonic series diverges.
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left|\dfrac{(-1)^{n-1}}{𝒏}\right|$ diverges.


● [10:48](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=648). Important conclusion.
     ◉ The original alternating harmonic series converges:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n-1}}{𝒏}$ converges.
          $\rule{0pt}{}$
     ◉ But its absolute value series diverges:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left|\dfrac{(-1)^{n-1}}{𝒏}\right|$ diverges.
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ the original series is not absolutely convergent.

● [12:10](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=730). **Definition of conditional convergence.**
     ◉ i̲f̲ the original series $\displaystyle \sum 𝒂_{n}$ converges, a̲n̲d̲ the absolute value series $\displaystyle \sum |𝒂_{n}|$ diverges,
     $\rule{0pt}{}$
          ○ t̲h̲e̲n̲ the series $\displaystyle \sum 𝒂_{n}$ is conditionally convergent.
          $\rule{0pt}{}$
     ◉ Symbolically:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum 𝒂_{n}$ converges
          $\rule{0pt}{}$
          ○ but $\displaystyle \sum |𝒂_{n}|$ diverges
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum 𝒂_{n}$ is conditionally convergent.


● [13:49](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=829). Conditional convergence for the alternating harmonic series.
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n-1}}{𝒏}$ converges,
          $\rule{0pt}{}$
     ◉ But:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left|\dfrac{(-1)^{n-1}}{𝒏}\right|=\sum_{n=1}^{\infty}\dfrac{1}{𝒏}$ diverges,
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n-1}}{𝒏}$ is conditionally convergent.


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
     $\rule{0pt}{}$
          ○ $\displaystyle \sum 𝒂_{n}$ converges,
          $\rule{0pt}{}$
          ○ but $\displaystyle \sum |𝒂_{n}|$ diverges.
          $\rule{0pt}{}$
     ◉ Absolutely convergent:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum |𝒂_{n}|$ converges,
          $\rule{0pt}{}$
          ○ so $\displaystyle \sum 𝒂_{n}$ also converges.
          $\rule{0pt}{}$
     ◉ Conceptual hierarchy:
          ○ absolute convergence is the strongest form of convergence.
          ○ conditional convergence is still convergence,
               ■ but it depends on sign cancellation.
          ○ divergence means there is no convergence.





 1.3 - Ａｂｓｏｌｕｔｅ　Ｃｏｎｖｅｒｇｅｎｃｅ　Ｅｘａｍｐｌｅ　ｗｉｔｈ　Ｓｉｎｅ
 

● [📷image](../img/Calculus 2 Lecture 9.6/[16-45]-01.png)

● [16:45](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1005). 🧩 Example — Absolute convergence example: $\displaystyle \sum_{n=1}^{\infty}\dfrac{\sin(2𝒏)}{𝒏^{2}}$.
     ◉ Given series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{\sin(2𝒏)}{𝒏^{2}}$
          $\rule{0pt}{}$
     ◉ First observations:
          ○ it is not always positive.
          ○ it is not alternating in the regular sense.
          ○ $\sin(2𝒏)$ oscillates between $-1$ and $1$.
     ◉ Therefore:
          ○ the Alternating Series Test is not appropriate.
          ○ ordinary Comparison Tests cannot be used directly because the terms are not always positive.

● [17:08](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1028). Divergence Test.
     ◉ Check:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{\sin(2𝒏)}{𝒏^{2}}$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $-1\le \sin(2𝒏)\le 1$
          $\rule{0pt}{}$
     ◉ And:
          $\rule{0pt}{}$
          ○ $𝒏^{2}\to\infty$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\dfrac{\sin(2𝒏)}{𝒏^{2}}\to 0$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ the Divergence Test is inconclusive.


● [18:25](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1105). Take the absolute value.
     ◉ Consider:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left|\dfrac{\sin(2𝒏)}{𝒏^{2}}\right|$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\left|\dfrac{\sin(2𝒏)}{𝒏^{2}}\right|=\dfrac{|\sin(2𝒏)|}{𝒏^{2}}$
          $\rule{0pt}{}$
     ◉ And:
          $\rule{0pt}{}$
          ○ $0\le |\sin(2𝒏)|\le 1$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $0\le \dfrac{|\sin(2𝒏)|}{𝒏^{2}}\le \dfrac{1}{𝒏^{2}}$


● [20:00](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1200). Use Direct Comparison.
     ◉ We have:
          $\rule{0pt}{}$
          ○ $0\le \dfrac{|\sin(2𝒏)|}{𝒏^{2}}\le \dfrac{1}{𝒏^{2}}$
          $\rule{0pt}{}$
     ◉ The comparison series is:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{𝒏^{2}}$
          $\rule{0pt}{}$
     ◉ This is a 𝒑-series with:
          $\rule{0pt}{}$
          ○ $𝒑=2$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $2>1$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{𝒏^{2}}$ converges.


● [21:10](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1270). Conclusion by Comparison Test.
     ◉ Since:
          $\rule{0pt}{}$
          ○ $0\le \dfrac{|\sin(2𝒏)|}{𝒏^{2}}\le \dfrac{1}{𝒏^{2}}$
          $\rule{0pt}{}$
     ◉ And:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{𝒏^{2}}$ converges,
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{|\sin(2𝒏)|}{𝒏^{2}}$ converges.


● [22:10](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1330). Final conclusion.
     ◉ Since the absolute value series converges:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left|\dfrac{\sin(2𝒏)}{𝒏^{2}}\right|$ converges,
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{\sin(2𝒏)}{𝒏^{2}}$ is absolutely convergent.
          $\rule{0pt}{}$
     ◉ Important:
          ○ we used absolute convergence because the original series was not always positive and not regularly alternating.





3 -Ｔｈｅ　Ｒａｔｉｏ　Ｔｅｓｔ


● [📷image](../img/Calculus 2 Lecture 9.6/[25-56]-01.png)

● [25:56](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1556). The Ratio Test.
     ◉ The Ratio Test compares:
          ○ the next term $𝒂_{n+1}$
          ○ with the current term $𝒂_{n}$.
     ◉ Main expression:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\left|\dfrac{𝒂_{n+1}}{𝒂_{n}}\right|$


● [26:24](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1584). Structure of the Ratio Test.
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{𝒂_{n+1}}{𝒂_{n}}\right|$
          $\rule{0pt}{}$
     ◉ Important:
          ○ $𝒂_{n+1}$ goes on top.
          ○ $𝒂_{n}$ goes on the bottom.
     ◉ Be careful:
          ○ do not invert the ratio.

● [28:15](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1695). Ratio Test  $\displaystyle \lim_{n\to\infty}\left|\dfrac{𝒂_{n+1}}{𝒂_{n}}\right|=𝑳$ outcomes.
     ◉ i̲f̲  $𝑳<1$
          ○ t̲h̲e̲n̲ the series is absolutely convergent.
     ◉  i̲f̲  $𝑳>1$
          ○ t̲h̲e̲n̲ the series diverges.
     ◉  i̲f̲  $𝑳=1$
          ○ t̲h̲e̲n̲ the test is inconclusive.

● N̲O̲T̲E̲ — Why the Ratio Test is powerful.
     ◉ The Ratio Test includes absolute values.
     ◉ Therefore:
          ○ it can prove absolute convergence.
     ◉ It is especially useful for:
          ○ factorials.
          ○ powers involving $𝒏$.
          ○ expressions where $\dfrac{𝒂_{n+1}}{𝒂_{n}}$ simplifies nicely.

● N̲O̲T̲E̲ — Ratio Test versus Divergence Test.
     ◉ Usually, we first check the Divergence Test.
     ◉ But with factorials or complicated powers,
          ○ the Divergence Test may be awkward.
     ◉ The Ratio Test can often detect:
          ○ absolute convergence,
          ○ or divergence,
          ○ without needing a separate Divergence Test first.
     ◉ If the Ratio Test gives $𝑳=1$,
          ○ then we must try another test.






3.1 - Ｒａｔｉｏ　Ｔｅｓｔ　Ｅｘａｍｐｌｅ　１


● [📷image](../img/Calculus 2 Lecture 9.6/[30-00]-01.png)

● [30:00](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1800). 🧩 Example 1 — Ratio test: $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n-1}(𝒏^{2}+1)}{2^{n}}$.
     ◉ It is alternating because of:
          $\rule{0pt}{}$
          ○ $(-1)^{n-1}$
     ◉ But:
          ○ the Ratio Test can show absolute convergence,
               ■ which is stronger than ordinary convergence.

● [33:00](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=1980). Set up the Ratio Test.
     ◉ Positive/absolute term:
          $\rule{0pt}{}$
          ○ $|𝒂_{n}|=\dfrac{𝒏^{2}+1}{2^{n}}$
          $\rule{0pt}{}$
     ◉ Next term:
          $\rule{0pt}{}$
          ○ $|𝒂_{n+1}|=\dfrac{(𝒏+1)^{2}+1}{2^{n+1}}$
          $\rule{0pt}{}$
     ◉ Ratio:
          $\rule{0pt}{}$
          ○ $\left|\dfrac{𝒂_{n+1}}{𝒂_{n}}\right|$
          $\rule{0pt}{}$
          ○ $=\dfrac{\dfrac{(𝒏+1)^{2}+1}{2^{n+1}}}{\dfrac{𝒏^{2}+1}{2^{n}}}$


● [36:16](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=2176). Simplify the ratio.
     ◉ [36:42](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=2202). Discussion about when the absolute value can be removed
     ◉ Reciprocate and multiply:
          $\rule{0pt}{}$
          ○ $\dfrac{(𝒏+1)^{2}+1}{2^{n+1}}\cdot \dfrac{2^{n}}{𝒏^{2}+1}$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $2^{n+1}=2^{n}\cdot 2$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\dfrac{2^{n}}{2^{n+1}}=\dfrac{1}{2}$
          $\rule{0pt}{}$
     ◉ So the ratio becomes:
          $\rule{0pt}{}$
          ○ $\dfrac{(𝒏+1)^{2}+1}{2(𝒏^{2}+1)}$


● [39:00](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=2340). Evaluate the limit.
     ◉ Expand:
          $\rule{0pt}{}$
          ○ $(𝒏+1)^{2}+1=𝒏^{2}+2𝒏+2$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\dfrac{𝒏^{2}+2𝒏+2}{2𝒏^{2}+2}$
          $\rule{0pt}{}$
     ◉ Compare leading terms:
          $\rule{0pt}{}$
          ○ $𝑳=\dfrac{1}{2}$


● [39:43](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=2383). Conclusion for Example 1.
     ◉ Since:
          $\rule{0pt}{}$
          ○ $𝑳=\dfrac{1}{2}$
          $\rule{0pt}{}$
     ◉ And:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{2}<1$
          $\rule{0pt}{}$
     ◉ By the Ratio Test:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n-1}(𝒏^{2}+1)}{2^{n}}$ is absolutely convergent.






3.2 - Ｒａｔｉｏ　Ｔｅｓｔ　Ｅｘａｍｐｌｅ　２

● [📷image-1](../img/Calculus 2 Lecture 9.6/[43-10]-01.png) [📷image-2](../img/Calculus 2 Lecture 9.6/[43-10]-02.png)

● [43:10](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=2590). 🧩 Example 2 — Ratio test: $\displaystyle \sum_{n=1}^{\infty}\dfrac{𝒏!}{𝒏^{n}}$.
     ◉ This is not:
          ○ geometric,
          ○ a 𝒑-series,
          ○ telescoping.
     ◉ The factorial suggests:
          ○ use the Ratio Test.

● [44:41](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=2681). Set up the Ratio Test.
     ◉ Let:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{𝒏!}{𝒏^{n}}$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $𝒂_{n+1}=\dfrac{(𝒏+1)!}{(𝒏+1)^{n+1}}$
          $\rule{0pt}{}$
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{𝒂_{n+1}}{𝒂_{n}}\right|$


● [45:46](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=2746). Build the ratio.
     ◉ Substitute:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\dfrac{\dfrac{(𝒏+1)!}{(𝒏+1)^{n+1}}}{\dfrac{𝒏!}{𝒏^{n}}}$
          $\rule{0pt}{}$
     ◉ Reciprocate and multiply:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\dfrac{(𝒏+1)!}{(𝒏+1)^{n+1}}\cdot \dfrac{𝒏^{n}}{𝒏!}$


● [48:31](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=2911). Factorial simplification.
     ◉ Fundamental property:
          $\rule{0pt}{}$
          ○ $(𝒏+1)!=(𝒏+1)\cdot 𝒏!$
          $\rule{0pt}{}$
     ◉ Substitute:
          $\rule{0pt}{}$
          ○ $\dfrac{(𝒏+1)\cdot 𝒏!\cdot 𝒏^{n}}{(𝒏+1)^{n+1}\cdot 𝒏!}$
          $\rule{0pt}{}$
     ◉ Cancel:
          $\rule{0pt}{}$
          ○ $𝒏!$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\dfrac{(𝒏+1)𝒏^{n}}{(𝒏+1)^{n+1}}$


● [50:40](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3040). Exponent manipulation.
     ◉ Since:
          $\rule{0pt}{}$
          ○ $(𝒏+1)^{n+1}=(𝒏+1)^{n}\cdot (𝒏+1)$
          $\rule{0pt}{}$
     ◉ Cancel:
          $\rule{0pt}{}$
          ○ $𝒏+1$
          $\rule{0pt}{}$
     ◉ We get:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\dfrac{𝒏^{n}}{(𝒏+1)^{n}}$
          $\rule{0pt}{}$
     ◉ Rewrite:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left(\dfrac{𝒏}{𝒏+1}\right)^{n}$


● [50:26](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3026). Special exponential limit.
     ◉ We reached:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left(\dfrac{𝒏}{𝒏+1}\right)^{n}$
          $\rule{0pt}{}$
     ◉ Direct substitution gives:
          $\rule{0pt}{}$
          ○ $\left(\dfrac{𝒏}{𝒏+1}\right)^{n}\to 1^{\infty}$
          $\rule{0pt}{}$
     ◉ This is an indeterminate form:
          $\rule{0pt}{}$
          ○ $1^{\infty}$
          $\rule{0pt}{}$
     ◉ Rewrite the fraction:
          $\rule{0pt}{}$
          ○ $\dfrac{𝒏}{𝒏+1}=\dfrac{1}{\dfrac{𝒏+1}{𝒏}}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\left(\dfrac{𝒏}{𝒏+1}\right)^{n}=\left[\dfrac{1}{\dfrac{𝒏+1}{𝒏}}\right]^{n}$
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{\left(\dfrac{𝒏+1}{𝒏}\right)^{n}}$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\dfrac{𝒏+1}{𝒏}=1+\dfrac{1}{𝒏}$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\left(\dfrac{𝒏}{𝒏+1}\right)^{n}=\dfrac{1}{\left(1+\dfrac{1}{𝒏}\right)^{n}}$


● N̲O̲T̲E̲: Evaluating the classic exponential limit.
     ◉ We know the classic limit:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\left(1+\dfrac{1}{𝒏}\right)^{n}=𝒆$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{1}{\left(1+\dfrac{1}{𝒏}\right)^{n}}=\dfrac{1}{𝒆}$
          $\rule{0pt}{}$
     ◉ So:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\left(\dfrac{𝒏}{𝒏+1}\right)^{n}=\dfrac{1}{𝒆}$


● [52:30](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3150). Optional derivation of the classic limit.
     ◉ To justify:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\left(1+\dfrac{1}{𝒏}\right)^{n}=𝒆$
          $\rule{0pt}{}$
     ◉ Rewrite using exponentials:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\left(1+\dfrac{1}{𝒏}\right)^{n}$
          $\rule{0pt}{}$
          ○ $=𝒆^{\lim_{n\to\infty}\ln\left(\left(1+\dfrac{1}{𝒏}\right)^{n}\right)}$
          $\rule{0pt}{}$
     ◉ Bring the exponent down:
          $\rule{0pt}{}$
          ○ $=𝒆^{\lim_{n\to\infty} n\ln\left(1+\dfrac{1}{𝒏}\right)}$
          $\rule{0pt}{}$
     ◉ Rewrite as a quotient:
          $\rule{0pt}{}$
          ○ $n\ln\left(1+\dfrac{1}{𝒏}\right)=\dfrac{\ln\left(1+\dfrac{1}{𝒏}\right)}{\dfrac{1}{𝒏}}$
          $\rule{0pt}{}$
     ◉ This gives the indeterminate form:
          $\rule{0pt}{}$
          ○ $0/0$
          $\rule{0pt}{}$
     ◉ Apply L'Hôpital's Rule:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{\ln\left(1+\dfrac{1}{𝒏}\right)}{\dfrac{1}{𝒏}}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{n\to\infty}\dfrac{\dfrac{1}{1+\dfrac{1}{𝒏}}\cdot\left(\dfrac{-1}{𝒏^{2}}\right)}{-\dfrac{1}{𝒏^{2}}}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{n\to\infty}\dfrac{1}{1+\dfrac{1}{𝒏}}$
          $\rule{0pt}{}$
          ○ $=1$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\left(1+\dfrac{1}{𝒏}\right)^{n}=𝒆^{1}=𝒆$
          $\rule{0pt}{}$
     ◉ Hence:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\left(\dfrac{𝒏}{𝒏+1}\right)^{n}=\dfrac{1}{𝒆}$


● [55:13](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3313). Conclusion for Example 2.
     ◉ The Ratio Test limit is:
          $\rule{0pt}{}$
          ○ $𝑳=\dfrac{1}{𝒆}$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{𝒆}<1$
          $\rule{0pt}{}$
     ◉ By the Ratio Test:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{𝒏!}{𝒏^{n}}$ converges absolutely.
          $\rule{0pt}{}$
     ◉ Since the terms are already positive:
          ○ absolute convergence is just convergence here,
          ○ but the Ratio Test still proves convergence.





3.3 - Ｒａｔｉｏ　Ｔｅｓｔ　Ｅｘａｍｐｌｅ　３

● [📷image-1](../img/Calculus 2 Lecture 9.6/[59-52]-01.png) [📷image-2](../img/Calculus 2 Lecture 9.6/[59-52]-02.png)

● [59:52](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3592). 🧩 Example 3 — Ratio test: $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-5)^{n-1}}{𝒏^{2}\cdot 3^{n}}$.
     ◉ Because of the negative base:
          ○ the signs alternate in some form.
     ◉ The Ratio Test is a good choice because:
          ○ there are exponential powers,
          ○ and the absolute value handles the negative signs.

● [1:00:54](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3654). Set up the Ratio Test.
     ◉ Let:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{(-5)^{n-1}}{𝒏^{2}\cdot 3^{n}}$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $𝒂_{n+1}=\dfrac{(-5)^{n}}{(𝒏+1)^{2}\cdot 3^{n+1}}$
          $\rule{0pt}{}$
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{𝒂_{n+1}}{𝒂_{n}}\right|$


● [1:02:18](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3738). Handle the negative base.
     ◉ Inside the absolute value:
          $\rule{0pt}{}$
          ○ $|(-5)^{n}|=5^{n}$
          $\rule{0pt}{}$
          ○ $|(-5)^{n-1}|=5^{n-1}$
          $\rule{0pt}{}$
     ◉ Important:
          ○ the absolute value removes the negative sign,
          ○ but it does not remove the factor $5^{n}$.

● [1:02:00](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3720). Simplify the ratio.
     ◉ Ratio:
          $\rule{0pt}{}$
          ○ $\dfrac{5^{n}}{(𝒏+1)^{2}\cdot 3^{n+1}}\cdot \dfrac{𝒏^{2}\cdot 3^{n}}{5^{n-1}}$
          $\rule{0pt}{}$
     ◉ Simplify powers:
          $\rule{0pt}{}$
          ○ $\dfrac{5^{n}}{5^{n-1}}=5$
          $\rule{0pt}{}$
          ○ $\dfrac{3^{n}}{3^{n+1}}=\dfrac{1}{3}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\dfrac{5}{3}\cdot \dfrac{𝒏^{2}}{(𝒏+1)^{2}}$


● [1:04:39](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3879). Evaluate the limit.
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{𝒏}{𝒏+1}=1$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\left(\dfrac{𝒏}{𝒏+1}\right)^{2}=1$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $𝑳=\dfrac{5}{3}\cdot 1=\dfrac{5}{3}$


● [1:05:03](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=3903). Conclusion for Example 3.
     ◉ Since:
          $\rule{0pt}{}$
          ○ $𝑳=\dfrac{5}{3}$
          $\rule{0pt}{}$
     ◉ And:
          $\rule{0pt}{}$
          ○ $\dfrac{5}{3}>1$
          $\rule{0pt}{}$
     ◉ By the Ratio Test:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-5)^{n-1}}{𝒏^{2}\cdot 3^{n}}$ diverges.
          $\rule{0pt}{}$
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
     ◉ If the Ratio Test gives $𝑳>1$,
          ○ the original series diverges.





4 - Ｔｈｅ　Ｒｏｏｔ　Ｔｅｓｔ

● [📷image](../img/Calculus 2 Lecture 9.6/[1-07-08]-01.png)

● [1:07:08](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4028). The Root Test.
     ◉ The Root Test is useful when the terms contain powers of $𝒏$.
     ◉ It is especially useful when the whole expression is raised to the $𝒏$-th power.
     ◉ It often overlaps with the Ratio Test:
          ○ Ratio Test works well for factorials and $𝒏$-th powers.
          ○ Root Test works especially well for $𝒏$-th powers.
     ◉ Avoid using the Root Test for factorials:
          ○ Ratio Test is usually better there.

● [1:09:14](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4154). Definition of the Root Test.
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\sqrt[n]{|𝒂_{n}|}$
          $\rule{0pt}{}$
     ◉ There is no ratio here.
     ◉ Unlike the Ratio Test:
     $\rule{0pt}{}$
          ○ we do not form $\dfrac{𝒂_{n+1}}{𝒂_{n}}$.
          $\rule{0pt}{}$
     ◉ We take:
          ○ the absolute value of $𝒂_{n}$,
          ○ then the $𝒏$-th root.

● [1:09:45](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4185). Root Test  $\displaystyle \lim_{n\to\infty}\sqrt[n]{|𝒂_{n}|}=𝑳$ outcomes.
     ◉ i̲f̲  $𝑳<1$
          ○ t̲h̲e̲n̲ the series is absolutely convergent.
     ◉ i̲f̲  $𝑳>1$
          ○ t̲h̲e̲n̲ the series diverges.
     ◉ i̲f̲  $𝑳=1$
          ○ t̲h̲e̲n̲ the test is inconclusive.





4.1 - Ｒｏｏｔ　Ｔｅｓｔ　Ｅｘａｍｐｌｅ


● [📷image](../img/Calculus 2 Lecture 9.6/[1-11-45]-01.png)

● [1:11:45](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4305). 🧩 Example —  Root test: $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n}2^{n+3}}{(𝒏+1)^{n}}$.
     ◉ It is alternating because of:
          $\rule{0pt}{}$
          ○ $(-1)^{n}$
          $\rule{0pt}{}$
     ◉ But:
          ○ showing decreasing behavior directly may not be convenient.
     ◉ Since the expression contains $𝒏$-th powers,
          ○ the Root Test is a natural choice.

● [1:13:32](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4412). Set up the Root Test.
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\sqrt[n]{\left|\dfrac{(-1)^{n}2^{n+3}}{(𝒏+1)^{n}}\right|}$
          $\rule{0pt}{}$
     ◉ The absolute value removes:
          $\rule{0pt}{}$
          ○ $(-1)^{n}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\sqrt[n]{\dfrac{2^{n+3}}{(𝒏+1)^{n}}}$


● [1:14:51](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4491). Separate constants and powers.
     ◉ Rewrite:
          $\rule{0pt}{}$
          ○ $2^{n+3}=2^{3}\cdot 2^{n}$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\dfrac{2^{n+3}}{(𝒏+1)^{n}}=2^{3}\cdot \dfrac{2^{n}}{(𝒏+1)^{n}}$
          $\rule{0pt}{}$
     ◉ So:
          $\rule{0pt}{}$
          ○ $\dfrac{2^{n}}{(𝒏+1)^{n}}=\left(\dfrac{2}{𝒏+1}\right)^{n}$


● [1:16:13](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4573). Apply the $𝒏$-th root.
     ◉ We have:
          $\rule{0pt}{}$
          ○ $\sqrt[n]{2^{3}\cdot \left(\dfrac{2}{𝒏+1}\right)^{n}}$
          $\rule{0pt}{}$
     ◉ Separate:
          $\rule{0pt}{}$
          ○ $\sqrt[n]{2^{3}}\cdot \sqrt[n]{\left(\dfrac{2}{𝒏+1}\right)^{n}}$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\sqrt[n]{2^{3}}=(2^{3})^{1/n}$
          $\rule{0pt}{}$
          ○ $\sqrt[n]{\left(\dfrac{2}{𝒏+1}\right)^{n}}=\dfrac{2}{𝒏+1}$


● [1:17:24](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4644). Evaluate the limit.
     ◉ Now:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}(2^{3})^{1/n}\cdot \dfrac{2}{𝒏+1}$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $(2^{3})^{1/n}\to 1$
          $\rule{0pt}{}$
          ○ $\dfrac{2}{𝒏+1}\to 0$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $𝑳=1\cdot 0=0$


● [1:17:48](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4668). Conclusion for the Root Test example.
     ◉ Since:
          $\rule{0pt}{}$
          ○ $𝑳=0$
          $\rule{0pt}{}$
     ◉ And:
          $\rule{0pt}{}$
          ○ $0<1$
          $\rule{0pt}{}$
     ◉ By the Root Test:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n}2^{n+3}}{(𝒏+1)^{n}}$ converges absolutely.






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
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}𝒂_{n}$
          $\rule{0pt}{}$
     ◉ i̲f̲ $\displaystyle \lim_{n\to\infty}𝒂_{n}\ne 0$
     $\rule{0pt}{}$
          ○ t̲h̲e̲n̲ $\displaystyle \sum 𝒂_{n}$ diverges.
          $\rule{0pt}{}$
     ◉ i̲f̲ $\displaystyle \lim_{n\to\infty}𝒂_{n}=0$
     $\rule{0pt}{}$
          ○ t̲h̲e̲n̲ the test is inconclusive.
          ○ continue with another test.

● [1:21:40](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=4900). ❷ — By type.
     ◉ Geometric Series.
          ○ Geometric form:
               $\rule{0pt}{}$
               ■ $\displaystyle \sum 𝒂𝒓^{n}$
               $\rule{0pt}{}$
          ○ i̲f̲ $|𝒓|<1$
               ■ It converges
          ○ i̲f̲ $|𝒓|\ge 1$
               ■ It diverges 
          ○ i̲f̲ it converges, 
               ■ t̲h̲e̲n̲ the sum is:
                    $\rule{0pt}{}$
                    ▣ $\dfrac{𝒂}{1-𝒓}$
                    $\rule{0pt}{}$
          ○ Important:
               ■ check convergence before using the sum formula.
     ◉ Telescoping Series.
          ○ Telescoping series often require:
               ■ partial fractions.
          ○ Main idea:
               ■ rewrite the terms so that many terms cancel.
          ○ Then:
               ■ find a formula for the partial sum $𝑺_{n}$.
          ○ Finally:
               ■ compute $\displaystyle \lim_{n\to\infty}𝑺_{n}$.
     ◉ 𝒑-Series.
          ○ 𝒑-series form:
               $\rule{0pt}{}$
               ■ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{𝒏^{𝒑}}$
               $\rule{0pt}{}$
          ○ i̲f̲ $𝒑>1$
               ■ It converges
          ○ i̲f̲ $𝒑\le 1$
               ■ It diverges
          ○ i̲f̲ $𝒑=1$ 
               ■ gives the harmonic series,
                    ▣ which diverges.

● [1:27:10](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=5230). ❸ — Integral Test.
     ◉ Use the Integral Test when the terms can be modeled by a function:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=𝒇(𝒏)$
          $\rule{0pt}{}$
     ◉ The function must be:
          ○ positive,
          ○ continuous,
          ○ decreasing.
     ◉ This only needs to hold from some point onward:
          $\rule{0pt}{}$
          ○ $[𝑵,\infty)$
          $\rule{0pt}{}$
     ◉ Then evaluate:
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{𝑵}^{\infty}𝒇(𝒙)\cdot 𝒅𝑥$
          $\rule{0pt}{}$
          ○ Meaning of $𝑵$:
               ■ $𝑵$ is the point from which the final tail of the series is tested.
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
               $\rule{0pt}{}$
               ■ $0\le 𝒂_{n}\le 𝒃_{n}$
               $\rule{0pt}{}$
               ■ $\displaystyle \sum 𝒃_{n}$ converges
               $\rule{0pt}{}$
               ■ therefore, $\displaystyle \sum 𝒂_{n}$ converges.
               $\rule{0pt}{}$
          ○ To prove divergence:
               ■ compare with a smaller divergent series.
          ○ Symbolically:
               $\rule{0pt}{}$
               ■ $0\le 𝒃_{n}\le 𝒂_{n}$
               $\rule{0pt}{}$
               ■ $\displaystyle \sum 𝒃_{n}$ diverges
               $\rule{0pt}{}$
               ■ therefore, $\displaystyle \sum 𝒂_{n}$ diverges.
               $\rule{0pt}{}$
     ◉ Limit Comparison Test.
          ○ Use when two positive-term series have similar end behavior.
          ○ Compute:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{n\to\infty}\dfrac{𝒂_{n}}{𝒃_{n}}$
               $\rule{0pt}{}$
          ○ i̲f̲ the limit exists and is a finite positive number: $0<𝑳<\infty$
               ■ t̲h̲e̲n̲ both series have the same convergence behavior.
                    ▣ they both converge or both diverge.

● [1:34:21](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=5661). ❺ — Alternating Series Test.
     ◉ Use when the series has the form:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum (-1)^{n}𝒂_{n}$
          $\rule{0pt}{}$
          ○ or $\displaystyle \sum (-1)^{n-1}𝒂_{n}$
          $\rule{0pt}{}$
     ◉ Where:
          $\rule{0pt}{}$
          ○ $𝒂_{n}>0$
          $\rule{0pt}{}$
     ◉ Check two conditions:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}𝒂_{n}=0$
          $\rule{0pt}{}$
          ○ $𝒂_{n+1}\le 𝒂_{n}$
          $\rule{0pt}{}$
     ◉ i̲f̲ both conditions hold:
          ○ t̲h̲e̲n̲ the alternating series converges.
     ◉ Important:
          ○ this proves ordinary convergence,
          ○ not necessarily absolute convergence.

● [1:36:03](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=5763). ❻ — Ratio Test.
     ◉ Try the Ratio Test for:
          ○ factorials.
          ○ $𝒏$-th powers.
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{𝒂_{n+1}}{𝒂_{n}}\right|$
          $\rule{0pt}{}$
     ◉ i̲f̲
          ○ $𝑳<1$
               ■ t̲h̲e̲n̲ absolutely convergent.
          ○ $𝑳>1$
               ■ t̲h̲e̲n̲ divergent.
          ○ $𝑳=1$
               ■ t̲h̲e̲n̲ inconclusive.

● [1:37:09](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=5829). ❼ — Root Test.
     ◉ Try the Root Test for:
          ○ $𝒏$-th powers.
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\sqrt[n]{|𝒂_{n}|}$
          $\rule{0pt}{}$
     ◉ i̲f̲
          ○ $𝑳<1$
               ■ t̲h̲e̲n̲ absolutely convergent.
          ○ $𝑳>1$
               ■ t̲h̲e̲n̲ divergent.
          ○ $𝑳=1$
               ■ t̲h̲e̲n̲ inconclusive.






6 - Ｑｕｉｃｋ　Ｉｄｅｎｔｉｆｉｃａｔｉｏｎ　Ｇｕｉｄｅ


● [📷image-1](../img/Calculus 2 Lecture 9.6/[1-40-19]-01.png) [📷image-2](../img/Calculus 2 Lecture 9.6/[1-40-19]-02.png)

● [1:40:19](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=6019). ❶ Always start by looking for immediate divergence:
     ◉ if $\displaystyle \lim_{n\to\infty}𝒂_{n}\ne 0$,
     $\rule{0pt}{}$
          ○ stop.
          ○ the series diverges.
     ◉ ⭐ Model Example:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{2𝒏-1}{3𝒏-1}$
          $\rule{0pt}{}$
     ◉ Check the general term:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{2𝒏-1}{3𝒏-1}=\dfrac{2}{3}$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\dfrac{2}{3}\ne 0$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ the series diverges by the Divergence Test.


● [1:40:57](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=6057). ❷ Split sums when possible.
     ◉ If a series is written as a sum or difference of recognizable series,
          ○ split it.
     ◉ ⭐ Model Example:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left[\dfrac{2}{3^{n}}-\dfrac{1}{𝒏(𝒏+1)}\right]$
          $\rule{0pt}{}$
     ◉ Split:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{2}{3^{n}}-\sum_{n=1}^{\infty}\dfrac{1}{𝒏(𝒏+1)}$
          $\rule{0pt}{}$
     ◉ First part:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{2}{3^{n}}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \sum_{n=1}^{\infty}2\left(\dfrac{1}{3}\right)^{n}$
          $\rule{0pt}{}$
          ○ geometric series with $|𝒓|=\dfrac{1}{3}<1$
          $\rule{0pt}{}$
          ○ therefore, it converges.
     ◉ Second part:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{𝒏(𝒏+1)}$
          $\rule{0pt}{}$
          ○ telescoping series.
     ◉ Therefore:
          ○ analyze each part separately.
     ◉ The whole series converges only if all parts converge.

● [1:41:36](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=6096). ❸ Look for 𝒑-Series.
     ◉ If the expression can be rewritten as:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{𝒏^{𝒑}}$
          $\rule{0pt}{}$
     ◉ Then:
          ○ use the 𝒑-Series Test.
     ◉ ⭐ Model Example:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left(\dfrac{1}{𝒏}\right)^{𝒆}$
          $\rule{0pt}{}$
     ◉ Rewrite:
          $\rule{0pt}{}$
          ○ $\left(\dfrac{1}{𝒏}\right)^{𝒆}=\dfrac{1}{𝒏^{𝒆}}$
          $\rule{0pt}{}$
     ◉ This is a 𝒑-series with:
          $\rule{0pt}{}$
          ○ $𝒑=𝒆$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $𝒆>1$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{𝒏^{𝒆}}$ converges.


● [1:42:05](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=6125). ❹ Integral Test versus Comparison.
     ◉ Use the Integral Test when:
          ○ the function is easy to integrate,
          ○ and positive, continuous, decreasing.
     ◉ ⭐ Model Example:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=3}^{\infty}\dfrac{1}{𝒏\sqrt{\ln(𝒏)}}$
          $\rule{0pt}{}$
     ◉ Model with:
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\dfrac{1}{𝒙\sqrt{\ln(𝒙)}}$
          $\rule{0pt}{}$
     ◉ This suggests the Integral Test because:
          ○ the function is positive for $𝒙\ge 3$.
          ○ it is continuous for $𝒙\ge 3$.
          ○ it is decreasing for large $𝒙$.
          ○ the integral is manageable by substitution.
     ◉ Integral idea:
          $\rule{0pt}{}$
          ○ let $𝒖=\ln(𝒙)$
          $\rule{0pt}{}$
          ○ then $𝒅𝒖=\dfrac{1}{𝒙}\cdot 𝒅𝑥$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ use the Integral Test.

● [1:42:38](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=6158). ❺ Direct Comparison for single dominant terms.
     ◉ If the expression has simple single-term behavior,
          ○ Direct Comparison may be easiest.
     ◉ ⭐ Model Example:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=3}^{\infty}\dfrac{\ln(𝒏)}{𝒏^{2}}$
          $\rule{0pt}{}$
     ◉ Single-term comparison idea:
          ○ $\ln(𝒏)$ grows slower than $\sqrt{𝒏}$.
     ◉ So for large $𝒏$:
          $\rule{0pt}{}$
          ○ $\ln(𝒏)<\sqrt{𝒏}$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\dfrac{\ln(𝒏)}{𝒏^{2}}<\dfrac{\sqrt{𝒏}}{𝒏^{2}}$
          $\rule{0pt}{}$
     ◉ Simplify:
          $\rule{0pt}{}$
          ○ $\dfrac{\sqrt{𝒏}}{𝒏^{2}}=\dfrac{1}{𝒏^{3/2}}$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=3}^{\infty}\dfrac{1}{𝒏^{3/2}}$ is a 𝒑-series with $𝒑=\dfrac{3}{2}>1$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=3}^{\infty}\dfrac{1}{𝒏^{3/2}}$ converges.
          $\rule{0pt}{}$
     ◉ By Direct Comparison:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=3}^{\infty}\dfrac{\ln(𝒏)}{𝒏^{2}}$ converges.


● [1:43:23](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=6203). ❻ Limit Comparison for multiple-term expressions.
     ◉ If the numerator or denominator has several terms,
          ○ Direct Comparison may be awkward.
     ◉ Then:
          ○ use leading terms.
     ◉ ⭐ Model Example:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{\sqrt{𝒏^{3}-2}}{𝒏^{4}+3𝒏^{2}+1}$
          $\rule{0pt}{}$
     ◉ End behavior:
     $\rule{0pt}{}$
          ○ $\sqrt{𝒏^{3}-2}$ behaves like $\sqrt{𝒏^{3}}=𝒏^{3/2}$
          $\rule{0pt}{}$
          ○ $𝒏^{4}+3𝒏^{2}+1$ behaves like $𝒏^{4}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\dfrac{\sqrt{𝒏^{3}-2}}{𝒏^{4}+3𝒏^{2}+1}$ behaves like $\dfrac{𝒏^{3/2}}{𝒏^{4}}$
          $\rule{0pt}{}$
     ◉ Simplify:
          $\rule{0pt}{}$
          ○ $\dfrac{𝒏^{3/2}}{𝒏^{4}}=\dfrac{1}{𝒏^{5/2}}$
          $\rule{0pt}{}$
     ◉ Choose:
          $\rule{0pt}{}$
          ○ $𝒃_{n}=\dfrac{1}{𝒏^{5/2}}$
          $\rule{0pt}{}$
     ◉ Then compute:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{𝒂_{n}}{𝒃_{n}}$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{𝒏^{5/2}}$ is a 𝒑-series with $𝒑=\dfrac{5}{2}>1$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ use the Limit Comparison Test.
          ○ the given series converges if the comparison limit is finite and positive.


● [1:44:15](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=6255). ❼ Alternating series.
     ◉ If the series clearly has:
          ○ $(-1)^{n}$
          ○ or $(-1)^{n-1}$
     ◉ Then:
          ○ try the Alternating Series Test.
     ◉ ⭐ Model Example:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}(-1)^{n}\dfrac{\sqrt{𝒏}}{𝒏^{2}+1}$
          $\rule{0pt}{}$
     ◉ Positive part:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{\sqrt{𝒏}}{𝒏^{2}+1}$
          $\rule{0pt}{}$
     ◉ Check:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}𝒂_{n}=0$
          $\rule{0pt}{}$
     ◉ Reason:
     $\rule{0pt}{}$
          ○ $\dfrac{\sqrt{𝒏}}{𝒏^{2}+1}$ behaves like $\dfrac{\sqrt{𝒏}}{𝒏^{2}}=\dfrac{1}{𝒏^{3/2}}$
          $\rule{0pt}{}$
          ○ and $\dfrac{1}{𝒏^{3/2}}\to 0$
          $\rule{0pt}{}$
     ◉ Then check decreasing:
          ○ $𝒂_{n+1}\le 𝒂_{n}$
          ○ or use $𝒇'(𝒙)<0$ for the related function.
     ◉ Therefore:
          ○ try the Alternating Series Test.

● [1:44:33](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=6273). ❽ Ratio Test or Root Test.
     ◉ Use these when:
          ○ other tests are not convenient,
          ○ the expression has factorials,
          ○ or $𝒏$-th powers.
     ◉ ⭐ Model Example:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{𝒏}{2^{n}}$
          $\rule{0pt}{}$
     ◉ This is not directly geometric:
          ○ because of the extra factor $𝒏$ in the numerator.
     ◉ (i) Use the Ratio Test:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{𝒏}{2^{n}}$
          $\rule{0pt}{}$
          ○ $𝒂_{n+1}=\dfrac{𝒏+1}{2^{n+1}}$
          $\rule{0pt}{}$
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{𝒂_{n+1}}{𝒂_{n}}\right|$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{n\to\infty}\dfrac{𝒏+1}{2^{n+1}}\cdot \dfrac{2^{n}}{𝒏}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{n\to\infty}\dfrac{𝒏+1}{𝒏}\cdot \dfrac{1}{2}$
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{2}$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $𝑳=\dfrac{1}{2}<1$
          $\rule{0pt}{}$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{𝒏}{2^{n}}$ converges by the Ratio Test.
          $\rule{0pt}{}$
     ◉ (ii) Root Test also works.
     ◉ Given:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{𝒏}{2^{n}}$
          $\rule{0pt}{}$
     ◉ Rewrite the numerator:
          $\rule{0pt}{}$
          ○ $𝒏=𝒏^{1}$
          $\rule{0pt}{}$
          ○ $𝒏^{1}=𝒏^{n/n}$
          $\rule{0pt}{}$
          ○ $𝒏^{n/n}=(𝒏^{1/n})^{n}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\dfrac{𝒏}{2^{n}}=\dfrac{(𝒏^{1/n})^{n}}{2^{n}}$
          $\rule{0pt}{}$
          ○ $=\left(\dfrac{𝒏^{1/n}}{2}\right)^{n}$
          $\rule{0pt}{}$
     ◉ Apply the Root Test:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\sqrt[n]{\left|\dfrac{𝒏}{2^{n}}\right|}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{n\to\infty}\sqrt[n]{\left(\dfrac{𝒏^{1/n}}{2}\right)^{n}}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{n\to\infty}\dfrac{𝒏^{1/n}}{2}$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}𝒏^{1/n}=1$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $𝑳=\dfrac{1}{2}$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $𝑳=\dfrac{1}{2}<1$
          $\rule{0pt}{}$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{𝒏}{2^{n}}$ converges by the Root Test.


● [1:45:12](https://www.youtube.com/watch?v=g4iZJOwMkjU&t=6312). ❾ Strategy for trigonometric functions.
     ◉ If the series contains:
          ○ $\sin(𝒏)$,
          ○ $\cos(𝒏)$,
          ○ $\sin(2𝒏)$,
          ○ or similar oscillating terms,
     ◉ Then:
          ○ it may not be positive,
          ○ and may not alternate regularly.
     ◉ ⭐ Model Example:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{\sin(𝒏)}{\sqrt{𝒏^{3}+1}}$
          $\rule{0pt}{}$
     ◉ In that case:
          ○ try absolute value.
     ◉ Take:
          $\rule{0pt}{}$
          ○ $\left|\dfrac{\sin(𝒏)}{\sqrt{𝒏^{3}+1}}\right|$
          $\rule{0pt}{}$
          ○ $=\dfrac{|\sin(𝒏)|}{\sqrt{𝒏^{3}+1}}$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $|\sin(𝒏)|\le 1$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\dfrac{|\sin(𝒏)|}{\sqrt{𝒏^{3}+1}}\le \dfrac{1}{\sqrt{𝒏^{3}+1}}$
          $\rule{0pt}{}$
     ◉ End behavior:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{\sqrt{𝒏^{3}+1}}$ behaves like $\dfrac{1}{𝒏^{3/2}}$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{𝒏^{3/2}}$ converges
          $\rule{0pt}{}$
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
          $\rule{0pt}{}$
          ○ $\dfrac{1}{𝒏^{𝒑}}$ form ⇒ 𝒑-Series.
          $\rule{0pt}{}$
          ○ positive continuous decreasing function ⇒ Integral Test.
          ○ positive terms like a known series ⇒ Comparison.
          ○ alternating signs ⇒ Alternating Series Test.
          ○ factorials ⇒ Ratio Test.
          ○ $𝒏$-th powers ⇒ Root Test.
          ○ trig oscillation ⇒ absolute value plus comparison.






Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Absolute Convergence. Prof. Herbert Gross.
     ◉ [MIT 🌐](https://ocw.mit.edu/courses/res-18-006-calculus-revisited-single-variable-calculus-fall-2010/resources/lecture-3-absolute-convergence/)

● Ratio and Root Tests.
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/5-6-ratio-and-root-tests)