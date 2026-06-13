-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ７．２ － Ｔｅｃｈｎｉｑｕｅｓ Ｆｏｒ Ｔｒｉｇｏｎｏｍｅｔｒｉｃ Ｉｎｔｅｇｒａｌｓ**---------------------------------




Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:01]. Introduction to Section 7.2: Techniques for Trigonometric Integrals.
     ◉ Continuation of the previous section on trigonometric integration.
     ◉ Focus on products of powers of sine and cosine, and later on tangent/secant and cotangent/cosecant.





     
Ｓｉｎｅ–Ｃｏｓｉｎｅ Ｐａｔｔｅｒｎｓ

● [1:03]. Case analysis for integrals of the form ∫ sinᵐ(𝒙) cosⁿ(𝒙) 𝒅𝒙. [📷image](./img/Calculus 2 Lecture 7.2/[1-03]Case analysis for integrals of the form ∫ sinᵐ(𝒙) cosⁿ(𝒙) 𝒅𝒙.png)
     ◉ Two cases:
          ○ Case 1: ᵐ and/or ⁿ is odd.
          ○ Case 2: ᵐ and ⁿ are even.
     ◉ Case 1: At least one power is odd.
          ○ If the power of sin(𝒙) is odd:
               ■ Keep one factor of sin(𝒙).
               ■ Use the Pythagorean identity to change sin²(𝒙) = 1 − cos²(𝒙).
          ○ If the power of cos(𝒙) is odd:
               ■ Do the same for cos(𝒙).
               ■ Use cos²(𝒙) = 1 − sin²(𝒙).
          ○ If both powers are odd:
               ■ Pick the one that will give power 2, if possible.
     ◉ Case 2: Both powers are even.
          ○ Use the half-angle identities:
               ■ sin²(𝒙) = (1/2)(1 − cos(2𝒙))
               ■ cos²(𝒙) = (1/2)(1 + cos(2𝒙))
          ○ Go to this link  [openstax🌐](https://openstax.org/books/precalculus-2e/pages/7-3-double-angle-half-angle-and-reduction-formulas)
     ◉ NOTE:
          ○ The labels “odd” and “even” apply only to integer powers.
          ○ A fractional exponent such as 1/2 is neither odd nor even.
          ○ In those cases, use the rule based on the other exponent, if that one is an integer odd or even power.




 
               
Ｅｘａｍｐｌｅｓ — Ｓｉｎｅ ａｎｄ Ｃｏｓｉｎｅ

● [9:47]. 🧩 Example 1 — Both powers odd: ∫ cos³(2𝒙) sin⁵(2𝒙) 𝒅𝒙. [📷image](./img/Calculus 2 Lecture 7.2/[9-47]Example 1 — Evaluate ∫ cos³(2𝒙) sin⁵(2𝒙) 𝒅𝒙.png)
     ◉ Case 1: both powers are odd.
          ○ Pick the smaller odd power so as to obtain a squared factor.
          ○ Strip off one factor of cos(2𝒙).
     ◉ Rewrite the integrand:
          ○ ∫ cos²(2𝒙) sin⁵(2𝒙) cos(2𝒙) 𝒅𝒙
     ◉ Use the Pythagorean identity:
          ○ cos²(2𝒙) = 1 − sin²(2𝒙)
          ○ ∫ [1 − sin²(2𝒙)] sin⁵(2𝒙) cos(2𝒙) 𝒅𝒙
     ◉ Simple substitution:
          ○ 𝒖 = sin(2𝒙)
          ○ 𝒅𝒖 = 2 cos(2𝒙) 𝒅𝒙
          ○ 𝒅𝒖/2 = cos(2𝒙) 𝒅𝒙
     ◉ Polynomial integral in 𝒖:
          ○ ∫ (1 − 𝒖²) 𝒖⁵ 𝒅𝒖/2
          ○ = (1/2) ∫ (𝒖⁵ − 𝒖⁷) 𝒅𝒖
          ○ = (1/2) [𝒖⁶/6 − 𝒖⁸/8]
     ◉ Final result:
          ○ (1/12) sin⁶(2𝒙) − (1/16) sin⁸(2𝒙) + 𝓒
          
● [19:11]. 🧩 Example 2 —  At least one power is odd: Evaluate ∫ sin³(𝒙) cos²(𝒙) 𝒅𝒙. [📷image](./img/Calculus 2 Lecture 7.2/[19-11]Example 2 —  At least one power is odd Evaluate ∫ sin³(𝒙) cos²(𝒙) 𝒅𝒙.png)
     ◉ The power of sine is odd.Strip off one factor of sin(𝒙).
     ◉ Convert sin²(𝒙) into 1 − cos²(𝒙).
     ◉ Substitution:
          ○ 𝒖 = cos(𝒙)
     ◉ Resulting polynomial integral in 𝒖.
     ◉ Final result:
          ○ (1/5) cos⁵(𝒙) − (1/3) cos³(𝒙) + 𝓒
          
● [27:37]. 🧩 Example 3 — Both powers are even: ∫ sin⁴(𝒙) cos⁴(𝒙) 𝒅𝒙. [📷image-1](./img/Calculus 2 Lecture 7.2/[27-37]Example 3 — Both powers are even ∫ sin⁴(𝒙) cos⁴(𝒙) 𝒅𝒙_1.png)  [📷image-2](./img/Calculus 2 Lecture 7.2/[27-37]Example 3 — Both powers are even ∫ sin⁴(𝒙) cos⁴(𝒙) 𝒅𝒙_2.png)
     ◉ Since both powers are even, use identities instead of the odd-power substitution strategy.
     ◉ Use the double-angle identity:
          ○ sin(𝒙)cos(𝒙) = (1/2) sin(2𝒙)
          ○ So:
               ■ ∫ sin⁴(𝒙) cos⁴(𝒙) 𝒅𝒙 = ∫ [(1/2) sin(2𝒙)]⁴ 𝒅𝒙
               ■ = (1/16) ∫ sin⁴(2𝒙) 𝒅𝒙
     ◉ Rewrite the fourth power:
          ○ (1/16) ∫ [sin²(2𝒙)]² 𝒅𝒙
     ◉ Use the half-angle identity:
          ○ sin²(2𝒙) = (1/2)(1 − cos(4𝒙))
          ○ So:
               ■ (1/16) ∫ [(1/2)(1 − cos(4𝒙))]² 𝒅𝒙
               ■ = (1/64) ∫ (1 − cos(4𝒙))² 𝒅𝒙
     ◉ Expand the square:
          ○ (1/64) ∫ [1 − 2cos(4𝒙) + cos²(4𝒙)] 𝒅𝒙
     ◉ Apply the half-angle identity again:
          ○ cos²(4𝒙) = (1/2)(1 + cos(8𝒙))
     ◉ Simplify the integrand:
          ○ (1/64) ∫ [3/2 − 2cos(4𝒙) + (1/2)cos(8𝒙)] 𝒅𝒙
     ◉ Final expanded result:
          ○ ∫ sin⁴(𝒙) cos⁴(𝒙) 𝒅𝒙 = (3/128)𝒙 − (1/128)sin(4𝒙) + (1/1024)sin(8𝒙) + 𝓒
     
● [48:58]. 🧩 Example 4 — Without using the reduction formula: Evaluate ∫ sin⁶(𝒙) 𝒅𝒙 [📷image-1](./img/Calculus 2 Lecture 7.2/[48-58]Example 4 — Without using the reduction formula ∫ sin⁶(𝒙) 𝒅𝒙_1.png)  [📷image-2](./img/Calculus 2 Lecture 7.2/[48-58]Example 4 — Without using the reduction formula ∫ sin⁶(𝒙) 𝒅𝒙_2.png) [📷image-3](./img/Calculus 2 Lecture 7.2/[48-58]Example 4 — Without using the reduction formula ∫ sin⁶(𝒙) 𝒅𝒙_3.png)  
     ◉ Rewrite the integrand:
          ○ ∫ sin⁶(𝒙) 𝒅𝒙 = ∫ (sin²(𝒙))³ 𝒅𝒙
     ◉ Use the half-angle identity:
          ○ sin²(𝒙) = (1/2)(1 − cos(2𝒙))
          ○ Therefore:
               ■ ∫ sin⁶(𝒙) 𝒅𝒙 = ∫ [(1/2)(1 − cos(2𝒙))]³ 𝒅𝒙
               ■ = (1/8) ∫ (1 − cos(2𝒙))³ 𝒅𝒙
     ◉ Expand the cube using Pascal’s Triangle:
          ○ (1 − cos(2𝒙))³ = 1 − 3cos(2𝒙) + 3cos²(2𝒙) − cos³(2𝒙)
          ○ So:
               ■ (1/8) ∫ [1 − 3cos(2𝒙) + 3cos²(2𝒙) − cos³(2𝒙)] 𝒅𝒙
     ◉ Treat the even-power term:
          ○ cos²(2𝒙) = (1/2)(1 + cos(4𝒙))
     ◉ Treat the odd-power term separately:
          ○ ∫ cos³(2𝒙) 𝒅𝒙 = ∫ (1 − sin²(2𝒙)) cos(2𝒙) 𝒅𝒙
          ○ Let 𝒖 = sin(2𝒙), so 𝒅𝒖/2 = cos(2𝒙) 𝒅𝒙
          ○ Then:
               ■ ∫ cos³(2𝒙) 𝒅𝒙 = (1/2) ∫ (1 − 𝒖²) 𝒅𝒖
               ■ = (1/2)𝒖 − (1/6)𝒖³
               ■ = (1/2)sin(2𝒙) − (1/6)sin³(2𝒙)
     ◉ Combine all terms and simplify.
     ◉ Final result:
          ○ ∫ sin⁶(𝒙) 𝒅𝒙 = (5/16)𝒙 − (1/4)sin(2𝒙) + (3/64)sin(4𝒙) + (1/48)sin³(2𝒙) + 𝓒





     
Ｄｅｆｉｎｅｄ Ｉｎｔｅｇｒａｌ Ｅｘａｍｐｌｅ

● [1:11:06]. 🧩 Example 5 — Definite integral: ∫[0, π/2] sin³(𝒙) cos¹ᐟ²(𝒙) 𝒅𝒙. [📷image](./img/Calculus 2 Lecture 7.2/[1-11-06]Example 5 — Definite integral ∫[0, π∕2] sin³(𝒙) cos¹ᐟ²(𝒙) 𝒅𝒙.png)
     ◉ The power of sine is odd, so strip off one factor of sin(𝒙).
          ○ ∫[0, π/2] sin²(𝒙) cos¹ᐟ²(𝒙) · sin(𝒙) 𝒅𝒙
     ◉ Use the Pythagorean identity:
          ○ sin²(𝒙) = 1 − cos²(𝒙)
          ○ ∫[0, π/2] (1 − cos²(𝒙)) cos¹ᐟ²(𝒙) · sin(𝒙) 𝒅𝒙
     ◉ Substitution:
          ○ 𝒖 = cos(𝒙)
          ○ 𝒅𝒖 = −sin(𝒙) 𝒅𝒙
          ○ −𝒅𝒖 = sin(𝒙) 𝒅𝒙
     ◉ Change the bounds:
          ○ When 𝒙 = 0, 𝒖 = 1
          ○ When 𝒙 = π/2, 𝒖 = 0
     ◉ Rewrite the integral in 𝒖:
          ○ −∫[1, 0] (1 − 𝒖²) 𝒖¹ᐟ² 𝒅𝒖
          ○ = ∫[0, 1] (𝒖¹ᐟ² − 𝒖⁵ᐟ²) 𝒅𝒖
     ◉ Evaluate:
          ○ [ (2/3)𝒖³ᐟ² − (2/7)𝒖⁷ᐟ² ]₀¹
          ○ = 2/3 − 2/7
     ◉ Final numerical value:
          ○ 8/21




          
Ｔａｎｇｅｎｔ ａｎｄ Ｓｅｃａｎｔ OR Ｃｏｓｅｃａｎｔ ａｎｄ Ｃｏｔａｎｇｅｎｔ

● [1:24:25]. Integrals involving tangent and secant: ∫ tanᵐ(𝒙) secⁿ(𝒙) 𝒅𝒙   or   ∫ cotᵐ(𝒙) cscⁿ(𝒙) 𝒅𝒙 [📷image-1](./img/Calculus 2 Lecture 7.2/[1-24-25]Integrals involving tangent and secant ∫ tanᵐ(𝒙) secⁿ(𝒙) 𝒅𝒙   or   ∫ cotᵐ(𝒙) cscⁿ(𝒙) 𝒅𝒙_1.png)  [📷image-2](./img/Calculus 2 Lecture 7.2/[1-24-25]Integrals involving tangent and secant ∫ tanᵐ(𝒙) secⁿ(𝒙) 𝒅𝒙   or   ∫ cotᵐ(𝒙) cscⁿ(𝒙) 𝒅𝒙_2.png)
     ◉ Rule 1: If the power of tan(𝒙) or cot(𝒙) is odd.
          ○ Keep one factor sec(𝒙)tan(𝒙).
               ■ Analogously: keep one factor csc(𝒙)cot(𝒙).
          ○ Use:
               ■ tan²(𝒙) = sec²(𝒙) − 1
               ■ cot²(𝒙) = csc²(𝒙) − 1
     ◉ Rule 2: If the power of sec(𝒙) or csc(𝒙) is even.
          ○ Strip off one factor sec²(𝒙).
               ■ Analogously: strip off one factor csc²(𝒙).
          ○ Use:
               ■ sec²(𝒙) = tan²(𝒙) + 1
               ■ csc²(𝒙) = cot²(𝒙) + 1
    ◉ If both rules apply, both methods are valid.
    ◉ Choose the one that makes the algebra simpler.
    ◉ There is no conflict: it is a choice of convenience.
    ◉ NOTE:
          ○ The labels “odd” and “even” apply only to integer powers.
          ○ A fractional exponent such as 1/2 is neither odd nor even.
          ○ In those cases, use the rule based on the other exponent, if that one is an integer odd or even power.
          
● [1:30:05]. 🧩 Example 6 — Tangent power odd: ∫ tan⁵(𝒙) sec³(𝒙) 𝒅𝒙. [📷image](./img/Calculus 2 Lecture 7.2/[1-30-05]Example 6 — Tangent power odd ∫ tan⁵(𝒙) sec³(𝒙) 𝒅𝒙.png)
     ◉ The power of tangent is odd.
          ○ Keep one factor sec(𝒙)tan(𝒙).
     ◉ Rewrite the integrand:
          ○ ∫ tan⁴(𝒙) sec²(𝒙) · sec(𝒙)tan(𝒙) 𝒅𝒙
          ○ = ∫ (tan²(𝒙))² sec²(𝒙) · sec(𝒙)tan(𝒙) 𝒅𝒙
     ◉ Use the identity:
          ○ tan²(𝒙) = sec²(𝒙) − 1
          ○ ∫ (sec²(𝒙) − 1)² sec²(𝒙) · sec(𝒙)tan(𝒙) 𝒅𝒙
     ◉ Substitution:
          ○ 𝒖 = sec(𝒙)
          ○ 𝒅𝒖 = sec(𝒙)tan(𝒙) 𝒅𝒙
     ◉ Resulting polynomial integral in 𝒖:
          ○ ∫ (𝒖² − 1)² 𝒖² 𝒅𝒖
          
● [1:36:39]. 🧩 Example 7 — Evaluate ∫[0, π/4] √tan(𝒙) sec⁶(𝒙) 𝒅𝒙. [📷image-1](./img/Calculus 2 Lecture 7.2/[1-36-39]Example 7 — Evaluate ∫[0, π∕4] √tan(𝒙) sec⁶(𝒙) 𝒅𝒙_1.png)  [📷image-2](./img/Calculus 2 Lecture 7.2/[1-36-39]Example 7 — Evaluate ∫[0, π∕4] √tan(𝒙) sec⁶(𝒙) 𝒅𝒙_2.png)
     ◉ Note:
          ○ The exponent 1/2 is neither odd nor even.
          ○ So the useful pattern comes from sec⁶(𝒙), since the secant power is even.
     ◉ Apply Rule 2.
          ○ Strip off one factor sec²(𝒙).
          ○ Rewrite the remaining secant power:
               ■ √tan(𝒙) sec⁶(𝒙) = (tan(𝒙))¹ᐟ² sec⁴(𝒙) · sec²(𝒙)
               ■ = (tan(𝒙))¹ᐟ² (sec²(𝒙))² · sec²(𝒙)
     ◉ Use the identity:
          ○ sec²(𝒙) = 1 + tan²(𝒙)
          ○ So the integrand becomes:
               ■ (tan(𝒙))¹ᐟ² (1 + tan²(𝒙))² sec²(𝒙) 𝒅𝒙
     ◉ Substitution:
          ○ 𝒖 = tan(𝒙)
          ○ 𝒅𝒖 = sec²(𝒙) 𝒅𝒙
     ◉ Change the bounds:
          ○ When 𝒙 = 0, 𝒖 = 0
          ○ When 𝒙 = π/4, 𝒖 = 1
     ◉ Resulting integral in 𝒖:
          ○ ∫[0,1] 𝒖¹ᐟ² (1 + 𝒖²)² 𝒅𝒖
          ○ = ∫[0,1] (𝒖¹ᐟ² + 2𝒖⁵ᐟ² + 𝒖⁹ᐟ²) 𝒅𝒖
     ◉ Evaluate:
          ○ [ (2/3)𝒖³ᐟ² + (4/7)𝒖⁷ᐟ² + (2/11)𝒖¹¹ᐟ² ]₀¹
          ○ = 2/3 + 4/7 + 2/11
               
● [1:51:18]. 🧩 Example 8 — Integrals involving cosecant and cotangent: Evaluate ∫ cot⁵(𝒙) csc⁵(𝒙) 𝒅𝒙. [📷image](./img/Calculus 2 Lecture 7.2/[1-51-18]Example 8 — Integrals involving cosecant and cotangent Evaluate ∫ cot⁵(𝒙) csc⁵(𝒙) 𝒅𝒙.png)
     ◉ By analogy with the tangent/secant rules, the power of cot(𝒙) is odd.
          ○ Keep one factor csc(𝒙)cot(𝒙).
     ◉ Rewrite the integrand:
          ○ ∫ cot⁴(𝒙) csc⁴(𝒙) · csc(𝒙)cot(𝒙) 𝒅𝒙
          ○ = ∫ (cot²(𝒙))² csc⁴(𝒙) · csc(𝒙)cot(𝒙) 𝒅𝒙
     ◉ Use the identity:
          ○ cot²(𝒙) = csc²(𝒙) − 1
          ○ ∫ (csc²(𝒙) − 1)² csc⁴(𝒙) · csc(𝒙)cot(𝒙) 𝒅𝒙
     ◉ Substitution:
          ○ 𝒖 = csc(𝒙)
          ○ 𝒅𝒖 = −csc(𝒙)cot(𝒙) 𝒅𝒙
          ○ −𝒅𝒖 = csc(𝒙)cot(𝒙) 𝒅𝒙
     ◉ Resulting polynomial integral in 𝒖:
          ○ −∫ (𝒖² − 1)² 𝒖⁴ 𝒅𝒖
          ○ = −∫ (𝒖⁴ − 2𝒖² + 1)𝒖⁴ 𝒅𝒖
          ○ = −∫ (𝒖⁸ − 2𝒖⁶ + 𝒖⁴) 𝒅𝒖
     ◉ Integrate term by term:
          ○ −[ (1/9)𝒖⁹ − (2/7)𝒖⁷ + (1/5)𝒖⁵ ] + 𝓒
     ◉ Final result:
          ○ ∫ cot⁵(𝒙) csc⁵(𝒙) 𝒅𝒙 = −(1/9)csc⁹(𝒙) + (2/7)csc⁷(𝒙) − (1/5)csc⁵(𝒙) + 𝓒






          
Ｏｔｈｅｒ Ｃａｓｅｓ Ｎｏｔ Ｆｉｔｔｉｎｇ Ｔｈｅ Ｓｔａｎｄａｒｄ Ｐａｔｔｅｒｎｓ

● [2:00:35]. Strategies for cases not covered by the standard patterns. [📷image](./img/Calculus 2 Lecture 7.2/[2-00-35]Strategies for cases not covered by the standard patterns.png)
     ◉ If it does not fit the pattern:
          ○ General idea: convert everything to sine and cosine when the standard rules do not apply.
          
● [2:03:23]. 🧩 Example 9 — Simplify ∫ (1 − tan²(𝒙))/sec²(𝒙) 𝒅𝒙. [📷image](./img/Calculus 2 Lecture 7.2/[2-03-23]Example 9 — Simplify ∫ (1 − tan²(𝒙))∕sec²(𝒙) 𝒅𝒙.png)
     ◉ Note: for other cases not covered by the standard patterns, convert to sin(𝒙) and cos(𝒙).
     ◉ Rewrite the fraction:
          ○ ∫ [1/sec²(𝒙) − tan²(𝒙)/sec²(𝒙)] 𝒅𝒙
     ◉ Convert to sine and cosine:
          ○ 1/sec²(𝒙) = cos²(𝒙)
          ○ tan²(𝒙)/sec²(𝒙) = [sin²(𝒙)/cos²(𝒙)] · cos²(𝒙) = sin²(𝒙)
     ◉ So the integrand becomes:
          ○ ∫ [cos²(𝒙) − sin²(𝒙)] 𝒅𝒙
     ◉ Recognize the identity:
          ○ cos²(𝒙) − sin²(𝒙) = cos(2𝒙)
     ◉ Therefore:
          ○ ∫ cos(2𝒙) 𝒅𝒙 = sin(2𝒙)/2 + 𝓒





          
Ｐｒｏｄｕｃｔｓ  Ｗｉｔｈ  Ｄｉｆｆｅｒｅｎｔ Ａｎｇｌｅｓ

● [2:08:13]. Integrals of products with different angles. [📷image](./img/Calculus 2 Lecture 7.2/[2-08-13]Integrals of products with different angles.png)
     ◉ Use product-to-sum identities. [openstax 🌐](https://openstax.org/books/precalculus-2e/pages/7-4-sum-to-product-and-product-to-sum-formulas)
          ○ sin(𝓶𝒙)sin(𝓷𝒙) = (1/2)[cos(𝓶𝒙 − 𝓷𝒙) − cos(𝓶𝒙 + 𝓷𝒙)]
          ○ sin(𝓶𝒙)cos(𝓷𝒙) = (1/2)[sin(𝓶𝒙 − 𝓷𝒙) + sin(𝓶𝒙 + 𝓷𝒙)]
          ○ cos(𝓶𝒙)cos(𝓷𝒙) = (1/2)[cos(𝓶𝒙 − 𝓷𝒙) + cos(𝓶𝒙 + 𝓷𝒙)]
          

          
● [2:13:00]. 🧩 Example 10 — Evaluate ∫[0, π/2] sin(𝒙)cos(2𝒙) 𝒅𝒙.[📷image](./img/Calculus 2 Lecture 7.2/[2-13-00]Example 10 — Evaluate ∫[0, π∕2] sin(𝒙)cos(2𝒙) 𝒅𝒙.png)
     ◉ Use the product-to-sum identity:
          ○ sin(𝒙)cos(2𝒙) = (1/2)[sin(𝒙 − 2𝒙) + sin(𝒙 + 2𝒙)]
          ○ = (1/2)[sin(−𝒙) + sin(3𝒙)]
          ○ = (1/2)[−sin(𝒙) + sin(3𝒙)]
     ◉ Rewrite the integral:
          ○ (1/2)∫[0, π/2] [−sin(𝒙) + sin(3𝒙)] 𝒅𝒙
     ◉ Integrate term by term:
          ○ (1/2)[cos(𝒙) − cos(3𝒙)/3]₀^{π/2}
     ◉ Evaluate the bounds:
          ○ (1/2)[(cos(π/2) − cos(3π/2)/3) − (cos(0) − cos(0)/3)]
          ○ = (1/2)[(0 − 0) − (1 − 1/3)]
          ○ = (1/2)[−2/3]
     ◉ Final result:
          ○ −1/3





Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

[openstax🌐](https://openstax.org/books/calculus-volume-2/pages/3-2-trigonometric-integrals)


