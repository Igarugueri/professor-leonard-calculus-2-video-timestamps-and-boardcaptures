--------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ６．６－Ａ Ｄｉｓｃｕｓｓｉｏｎ ｏｆ Ｈｙｐｅｒｂｏｌｉｃ Ｆｕｎｃｔｉｏｎｓ**---------------------------—





Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:00](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=0). Introduction to Hyperbolic Functions [📷image](../img/Calculus 2 Lecture 6.6/[0-00]-01.png)
     ◉ Fundamental Definitions
          ○ [1:05](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=65). Hyperbolic Sine (“sinh”):  $𝒇(𝒙)=\sinh(𝒙)$
               ■ Exponential definition:
               $\rule{0pt}{}$
                    ▣ $\sinh(𝒙)=\dfrac{𝒆^{𝒙}-𝒆^{-𝒙}}{2}$
                    $\rule{0pt}{}$
               ■ Engineering application:
                    ▣ The catenary curve describing suspended cables
                         ▢ A catenary is the natural shape a flexible cable takes when it hangs under its own weight between two supports
                         ▢ Common real-world examples
                              ▲ power lines between poles
                              ▲ suspension bridge cables
                              ▲ a chain hanging between two hooks
                         ▢ This curve appears naturally when balancing gravitational forces along the cable
                         ▢ The mathematical study of this curve leads to the introduction of hyperbolic functions
          ○ [2:02](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=122). Hyperbolic Cosine (“cosh”):  $𝒇(𝒙)=\cosh(𝒙)$
               ■ Exponential definition:
               $\rule{0pt}{}$
                    ▣ $\cosh(𝒙)=\dfrac{𝒆^{𝒙}+𝒆^{-𝒙}}{2}$
                    $\rule{0pt}{}$
          ○ [2:27](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=147). Derived Hyperbolic Functions
               ■ Hyperbolic tangent:
               $\rule{0pt}{}$
                    ▣ $\tanh(𝒙)=\dfrac{\sinh(𝒙)}{\cosh(𝒙)}$
                    $\rule{0pt}{}$
               ■ Hyperbolic cosecant:
               $\rule{0pt}{}$
                    ▣ $\operatorname{csch}(𝒙)=\dfrac{1}{\sinh(𝒙)}$
                    $\rule{0pt}{}$
               ■ Hyperbolic secant:
               $\rule{0pt}{}$
                    ▣ $\operatorname{sech}(𝒙)=\dfrac{1}{\cosh(𝒙)}$
                    $\rule{0pt}{}$
               ■ Hyperbolic cotangent:
               $\rule{0pt}{}$
                    ▣ $\coth(𝒙)=\dfrac{\cosh(𝒙)}{\sinh(𝒙)}$





Ｉｄｅｎｔｉｔｉｅｓ

● [4:19](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=259). Hyperbolic Function Identities [📷image](../img/Calculus 2 Lecture 6.6/[4-19]-01.png)
     ◉ $\sinh(-𝒙)=-\sinh(𝒙)$ (odd)
     $\rule{0pt}{}$
     ◉ $\cosh(-𝒙)=\cosh(𝒙)$ (even)
     $\rule{0pt}{}$
     ◉ $\cosh^{2}(𝒙)-\sinh^{2}(𝒙)=1$
     $\rule{0pt}{}$
     ◉ $\operatorname{sech}^{2}(𝒙)=1-\tanh^{2}(𝒙)$
     $\rule{0pt}{}$
     ◉ $\sinh(𝒙+𝒚)=\sinh(𝒙)\cosh(𝒚)+\cosh(𝒙)\sinh(𝒚)$
     $\rule{0pt}{}$
     ◉ $\cosh(𝒙+𝒚)=\cosh(𝒙)\cosh(𝒚)+\sinh(𝒙)\sinh(𝒚)$
     $\rule{0pt}{}$
     ◉ $\sinh(2𝒙)=2\sinh(𝒙)\cosh(𝒙)$
     $\rule{0pt}{}$
     ◉ $\cosh(2𝒙)=\cosh^{2}(𝒙)+\sinh^{2}(𝒙)$
     $\rule{0pt}{}$
     ◉ $\cosh^{2}(𝒙)=\dfrac{1}{2}\big(1+\cosh(2𝒙)\big)$
     $\rule{0pt}{}$
     ◉ $\sinh^{2}(𝒙)=\dfrac{1}{2}\big(-1+\cosh(2𝒙)\big)$
     $\rule{0pt}{}$
 
● [9:55](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=595). Algebraic Proof — Proof of $\sinh(2𝒙)$ [📷image](../img/Calculus 2 Lecture 6.6/[9-55]-01.png)
     ◉ Start from the exponential definition
     $\rule{0pt}{}$
          ○ $\sinh(2𝒙)=\dfrac{𝒆^{2𝒙}-𝒆^{-2𝒙}}{2}$
          $\rule{0pt}{}$
     ◉ Rewrite the powers
     $\rule{0pt}{}$
          ○ $𝒆^{2𝒙}=(𝒆^{𝒙})^{2}$
          $\rule{0pt}{}$
          ○ $𝒆^{-2𝒙}=(𝒆^{-𝒙})^{2}$
          $\rule{0pt}{}$
          ○ $\sinh(2𝒙)=\dfrac{(𝒆^{𝒙})^{2}-(𝒆^{-𝒙})^{2}}{2}$
          $\rule{0pt}{}$
     ◉ Use the difference of squares
     $\rule{0pt}{}$
          ○ $𝒂^{2}-𝒃^{2}=(𝒂-𝒃)(𝒂+𝒃)$
          $\rule{0pt}{}$
          ○ $\sinh(2𝒙)=\dfrac{(𝒆^{𝒙}-𝒆^{-𝒙})(𝒆^{𝒙}+𝒆^{-𝒙})}{2}$
          $\rule{0pt}{}$
     ◉ Separate the factors
     $\rule{0pt}{}$
          ○ $\sinh(2𝒙)=2\Big[\dfrac{𝒆^{𝒙}-𝒆^{-𝒙}}{2}\Big]\Big[\dfrac{𝒆^{𝒙}+𝒆^{-𝒙}}{2}\Big]$
          $\rule{0pt}{}$
     ◉ Recognize the hyperbolic functions
     $\rule{0pt}{}$
          ○ $\dfrac{𝒆^{𝒙}-𝒆^{-𝒙}}{2}=\sinh(𝒙)$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒆^{𝒙}+𝒆^{-𝒙}}{2}=\cosh(𝒙)$
          $\rule{0pt}{}$
     ◉ Final identity
          ○ $\sinh(2𝒙)=2\sinh(𝒙)\cosh(𝒙)$     



               


Ｄｅｒｉｖａｔｉｖｅｓ ＆ Ｉｎｔｅｇｒａｌｓ

● [14:45](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=885). Derivatives of Hyperbolic Functions [📷image](../img/Calculus 2 Lecture 6.6/[14-45]-01.png)
     ◉ Derivative of sinh
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[\sinh(𝒙)\big]=\cosh(𝒙)$
          $\rule{0pt}{}$
          ○ From the exponential definition
          $\rule{0pt}{}$
               ■ $\sinh(𝒙)=\dfrac{𝒆^{𝒙}-𝒆^{-𝒙}}{2}$
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}\Big[\dfrac{𝒆^{𝒙}-𝒆^{-𝒙}}{2}\Big]=\dfrac{𝒆^{𝒙}+𝒆^{-𝒙}}{2}$
               $\rule{0pt}{}$
               ■ Therefore
               $\rule{0pt}{}$
                    ▣ $\dfrac{𝒅}{𝒅𝒙}\big[\sinh(𝒙)\big]=\cosh(𝒙)$
                    $\rule{0pt}{}$
     ◉ Derivative of cosh
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[\cosh(𝒙)\big]=\sinh(𝒙)$
          $\rule{0pt}{}$
          ○ From the exponential definition
          $\rule{0pt}{}$
               ■ $\cosh(𝒙)=\dfrac{𝒆^{𝒙}+𝒆^{-𝒙}}{2}$
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}\Big[\dfrac{𝒆^{𝒙}+𝒆^{-𝒙}}{2}\Big]=\dfrac{𝒆^{𝒙}-𝒆^{-𝒙}}{2}$
               $\rule{0pt}{}$
               ■ Therefore
               $\rule{0pt}{}$
                    ▣ $\dfrac{𝒅}{𝒅𝒙}\big[\cosh(𝒙)\big]=\sinh(𝒙)$
                    $\rule{0pt}{}$
     ◉ Derivative of tanh
     $\rule{0pt}{}$
          ○ $\tanh(𝒙)=\dfrac{\sinh(𝒙)}{\cosh(𝒙)}$
          $\rule{0pt}{}$
          ○ Use the quotient rule
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}\big[\tanh(𝒙)\big]=\dfrac{𝒅}{𝒅𝒙}\Big[\dfrac{\sinh(𝒙)}{\cosh(𝒙)}\Big]$
               $\rule{0pt}{}$
               ■ $=\dfrac{\cosh(𝒙)\cdot\cosh(𝒙)-\sinh(𝒙)\cdot\sinh(𝒙)}{\cosh^{2}(𝒙)}$
               $\rule{0pt}{}$
               ■ $=\dfrac{\cosh^{2}(𝒙)-\sinh^{2}(𝒙)}{\cosh^{2}(𝒙)}$
               $\rule{0pt}{}$
               ■ Using the identity
               $\rule{0pt}{}$
                    ▣ $\cosh^{2}(𝒙)-\sinh^{2}(𝒙)=1$
                    $\rule{0pt}{}$
               ■ Final result
               $\rule{0pt}{}$
                    ▣ $\dfrac{𝒅}{𝒅𝒙}\big[\tanh(𝒙)\big]=\dfrac{1}{\cosh^{2}(𝒙)}$
                    $\rule{0pt}{}$
                    ▣ $\dfrac{𝒅}{𝒅𝒙}\big[\tanh(𝒙)\big]=\operatorname{sech}^{2}(𝒙)$
                    $\rule{0pt}{}$
        
● [20:03](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=1203). General Table of Derivatives and Integrals [📷image](../img/Calculus 2 Lecture 6.6/[20-03]-01.png)
     ◉ Table of derivatives
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[\sinh(𝒖)\big]=\cosh(𝒖)\cdot\dfrac{𝒅𝒖}{𝒅𝒙}$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[\cosh(𝒖)\big]=\sinh(𝒖)\cdot\dfrac{𝒅𝒖}{𝒅𝒙}$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[\tanh(𝒖)\big]=\operatorname{sech}^{2}(𝒖)\cdot\dfrac{𝒅𝒖}{𝒅𝒙}$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[\operatorname{csch}(𝒖)\big]=-\operatorname{csch}(𝒖)\coth(𝒖)\cdot\dfrac{𝒅𝒖}{𝒅𝒙}$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[\operatorname{sech}(𝒖)\big]=-\operatorname{sech}(𝒖)\tanh(𝒖)\cdot\dfrac{𝒅𝒖}{𝒅𝒙}$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[\coth(𝒖)\big]=-\operatorname{csch}^{2}(𝒖)\cdot\dfrac{𝒅𝒖}{𝒅𝒙}$
          $\rule{0pt}{}$
     ◉ Corresponding basic integrals
     $\rule{0pt}{}$
          ○ $\displaystyle \int \cosh(𝒖)\,d𝒖=\sinh(𝒖)+𝓒$
          $\rule{0pt}{}$
          ○ $\displaystyle \int \sinh(𝒖)\,d𝒖=\cosh(𝒖)+𝓒$
          $\rule{0pt}{}$
          ○ $\displaystyle \int \operatorname{sech}^{2}(𝒖)\,d𝒖=\tanh(𝒖)+𝓒$
          $\rule{0pt}{}$
          ○ $\displaystyle \int \operatorname{csch}(𝒖)\coth(𝒖)\,d𝒖=-\operatorname{csch}(𝒖)+𝓒$
          $\rule{0pt}{}$
          ○ $\displaystyle \int \operatorname{sech}(𝒖)\tanh(𝒖)\,d𝒖=-\operatorname{sech}(𝒖)+𝓒$
          $\rule{0pt}{}$
          ○ $\displaystyle \int \operatorname{csch}^{2}(𝒖)\,d𝒖=-\coth(𝒖)+𝓒$
          $\rule{0pt}{}$
     ◉ Key idea
          ○ The integral formulas are obtained directly by reversing the derivative formulas
          ○ The factor $\dfrac{𝒅𝒖}{𝒅𝒙}$ indicates the Chain Rule in derivatives and 𝒖-substitution in integrals        

● [27:35](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=1655). 🧩 Example 1 — Composite derivative:  $\dfrac{𝒅}{𝒅𝒙}\big[\cosh^{2}(3𝒕^{2}+1)\big]$ [📷image-1](../img/Calculus 2 Lecture 6.6/[27-35]-01.png) [📷image-2](../img/Calculus 2 Lecture 6.6/[27-35]-02.png)
     ◉ Identify the layers of composition
          ○ Outer layer: $(...)^{2}$
          ○ Middle layer: $\cosh(...)$
          ○ Inner layer: $3𝒕^{2}+1$
     ◉ Apply the power rule
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒕}\big[\cosh^{2}(3𝒕^{2}+1)\big]$
          $\rule{0pt}{}$
               ■ $=2\cosh(3𝒕^{2}+1)\cdot\dfrac{𝒅}{𝒅𝒕}\big[\cosh(3𝒕^{2}+1)\big]$
               $\rule{0pt}{}$
     ◉ Differentiate the hyperbolic cosine
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒕}\big[\cosh(3𝒕^{2}+1)\big]$
               ■ $=\sinh(3𝒕^{2}+1)\cdot\dfrac{𝒅}{𝒅𝒕}\big[3𝒕^{2}+1\big]$
               $\rule{0pt}{}$
     ◉ Differentiate the inner polynomial
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒕}\big[3𝒕^{2}+1\big]=6𝒕$
          $\rule{0pt}{}$
     ◉ Combine all factors
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒕}\big[\cosh^{2}(3𝒕^{2}+1)\big]$
          $\rule{0pt}{}$
               ■ $=2\cosh(3𝒕^{2}+1)\cdot\sinh(3𝒕^{2}+1)\cdot 6𝒕$
               $\rule{0pt}{}$
     ◉ Final simplified result
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒕}\big[\cosh^{2}(3𝒕^{2}+1)\big]=12𝒕\cosh(3𝒕^{2}+1)\sinh(3𝒕^{2}+1)$        

               
● [32:33](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=1953). 🧩 Example 2 — Nested derivative: $\dfrac{𝒅}{𝒅𝒙}\big[\coth(\operatorname{csch}(2𝒙))\big]$ [📷image](../img/Calculus 2 Lecture 6.6/[32-33]-01.png)
     ◉ Identify the composition
          ○ Outer function: $\coth(𝒖)$
          ○ Inner function: $𝒖=\cosh(2𝒙)$
     ◉ Differentiate the outer function
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[\coth(𝒖)\big]=-\operatorname{csch}^{2}(𝒖)\cdot\dfrac{𝒅𝒖}{𝒅𝒙}$
          $\rule{0pt}{}$
     ◉ Substitute 𝒖 = cosh(2𝒙)
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[\coth(\cosh(2𝒙))\big]=-\operatorname{csch}^{2}(\cosh(2𝒙))\cdot\dfrac{𝒅}{𝒅𝒙}\big[\cosh(2𝒙)\big]$
          $\rule{0pt}{}$
     ◉ Differentiate the inner function
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[\cosh(2𝒙)\big]=\sinh(2𝒙)\cdot\dfrac{𝒅}{𝒅𝒙}\big[2𝒙\big]$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[2𝒙\big]=2$
          $\rule{0pt}{}$
          ○ Therefore
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}\big[\cosh(2𝒙)\big]=2\sinh(2𝒙)$
               $\rule{0pt}{}$
     ◉ Combine the factors
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[\coth(\cosh(2𝒙))\big]$
          $\rule{0pt}{}$
               ■ $=-\operatorname{csch}^{2}(\cosh(2𝒙))\cdot 2\sinh(2𝒙)$
               $\rule{0pt}{}$
     ◉ Final result
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[\coth(\cosh(2𝒙))\big]=-2\operatorname{csch}^{2}(\cosh(2𝒙))\sinh(2𝒙)$

          
● [36:35](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=2195). 🧩 Example 3 — Integration by substitution:  $\displaystyle \int \cosh^{2}(3𝒙)\sinh(3𝒙)\,d𝒙$ [📷image](../img/Calculus 2 Lecture 6.6/[36-35]-01.png)
     ◉ Step 1 — First substitution
          ○ Let $𝒖=3𝒙$
          ○ Then $d𝒖=3\,d𝒙$
          ○ So $d𝒙=\dfrac{d𝒖}{3}$
     ◉ Step 2 — Rewrite the integral in terms of 𝒖
     $\rule{0pt}{}$
          ○ $\displaystyle \int \cosh^{2}(3𝒙)\sinh(3𝒙)\,d𝒙$
          $\rule{0pt}{}$
          ○ $=\displaystyle \int \cosh^{2}(𝒖)\sinh(𝒖)\cdot\dfrac{d𝒖}{3}$
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{3}\displaystyle \int \cosh^{2}(𝒖)\sinh(𝒖)\,d𝒖$
          $\rule{0pt}{}$
     ◉ Step 3 — Second substitution
          ○ Let $𝔀=\cosh(𝒖)$
          ○ Then $d𝔀=\sinh(𝒖)\,d𝒖$
     ◉ Step 4 — Rewrite using 𝔀
     $\rule{0pt}{}$
          ○ $\dfrac{1}{3}\displaystyle \int \cosh^{2}(𝒖)\sinh(𝒖)\,d𝒖$
          $\rule{0pt}{}$
          ○ $=\dfrac{1}{3}\displaystyle \int 𝔀^{2}\,d𝔀$
          $\rule{0pt}{}$
     ◉ Step 5 — Integrate
     $\rule{0pt}{}$
          ○ $\dfrac{1}{3}\displaystyle \int 𝔀^{2}\,d𝔀=\dfrac{1}{3}\cdot\dfrac{𝔀^{3}}{3}+𝓒$
          $\rule{0pt}{}$
          ○ $=\dfrac{𝔀^{3}}{9}+𝓒$
          $\rule{0pt}{}$
     ◉ Step 6 — Back-substitute
     $\rule{0pt}{}$
          ○ $=\dfrac{\cosh^{3}(𝒖)}{9}+𝓒$
          $\rule{0pt}{}$
          ○ $=\dfrac{\cosh^{3}(3𝒙)}{9}+𝓒$
          $\rule{0pt}{}$
     ◉ Final result
     $\rule{0pt}{}$
          ○ $\displaystyle \int \cosh^{2}(3𝒙)\sinh(3𝒙)\,d𝒙=\dfrac{\cosh^{3}(3𝒙)}{9}+𝓒$        
               





Ｉｎｖｅｒｓｅ Ｈｙｐｅｒｂｏｌｉｃ Ｆｕｎｃｔｉｏｎｓ

● [41:50](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=2510). Inverse Hyperbolic Functions [📷image](../img/Calculus 2 Lecture 6.6/[41-50]-01.png)
     ◉ Inverse hyperbolic domains
     $\rule{0pt}{}$
          ○ $𝒚=\sinh^{-1}(𝒙)$,   $(-\infty,\infty)$
          $\rule{0pt}{}$
          ○ $𝒚=\cosh^{-1}(𝒙)$,   $[1,\infty)$
          $\rule{0pt}{}$
          ○ $𝒚=\tanh^{-1}(𝒙)$,   $(-1,1)$
          $\rule{0pt}{}$
          ○ $𝒚=\operatorname{csch}^{-1}(𝒙)$,   $(-\infty,0)\cup(0,\infty)$
          $\rule{0pt}{}$
          ○ $𝒚=\operatorname{sech}^{-1}(𝒙)$,   $(0,1]$
          $\rule{0pt}{}$
          ○ $𝒚=\coth^{-1}(𝒙)$,   $(-\infty,-1)\cup(1,\infty)$
          $\rule{0pt}{}$
     ◉ Logarithmic definitions
          ○ Remember: the inverse of $𝒆^{𝒙}$ is $\ln(𝒙)$
          $\rule{0pt}{}$
          ○ $\sinh^{-1}(𝒙)=\ln\big(𝒙+\sqrt{𝒙^{2}+1}\big)$
          $\rule{0pt}{}$
          ○ $\tanh^{-1}(𝒙)=1/2\,\ln\big((1+𝒙)/(1-𝒙)\big)$
          $\rule{0pt}{}$
          ○ $\cosh^{-1}(𝒙)=\ln\big(𝒙+\sqrt{𝒙^{2}-1}\big)$
          $\rule{0pt}{}$
          
● [44:37](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=2677). Proof of the logarithmic identity for $\cosh^{-1}(𝒙)$ [📷image-1](../img/Calculus 2 Lecture 6.6/[44-37]-01.png) [📷image-2](../img/Calculus 2 Lecture 6.6/[44-37]-02.png)
     ◉ Start with the inverse definition
     $\rule{0pt}{}$
          ○ $\cosh^{-1}(𝒙)=𝒚\iff\cosh(𝒚)=𝒙$
          $\rule{0pt}{}$
     ◉ Rewrite cosh in exponential form
     $\rule{0pt}{}$
          ○ $𝒙=\dfrac{𝒆^{𝒚}+𝒆^{-𝒚}}{2}$
          $\rule{0pt}{}$
          ○ $2𝒙=𝒆^{𝒚}+𝒆^{-𝒚}$
          $\rule{0pt}{}$
     ◉ Eliminate the negative exponent
          ○ Multiply by $𝒆^{𝒚}$
          ○ $2𝒙𝒆^{𝒚}=𝒆^{2𝒚}+1$
          ○ $0=𝒆^{2𝒚}-2𝒙𝒆^{𝒚}+1$ 
     ◉ View the equation as quadratic in $𝒆^{𝒚}$
          ○ $0=𝒆^{2𝒚}-2𝒙𝒆^{𝒚}+1$ 
          ○ Let $𝒖=𝒆^{𝒚}$
          ○ $0=𝒖^{2}-2𝒙𝒖+1$
     ◉ Apply the quadratic formula
     $\rule{0pt}{}$
          ○ $𝒖=\dfrac{2𝒙\pm\sqrt{4𝒙^{2}-4}}{2}$
          $\rule{0pt}{}$
          ○ $𝒖=\dfrac{2𝒙\pm 2\sqrt{𝒙^{2}-1}}{2}$
          $\rule{0pt}{}$
          ○ $𝒖=𝒙\pm\sqrt{𝒙^{2}-1}$
          $\rule{0pt}{}$
     ◉ Return to $𝒆^{𝒚}$
     $\rule{0pt}{}$
          ○ $𝒆^{𝒚}=𝒙\pm\sqrt{𝒙^{2}-1}$
          $\rule{0pt}{}$
     ◉ Domain considerations
          ○ Since $𝒆^{𝒚}>0$, the negative branch is rejected
          $\rule{0pt}{}$
               ■ $𝒚=\cosh^{-1}(𝒙)$,   $[1,\infty)$
               $\rule{0pt}{}$
               ■ Also, $\cosh^{-1}(𝒙)$ is defined for $𝒙\ge 1$
               $\rule{0pt}{}$
          ○ Therefore $𝒆^{𝒚}=𝒙+\sqrt{𝒙^{2}-1}$
          $\rule{0pt}{}$
     ◉ Apply the natural logarithm
     $\rule{0pt}{}$
          ○ $\ln(𝒆^{𝒚})=\ln\big(𝒙+\sqrt{𝒙^{2}-1}\big)$
          $\rule{0pt}{}$
          ○ $𝒚=\ln\big(𝒙+\sqrt{𝒙^{2}-1}\big)$
          $\rule{0pt}{}$
     ◉ Final identity
     $\rule{0pt}{}$
          ○ $\cosh^{-1}(𝒙)=\ln\big(𝒙+\sqrt{𝒙^{2}-1}\big)$

          



Ｄｅｒｉｖａｔｉｖｅｓ ｏｆ Ｉｎｖｅｒｓｅ Ｈｙｐｅｒｂｏｌｉｃ Ｆｕｎｃｔｉｏｎｓ

● [55:19](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=3319). Proof of derivative of $\cosh^{-1}(𝒙)$ [📷image-1](../img/Calculus 2 Lecture 6.6/[55-19]-01.png)  [📷image-2](../img/Calculus 2 Lecture 6.6/[55-19]-02.png)
     ◉ Method 1 — Using logarithmic form
          ○ Start from the identity
          $\rule{0pt}{}$
               ■ $\cosh^{-1}(𝒙)=\ln\big(𝒙+\sqrt{𝒙^{2}-1}\big)$
               $\rule{0pt}{}$
          ○ Differentiate both sides
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}\big[\cosh^{-1}(𝒙)\big]=\dfrac{𝒅}{𝒅𝒙}\big[\ln\big(𝒙+\sqrt{𝒙^{2}-1}\big)\big]$
               $\rule{0pt}{}$
          ○ Apply chain rule
          $\rule{0pt}{}$
               ■ $=\dfrac{1}{𝒙+\sqrt{𝒙^{2}-1}}\cdot\dfrac{𝒅}{𝒅𝒙}\big[𝒙+\sqrt{𝒙^{2}-1}\big]$
               $\rule{0pt}{}$
          ○ Differentiate inside
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[𝒙]=1$
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}\big[\sqrt{𝒙^{2}-1}\big]=1/2\,(𝒙^{2}-1)^{-1/2}\cdot 2𝒙=\dfrac{𝒙}{\sqrt{𝒙^{2}-1}}$
               $\rule{0pt}{}$
               ■ So derivative becomes
               $\rule{0pt}{}$
                    ▣ $=\dfrac{1}{𝒙+\sqrt{𝒙^{2}-1}}\cdot\Big(1+\dfrac{𝒙}{\sqrt{𝒙^{2}-1}}\Big)$
                    $\rule{0pt}{}$
          ○ Combine terms
          $\rule{0pt}{}$
               ■ $=\dfrac{1}{𝒙+\sqrt{𝒙^{2}-1}}\cdot\Big(\dfrac{\sqrt{𝒙^{2}-1}+𝒙}{\sqrt{𝒙^{2}-1}}\Big)$
               $\rule{0pt}{}$
          ○ Simplify
          $\rule{0pt}{}$
               ■ $=\dfrac{1}{\sqrt{𝒙^{2}-1}}$
               $\rule{0pt}{}$
     ◉ [1:03:10](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=3790). Method 2 — Implicit differentiation
          ○ Let $𝒚=\cosh^{-1}(𝒙)$
          ○ Then $𝒙=\cosh(𝒚)$
          ○ Differentiate both sides
          $\rule{0pt}{}$
               ■ $1=\sinh(𝒚)\cdot\dfrac{𝒅𝒚}{𝒅𝒙}$
               $\rule{0pt}{}$
          ○ Solve for derivative
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅𝒚}{𝒅𝒙}=\dfrac{1}{\sinh(𝒚)}$
               $\rule{0pt}{}$
          ○ Express $\sinh(𝒚)$ in terms of 𝒙
          $\rule{0pt}{}$
               ■ $\cosh^{2}(𝒚)-\sinh^{2}(𝒚)=1$
               $\rule{0pt}{}$
               ■ $\sinh^{2}(𝒚)=\cosh^{2}(𝒚)-1=𝒙^{2}-1$
               $\rule{0pt}{}$
               ■ $\sinh(𝒚)=\sqrt{𝒙^{2}-1}$
               $\rule{0pt}{}$
          ○ Final result
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}\big[\cosh^{-1}(𝒙)\big]=\dfrac{1}{\sqrt{𝒙^{2}-1}}$

    
● [1:06:50](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=4010). Complete derivative table (inverse hyperbolic) [📷image](../img/Calculus 2 Lecture 6.6/[1-06-50]-01.png)
$\rule{0pt}{}$
     ◉ $\dfrac{𝒅}{𝒅𝒙}\big[\cosh^{-1}(𝒖)\big]=\dfrac{1}{\sqrt{𝒖^{2}-1}}\cdot\dfrac{𝒅𝒖}{𝒅𝒙}$
     $\rule{0pt}{}$
     ◉ $\dfrac{𝒅}{𝒅𝒙}\big[\sinh^{-1}(𝒖)\big]=\dfrac{1}{\sqrt{𝒖^{2}+1}}\cdot\dfrac{𝒅𝒖}{𝒅𝒙}$
     $\rule{0pt}{}$
     ◉ $\dfrac{𝒅}{𝒅𝒙}\big[\tanh^{-1}(𝒖)\big]=\dfrac{1}{1-𝒖^{2}}\cdot\dfrac{𝒅𝒖}{𝒅𝒙}$
     $\rule{0pt}{}$
     ◉ $\dfrac{𝒅}{𝒅𝒙}\big[\operatorname{sech}^{-1}(𝒖)\big]=-\dfrac{1}{𝒖\sqrt{1-𝒖^{2}}}\cdot\dfrac{𝒅𝒖}{𝒅𝒙}$
     $\rule{0pt}{}$
     ◉ $\dfrac{𝒅}{𝒅𝒙}\big[\operatorname{csch}^{-1}(𝒖)\big]=-\dfrac{1}{\lvert 𝒖\rvert\sqrt{𝒖^{2}+1}}\cdot\dfrac{𝒅𝒖}{𝒅𝒙}$
     $\rule{0pt}{}$
     ◉ $\dfrac{𝒅}{𝒅𝒙}\big[\coth^{-1}(𝒖)\big]=\dfrac{1}{1-𝒖^{2}}\cdot\dfrac{𝒅𝒖}{𝒅𝒙}$          
     
          
● [1:10:55](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=4255). 🧩 Final Example — Product rule: $\dfrac{𝒅}{𝒅𝒙}\big[𝒆^{𝒙}\cdot \operatorname{sech}^{-1}(3𝒙)\big]$ [📷image](../img/Calculus 2 Lecture 6.6/[1-10-55]-01.png)
     ◉ Identify the structure
          ○ Product of two functions
               ■ $𝒖=𝒆^{𝒙}$
               ■ $𝒗=\operatorname{sech}^{-1}(3𝒙)$
     ◉ Apply the product rule
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}[𝒖𝒗]=𝒖'𝒗+𝒖𝒗'$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[𝒆^{𝒙}\cdot \operatorname{sech}^{-1}(3𝒙)\big]$
          $\rule{0pt}{}$
               ■ $=\dfrac{𝒅}{𝒅𝒙}\big[𝒆^{𝒙}\big]\cdot \operatorname{sech}^{-1}(3𝒙)+𝒆^{𝒙}\cdot \dfrac{𝒅}{𝒅𝒙}\big[\operatorname{sech}^{-1}(3𝒙)\big]$
               $\rule{0pt}{}$
     ◉ Differentiate each factor
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[𝒆^{𝒙}\big]=𝒆^{𝒙}$
          $\rule{0pt}{}$
          ○ For the inverse hyperbolic term
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}\big[\operatorname{sech}^{-1}(𝒖)\big]=-\dfrac{1}{𝒖\sqrt{1-𝒖^{2}}}\cdot\dfrac{𝒅𝒖}{𝒅𝒙}$
               $\rule{0pt}{}$
               ■ Let $𝒖=3𝒙$
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅𝒖}{𝒅𝒙}=3$
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}\big[\operatorname{sech}^{-1}(3𝒙)\big]=-\dfrac{1}{3𝒙\sqrt{1-(3𝒙)^{2}}}\cdot 3$
               $\rule{0pt}{}$
               ■ $=-\dfrac{1}{𝒙\sqrt{1-9𝒙^{2}}}$
               $\rule{0pt}{}$
     ◉ Substitute back into the product rule
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[𝒆^{𝒙}\cdot \operatorname{sech}^{-1}(3𝒙)\big]$
          $\rule{0pt}{}$
               ■ $=𝒆^{𝒙}\operatorname{sech}^{-1}(3𝒙)+𝒆^{𝒙}\Big(-\dfrac{1}{𝒙\sqrt{1-9𝒙^{2}}}\Big)$
               $\rule{0pt}{}$
     ◉ Final simplified result
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[𝒆^{𝒙}\cdot \operatorname{sech}^{-1}(3𝒙)\big]$
          $\rule{0pt}{}$
               ■ $=𝒆^{𝒙}\operatorname{sech}^{-1}(3𝒙)-\dfrac{𝒆^{𝒙}}{𝒙\sqrt{1-9𝒙^{2}}}$        