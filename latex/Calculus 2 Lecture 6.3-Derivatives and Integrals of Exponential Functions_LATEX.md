-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ６．３： Ｄｅｒｉｖａｔｉｖｅｓ ａｎｄ Ｉｎｔｅｇｒａｌｓ ｏｆ Ｅｘｐｏｎｅｎｔｉａｌ Ｆｕｎｃｔｉｏｎｓ**---------------------------------





Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:01](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=1). Introduction to exponential functions and Euler’s number $𝓮$. [📷image](../img/Calculus 2 Lecture 6.3/[0-01]-01.png)
     ◉ Definition of the number $𝓮$ as the value satisfying $\ln(𝓮)=1$.
     ◉ Connection with area under the curve.
          ○ Definition of the natural logarithm as an integral:
          $\rule{0pt}{}$
               ■ $\ln(𝒙)=\displaystyle \int_{1}^{𝒙}\dfrac{1}{𝒕}\,𝒅𝒕$
               $\rule{0pt}{}$
          ○ Interpretation of $\ln(𝓮)$ as area under the curve:
          $\rule{0pt}{}$
               ■ $\ln(𝓮)=\displaystyle \int_{1}^{𝓮}\dfrac{1}{𝒕}\,𝒅𝒕=1$
               $\rule{0pt}{}$
     ◉ Proof of the existence of $𝓮$ using the Intermediate Value Theorem.
          ○ Continuity of $\ln$ on $(0,\infty)$.
          ○ Range of $\ln$ is $(-\infty,\infty)$.
          ○ By the Intermediate Value Theorem, there exists a value $𝓮$ such that $\ln(𝓮)=1$.
     ◉ Equivalence between logarithmic and exponential notation.
          ○ $\ln(𝒚)=𝒙$   ⇔   $𝓮^{𝒙}=𝒚$
     ◉ [5:55](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=355). Cancellation properties used in solving equations.
          ○ Proof of the identity $\ln(𝓮^{𝒙})=𝒙$.
               ■ Let $𝒚=𝓮^{𝒙}$.
                    ▣ $\ln(𝒚)=\ln(𝓮^{𝒙})$
               ■ Use the equivalence $\ln(𝒚)=𝒙$ ⇔ $𝓮^{𝒙}=𝒚$.
                    ▣ Since $𝒚=𝓮^{𝒙}$, then $\ln(𝒚)=𝒙$
                    ▣ Therefore, $\ln(𝓮^{𝒙})=𝒙$
                    $\rule{0pt}{}$
          ○ Proof of the identity $𝓮^{\ln(𝒙)}=𝒙$.
               ■ Let $𝒙>0$ and set $𝒖=\ln(𝒙)$.
                    ▣ $\ln(𝒙)=𝒖$
               ■ Convert to exponential form using $\ln(𝒚)=𝒙$ ⇔ $𝓮^{𝒙}=𝒚$.
                    ▣ $𝓮^{𝒖}=𝒙$
               ■ Substitute $𝒖=\ln(𝒙)$.
                    ▣ $𝓮^{\ln(𝒙)}=𝒙$


        


Ｓｏｌｖｉｎｇ Ｅｑｕａｔｉｏｎｓ ｗｉｔｈ $𝓮$ ａｎｄ $\ln$

● Algebraic methodology for solving equations involving $𝓮$ and $\ln$.
     ◉ [8:30](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=510). 🧩 Example – Variable isolation example: $𝓮^{(4-5𝒙)}=9$. [📷image](../img/Calculus 2 Lecture 6.3/[8-30]-01.png)
          ○ Apply the natural logarithm to both sides:
          $\rule{0pt}{}$
               ■ $\ln(𝓮^{(4-5𝒙)})=\ln 9$
               $\rule{0pt}{}$
          ○ Use the cancellation property $\ln(𝓮^{𝒖})=𝒖$:
               ■ $4-5𝒙=\ln 9$
          ○ Isolate the variable $𝒙$:
               ■ $-5𝒙=-4+\ln 9$
               $\rule{0pt}{}$
               ■ $𝒙=\dfrac{4}{5}-\dfrac{\ln 9}{5}$
               $\rule{0pt}{}$
     ◉ [11:14](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=674). 🧩 Example – Variable isolation example: $3𝓮^{(5𝒙-1)}=2$. [📷image](../img/Calculus 2 Lecture 6.3/[11-14]-01.png)
          ○ Isolate the exponential term:
          $\rule{0pt}{}$
               ■ $𝓮^{(5𝒙-1)}=\dfrac{2}{3}$
               $\rule{0pt}{}$
          ○ Apply the natural logarithm to both sides:
          $\rule{0pt}{}$
               ■ $\ln(𝓮^{(5𝒙-1)})=\ln\left(\dfrac{2}{3}\right)$
               $\rule{0pt}{}$
          ○ Use the cancellation property $\ln(𝓮^{𝒖})=𝒖$:
          $\rule{0pt}{}$
               ■ $5𝒙-1=\ln\left(\dfrac{2}{3}\right)$
               $\rule{0pt}{}$
          ○ Solve for $𝒙$:
          $\rule{0pt}{}$
               ■ $5𝒙=\ln\left(\dfrac{2}{3}\right)+1$
               $\rule{0pt}{}$
               ■ $𝒙=\dfrac{\ln\left(\dfrac{2}{3}\right)+1}{5}$
               $\rule{0pt}{}$
     ◉ [13:30](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=810). 🧩 Example – Variable isolation example: $\ln(7𝒙-1)=9$. [📷image](../img/Calculus 2 Lecture 6.3/[13-30]-01.png)
          ○ Convert from logarithmic to exponential form:
          $\rule{0pt}{}$
               ■ $7𝒙-1=𝓮^{9}$
          ○ Solve for $𝒙$:
               ■ $7𝒙=𝓮^{9}+1$
               $\rule{0pt}{}$
               ■ $𝒙=\dfrac{𝓮^{9}+1}{7}$
               $\rule{0pt}{}$
     ◉ [14:40](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=880). 🧩 Example – Solve the logarithmic equation: $\ln 𝒙+\ln(𝒙-1)=\ln 2$. [📷image](../img/Calculus 2 Lecture 6.3/[14-40]-01.png) 
          ○ Combine logarithms:
          $\rule{0pt}{}$
               ■ $\ln\Big[𝒙(𝒙-1)\Big]=\ln 2$
               $\rule{0pt}{}$
          ○ Convert to exponential form:
          $\rule{0pt}{}$
               ■ $𝓮^{\ln\Big[𝒙(𝒙-1)\Big]}=𝓮^{\ln 2}$
               $\rule{0pt}{}$
          ○ Use the cancellation property $𝓮^{\ln(𝒙)}=𝒙$:
               ■ $𝒙(𝒙-1)=2$
          ○ Solve the resulting polynomial equation:
               ■ $𝒙^{2}-𝒙=2$
               ■ $𝒙^{2}-𝒙-2=0$
               ■ $(𝒙-2)(𝒙+1)=0$
               ■ $𝒙=2$, $𝒙=-1$
     ◉ [18:20](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=1100). 🧩 Example – Solve the exponential equation: $𝓮^{(2𝒙)}-5𝓮^{𝒙}+6=0$. [📷image](../img/Calculus 2 Lecture 6.3/[18-20]-01.png) 
          ○ Rewrite using a substitution form:
          $\rule{0pt}{}$
               ■ $(𝓮^{𝒙})^{2}-5(𝓮^{𝒙})+6=0$
               $\rule{0pt}{}$
          ○ Substitute $𝒚=𝓮^{𝒙}$:
          $\rule{0pt}{}$
               ■ $𝒚^{2}-5𝒚+6=0$
               $\rule{0pt}{}$
          ○ Factor and solve for $𝒚$:
          $\rule{0pt}{}$
               ■ $(𝒚-3)(𝒚-2)=0$
               $\rule{0pt}{}$
               ■ $𝒚=3$, $𝒚=2$
          ○ Convert back to $𝒙$:
               ■ $𝓮^{𝒙}=3$
                    ▣ $\ln(𝓮^{𝒙})=\ln 3$
                         ▢ $𝒙=\ln 3$
               ■ $𝓮^{𝒙}=2$
                    ▣ $\ln(𝓮^{𝒙})=\ln 2$
                         ▢ $𝒙=\ln 2$

        


Ａｎａｌｙｔｉｃ Ｐｒｏｐｅｒｔｉｅｓ ｏｆ $𝓮^{𝒙}$

● [24:40](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=1480). Analytical properties and graphical representation of the function $𝓮^{𝒙}$. [📷image](../img/Calculus 2 Lecture 6.3/[24-40]-01.png)
     ◉ Domain and range.
          ○ Domain of $𝓮^{𝒙}$:
               ■ $D=(-\infty,\infty)$
          ○ Range of $𝓮^{𝒙}$:
               ■ $R=(0,\infty)$
     ◉ Continuity and concavity.
          ○ Continuity on the entire real line:
               ■ $𝓮^{𝒙}$ is continuous on $(-\infty,\infty)$
          ○ Concavity:
               ■ $𝓮^{𝒙}$ is concave up on $(-\infty,\infty)$
     ◉ Asymptotic behavior and fundamental limits.
          ○ Limits of the exponential function:
               ■ $\displaystyle \lim_{x\to\infty}𝓮^{𝒙}=\infty$
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to-\infty}𝓮^{𝒙}=0$
               $\rule{0pt}{}$
          ○ Corresponding limits of the logarithmic function:
               ■ $\displaystyle \lim_{x\to\infty}\ln 𝒙=\infty$
               $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to 0^+}\ln 𝒙=-\infty$
               $\rule{0pt}{}$

              
    


Ｌｉｍｉｔｓ ｗｉｔｈ Ｎｅｇａｔｉｖｅ Ｅｘｐｏｎｅｎｔｓ

● Evaluation of complex limits involving negative powers of $e$.
     ◉ Algebraic manipulation by dividing through by the dominant exponential term in the denominator, which grows without bound.
     ◉ Analysis of infinitesimal terms and evaluation of constants in the limit.
    
● [34:00](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=2040). 🧩 Example – Limit involving exponential functions as $𝒙\rightarrow -\infty$: $\displaystyle \lim_{x\to-\infty}\dfrac{𝓮^{-𝒙}-2𝓮^{(2𝒙)}}{𝓮^{(-2𝒙)}+3𝓮^{(2𝒙)}}$ [📷image](../img/Calculus 2 Lecture 6.3/[34-00]-01.png)
$\rule{0pt}{}$
     ◉ Simplify by dividing numerator and denominator by $𝓮^{(-2𝒙)}$, It is the dominant term (it grows without bound):
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to-\infty}\dfrac{𝓮^{𝒙}-2𝓮^{(4𝒙)}}{1+3𝓮^{(4𝒙)}}$
          $\rule{0pt}{}$
     ◉ Evaluate the limit using exponential behavior:
     $\rule{0pt}{}$
          ○ As $𝒙\rightarrow -\infty$, $𝓮^{𝒙}\rightarrow 0$ and $𝓮^{(4𝒙)}\rightarrow 0$
          $\rule{0pt}{}$
     ◉ Final evaluation:
     $\rule{0pt}{}$
          ○ $\dfrac{0-0}{1+0}=0$

● [40:41](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=2441). 🧩 Example – Evaluate the limit: $\displaystyle \lim_{x\to 0^+}\dfrac{{𝓮^{1/\ln 𝒙}}}{2+\cos\big(\pi 𝓮^{-𝒙}\big)}$. [📷image](../img/Calculus 2 Lecture 6.3/[40-41]-01.png)
$\rule{0pt}{}$
     ◉ Analyze each component as $𝒙\rightarrow 0^+$.
          ○ Exponential term:
               ■ $\ln 𝒙\rightarrow -\infty$
               $\rule{0pt}{}$
                    ▣ $\dfrac{1}{\ln 𝒙}\rightarrow 0$
                    $\rule{0pt}{}$
                         ▢ $𝓮^{\dfrac{1}{\ln 𝒙}}\rightarrow 1$
                         $\rule{0pt}{}$
          ○ Trigonometric term:
               ■ $𝓮^{-𝒙}\rightarrow 1$
                    ▣ $\pi 𝓮^{-𝒙}\rightarrow \pi$
                    $\rule{0pt}{}$
                         ▢ $\cos\big(\pi 𝓮^{-𝒙}\big)\rightarrow \cos(\pi)=-1$
                         $\rule{0pt}{}$
          ○ Combine the limits:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to 0^+}\dfrac{𝓮^{1/\ln 𝒙}}{2+\cos\big(\pi 𝓮^{-𝒙}\big)}=\dfrac{1}{2+(-1)}$
                    ▣ $=1$


    


Ｄｅｒｉｖａｔｉｖｅｓ and  Ｉｎｔｅｇｒａｌｓ ｏｆ Ｎａｔｕｒａｌ Ｅｘｐｏｎｅｎｔｉａｌ Ｆｕｎｃｔｉｏｎｓ

● [45:00](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=2700). Differential calculus applied to natural exponential functions. [📷image](../img/Calculus 2 Lecture 6.3/[45-00]-01.png)
     ◉ Fundamental derivative rule.
          ○ Statement of the theorem:
          $\rule{0pt}{}$
               ■ $\dfrac{d}{d𝒙}\Big[𝓮^{𝒙}\Big]=𝓮^{𝒙}$
               $\rule{0pt}{}$
     ◉ Analytical proof using logarithmic differentiation.
          ○ Define the function:
               ■ $𝒚=𝓮^{𝒙}$
          ○ Take natural logarithms on both sides:
               ■ $\ln 𝒚=\ln(𝓮^{𝒙})$
               ■ $\ln 𝒚=𝒙$
          ○ Differentiate implicitly with respect to $𝒙$:
          $\rule{0pt}{}$
               ■ $\dfrac{d}{d𝒙}\Big[\ln 𝒚\Big]=\dfrac{d}{d𝒙}\Big[𝒙\Big]$
               $\rule{0pt}{}$
               ■ $\dfrac{1}{𝒚}\cdot\dfrac{d𝒚}{d𝒙}=1$
               $\rule{0pt}{}$
          ○ Solve for $d𝒚/d𝒙$:
          $\rule{0pt}{}$
               ■ $\dfrac{d𝒚}{d𝒙}=𝒚$
               $\rule{0pt}{}$
               ■ $\dfrac{d𝒚}{d𝒙}=𝓮^{𝒙}$
               $\rule{0pt}{}$
     ◉ Chain rule extension.
          ○ General exponential function:
          $\rule{0pt}{}$
               ■ $\dfrac{d}{d𝒙}\Big[𝓮^{𝒇(𝒙)}\Big]=𝓮^{𝒇(𝒙)}\cdot\dfrac{d}{d𝒙}\Big[𝒇(𝒙)\Big]$
               $\rule{0pt}{}$
          ○ Equivalent notation using an auxiliary variable:
               ■ Let $𝒖=𝒇(𝒙)$
               $\rule{0pt}{}$
               ■ $\dfrac{d}{d𝒙}\Big[𝓮^{𝒖}\Big]=𝓮^{𝒖}\cdot\dfrac{d𝒖}{d𝒙}$
               $\rule{0pt}{}$
     ◉ [50:40](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=3040). 🧩 Example – Differentiate the function: $𝓮^{-𝒙^{3}}$. [📷image](../img/Calculus 2 Lecture 6.3/[50-40]-01.png)
          ○ Identify the composite structure:
               ■ Outer function: $𝓮^{𝒖}$
               ■ Inner function: $𝒖=-𝒙^{3}$
          ○ Apply the chain rule:
          $\rule{0pt}{}$
               ■ $\dfrac{d}{d𝒙}\Big[𝓮^{-𝒙^{3}}\Big]=𝓮^{-𝒙^{3}}\cdot\dfrac{d}{d𝒙}\Big[-𝒙^{3}\Big]$
               $\rule{0pt}{}$
          ○ Differentiate the inner function:
          $\rule{0pt}{}$
               ■ $\dfrac{d}{d𝒙}\Big[-𝒙^{3}\Big]=-3𝒙^{2}$
               $\rule{0pt}{}$
          ○ Final result:
          $\rule{0pt}{}$
               ■ $\dfrac{d}{d𝒙}\Big[𝓮^{-𝒙^{3}}\Big]=-3𝒙^{2}\cdot 𝓮^{-𝒙^{3}}$
               $\rule{0pt}{}$
     ◉ [52:25](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=3145). 🧩 Example – Differentiate the function: $𝒙^{2}𝓮^{-2𝒙}$. [📷image](../img/Calculus 2 Lecture 6.3/[52-25]-01.png)
          ○ Reminder: first identify which rules are needed to compute the derivative.
               ■ Product rule.
               ■ Chain rule.
          ○ Apply the product rule:
          $\rule{0pt}{}$
               ■ $\dfrac{d}{d𝒙}\Big[𝒙^{2}𝓮^{-2𝒙}\Big]=\dfrac{d}{d𝒙}\Big[𝒙^{2}\Big]\cdot 𝓮^{-2𝒙}+𝒙^{2}\cdot\dfrac{d}{d𝒙}\Big[𝓮^{-2𝒙}\Big]$
               $\rule{0pt}{}$
          ○ Differentiate each factor:
          $\rule{0pt}{}$
               ■ $\dfrac{d}{d𝒙}\Big[𝒙^{2}\Big]=2𝒙$
               $\rule{0pt}{}$
               ■ $\dfrac{d}{d𝒙}\Big[𝓮^{-2𝒙}\Big]=𝓮^{-2𝒙}\cdot\dfrac{d}{d𝒙}\Big[-2𝒙\Big]$
               $\rule{0pt}{}$
                    ▣ $\dfrac{d}{d𝒙}\Big[-2𝒙\Big]=-2$
                    $\rule{0pt}{}$
          ○ Combine the results:
          $\rule{0pt}{}$
               ■ $2𝒙𝓮^{-2𝒙}-2𝒙^{2}𝓮^{-2𝒙}$
          ○ Factor the common terms:
          $\rule{0pt}{}$
               ■ $2𝒙𝓮^{-2𝒙}(1-𝒙)$
     ◉ [56:10](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=3370). 🧩 Example – Differentiate the function $𝒚=\ln(𝓮^{\sqrt{𝒙}}+𝓮^{-\sqrt{𝒙}})$. [📷image](../img/Calculus 2 Lecture 6.3/[56-10]-01.png)
          ○ Identify the outer and inner structure.
               ■ Outer function: $\ln(\cdot)$
               $\rule{0pt}{}$
               ■ Inner function: $𝓮^{\sqrt{𝒙}}+𝓮^{-\sqrt{𝒙}}$
          ○ Apply the chain rule for the logarithm.
          $\rule{0pt}{}$
               ■ $\dfrac{d𝒚}{d𝒙}=\dfrac{1}{𝓮^{\sqrt{𝒙}}+𝓮^{-\sqrt{𝒙}}}\cdot\dfrac{d}{d𝒙}\Big[𝓮^{\sqrt{𝒙}}+𝓮^{-\sqrt{𝒙}}\Big]$
               $\rule{0pt}{}$
          ○ Differentiate each exponential term.
          $\rule{0pt}{}$
               ■ $\dfrac{d}{d𝒙}\Big[𝓮^{\sqrt{𝒙}}\Big]=𝓮^{\sqrt{𝒙}}\cdot\dfrac{d}{d𝒙}\Big[\sqrt{𝒙}\Big]$
               $\rule{0pt}{}$
                    ▣ $\dfrac{d}{d𝒙}\Big[\sqrt{𝒙}\Big]=\dfrac{1}{2\sqrt{𝒙}}$
                    $\rule{0pt}{}$
               ■ $\dfrac{d}{d𝒙}\Big[𝓮^{-\sqrt{𝒙}}\Big]=𝓮^{-\sqrt{𝒙}}\cdot\dfrac{d}{d𝒙}\Big[-\sqrt{𝒙}\Big]$
               $\rule{0pt}{}$
                    ▣ $\dfrac{d}{d𝒙}\Big[-\sqrt{𝒙}\Big]=-\dfrac{1}{2\sqrt{𝒙}}$
                    $\rule{0pt}{}$
          ○ Combine the derivatives.
          $\rule{0pt}{}$
               ■ $\dfrac{d}{d𝒙}\Big[𝓮^{\sqrt{𝒙}}+𝓮^{-\sqrt{𝒙}}\Big]$
               $\rule{0pt}{}$
                    ▣ $=\dfrac{𝓮^{\sqrt{𝒙}}}{2\sqrt{𝒙}}-\dfrac{𝓮^{-\sqrt{𝒙}}}{2\sqrt{𝒙}}$
                    $\rule{0pt}{}$
          ○ Substitute back into the logarithmic derivative.
          $\rule{0pt}{}$
               ■ $\dfrac{d𝒚}{d𝒙}=\dfrac{1}{𝓮^{\sqrt{𝒙}}+𝓮^{-\sqrt{𝒙}}}\cdot\dfrac{𝓮^{\sqrt{𝒙}}-𝓮^{-\sqrt{𝒙}}}{2\sqrt{𝒙}}$
               $\rule{0pt}{}$
          ○ Final simplified form.
          $\rule{0pt}{}$
               ■ $\dfrac{d𝒚}{d𝒙}=\dfrac{𝓮^{\sqrt{𝒙}}-𝓮^{-\sqrt{𝒙}}}{2\sqrt{𝒙}\big(𝓮^{\sqrt{𝒙}}+𝓮^{-\sqrt{𝒙}}\big)}$
               $\rule{0pt}{}$
     ◉ [56:10](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=3370). 🧩 Example – First identify which rules are needed to compute the derivative. [📷image](../img/Calculus 2 Lecture 6.3/[56-10]-02.png)
          ○ Function 1:
               ■ $𝒇(𝒙)=𝓮^{𝒙\ln 𝒙}$
                    ▣ Chain rule.
                    ▣ Product rule (inside the exponent $𝒙\ln 𝒙$).
          ○ Function 2:
               ■ $𝒈(𝒙)=\big(𝓮^{2𝒙}-𝓮^{-3𝒙}\big)^{5}$
                    ▣ Chain rule (outer power).
                    ▣ Sum / difference rule.
                    ▣ Chain rule (inside each exponential).
          ○ Function 3:
               ■ $𝒉(𝒙)=𝓮^{-𝒙}\cdot\tan(𝓮^{𝒙})$
                    ▣ Product rule.
                    ▣ Chain rule (for $𝓮^{-𝒙}$).
                    ▣ Chain rule (for $\tan(𝓮^{𝒙})$).

● [1:6:48](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=4008). Integral calculus of natural exponential functions.
$\rule{0pt}{}$
     ◉ Fundamental integration rule: $\displaystyle \int 𝓮^{𝒙}\,𝒅𝒙=𝓮^{𝒙}+𝓒$.
     ◉ [1:08:15](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=4095). 🧩 Example – Use of substitution with the variable $𝒖$:  $\displaystyle \int 𝓮^{2𝒙}\,𝒅𝒙$ [📷image](../img/Calculus 2 Lecture 6.3/[1-08-15]-01.png)
          ○ Choose the substitution:
               ■ Let $𝒖=2𝒙$
                    ▣ $𝒅𝒖=2𝒅𝒙$
                    ▣ $𝒅𝒙=\dfrac{𝒅𝒖}{2}$
          ○ Rewrite the integral in terms of $𝒖$:
          $\rule{0pt}{}$
               ■ $\displaystyle \int 𝓮^{𝒖}\left(\dfrac{𝒅𝒖}{2}\right)$
               $\rule{0pt}{}$
                    ▣ $=\dfrac{1}{2}\displaystyle \int 𝓮^{𝒖}\,𝒅𝒖$
                    $\rule{0pt}{}$
          ○ Integrate with respect to $𝒖$:
          $\rule{0pt}{}$
               ■ $\dfrac{1}{2}𝓮^{𝒖}+𝓒$
               $\rule{0pt}{}$
          ○ Substitute back to the original variable:
          $\rule{0pt}{}$
               ■ $\dfrac{1}{2}𝓮^{2𝒙}+𝓒$
               $\rule{0pt}{}$
     ◉ [1:11:45](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=4305). 🧩 Example – Use of substitution with the variable $𝒖$: $\displaystyle \int \dfrac{𝓮^{2/𝒙}}{𝒙^{2}}\,𝒅𝒙$
 [📷image](../img/Calculus 2 Lecture 6.3/[1-11-45]-01.png)
          ○ Choose the substitution:
          $\rule{0pt}{}$
               ■ Let $𝒖=\dfrac{2}{𝒙}$
               $\rule{0pt}{}$
                    ▣ $𝒖=2𝒙^{-1}$
                    ▣ $𝒅𝒖=-2𝒙^{-2}\,𝒅𝒙$
                    $\rule{0pt}{}$
                    ▣ $𝒅𝒖=-\dfrac{2}{𝒙^{2}}\,𝒅𝒙$
          ○ Solve for $𝒅𝒙$:
          $\rule{0pt}{}$
               ■ $𝒅𝒙=\left(\dfrac{𝒙^{2}}{-2}\right)𝒅𝒖$
               $\rule{0pt}{}$
          ○ Rewrite the integral in terms of $𝒖$:
          $\rule{0pt}{}$
               ■ $\displaystyle \int \left(\dfrac{𝓮^{𝒖}}{𝒙^{2}}\right)\cdot\left(\dfrac{𝒙^{2}}{-2}\right)\,𝒅𝒖$
               $\rule{0pt}{}$
                    ▣ $=-\dfrac{1}{2}\displaystyle \int 𝓮^{𝒖}\,𝒅𝒖$
                    $\rule{0pt}{}$
          ○ Integrate with respect to $𝒖$:
          $\rule{0pt}{}$
               ■ $-\dfrac{1}{2}𝓮^{𝒖}+𝓒$
               $\rule{0pt}{}$
          ○ Substitute back to the original variable:
          $\rule{0pt}{}$
               ■ $\displaystyle -\dfrac{1}{2}𝓮^{2/𝒙}+𝓒$
               $\rule{0pt}{}$
     ◉ [1:16:45](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=4605). 🧩 Example – Use of substitution with the variable $𝒖$: [📷image](../img/Calculus 2 Lecture 6.3/[1-16-45]-01.png)
          ○ Choose the substitution:
               ■ Let $𝒖=1+𝓮^{-𝒙}$
               $\rule{0pt}{}$
                    ▣ $𝒅𝒖=𝓮^{-𝒙}\cdot\dfrac{d}{d𝒙}\Big[-𝒙\Big]\,𝒅𝒙$
                    $\rule{0pt}{}$
                    ▣ $𝒅𝒖=-𝓮^{-𝒙}\,𝒅𝒙$
          ○ Solve for $𝒅𝒙$:
          $\rule{0pt}{}$
               ■ $𝒅𝒙=\dfrac{𝒅𝒖}{-𝓮^{-𝒙}}$
               $\rule{0pt}{}$
          ○ Rewrite the integral in terms of $𝒖$:
          $\rule{0pt}{}$
               ■ $\displaystyle \int \left(\dfrac{𝓮^{-𝒙}}{𝒖}\right)\cdot\left(\dfrac{𝒅𝒖}{-𝓮^{-𝒙}}\right)$
               $\rule{0pt}{}$
                    ▣ $=-\displaystyle \int \dfrac{1}{𝒖}\,𝒅𝒖$
                    $\rule{0pt}{}$
          ○ Integrate with respect to $𝒖$:
          $\rule{0pt}{}$
               ■ $-\displaystyle \int \dfrac{1}{𝒖}\,𝒅𝒖$
               $\rule{0pt}{}$
                    ▣ $=-\ln|𝒖|+𝓒$
                    $\rule{0pt}{}$
          ○ Substitute back to the original variable:
               ■ $-\ln|1+𝓮^{-𝒙}|+𝓒$
     ◉ [1:23:12](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=4992). 🧩 Example – Use of substitution with the variable $𝒖$: $\displaystyle \int 𝓮^{-𝒙}\sec\big(𝓮^{-𝒙}\big)\,𝒅𝒙$ [📷image](../img/Calculus 2 Lecture 6.3/[1-23-12]-01.png)
          ○ Choose the substitution:
               ■ Let $𝒖=𝓮^{-𝒙}$
                    ▣ $𝒅𝒖=-𝓮^{-𝒙}\,𝒅𝒙$
                    ▣ $-𝒅𝒖=𝓮^{-𝒙}\,𝒅𝒙$
          ○ Rewrite the integral in terms of $𝒖$:
          $\rule{0pt}{}$
               ■ $\displaystyle \int \sec(𝒖)(-𝒅𝒖)$
               $\rule{0pt}{}$
                    ▣ $=-\displaystyle \int \sec(𝒖)\,𝒅𝒖$
                    $\rule{0pt}{}$
          ○ Use the standard integral:
          $\rule{0pt}{}$
               ■ $\displaystyle \int \sec(𝒖)\,𝒅𝒖=\ln|\sec(𝒖)+\tan(𝒖)|+𝓒$
               $\rule{0pt}{}$
          ○ Apply the result and substitute back:
               ■ $-\ln|\sec(𝒖)+\tan(𝒖)|+𝓒$
                    ▣ $-\ln|\sec(𝓮^{-𝒙})+\tan(𝓮^{-𝒙})|+𝓒$
