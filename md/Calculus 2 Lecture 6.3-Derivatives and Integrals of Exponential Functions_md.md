-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ６．３： Ｄｅｒｉｖａｔｉｖｅｓ ａｎｄ Ｉｎｔｅｇｒａｌｓ ｏｆ Ｅｘｐｏｎｅｎｔｉａｌ Ｆｕｎｃｔｉｏｎｓ**---------------------------------





Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:01](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=1). Introduction to exponential functions and Euler’s number 𝓮. [📷image](../img/Calculus 2 Lecture 6.3/[0-01]-01.png)
     ◉ Definition of the number 𝓮 as the value satisfying ln(𝓮) = 1.
     ◉ Connection with area under the curve.
          ○ Definition of the natural logarithm as an integral:
               ■ ln(𝒙) = ∫ [1,𝒙] (1/𝒕) 𝒅𝒕
          ○ Interpretation of ln(𝓮) as area under the curve:
               ■ ln(𝓮) = ∫ [1,𝓮] (1/𝒕) 𝒅𝒕 = 1
     ◉ Proof of the existence of 𝓮 using the Intermediate Value Theorem.
          ○ Continuity of ln on (0, ∞).
          ○ Range of ln is (−∞, ∞).
          ○ By the Intermediate Value Theorem, there exists a value 𝓮 such that ln(𝓮) = 1.
     ◉ Equivalence between logarithmic and exponential notation.
          ○ ln(𝒚) = 𝒙   ⇔   𝓮^𝒙 = 𝒚
     ◉ [5:55](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=355). Cancellation properties used in solving equations.
          ○ Proof of the identity ln(𝓮^𝒙) = 𝒙.
               ■ Let 𝒚 = 𝓮^𝒙.
                    ▣ ln(𝒚) = ln(𝓮^𝒙)
               ■ Use the equivalence ln(𝒚) = 𝒙 ⇔ 𝓮^𝒙 = 𝒚.
                    ▣ Since 𝒚 = 𝓮^𝒙, then ln(𝒚) = 𝒙
                    ▣ Therefore, ln(𝓮^𝒙) = 𝒙
          ○ Proof of the identity 𝓮^(ln(𝒙)) = 𝒙.
               ■ Let 𝒙 > 0 and set 𝒖 = ln(𝒙).
                    ▣ ln(𝒙) = 𝒖
               ■ Convert to exponential form using ln(𝒚) = 𝒙 ⇔ 𝓮^𝒙 = 𝒚.
                    ▣ 𝓮^𝒖 = 𝒙
               ■ Substitute 𝒖 = ln(𝒙).
                    ▣ 𝓮^(ln(𝒙)) = 𝒙


        


Ｓｏｌｖｉｎｇ Ｅｑｕａｔｉｏｎｓ ｗｉｔｈ 𝓮 ａｎｄ ｌｎ

● Algebraic methodology for solving equations involving 𝓮 and ln.
     ◉ [8:30](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=510). 🧩 Example – Variable isolation example: 𝓮^(4 − 5𝒙) = 9. [📷image](../img/Calculus 2 Lecture 6.3/[8-30]-01.png)       
          ○ Apply the natural logarithm to both sides:
               ■ ln(𝓮^(4 − 5𝒙)) = ln 9
          ○ Use the cancellation property ln(𝓮^𝒖) = 𝒖:
               ■ 4 − 5𝒙 = ln 9
          ○ Isolate the variable 𝒙:
               ■ −5𝒙 = −4 + ln 9
               ■ 𝒙 = 4/5 − (ln 9)/5
     ◉ [11:14](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=674). 🧩 Example – Variable isolation example: 3𝓮^(5𝒙 − 1) = 2. [📷image](../img/Calculus 2 Lecture 6.3/[11-14]-01.png)       
          ○ Isolate the exponential term:
               ■ 𝓮^(5𝒙 − 1) = 2 / 3
          ○ Apply the natural logarithm to both sides:
               ■ ln(𝓮^(5𝒙 − 1)) = ln(2 / 3)
          ○ Use the cancellation property ln(𝓮^𝒖) = 𝒖:
               ■ 5𝒙 − 1 = ln(2 / 3)
          ○ Solve for 𝒙:
               ■ 5𝒙 = ln(2 / 3) + 1
               ■ 𝒙 = [ln(2 / 3) + 1] / 5
     ◉ [13:30](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=810). 🧩 Example – Variable isolation example: ln(7𝒙 − 1) = 9. [📷image](../img/Calculus 2 Lecture 6.3/[13-30]-01.png)       
          ○ Convert from logarithmic to exponential form:
               ■ 7𝒙 − 1 = 𝓮⁹
          ○ Solve for 𝒙:
               ■ 7𝒙 = 𝓮⁹ + 1
               ■ 𝒙 = (𝓮⁹ + 1) / 7
     ◉ [14:40](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=880). 🧩 Example – Solve the logarithmic equation: ln 𝒙 + ln(𝒙 − 1) = ln 2. [📷image](../img/Calculus 2 Lecture 6.3/[14-40]-01.png) 
          ○ Combine logarithms:
               ■ ln[𝒙(𝒙 − 1)] = ln 2
          ○ Convert to exponential form:
               ■ 𝓮^(ln[𝒙(𝒙 − 1)]) = 𝓮^(ln 2)
          ○ Use the cancellation property 𝓮^(ln(𝒙)) = 𝒙:
               ■ 𝒙(𝒙 − 1) = 2
          ○ Solve the resulting polynomial equation:
               ■ 𝒙² − 𝒙 = 2
               ■ 𝒙² − 𝒙 − 2 = 0
               ■ (𝒙 − 2)(𝒙 + 1) = 0
               ■ 𝒙 = 2, 𝒙 = −1
     ◉ [18:20](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=1100). 🧩 Example – Solve the exponential equation: 𝓮^(2𝒙) − 5𝓮^𝒙 + 6 = 0. [📷image](../img/Calculus 2 Lecture 6.3/[18-20]-01.png) 
          ○ Rewrite using a substitution form:
               ■ (𝓮^𝒙)² − 5(𝓮^𝒙) + 6 = 0
          ○ Substitute 𝒚 = 𝓮^𝒙:
               ■ 𝒚² − 5𝒚 + 6 = 0
          ○ Factor and solve for 𝒚:
               ■ (𝒚 − 3)(𝒚 − 2) = 0
               ■ 𝒚 = 3, 𝒚 = 2
          ○ Convert back to 𝒙:
               ■ 𝓮^𝒙 = 3
                    ▣ ln(𝓮^𝒙) = ln 3
                         ▢ 𝒙 = ln 3
               ■ 𝓮^𝒙 = 2
                    ▣ ln(𝓮^𝒙) = ln 2
                         ▢ 𝒙 = ln 2

        


Ａｎａｌｙｔｉｃ Ｐｒｏｐｅｒｔｉｅｓ ｏｆ 𝓮^𝒙

● [24:40](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=1480). Analytical properties and graphical representation of the function 𝓮^𝒙. [📷image](../img/Calculus 2 Lecture 6.3/[24-40]-01.png)
     ◉ Domain and range.
          ○ Domain of 𝓮^𝒙:
               ■ D = (−∞, ∞)
          ○ Range of 𝓮^𝒙:
               ■ R = (0, ∞)
     ◉ Continuity and concavity.
          ○ Continuity on the entire real line:
               ■ 𝓮^𝒙 is continuous on (−∞, ∞)
          ○ Concavity:
               ■ 𝓮^𝒙 is concave up on (−∞, ∞)
     ◉ Asymptotic behavior and fundamental limits.
          ○ Limits of the exponential function:
               ■ limₓ→∞ 𝓮^𝒙 = ∞
               ■ limₓ→−∞ 𝓮^𝒙 = 0
          ○ Corresponding limits of the logarithmic function:
               ■ limₓ→∞ ln 𝒙 = ∞
               ■ limₓ→0⁺ ln 𝒙 = −∞

              
    


Ｌｉｍｉｔｓ ｗｉｔｈ Ｎｅｇａｔｉｖｅ Ｅｘｐｏｎｅｎｔｓ

● Evaluation of complex limits involving negative powers of e.
     ◉ Algebraic manipulation by dividing through by the dominant exponential term in the denominator, which grows without bound.
     ◉ Analysis of infinitesimal terms and evaluation of constants in the limit.
    
● [34:00](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=2040). 🧩 Example – Limit involving exponential functions as 𝒙 → −∞: limₓ→−∞ (𝓮^(−𝒙) − 2𝓮^(2𝒙)) / (𝓮^(−2𝒙) + 3𝓮^(2𝒙)) [📷image](../img/Calculus 2 Lecture 6.3/[34-00]-01.png)
     ◉ Simplify by dividing numerator and denominator by 𝓮^(−2𝒙), It is the dominant term (it grows without bound) :
          ○ limₓ→−∞ (𝓮^𝒙 − 2𝓮^(4𝒙)) / (1 + 3𝓮^(4𝒙))
     ◉ Evaluate the limit using exponential behavior:
          ○ As 𝒙 → −∞, 𝓮^𝒙 → 0 and 𝓮^(4𝒙) → 0
     ◉ Final evaluation:
          ○ (0 − 0) / (1 + 0) = 0

● [40:41](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=2441). 🧩 Example – Evaluate the limit: limₓ→0⁺  𝓮^(1/ln 𝒙) / (2 + cos(π𝓮^(−𝒙))). [📷image](../img/Calculus 2 Lecture 6.3/[40-41]-01.png)
     ◉ Analyze each component as 𝒙 → 0⁺.
          ○ Exponential term:
               ■ ln 𝒙 → −∞
                    ▣ 1/ln 𝒙 → 0
                         ▢ 𝓮^(1/ln 𝒙) → 1
          ○ Trigonometric term:
               ■ 𝓮^(−𝒙) → 1
                    ▣ π𝓮^(−𝒙) → π
                         ▢ cos(π𝓮^(−𝒙)) → cos(π) = −1
          ○ Combine the limits:
               ■ limₓ→0⁺  𝓮^(1/ln 𝒙) / (2 + cos(π𝓮^(−𝒙))) = 1 / (2 + (−1))
                    ▣ = 1


    


Ｄｅｒｉｖａｔｉｖｅｓ and  Ｉｎｔｅｇｒａｌｓ ｏｆ Ｎａｔｕｒａｌ Ｅｘｐｏｎｅｎｔｉａｌ Ｆｕｎｃｔｉｏｎｓ

● [45:00](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=2700). Differential calculus applied to natural exponential functions. [📷image](../img/Calculus 2 Lecture 6.3/[45-00]-01.png)
     ◉ Fundamental derivative rule.
          ○ Statement of the theorem:
               ■ 𝒅/𝒅𝒙 [𝓮^𝒙] = 𝓮^𝒙
     ◉ Analytical proof using logarithmic differentiation.
          ○ Define the function:
               ■ 𝒚 = 𝓮^𝒙
          ○ Take natural logarithms on both sides:
               ■ ln 𝒚 = ln(𝓮^𝒙)
               ■ ln 𝒚 = 𝒙
          ○ Differentiate implicitly with respect to 𝒙:
               ■ 𝒅/𝒅𝒙 [ln 𝒚] = 𝒅/𝒅𝒙 [𝒙]
               ■ (1/𝒚) · 𝒅𝒚/𝒅𝒙 = 1
          ○ Solve for d𝒚/d𝒙:
               ■ 𝒅𝒚/𝒅𝒙 = 𝒚
               ■ 𝒅𝒚/𝒅𝒙 = 𝓮^𝒙
     ◉ Chain rule extension.
          ○ General exponential function:
               ■ 𝒅/𝒅𝒙 [𝓮^{𝒇(𝒙)}] = 𝓮^{𝒇(𝒙)} · 𝒅/𝒅𝒙 [𝒇(𝒙)]
          ○ Equivalent notation using an auxiliary variable:
               ■ Let 𝒖 = 𝒇(𝒙)
               ■ 𝒅/𝒅𝒙 [𝓮^𝒖] = 𝓮^𝒖 · 𝒅𝒖/𝒅𝒙    
     ◉ [50:40](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=3040). 🧩 Example – Differentiate the function: 𝓮^(−𝒙³). [📷image](../img/Calculus 2 Lecture 6.3/[50-40]-01.png)
          ○ Identify the composite structure:
               ■ Outer function: 𝓮^𝒖
               ■ Inner function: 𝒖 = −𝒙³
          ○ Apply the chain rule:
               ■ 𝒅/𝒅𝒙 [𝓮^(−𝒙³)] = 𝓮^(−𝒙³) · 𝒅/𝒅𝒙 [−𝒙³]
          ○ Differentiate the inner function:
               ■ 𝒅/𝒅𝒙 [−𝒙³] = −3𝒙²
          ○ Final result:
               ■ 𝒅/𝒅𝒙 [𝓮^(−𝒙³)] = −3𝒙² · 𝓮^(−𝒙³)
     ◉ [52:25](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=3145). 🧩 Example – Differentiate the function: 𝒙²𝓮^(−2𝒙). [📷image](../img/Calculus 2 Lecture 6.3/[52-25]-01.png)
          ○ Reminder: first identify which rules are needed to compute the derivative.
               ■ Product rule.
               ■ Chain rule.
          ○ Apply the product rule:
               ■ 𝒅/𝒅𝒙 [𝒙²𝓮^(−2𝒙)] = 𝒅/𝒅𝒙[𝒙²] · 𝓮^(−2𝒙) + 𝒙² · 𝒅/𝒅𝒙[𝓮^(−2𝒙)]
          ○ Differentiate each factor:
               ■ 𝒅/𝒅𝒙[𝒙²] = 2𝒙
               ■ 𝒅/𝒅𝒙[𝓮^(−2𝒙)] = 𝓮^(−2𝒙) · 𝒅/𝒅𝒙[−2𝒙]
                    ▣ 𝒅/𝒅𝒙[−2𝒙] = −2
          ○ Combine the results:
               ■ 2𝒙𝓮^(−2𝒙) − 2𝒙²𝓮^(−2𝒙)
          ○ Factor the common terms:
               ■ 2𝒙𝓮^(−2𝒙)(1 − 𝒙)
     ◉ [56:10](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=3370). 🧩 Example – Differentiate the function 𝒚 = ln(𝓮^{√𝒙} + 𝓮^{−√𝒙}). [📷image](../img/Calculus 2 Lecture 6.3/[56-10]-01.png)
          ○ Identify the outer and inner structure.
               ■ Outer function: ln(·)
               ■ Inner function: 𝓮^{√𝒙} + 𝓮^{−√𝒙}
          ○ Apply the chain rule for the logarithm.
               ■ 𝒅𝒚/𝒅𝒙 = 1 / (𝓮^{√𝒙} + 𝓮^{−√𝒙}) · 𝒅/𝒅𝒙[𝓮^{√𝒙} + 𝓮^{−√𝒙}]
          ○ Differentiate each exponential term.
               ■ 𝒅/𝒅𝒙[𝓮^{√𝒙}] = 𝓮^{√𝒙} · 𝒅/𝒅𝒙[√𝒙]
                    ▣ 𝒅/𝒅𝒙[√𝒙] = 1 / (2√𝒙)
               ■ 𝒅/𝒅𝒙[𝓮^{−√𝒙}] = 𝓮^{−√𝒙} · 𝒅/𝒅𝒙[−√𝒙]
                    ▣ 𝒅/𝒅𝒙[−√𝒙] = −1 / (2√𝒙)
          ○ Combine the derivatives.
               ■ 𝒅/𝒅𝒙[𝓮^{√𝒙} + 𝓮^{−√𝒙}]
                    ▣ = 𝓮^{√𝒙}/(2√𝒙) − 𝓮^{−√𝒙}/(2√𝒙)
          ○ Substitute back into the logarithmic derivative.
               ■ 𝒅𝒚/𝒅 𝒙 = 1/(𝓮^{√𝒙} + 𝓮^{−√𝒙}) · (𝓮^{√𝒙} − 𝓮^{−√𝒙})/(2√𝒙)
          ○ Final simplified form.
               ■ 𝒅𝒚/𝒅𝒙 = (𝓮^{√𝒙} − 𝓮^{−√𝒙}) / [2√𝒙 (𝓮^{√𝒙} + 𝓮^{−√𝒙})]
     ◉ [56:10](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=3370). 🧩 Example – First identify which rules are needed to compute the derivative. [📷image](../img/Calculus 2 Lecture 6.3/[56-10]-02.png)
          ○ Function 1:
               ■ 𝒇(𝒙) = 𝓮^{𝒙 ln 𝒙}
                    ▣ Chain rule.
                    ▣ Product rule (inside the exponent 𝒙 ln 𝒙).
          ○ Function 2:
               ■ 𝒈(𝒙) = (𝓮^{2𝒙} − 𝓮^{−3𝒙})⁵
                    ▣ Chain rule (outer power).
                    ▣ Sum / difference rule.
                    ▣ Chain rule (inside each exponential).
          ○ Function 3:
               ■ 𝒉(𝒙) = 𝓮^{−𝒙} · tan(𝓮^𝒙)
                    ▣ Product rule.
                    ▣ Chain rule (for 𝓮^{−𝒙}).
                    ▣ Chain rule (for tan(𝓮^𝒙)).

● [1:6:48](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=4008). Integral calculus of natural exponential functions.
     ◉ Fundamental integration rule: ∫ 𝓮^𝒙 𝒅𝒙 = 𝓮^𝒙 + 𝓒.
     ◉ [1:08:15](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=4095). 🧩 Example – Use of substitution with the variable 𝒖:  ∫ 𝓮^(2𝒙) 𝒅𝒙 [📷image](../img/Calculus 2 Lecture 6.3/[1-08-15]-01.png)
          ○ Choose the substitution:
               ■ Let 𝒖 = 2𝒙
                    ▣ 𝒅𝒖 = 2 𝒅𝒙
                    ▣ 𝒅𝒙 = 𝒅𝒖 / 2
          ○ Rewrite the integral in terms of 𝒖:
               ■ ∫ 𝓮^𝒖 (𝒅𝒖 / 2)
                    ▣ = (1/2) ∫ 𝓮^𝒖 𝒅𝒖
          ○ Integrate with respect to 𝒖:
               ■ (1/2) 𝓮^𝒖 + 𝓒
          ○ Substitute back to the original variable:
               ■ (1/2) 𝓮^(2𝒙) + 𝓒
     ◉ [1:11:45](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=4305). 🧩 Example – Use of substitution with the variable 𝒖: ∫ 𝓮^(2/𝒙) / 𝒙² 𝒅𝒙 [📷image](../img/Calculus 2 Lecture 6.3/[1-11-45]-01.png)
          ○ Choose the substitution:
               ■ Let 𝒖 = 2/𝒙
                    ▣ 𝒖 = 2𝒙⁻¹
                    ▣ 𝒅𝒖 = −2𝒙⁻² 𝒅𝒙
                    ▣ 𝒅𝒖 = −2 / 𝒙² 𝒅𝒙
          ○ Solve for 𝒅𝒙:
               ■ 𝒅𝒙 = (𝒙² / −2) 𝒅𝒖
          ○ Rewrite the integral in terms of 𝒖:
               ■ ∫ (𝓮^𝒖 / 𝒙²) · (𝒙² / −2) 𝒅𝒖
                    ▣ = −1/2 ∫ 𝓮^𝒖 𝒅𝒖
          ○ Integrate with respect to 𝒖:
               ■ −1/2 𝓮^𝒖 + 𝓒
          ○ Substitute back to the original variable:
               ■ −1/2 𝓮^(2/𝒙) + 𝓒
     ◉ [1:16:45](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=4605). 🧩 Example – Use of substitution with the variable 𝒖: [📷image](../img/Calculus 2 Lecture 6.3/[1-16-45]-01.png)
          ○ Choose the substitution:
               ■ Let 𝒖 = 1 + 𝓮^(−𝒙)
                    ▣ 𝒅𝒖 = 𝓮^(−𝒙) · d/𝒅𝒙[−𝒙] 𝒅𝒙
                    ▣ 𝒅𝒖 = −𝓮^(−𝒙) 𝒅𝒙
          ○ Solve for 𝒅𝒙:
               ■ 𝒅𝒙 = 𝒅𝒖 / (−𝓮^(−𝒙))
          ○ Rewrite the integral in terms of 𝒖:
               ■ ∫ (𝓮^(−𝒙) / 𝒖) · (𝒅𝒖 / −𝓮^(−𝒙))
                    ▣ = − ∫ (1/𝒖) 𝒅𝒖
          ○ Integrate with respect to 𝒖:
               ■ − ∫ (1/𝒖) 𝒅𝒖
                    ▣ = − ln |𝒖| + 𝓒
          ○ Substitute back to the original variable:
               ■ − ln |1 + 𝓮^(−𝒙)| + 𝓒
     ◉ [1:23:12](https://www.youtube.com/watch?v=5HlW7OnXUT4&t=4992). 🧩 Example – Use of substitution with the variable 𝒖: ∫ 𝓮^(−𝒙) sec(𝓮^(−𝒙)) 𝒅𝒙 [📷image](../img/Calculus 2 Lecture 6.3/[1-23-12]-01.png)
          ○ Choose the substitution:
               ■ Let 𝒖 = 𝓮^(−𝒙)
                    ▣ 𝒅𝒖 = −𝓮^(−𝒙) 𝒅𝒙
                    ▣ −𝒅𝒖 = 𝓮^(−𝒙) 𝒅𝒙
          ○ Rewrite the integral in terms of 𝒖:
               ■ ∫ sec(𝒖) (−𝒅𝒖)
                    ▣ = − ∫ sec(𝒖) 𝒅𝒖
          ○ Use the standard integral:
               ■ ∫ sec(𝒖) 𝒅𝒖 = ln|sec(𝒖) + tan(𝒖)| + 𝓒
          ○ Apply the result and substitute back:
               ■ − ln|sec(𝒖) + tan(𝒖)| + 𝓒
                    ▣ − ln|sec(𝓮^(−𝒙)) + tan(𝓮^(−𝒙))| + 𝓒


