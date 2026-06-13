-----------------------------------**Ｃａｌｃｕｌｕｓ　２　ｌｅｃｔｕｒｅ　６．１:  Tｈｅ　Nａｔｕｒａｌ　Lｏｇ　Fｕｎｃｔｉｏｎ**---------------------------------





Ｉｎｔｒｏｄｕｃｔｉｏｎ. Ｔｈｅ　ｎａｔｕｒａｌ　ｌｏｇａｒｉｔｈｍ　ｆｕｎｃｔｉｏｎ

● [0:00](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=0). The Natural Logarithm Function (ln) and Its Properties [📷image](../img/Calculus 2 Lecture 6.1/[0-00]-01.png)
     ◉ [0:40](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=40). The natural logarithm of unity
          ○ $\ln(1)=0$
               ■ The base $e$ and exponential notation: $e^{0}=1$
                    ▣ 🧩 Example –: $\log_{2}𝒙=4\rightarrow 2^{4}=𝒙$
     ◉ [2:00](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=120). Product Property (Expansion)
     $\rule{0pt}{}$
          ○ $\ln(𝒙\cdot 𝒚)=\ln 𝒙+\ln 𝒚$
          $\rule{0pt}{}$
     ◉ [3:05](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=185). Quotient Property (Expansion) 
     $\rule{0pt}{}$
          ○ $\ln\left(\dfrac{𝒙}{𝒚}\right)=\ln 𝒙-\ln 𝒚$
          $\rule{0pt}{}$
     ◉ [3:40](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=220). Power Property
          ○ $\ln(𝒙^{r})=r\cdot \ln 𝒙$



● [4:20](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=260). Practice: Expansion and Combination of Logarithms
$\rule{0pt}{}$
     ◉ [4:30](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=270). 🧩 Example – Expansion: $\ln\left(\dfrac{3𝒙^{4}}{2𝒚^{2}}\right)$ [📷image](../img/Calculus 2 Lecture 6.1/[4-30]-01.png)
         $\rule{0pt}{}$
          ○ Initial application of the Quotient Rule (subtraction)
          $\rule{0pt}{}$
               ■ $\ln(3𝒙^{4})-\ln(2𝒚^{2})$
               $\rule{0pt}{}$
          ○ $\ln 3+\ln(𝒙^{4})-[\ln 2+\ln(𝒚^{2})]$ Product Property 
          $\rule{0pt}{}$
          ○ $\ln 3+4\ln 𝒙-\ln 2-2\ln 𝒚$ Power Property
               ■ Caution: the exponent only affects its immediate argument
               $\rule{0pt}{}$
     ◉ [9:00](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=540). 🧩 Example – Expansion: $\ln\left(\dfrac{𝒙^{2}+1}{\sqrt{𝒙}}\right)$ [📷image](../img/Calculus 2 Lecture 6.1/[7-55]-01.png)
          ○ $\ln(𝒙^{2}+1)-\ln\sqrt{𝒙}$
          $\rule{0pt}{}$
          ○ $\ln(𝒙^{2}+1)-\ln\left(𝒙^{1/2}\right)$
          $\rule{0pt}{}$
          ○ $\ln(𝒙^{2}+1)-\dfrac{1}{2}\ln 𝒙$
          $\rule{0pt}{}$
          ○ Restriction: the sum $\ln(𝒙^{2}+1)$ cannot be expanded
          $\rule{0pt}{}$
     ◉ [11:31](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=691). 🧩 Example – Advanced Expansion: $\ln\left(\dfrac{𝒙^{5}\sin^{2}(\pi 𝒙)}{\sqrt[3]{𝒙^{4}+2}}\right)$ [📷image](../img/Calculus 2 Lecture 6.1/[11-31]-01.png)
          ○ $\ln(𝒙^{5}\sin^{2}(\pi 𝒙))-\ln\left((𝒙^{4}+2)^{1/3}\right)$
          $\rule{0pt}{}$
          ○ $\ln(𝒙^{5})+\ln\left(\sin^{2}(\pi 𝒙)\right)-\ln\left((𝒙^{4}+2)^{1/3}\right)$
          $\rule{0pt}{}$
          ○ $5\ln 𝒙+2\ln(\sin(\pi 𝒙))-\dfrac{1}{3}\ln(𝒙^{4}+2)$
     ◉ [17:25](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=1045). 🧩 Example – Logarithm Combination (Reverse Process): $\dfrac{2}{3}\big[5\ln 𝒙+\dfrac{1}{2}\ln(𝒙^{2}+1)-4\ln(𝒙-2)\big]$ [📷image](../img/Calculus 2 Lecture 6.1/[17-25]-01.png)
          ○ Rule: move coefficients to exponents first:
          $\rule{0pt}{}$
               ■ $\dfrac{2}{3}\big[\ln(𝒙^{5})+\ln\left((𝒙^{2}+1)^{1/2}\right)-\ln\left((𝒙-2)^{4}\right)\big]$
               $\rule{0pt}{}$
          ○ Unify all terms into a single ln:
          $\rule{0pt}{}$
               ■ $\dfrac{2}{3}\ln\left(\dfrac{𝒙^{5}(𝒙^{2}+1)^{1/2}}{(𝒙-2)^{4}}\right)$
               $\rule{0pt}{}$
          ○ Apply the external coefficient ($\dfrac{2}{3}$) as a final exponent:
          $\rule{0pt}{}$
               ■ $\ln\left[\dfrac{𝒙^{5}(𝒙^{2}+1)^{1/2}}{(𝒙-2)^{4}}\right]^{2/3}$





Ｇｒａｐｈｉｃａｌ　ｒｅｖｉｅｗ　ａｎｄ　ｔｈｅｏｒｅｔｉｃａｌ　ｂａｓｉｓ　ｆｏｒ　ｉｎｔｅｇｒａｌｓ  ａｎｄ　ｄｅｒｉｖａｔｉｖｅｓ

● [22:45](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=1365). Graphical Review [📷image](../img/Calculus 2 Lecture 6.1/[22-45]-01.png)
     ◉ Graph of $\ln 𝒙$ as the inverse function of $e^{𝒙}$
          ○ Domain restrictions: $\ln(0)$ and $\ln(\text{negative})$ are undefined

          
● [28:30](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=1710). Integral Review (Antiderivatives) [📷image-1](../img/Calculus 2 Lecture 6.1/[28-30]-01.png) [📷image-2](../img/Calculus 2 Lecture 6.1/[28-30]-02.png) 
    $\rule{0pt}{}$
     ◉ 🧩 Example – Power Rule $\displaystyle \int 𝒙^{n}\,d𝒙=\dfrac{𝒙^{n+1}}{n+1}+\mathcal{C}$: $\displaystyle \int 𝒙^{3}\,d𝒙$
          ○ $\displaystyle \int 𝒙^{3}\,d𝒙=\dfrac{𝒙^{4}}{4}+\mathcal{C}$ 
          $\rule{0pt}{}$
               ■ Remember $\mathcal{C}$ as a family of curves
     ◉ [30:20](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=1820). 🧩 Example –  Property of pulling constants outside the integral:  $\displaystyle \int 4𝒙^{5}\,d𝒙$  
     $\rule{0pt}{}$
          ○ $\displaystyle \int 4𝒙^{5}\,d𝒙=4\int 𝒙^{5}\,d𝒙=\dfrac{4𝒙^{6}}{6}$ 
          $\rule{0pt}{}$
          ○ Algebraic simplification for single-term quotients
          $\rule{0pt}{}$
               ■ $\dfrac{2𝒙^{6}}{3}+\mathcal{C}$ 
               $\rule{0pt}{}$
     ◉ [30:20](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=1820). 🧩 Example –: $\displaystyle \int \sin 𝒙\,d𝒙$
          ○ $\displaystyle \int \sin 𝒙\,d𝒙=-\cos 𝒙+\mathcal{C}$
     ◉ [32:30](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=1950). 🧩 Example – Definite integral with rational function:  $\displaystyle \int_{1}^{2}\dfrac{𝒙^{4}-1}{𝒙^{2}}\,d𝒙$
          ○ ⚠️ Why substitution is NOT appropriate here
               ■ The derivative of the denominator ($𝒙^{2}\rightarrow 2𝒙$) does not appear as a factor in the numerator
               ■ No visible composition $u(𝒙)/u'(𝒙)$ structure
               ■ The correct strategy is algebraic simplification, not substitution
          ○ Algebraic simplification of the integrand
               ■ Rewrite as powers: $𝒙^{2}-𝒙^{-2}$
          ○ Direct integration term by term
          $\rule{0pt}{}$
               ■ Antiderivative: $\dfrac{𝒙^{3}}{3}+\dfrac{1}{𝒙}$
               $\rule{0pt}{}$
          ○ Evaluation on $[1,2]$
          $\rule{0pt}{}$
               ■ Numerical result: $\dfrac{11}{6}$
               $\rule{0pt}{}$
     ◉ [37:25](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=2245). 🧩 Example – The Critical Case: $\displaystyle \int \dfrac{1}{𝒙}\,d𝒙$ [📷image-1](../img/Calculus 2 Lecture 6.1/[37-25]-01.png) [📷image-2](../img/Calculus 2 Lecture 6.1/[37-25]-02.png)
          ○ To approximate the problem, think about the graph of $𝒚=\dfrac{1}{𝓉}$
          $\rule{0pt}{}$
               ■ It is continuous and differentiable everywhere on $(0,\infty)$. 
                    ▣ The Fundamental Theorem of Calculus (FTC),  𝒫𝒜𝑅𝒯  Ⅰ 
                         ▢ Derivatives and integrals as inverse operations
                         ▢ Defining the area function $\mathcal{A}(𝒙)$ as the integral of $𝒇(𝓉)$ from $a$ to $𝒙$
                         ▢ Statement of  FTC  𝒫𝒜𝑅𝒯  Ⅰ :
                            $\rule{0pt}{}$
                               I̲f̲       $𝒚=𝒇(𝒙)$ 𝘪𝘴 𝘤𝘰𝘯𝘵𝘪𝘯𝘶𝘰𝘶𝘴 𝘰𝘷𝘦𝘳 $[𝓪,𝒙]$,  
                              t̲h̲e̲n̲   𝘵𝘩𝘦 𝘢𝘳𝘦𝘢 𝘪𝘴:  $\mathcal{A}(𝒙)$ 𝘴𝘶𝘤𝘩 𝘵𝘩𝘢𝘵 $\mathcal{A}'(𝒙)=𝒇(𝒙)$  
                                    $\mathcal{A}(𝒙)=\displaystyle \int_{𝓪}^{𝒙}𝒇(𝓉)\,d𝓉$
                            $\rule{0pt}{}$
          ○ What that means by the The Fundamental Theorem of Calculus 𝒫𝒜𝑅𝒯  Ⅰ?
               ■ Existence guaranteed by the Fundamental Theorem of Calculus, 𝒫𝒜𝑅𝒯  Ⅰ
               $\rule{0pt}{}$
                    ▣ Because $\dfrac{1}{𝓉}$ is continuous on $(0,\infty)$, by F.T.O.C. I, we must be able to find some differentiable function $\mathcal{F}(𝒙)$ such that:
                    $\rule{0pt}{}$
                         ▢ $\mathcal{F}(𝒙)=\displaystyle \int_{𝓪}^{𝒙}\dfrac{1}{𝓉}\,d𝓉$
                         $\rule{0pt}{}$
                         ▢ $\mathcal{F}'(𝒙)=\dfrac{d}{d𝒙}\displaystyle \int_{𝓪}^{𝒙}\dfrac{1}{𝓉}\,d𝓉=\dfrac{1}{𝒙}=𝒇(𝒙)$ 
                         $\rule{0pt}{}$
                         ▢ It turns out that this specific antiderivative $\mathcal{F}(𝒙)$ corresponds to the natural logarithm.
                         $\rule{0pt}{}$
                              ▲ $\ln 𝒙=\displaystyle \int_{1}^{𝒙}\dfrac{1}{𝓉}\,d𝓉$
                              $\rule{0pt}{}$
                                   ◭ $\dfrac{d}{d𝒙}[\ln 𝒙]=\dfrac{d}{d𝒙}\displaystyle \int_{1}^{𝒙}\dfrac{1}{𝓉}\,d𝓉=\dfrac{1}{𝒙}$
                                   $\rule{0pt}{}$
                              ▲ The family $\ln 𝒙+\mathcal{C}$ represents vertical shifts of the same curve. Imposing $\ln 1=0$ selects the curve with zero vertical shift, corresponding to $C=0$.
                              $\rule{0pt}{}$
     ◉ [46:20](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=2780). The role of the absolute value in $\displaystyle \int_{1}^{𝒙}\dfrac{1}{𝒙}\,d𝒙$ [📷image](../img/Calculus 2 Lecture 6.1/[46-20]-01.png)
          ○ Indefinite integral
               ■ Fundamental reason
                    ▣ The natural logarithm is defined only for positive arguments
                    ▣ $\ln(𝓪)$ exists only if $𝓪>0$
                    $\rule{0pt}{}$
               ■ Issue when integrating $\dfrac{1}{𝒙}$
               $\rule{0pt}{}$
                    ▣ The function $\dfrac{1}{𝒙}$ exists for $𝒙>0$ and for $𝒙<0$
                    $\rule{0pt}{}$
                    ▣ Writing $\ln 𝒙+\mathcal{C}$ would cover only the interval $𝒙>0$
               ■ Correct antiderivative
                    ▣ Using $\ln|𝒙|$ ensures a positive logarithmic argument
                    ▣ If $𝒙>0$, then $|𝒙|=𝒙$
                    ▣ If $𝒙<0$, then $|𝒙|=-𝒙>0$
               ■ Conclusion: The absolute value guarantees a valid expression over the entire domain where $\dfrac{1}{𝒙}$ exists
          ○ Definite integral
               ■ Setup of the definite integral
               $\rule{0pt}{}$
                    ▣ $\displaystyle \int_{𝓪}^{𝓫}\dfrac{1}{𝒙}\,d𝒙=\ln\big[|𝒙|\big]$ evaluated from $𝓪$ to $𝓫$ 
                    $\rule{0pt}{}$
                         ▢ On an interval not crossing $0$, $|\,|$ can be removed consistently.
               ■ Why the absolute value disappears
                    ▣ The limits $𝓪$ and $𝓫$ are chosen within a single interval
                    ▣ Either $𝓪>0$ and $𝓫>0$, or $𝓪<0$ and $𝓫<0$
                         ▢ NOTE: If the interval crosses $𝒙=0$ (for example, from $-2$ to $4$), the integral of $\dfrac{1}{𝒙}$ becomes improper (_Improper Integral_).
                                         Even though $\ln|𝒙|$ is a valid antiderivative, the integral must be split at 𝒙 = 0 and evaluated using limits.
                                         In this case, the limits diverge, so the definite integral does not exist.
               ■ Consequence
                    ▣ $\ln|𝒙|$ reduces to ln 𝒙 or ln(−𝒙) consistently on the interval
                    ▣ No sign change occurs inside the interval
               ■ Conclusion:In definite integrals, the absolute value is implicit once the interval is fixed
               
                   

● [49:12](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=2952). Derivatives of Natural Logarithmic Functions 
     ◉ Review of the Chain Rule [📷image](../img/Calculus 2 Lecture 6.1/[49-12]-01.png)  
          $\rule{0pt}{}$
          ○ Formula: $\dfrac{d}{d𝒙}[𝒇(𝓰(𝒙))]=𝒇'(𝓰(𝒙))\cdot 𝓰'(𝒙)$
          $\rule{0pt}{}$
          ○ [51:30](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=3090). $\dfrac{d}{d𝒙}[\ln 𝓰(𝒙)]=\dfrac{1}{𝓰(𝒙)}\cdot 𝓰'(𝒙)$
          $\rule{0pt}{}$
     ◉ [55:00](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=3300). 🧩 Example – Chain Rule: $\dfrac{d}{d𝒙}[\ln(3𝒙^{2}-1)]$ [📷image](../img/Calculus 2 Lecture 6.1/[55-00]-01.png)
          $\rule{0pt}{}$
          ○ $\dfrac{1}{3𝒙^{2}-1}\dfrac{d}{d𝒙}[3𝒙^{2}-1]=\dfrac{6𝒙}{3𝒙^{2}-1}$
          $\rule{0pt}{}$
     ◉ [57:54](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=3474). 🧩 Example – General Power Rule:  $\dfrac{d}{d𝒙}\big[\sqrt[3]{(\ln 𝒙)}\big]$ [📷image](../img/Calculus 2 Lecture 6.1/[57-54]-01.png)
          ○ $\dfrac{d}{d𝒙}\big[(\ln 𝒙)^{1/3}\big]$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{3}\cdot (\ln 𝒙)^{-2/3}\cdot \dfrac{d}{d𝒙}[\ln 𝒙]$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{3}\cdot (\ln 𝒙)^{-2/3}\cdot \dfrac{1}{𝒙}$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{3𝒙\cdot (\ln 𝒙)^{2/3}}$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{3𝒙\cdot \sqrt[3]{(\ln 𝒙)^{2}}}$
          $\rule{0pt}{}$
     ◉ [1:02:17](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=3737).🧩 Example – Chain Rule: $\dfrac{d}{d𝒙}\big[\ln(2𝒙+\sqrt{𝒙^{3}-1})\big]$ [📷image](../img/Calculus 2 Lecture 6.1/[1-02-17]-01.png)
     $\rule{0pt}{}$
          ○ $\dfrac{1}{2𝒙+\sqrt{𝒙^{3}-1}}\cdot \dfrac{d}{d𝒙}\big[2𝒙+(𝒙^{3}-1)^{1/2}\big]$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{2𝒙+\sqrt{𝒙^{3}-1}}\cdot \left(2+\dfrac{1}{2}\cdot (𝒙^{3}-1)^{-1/2}\cdot 3𝒙^{2}\right)$
          $\rule{0pt}{}$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{2𝒙+\sqrt{𝒙^{3}-1}}\cdot \left(2+\dfrac{3𝒙^{2}}{2\sqrt{𝒙^{3}-1}}\right)$
          $\rule{0pt}{}$
     ◉ [1:08:30](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=4110).🧩 Example – General Power Rule: $\dfrac{d}{d𝒙}[𝒙^{3}\ln(5𝒙)]$ [📷image](../img/Calculus 2 Lecture 6.1/[1-08-30]-01.png)
          ○ $\dfrac{d}{d𝒙}[𝒙^{3}]\cdot \ln(5𝒙)+𝒙^{3}\cdot \dfrac{d}{d𝒙}[\ln(5𝒙)]$
          $\rule{0pt}{}$
          ○ $3𝒙^{2}\cdot \ln(5𝒙)+𝒙^{3}\cdot \dfrac{1}{5𝒙}\cdot \dfrac{d}{d𝒙}[5𝒙]$
          $\rule{0pt}{}$
          ○ $3𝒙^{2}\cdot \ln(5𝒙)+𝒙^{3}\cdot \dfrac{1}{5𝒙}\cdot 5$
          $\rule{0pt}{}$
          ○ $3𝒙^{2}\cdot \ln(5𝒙)+𝒙^{2}$ 
          $\rule{0pt}{}$
          ○ $𝒙^{2}\cdot \big(3\ln(5𝒙)+1\big)$
          $\rule{0pt}{}$
     ◉ [1:14:28](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=4468). 🧩 Example – : $\dfrac{d}{d𝒙}[\ln|\cos 𝒙|]$ [📷image](../img/Calculus 2 Lecture 6.1/[1-14-28]-01.png)
          $\rule{0pt}{}$
          ○ The absolute value is required because $\ln()$ is defined only for positive arguments; $|\cos 𝒙|$ ensures the argument is positive (when $\cos 𝒙\neq 0$). 
          $\rule{0pt}{}$
          ○ $\dfrac{1}{\cos 𝒙}\cdot \dfrac{d}{d𝒙}[\cos 𝒙]$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{\cos 𝒙}\cdot (-\sin 𝒙)$
          $\rule{0pt}{}$
          ○ $-\dfrac{\sin 𝒙}{\cos 𝒙}=-\tan 𝒙$
          $\rule{0pt}{}$
     ◉ [1:17:30](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=4650). 🧩 Example – Logarithmic Expansion Before Differentiation: $\dfrac{d}{d𝒙}\left[\ln\left(\dfrac{𝒙^{2}(2𝒙^{2}+1)^{3}}{\sqrt{5-𝒙^{2}}}\right)\right]$ 
          ○ [📷image-1](../img/Calculus 2 Lecture 6.1/[1-17-30]-01.png) 
          ○ [📷image-2](../img/Calculus 2 Lecture 6.1/[1-17-30]-02.png)
          ○ Expanded expression: 
          $\rule{0pt}{}$
               ■ $\dfrac{d}{d𝒙}\big[\ln(𝒙^{2})+\ln((2𝒙^{2}+1)^{3})-\ln(\sqrt{5-𝒙^{2}})\big]$ 
               $\rule{0pt}{}$
               ■ $\dfrac{d}{d𝒙}\left[2\ln 𝒙+3\ln(2𝒙^{2}+1)-\dfrac{1}{2}\ln(5-𝒙^{2})\right]$
               $\rule{0pt}{}$
          ○ Term-by-term differentiation
          $\rule{0pt}{}$
               ■ $2\cdot \left(\dfrac{1}{𝒙}\right)+3\cdot \left(\dfrac{1}{2𝒙^{2}+1}\right)\cdot \dfrac{d}{d𝒙}[2𝒙^{2}+1]-\dfrac{1}{2}\cdot \left(\dfrac{1}{5-𝒙^{2}}\right)\cdot \dfrac{d}{d𝒙}[5-𝒙^{2}]$
               $\rule{0pt}{}$
               ■ $\dfrac{2}{𝒙}+3\cdot \left(\dfrac{1}{2𝒙^{2}+1}\right)\cdot (4𝒙)-\dfrac{1}{2}\cdot \left(\dfrac{1}{5-𝒙^{2}}\right)\cdot (-2𝒙)$
               $\rule{0pt}{}$
               ■ $\dfrac{2}{𝒙}+\dfrac{12𝒙}{2𝒙^{2}+1}+\dfrac{𝒙}{5-𝒙^{2}}$




Ｌｏｇａｒｉｔｈｍｉｃ　ａｎｄ　ｉｍｐｌｉｃｉｔ　ｄｉｆｆｅｒｅｎｔｉａｔｉｏｎ

● [1:27:15](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=5235). Logarithmic and Implicit Differentiation [📷image-1](../img/Calculus 2 Lecture 6.1/[1-27-15]-01.png) [📷image-2](../img/Calculus 2 Lecture 6.1/[1-27-15]-02.png)
     ◉ General Procedure
          ○ Expansion of $\ln 𝒚$
          ○ Implicit differentiation
          $\rule{0pt}{}$
               ■ $\dfrac{d}{d𝒙}[\ln 𝒚]=\dfrac{1}{𝒚}\cdot \dfrac{d𝒚}{d𝒙}$
               $\rule{0pt}{}$
                    ▣ Solve for $\dfrac{d𝒚}{d𝒙}$
                    $\rule{0pt}{}$
                    ▣ Substitute the original expression for $𝒚$
     ◉ 🧩 Example – Implicit Differentiation with ln: $y=\dfrac{(x-1)^{4}}{\sqrt[3]{(2x-1)}}$
     $\rule{0pt}{}$
          ○ Apply $\dfrac{d}{d𝒙}$ and solve for $\dfrac{d𝒚}{d𝒙}$
          $\rule{0pt}{}$
          ○ $\ln 𝒚=\ln\left[\dfrac{(𝒙-1)^{4}}{\sqrt[3]{(2𝒙-1)}}\right]$
          $\rule{0pt}{}$
          ○ $\ln 𝒚=4\ln(𝒙-1)-\dfrac{1}{3}\ln(2𝒙-1)$
          $\rule{0pt}{}$
          ○ $\dfrac{d}{d𝒙}[\ln 𝒚]=\dfrac{d}{d𝒙}\left[4\ln(𝒙-1)-\dfrac{1}{3}\ln(2𝒙-1)\right]$
          $\rule{0pt}{}$
          ○ $\left(\dfrac{1}{𝒚}\right)\cdot \dfrac{d𝒚}{d𝒙}=\dfrac{4}{𝒙-1}-\dfrac{1}{3}\cdot \dfrac{1}{2𝒙-1}\cdot 2$
          $\rule{0pt}{}$
          ○ $\left(\dfrac{1}{𝒚}\right)\cdot \dfrac{d𝒚}{d𝒙}=\dfrac{4}{𝒙-1}-\dfrac{2}{3(2𝒙-1)}$
          $\rule{0pt}{}$
          ○ $\dfrac{d𝒚}{d𝒙}=\left[\dfrac{4}{𝒙-1}-\dfrac{2}{3(2𝒙-1)}\right]\cdot 𝒚$
          $\rule{0pt}{}$
          ○ $\dfrac{d𝒚}{d𝒙}=\left[\dfrac{4}{𝒙-1}-\dfrac{2}{3(2𝒙-1)}\right]\cdot \left(\dfrac{(𝒙-1)^{4}}{\sqrt[3]{(2𝒙-1)}}\right)$
          $\rule{0pt}{}$
     ◉ [1:38:40](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=5920). 🧩 Example – Implicit Differentiation with ln: $\ln\left(\dfrac{2𝒙}{𝒚}\right)-\sin 𝒚+𝒙^{2}=0$
          ○ $\dfrac{d}{d𝒙}\big[\ln(2𝒙)-\ln 𝒚-\sin 𝒚+𝒙^{2}\big]=\dfrac{d}{d𝒙}[0]$
          $\rule{0pt}{}$
          ○ $\left(\dfrac{1}{2𝒙}\right)\cdot 2-\left(\dfrac{1}{𝒚}\right)\cdot 𝒚'-\cos 𝒚\cdot 𝒚'+2𝒙=0$
          $\rule{0pt}{}$
          ○ $\left(\dfrac{1}{𝒚}\right)\cdot 𝒚'-\cos 𝒚\cdot 𝒚'=-2𝒙-\dfrac{1}{𝒙}$ 
          $\rule{0pt}{}$
          ○ $𝒚'\left(\dfrac{1}{𝒚}-\cos 𝒚\right)=-2𝒙-\dfrac{1}{𝒙}$
          $\rule{0pt}{}$
          ○ $𝒚'=\dfrac{-2𝒙-\left(\dfrac{1}{𝒙}\right)}{\left(\dfrac{1}{𝒚}\right)-\cos 𝒚}$





Ｉｎｔｅｇｒａｌｓ　ｔｈａｔ　ｒｅｓｕｌｔ　ｉｎ　ｌｎ｜𝒖｜

● [1:43:00](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=6180). Integrals That Result in ln |𝒖| [📷image-1](../img/Calculus 2 Lecture 6.1/[1-43-00]-01.png) [📷image-2](../img/Calculus 2 Lecture 6.1/[1-43-00]-02.png)
     $\rule{0pt}{}$
     ◉ Integration rule: $\displaystyle \int \dfrac{1}{𝒖}\,d𝒖=\ln|𝒖|+\mathcal{C}$
          ○ Use substitution technique to loo like $\displaystyle \int \dfrac{1}{𝒖}\,d𝒖=\ln|𝒖|+\mathcal{C}$
          $\rule{0pt}{}$
     ◉ 🧩 Example –: $\displaystyle \int \dfrac{1}{5𝒙-2}\,d𝒙$
          ○ Substitution:
               ■ $𝒖=5𝒙-2$  
               $\rule{0pt}{}$
               ■ $\dfrac{d𝒖}{d𝒙}=5$  
               $\rule{0pt}{}$
               ■ $d𝒖=5\,d𝒙$  
               $\rule{0pt}{}$
               ■ $d𝒙=\dfrac{d𝒖}{5}$
               $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{1}{𝒖}\cdot \left(\dfrac{d𝒖}{5}\right)$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{5}\displaystyle \int \dfrac{1}{𝒖}\,d𝒖$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{5}\ln|𝒖|+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{5}\ln|5𝒙-2|+\mathcal{C}$
          $\rule{0pt}{}$
     ◉  [1:48:10](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=6490). 🧩 Example – ln into the integral: $\displaystyle \int \dfrac{\sqrt{\ln 𝒙}}{3𝒙}\,d𝒙$
          ○ Substitution:
               ■ $𝒖=\ln 𝒙$
               $\rule{0pt}{}$
               ■ $\dfrac{d𝒖}{d𝒙}=\dfrac{1}{𝒙}$
               $\rule{0pt}{}$
               ■ $d𝒖=\dfrac{1}{𝒙}\,d𝒙$
               $\rule{0pt}{}$
               ■ $d𝒙=𝒙\,d𝒖$
               $\rule{0pt}{}$
          ○ $\displaystyle \int \dfrac{\sqrt{𝒖}}{3𝒙}\cdot (𝒙\,d𝒖)$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{3}\displaystyle \int 𝒖^{1/2}\,d𝒖$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{3}\cdot \left(\dfrac{2}{3}\right)𝒖^{3/2}+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\dfrac{2}{9}𝒖^{3/2}+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\dfrac{2}{9}(\ln 𝒙)^{3/2}+\mathcal{C}$





Ｔｒｉｇｏｎｏｍｅｔｒｉｃ　ｉｎｔｅｇｒａｌｓ　ｉｎｖｏｌｖｉｎｇ　ｌｎ

● [1:54:10](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=6850). Trigonometric Integrals Involving ln 
     ◉ INTEGRALS [📷image](../img/Calculus 2 Lecture 6.1/[1-54-10]-01.png)
          ○ $\displaystyle \int \sin 𝒙\,d𝒙=-\cos 𝒙+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\displaystyle \int \cos 𝒙\,d𝒙=\sin 𝒙+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\displaystyle \int \sec^{2} 𝒙\,d𝒙=\tan 𝒙+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\displaystyle \int \sec 𝒙\tan 𝒙\,d𝒙=\sec 𝒙+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\displaystyle \int \csc 𝒙\cot 𝒙\,d𝒙=-\csc 𝒙+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\displaystyle \int \csc^{2} 𝒙\,d𝒙=-\cot 𝒙+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\displaystyle \int \tan 𝒖\,d𝒖=-\ln|\cos 𝒖|+\mathcal{C}=\ln|\sec 𝒖|+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\displaystyle \int \cot 𝒖\,d𝒖=\ln|\sin 𝒖|+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\displaystyle \int \sec 𝒖\,d𝒖=\ln|\sec 𝒖+\tan 𝒖|+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\displaystyle \int \csc 𝒖\,d𝒖=\ln|\csc 𝒖-\cot 𝒖|+\mathcal{C}$ 
          $\rule{0pt}{}$
               ■ NOTE 1:
                    ▣ The variable $𝒖$ indicates that these formulas are typically used _after a substitution_.
                    ▣ In practice, the integrand is rewritten so that it matches one of these forms.
     ◉ [1:56:30](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=6990). 🧩 Example – : Derivation of $\displaystyle \int \tan 𝒙\,d𝒙$ [📷image](../img/Calculus 2 Lecture 6.1/[1-56-30]-01.png)
          ○ $\displaystyle \int \left(\dfrac{\sin 𝒙}{\cos 𝒙}\right)\,d𝒙$
          $\rule{0pt}{}$
          ○ Substitution:
               ■ $𝒖=\cos 𝒙$  
               ■ $d𝒖=-\sin 𝒙\,d𝒙$  
               $\rule{0pt}{}$
               ■ $d𝒙=\dfrac{d𝒖}{-\sin 𝒙}$
               $\rule{0pt}{}$
          ○ $\displaystyle \int \left(\dfrac{\sin 𝒙}{𝒖}\right)\cdot \left(\dfrac{d𝒖}{-\sin 𝒙}\right)$
          $\rule{0pt}{}$
          ○ $-\displaystyle \int \dfrac{1}{𝒖}\,d𝒖$
          $\rule{0pt}{}$
          ○ $-\ln|𝒖|+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $-\ln|\cos 𝒙|+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\ln|\cos 𝒙|^{-1}+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\ln|\sec 𝒙|+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\displaystyle \int \tan 𝒙\,d𝒙=\ln|\sec 𝒙|+\mathcal{C}$; This expression is an antiderivative of $\tan 𝒙$ on any interval where $\tan 𝒙$ is continuous.
          $\rule{0pt}{}$
          ○ NOTE 2: On $-\ln|\cos 𝒙|$ and $\pi/2$
               ■ The antiderivative of $\tan 𝒙$ can be written as $-\ln|\cos 𝒙|+\mathcal{C}$ or equivalently as $\ln|\sec 𝒙|+\mathcal{C}$.
                   This is a purely algebraic equivalence: $-\ln|\cos 𝒙|=\ln|\cos 𝒙|^{-1}=\ln|\sec 𝒙|$.
               ■ The points $𝒙=\pi/2+k\pi$ are excluded in all cases.
                   At these values, $\cos 𝒙=0$, so $\tan 𝒙$, $\ln|\cos 𝒙|$, and $\ln|\sec 𝒙|$ are all undefined.
                   Therefore, the antiderivative is always understood on intervals where $\tan 𝒙$ is continuous, i.e., between consecutive vertical asymptotes.
     ◉ [2:03:40](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=7420). 🧩 Example – : Derivation of $\displaystyle \int \sec 𝒙\,d𝒙$ [📷image](../img/Calculus 2 Lecture 6.1/[2-03-40]-01.png)
          ○ Algebraic trick to create a substitution
               ■ Multiply by $(\sec 𝒙+\tan 𝒙)/(\sec 𝒙+\tan 𝒙)$
               $\rule{0pt}{}$
               ■ $\displaystyle \int \sec 𝒙\cdot \dfrac{\sec 𝒙+\tan 𝒙}{\sec 𝒙+\tan 𝒙}\,d𝒙$
               $\rule{0pt}{}$
               ■ $\displaystyle \int \dfrac{\sec^{2} 𝒙+\sec 𝒙\tan 𝒙}{\sec 𝒙+\tan 𝒙}\,d𝒙$
               $\rule{0pt}{}$
          ○ Substitution
               ■ $𝒖=\sec 𝒙+\tan 𝒙$
               ■ $d𝒖=(\sec 𝒙\tan 𝒙+\sec^{2} 𝒙)\,d𝒙$
          ○ Reduction to a basic logarithmic integral
          $\rule{0pt}{}$
               ■ $\displaystyle \int \dfrac{1}{𝒖}\,d𝒖$
               $\rule{0pt}{}$
          ○ Final result
               ■ $\ln|\sec 𝒙+\tan 𝒙|+\mathcal{C}$
               $\rule{0pt}{}$
               ■ Formula: $\displaystyle \int \sec 𝒙\,d𝒙=\ln|\sec 𝒙+\tan 𝒙|+C$
               $\rule{0pt}{}$
     ◉ [2:09:05](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=7745). Summary of Trigonometric Formulas with ln [📷image](../img/Calculus 2 Lecture 6.1/[2-09-05]-01.png)
          ○ $\displaystyle \int \tan 𝒖\,d𝒖=-\ln|\cos 𝒖|+\mathcal{C}=\ln|\sec 𝒖|+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\displaystyle \int \cot 𝒖\,d𝒖=\ln|\sin 𝒖|+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\displaystyle \int \sec 𝒖\,d𝒖=\ln|\sec 𝒖+\tan 𝒖|+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\displaystyle \int \csc 𝒖\,d𝒖=\ln|\csc 𝒖-\cot 𝒖|+\mathcal{C}$ 
          $\rule{0pt}{}$
     ◉ [2:13:15](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=7995). 🧩 Example – : $\displaystyle \int 𝒙\sec(𝒙^{2})\,d𝒙$ [📷image](../img/Calculus 2 Lecture 6.1/[2-13-15]-01.png)
          ○ It does not match any direct formula from the table, so we use substitution.
               ■ Substitution:
                    ▣ $𝒖=𝒙^{2}$
                    $\rule{0pt}{}$
                    ▣ $\dfrac{d𝒖}{d𝒙}=2𝒙$
                    $\rule{0pt}{}$
                    ▣ $d𝒖=2𝒙\,d𝒙$
                    $\rule{0pt}{}$
                    ▣ $d𝒙=\dfrac{d𝒖}{2𝒙}$
                    $\rule{0pt}{}$
          ○ $\displaystyle \int 𝒙\sec(𝒙^{2})\,d𝒙=\int 𝒙\sec(𝒖)\cdot \left(\dfrac{d𝒖}{2𝒙}\right)$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{2}\displaystyle \int \sec 𝒖\,d𝒖$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{2}\ln|\sec 𝒖+\tan 𝒖|+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\dfrac{1}{2}\ln|\sec(𝒙^{2})+\tan(𝒙^{2})|+\mathcal{C}$
          $\rule{0pt}{}$
     ◉ [2:16:15](https://www.youtube.com/watch?v=H9eCT6f_Ftw&t=8175). 🧩 Example – : $\displaystyle \int \dfrac{\sin(2𝒙)}{1+\sin^{2} 𝒙}\,d𝒙$ [📷image](../img/Calculus 2 Lecture 6.1/[2-16-15]-01.png)
     $\rule{0pt}{}$
          ○ Use the double-angle identity to reveal the derivative.
               ■ $\sin(2𝒙)=2\sin 𝒙\cos 𝒙$
          ○ Rewrite the integral:
          $\rule{0pt}{}$
               ■ $\displaystyle \int \dfrac{2\sin 𝒙\cos 𝒙}{1+\sin^{2} 𝒙}\,d𝒙$
               $\rule{0pt}{}$
          ○ Substitution:
               ■ $𝒖=1+\sin^{2} 𝒙$
               $\rule{0pt}{}$
               ■ $\dfrac{d𝒖}{d𝒙}=2\sin 𝒙\cos 𝒙$
               $\rule{0pt}{}$
               ■ $d𝒖=2\sin 𝒙\cos 𝒙\,d𝒙$
               $\rule{0pt}{}$
          ○ $\displaystyle \int \left(\dfrac{1}{𝒖}\right)d𝒖$
          $\rule{0pt}{}$
          ○ $\ln|𝒖|+\mathcal{C}$
          $\rule{0pt}{}$
          ○ $\ln|1+\sin^{2} 𝒙|+\mathcal{C}$
          $\rule{0pt}{}$
               ■ NOTE 3: $1+\sin^{2} 𝒙>0$ for all $𝒙$, so the absolute value is optional here.
     ◉ NOTE 4: Trigonometric identities commonly used in substitutions
          ○ These identities are frequently used to rewrite integrals so that a clear substitution appears.
          ○1️⃣ Double-angle formulas  
               ■ Used to expose a derivative factor (very common in substitutions):
                    ▣ $\sin(2𝒙)=2\sin 𝒙\cos 𝒙$  
                    ▣ $\cos(2𝒙)=\cos^{2}𝒙-\sin^{2}𝒙$  
                    ▣ $\cos(2𝒙)=1-2\sin^{2}𝒙$  
                    ▣ $\cos(2𝒙)=2\cos^{2}𝒙-1$
          ○2️⃣ Half-angle formulas  
               ■ Used when the integrand involves squared trigonometric functions:
               $\rule{0pt}{}$
                    ▣ $\sin^{2}𝒙=\dfrac{1-\cos(2𝒙)}{2}$  
                    $\rule{0pt}{}$
                    ▣ $\cos^{2}𝒙=\dfrac{1+\cos(2𝒙)}{2}$  
                    $\rule{0pt}{}$
                    ▣ $\tan^{2}𝒙=\dfrac{1-\cos(2𝒙)}{1+\cos(2𝒙)}$
                    $\rule{0pt}{}$
          ○3️⃣ Pythagorean identities  
               ■ Essential for simplifying expressions and choosing substitutions:
                    ▣ $\sin^{2}𝒙+\cos^{2}𝒙=1$  
                    ▣ $1+\tan^{2}𝒙=\sec^{2}𝒙$  
                    ▣ $1+\cot^{2}𝒙=\csc^{2}𝒙$  
          ○4️⃣ Practical rule of thumb  
               ■ If the numerator looks like the derivative of something in the denominator,  
                  try rewriting it using a trigonometric identity before choosing $𝒖$.
               ■ These identities are not just algebraic tools — they are often the key step that makes a substitution possible.
