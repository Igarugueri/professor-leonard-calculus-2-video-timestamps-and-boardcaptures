-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ６．４ － Ｄｅｒｉｖａｔｉｖｅｓ ａｎｄ Ｉｎｔｅｇｒａｌｓ ｏｆ Ｇｅｎｅｒａｌ Ｅｘｐｏｎｅｎｔｉａｌ Ｆｕｎｃｔｉｏｎｓ**------------------------------—




Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:05]. Fundamental properties of exponential expressions. [📷image](./img/Calculus 2 Lecture 6.4/[0-05]Fundamental properties of exponential expressions.png)
     ◉ product of powers with the same base:
          ○ 𝒂^𝒙 · 𝒂^𝒚 = 𝒂^{𝒙+𝒚}
     ◉ Power of a power:
          ○ (𝒂^𝒙)^𝒚 = 𝒂^{𝒙𝒚}
     ◉ Power of a product:
          ○ (𝒂𝒃)^𝒙 = 𝒂^𝒙 · 𝒃^𝒙
     ◉ Quotient of powers with the same base:
          ○ 𝒂^𝒙 / 𝒂^𝒚 = 𝒂^{𝒙−𝒚}
     ◉ Power of a quotient:
          ○ (𝒂/𝒃)^𝒙 = 𝒂^𝒙 / 𝒃^𝒙





Ｄｅｒｉｖａｔｉｖｅ ｏｆ ａｎ ｅｘｐｏｎｅｎｔｉａｌ ｆｕｎｃｔｉｏｎ

● [1:40]. Rewriting a general exponential function using the natural exponential form. [📷image](./img/Calculus 2 Lecture 6.4/[1-40]Rewriting a general exponential function using the natural exponential form.png)
     ◉ Expressing any positive base in terms of 𝓮.
          ○ Use the identity:
               ■ 𝒙 = 𝓮^{ln 𝒙}
          ○ Apply it to a constant base 𝒂:
               ■ 𝒂 = 𝓮^{ln 𝒂}
     ◉ Rewriting the exponential function 𝒂^𝒙.
          ○ Substitute 𝒂 = 𝓮^{ln 𝒂}:
               ■ 𝒂^𝒙 = (𝓮^{ln 𝒂})^𝒙
          ○ Use properties of exponents:
               ■ 𝒂^𝒙 = 𝓮^{𝒙 ln 𝒂}
     ◉ Representation of a general exponential function.
          ○ Define the function:
               ■ 𝒇(𝒙) = 𝒂^𝒙
          ○ Equivalent natural exponential form:
               ■ 𝒇(𝒙) = 𝓮^{𝒙 ln 𝒂}
     ◉ 🧩 Example – with base  2^π.
          ○ 𝒇(𝒙) = 𝒂^𝒙 = 𝓮^{𝒙 ln 𝒂}
               ■ 2^π = 𝓮^{π ln 2}

● [6:00]. Derivative of a general exponential function. [📷image](./img/Calculus 2 Lecture 6.4/[6-00]Derivative of a general exponential function.png)
     ◉ Rewriting the function using the natural exponential.
          ○ Start from the general exponential:
               ■ 𝒇(𝒙) = 𝒂^𝒙
          ○ Use the identity 𝒂 = 𝓮^{ln 𝒂}:
               ■ 𝒂^𝒙 = 𝓮^{𝒙 ln 𝒂}
     ◉ Apply differentiation rules.
          ○ Differentiate using the chain rule:
               ■ 𝒅/𝒅𝒙 [𝒂^𝒙] = 𝒅/𝒅𝒙 [𝓮^{𝒙 ln 𝒂}]
               ■ = 𝓮^{𝒙 ln 𝒂} · 𝒅/𝒅𝒙 [𝒙 ln 𝒂]
          ○ Differentiate the exponent:
               ■ 𝒅/𝒅𝒙 [𝒙 ln 𝒂] = ln 𝒂
     ◉ Final result.
          ○ Substitute back:
               ■ 𝒅/𝒅𝒙 [𝒂^𝒙] = (ln 𝒂) 𝓮^{𝒙 ln 𝒂}
               ■ 𝒅/𝒅𝒙 [𝒂^𝒙] = (ln 𝒂) 𝒂^𝒙

● [6:00]. 🧩 Example – Differentiate an exponential function with base different from 𝓮: 𝒚=3^𝒙 [📷image](./img/Calculus 2 Lecture 6.4/[6-00]Example Differentiate an exponential function with base different from 𝓮 3^𝒙.png)
     ◉ Apply the general derivative formula.
          ○ 𝒅/𝒅𝒙 [𝒂^𝒙] = (ln 𝒂) 𝒂^𝒙
     ◉ Example with base 3.
          ○ 𝒅/𝒅𝒙 [3^𝒙] = (ln 3) · 3^𝒙

● [12:52]. 🧩 Example – Differentiate an exponential function with base different from 𝓮: 𝒚=5^{∛𝒙} [📷image](./img/Calculus 2 Lecture 6.4/[12-52]Example Differentiate an exponential function with base different from 𝓮 5^{∛𝒙}.png)
     ◉ Apply the derivative rule for 𝒂^{𝒖}:
          ○ 𝒅/𝒅𝒙 [𝒂^{𝒖}] = (ln 𝒂) 𝒂^{𝒖} · 𝒅𝒖/𝒅𝒙
     ◉ Identify the inner function:
          ○ 𝒖 = ∛𝒙 = 𝒙^{1/3}
     ◉ Differentiate the inner function:
          ○ 𝒅/𝒅𝒙 [𝒙^{1/3}] = (1/3) 𝒙^{-2/3}
     ◉ Combine all factors:
          ○ 𝒅/𝒅𝒙 [5^{∛𝒙}] = (ln 5) · 5^{∛𝒙} · (1/3) 𝒙^{-2/3}
     ◉ Final simplified form:
          ○ 𝒅/𝒅𝒙 [5^{∛𝒙}] = (ln 5) · 5^{∛𝒙} / (3∛𝒙²)

● [16:45]. 🧩 Example – Differentiate an exponential function with base different from 𝓮: 𝒚 = 7^{tan(2𝒙)} [📷image](./img/Calculus 2 Lecture 6.4/[16-45]Example Differentiate an exponential function with base different from 𝓮 𝒚 = 7^{tan(2𝒙)}.png)
     ◉ Given function:
          ○ 𝒚 = 7^{tan(2𝒙)}
     ◉ Apply the derivative rule for 𝒂^{𝒖}:
          ○ 𝒅/𝒅𝒙 [𝒂^{𝒖}] = (ln 𝒂) 𝒂^{𝒖} · 𝒅𝒖/𝒅𝒙
     ◉ Identify the inner function:
          ○ 𝒖 = tan(2𝒙)
     ◉ Differentiate the inner function (chain rule):
          ○ 𝒅/𝒅𝒙 [tan(2𝒙)] = sec²(2𝒙) · 𝒅/𝒅𝒙[2𝒙]
          ○ 𝒅/𝒅𝒙 [tan(2𝒙)] = 2 sec²(2𝒙)
     ◉ Combine all factors:
          ○ 𝒅/𝒅𝒙 [7^{tan(2𝒙)}] = (ln 7) · 7^{tan(2𝒙)} · 2 sec²(2𝒙)
     ◉ Final result:
          ○ 𝒅/𝒅𝒙 [7^{tan(2𝒙)}] = 2 (ln 7) · 7^{tan(2𝒙)} · sec²(2𝒙)

● [20:35]. 🧩 Example – Differentiate a product involving an exponential function:  𝒚 = 𝒙^𝓮 · 𝓮^𝒙 [📷image](./img/Calculus 2 Lecture 6.4/[20-35]Example Differentiate a product involving an exponential function 𝒚 = 𝒙^𝓮 · 𝓮^𝒙.png)
     ◉ Apply the product rule:
          ○ 𝒅/𝒅𝒙[𝒖·𝒗] = 𝒖'·𝒗 + 𝒖·𝒗'
     ◉ Identify each factor:
          ○ 𝒖 = 𝒙^𝓮
          ○ 𝒗 = 𝓮^𝒙
     ◉ Differentiate each factor:
          ○ 𝒅/𝒅𝒙[𝒙^𝓮] = 𝓮·𝒙^{𝓮−1}
          ○ 𝒅/𝒅𝒙[𝓮^𝒙] = 𝓮^𝒙
     ◉ Substitute into the product rule:
          ○ 𝒅𝒚/𝒅𝒙 = (𝓮·𝒙^{𝓮−1})·𝓮^𝒙 + 𝒙^𝓮·𝓮^𝒙
     ◉ Factor the common exponential term:
          ○ 𝒅𝒚/𝒅𝒙 = 𝓮^𝒙 (𝓮·𝒙^{𝓮−1} + 𝒙^𝓮)

● [24:13]. 🧩 Example – Differentiate a quotient involving exponential functions with different bases: 𝒚 = 2^𝒙 / √(3^𝒙 + 1) [📷image](./img/Calculus 2 Lecture 6.4/[24-13]Example Differentiate a quotient involving exponential functions with different bases 𝒚 = 2^𝒙 ∕ √(3^𝒙 + 1).png)
     ◉ Rewrite the denominator using exponents:
          ○ √(3^𝒙 + 1) = (3^𝒙 + 1)^{1/2}
     ◉ Rewrite the function in exponent form:
          ○ 𝒚 = 2^𝒙 · (3^𝒙 + 1)^{-1/2}
     ◉ Apply the product rule:
          ○ 𝒅/𝒅𝒙[𝒖·𝒗] = 𝒖'·𝒗 + 𝒖·𝒗'
     ◉ Identify each factor:
          ○ 𝒖 = 2^𝒙
          ○ 𝒗 = (3^𝒙 + 1)^{-1/2}
     ◉ Differentiate each factor:
          ○ 𝒅/𝒅𝒙[2^𝒙] = (ln 2)·2^𝒙
          ○ 𝒅/𝒅𝒙[(3^𝒙 + 1)^{-1/2}]
               ■ = −1/2 (3^𝒙 + 1)^{-3/2} · 𝒅/𝒅𝒙[3^𝒙]
               ■ = −1/2 (3^𝒙 + 1)^{-3/2} · (ln 3)·3^𝒙
     ◉ Substitute into the product rule:
          ○ 𝒅𝒚/𝒅𝒙 =
               ■ (ln 2)·2^𝒙 (3^𝒙 + 1)^{-1/2}
               ■ − 2^𝒙 · (1/2)(ln 3)·3^𝒙 (3^𝒙 + 1)^{-3/2}
     ◉ Factor common terms:
          ○ 𝒅𝒚/𝒅𝒙 = 2^𝒙 (3^𝒙 + 1)^{-3/2}
               ■ [ (ln 2)(3^𝒙 + 1) − (1/2)(ln 3)·3^𝒙 ]


● [24:53]. 🧩 Example – Differentiate a product involving a general exponential function:  𝒚 = 𝒙 · 5^{3𝒙} [📷image](./img/Calculus 2 Lecture 6.4/[24-53]Example Differentiate a product involving a general exponential function  𝒚 = 𝒙 · 5^{3𝒙}.png)
     ◉ Apply the product rule:
          ○ 𝒅/𝒅𝒙[𝒖·𝒗] = 𝒖'·𝒗 + 𝒖·𝒗'
     ◉ Identify each factor:
          ○ 𝒖 = 𝒙
          ○ 𝒗 = 5^{3𝒙}
     ◉ Differentiate each factor:
          ○ 𝒅/𝒅𝒙[𝒙] = 1
          ○ 𝒅/𝒅𝒙[5^{3𝒙}] = (ln 5)·5^{3𝒙}·3
     ◉ Substitute into the product rule:
          ○ 𝒅𝒚/𝒅𝒙 = 5^{3𝒙} + 𝒙·(ln 5)·5^{3𝒙}·3
     ◉ Simplify the expression:
          ○ 𝒅𝒚/𝒅𝒙 = 5^{3𝒙} + 3𝒙(ln 5)5^{3𝒙}
     ◉ Factor the common exponential term:
          ○ 𝒅𝒚/𝒅𝒙 = 5^{3𝒙} (1 + 3𝒙 ln 5)

● [28:25]. 🧩 Example – Logarithmic differentiation for a variable base and exponent: 𝒚 = 𝒙^𝒙 [📷image](./img/Calculus 2 Lecture 6.4/[28-25]Example Logarithmic differentiation for a variable base and exponent 𝒚 = 𝒙^𝒙.png)
     ◉ **Logarithmic differentiation for a variable base and exponent:** [📷image](./img/Calculus 2 Lecture 6.4/[28-25]Logarithmic differentiation for a variable base and exponent.png)
          ○ Use this technique when the function has the form 𝒚 = (𝒇(𝒙))^{𝒈(𝒙)}, where both the base and the exponent depend on 𝒙.
          ○ Idea: take natural logarithms to simplify exponents into products, which are easier to differentiate.
               ■ ln(𝒚) = ln((𝒇(𝒙))^{𝒈(𝒙)}) = 𝒈(𝒙) · ln(𝒇(𝒙))
          ○ Differentiate both sides with respect to 𝒙 using implicit differentiation.
          ○ This method avoids complicated applications of the chain and product rules directly on the original expression.
          ○ Especially useful for expressions like 𝒙^𝒙, (sin 𝒙)^{𝒙}, or (𝒙²+1)^{√𝒙}.
     ◉ Take natural logarithms on both sides:
          ○ ln(𝒚) = ln(𝒙^𝒙)
     ◉ Use the power rule for logarithms:
          ○ ln(𝒚) = 𝒙 ln(𝒙)
     ◉ Differentiate both sides with respect to 𝒙:
          ○ 𝒅/𝒅𝒙[ln(𝒚)] = 𝒅/𝒅𝒙[𝒙 ln(𝒙)]
     ◉ Apply implicit differentiation on the left:
          ○ (1/𝒚) · 𝒅𝒚/𝒅𝒙 = 𝒅/𝒅𝒙[𝒙]·ln(𝒙) + 𝒙·𝒅/𝒅𝒙[ln(𝒙)]
     ◉ Compute each derivative:
          ○ (1/𝒚) · 𝒅𝒚/𝒅𝒙 = ln(𝒙) + 𝒙·(1/𝒙)
     ◉ Simplify:
          ○ (1/𝒚) · 𝒅𝒚/𝒅𝒙 = ln(𝒙) + 1
     ◉ Multiply both sides by 𝒚:
          ○ 𝒅𝒚/𝒅𝒙 = (ln(𝒙) + 1) · 𝒚
     ◉ Substitute back 𝒚 = 𝒙^𝒙:
          ○ 𝒅𝒚/𝒅𝒙 = (ln(𝒙) + 1) · 𝒙^𝒙


● [35:40]. 🧩 Example – Logarithmic differentiation for a variable base and exponent: 𝒚 = (𝒙² + 𝒙)^{√𝒙}. [📷image](./img/Calculus 2 Lecture 6.4/[35-40]Example Logarithmic differentiation for a variable base and exponent 𝒚 = (𝒙² + 𝒙)^{√𝒙}.png)
     ◉ Take natural logarithms:
          ○ ln(𝒚) = ln((𝒙² + 𝒙)^{√𝒙})
          ○ ln(𝒚) = √𝒙 · ln(𝒙² + 𝒙)
     ◉ Differentiate both sides with respect to 𝒙:
          ○ 𝒅/𝒅𝒙[ln(𝒚)] = 𝒅/𝒅𝒙[√𝒙 · ln(𝒙² + 𝒙)]
     ◉ Implicit differentiation on the left:
          ○ (1/𝒚) · 𝒅𝒚/𝒅𝒙 = 𝒅/𝒅𝒙[√𝒙] · ln(𝒙² + 𝒙) + √𝒙 · 𝒅/𝒅𝒙[ln(𝒙² + 𝒙)]
     ◉ Compute each derivative:
          ○ 𝒅/𝒅𝒙[√𝒙] = 1/(2√𝒙)
          ○ 𝒅/𝒅𝒙[ln(𝒙² + 𝒙)] = (1/(𝒙² + 𝒙)) · 𝒅/𝒅𝒙[𝒙² + 𝒙]
          ○ 𝒅/𝒅𝒙[𝒙² + 𝒙] = 2𝒙 + 1
     ◉ Substitute and simplify:
          ○ (1/𝒚) · 𝒅𝒚/𝒅𝒙 = ln(𝒙² + 𝒙)/(2√𝒙) + √𝒙(2𝒙 + 1)/(𝒙² + 𝒙)
     ◉ Solve for 𝒅𝒚/𝒅𝒙:
          ○ 𝒅𝒚/𝒅𝒙 = [ ln(𝒙² + 𝒙)/(2√𝒙) + √𝒙(2𝒙 + 1)/(𝒙² + 𝒙) ] · 𝒚
     ◉ Substitute back 𝒚 = (𝒙² + 𝒙)^{√𝒙}:
          ○ 𝒅𝒚/𝒅𝒙 = [ ln(𝒙² + 𝒙)/(2√𝒙) + √𝒙(2𝒙 + 1)/(𝒙² + 𝒙) ] · (𝒙² + 𝒙)^{√𝒙}

● [1:00:24]. 🧩 Example – Differentiation using the chain rule (not logarithmic differentiation).
     ◉ Given function with constant irrational exponent:
          ○ 𝒚 = (𝒙 + cos 𝒙)^{√2}
     ◉ Apply the power rule combined with the chain rule:
          ○ Outer function: 𝒖^{√2}
          ○ Inner function: 𝒖 = 𝒙 + cos 𝒙
     ◉ Differentiate step by step:
          ○ 𝒅/𝒅𝒙 [𝒚] = √2 · (𝒙 + cos 𝒙)^{√2 − 1} · 𝒅/𝒅𝒙(𝒙 + cos 𝒙)
          ○ 𝒅/𝒅𝒙(𝒙 + cos 𝒙) = 1 − sin 𝒙
     ◉ Final derivative:
          ○ 𝒅𝒚/𝒅𝒙 = √2 (𝒙 + cos 𝒙)^{√2 − 1} (1 − sin 𝒙)





Ｉｎｔｅｇｒａｌ ｏｆ ａｎ ｅｘｐｏｎｅｎｔｉａｌ ｆｕｎｃｔｉｏｎ

● [45:25]. Integral of an exponential function. [📷image](./img/Calculus 2 Lecture 6.4/[45-25]Integral of an exponential function.png)
     ◉ General antiderivative of a constant base exponential:
          ○ ∫ 𝒂^𝒖 𝒅𝒖 = 𝒂^𝒖 / ln(𝒂) + 𝓒,   for 𝒂 > 0, 𝒂 ≠ 1.
     ◉ Special case: natural exponential function:
          ○ ∫ 𝓮^𝒖 𝒅𝒖 = 𝓮^𝒖 / ln(𝓮) + 𝓒 = 𝓮^𝒖 + 𝓒,   since ln(𝓮) = 1.

● [46:50]. 🧩 Example – Definite integral of an exponential function with base different from 𝓮:  ∫[0,4] 3^𝒙 𝒅𝒙 [📷image](./img/Calculus 2 Lecture 6.4/[46-50]Example Definite integral of an exponential function with base different from 𝓮  ∫[0,4] 3^𝒙 𝒅𝒙.png)
     ◉ Apply the general antiderivative formula:
          ○ ∫ 𝒂^𝒙 𝒅𝒙 = 𝒂^𝒙 / ln(𝒂)
     ◉ Evaluate on the interval [0, 4]:
          ○ [ 3^𝒙 / ln(3) ]₀⁴
          ○ = (3⁴ − 3⁰) / ln(3)
     ◉ Final result:
          ○ = 80 / ln(3)

● [49:45]. 🧩 Example – Definite integral using substitution: ∫[1,4] 3^{√𝒙} / √𝒙  𝒅𝒙 [📷image](./img/Calculus 2 Lecture 6.4/[49-45]Example Definite integral using substitution ∫[1,4] 3^{√𝒙} ∕ √𝒙  𝒅𝒙.png)
     ◉ Choose the substitution:
          ○ Let 𝒖 = √𝒙
               ■ 𝒖 = 𝒙^{1/2}
               ■ 𝒅𝒖 = (1 / (2√𝒙)) 𝒅𝒙
               ■ 2 𝒅𝒖 = (1 / √𝒙) 𝒅𝒙
     ◉ Change the limits of integration:
          ○ When 𝒙 = 1  ⇒  𝒖 = 1
          ○ When 𝒙 = 4  ⇒  𝒖 = 2
     ◉ Rewrite the integral in terms of 𝒖:
          ○ ∫[1,2] 3^{𝒖} · 2 𝒅𝒖
          ○ = 2 ∫[1,2] 3^{𝒖} 𝒅𝒖
     ◉ Evaluate the integral:
          ○ 2 [ 3^{𝒖} / ln(3) ]₁²
          ○ = 2 ( 3² / ln(3) − 3¹ / ln(3) )
     ◉ Final result:
          ○ = 2 ( 9 − 3 ) / ln(3)
          ○ = 12 / ln(3)

● [57:20]. 🧩 Examples – 𝒖-substitution. [📷image](./img/Calculus 2 Lecture 6.4/[57-20]Examples 𝒖-substitution.png)
     ◉ Example 1 – Substitution in an exponential with a quadratic exponent:
          ○ Original integral:
               ■ ∫ (𝒙 + 1) · 3^{𝒙² + 2𝒙} 𝒅𝒙
          ○ Choose the substitution:
               ■ Let 𝒖 = 𝒙² + 2𝒙
               ■ 𝒅𝒖 = (2𝒙 + 2) 𝒅𝒙 = 2(𝒙 + 1) 𝒅𝒙
          ○ Rewrite the integral:
               ■ (1/2) ∫ 3^{𝒖} 𝒅𝒖
          ○ Integrate:
               ■ (1/2) · 3^{𝒖} / ln(3) + 𝓒
          ○ Back-substitution:
               ■ = 3^{𝒙² + 2𝒙} / (2 ln 3) + 𝓒
     ◉ Example 2 – Substitution in a rational exponential expression:
          ○ Original integral:
               ■ ∫ 3^𝒙 / (1 + 3^𝒙) 𝒅𝒙
          ○ Choose the substitution:
               ■ Let 𝒖 = 1 + 3^𝒙
               ■ 𝒅𝒖 = (ln 3) · 3^𝒙 𝒅𝒙
          ○ Rewrite the integral:
               ■ (1 / ln 3) ∫ 1/𝒖 𝒅𝒖
          ○ Integrate:
               ■ (1 / ln 3) ln|𝒖| + 𝓒
          ○ Back-substitution:
               ■ = (1 / ln 3) ln(1 + 3^𝒙) + 𝓒





Ｄｅｒｉｖａｔｉｖｅｓ  Lｏｇ  ｂａｓｅ  ' 𝓪 ' 


● [1:02:18]. Derivative of logarithmic functions with base 𝒂. [📷image](./img/Calculus 2 Lecture 6.4/[1-02-18]Derivative of logarithmic functions with base 𝒂.png)
     ◉ Change of base formula:
          ○ logₐ|𝒙| = ln|𝒙| / ln 𝒂
     ◉ Derivative of the logarithm with base 𝒂:
          ○ 𝒅/𝒅𝒙 [logₐ|𝒙|]
               ■ = 𝒅/𝒅𝒙 [ ln|𝒙| / ln 𝒂 ]
               ■ = 1 / ln 𝒂 · 𝒅/𝒅𝒙 [ ln|𝒙| ]
               ■ = 1 / (ln 𝒂 · 𝒙)
     ◉ Special case: natural logarithm:
          ○ 𝒅/𝒅𝒙 [ln 𝒙] = 1 / 𝒙

● [1:06:00]. Chain rule derivative of logarithmic functions with base 𝒂. [📷image](./img/Calculus 2 Lecture 6.4/[1-06-00]Chain rule derivative of logarithmic functions with base 𝒂.png)
     ◉ Change of base:
          ○ logₐ|𝒖| = ln|𝒖| / ln 𝒂
     ◉ Derivative using the chain rule:
          ○ 𝒅/𝒅𝒙 [ logₐ|𝒖| ]
               ■ = 1 / ln 𝒂 · 𝒅/𝒅𝒙 [ ln|𝒖| ]
               ■ = 1 / ln 𝒂 · (1 / 𝒖) · 𝒅𝒖/𝒅𝒙
               ■ = 1 / ( (ln 𝒂) · 𝒖 ) · 𝒅𝒖/𝒅𝒙

● [1:08:19]. 🧩 Example – Chain rule derivative of a logarithmic function with base 2: 𝒚 = log₂|tan 𝒙|  [📷image](./img/Calculus 2 Lecture 6.4/[1-08-19]Example Chain rule derivative of a logarithmic function with base 2 𝒚 = log₂ abs(tan 𝒙).png)
     ◉ Apply change of base:
          ○ 𝒚 = ln|tan 𝒙| / ln 2
     ◉ Differentiate using the chain rule:
          ○ 𝒅𝒚/𝒅𝒙 = 1 / ln 2 · 𝒅/𝒅𝒙 [ ln|tan 𝒙| ]
               ■ = 1 / ln 2 · 1 / tan 𝒙 · 𝒅/𝒅𝒙 [ tan 𝒙 ]
               ■ = sec²𝒙 / ( (ln 2) · tan 𝒙 )

● [1:11:00]. 🧩 Example – Differentiation of a product involving a logarithmic function (base 10): 𝒚 = 𝒙² · log(𝓮^{2𝒙} + 1)  [📷image](./img/Calculus 2 Lecture 6.4/[1-11-00]Example Differentiation of a product involving a logarithmic function (base 10)  𝒚 = 𝒙² · log(𝓮^{2𝒙} + 1).png)
     ◉ Apply the product rule:
          ○ 𝒅𝒚/𝒅𝒙 = 𝒅/𝒅𝒙[𝒙²] · log(𝓮^{2𝒙} + 1)
                       + 𝒙² · 𝒅/𝒅𝒙[ log(𝓮^{2𝒙} + 1) ]
     ◉ Differentiate each term:
          ○ 𝒅/𝒅𝒙[𝒙²] = 2𝒙
          ○ 𝒅/𝒅𝒙[ log(𝓮^{2𝒙} + 1) ]
               ■ = 1 / ( ln 10 · (𝓮^{2𝒙} + 1) ) · 𝒅/𝒅𝒙[𝓮^{2𝒙} + 1]
               ■ = 1 / ( ln 10 · (𝓮^{2𝒙} + 1) ) · 2𝓮^{2𝒙}
     ◉ Final result:
          ○ 𝒅𝒚/𝒅𝒙 = 2𝒙 · log(𝓮^{2𝒙} + 1) + (2𝒙² 𝓮^{2𝒙}) / ( ln 10 · (𝓮^{2𝒙} + 1) )





     



