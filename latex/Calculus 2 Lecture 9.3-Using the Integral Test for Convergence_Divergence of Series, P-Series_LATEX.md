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
          $\rule{0pt}{}$
          ○ $𝒂_{1}+𝒂_{2}+𝒂_{3}+\cdots$
          $\rule{0pt}{}$
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
          $\rule{0pt}{}$
          ○ $𝒂_{n}=𝒇(𝒏)$
          $\rule{0pt}{}$
     ◉ To apply the Integral Test, $𝒇(𝒙)$ must be:
          ○ ❶ Continuous
               ■ The function must be continuous on the interval. Meaning:
                    ▣ no breaks.
                    ▣ no jumps.
                    ▣ no vertical asymptotes inside the interval.
          ○ ❷ Positive
               ■ The function must be positive on the interval. Meaning:
                    $\rule{0pt}{}$
                    ▣ $𝒇(𝒙)>0$
                    $\rule{0pt}{}$
               ■ This matches the idea of adding positive terms in the series.
          ○ ❸ Decreasing
               ■ The function must be decreasing on the interval. Meaning:
                    ▣ as $𝒙$ increases, $𝒇(𝒙)$ gets smaller.
               ■ If decreasing is not obvious,
                    ▣ use the first derivative.
               ■ If:
                    $\rule{0pt}{}$
                    ▣ $𝒇'(𝒙)<0$
                    $\rule{0pt}{}$
               ■ Then:
                    ▣ $𝒇(𝒙)$ is decreasing.
     ◉ These conditions must hold on the interval being tested:
          ○ usually $[1,\infty)$
          ○ or sometimes $[𝑵,\infty)$, if the first few terms cause problems.

● [2:39](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=159). Formal statement of the Integral Test. [📷image](../img/Calculus 2 Lecture 9.3/[2-39]-01.png)
     ◉ Suppose:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=𝒇(𝒏)$
          $\rule{0pt}{}$
     ◉ If $𝒇(𝒙)$ is:
          ○ continuous,
          ○ positive,
          ○ and decreasing
     ◉ on $[1,\infty)$, then:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty} 𝒂_{n}$ and $\displaystyle \int_{1}^{\infty} 𝒇(𝒙)\cdot 𝒅𝑥$ have the same convergence behavior.


● N̲O̲T̲E̲ 2: Relationship between the series and the improper integral.
$\rule{0pt}{}$
     ◉ i̲f̲   $\displaystyle \int_{1}^{\infty} 𝒇(𝒙)\cdot 𝒅𝑥$ converges,
     $\rule{0pt}{}$
          ○ t̲h̲e̲n̲  $\displaystyle \sum_{𝒏=1}^{\infty} 𝒂_{n}$ converges.
          $\rule{0pt}{}$
     ◉ i̲f̲  $\displaystyle \int_{1}^{\infty} 𝒇(𝒙)\cdot 𝒅𝑥$ diverges,
     $\rule{0pt}{}$
          ○ t̲h̲e̲n̲ $\displaystyle \sum_{𝒏=1}^{\infty} 𝒂_{n}$ diverges.
          $\rule{0pt}{}$
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
$\rule{0pt}{}$
     ◉ If $\displaystyle \int_{1}^{\infty} 𝒇(𝒙)\cdot 𝒅𝑥=𝑳$
          ○ This does not mean $\displaystyle \sum_{𝒏=1}^{\infty} 𝒂_{n}=𝑳$
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
     ◉ Sometimes $𝒇(𝒙)$ is not decreasing from $𝒏=1$.
     ◉ But if $𝒇(𝒙)$ becomes decreasing after some point,
          ○ we can start the integral at that later point.
     ◉ Example:
          ○ instead of starting at $1$,
          ○ we may start at $3$, $5$, $7$, or another suitable integer.
     ◉ Reason:
          ○ removing finitely many terms does not affect convergence.




          

Ｅｘａｍｐｌｅｓ　Ｕｓｉｎｇ　ｔｈｅ　Ｉｎｔｅｇｒａｌ　Ｔｅｓｔ

Ｅｘａｍｐｌｅ   1  

● [📷image](../img/Calculus 2 Lecture 9.3/[10-30]-01.png)

● [10:30](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=630). 🧩 Example 1 — Determining convergence for $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{1}{𝒏^{2}+1}$.
     ◉ Given series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{1}{𝒏^{2}+1}$
          $\rule{0pt}{}$
     ◉ First check the Divergence Test:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{1}{𝒏^{2}+1}=0$
          $\rule{0pt}{}$
     ◉ Since the limit is $0$:
          ○ **the Divergence Test is inconclusive.**
          ○ we must use another test.

● [12:22](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=742). Applying the Integral Test to Example 1.
     ◉ Define:
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\dfrac{1}{𝒙^{2}+1}$
          $\rule{0pt}{}$
     ◉ Check the conditions on $[1,\infty)$:
          ○ $𝒇(𝒙)$ is positive.
          ○ $𝒇(𝒙)$ is continuous.
          ○ $𝒇(𝒙)$ is decreasing.
     ◉ Therefore:
          ○ the Integral Test can be applied.

● [13:40](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=820). Applying the Integral Test to a variant of Example 1: $𝒇(𝒙)=\dfrac{1}{𝒙^{2}-1}$
     ◉ Check the conditions on $[1,\infty)$:
          ○ $𝒇(𝒙)$ is not continuous at $𝒙=1$,
               ■ because $𝒙^{2}-1=0$ when $𝒙=1$.
          ○ therefore, we cannot use the interval $[1,\infty)$.
     ◉ Can we subtract a finite number of terms?
          ○ Yes.
          ○ convergence is not affected by removing finitely many terms.
     ◉ So we adjust the starting interval:
          ○ instead of $[1,\infty)$,
               ■ use $[2,\infty)$.
     ◉ Check the conditions on $[2,\infty)$:
          ○ $𝒇(𝒙)$ is positive.
          ○ $𝒇(𝒙)$ is continuous.
          ○ $𝒇(𝒙)$ is decreasing.
     ◉ Therefore:
          ○ the Integral Test can be applied on $[2,\infty)$.

● [14:22](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=862). Solving the improper integral in Example 1.
     ◉ Set up the integral:
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{1}^{\infty}\dfrac{1}{𝒙^{2}+1}\cdot 𝒅𝑥$
          $\rule{0pt}{}$
     ◉ Rewrite as an improper integral:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{b\to\infty}\int_{1}^{b}\dfrac{1}{𝒙^{2}+1}\cdot 𝒅𝑥$
          $\rule{0pt}{}$
     ◉ Antiderivative:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{𝒙^{2}+1}\cdot 𝒅𝑥=\tan^{-1}(𝒙)$

● [16:42](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1002). Evaluating the limit in Example 1.
     ◉ Evaluate:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{b\to\infty}\Big[\tan^{-1}(𝒙)\Big]_{1}^{b}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{b\to\infty}\Big[\tan^{-1}(b)-\tan^{-1}(1)\Big]$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{b\to\infty}\tan^{-1}(b)=\dfrac{\pi}{2}$
          $\rule{0pt}{}$
          ○ $\tan^{-1}(1)=\dfrac{\pi}{4}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\dfrac{\pi}{2}-\dfrac{\pi}{4}=\dfrac{\pi}{4}$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ the improper integral converges.

● [18:00](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1080). Conclusion for Example 1.
     ◉ Since the limit exists the improper integral converges,
     $\rule{0pt}{}$
          ○ the series $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{1}{𝒏^{2}+1}$ and the integral converge.
     ◉ Important:
     $\rule{0pt}{}$
          ○ $\dfrac{\pi}{4}$ is the value of the integral.
          $\rule{0pt}{}$
          ○ it is not necessarily the sum of the series.
          

Ｅｘａｍｐｌｅ   2 

● [📷image](../img/Calculus 2 Lecture 9.3/[19-34]-01.png)

● [19:34](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1174). 🧩 Example 2 — Analyzing $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{3}{2𝒏-1}$.
     ◉ Given series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{3}{2𝒏-1}$
          $\rule{0pt}{}$
     ◉ First check the Divergence Test:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{3}{2𝒏-1}=0$
          $\rule{0pt}{}$
     ◉ Since the limit is $0$:
          ○ **the Divergence Test is inconclusive.**
          ○ we must continue.

● [20:12](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1212). Applying the Integral Test to Example 2.
     ◉ Define:
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\dfrac{3}{2𝒙-1}$
          $\rule{0pt}{}$
     ◉ Check the conditions on $[1,\infty)$:
          ○ $𝒇(𝒙)$ is positive.
          ○ $𝒇(𝒙)$ is continuous.
          ○ $𝒇(𝒙)$ is decreasing.
     ◉ Therefore:
          ○ the Integral Test can be applied.

● [21:00](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1260). Solving the improper integral in Example 2.
     ◉ Set up:
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{1}^{\infty}\dfrac{3}{2𝒙-1}\cdot 𝒅𝑥$
          $\rule{0pt}{}$
     ◉ Rewrite as an improper integral:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{b\to\infty}\int_{1}^{b}\dfrac{3}{2𝒙-1}\cdot 𝒅𝑥$
          $\rule{0pt}{}$
     ◉ Use substitution:
          $\rule{0pt}{}$
          ○ $𝒖=2𝒙-1$
          $\rule{0pt}{}$
          ○ $d𝒖=2\cdot 𝒅𝑥$
          $\rule{0pt}{}$
          ○ $𝒅𝑥=\dfrac{d𝒖}{2}$
          $\rule{0pt}{}$
     ◉ Antiderivative:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{3}{2𝒙-1}\cdot 𝒅𝑥=\dfrac{3}{2}\ln|2𝒙-1|$

● [22:25](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1345). Evaluating the limit in Example 2.
     ◉ Evaluate:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{b\to\infty}\Big[\dfrac{3}{2}\ln(2𝒙-1)\Big]_{1}^{b}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{b\to\infty}\Big[\dfrac{3}{2}\ln(2b-1)-\dfrac{3}{2}\ln(1)\Big]$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\ln(1)=0$
          $\rule{0pt}{}$
          ○ $\ln(2b-1)\to\infty$ as $b\to\infty$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ the improper integral diverges.

● [25:15](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1515). Conclusion for Example 2.
     ◉ Since the improper integral diverges,
     $\rule{0pt}{}$
          ○ the series $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{3}{2𝒏-1}$ diverges.
          

Ｅｘａｍｐｌｅ  3

● [📷image-1](../img/Calculus 2 Lecture 9.3/[26-15]-01.png) [📷image-2](../img/Calculus 2 Lecture 9.3/[26-15]-02.png)

● [26:15](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1575). 🧩 Example 3 — The case of $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{\ln(𝒏)}{𝒏}$.
     ◉ Given series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{\ln(𝒏)}{𝒏}$
          $\rule{0pt}{}$
     ◉ First check the Divergence Test:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{\ln(𝒏)}{𝒏}=0$
          $\rule{0pt}{}$
     ◉ Since the limit is $0$:
          ○ the Divergence Test is inconclusive.
     ◉ Define $𝒇(𝒙)$ as a model of theseries:
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\dfrac{\ln(𝒙)}{𝒙}$

● [28:10](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1690). Checking decreasing behavior for Example 3.
     ◉ To prove decreasing,
          ○ take the derivative.
     ◉ Differentiate:
          $\rule{0pt}{}$
          ○ $\dfrac{d}{d𝒙}\left[\dfrac{\ln(𝒙)}{𝒙}\right]=\dfrac{1-\ln(𝒙)}{𝒙^{2}}$
          $\rule{0pt}{}$
     ◉ We need:
          $\rule{0pt}{}$
          ○ $𝒇'(𝒙)\le 0$
          $\rule{0pt}{}$
     ◉ Since $𝒙^{2}>0$,
          ○ the sign depends on $1-\ln(𝒙)$.
     ◉ [29:40](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1780). Sign analysis for Example 3.
          ○ The derivative is non-positive when:
               $\rule{0pt}{}$
               ■ $1-\ln(𝒙)\le 0$
               $\rule{0pt}{}$
          ○ This means:
               $\rule{0pt}{}$
               ■ $1\le \ln(𝒙)$
               $\rule{0pt}{}$
               ■ $𝒆\le 𝒙$
               $\rule{0pt}{}$
          ○ Therefore:
               ■ $𝒇(𝒙)$ is decreasing for $𝒙\ge 𝒆$.
          ○ Since:
               ■ $3>𝒆$
          ○ We can use the interval:
               ■ $[3,\infty)$
          ○  N̲O̲T̲E̲ — Strictly decreasing versus non-increasing.
               ■ If $𝒇'(𝒙)<0$
                    ▣ Then $𝒇(𝒙)$ is strictly decreasing.
                    ▣ This means the function is always going down
               ■ If $𝒇'(𝒙)\le 0$
                    ▣ Then $𝒇(𝒙)$ is decreasing / non-increasing.  
                    ▣ This means the function does not go up.
                    ▣ it may go down,
                         ▢ or it may stay flat at isolated points.
               ■ For the Integral Test:
                    ▣ non-increasing behavior is enough.
                    ▣ so using $𝒇'(𝒙)\le 0$ is valid.
              
● [31:07](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=1867). Adjusting the lower limit in Example 3.
     ◉ The original series starts at $𝒏=1$.
     ◉ But the function is guaranteed to be decreasing from $𝒙=3$ onward.
     ◉ This is allowed because:
          ○ removing finitely many terms does not affect convergence.
     ◉ Therefore:
          ○ use the integral from $3$ to $\infty$.

● [36:42](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=2202). Solving the improper integral in Example 3.
     ◉ Set up:
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{3}^{\infty}\dfrac{\ln(𝒙)}{𝒙}\cdot 𝒅𝑥$
          $\rule{0pt}{}$
     ◉ Rewrite as an improper integral:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{b\to\infty}\int_{3}^{b}\dfrac{\ln(𝒙)}{𝒙}\cdot 𝒅𝑥$
          $\rule{0pt}{}$
     ◉ Use substitution:
          $\rule{0pt}{}$
          ○ $𝒖=\ln(𝒙)$
          $\rule{0pt}{}$
          ○ $d𝒖=\dfrac{1}{𝒙}\cdot 𝒅𝑥$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{\ln(𝒙)}{𝒙}\cdot 𝒅𝑥=\dfrac{[\ln(𝒙)]^{2}}{2}$

● [38:41](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=2321). Conclusion for Example 3.
     ◉ Evaluate:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{b\to\infty}\Big[\dfrac{[\ln(𝒙)]^{2}}{2}\Big]_{3}^{b}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{b\to\infty}\left(\dfrac{[\ln(b)]^{2}}{2}-\dfrac{[\ln(3)]^{2}}{2}\right)$
          $\rule{0pt}{}$
     ◉ Since:
          ○ $\ln(b)\to\infty$ as $b\to\infty$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\dfrac{[\ln(b)]^{2}}{2}\to\infty$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ the improper integral diverges.
     ◉ Since the improper integral diverges,
     $\rule{0pt}{}$
          ○ the series $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{\ln(𝒏)}{𝒏}$ diverges.



          

𝒑－Ｓｅｒｉｅｓ

● [📷image](../img/Calculus 2 Lecture 9.3/[41-16]-01.png)

● [41:16](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=2476). Introduction to 𝒑-Series.
     ◉ A 𝒑-series has the form:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{1}{𝒏^{𝒑}}$
          $\rule{0pt}{}$
     ◉ Here:
          ○ $𝒏$ is the changing index.
          ○ $𝒑$ is a fixed exponent.

● General form of a 𝒑-series.
     ◉ The series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{1}{𝒏^{𝒑}}$
          $\rule{0pt}{}$
     ◉ Expands as:
          $\rule{0pt}{}$
          ○ $1+\dfrac{1}{2^{𝒑}}+\dfrac{1}{3^{𝒑}}+\dfrac{1}{4^{𝒑}}+\cdots$
          $\rule{0pt}{}$
     ◉ Important:
          ○ $𝒑$ does not change.
          ○ only $𝒏$ changes.

● [43:25](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=2605). Convergence and divergence rules for 𝒑-Series.
     ◉ 𝒑-series rule:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{1}{𝒏^{𝒑}}$ converges if $𝒑>1$.
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{1}{𝒏^{𝒑}}$ diverges if $𝒑\le 1$.
          $\rule{0pt}{}$
     ◉ Special case:
          ○ when $𝒑=1$,
          $\rule{0pt}{}$
               ■ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{1}{𝒏}$ is **the harmonic series.**
               $\rule{0pt}{}$
               ■ the harmonic series diverges.

● [49:41](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=2981). 🧩 Example — 𝒑-Series: $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{1}{𝒏^{2}}$ [📷image](../img/Calculus 2 Lecture 9.3/[49-41]-01.png)
     ◉ Here:
          ○ $𝒑=2$
     ◉ Since:
          ○ $2>1$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{1}{𝒏^{2}}$ converges.

● [50:55](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=3055). 🧩 Example — 𝒑-Series: $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{1}{\sqrt[3]{𝒏}}$ [📷image](../img/Calculus 2 Lecture 9.3/[50-55]-01.png)
     ◉ Rewrite:
          $\rule{0pt}{}$
          ○ $\sqrt[3]{𝒏}=𝒏^{1/3}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{1}{\sqrt[3]{𝒏}}=\sum_{𝒏=1}^{\infty}\dfrac{1}{𝒏^{1/3}}$
          $\rule{0pt}{}$
     ◉ Here:
     $\rule{0pt}{}$
          ○ $𝒑=\dfrac{1}{3}$
          $\rule{0pt}{}$
     ◉ Since:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{3}<1$
          $\rule{0pt}{}$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{1}{\sqrt[3]{𝒏}}$ diverges.


● [52:11](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=3131). 🧩 Example — 𝒑-Series: $\displaystyle \sum_{𝒏=1}^{\infty} 𝒏^{-\pi}$ [📷image](../img/Calculus 2 Lecture 9.3/[52-11]-01.png)
     ◉ Rewrite:
          $\rule{0pt}{}$
          ○ $𝒏^{-\pi}=\dfrac{1}{𝒏^{\pi}}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty} 𝒏^{-\pi}=\sum_{𝒏=1}^{\infty}\dfrac{1}{𝒏^{\pi}}$
          $\rule{0pt}{}$
     ◉ Here:
          ○ $𝒑=\pi$
     ◉ Since:
          ○ $\pi>1$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty} 𝒏^{-\pi}$ converges.


● [56:33](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=3393). Important note about recognizing 𝒑-Series.
     ◉ A 𝒑-series must have the form:
          $\rule{0pt}{}$
          ○ constant / $𝒏^{𝒑}$
     ◉ It cannot have extra terms added in the denominator.
     ◉ Example:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{1}{𝒏^{7}+1}$
          $\rule{0pt}{}$
     ◉ This is not directly a 𝒑-series.
     ◉ However:
          ○ it can later be compared to a 𝒑-series.
     ◉ **This leads to the Comparison Test.**



     

Ａｄｖａｎｃｅｄ　Ｉｎｔｅｇｒａｌ　Ｔｅｓｔ　Ｅｘａｍｐｌｅ

● [57:45](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=3465). 🧩 Advanced Example — :$\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{𝒆^{1/𝒏}}{𝒏^{2}}$. [📷image](../img/Calculus 2 Lecture 9.3/[57-45]-01.png)
     ◉ Given series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{𝒆^{1/𝒏}}{𝒏^{2}}$
          $\rule{0pt}{}$
     ◉ First check the Divergence Test:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{𝒆^{1/𝒏}}{𝒏^{2}}=0$
          $\rule{0pt}{}$
     ◉ Since the limit is $0$:
          ○ the Divergence Test is inconclusive.
     ◉ This is not geometric:
          ○ because the changing variable is not a constant raised to the $𝒏$.
     ◉ This is not a 𝒑-series:
          ○ because the numerator is not constant.
     ◉ Therefore:
          ○ try the Integral Test.

● [1:00:25](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=3625). Validating the Integral Test conditions for the advanced example.
     ◉ Define:
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\dfrac{𝒆^{1/𝒙}}{𝒙^{2}}$
          $\rule{0pt}{}$
     ◉ Check positivity:
     $\rule{0pt}{}$
          ○ $𝒆^{1/𝒙}$ is positive.
          $\rule{0pt}{}$
          ○ $𝒙^{2}$ is positive for $𝒙\ge 1$.
          $\rule{0pt}{}$
          ○ therefore, $𝒇(𝒙)$ is positive.
          $\rule{0pt}{}$
     ◉ Check continuity:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒆^{1/𝒙}}{𝒙^{2}}$ is continuous on $[1,\infty)$.
          $\rule{0pt}{}$
     ◉ Check decreasing:
          ○ use the first derivative.

● [1:01:09](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=3669). Showing decreasing behavior in the advanced example.
     ◉ Differentiate:
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\dfrac{𝒆^{1/𝒙}}{𝒙^{2}}$
          $\rule{0pt}{}$
     ◉ Using the quotient rule:
          $\rule{0pt}{}$
          ○ $𝒇'(𝒙)=\dfrac{-𝒆^{1/𝒙}\cdot (1+2𝒙)}{𝒙^{4}}$
          $\rule{0pt}{}$
     ◉ Sign analysis:
          ○ $𝒆^{1/𝒙}>0$
          ○ $1+2𝒙>0$ for $𝒙\ge 1$
          ○ $𝒙^{4}>0$
     ◉ Because of the negative sign:
          $\rule{0pt}{}$
          ○ $𝒇'(𝒙)<0$ on $[1,\infty)$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ $𝒇(𝒙)$ is decreasing on $[1,\infty)$.

● [1:07:22](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=4042). Solving the integral in the advanced example.
     ◉ Set up:
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{1}^{\infty}\dfrac{𝒆^{1/𝒙}}{𝒙^{2}}\cdot 𝒅𝑥$
          $\rule{0pt}{}$
     ◉ Rewrite as an improper integral:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{b\to\infty}\int_{1}^{b}\dfrac{𝒆^{1/𝒙}}{𝒙^{2}}\cdot 𝒅𝑥$
          $\rule{0pt}{}$
     ◉ Use substitution:
          $\rule{0pt}{}$
          ○ $𝒖=\dfrac{1}{𝒙}$
          $\rule{0pt}{}$
          ○ $d𝒖=-\dfrac{1}{𝒙^{2}}\cdot 𝒅𝑥$
          $\rule{0pt}{}$
          ○ $-d𝒖=\dfrac{1}{𝒙^{2}}\cdot 𝒅𝑥$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{𝒆^{1/𝒙}}{𝒙^{2}}\cdot 𝒅𝑥=-𝒆^{1/𝒙}$

● [1:09:48](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=4188). Evaluating the advanced example.
     ◉ Evaluate:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{b\to\infty}\Big[-𝒆^{1/𝒙}\Big]_{1}^{b}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{b\to\infty}\Big[-𝒆^{1/b}-(-𝒆^{1})\Big]$
          $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{b}\to 0$ as $b\to\infty$
          $\rule{0pt}{}$
          ○ $𝒆^{1/b}\to 𝒆^{0}=1$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $-𝒆^{1/b}+𝒆\to -1+𝒆$
          $\rule{0pt}{}$
          ○ $=𝒆-1$
          $\rule{0pt}{}$
     ◉ The improper integral converges.

● [1:10:22](https://www.youtube.com/watch?v=8jPpNK4GIVs&t=4222). Final conclusion for the advanced example.
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{1}^{\infty}\dfrac{𝒆^{1/𝒙}}{𝒙^{2}}\cdot 𝒅𝑥=𝒆-1$
          $\rule{0pt}{}$
     ◉ The improper integral converges.
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{𝒏=1}^{\infty}\dfrac{𝒆^{1/𝒏}}{𝒏^{2}}$ converges by the Integral Test.
          $\rule{0pt}{}$
     ◉ Important:
          ○ $𝒆-1$ is the value of the integral.
          ○ it is not necessarily the sum of the series.




Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● The 𝒑-Series and The Integral Test
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/5-3-the-divergence-and-integral-tests)