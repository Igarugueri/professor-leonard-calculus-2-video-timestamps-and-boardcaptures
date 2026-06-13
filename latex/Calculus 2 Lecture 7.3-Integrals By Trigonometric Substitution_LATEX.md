-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ７．３ - Ｉｎｔｅｇｒａｌｓ Ｂｙ Ｔｒｉｇｏｎｏｍｅｔｒｉｃ Ｓｕｂｓｔｉｔｕｔｉｏｎ**---------------------------------






Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:01](https://www.youtube.com/watch?v=q6JwTGpG8b4&t=1). Introduction to Section 7.3: Trigonometric Substitution.
     ◉ Standard integration methods do not directly handle certain radical expressions.
     ◉ The method is motivated by the Pythagorean Theorem and right-triangle constructions.




     
🧩 Ｆｉｒｓｔ Ｍｏｄｅｌ Ｅｘａｍｐｌｅ

● [📷image-1](../img/Calculus 2 Lecture 7.3/[1-12]-01.png) [📷image-2](../img/Calculus 2 Lecture 7.3/[1-12]-02.png)

● [1:12](https://www.youtube.com/watch?v=q6JwTGpG8b4&t=72). Geometric interpretation of radicals.
     ◉ Relate the radical to the Pythagorean Theorem and a right triangle.
     ◉ Rewrite:
          $\rule{0pt}{}$
          ○ $\sqrt{1+𝒙^{2}}=\sqrt{1^{2}+𝒙^{2}}$
          $\rule{0pt}{}$
     ◉ Determine whether the radical represents the hypotenuse or a leg.
          ○ General classification:
               $\rule{0pt}{}$
               ■ In a form like $\sqrt{𝒂^{2}+𝒙^{2}}$, the radical is the hypotenuse.
               $\rule{0pt}{}$
               ■ In a form like $\sqrt{𝒂^{2}-𝒙^{2}}$, the radical is a leg.
               $\rule{0pt}{}$
               ■ In a form like $\sqrt{𝒙^{2}-𝒂^{2}}$, the radical is also a leg.
               $\rule{0pt}{}$
               ■ NOTE: The letter $𝒂$ is just the constant in the expression. Its role depends on the form of the radical:
                   ▣ if the hypotenuse is the constant term, then $𝒂$ is the hypotenuse;
                   ▣ if the variable $𝒙$ term is the hypotenuse, then $𝒂$ is a leg.
          ○ Using the usual right-triangle notation:
               $\rule{0pt}{}$
               ■ Form $\sqrt{𝒂^{2}+𝓫^{2}}$: the radical is the hypotenuse $𝓬$.
               $\rule{0pt}{}$
               ■ Form $𝒂=\sqrt{𝓬^{2}-𝓫^{2}}$: the radical is a leg.
               $\rule{0pt}{}$
               ■ Form $𝓫=\sqrt{𝓬^{2}-𝒂^{2}}$: the radical is a leg.

● [4:14](https://www.youtube.com/watch?v=q6JwTGpG8b4&t=254). Strategy for constructing the reference triangle.
     ◉ Build the triangle for the model radical $\sqrt{1+𝒙^{2}}$.
          ○ adjacent side = $1$
          ○ opposite side = $𝒙$
          ○ hypotenuse = $\sqrt{1+𝒙^{2}}$
     ◉ Arrange the triangle so that a basic trig ratio gives $𝒙/𝒂$.
     ◉ Trigonometric relation:
          $\rule{0pt}{}$
          ○ $\tan(\theta)=\dfrac{𝒙}{1}$
          $\rule{0pt}{}$
          ○ $\tan(\theta)=𝒙$
          $\rule{0pt}{}$
     ◉ First substitution model:
          $\rule{0pt}{}$
          ○ $𝒙=\tan(\theta)$
          $\rule{0pt}{}$
     ◉ Rewrite the radical:
          $\rule{0pt}{}$
          ○ $\sqrt{1+𝒙^{2}}\to\sqrt{1+\tan^{2}(\theta)}$
          $\rule{0pt}{}$
     ◉ Differentiate:
          $\rule{0pt}{}$
          ○ $𝒅𝒙=\sec^{2}(\theta)\,𝒅\theta$


● [7:05](https://www.youtube.com/watch?v=q6JwTGpG8b4&t=425). Rewrite the integral using the substitution.
     ◉ Substitute:
          $\rule{0pt}{}$
          ○ $𝒙=\tan(\theta)$
          $\rule{0pt}{}$
          ○ $𝒅𝒙=\sec^{2}(\theta)\,𝒅\theta$
          $\rule{0pt}{}$
     ◉ Transform the radical:
          $\rule{0pt}{}$
          ○ $\sqrt{1+𝒙^{2}}\to\sqrt{1+\tan^{2}(\theta)}$

● [9:52](https://www.youtube.com/watch?v=q6JwTGpG8b4&t=592). Trigonometric integral obtained after substitution.
     ◉ Use the identity:
          $\rule{0pt}{}$
          ○ $1+\tan^{2}(\theta)=\sec^{2}(\theta)$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\sqrt{1+\tan^{2}(\theta)}=\sqrt{\sec^{2}(\theta)}=\sec(\theta)$
          $\rule{0pt}{}$
     ◉ The integral becomes:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \sec^{3}(\theta)\,𝒅\theta$
          $\rule{0pt}{}$
     ◉ Apply the known secant-power result:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \sec^{3}(\theta)\,𝒅\theta=\dfrac{1}{2}\sec(\theta)\tan(\theta)+\dfrac{1}{2}\ln|\sec(\theta)+\tan(\theta)|+\mathcal{C}$

● [14:44](https://www.youtube.com/watch?v=q6JwTGpG8b4&t=884). Return to the original variable using the triangle.
     ◉ Recover the trigonometric functions:
          $\rule{0pt}{}$
          ○ $\sec(\theta)=\sqrt{1+𝒙^{2}}$
          $\rule{0pt}{}$
          ○ $\tan(\theta)=𝒙$
          $\rule{0pt}{}$
     ◉ Substitute back into the antiderivative.

● [17:18](https://www.youtube.com/watch?v=q6JwTGpG8b4&t=1038). Final result.
     ◉ The antiderivative is:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{2}𝒙\sqrt{1+𝒙^{2}}+\dfrac{1}{2}\ln|\sqrt{1+𝒙^{2}}+𝒙|+\mathcal{C}$
          $\rule{0pt}{}$
               ■ See lecture 7.1





               
Ｔｈｅ Ｔｈｒｅｅ Ｓｔａｎｄａｒｄ Ｃａｓｅｓ

● [18:56](https://www.youtube.com/watch?v=q6JwTGpG8b4&t=1136). Classification of the three standard trig-substitution forms. [📷image-1](../img/Calculus 2 Lecture 7.3/[18-56]-01.png) [📷image-2](../img/Calculus 2 Lecture 7.3/[18-56]-02.png)
$\rule{0pt}{}$
     ◉ Case 1: $\sqrt{𝒂^{2}-𝒙^{2}}$
          ○ Build the triangle associated with sine substitution.
          ○ Use $𝒙=𝒂\sin(\theta)$.
          $\rule{0pt}{}$
     ◉ [27:36](https://www.youtube.com/watch?v=q6JwTGpG8b4&t=1656). Case 2: $\sqrt{𝒂^{2}+𝒙^{2}}$
          ○ Build the triangle associated with tangent substitution.
          ○ Use $𝒙=𝒂\tan(\theta)$.
          $\rule{0pt}{}$
     ◉ [30:40](https://www.youtube.com/watch?v=q6JwTGpG8b4&t=1840). Case 3: $\sqrt{𝒙^{2}-𝒂^{2}}$
          ○ Build the triangle associated with secant substitution.
          ○ Use $𝒙=𝒂\sec(\theta)$.





          
Ｅｘａｍｐｌｅｓ — Ｔｒｉｇｏｎｏｍｅｔｒｉｃ Ｓｕｂｓｔｉｔｕｔｉｏｎ

● [36:36](https://www.youtube.com/watch?v=q6JwTGpG8b4&t=2196). 🧩 Example 1 — : $\displaystyle \int \dfrac{𝒙^{2}}{\sqrt{9-𝒙^{2}}}\,𝒅𝒙$. [📷image-1](../img/Calculus 2 Lecture 7.3/[36-36]-01.png) [📷image-2](../img/Calculus 2 Lecture 7.3/[36-36]-02.png) [📷image-3](../img/Calculus 2 Lecture 7.3/[36-36]-03.png) 
$\rule{0pt}{}$
     ◉ Identify the radical as the form $\sqrt{𝒂^{2}-𝒙^{2}}$.
     ◉ Build the reference triangle:
          ○ hypotenuse = $3$
          ○ opposite side = $𝒙$
          ○ adjacent side = $\sqrt{9-𝒙^{2}}$
     ◉ Trigonometric relation:
          $\rule{0pt}{}$
          ○ $\sin(\theta)=\dfrac{𝒙}{3}$
          $\rule{0pt}{}$
     ◉ Substitution:
          $\rule{0pt}{}$
          ○ $𝒙=3\sin(\theta)$
          $\rule{0pt}{}$
          ○ $𝒅𝒙=3\cos(\theta)\,𝒅\theta$
          $\rule{0pt}{}$
     ◉ Substitute into the integral:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{(3\sin(\theta))^{2}}{\sqrt{9-(3\sin(\theta))^{2}}}\cdot 3\cos(\theta)\,𝒅\theta$
          $\rule{0pt}{}$
     ◉ Simplify the radical:
          $\rule{0pt}{}$
          ○ $\sqrt{9-9\sin^{2}(\theta)}=3\sqrt{1-\sin^{2}(\theta)}$
          $\rule{0pt}{}$
     ◉ Use the identity:
          $\rule{0pt}{}$
          ○ $1-\sin^{2}(\theta)=\cos^{2}(\theta)$
          $\rule{0pt}{}$
     ◉ Reduce the integral to:
          $\rule{0pt}{}$
          ○ $9\displaystyle \int \sin^{2}(\theta)\,𝒅\theta$
          $\rule{0pt}{}$
     ◉ Rewrite $\sin^{2}(\theta)$ with the half-angle identity:
          $\rule{0pt}{}$
          ○ $\sin^{2}(\theta)=\dfrac{1}{2}(1-\cos(2\theta))$
          $\rule{0pt}{}$
     ◉ Integrate:
          $\rule{0pt}{}$
          ○ $9\displaystyle \int \dfrac{1}{2}(1-\cos(2\theta))\,𝒅\theta$
          $\rule{0pt}{}$
          ○ $=\dfrac{9}{2}\Big[\theta-\dfrac{1}{2}\sin(2\theta)\Big]+\mathcal{C}$
          $\rule{0pt}{}$
     ◉ Rewrite in terms of $𝒙$:
          $\rule{0pt}{}$
          ○ $\theta=\sin^{-1}\left(\dfrac{𝒙}{3}\right)$
          $\rule{0pt}{}$
          ○ $\sin(\theta)=\dfrac{𝒙}{3}$
          $\rule{0pt}{}$
          ○ $\cos(\theta)=\dfrac{\sqrt{9-𝒙^{2}}}{3}$
          $\rule{0pt}{}$
          ○ $\sin(2\theta)=2\sin(\theta)\cos(\theta)$
          $\rule{0pt}{}$
     ◉ Final result:
          $\rule{0pt}{}$
          ○ $\dfrac{9}{2}\sin^{-1}\left(\dfrac{𝒙}{3}\right)-\dfrac{1}{2}𝒙\sqrt{9-𝒙^{2}}+\mathcal{C}$
     
● [54:25](https://www.youtube.com/watch?v=q6JwTGpG8b4&t=3265). 🧩 Example 2 — Definite integral: $\displaystyle \int_{1}^{\sqrt{3}}\dfrac{1}{(1+𝒙^{2})^{3/2}}\,𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.3/[54-25]-01.png)
     ◉ Rewrite the denominator as a radical power:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{(\sqrt{1+𝒙^{2}})^{3}}$
          $\rule{0pt}{}$
     ◉ Build the reference triangle for $\sqrt{1+𝒙^{2}}$:
          ○ adjacent side = $1$
          ○ opposite side = $𝒙$
          ○ hypotenuse = $\sqrt{1+𝒙^{2}}$
     ◉ Trigonometric relation:
          $\rule{0pt}{}$
          ○ $\tan(\theta)=𝒙$
          $\rule{0pt}{}$
     ◉ Substitution:
          $\rule{0pt}{}$
          ○ $𝒙=\tan(\theta)$
          $\rule{0pt}{}$
          ○ $𝒅𝒙=\sec^{2}(\theta)\,𝒅\theta$
          $\rule{0pt}{}$
     ◉ [1:01:17](https://www.youtube.com/watch?v=q6JwTGpG8b4&t=3677). Change the bounds:
          $\rule{0pt}{}$
          ○ $𝒙=1\to\theta=\pi/4$
          $\rule{0pt}{}$
          ○ $𝒙=\sqrt{3}\to\theta=\pi/3$
          $\rule{0pt}{}$
          ○ Therefore:
               ■ $𝒙\in[1,\sqrt{3}]\to\theta\in[\pi/4,\pi/3]$
     ◉ Transform the integral:
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{\pi/4}^{\pi/3}\dfrac{\sec^{2}(\theta)}{(\sqrt{1+\tan^{2}(\theta)})^{3}}\,𝒅\theta$
          $\rule{0pt}{}$
     ◉ Use the identity:
          $\rule{0pt}{}$
          ○ $1+\tan^{2}(\theta)=\sec^{2}(\theta)$
          $\rule{0pt}{}$
     ◉ Simplify to the elementary integral:
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{\pi/4}^{\pi/3}\cos(\theta)\,𝒅\theta$
          $\rule{0pt}{}$
     ◉ Evaluate:
          $\rule{0pt}{}$
          ○ $\sin(\theta)\Big|_{\pi/4}^{\pi/3}$
          $\rule{0pt}{}$
          ○ $=\sin(\pi/3)-\sin(\pi/4)$
          $\rule{0pt}{}$
     ◉ Final result:
          $\rule{0pt}{}$
          ○ $\dfrac{\sqrt{3}-\sqrt{2}}{2}$
          
● [1:10:57](https://www.youtube.com/watch?v=q6JwTGpG8b4&t=4257). 🧩 Example 3 —: $\displaystyle \int \dfrac{\sqrt{𝒙^{2}-4}}{𝒙^{4}}\,𝒅𝒙$. [📷image-1](../img/Calculus 2 Lecture 7.3/[1-10-57]-01.png) [📷image-2](../img/Calculus 2 Lecture 7.3/[1-10-57]-02.png)
     ◉ Identify the standard form:
          $\rule{0pt}{}$
          ○ $\sqrt{𝒙^{2}-𝒂^{2}}$
          $\rule{0pt}{}$
     ◉ Build the reference triangle:
          ○ hypotenuse = $𝒙$
          ○ adjacent side = $2$
          ○ opposite side = $\sqrt{𝒙^{2}-4}$
     ◉ Trigonometric relation:
          $\rule{0pt}{}$
          ○ $\sec(\theta)=\dfrac{𝒙}{2}$
          $\rule{0pt}{}$
     ◉ Substitution:
          $\rule{0pt}{}$
          ○ $𝒙=2\sec(\theta)$
          $\rule{0pt}{}$
          ○ $𝒅𝒙=2\sec(\theta)\tan(\theta)\,𝒅\theta$
          $\rule{0pt}{}$
     ◉ Transform the integral:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{\sqrt{(2\sec(\theta))^{2}-4}}{(2\sec(\theta))^{4}}\cdot 2\sec(\theta)\tan(\theta)\,𝒅\theta$
          $\rule{0pt}{}$
     ◉ Simplify step by step:
          $\rule{0pt}{}$
          ○ $\sqrt{4\sec^{2}(\theta)-4}=2\sqrt{\sec^{2}(\theta)-1}$
          $\rule{0pt}{}$
          ○ $\sec^{2}(\theta)-1=\tan^{2}(\theta)$
          $\rule{0pt}{}$
          ○ The integral becomes:
          $\rule{0pt}{}$
               ■ $\dfrac{1}{4}\displaystyle \int \dfrac{\tan^{2}(\theta)}{\sec^{3}(\theta)}\,𝒅\theta$
               $\rule{0pt}{}$
     ◉ Rewrite in sine and cosine:
          $\rule{0pt}{}$
          ○ $\dfrac{\tan^{2}(\theta)}{\sec^{3}(\theta)}=\sin^{2}(\theta)\cos(\theta)$
          $\rule{0pt}{}$
          ○ So:
               ■ $\dfrac{1}{4}\displaystyle \int \sin^{2}(\theta)\cos(\theta)\,𝒅\theta$
     ◉ Secondary substitution:
          $\rule{0pt}{}$
          ○ $𝒖=\sin(\theta)$
          $\rule{0pt}{}$
          ○ $𝒅𝒖=\cos(\theta)\,𝒅\theta$
          $\rule{0pt}{}$
     ◉ Resulting polynomial integral:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{4}\displaystyle \int 𝒖^{2}\,𝒅𝒖$
          $\rule{0pt}{}$
     ◉ Antiderivative:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{12}\sin^{3}(\theta)+\mathcal{C}$
          $\rule{0pt}{}$
     ◉ Return to the original variable using the triangle:
          $\rule{0pt}{}$
          ○ $\sin(\theta)=\dfrac{\sqrt{𝒙^{2}-4}}{𝒙}$
          $\rule{0pt}{}$
     ◉ Final result:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{12}\left[\dfrac{\sqrt{𝒙^{2}-4}}{𝒙}\right]^{3}+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\dfrac{(𝒙^{2}-4)^{3/2}}{12𝒙^{3}}+\mathcal{C}$
     
● [1:33:13](https://www.youtube.com/watch?v=q6JwTGpG8b4&t=5593). 🧩 Example 4 — Evaluate $\displaystyle \int \dfrac{1}{(3-2𝒙-𝒙^{2})^{5/2}}\,𝒅𝒙$. [📷image-1](../img/Calculus 2 Lecture 7.3/[1-33-13]-01.png) [📷image-2](../img/Calculus 2 Lecture 7.3/[1-33-13]-02.png) [📷image-3](../img/Calculus 2 Lecture 7.3/[36-36]-03.png) [📷image-4](../img/Calculus 2 Lecture 7.3/[1-33-13]-04.png) 
     ◉ Rewrite the denominator as a radical power:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{[\sqrt{3-2𝒙-𝒙^{2}}]^{5}}\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Complete the square in the quadratic expression:
          $\rule{0pt}{}$
          ○ $3-2𝒙-𝒙^{2}$
          $\rule{0pt}{}$
          ○ $=-𝒙^{2}-2𝒙+3$
          $\rule{0pt}{}$
          ○ $=-(𝒙^{2}+2𝒙)+3$
          $\rule{0pt}{}$
          ○ $=-(𝒙^{2}+2𝒙+1)+3+1$
          $\rule{0pt}{}$
          ○ $=-(𝒙+1)^{2}+4$
          $\rule{0pt}{}$
          ○ $=4-(𝒙+1)^{2}$
          $\rule{0pt}{}$
     ◉ Substitute this back into the integral:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{[\sqrt{4-(𝒙+1)^{2}}]^{5}}\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ First substitution to standardize the radical:
          $\rule{0pt}{}$
          ○ $𝒖=𝒙+1$
          $\rule{0pt}{}$
          ○ $𝒅𝒖=𝒅𝒙$
          $\rule{0pt}{}$
     ◉ The integral becomes:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{[\sqrt{4-𝒖^{2}}]^{5}}\,𝒅𝒖$
          $\rule{0pt}{}$
     ◉ Recognize the form:
          $\rule{0pt}{}$
          ○ $\sqrt{2^{2}-𝒖^{2}}$
          $\rule{0pt}{}$
     ◉ Build the reference triangle:
          ○ hypotenuse = $2$
          ○ opposite side = $𝒖$
          ○ adjacent side = $\sqrt{4-𝒖^{2}}$
     ◉ Trigonometric substitution:
          $\rule{0pt}{}$
          ○ $\sin(\theta)=\dfrac{𝒖}{2}$
          $\rule{0pt}{}$
          ○ $𝒖=2\sin(\theta)$
          $\rule{0pt}{}$
          ○ $𝒅𝒖=2\cos(\theta)\,𝒅\theta$
          $\rule{0pt}{}$
     ◉ Substitute into the integral:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{[\sqrt{4-(2\sin(\theta))^{2}}]^{5}}\cdot 2\cos(\theta)\,𝒅\theta$
          $\rule{0pt}{}$
          ○ $=\displaystyle \int \dfrac{1}{[\sqrt{4-4\sin^{2}(\theta)}]^{5}}\cdot 2\cos(\theta)\,𝒅\theta$
          $\rule{0pt}{}$
          ○ $=\displaystyle \int \dfrac{1}{[2\sqrt{1-\sin^{2}(\theta)}]^{5}}\cdot 2\cos(\theta)\,𝒅\theta$
          $\rule{0pt}{}$
          ○ $=\displaystyle \int \dfrac{2\cos(\theta)}{32[\sqrt{1-\sin^{2}(\theta)}]^{5}}\,𝒅\theta$
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{16}\displaystyle \int \dfrac{\cos(\theta)}{[\sqrt{1-\sin^{2}(\theta)}]^{5}}\,𝒅\theta$
          $\rule{0pt}{}$
     ◉ Use the identity:
          $\rule{0pt}{}$
          ○ $1-\sin^{2}(\theta)=\cos^{2}(\theta)$
          $\rule{0pt}{}$
     ◉ Then:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{16}\displaystyle \int \dfrac{\cos(\theta)}{[\sqrt{\cos^{2}(\theta)}]^{5}}\,𝒅\theta$
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{16}\displaystyle \int \dfrac{\cos(\theta)}{\cos^{5}(\theta)}\,𝒅\theta$
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{16}\displaystyle \int \dfrac{1}{\cos^{4}(\theta)}\,𝒅\theta$
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{16}\displaystyle \int \sec^{4}(\theta)\,𝒅\theta$
          $\rule{0pt}{}$
     ◉ Rewrite $\sec^{4}(\theta)$:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{16}\displaystyle \int \sec^{2}(\theta)\cdot \sec^{2}(\theta)\,𝒅\theta$
          $\rule{0pt}{}$
     ◉ Use the identity:
          $\rule{0pt}{}$
          ○ $\sec^{2}(\theta)=\tan^{2}(\theta)+1$
          $\rule{0pt}{}$
     ◉ So:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{16}\displaystyle \int (\tan^{2}(\theta)+1)\cdot \sec^{2}(\theta)\,𝒅\theta$
          $\rule{0pt}{}$
     ◉ Secondary substitution:
          $\rule{0pt}{}$
          ○ $\mathcal{W}=\tan(\theta)$
          $\rule{0pt}{}$
          ○ $𝒅\mathcal{W}=\sec^{2}(\theta)\,𝒅\theta$
          $\rule{0pt}{}$
     ◉ The integral becomes:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{16}\displaystyle \int (\mathcal{W}^{2}+1)\,𝒅\mathcal{W}$
          $\rule{0pt}{}$
     ◉ Integrate:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{16}\Big[\dfrac{1}{3}\mathcal{W}^{3}+\mathcal{W}\Big]$
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{16}\Big[\dfrac{1}{3}\tan^{3}(\theta)+\tan(\theta)\Big]$
          $\rule{0pt}{}$
     ◉ Return from $\theta$ to $𝒖$ using the triangle:
          $\rule{0pt}{}$
          ○ $\tan(\theta)=\dfrac{\text{opposite}}{\text{adjacent}}$
          $\rule{0pt}{}$
          ○ $\tan(\theta)=\dfrac{𝒖}{\sqrt{4-𝒖^{2}}}$
          $\rule{0pt}{}$
     ◉ Substitute:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{16}\left[\dfrac{1}{3}\left(\dfrac{𝒖}{\sqrt{4-𝒖^{2}}}\right)^{3}+\dfrac{𝒖}{\sqrt{4-𝒖^{2}}}\right]+\mathcal{C}$
          $\rule{0pt}{}$
     ◉ Put both terms over the same denominator:
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{16}\left[\dfrac{𝒖^{3}}{3(\sqrt{4-𝒖^{2}})^{3}}+\dfrac{3𝒖(4-𝒖^{2})}{3(\sqrt{4-𝒖^{2}})^{3}}\right]+\mathcal{C}$
          $\rule{0pt}{}$
     ◉ Combine the numerators:
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{16}\dfrac{𝒖^{3}+3𝒖(4-𝒖^{2})}{3(\sqrt{4-𝒖^{2}})^{3}}+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{16}\dfrac{𝒖^{3}+12𝒖-3𝒖^{3}}{3(\sqrt{4-𝒖^{2}})^{3}}+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{16}\dfrac{12𝒖-2𝒖^{3}}{3(\sqrt{4-𝒖^{2}})^{3}}+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{24}\dfrac{6𝒖-𝒖^{3}}{(\sqrt{4-𝒖^{2}})^{3}}+\mathcal{C}$
          $\rule{0pt}{}$
     ◉ Substitute back $𝒖=𝒙+1$:
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{24}\dfrac{6(𝒙+1)-(𝒙+1)^{3}}{(\sqrt{4-(𝒙+1)^{2}})^{3}}+\mathcal{C}$
          $\rule{0pt}{}$
     ◉ Expand the numerator:
          $\rule{0pt}{}$
          ○ $6(𝒙+1)=6𝒙+6$
          $\rule{0pt}{}$
          ○ $(𝒙+1)^{3}=𝒙^{3}+3𝒙^{2}+3𝒙+1$
          $\rule{0pt}{}$
          ○ $6(𝒙+1)-(𝒙+1)^{3}$
               ■ $=6𝒙+6-(𝒙^{3}+3𝒙^{2}+3𝒙+1)$
               ■ $=6𝒙+6-𝒙^{3}-3𝒙^{2}-3𝒙-1$
               ■ $=5+3𝒙-3𝒙^{2}-𝒙^{3}$
     ◉ Simplify the denominator:
          $\rule{0pt}{}$
          ○ $4-(𝒙+1)^{2}=4-(𝒙^{2}+2𝒙+1)$
          $\rule{0pt}{}$
          ○ $=3-2𝒙-𝒙^{2}$
          $\rule{0pt}{}$
     ◉ Final result:
          $\rule{0pt}{}$
          ○ $\dfrac{1}{24}\dfrac{5+3𝒙-3𝒙^{2}-𝒙^{3}}{(\sqrt{3-2𝒙-𝒙^{2}})^{3}}+\mathcal{C}$





Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

[openstax🌐](https://openstax.org/books/calculus-volume-2/pages/3-3-trigonometric-substitution)