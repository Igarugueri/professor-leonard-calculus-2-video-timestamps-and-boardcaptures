 -----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ９．２  -  Ｓｅｒｉｅｓ， Ｇｅｏｍｅｔｒｉｃ Ｓｅｒｉｅｓ， Ｈａｒｍｏｎｉｃ Ｓｅｒｉｅｓ， ａｎｄ Ｄｉｖｅｒｇｅｎｃｅ Ｔｅｓｔ**------------------------------—





Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:01](https://www.youtube.com/watch?v=DGcWMdW-72M&t=1). Conceptual transition — From sequences to series. [📷image](../img/Calculus 2 Lecture 9.2/[0-01]-01.png)
     ◉ A sequence lists terms.
     ◉ A series adds those terms together.
     ◉ Main idea:
          ○ If we take the terms of a sequence and add them, we obtain a series




          

Ｓｉｇｍａ　Ｎｏｔａｔｉｏｎ　＆　Ｐａｒｔｉａｌ　Ｓｕｍｓ

● [📷image](../img/Calculus 2 Lecture 9.2/[1-01]-01.png)

● [1:01](https://www.youtube.com/watch?v=DGcWMdW-72M&t=61). Introduction to Sigma notation.
     ◉ A series is obtained by adding the terms of a sequence.
     ◉ Basic form:
          $\rule{0pt}{}$
          ○ $𝒂_{1}+𝒂_{2}+𝒂_{3}+\cdots$
          $\rule{0pt}{}$
     ◉ Written with Sigma notation:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty} 𝒂_{n}$
          $\rule{0pt}{}$
     ◉ The symbol $\sum$ represents a sum.
     ◉ General meaning:
          ○ it tells us where to start
          ○ and where to stop adding the terms

● [2:28](https://www.youtube.com/watch?v=DGcWMdW-72M&t=148). Definition of a partial sum $S_{n}$.
     ◉ A partial sum adds only finitely many terms of the series.
     ◉ Written as:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{k=1}^{n} a_{k}$
          $\rule{0pt}{}$
     ◉ General form:
          $\rule{0pt}{}$
          ○ $S_{n}=\displaystyle \sum_{k=1}^{n} a_{k}$
          $\rule{0pt}{}$
     ◉ Since $n$ is finite,
          ○ the partial sum must exist
     ◉ Important interpretation:
          ○ We do not study the infinite sum all at once,
          ○ instead, we study the finite partial sums first

● [5:50](https://www.youtube.com/watch?v=DGcWMdW-72M&t=350). Important idea.
     ◉ Each new value of $n$ produces a new partial sum.
     ◉ For the next $n$,
          ○ there is a new $S_{n}$
     ◉ Therefore,
          ○ the partial sums form a sequence

● [7:18](https://www.youtube.com/watch?v=DGcWMdW-72M&t=438). Sequence of partial sums.
     ◉ Conceptual distinction:
          ○ Sequence if I don’t add them
          ○ Series if I do add them
     ◉ First terms of the sequence of partial sums:
          $\rule{0pt}{}$
          ○ $S_{1}=\displaystyle \sum_{k=1}^{1} a_{k}=𝒂_{1}$
          $\rule{0pt}{}$
          ○ $S_{2}=\displaystyle \sum_{k=1}^{2} a_{k}=𝒂_{1}+𝒂_{2}$
          $\rule{0pt}{}$
          ○ $S_{3}=\displaystyle \sum_{k=1}^{3} a_{k}=𝒂_{1}+𝒂_{2}+𝒂_{3}$
          $\rule{0pt}{}$
          ○ $S_{4}=\displaystyle \sum_{k=1}^{4} a_{k}=𝒂_{1}+𝒂_{2}+𝒂_{3}+𝒂_{4}$
          $\rule{0pt}{}$
          ○ $\cdots$
          $\rule{0pt}{}$
          ○ $S_{n}=𝒂_{1}+𝒂_{2}+𝒂_{3}+\cdots+𝒂_{n}$
          $\rule{0pt}{}$
     ◉ Sequence notation:
          $\rule{0pt}{}$
          ○ $S_{1},S_{2},S_{3},S_{4},\dots,S_{n}$
          $\rule{0pt}{}$
          ○ this creates the sequence of partial sums $\{S_{n}\}$
     ◉ Main idea:
          ○ Each new value of $n$ gives a different partial sum,
          ○ so the partial sums themselves form a sequence,
          ○ this is why sequences were covered first




     

Ｃｏｎｖｅｒｇｅｎｃｅ　＆　Ｄｉｖｅｒｇｅｎｃｅ　ｏｆ　Ｓｅｒｉｅｓ
 
● [9:10](https://www.youtube.com/watch?v=DGcWMdW-72M&t=550). Convergence and divergence of a series.
     ◉ **A series is studied through the sequence of its partial sums.**   

● [10:00](https://www.youtube.com/watch?v=DGcWMdW-72M&t=600). Formal definition of an infinite series by limits. [📷image](../img/Calculus 2 Lecture 9.2/[10-00]-01.png)
     ◉ i̲f̲ $\{S_{n}\}$ converges, that is, $\displaystyle \lim_{n\to\infty} S_{n}=S$,
          ○ t̲h̲e̲n̲ the series $\displaystyle \sum_{n=1}^{\infty} 𝒂_{n}$ also converges
          $\rule{0pt}{}$
               ■ and the sum of the series is $S$
     ◉ [13:07](https://www.youtube.com/watch?v=DGcWMdW-72M&t=787). The infinite series is defined through the limit of the partial sums:
               $\rule{0pt}{}$
               ■ $\displaystyle \sum_{n=1}^{\infty} 𝒂_{n}=\lim_{n\to\infty}\sum_{k=1}^{n} a_{k}=\lim_{n\to\infty} S_{n}=S$

● Covergence and divergence
     ◉ i̲f̲ the sequence of partial sums $\{S_{n}\}$ converges,
          ○ t̲h̲e̲n̲ the series $\displaystyle \sum_{n=1}^{\infty} 𝒂_{n}$ converges
     ◉ i̲f̲ the sequence of partial sums $\{S_{n}\}$ diverges,
          ○ t̲h̲e̲n̲ the series $\displaystyle \sum_{n=1}^{\infty} 𝒂_{n}$ diverges
               
● N̲O̲T̲E̲ — Meaning of $\{S_{n}\}$.
     ◉ The notation $\{S_{n}\}$ represents the sequence of all partial sums.
          ○ In expanded form:
               $\rule{0pt}{}$
               ■ $S_{1},S_{2},S_{3},S_{4},\dots,S_{n},\dots$
                    $\rule{0pt}{}$
                    ▣ $S_{n}=𝒂_{1}+𝒂_{2}+\cdots+𝒂_{n}$
          ○ Here:
               ■ $S_{1}$ is the first partial sum
               ■ $S_{2}$ is the second partial sum
               ■ $S_{3}$ is the third partial sum
               ■ and so on  
     ◉ $\displaystyle \sum_{n=1}^{\infty} 𝒂_{n}$ denotes the infinite series
     $\rule{0pt}{}$
          ○ $𝒂_{1}+𝒂_{2}+𝒂_{3}+\cdots$
     ◉ Important clarification:
          ○ although braces are used, $\{S_{n}\}$ is understood here as a sequence, not as an unordered set
     ◉ Therefore,
          ○ $\{S_{n}\}$ converges means:
               ■ the sequence of partial sums converges
     ◉ If $\{S_{n}\}$ converges to $S$,
          ○ then the series $\displaystyle \sum_{n=1}^{\infty} 𝒂_{n}$ converges
          ○ and the sum of the series is $S$


● [19:40](https://www.youtube.com/watch?v=DGcWMdW-72M&t=1180). 🧩 Example 1 — Series: $\displaystyle \sum_{n=1}^{\infty} n$ [📷image](../img/Calculus 2 Lecture 9.2/[19-40]-01.png)
     ◉ ❶ Find the partial sum.
          $\rule{0pt}{}$
          ○ $S_{n}=1+2+3+\cdots+n$
          $\rule{0pt}{}$
     ◉ ❷ Find a formula for $S_{n}$.
          $\rule{0pt}{}$
          ○ $1+2+3+\cdots+n=\dfrac{n(n+1)}{2}$
          ○ so
               $\rule{0pt}{}$
               ■ $S_{n}=\dfrac{n(n+1)}{2}$
               $\rule{0pt}{}$
     ◉ ❸ Take the limit as $n\to\infty$.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{n(n+1)}{2}=\infty$
          $\rule{0pt}{}$
     ◉ Conclusion:
          ○ the series diverges

● [27:20](https://www.youtube.com/watch?v=DGcWMdW-72M&t=1640). 🧩 Example 2 — Telescoping series: $\displaystyle \sum_{n=1}^{\infty}\left(\dfrac{1}{2n+3}-\dfrac{1}{2n+1}\right)$  [📷image](../img/Calculus 2 Lecture 9.2/[27-20]-01.png)
     ◉ ❶ Find the partial sum.
          $\rule{0pt}{}$
          ○ $S_{n}=\left(\dfrac{1}{5}-\dfrac{1}{3}\right)+\left(\dfrac{1}{7}-\dfrac{1}{5}\right)+\left(\dfrac{1}{9}-\dfrac{1}{7}\right)+\cdots$
          $\rule{0pt}{}$
          ○ write out several terms
          ○ identify the cancellation pattern
               ■ the first fraction of each term cancels with the second fraction of the previous term
          ○ keep only the terms that do not cancel
     ◉ ❷ Find a formula for $S_{n}$.
          ○ After cancellation,
               $\rule{0pt}{}$
               ■ $S_{n}=-\dfrac{1}{3}+\dfrac{1}{2n+3}$
               $\rule{0pt}{}$
     ◉ ❸ Take the limit as $n\to\infty$.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty} S_{n}=\lim_{n\to\infty}\left(-\dfrac{1}{3}+\dfrac{1}{2n+3}\right)$
          $\rule{0pt}{}$
          ○ $=-\dfrac{1}{3}$
          $\rule{0pt}{}$
     ◉ Conclusion:
          ○ the series converges
          $\rule{0pt}{}$
          ○ and its sum is $-\dfrac{1}{3}$
          $\rule{0pt}{}$
     ◉ N̲O̲T̲E̲ 1: This is a telescoping series.
          ○ Most middle terms cancel when the series is written out
          ○ only the non-cancelling outer terms remain
     ◉ N̲O̲T̲E̲ 2: General note on telescoping series.
     ◉ In a partial sum $S_{n}$, cancellation only occurs among the terms that are already included, that is, from $k=1$ up to $k=n$.
     ◉ A term cancels only if its opposite counterpart also appears within those first $n$ terms.
     ◉ If the cancelling counterpart would appear only in the next term, $k=n+1$, or later, then it does not cancel in $S_{n}$.
          ○ Therefore, when computing $S_{n}$,
               ■ do not continue the cancellation beyond the nth term
     ◉ Main idea:
          ○ The cancellation stops where the partial sum stops
               ■ so the surviving terms are the boundary terms that have not yet found their cancelling partners

● [43:04](https://www.youtube.com/watch?v=DGcWMdW-72M&t=2584). 🧩 Example 3 — Partial fractions in a telescoping series: $\displaystyle \sum_{n=1}^{\infty}\dfrac{4}{4n^{2}-1}$ [📷image-1](../img/Calculus 2 Lecture 9.2/[43-04]-01.png) [📷image-2](../img/Calculus 2 Lecture 9.2/[43-04]-02.png)
     ◉ ❶ Rewrite the general term using partial fractions.
          $\rule{0pt}{}$
          ○ $\dfrac{4}{4n^{2}-1}=\dfrac{4}{(2n-1)(2n+1)}$
          ○ Set
               $\rule{0pt}{}$
               ■ $\dfrac{4}{(2n-1)(2n+1)}=\dfrac{A}{2n-1}+\dfrac{B}{2n+1}$ 
          ○ Then
               $\rule{0pt}{}$
               ■ $4=A(2n+1)+B(2n-1)$
               $\rule{0pt}{}$
          ○ Solve for the constants:
               $\rule{0pt}{}$
               ■ $n=\dfrac{1}{2}\;\to\;4=2A\;\to\;A=2$
               $\rule{0pt}{}$
               ■ $n=-\dfrac{1}{2}\to 4=-2B\to B=-2$
               $\rule{0pt}{}$
          ○ Therefore
               $\rule{0pt}{}$
               ■ $\dfrac{4}{4n^{2}-1}=\dfrac{2}{2n-1}-\dfrac{2}{2n+1}$
               $\rule{0pt}{}$
     ◉ ❷ Find the partial sum.
          $\rule{0pt}{}$
          ○ $S_{n}=\left(\dfrac{2}{1}-\dfrac{2}{3}\right)+\left(\dfrac{2}{3}-\dfrac{2}{5}\right)+\left(\dfrac{2}{5}-\dfrac{2}{7}\right)+\cdots$
          $\rule{0pt}{}$
          ○ identify the telescoping pattern
          ○ most middle terms cancel
          ○ after cancellation,
               $\rule{0pt}{}$
               ■ $S_{n}=2-\dfrac{2}{2n+1}$
               $\rule{0pt}{}$
     ◉ ❸ Take the limit as $n\to\infty$.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty} S_{n}=\lim_{n\to\infty}\left(2-\dfrac{2}{2n+1}\right)$
          $\rule{0pt}{}$
          ○ $=2$
     ◉ Conclusion:
          ○ the series converges
          ○ and its sum is $2$
        





Ｇｅｏｍｅｔｒｉｃ　Ｓｅｒｉｅｓ

● [📷image](../img/Calculus 2 Lecture 9.2/[51-22]-01.png)

● [51:22](https://www.youtube.com/watch?v=DGcWMdW-72M&t=3082). Geometric series.
     ◉ A geometric series is defined to be:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty} 𝒂\cdot 𝓻^{n-1}=𝒂+𝒂𝓻+𝒂𝓻^{2}+𝒂𝓻^{3}+\cdots$
          $\rule{0pt}{}$
     ◉ Equivalent form:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty} 𝒂\cdot 𝓻^{n}$
          $\rule{0pt}{}$
     ◉ Here:
          ○ $𝒂$ is the first term
          ○ $𝓻$ is the common ratio

● [53:50](https://www.youtube.com/watch?v=DGcWMdW-72M&t=3230). Convergence criterion for geometric series.
     ◉ i̲f̲ $|𝓻|<1$ or $-1<𝓻<1$
          ○ t̲h̲e̲n̲ the series converges
     ◉ i̲f̲ $|𝓻|\ge 1$ or $(𝓻\le -1$ or $𝓻\ge 1)$
          ○ t̲h̲e̲n̲ the series diverges

● [57:18](https://www.youtube.com/watch?v=DGcWMdW-72M&t=3438). Sum of a geometric series.
     ◉ i̲f̲ $|𝓻|<1$,
          ○ t̲h̲e̲n̲
               $\rule{0pt}{}$
               ■ $\displaystyle \sum_{n=1}^{\infty} 𝒂\cdot 𝓻^{n-1}=\dfrac{𝒂}{1-𝓻}$
               $\rule{0pt}{}$
     ◉ Important note:
          ○ this formula applies only when the series converges
          ○ that is, only when $|𝓻|<1$

● [57:58](https://www.youtube.com/watch?v=DGcWMdW-72M&t=3478). Derivation of the geometric-series formula. [📷image](../img/Calculus 2 Lecture 9.2/[57-58]-01.png)
     ◉ Start with the partial sum:
          $\rule{0pt}{}$
          ○ $S_{n}=𝒂+𝒂𝓻+𝒂𝓻^{2}+\cdots+𝒂𝓻^{n-1}$
          $\rule{0pt}{}$
     ◉ Multiply by $𝓻$:
          $\rule{0pt}{}$
          ○ $𝓻S_{n}=𝒂𝓻+𝒂𝓻^{2}+\cdots+𝒂𝓻^{n}$
          $\rule{0pt}{}$
     ◉ Subtract:
          $\rule{0pt}{}$
          ○ $S_{n}-𝓻S_{n}=𝒂-𝒂𝓻^{n}$
          $\rule{0pt}{}$
     ◉ Factor:
          $\rule{0pt}{}$
          ○ $S_{n}(1-𝓻)=𝒂(1-𝓻^{n})$
          $\rule{0pt}{}$
     ◉ Solve for the partial sum:
          $\rule{0pt}{}$
          ○ $S_{n}=\dfrac{𝒂(1-𝓻^{n})}{1-𝓻}$
          $\rule{0pt}{}$
     ◉ [1:05:03](https://www.youtube.com/watch?v=DGcWMdW-72M&t=3903). Now pass to the infinite series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty} 𝒂𝓻^{n-1}=\lim_{n\to\infty} S_{n}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{n\to\infty}\dfrac{𝒂(1-𝓻^{n})}{1-𝓻}$
          $\rule{0pt}{}$
     ◉  i̲f̲  $|𝓻|<1$, **the series converges**
          ○ t̲h̲e̲n̲ $𝓻^{n}\to 0$
     ◉ Therefore,
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty} 𝒂𝓻^{n-1}=\dfrac{𝒂}{1-𝓻}$
          


          

Ｅｘａｍｐｌｅｓ　—　Ｇｅｏｍｅｔｒｉｃ　Ｓｅｒｉｅｓ

● [1:09:43](https://www.youtube.com/watch?v=DGcWMdW-72M&t=4183). 🧩 Example 4 — Geometric series with alternating signs:  $\displaystyle \sum_{n=1}^{\infty} 3\left(-\dfrac{1}{2}\right)^{n-1}$  [📷image](../img/Calculus 2 Lecture 9.2/[1-09-43]-01.png)
     ◉ First check whether the series is geometric.
          ○ check whether there is a constant ratio between consecutive terms
     ◉ To use the formula conveniently:
          ○ check that the initial index makes the exponent start at $0$
          ○ this matters because, when the first exponent is $0$,
               ■ the first term is $𝒂\cdot 𝓻^{0}=𝒂$
               ■ so $𝒂$ is the first term of the series
     ◉ Then identify:
          $\rule{0pt}{}$
          ○ $𝒂=3$
          $\rule{0pt}{}$
          ○ $𝓻=-\dfrac{1}{2}$
          $\rule{0pt}{}$
     ◉ Next:
          ○ test whether $|𝓻|<1$
          $\rule{0pt}{}$
          ○ $\left|-\dfrac{1}{2}\right|=\dfrac{1}{2}<1$
          $\rule{0pt}{}$
          ○ therefore, the series converges
     ◉ Apply the geometric-series formula:
          $\rule{0pt}{}$
          ○ $s=\dfrac{𝒂}{1-𝓻}$
          $\rule{0pt}{}$
          ○ $s=\dfrac{3}{1-\left(-\dfrac{1}{2}\right)}$
          $\rule{0pt}{}$
          ○ $s=\dfrac{3}{\dfrac{3}{2}}$
          $\rule{0pt}{}$
          ○ $s=2$
     ◉ Conclusion:
          ○ the series converges
          ○ and its sum is $2$
     
● [1:12:29](https://www.youtube.com/watch?v=DGcWMdW-72M&t=4349). 🧩 Example 5 — Geometric series with alternating signs:  $\displaystyle \sum_{n=1}^{\infty} 3\left(\dfrac{4}{3}\right)^{n-1}$
     ◉ i̲f̲  $|𝓻|\ge 1$  or  $(𝓻\le -1$ or $𝓻\ge 1)$
     $\rule{0pt}{}$
          ○ $𝓻=\dfrac{4}{3}>1$ t̲h̲e̲n̲ the series diverges

● [1:12:52](https://www.youtube.com/watch?v=DGcWMdW-72M&t=4372). 🧩 Example 6 — Geometric series with alternating signs:  $\displaystyle \sum_{n=1}^{\infty} 3\left(-\dfrac{4}{3}\right)^{n-1}$ [📷image](../img/Calculus 2 Lecture 9.2/[1-12-52]-01.png)
     ◉ i̲f̲  $|𝓻|\ge 1$  or  $(𝓻\le -1$ or $𝓻\ge 1)$
     $\rule{0pt}{}$
          ○ $𝓻=-\dfrac{4}{3}< -1$ t̲h̲e̲n̲ the series diverges
          
● [1:14:15](https://www.youtube.com/watch?v=DGcWMdW-72M&t=4455). 🧩 Example 7 — Rewriting the series $\displaystyle \sum_{n=1}^{\infty}= \dfrac{5}{3}-\dfrac{5}{9}+\dfrac{5}{27}-\dfrac{5}{81}+\cdots$ in geometric form. [📷image](../img/Calculus 2 Lecture 9.2/[1-14-15]-01.png)
     ◉ ❶ Check where the series starts.
          ○ Here the series starts at $n=1$,
          ○ so the exponent should begin at $0$ in the first term,
          ○ therefore we want a form involving $(n-1)$ in the exponent
     ◉ ❷ Factor as much as possible.
          ○ factor out $\dfrac{5}{3}$
          ○ this gives:
               $\rule{0pt}{}$
               ■ $\left(\dfrac{5}{3}\right)\left(1-\dfrac{1}{3}+\dfrac{1}{9}-\dfrac{1}{27}+\cdots\right)$
               $\rule{0pt}{}$
     ◉ ❸ Rewrite the remaining pattern in exponential form.
          $\rule{0pt}{}$
          ○ $1=\left(-\dfrac{1}{3}\right)^{0}$
          $\rule{0pt}{}$
          ○ $-\dfrac{1}{3}=\left(-\dfrac{1}{3}\right)^{1}$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{9}=\left(-\dfrac{1}{3}\right)^{2}$
          $\rule{0pt}{}$
          ○ $-\dfrac{1}{27}=\left(-\dfrac{1}{3}\right)^{3}$
          $\rule{0pt}{}$
          ○ so the series becomes:
               $\rule{0pt}{}$
               ■ $\displaystyle \sum_{n=1}^{\infty}\left(\dfrac{5}{3}\right)\left(-\dfrac{1}{3}\right)^{n-1}$
               $\rule{0pt}{}$
     ◉ Conclusion:
          ○ now the series is written in geometric form
          $\rule{0pt}{}$
          ○ $𝒂=\dfrac{5}{3}$
          $\rule{0pt}{}$
          ○ $𝓻=-\dfrac{1}{3}$
          $\rule{0pt}{}$
     ◉ ❺ Check convergence.
     $\rule{0pt}{}$
          ○ $|𝓻|=\dfrac{1}{3}<1$
          $\rule{0pt}{}$
          ○ therefore, the series converges
     ◉ ❻ Compute the sum.
          $\rule{0pt}{}$
          ○ $s=\dfrac{𝒂}{1-𝓻}$
          $\rule{0pt}{}$
          ○ $s=\dfrac{\dfrac{5}{3}}{1-\left(-\dfrac{1}{3}\right)}$
          $\rule{0pt}{}$
          ○ $s=\dfrac{\dfrac{5}{3}}{\dfrac{4}{3}}$
          $\rule{0pt}{}$
          ○ $s=\dfrac{5}{4}$
     ◉ Conclusion:
          ○ the series converges
          ○ and its sum is $\dfrac{5}{4}$

● Algebraic rewriting strategies.
     ◉ Sometimes a series does not look geometric at first.
     ◉ Strategy:
          ○ rewrite the powers so that the exponent matches the index pattern
          ○ factor out constants if necessary
     ◉ [1:21:55](https://www.youtube.com/watch?v=DGcWMdW-72M&t=4915). 🧩 Example 7 —  Rewrite $\displaystyle \sum_{n=1}^{\infty}\dfrac{𝒆^{n}}{3^{n+1}}$ into geometric form. [📷image](../img/Calculus 2 Lecture 9.2/[1-21-55]-01.png)
          $\rule{0pt}{}$
          ○ $\dfrac{𝒆^{n}}{3^{n+1}}=\dfrac{𝒆\cdot 𝒆^{n-1}}{3^{2}\cdot 3^{n-1}}$
          $\rule{0pt}{}$
               ■ now the exponent matches the index pattern, because the series starts at $1$ and the first exponent must be $0$, so that the first term is $𝒂$
          $\rule{0pt}{}$
          ○ $=\left(\dfrac{𝒆}{9}\right)\cdot \left(\dfrac{𝒆^{n-1}}{3^{n-1}}\right)$
          $\rule{0pt}{}$
          ○ $=\left(\dfrac{𝒆}{9}\right)\cdot \left(\dfrac{𝒆}{3}\right)^{n-1}$
          $\rule{0pt}{}$
          ○ so
               $\rule{0pt}{}$
               ■ $\displaystyle \sum_{n=1}^{\infty}\dfrac{𝒆^{n}}{3^{n+1}}=\sum_{n=1}^{\infty}\left(\dfrac{𝒆}{9}\right)\left(\dfrac{𝒆}{3}\right)^{n-1}$
               $\rule{0pt}{}$
     ◉ Identify the geometric parameters:
          $\rule{0pt}{}$
          ○ $𝒂=\dfrac{𝒆}{9}$
          $\rule{0pt}{}$
          ○ $𝓻=\dfrac{𝒆}{3}$
          $\rule{0pt}{}$
     ◉ Check convergence:
     $\rule{0pt}{}$
          ○ since $\dfrac{𝒆}{3}<1$,
          $\rule{0pt}{}$
               ■ the series converges
     ◉ Compute the sum:
          $\rule{0pt}{}$
          ○ $s=\dfrac{𝒂}{1-𝓻}$
          $\rule{0pt}{}$
          ○ $s=\dfrac{\dfrac{𝒆}{9}}{1-\dfrac{𝒆}{3}}$
          $\rule{0pt}{}$
          ○ $s=\dfrac{𝒆}{3(3-𝒆)}$
          
● N̲O̲T̲E̲ 1 — Subsequences and divergence.
     ◉ i̲f̲ a sequence $\{𝒂_{n}\}$ is convergent,
          ○ t̲h̲e̲n̲ any subsequence of $\{𝒂_{n}\}$ must also be convergent.
     ◉ Therefore,
          ○ to show that a sequence $\{𝒂_{n}\}$ diverges,
               ■ it is enough to show that a subsequence diverges.
     ◉ Connection with the harmonic series:
          ○ for a series, convergence is studied through its sequence of partial sums.
          ○ in the harmonic series, the terms $\dfrac{1}{n}$ go to $0$,
               ■ but this is not enough for the series to converge.
               ■ the partial sums keep growing.
          ○ so the harmonic series diverges because its sequence of partial sums does not converge.
          ○ one way to show this is to find a subsequence of partial sums that diverges.

● N̲O̲T̲E̲ 2 — Why the harmonic series diverges.
     ◉ The harmonic series is:
          $\rule{0pt}{}$
          ○ $1+\dfrac{1}{2}+\dfrac{1}{3}+\dfrac{1}{4}+\dfrac{1}{5}+\dfrac{1}{6}+\cdots$
          $\rule{0pt}{}$
     ◉ Instead of seeing it as one long sum,
          ○ we group the terms in blocks:
               $\rule{0pt}{}$
               ■ $1+\dfrac{1}{2}+\left(\dfrac{1}{3}+\dfrac{1}{4}\right)+\left(\dfrac{1}{5}+\dfrac{1}{6}+\dfrac{1}{7}+\dfrac{1}{8}\right)+\left(\dfrac{1}{9}+\cdots+\dfrac{1}{16}\right)+\cdots$
               $\rule{0pt}{}$
     ◉ Key idea:
          ○ in each block, every term is greater than or equal to the last term of that block.
     ◉ For example:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{3}+\dfrac{1}{4}>\dfrac{1}{4}+\dfrac{1}{4}=\dfrac{1}{2}$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{5}+\dfrac{1}{6}+\dfrac{1}{7}+\dfrac{1}{8}> \dfrac{1}{8}+\dfrac{1}{8}+\dfrac{1}{8}+\dfrac{1}{8}=\dfrac{1}{2}$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{9}+\cdots+\dfrac{1}{16}>8\cdot \dfrac{1}{16}=\dfrac{1}{2}$
          $\rule{0pt}{}$
     ◉ Therefore,
          ○ the partial sums keep increasing by at least $\dfrac{1}{2}$ again and again.
          ○ so the sequence of partial sums $\{S_{n}\}$ does not converge.
          ○ therefore, the harmonic series diverges.

● N̲O̲T̲E̲ 3 — Connection with partial sums and subsequences.
     ◉ A series converges or diverges depending on its sequence of partial sums $\{S_{n}\}$.
          ○ i̲f̲ $\{S_{n}\}$ converges,
               ■ t̲h̲e̲n̲ the series $\displaystyle \sum_{n=1}^{\infty} 𝒂_{n}$ converges.
          ○ i̲f̲ $\{S_{n}\}$ diverges,
               ■ t̲h̲e̲n̲ the series $\displaystyle \sum_{n=1}^{\infty} 𝒂_{n}$ diverges.
               $\rule{0pt}{}$
     ◉ Therefore, to prove that the harmonic series diverges,
          ○ we have to prove that its sequence of partial sums $\{S_{n}\}$ diverges.
     ◉ This is where the subsequence idea enters:
          ○ i̲f̲ $\{S_{n}\}$ were convergent,
               ■ t̲h̲e̲n̲ every subsequence of $\{S_{n}\}$ would also be convergent.
          ○ so, if we find one subsequence of partial sums that diverges,
               ■ then $\{S_{n}\}$ cannot converge.
          ○ therefore, the harmonic series diverges.
     ◉ In this case, a useful subsequence is:
          $\rule{0pt}{}$
          ○ $S_{1},S_{2},S_{4},S_{8},S_{16},\dots$
          $\rule{0pt}{}$
          ○ that is, the subsequence of partial sums with indices $1,2,4,8,16,\dots$
          ○ equivalently, $S$ with index $2^{k}$.
     ◉ This subsequence is useful because it matches the block grouping:
          $\rule{0pt}{}$
          ○ $S_{2}$ includes $1+\dfrac{1}{2}$
          $\rule{0pt}{}$
          ○ $S_{4}$ includes $1+\dfrac{1}{2}+\left(\dfrac{1}{3}+\dfrac{1}{4}\right)$
          $\rule{0pt}{}$
          ○ $S_{8}$ includes $1+\dfrac{1}{2}+\left(\dfrac{1}{3}+\dfrac{1}{4}\right)+\left(\dfrac{1}{5}+\dfrac{1}{6}+\dfrac{1}{7}+\dfrac{1}{8}\right)$
          $\rule{0pt}{}$
          ○ $S_{16}$ includes the next block up to $\dfrac{1}{16}$
          $\rule{0pt}{}$
     ◉ Since each new block adds at least $\dfrac{1}{2}$,
     $\rule{0pt}{}$
          ○ the subsequence $S_{1},S_{2},S_{4},S_{8},S_{16},\dots$ grows without bound.
          ○ therefore, this subsequence diverges.
          ○ so the full sequence of partial sums $\{S_{n}\}$ cannot converge.

● N̲O̲T̲E̲ 4 — Important clarification.
     ◉ Finding one convergent subsequence does not usually prove that the whole sequence converges.
     ◉ However, for an increasing sequence of partial sums,
          ○ i̲f̲ one subsequence converged to a finite number,
               ■ t̲h̲e̲n̲ the whole sequence would be bounded above.
               ■ therefore, the whole sequence would converge.
     ◉ In the harmonic series, this does not happen:
          ○ the partial sums keep growing without bound.
          ○ therefore, no subsequence of partial sums can converge to a finite number.

● N̲O̲T̲E̲ 5 — Subsequences and convergence/divergence.
     ◉ A divergent subsequence implies that the original sequence diverges:
          ○ divergent subsequence $\Rightarrow$ original sequence diverges
     ◉ Two subsequences with different limits imply that the original sequence diverges:
          ○ two subsequences with different limits $\Rightarrow$ original sequence diverges
     ◉ One convergent subsequence does not imply that the original sequence converges:
          ○ one convergent subsequence $\nRightarrow$ original sequence converges
     ◉ However, with an extra condition, it can be enough:
          ○ increasing sequence + one convergent subsequence $\Rightarrow$ original sequence converges
     ◉ Reason:
          ○ if the original sequence is increasing,
               ■ and one subsequence converges to a finite number,
                    ▣ then the whole sequence is bounded above.
                    ▣ therefore, the whole sequence converges.




          
Ｔｈｅ　Ｄｉｖｅｒｇｅｎｃｅ　Ｔｅｓｔ

● [📷image](../img/Calculus 2 Lecture 9.2/[1-33-47]-01.png)

● [1:33:47](https://www.youtube.com/watch?v=DGcWMdW-72M&t=5627). Necessary condition for convergence:
     ◉ i̲f̲ $\displaystyle \sum_{n=1}^{\infty} 𝒂_{n}$ converges,
          ○ t̲h̲e̲n̲ $\displaystyle \lim_{n\to\infty} 𝒂_{n}=0$
               
● N̲O̲T̲E̲ — Series convergence versus term convergence.
     ◉ If a series converges to $\mathcal{K}$:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty} 𝒂_{n}=\mathcal{K}$
          $\rule{0pt}{}$
     ◉ This means that the sequence of partial sums converges to $\mathcal{K}$:
          $\rule{0pt}{}$
          ○ $S_{n}=𝒂_{1}+𝒂_{2}+\cdots+𝒂_{n}$
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty} S_{n}=\mathcal{K}$
          $\rule{0pt}{}$
     ◉ Important distinction:
          ○ the series $\displaystyle \sum_{n=1}^{\infty} 𝒂_{n}$ may converge to a finite number,
               ■ but the individual terms $𝒂_{n}$ must converge to $0$.
     ◉ Reason:
          ○ for an infinite sum to stabilize at a finite number,
               ■ the new terms being added must become smaller and smaller.
               ■ therefore, they must tend to $0$.  

● [1:35:35](https://www.youtube.com/watch?v=DGcWMdW-72M&t=5735). Fundamental theorem and divergence test.
     ◉ i̲f̲
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty} 𝒂_{n}\ne 0$
          $\rule{0pt}{}$
     ◉ o̲r̲ ̲i̲f̲ the limit does not exist,
          ○ t̲h̲e̲n̲ the series diverges

● [1:38:50](https://www.youtube.com/watch?v=DGcWMdW-72M&t=5930). Important warning.
     ◉ $\displaystyle \lim_{n\to\infty} 𝒂_{n}=0$ does not guarantee that the series converges.
     $\rule{0pt}{}$
     ◉ It is only a necessary condition,
          ○ not a sufficient one

● [1:41:01](https://www.youtube.com/watch?v=DGcWMdW-72M&t=6061). 🧩 Example 8 — Using the Divergence Test: $\displaystyle \sum_{n=1}^{\infty}\dfrac{2n^{2}-1}{3n^{2}-1}$ [📷image](../img/Calculus 2 Lecture 9.2/[1-41-01]-01.png)
     ◉ Take the limit of the general term:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{2n^{2}-1}{3n^{2}-1}$
          $\rule{0pt}{}$
     ◉ Since the numerator and denominator have the same degree,
          ○ compare the leading coefficients:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{n\to\infty}\dfrac{2n^{2}-1}{3n^{2}-1}=\dfrac{2}{3}$
               $\rule{0pt}{}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\dfrac{2}{3}\ne 0$
          $\rule{0pt}{}$
     ◉ By the Divergence Test:
     $\rule{0pt}{}$
          ○ i̲f̲ $\displaystyle \lim_{n\to\infty} 𝒂_{n}\ne 0$,
          $\rule{0pt}{}$
               ■ t̲h̲e̲n̲ $\displaystyle \sum_{n=1}^{\infty} 𝒂_{n}$ diverges.
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{2n^{2}-1}{3n^{2}-1}$ diverges.



          

Ｐｒｏｐｅｒｔｉｅｓ　ｏｆ　Ｃｏｎｖｅｒｇｅｎｔ　Ｓｅｒｉｅｓ

● [1:42:26](https://www.youtube.com/watch?v=DGcWMdW-72M&t=6146). General properties of convergent series. [📷image](../img/Calculus 2 Lecture 9.2/[1-42-26]-01.png)
     ◉ Constant multiple:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}(c\cdot 𝒂_{n})=c\cdot \sum_{n=1}^{\infty} 𝒂_{n}$
          $\rule{0pt}{}$
     ◉ Sum and difference:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}(𝒂_{n}\pm b_{n})=\sum_{n=1}^{\infty} 𝒂_{n}\pm \sum_{n=1}^{\infty} b_{n}$

● Important practical remark.
     ◉ i̲f̲ a series is split into several parts,
          ○ t̲h̲e̲n̲ every part must converge for the whole expression to converge
     ◉ i̲f̲ one part diverges,
          ○ t̲h̲e̲n̲ the whole series diverges
          
● [1:43:35](https://www.youtube.com/watch?v=DGcWMdW-72M&t=6215). 🧩 Example 9 — Splitting a series into geometric series: $\displaystyle \sum_{n=1}^{\infty}\left[\dfrac{2^{n}-5^{n}}{3^{n}}\right]$ [📷image-1](../img/Calculus 2 Lecture 9.2/[1-43-35]-01.png) [📷image-2](../img/Calculus 2 Lecture 9.2/[1-43-35]-02.png) [📷image-3](../img/Calculus 2 Lecture 9.2/[1-43-35]-03.png)
     ◉ Split the fraction:
          $\rule{0pt}{}$
          ○ $\dfrac{2^{n}-5^{n}}{3^{n}}=\dfrac{2^{n}}{3^{n}}-\dfrac{5^{n}}{3^{n}}$
          $\rule{0pt}{}$
     ◉ Rewrite each term as a power:
          $\rule{0pt}{}$
          ○ $\dfrac{2^{n}}{3^{n}}=\left(\dfrac{2}{3}\right)^{n}$
          $\rule{0pt}{}$
          ○ $\dfrac{5^{n}}{3^{n}}=\left(\dfrac{5}{3}\right)^{n}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left[\dfrac{2^{n}-5^{n}}{3^{n}}\right]=\sum_{n=1}^{\infty}\left(\dfrac{2}{3}\right)^{n}-\sum_{n=1}^{\infty}\left(\dfrac{5}{3}\right)^{n}$
          $\rule{0pt}{}$
     ◉ Analyze each geometric series:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left(\dfrac{2}{3}\right)^{n}$ converges because $\left|\dfrac{2}{3}\right|<1$.
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left(\dfrac{5}{3}\right)^{n}$ diverges because $\left|\dfrac{5}{3}\right|>1$.
          $\rule{0pt}{}$
     ◉ Important warning:
          ○ the geometric series formula only applies when $|𝒓|<1$.
          $\rule{0pt}{}$
          ○ since $\left|\dfrac{5}{3}\right|>1$,
               ■ we cannot use $\dfrac{𝒂}{1-𝒓}$ for $\displaystyle \sum_{n=1}^{\infty}\left(\dfrac{5}{3}\right)^{n}$.
     ◉ Therefore:
          ○ the original series diverges.
     ◉ **Edited variant** — replacing $5^{n}$ with $1^{n}$:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left[\dfrac{2^{n}-1^{n}}{3^{n}}\right]$
          $\rule{0pt}{}$
     ◉ Split the fraction:
          $\rule{0pt}{}$
          ○ $\dfrac{2^{n}-1^{n}}{3^{n}}=\dfrac{2^{n}}{3^{n}}-\dfrac{1^{n}}{3^{n}}$
          $\rule{0pt}{}$
     ◉ Rewrite each term as a power:
          $\rule{0pt}{}$
          ○ $\dfrac{2^{n}}{3^{n}}=\left(\dfrac{2}{3}\right)^{n}$
          $\rule{0pt}{}$
          ○ $\dfrac{1^{n}}{3^{n}}=\left(\dfrac{1}{3}\right)^{n}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left[\dfrac{2^{n}-1^{n}}{3^{n}}\right]=\sum_{n=1}^{\infty}\left(\dfrac{2}{3}\right)^{n}-\sum_{n=1}^{\infty}\left(\dfrac{1}{3}\right)^{n}$
          $\rule{0pt}{}$
     ◉ Analyze each geometric series:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left(\dfrac{2}{3}\right)^{n}$ converges because $\left|\dfrac{2}{3}\right|<1$.
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left(\dfrac{1}{3}\right)^{n}$ converges because $\left|\dfrac{1}{3}\right|<1$.
          $\rule{0pt}{}$
     ◉ Use the geometric series formula:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty} 𝒂𝒓^{n-1}=\dfrac{𝒂}{1-𝒓}$, where $|𝒓|<1$.
          $\rule{0pt}{}$
     ◉ Rewrite each series starting with its first term:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left(\dfrac{2}{3}\right)^{n}=\sum_{n=1}^{\infty}\left(\dfrac{2}{3}\right)\left(\dfrac{2}{3}\right)^{n-1}$
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left(\dfrac{1}{3}\right)^{n}=\sum_{n=1}^{\infty}\left(\dfrac{1}{3}\right)\left(\dfrac{1}{3}\right)^{n-1}$
          $\rule{0pt}{}$
     ◉ Evaluate:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left(\dfrac{2}{3}\right)^{n}=\dfrac{\dfrac{2}{3}}{1-\dfrac{2}{3}}=\dfrac{\dfrac{2}{3}}{\dfrac{1}{3}}=2$
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left(\dfrac{1}{3}\right)^{n}=\dfrac{\dfrac{1}{3}}{1-\dfrac{1}{3}}=\dfrac{\dfrac{1}{3}}{\dfrac{2}{3}}=\dfrac{1}{2}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left[\dfrac{2^{n}-1^{n}}{3^{n}}\right]=2-\dfrac{1}{2}=\dfrac{3}{2}$
          $\rule{0pt}{}$
     ◉ Conclusion for the edited variant:
          ○ the edited series converges.

● [1:52:00](https://www.youtube.com/watch?v=DGcWMdW-72M&t=6720). Shortcut for identifying $𝒂$ in a geometric series. [📷image](../img/Calculus 2 Lecture 9.2/[1-52-07]-01.png)
     ◉ The value of $𝒂$ is the **first term of the series.**
     ◉ So:
          ○ first make sure the exponent pattern matches the starting index
     ◉ Then:
          ○ identify the actual first term
          ○ and use it in the formula $s=\dfrac{𝒂}{1-𝓻}$
          
● Matching exponents and starting indices.
     ◉ i̲f̲ the series starts at $n=k$,
          ○ t̲h̲e̲n̲ the exponent should be adjusted so that the first exponent is $0$
     ◉ This may require factoring out extra powers or constants.
     
● [1:52:40](https://www.youtube.com/watch?v=DGcWMdW-72M&t=6760). 🧩 Example 10 — Matching exponents and starting indices: $\displaystyle \sum_{n=1}^{\infty}\left(\dfrac{2}{3}\right)^{n}$
     ◉ Important issue:
          ○ the exponent starts at $n$,
               ■ but the geometric series formula is usually written with exponent $n-1$.
     ◉ Geometric series formula:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty} 𝒂𝒓^{n-1}=\dfrac{𝒂}{1-𝒓}$, where $|𝒓|<1$
          $\rule{0pt}{}$
     ◉ Rewrite the term so the exponent matches $n-1$:
          $\rule{0pt}{}$
          ○ $\left(\dfrac{2}{3}\right)^{n}=\left(\dfrac{2}{3}\right)\left(\dfrac{2}{3}\right)^{n-1}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left(\dfrac{2}{3}\right)^{n}=\sum_{n=1}^{\infty}\left(\dfrac{2}{3}\right)\left(\dfrac{2}{3}\right)^{n-1}$
          $\rule{0pt}{}$
     ◉ Identify the first term and the ratio:
          $\rule{0pt}{}$
          ○ $𝒂=\dfrac{2}{3}$
          $\rule{0pt}{}$
          ○ $𝒓=\dfrac{2}{3}$
     ◉ Since:
          $\rule{0pt}{}$
          ○ $\left|\dfrac{2}{3}\right|<1$
          $\rule{0pt}{}$
     ◉ The series converges.
     ◉ Apply the formula:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left(\dfrac{2}{3}\right)^{n}=\dfrac{\dfrac{2}{3}}{1-\dfrac{2}{3}}$
          $\rule{0pt}{}$
          ○ $=\dfrac{\dfrac{2}{3}}{\dfrac{1}{3}}$
          $\rule{0pt}{}$
          ○ $=2$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\left(\dfrac{2}{3}\right)^{n}=2$
          $\rule{0pt}{}$
     ◉ Key idea:
          ○ when the series starts at $n=1$,
               ■ the first term is not $1$.
               $\rule{0pt}{}$
               ■ the first term is $\left(\dfrac{2}{3}\right)^{1}=\dfrac{2}{3}$.
               $\rule{0pt}{}$
          ○ so we use $\dfrac{𝒂}{1-𝒓}$, with $𝒂=\dfrac{2}{3}$.

● [1:53:53](https://www.youtube.com/watch?v=DGcWMdW-72M&t=6833). 🧩 Example 11 — Matching exponents and starting indices: $\displaystyle \sum_{n=2}^{\infty}\dfrac{𝒆^{n}}{3^{n+1}}$. [📷image](../img/Calculus 2 Lecture 9.2/[1-53-53]-01.png)
     ◉ ❶ Rewrite the general term.
          $\rule{0pt}{}$
          ○ $\dfrac{𝒆^{n}}{3^{n+1}}=\dfrac{𝒆^{n}}{3\cdot 3^{n}}$
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{3}\left(\dfrac{𝒆}{3}\right)^{n}$
          $\rule{0pt}{}$
     ◉ ❷ Match the exponent to the starting index.
          ○ the series starts at $n=2$
          ○ so we want the exponent to begin at $0$ when $n=2$
          ○ therefore rewrite:
               $\rule{0pt}{}$
               ■ $\dfrac{1}{3}\left(\dfrac{𝒆}{3}\right)^{n}=\dfrac{1}{3}\left(\dfrac{𝒆}{3}\right)^{2}\left(\dfrac{𝒆}{3}\right)^{n-2}$
               $\rule{0pt}{}$
               ■ $=\left(\dfrac{𝒆^{2}}{27}\right)\left(\dfrac{𝒆}{3}\right)^{n-2}$
               $\rule{0pt}{}$
     ◉ ❸ Identify the geometric parameters.
          $\rule{0pt}{}$
          ○ $𝒂=\dfrac{𝒆^{2}}{27}$
          $\rule{0pt}{}$
          ○ $𝓻=\dfrac{𝒆}{3}$
          $\rule{0pt}{}$
     ◉ ❹ Check convergence.
     $\rule{0pt}{}$
          ○ since $\dfrac{𝒆}{3}<1$,
          $\rule{0pt}{}$
               ■ the series converges
     ◉ ❺ Compute the sum.
          $\rule{0pt}{}$
          ○ $s=\dfrac{𝒂}{1-𝓻}$
          $\rule{0pt}{}$
          ○ $s=\dfrac{\dfrac{𝒆^{2}}{27}}{1-\dfrac{𝒆}{3}}$
          $\rule{0pt}{}$
     ◉ Important idea:
          ○ here $𝒂$ is not $\dfrac{1}{3}$
          ○ $𝒂$ must be the actual first term of the geometric series
          ○ since the series starts at $n=2$, the first term is $\dfrac{𝒆^{2}}{27}$      




          

Ｓｔｒａｔｅｇｉｃ　Ｎｏｔｅｓ

● Main workflow for testing a series.
     ◉ 1. Identify the form of the series.
     ◉ 2. If possible, find the partial sum.
     ◉ 3. Take the limit of the partial sums.
     ◉ 4. For geometric series,
          ○ first test $|r|<1$
          ○ then use the sum formula i̲f̲ it converges
     ◉ 5. Always remember the Divergence Test:
          ○ i̲f̲ $\displaystyle \lim_{n\to\infty} 𝒂_{n}\ne 0$,
               ■ t̲h̲e̲n̲ the series diverges immediately



               

Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Infinite Series
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/5-2-infinite-series)

● The Divergence test
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/5-3-the-divergence-and-integral-tests)