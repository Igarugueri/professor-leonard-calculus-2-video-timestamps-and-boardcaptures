--------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ６．５－Ｃａｌｃｕｌｕｓ ｏｆ Ｉｎｖｅｒｓｅ Ｔｒｉｇｏｎｏｍｅｔｒｉｃ Ｆｕｎｃｔｉｏｎｓ**---------------------------—





Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:01](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=1). Intro𝒅𝒖ction to inverse trigonometric functions and fundamental properties.
     ◉ One-to-one requirement: a function must be injective to have an inverse.
          ○ A function is injective if different inputs always pro𝒅𝒖ce different outputs.
               ■ This guarantees that each value in the range corresponds to exactly one value in the domain.
               ■ Without injectivity, an inverse function would be ambiguous (one output mapping to multiple inputs).
          ○ Need for domain restriction in periodic trigonometric functions.
               ■ Trigonometric functions like $\sin$, $\cos$, and $\tan$ are periodic and repeat values infinitely many times.
               ■ Restricting the domain removes this repetition and forces the function to be one-to-one.
               ■ The chosen restricted interval is called the principal interval and defines the principal values of the inverse.





Ｉｎｖｅｒｓｅ　Ｓｉｎｅ　Ｆｕｎｃｔｉｏｎ

● [1:41](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=101). Analysis of the sine function $𝒚=\sin(𝒙)$ and its graphical behavior. [📷image-1](../img/Calculus 2 Lecture 6.5/[1-41]-01.png) [📷image-2](../img/Calculus 2 Lecture 6.5/[1-41]-02.png) [📷image-3](../img/Calculus 2 Lecture 6.5/[1-41]-03.png)
     ◉ Key graphical properties.
          ○ The sine function is periodic and oscillates between $-1$ and $1$.
          ○ It fails the **horizontal line test** on $\mathbb{R}$, so it is not one-to-one on its full domain.
     ◉ Restricting the domain to the interval $[-\pi/2,\pi/2]$ to ensure injectivity.
          ○ We restrict the domain so that the inverse is a function.
          ○ On this interval, $\sin(𝒙)$ is strictly increasing.
          ○ Every horizontal line intersects the graph at most once.
     ◉ Formal definition:
          ○ $𝒚=\sin^{-1}(𝒙)$ if and only if $\sin(𝒚)=𝒙$.
               ■ Here, 𝒚 is restricted to the principal interval $[-\pi/2,\pi/2]$.
     ◉ Interchange principle.
          ○ The original domain $[-\pi/2,\pi/2]$ becomes the range of the inverse function.
          ○ The original range $[-1,1]$ becomes the domain of the inverse.
     ◉ Final specification for $\sin^{-1}(𝒙)$.
          ○ Domain: $[-1,1]$
          ○ Range: $[-\pi/2,\pi/2]$






Ｉｎｖｅｒｓｅ　Ｃｏｓｉｎｅ　Ｆｕｎｃｔｉｏｎ

● [10:19](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=619). Study of the cosine function $𝒚=\cos(𝒙)$ and restricted domain. [📷image](../img/Calculus 2 Lecture 6.5/[10-19]-01.png)
     ◉ Key graphical properties.
          ○ The cosine function is periodic and oscillates between $-1$ and $1$.
          ○ On its full domain $\mathbb{R}$, it fails the horizontal line test.
     ◉ Selection of the interval $[0,\pi]$ to make the function one-to-one.
          ○ On the interval $[0,\pi]$, $\cos(𝒙)$ is strictly decreasing.
          ○ Every horizontal line intersects the graph at most once.
          ○ This interval is chosen to include both extreme values: $\cos(0)=1$ and $\cos(\pi)=-1$.
     ◉ Interchange principle.
          ○ The restricted domain $[0,\pi]$ becomes the range of the inverse function.
          ○ The original range $[-1,1]$ becomes the domain of the inverse.
     ◉ Final specification for $\cos^{-1}(𝒙)$.
          ○ Domain: $[-1,1]$
          ○ Range: $[0,\pi]$





Ｉｎｖｅｒｓｅ　Ｔａｎｇｅｎｔ　Ｆｕｎｃｔｉｏｎ

● [14:15](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=855). Analysis of the tangent function $𝒚=\tan(𝒙)$ and asymptotic behavior. [📷image](../img/Calculus 2 Lecture 6.5/[14-15]-01.png)
     ◉ Key graphical properties.
          ○ The tangent function is periodic and has vertical asymptotes at odd multiples of $\pi/2$.
          ○ It fails the horizontal line test on $\mathbb{R}$ 𝒅𝒖e to periodicity.
     ◉ Restriction to the open interval $(-\pi/2,\pi/2)$ 𝒅𝒖e to vertical asymptotes.
          ○ On this interval, $\tan(𝒙)$ is strictly increasing.
          ○ The function is continuous on $(-\pi/2,\pi/2)$.
     ◉ Interchange principle.
          ○ The restricted domain $(-\pi/2,\pi/2)$ becomes the range of the inverse function.
     ◉ Range and inverse implications.
          ○ Range of $\tan(𝒙)$ on $(-\pi/2,\pi/2)$: $(-\infty,\infty)$.
          ○ Therefore, the domain of $\tan^{-1}(𝒙)$ is $(-\infty,\infty)$.
     ◉ Final specification for $\tan^{-1}(𝒙)$.
          ○ Domain: $(-\infty,\infty)$.
          ○ Range: $(-\pi/2,\pi/2)$.





Ｏｔｈｅｒ　Ｉｎｖｅｒｓｅ　Ｔｒｉｇｏｎｏｍｅｔｒｉｃ　Ｆｕｎｃｔｉｏｎｓ

● [16:59](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=1019). Study of $𝒚=\csc(𝒙)$. [📷image-1](../img/Calculus 2 Lecture 6.5/[16-59]-01.png) [📷image-2](../img/Calculus 2 Lecture 6.5/[16-59]-02.png)
     ◉ Definition and discontinuities.
     $\rule{0pt}{}$
          ○ $\csc(𝒙)=\dfrac{1}{\sin(𝒙)}$
          $\rule{0pt}{}$
          ○ $\csc(𝒙)$ is undefined where $\sin(𝒙)=0$ ($𝒙=k\pi$, $k\in\mathbb{Z}$), pro𝒅𝒖cing vertical asymptotes.
     ◉ Graphical behavior.
          ○ The graph consists of separate branches above $1$ and below $-1$.
          ○ It fails the horizontal line test on $\mathbb{R}$, so its inverse would not be a function unless the domain is restricted.

● [22:54](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=1374). Graphical behavior of $𝒚=\sec(𝒙)$ and transformation to $\sec^{-1}(𝒙)$. [📷image](../img/Calculus 2 Lecture 6.5/[22-54]-01.png)
     ◉ Definition and discontinuities.
     $\rule{0pt}{}$
          ○ $\sec(𝒙)=\dfrac{1}{\cos(𝒙)}$
          $\rule{0pt}{}$
          ○ $\sec(𝒙)$ is undefined where $\cos(𝒙)=0$ ($𝒙=\pi/2+k\pi$), pro𝒅𝒖cing vertical asymptotes.
     ◉ Inverse function idea.
          ○ The domain must be restricted so $\sec(𝒙)$ becomes one-to-one.
          ○ Then $\sec^{-1}(𝒙)$ is defined using principal values on that restricted domain.

● [27:40](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=1660). Inverse cotangent function $\cot^{-1}(𝒙)$. [📷image](../img/Calculus 2 Lecture 6.5/[27-40]-01.png)
     ◉ Range and domain relationship.
          ○ $\cot(𝒙)$ is one-to-one on $(0,\pi)$ and its range is $(-\infty,\infty)$.
          ○ Therefore, the inverse function has:
               ■ Domain: $(-\infty,\infty)$
               ■ Range: $(0,\pi)$





Ｅｖａｌｕａｔｉｎｇ　Ｉｎｖｅｒｓｅ　Ｔｒｉｇｏｎｏｍｅｔｒｉｃ　Ｅｘｐｒｅｓｓｉｏｎｓ

● [30:00](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=1800). 🧩 Example – Evaluation of inverse trigonometric expressions using exact values: [📷image](../img/Calculus 2 Lecture 6.5/[30-00]-01.png)
     ◉ Key idea: evaluating an inverse trigonometric function means finding the angle 𝒚
        within the principal range such that the original trigonometric function equals
        the given value.
     ◉ Important restriction: the solution must lie inside the restricted interval of the
         inverse function, **not just any angle that satisfies the equation.**
         $\rule{0pt}{}$
     ◉ Evaluation of $\sin^{-1}\big(\dfrac{1}{2}\big)$
     $\rule{0pt}{}$
          ○ Solve $\sin(𝒚)=\dfrac{1}{2}$.
          $\rule{0pt}{}$
          ○ The angle must satisfy $𝒚\in[-\pi/2,\pi/2]$.
          $\rule{0pt}{}$
          ○ Therefore, $\sin^{-1}\big(\dfrac{1}{2}\big)=\pi/6$.
          $\rule{0pt}{}$
     ◉ Evaluation of $\cos^{-1}\big(-\dfrac{\sqrt{3}}{2}\big)$
     $\rule{0pt}{}$
          ○ Solve $\cos(𝒚)=-\dfrac{\sqrt{3}}{2}$.
          $\rule{0pt}{}$
          ○ The angle must lie in the interval $[0,\pi]$.
          ○ This places the angle in the second quadrant.
          $\rule{0pt}{}$
          ○ Hence, $\cos^{-1}\big(-\dfrac{\sqrt{3}}{2}\big)=\dfrac{5\pi}{6}$.
          $\rule{0pt}{}$
     ◉ Evaluation of $\tan^{-1}(\sqrt{3})$
     $\rule{0pt}{}$
          ○ Solve $\tan(𝒚)=\sqrt{3}$.
          ○ The principal range is $(-\pi/2,\pi/2)$.
          $\rule{0pt}{}$
          ○ Hence, $\tan^{-1}(\sqrt{3})=\pi/3$.
     ◉ Key warning:
          ○ Inverse trigonometric functions do NOT return all possible angles.
          ○ They return the unique angle within the principal interval.





Ｃｏｍｐｏｓｉｔｉｏｎ　ｏｆ　Ｉｎｖｅｒｓｅ　Ｔｒｉｇｏｎｏｍｅｔｒｉｃ　Ｆｕｎｃｔｉｏｎｓ

● [38:42](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=2322). 🧩 Example – Composition of trigonometric functions and geometric identities: [📷image](../img/Calculus 2 Lecture 6.5/[38-42]-01.png)
$\rule{0pt}{}$
     ◉  Evaluation of $\tan\big(\cos^{-1}\big(\dfrac{1}{2}\big)\big)$.
     $\rule{0pt}{}$
          ○ Let $\theta=\cos^{-1}\big(\dfrac{1}{2}\big)$.
          $\rule{0pt}{}$
          ○ Then $\cos\theta=\dfrac{1}{2}$, with $\theta$ restricted to the principal range $[0,\pi]$.
          $\rule{0pt}{}$
          ○ Right-triangle construction:
          $\rule{0pt}{}$
               ■ $\cos\theta=\dfrac{\text{adjacent}}{\text{hypotenuse}}=\dfrac{1}{2}$
               $\rule{0pt}{}$
               ■ Choose adjacent $=1$ and hypotenuse $=2$
               $\rule{0pt}{}$
               ■ Opposite $=\sqrt{2^{2}-1^{2}}=\sqrt{3}$
          ○ Therefore:
               ■ $\tan\theta=\dfrac{\text{opposite}}{\text{adjacent}}=\dfrac{\sqrt{3}}{1}=\sqrt{3}$
               $\rule{0pt}{}$
               ■ $\tan\big(\cos^{-1}\big(\dfrac{1}{2}\big)\big)=\sqrt{3}$.
               $\rule{0pt}{}$
     ◉ [42:34](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=2554). Evaluation of $\cot\big(\sin^{-1}\big(\dfrac{1}{3}\big)\big)$. [📷image](../img/Calculus 2 Lecture 6.5/[42-34]-01.png)
          ○ Let $\theta=\sin^{-1}\big(\dfrac{1}{3}\big)$.
          $\rule{0pt}{}$
          ○ Then $\sin\theta=\dfrac{1}{3}$, with $\theta$ in the principal range $[-\pi/2,\pi/2]$.
          $\rule{0pt}{}$
          ○ Construct a right triangle:
               ■ Opposite side $=1$
               ■ Hypotenuse $=3$
               ■ Adjacent side $=\sqrt{3^{2}-1^{2}}=\sqrt{8}=2\sqrt{2}$
          ○ Compute the cotangent:
               ■ $\cot\theta=\dfrac{\text{adjacent}}{\text{opposite}}=\dfrac{2\sqrt{2}}{1}$
          ○ Therefore:
               ■ $\cot\big(\sin^{-1}\big(\dfrac{1}{3}\big)\big)=2\sqrt{2}$.





Ｃａｎｃｅｌｌａｔｉｏｎ　Ｐｒｏｐｅｒｔｉｅｓ　ａｎｄ　Ｐｒｉｎｃｉｐａｌ　Ｖａｌｕｅｓ

● [46:00](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=2760). Cancellation properties and the importance of domain restrictions. [📷image](../img/Calculus 2 Lecture 6.5/[46-00]-01.png)
     ◉ Direct cancellation (function composed with its inverse):
          ○ $\sin(\sin^{-1}(𝒙))=𝒙$,      for $-1\le 𝒙\le 1$
          ○ $\cos(\cos^{-1}(𝒙))=𝒙$,    for $-1\le 𝒙\le 1$
          ○ $\tan(\tan^{-1}(𝒙))=𝒙$,     for $-\infty<𝒙<\infty$
     ◉ Reverse cancellation (inverse composed with the function):
          ○ $\sin^{-1}(\sin 𝒙)=𝒙$,       for $-\pi/2\le 𝒙\le \pi/2$
          ○ $\cos^{-1}(\cos 𝒙)=𝒙$,     for $0\le 𝒙\le \pi$
          ○ $\tan^{-1}(\tan 𝒙)=𝒙$,      for $-\pi/2<𝒙<\pi/2$
     ◉ Key idea:
          ○ The inverse does not “undo” the function everywhere — it only undoes it on the interval where the function is one-to-one.
          ○ Cancellation only works when the input lies in the restricted domain (principal interval) of the inverse function.
          ○ Outside these intervals, inverse trigonometric functions return the principal value, not the original angle.

● [49:20](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=2960). 🧩 Example – Cancellation using inverse trigonometric functions:  $\sin(\sin^{-1}(0.3))$ [📷image](../img/Calculus 2 Lecture 6.5/[49-20]-01.png)
     ◉ Key identity:
          ○ $\sin(\sin^{-1}(𝒙))=𝒙$
               ■ valid for $-1\le 𝒙\le 1$
     ◉ Domain check:
          ○ $0.3\in[-1,1]$ ✓
     ◉ Explanation:
          ○ $\sin^{-1}(𝒙)$ returns an angle whose sine is 𝒙.
          ○ Applying $\sin$ to that angle recovers the original value 𝒙.
          ○ Since 0.3 is within the domain of $\sin^{-1}$, the cancellation is valid.
     ◉ Final result:
          ○ $\sin(\sin^{-1}(0.3))=0.3$

● [49:55](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=2995). 🧩 Example – Cancellation using inverse trigonometric functions: $\cos^{-1}(\cos(3\pi/2))$ [📷image](../img/Calculus 2 Lecture 6.5/[49-55]-01.png)
     ◉ Step 1: Evaluate the inner cosine
          ○ $\cos(3\pi/2)=0$
     ◉ Step 2: Rewrite the expression
          ○ $\cos^{-1}(\cos(3\pi/2))=\cos^{-1}(0)$
     ◉ Step 3: Interpret $\cos^{-1}(0)$
          ○ Let $\theta=\cos^{-1}(0)$
          ○ This means: $\cos(\theta)=0$
     ◉ Step 4: Apply the principal range of $\cos^{-1}$
          ○ Range of $\cos^{-1}(𝒙)$ is $[0,\pi]$
          ○ In this interval, $\cos(\theta)=0$ at:
               ■ $\theta=\pi/2$
     ◉ Final result:
          ○ $\cos^{-1}(\cos(3\pi/2))=\pi/2$
     





Ｄｅｒｉｖａｔｉｖｅｓ　ｏｆ　Ｉｎｖｅｒｓｅ　Ｔｒｉｇｏｎｏｍｅｔｒｉｃ　Ｆｕｎｃｔｉｏｎｓ

● [51:40](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=3100). Derivatives of inverse trigonometric functions [📷image](../img/Calculus 2 Lecture 6.5/[51-40]-01.png)
     ◉ General form ($𝒖=𝒖(𝒙)$):
          ○ All formulas require the Chain Rule: multiply by $\dfrac{𝒅𝒖}{𝒅𝒙}$ 
     ◉ Inverse sine:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝑥}\Big[\sin^{-1}(𝒖)\Big]=\dfrac{1}{\sqrt{1-𝒖^{2}}}\cdot\dfrac{𝒅𝒖}{𝒅𝒙}$ 
          $\rule{0pt}{}$
     ◉ Inverse cosine:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝑥}\Big[\cos^{-1}(𝒖)\Big]=-\dfrac{1}{\sqrt{1-𝒖^{2}}}\cdot\dfrac{𝒅𝒖}{𝒅𝒙}$ 
          $\rule{0pt}{}$
     ◉ Inverse tangent:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝑥}\Big[\tan^{-1}(𝒖)\Big]=\dfrac{1}{1+𝒖^{2}}\cdot\dfrac{𝒅𝒖}{𝒅𝒙}$ 
          $\rule{0pt}{}$
     ◉ Inverse cosecant:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝑥}\Big[\csc^{-1}(𝒖)\Big]=-\dfrac{1}{\lvert 𝒖\rvert\sqrt{𝒖^{2}-1}}\cdot\dfrac{𝒅𝒖}{𝒅𝒙}$ 
          $\rule{0pt}{}$
     ◉ Inverse secant:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝑥}\Big[\sec^{-1}(𝒖)\Big]=\dfrac{1}{\lvert 𝒖\rvert\sqrt{𝒖^{2}-1}}\cdot\dfrac{𝒅𝒖}{𝒅𝒙}$ 
          $\rule{0pt}{}$
     ◉ Inverse cotangent:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝑥}\Big[\cot^{-1}(𝒖)\Big]=-\dfrac{1}{1+𝒖^{2}}\cdot\dfrac{𝒅𝒖}{𝒅𝒙}$ 

● [56:12](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=3372). Proofs using implicit differentiation: $𝑦=\cos^{-1}(𝒙)$ [📷image](../img/Calculus 2 Lecture 6.5/[56-12]-01.png) 
     ◉ Step 1: Rewrite using the inverse definition
          ○ $𝑦=\cos^{-1}(𝒙)\iff\cos(𝑦)=𝒙$
     ◉ Step 2: Differentiate both sides with respect to 𝒙
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝑥}\Big[\cos(𝑦)\Big]=\dfrac{𝒅}{𝒅𝑥}\Big[𝒙\Big]$
          $\rule{0pt}{}$
          ○ $-\sin(𝑦)\cdot\dfrac{𝒅𝑦}{𝒅𝑥}=1$
          $\rule{0pt}{}$
     ◉ Step 3: Solve for $\dfrac{𝒅𝑦}{𝒅𝑥}$
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝑦}{𝒅𝑥}=-\dfrac{1}{\sin(𝑦)}$
          $\rule{0pt}{}$
     ◉ Step 4: Eliminate 𝑦 using a trigonometric identity
     $\rule{0pt}{}$
          ○ $\sin^{2}(𝑦)+\cos^{2}(𝑦)=1$
          $\rule{0pt}{}$
          ○ $\sin^{2}(𝑦)=1-\cos^{2}(𝑦)$
          $\rule{0pt}{}$
     ◉ Step 5: Substitute $\cos(𝑦)=𝒙$
     $\rule{0pt}{}$
          ○ $\sin(𝑦)=\sqrt{1-𝒙^{2}}$
          ○ (positive root 𝒅𝒖e to the range of arccos)
     ◉ Step 6: Final result
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝑦}{𝒅𝑥}=-\dfrac{1}{\sqrt{1-𝒙^{2}}}$

● [1:01:03](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=3663). Proofs using implicit differentiation: $\sec^{-1}(𝒙)$ [📷image-1](../img/Calculus 2 Lecture 6.5/[38-42]-01.png) [📷image-2](../img/Calculus 2 Lecture 6.5/[1-01-03]-02.png)
     ◉ Step 1: Write the inverse definition
          ○ $𝑦=\sec^{-1}(𝒙)\iff\sec(𝑦)=𝒙$
     ◉ Step 2: Differentiate implicitly with respect to 𝒙
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝑥}\Big[\sec(𝑦)\Big]=\dfrac{𝒅}{𝒅𝑥}\Big[𝒙\Big]$
          $\rule{0pt}{}$
          ○ $\sec(𝑦)\cdot\tan(𝑦)\cdot\dfrac{𝒅𝑦}{𝒅𝑥}=1$
          $\rule{0pt}{}$
     ◉ Step 3: Solve for $\dfrac{𝒅𝑦}{𝒅𝑥}$
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝑦}{𝒅𝑥}=\dfrac{1}{\sec(𝑦)\cdot\tan(𝑦)}$
          $\rule{0pt}{}$
     ◉ Step 4: Express everything in terms of 𝒙
          ○ From $\sec(𝑦)=𝒙$
          $\rule{0pt}{}$
          ○ $\cos(𝑦)=\dfrac{1}{𝒙}$
          $\rule{0pt}{}$
     ◉ Step 5: Construct a right triangle
          ○ Hypotenuse $=𝒙$
          ○ Adjacent side $=1$
          ○ Opposite side $=\sqrt{𝒙^{2}-1}$
     ◉ Step 6: Compute $\tan(𝑦)$
     $\rule{0pt}{}$
          ○ $\tan(𝑦)=\dfrac{\text{opposite}}{\text{adjacent}}$
          $\rule{0pt}{}$
          ○ $\tan(𝑦)=\sqrt{𝒙^{2}-1}$
     ◉ Step 7: Substitute into the derivative
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝑦}{𝒅𝑥}=\dfrac{1}{𝒙\cdot\sqrt{𝒙^{2}-1}}$
          $\rule{0pt}{}$
     ◉ Step 8: Intro𝒅𝒖ce absolute value (domain issue)
          ○ $\sec^{-1}(𝒙)$ is defined for $\lvert 𝒙\rvert\ge 1$
          ○ $\sec(𝑦)=𝒙$ can be positive or negative
          ○ Therefore $\lvert 𝒙\rvert$ is required
     ◉ Final result:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝑥}\Big[\sec^{-1}(𝒙)\Big]=\dfrac{1}{\lvert 𝒙\rvert\sqrt{𝒙^{2}-1}}$

● [1:07:40](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=4060). 🧩 Example –  Derivative of: $\cos^{-1}(5𝒙)$. [📷image](../img/Calculus 2 Lecture 6.5/[1-07-40]-01.png) 
     ◉ Step 2: Recall the derivative rule
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝑥}\Big[\cos^{-1}(𝒖)\Big]=-\dfrac{1}{\sqrt{1-𝒖^{2}}}\cdot\dfrac{𝒅𝒖}{𝒅𝑥}$
          $\rule{0pt}{}$
     ◉ Step 3: Identify the inner function
          ○ $𝒖=5𝒙$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒖}{𝒅𝑥}=5$
          $\rule{0pt}{}$
     ◉ Step 4: Apply the chain rule
     $\rule{0pt}{}$
          ○ $𝒇'(𝒙)=\Big(-\dfrac{1}{\sqrt{1-(5𝒙)^{2}}}\Big)\cdot 5$
          $\rule{0pt}{}$
     ◉ Step 5: Simplify
     $\rule{0pt}{}$
          ○ $(5𝒙)^{2}=25𝒙^{2}$
          $\rule{0pt}{}$
          ○ $\sqrt{1-25𝒙^{2}}$
     ◉ Final result:
          ○ $𝒇'(𝒙)=-\dfrac{5}{\sqrt{1-25𝒙^{2}}}$

● [1:10:50](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=4250). 🧩 Example – Derivative of: $\sin^{-1}\big(\sqrt{2𝒕+1}\big)$. [📷image](../img/Calculus 2 Lecture 6.5/[1-10-50]-01.png) 
     ◉ Step 2: Recall the derivative rule
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒕}\Big[\sin^{-1}(𝒖)\Big]=\dfrac{1}{\sqrt{1-𝒖^{2}}}\cdot\dfrac{𝒅𝒖}{𝒅𝒕}$
          $\rule{0pt}{}$
     ◉ Step 3: Define the inner function
     $\rule{0pt}{}$
          ○ $𝒖=\sqrt{2𝒕+1}=(2𝒕+1)^{1/2}$
          $\rule{0pt}{}$
     ◉ Step 4: Differentiate 𝒖 (chain rule)
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒖}{𝒅𝒕}=\dfrac{1}{2}(2𝒕+1)^{-1/2}\cdot 2$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒖}{𝒅𝒕}=\dfrac{1}{\sqrt{2𝒕+1}}$
          $\rule{0pt}{}$
     ◉ Step 5: Substitute into the main rule
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒕}=\dfrac{1}{\sqrt{1-\big(\sqrt{2𝒕+1}\big)^{2}}}\cdot\dfrac{1}{\sqrt{2𝒕+1}}$
          $\rule{0pt}{}$
     ◉ Step 6: Simplify
     $\rule{0pt}{}$
          ○ $\big(\sqrt{2𝒕+1}\big)^{2}=2𝒕+1$
          $\rule{0pt}{}$
          ○ $\sqrt{1-(2𝒕+1)}=\sqrt{-2𝒕}$
          $\rule{0pt}{}$
     ◉ Final result:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒕}=\dfrac{1}{\sqrt{-2𝒕}\cdot\sqrt{2𝒕+1}}$
          $\rule{0pt}{}$
     ◉ Domain check (required for inverse trigonometric functions)
     $\rule{0pt}{}$
          ○ For  $\sin^{-1}(𝒖)$, the argument must satisfy: $-1\le 𝒖\le 1$
          $\rule{0pt}{}$
               ■ Need: $0\le\sqrt{2𝒕+1}\le 1\iff 0\le 2𝒕+1\le 1$
               $\rule{0pt}{}$
          ○ Therefore: $-\dfrac{1}{2}\le 𝒕\le 0$
          $\rule{0pt}{}$
          ○ When differentiating inverse trigonometric functions, **checking the domain is essential**,
             not only to ensure the function is defined, but also to guarantee that the derivative represents **real values**.

● [1:16:00](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=4560). 🧩 Example – Derivative of sec⁻¹(e⁻²𝒙) [📷image](../img/Calculus 2 Lecture 6.5/[1-16-00]-01.png) 
     ◉ Step 1 — Start with the chain rule formula:
     $\rule{0pt}{}$
          ○ If $𝒚=\sec^{-1}(𝒖)$, then  
          $\rule{0pt}{}$
            $\dfrac{𝒅𝒚}{𝒅𝑥}=\dfrac{1}{\lvert 𝒖\rvert\sqrt{𝒖^{2}-1}}\cdot\dfrac{𝒅𝒖}{𝒅𝑥}$
            $\rule{0pt}{}$
     ◉ Step 2 — Identify the inner function:
     $\rule{0pt}{}$
          ○ Let $𝒖=e^{-2𝒙}$
          $\rule{0pt}{}$
     ◉ Step 3 — Differentiate 𝒖:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒖}{𝒅𝑥}=e^{-2𝒙}\cdot(-2)$
          $\rule{0pt}{}$
     ◉ Step 4 — Substitute into the formula:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝑥}=\Big(\dfrac{1}{\lvert e^{-2𝒙}\rvert\sqrt{\big(e^{-2𝒙}\big)^{2}-1}}\Big)\cdot\big(-2e^{-2𝒙}\big)$
          $\rule{0pt}{}$
     ◉ Step 5 — Simplify:
     $\rule{0pt}{}$
          ○ $\lvert e^{-2𝒙}\rvert=e^{-2𝒙}$   (always positive)
          $\rule{0pt}{}$
          ○ $\big(e^{-2𝒙}\big)^{2}=e^{-4𝒙}\Rightarrow\dfrac{𝒅𝒚}{𝒅𝑥}=\dfrac{-2e^{-2𝒙}}{e^{-2𝒙}\sqrt{e^{-4𝒙}-1}}$
          $\rule{0pt}{}$
     ◉ Step 6 — Cancel $e^{-2𝒙}$:
     $\rule{0pt}{}$
          ⇒ $\dfrac{𝒅𝒚}{𝒅𝑥}=-\dfrac{2}{\sqrt{e^{-4𝒙}-1}}$
          $\rule{0pt}{}$
     ◉ Final answer:
          ○ $𝒚'=-\dfrac{2}{\sqrt{e^{-4𝒙}-1}}$
          $\rule{0pt}{}$
     ◉ Domain check (important for sec⁻¹):
          ○ Need $\lvert e^{-2𝒙}\rvert\ge 1$
               ■ The inverse function $\sec^{-1}(𝒖)$ is defined only when:
                    ▣ $\lvert 𝒖\rvert\ge 1$
               ■ Why? Because:
                    ▣ $\sec 𝒙=\dfrac{1}{\cos 𝒙}$
                    $\rule{0pt}{}$
               ■ Since $\lvert\cos 𝒙\rvert\le 1$, it follows that $\lvert\sec 𝒙\rvert\ge 1$.
               $\rule{0pt}{}$
               ■ Therefore, the natural domain of $\sec^{-1}(𝒖)$ is:
                    ▣ $\lvert 𝒖\rvert\ge 1$
                    $\rule{0pt}{}$
          ○ $e^{-2𝒙}\ge 1\iff -2𝒙\ge 0\iff 𝒙\le 0$  
          ○ Valid domain: $𝒙\le 0$

● [1:22:29](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=4949). 🧩 Example – Derivative of cot(cos⁻¹(𝒙²)). [📷image](../img/Calculus 2 Lecture 6.5/[1-22-29]-01.png) 
     ◉ Step 1 — Chain rule (outer function cot):
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝑥}\big[\cot(𝒖)\big]=-\csc^{2}(𝒖)\cdot\dfrac{𝒅𝒖}{𝒅𝑥}$
          $\rule{0pt}{}$
          ○ Let $𝒖=\cos^{-1}(𝒙^{2})$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝑥}=-\csc^{2}\big(\cos^{-1}(𝒙^{2})\big)\cdot\dfrac{𝒅}{𝒅𝑥}\big[\cos^{-1}(𝒙^{2})\big]$
          $\rule{0pt}{}$
     ◉ Step 2 — Chain rule (inverse cosine):
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝑥}\big[\cos^{-1}(𝒗)\big]=-\dfrac{1}{\sqrt{1-𝒗^{2}}}\cdot\dfrac{𝒅𝒗}{𝒅𝑥}$
          $\rule{0pt}{}$
          ○ Here $𝒗=𝒙^{2}\Rightarrow\dfrac{𝒅𝒗}{𝒅𝑥}=2𝒙$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝑥}\big[\cos^{-1}(𝒙^{2})\big]=-\Big(\dfrac{1}{\sqrt{1-(𝒙^{2})^{2}}}\Big)\cdot 2𝒙=-\dfrac{2𝒙}{\sqrt{1-𝒙^{4}}}$
          $\rule{0pt}{}$
     ◉ Step 3 — Substitute back and simplify signs:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝑥}=-\csc^{2}\big(\cos^{-1}(𝒙^{2})\big)\cdot\Big(-\dfrac{2𝒙}{\sqrt{1-𝒙^{4}}}\Big)$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝑥}=\dfrac{2𝒙\cdot\csc^{2}\big(\cos^{-1}(𝒙^{2})\big)}{\sqrt{1-𝒙^{4}}}$
          $\rule{0pt}{}$
     ◉ Step 4 — Triangle method to rewrite $\csc^{2}\big(\cos^{-1}(𝒙^{2})\big)$ in terms of 𝒙:
     $\rule{0pt}{}$
          ○ Let $\theta=\cos^{-1}(𝒙^{2})\iff\cos\theta=𝒙^{2}$
          ○ In a right triangle take:
               ■ adjacent $=𝒙^{2}$
               ■ hypotenuse $=1$
               $\rule{0pt}{}$
               ■ opposite $=\sqrt{1-𝒙^{4}}$     (since $1^{2}-(𝒙^{2})^{2}=1-𝒙^{4}$)
          ○ Then:
               ■ $\sin\theta=\dfrac{\text{opposite}}{\text{hypotenuse}}=\sqrt{1-𝒙^{4}}$
               $\rule{0pt}{}$
               ■ $\csc\theta=\dfrac{1}{\sin\theta}=\dfrac{1}{\sqrt{1-𝒙^{4}}}$
               $\rule{0pt}{}$
               ■ $\csc^{2}\theta=\dfrac{1}{1-𝒙^{4}}$
          ○ Therefore:
               ■ $\csc^{2}\big(\cos^{-1}(𝒙^{2})\big)=\dfrac{1}{1-𝒙^{4}}$
     ◉ Final answer:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝑥}=\Big(\dfrac{2𝒙}{1-𝒙^{4}}\Big)\cdot\dfrac{1}{\sqrt{1-𝒙^{4}}}$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝑥}=\dfrac{2𝒙}{(1-𝒙^{4})^{3/2}}$
          $\rule{0pt}{}$
     ◉ Domain note (real-valued):
          ○ The inner function is $\cos^{-1}(𝒙^{2})$, which is only defined when its input lies in $[-1,1]$.
          ○ Therefore we require:
               ■ $𝒙^{2}\in[-1,1]$
          ○ Since $𝒙^{2}$ is always non-negative, this re𝒅𝒖ces to:
               ■ $0\le 𝒙^{2}\le 1$
          ○ Taking square roots gives:
               ■ $\lvert 𝒙\rvert\le 1$
          ○ Hence the valid real domain for the original function is:
               ■ $-1\le 𝒙\le 1$
          ○ Additionally, the derivative contains $\sqrt{1-𝒙^{4}}$ in the denominator.
               ■ To avoid division by zero we must also have $1-𝒙^{4}>0$.
               ■ This again implies $\lvert 𝒙\rvert<1$ (strict inequality for the derivative).
          ○ Final practical domain for the derivative:
               ■ $-1<𝒙<1$

● NOTE: Triangle method simplification (Right Triangle Method)
     ◉ Core idea: represent the inverse angle with a right triangle.
          ○ Assign sides using the defining ratio of the inverse function.
          ○ Use Pythagoras to find the missing side.
          ○ Compute the desired trigonometric function from the triangle.
     ◉ Why this method is so useful (key point):
          ○ It avoids complicated algebraic manipulations.
          ○ It transforms abstract inverse-trig expressions into clear geometric relationships.
          ○ It provides an intuitive visual interpretation of the composition of functions.





Ｉｎｔｅｇｒａｌｓ　Ｉｎｖｏｌｖｉｎｇ　Ｉｎｖｅｒｓｅ　Ｔｒｉｇｏｎｏｍｅｔｒｉｃ　Ｆｕｎｃｔｉｏｎｓ

● [1:32:22](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=5542). Integrals leading to inverse trigonometric functions. [📷image](../img/Calculus 2 Lecture 6.5/[1-32-22]-01.png) 
     ◉ Fundamental inverse-trig integrals:
     $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{\sqrt{1-𝒖^{2}}}\,𝒅𝒖=\sin^{-1}(𝒖)+\mathcal{C}$  ;Works when $\lvert 𝒖\rvert\le 1$.
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{1+𝒖^{2}}\,𝒅𝒖=\tan^{-1}(𝒖)+\mathcal{C}$  ;Valid for all real 𝒖.
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{𝒖\sqrt{𝒖^{2}-1}}\,𝒅𝒖=\sec^{-1}(\lvert 𝒖\rvert)+\mathcal{C}$  ;Requires $\lvert 𝒖\rvert\ge 1$ (same restriction as $\sec^{-1}$).
          $\rule{0pt}{}$
     ◉ Idea behind these formulas:
          ○ Many “complicated-looking” integrals can be transformed into one of these three forms by substitution.
          ○ Once matched, the result is immediately an inverse trigonometric function.
          ○ **We use only the positive formulas because the negative sign is absorbed in the substitution $\dfrac{𝒅𝒖}{𝒅𝒖}$; that is why we do not 
             need integration formulas involving $\cos^{-1}$, $\cot^{-1}$, or $\csc^{-1}$ with a negative sign.**

● [1:35:50](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=5750). 🧩 Example – Integration by substitution leading to $\sin^{-1}(𝒖)$:  $\displaystyle \int \dfrac{1}{\sqrt{1-𝒖^{2}}}\,𝒅𝑢$ [📷image](../img/Calculus 2 Lecture 6.5/[1-35-50]-01.png) 
     ◉ Step 1 — Recognize the inverse-trig form  
          ○ The integrand resembles:
          $\rule{0pt}{}$
               ■ $\displaystyle \int \dfrac{1}{\sqrt{1-𝒖^{2}}}\,𝒅𝑢\rightarrow \sin^{-1}(𝒖)+\mathcal{C}$  
               $\rule{0pt}{}$
          ○ Problem: the denominator contains $16𝒙^{2}$, so it is not in standard form.
     ◉ Step 2 — Make a substitution  
          ○ Let $𝒖=4𝒙$  
          $\rule{0pt}{}$
               ■ Then $\dfrac{𝒅𝑢}{𝒅𝑥}=4$  
               $\rule{0pt}{}$
               ■ So $𝒅𝑥=\dfrac{1}{4}\,𝒅𝑢$  
               $\rule{0pt}{}$
     ◉ Step 3 — Rewrite the integral in terms of 𝒖  
     $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{\sqrt{1-16𝒙^{2}}}\,𝒅𝑥$  
          $\rule{0pt}{}$
          ○ $=\displaystyle \int \dfrac{1}{\sqrt{1-(4𝒙)^{2}}}\cdot\dfrac{1}{4}\,𝒅𝑢$  
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{4}\displaystyle \int \dfrac{1}{\sqrt{1-𝒖^{2}}}\,𝒅𝑢$  
          $\rule{0pt}{}$
     ◉ Step 4 — Apply the fundamental formula  
     $\rule{0pt}{}$
          ○ $\dfrac{1}{4}\displaystyle \int \dfrac{1}{\sqrt{1-𝒖^{2}}}\,𝒅𝑢$  
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{4}\sin^{-1}(𝒖)+\mathcal{C}$  
          $\rule{0pt}{}$
     ◉ Step 5 — Back-substitute  
     $\rule{0pt}{}$
          ○ $\dfrac{1}{4}\sin^{-1}(4𝒙)+\mathcal{C}$  
          $\rule{0pt}{}$
     ◉ Key idea to remember  
          ○ The goal of the substitution is to **match exactly** the pattern $\dfrac{1}{\sqrt{1-𝒖^{2}}}$  so we can use the inverse sine formula directly.

● [1:39:30](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=5970). 🧩 Example – :  $\displaystyle \int \dfrac{1}{\sqrt{25-𝒙^{2}}}\,𝒅𝑥$ [📷image](../img/Calculus 2 Lecture 6.5/[1-39-30]-01.png) 
$\rule{0pt}{}$
     ◉ Step 1 — Factor the constant:
          ○ Rewrite:
               ■  $\displaystyle \int \dfrac{1}{\sqrt{25-𝒙^{2}}}\,𝒅𝑥$
               $\rule{0pt}{}$
               ■ $=\displaystyle \int \dfrac{1}{5\sqrt{1-(𝒙/5)^{2}}}\,𝒅𝑥$
               $\rule{0pt}{}$
     ◉ Step 2 — 𝒖–substitution:
          ○ Let $𝒖=𝒙/5$  
          $\rule{0pt}{}$
          ○ Then: $𝒅𝑢=\dfrac{1}{5}\,𝒅𝑥\iff 𝒅𝑥=5\,𝒅𝑢$
     ◉ Step 3 — Substitute into the integral:
     $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{5\sqrt{1-𝒖^{2}}}\cdot 5\,𝒅𝑢$  
          $\rule{0pt}{}$
          ○ $=\displaystyle \int \dfrac{1}{\sqrt{1-𝒖^{2}}}\,𝒅𝑢$  
          $\rule{0pt}{}$
     ◉ Step 4 — Apply the standard formula:
     $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{\sqrt{1-𝒖^{2}}}\,𝒅𝑢=\sin^{-1}(𝒖)+\mathcal{C}$  
          $\rule{0pt}{}$
     ◉ Step 5 — Return to 𝒙:
          ○ $\sin^{-1}(𝒙/5)+\mathcal{C}$

● [1:42:45](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=6165). 🧩 Example –: $\displaystyle \int \dfrac{e^{𝒙}}{e^{2𝒙}+1}\,𝒅𝑥$ [📷image](../img/Calculus 2 Lecture 6.5/[1-42-45]-01.png) 
$\rule{0pt}{}$
     ◉ Step 1 — Rewrite to expose a perfect “something² + 1”:
     $\rule{0pt}{}$
          ○ $e^{2𝒙}=\left(e^{𝒙}\right)^{2}$
          $\rule{0pt}{}$
          ○  $\displaystyle \int \dfrac{e^{𝒙}}{e^{2𝒙}+1}\,𝒅𝑥=\displaystyle \int \dfrac{e^{𝒙}}{\left(e^{𝒙}\right)^{2}+1}\,𝒅𝑥$
          $\rule{0pt}{}$
     ◉ Step 2 — Substitution:
          ○ Let $𝒖=e^{𝒙}$
          ○ Then $𝒅𝑢=e^{𝒙}\,𝒅𝑥$
     ◉ Step 3 — Substitute:
     $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{e^{𝒙}}{\left(e^{𝒙}\right)^{2}+1}\,𝒅𝑥$
          $\rule{0pt}{}$
               ■  $\displaystyle \int \dfrac{1}{𝒖^{2}+1}\,𝒅𝑢$
               $\rule{0pt}{}$
     ◉ Step 4 — Use the standard inverse trig antiderivative:
     $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{𝒖^{2}+1}\,𝒅𝑢=\tan^{-1}(𝒖)+\mathcal{C}$
          $\rule{0pt}{}$
     ◉ Step 5 — Back-substitute:
          ○ $\tan^{-1}\left(e^{𝒙}\right)+\mathcal{C}$

● [1:46:58](https://www.youtube.com/watch?v=ST3ORfqVYQw&t=6418). 🧩 Example –: $\displaystyle \int \dfrac{1}{𝒙\sqrt{9𝒙^{2}-1}}\,𝒅𝑥$ [📷image](../img/Calculus 2 Lecture 6.5/[1-46-58]-01.png) 
$\rule{0pt}{}$
     ◉ Step 1 — Recognize structure:
          ○ Inside the root we have $9𝒙^{2}-1$, which suggests something like $\sqrt{𝒖^{2}-1}$
     ◉ Step 2 — Choose substitution:
          ○ Let $𝒖=3𝒙$
          $\rule{0pt}{}$
          ○ Then $\dfrac{𝒅𝑢}{𝒅𝑥}=3\Rightarrow 𝒅𝑥=\dfrac{1}{3}\,𝒅𝑢$
          $\rule{0pt}{}$
     ◉ Step 3 — Rewrite the integral in terms of 𝒖:
     $\rule{0pt}{}$
          ○ $𝒙=\dfrac{𝒖}{3}$
          $\rule{0pt}{}$
          ○ $\sqrt{9𝒙^{2}-1}=\sqrt{𝒖^{2}-1}$
          ○ So the integral becomes:
          $\rule{0pt}{}$
               ■  $\displaystyle \int \dfrac{1}{\left(𝒖/3\right)\sqrt{𝒖^{2}-1}}\cdot\dfrac{1}{3}\,𝒅𝑢$
               $\rule{0pt}{}$
     ◉ Step 4 — Simplify constants:
     $\rule{0pt}{}$
          ○ $=\displaystyle \int \dfrac{1}{𝒖\sqrt{𝒖^{2}-1}}\,𝒅𝑢$
          $\rule{0pt}{}$
     ◉ Step 5 — Use standard formula:
     $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{𝒖\sqrt{𝒖^{2}-1}}\,𝒅𝑢=\sec^{-1}(\lvert 𝒖\rvert)+\mathcal{C}$
          $\rule{0pt}{}$
     ◉ Step 6 — Back-substitute:
     $\rule{0pt}{}$
          ○ $\sec^{-1}(\lvert 3𝒙\rvert)+\mathcal{C}$
