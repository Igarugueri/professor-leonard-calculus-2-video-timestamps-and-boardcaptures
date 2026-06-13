-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ７．１ － Ｉｎｔｅｇｒａｔｉｏｎ Ｂｙ Ｐａｒｔｓ**---------------------------------






Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:00](https://www.youtube.com/watch?v=EOwjiFpDY_s&t=0). Introduction to Chapter 7, Section 7.1: Integration by Parts.
     ◉ Review of previous methods: integration tables and u-substitution.
     ◉ Conceptual analysis: substitution as the inverse process of the Chain Rule.

     




Ｄｅｒｉｖａｔｉｏｎ ｏｆ ｔｈｅ Ｆｏｒｍｕｌａ

● [1:03](https://www.youtube.com/watch?v=EOwjiFpDY_s&t=63). Derivation of the Integration by Parts formula from the Product Rule. [📷image-1](../img/Calculus 2 Lecture 7.1/[1-03]-01.png) [📷image-2](../img/Calculus 2 Lecture 7.1/[1-03]-02.png) 
     ◉ Starting point: the Product Rule.
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}[𝒇(𝒙)𝓰(𝒙)]=𝒇'(𝒙)𝓰(𝒙)+𝒇(𝒙)𝓰'(𝒙)$
          $\rule{0pt}{}$
     ◉ Integrate both sides.
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{𝒅}{𝒅𝒙}[𝒇(𝒙)𝓰(𝒙)]\,𝒅𝒙=\displaystyle \int [𝒇'(𝒙)𝓰(𝒙)+𝒇(𝒙)𝓰'(𝒙)]\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Apply the Fundamental Theorem of Calculus.
          $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{𝒅}{𝒅𝒙}[𝒇(𝒙)𝓰(𝒙)]\,𝒅𝒙=𝒇(𝒙)𝓰(𝒙)$
          $\rule{0pt}{}$
     ◉ Separate the integrals.
          $\rule{0pt}{}$
          ○ $𝒇(𝒙)𝓰(𝒙)=\displaystyle \int 𝒇'(𝒙)𝓰(𝒙)\,𝒅𝒙+\displaystyle \int 𝒇(𝒙)𝓰'(𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Rearrangement.
          $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒇(𝒙)𝓰'(𝒙)\,𝒅𝒙=𝒇(𝒙)𝓰(𝒙)-\displaystyle \int 𝓰(𝒙)𝒇'(𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ [5:29](https://www.youtube.com/watch?v=EOwjiFpDY_s&t=329). Introduction of auxiliary notation.
          ○ Define:
               $\rule{0pt}{}$
               ■ $𝒖=𝒇(𝒙)$
               ■ $\mathcal{V}=𝓰(𝒙)$
               $\rule{0pt}{}$
          ○ Corresponding differentials:
               $\rule{0pt}{}$
               ■ $𝒅𝒖=𝒇'(𝒙)\,𝒅𝒙$
               ■ $𝒅\mathcal{V}=𝓰'(𝒙)\,𝒅𝒙$
               $\rule{0pt}{}$
     ◉ Standard formula.
          $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒖\,𝒅\mathcal{V}=𝒖\mathcal{V}-\displaystyle \int \mathcal{V}\,𝒅𝒖$
          $\rule{0pt}{}$
     ◉ Practical note on choosing 𝒖 and 𝒅𝓥.
          ○ Choose 𝒖 so that $\dfrac{𝒅𝒖}{𝒅𝒙}$ becomes simpler or “better”.
          $\rule{0pt}{}$
          ○ Choose 𝒅𝓥 so that $\displaystyle \int 𝒅𝓥$ can actually be computed.


          


Ｂａｓｉｃ  Ｅｘａｍｐｌｅｓ

● [11:51](https://www.youtube.com/watch?v=EOwjiFpDY_s&t=711). 🧩 Example 1 — Evaluate $\displaystyle \int 𝒙𝒆^{𝒙}\,𝒅𝒙$ [📷image](../img/Calculus 2 Lecture 7.1/[11-51]-01.png)
     ◉ Why simple substitution does not work.
          ○ There is no natural inner function whose derivative produces the remaining factor directly.
          ○ The product $𝒙𝒆^{𝒙}$ suggests Integration by Parts instead.
     ◉ Criteria for choosing 𝒖 and 𝒅𝓥.
          ○ Heuristic rule:
               ■ Choose 𝒖 so that $\dfrac{𝒅𝒖}{𝒅𝒙}$ becomes simpler or has lower degree.
               ■ Choose 𝒅𝓥 so that $\mathcal{V}=\displaystyle \int 𝒅𝓥$ is easy to compute.
          ○ Assignment:
               $\rule{0pt}{}$
               ■ $𝒖=𝒙$
               ■ $𝒅\mathcal{V}=𝒆^{𝒙}\,𝒅𝒙$
               ■ $𝒅𝒖=𝒅𝒙$
               ■ $\mathcal{V}=𝒆^{𝒙}$
               $\rule{0pt}{}$
     ◉ Apply the formula:
          $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒖\,𝒅\mathcal{V}=𝒖\mathcal{V}-\displaystyle \int \mathcal{V}\,𝒅𝒖$
          $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒙𝒆^{𝒙}\,𝒅𝒙=𝒙𝒆^{𝒙}-\displaystyle \int 𝒆^{𝒙}\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Integrate the remaining term.
          $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒆^{𝒙}\,𝒅𝒙=𝒆^{𝒙}$
          $\rule{0pt}{}$
          ○ Therefore:
               $\rule{0pt}{}$
               ■ $\displaystyle \int 𝒙𝒆^{𝒙}\,𝒅𝒙=𝒙𝒆^{𝒙}-𝒆^{𝒙}+𝓒$
               $\rule{0pt}{}$
     ◉ Final result:
          $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒙𝒆^{𝒙}\,𝒅𝒙=𝒆^{𝒙}(𝒙-1)+𝓒$
          $\rule{0pt}{}$

● [17:58](https://www.youtube.com/watch?v=EOwjiFpDY_s&t=1078). 🧩 Example 2 — Evaluate $\displaystyle \int 𝒙^{3}\ln 𝒙\,𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.1/[19-08]-01.png)
     ◉ Common mistake: choosing $𝒖=𝒙^{3}$.
          ○ If $𝒖=𝒙^{3}$, then $𝒅𝒖=3𝒙^{2}\,𝒅𝒙$
          ○ But then $𝒅\mathcal{V}=\ln 𝒙\,𝒅𝒙$, which is not convenient because $\displaystyle \int \ln 𝒙\,𝒅𝒙$ is exactly the harder part.
     ◉ Main obstacle:
          ○ $\ln 𝒙$ is difficult to integrate if chosen as $𝒅\mathcal{V}$.
     ◉ Correct choice:
          $\rule{0pt}{}$
          ○ $𝒖=\ln 𝒙$
          ○ $𝒅\mathcal{V}=𝒙^{3}\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Compute the parts:
          $\rule{0pt}{}$
          ○ $𝒅𝒖=\dfrac{1}{𝒙}\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $\mathcal{V}=\displaystyle \int 𝒙^{3}\,𝒅𝒙=\dfrac{𝒙^{4}}{4}$
          $\rule{0pt}{}$
     ◉ Apply the Integration by Parts formula:
          $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒙^{3}\ln 𝒙\,𝒅𝒙=𝒖\mathcal{V}-\displaystyle \int \mathcal{V}\,𝒅𝒖$
          $\rule{0pt}{}$
          ○ $=\ln 𝒙\cdot \dfrac{𝒙^{4}}{4}-\displaystyle \int \left(\dfrac{𝒙^{4}}{4}\right)\left(\dfrac{1}{𝒙}\right)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Simplify the remaining integral:
          $\rule{0pt}{}$
          ○ $=\dfrac{𝒙^{4}}{4}\ln 𝒙-\left(\dfrac{1}{4}\right)\displaystyle \int 𝒙^{3}\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $=\dfrac{𝒙^{4}}{4}\ln 𝒙-\left(\dfrac{1}{4}\right)\left(\dfrac{𝒙^{4}}{4}\right)$
          $\rule{0pt}{}$
     ◉ Final result:
          $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒙^{3}\ln 𝒙\,𝒅𝒙=\left(\dfrac{1}{4}\right)𝒙^{4}\ln 𝒙-\left(\dfrac{1}{16}\right)𝒙^{4}+𝓒$
          $\rule{0pt}{}$



          


Ｒｅｐｅａｔｅｄ  Ｉｎｔｅｇｒａｔｉｏｎ   ｂｙ  Ｐａｒｔｓ  Ｅｘａｍｐｌｅ

● [28:42](https://www.youtube.com/watch?v=EOwjiFpDY_s&t=1722). 🧩 Example 3 — Repeated use of Integration by Parts: Evaluate $\displaystyle \int 𝒙^{2}\sin(2𝒙)\,𝒅𝒙$ [📷image](../img/Calculus 2 Lecture 7.1/[28-42]-01.png)
     ◉ First iteration of Integration by Parts.
          ○ Choose:
               ■ $𝒖=𝒙^{2}$
               ■ $𝒅\mathcal{V}=\sin(2𝒙)\,𝒅𝒙$
          ○ Then:
               ■ $𝒅𝒖=2𝒙\,𝒅𝒙$
               $\rule{0pt}{}$
               ■ $\mathcal{V}=\displaystyle \int \sin(2𝒙)\,𝒅𝒙=-\left(\dfrac{1}{2}\right)\cos(2𝒙)$
               $\rule{0pt}{}$
     ◉ Apply the formula.
          $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒙^{2}\sin(2𝒙)\,𝒅𝒙=𝒖\mathcal{V}-\displaystyle \int \mathcal{V}\,𝒅𝒖$
          $\rule{0pt}{}$
          ○ $=𝒙^{2}\Big[-\left(\dfrac{1}{2}\right)\cos(2𝒙)\Big]-\displaystyle \int \Big[-\left(\dfrac{1}{2}\right)\cos(2𝒙)\Big](2𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $=-\left(\dfrac{1}{2}\right)𝒙^{2}\cos(2𝒙)+\displaystyle \int 𝒙\cos(2𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Second iteration on the remaining integral.
     $\rule{0pt}{}$
          ○ For $\displaystyle \int 𝒙\cos(2𝒙)\,𝒅𝒙$, choose:
               $\rule{0pt}{}$
               ■ $𝒖=𝒙$
               ■ $𝒅\mathcal{V}=\cos(2𝒙)\,𝒅𝒙$
               $\rule{0pt}{}$
          ○ Then:
               $\rule{0pt}{}$
               ■ $𝒅𝒖=𝒅𝒙$
               $\rule{0pt}{}$
               ■ $\mathcal{V}=\displaystyle \int \cos(2𝒙)\,𝒅𝒙=\left(\dfrac{1}{2}\right)\sin(2𝒙)$
               $\rule{0pt}{}$
     ◉ Apply Integration by Parts again.
          $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒙\cos(2𝒙)\,𝒅𝒙=𝒖\mathcal{V}-\displaystyle \int \mathcal{V}\,𝒅𝒖$
          $\rule{0pt}{}$
          ○ $=𝒙\Big[\left(\dfrac{1}{2}\right)\sin(2𝒙)\Big]-\displaystyle \int \left(\dfrac{1}{2}\right)\sin(2𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $=\left(\dfrac{1}{2}\right)𝒙\sin(2𝒙)-\left(\dfrac{1}{2}\right)\displaystyle \int \sin(2𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $=\left(\dfrac{1}{2}\right)𝒙\sin(2𝒙)+\left(\dfrac{1}{4}\right)\cos(2𝒙)$
          $\rule{0pt}{}$
     ◉ Consolidate all terms.
          $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒙^{2}\sin(2𝒙)\,𝒅𝒙$
               ■ $=-\left(\dfrac{1}{2}\right)𝒙^{2}\cos(2𝒙)+\left(\dfrac{1}{2}\right)𝒙\sin(2𝒙)+\left(\dfrac{1}{4}\right)\cos(2𝒙)+𝓒$
          $\rule{0pt}{}$
     ◉ Key idea.
          ○ Each application of Integration by Parts lowers the power of 𝒙.
          ○ Repeating the method eventually reduces the problem to a basic trigonometric integral.



     


Ｃｉｒｃｕｌａｒ Ｉｎｔｅｇｒａｌｓ  ｂｙ   Ｐａｒｔｓ   Ｅｘａｍｐｌｅ


● [43:02](https://www.youtube.com/watch?v=EOwjiFpDY_s&t=2582). 🧩 Example 4 — Circula integral: $\displaystyle \int 𝒆^{𝒙}\sin(2𝒙)\,𝒅𝒙$. [📷image-1](../img/Calculus 2 Lecture 7.1/[43-02]-01.png) [📷image-2](../img/Calculus 2 Lecture 7.1/[43-02]-02.png) 
     ◉ Observation of the cyclic behavior of transcendental functions.
          ○ Repeated integration by parts brings back the original integral.
          ○ This creates a circular equation that must be solved algebraically.
     ◉ First application of Integration by Parts.
          ○ Choose:
               ■ $𝒖=\sin(2𝒙)$
               ■ $𝒅\mathcal{V}=𝒆^{𝒙}\,𝒅𝒙$
          ○ Then:
               ■ $𝒅𝒖=2\cos(2𝒙)\,𝒅𝒙$
               ■ $\mathcal{V}=𝒆^{𝒙}$
               $\rule{0pt}{}$
          ○ Apply the formula:
               $\rule{0pt}{}$
               ■ $\displaystyle \int 𝒆^{𝒙}\sin(2𝒙)\,𝒅𝒙=𝒆^{𝒙}\sin(2𝒙)-2\displaystyle \int 𝒆^{𝒙}\cos(2𝒙)\,𝒅𝒙$
               $\rule{0pt}{}$
     ◉ Second application on the new integral.
     $\rule{0pt}{}$
          ○ For $\displaystyle \int 𝒆^{𝒙}\cos(2𝒙)\,𝒅𝒙$, choose:
               $\rule{0pt}{}$
               ■ $𝒖=\cos(2𝒙)$
               ■ $𝒅\mathcal{V}=𝒆^{𝒙}\,𝒅𝒙$
          ○ Then:
               ■ $𝒅𝒖=-2\sin(2𝒙)\,𝒅𝒙$
               ■ $\mathcal{V}=𝒆^{𝒙}$
          ○ Apply the formula:
               $\rule{0pt}{}$
               ■ $\displaystyle \int 𝒆^{𝒙}\cos(2𝒙)\,𝒅𝒙=𝒆^{𝒙}\cos(2𝒙)+2\displaystyle \int 𝒆^{𝒙}\sin(2𝒙)\,𝒅𝒙$
               $\rule{0pt}{}$
     ◉ Substitute back into the first result.
          $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒆^{𝒙}\sin(2𝒙)\,𝒅𝒙$
               ■ $=𝒆^{𝒙}\sin(2𝒙)-2[𝒆^{𝒙}\cos(2𝒙)+2\displaystyle \int 𝒆^{𝒙}\sin(2𝒙)\,𝒅𝒙]$
               $\rule{0pt}{}$
               ■ $=𝒆^{𝒙}\sin(2𝒙)-2𝒆^{𝒙}\cos(2𝒙)-4\displaystyle \int 𝒆^{𝒙}\sin(2𝒙)\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Solve algebraically by isolating the original integral.
     $\rule{0pt}{}$
          ○ Add $4\displaystyle \int 𝒆^{𝒙}\sin(2𝒙)\,𝒅𝒙$ to both sides:
               $\rule{0pt}{}$
               ■ $5\displaystyle \int 𝒆^{𝒙}\sin(2𝒙)\,𝒅𝒙=𝒆^{𝒙}\sin(2𝒙)-2𝒆^{𝒙}\cos(2𝒙)$
               $\rule{0pt}{}$
          ○ Divide by $5$:
               $\rule{0pt}{}$
               ■ $\displaystyle \int 𝒆^{𝒙}\sin(2𝒙)\,𝒅𝒙=\left(\dfrac{1}{5}\right)𝒆^{𝒙}[\sin(2𝒙)-2\cos(2𝒙)]+𝓒$
               $\rule{0pt}{}$
     ◉ Final result:
          $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒆^{𝒙}\sin(2𝒙)\,𝒅𝒙=\left(\dfrac{1}{5}\right)𝒆^{𝒙}[\sin(2𝒙)-2\cos(2𝒙)]+𝓒$
          $\rule{0pt}{}$



          


Ｄｅｆｉｎｅｄ Ｉｎｔｅｇｒａｌｓ

● [59:00](https://www.youtube.com/watch?v=EOwjiFpDY_s&t=3540). 🧩 Example 5 — Definite integral and geometric interpretation: $\displaystyle \int_{1}^{𝒆}\ln 𝒙\,𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.1/[59-00]-01.png)
     ◉ Define the parts.
          ○ $𝒖=\ln 𝒙$
          ○ $𝒅\mathcal{V}=𝒅𝒙$
          ○ $𝒅𝒖=\left(\dfrac{1}{𝒙}\right)\,𝒅𝒙$
          ○ $\mathcal{V}=𝒙$
     ◉ Apply Integration by Parts.
          $\rule{0pt}{}$
          ○ $\displaystyle \int \ln 𝒙\,𝒅𝒙=𝒖\mathcal{V}-\displaystyle \int \mathcal{V}\,𝒅𝒖$
          $\rule{0pt}{}$
          ○ $=𝒙\ln 𝒙-\displaystyle \int 𝒙\cdot \left(\dfrac{1}{𝒙}\right)\,𝒅𝒙$
          $\rule{0pt}{}$
          ○ $=𝒙\ln 𝒙-\displaystyle \int 1\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Antiderivative obtained.
          $\rule{0pt}{}$
          ○ $𝒙\ln 𝒙-𝒙$
          $\rule{0pt}{}$
     ◉ Evaluate at the bounds.
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{1}^{𝒆}\ln 𝒙\,𝒅𝒙=\Big[𝒙\ln 𝒙-𝒙\Big]_{1}^{𝒆}$
          $\rule{0pt}{}$
          ○ $=[𝒆\ln 𝒆-𝒆]-[1\ln 1-1]$
          ○ $=[𝒆(1)-𝒆]-[0-1]$
          ○ $=0-(-1)$
          ○ $=1$
          $\rule{0pt}{}$
     ◉ Geometric interpretation.
          ○ The definite integral represents the area under the curve $𝒚=\ln 𝒙$ from $𝒙=1$ to $𝒙=𝒆$.
     ◉ Final conclusion.
          $\rule{0pt}{}$
          ○ $\displaystyle \int_{1}^{𝒆}\ln 𝒙\,𝒅𝒙=1$
          $\rule{0pt}{}$
          ○ Therefore, the area under $\ln 𝒙$ on $[1,𝒆]$ is exactly $1$.



          


Ｓｅｃａｎｔ Ｐｏｗｅｒｓ

● [1:06:25](https://www.youtube.com/watch?v=EOwjiFpDY_s&t=3985). 🧩 Example 6 — Odd powers of secant: $\displaystyle \int \sec 𝒙\,𝒅𝒙$, $\displaystyle \int \sec^{3} 𝒙\,𝒅𝒙$, and $\displaystyle \int \sec^{5} 𝒙\,𝒅𝒙$ [📷image-1](../img/Calculus 2 Lecture 7.1/[1-06-25 ]-01.png) [📷image-2](../img/Calculus 2 Lecture 7.1/[1-06-25 ]-02.png) [📷image-3](../img/Calculus 2 Lecture 7.1/[1-06-25 ]-03.png) 
     ◉ Preliminary basic integrals
          $\rule{0pt}{}$
          ○ $\displaystyle \int \sec 𝒙\,𝒅𝒙=\ln|\sec 𝒙+\tan 𝒙|+𝓒$
          $\rule{0pt}{}$
          ○ $\displaystyle \int \sec^{2} 𝒙\,𝒅𝒙=\tan 𝒙+𝓒$
          $\rule{0pt}{}$
     ◉ Solve $\displaystyle \int \sec^{3} 𝒙\,𝒅𝒙$ by Integration by Parts
          ○ Decomposition strategy:
               $\rule{0pt}{}$
               ■ $\displaystyle \int \sec^{3} 𝒙\,𝒅𝒙=\displaystyle \int \sec 𝒙\cdot \sec^{2} 𝒙\,𝒅𝒙$
               $\rule{0pt}{}$
          ○ Choose:
               $\rule{0pt}{}$
               ■ $𝒖=\sec 𝒙$
               ■ $𝒅\mathcal{V}=\sec^{2} 𝒙\,𝒅𝒙$
               $\rule{0pt}{}$
          ○ Then:
               $\rule{0pt}{}$
               ■ $𝒅𝒖=\sec 𝒙\tan 𝒙\,𝒅𝒙$
               ■ $\mathcal{V}=\tan 𝒙$
               $\rule{0pt}{}$
          ○ Apply Integration by Parts:
               $\rule{0pt}{}$
               ■ $\displaystyle \int \sec^{3} 𝒙\,𝒅𝒙=\sec 𝒙\tan 𝒙-\displaystyle \int \tan 𝒙\cdot \sec 𝒙\tan 𝒙\,𝒅𝒙$
               $\rule{0pt}{}$
               ■ $=\sec 𝒙\tan 𝒙-\displaystyle \int \tan^{2} 𝒙\sec 𝒙\,𝒅𝒙$
               $\rule{0pt}{}$
          ○ Use the Pythagorean identity:
               $\rule{0pt}{}$
               ■ $\tan^{2} 𝒙=\sec^{2} 𝒙-1$
               $\rule{0pt}{}$
          ○ Substitute:
               $\rule{0pt}{}$
               ■ $\displaystyle \int \sec^{3} 𝒙\,𝒅𝒙=\sec 𝒙\tan 𝒙-\displaystyle \int (\sec^{2} 𝒙-1)\sec 𝒙\,𝒅𝒙$
               $\rule{0pt}{}$
               ■ $=\sec 𝒙\tan 𝒙-\displaystyle \int \sec^{3} 𝒙\,𝒅𝒙+\displaystyle \int \sec 𝒙\,𝒅𝒙$
               $\rule{0pt}{}$
          ○ Solve for the original integral:
               $\rule{0pt}{}$
               ■ $2\displaystyle \int \sec^{3} 𝒙\,𝒅𝒙=\sec 𝒙\tan 𝒙+\ln|\sec 𝒙+\tan 𝒙|$
               $\rule{0pt}{}$
               ■ $\displaystyle \int \sec^{3} 𝒙\,𝒅𝒙=\left(\dfrac{1}{2}\right)\sec 𝒙\tan 𝒙+\left(\dfrac{1}{2}\right)\ln|\sec 𝒙+\tan 𝒙|+𝓒$
               $\rule{0pt}{}$
     ◉ Extension to $\displaystyle \int \sec^{5} 𝒙\,𝒅𝒙$
     $\rule{0pt}{}$
          ○ Decomposition strategy:
               $\rule{0pt}{}$
               ■ $\displaystyle \int \sec^{5} 𝒙\,𝒅𝒙=\displaystyle \int \sec^{3} 𝒙\cdot \sec^{2} 𝒙\,𝒅𝒙$
               $\rule{0pt}{}$
          ○ Choose:
               $\rule{0pt}{}$
               ■ $𝒖=\sec^{3} 𝒙$
               ■ $𝒅\mathcal{V}=\sec^{2} 𝒙\,𝒅𝒙$
               $\rule{0pt}{}$
          ○ Then:
               $\rule{0pt}{}$
               ■ $𝒅𝒖=3\sec^{3} 𝒙\tan 𝒙\,𝒅𝒙$
               ■ $\mathcal{V}=\tan 𝒙$
               $\rule{0pt}{}$
          ○ Apply Integration by Parts:
               $\rule{0pt}{}$
               ■ $\displaystyle \int \sec^{5} 𝒙\,𝒅𝒙=\sec^{3} 𝒙\tan 𝒙-3\displaystyle \int \tan^{2} 𝒙\sec^{3} 𝒙\,𝒅𝒙$
               $\rule{0pt}{}$
          ○ Use $\tan^{2} 𝒙=\sec^{2} 𝒙-1$:
               $\rule{0pt}{}$
               ■ $\displaystyle \int \sec^{5} 𝒙\,𝒅𝒙=\sec^{3} 𝒙\tan 𝒙-3\displaystyle \int (\sec^{2} 𝒙-1)\sec^{3} 𝒙\,𝒅𝒙$
               $\rule{0pt}{}$
               ■ $=\sec^{3} 𝒙\tan 𝒙-3\displaystyle \int \sec^{5} 𝒙\,𝒅𝒙+3\displaystyle \int \sec^{3} 𝒙\,𝒅𝒙$
               $\rule{0pt}{}$
          ○ Solve for the original integral:
               $\rule{0pt}{}$
               ■ $4\displaystyle \int \sec^{5} 𝒙\,𝒅𝒙=\sec^{3} 𝒙\tan 𝒙+3\displaystyle \int \sec^{3} 𝒙\,𝒅𝒙$
               $\rule{0pt}{}$
          ○ Substitute the previous result for $\displaystyle \int \sec^{3} 𝒙\,𝒅𝒙$:
               $\rule{0pt}{}$
               ■ $4\displaystyle \int \sec^{5} 𝒙\,𝒅𝒙=\sec^{3} 𝒙\tan 𝒙+\left(\dfrac{3}{2}\right)\sec 𝒙\tan 𝒙+\left(\dfrac{3}{2}\right)\ln|\sec 𝒙+\tan 𝒙|$
               $\rule{0pt}{}$
          ○ Final result:
               $\rule{0pt}{}$
               ■ $\displaystyle \int \sec^{5} 𝒙\,𝒅𝒙=\left(\dfrac{1}{4}\right)\sec^{3} 𝒙\tan 𝒙+\left(\dfrac{3}{8}\right)\sec 𝒙\tan 𝒙+\left(\dfrac{3}{8}\right)\ln|\sec 𝒙+\tan 𝒙|+𝓒$
               $\rule{0pt}{}$
     ◉ Key idea
          ○ Odd powers of secant are handled by peeling off a factor $\sec^{2} 𝒙$ and using Integration by Parts.
          ○ The identity $\tan^{2} 𝒙=\sec^{2} 𝒙-1$ converts the remaining expression back into secant powers, creating a recurrence relation.



          


Ｒｅｄｕｃｔｉｏｎ Ｆｏｒｍｕｌａｓ

● [1:29:40](https://www.youtube.com/watch?v=EOwjiFpDY_s&t=5380). Development and proof of the Reduction Formula. [📷image-1](../img/Calculus 2 Lecture 7.1/[1-29-40]-01.png) [📷image-2](../img/Calculus 2 Lecture 7.1/[1-29-40]-02.png) 
     ◉ NOTE: It is not only for sine. This is specifically the reduction formula for ∫ sinⁿx dx, but similar reduction formulas also exist for cosine, secant, and other families of integrals.
     ◉ Goal:
          ○ Reduce $\displaystyle \int \sin^{𝒏} 𝒙\,𝒅𝒙$ to an integral involving $\sin^{𝒏-2} 𝒙$.
          ○ Assume $𝒏\ge 2$.
     ◉ Split the integrand:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \sin^{𝒏} 𝒙\,𝒅𝒙=\displaystyle \int \sin^{𝒏-1} 𝒙\cdot \sin 𝒙\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Apply Integration by Parts.
          ○ Choose:
               $\rule{0pt}{}$
               ■ $𝒖=\sin^{𝒏-1} 𝒙$
               ■ $𝒅\mathcal{V}=\sin 𝒙\,𝒅𝒙$
               $\rule{0pt}{}$
          ○ Then:
               $\rule{0pt}{}$
               ■ $𝒅𝒖=(𝒏-1)\sin^{𝒏-2} 𝒙\cos 𝒙\,𝒅𝒙$
               ■ $\mathcal{V}=-\cos 𝒙$
               $\rule{0pt}{}$
     ◉ Substitute into the formula.
          $\rule{0pt}{}$
          ○ $\displaystyle \int \sin^{𝒏} 𝒙\,𝒅𝒙$
               ■ $=𝒖\mathcal{V}-\displaystyle \int \mathcal{V}\,𝒅𝒖$
               ■ $=-\sin^{𝒏-1} 𝒙\cos 𝒙+(𝒏-1)\displaystyle \int \cos^{2} 𝒙\sin^{𝒏-2} 𝒙\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Rewrite $\cos^{2} 𝒙$ in terms of sine.
          ○ Use:
               $\rule{0pt}{}$
               ■ $\cos^{2} 𝒙=1-\sin^{2} 𝒙$
               $\rule{0pt}{}$
          ○ Then:
               $\rule{0pt}{}$
               ■ $\displaystyle \int \sin^{𝒏} 𝒙\,𝒅𝒙$
               ■ $=-\sin^{𝒏-1} 𝒙\cos 𝒙+(𝒏-1)\displaystyle \int (1-\sin^{2} 𝒙)\sin^{𝒏-2} 𝒙\,𝒅𝒙$
               $\rule{0pt}{}$
     ◉ Expand the integral.
          $\rule{0pt}{}$
          ○ $=-\sin^{𝒏-1} 𝒙\cos 𝒙+(𝒏-1)\displaystyle \int \sin^{𝒏-2} 𝒙\,𝒅𝒙-(𝒏-1)\displaystyle \int \sin^{𝒏} 𝒙\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Collect like terms.
     $\rule{0pt}{}$
          ○ Add $(𝒏-1)\displaystyle \int \sin^{𝒏} 𝒙\,𝒅𝒙$ to both sides:
               $\rule{0pt}{}$
               ■ $𝒏\displaystyle \int \sin^{𝒏} 𝒙\,𝒅𝒙=-\sin^{𝒏-1} 𝒙\cos 𝒙+(𝒏-1)\displaystyle \int \sin^{𝒏-2} 𝒙\,𝒅𝒙$
               $\rule{0pt}{}$
     ◉ Divide by $𝒏$.
          $\rule{0pt}{}$
          ○ $\displaystyle \int \sin^{𝒏} 𝒙\,𝒅𝒙=-\left(\dfrac{1}{𝒏}\right)\sin^{𝒏-1} 𝒙\cos 𝒙+\left(\dfrac{𝒏-1}{𝒏}\right)\displaystyle \int \sin^{𝒏-2} 𝒙\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Final Reduction Formula for sine:
          $\rule{0pt}{}$
          ○ $\displaystyle \int \sin^{𝒏} 𝒙\,𝒅𝒙=-\left(\dfrac{1}{𝒏}\right)\sin^{𝒏-1} 𝒙\cos 𝒙+\left(\dfrac{𝒏-1}{𝒏}\right)\displaystyle \int \sin^{𝒏-2} 𝒙\,𝒅𝒙$
          $\rule{0pt}{}$
          
●  [1:48:13](https://www.youtube.com/watch?v=EOwjiFpDY_s&t=6493). 🧩 Example —: $\displaystyle \int \sin^{4} 𝒙\,𝒅𝒙$. [📷image](../img/Calculus 2 Lecture 7.1/[1-48-13]-01.png)
$\rule{0pt}{}$
     ◉ Apply the Reduction Formula with $𝒏=4$.
          $\rule{0pt}{}$
          ○ $\displaystyle \int \sin^{4} 𝒙\,𝒅𝒙=-\left(\dfrac{1}{4}\right)\sin^{3} 𝒙\cos 𝒙+\left(\dfrac{3}{4}\right)\displaystyle \int \sin^{2} 𝒙\,𝒅𝒙$
          $\rule{0pt}{}$
     ◉ Reduce the remaining integral $\displaystyle \int \sin^{2} 𝒙\,𝒅𝒙$.
          ○ Apply the Reduction Formula again with $𝒏=2$:
               $\rule{0pt}{}$
               ■ $\displaystyle \int \sin^{2} 𝒙\,𝒅𝒙=-\left(\dfrac{1}{2}\right)\sin 𝒙\cos 𝒙+\left(\dfrac{1}{2}\right)\displaystyle \int 1\,𝒅𝒙$
               $\rule{0pt}{}$
                ■ $=-\left(\dfrac{1}{2}\right)\sin 𝒙\cos 𝒙+\left(\dfrac{1}{2}\right)𝒙$
               $\rule{0pt}{}$
     ◉ Substitute this result back into the first expression.
          $\rule{0pt}{}$
          ○ $\displaystyle \int \sin^{4} 𝒙\,𝒅𝒙$
               ■ $=-\left(\dfrac{1}{4}\right)\sin^{3} 𝒙\cos 𝒙+\left(\dfrac{3}{4}\right)\Big[-\left(\dfrac{1}{2}\right)\sin 𝒙\cos 𝒙+\left(\dfrac{1}{2}\right)𝒙\Big]$
          $\rule{0pt}{}$
     ◉ Distribute the factor $3/4$.
          $\rule{0pt}{}$
          ○ $\displaystyle \int \sin^{4} 𝒙\,𝒅𝒙$
               ■ $=-\left(\dfrac{1}{4}\right)\sin^{3} 𝒙\cos 𝒙-\left(\dfrac{3}{8}\right)\sin 𝒙\cos 𝒙+\left(\dfrac{3}{8}\right)𝒙+𝓒$
          $\rule{0pt}{}$
     ◉ Final result.
          $\rule{0pt}{}$
          ○ $\displaystyle \int \sin^{4} 𝒙\,𝒅𝒙=-\left(\dfrac{1}{4}\right)\sin^{3} 𝒙\cos 𝒙-\left(\dfrac{3}{8}\right)\sin 𝒙\cos 𝒙+\left(\dfrac{3}{8}\right)𝒙+𝓒$
          $\rule{0pt}{}$
     



Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

[openstax🌐](https://openstax.org/books/calculus-volume-2/pages/3-1-integration-by-parts)