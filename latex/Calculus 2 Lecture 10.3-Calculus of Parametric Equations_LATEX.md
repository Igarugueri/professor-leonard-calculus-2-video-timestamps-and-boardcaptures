-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ １０．３： Ｃａｌｃｕｌｕｓ ｏｆ Ｐａｒａｍｅｔｒｉｃ Ｅｑｕａｔｉｏｎｓ**-------------------------------—





１ - Ｌｏｃａｌ　Ｆｕｎｃｔｉｏｎ　Ｎｅｉｇｈｂｏｒｈｏｏｄ　＆　Ｓｅｔｕｐ　ｆｏｒ　ｔｈｅ　Ｓｌｏｐｅ　Ｆｏｒｍｕｌａ

● [📷image-1](../img/Calculus 2 Lecture 10.3/[0-00]-01.png)  [📷image-2](../img/Calculus 2 Lecture 10.3/[0-00]-02.png)


● [0:00](https://www.youtube.com/watch?v=1H6HrfX_qCA&t=0). Introduction: Calculus with Parametric Equations.
     ◉ Goal:
          ○ Find the slope of a parametric curve at a specific point $P$
     ◉ Main idea:
          ○ A parametric curve may fail the vertical line test globally,
          ○ but near a specific point $P$, we can cut out a small section where the curve behaves like a function
     ◉ Function neighborhood:
          ○ A small local piece of the curve around $P$
          ○ on this small section, the vertical line test is satisfied
     ◉ Important:
          ○ The tangent line is understood locally, on this function neighborhood


● [4:10](https://www.youtube.com/watch?v=1H6HrfX_qCA&t=250). Parametric components of the curve.
     ◉ The curve is given parametrically by:
          ○ $𝒙=𝒇(𝑻)$
          ○ $𝒚=𝒈(𝑻)$
     ◉ The parameter varies on a local interval:
          ○ $𝑻\in \mathcal{I}=[𝒂,𝒃]$
     ◉ Meaning:
          ○ The endpoints of this interval determine the beginning and end of the small section we are studying around $P$


● [6:55](https://www.youtube.com/watch?v=1H6HrfX_qCA&t=415). Defining a local rectangular function.
     ◉ On this small section of the curve, we can treat $𝒚$ as a function of $𝒙$:
          ○ $𝒚=\mathcal{F}(𝒙)$
     ◉ This local function is consistent with the original parametric equations:
          ○ $𝒙=𝒇(𝑻)$
          ○ $𝒚=𝒈(𝑻)$
     ◉ Therefore:
          ○ $𝒈(𝑻)=\mathcal{F}(𝒇(𝑻))$
     ◉ This is the key setup:
          ○ now we can differentiate using the Chain Rule




２ - Ｄｅｒｉｖａｔｉｏｎ　ｏｆ　ｔｈｅ　Ｆｉｒｓｔ　Ｄｅｒｉｖａｔｉｖｅ　Ｆｏｒｍｕｌａ

● [📷image](../img/Calculus 2 Lecture 10.3/[11-09]-01.png)

● [11:09](https://www.youtube.com/watch?v=1H6HrfX_qCA&t=669). Derivation of the first derivative formula.
     ◉ On the small function neighborhood around $P$:
          ○ we can write $𝒚$ as a function of $𝒙$
          ○ $𝒚=\mathcal{F}(𝒙)$
     ◉ Original parametric equations:
          ○ $𝒙=𝒇(𝑻)$
          ○ $𝒚=𝒈(𝑻)$
     ◉ Therefore:
          ○ $𝒈(𝑻)=\mathcal{F}(𝒇(𝑻))$
     ◉ Differentiate with respect to $𝑻$:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝑻}\big[𝒈(𝑻)\big]=\dfrac{𝒅}{𝒅𝑻}\big[\mathcal{F}(𝒇(𝑻))\big]$
     $\rule{0pt}{}$
     ◉ Apply the Chain Rule:
     $\rule{0pt}{}$
          ○ $𝒈'(𝑻)=\mathcal{F}'\big(𝒇(𝑻)\big)\cdot 𝒇'(𝑻)$
     $\rule{0pt}{}$
     ◉ Since $\mathcal{F}'(𝒙)=\dfrac{𝒅𝒚}{𝒅𝒙}$:
     $\rule{0pt}{}$
          ○ $𝒈'(𝑻)=\left(\dfrac{𝒅𝒚}{𝒅𝒙}\right)\cdot 𝒇'(𝑻)$
     $\rule{0pt}{}$
     ◉ Solve for the derivative:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=\dfrac{𝒈'(𝑻)}{𝒇'(𝑻)}$
     $\rule{0pt}{}$
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=\dfrac{\dfrac{𝒅𝒚}{𝒅𝑻}}{\dfrac{𝒅𝒙}{𝒅𝑻}}$
     $\rule{0pt}{}$
     ◉ Meaning:
          ○ the slope of the parametric curve is the ratio of vertical change to horizontal change


● [18:06](https://www.youtube.com/watch?v=1H6HrfX_qCA&t=1086). 🧩 Example 1 — Find the equation of the tangent line for $𝒙=\sec(𝑻)$, $𝒚=\tan(𝑻)$, at $𝑻=\dfrac{\pi}{4}$, with $-\dfrac{\pi}{2}<𝑻<\dfrac{\pi}{2}$.
     ◉ [📷image](../img/Calculus 2 Lecture 10.3/[18-06]-01.png)
     ◉ ❶ Find the point on the curve.
     $\rule{0pt}{}$
          ○ at $𝑻=\dfrac{\pi}{4}$:
               ■ $𝒙=\sec\left(\dfrac{\pi}{4}\right)=\sqrt{2}$
               $\rule{0pt}{}$
               ■ $𝒚=\tan\left(\dfrac{\pi}{4}\right)=1$
               $\rule{0pt}{}$
          ○ so the point is:
          $\rule{0pt}{}$
               ■ $(\sqrt{2},1)$
               $\rule{0pt}{}$
     ◉ ❷ Find the slope.
          ○ use the parametric derivative formula:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅𝒚}{𝒅𝒙}=\dfrac{\dfrac{𝒅𝒚}{𝒅𝑻}}{\dfrac{𝒅𝒙}{𝒅𝑻}}$
               $\rule{0pt}{}$
          ○ differentiate:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅𝒚}{𝒅𝑻}=\sec^{2}(𝑻)$
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅𝒙}{𝒅𝑻}=\sec(𝑻)\tan(𝑻)$
               $\rule{0pt}{}$
          ○ substitute:
     $\rule{0pt}{}$
               ■ $\dfrac{𝒅𝒚}{𝒅𝒙}=\dfrac{\sec^{2}(𝑻)}{\sec(𝑻)\tan(𝑻)}$
     $\rule{0pt}{}$
               ■ $\dfrac{𝒅𝒚}{𝒅𝒙}=\dfrac{\sec(𝑻)}{\tan(𝑻)}$
               $\rule{0pt}{}$
          ○ evaluate at $𝑻=\dfrac{\pi}{4}$:
     $\rule{0pt}{}$
               ■ $𝒎=\dfrac{\sec\left(\dfrac{\pi}{4}\right)}{\tan\left(\dfrac{\pi}{4}\right)}$
     $\rule{0pt}{}$
               ■ $𝒎=\dfrac{\sqrt{2}}{1}=\sqrt{2}$
               $\rule{0pt}{}$
     ◉ ❸ Use point-slope form.
     $\rule{0pt}{}$
          ○ $𝒚-𝒚_{1}=𝒎(𝒙-𝒙_{1})$
          $\rule{0pt}{}$
          ○ $𝒚-1=\sqrt{2}(𝒙-\sqrt{2})$
          $\rule{0pt}{}$
     ◉ ❹ Simplify.
     $\rule{0pt}{}$
          ○ $𝒚-1=\sqrt{2}𝒙-2$
          $\rule{0pt}{}$
          ○ $𝒚=\sqrt{2}𝒙-1$
          $\rule{0pt}{}$
     ◉ Final result:
          ○ $𝒚=\sqrt{2}𝒙-1$





３ -  Ｈｏｒｉｚｏｎｔａｌ　ａｎｄ　Ｖｅｒｔｉｃａｌ　Ｔａｎｇｅｎｔｓ

● [28:46](https://www.youtube.com/watch?v=1H6HrfX_qCA&t=1726). Criteria for horizontal and vertical tangents.
     ◉ [📷image](../img/Calculus 2 Lecture 10.3/[28-46]-01.png)
     ◉ Horizontal tangent:
          $\rule{0pt}{}$
          ○ i̲f̲ $\dfrac{𝒅𝒚}{𝒅𝒕}=0$ and $\dfrac{𝒅𝒙}{𝒅𝒕}\neq 0$
          $\rule{0pt}{}$
               ■ t̲h̲e̲n̲ $\dfrac{𝒅𝒚}{𝒅𝒙}=0$
               $\rule{0pt}{}$
     ◉ Vertical tangent:
          $\rule{0pt}{}$
          ○ i̲f̲ $\dfrac{𝒅𝒚}{𝒅𝒕}\neq 0$ and $\dfrac{𝒅𝒙}{𝒅𝒕}=0$
          $\rule{0pt}{}$
               ■ t̲h̲e̲n̲ $\dfrac{𝒅𝒚}{𝒅𝒙}\to \pm\infty$
               $\rule{0pt}{}$
     ◉ Warning:
          $\rule{0pt}{}$
          ○ i̲f̲ $\dfrac{𝒅𝒚}{𝒅𝒕}=0$ and $\dfrac{𝒅𝒙}{𝒅𝒕}=0$
          $\rule{0pt}{}$
               ■ t̲h̲e̲n̲ the slope is indeterminate
               ■ this requires L’Hôpital’s Rule


● [33:42](https://www.youtube.com/watch?v=1H6HrfX_qCA&t=2022). 🧩 Example 2 — Horizontal and vertical tangents: $𝒙=𝒕^{2}$, $𝒚=𝒕^{3}-3𝒕$.
     ◉ [📷image-1](../img/Calculus 2 Lecture 10.3/[33-42]-01.png)  [📷image-2](../img/Calculus 2 Lecture 10.3/[33-42]-02.png)
     ◉ ❶ Locate horizontal tangents.
     $\rule{0pt}{}$
          ○ set $\dfrac{𝒅𝒚}{𝒅𝒕}=0$
          $\rule{0pt}{}$
          ○ $3𝒕^{2}-3=0$
          ○ $𝒕=\pm 1$
          ○ corresponding points:
               ■ $𝒕=-1$  →  $(𝒙,𝒚)=(1,2)$
               ■ $𝒕=1$   →  $(𝒙,𝒚)=(1,-2)$
     ◉ ❷ Locate the vertical tangent.
     $\rule{0pt}{}$
          ○ set $\dfrac{𝒅𝒙}{𝒅𝒕}=0$
          $\rule{0pt}{}$
          ○ $2𝒕=0$
          ○ $𝒕=0$
          ○ corresponding point:
               ■ $𝒕=0$  →  $(𝒙,𝒚)=(0,0)$
     ◉ ❸ Find the intercepts.
          ○ For the $𝒙$-intercepts, set $𝒚=0$:
               ■ $𝒕^{3}-3𝒕=0$
               ■ $𝒕(𝒕^{2}-3)=0$
               ■ $𝒕=0,\pm \sqrt{3}$
               ■ corresponding points:
                    ▣ $𝒕=0$     →  $(0,0)$
                    ▣ $𝒕=\sqrt{3}$    →  $(3,0)$
                    ▣ $𝒕=-\sqrt{3}$   →  $(3,0)$
          ○ For the $𝒚$-intercept, set $𝒙=0$:
               ■ $𝒕^{2}=0$
               ■ $𝒕=0$
               ■ corresponding point:
                    ▣ $(0,0)$
     ◉ ❹ Determine where the curve starts and ends.
          ○ i̲f̲ $𝒕\to -\infty$,
               ■ t̲h̲e̲n̲ $𝒙=𝒕^{2}\to \infty$ and $𝒚=𝒕^{3}-3𝒕\to -\infty$
               ■ so the curve starts in the lower-right part of the plane
          ○ i̲f̲ $𝒕\to \infty$,
               ■ t̲h̲e̲n̲ $𝒙=𝒕^{2}\to \infty$ and $𝒚=𝒕^{3}-3𝒕\to \infty$
               ■ so the curve ends in the upper-right part of the plane
     ◉ ❺ Determine the orientation.
          ○ as $𝒕$ increases, the curve starts in the lower-right branch
          ○ passes through $(3,0)$
          ○ reaches the horizontal tangent at $(1,2)$
          ○ moves to the vertical tangent at $(0,0)$
          ○ reaches the horizontal tangent at $(1,-2)$
          ○ passes again through $(3,0)$
          ○ and then continues to the upper-right branch
     ◉ Important:
          ○ two different parameter values, $𝒕=\pm \sqrt{3}$, give the same point $(3,0)$
          ○ so the curve passes through $(3,0)$ twice
     ◉ Final interpretation:
          ○ the curve has a loop
          ○ it has horizontal tangents at $(1,2)$ and $(1,-2)$
          ○ it has a vertical tangent at $(0,0)$
          ○ and the direction is determined by the start at $𝒕\to -\infty$ and the end at $𝒕\to \infty$





４  -  Ｓｅｃｏｎｄ　Ｄｅｒｉｖａｔｉｖｅ　ｆｏｒ　Ｐａｒａｍｅｔｒｉｃ　Ｃｕｒｖｅｓ

● [📷image](../img/Calculus 2 Lecture 10.3/[51-32]-01.png)


● [51:32](https://www.youtube.com/watch?v=1H6HrfX_qCA&t=3092). Derivation of the second derivative formula.
     ◉ Start with the first derivative formula:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=\dfrac{\dfrac{𝒅𝒚}{𝒅𝑻}}{\dfrac{𝒅𝒙}{𝒅𝑻}}$
     $\rule{0pt}{}$
     ◉ Differentiate with respect to $𝒙$:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\left[\dfrac{𝒅𝒚}{𝒅𝒙}\right]=\dfrac{𝒅}{𝒅𝒙}\left[\dfrac{\dfrac{𝒅𝒚}{𝒅𝑻}}{\dfrac{𝒅𝒙}{𝒅𝑻}}\right]$
     $\rule{0pt}{}$
     ◉ Therefore:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅^{2}𝒚}{𝒅𝒙^{2}}=\dfrac{𝒅}{𝒅𝒙}\left[\dfrac{𝒅𝒚}{𝒅𝒙}\right]$
          $\rule{0pt}{}$
     ◉ Use the parametric derivative rule again:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}[𝔂]=\dfrac{\dfrac{𝒅}{𝒅𝑻}[𝔂]}{\dfrac{𝒅𝒙}{𝒅𝑻}}$
     $\rule{0pt}{}$
     ◉ Apply it to $𝔂=\dfrac{𝒅𝒚}{𝒅𝒙}$:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅^{2}𝒚}{𝒅𝒙^{2}}=\dfrac{\dfrac{𝒅}{𝒅𝑻}\left[\dfrac{𝒅𝒚}{𝒅𝒙}\right]}{\dfrac{𝒅𝒙}{𝒅𝑻}}$
     $\rule{0pt}{}$
     ◉ Final result:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅^{2}𝒚}{𝒅𝒙^{2}}=\dfrac{\dfrac{𝒅}{𝒅𝑻}\left[\dfrac{𝒅𝒚}{𝒅𝒙}\right]}{\dfrac{𝒅𝒙}{𝒅𝑻}}$
     $\rule{0pt}{}$
     ◉ Important:
          ○ this is not simply $\dfrac{\dfrac{𝒅^{2}𝒚}{𝒅𝑻^{2}}}{\dfrac{𝒅^{2}𝒙}{𝒅𝑻^{2}}}$
     ◉ Meaning:
          ○ this formula is used to study concavity for a parametric curve


● [59:48](https://www.youtube.com/watch?v=1H6HrfX_qCA&t=3588). 🧩 Example 3 — Find the concavity for $𝒙=𝑻^{2}-4$, $𝒚=𝑻^{3}-3𝑻$.
     ◉ [📷image](../img/Calculus 2 Lecture 10.3/[59-48]-01.png)
     ◉ ❶ Start with the first derivative.
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=\dfrac{3𝑻^{2}-3}{2𝑻}$
     $\rule{0pt}{}$
     ◉ ❷ Differentiate $\dfrac{𝒅𝒚}{𝒅𝒙}$ with respect to $𝑻$.
          ○ use the Quotient Rule
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝑻}\left[\dfrac{𝒅𝒚}{𝒅𝒙}\right]=\dfrac{𝒅}{𝒅𝑻}\left[\dfrac{3𝑻^{2}-3}{2𝑻}\right]$
     $\rule{0pt}{}$
          ○ $=\dfrac{2𝑻\cdot 6𝑻-2(3𝑻^{2}-3)}{4𝑻^{2}}$
          $\rule{0pt}{}$
          ○ $=\dfrac{12𝑻^{2}-6𝑻^{2}+6}{4𝑻^{2}}$
          $\rule{0pt}{}$
          ○ $=\dfrac{6𝑻^{2}+6}{4𝑻^{2}}$
          $\rule{0pt}{}$
          ○ $=\dfrac{3𝑻^{2}+3}{2𝑻^{2}}$
          $\rule{0pt}{}$
     ◉ ❸ Divide by $\dfrac{𝒅𝒙}{𝒅𝑻}$.
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒙}{𝒅𝑻}=2𝑻$
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅^{2}𝒚}{𝒅𝒙^{2}}=\dfrac{\dfrac{𝒅}{𝒅𝑻}\left(\dfrac{𝒅𝒚}{𝒅𝒙}\right)}{\dfrac{𝒅𝒙}{𝒅𝑻}}$
     $\rule{0pt}{}$
          ○ $=\dfrac{\dfrac{3𝑻^{2}+3}{2𝑻^{2}}}{2𝑻}$
          $\rule{0pt}{}$
     ◉ Final result:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅^{2}𝒚}{𝒅𝒙^{2}}=\dfrac{3𝑻^{2}+3}{4𝑻^{3}}$
     $\rule{0pt}{}$




５．Ａｐｐｌｉｃａｔｉｏｎｓ


５．１ - Ａｒｃ　Ｌｅｎｇｔｈ

● [📷image](../img/Calculus 2 Lecture 10.3/[1-07-09]-01.png)


● [1-07:09](https://www.youtube.com/watch?v=1H6HrfX_qCA&t=4029). Length of a curve (arc length).
     ◉ From Calc 1:
          ○ i̲f̲ $𝒚=𝒇(𝒙)$,
               ■ t̲h̲e̲n̲ the length of the curve from $𝒙=𝒂$ to $𝒙=𝒃$ is
     $\rule{0pt}{}$
                    ▣ $\displaystyle 𝑳=\int_{𝒂}^{𝒃}\sqrt{1+\big[𝒇'(𝒙)\big]^{2}}\,𝒅𝒙$
     $\rule{0pt}{}$
     ◉ Parametrically:
          ○ now we do the same idea using $𝒙$ and $𝒚$ as functions of $𝒕$
     ◉ Conditions:
          ○ provided the part of the curve whose length we want to find
               ■ is smooth
               ■ and does not intersect itself
     ◉ Smooth means:
          ○ no gaps
          ○ no sharp points
     ◉ Important:
          ○ the curve should not double back on itself
          ○ otherwise we lose the nice local behavior needed for the formula
     ◉ Goal:
          ○ find the total distance traveled along the parametric curve from $𝒕=𝒂$ to $𝒕=𝒃$
     ◉ Formula:
     $\rule{0pt}{}$
          ○ $\displaystyle 𝑳=\int_{𝒂}^{𝒃}\sqrt{\left(\dfrac{𝒅𝒙}{𝒅𝒕}\right)^{2}+\left(\dfrac{𝒅𝒚}{𝒅𝒕}\right)^{2}}\,𝒅𝒕$
     $\rule{0pt}{}$
     ◉ Important:
          ○ the bounds $𝒂$ and $𝒃$ are values of the parameter $𝒕$
          ○ the integration is always with respect to $𝒕$
     ◉ How to read the formula:
     $\rule{0pt}{}$
          ○ take $\dfrac{𝒅𝒙}{𝒅𝒕}$ and square it
          $\rule{0pt}{}$
          ○ take $\dfrac{𝒅𝒚}{𝒅𝒕}$ and square it
          $\rule{0pt}{}$
          ○ add them
          ○ take the square root
          ○ then integrate over the parameter interval
     ◉ Main idea:
          ○ this looks very similar to the Calc 1 arc-length formula
          ○ and it also resembles the distance formula
     ◉ Meaning:
          ○ integrate the magnitude of the velocity vector over the parameter interval


● [1:13:45](https://www.youtube.com/watch?v=1H6HrfX_qCA&t=4425). 🧩 Example 4 — Arc length calculation: $𝒙=2𝑻^{2}$, $𝒚=3𝑻^{3}$, on $0\le 𝑻\le 1$.
     ◉ [📷image-1](../img/Calculus 2 Lecture 10.3/[1-13-45]-01.png) [📷image-2](../img/Calculus 2 Lecture 10.3/[1-13-45]-02.png)
     ◉ ❶ Find the derivatives.
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒙}{𝒅𝑻}=4𝑻$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝑻}=9𝑻^{2}$
          $\rule{0pt}{}$
     ◉ ❷ Set up the arc length integral.
     $\rule{0pt}{}$
          ○ $\displaystyle 𝑳=\int_{0}^{1}\sqrt{(4𝑻)^{2}+(9𝑻^{2})^{2}}\,𝒅𝑻$
     $\rule{0pt}{}$
     ◉ ❸ Simplify the expression.
     $\rule{0pt}{}$
          ○ $\displaystyle 𝑳=\int_{0}^{1}\sqrt{16𝑻^{2}+81𝑻^{4}}\,𝒅𝑻$
     $\rule{0pt}{}$
     $\rule{0pt}{}$
          ○ $\displaystyle 𝑳=\int_{0}^{1}\sqrt{𝑻^{2}(16+81𝑻^{2})}\,𝒅𝑻$
     $\rule{0pt}{}$
     $\rule{0pt}{}$
          ○ $\displaystyle 𝑳=\int_{0}^{1}𝑻\sqrt{16+81𝑻^{2}}\,𝒅𝑻$
     $\rule{0pt}{}$
     ◉ ❹ Use $𝒖$-substitution.
          ○ let $𝒖=16+81𝑻^{2}$
          ○ $𝒅𝒖=162𝑻\,𝒅𝑻$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{162}𝒅𝒖=𝑻\,𝒅𝑻$
          $\rule{0pt}{}$
          ○ change the bounds:
               ■ $𝑻=0$  →  $𝒖=16$
               ■ $𝑻=1$  →  $𝒖=97$
     ◉ ❺ Rewrite and evaluate the integral.
     $\rule{0pt}{}$
          ○ $\displaystyle 𝑳=\dfrac{1}{162}\int_{16}^{97}𝒖^{1/2}\,𝒅𝒖$
     $\rule{0pt}{}$
     $\rule{0pt}{}$
          ○ $\displaystyle 𝑳=\dfrac{1}{162}\cdot \Big[\dfrac{𝒖^{3/2}}{3/2}\Big]_{16}^{97}$
     $\rule{0pt}{}$
     $\rule{0pt}{}$
          ○ $\displaystyle 𝑳=\Big[\dfrac{𝒖^{3/2}}{243}\Big]_{16}^{97}$
     $\rule{0pt}{}$
     $\rule{0pt}{}$
          ○ $\displaystyle 𝑳=\dfrac{97^{3/2}-16^{3/2}}{243}$
     $\rule{0pt}{}$
     ◉ Final result:
     $\rule{0pt}{}$
          ○ $\displaystyle 𝑳=\dfrac{97^{3/2}-16^{3/2}}{243}$
          $\rule{0pt}{}$
     ◉ Final interpretation:
          ○ the total distance traveled is approximately $3.67$ units




５．２  -  Ｓｕｒｆａｃｅ　Ａｒｅａ　ｏｆ　Ｒｅｖｏｌｕｔｉｏｎ

● [📷image](../img/Calculus 2 Lecture 10.3/[1-26-22]-01.png)

● [1:26:22](https://www.youtube.com/watch?v=1H6HrfX_qCA&t=5182). Surface area of revolution.
     ◉ From Calc 1:
          ○ around the $𝒙$-axis:
     $\rule{0pt}{}$
               ■ $\displaystyle \mathcal{S}=\int_{𝒂}^{𝒃}2\pi\,𝒇(𝒙)\sqrt{1+\big[𝒇'(𝒙)\big]^{2}}\,𝒅𝒙$
     $\rule{0pt}{}$
          ○ around the $𝒚$-axis:
     $\rule{0pt}{}$
               ■ $\displaystyle \mathcal{S}=\int_{𝒂}^{𝒃}2\pi\,𝒈(𝒚)\sqrt{1+\big[𝒈'(𝒚)\big]^{2}}\,𝒅𝒚$
     $\rule{0pt}{}$
     ◉ Parametrically:
          ○ use the same arc-length factor as before
          ○ only the radius of revolution changes depending on the axis
     ◉ Main idea:
          ○ circumference of the circular cross section × arc length element
     ◉ Around the $𝒙$-axis:
          ○ the radius is $𝒚$
     $\rule{0pt}{}$
          ○ $\displaystyle \mathcal{S}=\int_{𝒂}^{𝒃}2\pi\,𝒚\sqrt{\left(\dfrac{𝒅𝒙}{𝒅𝒕}\right)^{2}+\left(\dfrac{𝒅𝒚}{𝒅𝒕}\right)^{2}}\,𝒅𝒕$
     $\rule{0pt}{}$
     ◉ Around the $𝒚$-axis:
          ○ the radius is $𝒙$
     $\rule{0pt}{}$
          ○ $\displaystyle \mathcal{S}=\int_{𝒂}^{𝒃}2\pi\,𝒙\sqrt{\left(\dfrac{𝒅𝒙}{𝒅𝒕}\right)^{2}+\left(\dfrac{𝒅𝒚}{𝒅𝒕}\right)^{2}}\,𝒅𝒕$
     $\rule{0pt}{}$
     ◉ Important:
          ○ the square-root factor is the same in both formulas
          ○ because the length element of the curve does not change
          ○ only the radius changes:
               ■ around the $𝒙$-axis → use $𝒚$
               ■ around the $𝒚$-axis → use $𝒙$




Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Parametric equations, polar coordinates, and vector-valued functions
     ◉ [Khan Academy🌐](https://www.khanacademy.org/math/ap-calculus-bc/bc-advanced-functions-new)

● Parametric Equations and Curves
     ◉ [Paul's Online 🌐](https://tutorial.math.lamar.edu/Classes/CalcII/ParametricEqn.aspx)