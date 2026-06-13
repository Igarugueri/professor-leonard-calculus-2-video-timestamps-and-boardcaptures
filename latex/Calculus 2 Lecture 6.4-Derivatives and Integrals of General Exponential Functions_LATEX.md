-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ６．４ － Ｄｅｒｉｖａｔｉｖｅｓ ａｎｄ Ｉｎｔｅｇｒａｌｓ ｏｆ Ｇｅｎｅｒａｌ Ｅｘｐｏｎｅｎｔｉａｌ Ｆｕｎｃｔｉｏｎｓ**------------------------------—




Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:05](https://www.youtube.com/watch?v=rR8imSHCuFk&t=5). Fundamental properties of exponential expressions. [📷image](../img/Calculus 2 Lecture 6.4/[0-05]-01.png)
     ◉ product of powers with the same base:
          ○ $𝒂^{𝒙}\cdot 𝒂^{𝒚}=𝒂^{𝒙+𝒚}$
     ◉ Power of a power:
          ○ $(𝒂^{𝒙})^{𝒚}=𝒂^{𝒙𝒚}$
     ◉ Power of a product:
          ○ $(𝒂𝒃)^{𝒙}=𝒂^{𝒙}\cdot 𝒃^{𝒙}$
     ◉ Quotient of powers with the same base:
          ○ $\dfrac{𝒂^{𝒙}}{𝒂^{𝒚}}=𝒂^{𝒙-𝒚}$
     ◉ Power of a quotient:
          ○ $\left(\dfrac{𝒂}{𝒃}\right)^{𝒙}=\dfrac{𝒂^{𝒙}}{𝒃^{𝒙}}$





Ｄｅｒｉｖａｔｉｖｅ ｏｆ ａｎ ｅｘｐｏｎｅｎｔｉａｌ ｆｕｎｃｔｉｏｎ

● [1:40](https://www.youtube.com/watch?v=rR8imSHCuFk&t=100). Rewriting a general exponential function using the natural exponential form. [📷image](../img/Calculus 2 Lecture 6.4/[1-40]-01.png)
     ◉ Expressing any positive base in terms of 𝓮.
          ○ Use the identity:
               ■ $𝒙=𝓮^{\ln 𝒙}$
          ○ Apply it to a constant base 𝒂:
               ■ $𝒂=𝓮^{\ln 𝒂}$
     ◉ Rewriting the exponential function 𝒂^𝒙.
          ○ Substitute 𝒂 = 𝓮^{ln 𝒂}:
               ■ $𝒂^{𝒙}=(𝓮^{\ln 𝒂})^{𝒙}$
          ○ Use properties of exponents:
               ■ $𝒂^{𝒙}=𝓮^{𝒙\ln 𝒂}$
     ◉ Representation of a general exponential function.
          ○ Define the function:
               ■ $𝒇(𝒙)=𝒂^{𝒙}$
          ○ Equivalent natural exponential form:
               ■ $𝒇(𝒙)=𝓮^{𝒙\ln 𝒂}$
     ◉ 🧩 Example – with base  $2^{π}$.
          ○ $𝒇(𝒙)=𝒂^{𝒙}=𝓮^{𝒙\ln 𝒂}$
               ■ $2^{\pi}=𝓮^{\pi\ln 2}$

● [6:00](https://www.youtube.com/watch?v=rR8imSHCuFk&t=360). Derivative of a general exponential function. [📷image](../img/Calculus 2 Lecture 6.4/[6-00]-01.png)
     ◉ Rewriting the function using the natural exponential.
          ○ Start from the general exponential:
               ■ $𝒇(𝒙)=𝒂^{𝒙}$
          ○ Use the identity 𝒂 = 𝓮^{ln 𝒂}:
               ■ $𝒂^{𝒙}=𝓮^{𝒙\ln 𝒂}$
     ◉ Apply differentiation rules.
          ○ Differentiate using the chain rule:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}\Big[𝒂^{𝒙}\Big]=\dfrac{𝒅}{𝒅𝒙}\Big[𝓮^{𝒙\ln 𝒂}\Big]$
               $\rule{0pt}{}$
               ■ $=𝓮^{𝒙\ln 𝒂}\cdot \dfrac{𝒅}{𝒅𝒙}\Big[𝒙\ln 𝒂\Big]$
               $\rule{0pt}{}$
          ○ Differentiate the exponent:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}\Big[𝒙\ln 𝒂\Big]=\ln 𝒂$
               $\rule{0pt}{}$
     ◉ Final result.
          ○ Substitute back:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}\Big[𝒂^{𝒙}\Big]=(\ln 𝒂)\,𝓮^{𝒙\ln 𝒂}$
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}\Big[𝒂^{𝒙}\Big]=(\ln 𝒂)\,𝒂^{𝒙}$
               $\rule{0pt}{}$

● [6:00](https://www.youtube.com/watch?v=rR8imSHCuFk&t=360). 🧩 Example – Differentiate an exponential function with base different from 𝓮: $𝒚=3^{𝒙}$ [📷image](../img/Calculus 2 Lecture 6.4/[6-00]-02.png)
     ◉ Apply the general derivative formula.
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\Big[𝒂^{𝒙}\Big]=(\ln 𝒂)\,𝒂^{𝒙}$
          $\rule{0pt}{}$
     ◉ Example with base 3.
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\Big[3^{𝒙}\Big]=(\ln 3)\cdot 3^{𝒙}$

● [12:52](https://www.youtube.com/watch?v=rR8imSHCuFk&t=772). 🧩 Example – Differentiate an exponential function with base different from 𝓮: $𝒚=5^{\sqrt[3]{𝒙}}$  [📷image](../img/Calculus 2 Lecture 6.4/[12-52]-01.png)
     ◉ Apply the derivative rule for $𝒂^{𝒖}$:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\Big[𝒂^{𝒖}\Big]=(\ln 𝒂)\,𝒂^{𝒖}\cdot \dfrac{𝒅𝒖}{𝒅𝒙}$
          $\rule{0pt}{}$
     ◉ Identify the inner function:
     $\rule{0pt}{}$
          ○ $𝒖=\sqrt[3]{𝒙}=𝒙^{1/3}$
          $\rule{0pt}{}$
     ◉ Differentiate the inner function:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\Big[𝒙^{1/3}\Big]=\dfrac{1}{3}\,𝒙^{-2/3}$
          $\rule{0pt}{}$
     ◉ Combine all factors:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\Big[5^{\sqrt[3]{𝒙}}\Big]=(\ln 5)\cdot 5^{\sqrt[3]{𝒙}}\cdot \dfrac{1}{3}\,𝒙^{-2/3}$
          $\rule{0pt}{}$
     ◉ Final simplified form:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\Big[5^{\sqrt[3]{𝒙}}\Big]=(\ln 5)\cdot \dfrac{5^{\sqrt[3]{𝒙}}}{3\sqrt[3]{𝒙^{2}}}$
           $\rule{0pt}{}$

● [16:45](https://www.youtube.com/watch?v=rR8imSHCuFk&t=1005). 🧩 Example – Differentiate an exponential function with base different from 𝓮: $𝒚=7^{\tan(2𝒙)}$ [📷image](../img/Calculus 2 Lecture 6.4/[16-45]-01.png)
     ◉ Given function:
     $\rule{0pt}{}$
          ○ $𝒚=7^{\tan(2𝒙)}$
     ◉ Apply the derivative rule for 𝒂^{𝒖}:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\Big[𝒂^{𝒖}\Big]=(\ln 𝒂)\,𝒂^{𝒖}\cdot \dfrac{𝒅𝒖}{𝒅𝒙}$
          $\rule{0pt}{}$
     ◉ Identify the inner function:
          ○ $𝒖=\tan(2𝒙)$
     ◉ Differentiate the inner function (chain rule):
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\Big[\tan(2𝒙)\Big]=\sec^{2}(2𝒙)\cdot \dfrac{𝒅}{𝒅𝒙}\Big[2𝒙\Big]$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\Big[\tan(2𝒙)\Big]=2\sec^{2}(2𝒙)$
          $\rule{0pt}{}$
     ◉ Combine all factors:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\Big[7^{\tan(2𝒙)}\Big]=(\ln 7)\cdot 7^{\tan(2𝒙)}\cdot 2\sec^{2}(2𝒙)$
          $\rule{0pt}{}$
     ◉ Final result:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\Big[7^{\tan(2𝒙)}\Big]=2(\ln 7)\cdot 7^{\tan(2𝒙)}\cdot \sec^{2}(2𝒙)$


● [20:35](https://www.youtube.com/watch?v=rR8imSHCuFk&t=1235). 🧩 Example – Differentiate a product involving an exponential function:  $𝒚=𝒙^{𝓮}\cdot 𝓮^{𝒙}$ [📷image](../img/Calculus 2 Lecture 6.4/[20-35]-01.png)
     ◉ Apply the product rule:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}[𝒖\cdot 𝒗]=𝒖'\cdot 𝒗+𝒖\cdot 𝒗'$
          $\rule{0pt}{}$
     ◉ Identify each factor:
          ○ $𝒖=𝒙^{𝓮}$
          ○ $𝒗=𝓮^{𝒙}$
     ◉ Differentiate each factor:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\Big[𝒙^{𝓮}\Big]=𝓮\cdot 𝒙^{𝓮-1}$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\Big[𝓮^{𝒙}\Big]=𝓮^{𝒙}$
          $\rule{0pt}{}$
     ◉ Substitute into the product rule:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=(𝓮\cdot 𝒙^{𝓮-1})\cdot 𝓮^{𝒙}+𝒙^{𝓮}\cdot 𝓮^{𝒙}$
          $\rule{0pt}{}$
     ◉ Factor the common exponential term:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=𝓮^{𝒙}\big(𝓮\cdot 𝒙^{𝓮-1}+𝒙^{𝓮}\big)$
          

● [24:13](https://www.youtube.com/watch?v=rR8imSHCuFk&t=1453). 🧩 Example – Differentiate a quotient involving exponential functions with different bases: $𝒚=\dfrac{2^{𝒙}}{\sqrt{3^{𝒙}+1}}$  [📷image](../img/Calculus 2 Lecture 6.4/[24-13]-01.png)
     ◉ Rewrite the denominator using exponents:
     $\rule{0pt}{}$
          ○ $\sqrt{3^{𝒙}+1}=(3^{𝒙}+1)^{1/2}$
          $\rule{0pt}{}$
     ◉ Rewrite the function in exponent form:
     $\rule{0pt}{}$
          ○ $𝒚=2^{𝒙}\cdot (3^{𝒙}+1)^{-1/2}$
          $\rule{0pt}{}$
     ◉ Apply the product rule:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}[𝒖\cdot 𝒗]=𝒖'\cdot 𝒗+𝒖\cdot 𝒗'$
          $\rule{0pt}{}$
     ◉ Identify each factor:
          ○ $𝒖=2^{𝒙}$
          ○ $𝒗=(3^{𝒙}+1)^{-1/2}$
     ◉ Differentiate each factor:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\Big[2^{𝒙}\Big]=(\ln 2)\cdot 2^{𝒙}$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\Big[(3^{𝒙}+1)^{-1/2}\Big]$
          $\rule{0pt}{}$
               ■ $=-\dfrac{1}{2}(3^{𝒙}+1)^{-3/2}\cdot \dfrac{𝒅}{𝒅𝒙}\Big[3^{𝒙}\Big]$
               $\rule{0pt}{}$
               ■ $=-\dfrac{1}{2}(3^{𝒙}+1)^{-3/2}\cdot (\ln 3)\cdot 3^{𝒙}$
               $\rule{0pt}{}$
     ◉ Substitute into the product rule:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=$  $(\ln 2)\cdot 2^{𝒙}(3^{𝒙}+1)^{-1/2}$  $- 2^{𝒙}\cdot \dfrac{1}{2}(\ln 3)\cdot 3^{𝒙}(3^{𝒙}+1)^{-3/2}$
          $\rule{0pt}{}$
     ◉ Factor common terms:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=2^{𝒙}(3^{𝒙}+1)^{-3/2}$ $\cdot$ $\Big[(\ln 2)(3^{𝒙}+1)-\dfrac{1}{2}(\ln 3)\cdot 3^{𝒙}\Big]$



● [24:53](https://www.youtube.com/watch?v=rR8imSHCuFk&t=1493). 🧩 Example – Differentiate a product involving a general exponential function:  $𝒚=𝒙\cdot 5^{3𝒙}$ [📷image](../img/Calculus 2 Lecture 6.4/[24-53]-01.png)
     ◉ Apply the product rule:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}[𝒖\cdot 𝒗]=𝒖'\cdot 𝒗+𝒖\cdot 𝒗'$
          $\rule{0pt}{}$
     ◉ Identify each factor:
          ○ $𝒖=𝒙$
          ○ $𝒗=5^{3𝒙}$
     ◉ Differentiate each factor:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}[𝒙]=1$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\Big[5^{3𝒙}\Big]=(\ln 5)\cdot 5^{3𝒙}\cdot 3$
          $\rule{0pt}{}$
     ◉ Substitute into the product rule:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=5^{3𝒙}+𝒙\cdot (\ln 5)\cdot 5^{3𝒙}\cdot 3$
          $\rule{0pt}{}$
     ◉ Simplify the expression:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=5^{3𝒙}+3𝒙(\ln 5)5^{3𝒙}$
          $\rule{0pt}{}$
     ◉ Factor the common exponential term:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=5^{3𝒙}\big(1+3𝒙\ln 5\big)$


● [28:25](https://www.youtube.com/watch?v=rR8imSHCuFk&t=1705). 🧩 Example – Logarithmic differentiation for a variable base and exponent: 𝒚 = $𝒙^{𝒙}$ [📷image](../img/Calculus 2 Lecture 6.4/[28-25]-01.png)
     ◉ **Logarithmic differentiation for a variable base and exponent:** [📷image](../img/Calculus 2 Lecture 6.4/[28-25]-02.png)
          ○ Use this technique when the function has the form $𝒚=(𝒇(𝒙))^{𝒈(𝒙)}$, where both the base and the exponent depend on 𝒙.
          ○ Idea: take natural logarithms to simplify exponents into products, which are easier to differentiate.
          $\rule{0pt}{}$
               ■ $\ln(𝒚)=\ln\Big((𝒇(𝒙))^{𝒈(𝒙)}\Big)=𝒈(𝒙)\cdot \ln\big(𝒇(𝒙)\big)$
               $\rule{0pt}{}$
          ○ Differentiate both sides with respect to 𝒙 using implicit differentiation.
          ○ This method avoids complicated applications of the chain and product rules directly on the original expression.
          $\rule{0pt}{}$
          ○ Especially useful for expressions like $𝒙^{𝒙}$, $(\sin 𝒙)^{𝒙}$, or $(𝒙^{2}+1)^{\sqrt{𝒙}}$.
     ◉ Take natural logarithms on both sides:
          ○ $\ln(𝒚)=\ln(𝒙^{𝒙})$
     ◉ Use the power rule for logarithms:
          ○ $\ln(𝒚)=𝒙\ln(𝒙)$
     ◉ Differentiate both sides with respect to 𝒙:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[\ln(𝒚)\big]=\dfrac{𝒅}{𝒅𝒙}\big[𝒙\ln(𝒙)\big]$
          $\rule{0pt}{}$
     ◉ Apply implicit differentiation on the left:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{𝒚}\cdot \dfrac{𝒅𝒚}{𝒅𝒙}=\dfrac{𝒅}{𝒅𝒙}[𝒙]\cdot \ln(𝒙)+𝒙\cdot \dfrac{𝒅}{𝒅𝒙}\big[\ln(𝒙)\big]$
          $\rule{0pt}{}$
     ◉ Compute each derivative:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{𝒚}\cdot \dfrac{𝒅𝒚}{𝒅𝒙}=\ln(𝒙)+𝒙\cdot \dfrac{1}{𝒙}$
          $\rule{0pt}{}$
     ◉ Simplify:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{𝒚}\cdot \dfrac{𝒅𝒚}{𝒅𝒙}=\ln(𝒙)+1$
          $\rule{0pt}{}$
     ◉ Multiply both sides by 𝒚:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=(\ln(𝒙)+1)\cdot 𝒚$
          $\rule{0pt}{}$
     ◉ Substitute back 𝒚 = $𝒙^{𝒙}$:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=(\ln(𝒙)+1)\cdot 𝒙^{𝒙}$


● [35:40](https://www.youtube.com/watch?v=rR8imSHCuFk&t=2140). 🧩 Example – Logarithmic differentiation for a variable base and exponent: $𝒚 = (𝒙² + 𝒙)^{√𝒙}$. [📷image](../img/Calculus 2 Lecture 6.4/[35-40]-01.png)
     ◉ Take natural logarithms:
     $\rule{0pt}{}$
          ○ $\ln(𝒚)=\ln\Big((𝒙^{2}+𝒙)^{\sqrt{𝒙}}\Big)$
          $\rule{0pt}{}$
          ○ $\ln(𝒚)=\sqrt{𝒙}\cdot \ln(𝒙^{2}+𝒙)$
          $\rule{0pt}{}$
     ◉ Differentiate both sides with respect to 𝒙:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[\ln(𝒚)\big]=\dfrac{𝒅}{𝒅𝒙}\big[\sqrt{𝒙}\cdot \ln(𝒙^{2}+𝒙)\big]$
          $\rule{0pt}{}$
     ◉ Implicit differentiation on the left:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{𝒚}\cdot \dfrac{𝒅𝒚}{𝒅𝒙}=\dfrac{𝒅}{𝒅𝒙}\big[\sqrt{𝒙}\big]\cdot \ln(𝒙^{2}+𝒙)+\sqrt{𝒙}\cdot \dfrac{𝒅}{𝒅𝒙}\big[\ln(𝒙^{2}+𝒙)\big]$
          $\rule{0pt}{}$
     ◉ Compute each derivative:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[\sqrt{𝒙}\big]=\dfrac{1}{2\sqrt{𝒙}}$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[\ln(𝒙^{2}+𝒙)\big]=\dfrac{1}{𝒙^{2}+𝒙}\cdot \dfrac{𝒅}{𝒅𝒙}\big[𝒙^{2}+𝒙\big]$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[𝒙^{2}+𝒙\big]=2𝒙+1$
          $\rule{0pt}{}$
     ◉ Substitute and simplify:
     $\rule{0pt}{}$
          ○ $\dfrac{1}{𝒚}\cdot \dfrac{𝒅𝒚}{𝒅𝒙}=\dfrac{\ln(𝒙^{2}+𝒙)}{2\sqrt{𝒙}}+\sqrt{𝒙}\dfrac{2𝒙+1}{𝒙^{2}+𝒙}$
          $\rule{0pt}{}$
     ◉ Solve for 𝒅𝒚/𝒅𝒙:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=\Big[\dfrac{\ln(𝒙^{2}+𝒙)}{2\sqrt{𝒙}}+\sqrt{𝒙}\dfrac{2𝒙+1}{𝒙^{2}+𝒙}\Big]\cdot 𝒚$
          $\rule{0pt}{}$
     ◉ Substitute back $𝒚 = (𝒙² + 𝒙)^{√𝒙}$:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=\Big[\dfrac{\ln(𝒙^{2}+𝒙)}{2\sqrt{𝒙}}+\sqrt{𝒙}\dfrac{2𝒙+1}{𝒙^{2}+𝒙}\Big]\cdot (𝒙^{2}+𝒙)^{\sqrt{𝒙}}$
          $\rule{0pt}{}$


● [1:00:24](https://www.youtube.com/watch?v=rR8imSHCuFk&t=3624). 🧩 Example – Differentiation using the chain rule (not logarithmic differentiation): $𝒚=(𝒙+\cos 𝒙)^{\sqrt{2}}$ [📷image](../img/Calculus 2 Lecture 6.4/[1-00-24]-01.png)
     ◉ Apply the power rule combined with the chain rule:
          ○ Outer function: $𝒖^{\sqrt{2}}$
          ○ Inner function: $𝒖=𝒙+\cos 𝒙$
     ◉ Differentiate step by step:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}[𝒚]=\sqrt{2}\cdot (𝒙+\cos 𝒙)^{\sqrt{2}-1}\cdot \dfrac{𝒅}{𝒅𝒙}(𝒙+\cos 𝒙)$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}(𝒙+\cos 𝒙)=1-\sin 𝒙$
          $\rule{0pt}{}$
     ◉ Final derivative:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=\sqrt{2}\,(𝒙+\cos 𝒙)^{\sqrt{2}-1}(1-\sin 𝒙)$





Ｉｎｔｅｇｒａｌ ｏｆ ａｎ ｅｘｐｏｎｅｎｔｉａｌ ｆｕｎｃｔｉｏｎ

● [45:25](https://www.youtube.com/watch?v=rR8imSHCuFk&t=2725). Integral of an exponential function. [📷image](../img/Calculus 2 Lecture 6.4/[45-25]-01.png)
     ◉ General antiderivative of a constant base exponential:
     $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒂^{𝒖}\,𝒅𝒖=\dfrac{𝒂^{𝒖}}{\ln(𝒂)}+𝓒$,   for $𝒂>0$, $𝒂\ne 1$.
          $\rule{0pt}{}$
     ◉ Special case: natural exponential function:
     $\rule{0pt}{}$
          ○ $\displaystyle \int 𝓮^{𝒖}\,𝒅𝒖=\dfrac{𝓮^{𝒖}}{\ln(𝓮)}+𝓒=𝓮^{𝒖}+𝓒$,   since $\ln(𝓮)=1$.
$\rule{0pt}{}$

● [46:50](https://www.youtube.com/watch?v=rR8imSHCuFk&t=2810). 🧩 Example – Definite integral of an exponential function with base different from 𝓮:  $\displaystyle \int_{0}^{4}3^{𝒙}\,𝒅𝒙$ [📷image](../img/Calculus 2 Lecture 6.4/[46-50]-01.png)
     ◉ Apply the general antiderivative formula:
     $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒂^{𝒙}\,𝒅𝒙=\dfrac{𝒂^{𝒙}}{\ln(𝒂)}$
          $\rule{0pt}{}$
     ◉ Evaluate on the interval [0, 4]:
     $\rule{0pt}{}$
          ○ $\Big[\dfrac{3^{𝒙}}{\ln(3)}\Big]_{0}^{4}$
          $\rule{0pt}{}$
          ○ $=\dfrac{3^{4}-3^{0}}{\ln(3)}$
          $\rule{0pt}{}$
     ◉ Final result:
     $\rule{0pt}{}$
          ○ $=\dfrac{80}{\ln(3)}$


● [49:45](https://www.youtube.com/watch?v=rR8imSHCuFk&t=2985). 🧩 Example – Definite integral using substitution: $\displaystyle \int_{1}^{4}\dfrac{3^{\sqrt{𝒙}}}{\sqrt{𝒙}}\,𝒅𝒙$ [📷image](../img/Calculus 2 Lecture 6.4/[49-45]-01.png)
     ◉ Choose the substitution:
          ○ Let $𝒖=\sqrt{𝒙}$
               ■ $𝒖=𝒙^{1/2}$
               ■ $𝒅𝒖=\dfrac{1}{2\sqrt{𝒙}}\,𝒅𝒙$
               ■ $2\,𝒅𝒖=\dfrac{1}{\sqrt{𝒙}}\,𝒅𝒙$
     ◉ Change the limits of integration:
          ○ When $𝒙=1$  ⇒  $𝒖=1$
          ○ When $𝒙=4$  ⇒  $𝒖=2$
     ◉ Rewrite the integral in terms of 𝒖:
     $\rule{0pt}{}$
          ○ $\displaystyle \int_{1}^{2}3^{𝒖}\cdot 2\,𝒅𝒖$
          $\rule{0pt}{}$
          ○ $=2\displaystyle \int_{1}^{2}3^{𝒖}\,𝒅𝒖$
          $\rule{0pt}{}$
     ◉ Evaluate the integral:
     $\rule{0pt}{}$
          ○ $2\Big[\dfrac{3^{𝒖}}{\ln(3)}\Big]_{1}^{2}$
          $\rule{0pt}{}$
          ○ $=2\Big(\dfrac{3^{2}}{\ln(3)}-\dfrac{3^{1}}{\ln(3)}\Big)$
          $\rule{0pt}{}$
     ◉ Final result:
     $\rule{0pt}{}$
          ○ $=2\cdot \dfrac{9-3}{\ln(3)}$
          $\rule{0pt}{}$
          ○ $=\dfrac{12}{\ln(3)}$


● [57:20](https://www.youtube.com/watch?v=rR8imSHCuFk&t=3440). 🧩 Examples – 𝒖-substitution. [📷image](../img/Calculus 2 Lecture 6.4/[57-20]-01.png)
     ◉ Example 1 – Substitution in an exponential with a quadratic exponent:
          ○ Original integral:
          $\rule{0pt}{}$
               ■ $\displaystyle \int (𝒙+1)\cdot 3^{𝒙^{2}+2𝒙}\,𝒅𝒙$
               $\rule{0pt}{}$
          ○ Choose the substitution:
               ■ Let $𝒖=𝒙^{2}+2𝒙$
               ■ $𝒅𝒖=(2𝒙+2)\,𝒅𝒙=2(𝒙+1)\,𝒅𝒙$
          ○ Rewrite the integral:
          $\rule{0pt}{}$
               ■ $\dfrac{1}{2}\displaystyle \int 3^{𝒖}\,𝒅𝒖$
               $\rule{0pt}{}$
          ○ Integrate:
          $\rule{0pt}{}$
               ■ $\dfrac{1}{2}\cdot \dfrac{3^{𝒖}}{\ln(3)}+𝓒$
               $\rule{0pt}{}$
          ○ Back-substitution:
          $\rule{0pt}{}$
               ■ $=\dfrac{3^{𝒙^{2}+2𝒙}}{2\ln 3}+𝓒$
               $\rule{0pt}{}$
     ◉ Example 2 – Substitution in a rational exponential expression:
          ○ Original integral:
          $\rule{0pt}{}$
               ■ $\displaystyle \int \dfrac{3^{𝒙}}{1+3^{𝒙}}\,𝒅𝒙$
               $\rule{0pt}{}$
          ○ Choose the substitution:
               ■ Let $𝒖=1+3^{𝒙}$
               ■ $𝒅𝒖=(\ln 3)\cdot 3^{𝒙}\,𝒅𝒙$
          ○ Rewrite the integral:
          $\rule{0pt}{}$
               ■ $\dfrac{1}{\ln 3}\displaystyle \int \dfrac{1}{𝒖}\,𝒅𝒖$
               $\rule{0pt}{}$
          ○ Integrate:
          $\rule{0pt}{}$
               ■ $\dfrac{1}{\ln 3}\ln|𝒖|+𝓒$
               $\rule{0pt}{}$
          ○ Back-substitution:
          $\rule{0pt}{}$
               ■ $=\dfrac{1}{\ln 3}\ln(1+3^{𝒙})+𝓒$






Ｄｅｒｉｖａｔｉｖｅｓ  Lｏｇ  ｂａｓｅ  ' 𝓪 ' 


● [1:02:18](https://www.youtube.com/watch?v=rR8imSHCuFk&t=3738). Derivative of logarithmic functions with base 𝒂. [📷image](../img/Calculus 2 Lecture 6.4/[1-02-18]-01.png)
     ◉ Change of base formula:
     $\rule{0pt}{}$
          ○ $\log_{𝒂}|𝒙|=\dfrac{\ln|𝒙|}{\ln 𝒂}$
          $\rule{0pt}{}$
     ◉ Derivative of the logarithm with base 𝒂:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[\log_{𝒂}|𝒙|\big]$
          $\rule{0pt}{}$
               ■ $=\dfrac{𝒅}{𝒅𝒙}\Big[\dfrac{\ln|𝒙|}{\ln 𝒂}\Big]$
               $\rule{0pt}{}$
               ■ $=\dfrac{1}{\ln 𝒂}\cdot \dfrac{𝒅}{𝒅𝒙}\big[\ln|𝒙|\big]$
               $\rule{0pt}{}$
               ■ $=\dfrac{1}{(\ln 𝒂)\cdot 𝒙}$
               $\rule{0pt}{}$
     ◉ Special case: natural logarithm:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}[\ln 𝒙]=\dfrac{1}{𝒙}$


● [1:06:00](https://www.youtube.com/watch?v=rR8imSHCuFk&t=3960). Chain rule derivative of logarithmic functions with base 𝒂. [📷image](../img/Calculus 2 Lecture 6.4/[1-06-00]-01.png)
     ◉ Change of base:
     $\rule{0pt}{}$
          ○ $\log_{𝒂}|𝒖|=\dfrac{\ln|𝒖|}{\ln 𝒂}$
          $\rule{0pt}{}$
     ◉ Derivative using the chain rule:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[\log_{𝒂}|𝒖|\big]$
          $\rule{0pt}{}$
               ■ $=\dfrac{1}{\ln 𝒂}\cdot \dfrac{𝒅}{𝒅𝒙}\big[\ln|𝒖|\big]$
               $\rule{0pt}{}$
               ■ $=\dfrac{1}{\ln 𝒂}\cdot \dfrac{1}{𝒖}\cdot \dfrac{𝒅𝒖}{𝒅𝒙}$
               $\rule{0pt}{}$
               ■ $=\dfrac{1}{(\ln 𝒂)\cdot 𝒖}\cdot \dfrac{𝒅𝒖}{𝒅𝒙}$
               $\rule{0pt}{}$

● [1:08:19](https://www.youtube.com/watch?v=rR8imSHCuFk&t=4099). 🧩 Example – Chain rule derivative of a logarithmic function with base 2: $𝒚=\log_{2}\lvert\tan 𝒙\rvert$ [📷image](../img/Calculus 2 Lecture 6.4/[1-08-19]-01.png)
     ◉ Apply change of base:
     $\rule{0pt}{}$
          ○ $𝒚=\dfrac{\ln|\tan 𝒙|}{\ln 2}$
          $\rule{0pt}{}$
     ◉ Differentiate using the chain rule:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=\dfrac{1}{\ln 2}\cdot \dfrac{𝒅}{𝒅𝒙}\big[\ln|\tan 𝒙|\big]$
          $\rule{0pt}{}$
               ■ $=\dfrac{1}{\ln 2}\cdot \dfrac{1}{\tan 𝒙}\cdot \dfrac{𝒅}{𝒅𝒙}\big[\tan 𝒙\big]$
               $\rule{0pt}{}$
               ■ $=\dfrac{\sec^{2}𝒙}{(\ln 2)\cdot \tan 𝒙}$


● [1:11:00](https://www.youtube.com/watch?v=rR8imSHCuFk&t=4260). 🧩 Example – Differentiation of a product involving a logarithmic function (base 10):  $𝒚 = 𝒙² · log(𝓮^{2𝒙} + 1)$  [📷image](../img/Calculus 2 Lecture 6.4/[1-11-00]-01.png)
     ◉ Apply the product rule:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=\dfrac{𝒅}{𝒅𝒙}[𝒙^{2}]\cdot \log(𝓮^{2𝒙}+1)$   $+$   $𝒙^{2}\cdot \dfrac{𝒅}{𝒅𝒙}\big[\log(𝓮^{2𝒙}+1)\big]$
          $\rule{0pt}{}$
     ◉ Differentiate each term:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}[𝒙^{2}]=2𝒙$
          $\rule{0pt}{}$
          ○ $\dfrac{𝒅}{𝒅𝒙}\big[\log(𝓮^{2𝒙}+1)\big]$
          $\rule{0pt}{}$
               ■ $=\dfrac{1}{\ln 10\cdot (𝓮^{2𝒙}+1)}\cdot \dfrac{𝒅}{𝒅𝒙}[𝓮^{2𝒙}+1]$
               $\rule{0pt}{}$
               ■ $=\dfrac{1}{\ln 10\cdot (𝓮^{2𝒙}+1)}\cdot 2𝓮^{2𝒙}$
               $\rule{0pt}{}$
     ◉ Final result:
     $\rule{0pt}{}$
          ○ $\dfrac{𝒅𝒚}{𝒅𝒙}=2𝒙\cdot \log(𝓮^{2𝒙}+1)+\dfrac{2𝒙^{2}𝓮^{2𝒙}}{\ln 10\cdot (𝓮^{2𝒙}+1)}$




     
