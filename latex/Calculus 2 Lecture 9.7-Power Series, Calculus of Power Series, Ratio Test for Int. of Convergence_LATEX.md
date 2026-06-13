-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ９．７： Ｐｏｗｅｒ Ｓｅｒｉｅｓ， Ｃａｌｃｕｌｕｓ ｏｆ Ｐｏｗｅｒ Ｓｅｒｉｅｓ， Ｒａｔｉｏ Ｔｅｓｔ ｆｏｒ Ｉｎｔ． ｏｆ Ｃｏｎｖｅｒｇｅｎｃｅ**-------------------------------—






１ - Ｉｎｔｒｏｄｕｃｔｉｏｎ　ｔｏ　Ｐｏｗｅｒ　Ｓｅｒｉｅｓ


● [📷image](../img/Calculus 2 Lecture 9.7/[0-16]-01.png)

● [0:01](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=1). Introduction to power series.
     ◉ Main idea:
          ○ previous sections on series were needed in order to understand power series.
     ◉ A power series is:
          ○ a series with a **variable**,
          ○ usually $𝒙$,
          ○ raised to powers depending on $n$.

● [0:16](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=16). Definition of a power series.
     ◉ A power series is:
          ○ a series with a **variable $𝒙$** raised to some power.
     ◉ The power is usually based on:
          ○ the index $n$.
     ◉ General idea:
          ○ instead of having only numerical terms,
          ○ we now have terms involving $𝒙$.

● [1:04](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=64). The exponent depends on $n$.
     ◉ In a power series:
          ○ the exponent changes as $n$ changes.
     ◉ Typical form:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}𝒂_{n}𝒙^{n}$
          $\rule{0pt}{}$
     ◉ Here:
          ○ $𝒂_{n}$ gives the coefficient.
          ○ $𝒙^{n}$ gives the power part.
     ◉ Important:
          ○ the variable is $𝒙$,
          ○ but the exponent is controlled by $n$.


● [1:29](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=89). Two main types of power series.
     ◉ Type 1:
          ○ power series centered at the origin.
          ○ centered at $0$.
     ◉ Type 2:
          ○ power series centered at a constant $𝑪$.
          ○ centered at $𝑪$ instead of $0$.




１．１ - Ｐｏｗｅｒ　Ｓｅｒｉｅｓ　Ｃｅｎｔｅｒｅｄ　ａｔ　ｔｈｅ　Ｏｒｉｇｉｎ

● [📷image](../img/Calculus 2 Lecture 9.7/[1-35]-01.png)

● [1:35](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=95). Type 1 — Power series centered at zero.
     ◉ General form:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}𝒂_{n}𝒙^{n}$
          $\rule{0pt}{}$
     ◉ This is centered at:
          ○ $0$ (origin)
     ◉ Reason:
          ○ nothing is added to or subtracted from $𝒙$.
     ◉ We can think of it as:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}𝒂_{n}(𝒙-0)^{n}$


● [2:57](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=177). Expanding the first few terms.
     ◉ Start with:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}𝒂_{n}𝒙^{n}$
          $\rule{0pt}{}$
     ◉ Plug in $n=0$:
          $\rule{0pt}{}$
          ○ $𝒂_{0}𝒙^{0}=𝒂_{0}$
          $\rule{0pt}{}$
     ◉ Plug in $n=1$:
          $\rule{0pt}{}$
          ○ $𝒂_{1}𝒙$
          $\rule{0pt}{}$
     ◉ Plug in $n=2$:
          $\rule{0pt}{}$
          ○ $𝒂_{2}𝒙^{2}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}𝒂_{n}𝒙^{n}=𝒂_{0}+𝒂_{1}𝒙+𝒂_{2}𝒙^{2}+𝒂_{3}𝒙^{3}+\cdots$

● N̲O̲T̲E̲ — Why this is centered at $0$.
     ◉ The center is the number subtracted from $𝒙$.
     ◉ In:
          $\rule{0pt}{}$
          ○ $𝒙^{n}$
          $\rule{0pt}{}$
     ◉ we can rewrite:
          $\rule{0pt}{}$
          ○ $𝒙^{n}=(𝒙-0)^{n}$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ the center is $0$.



１．２ - Ｐｏｗｅｒ　Ｓｅｒｉｅｓ　Ｃｅｎｔｅｒｅｄ　ａｔ  $𝑪$

● [📷image](../img/Calculus 2 Lecture 9.7/[5-11]-01.png)

● [5:11](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=311). Type 2 — Power series centered at a constant $𝑪$.
     ◉ General form:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}𝒂_{n}(𝒙-𝑪)^{n}$
          $\rule{0pt}{}$
     ◉ This is centered at:
          ○ $𝑪$
     ◉ Here:
          ○ $𝑪$ is a constant.
          ○ $𝒙$ is the variable.

● [5:32](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=332). First few terms of a shifted power series.
     ◉ Start with:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}𝒂_{n}(𝒙-𝑪)^{n}$
          $\rule{0pt}{}$
     ◉ Plug in $n=0$:
          $\rule{0pt}{}$
          ○ $𝒂_{0}(𝒙-𝑪)^{0}=𝒂_{0}$
          $\rule{0pt}{}$
     ◉ Plug in $n=1$:
          $\rule{0pt}{}$
          ○ $𝒂_{1}(𝒙-𝑪)$
          $\rule{0pt}{}$
     ◉ Plug in $n=2$:
          $\rule{0pt}{}$
          ○ $𝒂_{2}(𝒙-𝑪)^{2}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $𝒂_{0}+𝒂_{1}(𝒙-𝑪)+𝒂_{2}(𝒙-𝑪)^{2}+𝒂_{3}(𝒙-𝑪)^{3}+\cdots$


● [6:04](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=364). Identifying the center.
     ◉ In:
          $\rule{0pt}{}$
          ○ $(𝒙-𝑪)^{n}$
          $\rule{0pt}{}$
     ◉ the center is:
          ○ $𝑪$
     ◉ Example:
          ○ $(𝒙-3)^{n}$ is centered at $3$.
     ◉ Example:
          ○ $(𝒙+2)^{n}=(𝒙-(-2))^{n}$
          ○ so it is centered at $-2$.

● N̲O̲T̲E̲— The sign changes.
     ◉ The form is always:
          $\rule{0pt}{}$
          ○ $𝒙-𝑪$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ $𝒙-3$ means center $3$.
          ○ $𝒙+3$ means center $-3$.






2 - Ｅｘａｍｐｌｅｓ　ｏｆ　Ｐｏｗｅｒ　Ｓｅｒｉｅｓ


● [7:02](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=422). Examples of power series.
     ◉ Goal:
          ○ recognize the structure.
          ○ identify the center.
          ○ expand the first few terms.
          

2．１ Ｅｘａｍｐｌｅ  １

● [📷image](../img/Calculus 2 Lecture 9.7/[7-23]-01.png)

● [7:23](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=443). 🧩 Example 1 — Alternating power series centered at $0$: $\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}𝒙^{n}}{n!}$
     ◉ This is a power series because:
          ○ it contains **a variabke $𝒙$ raised to powers depending on $n$.**
     ◉ It is centered at:
          ○ $0$
     ◉ Reason:
          ○ the expression uses $𝒙^{n}$,
          ○ not $(𝒙-𝑪)^{n}$.


● [9:03](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=543). Expanding.
     ◉ Start with:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}𝒙^{n}}{n!}$
          $\rule{0pt}{}$
     ◉ Plug in $n=0$:
          $\rule{0pt}{}$
          ○ $\dfrac{(-1)^{0}𝒙^{0}}{0!}=1$
          $\rule{0pt}{}$
     ◉ Plug in $n=1$:
          $\rule{0pt}{}$
          ○ $\dfrac{(-1)^{1}𝒙^{1}}{1!}=-\dfrac{𝒙}{1!}$
          $\rule{0pt}{}$
     ◉ Plug in $n=2$:
          $\rule{0pt}{}$
          ○ $\dfrac{(-1)^{2}𝒙^{2}}{2!}=\dfrac{𝒙^{2}}{2!}$
          $\rule{0pt}{}$
     ◉ Plug in $n=3$:
          $\rule{0pt}{}$
          ○ $\dfrac{(-1)^{3}𝒙^{3}}{3!}=-\dfrac{𝒙^{3}}{3!}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $1-\dfrac{𝒙}{1!}+\dfrac{𝒙^{2}}{2!}-\dfrac{𝒙^{3}}{3!}+\dfrac{𝒙^{4}}{4!}-\cdots$


● N̲O̲T̲E̲ — Pattern in Example 1.
     ◉ The factor:
          $\rule{0pt}{}$
          ○ $(-1)^{n}$
          $\rule{0pt}{}$
     ◉ creates alternating signs:
          ○ $+,-,+,-,\dots$
     ◉ The power part:
          $\rule{0pt}{}$
          ○ $𝒙^{n}$
          $\rule{0pt}{}$
     ◉ makes it a power series.
     ◉ The factorial:
          $\rule{0pt}{}$
          ○ $n!$
          $\rule{0pt}{}$
     ◉ appears in the denominator.
     

2．2  Ｅｘａｍｐｌｅ  2

● [📷image](../img/Calculus 2 Lecture 9.7/[10-22]-01.png)
● [10:22](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=622). 🧩 Example 2 — Power series centered at $\dfrac{\pi}{4}$: $\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}(𝒙-\dfrac{\pi}{4})^{2n+1}}{(2n+1)!}$
     ◉ This is a power series because:
          ○ it contains the variable $𝒙$ raised to powers depending on $n$.
     ◉ It is centered at:
          ○ $\dfrac{\pi}{4}$
     ◉ Reason:
          ○ the variable part is $(𝒙-\dfrac{\pi}{4})$.

● [12:30](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=750). Expanding the first few terms.
     ◉ Start with:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}(𝒙-\dfrac{\pi}{4})^{2n+1}}{(2n+1)!}$
          $\rule{0pt}{}$
     ◉ Plug in $n=0$:
          $\rule{0pt}{}$
          ○ $\dfrac{(-1)^{0}(𝒙-\dfrac{\pi}{4})^{1}}{1!}=(𝒙-\dfrac{\pi}{4})$
          $\rule{0pt}{}$
     ◉ Plug in $n=1$:
          $\rule{0pt}{}$
          ○ $\dfrac{(-1)^{1}(𝒙-\dfrac{\pi}{4})^{3}}{3!}=-\dfrac{(𝒙-\dfrac{\pi}{4})^{3}}{3!}$
          $\rule{0pt}{}$
     ◉ Plug in $n=2$:
          $\rule{0pt}{}$
          ○ $\dfrac{(-1)^{2}(𝒙-\dfrac{\pi}{4})^{5}}{5!}=\dfrac{(𝒙-\dfrac{\pi}{4})^{5}}{5!}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}(𝒙-\dfrac{\pi}{4})^{2n+1}}{(2n+1)!}$
          $\rule{0pt}{}$
          ○ $=(𝒙-\dfrac{\pi}{4})-\dfrac{(𝒙-\dfrac{\pi}{4})^{3}}{3!}+\dfrac{(𝒙-\dfrac{\pi}{4})^{5}}{5!}-\cdots$


● N̲O̲T̲E̲ — Pattern.
     ◉ The factor:
          $\rule{0pt}{}$
          ○ $(-1)^{n}$
          $\rule{0pt}{}$
     ◉ creates the alternating signs:
          ○ $+,-,+,-,\dots$
     ◉ The exponent:
          $\rule{0pt}{}$
          ○ $2n+1$
          $\rule{0pt}{}$
     ◉ creates odd powers:
          ○ $1,3,5,7,\dots$
     ◉ The denominator:
          $\rule{0pt}{}$
          ○ $(2n+1)!$
          $\rule{0pt}{}$
     ◉ creates matching odd factorials:
          ○ $1!,3!,5!,7!,\dots$





3 - Ｐｏｗｅｒ　Ｓｅｒｉｅｓ　ａｓ　Ｆｕｎｃｔｉｏｎｓ

● [📷image](../img/Calculus 2 Lecture 9.7/[14-00]-01.png)

● [14:00](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=840). A++ power series defines a function.
     ◉ A power series contains the variable $𝒙$.
     ◉ Therefore:
          ○ it can define a function of $𝒙$.
     ◉ General function form:
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\displaystyle \sum_{n=0}^{\infty}𝒂_{n}(𝒙-𝑪)^{n}$


● [16:05](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=965). Domain of a power series function.
     ◉ The domain is:
          ○ the set of $𝒙$-values for which the series converges.
     ◉ Important:
          ○ not every $𝒙$-value necessarily works.
     ◉ For some values of $𝒙$:
          ○ the series converges.
     ◉ For other values of $𝒙$:
          ○ the series diverges.


● [16:47](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=1007). Input and output.
     ◉ Input:
          ○ a value of $𝒙$.
     ◉ After plugging in $𝒙$:
          ○ the power series becomes an ordinary numerical series.
     ◉ If that numerical series converges:
          ○ its sum becomes the output $𝒇(𝒙)$.
               ■ this only happens for values of $𝒙$ where the series converges.
     ◉ If that numerical series diverges:
          ○ there is no valid output for the function at that $𝒙$.

● N̲O̲T̲E̲ — Key interpretation.
     ◉ $𝒙$ is the input.
     ◉ The sum of the convergent series is the output.
     ◉ So:
          ○ $𝒇(𝒙)=$ sum of the power series.
     ◉ But this only works:
          ○ for $𝒙$-values inside the interval of convergence.





４ - Ｇｅｏｍｅｔｒｉｃ　Ｓｅｒｉｅｓ　ａｓ　ａ　Ｐｏｗｅｒ　Ｓｅｒｉｅｓ

● [📷image](../img/Calculus 2 Lecture 9.7/[21-46]-01.png)

● [21:46](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=1306). The most basic power series: $\displaystyle \sum_{n=0}^{\infty}𝒙^{n}$
     ◉ First few terms:
          ○ $1+𝒙+𝒙^{2}+𝒙^{3}+\cdots$
     ◉ This is a power series centered at:
          ○ $0$


● [22:23](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=1343). Geometric structure.
     ◉ A geometric series has form:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum 𝒂𝒓^{n}$
          $\rule{0pt}{}$
     ◉ A geometric series converges when:
          ○ $|𝒓|<1$

    
● [24:05](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=1445). The variable $𝒙$ acts as the common ratio.
     ◉ In the geometric series:
          ○ $𝒓$ is the common ratio.
     ◉ Here:
          ○ $𝒓=𝒙$
     ◉ Therefore:
          ○ the convergence depends on $𝒙$.


● [24:35](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=1475). Recognizing the geometric structure
     ◉ For:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}𝒙^{n}$
          $\rule{0pt}{}$
     ◉ we have:
          ○ $𝒂=1$
          ○ $𝒓=𝒙$
     ◉ Therefore:
          ○ $\displaystyle \sum_{n=0}^{\infty}𝒙^{n}$ is a geometric series.

          
● [25:28](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=1528). Condition for convergence.
     ◉ A geometric series converges when:
          ○ $|𝒓|<1$
     ◉ Since:
          ○ $𝒓=𝒙$
     ◉ We need:
          ○ $|𝒙|<1$
     ◉ Equivalent interval:
          ○ $-1<𝒙<1$


● [27:20](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=1640). Function representation.
     ◉ Define:
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\displaystyle \sum_{n=0}^{\infty}𝒙^{n}$
          $\rule{0pt}{}$
     ◉ Then:
          ○ $𝒇(𝒙)=\dfrac{1}{1-𝒙}$
     ◉ Domain:
          ○ $(-1,1)$
     ◉ Therefore:
          ○ the power series represents $\dfrac{1}{1-𝒙}$ only on $(-1,1)$.


● [28:06](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=1686). Sum of the geometric power series.
     ◉ Geometric sum formula:
          ○ $\dfrac{𝒂}{1-𝒓}$
     ◉ Here:
          ○ $𝒂=1$
          ○ $𝒓=𝒙$
     ◉ Therefore:
          ○ $\displaystyle \sum_{n=0}^{\infty}𝒙^{n}=\dfrac{1}{1-𝒙}$
     ◉ But only when:
          ○ $|𝒙|<1$



５ - Ｇｅｎｅｒａｌ　Ｐｏｗｅｒ　Ｓｅｒｉｅｓ：Ｒａｄｉｕｓ　ａｎｄ　Ｉｎｔｅｒｖａｌ　ｏｆ　Ｃｏｎｖｅｒｇｅｎｃｅ

● [📷image](../img/Calculus 2 Lecture 9.7/[33-31]-01.png)

● [33:31](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=2011). General power series.
     ◉ General form:
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\displaystyle \sum_{n=0}^{\infty}𝒂_{n}(𝒙-𝑪)^{n}$
          $\rule{0pt}{}$
     ◉ This is centered at:
          ○ $𝑪$
     ◉ Important note:
          ○ $𝒇(𝑪)=𝒂_{0}$
     ◉ Reason:
          ○ if $𝒙=𝑪$,
               ■ then $𝒙-𝑪=0$.
          ○ so every term after the first one disappears.
          ○ only $𝒂_{0}$ remains.


● [35:08](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=2108). Domain is centered at $𝑪$.
     ◉ The domain of a power series function:
          ○ is always an interval centered at $𝑪$.
     ◉ Reason:
          ○ the expression is built around $(𝒙-𝑪)$.
     ◉ The distance from $𝑪$ to the endpoints is called:
          ○ the radius of convergence.
     ◉ Therefore:
          ○ the center $𝑪$ sits in the middle of the interval of convergence.


● [36:33](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=2193). Three possible convergence cases.
     ◉ Case A:
          ○ convergence only at the center.
     ◉ Case B:
          ○ convergence for all real $𝒙$.
     ◉ Case C:
          ○ convergence inside a finite interval around the center.


● [37:00](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=2220). Case A — Convergence only at the center.
     ◉ The series converges only when:
          ○ $𝒙=𝑪$
     ◉ Then:
          ○ radius of convergence $𝑹=0$
     ◉ Meaning:
          ○ there is no interval around $𝑪$.
          ○ the only valid point is the center itself.
     ◉ Symbolically:
          ○ $0\leq |𝒙-𝑪|\leq 0$
     ◉ Therefore:
          ○ $𝒙=𝑪$ only.


● [38:37](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=2317). Case B — Convergence for all real $𝒙$.
     ◉ The series converges for:
          ○ every real value of $𝒙$.
     ◉ Then:
          ○ radius of convergence $𝑹=\infty$
     ◉ Symbolically:
          ○ $-\infty<𝒙-𝑪<\infty$
     ◉ Interval of convergence:
          ○ $(-\infty,\infty)$


● [39:35](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=2375). Case C — Finite radius of convergence.
     ◉ The series converges when:
          ○ $|𝒙-𝑪|<𝑹$
     ◉ It diverges when:
          ○ $|𝒙-𝑪|>𝑹$
     ◉ Here:
          ○ $𝑹$ is the radius of convergence.
     ◉ Meaning:
          ○ $𝑹$ tells how far we can move left and right from the center $𝑪$ while the series still converges.
     ◉ Interval from the radius.
          ○ Start with:
               $\rule{0pt}{}$
               ■ $|𝒙-𝑪|<𝑹$
               $\rule{0pt}{}$
          ○ Equivalent inequality:
               $\rule{0pt}{}$
               ■ $-𝑹<𝒙-𝑪<𝑹$
               $\rule{0pt}{}$
          ○ Add $𝑪$:
               $\rule{0pt}{}$
               ■ $𝑪-𝑹<𝒙<𝑪+𝑹$
               $\rule{0pt}{}$
          ○ Therefore:
               ■ the interval is centered at $𝑪$.
               ■ the radius is $𝑹$.
               ■ the preliminary interval is $(𝑪-𝑹,𝑪+𝑹)$.
     ◉ Endpoints must be checked separately.
          ○ The Ratio Test usually gives:
               $\rule{0pt}{}$
               ■ $|𝒙-𝑪|<𝑹$
               $\rule{0pt}{}$
          ○ But it does not decide:
               ■ $𝒙=𝑪-𝑹$
               ■ $𝒙=𝑪+𝑹$
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

● [📷image](../img/Calculus 2 Lecture 9.7/[44-18]-01.png)

● [44:18](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=2658). 🧩 Example 1 — Convergence only at the center: $\displaystyle \sum_{n=0}^{\infty}n!𝒙^{n}$
     ◉ This is a power series centered at:
          ○ $0$
     ◉ The factorial suggests:
          ○ use the Ratio Test.
     ◉ Goal:
          ○ determine for which $𝒙$-values the power series converges.

● [50:14](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=3014). Use the Ratio Test.
     ◉ Let:
          ○ $𝒂_{n}=n!𝒙^{n}$
     ◉ Then:
          ○ $𝒂_{n+1}=(n+1)!𝒙^{n+1}$
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{𝒂_{n+1}}{𝒂_{n}}\right|$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{n\to\infty}\left|\dfrac{(n+1)!𝒙^{n+1}}{n!𝒙^{n}}\right|$
          $\rule{0pt}{}$
     ◉ Simplify:
     $\rule{0pt}{}$
          ○ $\dfrac{(n+1)!}{n!}=n+1$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒙^{n+1}}{𝒙^{n}}=𝒙$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}(n+1)|𝒙|$


● [51:47](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=3107). Interpreting the Ratio Test result.
     ◉ If $𝒙\neq 0$:
          ○ $|𝒙|$ is a positive constant.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}(n+1)|𝒙|=\infty$
          $\rule{0pt}{}$
          ○ $\infty>1$
          ○ the series diverges by the Ratio Test.
     ◉ If $𝒙=0$:
          ○ $\displaystyle \lim_{n\to\infty}(n+1)|0|=0$
          $\rule{0pt}{}$
          ○ $0<1$
          ○ the series converges by the Ratio Test.
     ◉ Therefore:
          ○ the series converges only at $𝒙=0$.

● [53:25](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=3205). Radius and domain.
     ◉ Center:
          ○ $𝑪=0$
     ◉ Domain:
          ○ $𝒙=0$
     ◉ Radius of convergence:
          ○ $𝑹=0$
     ◉ Interpretation:
          ○ the power series represents a function only at the center.

● N̲O̲T̲E̲ — Key idea.
     ◉ The factorial $n!$ grows so fast that any $𝒙\neq 0$ makes the series diverge.
     ◉ Only the center survives:
          ○ $𝒙=0$
     ◉ Therefore:
          ○ the radius of convergence is $𝑹=0$.



５．１．２ - Ｅｘａｍｐｌｅ　２

● [📷image-1](../img/Calculus 2 Lecture 9.7/[56-59]-01.png)  [📷image-2](../img/Calculus 2 Lecture 9.7/[56-59]-02.png)

● [56:59](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=3419). 🧩 Example 2 — Power series converging for all $𝒙$: $\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}𝒙^{2n}}{(2n)!}$
     ◉ This is a power series centered at:
          ○ $0$
     ◉ Since factorials appear:
          ○ use the Ratio Test.
     ◉ Goal:
          ○ determine for which $𝒙$-values the power series converges.


● [58:07](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=3487). Set up the Ratio Test.
     ◉ Let:
          ○ $𝒂_{n}=\dfrac{(-1)^{n}𝒙^{2n}}{(2n)!}$
     ◉ Then:
          ○ $𝒂_{n+1}=\dfrac{(-1)^{n+1}𝒙^{2n+2}}{(2n+2)!}$
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{𝒂_{n+1}}{𝒂_{n}}\right|$


● [1:00:00](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=3600). Build the ratio.
     ◉ Substitute:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{\dfrac{(-1)^{n+1}𝒙^{2n+2}}{(2n+2)!}}{\dfrac{(-1)^{n}𝒙^{2n}}{(2n)!}}\right|$
          $\rule{0pt}{}$
     ◉ Reciprocate and multiply:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{(-1)^{n+1}𝒙^{2n+2}}{(2n+2)!}\cdot \dfrac{(2n)!}{(-1)^{n}𝒙^{2n}}\right|$


● [1:01:00](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=3660). Simplify signs and powers.
     ◉ The absolute value removes the alternating sign:
     $\rule{0pt}{}$
          ○ $\left|\dfrac{(-1)^{n+1}}{(-1)^{n}}\right|=1$
          $\rule{0pt}{}$
     ◉ Simplify the powers of $𝒙$:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒙^{2n+2}}{𝒙^{2n}}=𝒙^{2}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|𝒙^{2}\cdot \dfrac{(2n)!}{(2n+2)!}\right|$


● [1:02:35](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=3755). Factorial simplification.
     ◉ Use:
          ○ $(2n+2)!=(2n+2)(2n+1)(2n)!$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\dfrac{(2n)!}{(2n+2)!}=\dfrac{1}{(2n+2)(2n+1)}$
          $\rule{0pt}{}$
     ◉ So:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\dfrac{𝒙^{2}}{(2n+2)(2n+1)}$


● [1:06:44](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=4004). Limit result.
     ◉ For any fixed $𝒙$:
          ○ $𝒙^{2}$ is a constant.
          ○ $(2n+2)(2n+1)\to\infty$.
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\dfrac{𝒙^{2}}{(2n+2)(2n+1)}=0$
          $\rule{0pt}{}$
     ◉ This happens for all real $𝒙$.


● [1:08:27](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=4107). Conclusion for Example 2.
     ◉ Since:
          ○ $𝑳=0<1$
     ◉ By the Ratio Test:
          ○ the power series converges for all $𝒙$.
     ◉ Therefore:
          ○ radius of convergence $𝑹=\infty$
          ○ interval of convergence is $(-\infty,\infty)$

● N̲O̲T̲E̲ 1 — Key idea.
     ◉ The factorial in the denominator grows fast enough to dominate every fixed power of $𝒙$.
     ◉ No matter what real value $𝒙$ has:
          ○ the ratio limit becomes $0$.
     ◉ Therefore:
          ○ the series converges for all real $𝒙$.
          
● N̲O̲T̲E̲ 2 — Why the domain is all real numbers.
     ◉ After applying the Ratio Test, we get:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\dfrac{𝒙^{2}}{(2n+2)(2n+1)}$
          $\rule{0pt}{}$
     ◉ Important:
          ○ $𝒙$ is fixed.
          ○ $n$ is the variable that goes to infinity.
     ◉ For any fixed real value of $𝒙$:
          ○ $𝒙^{2}$ is just a constant.
          ○ $(2n+2)(2n+1)\to\infty$.
     ◉ Therefore:
          ○ constant / $\infty=0$
          ○ $𝑳=0$
     ◉ Since:
          ○ $0<1$
     ◉ By the Ratio Test:
          ○ the series converges for every real value of $𝒙$.
     ◉ Therefore:
          ○ domain $=(-\infty,\infty)$
          ○ radius of convergence $𝑹=\infty$
     ◉ Key idea:
          ○ we do not plug infinity into $𝒙$.
          ○ $𝒙$ stays fixed.
          ○ only $n$ goes to infinity.

          

５．１．３ - Ｅｘａｍｐｌｅ　３

● [📷image-1](../img/Calculus 2 Lecture 9.7/[1-12-28]-01.png)  [📷image-2](../img/Calculus 2 Lecture 9.7/[1-12-28]-02.png)

● [1:12:28](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=4348). 🧩 Example 3 — Finite interval of convergence: $\displaystyle \sum_{n=1}^{\infty}\dfrac{𝒙^{n}}{n}$
     ◉ This is a power series centered at:
          ○ $0$
     ◉ Goal:
          ○ find the radius of convergence.
          ○ find the interval of convergence.
     ◉ Use:
          ○ Ratio Test.


● [1:14:19](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=4459). Ratio Test setup.
     ◉ Let:
          ○ $𝒂_{n}=\dfrac{𝒙^{n}}{n}$
     ◉ Then:
          ○ $𝒂_{n+1}=\dfrac{𝒙^{n+1}}{n+1}$
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{𝒂_{n+1}}{𝒂_{n}}\right|$


● [1:15:17](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=4517). Simplify the ratio.
     ◉ Substitute:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{\dfrac{𝒙^{n+1}}{n+1}}{\dfrac{𝒙^{n}}{n}}\right|$
          $\rule{0pt}{}$
     ◉ Reciprocate and multiply:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{𝒙^{n+1}}{n+1}\cdot \dfrac{n}{𝒙^{n}}\right|$
          $\rule{0pt}{}$
     ◉ Simplify powers:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒙^{n+1}}{𝒙^{n}}=𝒙$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{n}{n+1}\cdot 𝒙\right|$
          $\rule{0pt}{}$
     ◉ Since:
     $\rule{0pt}{}$
          ○ $\dfrac{n}{n+1}>0$
          $\rule{0pt}{}$
     ◉ We can write:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\dfrac{n}{n+1}|𝒙|$
          $\rule{0pt}{}$
     ◉ Since:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{n}{n+1}=1$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ $𝑳=|𝒙|$


● [1:18:17](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=4697). Apply the Ratio Test condition.
     ◉ Ratio Test convergence requires:
          ○ $𝑳<1$
     ◉ Since:
          ○ $𝑳=|𝒙|$
     ◉ We need:
          ○ $|𝒙|<1$
     ◉ Therefore:
          ○ $-1<𝒙<1$
     ◉ This gives the preliminary interval:
          ○ $(-1,1)$

● [1:20:18](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=4818). Radius of convergence.
     ◉ From:
          ○ $|𝒙|<1$
     ◉ Radius:
          ○ $𝑹=1$
     ◉ Center:
          ○ $𝑪=0$
     ◉ Meaning:
          ○ the series converges for all $𝒙$ inside distance $1$ from the center.
          ○ the Ratio Test does not decide the endpoints.


● [1:22:12](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=4932). Check the endpoint $𝒙=-1$.
     ◉ Plug into the original power series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{𝒙^{n}}{n}$
          $\rule{0pt}{}$
     ◉ If $𝒙=-1$
     $\rule{0pt}{}$
          ○ Then $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n}}{n}$
          $\rule{0pt}{}$
     ◉ This is the alternating harmonic series.
     ◉ It converges by:
          ○ Alternating Series Test.
     ◉ Therefore:
          ○ $𝒙=-1$ is included.

● [1:25:05](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=5105). Check the endpoint $𝒙=1$.
     ◉ Plug into the original power series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{𝒙^{n}}{n}$
          $\rule{0pt}{}$
     ◉ If:
          ○ $𝒙=1$
     ◉ Then:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{n}$
          $\rule{0pt}{}$
     ◉ This is the harmonic series.
     ◉ The harmonic series diverges.
     ◉ Therefore:
          ○ $𝒙=1$ is not included.

● [1:26:35](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=5195). Final interval for Example 3.
     ◉ Radius:
          ○ $𝑹=1$
     ◉ Center:
          ○ $𝑪=0$
     ◉ Interval of convergence:
          ○ $[-1,1)$
     ◉ Meaning:
          ○ the power series converges at $-1$.
          ○ it diverges at $1$.
          ○ it converges for every $𝒙$ between $-1$ and $1$.

● N̲O̲T̲E̲ — Key idea.
     ◉ The Ratio Test gives:
          ○ $|𝒙|<1$
     ◉ This tells us the open interval:
          ○ $(-1,1)$
     ◉ But the endpoints must be checked separately.
     ◉ At $𝒙=-1$:
          ○ the series becomes alternating harmonic,
          ○ so it converges.
     ◉ At $𝒙=1$:
          ○ the series becomes harmonic,
          ○ so it diverges.
     ◉ Therefore:
          ○ left endpoint included.
          ○ right endpoint excluded.



５．１．４ - Ｅｘａｍｐｌｅ　４

● [📷image-1](../img/Calculus 2 Lecture 9.7/[1-28-30]-01.png) [📷image-2](../img/Calculus 2 Lecture 9.7/[1-28-30]-02.png) [📷image-3](../img/Calculus 2 Lecture 9.7/[1-28-30]-03.png)

● [1:28:30](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=5310). 🧩 Example 4 — Power series centered at $2$: $\displaystyle \sum_{n=1}^{\infty}\dfrac{(𝒙-2)^{n}}{n^{2}\cdot 3^{n}}$
     ◉ Given:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{(𝒙-2)^{n}}{n^{2}\cdot 3^{n}}$
          $\rule{0pt}{}$
     ◉ This is a power series because:
          ○ it contains $(𝒙-2)$ raised to the power $n$.
     ◉ Therefore:
          ○ center $=2$
               ■ if it converges, the interval of convergence will be centered at $2$.
     ◉ Use:
          ○ Ratio Test.

● [1:29:34](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=5374). Ratio Test setup.
     ◉ Let:
          ○ $𝒂_{n}=\dfrac{(𝒙-2)^{n}}{n^{2}\cdot 3^{n}}$
     ◉ Then:
          ○ $𝒂_{n+1}=\dfrac{(𝒙-2)^{n+1}}{(n+1)^{2}\cdot 3^{n+1}}$
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{𝒂_{n+1}}{𝒂_{n}}\right|$


● [1:30:10](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=5410). Build the ratio.
     ◉ Substitute:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{\dfrac{(𝒙-2)^{n+1}}{(n+1)^{2}\cdot 3^{n+1}}}{\dfrac{(𝒙-2)^{n}}{n^{2}\cdot 3^{n}}}\right|$
          $\rule{0pt}{}$
     ◉ Reciprocate and multiply:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{(𝒙-2)^{n+1}}{(n+1)^{2}\cdot 3^{n+1}}\cdot \dfrac{n^{2}\cdot 3^{n}}{(𝒙-2)^{n}}\right|$


● [1:32:00](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=5520). Simplify the ratio.
     ◉ Simplify powers of $(𝒙-2)$:
     $\rule{0pt}{}$
          ○ $\dfrac{(𝒙-2)^{n+1}}{(𝒙-2)^{n}}=𝒙-2$
          $\rule{0pt}{}$
     ◉ Simplify powers of $3$:
     $\rule{0pt}{}$
          ○ $\dfrac{3^{n}}{3^{n+1}}=\dfrac{1}{3}$
          $\rule{0pt}{}$
     ◉ Keep the polynomial factor:
     $\rule{0pt}{}$
          ○ $\dfrac{n^{2}}{(n+1)^{2}}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{(𝒙-2)n^{2}}{3(n+1)^{2}}\right|$


● [1:33:22](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=5602). Separate the $n$-part from the $𝒙$-part.
     ◉ Rewrite:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\dfrac{n^{2}}{(n+1)^{2}}\cdot \left|\dfrac{𝒙-2}{3}\right|$
          $\rule{0pt}{}$
     ◉ Since:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{n^{2}}{(n+1)^{2}}=1$
          $\rule{0pt}{}$
     ◉ Then:
          ○ $𝑳=\left|\dfrac{𝒙-2}{3}\right|$


● [1:34:35](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=5675). Apply the Ratio Test.
     ◉ Ratio Test convergence requires:
          ○ $𝑳<1$
     ◉ Since:
     $\rule{0pt}{}$
          ○ $𝑳=\left|\dfrac{𝒙-2}{3}\right|$
          $\rule{0pt}{}$
     ◉ We need:
     $\rule{0pt}{}$
          ○ $\left|\dfrac{𝒙-2}{3}\right|<1$
          $\rule{0pt}{}$
     ◉ Multiply by $3$:
          ○ $|𝒙-2|<3$
     ◉ Therefore:
          ○ radius of convergence $𝑹=3$

● [1:35:58](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=5758). Solve the interval.
     ◉ Start with:
          ○ $|𝒙-2|<3$
     ◉ Equivalent:
          ○ $-3<𝒙-2<3$
     ◉ Add $2$:
          ○ $-1<𝒙<5$
     ◉ Preliminary interval:
          ○ $(-1,5)$
     ◉ Important:
          ○ this is only the open interval.
          ○ the endpoints must still be checked separately.


● [1:37:17](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=5837). Check endpoint $𝒙=-1$.
     ◉ Plug into the original power series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{(𝒙-2)^{n}}{n^{2}\cdot 3^{n}}$
          $\rule{0pt}{}$
     ◉ If:
          ○ $𝒙=-1$
     ◉ Then:
          ○ $𝒙-2=-3$
     ◉ So:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-3)^{n}}{n^{2}\cdot 3^{n}}$
          $\rule{0pt}{}$
     ◉ Simplify:
     $\rule{0pt}{}$
          ○ $\dfrac{(-3)^{n}}{3^{n}}=(-1)^{n}$
          $\rule{0pt}{}$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n}}{n^{2}}$
          $\rule{0pt}{}$
     ◉ This series converges by:
          ○ Alternating Series Test.
     ◉ Therefore:
          ○ $𝒙=-1$ is included.


● [1:39:36](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=5976). Check endpoint $𝒙=5$.
     ◉ Plug into the original power series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{(𝒙-2)^{n}}{n^{2}\cdot 3^{n}}$
          $\rule{0pt}{}$
     ◉ If:
          ○ $𝒙=5$
     ◉ Then:
          ○ $𝒙-2=3$
     ◉ So:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{3^{n}}{n^{2}\cdot 3^{n}}$
          $\rule{0pt}{}$
     ◉ Simplify:
     $\rule{0pt}{}$
          ○ $\dfrac{3^{n}}{3^{n}}=1$
          $\rule{0pt}{}$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{n^{2}}$
          $\rule{0pt}{}$
     ◉ This is a 𝒑-series with:
          ○ $𝒑=2$
     ◉ Since:
          ○ $2>1$
     ◉ The series converges.
     ◉ Therefore:
          ○ $𝒙=5$ is included.


● [1:40:52](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=6052). Final interval for Example 4.
     ◉ Radius:
          ○ $𝑹=3$
     ◉ Center:
          ○ $𝑪=2$
     ◉ Interval of convergence:
          ○ $[-1,5]$
     ◉ Check:
          ○ $2$ is exactly the midpoint of $-1$ and $5$.
     ◉ Meaning:
          ○ the power series converges from $-1$ to $5$,
          ○ including both endpoints.

● N̲O̲T̲E̲ — Key idea.
     ◉ The Ratio Test gives:
          ○ $|𝒙-2|<3$
     ◉ This means:
          ○ center $=2$
          ○ radius $=3$
     ◉ So the open interval is:
          ○ $(2-3,2+3)=(-1,5)$
     ◉ Then we check endpoints:
          ○ at $𝒙=-1$, the series becomes $\displaystyle \sum \dfrac{(-1)^{n}}{n^{2}}$ and converges.
          $\rule{0pt}{}$
          ○ at $𝒙=5$, the series becomes $\displaystyle \sum \dfrac{1}{n^{2}}$ and converges.
     ◉ Therefore:
          ○ both endpoints are included.
          ○ final interval $=[-1,5]$.



５．１．５  - Ｅｘａｍｐｌｅ　５


● [📷image-1](../img/Calculus 2 Lecture 9.7/[1-41-21]-01.png) [📷image-2](../img/Calculus 2 Lecture 9.7/[1-41-21]-02.png) [📷image-3](../img/Calculus 2 Lecture 9.7/[1-41-21]-03.png)

● [1:41:21](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=6081). 🧩 Example 5 — Endpoint behavior with square roots: $\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}2^{n}𝒙^{n}}{\sqrt{n+1}}$
     ◉ Given:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}2^{n}𝒙^{n}}{\sqrt{n+1}}$
          $\rule{0pt}{}$
     ◉ This is a power series centered at:
          ○ $0$
     ◉ Goal:
          ○ find the radius of convergence.
          ○ find the interval of convergence.
     ◉ Use:
          ○ Ratio Test.

● [1:43:20](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=6200). Ratio Test setup.
     ◉ Let:
          ○ $𝒂_{n}=\dfrac{(-1)^{n}2^{n}𝒙^{n}}{\sqrt{n+1}}$
     ◉ Then:
          ○ $𝒂_{n+1}=\dfrac{(-1)^{n+1}2^{n+1}𝒙^{n+1}}{\sqrt{n+2}}$
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{𝒂_{n+1}}{𝒂_{n}}\right|$

● [1:44:31](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=6271). Build the ratio.
     ◉ Substitute:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{\dfrac{(-1)^{n+1}2^{n+1}𝒙^{n+1}}{\sqrt{n+2}}}{\dfrac{(-1)^{n}2^{n}𝒙^{n}}{\sqrt{n+1}}}\right|$
          $\rule{0pt}{}$
     ◉ Reciprocate and multiply:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{(-1)^{n+1}2^{n+1}𝒙^{n+1}}{\sqrt{n+2}}\cdot \dfrac{\sqrt{n+1}}{(-1)^{n}2^{n}𝒙^{n}}\right|$

● [1:46:25](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=6385). Simplify the ratio.
     ◉ The absolute value removes:
     $\rule{0pt}{}$
          ○ $\dfrac{(-1)^{n+1}}{(-1)^{n}}$
          $\rule{0pt}{}$
     ◉ Simplify powers of $2$:
     $\rule{0pt}{}$
          ○ $\dfrac{2^{n+1}}{2^{n}}=2$
          $\rule{0pt}{}$
     ◉ Simplify powers of $𝒙$:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒙^{n+1}}{𝒙^{n}}=𝒙$
          $\rule{0pt}{}$
     ◉ Keep the square-root factor:
     $\rule{0pt}{}$
          ○ $\dfrac{\sqrt{n+1}}{\sqrt{n+2}}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|2𝒙\cdot \dfrac{\sqrt{n+1}}{\sqrt{n+2}}\right|$


● [1:47:45](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=6465). Separate the $n$-part from the $𝒙$-part.
     ◉ Rewrite:
          $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\sqrt{\dfrac{n+1}{n+2}}\cdot 2|𝒙|$
          $\rule{0pt}{}$
     ◉ Since:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\sqrt{\dfrac{n+1}{n+2}}=1$
          $\rule{0pt}{}$
     ◉ Then:
          ○ $𝑳=2|𝒙|$


● [1:48:34](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=6514). Apply Ratio Test condition.
     ◉ Ratio Test convergence requires:
          ○ $𝑳<1$
     ◉ Since:
          ○ $𝑳=2|𝒙|$
     ◉ We need:
          ○ $2|𝒙|<1$
     ◉ Divide by $2$:
     $\rule{0pt}{}$
          ○ $|𝒙|<\dfrac{1}{2}$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ radius of convergence $𝑹=\dfrac{1}{2}$
     ◉ Preliminary interval:
     $\rule{0pt}{}$
          ○ $-\dfrac{1}{2}<𝒙<\dfrac{1}{2}$
          $\rule{0pt}{}$
     ◉ Important:
          ○ the endpoints must still be checked separately.


● [1:50:30](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=6630). Check endpoint $𝒙=-\dfrac{1}{2}$.
     ◉ Plug into the original power series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}2^{n}𝒙^{n}}{\sqrt{n+1}}$
          $\rule{0pt}{}$
     ◉ If:
          ○ $𝒙=-\dfrac{1}{2}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}2^{n}(-\dfrac{1}{2})^{n}}{\sqrt{n+1}}$
          $\rule{0pt}{}$
     ◉ Simplify the signs and powers:
     $\rule{0pt}{}$
          ○ $(-1)^{n}2^{n}(-\dfrac{1}{2})^{n}=1$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}\dfrac{1}{\sqrt{n+1}}$


● [1:53:00](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=6780). Endpoint $𝒙=-\dfrac{1}{2}$ — Method 1: Limit Comparison Test.
     ◉ Compare:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}\dfrac{1}{\sqrt{n+1}}$
          $\rule{0pt}{}$
     ◉ with:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{\sqrt{n}}=\sum_{n=1}^{\infty}\dfrac{1}{n^{1/2}}$
          $\rule{0pt}{}$
     ◉ Compute:
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{\dfrac{1}{\sqrt{n+1}}}{\dfrac{1}{\sqrt{n}}}$
          $\rule{0pt}{}$
     ◉ Simplify:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{\sqrt{n}}{\sqrt{n+1}}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{n\to\infty}\sqrt{\dfrac{n}{n+1}}$
          $\rule{0pt}{}$
          ○ $=1$
     ◉ Since the limit is finite and positive:
          ○ both series have the same behavior.
     ◉ But:
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{n^{1/2}}$ diverges,
               ■ because it is a 𝒑-series with $𝒑=\dfrac{1}{2}\leq 1$.
     ◉ Therefore:
          ○ $\displaystyle \sum_{n=0}^{\infty}\dfrac{1}{\sqrt{n+1}}$ diverges.


● [1:56:29](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=6989). Endpoint $𝒙=-\dfrac{1}{2}$ — Method 2: Reindexing the series.
     ◉ The series is:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}\dfrac{1}{\sqrt{n+1}}$
          $\rule{0pt}{}$
     ◉ Let:
          ○ $k=n+1$
     ◉ When:
          ○ $n=0$,
          ○ $k=1$.
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}\dfrac{1}{\sqrt{n+1}}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \sum_{k=1}^{\infty}\dfrac{1}{\sqrt{k}}$
          $\rule{0pt}{}$
     ◉ This is:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{k=1}^{\infty}\dfrac{1}{k^{1/2}}$
          $\rule{0pt}{}$
     ◉ Since:
     $\rule{0pt}{}$
          ○ $𝒑=\dfrac{1}{2}\leq 1$
          $\rule{0pt}{}$
     ◉ The 𝒑-series diverges.
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $𝒙=-\dfrac{1}{2}$ is not included.


● [1:59:03](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=7143). Check endpoint $𝒙=\dfrac{1}{2}$.
     ◉ Plug into the original power series:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}2^{n}𝒙^{n}}{\sqrt{n+1}}$
          $\rule{0pt}{}$
     ◉ If:
          ○ $𝒙=\dfrac{1}{2}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}2^{n}(\dfrac{1}{2})^{n}}{\sqrt{n+1}}$
          $\rule{0pt}{}$
     ◉ Simplify:
     $\rule{0pt}{}$
          ○ $2^{n}(\dfrac{1}{2})^{n}=1$
          $\rule{0pt}{}$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}}{\sqrt{n+1}}$


● [1:59:40](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=7180). Endpoint $𝒙=\dfrac{1}{2}$ — Alternating Series Test.
     ◉ Positive part:
     $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{1}{\sqrt{n+1}}$
          $\rule{0pt}{}$
     ◉ Check the limit:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{1}{\sqrt{n+1}}=0$
          $\rule{0pt}{}$
     ◉ Check decreasing:
     $\rule{0pt}{}$
          ○ $𝒂_{n+1}=\dfrac{1}{\sqrt{n+2}}$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{\sqrt{n+2}}<\dfrac{1}{\sqrt{n+1}}=𝒂_{n}$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ $𝒂_{n}$ is decreasing.
     ◉ By the Alternating Series Test:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}}{\sqrt{n+1}}$ converges.
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ $𝒙=\dfrac{1}{2}$ is included.


● [2:01:02](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=7262). Final interval for Example 5.
     ◉ Radius:
          ○ $𝑹=\dfrac{1}{2}$
     ◉ Center:
          ○ $𝑪=0$
     ◉ Interval of convergence:
     $\rule{0pt}{}$
          ○ $\left(-\dfrac{1}{2},\dfrac{1}{2}\right]$
          $\rule{0pt}{}$
     ◉ Meaning:
          ○ the series diverges at $-\dfrac{1}{2}$.
          $\rule{0pt}{}$
          ○ the series converges at $\dfrac{1}{2}$.
          ○ the series converges for every $𝒙$ between $-\dfrac{1}{2}$ and $\dfrac{1}{2}$.

● N̲O̲T̲E̲ — Key idea.
     ◉ The Ratio Test gives:
     $\rule{0pt}{}$
          ○ $|𝒙|<\dfrac{1}{2}$
          $\rule{0pt}{}$
     ◉ This gives the open interval:
     $\rule{0pt}{}$
          ○ $\left(-\dfrac{1}{2},\dfrac{1}{2}\right)$
          $\rule{0pt}{}$
     ◉ At the left endpoint:
          ○ the signs cancel,
          ○ leaving a positive divergent 𝒑-series.
     ◉ At the right endpoint:
          ○ the series remains alternating,
          ○ and converges by the Alternating Series Test.
     ◉ Therefore:
          ○ left endpoint excluded.
          ○ right endpoint included.
          $\rule{0pt}{}$
          ○ final interval $=\left(-\dfrac{1}{2},\dfrac{1}{2}\right]$.






６ - Ｃａｌｃｕｌｕｓ　ｏｆ　Ｐｏｗｅｒ　Ｓｅｒｉｅｓ

● [📷image](../img/Calculus 2 Lecture 9.7/[2-03-14]-01.png)

● [2:03:14](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=7394). Calculus of power series.
     ◉ We can perform calculus operations on power series:
          ○ derivatives.
          ○ integrals.
     ◉ Main idea:
          ○ differentiate or integrate term by term.

● [2:04:24](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=7464). Start with a general power series.
     ◉ Suppose:
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\displaystyle \sum_{n=0}^{\infty}𝒂_{n}(𝒙-𝑪)^{n}$
          $\rule{0pt}{}$
     ◉ Expanded:
          ○ $𝒇(𝒙)=𝒂_{0}+𝒂_{1}(𝒙-𝑪)+𝒂_{2}(𝒙-𝑪)^{2}+𝒂_{3}(𝒙-𝑪)^{3}+\cdots$



６.1 - Ｄｅｒｉｖａｔｉｖｅｓ　ｏｆ　Ｐｏｗｅｒ　Ｓｅｒｉｅｓ

● [2:05:50](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=7550). Derivative term by term.
     ◉ Since:
          ○ each $𝒂_{n}$ is a constant,
     ◉ we can differentiate term by term.
     ◉ The variable part is:
          ○ $(𝒙-𝑪)^{n}$

● [2:06:39](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=7599). Apply the power rule and chain rule.
     ◉ Derivative of the first term:
          ○ $𝒂_{0}\to 0$
     ◉ Derivative of the second term:
          ○ $𝒂_{1}(𝒙-𝑪)\to 𝒂_{1}$
     ◉ Derivative of the third term:
          ○ $𝒂_{2}(𝒙-𝑪)^{2}\to 2𝒂_{2}(𝒙-𝑪)$
     ◉ Derivative of the fourth term:
          ○ $𝒂_{3}(𝒙-𝑪)^{3}\to 3𝒂_{3}(𝒙-𝑪)^{2}$

● [2:9:45](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=7785). General derivative formula.
     ◉ Starting from:
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\displaystyle \sum_{n=0}^{\infty}𝒂_{n}(𝒙-𝑪)^{n}$
          $\rule{0pt}{}$
     ◉ Then:
          ○ $𝒇'(𝒙)=\displaystyle \sum_{n=1}^{\infty}n𝒂_{n}(𝒙-𝑪)^{n-1}$
     ◉ Important:
          ○ the derivative starts at $n=1$.
     ◉ Reason:
          ○ the $n=0$ term is constant,
          ○ so its derivative is $0$.



６.2 - Ｉｎｔｅｇｒａｌｓ　ｏｆ　Ｐｏｗｅｒ　Ｓｅｒｉｅｓ

● [2:12:35](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=7955). Integral term by term.
     ◉ We can integrate a power series term by term.
     ◉ Starting from:
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\displaystyle \sum_{n=0}^{\infty}𝒂_{n}(𝒙-𝑪)^{n}$
          $\rule{0pt}{}$
     ◉ Each term integrates using:
          ○ power rule for integrals.

● [2:14:50](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=8090). General integral formula.
     ◉ The integral is:
     $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒇(𝒙)\,𝒅𝑥=𝑲+\sum_{n=0}^{\infty}\dfrac{𝒂_{n}(𝒙-𝑪)^{n+1}}{n+1}$
          $\rule{0pt}{}$
     ◉ Important:
          ○ include the constant of integration.
     ◉ The series still starts at:
          ○ $n=0$

● N̲O̲T̲E̲ — Endpoints may change.
     ◉ Differentiating or integrating a power series:
          ○ keeps the same radius of convergence.
     ◉ But:
          ○ endpoint behavior may change.
     ◉ A derivative can lose endpoints.
     ◉ An integral can gain endpoints.
     ◉ Therefore:
          ○ endpoints must be checked separately when needed.




６. ３  -  Ａｐｐｌｉｃａｔｉｏｎ: Ｐｏｗｅｒ　Ｓｅｒｉｅｓ　Ｆｏｒ　$\ln(1-𝒙)$

● [📷image-1](../img/Calculus 2 Lecture 9.7/[2-17-26]-01.png)  [📷image-2](../img/Calculus 2 Lecture 9.7/[2-17-26]-02.png)

● [2:17:26](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=8246). 🧩 Application — Find a power series representation for $\ln(1-𝒙)$.
     ◉ Goal:
          ○ find a power series representation for:
               ■ $\ln(1-𝒙)$
     ◉ Interval:
          ○ $-1<𝒙<1$
     ◉ Main idea:
          ○ start from a known power series,
          ○ then integrate term by term to create the logarithm.

● [2:17:49](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=8269). Choosing the starting function.
     ◉ We want:
          ○ $\ln(1-𝒙)$
     ◉ Leonard’s strategy:
          ○ look for a simpler function whose integral gives $\ln(1-𝒙)$.
     ◉ Since:
          ○ the integral of $\dfrac{1}{1-𝒙}$ is very close to $\ln(1-𝒙)$,
     ◉ We start with:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{1-𝒙}$
          $\rule{0pt}{}$
     ◉ Important:
     $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{1-𝒙}\,𝒅𝒙=-\ln(1-𝒙)$
          $\rule{0pt}{}$
     ◉ The negative sign appears because:
          ○ the derivative of $1-𝒙$ is $-1$.

● [2:18:36](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=8316). Why $\dfrac{1}{1-𝒙}$ is useful.
     ◉ The function:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{1-𝒙}$
          $\rule{0pt}{}$
     ◉ is the sum of a geometric power series.
     ◉ Geometric series formula:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{1-𝒓}=1+𝒓+𝒓^{2}+𝒓^{3}+\cdots$
          $\rule{0pt}{}$
     ◉ In this case:
          ○ $𝒓=𝒙$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{1-𝒙}=1+𝒙+𝒙^{2}+𝒙^{3}+\cdots$
          $\rule{0pt}{}$
     ◉ Series notation:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{1-𝒙}=\displaystyle \sum_{n=0}^{\infty}𝒙^{n}$
          $\rule{0pt}{}$
          ○ or equivalently:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{1-𝒙}=\displaystyle \sum_{n=1}^{\infty}𝒙^{n-1}$


● [2:21:58](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=8518). Why the interval is $(-1,1)$.
     ◉ This interval comes from the geometric series.
     ◉ A geometric series converges when:
          ○ $|𝒓|<1$
     ◉ Here:
          ○ $𝒓=𝒙$
     ◉ Therefore:
          ○ $|𝒙|<1$
     ◉ Equivalent:
          ○ $-1<𝒙<1$
     ◉ Meaning:
          ○ the power series for $\dfrac{1}{1-𝒙}$ is valid only on $(-1,1)$.
     ◉ Since we are using that power series as our starting point,
          ○ the representation for $\ln(1-𝒙)$ is also built on this interval.

● [2:24:49](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=8689). Integrate both sides.
     ◉ Start with:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{1-𝒙}=1+𝒙+𝒙^{2}+𝒙^{3}+\cdots$
          $\rule{0pt}{}$
     ◉ Integrate both sides:
     $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{1-𝒙}\,𝒅𝒙=\int(1+𝒙+𝒙^{2}+𝒙^{3}+\cdots)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Left side:
     $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{1-𝒙}\,𝒅𝒙=-\ln(1-𝒙)$
          $\rule{0pt}{}$
     ◉ Right side:
     $\rule{0pt}{}$
          ○ $\displaystyle \int(1+𝒙+𝒙^{2}+𝒙^{3}+\cdots)\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $=𝒙+\dfrac{𝒙^{2}}{2}+\dfrac{𝒙^{3}}{3}+\dfrac{𝒙^{4}}{4}+\cdots+𝑲$


● [2:26:17](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=8777). Solve for $\ln(1-𝒙)$.
     ◉ We have:
          ○ $-\ln(1-𝒙)=𝒙+\dfrac{𝒙^{2}}{2}+\dfrac{𝒙^{3}}{3}+\dfrac{𝒙^{4}}{4}+\cdots+𝑲$
          $\rule{0pt}{}$
     ◉ Multiply by $-1$:
          ○ $\ln(1-𝒙)=-𝒙-\dfrac{𝒙^{2}}{2}-\dfrac{𝒙^{3}}{3}-\dfrac{𝒙^{4}}{4}-\cdots-𝑲$


● [2:27:02](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=8822). Determine the constant.
     ◉ Plug in:
          ○ $𝒙=0$
     ◉ Left side:
          ○ $\ln(1-0)=\ln(1)=0$
     ◉ Right side:
          ○ all terms with $𝒙$ become $0$.
     ◉ Therefore:
          ○ $0=-𝑲$
     ◉ So:
          ○ $𝑲=0$


● [2:27:31](https://www.youtube.com/watch?v=TGD-TP1c7i4&t=8851). Final power series representation.
     ◉ Therefore:
          ○ $\ln(1-𝒙)=-𝒙-\dfrac{𝒙^{2}}{2}-\dfrac{𝒙^{3}}{3}-\dfrac{𝒙^{4}}{4}-\cdots$
          $\rule{0pt}{}$
     ◉ Factor the negative sign:
     $\rule{0pt}{}$
          ○ $\ln(1-𝒙)=-\left(𝒙+\dfrac{𝒙^{2}}{2}+\dfrac{𝒙^{3}}{3}+\dfrac{𝒙^{4}}{4}+\cdots\right)$
          $\rule{0pt}{}$
     ◉ Series notation:
     $\rule{0pt}{}$
          ○ $\ln(1-𝒙)=-\displaystyle \sum_{n=1}^{\infty}\dfrac{𝒙^{n}}{n}$
     ◉ Valid on:
          ○ $(-1,1)$


● N̲O̲T̲E̲ 1 — Why this method works.
     ◉ We do not invent the logarithm series from nothing.
     ◉ We start from the geometric power series:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{1-𝒙}=\displaystyle \sum_{n=0}^{\infty}𝒙^{n}
          $\rule{0pt}{}$
     ◉ Then we integrate term by term.
     $\rule{0pt}{}$
     ◉ Integrating $\dfrac{1}{1-𝒙}$ produces:
     $\rule{0pt}{}$
          ○ $-\ln(1-𝒙)$
     ◉ Integrating the power series produces:
     $\rule{0pt}{}$
          ○ $𝒙+\dfrac{𝒙^{2}}{2}+\dfrac{𝒙^{3}}{3}+\dfrac{𝒙^{4}}{4}+\cdots$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ $\ln(1-𝒙)=-\displaystyle \sum_{n=1}^{\infty}\dfrac{𝒙^{n}}{n}$


● N̲O̲T̲E̲ 2 — Meaning of the interval.
     ◉ The interval $(-1,1)$ comes from the geometric series.
     ◉ Since:
          ○ $\dfrac{1}{1-𝒙}=\displaystyle \sum_{n=0}^{\infty}𝒙^{n}$
     ◉ only when:
          ○ $|𝒙|<1$
     ◉ The integrated series representation is valid on the same open interval:
          ○ $-1<𝒙<1$
     ◉ Key idea:
          ○ a power series represents a function only where the series converges.





Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Power Series and Functions
     ◉ [openstax 🌐](https://openstax.org/books/calculus-volume-2/pages/6-2-properties-of-power-series)

● Properties of Power Series
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/5-6-ratio-and-root-tests)