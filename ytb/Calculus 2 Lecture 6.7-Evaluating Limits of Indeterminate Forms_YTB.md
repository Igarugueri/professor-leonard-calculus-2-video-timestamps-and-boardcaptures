--------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ６．７ － Ｅｖａｌｕａｔｉｎｇ Ｌｉｍｉｔｓ ｏｆ Ｉｎｄｅｔｅｒｍｉｎａｔｅ Ｆｏｒｍｓ**---------------------------—






Ｉｎｔｒｏｄｕｃｔｉｏｎ  and Ｌ’Ｈôｐｉｔａｌ’ｓ Ｒｕｌｅ


● [0:00]. Introduction to Section 6.7: Indeterminate Forms of Limits.
     ◉ Concept of indeterminate forms and a simplified first approach.
          ○ Limits as a fundamental idea of calculus and their relation to derivatives.
               ■ A derivative is defined as a limit.
               ■ It represents the limiting value of a slope.
               ■ We let two points get arbitrarily close until the secant slope approaches a single value.
          ○ The origin of the derivative as the limit of a difference quotient.

● [1:32]. First indeterminate form: 0/0.
     ◉ Evaluating limₓ→𝒖 𝒇(𝒙)/𝓰(𝒙) when both numerator and denominator approach 0.
          ○ If both the numerator and denominator go to 0, the quotient is not automatically determined.
          ○ The expression must be analyzed more carefully.
     ◉ Proposed analysis: compare the behavior of the derivative ratio 𝒅𝒇/𝒅𝒙 and 𝒅𝓰/𝒅𝒙.
          ○ This leads to the idea behind L’Hôpital’s Rule.


● [3:02]. Introduction to L’Hôpital’s Rule.
     ◉ Conceptual explanation in terms of the ratio of rates of change.
     ◉ Validity premise for indeterminate forms of type 0/0.
          ○ If
               ■ limₓ→𝒂 𝒇(𝒙)/𝓰(𝒙) = 0/0,
          ○ then another idea is:
               ■ limₓ→𝒂 𝒇(𝒙)/𝓰(𝒙) = limₓ→𝒂 𝒇′(𝒙)/𝓰′(𝒙)
          ○ Only if the original limit is truly of indeterminate form 0/0.

● [3:23]. 🧩 Example 1 — Evaluate limₓ→2 4(𝒙² − 4)/(𝒙 − 2).
     ◉ MANDATORY verification of the indeterminate form 0/0.
          ○ Substituting 𝒙 = 2 gives:
               ■ 4(2² − 4)/(2 − 2) = 0/0
     ◉ Traditional method: remove the removable discontinuity by factoring.
          ○ 𝒙² − 4 = (𝒙 − 2)(𝒙 + 2)
          ○ Therefore:
               ■ limₓ→2 4(𝒙² − 4)/(𝒙 − 2)
               ■ = limₓ→2 4(𝒙 − 2)(𝒙 + 2)/(𝒙 − 2)
               ■ = limₓ→2 4(𝒙 + 2)
               ■ = 16
     ◉ [9:21]. Solution using L’Hôpital’s Rule.
          ○ Apply L’Hôpital:
               ■ limₓ→2 4(𝒙² − 4)/(𝒙 − 2)
               ■ ⟶ limₓ→2 [𝒅/𝒅𝒙 (4(𝒙² − 4))] / [𝒅/𝒅𝒙 (𝒙 − 2)]
          ○ Numerator derivative:
               ■ 𝒅/𝒅𝒙 [4(𝒙² − 4)] = 4 · 2𝒙 = 8𝒙
          ○ Denominator derivative:
               ■ 𝒅/𝒅𝒙 [𝒙 − 2] = 1
          ○ Final evaluation:
               ■ limₓ→2 8𝒙/1 = 16

● [5:58]. 🧩 Example 2 — Evaluate limₓ→₀ (sin 𝒙)/𝒙.
     ◉ Fundamental trigonometric limit.
          ○ limₓ→₀ (sin 𝒙)/𝒙 = 0/0
          ○ Classical proof using the Squeeze Theorem.
     ◉ [10:55]. Application of L’Hôpital’s Rule.
          ○ Apply L’Hôpital:
               ■ limₓ→₀ (sin 𝒙)/𝒙
               ■ ⟶ limₓ→₀ (cos 𝒙)/1
          ○ Derivatives:
               ■ 𝒅/𝒅𝒙 [sin 𝒙] = cos 𝒙
               ■ 𝒅/𝒅𝒙 [𝒙] = 1
          ○ Final result:
               ■ cos(0)/1 = 1

● [7:25]. Formal statement of L’Hôpital’s Rule.
     ◉ limₓ→𝒖 𝒇(𝒙)/𝓰(𝒙) = limₓ→𝒖 [𝒅/𝒅𝒙 𝒇(𝒙)] / [𝒅/𝒅𝒙 𝓰(𝒙)].
     ◉ Important distinction: L’Hôpital’s Rule is not the Quotient Rule.
     




          
Ｉｎｆｉｎｉｔｙ ｏｖｅｒ Ｉｎｆｉｎｉｔｙ


● [12:30]. Extension to the indeterminate form ∞/∞.
     ◉ Algebraic justification using reciprocals.
          ○ If limₓ→𝒂 𝒇(𝒙)/𝓰(𝒙) gives the form ∞/∞,
               ■ then rewriting the expression as
                    ▣ (1/𝓰(𝒙)) / (1/𝒇(𝒙))
                 transforms it into the form 0/0.
          ○ This shows that the same idea behind L’Hôpital’s Rule also applies to ∞/∞.

● [14:55]. Formal statement including both indeterminate forms.
     ◉ i̲f̲ 
          ○ limₓ→𝒂 𝒇(𝒙)/𝓰(𝒙) = 0/0 or ∞/∞,
     ◉ t̲h̲e̲m̲
          ○ limₓ→𝒂 𝒇(𝒙)/𝓰(𝒙) = limₓ→𝒂 𝒇′(𝒙)/𝓰′(𝒙),
               ■ provided the limit on the right exists.

● [15:36]. General scope of L’Hôpital’s Rule.
     ◉ Valid for one-sided limits:
          ○ limₓ→𝒂⁺
          ○ limₓ→𝒂⁻
     ◉ Valid for limits at infinity:
          ○ limₓ→∞
          ○ limₓ→−∞

● [16:00]. Important note before applying the rule.
     ◉ You must verify first that the original expression is truly of indeterminate form.
          ○ The rule applies only to:
               ■ 0/0
               ■ ∞/∞ 
     ◉ Requirement of verifying the indeterminate form before applying L’Hôpital’s Rule
          ○ [17:36]. 🧩 Counterexample — Analyze limₓ→₀⁺ (cos 𝒙)/𝒙. [📷image](./img/Calculus 2 Lecture 6.7/[17-36]Counterexample — Analyze limₓ→₀⁺ (cos 𝒙)∕𝒙.png)
               ■ Form check:
                    ▣ As 𝒙 → 0⁺, cos 𝒙 → 1 and 𝒙 → 0
                    ▣ Therefore the expression has the form 1/0 → ∞, not an indeterminate form
               ■ Incorrect application of L’Hôpital’s Rule:
                    ▣ Differentiating would give limₓ→₀⁺ (−sin 𝒙)/1 = 0
                    ▣ This contradicts the actual behavior of the original limit
               ■ Key conclusion:
                    ▣ L’Hôpital’s Rule cannot be applied unless the original limit is first verified to be of type 0/0 or ∞/∞




          
Ｐｒａｃｔｉｃｅ Ｐｒｏｂｌｅｍｓ

● [19:48]. 🧩 Example — Exponential functions: limₓ→₀ (𝒆ˣ − 1)/(2𝒙). 
     ◉ You must verify first that the original expression is truly of indeterminate form.
          ○ As 𝒙 → 0, 𝒆ˣ − 1 → 0 and 2𝒙 → 0
          ○ Therefore:
               ■ limₓ→₀ (𝒆ˣ − 1)/(2𝒙) = 0/0
     ◉ Apply L’Hôpital’s Rule.
          ○ Differentiate the numerator and denominator:
               ■ 𝒅/𝒅𝒙 [𝒆ˣ − 1] = 𝒆ˣ
               ■ 𝒅/𝒅𝒙 [2𝒙] = 2
     ◉ Evaluate the new limit.
          ○ limₓ→₀ 𝒆ˣ/2 = 𝒆⁰/2 = 1/2
     ◉ Final result:
          ○ limₓ→₀ (𝒆ˣ − 1)/(2𝒙) = 1/2
          
● [22:11]. 🧩 Example — Logarithmic functions: limₓ→∞ (ln 𝒙)/𝒙. 
     ◉ You must verify first that the original expression is truly of indeterminate form.
          ○ As 𝒙 → ∞, ln 𝒙 → ∞ and 𝒙 → ∞
          ○ Therefore:
               ■ limₓ→∞ (ln 𝒙)/𝒙 = ∞/∞
     ◉ Apply L’Hôpital’s Rule.
          ○ Differentiate the numerator and denominator:
               ■ 𝒅/𝒅𝒙 [ln 𝒙] = 1/𝒙
               ■ 𝒅/𝒅𝒙 [𝒙] = 1
     ◉ Evaluate the new limit.
          ○ limₓ→∞ (1/𝒙)/1 = 0
     ◉ Final result:
          ○ limₓ→∞ (ln 𝒙)/𝒙 = 0
          
● [24:34]. 🧩 Example — Composite trigonometric functions: limₓ→π [2 sin² 𝒙] / [1 + cos 𝒙]. 
     ◉ You must verify first that the original expression is truly of indeterminate form.
          ○ As 𝒙 → π, sin π = 0 and cos π = −1
          ○ Therefore:
               ■ limₓ→π [2 sin² 𝒙] / [1 + cos 𝒙] = 0/0
     ◉ Apply L’Hôpital’s Rule.
          ○ Differentiate the numerator using the Chain Rule:
               ■ 𝒅/𝒅𝒙 [2 sin² 𝒙] = 4 sin 𝒙 cos 𝒙
          ○ Differentiate the denominator:
               ■ 𝒅/𝒅𝒙 [1 + cos 𝒙] = −sin 𝒙
     ◉ Simplify before evaluating.
          ○ limₓ→π [4 sin 𝒙 cos 𝒙] / [−sin 𝒙]
          ○ = limₓ→π [−4 cos 𝒙]
     ◉ Final evaluation:
          ○ −4 cos π = −4(−1) = 4
     ◉ Final result:
          ○ limₓ→π [2 sin² 𝒙] / [1 + cos 𝒙] = 4





Ｒｅｐｅａｔｅｄ Ａｐｐｌｉｃａｔｉｏｎ

● [27:50]. 🧩 Example — Repeated application of L’Hôpital’s Rule: limₓ→∞ 𝒙³/𝒆²ˣ. 
     ◉ You must verify first that the original expression is truly of indeterminate form.
          ○ As 𝒙 → ∞, 𝒙³ → ∞ and 𝒆²ˣ → ∞
          ○ Therefore:
               ■ limₓ→∞ 𝒙³/𝒆²ˣ = ∞/∞
     ◉ First application of L’Hôpital’s Rule.
          ○ Differentiate the numerator and denominator:
               ■ 𝒅/𝒅𝒙 [𝒙³] = 3𝒙²
               ■ 𝒅/𝒅𝒙 [𝒆²ˣ] = 2𝒆²ˣ
          ○ New limit:
               ■ limₓ→∞ 3𝒙²/(2𝒆²ˣ)
     ◉ Second application of L’Hôpital’s Rule.
          ○ The new form is still ∞/∞
          ○ Differentiate again:
               ■ 𝒅/𝒅𝒙 [3𝒙²] = 6𝒙
               ■ 𝒅/𝒅𝒙 [2𝒆²ˣ] = 4𝒆²ˣ
          ○ New limit:
               ■ limₓ→∞ 6𝒙/(4𝒆²ˣ)
     ◉ Third application of L’Hôpital’s Rule.
          ○ The new form is still ∞/∞
          ○ Differentiate once more:
               ■ 𝒅/𝒅𝒙 [6𝒙] = 6
               ■ 𝒅/𝒅𝒙 [4𝒆²ˣ] = 8𝒆²ˣ
          ○ New limit:
               ■ limₓ→∞ 6/(8𝒆²ˣ)
     ◉ Final evaluation:
          ○ As 𝒙 → ∞, 𝒆²ˣ → ∞
          ○ Therefore:
               ■ limₓ→∞ 6/(8𝒆²ˣ) = 0
     ◉ Final result:
          ○ limₓ→∞ 𝒙³/𝒆²ˣ = 0

● [32:00]. 🧩 Example — Repeated application of L’Hôpital’s Rule: limₓ→₀ 𝒙³/(𝒙 − tan 𝒙). 
     ◉ You must verify first that the original expression is truly of indeterminate form.
          ○ As 𝒙 →₀, 𝒙³ → 0 and 𝒙 − tan 𝒙 → 0
          ○ Therefore:
               ■ limₓ→₀ 𝒙³/(𝒙 − tan 𝒙) = 0/0
     ◉ First application of L’Hôpital’s Rule.
          ○ Differentiate the numerator and denominator:
               ■ 𝒅/𝒅𝒙 [𝒙³] = 3𝒙²
               ■ 𝒅/𝒅𝒙 [𝒙 − tan 𝒙] = 1 − sec² 𝒙
          ○ New limit:
               ■ limₓ→₀ 3𝒙²/(1 − sec² 𝒙)
          ○ This is still of type 0/0.
     ◉ Second application of L’Hôpital’s Rule.
          ○ Differentiate again:
               ■ 𝒅/𝒅𝒙 [3𝒙²] = 6𝒙
               ■ 𝒅/𝒅𝒙 [1 − sec² 𝒙] = −2 sec² 𝒙 tan 𝒙
          ○ New limit:
               ■ limₓ→₀ 6𝒙/(−2 sec² 𝒙 tan 𝒙)
          ○ This is still of type 0/0.
     ◉ Third application of L’Hôpital’s Rule.
          ○ Differentiate the numerator:
               ■ 𝒅/𝒅𝒙 [6𝒙] = 6
          ○ Differentiate the denominator using the Product Rule:
               ■ 𝒅/𝒅𝒙 [−2 sec² 𝒙 tan 𝒙]
               ■ = 𝒅/𝒅𝒙 [−2 sec² 𝒙] · tan 𝒙 + (−2 sec² 𝒙) · 𝒅/𝒅𝒙 [tan 𝒙]
               ■ = (−4 sec² 𝒙 tan 𝒙) tan 𝒙 − 2 sec² 𝒙 sec² 𝒙
               ■ = −4 sec² 𝒙 tan² 𝒙 − 2 sec⁴ 𝒙
          ○ New limit:
               ■ limₓ→₀ 6/(−4 sec² 𝒙 tan² 𝒙 − 2 sec⁴ 𝒙)
     ◉ Final evaluation:
          ○ At 𝒙 = 0:
               ■ tan 0 = 0
               ■ sec 0 = 1
          ○ Therefore:
               ■ 6/(−4·1·0 − 2·1) = 6/(−2) = −3
     ◉ Final result:
          ○ limₓ→₀ 𝒙³/(𝒙 − tan 𝒙) = −3




     
     
Ｏｔｈｅｒ Ｉｎｄｅｔｅｒｍｉｎａｔｅ Ｆｏｒｍｓ ∞ − ∞  and   0 · ∞

● [41:19]. Indeterminate form ∞ − ∞. 
     ◉ Strategy for ∞ − ∞:
          ○ Rewrite the expression algebraically as a single fraction.
          ○ Then check whether the new form becomes 0/0 or ∞/∞.
          ○ Only after that can L’Hôpital’s Rule be applied.
     ◉ [43:15]. 🧩 Example — limₓ→₀⁺ (1/𝒙 − 1/(1 − cos 𝒙)). 
          ○ The original form is ∞ − ∞, so L’Hôpital’s Rule cannot be used immediately.
          ○ Rewrite using a common denominator:
               ■ limₓ→₀⁺ [ (1 − cos 𝒙) − 𝒙 ] / [ 𝒙(1 − cos 𝒙) ]
          ○ Verify the new indeterminate form:
               ■ As 𝒙 → 0⁺, the numerator → 0 and the denominator → 0
               ■ Therefore the expression becomes 0/0
          ○ Apply L’Hôpital’s Rule.
               ■ Numerator derivative:
                    ▣ 𝒅/𝒅𝒙 [1 − cos 𝒙 − 𝒙] = sin 𝒙 − 1
               ■ Denominator derivative:
                    ▣ 𝒅/𝒅𝒙 [𝒙 − 𝒙 cos 𝒙] = 1 − [cos 𝒙 + 𝒙(−sin 𝒙)]
                    ▣ = 1 − cos 𝒙 + 𝒙 sin 𝒙
          ○ Evaluate the new limit:
               ■ limₓ→₀⁺ (sin 𝒙 − 1) / (1 − cos 𝒙 + 𝒙 sin 𝒙)
               ■ = −1 / 0⁺
          ○ Final result:
               ■ limₓ→₀⁺ (1/𝒙 − 1/(1 − cos 𝒙)) = −∞
          
● [52:40]. Indeterminate form 0 · ∞. 
     ◉ Strategy for 0 · ∞:
          ○ Rewrite the expression as a quotient by using the reciprocal of one factor.
          ○ Then check whether the new expression becomes 0/0 or ∞/∞.
          ○ Only after that can L’Hôpital’s Rule be applied.
     ◉ [54:17]. 🧩 Example — Analyze limₓ→₀⁺ csc 𝒙 · ln(1 − sin 𝒙). 
          ○ Verify the original indeterminate form.
               ■ As 𝒙 → 0⁺, csc 𝒙 = 1/sin 𝒙 → ∞
               ■ As 𝒙 → 0⁺, ln(1 − sin 𝒙) → ln(1) = 0
               ■ Therefore the expression has the form 0 · ∞
          ○ Rewrite as a quotient.
               ■ csc 𝒙 = 1/sin 𝒙
               ■ So:
                    ▣ limₓ→₀⁺ csc 𝒙 · ln(1 − sin 𝒙)
                    ▣ = limₓ→₀⁺ ln(1 − sin 𝒙) / sin 𝒙
          ○ Verify the new indeterminate form.
               ■ As 𝒙 → 0⁺, ln(1 − sin 𝒙) → 0 and sin 𝒙 → 0
               ■ Therefore the quotient is now of type 0/0
          ○ Apply L’Hôpital’s Rule.
               ■ Numerator derivative:
                    ▣ 𝒅/𝒅𝒙 [ln(1 − sin 𝒙)] = −cos 𝒙 / (1 − sin 𝒙)
               ■ Denominator derivative:
                    ▣ 𝒅/𝒅𝒙 [sin 𝒙] = cos 𝒙
          ○ Simplify the new quotient.
               ■ limₓ→₀⁺ [−cos 𝒙 / (1 − sin 𝒙)] / cos 𝒙
               ■ = limₓ→₀⁺ −1 / (1 − sin 𝒙)
          ○ Final evaluation.
               ■ −1 / (1 − sin 0) = −1
          ○ Final result:
               ■ limₓ→₀⁺ csc 𝒙 · ln(1 − sin 𝒙) = −1




          
Ｅｘｐｏｎｅｎｔｉａｌ Ｉｎｄｅｔｅｒｍｉｎａｔｅ Ｆｏｒｍｓ   0⁰,   ∞⁰,   and   1^∞
 
● [58:03]. Exponential indeterminate forms: 0⁰, ∞⁰, and 1^∞. 
     ◉ [1:00:13]. Logarithmic transformation method: 𝒇(𝒙)^𝓰(𝒙) = 𝒆^{𝓰(𝒙) ln 𝒇(𝒙)}.

● [1:01:21]. 🧩 Case Study — limₓ→₀⁺ 𝒙ˣ. 
     ◉ Recognize the indeterminate exponential form.
          ○ As 𝒙 → 0⁺,
               ■ 𝒙 → 0
               ■ 𝒙 → 0
          ○ Therefore:
               ■ 𝒙ˣ has the indeterminate form 0⁰
     ◉ Use the logarithmic-exponential transformation.
          ○ 𝒙ˣ = 𝒆^{ln(𝒙ˣ)}
          ○ 𝒙ˣ = 𝒆^{𝒙 ln 𝒙}
     ◉ Use continuity of the exponential function.
          ○ limₓ→₀⁺ 𝒙ˣ = 𝒆^{limₓ→₀⁺ 𝒙 ln 𝒙}
     ◉ Analyze the exponent.
          ○ As 𝒙 → 0⁺,
               ■ 𝒙 ln 𝒙 = 0 · (−∞)
          ○ Rewrite it as a quotient:
               ■ 𝒙 ln 𝒙 = (ln 𝒙)/(1/𝒙)
          ○ This gives the indeterminate form:
               ■ (−∞)/(∞)
     ◉ Apply L’Hôpital’s Rule to the exponent.
          ○ Differentiate the numerator and denominator:
               ■ 𝒅/𝒅𝒙 [ln 𝒙] = 1/𝒙
               ■ 𝒅/𝒅𝒙 [1/𝒙] = −1/𝒙²
          ○ Therefore:
               ■ limₓ→₀⁺ (ln 𝒙)/(1/𝒙) = limₓ→₀⁺ (1/𝒙)/(−1/𝒙²)
               ■ = limₓ→₀⁺ (−𝒙)
               ■ = 0
     ◉ Final evaluation.
          ○ limₓ→₀⁺ 𝒙ˣ = 𝒆⁰ = 1      
    
● [1:15:15]. 🧩 Case Study — limₓ→π/2⁻ (tan 𝒙)^{cos 𝒙}. 
     ◉ Verify the indeterminate form.
          ○ As 𝒙 → π⁄₂⁻:
               ■ tan 𝒙 → ∞
               ■ cos 𝒙 → 0
          ○ Therefore:
               ■ (tan 𝒙)^{cos 𝒙} has the indeterminate form ∞⁰
     ◉ Exponential rewrite.
          ○ Let
               ■ 𝒚 = (tan 𝒙)^{cos 𝒙}
          ○ Then
               ■ ln 𝒚 = cos 𝒙 · ln(tan 𝒙)
          ○ So
               ■ 𝒚 = 𝒆^{cos 𝒙 · ln(tan 𝒙)}
     ◉ Convert the exponent into a quotient.
          ○ cos 𝒙 · ln(tan 𝒙) = ln(tan 𝒙) / sec 𝒙
          ○ Therefore study
               ■ limₓ→π⁄₂⁻  ln(tan 𝒙) / sec 𝒙 has the indeterminate form ∞/∞ 
     ◉ Apply L’Hôpital’s Rule to the exponent.
          ○ Numerator derivative:
               ■ 𝒅/𝒅𝒙 [ln(tan 𝒙)] = (1/tan 𝒙) · sec² 𝒙
          ○ Denominator derivative:
               ■ 𝒅/𝒅𝒙 [sec 𝒙] = sec 𝒙 tan 𝒙
          ○ New quotient:
               ■ limₓ→π⁄₂⁻ [(sec² 𝒙 / tan 𝒙) / (sec 𝒙 tan 𝒙)]
     ◉ Trigonometric simplification.
          ○ [(sec² 𝒙 / tan 𝒙) / (sec 𝒙 tan 𝒙)]
               ■ = sec 𝒙 / tan² 𝒙
               ■ = (1/cos 𝒙) / (sin² 𝒙 / cos² 𝒙)
               ■ = cos 𝒙 / sin² 𝒙
     ◉ Evaluate the exponent.
          ○ As 𝒙 → π⁄₂⁻:
               ■ cos 𝒙 → 0
               ■ sin² 𝒙 → 1
          ○ Therefore:
               ■ limₓ→π⁄₂⁻ cos 𝒙 / sin² 𝒙 = 0
     ◉ Final result.
          ○ limₓ→π⁄₂⁻ (tan 𝒙)^{cos 𝒙}
               ■ = 𝒆⁰
               ■ = 1
● [1:28:52]. 🧩 Case Study — limₓ→∞ (1 − 1/𝒙)^𝒙. 
     ◉ Identify the indeterminate form.
          ○ As 𝒙 → ∞:
               ■ 1 − 1/𝒙 → 1
               ■ 𝒙 → ∞
          ○ Therefore:
               ■ (1 − 1/𝒙)^𝒙 has the form 1^∞
     ◉ Rewrite using the exponential method.
          ○ Let
               ■ 𝒚 = (1 − 1/𝒙)^𝒙
          ○ Then
               ■ ln 𝒚 = 𝒙 ln(1 − 1/𝒙)
          ○ So
               ■ 𝒚 = 𝒆^{𝒙 ln(1 − 1/𝒙)}
     ◉ Convert the exponent into a quotient.
          ○ 𝒙 ln(1 − 1/𝒙) = ln(1 − 1/𝒙) / (1/𝒙)
          ○ Therefore study
               ■ limₓ→∞ ln(1 − 1/𝒙) / (1/𝒙)
     ◉ Verify the new indeterminate form.
          ○ As 𝒙 → ∞:
               ■ ln(1 − 1/𝒙) → ln(1) = 0
               ■ 1/𝒙 → 0
          ○ Therefore the exponent is now of type 0/0
     ◉ Apply L’Hôpital’s Rule.
          ○ Differentiate the numerator:
               ■ 𝒅/𝒅𝒙 [ln(1 − 1/𝒙)] = 1/(1 − 1/𝒙) · 1/𝒙²
          ○ Differentiate the denominator:
               ■ 𝒅/𝒅𝒙 [1/𝒙] = −1/𝒙²
     ◉ Simplify the quotient.
          ○ limₓ→∞ [ 1/(1 − 1/𝒙) · 1/𝒙² ] / [ −1/𝒙² ]
          ○ = limₓ→∞ −1 / (1 − 1/𝒙)
          ○ = −1
     ◉ Evaluate the original limit.
          ○ 𝒚 = 𝒆⁻¹
     ◉ Final result:
          ○ limₓ→∞ (1 − 1/𝒙)^𝒙 = 1/𝒆


     
Ｃｏｎｃｌｕｓｉｏｎ

● [1:39:52]. Summary of the goals and closing remarks on L’Hôpital’s Rule.