-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ９．１ － Ｃｏｎｖｅｒｇｅｎｃｅ  ａｎｄ   Ｄｉｖｅｒｇｅｎｃｅ  ｏｆ  Ｓｅｑｕｅｎｃｅｓ**------------------------------—






Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:00](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=0). Introduction to Sequences and Series.
     ◉ In this section, the focus is only on sequences.
     ◉ Main goals:
          ○ understand what a sequence is
          ○ generate terms from sequence notation
          ○ find sequence notation from a list of terms
          ○ determine whether a sequence converges or diverges
     ◉ Motivating idea:
          ○ a complicated function $𝒇(𝒙)$ can often be expressed as a series of simpler functions




          

Ｓｅｑｕｅｎｃｅｓ　—　Ｂａｓｉｃ　Ｄｅｆｉｎｉｔｉｏｎｓ　＆　Ｎｏｔａｔｉｏｎ

● [1:37](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=97). Definition of a sequence $𝒂_{n}$. [📷image](../img/Calculus 2 Lecture 9.1/[1-37]-01.png)
     ◉ A sequence is a set of terms, typically an ordered list of terms.
     ◉ Standard notation:
          $\rule{0pt}{}$
          ○ $𝒂_{1},\,𝒂_{2},\,𝒂_{3},\,\ldots,\,𝒂_{n}$
          $\rule{0pt}{}$
     ◉ The index $n$ is a positive integer.
     ◉ Alternative notation:
          $\rule{0pt}{}$
          ○ $\{a_{𝒏}\}_{n=k}^{\infty}$
          $\rule{0pt}{}$
     ◉ Convention:
          ○ if no starting index is shown,
               ■ $𝒏$ starts at $1$
               


               

Ｇｅｎｅｒａｔｉｎｇ　Ｔｅｒｍｓ　Ｆｒｏｍ　Ｓｅｑｕｅｎｃｅ　Ｎｏｔａｔｉｏｎ

● [4:20](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=260). Generating terms from sequence notation.
     ◉ Basic idea:
          ○ substitute specific values of $𝒏$ into the formula to generate terms

● [4:48](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=288). 🧩 Example 1 — Listing the first terms of the sequence $\left\{\dfrac{(-1)^{\,n+1}\cdot 2^{n}}{n+1}\right\}_{n=1}^{\infty}$. [📷image](../img/Calculus 2 Lecture 9.1/[4-48]-01.png)
     ◉ Substitute:
          $\rule{0pt}{}$
          ○ $n=1\;\to\;𝒂_{1}=1$
          $\rule{0pt}{}$
          ○ $n=2\;\to\;𝒂_{2}=-\dfrac{4}{3}$
          $\rule{0pt}{}$
          ○ $n=3\;\to\;𝒂_{3}=2$
          $\rule{0pt}{}$
          ○ $n=4\;\to\;𝒂_{4}=-\dfrac{16}{5}$
          $\rule{0pt}{}$
          ○ $n=5\;\to\;𝒂_{5}=\dfrac{16}{3}$
          $\rule{0pt}{}$
     ◉ Alternating behavior:
          ○ the factor $(-1)^{n+1}$ makes the sequence alternate in sign
          ○ positive, negative, positive, negative, ...
     ◉ Pattern recognition:
          ○ the sequence continues indefinitely
          ○ each term is obtained by substituting the next positive integer value of $n$
 

● [11:15](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=675). 🧩 Example 2 — Evaluating the sequence $\left\{(-1)^{n}\sqrt{n-2}\right\}$ with starting index $n=2$. [📷image](../img/Calculus 2 Lecture 9.1/[11-15]-01.png)
     ◉ Reason for the starting index:
          ○ the sequence starts at $n=2$ because $\sqrt{n-2}$ is not real when $n=1$
     ◉ Evaluate the first terms by substitution.
          $\rule{0pt}{}$
          ○ $n=2\;\to\;𝒂_{2}=0$
          $\rule{0pt}{}$
          ○ $n=3\;\to\;𝒂_{3}=-1$
          $\rule{0pt}{}$
          ○ $n=4\;\to\;𝒂_{4}=\sqrt{2}$
          $\rule{0pt}{}$
          ○ $n=5\;\to\;𝒂_{5}=-\sqrt{3}$
          $\rule{0pt}{}$
          ○ $n=6\;\to\;𝒂_{6}=2$
          $\rule{0pt}{}$
     ◉ Pattern:
          ○ the factor $(-1)^{n}$ makes the signs alternate
          ○ the radical part follows $\sqrt{0},\,\sqrt{1},\,\sqrt{2},\,\sqrt{3},\,\sqrt{4},\,\ldots$




          

Ｆｉｎｄｉｎｇ　Ｓｅｑｕｅｎｃｅ　Ｎｏｔａｔｉｏｎ　Ｆｒｏｍ　Ａ　Ｌｉｓｔ　Ｏｆ　Ｔｅｒｍｓ

● Determining the notation of a sequence from a list of terms.
     ◉ General strategy:
          ○ 1. Rewrite the given terms in a uniform form, if possible.
          ○ 2. Relate each part of the term to the index $n$.
          ○ 3. Move from the specific pattern to the general formula.

● Pattern-identification strategies.
     ◉ Look for:
          ○ numerator patterns
          ○ denominator patterns
          ○ alternating signs
          ○ radicals
          ○ factorials

● [20:06](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=1206). 🧩 Example 3 — Finding the sequence notation from a list of terms: $2,\,\dfrac{3}{\sqrt{2}},\,\dfrac{4}{\sqrt{3}},\,\dfrac{5}{2},\,\ldots$ [📷image](../img/Calculus 2 Lecture 9.1/[20-06]-01.png)
     ◉ Step 1. Rewrite the given terms in a uniform form, if possible.
          $\rule{0pt}{}$
          ○ $a_{1}=2$
          $\rule{0pt}{}$
          ○ $a_{2}=\dfrac{3}{\sqrt{2}}$
          $\rule{0pt}{}$
          ○ $a_{3}=\dfrac{4}{\sqrt{3}}$
          $\rule{0pt}{}$
          ○ $a_{4}=\dfrac{5}{2}$
          $\rule{0pt}{}$
     ◉ Step 2. Relate each part of the term to the index $n$.
          $\rule{0pt}{}$
          ○ $a_{1}=2\;\;\to\;\;\dfrac{2}{\sqrt{1}}$
          $\rule{0pt}{}$
          ○ $a_{2}=\dfrac{3}{\sqrt{2}}\;\;\to\;\;\dfrac{3}{\sqrt{2}}$
          $\rule{0pt}{}$
          ○ $a_{3}=\dfrac{4}{\sqrt{3}}\;\;\to\;\;\dfrac{4}{\sqrt{3}}$
          $\rule{0pt}{}$
          ○ $a_{4}=\dfrac{5}{2}\;\;\to\;\;\dfrac{5}{\sqrt{4}}$
          $\rule{0pt}{}$
     ◉ Step 3. Move from the specific pattern to the general formula.
          $\rule{0pt}{}$
          ○ $a_{1}=2\;\;\to\;\;\dfrac{2}{\sqrt{1}}\;\;\to\;\;\dfrac{1+1}{\sqrt{1}}$
          $\rule{0pt}{}$
          ○ $a_{2}=\dfrac{3}{\sqrt{2}}\;\;\to\;\;\dfrac{3}{\sqrt{2}}\;\;\to\;\;\dfrac{2+1}{\sqrt{2}}$
          $\rule{0pt}{}$
          ○ $a_{3}=\dfrac{4}{\sqrt{3}}\;\;\to\;\;\dfrac{4}{\sqrt{3}}\;\;\to\;\;\dfrac{3+1}{\sqrt{3}}$
          $\rule{0pt}{}$
          ○ $a_{4}=\dfrac{5}{2}\;\;\to\;\;\dfrac{5}{\sqrt{4}}\;\;\to\;\;\dfrac{4+1}{\sqrt{4}}$
          $\rule{0pt}{}$
          ○ Pattern identification:
               ■ numerator = $n+1$
               ■ denominator = $\sqrt{n}$
               ■ General formula:
               $\rule{0pt}{}$
                    ▣ $a_{n}=\dfrac{n+1}{\sqrt{n}}$

● [23:30](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=1410). 🧩 Example 4 — Finding the sequence notation from a list of terms: $-1,\,\dfrac{1}{2},\,-\dfrac{1}{6},\,\dfrac{1}{24},\,-\dfrac{1}{120},\,\ldots$ [📷image](../img/Calculus 2 Lecture 9.1/[23-30]-01.png)
     ◉ Step 1. Identify the sign pattern.
          $\rule{0pt}{}$
          ○ $a_{1}=-1\;\;\to\;\;\text{negative}$
          $\rule{0pt}{}$
          ○ $a_{2}=\dfrac{1}{2}\;\;\to\;\;\text{positive}$
          $\rule{0pt}{}$
          ○ $a_{3}=-\dfrac{1}{6}\;\;\to\;\;\text{negative}$
          $\rule{0pt}{}$
          ○ $a_{4}=\dfrac{1}{24}\;\;\to\;\;\text{positive}$
          $\rule{0pt}{}$
          ○ $a_{5}=-\dfrac{1}{120}\;\;\to\;\;\text{negative}$
          $\rule{0pt}{}$
     ◉ Step 2. Rewrite the denominators in factorial form.
          $\rule{0pt}{}$
          ○ $a_{1}=-1\;\;\to\;\;-\dfrac{1}{1}$
          $\rule{0pt}{}$
          ○ $a_{2}=\dfrac{1}{2}\;\;\to\;\;\dfrac{1}{2\cdot 1}$
          $\rule{0pt}{}$
          ○ $a_{3}=-\dfrac{1}{6}\;\;\to\;\;-\dfrac{1}{3\cdot 2\cdot 1}$
          $\rule{0pt}{}$
          ○ $a_{4}=\dfrac{1}{24}\;\;\to\;\;\dfrac{1}{4\cdot 3\cdot 2\cdot 1}$
          $\rule{0pt}{}$
          ○ $a_{5}=-\dfrac{1}{120}\;\;\to\;\;-\dfrac{1}{5\cdot 4\cdot 3\cdot 2\cdot 1}$
          $\rule{0pt}{}$
     ◉ Step 3. Move from the specific pattern to the general formula.
          $\rule{0pt}{}$
          ○ $a_{1}=-1\;\;\to\;\;-\dfrac{1}{1}\;\;\to\;\;-\dfrac{1}{1!}$
          $\rule{0pt}{}$
          ○ $a_{2}=\dfrac{1}{2}\;\;\to\;\;\dfrac{1}{2\cdot 1}\;\;\to\;\;\dfrac{1}{2!}$
          $\rule{0pt}{}$
          ○ $a_{3}=-\dfrac{1}{6}\;\;\to\;\;-\dfrac{1}{3\cdot 2\cdot 1}\;\;\to\;\;-\dfrac{1}{3!}$
          $\rule{0pt}{}$
          ○ $a_{4}=\dfrac{1}{24}\;\;\to\;\;\dfrac{1}{4\cdot 3\cdot 2\cdot 1}\;\;\to\;\;\dfrac{1}{4!}$
          $\rule{0pt}{}$
          ○ $a_{5}=-\dfrac{1}{120}\;\;\to\;\;-\dfrac{1}{5\cdot 4\cdot 3\cdot 2\cdot 1}\;\;\to\;\;-\dfrac{1}{5!}$
          $\rule{0pt}{}$
          ○ the sign alternates
          ○ the numerator is always $\pm 1$
          ○ the denominator is $n!$
          ○ since the sequence starts with a negative term,
               ■ use $(-1)^{n}$ for the sign pattern
     ◉ General formula:
          $\rule{0pt}{}$
          ○ $a_{n}=\dfrac{(-1)^{n}}{n!}$




          

Ｒｅｃｕｒｓｉｖｅ　Ｓｅｑｕｅｎｃｅｓ

● Recursive sequences.
     ◉ A recursive sequence is defined using previous terms.
     ◉ To generate a new term,
          ○ use the given initial values
          ○ and apply the recursive formula to the preceding terms

● [36:40](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=2200). 🧩 Example 5 — Recursive sequence. [📷image](../img/Calculus 2 Lecture 9.1/[36-40]-01.png)
     ◉ Given:
          $\rule{0pt}{}$
          ○ $a_{1}=2$
          $\rule{0pt}{}$
          ○ $a_{2}=4$
          $\rule{0pt}{}$
          ○ $a_{n+1}=2a_{n}-a_{n-1}$
          $\rule{0pt}{}$
     ◉ Idea:
          ○ each new term is built from previous terms
          ○ this is a recursive sequence
     ◉ Generate the next terms:
          $\rule{0pt}{}$
          ○ $a_{3}=2a_{2}-a_{1}\;\;\to\;\;2(4)-2\;\;\to\;\;6$
          $\rule{0pt}{}$
          ○ $a_{4}=2a_{3}-a_{2}\;\;\to\;\;2(6)-4\;\;\to\;\;8$
          $\rule{0pt}{}$
          ○ $a_{5}=2a_{4}-a_{3}\;\;\to\;\;2(8)-6\;\;\to\;\;10$
          $\rule{0pt}{}$
     ◉ First generated terms:
          $\rule{0pt}{}$
          ○ $2,\,4,\,6,\,8,\,10,\,\ldots$




          

Ｌｉｍｉｔｓ　Ｏｆ　Ｓｅｑｕｅｎｃｅｓ　—　Ｃｏｎｖｅｒｇｅｎｃｅ　＆　Ｄｉｖｅｒｇｅｎｃｅ

● [43:42](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=2622). Limit of a sequence. [📷image](../img/Calculus 2 Lecture 9.1/[43-42]-01.png)
     ◉ A sequence $\{a_{n}\}$ has a limit if the terms approach a single value as $n\to\infty$.
     ◉ Notation:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty} a_{n}$
          $\rule{0pt}{}$
     ◉ Main idea:
          ○ the goal is to study what happens to $a_{n}$ as $n\to\infty$

● Convergence.
     ◉  i̲f̲ $\displaystyle \lim_{n\to\infty} a_{n}$ exists and equals a real number,
     $\rule{0pt}{}$
          ○ t̲h̲e̲n̲ the sequence is convergent.

● Divergence.
     ◉ i̲f̲  the limit does not exist,
          ○ o̲r̲  i̲f̲ the sequence tends to $+\infty$ or $-\infty$,
               ■ t̲h̲e̲n̲ the sequence is divergent.




               

Ｐｒｏｐｅｒｔｉｅｓ　Ｏｆ　Ｌｉｍｉｔｓ　Ｏｆ　Ｓｅｑｕｅｎｃｅｓ

● [46:40](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=2800). Properties of limits of sequences. [📷image](../img/Calculus 2 Lecture 9.1/[46-40]-01.png)
     ◉ Constant multiple:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}(c\cdot a_{n})=c\displaystyle \lim_{n\to\infty} a_{n}$
          $\rule{0pt}{}$
     ◉ Sum:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}(a_{n}+b_{n})=\displaystyle \lim_{n\to\infty} a_{n}+\displaystyle \lim_{n\to\infty} b_{n}$
          $\rule{0pt}{}$
     ◉ Product:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}(a_{n}\cdot b_{n})=\left(\displaystyle \lim_{n\to\infty} a_{n}\right)\cdot\left(\displaystyle \lim_{n\to\infty} b_{n}\right)$
          $\rule{0pt}{}$
     ◉ Quotient:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\left(\dfrac{a_{n}}{b_{n}}\right)=\dfrac{\displaystyle \lim_{n\to\infty} a_{n}}{\displaystyle \lim_{n\to\infty} b_{n}}$
          $\rule{0pt}{}$
     ◉ Power rule:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}(a_{n})^{p}=\left(\displaystyle \lim_{n\to\infty} a_{n}\right)^{p}$
          $\rule{0pt}{}$
          ○ valid when $a_{n}>0$ and $p>0$




     

Ｔｅｓｔｉｎｇ　Ｃｏｎｖｅｒｇｅｎｃｅ　Ｂｙ　Ｅｖａｌｕａｔｉｎｇ　Ｌｉｍｉｔｓ

● [📷image-1](../img/Calculus 2 Lecture 9.1/[50-39]-01.png) [📷image-2](../img/Calculus 2 Lecture 9.1/[50-39]-02.png)

● [50:39](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=3039). 🧩 Example 1 — Oscillating sequence: $a_{n}=(-1)^{n}$.
     ◉ Terms:
          $\rule{0pt}{}$
          ○ $-1,\,1,\,-1,\,1,\,-1,\,\ldots$
     ◉ Conclusion:
          ○ the sequence oscillates and does not approach a single number
          ○ therefore it diverges

● [52:52](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=3172). 🧩 Example 2 — Sequence: $a_{n}=\dfrac{2n}{n+1}$.
     ◉ Take the limit:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{2n}{n+1}$
          $\rule{0pt}{}$
     ◉ Simplify by dividing by the highest power of $n$ in the denominator:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{2n/n}{(n+1)/n}$
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{2}{1+\dfrac{1}{n}}$
          $\rule{0pt}{}$
     ◉ Limit:
          $\rule{0pt}{}$
          ○ $2$
     ◉ Conclusion:
          ○ the sequence converges to $2$

● [56:51](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=3411). 🧩 Example 3 — Sequence: $a_{n}=\dfrac{2+(-1)^{n}}{n}$.
     ◉ Take the limit:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{2+(-1)^{n}}{n}$
          $\rule{0pt}{}$
     ◉ Rewrite:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\left[\dfrac{2}{n}+\dfrac{(-1)^{n}}{n}\right]$
          $\rule{0pt}{}$
     ◉ Key observation:
     $\rule{0pt}{}$
          ○ $\dfrac{2}{n}\to 0$
          $\rule{0pt}{}$
          ○ $\dfrac{(-1)^{n}}{n}\to 0$
          $\rule{0pt}{}$
     ◉ Conclusion:
          ○ the sequence converges to $0$

● [1:01:01](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=3661). 🧩 Example 4 — Sequence: $a_{n}=\dfrac{\ln(n)}{n}$.
     ◉ Take the limit:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{\ln(n)}{n}$
          $\rule{0pt}{}$
     ◉ Apply L'Hôpital's Rule:
          $\rule{0pt}{}$
          ○ $\dfrac{d}{dn}[\ln(n)]=\dfrac{1}{n}$
          $\rule{0pt}{}$
          ○ $\dfrac{d}{dn}[n]=1$
          $\rule{0pt}{}$
     ◉ Result:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{(1/n)}{1}=0$
          $\rule{0pt}{}$
     ◉ Conclusion:
          ○ the sequence converges to $0$

● [1:03:08](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=3788). 🧩 Example 5 — Difference of radicals: $a_{n}=\sqrt{n+1}-\sqrt{n}$
     ◉ Technique:
          ○ multiply by the conjugate
     ◉ Transformation:
          $\rule{0pt}{}$
          ○ $\left[\sqrt{n+1}-\sqrt{n}\right]\cdot\dfrac{\sqrt{n+1}+\sqrt{n}}{\sqrt{n+1}+\sqrt{n}}$
          $\rule{0pt}{}$
          ○ $=\dfrac{(n+1)-n}{\sqrt{n+1}+\sqrt{n}}$
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{\sqrt{n+1}+\sqrt{n}}$
          $\rule{0pt}{}$
     ◉ Result:
          ○ the limit is $0$
     ◉ Conclusion:
          ○ the sequence converges to $0$

          

Ｓｑｕｅｅｚｅ　Ｔｈｅｏｒｅｍ　Ｆｏｒ　Ｓｅｑｕｅｎｃｅｓ

● [1:07:42](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=4062). Squeeze Theorem. [📷image](../img/Calculus 2 Lecture 9.1/[1-07-42]-01.png)
     ◉ i̲f̲ 
          $\rule{0pt}{}$
          ○ $a_{n}\le b_{n}\le c_{n}$
          $\rule{0pt}{}$
     ◉ a̲n̲d̲
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty} a_{n}=\displaystyle \lim_{n\to\infty} c_{n}=L$
          $\rule{0pt}{}$
     ◉ t̲h̲e̲n̲
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty} b_{n}=L$

● [1:11:06](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=4266). 🧩 Example — Sequence: $a_{n}=\dfrac{n!}{n^{n}}$. [📷image](../img/Calculus 2 Lecture 9.1/[1-11-00]-01.png)
     ◉ First observation:
          $\rule{0pt}{}$
          ○ $0\le a_{n}$
          $\rule{0pt}{}$
     ◉ Key comparison:
          $\rule{0pt}{}$
          ○ $n!=n(n-1)(n-2)\cdots 2\cdot 1$
          $\rule{0pt}{}$
          ○ $n!$ has $n$ factors
          ○ the last factor is $1$
          ○ since $1\le n$,
               ■ it is not necessary to compare that last factor with another extra $n$
               ■ therefore the estimate can be sharpened to
                    ▣ $n!\le n^{n-1}$
     ◉ Divide by $n^{n}$:
          $\rule{0pt}{}$
          ○ $\dfrac{n!}{n^{n}}\le \dfrac{n^{n-1}}{n^{n}}=\dfrac{1}{n}$
          $\rule{0pt}{}$
     ◉ Apply the Squeeze Theorem:
          $\rule{0pt}{}$
          ○ $0\le a_{n}\le \dfrac{1}{n}$
          $\rule{0pt}{}$
          ○ and $\dfrac{1}{n}\to 0$ as $n\to\infty$
          $\rule{0pt}{}$
          ○ therefore
               ■ $a_{n}\to 0$
     ◉ Conclusion:
          ○ the sequence converges to $0$


          


Ａｂｓｏｌｕｔｅ　Ｖａｌｕｅ　Ｔｈｅｏｒｅｍ　Ｆｏｒ　Ｓｅｑｕｅｎｃｅｓ

● [1:27:35](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=5255). Absolute value theorem. [📷image](../img/Calculus 2 Lecture 9.1/[1-27-35]-01.png)
$\rule{0pt}{}$
     ◉ i̲f̲  $\displaystyle \lim_{n\to\infty}|𝒂_{n}|=0$
     $\rule{0pt}{}$
          ○ t̲h̲e̲n̲ $\displaystyle \lim_{n\to\infty} 𝒂_{n}=0$

● [1:29:01](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=5341). 🧩 Example — Sequence: $𝒂_{n}=\dfrac{(-1)^{n}}{𝒏}$. [📷image](../img/Calculus 2 Lecture 9.1/[1-29-01]-01.png)
     ◉ Absolute value:
          $\rule{0pt}{}$
          ○ $\left|\dfrac{(-1)^{n}}{𝒏}\right|=\dfrac{1}{𝒏}$
          $\rule{0pt}{}$
     ◉ Since
     $\rule{0pt}{}$
          ○ $\dfrac{1}{𝒏}\to 0,$
               ■ it follows that $\dfrac{(-1)^{n}}{𝒏}\to 0$
     ◉ Conclusion:
          ○ the sequence converges




          

Ｃｏｎｔｉｎｕｏｕｓ　Ｆｕｎｃｔｉｏｎｓ　＆　Ｓｅｑｕｅｎｃｅ　Ｌｉｍｉｔｓ

● [1:31:10](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=5470). Limit of sequences inside continuous functions. [📷image](../img/Calculus 2 Lecture 9.1/[1-31-10]-01.png)
     ◉ i̲f̲ $𝒇$ is continuous and $\displaystyle \lim_{n\to\infty} 𝒂_{n}=L$
     $\rule{0pt}{}$
          ○ t̲h̲e̲n̲ $\displaystyle \lim_{n\to\infty} 𝒇(𝒂_{n})=𝒇\left(\displaystyle \lim_{n\to\infty} 𝒂_{n}\right)=𝒇(L)$
          $\rule{0pt}{}$
     ◉ Idea:
          ○ if a sequence $a_{n}$ approaches a number $L$, and $𝒇$ is continuous, then you can “bring the limit inside the function.”


● [1:33:49](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=5629). 🧩 Example — Sequence: $e^{\sin(1/n)}$. [📷image](../img/Calculus 2 Lecture 9.1/[1-33-49]-01.png)
     ◉ Apply the theorem:
          ○ i̲f̲ $𝒇$ is continuous and $\displaystyle \lim_{n\to\infty} 𝒂_{n}=𝑳$
          $\rule{0pt}{}$
               ■ t̲h̲e̲n̲ $\displaystyle \lim_{n\to\infty} 𝒇(𝒂_{n})=𝒇\left(\displaystyle \lim_{n\to\infty} 𝒂_{n}\right)=𝒇(𝑳)$
               $\rule{0pt}{}$
     ◉ Identify the parts:
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=e^{x}$
          $\rule{0pt}{}$
          ○ $𝒂_{n}=\sin\left(\dfrac{1}{n}\right)$
          $\rule{0pt}{}$
          ○ $𝒇(𝒂_{n})=e^{\sin(1/n)}$
          $\rule{0pt}{}$
     ◉ Since
     $\rule{0pt}{}$
          ○ $\dfrac{1}{n}\to 0$
          $\rule{0pt}{}$
          ○ $\sin\left(\dfrac{1}{n}\right)\to \sin(0)=0$
          $\rule{0pt}{}$
               ■ so $\displaystyle \lim_{n\to\infty} 𝒂_{n}=0$
               $\rule{0pt}{}$
     ◉ Substitute into the theorem:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty} 𝒇(𝒂_{n})\;=\;𝒇\left(\displaystyle \lim_{n\to\infty} 𝒂_{n}\right)\;=\;𝒇(𝑳)$
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty} e^{\sin(1/n)}=e^{\left(\displaystyle \lim_{n\to\infty}\sin(1/n)\right)}=𝒇(0)=e^{0}=1$
          $\rule{0pt}{}$
     ◉ Conclusion:
          ○ the sequence converges to $1$

● [1:36:02](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=5762). 🧩 Example — Sequence: $\tan^{-1}(𝒏^{2})$. [📷image](../img/Calculus 2 Lecture 9.1/[1-36-02]-01.png)
     ◉ Apply the theorem:
     $\rule{0pt}{}$
          ○ i̲f̲ $𝒇$ is continuous and $\displaystyle \lim_{n\to\infty} 𝒂_{n}=𝑳$
          $\rule{0pt}{}$
               ■ t̲h̲e̲n̲ $\displaystyle \lim_{n\to\infty} 𝒇(𝒂_{n})=𝒇\left(\displaystyle \lim_{n\to\infty} 𝒂_{n}\right)=𝒇(𝑳)$
               $\rule{0pt}{}$
     ◉ Identify the parts:
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\tan^{-1}(𝒙)$
          $\rule{0pt}{}$
          ○ $𝒂_{n}=n^{2}$
          $\rule{0pt}{}$
          ○ $𝒇(𝒂_{n})=\tan^{-1}(n^{2})$
          $\rule{0pt}{}$
     ◉ Since
          ○ $n^{2}\to \infty$
               ■ so $\displaystyle \lim_{n\to\infty} 𝒂_{n}=\infty$
               $\rule{0pt}{}$
               ■ hence $𝑳=\infty$
     ◉ Substitute into the theorem:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty} 𝒇(𝒂_{n})=𝒇\left(\displaystyle \lim_{n\to\infty} 𝒂_{n}\right)=𝒇(𝑳)$
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\tan^{-1}(n^{2})=\tan^{-1}\left(\displaystyle \lim_{n\to\infty} n^{2}\right)=𝒇(\infty)=\tan^{-1}(\infty)=\dfrac{\pi}{2}$
          $\rule{0pt}{}$
     ◉ Conclusion:
          ○ the sequence converges to $\dfrac{\pi}{2}$




               

Ｍｏｎｏｔｏｎｉｃ　Ｓｅｑｕｅｎｃｅｓ

● [1:37:58](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=5878). Monotonic sequences. [📷image](../img/Calculus 2 Lecture 9.1/[1-37-58]-01.png)
     ◉ A monotonic sequence is one that is always:
          ○ increasing
          ○ or decreasing

● Ways to **prove** monotonicity.
     ◉ Method 1:
          ○ compare $𝒂_{n}$ and $𝒂_{n+1}$ directly
          ○ To prove increasing:
          $\rule{0pt}{}$
               ■ show $𝒂_{n}\le 𝒂_{n+1}$
               $\rule{0pt}{}$
          ○ To prove decreasing:
          $\rule{0pt}{}$
               ■ show $𝒂_{n+1}\le 𝒂_{n}$
               $\rule{0pt}{}$
     ◉ Method 2:
          ○ Use the derivative of an associated function,
               ■ associate the sequence with a function $𝒇(𝒙)$
          ○ **First, look at where the sequence starts.**
          ○ **Then use that to determine the relevant domain of the associated function.**
          ○ Next, check the sign of $𝒇'(𝒙)$ on that domain.
          ○ If you prove that $𝒇$ is increasing on the interval containing all those $n$-values,
               ■ then the sequence is also increasing.
               $\rule{0pt}{}$
          ○ i̲f̲ $𝒇'(𝒙)>0$ on the relevant domain,
               ■ t̲h̲e̲n̲ the sequence is increasing
               $\rule{0pt}{}$
          ○ i̲f̲ $𝒇'(𝒙)<0$ on the relevant domain,
               ■ t̲h̲e̲n̲ the sequence is decreasing

● [1:41:10 ](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=6070). 🧩 Example — Show that $𝒂_{n}=\dfrac{𝒏}{𝒏+1}$ is increasing. [📷image](../img/Calculus 2 Lecture 9.1/[1-41-10 ]-01.png)
     ◉ Method 1 — Compare consecutive terms.
          ○ To show that the sequence is increasing, it is enough to prove that
          $\rule{0pt}{}$
               ■ $a_{n}\le a_{n+1}$
               $\rule{0pt}{}$
          ○ So show that
          $\rule{0pt}{}$
               ■ $\dfrac{n}{n+1}\le \dfrac{n+1}{n+2}$
               $\rule{0pt}{}$
          ○ Cross-multiply:
          $\rule{0pt}{}$
               ■ $n(n+2)\le (n+1)(n+1)$
               $\rule{0pt}{}$
          ○ Expand both sides:
          $\rule{0pt}{}$
               ■ $n^{2}+2n\le n^{2}+2n+1$
               $\rule{0pt}{}$
          ○ This is true for all $n\ge 1$.
          ○ Therefore
               ■ $a_{n}$ is increasing
     ◉ [1:47:42](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=6462). Method 2 — Use the associated function.
          ○ Define
          $\rule{0pt}{}$
               ■ $𝒇(𝒙)=\dfrac{x}{x+1}$
               $\rule{0pt}{}$
          ○ Differentiate:
          $\rule{0pt}{}$
               ■ $𝒇'(𝒙)=\dfrac{(x+1)-x}{(x+1)^{2}}$
               $\rule{0pt}{}$
               ■ $𝒇'(𝒙)=\dfrac{1}{(x+1)^{2}}$
               $\rule{0pt}{}$
          ○ The relevant domain is determined by the sequence.
               ■ Since the sequence is defined for $n\ge 1$, we check $𝒇'(𝒙)$ on $x\ge 1$.
          ○ Since
               ■ $𝒇'(𝒙)\ge 0$ for $x\ge 1$,
          ○ it follows that
               ■ $𝒇$ is increasing on $[1,\infty)$
          ○ Because the sequence uses the inputs $n=1,2,3,\ldots$
               ■ $a_{n}=𝒇(n)$ also increases
          ○ Therefore:
               ■ i̲f̲ $𝒇'(𝒙)>0$ on the relevant domain,
                    ▣ t̲h̲e̲n̲ the sequence is increasing
                    ▣ the sequence $a_{n}=\dfrac{n}{n+1}$ is increasing

     
● [1:55:01](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=6901). 🧩 Example — Analyze $𝒇(𝒙)=\dfrac{𝒙}{e^{x}}$. [📷image](../img/Calculus 2 Lecture 9.1/[1-55-01]-01.png)
     ◉ Associate the sequence with the function:
          $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{n}{e^{n}}$
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\dfrac{𝒙}{e^{x}}$
          $\rule{0pt}{}$
     ◉ Relevant domain:
          ○ Since the sequence starts at $n=1$,
               ■ we study $𝒇(𝒙)$ on $[1,\infty)$
     ◉ Derivative:
          $\rule{0pt}{}$
          ○ $𝒇'(𝒙)=\dfrac{1-𝒙}{e^{x}}$
          $\rule{0pt}{}$
     ◉ Sign of the derivative on the relevant domain:
          ○ Since $e^{x}>0$ for every $𝒙$,
               ■ the sign of $𝒇'(𝒙)$ depends only on $1-𝒙$
               $\rule{0pt}{}$
          ○ If $𝒙\ge 1$, then $1-𝒙\le 0$
          $\rule{0pt}{}$
          ○ Therefore $𝒇'(𝒙)\le 0$ for $𝒙\ge 1$
          $\rule{0pt}{}$
     ◉ Conclusion:
     $\rule{0pt}{}$
          ○ i̲f̲ $𝒇'(𝒙)<0$ on the relevant domain,
               ■ t̲h̲e̲n̲ the sequence is decreasing
               ■ $𝒇$ is decreasing on $[1,\infty)$
          ○ therefore the associated sequence $\left\{\dfrac{n}{e^{n}}\right\}$ is decreasing




          

Ｂｏｕｎｄｅｄ　Ｓｅｑｕｅｎｃｅｓ

● [2:00:11](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=7211). Bounded sequences. [📷image](../img/Calculus 2 Lecture 9.1/[2-00-11]-01.png)
     ◉ Bounded above:
          $\rule{0pt}{}$
          ○ $𝒂_{n}\le 𝑴$
          $\rule{0pt}{}$
     ◉ Bounded below:
          $\rule{0pt}{}$
          ○ $𝒂_{n}\ge 𝒎$
          $\rule{0pt}{}$
     ◉ Bounded:
          $\rule{0pt}{}$
          ○ $𝒎\le 𝒂_{n}\le 𝑴$




          

Ｍｏｎｏｔｏｎｉｃ　Ｓｅｑｕｅｎｃｅ　Ｔｈｅｏｒｅｍ

● [2:03:45](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=7425). Monotonic Sequence Theorem.
     ◉ i̲f̲ a sequence is monotonic and bounded,
          ○ t̲h̲e̲n̲ it converges
     ◉ More specifically:
          ○ increasing + bounded above ⇒ convergent
          ○ decreasing + bounded below ⇒ convergent

● [2:08:44](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=7724). 🧩 Example — Show that $𝒂_{n}=\dfrac{2^{n}}{𝒏!}$ is convergent. [📷image-1](../img/Calculus 2 Lecture 9.1/[2-08-44]-01.png) [📷image-2](../img/Calculus 2 Lecture 9.1/[2-08-44]-02.png)
     ◉ If we write out some terms, it appears that the sequence is decreasing.
     ◉ [2:11:05](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=7865). To determine whether a sequence is monotonic:
          ○ Decreasing sequence:
               ■ $𝒂_{n}\ge 𝒂_{n+1}$
               ■ equivalently, $𝒂_{n+1}\le 𝒂_{n}$
               ■ if the sequence is positive, equivalently, $\dfrac{𝒂_{n+1}}{𝒂_{n}}\le 1$
     ◉ [2:13:05](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=7985). Determine whether $𝒂_{n}=\dfrac{2^{n}}{𝒏!}$ is decreasing:
          $\rule{0pt}{}$
          ○ $\dfrac{𝒂_{n+1}}{𝒂_{n}}=\dfrac{\left(2^{n+1}/(n+1)!\right)}{\left(2^{n}/n!\right)}$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒂_{n+1}}{𝒂_{n}}=\left(\dfrac{2^{n+1}}{(n+1)!}\right)\cdot\left(\dfrac{n!}{2^{n}}\right)$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒂_{n+1}}{𝒂_{n}}=\left(\dfrac{2\cdot 2^{n}}{(n+1)\cdot n!}\right)\cdot\left(\dfrac{n!}{2^{n}}\right)$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒂_{n+1}}{𝒂_{n}}=\dfrac{2}{n+1}$
          $\rule{0pt}{}$
          ○ $\dfrac{2}{n+1}\le 1$
          $\rule{0pt}{}$
               ■ true for $n\ge 1$
          ○ Result:
               ■ the sequence is decreasing
     ◉ [2:20:24](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=8424). Also:
          ○ Since $𝒂_{n}=\dfrac{2^{n}}{𝒏!}$ cannot be negative,
          $\rule{0pt}{}$
               ■ it must be bounded below by $0$
               ■ $𝒂_{n}$ is always positive
     ◉ By the Monotonic Sequence Theorem:
          ○ decreasing + bounded below ⇒ convergent
          ○ therefore the sequence is convergent




          

Ｇｅｏｍｅｔｒｉｃ　Ｓｅｑｕｅｎｃｅｓ　𝒓ⁿ

● [2:23:45](https://www.youtube.com/watch?v=FoNLQvf4NUs&t=8625). Summary for geometric sequences $𝒓^{n}$. [📷image](../img/Calculus 2 Lecture 9.1/[2-23-45]-01.png)
     ◉ If $-1<𝒓<1$,
          ○ then $𝒓^{n}\to 0$
          ○ if $0<𝒓<1$,
               ■ the terms stay positive and approach $0$
          ○ if $-1<𝒓<0$,
               ■ the terms alternate in sign and approach $0$
     ◉ If $𝒓=1$,
          ○ then $𝒓^{n}\to 1$
     ◉ If $𝒓=-1$,
          ○ the sequence oscillates and diverges
     ◉ If $|𝒓|>1$,
          ○ the sequence diverges
          ○ if $𝒓>1$,
               ■ the terms grow without bound
          ○ if $𝒓<-1$,
               ■ the terms alternate in sign and their magnitudes grow without bound
          ○ NOTE:
               ■ First define the absolute value:
                    ▣ $|𝒓|=𝒓,\;\;\text{if }𝒓\ge 0$
                    ▣ $|𝒓|=-𝒓,\;\;\text{if }𝒓<0$
               ■ Then solve $|𝒓|>1$ by cases:
                    ▣ If $𝒓\ge 0$, then $|𝒓|=𝒓$
                         ▢ so $𝒓>1$
                    ▣ If $𝒓<0$, then $|𝒓|=-𝒓$
                         ▢ so $-𝒓>1$
                         ▢ therefore $𝒓<-1$
               ■ Conclusion:
                    ▣ $|𝒓|>1$ means $𝒓>1$ or $𝒓<-1$
     ◉ Therefore:
          ○ **the sequence $\{𝒓^{n}\}$ converges if and only if $-1<𝒓\le 1$**





Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Sequences
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/5-1-sequences)