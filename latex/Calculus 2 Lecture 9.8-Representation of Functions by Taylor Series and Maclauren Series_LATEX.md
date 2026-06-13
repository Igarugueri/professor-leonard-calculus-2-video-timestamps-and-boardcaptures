-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ９．８： Ｒｅｐｒｅｓｅｎｔａｔｉｏｎ ｏｆ Ｆｕｎｃｔｉｏｎｓ ｂｙ Ｔａｙｌｏｒ Ｓｅｒｉｅｓ ａｎｄ Ｍａｃｌａｕｒｅｎ Ｓｅｒｉｅｓ**----------------------------------






１ - Ｔａｙｌｏｒ　ａｎｄ　Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ:　Ｔｈｅｏｒｙ

● [📷image](./img/Calculus 2 Lecture 9.8/[0-00]-01.png)

● [0:00](https://www.youtube.com/watch?v=3VHol7eosLA&t=0). Introduction — Representing functions with power series.
     ◉ Main idea:
          ○ we want to represent a function using a power series.
     ◉ Instead of only studying whether a series converges,
          ○ now we use series to build functions.
     ◉ Big goal:
          ○ take a function $𝒇(𝒙)$,
          ○ and write it as an infinite polynomial-like expression.

● [0:19](https://www.youtube.com/watch?v=3VHol7eosLA&t=19). Suppose $𝒇$ has a power series representation.
     ◉ Basic assumption:
          ○ $𝒇$ can be represented by a power series around a center $𝑪$.
     ◉ In other words:
          ○ we assume that $𝒇$ behaves like an infinite polynomial centered at $𝑪$.
     ◉ This means:
          ○ the function is built from powers of $(𝒙-𝑪)$.
     ◉ The center $𝑪$ is the point around which the series is organized.



１．１ - Ｐｏｗｅｒ　Ｓｅｒｉｅｓ　Ｒｅｐｒｅｓｅｎｔａｔｉｏｎ

● [0:52](https://www.youtube.com/watch?v=3VHol7eosLA&t=52). General power series representation.
     ◉ Form:
     $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\displaystyle \sum_{n=0}^{\infty}𝒂_{n}(𝒙-𝑪)^{n}$
          $\rule{0pt}{}$
     ◉ Expanded form:
     $\rule{0pt}{}$
          ○ $𝒇(𝒙)=𝒂_{0}+𝒂_{1}(𝒙-𝑪)+𝒂_{2}(𝒙-𝑪)^{2}+𝒂_{3}(𝒙-𝑪)^{3}+\cdots+𝒂_{n}(𝒙-𝑪)^{n}+\cdots$
          $\rule{0pt}{}$
     ◉ Meaning:
          ○ $𝑪$ is the center.
          ○ $𝒂_{n}$ are the coefficients.
          ○ $(𝒙-𝑪)^{n}$ gives the power-series structure.
     ◉ Important:
          ○ this looks like a polynomial,
          ○ but it has infinitely many terms.
     ◉ Each coefficient $𝒂_{n}$ controls:
          ○ the size of the term with power $n$.
     ◉ Each power $(𝒙-𝑪)^{n}$ measures:
          ○ how far $𝒙$ is from the center $𝑪$.



１．２ - Ｅｘｉｓｔｅｎｃｅ　ｏｆ　Ｄｅｒｉｖａｔｉｖｅｓ

● [1:40](https://www.youtube.com/watch?v=3VHol7eosLA&t=100). Requirement of differentiability.
     ◉ If $𝒇$ has a power series representation,
          ○ then all the way to the $n$-th derivative of $𝒇$ must exist at $𝑪$.
     ◉ Symbolically:
     $\rule{0pt}{}$
          ○ $𝒇^{(n)}(𝑪)$ exists.
     ◉ Reason:
          ○ a power series contains powers of $(𝒙-𝑪)$.
     ◉ Since powers can be differentiated repeatedly,
          ○ the function represented by the power series must also allow repeated differentiation.
     ◉ Key idea:
          ○ if the series has terms up to power $n$,
          ○ then taking derivatives up to order $n$ makes sense.
     ◉ Therefore:
          ○ Taylor series are deeply connected to derivatives.



１．３ - Ｆｉｎｄｉｎｇ　ｔｈｅ　Ｃｏｅｆｆｉｃｉｅｎｔｓ　𝒂ₙ

● [5:05](https://www.youtube.com/watch?v=3VHol7eosLA&t=305). Goal — determine the coefficients $𝒂_{n}$.
     ◉ We want:
          ○ a formula for $𝒂_{n}$ in terms of derivatives of $𝒇$.
     ◉ Why:
          ○ if we can find every $𝒂_{n}$,
          ○ then we can build the whole power series for $𝒇$.
     ◉ The coefficients are not random:
          ○ they are determined by the values of $𝒇$ and its derivatives at the center $𝑪$.


● [5:35](https://www.youtube.com/watch?v=3VHol7eosLA&t=335). Start from the expanded power series.
     ◉ Write:
     $\rule{0pt}{}$
          ○ $𝒇(𝒙)=𝒂_{0}+𝒂_{1}(𝒙-𝑪)+𝒂_{2}(𝒙-𝑪)^{2}+𝒂_{3}(𝒙-𝑪)^{3}+\cdots+𝒂_{n}(𝒙-𝑪)^{n}+\cdots$
          $\rule{0pt}{}$
     ◉ This allows us to see:
          ○ what happens to each term when we differentiate.
     ◉ The key is to track:
          ○ which term becomes a constant after enough derivatives.


● [7:40](https://www.youtube.com/watch?v=3VHol7eosLA&t=460). Take derivatives term by term.
     ◉ First derivative:
     $\rule{0pt}{}$
          ○ $𝒇'(𝒙)=𝒂_{1}+2𝒂_{2}(𝒙-𝑪)+3𝒂_{3}(𝒙-𝑪)^{2}+\cdots+n𝒂_{n}(𝒙-𝑪)^{n-1}+\cdots$
          $\rule{0pt}{}$
     ◉ Second derivative:
     $\rule{0pt}{}$
          ○ $𝒇''(𝒙)=2\cdot 1\cdot 𝒂_{2}+3\cdot 2\cdot 𝒂_{3}(𝒙-𝑪)+\cdots+n(n-1)𝒂_{n}(𝒙-𝑪)^{n-2}+\cdots$
          $\rule{0pt}{}$
     ◉ Third derivative:
     $\rule{0pt}{}$
          ○ $𝒇'''(𝒙)=3\cdot 2\cdot 1\cdot 𝒂_{3}+\cdots+n(n-1)(n-2)𝒂_{n}(𝒙-𝑪)^{n-3}+\cdots$
          $\rule{0pt}{}$
     ◉ Pattern:
          ○ every derivative lowers the power by $1$.
          ○ every derivative brings down one more factor.
     ◉ Therefore:
          ○ the $n$-th derivative eventually brings down all factors from $n$ to $1$.


● [12:19](https://www.youtube.com/watch?v=3VHol7eosLA&t=739). Factorial pattern.
     ◉ Repeated differentiation produces:
          ○ $n(n-1)(n-2)\cdots 3\cdot 2\cdot 1$
     ◉ This is:
          ○ $n!$
     ◉ Meaning:
          ○ factorials appear naturally because derivatives keep bringing down powers.
     ◉ Example idea:
          ○ differentiating $(𝒙-𝑪)^{n}$ once gives $n(𝒙-𝑪)^{n-1}$.
          $\rule{0pt}{}$
          ○ differentiating again gives $n(n-1)(𝒙-𝑪)^{n-2}$.
          $\rule{0pt}{}$
          ○ after $n$ derivatives, the power becomes $0:(𝒙-𝑪)^{n-n}$
     ◉ Since:
          ○ $(𝒙-𝑪)^{0}=1$
     ◉ The remaining coefficient is:
          ○ $n!𝒂_{n}$


● [13:50](https://www.youtube.com/watch?v=3VHol7eosLA&t=830). What happens to the $n$-th term.
     ◉ Start with the $n$-th term:
     $\rule{0pt}{}$
          ○ $𝒂_{n}(𝒙-𝑪)^{n}$
          $\rule{0pt}{}$
     ◉ After one derivative:
     $\rule{0pt}{}$
          ○ $n𝒂_{n}(𝒙-𝑪)^{n-1}$
          $\rule{0pt}{}$
     ◉ After two derivatives:
     $\rule{0pt}{}$
          ○ $n(n-1)𝒂_{n}(𝒙-𝑪)^{n-2}$
          $\rule{0pt}{}$
     ◉ After three derivatives:
     $\rule{0pt}{}$
          ○ $n(n-1)(n-2)𝒂_{n}(𝒙-𝑪)^{n-3}$
          $\rule{0pt}{}$
     ◉ After $n$ derivatives:
          ○ $n!𝒂_{n}$
     ◉ Important:
          ○ the $n$-th term becomes a constant after exactly $n$ derivatives.


● [16:50](https://www.youtube.com/watch?v=3VHol7eosLA&t=1010). Evaluate at the center $𝑪$.
     ◉ When $𝒙=𝑪$:
          ○ every term containing $(𝒙-𝑪)$ becomes $0$.
     ◉ Reason:
          ○ $𝑪-𝑪=0$
     ◉ Therefore:
          ○ all terms that still contain a positive power of $(𝒙-𝑪)$ vanish.
     ◉ The only surviving term is:
          ○ $n!𝒂_{n}$
     ◉ This is the key trick:
          ○ differentiating enough times isolates $𝒂_{n}$.
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $𝒇^{(n)}(𝑪)=n!𝒂_{n}$


● [18:17](https://www.youtube.com/watch?v=3VHol7eosLA&t=1097). Solve for the coefficient.
     ◉ From:
     $\rule{0pt}{}$
          ○ $𝒇^{(n)}(𝑪)=n!𝒂_{n}$
          $\rule{0pt}{}$
     ◉ Divide by $n!$:
     $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{𝒇^{(n)}(𝑪)}{n!}$
          $\rule{0pt}{}$
     ◉ This is the central result:
          ○ every coefficient $𝒂_{n}$ is determined by the $n$-th derivative of $𝒇$ at the center.
     ◉ Meaning:
          ○ the derivatives of $𝒇$ at $𝑪$ encode the whole power series.



１．４ - Ｔａｙｌｏｒ　Ｓｅｒｉｅｓ　Ｆｏｒｍｕｌａ

● [20:46](https://www.youtube.com/watch?v=3VHol7eosLA&t=1246). Taylor series formula. [📷image](./img/Calculus 2 Lecture 9.8/[20-46]-01.png)
     ◉ Substitute:
     $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{𝒇^{(n)}(𝑪)}{n!}$
          $\rule{0pt}{}$
     ◉ Into:
     $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\displaystyle \sum_{n=0}^{\infty}𝒂_{n}(𝒙-𝑪)^{n}$
          $\rule{0pt}{}$
     ◉ Taylor series:
     $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\displaystyle \sum_{n=0}^{\infty}\left[\dfrac{𝒇^{(n)}(𝑪)}{n!}\right](𝒙-𝑪)^{n}$
          $\rule{0pt}{}$
     ◉ Meaning:
          ○ Taylor series rebuilds $𝒇$ from its derivatives at $𝑪$.
     ◉ Each term uses:
          ○ one derivative value,
          ○ one factorial,
          ○ one power of $(𝒙-𝑪)$.


● [21:43](https://www.youtube.com/watch?v=3VHol7eosLA&t=1303). Expanded Taylor series.
     ◉ First terms:
     $\rule{0pt}{}$
          ○ $𝒇(𝑪)$
          $\rule{0pt}{}$
          ○ $+𝒇'(𝑪)(𝒙-𝑪)$
          $\rule{0pt}{}$
          ○ $+\left[\dfrac{𝒇''(𝑪)}{2!}\right](𝒙-𝑪)^{2}$
          $\rule{0pt}{}$
          ○ $+\left[\dfrac{𝒇'''(𝑪)}{3!}\right](𝒙-𝑪)^{3}$
          $\rule{0pt}{}$
          ○ $+\cdots$
     ◉ Interpretation:
          ○ the first term gives the value of the function at the center.
          ○ the second term uses the slope at the center.
          ○ the third term uses curvature information.
          ○ higher terms add more local information about the function.
     ◉ Big idea:
          ○ Taylor series turns derivative information at one point into a full function representation.
          

１．５ - Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　Ｆｏｒｍｕｌａ

● [📷image](./img/Calculus 2 Lecture 9.8/[24-00]-01.png)


● [24:00](https://www.youtube.com/watch?v=3VHol7eosLA&t=1440). Maclaurin series.
     ◉ A Maclaurin series is:
          ○ a Taylor series centered at $𝑪=0$.
     ◉ In other words:
          ○ Maclaurin is not a different kind of series.
          ○ it is a special case of the Taylor series.
     ◉ The only change is:
          ○ the center $𝑪$ becomes $0$.


● [24:38](https://www.youtube.com/watch?v=3VHol7eosLA&t=1478). Taylor versus Maclaurin.
     ◉ Every Maclaurin series is a Taylor series.
     ◉ But not every Taylor series is a Maclaurin series.
     ◉ Reason:
          ○ Maclaurin is the special case $𝑪=0$.
     ◉ Analogy:
          ○ every square is a rectangle,
          ○ but not every rectangle is a square.
     ◉ Similarly:
          ○ every Maclaurin series is a Taylor series,
          ○ but only Taylor series centered at $0$ are Maclaurin series.


● [25:03](https://www.youtube.com/watch?v=3VHol7eosLA&t=1503). What changes when $𝑪=0$.
     ◉ Taylor series:
     $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\displaystyle \sum_{n=0}^{\infty}\left[\dfrac{𝒇^{(n)}(𝑪)}{n!}\right](𝒙-𝑪)^{n}$
     ◉ If:
          ○ $𝑪=0$
     ◉ Then:
          ○ $(𝒙-𝑪)^{n}=(𝒙-0)^{n}$
          $\rule{0pt}{}$
          ○ $(𝒙-0)^{n}=𝒙^{n}$
     ◉ Therefore:
          ○ the formula becomes simpler.


● [25:42](https://www.youtube.com/watch?v=3VHol7eosLA&t=1542). Maclaurin formula.
     ◉ Since:
          ○ $𝑪=0$
     ◉ Then:
     $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\displaystyle \sum_{n=0}^{\infty}\left[\dfrac{𝒇^{(n)}(0)}{n!}\right]𝒙^{n}$
          $\rule{0pt}{}$
     ◉ Expanded form:
     $\rule{0pt}{}$
          ○ $𝒇(𝒙)=𝒇(0)$
          $\rule{0pt}{}$
          ○ $+\left[\dfrac{𝒇'(0)}{1!}\right]𝒙$
          $\rule{0pt}{}$
          ○ $+\left[\dfrac{𝒇''(0)}{2!}\right]𝒙^{2}$
          $\rule{0pt}{}$
          ○ $+\left[\dfrac{𝒇'''(0)}{3!}\right]𝒙^{3}$
          ○ $+\cdots$
     ◉ Meaning:
          ○ all derivatives are evaluated at $0$.
          ○ all powers are powers of $𝒙$.
          ○ there is no $(𝒙-𝑪)$, because the center is $0$.

● N̲O̲T̲E̲ — Main difference.
     ◉ Taylor series:
          ○ centered at any value $𝑪$.
     ◉ Maclaurin series:
          ○ centered only at $0$.
     ◉ So:
          ○ Taylor uses $(𝒙-𝑪)^{n}$.
          ○ Maclaurin uses $𝒙^{n}$.






２ - Ｅｘａｍｐｌｅｓ　ｏｆ　Ｔａｙｌｏｒ　ａｎｄ　Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ


２．１ - Ｅｘａｍｐｌｅ 1:　Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　$𝓮^{x}$

● [📷image-1](./img/Calculus 2 Lecture 9.8/[28-07]-01.png) [📷image-2](./img/Calculus 2 Lecture 9.8/[28-07]-02.png)


● [28:07](https://www.youtube.com/watch?v=3VHol7eosLA&t=1687). 🧩 Example 1 — Find the Taylor series for $𝒇(𝒙)=𝓮^{x}$ at $𝑪=0$.
     ◉ Since:
          ○ $𝑪=0$
     ◉ This is really:
          ○ the Maclaurin series for $𝓮^{x}$.


● [29:10](https://www.youtube.com/watch?v=3VHol7eosLA&t=1750). General method.
     ◉ Steps:
          ○ ❶ Find derivatives of $𝒇$ and look for a pattern.
          ○ ❷ Plug in $𝒙=𝑪$.
          ○ ❸ Set up the series.
          ○ ❹ Find the interval of convergence.


● [30:14](https://www.youtube.com/watch?v=3VHol7eosLA&t=1814). Step ❶ — Find derivatives.
     ◉ Start with:
          ○ $𝒇(𝒙)=𝓮^{x}$
     ◉ Derivatives:
          ○ $𝒇'(𝒙)=𝓮^{x}$
          ○ $𝒇''(𝒙)=𝓮^{x}$
          ○ $𝒇'''(𝒙)=𝓮^{x}$
          ○ $\cdots$
     ◉ Pattern:
          ○ $𝒇^{(n)}(𝒙)=𝓮^{x}$
     ◉ Reason:
          ○ every derivative of $𝓮^{x}$ is still $𝓮^{x}$.


● [32:19](https://www.youtube.com/watch?v=3VHol7eosLA&t=1939). Step ❷ — Plug in $𝒙=𝑪$.
     ◉ Since:
          ○ $𝑪=0$
     ◉ Evaluate at $0$:
          ○ $𝒇(0)=𝓮^{0}=1$
          ○ $𝒇'(0)=𝓮^{0}=1$
          ○ $𝒇''(0)=𝓮^{0}=1$
          ○ $𝒇'''(0)=𝓮^{0}=1$
          ○ $\cdots$
     ◉ Therefore:
          ○ $𝒇^{(n)}(0)=1$


● [34:19](https://www.youtube.com/watch?v=3VHol7eosLA&t=2059). Step ❸ — Build the Maclaurin series.
     ◉ Maclaurin formula:
     $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\displaystyle \sum_{n=0}^{\infty}\left[\dfrac{𝒇^{(n)}(0)}{n!}\right]𝒙^{n}$
          $\rule{0pt}{}$
     ◉ Since:
     $\rule{0pt}{}$
          ○ $𝒇^{(n)}(0)=1$
          $\rule{0pt}{}$
     ◉ Substitute:
     $\rule{0pt}{}$
          ○ $𝓮^{x}=\displaystyle \sum_{n=0}^{\infty}\left[\dfrac{1}{n!}\right]𝒙^{n}$
          $\rule{0pt}{}$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $𝓮^{x}=\displaystyle \sum_{n=0}^{\infty}\dfrac{𝒙^{n}}{n!}$
          $\rule{0pt}{}$
     ◉ Expanded form:
     $\rule{0pt}{}$
          ○ $𝓮^{x}=1+𝒙+\dfrac{𝒙^{2}}{2!}+\dfrac{𝒙^{3}}{3!}+\dfrac{𝒙^{4}}{4!}+\cdots$
          $\rule{0pt}{}$
     ◉ Meaning:
          ○ each term follows the pattern $\dfrac{𝒙^{n}}{n!}$.


● [36:35](https://www.youtube.com/watch?v=3VHol7eosLA&t=2195). Step ❹ — Find the interval of convergence.
     ◉ Use:
          ○ Ratio Test.
     ◉ Reason:
          ○ the series contains $n!$.
          ○ factorials usually suggest the Ratio Test.
     ◉ [38:54](https://www.youtube.com/watch?v=3VHol7eosLA&t=2334). Ratio Test.
          ○ Start with:
          $\rule{0pt}{}$
               ■ $𝒂_{n}=\dfrac{𝒙^{n}}{n!}$
               $\rule{0pt}{}$
          ○ Then:
          $\rule{0pt}{}$
               ■ $𝒂_{n+1}=\dfrac{𝒙^{n+1}}{(n+1)!}$
               $\rule{0pt}{}$
          ○ Compute:
          $\rule{0pt}{}$
               ■ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{𝒂_{n+1}}{𝒂_{n}}\right|$
               $\rule{0pt}{}$
          ○ Substitute:
          $\rule{0pt}{}$
               ■ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{𝒙^{n+1}}{(n+1)!}\cdot \dfrac{n!}{𝒙^{n}}\right|$
               $\rule{0pt}{}$
          ○ Simplify:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒙^{n+1}}{𝒙^{n}}=𝒙$
               $\rule{0pt}{}$
               ■ $\dfrac{n!}{(n+1)!}=\dfrac{1}{n+1}$
               $\rule{0pt}{}$
          ○ Therefore:
          $\rule{0pt}{}$
               ■ $𝑳=\displaystyle \lim_{n\to\infty}\dfrac{|𝒙|}{n+1}$
               $\rule{0pt}{}$
     ◉ [40:23](https://www.youtube.com/watch?v=3VHol7eosLA&t=2423). Limit result.
          ○ Since:
               ■ $𝒙$ is fixed,
               ■ and $n+1\to\infty$
          ○ Then:
          $\rule{0pt}{}$
               ■ $\dfrac{|𝒙|}{n+1}\to 0$
               $\rule{0pt}{}$
          ○ Therefore:
               ■ $𝑳=0$
          ○ This happens:
               ■ for every real value of $𝒙$.
     ◉ [41:15](https://www.youtube.com/watch?v=3VHol7eosLA&t=2475). Interval of convergence.
          ○ Since:
               ■ $𝑳=0<1$
          ○ By the Ratio Test:
               ■ the series converges for all real $𝒙$.
          ○ Therefore:
               ■ interval of convergence is $(-\infty,\infty)$
          ○ Radius:
               ■ $𝑹=\infty$


● [42:06](https://www.youtube.com/watch?v=3VHol7eosLA&t=2526). Final representation.
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $𝓮^{x}=\displaystyle \sum_{n=0}^{\infty}\dfrac{𝒙^{n}}{n!}$
          $\rule{0pt}{}$
     ◉ On:
          ○ $(-\infty,\infty)$
     ◉ Expanded:
          ○ $𝓮^{x}=1+𝒙+\dfrac{𝒙^{2}}{2!}+\dfrac{𝒙^{3}}{3!}+\dfrac{𝒙^{4}}{4!}+\cdots$

● [43:06](https://www.youtube.com/watch?v=3VHol7eosLA&t=2586). Application — approximating $𝓮^{2}$.
     ◉ Use:
     $\rule{0pt}{}$
          ○ $𝓮^{x}=1+𝒙+\dfrac{𝒙^{2}}{2!}+\dfrac{𝒙^{3}}{3!}+\dfrac{𝒙^{4}}{4!}+\cdots$
          $\rule{0pt}{}$
     ◉ Plug in:
          ○ $𝒙=2$
     ◉ Then:
     $\rule{0pt}{}$
          ○ $𝓮^{2}=1+2+\dfrac{2^{2}}{2!}+\dfrac{2^{3}}{3!}+\dfrac{2^{4}}{4!}+\cdots$
          $\rule{0pt}{}$
     ◉ Meaning:
          ○ the more terms we add,
          ○ the better the approximation of $𝓮^{2}$.

● N̲O̲T̲E̲ — Why this example is simple.
     ◉ The derivative pattern is immediate:
          ○ every derivative of $𝓮^{x}$ is $𝓮^{x}$.
     ◉ At $𝒙=0$:
          ○ every derivative equals $1$.
     ◉ Therefore:
          ○ the coefficients are especially simple:
               ■ $\dfrac{1}{n!}$



２．２ - Ｅｘａｍｐｌｅ 2:　Ｔａｙｌｏｒ　Ｓｅｒｉｅｓ　ｆｏｒ　$\ln(𝒙)$　ｃｅｎｔｅｒｅｄ　ａｔ　$𝑪=1$

● [📷image-1](./img/Calculus 2 Lecture 9.8/[45-30]-01.png) [📷image-2](./img/Calculus 2 Lecture 9.8/[45-30]-02.png) [📷image-3](./img/Calculus 2 Lecture 9.8/[45-30]-03.png)

● [45:30](https://www.youtube.com/watch?v=3VHol7eosLA&t=2730). 🧩 Example 2 — Find the Taylor series for $𝒇(𝒙)=\ln(𝒙)$ centered at $𝑪=1$.

● [46:41](https://www.youtube.com/watch?v=3VHol7eosLA&t=2801). Step ❶ — Find derivatives.
     ◉ Start:
     $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\ln(𝒙)$
          $\rule{0pt}{}$
     ◉ Derivatives:
     $\rule{0pt}{}$
          ○ $𝒇'(𝒙)=\dfrac{1}{𝒙}$
          $\rule{0pt}{}$
          ○ $𝒇''(𝒙)=-\dfrac{1}{𝒙^{2}}$
          $\rule{0pt}{}$
          ○ $𝒇'''(𝒙)=\dfrac{2!}{𝒙^{3}}$
          $\rule{0pt}{}$
          ○ $𝒇^{(4)}(𝒙)=-\dfrac{3!}{𝒙^{4}}$
          $\rule{0pt}{}$
          ○ $𝒇^{(5)}(𝒙)=\dfrac{4!}{𝒙^{5}}$
          $\rule{0pt}{}$
     ◉ Pattern:
          ○ alternating signs.
          ○ factorial behavior.
          ○ powers of $𝒙$ in the denominator.
     ◉ General derivative:
     $\rule{0pt}{}$
          ○ $𝒇^{(n)}(𝒙)=\dfrac{(-1)^{n-1}(n-1)!}{𝒙^{n}}$


● [51:59](https://www.youtube.com/watch?v=3VHol7eosLA&t=3119). Step ❷ — Evaluate at the center $𝑪=1$.
     ◉ Since:
          ○ $𝒙=1$
     ◉ The derivative values become:
          ○ $𝒇(1)=0$
          ○ $𝒇'(1)=1$
          ○ $𝒇''(1)=-1!$
          ○ $𝒇'''(1)=2!$
          ○ $𝒇^{(4)}(1)=-3!$
          ○ $𝒇^{(5)}(1)=4!$
     ◉ Pattern:
          ○ $𝒇^{(n)}(1)=(-1)^{n-1}(n-1)!$


● [54:59](https://www.youtube.com/watch?v=3VHol7eosLA&t=3299). Step ❸ — Build and simplify the Taylor series.
     ◉ Taylor formula:
     $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\displaystyle \sum_{n=0}^{\infty}\left[\dfrac{𝒇^{(n)}(𝑪)}{n!}\right](𝒙-𝑪)^{n}$
          $\rule{0pt}{}$
     ◉ Since:
          ○ $𝑪=1$
     ◉ Then:
     $\rule{0pt}{}$
          ○ $\ln(𝒙)=\displaystyle \sum_{n=1}^{\infty}\left[\dfrac{𝒇^{(n)}(1)}{n!}\right](𝒙-1)^{n}$
          $\rule{0pt}{}$
     ◉ Substitute:
     $\rule{0pt}{}$
          ○ $𝒇^{(n)}(1)=(-1)^{n-1}(n-1)!$
          $\rule{0pt}{}$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\ln(𝒙)=\displaystyle \sum_{n=1}^{\infty}\left[\dfrac{(-1)^{n-1}(n-1)!(𝒙-1)^{n}}{n!}\right]$
          $\rule{0pt}{}$
     ◉ Simplify:
     $\rule{0pt}{}$
          ○ $\dfrac{(n-1)!}{n!}=\dfrac{1}{n}$
          $\rule{0pt}{}$
     ◉ Final Taylor series:
     $\rule{0pt}{}$
          ○ $\ln(𝒙)=\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n-1}(𝒙-1)^{n}}{n}$


● [1:00:00](https://www.youtube.com/watch?v=3VHol7eosLA&t=3600). Step ❹ — Find the interval of convergence.
     ◉ Use:
          ○ Ratio Test.
     ◉ Start with:
     $\rule{0pt}{}$
          ○ $𝒂_{n}=\dfrac{(-1)^{n-1}(𝒙-1)^{n}}{n}$
          $\rule{0pt}{}$
     ◉ Then:
     $\rule{0pt}{}$
          ○ $𝒂_{n+1}=\dfrac{(-1)^{n}(𝒙-1)^{n+1}}{n+1}$
          $\rule{0pt}{}$
     ◉ Compute:
     $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left|\dfrac{𝒂_{n+1}}{𝒂_{n}}\right|$
          $\rule{0pt}{}$
     ◉ After simplifying:
     $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{n\to\infty}\left[\dfrac{n}{n+1}\right]|𝒙-1|$
          $\rule{0pt}{}$
     ◉ Since:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{n\to\infty}\dfrac{n}{n+1}=1$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ $𝑳=|𝒙-1|$
     ◉ Apply the Ratio Test condition.
          ○ Ratio Test convergence requires:
               ■ $𝑳<1$
          ○ Since:
               ■ $𝑳=|𝒙-1|$
          ○ We need:
               ■ $|𝒙-1|<1$
     ◉ Radius and preliminary interval.
          ○ Compare with the standard form:
               ■ $|𝒙-𝑪|<𝑹$
          ○ Here:
               ■ $|𝒙-1|<1$
          ○ Therefore:
               ■ center $𝑪=1$
               ■ radius $𝑹=1$
          ○ Meaning:
               ■ from the center $1$, move $1$ unit left and $1$ unit right.
          ○ So:
               ■ $1-1<𝒙<1+1$
               ■ $0<𝒙<2$
          ○ Preliminary interval:
               ■ $(0,2)$


● [1:06:12](https://www.youtube.com/watch?v=3VHol7eosLA&t=3972). Endpoint $𝒙=0$.
     ◉ Plug into the Taylor series:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n-1}(0-1)^{n}}{n}$
          $\rule{0pt}{}$
     ◉ Since:
     $\rule{0pt}{}$
          ○ $(0-1)^{n}=(-1)^{n}$
          $\rule{0pt}{}$
     ◉ Then:
     $\rule{0pt}{}$
          ○ $(-1)^{n-1}(-1)^{n}=(-1)^{2n-1}$
          $\rule{0pt}{}$
     ◉ Since:
          ○ $2n-1$ is always odd
     ◉ We get:
     $\rule{0pt}{}$
          ○ $(-1)^{2n-1}=-1$
          $\rule{0pt}{}$
     ◉ Therefore the series becomes:
     $\rule{0pt}{}$
          ○ $-\displaystyle \sum_{n=1}^{\infty}\dfrac{1}{n}$
          $\rule{0pt}{}$
     ◉ This is:
          ○ the negative harmonic series.
     ◉ Since the harmonic series diverges:
          ○ this endpoint diverges.
     ◉ Therefore:
          ○ $𝒙=0$ is not included.


● [1:10:30](https://www.youtube.com/watch?v=3VHol7eosLA&t=4230). Endpoint $𝒙=2$.
     ◉ Plug into the Taylor series:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n-1}(2-1)^{n}}{n}$
          $\rule{0pt}{}$
     ◉ Since:
     $\rule{0pt}{}$
          ○ $(2-1)^{n}=1^{n}=1$
          $\rule{0pt}{}$
     ◉ The series becomes:
     $\rule{0pt}{}$
          ○ $\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n-1}}{n}$
          $\rule{0pt}{}$
     ◉ This is:
          ○ the alternating harmonic series.
     ◉ It converges by:
          ○ Alternating Series Test.
     ◉ Therefore:
          ○ $𝒙=2$ is included.


● [1:12:52](https://www.youtube.com/watch?v=3VHol7eosLA&t=4372). Final result.
     ◉ Taylor series:
          ○ $\ln(𝒙)=\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n-1}(𝒙-1)^{n}}{n}$
     ◉ Center:
          ○ $𝑪=1$
     ◉ Radius:
          ○ $𝑹=1$
     ◉ Interval of convergence:
          ○ $(0,2]$



２．３ - Ｅｘａｍｐｌｅ 3:　Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　Ｓｉｎｅ　ａｎｄ　Ｃｏｓｉｎｅ

● [📷image-1](./img/Calculus 2 Lecture 9.8/[1-14-34]-01.png) [📷image-2](./img/Calculus 2 Lecture 9.8/[1-14-34]-02.png) [📷image-3](./img/Calculus 2 Lecture 9.8/[1-14-34]-03.png) [📷image-4](./img/Calculus 2 Lecture 9.8/[1-14-34]-04.png)

● [1:14:34](https://www.youtube.com/watch?v=3VHol7eosLA&t=4474). 🧩 Example 3 — Find the Maclaurin series for $\sin(𝒙)$ and $\cos(𝒙)$

● [1:15:52](https://www.youtube.com/watch?v=3VHol7eosLA&t=4552). Step ❶ — Find derivatives.
     ◉ Start:
          ○ $𝒇(𝒙)=\sin(𝒙)$
     ◉ Derivatives:
          ○ $𝒇'(𝒙)=\cos(𝒙)$
          ○ $𝒇''(𝒙)=-\sin(𝒙)$
          ○ $𝒇'''(𝒙)=-\cos(𝒙)$
          ○ $𝒇^{(4)}(𝒙)=\sin(𝒙)$
     ◉ Pattern:
          ○ the derivatives repeat in a cycle:
               ■ $\sin(𝒙)$
               ■ $\cos(𝒙)$
               ■ $-\sin(𝒙)$
               ■ $-\cos(𝒙)$
               ■ $\sin(𝒙)$
          ○ because of this cycle, it is not convenient to write one simple formula for $𝒇^{(n)}(𝒙)$ directly.


● [1:17:53](https://www.youtube.com/watch?v=3VHol7eosLA&t=4673). Step ❷ — Evaluate at $𝒙=0$.
     ◉ Since this is a Maclaurin series:
          ○ $𝑪=0$
     ◉ Evaluate the derivative cycle at $0$:
          ○ $\sin(0)=0$
          ○ $\cos(0)=1$
          ○ $-\sin(0)=0$
          ○ $-\cos(0)=-1$
          ○ $\sin(0)=0$
     ◉ Therefore the values repeat as:
          ○ $0,1,0,-1,0,1,0,-1,\dots$
     ◉ Meaning:
          ○ the even-power terms disappear.
          ○ only the odd-power terms survive.


● [1:18:38](https://www.youtube.com/watch?v=3VHol7eosLA&t=4718). Write out the Maclaurin series terms.
     ◉ Maclaurin formula:
     $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\displaystyle \sum_{n=0}^{\infty}\left[\dfrac{𝒇^{(n)}(0)}{n!}\right]𝒙^{n}$
          $\rule{0pt}{}$
     ◉ Expanded:
     $\rule{0pt}{}$
          ○ $\sin(𝒙)=𝒇(0)+𝒇'(0)𝒙+\left[\dfrac{𝒇''(0)}{2!}\right]𝒙^{2}+\left[\dfrac{𝒇'''(0)}{3!}\right]𝒙^{3}+\left[\dfrac{𝒇^{(4)}(0)}{4!}\right]𝒙^{4}+\cdots$
          $\rule{0pt}{}$
     ◉ Substitute the values:
     $\rule{0pt}{}$
          ○ $\sin(𝒙)=0+𝒙+0+\left[\dfrac{(-1)𝒙^{3}}{3!}\right]+0+\dfrac{𝒙^{5}}{5!}+0+\left[\dfrac{(-1)𝒙^{7}}{7!}\right]+\cdots$
          $\rule{0pt}{}$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\sin(𝒙)=𝒙-\dfrac{𝒙^{3}}{3!}+\dfrac{𝒙^{5}}{5!}-\dfrac{𝒙^{7}}{7!}+\cdots$


● [1:23:57](https://www.youtube.com/watch?v=3VHol7eosLA&t=5037). Step ❸ — Rewrite the pattern using a new index.
     ◉ The surviving powers are:
          ○ $1,3,5,7,\dots$
     ◉ These are odd powers.
     ◉ Odd powers can be written as:
          ○ $2𝒌+1$
     ◉ The signs alternate:
          ○ positive, negative, positive, negative, $\dots$
     ◉ Alternating sign pattern:
          ○ $(-1)^{k}$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\sin(𝒙)=\displaystyle \sum_{k=0}^{\infty}\dfrac{(-1)^{k}𝒙^{2k+1}}{(2k+1)!}$


● [1:28:18](https://www.youtube.com/watch?v=3VHol7eosLA&t=5298). Step ❹ — Find the interval of convergence.
     ◉ Use:
          ○ Ratio Test.
     ◉ Start with:
     $\rule{0pt}{}$
          ○ $𝒂_{k}=\dfrac{(-1)^{k}𝒙^{2k+1}}{(2k+1)!}$
          $\rule{0pt}{}$
     ◉ Then:
     $\rule{0pt}{}$
          ○ $𝒂_{k+1}=\dfrac{(-1)^{k+1}𝒙^{2k+3}}{(2k+3)!}$
          $\rule{0pt}{}$
     ◉ Compute:
     $\rule{0pt}{}$
          ○ $𝑳=\displaystyle \lim_{k\to\infty}\left|\dfrac{𝒂_{k+1}}{𝒂_{k}}\right|$
          $\rule{0pt}{}$
     ◉ Simplify the Ratio Test expression.
          ○ Powers of $𝒙$:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒙^{2k+3}}{𝒙^{2k+1}}=𝒙^{2}$
               $\rule{0pt}{}$
          ○ Factorials:
          $\rule{0pt}{}$
               ■ $\dfrac{(2k+1)!}{(2k+3)!}=\dfrac{1}{(2k+3)(2k+2)}$
               $\rule{0pt}{}$
          ○ Therefore:
          $\rule{0pt}{}$
               ■ $𝑳=\displaystyle \lim_{k\to\infty}\dfrac{𝒙^{2}}{(2k+3)(2k+2)}$
               $\rule{0pt}{}$
     ◉ Limit result.
          ○ Since:
               ■ $𝒙$ is fixed.
               ■ $(2k+3)(2k+2)\to\infty$
          ○ Then:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒙^{2}}{(2k+3)(2k+2)}\to 0$
               $\rule{0pt}{}$
          ○ Therefore:
               ■ $𝑳=0$
          ○ This happens:
               ■ for every real value of $𝒙$.
     ◉ Interval of convergence for Sine.
          ○ Since:
               ■ $𝑳=0<1$
          ○ By the Ratio Test:
               ■ the series converges for all real $𝒙$.
          ○ Therefore:
               ■ radius of convergence $𝑹=\infty$
               ■ interval of convergence is $(-\infty,\infty)$


● [1:34:07](https://www.youtube.com/watch?v=3VHol7eosLA&t=5647). Final Maclaurin series for Sine.
     ◉ Therefore:
          ○ $\sin(𝒙)=\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}𝒙^{2n+1}}{(2n+1)!}$
     ◉ Expanded:
          ○ $\sin(𝒙)=𝒙-\dfrac{𝒙^{3}}{3!}+\dfrac{𝒙^{5}}{5!}-\dfrac{𝒙^{7}}{7!}+\cdots$
     ◉ On:
          ○ $(-\infty,\infty)$


● [1:36:17](https://www.youtube.com/watch?v=3VHol7eosLA&t=5777). Derive Cosine from the Sine series.
     ◉ Since:
          ○ the derivative of $\sin(𝒙)$ is $\cos(𝒙)$
     ◉ And:
          ○ $\sin(𝒙)=𝒙-\dfrac{𝒙^{3}}{3!}+\dfrac{𝒙^{5}}{5!}-\dfrac{𝒙^{7}}{7!}+\cdots$
          $\rule{0pt}{}$
     ◉ Differentiate both sides term by term:
     $\rule{0pt}{}$
          ○ $\cos(𝒙)=$ derivative of $\left[𝒙-\dfrac{𝒙^{3}}{3!}+\dfrac{𝒙^{5}}{5!}-\dfrac{𝒙^{7}}{7!}+\cdots\right]$
          $\rule{0pt}{}$
     ◉ Term-by-term result:
          ○ derivative of $𝒙$ is $1$
          $\rule{0pt}{}$
          ○ derivative of $-\dfrac{𝒙^{3}}{3!}$ is $-\dfrac{𝒙^{2}}{2!}$
          $\rule{0pt}{}$
          ○ derivative of $\dfrac{𝒙^{5}}{5!}$ is $\dfrac{𝒙^{4}}{4!}$
          $\rule{0pt}{}$
          ○ derivative of $-\dfrac{𝒙^{7}}{7!}$ is $-\dfrac{𝒙^{6}}{6!}$
          $\rule{0pt}{}$
     ◉ Therefore:
          ○ $\cos(𝒙)=1-\dfrac{𝒙^{2}}{2!}+\dfrac{𝒙^{4}}{4!}-\dfrac{𝒙^{6}}{6!}+\cdots$
          $\rule{0pt}{}$
     ◉ Final Maclaurin series for Cosine.
          ○ Series notation:
          $\rule{0pt}{}$
               ■ $\cos(𝒙)=\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}𝒙^{2n}}{(2n)!}$
               $\rule{0pt}{}$
          ○ Expanded:
               ■ $\cos(𝒙)=1-\dfrac{𝒙^{2}}{2!}+\dfrac{𝒙^{4}}{4!}-\dfrac{𝒙^{6}}{6!}+\cdots$
               $\rule{0pt}{}$
          ○ Interval of convergence:
               ■ $(-\infty,\infty)$


● N̲O̲T̲E̲ — Why Cosine comes from Sine.
     ◉ Leonard does not rebuild the Cosine series from scratch.
     ◉ He uses the Sine series already found.
     ◉ Since:
          ○ $\cos(𝒙)$ is the derivative of $\sin(𝒙)$
     ◉ Then:
          ○ the Cosine series is obtained by differentiating the Sine series term by term.
     ◉ This lowers:
          ○ each power by $1$.
          ○ each factorial by $1$.
     ◉ That is why:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒙^{3}}{3!}$ becomes $\dfrac{𝒙^{2}}{2!}$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒙^{5}}{5!}$ becomes $\dfrac{𝒙^{4}}{4!}$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒙^{7}}{7!}$ becomes $\dfrac{𝒙^{6}}{6!}$



２．４ - Ｅｘａｍｐｌｅ 4:　Ｂｉｎｏｍｉａｌ　Ｓｅｒｉｅｓ　ｆｏｒ　$(1+𝒙)^{k}$

● [📷image-1](./img/Calculus 2 Lecture 9.8/[1-38-58]-01.png) [📷image-2](./img/Calculus 2 Lecture 9.8/[1-38-58]-02.png) 


● [1:38:58](https://www.youtube.com/watch?v=3VHol7eosLA&t=5938). 🧩 Example 4 — The Binomial Series: $𝒇(𝒙)=(1+𝒙)^{k}$
     ◉ Here:
          ○ $k$ is a real number.
     ◉ Goal:
          ○ find the Maclaurin series for $(1+𝒙)^{k}$.


● [1:39:58](https://www.youtube.com/watch?v=3VHol7eosLA&t=5998). Step ❶ — Find derivatives.
     ◉ Start with:
          ○ $𝒇(𝒙)=(1+𝒙)^{k}$
     ◉ First derivatives:
          ○ $𝒇'(𝒙)=k(1+𝒙)^{k-1}$
          ○ $𝒇''(𝒙)=k(k-1)(1+𝒙)^{k-2}$
          ○ $𝒇'''(𝒙)=k(k-1)(k-2)(1+𝒙)^{k-3}$
          ○ $𝒇^{(4)}(𝒙)=k(k-1)(k-2)(k-3)(1+𝒙)^{k-4}$
     ◉ Pattern:
          ○ each derivative brings down one more factor.
          ○ the factors are:
               ■ $k$
               ■ $k-1$
               ■ $k-2$
               ■ $k-3$
               ■ $\cdots$
     ◉ [1:42:04](https://www.youtube.com/watch?v=3VHol7eosLA&t=6124). General derivative pattern.
          ○ For the $n$-th derivative:
          $\rule{0pt}{}$
               ■ $𝒇^{(n)}(𝒙)=k(k-1)(k-2)\cdots(k-n+1)(1+𝒙)^{k-n}$
               $\rule{0pt}{}$
          ○ General factor:
               ■ the $i$-th factor is $k-i+1$,
               ■ where $i=1,2,\dots,n$.
          ○ Compact product notation:
          $\rule{0pt}{}$
               ■ $𝒇^{(n)}(𝒙)=\left[\displaystyle \prod_{i=1}^{n}(k-i+1)\right](1+𝒙)^{k-n}$


● [1:44:20](https://www.youtube.com/watch?v=3VHol7eosLA&t=6260). Step ❷ — Evaluate at $𝒙=0$.
     ◉ Since:
          ○ $1+0=1$
     ◉ Then:
          ○ $(1+0)^{k-n}=1$
     ◉ Therefore:
          ○ $𝒇^{(n)}(0)=k(k-1)(k-2)\cdots(k-n+1)$
     ◉ Compact notation:
     $\rule{0pt}{}$
          ○ $𝒇^{(n)}(0)=\displaystyle \prod_{i=1}^{n}(k-i+1)$
     ◉ Important:
          ○ for $n=0$, the product is empty.
          ○ by convention, the empty product is $1$.
          ○ this gives the first term of the Maclaurin series.


● [1:45:18](https://www.youtube.com/watch?v=3VHol7eosLA&t=6318). Step ❸ — Build the Maclaurin series.
     ◉ Maclaurin formula:
     $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\displaystyle \sum_{n=0}^{\infty}\left[\dfrac{𝒇^{(n)}(0)}{n!}\right]𝒙^{n}$
          $\rule{0pt}{}$
     ◉ Substitute:
     $\rule{0pt}{}$
          ○ $𝒇^{(n)}(0)=k(k-1)(k-2)\cdots(k-n+1)$
          $\rule{0pt}{}$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $(1+𝒙)^{k}=\displaystyle \sum_{n=0}^{\infty}\left[\dfrac{k(k-1)(k-2)\cdots(k-n+1)}{n!}\right]𝒙^{n}$
          $\rule{0pt}{}$
     ◉ [1:47:24](https://www.youtube.com/watch?v=3VHol7eosLA&t=6444). Expanded Binomial Series.
          ○ The first terms are:
          $\rule{0pt}{}$
               ■ $(1+𝒙)^{k}=1+k𝒙+\left[\dfrac{k(k-1)}{2!}\right]𝒙^{2}+\left[\dfrac{k(k-1)(k-2)}{3!}\right]𝒙^{3}+\cdots$
               $\rule{0pt}{}$
          ○ Meaning:
               ■ the coefficient of $𝒙^{n}$ is built from the falling product:
                    ▣ $k(k-1)(k-2)\cdots(k-n+1)$
               ■ divided by:
                    ▣ $n!$
     ◉ [1:52:27](https://www.youtube.com/watch?v=3VHol7eosLA&t=6747). Binomial coefficient notation.
          ○ The coefficient:
          $\rule{0pt}{}$
               ■ $\dfrac{k(k-1)(k-2)\cdots(k-n+1)}{n!}$
               $\rule{0pt}{}$
          ○ is called:
               ■ the binomial coefficient.
          ○ It is read as:
               ■ “$k$ choose $n$”
          ○ Standard notation:
          $\rule{0pt}{}$
               ■ $\binom{k}{n}$
               $\rule{0pt}{}$
          ○ Meaning:
               ■ it gives the coefficient of $𝒙^{n}$ in the binomial series.
          ○ Therefore:
          $\rule{0pt}{}$
               ■ $(1+𝒙)^{k}=\displaystyle \sum_{n=0}^{\infty}\binom{k}{n}𝒙^{n}$


● [1:53:39](https://www.youtube.com/watch?v=3VHol7eosLA&t=6819). Step ❹ — Convergence cases for the Binomial Series.
     ◉ C̲a̲s̲e̲ ̲1̲ ̲— $k$ is a nonnegative integer:
          ○ $k\in\{0,1,2,3,\dots\}$
          ○ t̲h̲e̲n̲:
               ■ the binomial series stops after finitely many terms.
               ■ therefore it becomes an ordinary polynomial.
               ■ it converges for all real $𝒙$.
               ■ interval of convergence: $(-\infty,\infty)$
     ◉ C̲a̲s̲e̲ ̲2̲  — $k$ is not a nonnegative integer:
          ○ $k\notin\{0,1,2,3,\dots\}$
          ○ t̲h̲e̲n̲:
               ■ the binomial series is infinite.
               ■ the basic convergence interval is:
                    ▣ $-1<𝒙<1$
               ■ radius of convergence:
                    ▣ $𝑹=1$
               ■ endpoint behavior depends on $k$.
     ◉ [1:56:33](https://www.youtube.com/watch?v=3VHol7eosLA&t=6993). Endpoint cases when $k\notin\{0,1,2,3,\dots\}$.
          ○ i̲f̲ $k\leq -1$
               ■ t̲h̲e̲n̲:
                    ▣ neither endpoint is included.
                    ▣ interval: $(-1,1)$
          ○ i̲f̲ $-1<k<0$
               ■ t̲h̲e̲n̲:
                    ▣ only $𝒙=1$ is included.
                    ▣ interval: $(-1,1]$
          ○ i̲f̲ $k>0$ and $k\notin\{0,1,2,3,\dots\}$
               ■ t̲h̲e̲n̲:
                    ▣ both endpoints are included.
                    ▣ interval: $[-1,1]$
               
● N̲O̲T̲E̲ 1 — Binomial coefficients become polynomial coefficients.
     ◉ Main idea:
          ○ when $k$ is a nonnegative integer,
               ■ the binomial series stops after finitely many terms.
               ■ therefore it becomes an ordinary polynomial.
          ○ the binomial coefficients become the coefficients of that polynomial.
     ◉ Notation:
     $\rule{0pt}{}$
          ○ $\binom{k}{n}$ means “$k$ over $n$”.
          $\rule{0pt}{}$
          ○ In standard mathematical notation:
          $\rule{0pt}{}$
               ■ $\binom{k}{n}=$ binomial coefficient.
               $\rule{0pt}{}$
          ○ It represents:
          $\rule{0pt}{}$
               ■ $\dfrac{k(k-1)(k-2)\cdots(k-n+1)}{n!}$
          ○ Meaning:
          $\rule{0pt}{}$
               ■ $\binom{k}{n}$ gives the coefficient of $𝒙^{n}$ in the binomial expansion.
               $\rule{0pt}{}$
     ◉ Example:
          ○ let $k=4$.
          ○ Start from the binomial series:
          $\rule{0pt}{}$
               ■ $(1+𝒙)^{k}=\displaystyle \sum_{n=0}^{\infty}\binom{k}{n}𝒙^{n}$
               $\rule{0pt}{}$
          ○ Substitute:
               ■ $k=4$
          ○ Then:
               ■ $(1+𝒙)^{4}=\displaystyle \sum_{n=0}^{\infty}\binom{4}{n}𝒙^{n}$
               $\rule{0pt}{}$
          ○ But since $k=4$ is a nonnegative integer,
               ■ the series stops at $n=4$.
          ○ Therefore:
          $\rule{0pt}{}$
               ■ $(1+𝒙)^{4}=\displaystyle \sum_{n=0}^{4}\binom{4}{n}𝒙^{n}$
               $\rule{0pt}{}$
     ◉ Expand the sum term by term:
     $\rule{0pt}{}$
          ○ $(1+𝒙)^{4}$
          $\rule{0pt}{}$
               ■ $=\binom{4}{0}𝒙^{0}$
               $\rule{0pt}{}$
               ■ $+\binom{4}{1}𝒙^{1}$
               $\rule{0pt}{}$
               ■ $+\binom{4}{2}𝒙^{2}$
               $\rule{0pt}{}$
               ■ $+\binom{4}{3}𝒙^{3}$
               $\rule{0pt}{}$
               ■ $+\binom{4}{4}𝒙^{4}$
               $\rule{0pt}{}$
     ◉ Compute each binomial coefficient.
          ○ First coefficient:
          $\rule{0pt}{}$
               ■ $\binom{4}{0}=1$
               $\rule{0pt}{}$
               ■ So:
               $\rule{0pt}{}$
                    ▣ $\binom{4}{0}𝒙^{0}=1\cdot 𝒙^{0}=1$
                    $\rule{0pt}{}$
          ○ Second coefficient:
          $\rule{0pt}{}$
               ■ $\binom{4}{1}=\dfrac{4}{1!}$
               $\rule{0pt}{}$
               ■ Since:
                    ▣ $1!=1$
               ■ Then:
               $\rule{0pt}{}$
                    ▣ $\binom{4}{1}=4$
                    $\rule{0pt}{}$
               ■ So:
               $\rule{0pt}{}$
                    ▣ $\binom{4}{1}𝒙^{1}=4𝒙$
                    $\rule{0pt}{}$
          ○ Third coefficient:
          $\rule{0pt}{}$
               ■ $\binom{4}{2}=\dfrac{4(4-1)}{2!}$
               $\rule{0pt}{}$
               ■ Simplify:
                    ▣ $\binom{4}{2}=\dfrac{4\cdot 3}{2!}$
                    $\rule{0pt}{}$
                    ▣ $\binom{4}{2}=\dfrac{12}{2}$
                    $\rule{0pt}{}$
                    ▣ $\binom{4}{2}=6$
                    $\rule{0pt}{}$
               ■ So:
                    ▣ $\binom{4}{2}𝒙^{2}=6𝒙^{2}$
                    $\rule{0pt}{}$
          ○ Fourth coefficient:
          $\rule{0pt}{}$
               ■ $\binom{4}{3}=\dfrac{4(4-1)(4-2)}{3!}$
               $\rule{0pt}{}$
               ■ Simplify:
               $\rule{0pt}{}$
                    ▣ $\binom{4}{3}=\dfrac{4\cdot 3\cdot 2}{3!}$
                    $\rule{0pt}{}$
                    ▣ $\binom{4}{3}=\dfrac{24}{6}$
                    $\rule{0pt}{}$
                    ▣ $\binom{4}{3}=4$
                    $\rule{0pt}{}$
               ■ So:
               $\rule{0pt}{}$
                    ▣ $\binom{4}{3}𝒙^{3}=4𝒙^{3}$
                    $\rule{0pt}{}$
          ○ Fifth coefficient:
          $\rule{0pt}{}$
               ■ $\binom{4}{4}=\dfrac{4(4-1)(4-2)(4-3)}{4!}$
               $\rule{0pt}{}$
               ■ Simplify:
               $\rule{0pt}{}$
                    ▣ $\binom{4}{4}=\dfrac{4\cdot 3\cdot 2\cdot 1}{4!}$
                    $\rule{0pt}{}$
                    ▣ $\binom{4}{4}=\dfrac{24}{24}$
                    $\rule{0pt}{}$
                    ▣ $\binom{4}{4}=1$
                    $\rule{0pt}{}$
               ■ So:
               $\rule{0pt}{}$
                    ▣ $\binom{4}{4}𝒙^{4}=𝒙^{4}$
                    $\rule{0pt}{}$
     ◉ Put all the terms together:
     $\rule{0pt}{}$
          ○ $(1+𝒙)^{4}=1+4𝒙+6𝒙^{2}+4𝒙^{3}+𝒙^{4}$
          $\rule{0pt}{}$
     ◉ Coefficient pattern:
          ○ $1,4,6,4,1$
     ◉ Meaning:
          ○ the binomial coefficients:
          $\rule{0pt}{}$
               ■ $\binom{4}{0}$
               $\rule{0pt}{}$
               ■ $\binom{4}{1}$
               $\rule{0pt}{}$
               ■ $\binom{4}{2}$
               $\rule{0pt}{}$
               ■ $\binom{4}{3}$
               $\rule{0pt}{}$
               ■ $\binom{4}{4}$
               $\rule{0pt}{}$
          ○ become the polynomial coefficients:
               ■ $1,4,6,4,1$
     ◉ Therefore:
          ○ the coefficient of $𝒙^{n}$ in $(1+𝒙)^{4}$ is:
          $\rule{0pt}{}$
               ■ $\binom{4}{n}$
               $\rule{0pt}{}$
     ◉ Final takeaway:
          ○ binomial coefficients are exactly the coefficients that appear when expanding powers like:
               ■ $(1+𝒙)^{4}$
          ○ and they match the corresponding row of Pascal's Triangle:
               ■ $1,4,6,4,1$
     ◉ Important:
          ○ for $n=0$, the product $k(k-1)(k-2)\cdots(k-n+1)$ is empty.
          ○ by convention, an empty product equals $1$.
          ○ therefore:
               ■ $\binom{k}{0}=1$

              
● N̲O̲T̲E̲ 2 — Best way to write the binomial coefficient.
     ◉ The cleanest way to express the binomial coefficient is:
     $\rule{0pt}{}$
          ○ $\binom{k}{n}=\dfrac{\displaystyle \prod_{i=1}^{n}(k-i+1)}{n!}$
          $\rule{0pt}{}$
     ◉ Meaning:
          ○ the numerator is a product.
          ○ we multiply all the factors:
               ■ $k-i+1$
          ○ where:
               ■ $i=1,2,3,\dots,n$
     ◉ Expanded form:
     $\rule{0pt}{}$
          ○ $\binom{k}{n}=\dfrac{k(k-1)(k-2)\cdots(k-n+1)}{n!}$
          $\rule{0pt}{}$
     ◉ Why the product notation is better:
          ○ it shows exactly where the product starts.
          ○ it shows exactly where the product ends.
          ○ it avoids confusion when $n=0$.
     ◉ Important special case:
          ○ if $n=0$,
               ■ the product $\displaystyle \prod_{i=1}^{0}$ is empty.
               $\rule{0pt}{}$
               ■ by convention, an empty product equals $1$.
               ■ also, $0!=1$.
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\binom{k}{0}=\dfrac{1}{1}=1$
          $\rule{0pt}{}$
     ◉ Example:
     $\rule{0pt}{}$
          ○ $\binom{4}{0}=1$
          $\rule{0pt}{}$
          ○ not $5$.
     ◉ Reason:
          ○ when $n=0$, there is no factor $k-n+1$.
          ○ the product is empty.
          ○ so the numerator is $1$.

               
２．５ - Ｅｘａｍｐｌｅ 5:　Ｂｉｎｏｍｉａｌ　Ｓｅｒｉｅｓ　ｆｏｒ　$\sqrt{1+𝒙}$

● [📷image-1](./img/Calculus 2 Lecture 9.8/[1-59-18]-01.png) [📷image-2](./img/Calculus 2 Lecture 9.8/[1-59-18]-02.png) 

● [1:59:18](https://www.youtube.com/watch?v=3VHol7eosLA&t=7158). 🧩 Example 5 — Binominal Series: $\sqrt{1+𝒙}$.
     ◉ Start with:
     $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\sqrt{1+𝒙}$
          $\rule{0pt}{}$
     ◉ Rewrite the square root as a power:
     $\rule{0pt}{}$
          ○ $\sqrt{1+𝒙}=(1+𝒙)^{1/2}$
          $\rule{0pt}{}$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $k=\dfrac{1}{2}$
          $\rule{0pt}{}$
     ◉ Goal:
          ○ use the Binomial Series for $(1+𝒙)^{k}$.


● [2:00:45](https://www.youtube.com/watch?v=3VHol7eosLA&t=7245). Substitute $k=\dfrac{1}{2}$ into the Binomial Series.
$\rule{0pt}{}$
     ◉ General Binomial Series:
     $\rule{0pt}{}$
          ○ $(1+𝒙)^{k}=1+k𝒙+\left[\dfrac{k(k-1)}{2!}\right]𝒙^{2}+\left[\dfrac{k(k-1)(k-2)}{3!}\right]𝒙^{3}+\cdots$
          $\rule{0pt}{}$
     ◉ Substitute:
     $\rule{0pt}{}$
          ○ $k=\dfrac{1}{2}$
          $\rule{0pt}{}$
     ◉ Then:
     $\rule{0pt}{}$
          ○ $(1+𝒙)^{1/2}$
          $\rule{0pt}{}$
          ○ $=1+\left(\dfrac{1}{2}\right)𝒙$
          $\rule{0pt}{}$
          ○ $+\left[\dfrac{\left(\dfrac{1}{2}\right)\left(\dfrac{1}{2}-1\right)}{2!}\right]𝒙^{2}$
          $\rule{0pt}{}$
          ○ $+\left[\dfrac{\left(\dfrac{1}{2}\right)\left(\dfrac{1}{2}-1\right)\left(\dfrac{1}{2}-2\right)}{3!}\right]𝒙^{3}$
          $\rule{0pt}{}$
          ○ $+\left[\dfrac{\left(\dfrac{1}{2}\right)\left(\dfrac{1}{2}-1\right)\left(\dfrac{1}{2}-2\right)\left(\dfrac{1}{2}-3\right)}{4!}\right]𝒙^{4}$
          $\rule{0pt}{}$
          ○ $+\cdots$


● [2:03:41](https://www.youtube.com/watch?v=3VHol7eosLA&t=7421). Simplify the coefficients.
     ◉ First term:
          ○ $1$
     ◉ Second term:
     $\rule{0pt}{}$
          ○ $\left(\dfrac{1}{2}\right)𝒙$
          $\rule{0pt}{}$
     ◉ Third term:
     $\rule{0pt}{}$
          ○ $\left[\dfrac{\left(\dfrac{1}{2}\right)\left(\dfrac{1}{2}-1\right)}{2!}\right]𝒙^{2}$
          $\rule{0pt}{}$
          ○ $=\left[\dfrac{\left(\dfrac{1}{2}\right)\left(-\dfrac{1}{2}\right)}{2!}\right]𝒙^{2}$
          $\rule{0pt}{}$
          ○ $=-\dfrac{𝒙^{2}}{2!\cdot 2^{2}}$
          $\rule{0pt}{}$
     ◉ Fourth term:
     $\rule{0pt}{}$
          ○ $\left[\dfrac{\left(\dfrac{1}{2}\right)\left(\dfrac{1}{2}-1\right)\left(\dfrac{1}{2}-2\right)}{3!}\right]𝒙^{3}$
          $\rule{0pt}{}$
          ○ $=\left[\dfrac{\left(\dfrac{1}{2}\right)\left(-\dfrac{1}{2}\right)\left(-\dfrac{3}{2}\right)}{3!}\right]𝒙^{3}$
          $\rule{0pt}{}$
          ○ $=\dfrac{1\cdot 3𝒙^{3}}{3!\cdot 2^{3}}$
          $\rule{0pt}{}$
     ◉ Fifth term:
     $\rule{0pt}{}$
          ○ $\left[\dfrac{\left(\dfrac{1}{2}\right)\left(\dfrac{1}{2}-1\right)\left(\dfrac{1}{2}-2\right)\left(\dfrac{1}{2}-3\right)}{4!}\right]𝒙^{4}$
          $\rule{0pt}{}$
          ○ $=\left[\dfrac{\left(\dfrac{1}{2}\right)\left(-\dfrac{1}{2}\right)\left(-\dfrac{3}{2}\right)\left(-\dfrac{5}{2}\right)}{4!}\right]𝒙^{4}$
          $\rule{0pt}{}$
          ○ $=-\dfrac{1\cdot 3\cdot 5𝒙^{4}}{4!\cdot 2^{4}}$
          

● [2:05:51](https://www.youtube.com/watch?v=3VHol7eosLA&t=7551). Pattern of the series.
     ◉ After simplifying:
     $\rule{0pt}{}$
          ○ $\sqrt{1+𝒙}$
          $\rule{0pt}{}$
          ○ $=1+\left(\dfrac{1}{2}\right)𝒙-\dfrac{𝒙^{2}}{2!\cdot 2^{2}}+\dfrac{1\cdot 3𝒙^{3}}{3!\cdot 2^{3}}-\dfrac{1\cdot 3\cdot 5𝒙^{4}}{4!\cdot 2^{4}}+\cdots$
     ◉ Pattern:
          ○ after the first two terms, the signs alternate.
          ○ the numerator uses odd products:
               ■ $1$
               ■ $1\cdot 3$
               ■ $1\cdot 3\cdot 5$
               ■ $1\cdot 3\cdot 5\cdot 7$
               ■ $\cdots$
          ○ the denominator uses:
               ■ $n!$
               ■ $2^{n}$

● [2:07:22](https://www.youtube.com/watch?v=3VHol7eosLA&t=7642). Series notation.
     ◉ Separate the first two terms:
          ○ $1$
          $\rule{0pt}{}$
          ○ $\left(\dfrac{1}{2}\right)𝒙$
          $\rule{0pt}{}$
     ◉ Then write the remaining pattern as a sum:
     $\rule{0pt}{}$
          ○ $(1+𝒙)^{1/2}=1+\left(\dfrac{1}{2}\right)𝒙+\displaystyle \sum_{n=2}^{\infty}(-1)^{n+1}\dfrac{\left[1\cdot 3\cdot 5\cdots(2n-3)\right]𝒙^{n}}{n!\cdot 2^{n}}$
     ◉ Important:
          ○ the sum starts at $n=2$.
     ◉ Reason:
          ○ the first two terms:
               ■ $1$
               $\rule{0pt}{}$
               ■ $\left(\dfrac{1}{2}\right)𝒙$
               $\rule{0pt}{}$
          ○ do not fit the same odd-product pattern cleanly.
     ◉ Check:
          ○ when $n=2$:
               ■ $2n-3=1$
               ■ numerator: $1$
               $\rule{0pt}{}$
               ■ sign: $(-1)^{3}=-1$
               $\rule{0pt}{}$
               ■ term: $-\dfrac{𝒙^{2}}{2!\cdot 2^{2}}$
               $\rule{0pt}{}$
          ○ when $n=3$:
               ■ $2n-3=3$
               ■ numerator: $1\cdot 3$
               $\rule{0pt}{}$
               ■ sign: $(-1)^{4}=1$
               $\rule{0pt}{}$
               ■ term: $\dfrac{1\cdot 3𝒙^{3}}{3!\cdot 2^{3}}$


● [2:10:42](https://www.youtube.com/watch?v=3VHol7eosLA&t=7842). Interval of convergence.
     ◉ No new convergence test is needed here.
     ◉ Reason:
          ○ this example uses the known Binomial Series rules.
     ◉ Since:
          ○ $k=\dfrac{1}{2}$
          $\rule{0pt}{}$
          ○ $k>0$
          ○ $k\notin\{0,1,2,3,\dots\}$
     ◉ By the Binomial Series endpoint rules:
          ○ both endpoints are included.
     ◉ Therefore:
          ○ interval of convergence: $[-1,1]$
     ◉ Meaning:
          ○ the series represents $\sqrt{1+𝒙}$ on $[-1,1]$.






３ - Ｃｏｍｍｏｎ　Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ

● [📷image-1](./img/Calculus 2 Lecture 9.8/[2-12-55]-01.png) [📷image-2](./img/Calculus 2 Lecture 9.8/[2-12-55]-02.png) [📷image-3](./img/Calculus 2 Lecture 9.8/[2-12-55]-03.png) 

● [2:12:55](https://www.youtube.com/watch?v=3VHol7eosLA&t=7975). Common Maclaurin series.
     ◉ These are known series that can be reused instead of rebuilding everything from scratch.


３．１ - Ｇｅｏｍｅｔｒｉｃ　Ｓｅｒｉｅｓ　ｆｏｒ　$\dfrac{1}{1-𝒙}$

● [2:13:17](https://www.youtube.com/watch?v=3VHol7eosLA&t=7997). Geometric power series.
     ◉ Function:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{1-𝒙}$
          $\rule{0pt}{}$
     ◉ Series:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{1-𝒙}=1+𝒙+𝒙^{2}+𝒙^{3}+\cdots$
          $\rule{0pt}{}$
     ◉ Series notation:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{1-𝒙}=\displaystyle \sum_{n=0}^{\infty}𝒙^{n}$
          $\rule{0pt}{}$
     ◉ Interval:
          ○ $(-1,1)$



３．２ - Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　$𝓮^{x}$

● [2:14:02](https://www.youtube.com/watch?v=3VHol7eosLA&t=8042). Maclaurin series for $𝓮^{x}$.
     ◉ Function:
          ○ $𝓮^{x}$
     ◉ Series:
          ○ $𝓮^{x}=1+𝒙+\dfrac{𝒙^{2}}{2!}+\dfrac{𝒙^{3}}{3!}+\cdots$
     ◉ Series notation:
     $\rule{0pt}{}$
          ○ $𝓮^{x}=\displaystyle \sum_{n=0}^{\infty}\dfrac{𝒙^{n}}{n!}$
          $\rule{0pt}{}$
     ◉ Interval:
          ○ $(-\infty,\infty)$


３．３ - Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　Ｓｉｎｅ

● [2:14:40](https://www.youtube.com/watch?v=3VHol7eosLA&t=8080). Maclaurin series for Sine.
     ◉ Function:
          ○ $\sin(𝒙)$
     ◉ Series:
          ○ $\sin(𝒙)=𝒙-\dfrac{𝒙^{3}}{3!}+\dfrac{𝒙^{5}}{5!}-\dfrac{𝒙^{7}}{7!}+\cdots$
     ◉ Series notation:
     $\rule{0pt}{}$
          ○ $\sin(𝒙)=\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}𝒙^{2n+1}}{(2n+1)!}$
          $\rule{0pt}{}$
     ◉ Interval:
          ○ $(-\infty,\infty)$



３．４ - Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　Ｃｏｓｉｎｅ

● [2:15:25](https://www.youtube.com/watch?v=3VHol7eosLA&t=8125). Maclaurin series for Cosine.
     ◉ Function:
          ○ $\cos(𝒙)$
     ◉ Series:
          ○ $\cos(𝒙)=1-\dfrac{𝒙^{2}}{2!}+\dfrac{𝒙^{4}}{4!}-\dfrac{𝒙^{6}}{6!}+\cdots$
     ◉ Series notation:
     $\rule{0pt}{}$
          ○ $\cos(𝒙)=\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}𝒙^{2n}}{(2n)!}$
          $\rule{0pt}{}$
     ◉ Interval:
          ○ $(-\infty,\infty)$


３．５ - Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　$\ln(1+𝒙)$

● [2:16:08](https://www.youtube.com/watch?v=3VHol7eosLA&t=8168). Maclaurin series for $\ln(1+𝒙)$.
     ◉ Function:
          ○ $\ln(1+𝒙)$
     ◉ Series:
          ○ $\ln(1+𝒙)=𝒙-\dfrac{𝒙^{2}}{2}+\dfrac{𝒙^{3}}{3}-\dfrac{𝒙^{4}}{4}+\cdots$
     ◉ Series notation:
     $\rule{0pt}{}$
          ○ $\ln(1+𝒙)=\displaystyle \sum_{n=1}^{\infty}\dfrac{(-1)^{n-1}𝒙^{n}}{n}$
          $\rule{0pt}{}$
     ◉ Interval:
          ○ $(-1,1]$


３．６ - Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　$\sin^{-1}(𝒙)$

● [2:17:05](https://www.youtube.com/watch?v=3VHol7eosLA&t=8225). Maclaurin series for $\sin^{-1}(𝒙)$.
     ◉ Function:
          ○ $\sin^{-1}(𝒙)$
     ◉ Series:
          ○ $\sin^{-1}(𝒙)=𝒙+\dfrac{𝒙^{3}}{2\cdot 3}+\dfrac{(1\cdot 3)𝒙^{5}}{2\cdot 4\cdot 5}+\cdots$
     ◉ Series notation:
     $\rule{0pt}{}$
          ○ $\sin^{-1}(𝒙)=\displaystyle \sum_{n=0}^{\infty}\dfrac{(2n)!𝒙^{2n+1}}{(2^{2n})(n!)^{2}(2n+1)}$
          $\rule{0pt}{}$
     ◉ Interval:
          ○ $[-1,1]$



３．７ - Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　$\tan^{-1}(𝒙)$

● [2:18:20](https://www.youtube.com/watch?v=3VHol7eosLA&t=8300). Maclaurin series for $\tan^{-1}(𝒙)$.
     ◉ Function:
          ○ $\tan^{-1}(𝒙)$
     ◉ Series:
          ○ $\tan^{-1}(𝒙)=𝒙-\dfrac{𝒙^{3}}{3}+\dfrac{𝒙^{5}}{5}-\dfrac{𝒙^{7}}{7}+\cdots$
     ◉ Series notation:
     $\rule{0pt}{}$
          ○ $\tan^{-1}(𝒙)=\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}𝒙^{2n+1}}{2n+1}$
          $\rule{0pt}{}$
     ◉ Interval:
          ○ $[-1,1]$



３．８ - Ｂｉｎｏｍｉａｌ　Ｓｅｒｉｅｓ

● [2:19:18](https://www.youtube.com/watch?v=3VHol7eosLA&t=8358). Binomial series.
     ◉ Function:
          ○ $(1+𝒙)^{k}$
     ◉ Series:
     $\rule{0pt}{}$
          ○ $(1+𝒙)^{k}=\displaystyle \sum_{n=0}^{\infty}\binom{k}{n}𝒙^{n}$
          $\rule{0pt}{}$
     ◉ Basic interval:
          ○ $(-1,1)$
     ◉ Special cases:
          ○ if $k\in\{0,1,2,3,\dots\}$,
               ■ interval: $(-\infty,\infty)$
          ○ if $k\notin\{0,1,2,3,\dots\}$,
               ■ endpoint behavior depends on $k$.




４ - Ｍａｎｉｐｕｌａｔｉｎｇ　Ｋｎｏｗｎ　Ｓｅｒｉｅｓ

● [2:20:56](https://www.youtube.com/watch?v=3VHol7eosLA&t=8456). Main strategy.
     ◉ Instead of deriving a Taylor or Maclaurin series from scratch,
          ○ manipulate a known series.
     ◉ Goal:
          ○ make the given function fit one of the known forms.


４．１ - Ｅｘａｍｐｌｅ 6:　Ｔａｙｌｏｒ　Ｓｅｒｉｅｓ　ｆｏｒ　$\dfrac{1}{1+𝒙}$　ｃｅｎｔｅｒｅｄ　ａｔ　$𝑪=2$

● [📷image-1](./img/Calculus 2 Lecture 9.8/[2-21-34]-01.png) [📷image-2](./img/Calculus 2 Lecture 9.8/[2-21-34]-02.png)

● [2:21:34](https://www.youtube.com/watch?v=3VHol7eosLA&t=8494). 🧩 Example 6 — Find Taylor series for $\dfrac{1}{1+𝒙}$ centered at $𝑪=2$.
     ◉ Since the center is:
          ○ $𝑪=2$
     ◉ The series must involve:
          ○ $(𝒙-2)$

● [2:22:54](https://www.youtube.com/watch?v=3VHol7eosLA&t=8574). Force the center into the expression.
     ◉ Rewrite:
          ○ $1+𝒙=1+[(𝒙-2)+2]$
          ○ $1+𝒙=3+(𝒙-2)$
     ◉ Therefore:
          ○ $\dfrac{1}{1+𝒙}=\dfrac{1}{3+(𝒙-2)}$


● [2:25:02](https://www.youtube.com/watch?v=3VHol7eosLA&t=8702). Fit the geometric form.
     ◉ Goal:
          ○ make it look like $\dfrac{1}{1-𝒖}$
     ◉ Factor out $3$:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{3+(𝒙-2)}=\left(\dfrac{1}{3}\right)\cdot \dfrac{1}{1+\dfrac{(𝒙-2)}{3}}$
          $\rule{0pt}{}$
     ◉ Rewrite the plus sign as a minus:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{1+\dfrac{(𝒙-2)}{3}}=\dfrac{1}{1-\left(-\dfrac{(𝒙-2)}{3}\right)}$
          $\rule{0pt}{}$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{1+𝒙}=\left(\dfrac{1}{3}\right)\cdot \dfrac{1}{1-\left(-\dfrac{(𝒙-2)}{3}\right)}$


● [2:28:12](https://www.youtube.com/watch?v=3VHol7eosLA&t=8892). Substitute into the geometric series.
     ◉ Known series:
          ○ $\dfrac{1}{1-𝒖}=1+𝒖+𝒖^{2}+𝒖^{3}+\cdots$
     ◉ Here:
          ○ $𝒖=-\dfrac{(𝒙-2)}{3}$
     ◉ Substitute:
          ○ $\dfrac{1}{1+𝒙}=\left(\dfrac{1}{3}\right)\left[1+\left(-\dfrac{(𝒙-2)}{3}\right)+\left(-\dfrac{(𝒙-2)}{3}\right)^{2}+\left(-\dfrac{(𝒙-2)}{3}\right)^{3}+\cdots\right]$

● [2:31:35](https://www.youtube.com/watch?v=3VHol7eosLA&t=9095). Series notation.
     ◉ Start from:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{1+𝒙}=\left(\dfrac{1}{3}\right)\displaystyle \sum_{n=0}^{\infty}\left[-\dfrac{(𝒙-2)}{3}\right]^{n}$
          $\rule{0pt}{}$
     ◉ Simplify:
     $\rule{0pt}{}$
          ○ $\left[-\dfrac{(𝒙-2)}{3}\right]^{n}=\dfrac{(-1)^{n}(𝒙-2)^{n}}{3^{n}}$
          $\rule{0pt}{}$
     ◉ Since there is also a factor $\dfrac{1}{3}$ outside:
     $\rule{0pt}{}$
          ○ $\left(\dfrac{1}{3}\right)\cdot \dfrac{1}{3^{n}}=\dfrac{1}{3^{n+1}}$
          $\rule{0pt}{}$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{1+𝒙}=\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}(𝒙-2)^{n}}{3^{n+1}}$


● [2:34:18](https://www.youtube.com/watch?v=3VHol7eosLA&t=9258). Interval of convergence.
     ◉ No new convergence test is needed here.
     ◉ Reason:
          ○ this is based on the geometric series.
     ◉ The geometric series requires:
          ○ $|𝒖|<1$
     ◉ Here:
     $\rule{0pt}{}$
          ○ $𝒖=-\dfrac{(𝒙-2)}{3}$
          $\rule{0pt}{}$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\left|-\dfrac{(𝒙-2)}{3}\right|<1$
          $\rule{0pt}{}$
     ◉ Since absolute value removes the negative sign:
     $\rule{0pt}{}$
          ○ $\dfrac{|𝒙-2|}{3}<1$
          $\rule{0pt}{}$
     ◉ Multiply by $3$:
     $\rule{0pt}{}$
          ○ $|𝒙-2|<3$
          $\rule{0pt}{}$
     ◉ Radius of convergence.
          ○ Compare with the standard form:
               ■ $|𝒙-𝑪|<𝑹$
          ○ Here:
               ■ $|𝒙-2|<3$
          ○ Therefore:
               ■ center $𝑪=2$
               ■ radius $𝑹=3$
     ◉ Solve the interval.
          ○ From:
               ■ $|𝒙-2|<3$
          ○ We get:
               ■ $-3<𝒙-2<3$
          ○ Add $2$:
               ■ $-1<𝒙<5$
     ◉ Interval of convergence:
          ○ $(-1,5)$
     ◉ Meaning:
          ○ the Taylor series represents $\dfrac{1}{1+𝒙}$ centered at $𝑪=2$ only for $-1<𝒙<5$.

          
● N̲O̲T̲E̲ — Meaning of Leonard's “X” in the geometric series.
     ◉ Leonard writes:
          ○ $-1<$ “X” $<1$
     ◉ But here:
          ○ “X” is not the original variable $𝒙$.
     ◉ In this example, “X” means the quantity substituted into the geometric series.
     ◉ Since:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{1-𝒖}=\displaystyle \sum_{n=0}^{\infty}𝒖^{n}$
          $\rule{0pt}{}$
     ◉ and:
          ○ $𝒖=-\dfrac{(𝒙-2)}{3}$
          $\rule{0pt}{}$
     ◉ Then Leonard's “X” is:
     $\rule{0pt}{}$
          ○ “X” $=-\dfrac{(𝒙-2)}{3}$
          $\rule{0pt}{}$
     ◉ Therefore, the convergence condition:
     $\rule{0pt}{}$
          ○ $-1<$ “X” $<1$
          $\rule{0pt}{}$
     ◉ becomes:
     $\rule{0pt}{}$
          ○ $-1<-\dfrac{(𝒙-2)}{3}<1$
          $\rule{0pt}{}$
     ◉ Solve:
          ○ $-3<-(𝒙-2)<3$
          ○ $3>𝒙-2>-3$
          ○ $-3<𝒙-2<3$
          ○ $-1<𝒙<5$
     ◉ Meaning:
          ○ the geometric-series variable is the substituted expression.
          ○ here, that expression is $-\dfrac{(𝒙-2)}{3}$.
          ○ the original variable $𝒙$ must satisfy $-1<𝒙<5$.
     ◉ Therefore:
          ○ center $𝑪=2$
          ○ radius $𝑹=3$
          ○ interval of convergence: $(-1,5)$



４．２ - Ｅｘａｍｐｌｅ 7:　Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　$𝒙^{2}\sin(2𝒙)$

● [📷image](./img/Calculus 2 Lecture 9.8/[2-38-20]-01.png)


● [2:38:20](https://www.youtube.com/watch?v=3VHol7eosLA&t=9500). 🧩 Example 7 — Find Maclaurin series for $𝒙^{2}\sin(2𝒙)$.
     ◉ Goal:
          ○ find a Maclaurin series representation for $𝒙^{2}\sin(2𝒙)$.
     ◉ Use known series:
          ○ $\sin(𝒙)$
     ◉ Reason:
          ○ the given function contains $\sin(2𝒙)$.

● [2:38:49](https://www.youtube.com/watch?v=3VHol7eosLA&t=9529). Start from the known Sine series.
     ◉ Known:
          ○ $\sin(𝒙)=𝒙-\dfrac{𝒙^{3}}{3!}+\dfrac{𝒙^{5}}{5!}-\cdots$
     ◉ Series notation:
     $\rule{0pt}{}$
          ○ $\sin(𝒙)=\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}𝒙^{2n+1}}{(2n+1)!}$
          $\rule{0pt}{}$
     ◉ Interval:
          ○ $(-\infty,\infty)$


● [2:39:07](https://www.youtube.com/watch?v=3VHol7eosLA&t=9547). Substitute $2𝒙$ into the Sine series.
     ◉ Since:
          ○ $\sin(𝒙)=𝒙-\dfrac{𝒙^{3}}{3!}+\dfrac{𝒙^{5}}{5!}-\cdots$
          $\rule{0pt}{}$
     ◉ Replace $𝒙$ by $2𝒙$:
     $\rule{0pt}{}$
          ○ $\sin(2𝒙)=2𝒙-\dfrac{(2𝒙)^{3}}{3!}+\dfrac{(2𝒙)^{5}}{5!}-\cdots$
          $\rule{0pt}{}$
     ◉ Simplify powers:
     $\rule{0pt}{}$
          ○ $\sin(2𝒙)=2𝒙-\dfrac{2^{3}𝒙^{3}}{3!}+\dfrac{2^{5}𝒙^{5}}{5!}-\cdots$
          $\rule{0pt}{}$
     ◉ Series notation:
     $\rule{0pt}{}$
          ○ $\sin(2𝒙)=\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}2^{2n+1}𝒙^{2n+1}}{(2n+1)!}$


● [2:42:49](https://www.youtube.com/watch?v=3VHol7eosLA&t=9769). Multiply by $𝒙^{2}$.
     ◉ We need:
     $\rule{0pt}{}$
          ○ $𝒙^{2}\sin(2𝒙)$
          $\rule{0pt}{}$
     ◉ So multiply the whole series by $𝒙^{2}$:
     $\rule{0pt}{}$
          ○ $𝒙^{2}\sin(2𝒙)=𝒙^{2}\cdot \displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}2^{2n+1}𝒙^{2n+1}}{(2n+1)!}$
          $\rule{0pt}{}$
     ◉ This raises every power of $𝒙$ by $2$:
     $\rule{0pt}{}$
          ○ $𝒙^{2}\cdot 𝒙^{2n+1}=𝒙^{2n+3}$


● [2:43:14](https://www.youtube.com/watch?v=3VHol7eosLA&t=9794). Final series notation.
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $𝒙^{2}\sin(2𝒙)=\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}2^{2n+1}𝒙^{2n+3}}{(2n+1)!}$
          $\rule{0pt}{}$
     ◉ Expanded:
          ○ $𝒙^{2}\sin(2𝒙)=2𝒙^{3}-\dfrac{2^{3}𝒙^{5}}{3!}+\dfrac{2^{5}𝒙^{7}}{5!}-\cdots$


● [2:44:31](https://www.youtube.com/watch?v=3VHol7eosLA&t=9871). Interval of convergence.
     ◉ No new convergence test is needed here.
     ◉ Reason:
          ○ the original Sine series converges for all real $𝒙$.
     ◉ Substituting:
          ○ $𝒙\to 2𝒙$
     ◉ and multiplying by:
          ○ $𝒙^{2}$
     ◉ do not restrict the interval.
     ◉ Therefore:
          ○ interval of convergence: $(-\infty,\infty)$
     ◉ Meaning:
          ○ the Maclaurin series represents $𝒙^{2}\sin(2𝒙)$ for every real $𝒙$.

● [2:45:03](https://www.youtube.com/watch?v=3VHol7eosLA&t=9903). Meaning of “the series represents the function”.
     ◉ Saying that the series represents the function means:
          ○ both expressions give the same value for every $𝒙$ in the interval of convergence.
     ◉ In this example:
     $\rule{0pt}{}$
          ○ $𝒙^{2}\sin(2𝒙)=\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}2^{2n+1}𝒙^{2n+3}}{(2n+1)!}$
          $\rule{0pt}{}$
     ◉ Since the interval is:
          ○ $(-\infty,\infty)$
     ◉ Then:
          ○ we can substitute any real value of $𝒙$ into the original function.
          ○ we can also substitute that same value of $𝒙$ into the series.
          ○ both give the same result.
     ◉ Important:
          ○ using infinitely many terms gives the exact value.
          ○ using only a few terms gives an approximation.


          
４．３ - Ｅｘａｍｐｌｅ 8:　Ｍａｃｌａｕｒｉｎ　Ｓｅｒｉｅｓ　ｆｏｒ　$\sinh(𝒙)$

● [📷image](./img/Calculus 2 Lecture 9.8/[2-46-25]-01.png)


● [2:46:25](https://www.youtube.com/watch?v=3VHol7eosLA&t=9985). 🧩 Example 8 — Find Maclaurin series for $\sinh(𝒙)$.
     ◉ Definition:
          ○ $\sinh(𝒙)=\dfrac{𝓮^{x}-𝓮^{-x}}{2}$
     ◉ Rewrite:
          ○ $\sinh(𝒙)=\left(\dfrac{1}{2}\right)𝓮^{x}-\left(\dfrac{1}{2}\right)𝓮^{-x}$
     ◉ Use:
          ○ the known Maclaurin series for $𝓮^{x}$.


● [2:47:16](https://www.youtube.com/watch?v=3VHol7eosLA&t=10036). Use the series for $𝓮^{x}$.
     ◉ Known:
          ○ $𝓮^{x}=1+𝒙+\dfrac{𝒙^{2}}{2!}+\dfrac{𝒙^{3}}{3!}+\dfrac{𝒙^{4}}{4!}+\dfrac{𝒙^{5}}{5!}+\cdots$
     ◉ Therefore:
          ○ $\left(\dfrac{1}{2}\right)𝓮^{x}=\left(\dfrac{1}{2}\right)\left[1+𝒙+\dfrac{𝒙^{2}}{2!}+\dfrac{𝒙^{3}}{3!}+\dfrac{𝒙^{4}}{4!}+\dfrac{𝒙^{5}}{5!}+\cdots\right]$


● [2:48:18](https://www.youtube.com/watch?v=3VHol7eosLA&t=10098). Build the series for $𝓮^{-x}$.
     ◉ Substitute:
          ○ $𝒙\to -𝒙$
     ◉ Then:
          ○ $𝓮^{-x}=1-𝒙+\dfrac{𝒙^{2}}{2!}-\dfrac{𝒙^{3}}{3!}+\dfrac{𝒙^{4}}{4!}-\dfrac{𝒙^{5}}{5!}+\cdots$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\left(\dfrac{1}{2}\right)𝓮^{-x}=\left(\dfrac{1}{2}\right)\left[1-𝒙+\dfrac{𝒙^{2}}{2!}-\dfrac{𝒙^{3}}{3!}+\dfrac{𝒙^{4}}{4!}-\dfrac{𝒙^{5}}{5!}+\cdots\right]$


● [2:50:02](https://www.youtube.com/watch?v=3VHol7eosLA&t=10202). Subtract the two series.
     ◉ Start from:
     $\rule{0pt}{}$
          ○ $\sinh(𝒙)=\left(\dfrac{1}{2}\right)𝓮^{x}-\left(\dfrac{1}{2}\right)𝓮^{-x}$
          $\rule{0pt}{}$
     ◉ Substitute the series:
          ○ $\sinh(𝒙)$
          $\rule{0pt}{}$
          ○ $=\left(\dfrac{1}{2}\right)\left[1+𝒙+\dfrac{𝒙^{2}}{2!}+\dfrac{𝒙^{3}}{3!}+\dfrac{𝒙^{4}}{4!}+\dfrac{𝒙^{5}}{5!}+\cdots\right]$
          $\rule{0pt}{}$
          ○ $-\left(\dfrac{1}{2}\right)\left[1-𝒙+\dfrac{𝒙^{2}}{2!}-\dfrac{𝒙^{3}}{3!}+\dfrac{𝒙^{4}}{4!}-\dfrac{𝒙^{5}}{5!}+\cdots\right]$
          $\rule{0pt}{}$
     ◉ Cancellation:
          ○ constant terms cancel:
               ■ $1-1=0$
          ○ even-power terms cancel:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒙^{2}}{2!}-\dfrac{𝒙^{2}}{2!}=0$
               $\rule{0pt}{}$
               ■ $\dfrac{𝒙^{4}}{4!}-\dfrac{𝒙^{4}}{4!}=0$
               $\rule{0pt}{}$
          ○ odd-power terms add:
               ■ $𝒙-(-𝒙)=2𝒙$
               $\rule{0pt}{}$
               ■ $\dfrac{𝒙^{3}}{3!}-\left(-\dfrac{𝒙^{3}}{3!}\right)=\dfrac{2𝒙^{3}}{3!}$
               $\rule{0pt}{}$
               ■ $\dfrac{𝒙^{5}}{5!}-\left(-\dfrac{𝒙^{5}}{5!}\right)=\dfrac{2𝒙^{5}}{5!}$


● [2:51:08](https://www.youtube.com/watch?v=3VHol7eosLA&t=10268). Simplify after multiplying by $\dfrac{1}{2}$.
     ◉ After subtraction:
     $\rule{0pt}{}$
          ○ $\sinh(𝒙)=\left(\dfrac{1}{2}\right)\left[2𝒙+\dfrac{2𝒙^{3}}{3!}+\dfrac{2𝒙^{5}}{5!}+\cdots\right]$
          $\rule{0pt}{}$
     ◉ Distribute:
          ○ $\sinh(𝒙)=𝒙+\dfrac{𝒙^{3}}{3!}+\dfrac{𝒙^{5}}{5!}+\cdots$

● [2:52:01](https://www.youtube.com/watch?v=3VHol7eosLA&t=10321). Final Maclaurin series.
     ◉ Result:
          ○ $\sinh(𝒙)=𝒙+\dfrac{𝒙^{3}}{3!}+\dfrac{𝒙^{5}}{5!}+\dfrac{𝒙^{7}}{7!}+\cdots$
     ◉ Series notation:
     $\rule{0pt}{}$
          ○ $\sinh(𝒙)=\displaystyle \sum_{n=0}^{\infty}\dfrac{𝒙^{2n+1}}{(2n+1)!}$
          $\rule{0pt}{}$
     ◉ Meaning:
          ○ only odd powers remain.
          ○ all signs are positive.

● [2:53:18](https://www.youtube.com/watch?v=3VHol7eosLA&t=10398). Interval of convergence.
     ◉ No new convergence test is needed here.
     ◉ Reason:
          ○ this series is built from the Maclaurin series for $𝓮^{x}$ and $𝓮^{-x}$.
     ◉ Since:
          ○ $𝓮^{x}$ converges for all real $𝒙$.
          ○ $𝓮^{-x}$ also converges for all real $𝒙$.
     ◉ Therefore:
          ○ interval of convergence: $(-\infty,\infty)$
     ◉ Meaning:
          ○ the series represents $\sinh(𝒙)$ for every real $𝒙$.



４．４ - Ｅｘａｍｐｌｅ 9:　Ｉｎｔｅｇｒａｔｉｎｇ　ｔｈｅ　Ｓｅｒｉｅｓ　ｆｏｒ　$𝓮^{-x^{2}}$

● [📷image](./img/Calculus 2 Lecture 9.8/[2-55-00]-01.png)


● [2:55:00](https://www.youtube.com/watch?v=3VHol7eosLA&t=10500). 🧩 Example 9 — Integrate by series: $𝓮^{-x^{2}}$.
     ◉ Goal:
          ○ find a series representation for:
          $\rule{0pt}{}$
               ■ $\displaystyle \int 𝓮^{-x^{2}}\,d𝒙$
               $\rule{0pt}{}$
     ◉ Important:
     $\rule{0pt}{}$
          ○ $\displaystyle \int 𝓮^{-x^{2}}\,d𝒙$ cannot be integrated directly using elementary functions.
          $\rule{0pt}{}$
          ○ therefore, we use a power series.

● [2:55:44](https://www.youtube.com/watch?v=3VHol7eosLA&t=10544). Start from the Maclaurin series for $𝓮^{x}$.
     ◉ Known:
     $\rule{0pt}{}$
          ○ $𝓮^{x}=1+𝒙+\dfrac{𝒙^{2}}{2!}+\dfrac{𝒙^{3}}{3!}+\cdots$
          $\rule{0pt}{}$
     ◉ Series notation:
     $\rule{0pt}{}$
          ○ $𝓮^{x}=\displaystyle \sum_{n=0}^{\infty}\dfrac{𝒙^{n}}{n!}$
          $\rule{0pt}{}$
     ◉ Interval:
          ○ $(-\infty,\infty)$


● [2:56:00](https://www.youtube.com/watch?v=3VHol7eosLA&t=10560). Substitute $-𝒙^{2}$ into the series.
     ◉ Since:
     $\rule{0pt}{}$
          ○ $𝓮^{x}=\displaystyle \sum_{n=0}^{\infty}\dfrac{𝒙^{n}}{n!}$
          $\rule{0pt}{}$
     ◉ Substitute:
          ○ $𝒙\to -𝒙^{2}$
     ◉ Then:
     $\rule{0pt}{}$
          ○ $𝓮^{-x^{2}}=\displaystyle \sum_{n=0}^{\infty}\dfrac{(-𝒙^{2})^{n}}{n!}$
          $\rule{0pt}{}$
     ◉ Simplify:
     $\rule{0pt}{}$
          ○ $(-𝒙^{2})^{n}=(-1)^{n}𝒙^{2n}$
          $\rule{0pt}{}$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $𝓮^{-x^{2}}=\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}𝒙^{2n}}{n!}$


● [2:57:18](https://www.youtube.com/watch?v=3VHol7eosLA&t=10638). Expanded form of $𝓮^{-x^{2}}$.
     ◉ The series becomes:
          ○ $𝓮^{-x^{2}}=1-𝒙^{2}+\dfrac{𝒙^{4}}{2!}-\dfrac{𝒙^{6}}{3!}+\dfrac{𝒙^{8}}{4!}-\cdots$
     ◉ Meaning:
          ○ the powers of $𝒙$ are even.
          ○ the signs alternate.
          ○ the denominator keeps the factorial pattern $n!$.


● [2:58:35](https://www.youtube.com/watch?v=3VHol7eosLA&t=10715). Integrate term by term.
     ◉ Since:
     $\rule{0pt}{}$
          ○ $𝓮^{-x^{2}}=\displaystyle \sum_{n=0}^{\infty}\dfrac{(-1)^{n}𝒙^{2n}}{n!}$
          $\rule{0pt}{}$
     ◉ Integrate both sides:
     $\rule{0pt}{}$
          ○ $\displaystyle \int 𝓮^{-x^{2}}\,d𝒙=\int \sum_{n=0}^{\infty}\dfrac{(-1)^{n}𝒙^{2n}}{n!}\,d𝒙$
          $\rule{0pt}{}$
     ◉ Move the integral into the series:
     $\rule{0pt}{}$
          ○ $\displaystyle \int 𝓮^{-x^{2}}\,d𝒙=\sum_{n=0}^{\infty}\int \left[\dfrac{(-1)^{n}𝒙^{2n}}{n!}\right]d𝒙$


● [2:59:18](https://www.youtube.com/watch?v=3VHol7eosLA&t=10758). Result after integration.
     ◉ Constants stay outside the integral:
     $\rule{0pt}{}$
          ○ $\dfrac{(-1)^{n}}{n!}$
          $\rule{0pt}{}$
     ◉ Integrate the power:
     $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒙^{2n}\,d𝒙=\dfrac{𝒙^{2n+1}}{2n+1}$
          $\rule{0pt}{}$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\displaystyle \int 𝓮^{-x^{2}}\,d𝒙=\sum_{n=0}^{\infty}\dfrac{(-1)^{n}𝒙^{2n+1}}{(2n+1)n!}+𝑪$


● [2:59:58](https://www.youtube.com/watch?v=3VHol7eosLA&t=10798). Expanded integrated series.
     ◉ The integral becomes:
     $\rule{0pt}{}$
          ○ $\displaystyle \int 𝓮^{-x^{2}}\,d𝒙=𝒙-\dfrac{𝒙^{3}}{3}+\dfrac{𝒙^{5}}{5\cdot 2!}-\dfrac{𝒙^{7}}{7\cdot 3!}+\dfrac{𝒙^{9}}{9\cdot 4!}-\cdots+𝑪$
          $\rule{0pt}{}$
     ◉ Meaning:
          ○ each term is obtained by adding $1$ to the power.
          ○ then dividing by the new power.

● [3:00:46](https://www.youtube.com/watch?v=3VHol7eosLA&t=10846). Interval of convergence.
     ◉ No new convergence test is needed here.
     ◉ Reason:
          ○ the original series for $𝓮^{x}$ converges for all real $𝒙$.
     ◉ Substituting:
          ○ $𝒙\to -𝒙^{2}$
     ◉ and integrating term by term:
          ○ do not restrict the interval of convergence.
     ◉ Therefore:
          ○ interval of convergence: $(-\infty,\infty)$
     ◉ Meaning:
          ○ the series representation for $\displaystyle \int 𝓮^{-x^{2}}\,d𝒙$ is valid for every real $𝒙$.





Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Taylor and Maclaurin Series
     ◉ [openstax 🌐](https://openstax.org/books/calculus-volume-2/pages/6-3-taylor-and-maclaurin-series)

● Working with Taylor Series
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/6-4-working-with-taylor-series)