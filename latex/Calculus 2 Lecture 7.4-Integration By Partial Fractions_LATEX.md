-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ７．４ - Ｉｎｔｅｇｒａｔｉｏｎ Ｂｙ Ｐａｒｔｉａｌ Ｆｒａｃｔｉｏｎｓ**---------------------------------




Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:00](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=0). Introduction to Section 7.4: Partial Fractions.
     ◉ Guiding question:
          ○ How to integrate rational functions that do not fit directly into substitution, integration by parts, or trig substitution.
     ◉ Central idea:
          ○ Take one complicated rational fraction and decompose it into simpler fractions.
     ◉ Key observation:
          ○ The decomposition depends on the type of factors that appear in the denominator.





          

Ａｌｇｅｂｒａｉｃ　Ｆｏｕｎｄａｔｉｏｎｓ

● [📷image](../img/Calculus 2 Lecture 7.4/[1-07]-01.png)

● [1:07](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=67). Two algebra rules that justify the method: “The how”
     ◉ [1:22](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=82). Rule 1 — Polynomial factorization.
          ○ Every polynomial can be factored as a product of:
               ■ linear factors: $𝒂𝒙+𝒃$
               ■ and/or irreducible quadratic factors: $𝒂𝒙^{2}+𝒃𝒙+𝒄$
                    ▣ Some quadratics cannot be factored over the reals/rationals because their roots are complex.
     ◉ [4:15](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=255). Rule 2 — Proper rational functions.
          ○ If every rational function $𝑹(𝒙)/𝑸(𝒙)$ satisfies
               ■ $degree(𝑹)<degree(𝑸)$,
          ○ then it can be decomposed into partial fractions.

● [5:41](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=341). Clarification of preliminary concepts using the introductory example.
$\rule{0pt}{}$
     ◉ 🧩 Example 1 — Evaluate $\displaystyle \int \dfrac{4x^{2}-4x+6}{x^{3}-x^{2}-6x}\,dx$.
     $\rule{0pt}{}$
     ◉ What “polynomial” means.
     ◉ What “rational function” means.
     ◉ What the degree of the numerator and denominator means.
          ○ The degree of $𝑹(𝒙)=4x^{2}-4x+6$ is $2$.
          ○ The degree of $𝑸(𝒙)=x^{3}-x^{2}-6x$ is $3$.
          ○ So $degree(𝑹)<degree(𝑸)$, and partial fraction decomposition is possible.
     ◉ [6:18](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=378). Criterion for improper rational functions.
          ○ If $degree(𝑹)\ge degree(𝑸)$,
          ○ then
               ■ first perform polynomial long division,
               ■ and then apply partial fractions to the proper remainder.

● [6:57](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=417). Note on division.
     ◉ There is no “magic shortcut” different from long division.
     ◉ Synthetic division only counts as a shortened version when it genuinely applies.





     

Ｃａｓｅ　１　—　Ｄｉｓｔｉｎｃｔ　Ｌｉｎｅａｒ　Ｆａｃｔｏｒｓ

● [8:14](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=494). Case 1: **Distinct** linear factors. [📷image](../img/Calculus 2 Lecture 7.4/[8-14]-01.png)
     ◉ Definition.
          ○ Linear factors are **distinct** when none of them repeats.
          ○ Example of distinct factors:
               ■ $(𝒙+1)(𝒙-1)(𝒙+4)$
          ○ Example of non-distinct factors:
               ■ $(𝒙+1)^{2}(𝒙-4)$
     ◉ Decomposition rule.
          ○ If the denominator has distinct linear factors,
               ■ write one fraction for each linear factor.
     ◉ General model.
          $\rule{0pt}{}$
          ○ $𝑹(𝒙)/𝑸(𝒙)=\dfrac{𝑨}{𝒂_{1}𝒙+𝒃_{1}}+\dfrac{𝑩}{𝒂_{2}𝒙+𝒃_{2}}+\cdots$
          $\rule{0pt}{}$
     ◉ Rule for the numerators.
          ○ For linear factors, the numerators are constants.          

● [11:20](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=680). 🧩 Example 1 — Distinct linear factors: $\displaystyle \int \dfrac{4𝒙^{2}-4𝒙+6}{𝒙^{3}-𝒙^{2}-6𝒙}\,𝒅𝒙$. [📷image-1](../img/Calculus 2 Lecture 7.4/[11-20]-01.png) [📷image-2](../img/Calculus 2 Lecture 7.4/[11-20]-02.png)
     ◉ First step:
          ○ Ignore the numerator for the moment and factor the denominator completely.
     ◉ Complete factorization of the denominator.
          $\rule{0pt}{}$
          ○ $𝒙^{3}-𝒙^{2}-6𝒙=𝒙(𝒙^{2}-𝒙-6)$
          $\rule{0pt}{}$
          ○ $=𝒙(𝒙-3)(𝒙+2)$
     ◉ Identification of the factor type.
          ○ There are three factors.
          ○ All are linear.
          ○ All are distinct.
     ◉ Setup of the decomposition.
          $\rule{0pt}{}$
          ○ $\dfrac{4𝒙^{2}-4𝒙+6}{𝒙(𝒙-3)(𝒙+2)}=\dfrac{𝑨}{𝒙}+\dfrac{𝑩}{𝒙-3}+\dfrac{𝑪}{𝒙+2}$
          $\rule{0pt}{}$
     ◉ Common-denominator idea.
          ○ Once everything is written over the same denominator,
               ■ the numerators must match.
     ◉ “Cover-up” method to build the common numerator.
          ○ Each fraction is multiplied by the factors it is missing.
          $\rule{0pt}{}$
          ○ $\dfrac{𝑨}{𝒙}$ contributes $𝑨(𝒙-3)(𝒙+2)$
          $\rule{0pt}{}$
          ○ $\dfrac{𝑩}{𝒙-3}$ contributes $𝑩𝒙(𝒙+2)$
          $\rule{0pt}{}$
          ○ $\dfrac{𝑪}{𝒙+2}$ contributes $𝑪𝒙(𝒙-3)$
          $\rule{0pt}{}$
     ◉ Equality of numerators.
          $\rule{0pt}{}$
          ○ $4𝒙^{2}-4𝒙+6=𝑨(𝒙-3)(𝒙+2)+𝑩𝒙(𝒙+2)+𝑪𝒙(𝒙-3)$
          $\rule{0pt}{}$
     ◉ Distribution and regrouping of terms.
          $\rule{0pt}{}$
          ○ $4𝒙^{2}-4𝒙+6=(𝑨𝒙^{2}-𝑨𝒙-6𝑨)+(𝑩𝒙^{2}+2𝑩𝒙)+(𝑪𝒙^{2}-3𝑪𝒙)$
          $\rule{0pt}{}$
          ○ $4𝒙^{2}-4𝒙+6=(𝑨+𝑩+𝑪)𝒙^{2}+(-𝑨+2𝑩-3𝑪)𝒙-6𝑨$
          $\rule{0pt}{}$
     ◉ Comparison of coefficients.
          $\rule{0pt}{}$
          ○ $4=𝑨+𝑩+𝑪$
          $\rule{0pt}{}$
          ○ $-4=-𝑨+2𝑩-3𝑪$
          $\rule{0pt}{}$
          ○ $6=-6𝑨$
     ◉ Solving the system.
          ○ From $6=-6𝑨$, we get:
               $\rule{0pt}{}$
               ■ $𝑨=-1$
          ○ Substitute $𝑨=-1$ into the first equation:
               $\rule{0pt}{}$
               ■ $4=-1+𝑩+𝑪$
               ■ $5=𝑩+𝑪$
          ○ Substitute $𝑨=-1$ into the second equation:
               $\rule{0pt}{}$
               ■ $-4=1+2𝑩-3𝑪$
               ■ $-5=2𝑩-3𝑪$
          ○ Solve the remaining two-equation system:
               $\rule{0pt}{}$
               ■ $5=𝑩+𝑪$
               ■ $-5=2𝑩-3𝑪$
          ○ Multiply the first equation by $2$:
               $\rule{0pt}{}$
               ■ $10=2𝑩+2𝑪$
          ○ Subtract the second equation:
               $\rule{0pt}{}$
               ■ $15=5𝑪$
               ■ $𝑪=3$
          ○ Back-substitute into $5=𝑩+𝑪$:
               $\rule{0pt}{}$
               ■ $5=𝑩+3$
               ■ $𝑩=2$
     ◉ Coefficients obtained.
          ○ $𝑨=-1$
          ○ $𝑩=2$
          ○ $𝑪=3$
     ◉ [31:31](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=1891). Rewriting the integral.
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{4𝒙^{2}-4𝒙+6}{𝒙^{3}-𝒙^{2}-6𝒙}\,𝒅𝒙=\displaystyle \int \left[-\dfrac{1}{𝒙}+\dfrac{2}{𝒙-3}+\dfrac{3}{𝒙+2}\right]\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Important observation.
          ○ With linear factors, the final integration produces a sum of logarithms.
     ◉ Final integration.
          $\rule{0pt}{}$
          ○ $-\ln|𝒙|+2\ln|𝒙-3|+3\ln|𝒙+2|+𝑪$
     ◉ Warning about coefficients.
          ○ If the denominator were something like $2𝒙-3$, the extra derivative factor would have to be taken into account when integrating.

● [37:39](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=2259). Shortcut for distinct linear factors. [📷image](../img/Calculus 2 Lecture 7.4/[37-39]-01.png)
     ◉ 🧩 Example 1 — Distinct linear factors: $\displaystyle \int \dfrac{4𝒙^{2}-4𝒙+6}{𝒙^{3}-𝒙^{2}-6𝒙}\,𝒅𝒙$
     ◉ Instead of distributing everything,
          ○ substitute values of $𝒙$ that make specific factors zero.
     ◉ Start from the numerator identity:
          $\rule{0pt}{}$
          ○ $4𝒙^{2}-4𝒙+6=𝑨(𝒙-3)(𝒙+2)+𝑩𝒙(𝒙+2)+𝑪𝒙(𝒙-3)$
     ◉ With $𝒙=0$:
          $\rule{0pt}{}$
          ○ $6=𝑨(-3)(2)$
          $\rule{0pt}{}$
          ○ $6=-6𝑨$
          $\rule{0pt}{}$
          ○ $𝑨=-1$
     ◉ With $𝒙=3$:
          $\rule{0pt}{}$
          ○ $30=𝑩\cdot 3\cdot 5$
          $\rule{0pt}{}$
          ○ $30=15𝑩$
          $\rule{0pt}{}$
          ○ $𝑩=2$
     ◉ With $𝒙=-2$:
          $\rule{0pt}{}$
          ○ $30=𝑪(-2)(-5)$
          $\rule{0pt}{}$
          ○ $30=10𝑪$
          $\rule{0pt}{}$
          ○ $𝑪=3$
     ◉ Coefficients obtained by the shortcut.
          ○ $𝑨=-1$
          ○ $𝑩=2$
          ○ $𝑪=3$
     ◉ Rewritten partial-fraction form.
          $\rule{0pt}{}$
          ○ $-\dfrac{1}{𝒙}+\dfrac{2}{𝒙-3}+\dfrac{3}{𝒙+2}$
          $\rule{0pt}{}$
     ◉ Advantage of the shortcut.
          ○ It is much faster when all factors are linear and distinct.
          ○ It avoids distributing and solving the full coefficient-comparison system.
     ◉ Limitation.
          ○ It does not work as well with irreducible quadratics,
               ■ because you cannot usually make them zero with simple real values.

● [45:10](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=2710). 🧩 Example 2 — Long division first: $\displaystyle \int \dfrac{𝒙^{4}-3𝒙^{2}-3𝒙-2}{𝒙^{3}-𝒙^{2}-2𝒙}\,𝒅𝒙$. [📷image-1](../img/Calculus 2 Lecture 7.4/[45-10]-01.png) [📷image-2](../img/Calculus 2 Lecture 7.4/[45-10]-02.png) [📷image-3](../img/Calculus 2 Lecture 7.4/[45-10]-03.png)
     ◉ Difference from the previous example.
          ○ The degree of the numerator is greater than the degree of the denominator.
     ◉ Consequence.
          ○ **Long division must be done first**.
     ◉ Beginning of polynomial long division.
          ○ Rewrite the numerator with a placeholder term:
               ■ $𝒙^{4}+0𝒙^{3}-3𝒙^{2}-3𝒙-2$
     ◉ Use of placeholders.
          ○ Insert $0𝒙^{3}$ so no powers of $𝒙$ are skipped during the division.
     ◉ Long-division steps.
          ○ First quotient term:
               ■ $𝒙^{4}\div 𝒙^{3}=𝒙$
          ○ Multiply back:
               ■ $𝒙(𝒙^{3}-𝒙^{2}-2𝒙)=𝒙^{4}-𝒙^{3}-2𝒙^{2}$
          ○ Subtract and simplify:
               $\rule{0pt}{}$
               ■ $(𝒙^{4}+0𝒙^{3}-3𝒙^{2}-3𝒙-2)-(𝒙^{4}-𝒙^{3}-2𝒙^{2})$
               $\rule{0pt}{}$
               ■ $=𝒙^{3}-𝒙^{2}-3𝒙-2$
          ○ Second quotient term:
          $\rule{0pt}{}$
               ■ $𝒙^{3}\div 𝒙^{3}=1$
               $\rule{0pt}{}$
          ○ Multiply back again:
          $\rule{0pt}{}$
               ■ $1(𝒙^{3}-𝒙^{2}-2𝒙)=𝒙^{3}-𝒙^{2}-2𝒙$
               $\rule{0pt}{}$
          ○ Subtract and simplify:
               $\rule{0pt}{}$
               ■ $(𝒙^{3}-𝒙^{2}-3𝒙-2)-(𝒙^{3}-𝒙^{2}-2𝒙)$
               $\rule{0pt}{}$
               ■ $=-𝒙-2$
     ◉ Result of the division.
          ○ Quotient:
               ■ $𝒙+1$
          ○ Remainder:
               ■ $-𝒙-2$
     ◉ Correct form of the result.
          $\rule{0pt}{}$
          ○ $\dfrac{𝒙^{4}-3𝒙^{2}-3𝒙-2}{𝒙^{3}-𝒙^{2}-2𝒙}$
          $\rule{0pt}{}$
          ○ $=𝒙+1+\dfrac{-𝒙-2}{𝒙^{3}-𝒙^{2}-2𝒙}$
          $\rule{0pt}{}$
     ◉ Care with the sign of the remainder.
          ○ It is convenient to factor out the negative sign:
          $\rule{0pt}{}$
               ■ $𝒙+1-\dfrac{𝒙+2}{𝒙^{3}-𝒙^{2}-2𝒙}$
               $\rule{0pt}{}$
          ○ The instructor isolates this rational piece first before decomposing it.
     ◉ Factorization of the denominator in the remainder.
          $\rule{0pt}{}$
          ○ $𝒙^{3}-𝒙^{2}-2𝒙=𝒙(𝒙^{2}-𝒙-2)$
          $\rule{0pt}{}$
          ○ $=𝒙(𝒙-2)(𝒙+1)$
          $\rule{0pt}{}$
     ◉ Now the remaining rational part is proper.
     ◉ New partial-fraction decomposition.
          $\rule{0pt}{}$
          ○ $\dfrac{𝒙+2}{𝒙(𝒙-2)(𝒙+1)}=\dfrac{𝑨}{𝒙}+\dfrac{𝑩}{𝒙-2}+\dfrac{𝑪}{𝒙+1}$
          $\rule{0pt}{}$
     ◉ Equality of numerators.
          $\rule{0pt}{}$
          ○ $𝒙+2=𝑨(𝒙-2)(𝒙+1)+𝑩𝒙(𝒙+1)+𝑪𝒙(𝒙-2)$
          $\rule{0pt}{}$
     ◉ Quick solution by substituting roots.
          ○ With $𝒙=0$:
               $\rule{0pt}{}$
               ■ $2=𝑨(-2)(1)$
               ■ $2=-2𝑨$
               ■ $𝑨=-1$
               $\rule{0pt}{}$
          ○ With $𝒙=2$:
               $\rule{0pt}{}$
               ■ $4=𝑩(2)(3)$
               ■ $4=6𝑩$
               ■ $𝑩=\dfrac{2}{3}$
               $\rule{0pt}{}$
          ○ With $𝒙=-1$:
               $\rule{0pt}{}$
               ■ $1=𝑪(-1)(-3)$
               ■ $1=3𝑪$
               ■ $𝑪=\dfrac{1}{3}$
               $\rule{0pt}{}$
     ◉ Rewriting the full integral.
          $\rule{0pt}{}$
          ○ $\displaystyle \int \left[𝒙+1-\left(-\dfrac{1}{𝒙}+\dfrac{\dfrac{2}{3}}{𝒙-2}+\dfrac{\dfrac{1}{3}}{𝒙+1}\right)\right]\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $=\displaystyle \int \left[𝒙+1+\dfrac{1}{𝒙}-\dfrac{\dfrac{2}{3}}{𝒙-2}-\dfrac{\dfrac{1}{3}}{𝒙+1}\right]\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Final integration by simple pieces.
          ○ Direct integration of the polynomial part:
               $\rule{0pt}{}$
               ■ $\displaystyle \int (𝒙+1)\,𝒅𝒙=\dfrac{1}{2}𝒙^{2}+𝒙$
               $\rule{0pt}{}$
          ○ Logarithmic terms:
               $\rule{0pt}{}$
               ■ $\displaystyle \int \dfrac{1}{𝒙}\,𝒅𝒙=\ln|𝒙|$
               $\rule{0pt}{}$
               ■ $\displaystyle \int \dfrac{\dfrac{2}{3}}{𝒙-2}\,𝒅𝒙=\dfrac{2}{3}\ln|𝒙-2|$
               $\rule{0pt}{}$
               ■ $\displaystyle \int \dfrac{\dfrac{1}{3}}{𝒙+1}\,𝒅𝒙=\dfrac{1}{3}\ln|𝒙+1|$
               $\rule{0pt}{}$
     ◉ Final result.
          $\rule{0pt}{}$
          ○ $\dfrac{1}{2}𝒙^{2}+𝒙+\ln|𝒙|-\dfrac{2}{3}\ln|𝒙-2|-\dfrac{1}{3}\ln|𝒙+1|+𝑪$




          
          
Ｃａｓｅ　２　—　Ｒｅｐｅａｔｅｄ　Ｌｉｎｅａｒ　Ｆａｃｔｏｒｓ

● [1:05:05](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=3905). 🧩 Example 3 —  Transition to case 2, repeated linear factor: $\displaystyle \int \dfrac{2𝒙^{2}+3𝒙+7}{𝒙^{3}+𝒙^{2}-𝒙-1}\,𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.4/[1-05-05]-01.png)
     ◉ First step:
          ○ factor the denominator.
     ◉ Factorization by grouping.
          $\rule{0pt}{}$
          ○ $𝒙^{3}+𝒙^{2}-𝒙-1$
          $\rule{0pt}{}$
          ○ $=𝒙^{2}(𝒙+1)-1(𝒙+1)$
          $\rule{0pt}{}$
          ○ $=(𝒙+1)(𝒙^{2}-1)$
          $\rule{0pt}{}$
          ○ $=(𝒙-1)(𝒙+1)^{2}$
          $\rule{0pt}{}$
     ◉ Recognition of the new case.
          ○ A repeated linear factor appears.

● [1:10:23](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=4223). Case 2: Repeated linear factors.  [📷image](../img/Calculus 2 Lecture 7.4/[1-10-23]-01.png)
     ◉ If a linear factor is repeated,
          ○ a fraction must be included for each power up to the highest one.
     ◉ General model.
          $\rule{0pt}{}$
          ○ $\dfrac{𝑨_{1}}{(𝒙-𝒂)}+\dfrac{𝑨_{2}}{(𝒙-𝒂)^{2}}+\cdots+\dfrac{𝑨_{n}}{(𝒙-𝒂)^{n}}$

● [1:11:19](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=4279).🧩 Continue Example 3 — Transition to case 2: $\displaystyle \int \dfrac{2𝒙^{2}+3𝒙+7}{𝒙^{3}+𝒙^{2}-𝒙-1}\,𝒅𝒙$ [📷image](../img/Calculus 2 Lecture 7.4/[1-11-19]-01.png)
     ◉ Application to 🧩 Example 3.
          $\rule{0pt}{}$
          ○ $\dfrac{𝑨}{𝒙-1}+\dfrac{𝑩}{𝒙+1}+\dfrac{𝑪}{(𝒙+1)^{2}}$
          $\rule{0pt}{}$
     ◉ Construction of the common denominator.
          ○ The highest necessary power of the repeated factor is used.
     ◉ [1:10:23](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=4223). What would happen if the denominator also contained $𝒙^{3}$? [📷image](../img/Calculus 2 Lecture 7.4/[1-10-23]-02.png)
          ○ Then $𝒙^{3}$ would count as another repeated linear factor.
          ○ You would need one fraction for each power:
               $\rule{0pt}{}$
               ■ $\dfrac{𝑫}{𝒙}+\dfrac{𝑬}{𝒙^{2}}+\dfrac{𝑭}{𝒙^{3}}$
               $\rule{0pt}{}$
          ○ So the setup would become:
               $\rule{0pt}{}$
               ■ $\dfrac{𝑨}{𝒙-1}+\dfrac{𝑩}{𝒙+1}+\dfrac{𝑪}{(𝒙+1)^{2}}+\dfrac{𝑫}{𝒙}+\dfrac{𝑬}{𝒙^{2}}+\dfrac{𝑭}{𝒙^{3}}$
               $\rule{0pt}{}$
     ◉ The shortcut still works partially.
          ○ $𝒙=1$ and $𝒙=-1$ can be used to isolate some constants.
     ◉ Coefficients obtained from the repeated-factor setup.
          ○ With $𝒙=1$:
               $\rule{0pt}{}$
               ■ $12=𝑨(2)^{2}$
               ■ $𝑨=3$
               $\rule{0pt}{}$
          ○ With $𝒙=-1$:
               $\rule{0pt}{}$
               ■ $6=𝑪(-2)$
               ■ $𝑪=-3$
               $\rule{0pt}{}$
     ◉ Use of an additional value to find the remaining constant.
          ○ Taking $𝒙=0$:
               $\rule{0pt}{}$
               ■ $7=𝑨-𝑩-𝑪$
               ■ $7=3-𝑩+3$
               ■ $𝑩=-1$
               $\rule{0pt}{}$
     ◉ Rewriting the integral.
          $\rule{0pt}{}$
          ○ $\displaystyle \int \left[\dfrac{3}{𝒙-1}-\dfrac{1}{𝒙+1}-\dfrac{3}{(𝒙+1)^{2}}\right]\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Integration of the repeated term.
     $\rule{0pt}{}$
          ○ $-\dfrac{3}{(𝒙+1)^{2}}$ is integrated with the power rule, not with $\ln$.
          $\rule{0pt}{}$
          ○ Let $𝒖=𝒙+1$, then:
               $\rule{0pt}{}$
               ■ $\displaystyle \int \dfrac{3}{(𝒙+1)^{2}}\,𝒅𝒙=3\int (𝒙+1)^{-2}\,𝒅𝒙=-\dfrac{3}{𝒙+1}$
               $\rule{0pt}{}$
          ○ Because the term in the integral is subtracted,
               ■ the final contribution becomes $+\dfrac{3}{𝒙+1}$
     ◉ Result.
          $\rule{0pt}{}$
          ○ $3\ln|𝒙-1|-\ln|𝒙+1|+\dfrac{3}{𝒙+1}+𝑪$
          $\rule{0pt}{}$
     ◉ Additional comment.
          ○ The logarithmic part can also be combined as:
          $\rule{0pt}{}$
               ■ $\ln\left|\dfrac{(𝒙-1)^{3}}{𝒙+1}\right|+\dfrac{3}{𝒙+1}+𝑪$



          


       

Ｃａｓｅ　３　—　Ｉｒｒｅｄｕｃｉｂｌｅ　Ｑｕａｄｒａｔｉｃ　Ｆａｃｔｏｒｓ

● [1:31:31](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=5491). 🧩 Example 4 — Transition to case 3: $\displaystyle \int \dfrac{𝒙^{2}-𝒙-21}{2𝒙^{3}-𝒙^{2}+8𝒙-4}\,𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.4/[1-31-31]-01.png)
     ◉ Exam-style approach.
          ○ First check whether it fits a simpler method.
          ○ Then verify the degree.
          ○ Then factor.
     ◉ Factorization of the denominator.
          $\rule{0pt}{}$
          ○ $2𝒙^{3}-𝒙^{2}+8𝒙-4=(2𝒙-1)(𝒙^{2}+4)$
          $\rule{0pt}{}$
     ◉ Recognition of an irreducible quadratic.
          ○ $𝒙^{2}+4$ does not factor over the reals.

● [1:35:11](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=5711). Case 3: Irreducible quadratic factors. [📷image](../img/Calculus 2 Lecture 7.4/[1-35-11]-01.png)
     ◉ General rule.
          ○ Each irreducible quadratic gets a linear numerator.
     ◉ Degree rule.
          ○ The numerator must have degree one less than the denominator factor.
          
● [1:36:54](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=5814).🧩 Continue Example 4 — Transition to case 3 $\displaystyle \int \dfrac{𝒙^{2}-𝒙-21}{2𝒙^{3}-𝒙^{2}+8𝒙-4}\,𝒅𝒙$.  [📷image-1](../img/Calculus 2 Lecture 7.4/[1-36-54]-01.png) [📷image-2](../img/Calculus 2 Lecture 7.4/[1-36-54]-02.png) [📷image-3](../img/Calculus 2 Lecture 7.4/[1-36-54]-03.png)
     ◉ Application to the example.
          $\rule{0pt}{}$
          ○ $\dfrac{𝑨}{2𝒙-1}+\dfrac{𝑩𝒙+𝑪}{𝒙^{2}+4}$
          $\rule{0pt}{}$
     ◉ Construction of the common denominator.
          $\rule{0pt}{}$
          ○ $𝒙^{2}-𝒙-21=𝑨(𝒙^{2}+4)+(𝑩𝒙+𝑪)(2𝒙-1)$
          $\rule{0pt}{}$
     ◉ In this case the shortcut does not solve everything.
          ○ You may try some simple value,
          ○ but in the end you must distribute and compare coefficients.
     ◉ Regrouping by powers of $𝒙$.
          $\rule{0pt}{}$
          ○ $𝒙^{2}-𝒙-21=(𝑨+2𝑩)𝒙^{2}+(-𝑩+2𝑪)𝒙+(4𝑨-𝑪)$
          $\rule{0pt}{}$
     ◉ Comparison of coefficients.
          $\rule{0pt}{}$
          ○ $𝑨+2𝑩=1$
          $\rule{0pt}{}$
          ○ $-𝑩+2𝑪=-1$
          $\rule{0pt}{}$
          ○ $4𝑨-𝑪=-21$
          $\rule{0pt}{}$
     ◉ Final coefficients.
          ○ $𝑨=-5$
          ○ $𝑩=3$
          ○ $𝑪=1$
     ◉ Rewriting the integral.
          $\rule{0pt}{}$
          ○ $\displaystyle \int \left[-\dfrac{5}{2𝒙-1}+\dfrac{3𝒙+1}{𝒙^{2}+4}\right]\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Splitting the quadratic term.
          $\rule{0pt}{}$
          ○ $\dfrac{3𝒙+1}{𝒙^{2}+4}=\dfrac{3𝒙}{𝒙^{2}+4}+\dfrac{1}{𝒙^{2}+4}$
          $\rule{0pt}{}$
     ◉ Different techniques are used in each part:
     $\rule{0pt}{}$
          ○ $\ln$ for $-\dfrac{5}{2𝒙-1}$
          $\rule{0pt}{}$
          ○ substitution for $\dfrac{𝒙}{𝒙^{2}+4}$
          $\rule{0pt}{}$
          ○ $\tan^{-1}$ for $\dfrac{1}{𝒙^{2}+4}$
          $\rule{0pt}{}$
     ◉ Integration of the linear-factor term.
          ○ Let $𝒖=2𝒙-1$, so $𝒅𝒖=2𝒅𝒙$
          ○ Then:
               $\rule{0pt}{}$
               ■ $\displaystyle \int \dfrac{-5}{2𝒙-1}\,𝒅𝒙=-\dfrac{5}{2}\ln|2𝒙-1|$
               $\rule{0pt}{}$
     ◉ Substitution for $\dfrac{𝒙}{𝒙^{2}+4}$.
     $\rule{0pt}{}$
          ○ Let $𝒖=𝒙^{2}+4$, so $𝒅𝒖=2𝒙\,𝒅𝒙$
          ○ Then:
               $\rule{0pt}{}$
               ■ $3\displaystyle \int \dfrac{𝒙}{𝒙^{2}+4}\,𝒅𝒙=\dfrac{3}{2}\ln|𝒙^{2}+4|$
               $\rule{0pt}{}$
          ○ Since $𝒙^{2}+4>0$,
               ■ this may also be written as $\dfrac{3}{2}\ln(𝒙^{2}+4)$
               $\rule{0pt}{}$
     ◉ [1:55:48](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=6948). First method for $\displaystyle \int \dfrac{1}{𝒙^{2}+4}\,𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.4/[1-55-48]-01.png)
     $\rule{0pt}{}$
          ○ Rewrite it in a form compatible with $\tan^{-1}$.
          ○ Factor out a $4$ from the denominator:
               $\rule{0pt}{}$
               ■ $\dfrac{1}{𝒙^{2}+4}=\dfrac{1}{4\left[\left(\dfrac{𝒙}{2}\right)^{2}+1\right]}$
          ○ Hence:
               $\rule{0pt}{}$
               ■ $\displaystyle \int \dfrac{1}{𝒙^{2}+4}\,𝒅𝒙=\dfrac{1}{4}\int \dfrac{1}{\left(\dfrac{𝒙}{2}\right)^{2}+1}\,𝒅𝒙$
               $\rule{0pt}{}$
          ○ Using $𝒖=\dfrac{𝒙}{2}$, so $𝒅𝒙=2𝒅𝒖$:
               $\rule{0pt}{}$
               ■ $\displaystyle \int \dfrac{1}{𝒙^{2}+4}\,𝒅𝒙=\dfrac{1}{2}\tan^{-1}\left(\dfrac{𝒙}{2}\right)$
               $\rule{0pt}{}$
     ◉ [1:56:48](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=7008). Second method for $\displaystyle \int \dfrac{1}{𝒙^{2}+4}\,𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.4/[1-56-48]-01.png)
     $\rule{0pt}{}$
          ○ Interpret it through trig substitution.
          ○ Use:
               $\rule{0pt}{}$
               ■ $\tan(\theta)=\dfrac{𝒙}{2}$
               $\rule{0pt}{}$
               ■ $𝒙=2\tan(\theta)$
               $\rule{0pt}{}$
               ■ $𝒅𝒙=2\sec^{2}(\theta)\,𝒅\theta$
               $\rule{0pt}{}$
          ○ Then:
               $\rule{0pt}{}$
               ■ $\displaystyle \int \dfrac{1}{𝒙^{2}+4}\,𝒅𝒙=\int \dfrac{2\sec^{2}(\theta)}{4\tan^{2}(\theta)+4}\,𝒅\theta$
               $\rule{0pt}{}$
               ■ $=\dfrac{1}{2}\int \dfrac{\sec^{2}(\theta)}{\tan^{2}(\theta)+1}\,𝒅\theta$
               $\rule{0pt}{}$
               ■ $=\dfrac{1}{2}\int 1\,𝒅\theta$
               $\rule{0pt}{}$
               ■ $=\dfrac{1}{2}\theta$
               $\rule{0pt}{}$
          ○ Returning to $𝒙$:
               $\rule{0pt}{}$
               ■ $\theta=\tan^{-1}\left(\dfrac{𝒙}{2}\right)$
               ■ so the result is again $\dfrac{1}{2}\tan^{-1}\left(\dfrac{𝒙}{2}\right)$
               $\rule{0pt}{}$
     ◉ Final combined result.
          $\rule{0pt}{}$
          ○ $-\dfrac{5}{2}\ln|2𝒙-1|+\dfrac{3}{2}\ln|𝒙^{2}+4|+\dfrac{1}{2}\tan^{-1}\left(\dfrac{𝒙}{2}\right)+𝑪$
          
● [2:01:43](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=7303). 🧩 Example 4 — Explanation: $\displaystyle \int \dfrac{1}{𝒙^{2}+4}\,𝒅𝒙$. [📷image-1](../img/Calculus 2 Lecture 7.4/[2-01-43]-01.png)  [📷image-2](../img/Calculus 2 Lecture 7.4/[2-01-43]-02.png)




          

Ｃａｓｅ　４　—　Ｒｅｐｅａｔｅｄ　Ｉｒｒｅｄｕｃｉｂｌｅ　Ｑｕａｄｒａｔｉｃｓ

● [2:16:10](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=8170). Case 4: Repeated irreducible quadratics.
     ◉ If an irreducible quadratic factor is repeated,
          ○ write one fraction for each power.
     ◉ Each numerator remains linear.
     ◉ General model:
          $\rule{0pt}{}$
          ○ $\dfrac{𝑨𝒙+𝑩}{quadratic}$
          $\rule{0pt}{}$
          ○ $+\dfrac{𝑪𝒙+𝑫}{(quadratic)^{2}}$
          $\rule{0pt}{}$
          ○ $+\cdots$


● [2:17:02](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=8222). Large structural review 🧩 Example — : $\dfrac{5𝒙^{4}-3𝒙^{2}-𝒙+1}{𝒙(𝒙-1)^{2}(𝒙^{2}+1)(𝒙^{2}+𝒙+1)^{2}}$ [📷image](../img/Calculus 2 Lecture 7.4/[2-17-02]-01.png)$\rule{0pt}{}$
$\rule{0pt}{}$
     ◉ 1. Check whether the denominator can be factored any further.
          ○ In this example, the denominator is already completely factored over the reals.
     ◉ 2. Identify the types of factors in the denominator.
          ○ linear factor:
               ■ $𝒙$
          ○ repeated linear factor:
               ■ $(𝒙-1)^{2}$
          ○ irreducible quadratic factor:
               ■ $𝒙^{2}+1$
          ○ repeated irreducible quadratic factor:
               ■ $(𝒙^{2}+𝒙+1)^{2}$
     ◉ 3. Check whether the rational function is proper.
          ○ degree of the numerator = $4$
          ○ degree of the denominator = $9$
          ○ so $degree(numerator)<degree(denominator)$
          ○ therefore, no long division is needed.
     ◉ 4. General counting rule.
          ○ Write one fraction for each factor.
          ○ If a factor is repeated, include one fraction for each power up to the highest one.
          $\rule{0pt}{}$
          ○ $\dfrac{}{𝒙}+\dfrac{}{𝒙-1}+\dfrac{}{(𝒙-1)^{2}}+\dfrac{}{𝒙^{2}+1}+\dfrac{}{𝒙^{2}+𝒙+1}+\dfrac{}{(𝒙^{2}+𝒙+1)^{2}}$
          $\rule{0pt}{}$
     ◉ 5. General rule for the numerators.
          ○ Use constants for linear factors.
          ○ Use linear expressions for irreducible quadratic factors.
     ◉ 6. Correct decomposition for this example.
          $\rule{0pt}{}$
          ○ $\dfrac{𝑨}{𝒙}+\dfrac{𝑩}{𝒙-1}+\dfrac{𝑪}{(𝒙-1)^{2}}+\dfrac{𝑫𝒙+𝑬}{𝒙^{2}+1}+\dfrac{𝑭𝒙+𝑮}{𝒙^{2}+𝒙+1}+\dfrac{𝑯𝒙+𝑰}{(𝒙^{2}+𝒙+1)^{2}}$
          $\rule{0pt}{}$
     ◉ Key takeaway.
          ○ This single example combines all the main cases:
               ■ linear factors
               ■ repeated linear factors
               ■ irreducible quadratics
               ■ repeated irreducible quadratics
     ◉ There is no “alternative shortcut.”
          ○ The correct partial-fraction decomposition is exactly this setup.
 

● [2:23:40](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=8620). 🧩 Example 5 — Case 4: Evaluate $\displaystyle \int \dfrac{𝒙^{3}-2𝒙^{2}+3𝒙+2}{𝒙(𝒙^{2}+1)^{2}}\,𝒅𝒙$. [📷image-1](../img/Calculus 2 Lecture 7.4/[2-23-40]-01.png)  [📷image-2](../img/Calculus 2 Lecture 7.4/[2-23-40]-02.png) [📷image-3](../img/Calculus 2 Lecture 7.4/[2-23-40]-03.png)
     ◉ Correct setup.
          $\rule{0pt}{}$
          ○ $\dfrac{𝑨}{𝒙}+\dfrac{𝑩𝒙+𝑪}{𝒙^{2}+1}+\dfrac{𝑫𝒙+𝑬}{(𝒙^{2}+1)^{2}}$
          $\rule{0pt}{}$
     ◉ Construction of the common denominator.
          $\rule{0pt}{}$
          ○ $𝒙^{3}-2𝒙^{2}+3𝒙+2$
          $\rule{0pt}{}$
          ○ $=𝑨(𝒙^{2}+1)^{2}+(𝑩𝒙+𝑪)𝒙(𝒙^{2}+1)+(𝑫𝒙+𝑬)𝒙$
          $\rule{0pt}{}$
     ◉ First useful value.
          ○ Let $𝒙=0$.
          ○ Then $2=𝑨$.
     ◉ Since the shortcut is no longer enough,
          ○ the expression must be distributed and regrouped by powers of $𝒙$.
     ◉ Expansion and collection of like terms.
          $\rule{0pt}{}$
          ○ $𝒙^{3}-2𝒙^{2}+3𝒙+2$
          $\rule{0pt}{}$
          ○ $=(𝑨+𝑩)𝒙^{4}+𝑪𝒙^{3}+(2𝑨+𝑩+𝑫)𝒙^{2}+(𝑪+𝑬)𝒙+𝑨$
          $\rule{0pt}{}$
     ◉ Comparison of coefficients.
          ○ coefficient of $𝒙^{4}$:
               ■ $𝑨+𝑩=0$
          ○ coefficient of $𝒙^{3}$:
               ■ $𝑪=1$
          ○ coefficient of $𝒙^{2}$:
               ■ $2𝑨+𝑩+𝑫=-2$
          ○ coefficient of $𝒙$:
               ■ $𝑪+𝑬=3$
          ○ constant term:
               ■ $𝑨=2$
     ◉ Step-by-step solution of the coefficients.
          ○ $𝑨=2$
          ○ $𝑪=1$
          ○ from $𝑪+𝑬=3$:
               $\rule{0pt}{}$
               ■ $1+𝑬=3$
               ■ $𝑬=2$
          ○ from $𝑨+𝑩=0$:
               $\rule{0pt}{}$
               ■ $2+𝑩=0$
               ■ $𝑩=-2$
          ○ from $2𝑨+𝑩+𝑫=-2$:
               $\rule{0pt}{}$
               ■ $2(2)+(-2)+𝑫=-2$
               ■ $𝑫=-4$
     ◉ Rewriting the integral.
          $\rule{0pt}{}$
          ○ $\displaystyle \int \left[\dfrac{2}{𝒙}+\dfrac{-2𝒙+1}{𝒙^{2}+1}+\dfrac{-4𝒙+2}{(𝒙^{2}+1)^{2}}\right]\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Splitting into several simpler integrals.
          $\rule{0pt}{}$
          ○ $2\displaystyle \int \dfrac{1}{𝒙}\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $-2\displaystyle \int \dfrac{𝒙}{𝒙^{2}+1}\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{𝒙^{2}+1}\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $-4\displaystyle \int \dfrac{𝒙}{(𝒙^{2}+1)^{2}}\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $2\displaystyle \int \dfrac{1}{(𝒙^{2}+1)^{2}}\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Techniques used.
     $\rule{0pt}{}$
          ○ Logarithm for $\dfrac{1}{𝒙}$:
          $\rule{0pt}{}$
               ■ $2\displaystyle \int \dfrac{1}{𝒙}\,𝒅𝒙=2\ln|𝒙|$
               $\rule{0pt}{}$
          ○ Substitution for $\dfrac{𝒙}{𝒙^{2}+1}$:
               $\rule{0pt}{}$
               ■ let $𝒖=𝒙^{2}+1$
               ■ $𝒅𝒖=2𝒙\,𝒅𝒙$
               $\rule{0pt}{}$
               ■ $-2\displaystyle \int \dfrac{𝒙}{𝒙^{2}+1}\,𝒅𝒙=-\ln|𝒙^{2}+1|$
               $\rule{0pt}{}$
          ○ Inverse tangent for $\dfrac{1}{𝒙^{2}+1}$:
          $\rule{0pt}{}$
               ■ $\displaystyle \int \dfrac{1}{𝒙^{2}+1}\,𝒅𝒙=\tan^{-1}(𝒙)$
               $\rule{0pt}{}$
          ○ Negative-power substitution for $\dfrac{𝒙}{(𝒙^{2}+1)^{2}}$:
               $\rule{0pt}{}$
               ■ let $𝒖=𝒙^{2}+1$
               ■ $𝒅𝒖=2𝒙\,𝒅𝒙$
               $\rule{0pt}{}$
               ■ $-4\displaystyle \int \dfrac{𝒙}{(𝒙^{2}+1)^{2}}\,𝒅𝒙=\dfrac{2}{𝒙^{2}+1}$
               $\rule{0pt}{}$
          ○ Trig substitution for $\dfrac{1}{(𝒙^{2}+1)^{2}}$:
               $\rule{0pt}{}$
               ■ use $\tan(\theta)=𝒙$
               ■ then $𝒅𝒙=\sec^{2}(\theta)\,𝒅\theta$
               $\rule{0pt}{}$
               ■ $2\displaystyle \int \dfrac{1}{(𝒙^{2}+1)^{2}}\,𝒅𝒙=2\int \cos^{2}(\theta)\,𝒅\theta$
               $\rule{0pt}{}$
     ◉ Treatment of the last term.
          ○ Use the identity:
          $\rule{0pt}{}$
               ■ $\cos^{2}(\theta)=\dfrac{1+\cos(2\theta)}{2}$
               $\rule{0pt}{}$
          ○ Then:
               $\rule{0pt}{}$
               ■ $2\int \cos^{2}(\theta)\,𝒅\theta=\theta+\dfrac{\sin(2\theta)}{2}$
               $\rule{0pt}{}$
               ■ $=\theta+\sin(\theta)\cos(\theta)$
               $\rule{0pt}{}$
     ◉ Return from $\theta$ to $𝒙$.
     $\rule{0pt}{}$
          ○ $\theta=\tan^{-1}(𝒙)$
          $\rule{0pt}{}$
          ○ $\sin(\theta)=\dfrac{𝒙}{\sqrt{𝒙^{2}+1}}$
          $\rule{0pt}{}$
          ○ $\cos(\theta)=\dfrac{1}{\sqrt{𝒙^{2}+1}}$
          $\rule{0pt}{}$
          ○ so:
               ■ $\theta+\sin(\theta)\cos(\theta)=\tan^{-1}(𝒙)+\dfrac{𝒙}{𝒙^{2}+1}$
               $\rule{0pt}{}$
     ◉ Final combination of terms.
          $\rule{0pt}{}$
          ○ $2\ln|𝒙|$
          $\rule{0pt}{}$
          ○ $-\ln|𝒙^{2}+1|$
          $\rule{0pt}{}$
          ○ $+\tan^{-1}(𝒙)$
          $\rule{0pt}{}$
          ○ $+\dfrac{2}{𝒙^{2}+1}$
          $\rule{0pt}{}$
          ○ $+\tan^{-1}(𝒙)$
          $\rule{0pt}{}$
          ○ $+\dfrac{𝒙+2}{𝒙^{2}+1}$
          $\rule{0pt}{}$
     ◉ Simplified final answer.
          $\rule{0pt}{}$
          ○ $2\ln|𝒙|-\ln|𝒙^{2}+1|+2\tan^{-1}(𝒙)+\dfrac{𝒙+2}{𝒙^{2}+1}+𝑪$


          

Ｃｏｎｃｌｕｓｉｏｎ

● [2:55:14](https://www.youtube.com/watch?v=KJGp0pyPoVo&t=10514). Closing of the last example.
     ◉ The hardest part of the method is usually the algebra:
          ○ factor correctly
          ○ set up the decomposition correctly
          ○ compare coefficients without sign errors
     ◉ Once the decomposition is done,
          ○ the integration usually reduces to already-known techniques:
               ■ logarithms
               ■ substitution
               ■ $\tan^{-1}$
               ■ and, in some cases, trig substitution



Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

[openstax🌐](https://openstax.org/books/calculus-volume-2/pages/3-3-trigonometric-substitution)