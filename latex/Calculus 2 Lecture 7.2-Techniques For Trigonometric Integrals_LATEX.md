-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ７．２ － Ｔｅｃｈｎｉｑｕｅｓ Ｆｏｒ Ｔｒｉｇｏｎｏｍｅｔｒｉｃ Ｉｎｔｅｇｒａｌｓ**---------------------------------




Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:01](https://www.youtube.com/watch?v=pLrUBjiEo-w&t=1). Introduction to Section 7.2: Techniques for Trigonometric Integrals.
     ◉ Continuation of the previous section on trigonometric integration.
     ◉ Focus on products of powers of sine and cosine, and later on tangent/secant and cotangent/cosecant.




     
Ｓｉｎｅ–Ｃｏｓｉｎｅ Ｐａｔｔｅｒｎｓ

● [1:03](https://www.youtube.com/watch?v=pLrUBjiEo-w&t=63). Case analysis for integrals of the form $\displaystyle \int \sin^{m}(𝒙)\cos^{n}(𝒙)\,𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.2/[1-03]-01.png)
     ◉ Two cases:
          ○ Case 1: $m$ and/or $n$ is odd.
          ○ Case 2: $m$ and $n$ are even.
     ◉ Case 1: At least one power is odd.
          ○ If the power of $\sin(𝒙)$ is odd:
               ■ Keep one factor of $\sin(𝒙)$.
               ■ Use the Pythagorean identity to change $\sin^{2}(𝒙)=1-\cos^{2}(𝒙)$.
          ○ If the power of $\cos(𝒙)$ is odd:
               ■ Do the same for $\cos(𝒙)$.
               $\rule{0pt}{}$
               ■ Use $\cos^{2}(𝒙)=1-\sin^{2}(𝒙)$.
               $\rule{0pt}{}$
          ○ If both powers are odd:
               ■ Pick the one that will give power $2$, if possible.
     ◉ Case 2: Both powers are even.
          ○ Use the half-angle identities:
          $\rule{0pt}{}$
               ■ $\sin^{2}(𝒙)=\left(\dfrac{1}{2}\right)(1-\cos(2𝒙))$
          $\rule{0pt}{}$
               ■ $\cos^{2}(𝒙)=\left(\dfrac{1}{2}\right)(1+\cos(2𝒙))$
          $\rule{0pt}{}$
          ○ Go to this link  [openstax🌐](https://openstax.org/books/precalculus-2e/pages/7-3-double-angle-half-angle-and-reduction-formulas)
     ◉ NOTE:
          ○ The labels “odd” and “even” apply only to integer powers.
          ○ A fractional exponent such as $\dfrac{1}{2}$ is neither odd nor even.
          ○ In those cases, use the rule based on the other exponent, if that one is an integer odd or even power.




 
               
Ｅｘａｍｐｌｅｓ — Ｓｉｎｅ ａｎｄ Ｃｏｓｉｎｅ

● [9:47](https://www.youtube.com/watch?v=pLrUBjiEo-w&t=587). 🧩 Example 1 — Both powers odd: $\displaystyle \int \cos^{3}(2𝒙)\sin^{5}(2𝒙)\,𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.2/[9-47]-01.png)
     ◉ Case 1: both powers are odd.
          ○ Pick the smaller odd power so as to obtain a squared factor.
          ○ Strip off one factor of $\cos(2𝒙)$.
     ◉ Rewrite the integrand:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \cos^{2}(2𝒙)\sin^{5}(2𝒙)\cos(2𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Use the Pythagorean identity:
          $\rule{0pt}{}$
          ○ $\cos^{2}(2𝒙)=1-\sin^{2}(2𝒙)$
          $\rule{0pt}{}$
          ○ $\displaystyle \int [1-\sin^{2}(2𝒙)]\sin^{5}(2𝒙)\cos(2𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Simple substitution:
          $\rule{0pt}{}$
          ○ $𝒖=\sin(2𝒙)$
          $\rule{0pt}{}$
          ○ $𝒅𝒖=2\cos(2𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒖}{2}=\cos(2𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Polynomial integral in 𝒖:
          $\rule{0pt}{}$
          ○ $\displaystyle \int (1-𝒖^{2})𝒖^{5}\,\dfrac{𝒅𝒖}{2}$
          $\rule{0pt}{}$
          ○ $=\left(\dfrac{1}{2}\right)\displaystyle \int (𝒖^{5}-𝒖^{7})\,𝒅𝒖$
          $\rule{0pt}{}$
          ○ $=\left(\dfrac{1}{2}\right)\Big[𝒖^{6}/6-𝒖^{8}/8\Big]$
          $\rule{0pt}{}$
     ◉ Final result:
          $\rule{0pt}{}$
          ○ $\left(\dfrac{1}{12}\right)\sin^{6}(2𝒙)-\left(\dfrac{1}{16}\right)\sin^{8}(2𝒙)+𝓒$
          
● [19:11](https://www.youtube.com/watch?v=pLrUBjiEo-w&t=1151). 🧩 Example 2 —  At least one power is odd: Evaluate $\displaystyle \int \sin^{3}(𝒙)\cos^{2}(𝒙)\,𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.2/[19-11]-01.png)
     ◉ The power of sine is odd.Strip off one factor of $\sin(𝒙)$.
     ◉ Convert $\sin^{2}(𝒙)$ into $1-\cos^{2}(𝒙)$.
     ◉ Substitution:
          $\rule{0pt}{}$
          ○ $𝒖=\cos(𝒙)$
          $\rule{0pt}{}$
     ◉ Resulting polynomial integral in 𝒖.
     ◉ Final result:
          $\rule{0pt}{}$
          ○ $\left(\dfrac{1}{5}\right)\cos^{5}(𝒙)-\left(\dfrac{1}{3}\right)\cos^{3}(𝒙)+𝓒$
          
● [27:37](https://www.youtube.com/watch?v=pLrUBjiEo-w&t=1657). 🧩 Example 3 — Both powers are even: $\displaystyle \int \sin^{4}(𝒙)\cos^{4}(𝒙)\,𝒅𝒙$. [📷image-1](../img/Calculus 2 Lecture 7.2/[27-37]-01.png)  [📷image-2](../img/Calculus 2 Lecture 7.2/[27-37]-02.png)
     ◉ Since both powers are even, use identities instead of the odd-power substitution strategy.
     ◉ Use the double-angle identity:
          $\rule{0pt}{}$
          ○ $\sin(𝒙)\cos(𝒙)=\left(\dfrac{1}{2}\right)\sin(2𝒙)$
          $\rule{0pt}{}$
          ○ So:
               ■ $\displaystyle \int \sin^{4}(𝒙)\cos^{4}(𝒙)\,𝒅𝒙=\displaystyle \int \big[\left(\dfrac{1}{2}\right)\sin(2𝒙)\big]^{4}\,𝒅𝒙$
          $\rule{0pt}{}$
               ■ $=\left(\dfrac{1}{16}\right)\displaystyle \int \sin^{4}(2𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Rewrite the fourth power:
          $\rule{0pt}{}$
          ○ $\left(\dfrac{1}{16}\right)\displaystyle \int \big[\sin^{2}(2𝒙)\big]^{2}\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Use the half-angle identity:
          $\rule{0pt}{}$
          ○ $\sin^{2}(2𝒙)=\left(\dfrac{1}{2}\right)(1-\cos(4𝒙))$
          $\rule{0pt}{}$
          ○ So:
               ■ $\left(\dfrac{1}{16}\right)\displaystyle \int \big[\left(\dfrac{1}{2}\right)(1-\cos(4𝒙))\big]^{2}\,𝒅𝒙$
          $\rule{0pt}{}$
               ■ $=\left(\dfrac{1}{64}\right)\displaystyle \int (1-\cos(4𝒙))^{2}\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Expand the square:
          $\rule{0pt}{}$
          ○ $\left(\dfrac{1}{64}\right)\displaystyle \int [1-2\cos(4𝒙)+\cos^{2}(4𝒙)]\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Apply the half-angle identity again:
          $\rule{0pt}{}$
          ○ $\cos^{2}(4𝒙)=\left(\dfrac{1}{2}\right)(1+\cos(8𝒙))$
          $\rule{0pt}{}$
     ◉ Simplify the integrand:
          $\rule{0pt}{}$
          ○ $\left(\dfrac{1}{64}\right)\displaystyle \int \left[\dfrac{3}{2}-2\cos(4𝒙)+\left(\dfrac{1}{2}\right)\cos(8𝒙)\right]\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Final expanded result:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \sin^{4}(𝒙)\cos^{4}(𝒙)\,𝒅𝒙=\left(\dfrac{3}{128}\right)𝒙-\left(\dfrac{1}{128}\right)\sin(4𝒙)+\left(\dfrac{1}{1024}\right)\sin(8𝒙)+𝓒$
     
● [48:58](https://www.youtube.com/watch?v=pLrUBjiEo-w&t=2938). 🧩 Example 4 — Without using the reduction formula: Evaluate $\displaystyle \int \sin^{6}(𝒙)\,𝒅𝒙$ [📷image-1](../img/Calculus 2 Lecture 7.2/[48-58]-01.png)  [📷image-2](../img/Calculus 2 Lecture 7.2/[48-58]-02.png) [📷image-3](../img/Calculus 2 Lecture 7.2/[48-58]-03.png)  
     ◉ Rewrite the integrand:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \sin^{6}(𝒙)\,𝒅𝒙=\displaystyle \int (\sin^{2}(𝒙))^{3}\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Use the half-angle identity:
          $\rule{0pt}{}$
          ○ $\sin^{2}(𝒙)=\left(\dfrac{1}{2}\right)(1-\cos(2𝒙))$
          $\rule{0pt}{}$
          ○ Therefore:
          $\rule{0pt}{}$
               ■ $\displaystyle \int \sin^{6}(𝒙)\,𝒅𝒙=\displaystyle \int \big[\left(\dfrac{1}{2}\right)(1-\cos(2𝒙))\big]^{3}\,𝒅𝒙$
          $\rule{0pt}{}$
               ■ $=\left(\dfrac{1}{8}\right)\displaystyle \int (1-\cos(2𝒙))^{3}\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Expand the cube using Pascal’s Triangle:
          $\rule{0pt}{}$
          ○ $(1-\cos(2𝒙))^{3}=1-3\cos(2𝒙)+3\cos^{2}(2𝒙)-\cos^{3}(2𝒙)$
          $\rule{0pt}{}$
          ○ So:
               ■ $\left(\dfrac{1}{8}\right)\displaystyle \int [1-3\cos(2𝒙)+3\cos^{2}(2𝒙)-\cos^{3}(2𝒙)]\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Treat the even-power term:
          $\rule{0pt}{}$
          ○ $\cos^{2}(2𝒙)=\left(\dfrac{1}{2}\right)(1+\cos(4𝒙))$
          $\rule{0pt}{}$
     ◉ Treat the odd-power term separately:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \cos^{3}(2𝒙)\,𝒅𝒙=\displaystyle \int (1-\sin^{2}(2𝒙))\cos(2𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ Let $𝒖=\sin(2𝒙)$, so $\dfrac{𝒅𝒖}{2}=\cos(2𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ Then:
          $\rule{0pt}{}$
               ■ $\displaystyle \int \cos^{3}(2𝒙)\,𝒅𝒙=\left(\dfrac{1}{2}\right)\displaystyle \int (1-𝒖^{2})\,𝒅𝒖$
          $\rule{0pt}{}$
               ■ $=\left(\dfrac{1}{2}\right)𝒖-\left(\dfrac{1}{6}\right)𝒖^{3}$
          $\rule{0pt}{}$
               ■ $=\left(\dfrac{1}{2}\right)\sin(2𝒙)-\left(\dfrac{1}{6}\right)\sin^{3}(2𝒙)$
          $\rule{0pt}{}$
     ◉ Combine all terms and simplify.
     ◉ Final result:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \sin^{6}(𝒙)\,𝒅𝒙=\left(\dfrac{5}{16}\right)𝒙-\left(\dfrac{1}{4}\right)\sin(2𝒙)+\left(\dfrac{3}{64}\right)\sin(4𝒙)+\left(\dfrac{1}{48}\right)\sin^{3}(2𝒙)+𝓒$





     
Ｄｅｆｉｎｅｄ Ｉｎｔｅｇｒａｌ Ｅｘａｍｐｌｅ

● [1:11:06](https://www.youtube.com/watch?v=pLrUBjiEo-w&t=4266). 🧩 Example 5 — Definite integral: $\displaystyle \int_{0}^{\pi/2}\sin^{3}(𝒙)\cos^{1/2}(𝒙)\,𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.2/[1-11-06]-01.png)
     ◉ The power of sine is odd, so strip off one factor of $\sin(𝒙)$.
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{0}^{\pi/2}\sin^{2}(𝒙)\cos^{1/2}(𝒙)\cdot \sin(𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Use the Pythagorean identity:
          $\rule{0pt}{}$
          ○ $\sin^{2}(𝒙)=1-\cos^{2}(𝒙)$
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{0}^{\pi/2}(1-\cos^{2}(𝒙))\cos^{1/2}(𝒙)\cdot \sin(𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Substitution:
          $\rule{0pt}{}$
          ○ $𝒖=\cos(𝒙)$
          $\rule{0pt}{}$
          ○ $𝒅𝒖=-\sin(𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $-𝒅𝒖=\sin(𝒙)\,𝒅𝒙$
     ◉ Change the bounds:
          ○ When $𝒙=0$, $𝒖=1$
          ○ When $𝒙=\pi/2$, $𝒖=0$
     ◉ Rewrite the integral in 𝒖:
          $\rule{0pt}{}$
          ○ $-\displaystyle \int_{1}^{0}(1-𝒖^{2})𝒖^{1/2}\,𝒅𝒖$
          $\rule{0pt}{}$
          ○ $=\displaystyle \int_{0}^{1}(𝒖^{1/2}-𝒖^{5/2})\,𝒅𝒖$
          $\rule{0pt}{}$
     ◉ Evaluate:
          $\rule{0pt}{}$
          ○ $\Big[\left(\dfrac{2}{3}\right)𝒖^{3/2}-\left(\dfrac{2}{7}\right)𝒖^{7/2}\Big]_{0}^{1}$
          $\rule{0pt}{}$
          ○ $=\dfrac{2}{3}-\dfrac{2}{7}$
          $\rule{0pt}{}$
     ◉ Final numerical value:
          ○ $\dfrac{8}{21}$





          
Ｔａｎｇｅｎｔ ａｎｄ Ｓｅｃａｎｔ OR Ｃｏｓｅｃａｎｔ ａｎｄ Ｃｏｔａｎｇｅｎｔ


● [1:24:25](https://www.youtube.com/watch?v=pLrUBjiEo-w&t=5065). Integrals involving tangent and secant: $\displaystyle \int \tan^{m}(𝒙)\sec^{n}(𝒙)\,𝒅𝒙$   or   $\displaystyle \int \cot^{m}(𝒙)\csc^{n}(𝒙)\,𝒅𝒙$ [📷image-1](../img/Calculus 2 Lecture 7.2/[1-24-25]-01.png)  [📷image-2](../img/Calculus 2 Lecture 7.2/[1-24-25]-02.png)
     ◉ Rule 1: If the power of $\tan(𝒙)$ or $\cot(𝒙)$ is odd.
          ○ Keep one factor $\sec(𝒙)\tan(𝒙)$.
          $\rule{0pt}{}$
               ■ Analogously: keep one factor $\csc(𝒙)\cot(𝒙)$.
          $\rule{0pt}{}$
          ○ Use:
               ■ $\tan^{2}(𝒙)=\sec^{2}(𝒙)-1$
          $\rule{0pt}{}$
               ■ $\cot^{2}(𝒙)=\csc^{2}(𝒙)-1$
          $\rule{0pt}{}$
     ◉ Rule 2: If the power of $\sec(𝒙)$ or $\csc(𝒙)$ is even.
          ○ Strip off one factor $\sec^{2}(𝒙)$.
          $\rule{0pt}{}$
               ■ Analogously: strip off one factor $\csc^{2}(𝒙)$.
          $\rule{0pt}{}$
          ○ Use:
               ■ $\sec^{2}(𝒙)=\tan^{2}(𝒙)+1$
          $\rule{0pt}{}$
               ■ $\csc^{2}(𝒙)=\cot^{2}(𝒙)+1$
          $\rule{0pt}{}$
    ◉ If both rules apply, both methods are valid.
    ◉ Choose the one that makes the algebra simpler.
    ◉ There is no conflict: it is a choice of convenience.
    ◉ NOTE:
          ○ The labels “odd” and “even” apply only to integer powers.
          ○ A fractional exponent such as $\dfrac{1}{2}$ is neither odd nor even.
          ○ In those cases, use the rule based on the other exponent, if that one is an integer odd or even power.
          
● [1:30:05](https://www.youtube.com/watch?v=pLrUBjiEo-w&t=5405). 🧩 Example 6 — Tangent power odd: $\displaystyle \int \tan^{5}(𝒙)\sec^{3}(𝒙)\,𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.2/[1-30-05]-01.png)
     ◉ The power of tangent is odd.
          ○ Keep one factor $\sec(𝒙)\tan(𝒙)$.
     ◉ Rewrite the integrand:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \tan^{4}(𝒙)\sec^{2}(𝒙)\cdot \sec(𝒙)\tan(𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $=\displaystyle \int (\tan^{2}(𝒙))^{2}\sec^{2}(𝒙)\cdot \sec(𝒙)\tan(𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Use the identity:
          $\rule{0pt}{}$
          ○ $\tan^{2}(𝒙)=\sec^{2}(𝒙)-1$
          $\rule{0pt}{}$
          ○ $\displaystyle \int (\sec^{2}(𝒙)-1)^{2}\sec^{2}(𝒙)\cdot \sec(𝒙)\tan(𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Substitution:
          $\rule{0pt}{}$
          ○ $𝒖=\sec(𝒙)$
          $\rule{0pt}{}$
          ○ $𝒅𝒖=\sec(𝒙)\tan(𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Resulting polynomial integral in 𝒖:
          $\rule{0pt}{}$
          ○ $\displaystyle \int (𝒖^{2}-1)^{2}𝒖^{2}\,𝒅𝒖$
          
● [1:36:39](https://www.youtube.com/watch?v=pLrUBjiEo-w&t=5799). 🧩 Example 7 — Evaluate $\displaystyle \int_{0}^{\pi/4}\sqrt{\tan(𝒙)}\sec^{6}(𝒙)\,𝒅𝒙$. [📷image-1](../img/Calculus 2 Lecture 7.2/[1-36-39]-01.png)  [📷image-2](../img/Calculus 2 Lecture 7.2/[1-36-39]-02.png)
         ◉ Note:
          ○ The exponent $1/2$ is neither odd nor even.
          ○ So the useful pattern comes from $\sec^{6}(𝒙)$, since the secant power is even.
     ◉ Apply Rule 2.
          ○ Strip off one factor $\sec^{2}(𝒙)$.
          ○ Rewrite the remaining secant power:
          $\rule{0pt}{}$
               ■ $\sqrt{\tan(𝒙)}\sec^{6}(𝒙)=(\tan(𝒙))^{1/2}\sec^{4}(𝒙)\cdot \sec^{2}(𝒙)$
          $\rule{0pt}{}$
               ■ $=(\tan(𝒙))^{1/2}(\sec^{2}(𝒙))^{2}\cdot \sec^{2}(𝒙)$
          $\rule{0pt}{}$
     ◉ Use the identity:
          $\rule{0pt}{}$
          ○ $\sec^{2}(𝒙)=1+\tan^{2}(𝒙)$
          $\rule{0pt}{}$
          ○ So the integrand becomes:
          $\rule{0pt}{}$
               ■ $(\tan(𝒙))^{1/2}(1+\tan^{2}(𝒙))^{2}\sec^{2}(𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Substitution:
          $\rule{0pt}{}$
          ○ $𝒖=\tan(𝒙)$
          $\rule{0pt}{}$
          ○ $𝒅𝒖=\sec^{2}(𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Change the bounds:
          ○ When $𝒙=0$, $𝒖=0$
          ○ When $𝒙=\pi/4$, $𝒖=1$
     ◉ Resulting integral in 𝒖:
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{0}^{1} 𝒖^{1/2}(1+𝒖^{2})^{2}\,𝒅𝒖$
          $\rule{0pt}{}$
          ○ $=\displaystyle \int_{0}^{1} (𝒖^{1/2}+2𝒖^{5/2}+𝒖^{9/2})\,𝒅𝒖$
          $\rule{0pt}{}$
     ◉ Evaluate:
          $\rule{0pt}{}$
          ○ $\Big[\left(\dfrac{2}{3}\right)𝒖^{3/2}+\left(\dfrac{4}{7}\right)𝒖^{7/2}+\left(\dfrac{2}{11}\right)𝒖^{11/2}\Big]_{0}^{1}$
          $\rule{0pt}{}$
          ○ $=\dfrac{2}{3}+\dfrac{4}{7}+\dfrac{2}{11}$
               
● [1:51:18](https://www.youtube.com/watch?v=pLrUBjiEo-w&t=6678). 🧩 Example 8 — Integrals involving cosecant and cotangent: Evaluate $\displaystyle \int \cot^{5}(𝒙)\csc^{5}(𝒙)\,𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.2/[1-51-18]-01.png)
     ◉ By analogy with the tangent/secant rules, the power of $\cot(𝒙)$ is odd.
          ○ Keep one factor $\csc(𝒙)\cot(𝒙)$.
     ◉ Rewrite the integrand:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \cot^{4}(𝒙)\csc^{4}(𝒙)\cdot \csc(𝒙)\cot(𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $=\displaystyle \int (\cot^{2}(𝒙))^{2}\csc^{4}(𝒙)\cdot \csc(𝒙)\cot(𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Use the identity:
          $\rule{0pt}{}$
          ○ $\cot^{2}(𝒙)=\csc^{2}(𝒙)-1$
          $\rule{0pt}{}$
          ○ $\displaystyle \int (\csc^{2}(𝒙)-1)^{2}\csc^{4}(𝒙)\cdot \csc(𝒙)\cot(𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Substitution:
          $\rule{0pt}{}$
          ○ $𝒖=\csc(𝒙)$
          $\rule{0pt}{}$
          ○ $𝒅𝒖=-\csc(𝒙)\cot(𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $-𝒅𝒖=\csc(𝒙)\cot(𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Resulting polynomial integral in 𝒖:
          $\rule{0pt}{}$
          ○ $-\displaystyle \int (𝒖^{2}-1)^{2}𝒖^{4}\,𝒅𝒖$
          $\rule{0pt}{}$
          ○ $=-\displaystyle \int (𝒖^{4}-2𝒖^{2}+1)𝒖^{4}\,𝒅𝒖$
          $\rule{0pt}{}$
          ○ $=-\displaystyle \int (𝒖^{8}-2𝒖^{6}+𝒖^{4})\,𝒅𝒖$
          $\rule{0pt}{}$
     ◉ Integrate term by term:
          $\rule{0pt}{}$
          ○ $-\Big[\left(\dfrac{1}{9}\right)𝒖^{9}-\left(\dfrac{2}{7}\right)𝒖^{7}+\left(\dfrac{1}{5}\right)𝒖^{5}\Big]+𝓒$
          $\rule{0pt}{}$
     ◉ Final result:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \cot^{5}(𝒙)\csc^{5}(𝒙)\,𝒅𝒙=-\left(\dfrac{1}{9}\right)\csc^{9}(𝒙)+\left(\dfrac{2}{7}\right)\csc^{7}(𝒙)-\left(\dfrac{1}{5}\right)\csc^{5}(𝒙)+𝓒$






          
Ｏｔｈｅｒ Ｃａｓｅｓ Ｎｏｔ Ｆｉｔｔｉｎｇ Ｔｈｅ Ｓｔａｎｄａｒｄ Ｐａｔｔｅｒｎｓ


● [2:00:35](https://www.youtube.com/watch?v=pLrUBjiEo-w&t=7235). Strategies for cases not covered by the standard patterns. [📷image](../img/Calculus 2 Lecture 7.2/[2-00-35]-01.png)
     ◉ If it does not fit the pattern:
          ○ General idea: convert everything to sine and cosine when the standard rules do not apply.
          
● [2:03:23](https://www.youtube.com/watch?v=pLrUBjiEo-w&t=7403). 🧩 Example 9 — Simplify $\displaystyle \int \dfrac{1-\tan^{2}(𝒙)}{\sec^{2}(𝒙)}\,𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.2/[2-03-23]-01.png)
$\rule{0pt}{}$
     ◉ Note: for other cases not covered by the standard patterns, convert to $\sin(𝒙)$ and $\cos(𝒙)$.
     ◉ Rewrite the fraction:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \left[\dfrac{1}{\sec^{2}(𝒙)}-\dfrac{\tan^{2}(𝒙)}{\sec^{2}(𝒙)}\right]\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Convert to sine and cosine:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{\sec^{2}(𝒙)}=\cos^{2}(𝒙)$
          $\rule{0pt}{}$
          ○ $\dfrac{\tan^{2}(𝒙)}{\sec^{2}(𝒙)}=\left[\dfrac{\sin^{2}(𝒙)}{\cos^{2}(𝒙)}\right]\cdot \cos^{2}(𝒙)=\sin^{2}(𝒙)$
          $\rule{0pt}{}$
     ◉ So the integrand becomes:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \big[\cos^{2}(𝒙)-\sin^{2}(𝒙)\big]\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Recognize the identity:
          $\rule{0pt}{}$
          ○ $\cos^{2}(𝒙)-\sin^{2}(𝒙)=\cos(2𝒙)$
          $\rule{0pt}{}$
     ◉ Therefore:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \cos(2𝒙)\,𝒅𝒙=\dfrac{\sin(2𝒙)}{2}+𝓒$





          
Ｐｒｏｄｕｃｔｓ  Ｗｉｔｈ  Ｄｉｆｆｅｒｅｎｔ Ａｎｇｌｅｓ


● [2:08:13](https://www.youtube.com/watch?v=pLrUBjiEo-w&t=7693). Integrals of products with different angles. [📷image](../img/Calculus 2 Lecture 7.2/[2-08-13]-01.png)
     ◉ Use product-to-sum identities. [openstax 🌐](https://openstax.org/books/precalculus-2e/pages/7-4-sum-to-product-and-product-to-sum-formulas)
          $\rule{0pt}{}$
          ○ $\sin(𝓶𝒙)\sin(𝓷𝒙)=\left(\dfrac{1}{2}\right)\big[\cos(𝓶𝒙-𝓷𝒙)-\cos(𝓶𝒙+𝓷𝒙)\big]$
          $\rule{0pt}{}$
          ○ $\sin(𝓶𝒙)\cos(𝓷𝒙)=\left(\dfrac{1}{2}\right)\big[\sin(𝓶𝒙-𝓷𝒙)+\sin(𝓶𝒙+𝓷𝒙)\big]$
          $\rule{0pt}{}$
          ○ $\cos(𝓶𝒙)\cos(𝓷𝒙)=\left(\dfrac{1}{2}\right)\big[\cos(𝓶𝒙-𝓷𝒙)+\cos(𝓶𝒙+𝓷𝒙)\big]$
          
          
● [2:13:00](https://www.youtube.com/watch?v=pLrUBjiEo-w&t=7980). 🧩 Example 10 — Evaluate $\displaystyle \int_{0}^{\pi/2}\sin(𝒙)\cos(2𝒙)\,𝒅𝒙$.[📷image](../img/Calculus 2 Lecture 7.2/[2-13-00]-01.png)
     ◉ Use the product-to-sum identity:
          $\rule{0pt}{}$
          ○ $\sin(𝒙)\cos(2𝒙)=\left(\dfrac{1}{2}\right)\big[\sin(𝒙-2𝒙)+\sin(𝒙+2𝒙)\big]$
          $\rule{0pt}{}$
          ○ $=\left(\dfrac{1}{2}\right)\big[\sin(-𝒙)+\sin(3𝒙)\big]$
          $\rule{0pt}{}$
          ○ $=\left(\dfrac{1}{2}\right)\big[-\sin(𝒙)+\sin(3𝒙)\big]$
          $\rule{0pt}{}$
     ◉ Rewrite the integral:
          $\rule{0pt}{}$
          ○ $\left(\dfrac{1}{2}\right)\displaystyle \int_{0}^{\pi/2} [-\sin(𝒙)+\sin(3𝒙)]\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Integrate term by term:
          $\rule{0pt}{}$
          ○ $\left(\dfrac{1}{2}\right)\Big[\cos(𝒙)-\dfrac{\cos(3𝒙)}{3}\Big]_{0}^{\pi/2}$
          $\rule{0pt}{}$
     ◉ Evaluate the bounds:
          $\rule{0pt}{}$
          ○ $\left(\dfrac{1}{2}\right)\Big[(\cos(\pi/2)-\dfrac{\cos(3\pi/2)}{3})-(\cos(0)-\dfrac{\cos(0)}{3})\Big]$
          $\rule{0pt}{}$
          ○ $=\left(\dfrac{1}{2}\right)\big[(0-0)-(1-\dfrac{1}{3})\big]$
          $\rule{0pt}{}$
          ○ $=\left(\dfrac{1}{2}\right)\big[-\dfrac{2}{3}\big]$
          $\rule{0pt}{}$
     ◉ Final result:
          $\rule{0pt}{}$
          ○ $-\dfrac{1}{3}$





Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

[openstax🌐](https://openstax.org/books/calculus-volume-2/pages/3-2-trigonometric-integrals)