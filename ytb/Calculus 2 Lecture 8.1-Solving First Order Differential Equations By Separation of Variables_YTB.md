-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ８．１  -  Ｓｏｌｖｉｎｇ Ｆｉｒｓｔ Ｏｒｄｅｒ Ｄｉｆｆｅｒｅｎｔｉａｌ Eｑｕａｔｉｏｎｓ Ｂｙ Ｓｅｐａｒａｔｉｏｎ ｏｆ Ｖａｒｉａｂｌｅｓ**---------------------------------







Ｉｎｔｒｏｄｕｃｔｉｏｎ　Ｔｏ　Ｆｉｒｓｔ－Ｏｒｄｅｒ　Ｄｉｆｆｅｒｅｎｔｉａｌ　Ｅｑｕａｔｉｏｎｓ

● [📷image](./img/Calculus 2 Lecture 8.1/[0-00]Introduction to first-order differential equations.png)

● [0:00]. Introduction to first-order differential equations.
     ◉ Differential equations have broad applications, especially in engineering and applied sciences.
     ◉ Focus of the lecture:
          ○ separable differential equations
               ■ the most basic class of first-order differential equations

● [1:24]. Definition of a differential equation and the concept of order.
     ◉ A differential equation is an equation involving a derivative and an unknown function.
     ◉ Definition of order:
          ○ the order of a differential equation is the highest derivative that appears in it.
     ◉ First-order differential equations.
          ○ A first-order differential equation contains only a first derivative.

● [3:05]. Basic first-order equations of the form 𝒅𝒚/𝒅𝒙 = 𝒇(𝒙).
     ◉ [3:58]. Basic idea:
          ○ A first-order differential equation contains the first derivative of an unknown function.
          ○ Solving it means finding the function whose derivative satisfies the equation.
               ■ In simple cases such as
                    ▣ 𝒅𝒚/𝒅𝒙 = 𝒇(𝒙),
                    ▣ we can recover 𝒚 by integrating:
                         ▢ 𝒚 = ∫ 𝒇(𝒙) 𝒅𝒙
     ◉ [4:23]. Limitation of this basic method.
          ○ It works only when the right-hand side depends entirely on 𝒙:𝒇(𝒙).
          ○ It does not immediately solve equations of the form 𝒅𝒚/𝒅𝒙 = 𝒇(𝒙, 𝒚).

● [5:23]. First-order equations with mixed variables.
     ◉ General form:
          ○ 𝒅𝒚/𝒅𝒙 = 𝒇(𝒙, 𝒚)
     ◉ Meaning of a solution:
          ○ A solution is a function 𝒚 = 𝒚(𝒙), defined on some interval, such that
               ■ when we differentiate 𝒚(𝒙), its derivative matches the right-hand side of the differential equation.
          ○ In other words,
               ■ 𝒚 = 𝒚(𝒙) is a solution if 𝒅𝒚/𝒅𝒙 = 𝒇(𝒙, 𝒚(𝒙)).
     ◉ Important idea:
          ○ We treat 𝒚 as a function of 𝒙.
          ○ Even if 𝒚 is not given explicitly, it is still understood to depend on 𝒙, just as in implicit differentiation.




     

Ｖｅｒｉｆｙｉｎｇ　Ｓｏｌｕｔｉｏｎｓ

● Verifying whether a proposed function is a solution to a differential equation.
     ◉ Strategy:
          ○ Differentiate the proposed function.
          ○ Then compare the result with the right-hand side of the differential equation.
     ◉ Key idea:
          ○ A proposed function is a solution if, after differentiating it,
               ■ the derivative satisfies the differential equation identically.
          ○ In other words,
               ■ substituting the function into the equation must make both sides equal on the given interval.

● [8:13]. 🧩 Example 1 — Verify that 𝒚 = 𝒙 + 1 + 𝒄𝒆ˣ is a solution to 𝒚' = 𝒚 − 𝒙 on (−∞, ∞). [📷image](./img/Calculus 2 Lecture 8.1/[8-13]Example 1 — Verify that 𝒚 = 𝒙 + 1 + 𝒄𝒆ˣ is a solution to 𝒚' = 𝒚 − 𝒙 on (−∞, ∞).png)
     ◉ Step 1: Differentiate the proposed function.
          ○ 𝒚 = 𝒙 + 1 + 𝒄𝒆ˣ
          ○ Therefore,
               ■ 𝒅𝒚/𝒅𝒙 = 1 + 𝒄𝒆ˣ  = 𝒚' (1)
     ◉ Step 2: Compute the right-hand side of the differential equation.
          ○ The equation requires:
               ■ 𝒚' = 𝒚 − 𝒙
          ○ Since 𝒚 = 𝒙 + 1 + 𝒄𝒆ˣ,
               ■ 𝒚' = 𝒚 − 𝒙 = (𝒙 + 1 + 𝒄𝒆ˣ) − 𝒙 = 1 + 𝒄𝒆ˣ (2)
     ◉ Step 3: Compare both expressions.
          ○ From differentiation:
               ■ 𝒚' = 1 + 𝒄𝒆ˣ (1)
          ○ From substitution into 𝒚 − 𝒙:
               ■ 𝒚 − 𝒙 = 1 + 𝒄𝒆ˣ (2)
          ○ Therefore,
               ■ 𝒚' = 𝒚 − 𝒙
     ◉ Conclusion:
          ○ The proposed function is indeed a solution on (−∞, ∞).
     ◉ NOTE:
          ○ The constant 𝒄 remains arbitrary here.
          ○ That means this expression represents a family of solutions, not just one single curve.





          

Ｇｅｎｅｒａｌ　Ｓｏｌｕｔｉｏｎｓ　Ａｎｄ　Ｉｎｉｔｉａｌ　Ｖａｌｕｅ　Ｐｒｏｂｌｅｍｓ

● [14:41]. General solutions and arbitrary constants. [📷image](./img/Calculus 2 Lecture 8.1/[14-41]General solutions and arbitrary constants.png)
     ◉ [15:16]. A first-order differential equation typically has a solution with one arbitrary constant 𝒄.
     ◉ A solution containing one arbitrary constant is called a general solution.
     ◉ Geometric interpretation:
          ○ the general solution represents a family of integral curves. 

● [16:30]. Particular solutions and initial values. [📷image](./img/Calculus 2 Lecture 8.1/[16-30]Particular solutions and initial values.png)
     ◉ For a particular solution,
          ○ an initial value is required.
     ◉ Standard initial-value form:
          ○ 𝒚(𝒙₀) = 𝒚₀
     ◉ Geometric meaning:
          ○ the initial value selects one specific curve from the family of solutions.
          ○ Equivalently,
               ■ it forces the solution curve to pass through the fixed point (𝒙₀, 𝒚₀).
     ◉ NOTE 1:
          ○ the arbitrary constant is what distinguishes one curve from another within the same family.
          ○ once the initial value is imposed,
               ■ the constant is determined,
               ■ and the general solution becomes a particular solution.
     ◉ NOTE 2:
          ○ Two different initial points can determine the same constant only if both points lie on the same particular solution curve.

● [20:55]. 🧩 Example 2 — :Initial value problem with 𝒚(0) = 0. [📷image](./img/Calculus 2 Lecture 8.1/[20-55]Example 2 — Initial value problem with 𝒚(0) = 0.png)
     ◉ Use the previously verified general solution on🧩Example 1:
          ○ 𝒚 = 𝒙 + 1 + 𝒄𝒆ˣ
     ◉ Substitute the initial value.
          ○ 0 = 0 + 1 + 𝒄𝒆⁰
          ○ 0 = 1 + 𝒄
          ○ 𝒄 = −1
     ◉ Particular solution:
          ○ 𝒚 = 𝒙 + 1 − 𝒆ˣ
     ◉ Interpretation:
          ○ the initial condition reduces the general solution to one specific curve.





          

Ｓｅｐａｒａｂｌｅ　Ｄｉｆｆｅｒｅｎｔｉａｌ　Ｅｑｕａｔｉｏｎｓ

● [📷image](./img/Calculus 2 Lecture 8.1/[26-21]Definition of a separable differential equation.png)

● [26:21]. Definition of a separable differential equation.  
     ◉ A separable differential equation is a first-order differential equation that can be written as a product of:
          ○ a function of 𝒙
          ○ and a function of 𝒚
     ◉ Structural idea:
          ○ one factor depends on one variable,
          ○ and the other factor depends on the second variable.
     ◉ Main consequence:
          ○ the variables can be separated onto opposite sides of the equation.

● [28:34]. Standard forms of separable equations.
     ◉ Product form:
          ○ 𝒅𝒚/𝒅𝒙 = 𝓰(𝒙)𝒉(𝒚)
     ◉ Equivalent differential form:
          ○ 𝓜(𝒙) 𝒅𝒙 + 𝓝(𝒚) 𝒅𝒚 = 0
     ◉ These two forms are equivalent ways of expressing the same separable structure.

● [30:10]. Classification 🧩 examples: separable vs. non-separable. 
     ◉ A differential equation is separable when all 𝒙-terms can be placed on one side and all 𝒚-terms on the other.
     ◉ If 𝒙 and 𝒚 remain mixed in a way that cannot be separated,
          ○ the equation is non-separable.
     ◉ Separable examples:
          ○ (𝒙² + 1) 𝒅𝒙 + 1/𝒚 𝒅𝒚 = 0
               ■ already written with the 𝒙-part and the 𝒚-part separated
          ○ 𝒅𝒚/𝒅𝒕 = 𝒌𝒚
               ■ can be viewed as 𝓰(𝒕)𝒉(𝒚)
               ■ with 𝒌 = 𝓰(𝒕)
               ■ and 𝒚 = 𝒉(𝒚)
     ◉ Non-separable examples:
          ○ 𝒅𝒚/𝒅𝒙 = 𝒙𝒚² + 2𝒙²
               ■ the terms do not factor into one function of 𝒙 times one function of 𝒚
               ■ Compare with:
                    ▣ 𝒅𝒚/𝒅𝒙 = 𝒙²𝒚² + 2𝒙²
                    ▣ = 𝒙²(𝒚² + 2)
                    ▣ this one is separable, because it can be written as
                         ▢ 𝓰(𝒙)𝒉(𝒚)
                    ▣ with
                         ▢ 𝓰(𝒙) = 𝒙²
                         ▢ 𝒉(𝒚) = 𝒚² + 2  
          ○ (𝒙 + 𝒚) 𝒅𝒙 + 𝒙𝒚 𝒅𝒚 = 0
               ■ the variables remain mixed and cannot be cleanly separated




Ｇｅｎｅｒａｌ ｍｅｔｈｏｄ ｆｏｒ ｓｏｌｖｉｎｇ ｂｙ ｓｅｐａｒａｔｉｏｎ ｏｆ ｖａｒｉａｂｌｅｓ．


● [35:10]. General method for solving by separation of variables. [📷image](./img/Calculus 2 Lecture 8.1/[35-10]General method for solving by separation of variables.png)
     ◉ Start with a separable equation:
          ○ 𝒅𝒚/𝒅𝒙 = 𝓰(𝒙) · 𝒉(𝒚)
     ◉ Rearrangement:
          ○ Divide both sides by 𝒉(𝒚):
               ■ 1/𝒉(𝒚) ⋅ 𝒅𝒚/𝒅𝒙 = 𝓰(𝒙)
          ○ Then separate the variables:
               ■ 1/𝒉(𝒚) 𝒅𝒚 = 𝓰(𝒙) 𝒅𝒙
     ◉ Integrate both sides.
          ○ ∫ 1/𝒉(𝒚) 𝒅𝒚 = ∫ 𝓰(𝒙) 𝒅𝒙
     ◉ General solution form:
          ○ 𝓗(𝒚) = 𝓖(𝒙) + 𝒄
     ◉ Interpretation of the notation:
          ○ 𝓗(𝒚) is the antiderivative of 1/𝒉(𝒚) with respect to 𝒚
          ○ 𝓖(𝒙) is the antiderivative of 𝓰(𝒙) with respect to 𝒙
     ◉ Heuristic idea:
          ○ The step
               ■ 1/𝒉(𝒚) ⋅ 𝒅𝒚/𝒅𝒙 = 𝓰(𝒙)
          ○ is treated as if the 𝒅𝒙 moves to the other side:
               ■ 1/𝒉(𝒚) 𝒅𝒚 = 𝓰(𝒙) 𝒅𝒙
          ○ This is the standard separation-of-variables manipulation.
     ◉ Main idea:
          ○ first separate all 𝒚-terms from all 𝒙-terms
          ○ then integrate each side with respect to its own variable

● [40:21]. 🧩 Example 1 — Solve 𝒅𝒚/𝒅𝒙 = 𝒚/𝒙 [📷image-1](./img/Calculus 2 Lecture 8.1/[40-21]Example 1 — Solve 𝒅𝒚∕𝒅𝒙 = 𝒚∕𝒙_1.png) [📷image-2](./img/Calculus 2 Lecture 8.1/[40-21]Example 1 — Solve 𝒅𝒚∕𝒅𝒙 = 𝒚∕𝒙_2.png)
     ◉ Recognize it as separable.
          ○ Rewrite:
               ■ 1/𝒚 ⋅ 𝒅𝒚/𝒅𝒙 = 1/𝒙
     ◉ Separate and integrate.
          ○ ∫ 1/𝒚 ⋅ 𝒅𝒚 = ∫ 1/𝒙 ⋅ 𝒅𝒙
     ◉ Logarithmic antiderivatives:
          ○ ln|𝒚| = ln|𝒙| + 𝒄₁
     ◉ [44:27]. Constant manipulation.
          ○ Rewrite the constant in logarithmic form so it can be combined with the other logarithm:
               ■ 𝒄₁ = ln|e^{𝒄₁}|
               ■ Let 𝒄₂ = e^{𝒄₁}
               ■ Then 𝒄₁ = ln|𝒄₂|
     ◉ Combine logarithms.
          ○ ln|𝒚| = ln|𝒙| + ln|𝒄₂|
          ○ = ln|𝒙 ⋅ 𝒄₂|
     ◉ Exponentiate both sides.
          ○ e^{ln|𝒚|} = e^{ln|𝒙 ⋅ 𝒄₂|}
          ○ so |𝒚| = |𝒙 ⋅ 𝒄₂|
     ◉ Remove the absolute values.
          ○ 𝒚 = ±𝒙 ⋅ 𝒄₂
          ○ = ±𝒄₂ 𝒙
     ◉ Absorb the sign into the constant.
          ○ Let 𝒄 = ±𝒄₂
          ○ Therefore:
               ■ 𝒚 = 𝒄𝒙
     ◉ [50:40]. Final general solution.
          ○ 𝒚 = 𝒄𝒙
     ◉ NOTE:
          ○ In logarithmic separable equations, the constant is often rewritten and renamed so the logarithms can be combined cleanly.
          ○ The ± sign that appears after removing absolute values is absorbed into the arbitrary constant.

● [56:02]. 🧩 Example 2 — Solve 𝒅𝒚/𝒅𝒙 = 𝒙𝒚/(𝒙² + 1). [📷image-1](./img/Calculus 2 Lecture 8.1/[56-02]Example 2 — Solve 𝒅𝒚∕𝒅𝒙 = 𝒙𝒚 ∕ (𝒙² + 1)_1.png) [📷image-2](./img/Calculus 2 Lecture 8.1/[56-02]Example 2 — Solve 𝒅𝒚∕𝒅𝒙 = 𝒙𝒚 ∕ (𝒙² + 1)_2.png)
     ◉ Recognize it as separable.
          ○ Product form:
               ■ 𝒅𝒚/𝒅𝒙 = 𝓰(𝒙) ⋅ 𝒉(𝒚)
               ■ 𝒅𝒚/𝒅𝒙 = (𝒙/(𝒙² + 1)) ⋅ 𝒚
     ◉ Separate the variables.
          ○ 1/𝒚 ⋅ 𝒅𝒚/𝒅𝒙 = 𝒙/(𝒙² + 1)
          ○ hence
               ■ 1/𝒚 𝒅𝒚 = 𝒙/(𝒙² + 1) 𝒅𝒙
     ◉ Integrate both sides.
          ○ ∫ 1/𝒚 𝒅𝒚 = ∫ 𝒙/(𝒙² + 1) 𝒅𝒙
          ○ ln|𝒚| = ∫ 𝒙/(𝒙² + 1) 𝒅𝒙 + 𝒄₁
     ◉ Use the substitution on the right-hand side.
          ○ Let 𝒖 = 𝒙² + 1
          ○ then 𝒅𝒖 = 2𝒙 𝒅𝒙
          ○ so 𝒅𝒖/2 = 𝒙 𝒅𝒙
          ○ Therefore:
               ■ ∫ 𝒙/(𝒙² + 1) 𝒅𝒙 = 1/2 ∫ 1/𝒖 𝒅𝒖
               ■ = 1/2 ln|𝒖|
               ■ = 1/2 ln|𝒙² + 1|
     ◉ So the integrated equation becomes:
          ○ ln|𝒚| = 1/2 ln|𝒙² + 1| + 𝒄₁
     ◉ [1:02:15]. Rewrite the constant in logarithmic form.
          ○ 𝒄₁ = ln|e^{𝒄₁}|
          ○ Let 𝒄₂ = e^{𝒄₁}
          ○ Then:
               ■ 𝒄₁ = ln|𝒄₂|
     ◉ Substitute this back into the equation.
          ○ ln|𝒚| = 1/2 ln|𝒙² + 1| + ln|𝒄₂|
     ◉ Rewrite the factor 1/2 as an exponent.
          ○ 1/2 ln|𝒙² + 1| = ln|(𝒙² + 1)^{1/2}|
          ○ = ln|√(𝒙² + 1)|
     ◉ Combine the logarithms.
          ○ ln|𝒚| = ln|√(𝒙² + 1)| + ln|𝒄₂|
          ○ = ln|√(𝒙² + 1) ⋅ 𝒄₂|
     ◉ Exponentiate both sides.
          ○ e^{ln|𝒚|} = e^{ln|√(𝒙² + 1) ⋅ 𝒄₂|}
          ○ so
               ■ |𝒚| = |√(𝒙² + 1) ⋅ 𝒄₂|
     ◉ Remove the absolute values.
          ○ 𝒚 = ±√(𝒙² + 1) ⋅ 𝒄₂
          ○ = ±𝒄₂ √(𝒙² + 1)
     ◉ Absorb the sign into the constant.
          ○ Let 𝒄 = ±𝒄₂
     ◉  Final general solution.
          ○ 𝒚 = 𝒄√(𝒙² + 1)
     ◉ NOTE:
          ○ Since 𝒙² + 1 > 0 for every real 𝒙,
               ■ √(𝒙² + 1) is always defined and positive.
          ○ As in the previous example,
               ■ the ± sign is absorbed into the arbitrary constant.





          

Ａｄｖａｎｃｅｄ　Ｉｎｉｔｉａｌ　Ｖａｌｕｅ　Ｐｒｏｂｌｅｍ

● [1:09:33]. 🧩 Example — Solve the IVP: (𝒚² − 1) 𝒅𝒚/𝒅𝒙 = −𝒚𝒆ˣ with 𝒚(0) = 1. [📷image](./img/Calculus 2 Lecture 8.1/[1-09-33]Example — Solve the IVP (𝒚² − 1) 𝒅𝒚∕𝒅𝒙 = −𝒚𝒆ˣ with 𝒚(0) = 1.png)
     ◉ Separate the variables.
          ○ (𝒚² − 1) 𝒅𝒚 = −𝒚𝒆ˣ 𝒅𝒙
          ○ (𝒚² − 1)/𝒚 𝒅𝒚 = −𝒆ˣ 𝒅𝒙
     ◉ Simplify the 𝒚-integrand.
          ○ (𝒚² − 1)/𝒚 = 𝒚 − 1/𝒚
     ◉ Integrate both sides.
          ○ ∫ (𝒚 − 1/𝒚) 𝒅𝒚 = ∫ −𝒆ˣ 𝒅𝒙
          ○ 1/2 𝒚² − ln|𝒚| = −𝒆ˣ + 𝒄₁
     ◉ Multiply through by 2.
          ○ 𝒚² − 2ln|𝒚| = −2𝒆ˣ + 2𝒄₁
     ◉ Rewrite the logarithmic term.
          ○ Since 2ln|𝒚| = ln(𝒚²),
               ■ 𝒚² − ln(𝒚²) = −2𝒆ˣ + 𝒄₂
               ■ where 𝒄₂ = 2𝒄₁
     ◉ Apply the initial value.
          ○ Substitute 𝒚(0) = 1:
               ■ 1² − ln(1²) = −2𝒆⁰ + 𝒄₂
               ■ 1 − 0 = −2 + 𝒄₂
               ■ 𝒄₂ = 3
     ◉ Particular implicit solution.
          ○ 𝒚² − ln(𝒚²) = −2𝒆ˣ + 3
     ◉ NOTE:
          ○ The solution is left in implicit form.
          ○ Solving explicitly for 𝒚 is not practical here.





          

Ｎａｔｕｒａｌ　Ｇｒｏｗｔｈ　＆　Ｄｅｃａｙ

● [1:18:47]. Modeling natural growth and decay. [📷image](./img/Calculus 2 Lecture 8.1/[1-18-47]Modeling natural growth and decay.png)
     ◉ Basic idea:
          ○ Growth or decay occurs at a rate proportional to the size of the population.
     ◉ Important clarification:
          ○ 𝒚 = 𝒌𝒕 does not imply 𝒅𝒚/𝒅𝒕 = 𝒌𝒚.
          ○ In fact, if 𝒚 = 𝒌𝒕, then
               ■ 𝒅𝒚/𝒅𝒕 = 𝒌
          ○ For natural growth and decay, the correct assumption is:
               ■ the rate of change is proportional to the current population
          ○ So:
               ■ 𝒅𝒚/𝒅𝒕 ∝ 𝒚
               ■ hence 𝒅𝒚/𝒅𝒕 = 𝒌𝒚
          ○ In words:
               ■ the rate of change of the population is proportional to the population itself.
     ◉ Differential equation model:
          ○ 𝒅𝒚/𝒅𝒕 = 𝒌𝒚
          ○ where 𝒚 = 𝒚(𝒕)
     ◉ Interpretation of the derivative:
          ○ 𝒅𝒚/𝒅𝒕 measures how fast the population changes with respect to time.
          ○ If 𝒅𝒚/𝒅𝒕 > 0,
               ■ the population is increasing.
          ○ If 𝒅𝒚/𝒅𝒕 < 0,
               ■ the population is decreasing.
     ◉ Interpretation of 𝒌:
          ○ if 𝒌 > 0,
               ■ the population grows
          ○ if 𝒌 < 0,
               ■ the population decays
     ◉ Initial value:
          ○ 𝒚(0) = 𝒚₀
          ○ 𝒚₀ represents the starting population.

● [1:23:26]. Derivation of the exponential growth/decay law. [📷image-1](./img/Calculus 2 Lecture 8.1/[1-23-26]Derivation of the exponential growth ∕ decay law_1.png) [📷image-2](./img/Calculus 2 Lecture 8.1/[1-23-26]Derivation of the exponential growth ∕ decay law_2.png)
     ◉ Start from the model:
          ○ 𝒅𝒚/𝒅𝒕 = 𝒌𝒚
     ◉ Separate variables:
          ○ 1/𝒚 ⋅ 𝒅𝒚/𝒅𝒕 = 𝒌
          ○ hence
               ■ 1/𝒚 𝒅𝒚 = 𝒌 𝒅𝒕
     ◉ Integrate both sides:
          ○ ∫ 1/𝒚 𝒅𝒚 = ∫ 𝒌 𝒅𝒕
          ○ ln|𝒚| = 𝒌𝒕 + 𝒄₁
     ◉ Exponentiate:
          ○ e^{ln|𝒚|} = e^{𝒌𝒕 + 𝒄₁}
          ○ |𝒚| = e^{𝒌𝒕} ⋅ e^{𝒄₁}
     ◉ Rewrite the constant:
          ○ Let 𝒄₂ = e^{𝒄₁}
          ○ then
               ■ |𝒚| = 𝒄₂ e^{𝒌𝒕}
     ◉ Remove the absolute value:
          ○ 𝒚 = ±𝒄₂ e^{𝒌𝒕}
     ◉ Absorb the sign into the constant:
          ○ Let 𝒄 = ±𝒄₂
          ○ therefore
               ■ 𝒚 = 𝒄e^{𝒌𝒕}
     ◉ Use the initial value 𝒚(0) = 𝒚₀:
          ○ 𝒚₀ = 𝒄e⁰
          ○ 𝒚₀ = 𝒄
     ◉ Final model:
          ○ 𝒚 = 𝒚₀e^{𝒌𝒕}
     ◉ Interpretation:
          ○ 𝒚₀ is the initial population.
          ○ The constant 𝒌 determines whether the model describes growth or decay.




          

Ｍｏｄｅｌ　Ａｓｓｕｍｐｔｉｏｎｓ　Ｆｏｒ　Ｎａｔｕｒａｌ　Ｇｒｏｗｔｈ　＆　Ｄｅｃａｙ

● [1:44:15]. Modeling assumption for the exponential growth/decay model.
     ◉ Core assumption:
          ○ The equation 𝒅𝒚/𝒅𝒕 = 𝒌𝒚 can only be used when the problem states that the growth or decay rate is **proportional** to the current population.
          ○ This proportionality cannot be assumed unless it is explicitly given in the statement.
     ◉ Important remark:
          ○ Not every growth or decay process is proportional to the population size.
          ○ Some external effects may act non-proportionally, so the model 𝒅𝒚/𝒅𝒕 = 𝒌𝒚 would no longer be appropriate.
     ◉ Example of a non-proportional effect:
          ○ If an external agent acts independently of the current population size,
               ■ the population may decrease in a way that is not proportional to 𝒚.
          ○ In such a case,
               ■ the exponential model should not be assumed.





Λｐｐｌｉｃａｔｉｏｎｓ
               

1 - Ｂａｃｔｅｒｉａｌ　Ｇｒｏｗｔｈ

● [1:46:45]. 🧩 Application — Bacterial growth. [📷image](./img/Calculus 2 Lecture 8.1/[1-46-45]Application — Bacterial growth.png)
     ◉ Growth of bacteria is proportional to its population. Initially, 600 bacteria are present. After 3 hours, 10,000 bacteria are present.
     ◉ Modeling assumption:
          ○ the growth of the bacteria is proportional to its population.
     ◉ Initial data:
          ○ initially there are 600 bacteria
          ○ after 3 hours there are 10,000 bacteria
     ◉ Goal:
          ○ find the number of bacteria after 𝒕 hours.
     ◉ Start from the natural growth model:
          ○ 𝒚 = 𝒚₀e^{𝒌𝒕}
     ◉ Substitute the initial population.
          ○ 𝒚 = 600e^{𝒌𝒕}
     ◉ Use the second data point:
          ○ 𝒚(3) = 10{,}000
          ○ 10{,}000 = 600e^{3𝒌}
          ○ 50/3 = e^{3𝒌}
     ◉ Solve more efficiently for e^𝒌.
          ○ (50/3)^{1/3} = (e^{3𝒌})^{1/3}
          ○ e^𝒌 = (50/3)^{1/3}
     ◉ Rewrite the model.
          ○ 𝒚 = 600e^{𝒌𝒕}
          ○ = 600(e^𝒌)^𝒕
          ○ = 600[(50/3)^{1/3}]^𝒕
          ○ = 600(50/3)^{𝒕/3}
     ◉ Final model:
          ○ 𝒚 = 600(50/3)^{𝒕/3}

● [1:55:48]. Population after 5 hours.
     ◉ Substitute 𝒕 = 5 into the model.
          ○ 𝒚 = 600(50/3)^{5/3}
     ◉ Numerical value:
          ○ 𝒚 ≈ 65248 bacteria

● [1:58:13]. Time required to reach 24,000 bacteria.
     ◉ Set
          ○ 24000 = 600(50/3)^{𝒕/3}
     ◉ Simplify:
          ○ 40 = (50/3)^{𝒕/3}
     ◉ Take logarithms:
          ○ ln(40) = (𝒕/3) ln(50/3)
     ◉ Solve for 𝒕:
          ○ 𝒕 = 3ln(40) / ln(50/3)
     ◉ Approximate time:
          ○ 𝒕 ≈ 3.93 hours






2 - Ｈａｌｆ－Ｌｉｆｅ　＆　Ｒａｄｉｏａｃｔｉｖｅ　Ｄｅｃａｙ

● [2:02:35]. 🧩 Application — Half-life and radioactive decay model. [📷image-1](./img/Calculus 2 Lecture 8.1/[2-02-35]Application — Half-life and radioactive decay model_1.png) [📷image-2](./img/Calculus 2 Lecture 8.1/[2-02-35]Application — Half-life and radioactive decay model_2.png)
     ◉ Suppose the half-life of compound A is 1602 years. We have 100 mg to start. Find the amount after 𝒕 years.
     ◉ Given:
          ○ half-life = 1602 years
          ○ initial amount = 100 mg
     ◉ Goal:
          ○ find the amount after 𝒕 years.
     ◉ Start from the natural decay model:
          ○ 𝒚 = 𝒚₀e^{𝒌𝒕}
     ◉ Substitute the initial amount.
          ○ 𝒚 = 100e^{𝒌𝒕}
     ◉ Half-life condition:
          ○ after 1602 years, half of the initial amount remains
               ■ 𝒚(1602) = 50
          ○ so
               ■ 50 = 100e^{1602𝒌}
               ■ 1/2 = e^{1602𝒌}
     ◉ Solve for e^𝒌.
          ○ (1/2)^{1/1602} = (e^{1602𝒌})^{1/1602}
          ○ e^𝒌 = (1/2)^{1/1602}
     ◉ Rewrite the model.
          ○ 𝒚 = 100e^{𝒌𝒕}
          ○ = 100(e^𝒌)^𝒕
          ○ = 100[(1/2)^{1/1602}]^𝒕
          ○ = 100(1/2)^{𝒕/1602}
     ◉ Final decay model:
          ○ 𝒚 = 100(1/2)^{𝒕/1602}

● Amount remaining after 1000 years.
     ◉ Substitute 𝒕 = 1000 into the model.
          ○ 𝒚 = 100(1/2)^{1000/1602}
     ◉ Numerical value:
          ○ 𝒚 ≈ 64.88 mg

● Time required for the amount to decay to 40 mg.
     ◉ Set
          ○ 40 = 100(1/2)^{𝒕/1602}
     ◉ Simplify:
          ○ 2/5 = (1/2)^{𝒕/1602}
     ◉ Take logarithms:
          ○ ln(2/5) = (𝒕/1602) ln(1/2)
     ◉ Solve for 𝒕:
          ○ 𝒕 = 1602 ln(2/5) / ln(1/2)
     ◉ Approximate time:
          ○ 𝒕 ≈ 2118 years






3 - Ｎｅｗｔｏｎ’ｓ　Ｌａｗ　Ｏｆ　Ｃｏｏｌｉｎｇ


● [2:17:55]. 🧩 Application — Newton’s Law of Cooling. [📷image](./img/Calculus 2 Lecture 8.1/[2-17-55]Application — Newton’s Law of Cooling.png)
     ◉ Basic principle:
          ○ A body cools at a rate proportional to the difference between:
               ■ the temperature of the body
               ■ and the ambient temperature
     ◉ Differential equation model:
          ○ 𝒅𝒚/𝒅𝒕 = 𝒌(𝒚 − 𝒚_𝒂)
     ◉ Meaning of the variables:
          ○ 𝒚 = temperature of the body
          ○ 𝒕 = time
          ○ 𝒚_𝒂 = ambient temperature
     ◉ Important idea:
          ○ The cooling rate depends not just on 𝒚 itself,
               ■ but on how far 𝒚 is from the ambient temperature.
          ○ As 𝒚 gets closer to 𝒚_𝒂,
               ■ the rate of cooling becomes smaller.



               

3.1 - Ｔｕｒｋｅｙ　Ｃｏｏｌｉｎｇ　Ｃａｓｅ　Ｓｔｕｄｙ

● [📷image-1](./img/Calculus 2 Lecture 8.1/[2-22-22]Case study — Cooling of a turkey_1.png) [📷image-2](./img/Calculus 2 Lecture 8.1/[2-22-22]Case study — Cooling of a turkey_2.png) [📷image-3](./img/Calculus 2 Lecture 8.1/[2-22-22]Case study — Cooling of a turkey_3.png) [📷image-4](./img/Calculus 2 Lecture 8.1/[2-22-22]Case study — Cooling of a turkey_4.png) 

● [2:22:22]. 🧩 Case study — Cooling of a turkey.
     ◉ A turkey is taken out of an oven at 225°. After 20 min, the temperature was 185°. The temperature of my house was 70°.
     ◉ Conditions:
          ○ ambient temperature 𝒚_𝒂 = 70
          ○ 𝒚(0) = 225
          ○ 𝒚(20) = 185
     ◉ Interpretation of the variables:
          ○ 𝒚(𝒕) = temperature of the turkey
          ○ 𝒕 = time in minutes
     ◉ Substitute the ambient temperature into the model:
          ○ 𝒅𝒚/𝒅𝒕 = 𝒌(𝒚 − 70)

●  Separate the variables.
     ◉ Rearrangement:
          ○ 1/(𝒚 − 70) ⋅ 𝒅𝒚/𝒅𝒕 = 𝒌
          ○ hence
               ■ 1/(𝒚 − 70) 𝒅𝒚 = 𝒌 𝒅𝒕
     ◉ Integrate both sides:
          ○ ∫ 1/(𝒚 − 70) 𝒅𝒚 = ∫ 𝒌 𝒅𝒕
          ○ ln|𝒚 − 70| = 𝒌𝒕 + 𝒄₁

● Solve the general form.
     ◉ Exponentiate:
          ○ e^{ln|𝒚 − 70|} = e^{𝒌𝒕 + 𝒄₁}
          ○ |𝒚 − 70| = e^{𝒌𝒕} ⋅ e^{𝒄₁}
     ◉ Rewrite the constant:
          ○ Let 𝒄₂ = e^{𝒄₁}
          ○ then
               ■ |𝒚 − 70| = 𝒄₂e^{𝒌𝒕}
     ◉ Remove the absolute value:
          ○ 𝒚 − 70 = ±𝒄₂e^{𝒌𝒕}
     ◉ Absorb the sign into the constant:
          ○ Let 𝒄 = ±𝒄₂
          ○ therefore
               ■ 𝒚 − 70 = 𝒄e^{𝒌𝒕}

● [2:36:30]. Apply the first condition 𝒚(0) = 225.
     ◉ Substitute into the general solution:
          ○ 225 − 70 = 𝒄e^{𝒌⋅0}
          ○ 155 = 𝒄
     ◉ So:
          ○ 𝒚 − 70 = 155e^{𝒌𝒕}

● Apply the second condition 𝒚(20) = 185.
     ◉ Substitute:
          ○ 185 − 70 = 155e^{20𝒌}
          ○ 115 = 155e^{20𝒌}
          ○ 23/31 = e^{20𝒌}
     ◉ Solve more efficiently for e^𝒌:
          ○ (23/31)^{1/20} = (e^{20𝒌})^{1/20}
          ○ e^𝒌 = (23/31)^{1/20}

● Final temperature model.
     ◉ Rewrite:
          ○ 𝒚 − 70 = 155e^{𝒌𝒕}
          ○ = 155(e^𝒌)^𝒕
          ○ = 155[(23/31)^{1/20}]^𝒕
          ○ = 155(23/31)^{𝒕/20}
     ◉ Therefore:
          ○ 𝒚 = 70 + 155(23/31)^{𝒕/20}

● [2:44:45]. Temperature after 30 minutes.
     ◉ Substitute 𝒕 = 30 into the model:
          ○ 𝒚 = 70 + 155(23/31)^{30/20}
     ◉ Approximate value:
          ○ 𝒚 ≈ 169°

● [2:46:05]. Time needed for the turkey to cool to 125°F.
     ◉ Set:
          ○ 125 = 70 + 155(23/31)^{𝒕/20}
     ◉ Simplify:
          ○ 55 = 155(23/31)^{𝒕/20}
          ○ 11/31 = (23/31)^{𝒕/20}
     ◉ Take logarithms:
          ○ ln(11/31) = (𝒕/20) ln(23/31)
     ◉ Solve for 𝒕:
          ○ 𝒕 = 20 ln(11/31) / ln(23/31)
     ◉ Approximate time:
          ○ 𝒕 ≈ 69.4 minutes

● NOTE:
     ◉ The model predicts that the turkey cools quickly at first,
          ○ because the difference between its temperature and the room temperature is large.
     ◉ Later the cooling slows down,
          ○ because the turkey gets closer to the ambient temperature 70.


     

Ｃｏｒｅ　Ｉｄｅａｓ

● Main conceptual summary.
     ◉ A first-order differential equation involves a first derivative.
     ◉ A general solution contains one arbitrary constant.
     ◉ An initial value selects one particular solution.
     ◉ Separable equations are solved by:
          ○ separating variables
          ○ integrating both sides
          ○ and then simplifying algebraically
     ◉ Many natural models arise from separable equations:
          ○ exponential growth
          ○ exponential decay
          ○ half-life
          ○ Newton’s law of cooling




Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Introduction to Differential Equations
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/4-introduction)