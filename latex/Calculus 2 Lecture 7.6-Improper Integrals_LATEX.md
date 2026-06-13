-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ７．６－Ｉｍｐｒｏｐｅｒ Ｉｎｔｅｇｒａｌｓ**---------------------------------







Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:00](https://www.youtube.com/watch?v=g-M8FHslgdk&t=0). Introduction to improper integrals and conditions for existence. [📷image](../img/Calculus 2 Lecture 7.6/[0-00]-01.png)
     ◉ [0:39](https://www.youtube.com/watch?v=g-M8FHslgdk&t=39). Fundamental requirement:
          ○ Usual conditions for a definite integral 
               $\rule{0pt}{}$
               ■ $\displaystyle \int_{𝒂}^{𝒃} 𝒇(𝒙)\,𝒅𝒙$, $𝒇(𝒙)$ must be bounded and finite on $[𝒂,𝒃]$.
               $\rule{0pt}{}$
     ◉ [1:17](https://www.youtube.com/watch?v=g-M8FHslgdk&t=77). Visual definition:
          ○ Improper integrals arise when the region extends infinitely.
          ○ Or when the integrand is not bounded on the interval.




          

Ｆｕｎｄａｍｅｎｔａｌ　Ｃａｓｅｓ

● [2:14](https://www.youtube.com/watch?v=g-M8FHslgdk&t=134). Classification of the two fundamental cases. [📷image](../img/Calculus 2 Lecture 7.6/[2-14]-01.png)
     ◉ Informal idea:
          ○ An improper integral appears when the usual conditions for a definite integral fail.
          ○ That typically happens because:
               ■ the interval is infinite,
               ■ or the function is unbounded on the interval.
     ◉ **Case 1**:
          ○ The interval of integration is infinite.
          ○ It starts at 𝒂 but extends without bound.
     ◉ **Case 2**:
          ○ The interval $[𝒂,𝒃]$ is finite,
          ○ but the function $𝒇(𝒙)$ is unbounded (has an infinite discontinuity) at an endpoint or at some point inside the interval.
    




          

Ｃａｓｅ　1　—　Ｉｎｆｉｎｉｔｅ　Ｉｎｔｅｒｖａｌｓ

● [8:12](https://www.youtube.com/watch?v=g-M8FHslgdk&t=492). 🧩 Example 1 — Evaluate the integral $\displaystyle \int_{1}^{\infty}\dfrac{1}{𝒙^{2}}\,𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.6/[8-12]-01.png)
     ◉ 1. Identify why the integral is improper.
     $\rule{0pt}{}$
          ○ The function $\dfrac{1}{𝒙^{2}}$ is defined for every $𝒙\ge 1$.
          $\rule{0pt}{}$
          ○ There is no infinite discontinuity on $[1,\infty)$.
          ○ The improper behavior comes from the interval extending to infinity.
          ○ So this is **Case 1**: an infinite interval.
          ○ But if we changed the interval to $[-1,\infty]$, then at $𝒙=0$ the function would be undefined.
               ■ It would have an infinite discontinuity there.
               ■ In that situation, a vertical asymptote appears.
               ■ So **Case 2** would also be present.
     ◉ 2. Replace the infinite upper limit with a variable.
          $\rule{0pt}{}$
          ○ Consider $\displaystyle \int_{1}^{𝒃}\dfrac{1}{𝒙^{2}}\,𝒅𝒙$, where $𝒃>1$.
          $\rule{0pt}{}$
          ○ We do this because we cannot substitute $\infty$ directly into the integral.
     ◉ 3. Visual interpretation.
          $\rule{0pt}{}$
          ○ This represents the area under $\dfrac{1}{𝒙^{2}}$ from $𝒙=1$ to $𝒙=𝒃$.
          $\rule{0pt}{}$
          ○ Then we study what happens as $𝒃$ grows without bound.
     ◉ 4. Evaluate the finite integral first.
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{1}^{𝒃}\dfrac{1}{𝒙^{2}}\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $=\displaystyle \int_{1}^{𝒃} 𝒙^{-2}\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $=\Big[\dfrac{𝒙^{-1}}{-1}\Big]_{1}^{𝒃}$
          $\rule{0pt}{}$
          ○ $=\Big[-\dfrac{1}{𝒙}\Big]_{1}^{𝒃}$
          $\rule{0pt}{}$
          ○ $=-\dfrac{1}{𝒃}-\left(-\dfrac{1}{1}\right)$
          $\rule{0pt}{}$
          ○ $=-\dfrac{1}{𝒃}+1$
          $\rule{0pt}{}$
     ◉ [15:53](https://www.youtube.com/watch?v=g-M8FHslgdk&t=953). Use a limit to recover the improper integral.
          ○ The way we handle “plugging in infinity” is with a limit.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{𝒃\to\infty}\int_{1}^{𝒃}\dfrac{1}{𝒙^{2}}\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒃\to\infty}\left(-\dfrac{1}{𝒃}+1\right)$
          $\rule{0pt}{}$
          ○ $=0+1$
          $\rule{0pt}{}$
          ○ $=1$
     ◉ Final evaluation.
          ○ The integral converges.
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{1}^{\infty}\dfrac{1}{𝒙^{2}}\,𝒅𝒙=1$



          

Ｃｏｎｖｅｒｇｅｎｃｅ　Ａｎｄ　Ｎｏｔａｔｉｏｎ

● [18:34](https://www.youtube.com/watch?v=g-M8FHslgdk&t=1114). General notation and definitions of convergence. [📷image](../img/Calculus 2 Lecture 7.6/[18-34]-01.png)
     ◉ Formal notation:
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{𝒂}^{\infty} 𝒇(𝒙)\cdot 𝒅𝒙=\lim_{𝒃\to\infty}\int_{𝒂}^{𝒃} 𝒇(𝒙)\cdot 𝒅𝒙$
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{-\infty}^{𝒃} 𝒇(𝒙)\cdot 𝒅𝒙=\lim_{𝒂\to-\infty}\int_{𝒂}^{𝒃} 𝒇(𝒙)\cdot 𝒅𝒙$
          $\rule{0pt}{}$
     ◉ [21:55](https://www.youtube.com/watch?v=g-M8FHslgdk&t=1315). Definitions:
          ○ **Convergence**:
               ■ the limit exists and is finite
          ○ **Divergence**:
               ■ the limit does not exist, or is infinite



               

Ｅｘａｍｐｌｅｓ　Ｏｎ　Ｉｎｆｉｎｉｔｅ　Ｉｎｔｅｒｖａｌｓ

● [25:35](https://www.youtube.com/watch?v=g-M8FHslgdk&t=1535). 🧩 Example 2 — Evaluate the integral $\displaystyle \int_{1}^{\infty}\dfrac{3}{𝒙}\cdot 𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.6/[25-35]-01.png)
     ◉ Identify why the integral is improper.
     $\rule{0pt}{}$
          ○ The function $\dfrac{3}{𝒙}$ is defined for every $𝒙\ge 1$.
          $\rule{0pt}{}$
               ■ There is no infinite discontinuity on $[1,\infty)$.
          ○ The improper behavior comes from the interval extending to infinity.
          ○ So this is **Case 1**: an infinite interval.
     ◉ Replace the infinite upper limit with a variable.
          $\rule{0pt}{}$
          ○ Consider $\displaystyle \int_{1}^{𝒃}\dfrac{3}{𝒙}\cdot 𝒅𝒙$, where $𝒃>1$.
          $\rule{0pt}{}$
     ◉ Rewrite the improper integral as a limit.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{𝒃\to\infty}\int_{1}^{𝒃}\dfrac{3}{𝒙}\cdot 𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Evaluate the antiderivative first.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{𝒃\to\infty}\Big[3\ln|𝒙|\Big]_{1}^{𝒃}$
          $\rule{0pt}{}$
     ◉ Simplify the expression.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{𝒃\to\infty} 3\big[\ln(𝒃)-\ln(1)\big]$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒃\to\infty} 3\big[\ln(𝒃)-0\big]$
          $\rule{0pt}{}$
     ◉ Analyze the limit.
          ○ As $𝒃\to\infty$, $\ln(𝒃)\to\infty$.
          ○ Therefore the expression grows without bound.
     ◉ Final conclusion.
          ○ The integral is **divergent**.

● [31:10](https://www.youtube.com/watch?v=g-M8FHslgdk&t=1870). 🧩 Example 3 — **Generalization for power integrals (p-integrals)**: $\displaystyle \int_{1}^{\infty}\dfrac{1}{𝒙^{𝒏}}\cdot 𝒅𝒙$. [📷image-1](../img/Calculus 2 Lecture 7.6/[31-10]-01.png)  [📷image-2](../img/Calculus 2 Lecture 7.6/[31-10]-02.png)
     ◉ Goal:
          $\rule{0pt}{}$
          ○ Study the general behavior of improper integrals of the form $\displaystyle \int_{1}^{\infty}\dfrac{1}{𝒙^{𝒏}}\cdot 𝒅𝒙$.
     ◉ Rewrite the improper integral as a limit.
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{1}^{\infty}\dfrac{1}{𝒙^{𝒏}}\cdot 𝒅𝒙=\lim_{𝒃\to\infty}\int_{1}^{𝒃}\dfrac{1}{𝒙^{𝒏}}\cdot 𝒅𝒙$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒃\to\infty}\int_{1}^{𝒃} 𝒙^{-𝒏}\cdot 𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Important precondition.
          ○ The formal antiderivative used below is valid only for $𝒏\neq 1$.
          ○ So the case $𝒏=1$ must be treated separately.
          ○ If $𝒏=1$, then
               $\rule{0pt}{}$
               ■ $\displaystyle \int \dfrac{1}{𝒙}\,𝒅𝒙=\ln|𝒙|$
               $\rule{0pt}{}$
     ◉ Integrate formally for $𝒏\neq 1$.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{𝒃\to\infty}\Big[\dfrac{𝒙^{-𝒏+1}}{-𝒏+1}\Big]_{1}^{𝒃}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒃\to\infty}\left[\dfrac{𝒃^{-𝒏+1}}{1-𝒏}-\dfrac{1}{1-𝒏}\right]$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒃\to\infty}\dfrac{𝒃^{-𝒏+1}-1}{1-𝒏}$
          $\rule{0pt}{}$
     ◉ Rewrite the exponent to study the limit.
          $\rule{0pt}{}$
          ○ $-𝒏+1=-(𝒏-1)$
          $\rule{0pt}{}$
          ○ so $𝒃^{-𝒏+1}=\dfrac{1}{𝒃^{𝒏-1}}$
          $\rule{0pt}{}$
          ○ Hence:
               $\rule{0pt}{}$
               ■ $\displaystyle \int_{1}^{\infty}\dfrac{1}{𝒙^{𝒏}}\cdot 𝒅𝒙=\dfrac{1}{1-𝒏}\cdot \lim_{𝒃\to\infty}\left[\dfrac{1}{𝒃^{𝒏-1}}-1\right]$
               $\rule{0pt}{}$
     ◉ Analyze the limit.
          ○ If $𝒏>1$,
               ■ then $𝒏-1>0$
               $\rule{0pt}{}$
               ■ so $\dfrac{1}{𝒃^{𝒏-1}}\to 0$
               $\rule{0pt}{}$
               ■ and the integral converges.
          ○ If $𝒏=1$,
               $\rule{0pt}{}$
               ■ the integral becomes $\displaystyle \int_{1}^{\infty}\dfrac{1}{𝒙}\cdot 𝒅𝒙$
               $\rule{0pt}{}$
               ■ which diverges, as shown in the previous example.
          ○ If $𝒏<1$,
               ■ then $𝒏-1<0$
               ■ so $𝒃^{-𝒏+1}$ grows without bound
               ■ and the integral diverges.
     ◉ **Final p-integral criterion.**
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{1}^{\infty}\dfrac{1}{𝒙^{𝒏}}\cdot 𝒅𝒙$ **converges if $𝒏>1$**
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{1}^{\infty}\dfrac{1}{𝒙^{𝒏}}\cdot 𝒅𝒙$ **diverges if $𝒏\le 1$**      


● [43:46](https://www.youtube.com/watch?v=g-M8FHslgdk&t=2626). 🧩 Example 4 — Evaluate the improper integral $\displaystyle \int_{1}^{\infty} 𝒆^{-2𝒙}\cdot 𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.6/[43-46]-01.png)
     ◉ Rewrite the improper integral as a limit.
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{1}^{\infty} 𝒆^{-2𝒙}\cdot 𝒅𝒙=\lim_{𝒃\to\infty}\int_{1}^{𝒃} 𝒆^{-2𝒙}\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ [46:39](https://www.youtube.com/watch?v=g-M8FHslgdk&t=2799). Use substitution.
          ○ Let:
               ■ $𝒖=-2𝒙$
               ■ $𝒅𝒖=-2\,𝒅𝒙$
               ■ $\dfrac{𝒅𝒖}{-2}=𝒅𝒙$
               $\rule{0pt}{}$
     ◉ Rewrite the integral using 𝒖.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{𝒃\to\infty}\int_{1}^{𝒃} 𝒆^{-2𝒙}\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒃\to\infty}\int 𝒆^{𝒖}\cdot \dfrac{𝒅𝒖}{-2}$
          $\rule{0pt}{}$
          ○ $=-\dfrac{1}{2}\displaystyle \lim_{𝒃\to\infty}\Big[𝒆^{𝒖}\Big]_{1}^{𝒃}$
          $\rule{0pt}{}$
          ○ $=-\dfrac{1}{2}\displaystyle \lim_{𝒃\to\infty}\Big[𝒆^{-2𝒙}\Big]_{1}^{𝒃}$
          $\rule{0pt}{}$
     ◉ Evaluate the limit.
          $\rule{0pt}{}$
          ○ $=-\dfrac{1}{2}\displaystyle \lim_{𝒃\to\infty}\Big[𝒆^{-2𝒃}-𝒆^{-2}\Big]$
          $\rule{0pt}{}$
          ○ $=-\dfrac{1}{2}\displaystyle \lim_{𝒃\to\infty}\left[\dfrac{1}{𝒆^{2𝒃}}-\dfrac{1}{𝒆^{2}}\right]$
          $\rule{0pt}{}$
          ○ Since $\dfrac{1}{𝒆^{2𝒃}}\to 0$ as $𝒃\to\infty$,
               $\rule{0pt}{}$
               ■ the expression becomes $-\dfrac{1}{2}\left(0-\dfrac{1}{𝒆^{2}}\right)$
               $\rule{0pt}{}$
     ◉ Final result.
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{1}^{\infty} 𝒆^{-2𝒙}\cdot 𝒅𝒙=\dfrac{1}{2𝒆^{2}}$
          $\rule{0pt}{}$
     ◉ Conclusion.
          ○ The improper integral converges.

● [54:14](https://www.youtube.com/watch?v=g-M8FHslgdk&t=3254). 🧩 Example 5 — Evaluate the improper integral $\displaystyle \int_{0}^{\infty}\sin(𝒙)\cdot 𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.6/[54-14]-01.png)
     ◉ Rewrite the improper integral as a limit.
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{0}^{\infty}\sin(𝒙)\,𝒅𝒙=\lim_{𝒃\to\infty}\int_{0}^{𝒃}\sin(𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Evaluate the antiderivative.
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒃\to\infty}\Big[-\cos(𝒙)\Big]_{0}^{𝒃}$
          $\rule{0pt}{}$
     ◉ Substitute the bounds.
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒃\to\infty}\Big[-\cos(𝒃)-(-\cos(0))\Big]$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒃\to\infty}\Big[-\cos(𝒃)+\cos(0)\Big]$
          $\rule{0pt}{}$
     ◉ Analyze the limit.
          ○ $\cos(0)=1$
          ○ but $\cos(𝒃)$ does not approach a single value as $𝒃\to\infty$
          ○ it keeps oscillating between $-1$ and $1$
     ◉ Conclusion.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{𝒃\to\infty}\Big[-\cos(𝒃)+1\Big]$ does not exist
          $\rule{0pt}{}$
          ○ so $\displaystyle \int_{0}^{\infty}\sin(𝒙)\cdot 𝒅𝒙$ diverges

● [1:00:30](https://www.youtube.com/watch?v=g-M8FHslgdk&t=3630). 🧩 Example 6 — Evaluate the improper integral $\displaystyle \int_{-\infty}^{0} 𝒙𝒆^{𝒙}\cdot 𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.6/[1-00-30]-01.png)
     ◉ Identify why the integral is improper.
          ○ This is **Case 1**: an infinite interval.
          ○ The interval extends to $-\infty$.
          ○ There is no infinite discontinuity in the integrand $𝒙𝒆^{𝒙}$ on $(-\infty,0]$.
     ◉ Rewrite the improper integral as a limit.
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{-\infty}^{0} 𝒙𝒆^{𝒙}\cdot 𝒅𝒙=\lim_{𝒂\to-\infty}\int_{𝒂}^{0} 𝒙𝒆^{𝒙}\cdot 𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Use integration by parts.
          ○ Choose:
               ■ $𝒖=𝒙$
               ■ $𝒅\mathcal{V}=𝒆^{𝒙}\,𝒅𝒙$
          ○ Then:
               ■ $𝒅𝒖=𝒅𝒙$
               ■ $\mathcal{V}=𝒆^{𝒙}$
     ◉ Apply the integration by parts formula.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{𝒂\to-\infty}\Big[𝒙𝒆^{𝒙}-\int 𝒆^{𝒙}\,𝒅𝒙\Big]_{𝒂}^{0}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒂\to-\infty}\Big[𝒙𝒆^{𝒙}-𝒆^{𝒙}\Big]_{𝒂}^{0}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒂\to-\infty}\Big[𝒆^{𝒙}(𝒙-1)\Big]_{𝒂}^{0}$
          $\rule{0pt}{}$
     ◉ Evaluate the bounds.
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒂\to-\infty}\Big[𝒆^{0}(0-1)-𝒆^{𝒂}(𝒂-1)\Big]$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒂\to-\infty}\Big[-1-𝒂𝒆^{𝒂}+𝒆^{𝒂}\Big]$
          $\rule{0pt}{}$
     ◉ [1:11:14](https://www.youtube.com/watch?v=g-M8FHslgdk&t=4274). Key issue:
          ○ Resolve the indeterminate behavior in the term $𝒂𝒆^{𝒂}$.
          ○ Rewrite:
               $\rule{0pt}{}$
               ■ $𝒂𝒆^{𝒂}=\dfrac{𝒂}{𝒆^{-𝒂}}$
               $\rule{0pt}{}$
          ○ Then apply L'Hôpital's Rule to the limit:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{𝒂\to-\infty} 𝒂𝒆^{𝒂}$
               $\rule{0pt}{}$
               ■ $=\displaystyle \lim_{𝒂\to-\infty}\dfrac{𝒂}{𝒆^{-𝒂}}$
               $\rule{0pt}{}$
               ■ $=\displaystyle \lim_{𝒂\to-\infty}\dfrac{1}{-𝒆^{-𝒂}}$
               $\rule{0pt}{}$
               ■ $=\displaystyle \lim_{𝒂\to-\infty}\left(-\dfrac{1}{𝒆^{-𝒂}}\right)$
               $\rule{0pt}{}$
               ■ Since $𝒂\to-\infty$, we have $-𝒂\to\infty$, so $𝒆^{-𝒂}\to\infty$
               ■ Therefore, $-\dfrac{1}{𝒆^{-𝒂}}\to 0$
               ■ Hence:
                    $\rule{0pt}{}$
                    ▣ $\displaystyle \lim_{𝒂\to-\infty} 𝒂𝒆^{𝒂}=0$
                    $\rule{0pt}{}$
     ◉ Final result.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{𝒂\to-\infty}\Big[-1-𝒂𝒆^{𝒂}+𝒆^{𝒂}\Big]=-1-0+0$
          $\rule{0pt}{}$
          ○ $=-1$
     ◉ Conclusion.
          ○ The integral converges.
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{-\infty}^{0} 𝒙𝒆^{𝒙}\cdot 𝒅𝒙=-1$

● [1:17:15](https://www.youtube.com/watch?v=g-M8FHslgdk&t=4635). 🧩 Example 7 — **Integrals over the entire real line**: $\displaystyle \int_{-\infty}^{\infty}\dfrac{𝒆^{𝒙}}{1+𝒆^{2𝒙}}\cdot 𝒅𝒙$ [📷image-1](../img/Calculus 2 Lecture 7.6/[1-17-15]-01.png) [📷image-2](../img/Calculus 2 Lecture 7.6/[1-17-15]-02.png)
     ◉ 1. Identify why the integral is improper.
     $\rule{0pt}{}$
          ○ The function $\dfrac{𝒆^{𝒙}}{1+𝒆^{2𝒙}}$ is defined everywhere.
          $\rule{0pt}{}$
          ○ There is no infinite discontinuity on $[-\infty,\infty]$.
          ○ The improper behavior comes from the interval extending to infinity.
          ○ So this is **Case 1**: an infinite interval.
     ◉ General form:
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{-\infty}^{\infty} 𝒇(𝒙)\cdot 𝒅𝒙$
          $\rule{0pt}{}$
     ◉ [1:20:03](https://www.youtube.com/watch?v=g-M8FHslgdk&t=4803). Additivity property:
          ○ Split the integral at $𝒙=0$.
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{-\infty}^{\infty}\dfrac{𝒆^{𝒙}}{1+𝒆^{2𝒙}}\cdot 𝒅𝒙$
          $\rule{0pt}{}$
          ○ $=\displaystyle \int_{-\infty}^{0}\dfrac{𝒆^{𝒙}}{1+𝒆^{2𝒙}}\cdot 𝒅𝒙+\int_{0}^{\infty}\dfrac{𝒆^{𝒙}}{1+𝒆^{2𝒙}}\cdot 𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Rewrite both pieces as limits.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{𝒂\to-\infty}\int_{𝒂}^{0}\dfrac{𝒆^{𝒙}}{1+𝒆^{2𝒙}}\cdot 𝒅𝒙$
          $\rule{0pt}{}$
          ○ $+\displaystyle \lim_{𝒃\to\infty}\int_{0}^{𝒃}\dfrac{𝒆^{𝒙}}{1+𝒆^{2𝒙}}\cdot 𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Substitution for the integrand.
          ○ Let $𝒖=𝒆^{𝒙}$
          ○ Then $𝒅𝒖=𝒆^{𝒙}\,𝒅𝒙$
          ○ So:
               $\rule{0pt}{}$
               ■ $\displaystyle \int \dfrac{𝒆^{𝒙}}{1+𝒆^{2𝒙}}\cdot 𝒅𝒙=\int \dfrac{1}{1+𝒖^{2}}\cdot 𝒅𝒖$
               $\rule{0pt}{}$
               ■ $=\tan^{-1}(𝒖)$
               $\rule{0pt}{}$
               ■ $=\tan^{-1}(𝒆^{𝒙})$
               $\rule{0pt}{}$
     ◉ Apply the antiderivative to both improper pieces.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{𝒂\to-\infty}\Big[\tan^{-1}(𝒆^{𝒙})\Big]_{𝒂}^{0}$
          $\rule{0pt}{}$
          ○ $+\displaystyle \lim_{𝒃\to\infty}\Big[\tan^{-1}(𝒆^{𝒙})\Big]_{0}^{𝒃}$
          $\rule{0pt}{}$
     ◉ Evaluate each limit.
          ○ First piece:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{𝒂\to-\infty}\Big[\tan^{-1}(𝒆^{0})-\tan^{-1}(𝒆^{𝒂})\Big]$
               $\rule{0pt}{}$
               ■ $=\tan^{-1}(1)-\tan^{-1}(0)$
               $\rule{0pt}{}$
               ■ $=\dfrac{\pi}{4}-0$
               $\rule{0pt}{}$
          ○ Second piece:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{𝒃\to\infty}\Big[\tan^{-1}(𝒆^{𝒃})-\tan^{-1}(𝒆^{0})\Big]$
               $\rule{0pt}{}$
               ■ $=\tan^{-1}(\infty)-\tan^{-1}(1)$
               $\rule{0pt}{}$
               ■ $=\dfrac{\pi}{2}-\dfrac{\pi}{4}$
               $\rule{0pt}{}$
     ◉ Final result:
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{-\infty}^{\infty}\dfrac{𝒆^{𝒙}}{1+𝒆^{2𝒙}}\cdot 𝒅𝒙=\dfrac{\pi}{4}+\left(\dfrac{\pi}{2}-\dfrac{\pi}{4}\right)$
          $\rule{0pt}{}$
          ○ $=\dfrac{\pi}{2}$
          $\rule{0pt}{}$
     ◉ Conclusion:
          ○ The improper integral **converges**
          $\rule{0pt}{}$
          ○ and its value is $\dfrac{\pi}{2}$.  





               

Ｃａｓｅ　2　—　Ｉｎｆｉｎｉｔｅ　Ｄｉｓｃｏｎｔｉｎｕｉｔｉｅｓ

● [1:33:31](https://www.youtube.com/watch?v=g-M8FHslgdk&t=5611). 🧩 Example 6 — Analysis of Case 2: Infinite discontinuities: $\displaystyle \int_{0}^{9} 𝒙^{-1/2}\cdot 𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.6/[1-33-31]-01.png)
     ◉ 1. Identify why the integral is improper.
          $\rule{0pt}{}$
          ○ The function $𝒙^{-1/2}=\dfrac{1}{\sqrt{𝒙}}$ is undefined at $𝒙=0$.
          $\rule{0pt}{}$
          ○ There is a vertical asymptote at $𝒙=0$.
          ○ So the improper behavior comes from the function itself, not from an infinite interval.
     ◉ 2. Replace the problematic endpoint with an intermediate value.
          ○ Because we cannot plug $𝒙=0$ directly into the integral, we replace the lower limit $0$ with $𝒄$, where $0<𝒄<9$.
          ○ This gives:
               $\rule{0pt}{}$
               ■ $\displaystyle \int_{𝒄}^{9} 𝒙^{-1/2}\cdot 𝒅𝒙$
               $\rule{0pt}{}$
          ○ This parallels Case 1:
               ■ in Case 1 we replaced $\infty$ with a variable $𝒃$,
               ■ here we replace the problematic endpoint $0$ with a variable $𝒄$.
     ◉ 3. Use a one-sided limit.
          ○ Since the discontinuity is at the left endpoint, we approach from the right:
               ■ $𝒄\to 0^{+}$
          ○ So the improper integral is rewritten as:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{𝒄\to 0^{+}}\int_{𝒄}^{9} 𝒙^{-1/2}\cdot 𝒅𝒙$
               $\rule{0pt}{}$
     ◉ 4. Evaluate the integral first.
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{𝒄}^{9} 𝒙^{-1/2}\cdot 𝒅𝒙=\Big[2𝒙^{1/2}\Big]_{𝒄}^{9}$
          $\rule{0pt}{}$
          ○ $=2\sqrt{9}-2\sqrt{𝒄}$
          $\rule{0pt}{}$
     ◉ 5. Take the limit.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{𝒄\to 0^{+}}\Big[2\sqrt{9}-2\sqrt{𝒄}\Big]$
          $\rule{0pt}{}$
          ○ $=6-0$
          $\rule{0pt}{}$
          ○ $=6$
     ◉ Final result.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{𝒄\to 0^{+}}\int_{𝒄}^{9} 𝒙^{-1/2}\cdot 𝒅𝒙=6$
          $\rule{0pt}{}$
          ○ Therefore, the improper integral converges.
     
● [1:43:08](https://www.youtube.com/watch?v=g-M8FHslgdk&t=6188). **Types Of Infinite Discontinuities.** [📷image](../img/Calculus 2 Lecture 7.6/[1-43-08]-01.png)
     ◉ The discontinuity can occur at the upper endpoint.
          ○ If $𝒇(𝒙)$ blows up at $𝒙=𝒃$, then the improper integral
               $\rule{0pt}{}$
               ■ $\displaystyle \int_{𝒂}^{𝒃} 𝒇(𝒙)\,𝒅𝒙$
               $\rule{0pt}{}$
          ○ is defined by approaching $𝒃$ from the left:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{𝒄\to 𝒃^{-}}\int_{𝒂}^{𝒄} 𝒇(𝒙)\,𝒅𝒙$
               $\rule{0pt}{}$
     ◉ [1:46:35](https://www.youtube.com/watch?v=g-M8FHslgdk&t=6395). The discontinuity can occur at the lower endpoint.
          ○ If $𝒇(𝒙)$ blows up at $𝒙=𝒂$, then the improper integral
               $\rule{0pt}{}$
               ■ $\displaystyle \int_{𝒂}^{𝒃} 𝒇(𝒙)\,𝒅𝒙$
               $\rule{0pt}{}$
          ○ is defined by approaching $𝒂$ from the right:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{𝒄\to 𝒂^{+}}\int_{𝒄}^{𝒃} 𝒇(𝒙)\,𝒅𝒙$
               $\rule{0pt}{}$
     ◉ [1:50:01](https://www.youtube.com/watch?v=g-M8FHslgdk&t=6601). The discontinuity can occur at an interior point.
          ○ If $𝒇(𝒙)$ blows up at some point $𝒙=𝒄$ with $𝒂<𝒄<𝒃$,
          ○ then the integral must be split into two improper integrals:
               $\rule{0pt}{}$
               ■ $\displaystyle \int_{𝒂}^{𝒃} 𝒇(𝒙)\,𝒅𝒙=\int_{𝒂}^{𝒄} 𝒇(𝒙)\,𝒅𝒙+\int_{𝒄}^{𝒃} 𝒇(𝒙)\,𝒅𝒙$
               $\rule{0pt}{}$
          ○ and each part is defined separately:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{𝒕\to 𝒄^{-}}\int_{𝒂}^{𝒕} 𝒇(𝒙)\,𝒅𝒙$
               $\rule{0pt}{}$
               ■ $+\displaystyle \lim_{𝒔\to 𝒄^{+}}\int_{𝒔}^{𝒃} 𝒇(𝒙)\,𝒅𝒙$
               $\rule{0pt}{}$
          ○ Both one-sided improper integrals must converge for the original integral to converge.
    ◉ NOTE:
          ○ A removable discontinuity does not create area by itself, because changing or removing the value of a function at isolated points does not change the value of the integral.
          ○ Having many removable discontinuities does not necessarily prevent the area from being computed, because isolated point changes do not affect the value of the integral.





          

Ｅｘａｍｐｌｅｓ　Ｏｎ　Ｉｎｆｉｎｉｔｅ　Ｄｉｓｃｏｎｔｉｎｕｉｔｉｅｓ

● [1:55:11](https://www.youtube.com/watch?v=g-M8FHslgdk&t=6911). 🧩 Example 7 — Discontinuity at the upper limit: $\displaystyle \int_{1}^{4}\dfrac{1}{(4-𝒙)^{2/3}}\cdot 𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.6/[1-55-11]-01.png)
     ◉ 1. Identify why the integral is improper.
          ○ The interval $[1,4]$ is finite.
          ○ The problem is not an infinite interval.
          ○ The integrand $\dfrac{1}{(4-𝒙)^{2/3}}$ blows up at $𝒙=4$.
          ○ So the improper behavior comes from an infinite discontinuity at the **upper endpoint**.
     ◉ 2. Replace the problematic endpoint with a variable.
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{1}^{4}\dfrac{1}{(4-𝒙)^{2/3}}\cdot 𝒅𝒙=\lim_{𝒄\to 4^{-}}\int_{1}^{𝒄}(4-𝒙)^{-2/3}\cdot 𝒅𝒙$
          $\rule{0pt}{}$
     ◉ 3. Use substitution.
          ○ Let $𝒖=4-𝒙$
          ○ Then $𝒅𝒖=-𝒅𝒙$
          ○ So $-𝒅𝒖=𝒅𝒙$
     ◉ 4. Integrate.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{𝒄\to 4^{-}}\int_{1}^{𝒄}(4-𝒙)^{-2/3}\cdot 𝒅𝒙$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒄\to 4^{-}}-\int 𝒖^{-2/3}\cdot 𝒅𝒖$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒄\to 4^{-}}-\Big[3𝒖^{1/3}\Big]_{1}^{𝒄}$
          $\rule{0pt}{}$
          ○ $=-3\displaystyle \lim_{𝒄\to 4^{-}}\Big[(4-𝒙)^{1/3}\Big]_{1}^{𝒄}$
          $\rule{0pt}{}$
     ◉ 5. Evaluate the limit.
          $\rule{0pt}{}$
          ○ $-3\displaystyle \lim_{𝒄\to 4^{-}}\Big[(4-𝒄)^{1/3}-(4-1)^{1/3}\Big]$
          $\rule{0pt}{}$
          ○ $=-3\Big[0-3^{1/3}\Big]$
          $\rule{0pt}{}$
          ○ $=3\cdot 3^{1/3}$
          $\rule{0pt}{}$
     ◉ Final result.
          ○ The integral **converges**.
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{1}^{4}\dfrac{1}{(4-𝒙)^{2/3}}\cdot 𝒅𝒙=3\cdot 3^{1/3}$

● [2:03:43](https://www.youtube.com/watch?v=g-M8FHslgdk&t=7423). 🧩 Example 8 — Lower endpoint. Evaluate the logarithmic improper integral: $\displaystyle \int_{0}^{1}\ln(𝒙)\cdot 𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.6/[2-03-43]-01.png)
     ◉ 1. Identify why the integral is improper.
          ○ The interval $[0,1]$ is finite.
          ○ The problem is not an infinite interval.
          ○ The integrand $\ln(𝒙)$ is not defined at $𝒙=0$.
          ○ In fact, $\ln(𝒙)\to -\infty$ as $𝒙\to 0^{+}$.
          ○ So this is **Case 2**: an infinite discontinuity at the lower endpoint.
     ◉ 2. First find the antiderivative of $\ln(𝒙)$.
          ○ Use integration by parts:
               ■ $𝒖=\ln(𝒙)$
               ■ $𝒅\mathcal{V}=𝒅𝒙$
               ■ $𝒅𝒖=\dfrac{1}{𝒙}\cdot 𝒅𝒙$
               ■ $\mathcal{V}=𝒙$
          ○ Then:
               $\rule{0pt}{}$
               ■ $\displaystyle \int \ln(𝒙)\,𝒅𝒙=𝒙\ln(𝒙)-\int 𝒙\cdot \dfrac{1}{𝒙}\,𝒅𝒙$
               $\rule{0pt}{}$
               ■ $=𝒙\ln(𝒙)-𝒙+𝑪$
               $\rule{0pt}{}$
     ◉ 3. Rewrite the improper integral as a limit.
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{0}^{1}\ln(𝒙)\cdot 𝒅𝒙=\lim_{𝒄\to 0^{+}}\int_{𝒄}^{1}\ln(𝒙)\cdot 𝒅𝒙$
          $\rule{0pt}{}$
     ◉ 4. Evaluate with the antiderivative.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{𝒄\to 0^{+}}\Big[𝒙\ln(𝒙)-𝒙\Big]_{𝒄}^{1}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒄\to 0^{+}}\Big[(1\ln(1)-1)-(𝒄\ln(𝒄)-𝒄)\Big]$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒄\to 0^{+}}\Big[-1-𝒄\ln(𝒄)+𝒄\Big]$
          $\rule{0pt}{}$
     ◉ 5. Handle the difficult limit.
          ○ Since $𝒄\to 0^{+}$, we have $𝒄\to 0$.
          ○ So it remains to evaluate:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{𝒄\to 0^{+}} 𝒄\ln(𝒄)$
               $\rule{0pt}{}$
          ○ Rewrite it as:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{𝒄\to 0^{+}}\dfrac{\ln(𝒄)}{1/𝒄}$
               $\rule{0pt}{}$
          ○ Apply L'Hôpital's Rule:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{𝒄\to 0^{+}}\left[\dfrac{1/𝒄}{-1/𝒄^{2}}\right]$
               $\rule{0pt}{}$
               ■ $=\displaystyle \lim_{𝒄\to 0^{+}}(-𝒄)$
               $\rule{0pt}{}$
               ■ $=0$
               $\rule{0pt}{}$
          ○ Hence:
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{𝒄\to 0^{+}} 𝒄\ln(𝒄)=0$
               $\rule{0pt}{}$
               ■ and $\displaystyle \lim_{𝒄\to 0^{+}} 𝒄=0$
               $\rule{0pt}{}$
     ◉ 6. Final result.
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{0}^{1}\ln(𝒙)\cdot 𝒅𝒙=-1$
          $\rule{0pt}{}$
          ○ So the integral **converges**.
          
● [2:14:40](https://www.youtube.com/watch?v=g-M8FHslgdk&t=8080). 🧩 Example 9 — **Discontinuity at an interior point of the interval**: $\displaystyle \int_{-1}^{1}\dfrac{1}{𝒙^{2}}\cdot 𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.6/[2-14-40]-01.png)
     ◉ 1. Identify why the integral is improper.
          ○ The interval $[-1,1]$ is finite.
          $\rule{0pt}{}$
          ○ The integrand $\dfrac{1}{𝒙^{2}}$ is not defined at $𝒙=0$.
          $\rule{0pt}{}$
          ○ There is a vertical asymptote at the interior point $𝒙=0$.
          ○ So this is **Case 2**: an infinite discontinuity at an interior point.
     ◉ 2. Split the integral at the discontinuity.
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{-1}^{1}\dfrac{1}{𝒙^{2}}\cdot 𝒅𝒙$
          $\rule{0pt}{}$
          ○ $=\displaystyle \int_{-1}^{0}\dfrac{1}{𝒙^{2}}\cdot 𝒅𝒙+\int_{0}^{1}\dfrac{1}{𝒙^{2}}\cdot 𝒅𝒙$
          $\rule{0pt}{}$
          ○ Key idea:
               ■ When the discontinuity is at an interior point,
                    ▣ the improper integral must be separated into **two improper integrals**
                    ▣ one on each side of the discontinuity.
               ■ Convergence requirement.
                    ▣ The original integral converges **only if both pieces converge**.
                    ▣ If either side diverges,
                         ▢ then the whole integral diverges.
    ◉ 3. Evaluate the left-hand side.
         $\rule{0pt}{}$
         ○ $\displaystyle \lim_{𝒄\to 0^{-}}\int_{-1}^{𝒄} 𝒙^{-2}\cdot 𝒅𝒙$
         $\rule{0pt}{}$
         ○ $=\displaystyle \lim_{𝒄\to 0^{-}}\Big[-\dfrac{1}{𝒙}\Big]_{-1}^{𝒄}$
         $\rule{0pt}{}$
         ○ $=\displaystyle \lim_{𝒄\to 0^{-}}\left(-\dfrac{1}{𝒄}-1\right)$
         $\rule{0pt}{}$
         ○ Since $𝒄\to 0^{-}$, we have $-\dfrac{1}{𝒄}\to +\infty$
         ○ Therefore the left-hand integral **diverges**.
   ◉ 5. Evaluate the right-hand side.
         $\rule{0pt}{}$
         ○ $\displaystyle \lim_{𝒄\to 0^{+}}\int_{𝒄}^{1} 𝒙^{-2}\cdot 𝒅𝒙$
         $\rule{0pt}{}$
         ○ $=\displaystyle \lim_{𝒄\to 0^{+}}\Big[-\dfrac{1}{𝒙}\Big]_{𝒄}^{1}$
         $\rule{0pt}{}$
         ○ $=\displaystyle \lim_{𝒄\to 0^{+}}\left(-1+\dfrac{1}{𝒄}\right)$
         $\rule{0pt}{}$
         ○ Since $𝒄\to 0^{+}$, we have $\dfrac{1}{𝒄}\to +\infty$
         ○ Therefore the right-hand integral **diverges**.
   ◉ 6. Final conclusion.
         ○ Both one-sided improper integrals diverge.
         $\rule{0pt}{}$
         ○ So the original integral $\displaystyle \int_{-1}^{1}\dfrac{1}{𝒙^{2}}\cdot 𝒅𝒙$ **diverges**.

● [2:16:32](https://www.youtube.com/watch?v=g-M8FHslgdk&t=8192). 🧩 Example 10 — Combined-case: $\displaystyle \int_{0}^{\infty}\dfrac{𝒆^{-\sqrt{𝒙}}}{\sqrt{𝒙}}\cdot 𝒅𝒙$. [📷image-1](../img/Calculus 2 Lecture 7.6/[2-16-32]-01.png) [📷image-2](../img/Calculus 2 Lecture 7.6/[2-16-32]-02.png)
     ◉ 1. Identify why the integral is improper.
          ○ The interval extends to $\infty$.
          ○ The integrand $\dfrac{𝒆^{-\sqrt{𝒙}}}{\sqrt{𝒙}}$ is also unbounded at $𝒙=0$ because of the factor $\dfrac{1}{\sqrt{𝒙}}$.
          ○ So this example combines:
               ■ **Case 1**: an infinite interval
               ■ **Case 2**: an infinite discontinuity at the lower endpoint
     ◉ 2. Strategy.
          ○ Split the integral at $𝒙=1$ so each issue is handled separately.
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{0}^{\infty}\dfrac{𝒆^{-\sqrt{𝒙}}}{\sqrt{𝒙}}\cdot 𝒅𝒙$
          $\rule{0pt}{}$
          ○ $=\displaystyle \int_{0}^{1}\dfrac{𝒆^{-\sqrt{𝒙}}}{\sqrt{𝒙}}\cdot 𝒅𝒙+\int_{1}^{\infty}\dfrac{𝒆^{-\sqrt{𝒙}}}{\sqrt{𝒙}}\cdot 𝒅𝒙$
          $\rule{0pt}{}$
     ◉ 3. Rewrite both pieces as limits.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{𝒄\to 0^{+}}\int_{𝒄}^{1}\dfrac{𝒆^{-\sqrt{𝒙}}}{\sqrt{𝒙}}\cdot 𝒅𝒙$
          $\rule{0pt}{}$
          ○ $+\displaystyle \lim_{𝒃\to\infty}\int_{1}^{𝒃}\dfrac{𝒆^{-\sqrt{𝒙}}}{\sqrt{𝒙}}\cdot 𝒅𝒙$
          $\rule{0pt}{}$
     ◉ 4. Use the same substitution in both parts.
          ○ Let $𝒖=-\sqrt{𝒙}$
          $\rule{0pt}{}$
          ○ Then $𝒅𝒖=-\dfrac{1}{2\sqrt{𝒙}}\cdot 𝒅𝒙$
          $\rule{0pt}{}$
          ○ So $𝒅𝒙=-2\sqrt{𝒙}\cdot 𝒅𝒖$
          $\rule{0pt}{}$
          ○ Hence:
               $\rule{0pt}{}$
               ■ $\displaystyle \int \dfrac{𝒆^{-\sqrt{𝒙}}}{\sqrt{𝒙}}\cdot 𝒅𝒙=-2\int 𝒆^{𝒖}\,𝒅𝒖=-2𝒆^{𝒖}=-2𝒆^{-\sqrt{𝒙}}$
               $\rule{0pt}{}$
     ◉ 5. Evaluate the first improper piece.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{𝒄\to 0^{+}}\Big[-2𝒆^{-\sqrt{𝒙}}\Big]_{𝒄}^{1}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒄\to 0^{+}}\Big[-2𝒆^{-1}+2𝒆^{-\sqrt{𝒄}}\Big]$
          $\rule{0pt}{}$
          ○ $=-\dfrac{2}{𝒆}+2$
          $\rule{0pt}{}$
     ◉ 6. Evaluate the second improper piece.
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{𝒃\to\infty}\Big[-2𝒆^{-\sqrt{𝒙}}\Big]_{1}^{𝒃}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒃\to\infty}\Big[-2𝒆^{-\sqrt{𝒃}}+2𝒆^{-1}\Big]$
          $\rule{0pt}{}$
          ○ $=0+\dfrac{2}{𝒆}$
          $\rule{0pt}{}$
     ◉ 7. Add both results.
          $\rule{0pt}{}$
          ○ $\left(-\dfrac{2}{𝒆}+2\right)+\dfrac{2}{𝒆}=2$
          $\rule{0pt}{}$
     ◉ Final result.
          ○ The integral **converges**.
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{0}^{\infty}\dfrac{𝒆^{-\sqrt{𝒙}}}{\sqrt{𝒙}}\cdot 𝒅𝒙=2$
    





Ｃｏｍｐａｒｉｓｏｎ　Ｔｈｅｏｒｅｍ

● [2:27:00](https://www.youtube.com/watch?v=g-M8FHslgdk&t=8820). Comparison Theorem for improper integrals. [📷image](../img/Calculus 2 Lecture 7.6/[2-27-00]-01.png)
     ◉ Setup:
          $\rule{0pt}{}$
          ○ Assume $0\le 𝒈(𝒙)\le 𝒇(𝒙)$ on $[𝒂,\infty)$.
          $\rule{0pt}{}$
          ○ So $𝒇(𝒙)$ is above $𝒈(𝒙)$ on the interval.
     ◉ Fundamental comparison:
          $\rule{0pt}{}$
          ○ If $\displaystyle \int_{𝒂}^{\infty} 𝒇(𝒙)\cdot 𝒅𝒙$ converges,
          $\rule{0pt}{}$
          ○ then $\displaystyle \int_{𝒂}^{\infty} 𝒈(𝒙)\cdot 𝒅𝒙$ also converges.
          $\rule{0pt}{}$
          ○ Intuition:
               ■ if the bigger area is finite,
               ■ then the smaller area must also be finite.
     ◉ Reverse comparison:
          $\rule{0pt}{}$
          ○ If $\displaystyle \int_{𝒂}^{\infty} 𝒈(𝒙)\cdot 𝒅𝒙$ diverges,
          $\rule{0pt}{}$
          ○ then $\displaystyle \int_{𝒂}^{\infty} 𝒇(𝒙)\cdot 𝒅𝒙$ also diverges.
          $\rule{0pt}{}$
          ○ Intuition:
               ■ if the smaller area is already infinite,
               ■ then the bigger area must also be infinite.
     ◉ Important conditions:
          ○ The comparison is stated for nonnegative functions.
          ○ That is why we require $0\le 𝒈(𝒙)\le 𝒇(𝒙)$.
     ◉ Important warning:
          ○ The implications only work in these directions.
          ○ You may conclude:
               ■ bigger converges ⇒ smaller converges
               ■ smaller diverges ⇒ bigger diverges
          ○ But you may not conclude:
               ■ smaller converges ⇒ bigger converges
               ■ bigger diverges ⇒ smaller diverges
     ◉ Main idea:
          ○ Instead of integrating a difficult function directly,
          ○ compare it with a simpler function whose improper behavior is already known.
     



          

Ｅｘａｍｐｌｅ　Ｏｆ　Ｔｈｅ　Ｃｏｍｐａｒｉｓｏｎ　Ｔｅｓｔ

● [2:35:00](https://www.youtube.com/watch?v=g-M8FHslgdk&t=9300). 🧩 Example 11 — Comparison test: $\displaystyle \int_{1}^{\infty}\dfrac{1}{𝒙+\sin^{2}𝒙}\cdot 𝒅𝒙$ [📷image](../img/Calculus 2 Lecture 7.6/[2-35-00]-01.png)
     ◉ Goal:
          ○ Apply the Comparison Test to determine whether
               $\rule{0pt}{}$
               ■ $\displaystyle \int_{1}^{\infty}\dfrac{1}{𝒙+\sin^{2}𝒙}\cdot 𝒅𝒙$
               $\rule{0pt}{}$
               ■ converges or diverges.
     ◉ Comparison function:
          ○ Compare it with
               $\rule{0pt}{}$
               ■ $\displaystyle \int_{1}^{\infty}\dfrac{1}{1+𝒙}\cdot 𝒅𝒙$
               $\rule{0pt}{}$
     ◉ Key inequality:
          ○ Since $\sin(𝒙)\le 1$,
               ■ then $\sin^{2}(𝒙)\le 1$
          ○ Adding $𝒙$ to both sides gives:
               $\rule{0pt}{}$
               ■ $𝒙+\sin^{2}(𝒙)\le 𝒙+1$
               $\rule{0pt}{}$
          ○ Taking reciprocals reverses the inequality:
               $\rule{0pt}{}$
               ■ $\dfrac{1}{𝒙+\sin^{2}𝒙}\ge \dfrac{1}{1+𝒙}$
               $\rule{0pt}{}$
     ◉ Why this is useful:
          ○ The integrand is nonnegative.
          ○ It is bigger than a simpler function whose improper integral is already known.
     ◉ Check the comparison integral:
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{1}^{\infty}\dfrac{1}{1+𝒙}\cdot 𝒅𝒙$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒃\to\infty}\int_{1}^{𝒃}\dfrac{1}{1+𝒙}\cdot 𝒅𝒙$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒃\to\infty}\Big[\ln|1+𝒙|\Big]_{1}^{𝒃}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{𝒃\to\infty}\Big[\ln(1+𝒃)-\ln(2)\Big]$
          $\rule{0pt}{}$
          ○ $=\infty$
     ◉ Conclusion by comparison:
          ○ Because
               $\rule{0pt}{}$
               ■ $\dfrac{1}{𝒙+\sin^{2}𝒙}\ge \dfrac{1}{1+𝒙}$
               $\rule{0pt}{}$
          ○ and
               $\rule{0pt}{}$
               ■ $\displaystyle \int_{1}^{\infty}\dfrac{1}{1+𝒙}\cdot 𝒅𝒙$ diverges,
               $\rule{0pt}{}$
          ○ it follows from the Comparison Test that
               $\rule{0pt}{}$
               ■ $\displaystyle \int_{1}^{\infty}\dfrac{1}{𝒙+\sin^{2}𝒙}\cdot 𝒅𝒙$ also diverges.
               $\rule{0pt}{}$
     ◉ Final result:
          ○ The integral is **divergent**.
     ◉ NOTE:
          ○ Recall the algebra of inequalities for positive quantities:
               $\rule{0pt}{}$
               ■ If $0<𝒇(𝒙)\le 𝒈(𝒙)$, then $\dfrac{1}{𝒇(𝒙)}\ge \dfrac{1}{𝒈(𝒙)}$.
               $\rule{0pt}{}$
          ○ In words:
               ■ a smaller positive denominator gives a larger fraction,
               ■ and a larger positive denominator gives a smaller fraction.
          ○ This is why, from
               $\rule{0pt}{}$
               ■ $𝒙+\sin^{2}(𝒙)\le 1+𝒙$,
               $\rule{0pt}{}$
          ○ we may conclude that
               $\rule{0pt}{}$
               ■ $\dfrac{1}{𝒙+\sin^{2}𝒙}\ge \dfrac{1}{1+𝒙}$.     






Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Improper Integrals
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/3-7-improper-integrals)
● Comparison Tests
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/5-4-comparison-tests)
● Basic Functions and Identities
     ◉ [openstax🌐](https://openstax.org/books/precalculus-2e/pages/a-basic-functions-and-identities)