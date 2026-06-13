-----------------------------------** Ｃａｌｃｕｌｕｓ　２　ｌｅｃｔｕｒｅ　６．２：　Dｅｒｉｖａｔｉｖｅｓ　Oｆ　Iｎｖｅｒｓｅ　Fｕｎｃｔｉｏｎｓ**------------------------------—




Ｅｘｉｓｔｅｎｃｅ,  Ｎｏｔａｔｉｏｎ ａｎｄ Ａｌｇｅｂｒａｉｃ Ｐｒｏｐｅｒｔｉｅｓ ｏｆ Ｉｎｖｅｒｓｅ Ｆｕｎｃｔｉｏｎｓ

● [0:00](https://www.youtube.com/watch?v=HnsUNWNYZ28&t=0). Introduction to Section 6.2: Properties and derivatives of inverse functions.

● [0:29](https://www.youtube.com/watch?v=HnsUNWNYZ28&t=29). Fundamental requirements for the existence of an inverse function.
     ◉ One-to-one functions and uniqueness of outputs for each input.
     ◉ Use of the horizontal line test to verify injectivity. [📷image](../img/Calculus 2 Lecture 6.2/[0-29]-02.png)
     ◉ Definition of the inverse function by interchanging inputs and outputs.[📷image](../img/Calculus 2 Lecture 6.2/[0-29]-01.png)
          ○ In a function, the input is $𝒙$ and the output is $𝒚$. To obtain the inverse function, the roles of input and output are exchanged: 
               ■ What was the input becomes the output, and what was the output becomes the input. That is, if the original function maps
                 $𝒙\rightarrow 𝒚$ the inverse function maps $𝒚\rightarrow 𝒙$ In practice, to compute an inverse function:
                    ▣ 1) Write $𝒚=𝒇(𝒙)$
                    ▣ 2) Interchange $𝒙$ and $𝒚$
                    ▣ 3) Solve for $𝒚$
                    ▣ 🧩 Example – : $𝒇(𝒙)=2𝒙+1$
                         ▢ After interchanging variables: $𝒙=2𝒚+1$
                         $\rule{0pt}{}$
                         ▢ Solving for $𝒚=\dfrac{𝒙-1}{2}$

● [1:53](https://www.youtube.com/watch?v=HnsUNWNYZ28&t=113). Notation and basic properties of 𝒇⁻¹. [📷image](../img/Calculus 2 Lecture 6.2/[1-53]-01.png)
     ◉ Distinction between inverse notation $𝒇^{-1}$ and exponents.
     ◉ Verification of inverses using composition of functions.
     $\rule{0pt}{}$
          ○ Identity property: $𝒇^{-1}(𝒇(𝒙))=𝒙$
          $\rule{0pt}{}$
          ○ Identity property: $𝒇(𝒇^{-1}(𝒙))=𝒙$
          $\rule{0pt}{}$
               ■ The $𝒙$ in $𝒇^{-1}(𝒙)$ is not the same $𝒙$ as in the original function; it represents a y-value.
          




Ｆｉｎｄｉｎｇ ｔｈｅ Ｉｎｖｅｒｓｅ Ｆｕｎｃｔｉｏｎ

● [4:17](https://www.youtube.com/watch?v=HnsUNWNYZ28&t=257). Algebraic procedure to determine the inverse function. [📷image-1](../img/Calculus 2 Lecture 6.2/[4-17]-01.png)  [📷image-2](../img/Calculus 2 Lecture 6.2/[4-17]-02.png)
     ◉ Steps for interchanging the variables $𝒙$ and $𝒚$.
          ○ 🧩 Example – Find the inverse: $𝒇(𝒙)=\dfrac{1}{\sqrt{(2𝒙-3)}}$.
               ■ Write the function using $𝒚$:
               $\rule{0pt}{}$
                    ▣ $𝒚=\dfrac{1}{\sqrt{(2𝒙-3)}}$
                    $\rule{0pt}{}$
               ■ Interchange variables:
               $\rule{0pt}{}$
                    ▣ $𝒙=\dfrac{1}{\sqrt{(2𝒚-3)}}$
                    $\rule{0pt}{}$
               ■ Solve for $𝒚$:
               $\rule{0pt}{}$
                    ▣ $\sqrt{(2𝒚-3)}=\dfrac{1}{𝒙}$
                    $\rule{0pt}{}$
                    ▣ $2𝒚-3=\left(\dfrac{1}{𝒙}\right)^{2}$
                    $\rule{0pt}{}$
                    ▣ $2𝒚-3=\dfrac{1}{𝒙^{2}}$
                    $\rule{0pt}{}$
                    ▣ $2𝒚=\dfrac{1}{𝒙^{2}}+3$
                    $\rule{0pt}{}$
                    ▣ $𝒚=\dfrac{1}{2𝒙^{2}}+\dfrac{3}{2}$
                    $\rule{0pt}{}$
                    ▣ $𝒚=\dfrac{1+3𝒙^{2}}{2𝒙^{2}}$
                    $\rule{0pt}{}$
               ■ Definition of the inverse function:
               $\rule{0pt}{}$
                    ▣ $𝒇^{-1}(𝒙)=\dfrac{1+3𝒙^{2}}{2𝒙^{2}}$
                    $\rule{0pt}{}$
               ■ Verification by composition:
               $\rule{0pt}{}$
                    ▣ $𝒇^{-1}(𝒇(𝒙))=\dfrac{1+3\left(\dfrac{1}{\sqrt{(2𝒙-3)}}\right)^{2}}{2\left(\dfrac{1}{\sqrt{(2𝒙-3)}}\right)^{2}}$
                    $\rule{0pt}{}$
                         ▢ Combine terms over a common denominator:
                         $\rule{0pt}{}$
                              ▲ $\dfrac{1+\dfrac{3}{2𝒙-3}}{\dfrac{2}{2𝒙-3}}$
                              $\rule{0pt}{}$
                                   ◭ Multiply numerator and denominator by $(2𝒙-3)$:
                                   $\rule{0pt}{}$
                                        △ $\dfrac{2𝒙-3+3}{2}=\dfrac{2𝒙}{2}=𝒙$ — Each function exactly undoes what the other does; $𝒇^{-1}(𝒇(𝒙))=𝒙$ ∎

● [10:40](https://www.youtube.com/watch?v=HnsUNWNYZ28&t=640).  The idea behind an inverse function.
     ◉ For every one-to-one function, its inverse can be found and is also one-to-one.
   



Ｇｒａｐｈｉｃａｌ Ｉｎｔｅｒｐｒｅｔａｔｉｏｎ  Ｄｅｒｉｖａｔｉｖｅ ｏｆ ｔｈｅ Ｉｎｖｅｒｓｅ Ｆｕｎｃｔｉｏｎ

● [11:05](https://www.youtube.com/watch?v=HnsUNWNYZ28&t=665). Graphical and geometric relationship of inverse functions. [📷image](../img/Calculus 2 Lecture 6.2/[11-05]-02.png)
     ◉ 1) Symmetry and reflection of the graph across the identity line $𝒚=𝒙$.
     ◉ 2) I̲f̲ $𝒇$ is continuous on a given domain, t̲h̲e̲n̲ $𝒇^{-1}$ is continuous on a corresponding domain.
          ○ Continuity theorems for inverse functions.
               ■ Set relationship: the domain of $𝒇$ becomes the range of $𝒇^{-1}$. 
               ■ The range of $𝒇$ determines the domain of $𝒇^{-1}$.
               ■ 🧩 Example – Domain and range shown graphically. [📷image](../img/Calculus 2 Lecture 6.2/[11-05]-01.png)
                    ▣ The graph of $𝒇$ and its inverse illustrate how the domain of $𝒇$ becomes the range of $𝒇^{-1}$ under reflection across $𝒚=𝒙$.
     ◉ [17:35](https://www.youtube.com/watch?v=HnsUNWNYZ28&t=1055). 3) Differentiability and computation of derivatives of inverse functions.
          ○ Existence theorem for the derivative of $𝒇^{-1}$ when $𝒇$ is differentiable.
               ■ I̲f̲ $𝒇$ is differentiable, t̲h̲e̲n̲ $𝒇^{-1}$ is also differentiable.
          ○ Derivation of the formula for the derivative of the inverse function.
               ■ Derivative formula:
                    ▣ $\dfrac{d}{d𝒙}\Big[𝒇^{-1}(𝒙)\Big]=\dfrac{1}{𝒇'(𝒇^{-1}(𝒙))}$ OR
                    $\rule{0pt}{}$
                         ▢ If $𝓰(𝒙)=𝒇^{-1}$ then $𝓰'(𝒙)=\dfrac{1}{𝒇'(𝓰(𝒙))}$
                       




Ｅｖａｌｕａｔｉｎｇ Ｉｎｖｅｒｓｅ Ｆｕｎｃｔｉｏｎｓ

● [21:5]. Evaluating inverse functions at specific points without explicit computation.
     ◉ S͟t͟a͟t͟m͟e͟n͟t͟  :  $𝒇(𝒙)=𝓪$   ⇔   $𝒇'(𝓪)=𝒙$
     $\rule{0pt}{}$
     ◉ [22:27](https://www.youtube.com/watch?v=HnsUNWNYZ28&t=1347). 🧩 Example – : $𝒇(𝒙)=𝒙^{3}-1$, find $𝒇^{-1}(𝓪)$ when $𝓪=-1$ [📷image](../img/Calculus 2 Lecture 6.2/[22-27]-01.png)
          ○ 1) Set $𝒇(𝒙)=𝓪$:
               ■ $𝒙^{3}-1=-1$
          ○ 2) Solve for $𝒙$:
               ■ $𝒙^{3}=0$
               ■ $𝒙=0$
          ○ 3) Find $𝒇^{-1}(𝓪)$:
          $\rule{0pt}{}$
               ■ $𝒇^{-1}(-1)=0$ 
     ◉ [27:20](https://www.youtube.com/watch?v=HnsUNWNYZ28&t=1640). 🧩 Example – $𝒇(𝒙)=\left(\dfrac{3}{\pi}\right)𝒙+\sin(𝒙)$, find $𝒇^{-1}(𝓪)$ when $𝓪=1$ [📷image](../img/Calculus 2 Lecture 6.2/[27-20]-01.png)
     $\rule{0pt}{}$
          ○ S͟t͟a͟t͟m͟e͟n͟t͟  : $𝒇(𝒙)=𝓪$   ⇔   $𝒇^{-1}(𝓪)=𝒙$
          $\rule{0pt}{}$
          ○ 1) Set $𝒇(𝒙)=𝓪$:
          $\rule{0pt}{}$
               ■ $\left(\dfrac{3}{\pi}\right)𝒙+\sin(𝒙)=1$
               $\rule{0pt}{}$
          ○ 2) Solve for $𝒙$:
          $\rule{0pt}{}$
               ■ $𝒙=\dfrac{\pi}{6}$
               $\rule{0pt}{}$
          ○ 3) Verification:
          $\rule{0pt}{}$
               ■ $\left(\dfrac{3}{\pi}\right)\left(\dfrac{\pi}{6}\right)+\sin\left(\dfrac{\pi}{6}\right)=\dfrac{1}{2}+\dfrac{1}{2}=1$
               $\rule{0pt}{}$
          ○ 4) Evaluate the inverse:
          $\rule{0pt}{}$
               ■ $𝒇^{-1}(1)=\dfrac{\pi}{6}$



 

Ａｐｐｌｉｃａｔｉｏｎｓ ｏｆ ｔｈｅ Ｉｎｖｅｒｓｅ Ｄｅｒｉｖａｔｉｖｅ

● [37:54](https://www.youtube.com/watch?v=HnsUNWNYZ28&t=2274). Application of the derivative of the inverse function evaluated at a given point. 
     ◉ 🧩 Example – Find the derivative of the inverse of: $𝒇(𝒙)=𝒙^{3}$ at the point $(2,8)$ where $𝒈=𝒇^{-1}$. [📷image](../img/Calculus 2 Lecture 6.2/[37-54]-01.png)    
          ○ Identify the given point on 𝒇:
               ■ $𝒇(2)=2^{3}=8$
          ○ Compute the derivative of 𝒇:
               ■ $𝒇'(𝒙)=3𝒙^{2}$
          ○ Identify the corresponding value on the inverse function:
               ■ $𝒈(8)=2$
          ○ Apply the derivative formula for inverse functions:
               ■ $𝒈'(8)=\dfrac{1}{𝒇'(2)}$
               $\rule{0pt}{}$
               ■ $𝒈'(8)=\dfrac{1}{3\cdot 2^{2}}$
               $\rule{0pt}{}$
               ■ $𝒈'(8)=\dfrac{1}{12}$
               $\rule{0pt}{}$
     ◉ [39:00](https://www.youtube.com/watch?v=HnsUNWNYZ28&t=2340). 🧩 Example – Find the derivative of the inverse of $𝒇(𝒙)=\left(𝒙^{2}+1\right)^{3}$ at the point $(1,8)$, where $𝒈=𝒇^{-1}$. [📷image](../img/Calculus 2 Lecture 6.2/[39-00]-01.png)    
          ○ Identify the given point on 𝒇:
               ■ $𝒇(1)=(1^{2}+1)^{3}=8$
          ○ Identify the corresponding value on the inverse function:
               ■ $𝒈(8)=1$
          ○ Compute the derivative of 𝒇:
          $\rule{0pt}{}$
               ■ $𝒇'(𝒙)=6𝒙(𝒙^{2}+1)^{2}$
               $\rule{0pt}{}$
          ○ Apply the derivative formula for inverse functions:
          $\rule{0pt}{}$
               ■ $𝒈'(8)=\dfrac{1}{𝒇'(𝒈(8))}$
               $\rule{0pt}{}$
               ■ $𝒈'(8)=\dfrac{1}{𝒇'(1)}$
               $\rule{0pt}{}$
               ■ $𝒈'(8)=\dfrac{1}{24}$
