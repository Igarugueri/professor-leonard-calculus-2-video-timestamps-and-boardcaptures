-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ９．１ － Ｃｏｎｖｅｒｇｅｎｃｅ  ａｎｄ   Ｄｉｖｅｒｇｅｎｃｅ  ｏｆ  Ｓｅｑｕｅｎｃｅｓ**------------------------------—






Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:00]. Introduction to Sequences and Series.
     ◉ In this section, the focus is only on sequences.
     ◉ Main goals:
          ○ understand what a sequence is
          ○ generate terms from sequence notation
          ○ find sequence notation from a list of terms
          ○ determine whether a sequence converges or diverges
     ◉ Motivating idea:
          ○ a complicated function 𝒇(𝒙) can often be expressed as a series of simpler functions




          

Ｓｅｑｕｅｎｃｅｓ　—　Ｂａｓｉｃ　Ｄｅｆｉｎｉｔｉｏｎｓ　＆　Ｎｏｔａｔｉｏｎ

● [1:37]. Definition of a sequence 𝒂ₙ. 
     ◉ A sequence is a set of terms, typically an ordered list of terms.
     ◉ Standard notation:
          ○ 𝒂₁, 𝒂₂, 𝒂₃, …, 𝒂ₙ
     ◉ The index n is a positive integer.
     ◉ Alternative notation:
          ○ a sequence may also be written as {a_𝒏}_{n=k}^∞
     ◉ Convention:
          ○ if no starting index is shown,
               ■ 𝒏 starts at 1
               


               

Ｇｅｎｅｒａｔｉｎｇ　Ｔｅｒｍｓ　Ｆｒｏｍ　Ｓｅｑｕｅｎｃｅ　Ｎｏｔａｔｉｏｎ

● [4:20]. Generating terms from sequence notation.
     ◉ Basic idea:
          ○ substitute specific values of 𝒏 into the formula to generate terms

● [4:48]. 🧩 Example 1 — Listing the first terms of the sequence {((-1)ⁿ⁺¹ 2ⁿ)/(n+1)}. 
     ◉ Substitute:
          ○ n = 1  →  𝒂₁ = 1
          ○ n = 2  →  𝒂₂ = -4/3
          ○ n = 3  →  𝒂₃ = 2
          ○ n = 4  →  𝒂₄ = -16/5
          ○ n = 5  →  𝒂₅ = 16/3
     ◉ Alternating behavior:
          ○ the factor (-1)ⁿ⁺¹ makes the sequence alternate in sign
          ○ positive, negative, positive, negative, ...
     ◉ Pattern recognition:
          ○ the sequence continues indefinitely
          ○ each term is obtained by substituting the next positive integer value of n
 

● [11:15]. 🧩 Example 2 — Evaluating the sequence {(-1)ⁿ √(n - 2)} with starting index n = 2. 
     ◉ Reason for the starting index:
          ○ the sequence starts at n = 2 because √(n - 2) is not real when n = 1
     ◉ Evaluate the first terms by substitution.
          ○ n = 2  →  𝒂₂ = 0
          ○ n = 3  →  𝒂₃ = -1
          ○ n = 4  →  𝒂₄ = √2
          ○ n = 5  →  𝒂₅ = -√3
          ○ n = 6  →  𝒂₆ = 2
     ◉ Pattern:
          ○ the factor (-1)ⁿ makes the signs alternate
          ○ the radical part follows √0, √1, √2, √3, √4, ...




          

Ｆｉｎｄｉｎｇ　Ｓｅｑｕｅｎｃｅ　Ｎｏｔａｔｉｏｎ　Ｆｒｏｍ　Ａ　Ｌｉｓｔ　Ｏｆ　Ｔｅｒｍｓ

● Determining the notation of a sequence from a list of terms.
     ◉ General strategy:
          ○ 1. Rewrite the given terms in a uniform form, if possible.
          ○ 2. Relate each part of the term to the index n.
          ○ 3. Move from the specific pattern to the general formula.

● Pattern-identification strategies.
     ◉ Look for:
          ○ numerator patterns
          ○ denominator patterns
          ○ alternating signs
          ○ radicals
          ○ factorials

● [20:06]. 🧩 Example 3 — Finding the sequence notation from a list of terms: 2, 3/√2, 4/√3, 5/2, … 
     ◉ Step 1. Rewrite the given terms in a uniform form, if possible.
          ○ a₁ = 2
          ○ a₂ = 3/√2
          ○ a₃ = 4/√3
          ○ a₄ = 5/2
     ◉ Step 2. Relate each part of the term to the index n.
          ○ a₁ = 2        →  2/√1  
          ○ a₂ = 3/√2   →  3/√2  
          ○ a₃ = 4/√3   →  4/√3  
          ○ a₄ = 5/2     →  5/√4  
     ◉ Step 3. Move from the specific pattern to the general formula.
          ○ a₁ = 2        →   2/√1   →   (1 + 1)/√1
          ○ a₂ = 3/√2   →   3/√2   →   (2 + 1)/√2
          ○ a₃ = 4/√3   →   4/√3   →   (3 + 1)/√3
          ○ a₄ = 5/2     →   5/√4   →   (4 + 1)/√4
          ○ Pattern identification:
               ■ numerator = n + 1
               ■ denominator = √n
               ■ General formula:
                    ▣ aₙ = (n + 1)/√n

● [23:30]. 🧩 Example 4 — Finding the sequence notation from a list of terms: -1, 1/2, -1/6, 1/24, -1/120, … 
     ◉ Step 1. Identify the sign pattern.
          ○ a₁ = -1         →  negative
          ○ a₂ = 1/2       →  positive
          ○ a₃ = -1/6      →  negative
          ○ a₄ = 1/24     →  positive
          ○ a₅ = -1/120  →  negative
     ◉ Step 2. Rewrite the denominators in factorial form.
          ○ a₁ = -1          →  -1/1
          ○ a₂ = 1/2        →  1/(2·1)  
          ○ a₃ = -1/6       →  -1/(3·2·1) 
          ○ a₄ = 1/24      →  1/(4·3·2·1)
          ○ a₅ = -1/120   →  -1/(5·4·3·2·1) 
     ◉ Step 3. Move from the specific pattern to the general formula.
          ○ a₁ = -1      →  -1/1      →  -1/1!
          ○ a₂ = 1/2     →  1/(2·1)   →  1/2!
          ○ a₃ = -1/6    →  -1/(3·2·1) →  -1/3!
          ○ a₄ = 1/24    →  1/(4·3·2·1) →  1/4!
          ○ a₅ = -1/120  →  -1/(5·4·3·2·1) →  -1/5!
          ○ the sign alternates
          ○ the numerator is always ±1
          ○ the denominator is n!
          ○ since the sequence starts with a negative term,
               ■ use (-1)ⁿ for the sign pattern
     ◉ General formula:
          ○ aₙ = (-1)ⁿ / n!




          

Ｒｅｃｕｒｓｉｖｅ　Ｓｅｑｕｅｎｃｅｓ

● Recursive sequences.
     ◉ A recursive sequence is defined using previous terms.
     ◉ To generate a new term,
          ○ use the given initial values
          ○ and apply the recursive formula to the preceding terms

● [36:40]. 🧩 Example 5 — Recursive sequence. 
     ◉ Given:
          ○ a₁ = 2
          ○ a₂ = 4
          ○ aₙ₊₁ = 2aₙ - aₙ₋₁
     ◉ Idea:
          ○ each new term is built from previous terms
          ○ this is a recursive sequence
     ◉ Generate the next terms:
          ○ a₃ = 2a₂ - a₁  →  2(4) - 2  →  6
          ○ a₄ = 2a₃ - a₂  →  2(6) - 4  →  8
          ○ a₅ = 2a₄ - a₃  →  2(8) - 6  →  10
     ◉ First generated terms:
          ○ 2, 4, 6, 8, 10, ...




          

Ｌｉｍｉｔｓ　Ｏｆ　Ｓｅｑｕｅｎｃｅｓ　—　Ｃｏｎｖｅｒｇｅｎｃｅ　＆　Ｄｉｖｅｒｇｅｎｃｅ

● [43:42]. Limit of a sequence. 
     ◉ A sequence {aₙ} has a limit if the terms approach a single value as n → ∞.
     ◉ Notation:
          ○ limₙ→∞ aₙ
     ◉ Main idea:
          ○ the goal is to study what happens to aₙ as n → ∞

● Convergence.
     ◉ If limₙ→∞ aₙ exists and equals a real number,
          ○ then the sequence is convergent.

● Divergence.
     ◉ If the limit does not exist,
          ○ or if the sequence tends to +∞ or -∞,
               ■ then the sequence is divergent.




               

Ｐｒｏｐｅｒｔｉｅｓ　Ｏｆ　Ｌｉｍｉｔｓ　Ｏｆ　Ｓｅｑｕｅｎｃｅｓ

● [46:40]. Properties of limits of sequences. 
     ◉ Constant multiple:
          ○ limₙ→∞ (c ·aₙ) = c limₙ→∞ aₙ
     ◉ Sum:
          ○ limₙ→∞ (aₙ + bₙ) = limₙ→∞ aₙ + limₙ→∞ bₙ
     ◉ Product:
          ○ limₙ→∞ (aₙ· bₙ) = (limₙ→∞ aₙ)·(limₙ→∞ bₙ)
     ◉ Quotient:
          ○ limₙ→∞ (aₙ / bₙ) = (limₙ→∞ aₙ) / (limₙ→∞ bₙ)
     ◉ Power rule:
          ○ limₙ→∞ (aₙ)ᵖ = (limₙ→∞ aₙ)ᵖ
          ○ valid when aₙ > 0 and p > 0




     

Ｔｅｓｔｉｎｇ　Ｃｏｎｖｅｒｇｅｎｃｅ　Ｂｙ　Ｅｖａｌｕａｔｉｎｇ　Ｌｉｍｉｔｓ

● [50:39]. 🧩 Example 1 — Oscillating sequence: aₙ = (-1)ⁿ.
     ◉ Terms:
          ○ -1, 1, -1, 1, -1, ...
     ◉ Conclusion:
          ○ the sequence oscillates and does not approach a single number
          ○ therefore it diverges

● [52:52]. 🧩 Example 2 — Sequence: aₙ = 2n/(n + 1).
     ◉ Take the limit:
          ○ limₙ→∞ 2n/(n + 1)
     ◉ Simplify by dividing by the highest power of n in the denominator:
          ○ limₙ→∞ (2n/n)/((n + 1)/n)
          ○ limₙ→∞ 2/(1 + 1/n)
     ◉ Limit:
          ○ 2
     ◉ Conclusion:
          ○ the sequence converges to 2

● [56:51]. 🧩 Example 3 — Sequence: aₙ = (2 + (-1)ⁿ)/n.
     ◉ Take the limit:
          ○ limₙ→∞ (2 + (-1)ⁿ)/n
     ◉ Rewrite:
          ○ limₙ→∞ [2/n + (-1)ⁿ/n]
     ◉ Key observation:
          ○ 2/n → 0
          ○ (-1)ⁿ/n → 0
     ◉ Conclusion:
          ○ the sequence converges to 0

● [1:01:01]. 🧩 Example 4 — Sequence: aₙ = ln(n)/n.
     ◉ Take the limit:
          ○ limₙ→∞ ln(n)/n
     ◉ Apply L'Hôpital's Rule:
          ○ d/dn [ln(n)] = 1/n
          ○ d/dn [n] = 1
     ◉ Result:
          ○ limₙ→∞ (1/n)/1 = 0
     ◉ Conclusion:
          ○ the sequence converges to 0

● [1:03:08]. 🧩 Example 5 — Difference of radicals: aₙ = √(n + 1) - √n
     ◉ Technique:
          ○ multiply by the conjugate
     ◉ Transformation:
          ○ [√(n + 1) - √n] · [√(n + 1) + √n] / [√(n + 1) + √n]
          ○ = [(n + 1) - n] / [√(n + 1) + √n]
          ○ = 1 / [√(n + 1) + √n]
     ◉ Result:
          ○ the limit is 0
     ◉ Conclusion:
          ○ the sequence converges to 0




          

Ｓｑｕｅｅｚｅ　Ｔｈｅｏｒｅｍ　Ｆｏｒ　Ｓｅｑｕｅｎｃｅｓ

● [1:07:42]. Squeeze Theorem. 
     ◉ If
          ○ aₙ ≤ bₙ ≤ cₙ
     ◉ and
          ○ limₙ→∞ aₙ = limₙ→∞ cₙ = L
     ◉ then
          ○ limₙ→∞ bₙ = L

● [1:11:06]. 🧩 Example — Sequence: aₙ = n!/nⁿ. 
     ◉ First observation:
          ○ 0 ≤ aₙ
     ◉ Key comparison:
          ○ n! = n(n - 1)(n - 2) ··· 2·1
          ○ n! has n factors
          ○ the last factor is 1
          ○ since 1 ≤ n,
               ■ it is not necessary to compare that last factor with another extra n
               ■ therefore the estimate can be sharpened to
                    ▣ n! ≤ nⁿ⁻¹
     ◉ Divide by nⁿ:
          ○ n!/nⁿ ≤ nⁿ⁻¹/nⁿ = 1/n
     ◉ Apply the Squeeze Theorem:
          ○ 0 ≤ aₙ ≤ 1/n
          ○ and 1/n → 0 as n → ∞
          ○ therefore
               ■ aₙ → 0
     ◉ Conclusion:
          ○ the sequence converges to 0


          


Ａｂｓｏｌｕｔｅ　Ｖａｌｕｅ　Ｔｈｅｏｒｅｍ　Ｆｏｒ　Ｓｅｑｕｅｎｃｅｓ

● [1:27:35]. Absolute value theorem. 
     ◉ i̲f̲  limₙ→∞ |𝒂ₙ| = 0 
          ○ t̲h̲e̲n̲ limₙ→∞ 𝒂ₙ = 0

● [1:29:01]. 🧩 Example — Sequence: 𝒂ₙ = (-1)ⁿ/𝒏. 
     ◉ Absolute value:
          ○ |(-1)ⁿ/𝒏| = 1/𝒏
     ◉ Since
          ○ 1/𝒏 → 0,
               ■ it follows that (-1)ⁿ/𝒏 → 0
     ◉ Conclusion:
          ○ the sequence converges




          

Ｃｏｎｔｉｎｕｏｕｓ　Ｆｕｎｃｔｉｏｎｓ　＆　Ｓｅｑｕｅｎｃｅ　Ｌｉｍｉｔｓ

● [1:31:10]. Limit of sequences inside continuous functions. 
     ◉  i̲f̲  𝒇 is continuous and limₙ→∞ 𝒂ₙ = L 
          ○ t̲h̲e̲n̲ limₙ→∞ 𝒇(𝒂ₙ) = 𝒇(limₙ→∞ 𝒂ₙ) = 𝒇(L) 
     ◉ Idea:
          ○ if a sequence aₙ approaches a number L, and 𝒇 is continuous, then you can “bring the limit inside the function.”


● [1:33:49]. 🧩 Example — Sequence:  e^sin(1/n). 
     ◉ Apply the theorem:
          ○ i̲f̲  𝒇 is continuous and limₙ→∞ 𝒂ₙ = 𝑳
               ■ t̲h̲e̲n̲ limₙ→∞ 𝒇(𝒂ₙ) = 𝒇(limₙ→∞ 𝒂ₙ) = 𝒇(𝑳)
     ◉ Identify the parts:
          ○ 𝒇(𝒙) = eˣ
          ○ 𝒂ₙ = sin(1/n)
          ○ 𝒇(𝒂ₙ) = e^sin(1/n)
     ◉ Since
          ○ 1/n → 0
          ○ sin(1/n) → sin(0) = 0
               ■ so limₙ→∞ 𝒂ₙ = 0
     ◉ Substitute into the theorem:
          ○ limₙ→∞ 𝒇(𝒂ₙ)           =   𝒇(limₙ→∞ 𝒂ₙ)            =  𝒇(𝑳)
          ○ limₙ→∞  e^sin(1/n)  =   e^(limₙ→∞ sin(1/n))  =  𝒇(0) = e⁰ = 1
     ◉ Conclusion:
          ○ the sequence converges to 1

● [1:36:02]. 🧩 Example — Sequence: tan⁻¹(𝒏²). 
     ◉ Apply the theorem:
          ○ i̲f̲  𝒇 is continuous and limₙ→∞ 𝒂ₙ = 𝑳
               ■ t̲h̲e̲n̲ limₙ→∞ 𝒇(𝒂ₙ) = 𝒇(limₙ→∞ 𝒂ₙ) = 𝒇(𝑳)
     ◉ Identify the parts:
          ○ 𝒇(𝒙) = tan⁻¹(𝒙)
          ○ 𝒂ₙ = n²
          ○ 𝒇(𝒂ₙ) = tan⁻¹(n²)
     ◉ Since
          ○ n² → ∞
               ■ so limₙ→∞ 𝒂ₙ = ∞
               ■ hence 𝑳 = ∞
     ◉ Substitute into the theorem:
          ○ limₙ→∞ 𝒇(𝒂ₙ) = 𝒇(limₙ→∞ 𝒂ₙ) = 𝒇(𝑳)
          ○ limₙ→∞ tan⁻¹(n²) = tan⁻¹(limₙ→∞ n²) = 𝒇(∞) = tan⁻¹(∞) = π/2
     ◉ Conclusion:
          ○ the sequence converges to π/2




               

Ｍｏｎｏｔｏｎｉｃ　Ｓｅｑｕｅｎｃｅｓ

● [1:37:58]. Monotonic sequences. 
     ◉ A monotonic sequence is one that is always:
          ○ increasing
          ○ or decreasing

● Ways to **prove** monotonicity.
     ◉ Method 1:
          ○ compare 𝒂ₙ and 𝒂ₙ₊₁ directly
          ○ To prove increasing:
               ■ show 𝒂ₙ ≤ 𝒂ₙ₊₁
          ○ To prove decreasing:
               ■ show 𝒂ₙ₊₁ ≤ 𝒂ₙ
     ◉ Method 2:
          ○ Use the derivative of an associated function,
               ■ associate the sequence with a function 𝒇(𝒙)
          ○ **First, look at where the sequence starts.**
          ○ **Then use that to determine the relevant domain of the associated function.**
          ○ Next, check the sign of 𝒇′(𝒙) on that domain.
          ○ If you prove that 𝒇 is increasing on the interval containing all those n-values,
               ■ then the sequence is also increasing.
          ○ i̲f̲ 𝒇′(𝒙) > 0 on the relevant domain,
               ■ t̲h̲e̲n̲ the sequence is increasing
          ○ i̲f̲ 𝒇′(𝒙) < 0 on the relevant domain,
               ■ t̲h̲e̲n̲ the sequence is decreasing

● [1:41:10 ]. 🧩 Example — Show that 𝒂ₙ = 𝒏/(𝒏 + 1) is increasing. 
     ◉ Method 1 — Compare consecutive terms.
          ○ To show that the sequence is increasing, it is enough to prove that
               ■ aₙ ≤ aₙ₊₁
          ○ So show that
               ■ n/(n + 1) ≤ (n + 1)/(n + 2)
          ○ Cross-multiply:
               ■ n(n + 2) ≤ (n + 1)(n + 1)
          ○ Expand both sides:
               ■ n² + 2n ≤ n² + 2n + 1
          ○ This is true for all n ≥ 1.
          ○ Therefore
               ■ aₙ is increasing
     ◉ [1:47:42]. Method 2 — Use the associated function.
          ○ Define
               ■ 𝒇(𝒙) = x/(x + 1)
          ○ Differentiate:
               ■ 𝒇′(𝒙) = [(x + 1) - x]/(x + 1)²
               ■ 𝒇′(𝒙) = 1/(x + 1)²
          ○ The relevant domain is determined by the sequence.
               ■ Since the sequence is defined for n ≥ 1, we check 𝒇′(𝒙) on x ≥ 1.
          ○ Since
               ■ 𝒇′(𝒙) ≥ 0 for x ≥ 1,
          ○ it follows that
               ■ 𝒇 is increasing on [1, ∞)
          ○ Because the sequence uses the inputs n = 1, 2, 3, ...
               ■ aₙ = 𝒇(n) also increases
          ○ Therefore:
               ■ i̲f̲ 𝒇′(𝒙) > 0 on the relevant domain,
                    ▣ t̲h̲e̲n̲ the sequence is increasing
                    ▣ the sequence aₙ = n/(n + 1) is increasing

     
● [1:55:01]. 🧩 Example — Analyze 𝒇(𝒙) = 𝒙/eˣ. 
     ◉ Associate the sequence with the function:
          ○ 𝒂ₙ = n/eⁿ
          ○ 𝒇(𝒙) = 𝒙/eˣ
     ◉ Relevant domain:
          ○ Since the sequence starts at n = 1,
               ■ we study 𝒇(𝒙) on [1, ∞)
     ◉ Derivative:
          ○ 𝒇′(𝒙) = (1 - 𝒙)/eˣ
     ◉ Sign of the derivative on the relevant domain:
          ○ Since eˣ > 0 for every 𝒙,
               ■ the sign of 𝒇′(𝒙) depends only on 1 - 𝒙
          ○ If 𝒙 ≥ 1, then 1 - 𝒙 ≤ 0
          ○ Therefore 𝒇′(𝒙) ≤ 0 for 𝒙 ≥ 1
     ◉ Conclusion:
          ○ i̲f̲ 𝒇′(𝒙) < 0 on the relevant domain,
               ■ t̲h̲e̲n̲ the sequence is decreasing
               ■ 𝒇 is decreasing on [1, ∞)
          ○ therefore the associated sequence {n/eⁿ} is decreasing




          

Ｂｏｕｎｄｅｄ　Ｓｅｑｕｅｎｃｅｓ

● [2:00:11]. Bounded sequences. 
     ◉ Bounded above:
          ○ 𝒂ₙ ≤ 𝑴
     ◉ Bounded below:
          ○ 𝒂ₙ ≥ 𝒎
     ◉ Bounded:
          ○ 𝒎 ≤ 𝒂ₙ ≤ 𝑴




          

Ｍｏｎｏｔｏｎｉｃ　Ｓｅｑｕｅｎｃｅ　Ｔｈｅｏｒｅｍ

● [2:03:45]. Monotonic Sequence Theorem.
     ◉ If a sequence is monotonic and bounded,
          ○ then it converges
     ◉ More specifically:
          ○ increasing + bounded above ⇒ convergent
          ○ decreasing + bounded below ⇒ convergent

● [2:08:44]. 🧩 Example — Show that 𝒂ₙ = 2ⁿ/𝒏! is convergent. 
     ◉ If we write out some terms, it appears that the sequence is decreasing.
     ◉ [2:11:05]. To determine whether a sequence is monotonic:
          ○ Decreasing sequence:
               ■ 𝒂ₙ ≥ 𝒂ₙ₊₁
               ■ equivalently, 𝒂ₙ₊₁ ≤ 𝒂ₙ
               ■ if the sequence is positive, equivalently, 𝒂ₙ₊₁/𝒂ₙ ≤ 1
     ◉ [2:13:05]. Determine whether 𝒂ₙ = 2ⁿ/𝒏! is decreasing:
          ○ 𝒂ₙ₊₁/𝒂ₙ = (2ⁿ⁺¹/(n + 1)!)/(2ⁿ/n!)
          ○ 𝒂ₙ₊₁/𝒂ₙ = (2ⁿ⁺¹/(n + 1)!) · (n!/2ⁿ)
          ○ 𝒂ₙ₊₁/𝒂ₙ = (2 · 2ⁿ/((n + 1) · n!)) · (n!/2ⁿ)
          ○ 𝒂ₙ₊₁/𝒂ₙ = 2/(n + 1)
          ○ 2/(n + 1) ≤ 1
               ■ true for n ≥ 1
          ○ Result:
               ■ the sequence is decreasing
     ◉ [2:20:24]. Also:
          ○ Since 𝒂ₙ = 2ⁿ/𝒏! cannot be negative,
               ■ it must be bounded below by 0
               ■ 𝒂ₙ is always positive
     ◉ By the Monotonic Sequence Theorem:
          ○ decreasing + bounded below ⇒ convergent
          ○ therefore the sequence is convergent




          

Ｇｅｏｍｅｔｒｉｃ　Ｓｅｑｕｅｎｃｅｓ　𝒓ⁿ

● [2:23:45]. Summary for geometric sequences 𝒓ⁿ. 
     ◉ If -1 < 𝒓 < 1,
          ○ then 𝒓ⁿ → 0
          ○ if 0 < 𝒓 < 1,
               ■ the terms stay positive and approach 0
          ○ if -1 < 𝒓 < 0,
               ■ the terms alternate in sign and approach 0
     ◉ If 𝒓 = 1,
          ○ then 𝒓ⁿ → 1
     ◉ If 𝒓 = -1,
          ○ the sequence oscillates and diverges
     ◉ If |𝒓| > 1,
          ○ the sequence diverges
          ○ if 𝒓 > 1,
               ■ the terms grow without bound
          ○ if 𝒓 < -1,
               ■ the terms alternate in sign and their magnitudes grow without bound
          ○ NOTE:  
               ■ First define the absolute value:
                    ▣ |𝒓| = 𝒓,   if 𝒓 ≥ 0
                    ▣ |𝒓| = -𝒓,  if 𝒓 < 0
               ■ Then solve |𝒓| > 1 by cases:
                    ▣ If 𝒓 ≥ 0, then |𝒓| = 𝒓
                         ▢ so 𝒓 > 1
                    ▣ If 𝒓 < 0, then |𝒓| = -𝒓
                         ▢ so -𝒓 > 1
                         ▢ therefore 𝒓 < -1
               ■ Conclusion:
                    ▣ |𝒓| > 1 means 𝒓 > 1 or 𝒓 < -1
     ◉ Therefore:
          ○ **the sequence {𝒓ⁿ} converges if and only if -1 < 𝒓 ≤ 1**





Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Sequences
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/5-1-sequences)