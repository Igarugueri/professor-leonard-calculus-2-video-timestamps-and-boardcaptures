-----------------------------------** Ｃａｌｃｕｌｕｓ　２　ｌｅｃｔｕｒｅ　６．２：　Dｅｒｉｖａｔｉｖｅｓ　Oｆ　Iｎｖｅｒｓｅ　Fｕｎｃｔｉｏｎｓ**------------------------------—




Ｅｘｉｓｔｅｎｃｅ,  Ｎｏｔａｔｉｏｎ ａｎｄ Ａｌｇｅｂｒａｉｃ Ｐｒｏｐｅｒｔｉｅｓ ｏｆ Ｉｎｖｅｒｓｅ Ｆｕｎｃｔｉｏｎｓ

● [0:00]. Introduction to Section 6.2: Properties and derivatives of inverse functions.

● [0:29]. Fundamental requirements for the existence of an inverse function.
     ◉ One-to-one functions and uniqueness of outputs for each input.
     ◉ Use of the horizontal line test to verify injectivity. 
     ◉ Definition of the inverse function by interchanging inputs and outputs.
          ○ In a function, the input is 𝒙 and the output is 𝒚. To obtain the inverse function, the roles of input and output are exchanged: 
               ■ What was the input becomes the output, and what was the output becomes the input. That is, if the original function maps
                 𝒙 → 𝒚 the inverse function maps 𝒚 → 𝒙 In practice, to compute an inverse function:
                    ▣ 1) Write 𝒚 = 𝒇(𝒙)
                    ▣ 2) Interchange 𝒙 and 𝒚
                    ▣ 3) Solve for 𝒚
                    ▣ 🧩 Example – : 𝒇(𝒙) = 2𝒙 + 1
                         ▢ After interchanging variables: 𝒙 = 2𝒚 + 1
                         ▢ Solving for 𝒚: 𝒚 = (𝒙 − 1) / 2

● [1:53]. Notation and basic properties of 𝒇⁻¹. 
     ◉ Distinction between inverse notation 𝒇⁻¹ and exponents.
     ◉ Verification of inverses using composition of functions.
          ○ Identity property: 𝒇⁻¹(𝒇(𝒙)) = 𝒙
          ○ Identity property: 𝒇(𝒇⁻¹(𝒙)) = 𝒙
               ■ The 𝒙 in 𝒇⁻¹(𝒙) is not the same 𝒙 as in the original function; it represents a y-value.
          



Ｆｉｎｄｉｎｇ ｔｈｅ Ｉｎｖｅｒｓｅ Ｆｕｎｃｔｉｏｎ

● [4:17]. Algebraic procedure to determine the inverse function. 
     ◉ Steps for interchanging the variables 𝒙 and 𝒚.
          ○ 🧩 Example – Find the inverse: 𝒇(𝒙) = 1 / √(2𝒙 − 3).
               ■ Write the function using 𝒚:
                    ▣ 𝒚 = 1 / √(2𝒙 − 3)
               ■ Interchange variables:
                    ▣ 𝒙 = 1 / √(2𝒚 − 3)
               ■ Solve for 𝒚:
                    ▣ √(2𝒚 − 3) = 1 / 𝒙
                    ▣ 2𝒚 − 3 = (1 / 𝒙)²
                    ▣ 2𝒚 − 3 = 1 / 𝒙²
                    ▣ 2𝒚 = 1 / 𝒙² + 3
                    ▣ 𝒚 = 1 / (2𝒙²) + 3 / 2
                    ▣ 𝒚 = (1 + 3𝒙²) / (2𝒙²)
               ■ Definition of the inverse function:
                    ▣ 𝒇⁻¹(𝒙) = (1 + 3𝒙²) / (2𝒙²)
               ■ Verification by composition:
                    ▣ 𝒇⁻¹(𝒇(𝒙)) = (1 + 3(1 / √(2𝒙 − 3))²) / (2(1 / √(2𝒙 − 3))²)
                         ▢ Combine terms over a common denominator:
                              ▲ (1 + 3 / (2𝒙 − 3)) / (2 / (2𝒙 − 3))
                                   ◭ Multiply numerator and denominator by (2𝒙 − 3):
                                        △ (2𝒙 − 3 + 3) / 2 = 2𝒙 / 2 = 𝒙 — Each function exactly undoes what the other does; 𝒇⁻¹(𝒇(𝒙)) = 𝒙 ∎

● [10:40].  The idea behind an inverse function.
     ◉ For every one-to-one function, its inverse can be found and is also one-to-one.
   



Ｇｒａｐｈｉｃａｌ Ｉｎｔｅｒｐｒｅｔａｔｉｏｎ  Ｄｅｒｉｖａｔｉｖｅ ｏｆ ｔｈｅ Ｉｎｖｅｒｓｅ Ｆｕｎｃｔｉｏｎ

● [11:05]. Graphical and geometric relationship of inverse functions. 
     ◉ 1) Symmetry and reflection of the graph across the identity line 𝒚 = 𝒙.
     ◉ 2) I̲f̲ 𝒇 is continuous on a given domain, t̲h̲e̲n̲ 𝒇⁻¹ is continuous on a corresponding domain.
          ○ Continuity theorems for inverse functions.
               ■ Set relationship: the domain of 𝒇 becomes the range of 𝒇⁻¹. 
               ■ The range of 𝒇 determines the domain of 𝒇⁻¹.
               ■ 🧩 Example – Domain and range shown graphically. 
                    ▣ The graph of 𝒇 and its inverse illustrate how the domain of 𝒇 becomes the range of 𝒇⁻¹ under reflection across 𝒚 = 𝒙.
     ◉ [17:35]. 3) Differentiability and computation of derivatives of inverse functions.
          ○ Existence theorem for the derivative of 𝒇⁻¹ when 𝒇 is differentiable.
               ■ I̲f̲ 𝒇 is differentiable, t̲h̲e̲n̲ 𝒇⁻¹ is also differentiable.
          ○ Derivation of the formula for the derivative of the inverse function.
               ■ Derivative formula:
                    ▣ d/d𝒙 [𝒇⁻¹(𝒙)] = 1 / 𝒇'(𝒇⁻¹(𝒙)) OR
                         ▢ If 𝓰(𝒙) = 𝒇⁻¹ then 𝓰'(𝒙) = 1 / 𝒇'(𝓰(𝒙))
                       



Ｅｖａｌｕａｔｉｎｇ Ｉｎｖｅｒｓｅ Ｆｕｎｃｔｉｏｎｓ

● [21:5]. Evaluating inverse functions at specific points without explicit computation.
     ◉ S͟t͟a͟t͟m͟e͟n͟t͟  :  𝒇(𝒙) = 𝓪   ⇔   𝒇'(𝓪) = 𝒙
     ◉ [22:27]. 🧩 Example – : 𝒇(𝒙) = 𝒙³ - 1, find 𝒇⁻¹(𝓪) when 𝓪 = -1 
          ○ 1) Set 𝒇(𝒙) = 𝓪:
               ■ 𝒙³ − 1 = −1
          ○ 2) Solve for 𝒙:
               ■ 𝒙³ = 0
               ■ 𝒙 = 0
          ○ 3) Find 𝒇⁻¹(𝓪):
               ■ 𝒇⁻¹(−1) = 0 
     ◉ [27:20]. 🧩 Example – 𝒇(𝒙) = (3/π)𝒙 + sin(𝒙), find 𝒇⁻¹(𝓪) when 𝓪 = 1 
          ○ S͟t͟a͟t͟m͟e͟n͟t͟  : 𝒇(𝒙) = 𝓪   ⇔   𝒇⁻¹(𝓪) = 𝒙
          ○ 1) Set 𝒇(𝒙) = 𝓪:
               ■ (3/π)𝒙 + sin(𝒙) = 1
          ○ 2) Solve for 𝒙:
               ■ 𝒙 = π / 6
          ○ 3) Verification:
               ■ (3/π)(π/6) + sin(π/6) = 1/2 + 1/2 = 1
          ○ 4) Evaluate the inverse:
               ■ 𝒇⁻¹(1) = π / 6



 

Ａｐｐｌｉｃａｔｉｏｎｓ ｏｆ ｔｈｅ Ｉｎｖｅｒｓｅ Ｄｅｒｉｖａｔｉｖｅ

● [37:54]. Application of the derivative of the inverse function evaluated at a given point. 
     ◉ 🧩 Example – Find the derivative of the inverse of: 𝒇(𝒙) = 𝒙³ at the point (2, 8) where 𝒈 = 𝒇⁻¹.     
          ○ Identify the given point on 𝒇:
               ■ 𝒇(2) = 2³ = 8
          ○ Compute the derivative of 𝒇:
               ■ 𝒇'(𝒙) = 3𝒙²
          ○ Identify the corresponding value on the inverse function:
               ■ 𝒈(8) = 2
          ○ Apply the derivative formula for inverse functions:
               ■ 𝒈'(8) = 1 / 𝒇'(2)
               ■ 𝒈'(8) = 1 / (3 · 2²)
               ■ 𝒈'(8) = 1 / 12
     ◉ [39:00]. 🧩 Example – Find the derivative of the inverse of 𝒇(𝒙) = (𝒙² + 1)³ at the point (1, 8), where 𝒈 = 𝒇⁻¹.    
          ○ Identify the given point on 𝒇:
               ■ 𝒇(1) = (1² + 1)³ = 8
          ○ Identify the corresponding value on the inverse function:
               ■ 𝒈(8) = 1
          ○ Compute the derivative of 𝒇:
               ■ 𝒇'(𝒙) = 6𝒙(𝒙² + 1)²
          ○ Apply the derivative formula for inverse functions:
               ■ 𝒈'(8) = 1 / 𝒇'(𝒈(8))
               ■ 𝒈'(8) = 1 / 𝒇'(1)
               ■ 𝒈'(8) = 1 / 24




