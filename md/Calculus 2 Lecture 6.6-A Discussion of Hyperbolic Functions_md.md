--------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ６．６－Ａ Ｄｉｓｃｕｓｓｉｏｎ ｏｆ Ｈｙｐｅｒｂｏｌｉｃ Ｆｕｎｃｔｉｏｎｓ**---------------------------—





Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:00](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=0). Introduction to Hyperbolic Functions [📷image](../img/Calculus 2 Lecture 6.6/[0-00]-01.png)
     ◉ Fundamental Definitions
          ○ [1:05](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=65). Hyperbolic Sine (“sinh”):  𝒇(𝒙) = sinh(𝒙)
               ■ Exponential definition:
                    ▣ sinh(𝒙) = (𝒆ˣ − 𝒆⁻ˣ) / 2
               ■ Engineering application:
                    ▣ The catenary curve describing suspended cables
                         ▢ A catenary is the natural shape a flexible cable takes when it hangs under its own weight between two supports
                         ▢ Common real-world examples
                              ▲ power lines between poles
                              ▲ suspension bridge cables
                              ▲ a chain hanging between two hooks
                         ▢ This curve appears naturally when balancing gravitational forces along the cable
                         ▢ The mathematical study of this curve leads to the introduction of hyperbolic functions
          ○ [2:02](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=122). Hyperbolic Cosine (“cosh”):  𝒇(𝒙) = cosh(𝒙)
               ■ Exponential definition:
                    ▣ cosh(𝒙) = (𝒆ˣ + 𝒆⁻ˣ) / 2
          ○ [2:27](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=147). Derived Hyperbolic Functions
               ■ Hyperbolic tangent:
                    ▣ tanh(𝒙) = sinh(𝒙) / cosh(𝒙)
               ■ Hyperbolic cosecant:
                    ▣ csch(𝒙) = 1 / sinh(𝒙)
               ■ Hyperbolic secant:
                    ▣ sech(𝒙) = 1 / cosh(𝒙)
               ■ Hyperbolic cotangent:
                    ▣ coth(𝒙) = cosh(𝒙) / sinh(𝒙)





Ｉｄｅｎｔｉｔｉｅｓ

● [4:19](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=259). Hyperbolic Function Identities [📷image](../img/Calculus 2 Lecture 6.6/[4-19]-01.png)
     ◉ sinh(−𝒙) = −sinh(𝒙) (odd)
     ◉ cosh(−𝒙) = cosh(𝒙) (even)
     ◉ cosh²(𝒙) − sinh²(𝒙) = 1
     ◉ sech²(𝒙) = 1 − tanh²(𝒙)
     ◉ sinh(𝒙 + 𝒚) = sinh(𝒙) cosh(𝒚) + cosh(𝒙) sinh(𝒚)
     ◉ cosh(𝒙 + 𝒚) = cosh(𝒙) cosh(𝒚) + sinh(𝒙) sinh(𝒚)
     ◉ sinh(2𝒙) = 2 sinh(𝒙) cosh(𝒙)
     ◉ cosh(2𝒙) = cosh²(𝒙) + sinh²(𝒙)
     ◉ cosh²(𝒙) = ½ (1 + cosh(2𝒙))
     ◉ sinh²(𝒙) = ½ (−1 + cosh(2𝒙))
 
● [9:55](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=595). Algebraic Proof — Proof of sinh(2𝒙) [📷image](../img/Calculus 2 Lecture 6.6/[9-55]-01.png)
     ◉ Start from the exponential definition
          ○ sinh(2𝒙) = (𝒆²ˣ − 𝒆⁻²ˣ) / 2
     ◉ Rewrite the powers
          ○ 𝒆²ˣ = (𝒆ˣ)²
          ○ 𝒆⁻²ˣ = (𝒆⁻ˣ)²
          ○ sinh(2𝒙) = ((𝒆ˣ)² − (𝒆⁻ˣ)²) / 2
     ◉ Use the difference of squares
          ○ 𝒂² − 𝒃² = (𝒂 − 𝒃)(𝒂 + 𝒃)
          ○ sinh(2𝒙) = (𝒆ˣ − 𝒆⁻ˣ)(𝒆ˣ + 𝒆⁻ˣ) / 2
     ◉ Separate the factors
          ○ sinh(2𝒙) = 2[(𝒆ˣ − 𝒆⁻ˣ)/2][(𝒆ˣ + 𝒆⁻ˣ)/2]
     ◉ Recognize the hyperbolic functions
          ○ (𝒆ˣ − 𝒆⁻ˣ)/2 = sinh(𝒙)
          ○ (𝒆ˣ + 𝒆⁻ˣ)/2 = cosh(𝒙)
     ◉ Final identity
          ○ sinh(2𝒙) = 2 sinh(𝒙) cosh(𝒙)     



               


Ｄｅｒｉｖａｔｉｖｅｓ ＆ Ｉｎｔｅｇｒａｌｓ

● [14:45](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=885). Derivatives of Hyperbolic Functions [📷image](../img/Calculus 2 Lecture 6.6/[14-45]-01.png)
     ◉ Derivative of sinh
          ○ 𝒅/𝒅𝒙 [sinh(𝒙)] = cosh(𝒙)
          ○ From the exponential definition
               ■ sinh(𝒙) = (𝒆ˣ − 𝒆⁻ˣ) / 2
               ■ 𝒅/𝒅𝒙[(𝒆ˣ − 𝒆⁻ˣ)/2] = (𝒆ˣ + 𝒆⁻ˣ) / 2
               ■ Therefore
                    ▣ 𝒅/𝒅𝒙[sinh(𝒙)] = cosh(𝒙)
     ◉ Derivative of cosh
          ○ 𝒅/𝒅𝒙 [cosh(𝒙)] = sinh(𝒙)
          ○ From the exponential definition
               ■ cosh(𝒙) = (𝒆ˣ + 𝒆⁻ˣ) / 2
               ■ 𝒅/𝒅𝒙[(𝒆ˣ + 𝒆⁻ˣ)/2] = (𝒆ˣ − 𝒆⁻ˣ) / 2
               ■ Therefore
                    ▣ 𝒅/𝒅𝒙[cosh(𝒙)] = sinh(𝒙)
     ◉ Derivative of tanh
          ○ tanh(𝒙) = sinh(𝒙) / cosh(𝒙)
          ○ Use the quotient rule
               ■ 𝒅/𝒅𝒙[tanh(𝒙)] = 𝒅/𝒅𝒙[sinh(𝒙)/cosh(𝒙)]
               ■ = (cosh(𝒙)·cosh(𝒙) − sinh(𝒙)·sinh(𝒙)) / cosh²(𝒙)
               ■ = (cosh²(𝒙) − sinh²(𝒙)) / cosh²(𝒙)
               ■ Using the identity
                    ▣ cosh²(𝒙) − sinh²(𝒙) = 1
               ■ Final result
                    ▣ 𝒅/𝒅𝒙[tanh(𝒙)] = 1 / cosh²(𝒙)
                    ▣ 𝒅/𝒅𝒙[tanh(𝒙)] = sech²(𝒙)
        
● [20:03](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=1203). General Table of Derivatives and Integrals [📷image](../img/Calculus 2 Lecture 6.6/[20-03]-01.png)
     ◉ Table of derivatives
          ○ 𝒅/𝒅𝒙 [sinh(𝒖)] = cosh(𝒖) · 𝒅𝒖/𝒅𝒙
          ○ 𝒅/𝒅𝒙 [cosh(𝒖)] = sinh(𝒖) · 𝒅𝒖/𝒅𝒙
          ○ 𝒅/𝒅𝒙 [tanh(𝒖)] = sech²(𝒖) · 𝒅𝒖/𝒅𝒙
          ○ 𝒅/𝒅𝒙 [csch(𝒖)] = −csch(𝒖) coth(𝒖) · 𝒅𝒖/𝒅𝒙
          ○ 𝒅/𝒅𝒙 [sech(𝒖)] = −sech(𝒖) tanh(𝒖) · 𝒅𝒖/𝒅𝒙
          ○ 𝒅/𝒅𝒙 [coth(𝒖)] = −csch²(𝒖) · 𝒅𝒖/𝒅𝒙
     ◉ Corresponding basic integrals
          ○ ∫ cosh(𝒖) d𝒖 = sinh(𝒖) + 𝓒
          ○ ∫ sinh(𝒖) d𝒖 = cosh(𝒖) + 𝓒
          ○ ∫ sech²(𝒖) d𝒖 = tanh(𝒖) + 𝓒
          ○ ∫ csch(𝒖) coth(𝒖) d𝒖 = −csch(𝒖) + 𝓒
          ○ ∫ sech(𝒖) tanh(𝒖) d𝒖 = −sech(𝒖) + 𝓒
          ○ ∫ csch²(𝒖) d𝒖 = −coth(𝒖) + 𝓒
     ◉ Key idea
          ○ The integral formulas are obtained directly by reversing the derivative formulas
          ○ The factor 𝒅𝒖/𝒅𝒙 indicates the Chain Rule in derivatives and 𝒖-substitution in integrals        

● [27:35](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=1655). 🧩 Example 1 — Composite derivative:  𝒅/𝒅𝒙 [cosh²(3𝒕² + 1)] [📷image-1](../img/Calculus 2 Lecture 6.6/[27-35]-01.png) [📷image-2](../img/Calculus 2 Lecture 6.6/[27-35]-02.png)
     ◉ Identify the layers of composition
          ○ Outer layer: (...)²
          ○ Middle layer: cosh(...)
          ○ Inner layer: 3𝒕² + 1
     ◉ Apply the power rule
          ○ 𝒅/𝒅𝒕 [cosh²(3𝒕² + 1)]
               ■ = 2 cosh(3𝒕² + 1) · 𝒅/𝒅𝒕[cosh(3𝒕² + 1)]
     ◉ Differentiate the hyperbolic cosine
          ○ 𝒅/𝒅𝒕[cosh(3𝒕² + 1)]
               ■ = sinh(3𝒕² + 1) · 𝒅/𝒅𝒕[3𝒕² + 1]
     ◉ Differentiate the inner polynomial
          ○ 𝒅/𝒅𝒕[3𝒕² + 1] = 6𝒕
     ◉ Combine all factors
          ○ 𝒅/𝒅𝒕 [cosh²(3𝒕² + 1)]
               ■ = 2 cosh(3𝒕² + 1) · sinh(3𝒕² + 1) · 6𝒕
     ◉ Final simplified result
          ○ 𝒅/𝒅𝒕 [cosh²(3𝒕² + 1)] = 12𝒕 cosh(3𝒕² + 1) sinh(3𝒕² + 1)        
               
● [32:33](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=1953). 🧩 Example 2 — Nested derivative: 𝒅/𝒅𝒙 [coth(csch(2𝒙))] [📷image](../img/Calculus 2 Lecture 6.6/[32-33]-01.png)
     ◉ Identify the composition
          ○ Outer function: coth(𝒖)
          ○ Inner function: 𝒖 = cosh(2𝒙)
     ◉ Differentiate the outer function
          ○ 𝒅/𝒅𝒙[coth(𝒖)] = −csch²(𝒖) · 𝒅𝒖/𝒅𝒙
     ◉ Substitute 𝒖 = cosh(2𝒙)
          ○ 𝒅/𝒅𝒙[coth(cosh(2𝒙))] = −csch²(cosh(2𝒙)) · 𝒅/𝒅𝒙[cosh(2𝒙)]
     ◉ Differentiate the inner function
          ○ 𝒅/𝒅𝒙[cosh(2𝒙)] = sinh(2𝒙) · 𝒅/𝒅𝒙[2𝒙]
          ○ 𝒅/𝒅𝒙[2𝒙] = 2
          ○ Therefore
               ■ 𝒅/𝒅𝒙[cosh(2𝒙)] = 2 sinh(2𝒙)
     ◉ Combine the factors
          ○ 𝒅/𝒅𝒙[coth(cosh(2𝒙))]
               ■ = −csch²(cosh(2𝒙)) · 2 sinh(2𝒙)
     ◉ Final result
          ○ 𝒅/𝒅𝒙[coth(cosh(2𝒙))] = −2 csch²(cosh(2𝒙)) sinh(2𝒙)
          
● [36:35](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=2195). 🧩 Example 3 — Integration by substitution:  ∫ cosh²(3𝒙) sinh(3𝒙) d𝒙 [📷image](../img/Calculus 2 Lecture 6.6/[36-35]-01.png)
     ◉ Step 1 — First substitution
          ○ Let 𝒖 = 3𝒙
          ○ Then d𝒖 = 3 d𝒙
          ○ So d𝒙 = d𝒖 / 3
     ◉ Step 2 — Rewrite the integral in terms of 𝒖
          ○ ∫ cosh²(3𝒙) sinh(3𝒙) d𝒙
          ○ = ∫ cosh²(𝒖) sinh(𝒖) · d𝒖/3
          ○ = (1/3) ∫ cosh²(𝒖) sinh(𝒖) d𝒖
     ◉ Step 3 — Second substitution
          ○ Let 𝔀 = cosh(𝒖)
          ○ Then d𝔀 = sinh(𝒖) d𝒖
     ◉ Step 4 — Rewrite using 𝔀
          ○ (1/3) ∫ cosh²(𝒖) sinh(𝒖) d𝒖
          ○ = (1/3) ∫ 𝔀² d𝔀
     ◉ Step 5 — Integrate
          ○ (1/3) ∫ 𝔀² d𝔀 = (1/3) · 𝔀³/3 + 𝓒
          ○ = 𝔀³/9 + 𝓒
     ◉ Step 6 — Back-substitute
          ○ = cosh³(𝒖)/9 + 𝓒
          ○ = cosh³(3𝒙)/9 + 𝓒
     ◉ Final result
          ○ ∫ cosh²(3𝒙) sinh(3𝒙) d𝒙 = cosh³(3𝒙)/9 + 𝓒        
               




Ｉｎｖｅｒｓｅ Ｈｙｐｅｒｂｏｌｉｃ Ｆｕｎｃｔｉｏｎｓ

● [41:50](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=2510). Inverse Hyperbolic Functions [📷image](../img/Calculus 2 Lecture 6.6/[41-50]-01.png)
     ◉ Inverse hyperbolic domains
          ○ 𝒚 = sinh⁻¹(𝒙),   (−∞, ∞)
          ○ 𝒚 = cosh⁻¹(𝒙),   [1, ∞)
          ○ 𝒚 = tanh⁻¹(𝒙),   (−1, 1)
          ○ 𝒚 = csch⁻¹(𝒙),   (−∞, 0) ∪ (0, ∞)
          ○ 𝒚 = sech⁻¹(𝒙),   (0, 1]
          ○ 𝒚 = coth⁻¹(𝒙),   (−∞, −1) ∪ (1, ∞)
     ◉ Logarithmic definitions
          ○ Remember: the inverse of 𝒆ˣ is ln(𝒙)
          ○ sinh⁻¹(𝒙) = ln(𝒙 + √(𝒙² + 1))
          ○ tanh⁻¹(𝒙) = (1/2) ln((1 + 𝒙)/(1 − 𝒙))
          ○ cosh⁻¹(𝒙) = ln(𝒙 + √(𝒙² − 1))
          
● [44:37](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=2677). Proof of the logarithmic identity for cosh⁻¹(𝒙) [📷image-1](../img/Calculus 2 Lecture 6.6/[44-37]-01.png) [📷image-2](../img/Calculus 2 Lecture 6.6/[44-37]-02.png)
     ◉ Start with the inverse definition
          ○ cosh⁻¹(𝒙) = 𝒚  ⇔  cosh(𝒚) = 𝒙
     ◉ Rewrite cosh in exponential form
          ○ 𝒙 = (𝒆ʸ + 𝒆⁻ʸ) / 2
          ○ 2𝒙 = 𝒆ʸ + 𝒆⁻ʸ
     ◉ Eliminate the negative exponent
          ○ Multiply by 𝒆ʸ
          ○ 2𝒙𝒆ʸ = 𝒆²ʸ + 1
          ○ 0 = 𝒆²ʸ − 2𝒙𝒆ʸ + 1 
     ◉ View the equation as quadratic in 𝒆ʸ
          ○ 0 = 𝒆²ʸ − 2𝒙𝒆ʸ + 1 
          ○ Let 𝒖 = 𝒆ʸ
          ○ 0 = 𝒖² − 2𝒙𝒖 + 1
     ◉ Apply the quadratic formula
          ○ 𝒖 = (2𝒙 ± √(4𝒙² − 4)) / 2
          ○ 𝒖 = (2𝒙 ± 2√(𝒙² − 1)) / 2
          ○ 𝒖 = 𝒙 ± √(𝒙² − 1)
     ◉ Return to 𝒆ʸ
          ○ 𝒆ʸ = 𝒙 ± √(𝒙² − 1)
     ◉ Domain considerations
          ○ Since 𝒆ʸ > 0, the negative branch is rejected
               ■ 𝒚 = cosh⁻¹(𝒙),   [1, ∞)
               ■ Also, cosh⁻¹(𝒙) is defined for 𝒙 ≥ 1
          ○ Therefore 𝒆ʸ = 𝒙 + √(𝒙² − 1)
     ◉ Apply the natural logarithm
          ○ ln(𝒆ʸ) = ln(𝒙 + √(𝒙² − 1))
          ○ 𝒚 = ln(𝒙 + √(𝒙² − 1))
     ◉ Final identity
          ○ cosh⁻¹(𝒙) = ln(𝒙 + √(𝒙² − 1))

          



Ｄｅｒｉｖａｔｉｖｅｓ ｏｆ Ｉｎｖｅｒｓｅ Ｈｙｐｅｒｂｏｌｉｃ Ｆｕｎｃｔｉｏｎｓ

● [55:19](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=3319). Proof of derivative of cosh⁻¹(𝒙) [📷image-1](../img/Calculus 2 Lecture 6.6/[55-19]-01.png)  [📷image-2](../img/Calculus 2 Lecture 6.6/[55-19]-02.png)
     ◉ Method 1 — Using logarithmic form
          ○ Start from the identity
               ■ cosh⁻¹(𝒙) = ln(𝒙 + √(𝒙² − 1))
          ○ Differentiate both sides
               ■ 𝒅/𝒅𝒙[cosh⁻¹(𝒙)] = 𝒅/𝒅𝒙[ln(𝒙 + √(𝒙² − 1))]
          ○ Apply chain rule
               ■ = 1 / (𝒙 + √(𝒙² − 1)) · 𝒅/𝒅𝒙[𝒙 + √(𝒙² − 1)]
          ○ Differentiate inside
               ■ 𝒅/𝒅𝒙[𝒙] = 1
               ■ 𝒅/𝒅𝒙[√(𝒙² − 1)] = (1/2)(𝒙² − 1)⁻¹ᐟ² · 2𝒙 = 𝒙 / √(𝒙² − 1)
               ■ So derivative becomes
                    ▣ = 1 / (𝒙 + √(𝒙² − 1)) · (1 + 𝒙 / √(𝒙² − 1))
          ○ Combine terms
               ■ = 1 / (𝒙 + √(𝒙² − 1)) · ((√(𝒙² − 1) + 𝒙) / √(𝒙² − 1))
          ○ Simplify
               ■ = 1 / √(𝒙² − 1)
     ◉ [1:03:10](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=3790). Method 2 — Implicit differentiation
          ○ Let 𝒚 = cosh⁻¹(𝒙)
          ○ Then 𝒙 = cosh(𝒚)
          ○ Differentiate both sides
               ■ 1 = sinh(𝒚) · 𝒅𝒚/𝒅𝒙
          ○ Solve for derivative
               ■ 𝒅𝒚/𝒅𝒙 = 1 / sinh(𝒚)
          ○ Express sinh(𝒚) in terms of 𝒙
               ■ cosh²(𝒚) − sinh²(𝒚) = 1
               ■ sinh²(𝒚) = cosh²(𝒚) − 1 = 𝒙² − 1
               ■ sinh(𝒚) = √(𝒙² − 1)
          ○ Final result
               ■ 𝒅/𝒅𝒙[cosh⁻¹(𝒙)] = 1 / √(𝒙² − 1)
    
 ● [1:06:50](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=4010). Complete derivative table (inverse hyperbolic) [📷image](../img/Calculus 2 Lecture 6.6/[1-06-50]-01.png)
     ◉ 𝒅/𝒅𝒙 [cosh⁻¹(𝒖)] = 1 / √(𝒖² − 1) · 𝒅𝒖/𝒅𝒙
     ◉ 𝒅/𝒅𝒙 [sinh⁻¹(𝒖)] = 1 / √(𝒖² + 1) · 𝒅𝒖/𝒅𝒙
     ◉ 𝒅/𝒅𝒙 [tanh⁻¹(𝒖)] = 1 / (1 − 𝒖²) · 𝒅𝒖/𝒅𝒙
     ◉ 𝒅/𝒅𝒙 [sech⁻¹(𝒖)] = −1 / (𝒖 √(1 − 𝒖²)) · 𝒅𝒖/𝒅𝒙
     ◉ 𝒅/𝒅𝒙 [csch⁻¹(𝒖)] = −1 / (|𝒖| √(𝒖² + 1)) · 𝒅𝒖/𝒅𝒙
     ◉ 𝒅/𝒅𝒙 [coth⁻¹(𝒖)] = 1 / (1 − 𝒖²) · 𝒅𝒖/𝒅𝒙          
          
● [1:10:55](https://www.youtube.com/watch?v=3kPg0gkJQgc&t=4255). 🧩 Final Example — Product rule: 𝒅/𝒅𝒙 [𝒆ˣ ⋅ sech⁻¹(3𝒙)] [📷image](../img/Calculus 2 Lecture 6.6/[1-10-55]-01.png)
     ◉ Identify the structure
          ○ Product of two functions
               ■ 𝒖 = 𝒆ˣ
               ■ 𝒗 = sech⁻¹(3𝒙)
     ◉ Apply the product rule
          ○ 𝒅/𝒅𝒙[𝒖𝒗] = 𝒖′𝒗 + 𝒖𝒗′
          ○ 𝒅/𝒅𝒙[𝒆ˣ ⋅ sech⁻¹(3𝒙)]
               ■ = 𝒅/𝒅𝒙[𝒆ˣ] ⋅ sech⁻¹(3𝒙) + 𝒆ˣ ⋅ 𝒅/𝒅𝒙[sech⁻¹(3𝒙)]
     ◉ Differentiate each factor
          ○ 𝒅/𝒅𝒙[𝒆ˣ] = 𝒆ˣ
          ○ For the inverse hyperbolic term
               ■ 𝒅/𝒅𝒙[sech⁻¹(𝒖)] = −1 / (𝒖√(1−𝒖²)) ⋅ 𝒅𝒖/𝒅𝒙
               ■ Let 𝒖 = 3𝒙
               ■ 𝒅𝒖/𝒅𝒙 = 3
               ■ 𝒅/𝒅𝒙[sech⁻¹(3𝒙)] = −1 / (3𝒙√(1−(3𝒙)²)) ⋅ 3
               ■ = −1 / (𝒙√(1−9𝒙²))
     ◉ Substitute back into the product rule
          ○ 𝒅/𝒅𝒙[𝒆ˣ ⋅ sech⁻¹(3𝒙)]
               ■ = 𝒆ˣ sech⁻¹(3𝒙) + 𝒆ˣ (−1 / (𝒙√(1−9𝒙²)))
     ◉ Final simplified result
          ○ 𝒅/𝒅𝒙[𝒆ˣ ⋅ sech⁻¹(3𝒙)]
               ■ = 𝒆ˣ sech⁻¹(3𝒙) − 𝒆ˣ / (𝒙√(1−9𝒙²))        