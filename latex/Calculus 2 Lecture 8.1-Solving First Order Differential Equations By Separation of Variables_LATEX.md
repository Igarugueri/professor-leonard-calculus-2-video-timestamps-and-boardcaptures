-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ８．１  -  Ｓｏｌｖｉｎｇ Ｆｉｒｓｔ Ｏｒｄｅｒ Ｄｉｆｆｅｒｅｎｔｉａｌ Ξｑｕａｔｉｏｎｓ Ｂｙ Ｓｅｐａｒａｔｉｏｎ ｏｆ Ｖａｒｉａｂｌｅｓ**---------------------------------







Ｉｎｔｒｏｄｕｃｔｉｏｎ　Ｔｏ　Ｆｉｒｓｔ－Ｏｒｄｅｒ　Ｄｉｆｆｅｒｅｎｔｉａｌ　Ｅｑｕａｔｉｏｎｓ

● [📷image](../img/Calculus 2 Lecture 8.1/[0-00]-01.png)

● [0:00](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=0). Introduction to first-order differential equations.
     ◉ Differential equations have broad applications, especially in engineering and applied sciences.
     ◉ Focus of the lecture:
          ○ separable differential equations
               ■ the most basic class of first-order differential equations

● [1:24](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=84). Definition of a differential equation and the concept of order.
     ◉ A differential equation is an equation involving a derivative and an unknown function.
     ◉ Definition of order:
          ○ the order of a differential equation is the highest derivative that appears in it.
     ◉ First-order differential equations.
          ○ A first-order differential equation contains only a first derivative.

● [3:05](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=185). Basic first-order equations of the form $\dfrac{𝒅𝒚}{𝒅𝒙}=𝒇(𝒙)$.
     ◉ [3:58](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=238). Basic idea:
          ○ A first-order differential equation contains the first derivative of an unknown function.
          ○ Solving it means finding the function whose derivative satisfies the equation.
               ■ In simple cases such as
                    $\rule{0pt}{}$
                    ▣ $\dfrac{𝒅𝒚}{𝒅𝒙}=𝒇(𝒙)$,
                    $\rule{0pt}{}$
                    ▣ we can recover $𝒚$ by integrating:
                         $\rule{0pt}{}$
                         ▢ $𝒚=\displaystyle \int 𝒇(𝒙)\,𝒅𝒙$
                         $\rule{0pt}{}$
     ◉ [4:23](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=263). Limitation of this basic method.
          ○ It works only when the right-hand side depends entirely on $𝒙$: $𝒇(𝒙)$.
          $\rule{0pt}{}$
          ○ It does not immediately solve equations of the form $\dfrac{𝒅𝒚}{𝒅𝒙}=𝒇(𝒙,𝒚)$.

● [5:23](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=323). First-order equations with mixed variables.
     ◉ General form:
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=𝒇(𝒙,𝒚)$
          $\rule{0pt}{}$
     ◉ Meaning of a solution:
          ○ A solution is a function $𝒚=𝒚(𝒙)$, defined on some interval, such that
               ■ when we differentiate $𝒚(𝒙)$, its derivative matches the right-hand side of the differential equation.
          ○ In other words,
               ■ $𝒚=𝒚(𝒙)$ is a solution if $\dfrac{𝒅𝒚}{𝒅𝒙}=𝒇(𝒙,𝒚(𝒙))$.
     ◉ Important idea:
          ○ We treat $𝒚$ as a function of $𝒙$.
          ○ Even if $𝒚$ is not given explicitly, it is still understood to depend on $𝒙$, just as in implicit differentiation.




     

Ｖｅｒｉｆｙｉｎｇ　Ｓｏｌｕｔｉｏｎｓ

● Verifying whether a proposed function is a solution to a differential equation.
     ◉ Strategy:
          ○ Differentiate the proposed function.
          ○ Then compare the result with the right-hand side of the differential equation.
     ◉ Key idea:
          ○ A proposed function is a solution if, after differentiating it,
               ■ the derivative satisfies the differential equation identically.
          ○ In other words,
               ■ substituting the function into the equation must make both sides equal on the given interval.

● [8:13](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=493). 🧩 Example 1 — Verify that $𝒚=𝒙+1+𝒄𝒆^{𝒙}$ is a solution to $𝒚'=𝒚-𝒙$ on $(-\infty,\infty)$. [📷image](../img/Calculus 2 Lecture 8.1/[8-13]-01.png)
     ◉ Step 1: Differentiate the proposed function.
          $\rule{0pt}{}$
          ○ $𝒚=𝒙+1+𝒄𝒆^{𝒙}$
          $\rule{0pt}{}$
          ○ Therefore,
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅𝒚}{𝒅𝒙}=1+𝒄𝒆^{𝒙}=𝒚' \;\;(1)$
               $\rule{0pt}{}$
     ◉ Step 2: Compute the right-hand side of the differential equation.
          ○ The equation requires:
               $\rule{0pt}{}$
               ■ $𝒚'=𝒚-𝒙$
               $\rule{0pt}{}$
          ○ Since $𝒚=𝒙+1+𝒄𝒆^{𝒙}$,
               $\rule{0pt}{}$
               ■ $𝒚-𝒙=(𝒙+1+𝒄𝒆^{𝒙})-𝒙=1+𝒄𝒆^{𝒙}\;\;(2)$
               $\rule{0pt}{}$
     ◉ Step 3: Compare both expressions.
          ○ From differentiation:
               $\rule{0pt}{}$
               ■ $𝒚'=1+𝒄𝒆^{𝒙}\;\;(1)$
               $\rule{0pt}{}$
          ○ From substitution into $𝒚-𝒙$:
               $\rule{0pt}{}$
               ■ $𝒚-𝒙=1+𝒄𝒆^{𝒙}\;\;(2)$
               $\rule{0pt}{}$
          ○ Therefore,
               $\rule{0pt}{}$
               ■ $𝒚'=𝒚-𝒙$
               $\rule{0pt}{}$
     ◉ Conclusion:
          ○ The proposed function is indeed a solution on $(-\infty,\infty)$.
     ◉ NOTE:
          ○ The constant $𝒄$ remains arbitrary here.
          ○ That means this expression represents a family of solutions, not just one single curve.





          

Ｇｅｎｅｒａｌ　Ｓｏｌｕｔｉｏｎｓ　Ａｎｄ　Ｉｎｉｔｉａｌ　Ｖａｌｕｅ　Ｐｒｏｂｌｅｍｓ

● [14:41](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=881). General solutions and arbitrary constants. [📷image](../img/Calculus 2 Lecture 8.1/[14-41]-01.png)
     ◉ [15:16](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=916). A first-order differential equation typically has a solution with one arbitrary constant $𝒄$.
     ◉ A solution containing one arbitrary constant is called a general solution.
     ◉ Geometric interpretation:
          ○ the general solution represents a family of integral curves. 

● [16:30](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=990). Particular solutions and initial values. [📷image](../img/Calculus 2 Lecture 8.1/[16-30]-01.png)
     ◉ For a particular solution,
          ○ an initial value is required.
     ◉ Standard initial-value form:
          $\rule{0pt}{}$
          ○ $𝒚(𝒙_{0})=𝒚_{0}$
     ◉ Geometric meaning:
          ○ the initial value selects one specific curve from the family of solutions.
          ○ Equivalently,
               ■ it forces the solution curve to pass through the fixed point $(𝒙_{0},𝒚_{0})$.
     ◉ NOTE 1:
          ○ the arbitrary constant is what distinguishes one curve from another within the same family.
          ○ once the initial value is imposed,
               ■ the constant is determined,
               ■ and the general solution becomes a particular solution.
     ◉ NOTE 2:
          ○ Two different initial points can determine the same constant only if both points lie on the same particular solution curve.

● [20:55](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=1255). 🧩 Example 2 — :Initial value problem with $𝒚(0)=0$. [📷image](../img/Calculus 2 Lecture 8.1/[20-55]-01.png)
     ◉ Use the previously verified general solution on🧩Example 1:
          $\rule{0pt}{}$
          ○ $𝒚=𝒙+1+𝒄𝒆^{𝒙}$
          $\rule{0pt}{}$
     ◉ Substitute the initial value.
          $\rule{0pt}{}$
          ○ $0=0+1+𝒄𝒆^{0}$
          $\rule{0pt}{}$
          ○ $0=1+𝒄$
          $\rule{0pt}{}$
          ○ $𝒄=-1$
          $\rule{0pt}{}$
     ◉ Particular solution:
          $\rule{0pt}{}$
          ○ $𝒚=𝒙+1-𝒆^{𝒙}$
          $\rule{0pt}{}$
     ◉ Interpretation:
          ○ the initial condition reduces the general solution to one specific curve.





          

Ｓｅｐａｒａｂｌｅ　Ｄｉｆｆｅｒｅｎｔｉａｌ　Ｅｑｕａｔｉｏｎｓ

● [📷image](../img/Calculus 2 Lecture 8.1/[26-21]-01.png)

● [26:21](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=1581). Definition of a separable differential equation.  
     ◉ A separable differential equation is a first-order differential equation that can be written as a product of:
          ○ a function of $𝒙$
          ○ and a function of $𝒚$
     ◉ Structural idea:
          ○ one factor depends on one variable,
          ○ and the other factor depends on the second variable.
     ◉ Main consequence:
          ○ the variables can be separated onto opposite sides of the equation.

● [28:34](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=1714). Standard forms of separable equations.
     ◉ Product form:
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=𝓰(𝒙)𝒉(𝒚)$
          $\rule{0pt}{}$
     ◉ Equivalent differential form:
          $\rule{0pt}{}$
          ○ $\mathcal{M}(𝒙)\,𝒅𝒙+\mathcal{N}(𝒚)\,𝒅𝒚=0$
          $\rule{0pt}{}$
     ◉ These two forms are equivalent ways of expressing the same separable structure.

● [30:10](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=1810). Classification 🧩 examples: separable vs. non-separable. 
     ◉ A differential equation is separable when all $𝒙$-terms can be placed on one side and all $𝒚$-terms on the other.
     ◉ If $𝒙$ and $𝒚$ remain mixed in a way that cannot be separated,
          ○ the equation is non-separable.
     ◉ Separable examples:
     $\rule{0pt}{}$
          ○ $(𝒙^{2}+1)\,𝒅𝒙+\dfrac{1}{𝒚}\,𝒅𝒚=0$
          $\rule{0pt}{}$
               ■ already written with the $𝒙$-part and the $𝒚$-part separated
               $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒕}=𝒌𝒚$
          $\rule{0pt}{}$
               ■ can be viewed as $𝓰(𝒕)𝒉(𝒚)$
               ■ with $𝒌=𝓰(𝒕)$
               ■ and $𝒚=𝒉(𝒚)$
     ◉ Non-separable examples:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=𝒙𝒚^{2}+2𝒙^{2}$
          $\rule{0pt}{}$
               ■ the terms do not factor into one function of $𝒙$ times one function of $𝒚$
               ■ Compare with:
                    $\rule{0pt}{}$
                    ▣ $\dfrac{𝒅𝒚}{𝒅𝒙}=𝒙^{2}𝒚^{2}+2𝒙^{2}$
                    $\rule{0pt}{}$
                    ▣ $=𝒙^{2}(𝒚^{2}+2)$
                    $\rule{0pt}{}$
                    ▣ this one is separable, because it can be written as
                         $\rule{0pt}{}$
                         ▢ $𝓰(𝒙)𝒉(𝒚)$
                    $\rule{0pt}{}$
                    ▣ with
                         $\rule{0pt}{}$
                         ▢ $𝓰(𝒙)=𝒙^{2}$
                         $\rule{0pt}{}$
                         ▢ $𝒉(𝒚)=𝒚^{2}+2$  
                         $\rule{0pt}{}$
          ○ $(𝒙+𝒚)\,𝒅𝒙+𝒙𝒚\,𝒅𝒚=0$
          $\rule{0pt}{}$
               ■ the variables remain mixed and cannot be cleanly separated






Ｇｅｎｅｒａｌ ｍｅｔｈｏｄ ｆｏｒ ｓｏｌｖｉｎｇ ｂｙ ｓｅｐａｒａｔｉｏｎ ｏｆ ｖａｒｉａｂｌｅｓ．

● [35:10](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=2110). General method for solving by separation of variables. [📷image](../img/Calculus 2 Lecture 8.1/[35-10]-01.png)
     ◉ Start with a separable equation:
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=𝓰(𝒙)\cdot 𝒉(𝒚)$
          $\rule{0pt}{}$
     ◉ Rearrangement:
          ○ Divide both sides by $𝒉(𝒚)$:
               $\rule{0pt}{}$
               ■ $\dfrac{1}{𝒉(𝒚)}\cdot \dfrac{𝒅𝒚}{𝒅𝒙}=𝓰(𝒙)$
               $\rule{0pt}{}$
          ○ Then separate the variables:
               $\rule{0pt}{}$
               ■ $\dfrac{1}{𝒉(𝒚)}\,𝒅𝒚=𝓰(𝒙)\,𝒅𝒙$
               $\rule{0pt}{}$
     ◉ Integrate both sides.
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{𝒉(𝒚)}\,𝒅𝒚=\int 𝓰(𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ General solution form:
          $\rule{0pt}{}$
          ○ $\mathcal{H}(𝒚)=\mathcal{G}(𝒙)+𝒄$
          $\rule{0pt}{}$
     ◉ Interpretation of the notation:
          ○ $\mathcal{H}(𝒚)$ is the antiderivative of $\dfrac{1}{𝒉(𝒚)}$ with respect to $𝒚$
          $\rule{0pt}{}$
          ○ $\mathcal{G}(𝒙)$ is the antiderivative of $𝓰(𝒙)$ with respect to $𝒙$
          $\rule{0pt}{}$
     ◉ Heuristic idea:
          ○ The step
               $\rule{0pt}{}$
               ■ $\dfrac{1}{𝒉(𝒚)}\cdot \dfrac{𝒅𝒚}{𝒅𝒙}=𝓰(𝒙)$
               $\rule{0pt}{}$
          ○ is treated as if the $𝒅𝒙$ moves to the other side:
               $\rule{0pt}{}$
               ■ $\dfrac{1}{𝒉(𝒚)}\,𝒅𝒚=𝓰(𝒙)\,𝒅𝒙$
               $\rule{0pt}{}$
          ○ This is the standard separation-of-variables manipulation.
     ◉ Main idea:
          ○ first separate all $𝒚$-terms from all $𝒙$-terms
          ○ then integrate each side with respect to its own variable

● [40:21](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=2421). 🧩 Example 1 — Solve $\dfrac{𝒅𝒚}{𝒅𝒙}=\dfrac{𝒚}{𝒙}$ [📷image-1](../img/Calculus 2 Lecture 8.1/[40-21]-01.png) [📷image-2](../img/Calculus 2 Lecture 8.1/[40-21]-02.png)
     ◉ Recognize it as separable.
          ○ Rewrite:
               $\rule{0pt}{}$
               ■ $\dfrac{1}{𝒚}\cdot \dfrac{𝒅𝒚}{𝒅𝒙}=\dfrac{1}{𝒙}$
               $\rule{0pt}{}$
     ◉ Separate and integrate.
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{𝒚}\,𝒅𝒚=\int \dfrac{1}{𝒙}\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Logarithmic antiderivatives:
          $\rule{0pt}{}$
          ○ $\ln|𝒚|=\ln|𝒙|+𝒄_{1}$
          $\rule{0pt}{}$
     ◉ [44:27](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=2667). Constant manipulation.
          ○ Rewrite the constant in logarithmic form so it can be combined with the other logarithm:
               $\rule{0pt}{}$
               ■ $𝒄_{1}=\ln|𝒆^{𝒄_{1}}|$
               $\rule{0pt}{}$
               ■ Let $𝒄_{2}=𝒆^{𝒄_{1}}$
               $\rule{0pt}{}$
               ■ Then $𝒄_{1}=\ln|𝒄_{2}|$
               $\rule{0pt}{}$
     ◉ Combine logarithms.
          $\rule{0pt}{}$
          ○ $\ln|𝒚|=\ln|𝒙|+\ln|𝒄_{2}|$
          $\rule{0pt}{}$
          ○ $=\ln|𝒙\cdot 𝒄_{2}|$
          $\rule{0pt}{}$
     ◉ Exponentiate both sides.
          $\rule{0pt}{}$
          ○ $𝒆^{\ln|𝒚|}=𝒆^{\ln|𝒙\cdot 𝒄_{2}|}$
          $\rule{0pt}{}$
          ○ so $|𝒚|=|𝒙\cdot 𝒄_{2}|$
          $\rule{0pt}{}$
     ◉ Remove the absolute values.
          $\rule{0pt}{}$
          ○ $𝒚=\pm 𝒙\cdot 𝒄_{2}$
          $\rule{0pt}{}$
          ○ $=\pm 𝒄_{2}\,𝒙$
          $\rule{0pt}{}$
     ◉ Absorb the sign into the constant.
          ○ Let $𝒄=\pm 𝒄_{2}$
          ○ Therefore:
               $\rule{0pt}{}$
               ■ $𝒚=𝒄𝒙$
               $\rule{0pt}{}$
     ◉ [50:40](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=3040). Final general solution.
          $\rule{0pt}{}$
          ○ $𝒚=𝒄𝒙$
          $\rule{0pt}{}$
     ◉ NOTE:
          ○ In logarithmic separable equations, the constant is often rewritten and renamed so the logarithms can be combined cleanly.
          ○ The $\pm$ sign that appears after removing absolute values is absorbed into the arbitrary constant.

● [56:02](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=3362). 🧩 Example 2 — Solve $\dfrac{𝒅𝒚}{𝒅𝒙}=\dfrac{𝒙𝒚}{𝒙^{2}+1}$. [📷image-1](../img/Calculus 2 Lecture 8.1/[56-02]-01.png) [📷image-2](../img/Calculus 2 Lecture 8.1/[56-02]-02.png)
     ◉ Recognize it as separable.
          ○ Product form:
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅𝒚}{𝒅𝒙}=𝓰(𝒙)\cdot 𝒉(𝒚)$
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅𝒚}{𝒅𝒙}=\left(\dfrac{𝒙}{𝒙^{2}+1}\right)\cdot 𝒚$
               $\rule{0pt}{}$
     ◉ Separate the variables.
          $\rule{0pt}{}$
          ○ $\dfrac{1}{𝒚}\cdot \dfrac{𝒅𝒚}{𝒅𝒙}=\dfrac{𝒙}{𝒙^{2}+1}$
          $\rule{0pt}{}$
          ○ hence
               $\rule{0pt}{}$
               ■ $\dfrac{1}{𝒚}\,𝒅𝒚=\dfrac{𝒙}{𝒙^{2}+1}\,𝒅𝒙$
               $\rule{0pt}{}$
     ◉ Integrate both sides.
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{𝒚}\,𝒅𝒚=\int \dfrac{𝒙}{𝒙^{2}+1}\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $\ln|𝒚|=\displaystyle \int \dfrac{𝒙}{𝒙^{2}+1}\,𝒅𝒙+𝒄_{1}$
          $\rule{0pt}{}$
     ◉ Use the substitution on the right-hand side.
          ○ Let $𝒖=𝒙^{2}+1$
          ○ then $𝒅𝒖=2𝒙\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ so $\dfrac{𝒅𝒖}{2}=𝒙\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ Therefore:
               $\rule{0pt}{}$
               ■ $\displaystyle \int \dfrac{𝒙}{𝒙^{2}+1}\,𝒅𝒙=\dfrac{1}{2}\int \dfrac{1}{𝒖}\,𝒅𝒖$
               $\rule{0pt}{}$
               ■ $=\dfrac{1}{2}\ln|𝒖|$
               $\rule{0pt}{}$
               ■ $=\dfrac{1}{2}\ln|𝒙^{2}+1|$
               $\rule{0pt}{}$
     ◉ So the integrated equation becomes:
          $\rule{0pt}{}$
          ○ $\ln|𝒚|=\dfrac{1}{2}\ln|𝒙^{2}+1|+𝒄_{1}$
          $\rule{0pt}{}$
     ◉ [1:02:15](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=3735). Rewrite the constant in logarithmic form.
          $\rule{0pt}{}$
          ○ $𝒄_{1}=\ln|𝒆^{𝒄_{1}}|$
          $\rule{0pt}{}$
          ○ Let $𝒄_{2}=𝒆^{𝒄_{1}}$
          $\rule{0pt}{}$
          ○ Then:
               $\rule{0pt}{}$
               ■ $𝒄_{1}=\ln|𝒄_{2}|$
               $\rule{0pt}{}$
     ◉ Substitute this back into the equation.
          $\rule{0pt}{}$
          ○ $\ln|𝒚|=\dfrac{1}{2}\ln|𝒙^{2}+1|+\ln|𝒄_{2}|$
          $\rule{0pt}{}$
     ◉ Rewrite the factor $\dfrac{1}{2}$ as an exponent.
          $\rule{0pt}{}$
          ○ $\dfrac{1}{2}\ln|𝒙^{2}+1|=\ln|(𝒙^{2}+1)^{1/2}|$
          $\rule{0pt}{}$
          ○ $=\ln|\sqrt{𝒙^{2}+1}|$
          $\rule{0pt}{}$
     ◉ Combine the logarithms.
          $\rule{0pt}{}$
          ○ $\ln|𝒚|=\ln|\sqrt{𝒙^{2}+1}|+\ln|𝒄_{2}|$
          $\rule{0pt}{}$
          ○ $=\ln|\sqrt{𝒙^{2}+1}\cdot 𝒄_{2}|$
          $\rule{0pt}{}$
     ◉ Exponentiate both sides.
          $\rule{0pt}{}$
          ○ $𝒆^{\ln|𝒚|}=𝒆^{\ln|\sqrt{𝒙^{2}+1}\cdot 𝒄_{2}|}$
          $\rule{0pt}{}$
          ○ so
               $\rule{0pt}{}$
               ■ $|𝒚|=|\sqrt{𝒙^{2}+1}\cdot 𝒄_{2}|$
               $\rule{0pt}{}$
     ◉ Remove the absolute values.
          $\rule{0pt}{}$
          ○ $𝒚=\pm \sqrt{𝒙^{2}+1}\cdot 𝒄_{2}$
          $\rule{0pt}{}$
          ○ $=\pm 𝒄_{2}\sqrt{𝒙^{2}+1}$
          $\rule{0pt}{}$
     ◉ Absorb the sign into the constant.
          ○ Let $𝒄=\pm 𝒄_{2}$
     ◉  Final general solution.
          $\rule{0pt}{}$
          ○ $𝒚=𝒄\sqrt{𝒙^{2}+1}$
          $\rule{0pt}{}$
     ◉ NOTE:
          ○ Since $𝒙^{2}+1>0$ for every real $𝒙$,
          $\rule{0pt}{}$
               ■ $\sqrt{𝒙^{2}+1}$ is always defined and positive.
          ○ As in the previous example,
               ■ the $\pm$ sign is absorbed into the arbitrary constant.





          

Ａｄｖａｎｃｅｄ　Ｉｎｉｔｉａｌ　Ｖａｌｕｅ　Ｐｒｏｂｌｅｍ

● [1:09:33](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=4173). 🧩 Example — Solve the IVP: $(𝒚^{2}-1)\dfrac{𝒅𝒚}{𝒅𝒙}=-𝒚𝒆^{𝒙}$ with $𝒚(0)=1$. [📷image](../img/Calculus 2 Lecture 8.1/[1-09-33]-01.png)
     ◉ Separate the variables.
          $\rule{0pt}{}$
          ○ $(𝒚^{2}-1)\,𝒅𝒚=-𝒚𝒆^{𝒙}\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒚^{2}-1}{𝒚}\,𝒅𝒚=-𝒆^{𝒙}\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Simplify the $𝒚$-integrand.
          $\rule{0pt}{}$
          ○ $\dfrac{𝒚^{2}-1}{𝒚}=𝒚-\dfrac{1}{𝒚}$
          $\rule{0pt}{}$
     ◉ Integrate both sides.
          $\rule{0pt}{}$
          ○ $\displaystyle \int \left(𝒚-\dfrac{1}{𝒚}\right)\,𝒅𝒚=\int -𝒆^{𝒙}\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{2}𝒚^{2}-\ln|𝒚|=-𝒆^{𝒙}+𝒄_{1}$
          $\rule{0pt}{}$
     ◉ Multiply through by $2$.
          $\rule{0pt}{}$
          ○ $𝒚^{2}-2\ln|𝒚|=-2𝒆^{𝒙}+2𝒄_{1}$
          $\rule{0pt}{}$
     ◉ Rewrite the logarithmic term.
          ○ Since $2\ln|𝒚|=\ln(𝒚^{2})$,
               $\rule{0pt}{}$
               ■ $𝒚^{2}-\ln(𝒚^{2})=-2𝒆^{𝒙}+𝒄_{2}$
               $\rule{0pt}{}$
               ■ where $𝒄_{2}=2𝒄_{1}$
     ◉ Apply the initial value.
          ○ Substitute $𝒚(0)=1$:
               $\rule{0pt}{}$
               ■ $1^{2}-\ln(1^{2})=-2𝒆^{0}+𝒄_{2}$
               $\rule{0pt}{}$
               ■ $1-0=-2+𝒄_{2}$
               $\rule{0pt}{}$
               ■ $𝒄_{2}=3$
               $\rule{0pt}{}$
     ◉ Particular implicit solution.
          $\rule{0pt}{}$
          ○ $𝒚^{2}-\ln(𝒚^{2})=-2𝒆^{𝒙}+3$
          $\rule{0pt}{}$
     ◉ NOTE:
          ○ The solution is left in implicit form.
          ○ Solving explicitly for $𝒚$ is not practical here.





          

Ｎａｔｕｒａｌ　Ｇｒｏｗｔｈ　＆　Ｄｅｃａｙ

● [1:18:47](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=4727). Modeling natural growth and decay. [📷image](../img/Calculus 2 Lecture 8.1/[1-18-47]-01.png)
     ◉ Basic idea:
          ○ Growth or decay occurs at a rate proportional to the size of the population.
     ◉ Important clarification:
          ○ $𝒚=𝒌𝒕$ does not imply $\dfrac{𝒅𝒚}{𝒅𝒕}=𝒌𝒚$.
          ○ In fact, if $𝒚=𝒌𝒕$, then
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅𝒚}{𝒅𝒕}=𝒌$
               $\rule{0pt}{}$
          ○ For natural growth and decay, the correct assumption is:
               ■ the rate of change is proportional to the current population
          ○ So:
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅𝒚}{𝒅𝒕}\propto 𝒚$
               $\rule{0pt}{}$
               ■ hence $\dfrac{𝒅𝒚}{𝒅𝒕}=𝒌𝒚$
               $\rule{0pt}{}$
          ○ In words:
               ■ the rate of change of the population is proportional to the population itself.
     ◉ Differential equation model:
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒕}=𝒌𝒚$
          $\rule{0pt}{}$
          ○ where $𝒚=𝒚(𝒕)$
     ◉ Interpretation of the derivative:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒕}$ measures how fast the population changes with respect to time.
          $\rule{0pt}{}$
          ○ If $\dfrac{𝒅𝒚}{𝒅𝒕}>0$,
          $\rule{0pt}{}$
               ■ the population is increasing.
               $\rule{0pt}{}$
          ○ If $\dfrac{𝒅𝒚}{𝒅𝒕}<0$,
          $\rule{0pt}{}$
               ■ the population is decreasing.
     ◉ Interpretation of $𝒌$:
          ○ if $𝒌>0$,
               ■ the population grows
          ○ if $𝒌<0$,
               ■ the population decays
     ◉ Initial value:
          $\rule{0pt}{}$
          ○ $𝒚(0)=𝒚_{0}$
          $\rule{0pt}{}$
          ○ $𝒚_{0}$ represents the starting population.

● [1:23:26](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=5006). Derivation of the exponential growth/decay law. [📷image-1](../img/Calculus 2 Lecture 8.1/[1-23-26]-01.png) [📷image-2](../img/Calculus 2 Lecture 8.1/[1-23-26]-02.png)
     ◉ Start from the model:
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒕}=𝒌𝒚$
          $\rule{0pt}{}$
     ◉ Separate variables:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{𝒚}\cdot \dfrac{𝒅𝒚}{𝒅𝒕}=𝒌$
          $\rule{0pt}{}$
          ○ hence
               $\rule{0pt}{}$
               ■ $\dfrac{1}{𝒚}\,𝒅𝒚=𝒌\,𝒅𝒕$
               $\rule{0pt}{}$
     ◉ Integrate both sides:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{𝒚}\,𝒅𝒚=\int 𝒌\,𝒅𝒕$
          $\rule{0pt}{}$
          ○ $\ln|𝒚|=𝒌𝒕+𝒄_{1}$
          $\rule{0pt}{}$
     ◉ Exponentiate:
          $\rule{0pt}{}$
          ○ $𝒆^{\ln|𝒚|}=𝒆^{𝒌𝒕+𝒄_{1}}$
          $\rule{0pt}{}$
          ○ $|𝒚|=𝒆^{𝒌𝒕}\cdot 𝒆^{𝒄_{1}}$
          $\rule{0pt}{}$
     ◉ Rewrite the constant:
          ○ Let $𝒄_{2}=𝒆^{𝒄_{1}}$
          ○ then
               $\rule{0pt}{}$
               ■ $|𝒚|=𝒄_{2}\,𝒆^{𝒌𝒕}$
               $\rule{0pt}{}$
     ◉ Remove the absolute value:
          $\rule{0pt}{}$
          ○ $𝒚=\pm 𝒄_{2}\,𝒆^{𝒌𝒕}$
          $\rule{0pt}{}$
     ◉ Absorb the sign into the constant:
          ○ Let $𝒄=\pm 𝒄_{2}$
          ○ therefore
               $\rule{0pt}{}$
               ■ $𝒚=𝒄𝒆^{𝒌𝒕}$
               $\rule{0pt}{}$
     ◉ Use the initial value $𝒚(0)=𝒚_{0}$:
          $\rule{0pt}{}$
          ○ $𝒚_{0}=𝒄𝒆^{0}$
          $\rule{0pt}{}$
          ○ $𝒚_{0}=𝒄$
     ◉ Final model:
          $\rule{0pt}{}$
          ○ $𝒚=𝒚_{0}𝒆^{𝒌𝒕}$
     ◉ Interpretation:
          ○ $𝒚_{0}$ is the initial population.
          ○ The constant $𝒌$ determines whether the model describes growth or decay.




          

Ｍｏｄｅｌ　Ａｓｓｕｍｐｔｉｏｎｓ　Ｆｏｒ　Ｎａｔｕｒａｌ　Ｇｒｏｗｔｈ　＆　Ｄｅｃａｙ

● [1:44:15](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=6255). Modeling assumption for the exponential growth/decay model.
     ◉ Core assumption:
     $\rule{0pt}{}$
          ○ The equation $\dfrac{𝒅𝒚}{𝒅𝒕}=𝒌𝒚$ can only be used when the problem states that the growth or decay rate is **proportional** to the current population.
          $\rule{0pt}{}$
          ○ This proportionality cannot be assumed unless it is explicitly given in the statement.
     ◉ Important remark:
          ○ Not every growth or decay process is proportional to the population size.
          $\rule{0pt}{}$
          ○ Some external effects may act non-proportionally, so the model $\dfrac{𝒅𝒚}{𝒅𝒕}=𝒌𝒚$ would no longer be appropriate.
     ◉ Example of a non-proportional effect:
          ○ If an external agent acts independently of the current population size,
               ■ the population may decrease in a way that is not proportional to $𝒚$.
          ○ In such a case,
               ■ the exponential model should not be assumed.





Λｐｐｌｉｃａｔｉｏｎｓ
               

1 - Ｂａｃｔｅｒｉａｌ　Ｇｒｏｗｔｈ

● [1:46:45](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=6405). 🧩 Application — Bacterial growth. [📷image](../img/Calculus 2 Lecture 8.1/[1-46-45]-01.png)
     ◉ Growth of bacteria is proportional to its population. Initially, 600 bacteria are present. After 3 hours, 10,000 bacteria are present.
     ◉ Modeling assumption:
          ○ the growth of the bacteria is proportional to its population.
     ◉ Initial data:
          ○ initially there are 600 bacteria
          ○ after 3 hours there are 10,000 bacteria
     ◉ Goal:
          ○ find the number of bacteria after $𝒕$ hours.
     ◉ Start from the natural growth model:
          $\rule{0pt}{}$
          ○ $𝒚=𝒚_{0}𝒆^{𝒌𝒕}$
     ◉ Substitute the initial population.
          $\rule{0pt}{}$
          ○ $𝒚=600𝒆^{𝒌𝒕}$
     ◉ Use the second data point:
          $\rule{0pt}{}$
          ○ $𝒚(3)=10{,}000$
          $\rule{0pt}{}$
          ○ $10{,}000=600𝒆^{3𝒌}$
          $\rule{0pt}{}$
          ○ $\dfrac{50}{3}=𝒆^{3𝒌}$
          $\rule{0pt}{}$
     ◉ Solve more efficiently for $𝒆^{𝒌}$.
          $\rule{0pt}{}$
          ○ $\left(\dfrac{50}{3}\right)^{1/3}=\left(𝒆^{3𝒌}\right)^{1/3}$
          $\rule{0pt}{}$
          ○ $𝒆^{𝒌}=\left(\dfrac{50}{3}\right)^{1/3}$
          $\rule{0pt}{}$
     ◉ Rewrite the model.
          $\rule{0pt}{}$
          ○ $𝒚=600𝒆^{𝒌𝒕}$
          $\rule{0pt}{}$
          ○ $=600(𝒆^{𝒌})^{𝒕}$
          $\rule{0pt}{}$
          ○ $=600\left[\left(\dfrac{50}{3}\right)^{1/3}\right]^{𝒕}$
          $\rule{0pt}{}$
          ○ $=600\left(\dfrac{50}{3}\right)^{𝒕/3}$
     ◉ Final model:
          $\rule{0pt}{}$
          ○ $𝒚=600\left(\dfrac{50}{3}\right)^{𝒕/3}$

● [1:55:48](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=6948). Population after 5 hours.
     ◉ Substitute $𝒕=5$ into the model.
          $\rule{0pt}{}$
          ○ $𝒚=600\left(\dfrac{50}{3}\right)^{5/3}$
          $\rule{0pt}{}$
     ◉ Numerical value:
          ○ $𝒚\approx 65248$ bacteria

● [1:58:13](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=7093). Time required to reach 24,000 bacteria.
     ◉ Set
          $\rule{0pt}{}$
          ○ $24000=600\left(\dfrac{50}{3}\right)^{𝒕/3}$
     ◉ Simplify:
          $\rule{0pt}{}$
          ○ $40=\left(\dfrac{50}{3}\right)^{𝒕/3}$
          $\rule{0pt}{}$
     ◉ Take logarithms:
          $\rule{0pt}{}$
          ○ $\ln(40)=\left(\dfrac{𝒕}{3}\right)\ln\left(\dfrac{50}{3}\right)$
     ◉ Solve for $𝒕$:
          $\rule{0pt}{}$
          ○ $𝒕=\dfrac{3\ln(40)}{\ln\left(\dfrac{50}{3}\right)}$
          $\rule{0pt}{}$
     ◉ Approximate time:
          ○ $𝒕\approx 3.93$ hours






2 - Ｈａｌｆ－Ｌｉｆｅ　＆　Ｒａｄｉｏａｃｔｉｖｅ　Ｄｅｃａｙ

● [2:02:35](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=7355). 🧩 Application — Half-life and radioactive decay model. [📷image-1](../img/Calculus 2 Lecture 8.1/[2-02-35]-01.png) [📷image-2](../img/Calculus 2 Lecture 8.1/[2-02-35]-02.png)
     ◉ Suppose the half-life of compound A is 1602 years. We have 100 mg to start. Find the amount after $𝒕$ years.
     ◉ Given:
          ○ half-life = 1602 years
          ○ initial amount = 100 mg
     ◉ Goal:
          ○ find the amount after $𝒕$ years.
     ◉ Start from the natural decay model:
          $\rule{0pt}{}$
          ○ $𝒚=𝒚_{0}𝒆^{𝒌𝒕}$
     ◉ Substitute the initial amount.
          $\rule{0pt}{}$
          ○ $𝒚=100𝒆^{𝒌𝒕}$
     ◉ Half-life condition:
          ○ after 1602 years, half of the initial amount remains
               $\rule{0pt}{}$
               ■ $𝒚(1602)=50$
               $\rule{0pt}{}$
          ○ so
               $\rule{0pt}{}$
               ■ $50=100𝒆^{1602𝒌}$
               $\rule{0pt}{}$
               ■ $\dfrac{1}{2}=𝒆^{1602𝒌}$
               $\rule{0pt}{}$
     ◉ Solve for $𝒆^{𝒌}$.
          $\rule{0pt}{}$
          ○ $\left(\dfrac{1}{2}\right)^{1/1602}=\left(𝒆^{1602𝒌}\right)^{1/1602}$
          $\rule{0pt}{}$
          ○ $𝒆^{𝒌}=\left(\dfrac{1}{2}\right)^{1/1602}$
          $\rule{0pt}{}$
     ◉ Rewrite the model.
          $\rule{0pt}{}$
          ○ $𝒚=100𝒆^{𝒌𝒕}$
          $\rule{0pt}{}$
          ○ $=100(𝒆^{𝒌})^{𝒕}$
          $\rule{0pt}{}$
          ○ $=100\left[\left(\dfrac{1}{2}\right)^{1/1602}\right]^{𝒕}$
          $\rule{0pt}{}$
          ○ $=100\left(\dfrac{1}{2}\right)^{𝒕/1602}$
          $\rule{0pt}{}$
     ◉ Final decay model:
          $\rule{0pt}{}$
          ○ $𝒚=100\left(\dfrac{1}{2}\right)^{𝒕/1602}$

● Amount remaining after 1000 years.
     ◉ Substitute $𝒕=1000$ into the model.
          $\rule{0pt}{}$
          ○ $𝒚=100\left(\dfrac{1}{2}\right)^{1000/1602}$
          $\rule{0pt}{}$
     ◉ Numerical value:
          ○ $𝒚\approx 64.88$ mg

● Time required for the amount to decay to 40 mg.
     ◉ Set
          $\rule{0pt}{}$
          ○ $40=100\left(\dfrac{1}{2}\right)^{𝒕/1602}$
     ◉ Simplify:
          $\rule{0pt}{}$
          ○ $\dfrac{2}{5}=\left(\dfrac{1}{2}\right)^{𝒕/1602}$
          $\rule{0pt}{}$
     ◉ Take logarithms:
          $\rule{0pt}{}$
          ○ $\ln\left(\dfrac{2}{5}\right)=\left(\dfrac{𝒕}{1602}\right)\ln\left(\dfrac{1}{2}\right)$
          $\rule{0pt}{}$
     ◉ Solve for $𝒕$:
          $\rule{0pt}{}$
          ○ $𝒕=\dfrac{1602\ln\left(\dfrac{2}{5}\right)}{\ln\left(\dfrac{1}{2}\right)}$
          $\rule{0pt}{}$
     ◉ Approximate time:
          ○ $𝒕\approx 2118$ years






3 - Ｎｅｗｔｏｎ’ｓ　Ｌａｗ　Ｏｆ　Ｃｏｏｌｉｎｇ


● [2:17:55](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=8275). 🧩 Application — Newton’s Law of Cooling. [📷image](../img/Calculus 2 Lecture 8.1/[2-17-55]-01.png)
     ◉ Basic principle:
          ○ A body cools at a rate proportional to the difference between:
               ■ the temperature of the body
               ■ and the ambient temperature
     ◉ Differential equation model:
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒕}=𝒌(𝒚-𝒚_{𝒂})$
          $\rule{0pt}{}$
     ◉ Meaning of the variables:
          ○ $𝒚$ = temperature of the body
          ○ $𝒕$ = time
          ○ $𝒚_{𝒂}$ = ambient temperature
     ◉ Important idea:
          ○ The cooling rate depends not just on $𝒚$ itself,
               ■ but on how far $𝒚$ is from the ambient temperature.
          ○ As $𝒚$ gets closer to $𝒚_{𝒂}$,
               ■ the rate of cooling becomes smaller.



               

3.1 - Ｔｕｒｋｅｙ　Ｃｏｏｌｉｎｇ　Ｃａｓｅ　Ｓｔｕｄｙ

● [📷image-1](../img/Calculus 2 Lecture 8.1/[2-22-22]-01.png) [📷image-2](../img/Calculus 2 Lecture 8.1/[2-22-22]-02.png) [📷image-3](../img/Calculus 2 Lecture 8.1/[2-22-22]-03.png) [📷image-4](../img/Calculus 2 Lecture 8.1/[2-22-22]-04.png) 

● [2:22:22](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=8542). 🧩 C ase study — Cooling of a turkey.
     ◉ A turkey is taken out of an oven at 225°. After 20 min, the temperature was 185°. The temperature of my house was 70°.
     ◉ Conditions:
          ○ ambient temperature $𝒚_{𝒂}=70$
          ○ $𝒚(0)=225$
          ○ $𝒚(20)=185$
     ◉ Interpretation of the variables:
          ○ $𝒚(𝒕)$ = temperature of the turkey
          ○ $𝒕$ = time in minutes
     ◉ Substitute the ambient temperature into the model:
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒕}=𝒌(𝒚-70)$

●  Separate the variables.
     ◉ Rearrangement:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{𝒚-70}\cdot \dfrac{𝒅𝒚}{𝒅𝒕}=𝒌$
          $\rule{0pt}{}$
          ○ hence
               $\rule{0pt}{}$
               ■ $\dfrac{1}{𝒚-70}\,𝒅𝒚=𝒌\,𝒅𝒕$
               $\rule{0pt}{}$
     ◉ Integrate both sides:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{𝒚-70}\,𝒅𝒚=\int 𝒌\,𝒅𝒕$
          $\rule{0pt}{}$
          ○ $\ln|𝒚-70|=𝒌𝒕+𝒄_{1}$

● Solve the general form.
     ◉ Exponentiate:
          $\rule{0pt}{}$
          ○ $𝒆^{\ln|𝒚-70|}=𝒆^{𝒌𝒕+𝒄_{1}}$
          $\rule{0pt}{}$
          ○ $|𝒚-70|=𝒆^{𝒌𝒕}\cdot 𝒆^{𝒄_{1}}$
          $\rule{0pt}{}$
     ◉ Rewrite the constant:
          ○ Let $𝒄_{2}=𝒆^{𝒄_{1}}$
          ○ then
               $\rule{0pt}{}$
               ■ $|𝒚-70|=𝒄_{2}𝒆^{𝒌𝒕}$
     ◉ Remove the absolute value:
          $\rule{0pt}{}$
          ○ $𝒚-70=\pm 𝒄_{2}𝒆^{𝒌𝒕}$
          $\rule{0pt}{}$
     ◉ Absorb the sign into the constant:
          ○ Let $𝒄=\pm 𝒄_{2}$
          ○ therefore
               $\rule{0pt}{}$
               ■ $𝒚-70=𝒄𝒆^{𝒌𝒕}$

● [2:36:30](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=9390). Apply the first condition $𝒚(0)=225$.
     ◉ Substitute into the general solution:
          $\rule{0pt}{}$
          ○ $225-70=𝒄𝒆^{𝒌\cdot 0}$
          $\rule{0pt}{}$
          ○ $155=𝒄$
     ◉ So:
          $\rule{0pt}{}$
          ○ $𝒚-70=155𝒆^{𝒌𝒕}$

● Apply the second condition $𝒚(20)=185$.
     ◉ Substitute:
          $\rule{0pt}{}$
          ○ $185-70=155𝒆^{20𝒌}$
          $\rule{0pt}{}$
          ○ $115=155𝒆^{20𝒌}$
          $\rule{0pt}{}$
          ○ $\dfrac{23}{31}=𝒆^{20𝒌}$
          $\rule{0pt}{}$
     ◉ Solve more efficiently for $𝒆^{𝒌}$:
          $\rule{0pt}{}$
          ○ $\left(\dfrac{23}{31}\right)^{1/20}=\left(𝒆^{20𝒌}\right)^{1/20}$
          $\rule{0pt}{}$
          ○ $𝒆^{𝒌}=\left(\dfrac{23}{31}\right)^{1/20}$

● Final temperature model.
     ◉ Rewrite:
          $\rule{0pt}{}$
          ○ $𝒚-70=155𝒆^{𝒌𝒕}$
          $\rule{0pt}{}$
          ○ $=155(𝒆^{𝒌})^{𝒕}$
          $\rule{0pt}{}$
          ○ $=155\left[\left(\dfrac{23}{31}\right)^{1/20}\right]^{𝒕}$
          $\rule{0pt}{}$
          ○ $=155\left(\dfrac{23}{31}\right)^{𝒕/20}$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $𝒚=70+155\left(\dfrac{23}{31}\right)^{𝒕/20}$

● [2:44:45](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=9885). Temperature after 30 minutes.
     ◉ Substitute $𝒕=30$ into the model:
          $\rule{0pt}{}$
          ○ $𝒚=70+155\left(\dfrac{23}{31}\right)^{30/20}$
          $\rule{0pt}{}$
     ◉ Approximate value:
          ○ $𝒚\approx 169°$

● [2:46:05](https://www.youtube.com/watch?v=WxVaVzxsDb0&t=9965). Time needed for the turkey to cool to 125°F.
     ◉ Set:
          $\rule{0pt}{}$
          ○ $125=70+155\left(\dfrac{23}{31}\right)^{𝒕/20}$
          $\rule{0pt}{}$
     ◉ Simplify:
          $\rule{0pt}{}$
          ○ $55=155\left(\dfrac{23}{31}\right)^{𝒕/20}$
          $\rule{0pt}{}$
          ○ $\dfrac{11}{31}=\left(\dfrac{23}{31}\right)^{𝒕/20}$
          $\rule{0pt}{}$
     ◉ Take logarithms:
          $\rule{0pt}{}$
          ○ $\ln\left(\dfrac{11}{31}\right)=\left(\dfrac{𝒕}{20}\right)\ln\left(\dfrac{23}{31}\right)$
          $\rule{0pt}{}$
     ◉ Solve for $𝒕$:
          $\rule{0pt}{}$
          ○ $𝒕=\dfrac{20\ln\left(\dfrac{11}{31}\right)}{\ln\left(\dfrac{23}{31}\right)}$
          $\rule{0pt}{}$
     ◉ Approximate time:
          ○ $𝒕\approx 69.4$ minutes

● NOTE:
     ◉ The model predicts that the turkey cools quickly at first,
          ○ because the difference between its temperature and the room temperature is large.
     ◉ Later the cooling slows down,
          ○ because the turkey gets closer to the ambient temperature 70.




     

Ｃｏｒｅ　Ｉｄｅａｓ

● Main conceptual summary.
     ◉ A first-order differential equation involves a first derivative.
     ◉ A general solution contains one arbitrary constant.
     ◉ An initial value selects one particular solution.
     ◉ Separable equations are solved by:
          ○ separating variables
          ○ integrating both sides
          ○ and then simplifying algebraically
     ◉ Many natural models arise from separable equations:
          ○ exponential growth
          ○ exponential decay
          ○ half-life
          ○ Newton’s law of cooling




Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Introduction to Differential Equations
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/4-introduction)