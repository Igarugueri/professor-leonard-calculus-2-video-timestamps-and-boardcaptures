-----------------------------------**Ｃａｌｃｕｌｕｓ　２　ｌｅｃｔｕｒｅ　６．１:  Tｈｅ　Nａｔｕｒａｌ　Lｏｇ　Fｕｎｃｔｉｏｎ**---------------------------------




Ｉｎｔｒｏｄｕｃｔｉｏｎ. Ｔｈｅ　ｎａｔｕｒａｌ　ｌｏｇａｒｉｔｈｍ　ｆｕｎｃｔｉｏｎ

● [0:00]. The Natural Logarithm Function (ln) and Its Properties 
     ◉ [0:40]. The natural logarithm of unity
          ○ ln(1) = 0
               ■ The base 𝓮 and exponential notation: 𝓮⁰ = 1
                    ▣ 🧩 Example –: log₂ 𝒙 = 4 → 2⁴ = 𝒙
     ◉ [2:00]. Product Property (Expansion)
          ○ ln(𝒙 · 𝒚) = ln 𝒙 + ln 𝒚
     ◉ [3:05]. Quotient Property (Expansion) 
          ○ ln(𝒙 / 𝒚) = ln 𝒙 − ln 𝒚
     ◉ [3:40]. Power Property
          ○  ln(𝒙ʳ) = r · ln 𝒙


● [4:20]. Practice: Expansion and Combination of Logarithms
     ◉ [4:30]. 🧩 Example – Expansion: ln(3𝒙⁴ / 2𝒚²) 
          ○ Initial application of the Quotient Rule (subtraction)
               ■  ln 3𝒙⁴ − ln 2𝒚²
          ○ ln 3 + ln 𝒙⁴ − [ ln 2 + ln 𝒚² ] Product Property 
          ○ ln 3 + 4 ln 𝒙 − ln 2 − 2 ln 𝒚 Power Property
               ■ Caution: the exponent only affects its immediate argument
     ◉ [9:00]. 🧩 Example – Expansion: ln((𝒙² + 1) / √𝒙) 
          ○ ln(𝒙² + 1) − ln √𝒙
          ○ ln(𝒙² + 1) − ln 𝒙¹ᐟ²
          ○ ln(𝒙² + 1) − 1/2 ln 𝒙
          ○ Restriction: the sum ln(𝒙² + 1) cannot be expanded
     ◉ [11:31]. 🧩 Example – Advanced Expansion: ln( 𝒙⁵ sin²(π𝒙) / ∛(𝒙⁴ + 2) ) 
          ○ ln(𝒙⁵ sin²(π𝒙)) − ln( (𝒙⁴ + 2)¹ᐟ³ )
          ○ ln 𝒙⁵ + ln sin²(π𝒙) − ln(𝒙⁴ + 2)¹ᐟ³
          ○ 5 ln 𝒙 + 2 ln sin(π𝒙) − 1/3 ln(𝒙⁴ + 2)
     ◉ [17:25]. 🧩 Example – Logarithm Combination (Reverse Process): 2/3 [ 5 ln 𝒙 + 1/2 ln(𝒙² + 1) − 4 ln(𝒙 − 2) ] 
          ○ Rule: move coefficients to exponents first:
               ■ 2/3 [ ln 𝒙⁵ + ln(𝒙² + 1)¹ᐟ² − ln(𝒙 − 2)⁴ ]
          ○ Unify all terms into a single ln:
               ■ 2/3 ln ( 𝒙⁵ (𝒙² + 1)¹ᐟ² / (𝒙 − 2)⁴ )
          ○ Apply the external coefficient (2/3) as a final exponent:
               ■ ln [ 𝒙⁵ (𝒙² + 1)¹ᐟ² / (𝒙 − 2)⁴ ]²ᐟ³




Ｇｒａｐｈｉｃａｌ　ｒｅｖｉｅｗ　ａｎｄ　ｔｈｅｏｒｅｔｉｃａｌ　ｂａｓｉｓ　ｆｏｒ　ｉｎｔｅｇｒａｌｓ  ａｎｄ　ｄｅｒｉｖａｔｉｖｅｓ

● [22:45]. Graphical Review 
     ◉ Graph of ln 𝒙 as the inverse function of e^𝒙
          ○ Domain restrictions: ln(0) and ln(negative) are undefined
          
● [28:30]. Integral Review (Antiderivatives) 
     ◉ 🧩 Example – Power Rule ∫ 𝒙ⁿ d𝒙 = (𝒙ⁿ⁺¹)/(n+1) + 𝓒: ∫ 𝒙³ d𝒙
          ○  ∫ 𝒙³ d𝒙 = 𝒙⁴/4 + 𝓒 
               ■ Remember 𝓒  as a family of curves
     ◉ [30:20]. 🧩 Example –  Property of pulling constants outside the integral:  ∫ 4𝒙⁵ d𝒙  
          ○ ∫ 4𝒙⁵ d𝒙 =  4 ∫ 𝒙⁵ d𝒙 = 4𝒙⁶/6 
          ○ Algebraic simplification for single-term quotients
               ■ 2𝒙⁶/3 + 𝓒 
     ◉ [30:20]. 🧩 Example –: ∫ sin 𝒙 d𝒙
          ○  ∫ sin 𝒙 d𝒙 = - cos 𝒙 + 𝓒
     ◉ [32:30]. 🧩 Example – Definite integral with rational function:  ∫₁² (𝒙⁴ − 1) / 𝒙² d𝒙
          ○ ⚠️ Why substitution is NOT appropriate here
               ■ The derivative of the denominator (𝒙² → 2𝒙) does not appear as a factor in the numerator
               ■  No visible composition 𝑢(𝒙) / 𝑢'(𝒙) structure
               ■ The correct strategy is algebraic simplification, not substitution
          ○ Algebraic simplification of the integrand
               ■ Rewrite as powers: 𝒙² − 𝒙⁻²
          ○ Direct integration term by term
               ■ Antiderivative: 𝒙³/3 + 1/𝒙
          ○ Evaluation on [1, 2]
               ■ Numerical result: 11/6
     ◉ [37:25]. 🧩 Example – The Critical Case: ∫ 1/𝒙 d𝒙 
          ○ To approximate the problem, think about the graph of 𝒚 = 1/𝓉
               ■ It is continuous and differentiable everywhere on (0, ∞). 
                    ▣  The Fundamental Theorem of Calculus (FTC),  𝒫𝒜𝑅𝒯  Ⅰ 
                         ▢ Derivatives and integrals as inverse operations
                         ▢ Defining the area function 𝓐(𝒙) as the integral of 𝒇(𝓉) from a to 𝒙
                         ▢ Statement of  FTC  𝒫𝒜𝑅𝒯  Ⅰ :
                            {
                               I̲f̲       𝒚  = 𝒇(𝒙) 𝘪𝘴 𝘤𝘰𝘯𝘵𝘪𝘯𝘶𝘰𝘶𝘴 𝘰𝘷𝘦𝘳 [𝓪, 𝒙],  
                              t̲h̲e̲n̲   𝘵𝘩𝘦 𝘢𝘳𝘦𝘢 𝘪𝘴:  𝒜(𝒙) 𝘴𝘶𝘤𝘩 𝘵𝘩𝘢𝘵 𝒜′(𝒙) = 𝒇(𝒙)  
                                    𝒜(𝒙) = ∫[𝓪, 𝒙] 𝒇(𝓉)·𝒅𝓉
                             }
          ○ What that means by the The Fundamental Theorem of Calculus 𝒫𝒜𝑅𝒯  Ⅰ?
               ■ Existence guaranteed by the Fundamental Theorem of Calculus, 𝒫𝒜𝑅𝒯  Ⅰ
                    ▣ Because 1/𝓉 is continuous on (0, ∞), by F.T.O.C. I, we must be able to find some differentiable function 𝓕(𝒙) such that:
                         ▢ 𝓕(𝒙) = ∫[𝓪, 𝒙]1/𝓉 𝒅𝓉
                         ▢ 𝓕′(𝒙) = 𝒅/𝒅𝒙 ∫[𝓪, 𝒙]1/𝓉 𝒅𝓉 = 1/𝒙 = 𝒇(𝒙) 
                         ▢ It turns out that this specific antiderivative 𝓕(𝒙) corresponds to the natural logarithm.
                              ▲ ln 𝒙 = ∫[1, 𝒙] 1/𝓉 𝒅𝓉
                                   ◭ 𝒅/𝒅𝒙 [ln 𝒙] = 𝒅/𝒅𝒙 ∫[1, 𝒙] 1/𝓉 𝒅𝓉 = 1/𝒙
                              ▲ The family ln 𝒙 + 𝓒 represents vertical shifts of the same curve. Imposing ln1 = 0 selects the curve with zero vertical shift, corresponding to C = 0.
     ◉ [46:20]. The role of the absolute value in ∫[1, 𝒙] 1/𝒙 𝒅𝒙 
          ○ Indefinite integral
               ■ Fundamental reason
                    ▣ The natural logarithm is defined only for positive arguments
                    ▣ ln(𝓪) exists only if 𝓪 > 0
               ■ Issue when integrating 1/𝒙
                    ▣ The function 1/𝒙 exists for 𝒙 > 0 and for 𝒙 < 0
                    ▣ Writing ln 𝒙 + 𝓒 would cover only the interval 𝒙 > 0
               ■ Correct antiderivative
                    ▣ Using ln|𝒙| ensures a positive logarithmic argument
                    ▣ If 𝒙 > 0, then |𝒙| = 𝒙
                    ▣ If 𝒙 < 0, then |𝒙| = −𝒙 > 0
               ■ Conclusion: The absolute value guarantees a valid expression over the entire domain where 1/𝒙 exists
          ○ Definite integral
               ■ Setup of the definite integral
                    ▣ ∫[𝓪, 𝓫] 1/𝒙 𝒅𝒙 = ln[|𝒙|] evaluated from 𝓪 to 𝓫 
                         ▢ On an interval not crossing 0, | | can be removed consistently.
               ■ Why the absolute value disappears
                    ▣ The limits 𝓪 and 𝓫 are chosen within a single interval
                    ▣ Either 𝓪 > 0 and 𝓫 > 0, or 𝓪 < 0 and 𝓫 < 0
                         ▢ NOTE: If the interval crosses 𝒙 = 0 (for example, from −2 to 4), the integral of 1/𝒙 becomes improper (_Improper Integral_).
                                         Even though ln|𝒙| is a valid antiderivative, the integral must be split at 𝒙 = 0 and evaluated using limits.
                                         In this case, the limits diverge, so the definite integral does not exist.
               ■ Consequence
                    ▣ ln|𝒙| reduces to ln 𝒙 or ln(−𝒙) consistently on the interval
                    ▣ No sign change occurs inside the interval
               ■ Conclusion:In definite integrals, the absolute value is implicit once the interval is fixed[[[[
               
                   

● [49:12]. Derivatives of Natural Logarithmic Functions 
     ◉ Review of the Chain Rule  
          ○ Formula: 𝒅/𝒅𝒙[𝒇(𝓰(𝒙))] = 𝒇′(𝓰(𝒙)) · 𝓰′(𝒙)
          ○ [51:30]. 𝒅/𝒅𝒙[ln 𝓰(𝒙)] = 1/𝓰(𝒙) · 𝓰′(𝒙)
     ◉ [55:00]. 🧩 Example – Chain Rule: 𝒅/𝒅𝒙[ln(3𝒙² − 1)] 
          ○ 1 / (3𝒙² − 1) 𝒅/𝒅𝒙[3𝒙² − 1]  =  6𝒙 / (3𝒙² − 1)
     ◉ [57:54]. 🧩 Example – General Power Rule:  𝒅/𝒅𝒙[ ³√(ln 𝒙)] 
          ○ 𝒅/𝒅𝒙 [(ln 𝒙)¹ᐟ³ ]
          ○ 1/3 · (ln 𝒙)⁻²ᐟ³ · 𝒅/𝒅𝒙[ln 𝒙]
          ○ 1/3 · (ln 𝒙)⁻²ᐟ³ · 1/𝒙
          ○ 1 / (3𝒙 · (ln 𝒙)²ᐟ³)
          ○ 1 / (3𝒙 · ³√((ln 𝒙)²))
     ◉ [1:02:17].🧩 Example – Chain Rule: 𝒅/𝒅𝒙 [ ln( 2𝒙 + √(𝒙³ − 1) ) ] 
          ○ 1 / ( 2𝒙 + √(𝒙³ − 1) ) · 𝒅/𝒅𝒙 [ 2𝒙 + (𝒙³ − 1)¹ᐟ² ]
          ○ 1 / ( 2𝒙 + √(𝒙³ − 1) ) · ( 2 + 1/2 · (𝒙³ − 1)⁻¹ᐟ² · 3𝒙² )
          ○ 1 / ( 2𝒙 + √(𝒙³ − 1) ) · ( 2 + 3𝒙² / (2√(𝒙³ − 1)) )
     ◉ [1:08:30].🧩 Example – General Power Rule: 𝒅/𝒅𝒙[𝒙³ ln(5𝒙)] 
          ○ 𝒅/𝒅𝒙 [ 𝒙³ ] · ln(5𝒙) + 𝒙³ · 𝒅/𝒅𝒙 [ ln(5𝒙) ]
          ○ 3𝒙² · ln(5𝒙) + 𝒙³ · 1/(5𝒙) · 𝒅/𝒅𝒙 [5𝒙]
          ○ 3𝒙² · ln(5𝒙) + 𝒙³ · 1/(5𝒙) · 5
          ○ 3𝒙² · ln(5𝒙) + 𝒙² 
          ○ 𝒙² · ( 3 ln(5𝒙) + 1 )
     ◉ [1:14:28]. 🧩 Example – : 𝒅/𝒅𝒙[ln |cos 𝒙|] 
          ○ The absolute value is required because ln() is defined only for positive arguments; |cos 𝒙| ensures the argument is positive (when cos 𝒙 ≠ 0). 
          ○ 1 / cos 𝒙 · 𝒅/𝒅𝒙 [ cos 𝒙 ]
          ○ 1 / cos 𝒙 · ( − sin 𝒙 )
          ○ − sin 𝒙 / cos 𝒙 = − tan 𝒙
     ◉ [1:17:30]. 🧩 Example – Logarithmic Expansion Before Differentiation: 𝒅/𝒅𝒙 [ ln ( ( 𝒙² (2𝒙² + 1)³ ) / √(5 − 𝒙²) ] 
          ○ Expanded expression: 
               ■ 𝒅/𝒅𝒙 [ ln(𝒙²) + ln((2𝒙² + 1)³) − ln(√(5 − 𝒙²)) ] 
               ■ 𝒅/𝒅𝒙 [ 2 ln 𝒙 + 3 ln(2𝒙² + 1) − (1/2) ln(5 − 𝒙²) ]
          ○ Term-by-term differentiation
               ■ 2·(1/𝒙) + 3·(1/(2𝒙² + 1))·𝒅/𝒅𝒙[2𝒙² + 1] − (1/2)·(1/(5 − 𝒙²))·𝒅/𝒅𝒙[5 − 𝒙²]
               ■ 2/𝒙 + 3·(1/(2𝒙² + 1))·(4𝒙) − (1/2)·(1/(5 − 𝒙²))·(−2𝒙)
               ■ 2/𝒙 + 12𝒙 / (2𝒙² + 1) + 𝒙 / (5 − 𝒙²) 




Ｌｏｇａｒｉｔｈｍｉｃ　ａｎｄ　ｉｍｐｌｉｃｉｔ　ｄｉｆｆｅｒｅｎｔｉａｔｉｏｎ

● [1:27:15]. Logarithmic and Implicit Differentiation 
     ◉ General Procedure
          ○ Expansion of ln 𝒚
          ○ Implicit differentiation
               ■ 𝒅/𝒅𝒙[ln 𝒚] = 1/𝒚 · 𝒅𝒚/𝒅𝒙
                    ▣ Solve for 𝒅𝒚/𝒅𝒙
                    ▣ Substitute the original expression for 𝒚
     ◉ 🧩 Example – Implicit Differentiation with ln: y = (x − 1)⁴ / ∛(2x − 1)
          ○ Apply 𝒅/𝒅𝒙 and solve for 𝒅𝒚/𝒅𝒙
          ○ ln 𝒚 = ln [ (𝒙 − 1)⁴ / ³√(2𝒙 − 1) ]
          ○ ln 𝒚 = 4 ln(𝒙 − 1) − 1/3 ln(2𝒙 − 1)
          ○ 𝒅/𝒅𝒙 [ ln 𝒚 ] = 𝒅/𝒅𝒙 [ 4 ln(𝒙 − 1) − 1/3 ln(2𝒙 − 1) ]
          ○ (1 / 𝒚) · 𝒅𝒚/𝒅𝒙 = 4 / (𝒙 − 1) − 1/3 · 1 / (2𝒙 − 1) · 2
          ○ (1 / 𝒚) · 𝒅𝒚/𝒅𝒙 = 4 / (𝒙 − 1) − 2 / [ 3(2𝒙 − 1) ]
          ○ 𝒅𝒚/𝒅𝒙 = [ 4 / (𝒙 − 1) − 2 / (3(2𝒙 − 1)) ] · 𝒚
          ○ 𝒅𝒚/𝒅𝒙 = [ 4 / (𝒙 − 1) − 2 / (3(2𝒙 − 1)) ] · ( (𝒙 − 1)⁴ / ∛(2𝒙 − 1) )
     ◉ [1:38:40]. 🧩 Example – Implicit Differentiation with ln: ln(2𝒙 / 𝒚) − sin 𝒚 + 𝒙² = 0
          ○ 𝒅/𝒅𝒙 [ ln(2𝒙) − ln 𝒚 − sin 𝒚 + 𝒙² ] = 𝒅/𝒅𝒙 [0]
          ○ (1 / 2𝒙) · 2 − (1 / 𝒚) · 𝒚′ − cos 𝒚 · 𝒚′ + 2𝒙 = 0
          ○ (1 / 𝒚) · 𝒚′ − cos 𝒚 · 𝒚′ = −2𝒙 − 1 / 𝒙 
          ○ 𝒚′ ( 1 / 𝒚 − cos 𝒚 ) = −2𝒙 − 1 / 𝒙
          ○ 𝒚′ = ( −2𝒙 − (1 / 𝒙) ) / ( (1 / 𝒚) − cos 𝒚 )




Ｉｎｔｅｇｒａｌｓ　ｔｈａｔ　ｒｅｓｕｌｔ　ｉｎ　ｌｎ｜𝒖｜

● [1:43:00]. Integrals That Result in ln |𝒖| 
     ◉ Integration rule: ∫ 1/𝒖 d𝒖 = ln |𝒖| + 𝓒
          ○ Use substitution technique to loo like ∫ 1/𝒖 d𝒖 = ln |𝒖| + 𝓒
     ◉ 🧩 Example –: ∫ 1/(5𝒙 − 2) d𝒙
          ○ Substitution:
               ■ 𝒖 = 5𝒙 − 2  
               ■ 𝒅𝒖/𝒅𝒙 = 5  
               ■ 𝒅𝒖 = 5 d𝒙  
               ■ 𝒅𝒙 = 𝒅𝒖 / 5
          ○ ∫1/𝒖 · (𝒅𝒖 / 5)
          ○ 1/5 ∫ 1/𝒖 d𝒖
          ○ 1/5 ln |𝒖| + 𝓒
          ○ 1/5 ln |5𝒙 − 2| + 𝓒
     ◉  [1:48:10]. 🧩 Example – ln into the integral: ∫ √(ln 𝒙) / (3𝒙) d𝒙
          ○ Substitution:
               ■ 𝒖 = ln 𝒙
               ■ 𝒅𝒖/𝒅𝒙 = 1/𝒙
               ■ 𝒅𝒖 = 1/𝒙 d𝒙
               ■ d𝒙 = 𝒙 𝒅𝒖
          ○ ∫ √𝒖 / (3𝒙) · (𝒙 𝒅𝒖)
          ○ 1/3 ∫ 𝒖¹ᐟ² d𝒖
          ○ 1/3 · (2/3) 𝒖³ᐟ² + 𝓒
          ○ 2/9 𝒖³ᐟ² + 𝓒
          ○ 2/9 (ln 𝒙)³ᐟ² + 𝓒




Ｔｒｉｇｏｎｏｍｅｔｒｉｃ　ｉｎｔｅｇｒａｌｓ　ｉｎｖｏｌｖｉｎｇ　ｌｎ

● [1:54:10]. Trigonometric Integrals Involving ln 
     ◉ INTEGRALS 
          ○ ∫ sin 𝒙 d𝒙 = − cos 𝒙 + 𝓒
          ○ ∫ cos 𝒙 d𝒙 = sin 𝒙 + 𝓒
          ○ ∫ sec² 𝒙 d𝒙 = tan 𝒙 + 𝓒
          ○ ∫ sec 𝒙 tan 𝒙 d𝒙 = sec 𝒙 + 𝓒
          ○ ∫ csc 𝒙 cot 𝒙 d𝒙 = − csc 𝒙 + 𝓒 
          ○ ∫ csc² 𝒙 d𝒙 = − cot 𝒙 + 𝓒
          ○ ∫ tan 𝒖 d𝒖 = − ln |cos 𝒖| + 𝓒 = ln |sec 𝒖| + 𝓒
          ○ ∫ cot 𝒖 d𝒖 = ln |sin 𝒖| + 𝓒
          ○ ∫ sec 𝒖 d𝒖 = ln |sec 𝒖 + tan 𝒖| + 𝓒
          ○ ∫ csc 𝒖 d𝒖 = ln |csc 𝒖 − cot 𝒖| + 𝓒 
          ○ NOTE 1:
               ■ The variable 𝒖 indicates that these formulas are typically used _after a substitution_.
               ■ In practice, the integrand is rewritten so that it matches one of these forms.
     ◉ [1:56:30]. 🧩 Example – : Derivation of ∫ tan 𝒙 d𝒙 
          ○ ∫ (sin 𝒙 / cos 𝒙) d𝒙
          ○ Substitution:
               ■ 𝒖 = cos 𝒙  
               ■ 𝒅𝒖 = −sin 𝒙 d𝒙  
               ■ 𝒅𝒙 = 𝒅𝒖 / (−sin 𝒙)
          ○ ∫ (sin 𝒙 / 𝒖) · (𝒅𝒖 / −sin 𝒙)
          ○ − ∫ 1/𝒖 d𝒖
          ○ − ln |𝒖| + 𝓒
          ○ − ln |cos 𝒙| + 𝓒
          ○ ln |cos 𝒙|⁻¹ + 𝓒
          ○ ln |sec 𝒙| + 𝓒
          ○ ∫ tan 𝒙 d𝒙 = ln |sec 𝒙| + 𝓒; This expression is an antiderivative of tan 𝒙 on any interval where tan 𝒙 is continuous.
          ○ NOTE 2: On −ln|cos 𝒙| and π/2
               ■ The antiderivative of tan 𝒙 can be written as −ln|cos 𝒙| + 𝓒 or equivalently as ln|sec 𝒙| + 𝓒.
                    This is a purely algebraic equivalence: −ln|cos 𝒙| = ln|cos 𝒙|⁻¹ = ln|sec 𝒙|.
               ■ The points 𝒙 = π/2 + kπ are excluded in all cases.
                    At these values, cos 𝒙 = 0, so tan 𝒙, ln|cos 𝒙|, and ln|sec 𝒙| are all undefined.
                    Therefore, the antiderivative is always understood on intervals where tan 𝒙 is continuous, i.e., between consecutive vertical asymptotes.
     ◉ [2:03:40]. 🧩 Example – : Derivation of ∫ sec 𝒙 d𝒙 
          ○ Algebraic trick to create a substitution
               ■ Multiply by (sec 𝒙 + tan 𝒙)/(sec 𝒙 + tan 𝒙)
               ■ ∫ sec 𝒙 · (sec 𝒙 + tan 𝒙)/(sec 𝒙 + tan 𝒙) d𝒙
               ■ ∫ (sec² 𝒙 + sec 𝒙 tan 𝒙)/(sec 𝒙 + tan 𝒙) d𝒙
          ○ Substitution
               ■ 𝒖 = sec 𝒙 + tan 𝒙
               ■ 𝒅𝒖 = (sec 𝒙 tan 𝒙 + sec² 𝒙) d𝒙
          ○ Reduction to a basic logarithmic integral
               ■ ∫ 1/𝒖 d𝒖
          ○ Final result
               ■ ln |sec 𝒙 + tan 𝒙| + 𝓒
               ■ Formula: ∫ sec 𝒙 d𝒙 = ln |sec 𝒙 + tan 𝒙| + C
     ◉ [2:09:05]. Summary of Trigonometric Formulas with ln 
          ○ ∫ tan 𝒖 d𝒙 = − ln |cos 𝒖| + 𝓒 = ln |sec 𝒖| + 𝓒
          ○ ∫ cot 𝒖 d𝒖 = ln |sin 𝒖| + 𝓒
          ○ ∫ sec 𝒖 d𝒙 = ln |sec 𝒖 + tan 𝒖| + 𝓒
          ○ ∫ csc 𝒖 d𝒖 = ln |csc 𝒖 − cot 𝒖| + 𝓒 
     ◉ [2:13:15]. 🧩 Example – : ∫ 𝒙 sec(𝒙²) d𝒙 
          ○ It does not match any direct formula from the table, so we use substitution.
               ■ Substitution:
                    ▣ 𝒖 = 𝒙²
                    ▣ 𝒅𝒖/𝒅𝒙 = 2𝒙
                    ▣ 𝒅𝒖 = 2𝒙 d𝒙
                    ▣ d𝒙 = 𝒅𝒖/(2𝒙)
          ○ ∫ 𝒙 sec(𝒙²) d𝒙 = ∫ 𝒙 sec(𝒖) · (𝒅𝒖/(2𝒙))
          ○ 1/2 ∫ sec 𝒖 d𝒖
          ○ 1/2 ln |sec 𝒖 + tan 𝒖| + 𝓒
          ○ 1/2 ln |sec(𝒙²) + tan(𝒙²)| + 𝓒
     ◉ [2:16:15]. 🧩 Example – : ∫ sin(2𝒙) / (1 + sin² 𝒙) d𝒙 
          ○ Use the double-angle identity to reveal the derivative.
               ■ sin(2𝒙) = 2 sin 𝒙 cos 𝒙
          ○ Rewrite the integral:
               ■ ∫ [2 sin 𝒙 cos 𝒙] / [1 + sin² 𝒙] d𝒙
          ○ Substitution:
               ■ 𝒖 = 1 + sin² 𝒙
               ■ 𝒅𝒖/𝒅𝒙 = 2 sin 𝒙 cos 𝒙
               ■ 𝒅𝒖 = 2 sin 𝒙 cos 𝒙 d𝒙
          ○ ∫ (1/𝒖) 𝒅𝒖
          ○ ln |𝒖| + 𝓒
          ○ ln |1 + sin² 𝒙| + 𝓒
               ■ NOTE 3: 1 + sin² 𝒙 > 0 for all 𝒙, so the absolute value is optional here.
     ◉ NOTE 4: Trigonometric identities commonly used in substitutions
          ○ These identities are frequently used to rewrite integrals so that a clear substitution appears.
          ○1️⃣ Double-angle formulas  
               ■ Used to expose a derivative factor (very common in substitutions):
                    ▣ sin(2𝒙) = 2 sin 𝒙 cos 𝒙  
                    ▣ cos(2𝒙) = cos²𝒙 − sin²𝒙  
                    ▣ cos(2𝒙) = 1 − 2 sin²𝒙  
                    ▣ cos(2𝒙) = 2 cos²𝒙 − 1
          ○2️⃣ Half-angle formulas  
               ■ Used when the integrand involves squared trigonometric functions:
                    ▣ sin²𝒙 = (1 − cos(2𝒙)) / 2  
                    ▣ cos²𝒙 = (1 + cos(2𝒙)) / 2  
                    ▣ tan²𝒙 = (1 − cos(2𝒙)) / (1 + cos(2𝒙))
          ○3️⃣ Pythagorean identities  
               ■ Essential for simplifying expressions and choosing substitutions:
                    ▣ sin²𝒙 + cos²𝒙 = 1  
                    ▣ 1 + tan²𝒙 = sec²𝒙  
                    ▣ 1 + cot²𝒙 = csc²𝒙  
          ○4️⃣ Practical rule of thumb  
               ■ If the numerator looks like the derivative of something in the denominator,  
                 try rewriting it using a trigonometric identity before choosing 𝒖.
               ■ These identities are not just algebraic tools — they are often the key step that makes a substitution possible.


