-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ １０．６： Ｎｕｍｅｒｉｃａｌ  Ｉｎｔｅｇｒａｔｉｏｎ  Ｗｉｔｈ  Ｔｒａｐｅｚｏｉｄａｌ  ａｎｄ  Ｓｉｍｐｓｏｎ＇ｓ  Ｒｕｌｅ**-----------------------------------






１ - Ｎｕｍｅｒｉｃａｌ Ｉｎｔｅｇｒａｔｉｏｎ


● [0:00](https://www.youtube.com/watch?v=RTX-ik_8i-k&t=0). Introduction to Numerical Integration.
     ◉ Goal:
          ○ approximate definite integrals such as $\displaystyle \int_{𝒂}^{𝒃}𝒇(𝒙)\,d𝒙$ when no standard antiderivative formula is known yet
     ◉ Main idea:
          ○ use finite numerical processes to estimate the value of a definite integral
     ◉ Therefore:
          ○ the two main methods introduced here are the Trapezoidal Rule and Simpson’s Rule

● [1:27](https://www.youtube.com/watch?v=RTX-ik_8i-k&t=87). The Trapezoidal Rule. [📷image](../img/Calculus 2 Lecture 10.6/[1-27]-01.png)
     ◉ Goal:
          ○ approximate the area under a curve by dividing the interval into trapezoids
     ◉ Formula:
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{𝒂}^{𝒃}𝒇(𝒙)\,d𝒙\approx \dfrac{\Delta 𝒙}{2}\Big[𝒇(𝒙_{0})+2𝒇(𝒙_{1})+2𝒇(𝒙_{2})+\cdots+2𝒇(𝒙_{n-1})+𝒇(𝒙_{n})\Big]$
          $\rule{0pt}{}$
     ◉ Important:
          ○ the first term $𝒇(𝒙_{0})$ is not doubled
          ○ the last term $𝒇(𝒙_{n})$ is not doubled
          ○ every interior term is multiplied by $2$

● [2:52](https://www.youtube.com/watch?v=RTX-ik_8i-k&t=172). Components of the numerical formula.
     ◉ Subinterval width:
          $\rule{0pt}{}$
          ○ $\Delta 𝒙=\dfrac{𝒃-𝒂}{n}$
          $\rule{0pt}{}$
     ◉ Reason:
          ○ $n$ must be finite, since this is a numerical approximation
          ○ i̲f̲ $n\to\infty$
               ■ t̲h̲e̲n̲ the process approaches the exact integral rather than a finite approximation
     ◉ Grid points:
          $\rule{0pt}{}$
          ○ $𝒙_{i}=𝒂+i\Delta 𝒙$
          $\rule{0pt}{}$
     ◉ Meaning:
          ○ start at the lower bound $𝒂$
          ○ then keep adding $\Delta 𝒙$ to generate the sequence $𝒙_{0},𝒙_{1},𝒙_{2},\dots$

          
● [4:18](https://www.youtube.com/watch?v=RTX-ik_8i-k&t=258). 🧩 Example — Approximate: $\displaystyle \int_{1}^{2}\dfrac{1}{𝒙}\,d𝒙$ with $n=10$. [📷image](../img/Calculus 2 Lecture 10.6/[4-18]-01.png)
     ◉ Goal:
          ○ use the Trapezoidal Rule to estimate the value of the integral
     ◉ Compute the width:
          $\rule{0pt}{}$
          ○ $\Delta 𝒙=\dfrac{2-1}{10}=\dfrac{1}{10}=0.1$
          $\rule{0pt}{}$
     ◉ Generate the grid points:
          ○ $𝒙_{0}=1.0$
          ○ $𝒙_{1}=1.1$
          ○ $𝒙_{2}=1.2$
          ○ $𝒙_{3}=1.3$
          ○ $\dots$
          ○ $𝒙_{9}=1.9$
          ○ $𝒙_{10}=2.0$
     ◉ Set up the trapezoidal sum:
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{1}^{2}\dfrac{1}{𝒙}\,d𝒙\approx \dfrac{0.1}{2}\Big[𝒇(1)+2𝒇(1.1)+2𝒇(1.2)+2𝒇(1.3)+\dots+2𝒇(1.9)+𝒇(2)\Big]$
          $\rule{0pt}{}$
     ◉ Use the function:
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)=\dfrac{1}{𝒙}$
          $\rule{0pt}{}$
     ◉ Numerical approximation:
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{1}^{2}\dfrac{1}{𝒙}\,d𝒙\approx \dfrac{0.1}{2}\Big[\dfrac{1}{1}+2\cdot \left(\dfrac{1}{1.1}\right)+2\cdot \left(\dfrac{1}{1.2}\right)+2\cdot \left(\dfrac{1}{1.3}\right)+\dots+2\cdot \left(\dfrac{1}{1.9}\right)+\dfrac{1}{2}\Big]$
          $\rule{0pt}{}$
     ◉ Final result:
          ○ numerical approximation $\approx 0.69377$
     ◉ Exact value check:
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{1}^{2}\dfrac{1}{𝒙}\,d𝒙=\Big[\ln(𝒙)\Big]_{1}^{2}=\ln(2)-\ln(1)=\ln(2)\approx 0.69314$
          $\rule{0pt}{}$
     ◉ Final interpretation:
          ○ the trapezoidal approximation is very close to the exact value
          ○ it is correct to the thousandths place
          ○ the error is about $0.00063$
     ◉ Accuracy idea:
          ○ i̲f̲ $n$ increases
          ○ t̲h̲e̲n̲ the error decreases because the trapezoids become narrower





２－Ｓｉｍｐｓｏｎ’ｓ Ｒｕｌｅ
          
● [15:19](https://www.youtube.com/watch?v=RTX-ik_8i-k&t=919). Simpson’s Rule.
     ◉ Goal:
          ○ approximate definite integrals with a method that is usually more accurate than the Trapezoidal Rule
     ◉ Main idea:
          ○ use a coefficient pattern based on parabolic fitting rather than trapezoids
     ◉ Formula:
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{𝒂}^{𝒃}𝒇(𝒙)\,d𝒙\approx \dfrac{\Delta 𝒙}{3}\Big[𝒇(𝒙_{0})+4𝒇(𝒙_{1})+2𝒇(𝒙_{2})+4𝒇(𝒙_{3})+\cdots+4𝒇(𝒙_{n-1})+𝒇(𝒙_{n})\Big]$
          $\rule{0pt}{}$
     ◉ Important:
          ○ the endpoints are not multiplied by anything
          ○ the interior coefficients alternate:
               ■ $4,2,4,2,4,2,\dots$
          ○ the lead factor is $\Delta 𝒙/3$, not $\Delta 𝒙/2$

● [16:18](https://www.youtube.com/watch?v=RTX-ik_8i-k&t=978). **Restriction on $n$ for Simpson’s Rule.**
     ◉ Condition:
          ○ i̲f̲ $n$ is even
               ■ t̲h̲e̲n̲ Simpson’s Rule can be used
     ◉ Warning:
          ○ Simpson’s Rule does not apply when $n$ is odd


● [17:19](https://www.youtube.com/watch?v=RTX-ik_8i-k&t=1039). 🧩 Example — Approximate: $\displaystyle \int_{0}^{2}\dfrac{1}{\sqrt{𝒙+1}}\,d𝒙$ with $n=6$. [📷image-1](../img/Calculus 2 Lecture 10.6/[17-19]-01.png) [📷image-2](../img/Calculus 2 Lecture 10.6/[17-19]-02.png)
     ◉ Reason:
          ○ $n=6$ is even, so Simpson’s Rule is allowed
     ◉ Goal:
          ○ approximate the integral using Simpson’s Rule
     ◉ Procedure:
          ○ Compute the width:
               $\rule{0pt}{}$
               ■ $\Delta 𝒙=\dfrac{2-0}{6}=\dfrac{1}{3}$
               $\rule{0pt}{}$
          ○ Important:
               ■ keep $\Delta 𝒙$ as the fraction $\dfrac{1}{3}$ instead of rounding
               ■ this helps avoid unnecessary rounding error
          ○ Generate the grid points:
               ■ $𝒙_{0}=0$
               $\rule{0pt}{}$
               ■ $𝒙_{1}=\dfrac{1}{3}$
               $\rule{0pt}{}$
               ■ $𝒙_{2}=\dfrac{2}{3}$
               $\rule{0pt}{}$
               ■ $𝒙_{3}=1$
               $\rule{0pt}{}$
               ■ $𝒙_{4}=\dfrac{4}{3}$
               $\rule{0pt}{}$
               ■ $𝒙_{5}=\dfrac{5}{3}$
               $\rule{0pt}{}$
               ■ $𝒙_{6}=2$
          ○ Set up the Simpson sum:
               $\rule{0pt}{}$
               ■ $\displaystyle \int_{0}^{2}\dfrac{1}{\sqrt{𝒙+1}}\,d𝒙\approx \dfrac{(1/3)}{3}\Big[𝒇(0)+4𝒇\left(\dfrac{1}{3}\right)+2𝒇\left(\dfrac{2}{3}\right)+4𝒇(1)+2𝒇\left(\dfrac{4}{3}\right)+4𝒇\left(\dfrac{5}{3}\right)+𝒇(2)\Big]$
               $\rule{0pt}{}$
          ○ Use the function:
               $\rule{0pt}{}$
               ■ $𝒇(𝒙)=\dfrac{1}{\sqrt{𝒙+1}}$
               $\rule{0pt}{}$
          ○ Numerical approximation:
               ■ $\approx 1.46421$
     ◉ Exact value check:
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{0}^{2}\dfrac{1}{\sqrt{𝒙+1}}\,d𝒙=\int_{0}^{2}(𝒙+1)^{-1/2}\,d𝒙$
          $\rule{0pt}{}$
          $\rule{0pt}{}$
          ○ $=2\sqrt{𝒙+1}\Big|_{0}^{2}$
          $\rule{0pt}{}$
          $\rule{0pt}{}$
          ○ $=2\sqrt{3}-2$
          $\rule{0pt}{}$
          ○ $\approx 1.46410$
     ◉ Final interpretation:
          ○ the Simpson approximation is extremely close to the exact value
          ○ the error is only about $0.0001$




Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Numerical Integration
     ◉ [Openstax🌐](https://openstax.org/books/calculus-volume-2/pages/3-6-numerical-integration)