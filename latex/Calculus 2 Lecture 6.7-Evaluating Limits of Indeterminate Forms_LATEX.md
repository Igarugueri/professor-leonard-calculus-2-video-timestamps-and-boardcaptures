--------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ６．７ － Ｅｖａｌｕａｔｉｎｇ Ｌｉｍｉｔｓ ｏｆ Ｉｎｄｅｔｅｒｍｉｎａｔｅ Ｆｏｒｍｓ**---------------------------—






Ｉｎｔｒｏｄｕｃｔｉｏｎ  and Ｌ’Ｈôｐｉｔａｌ’ｓ Ｒｕｌｅ

● [📷image-1](../img/Calculus 2 Lecture 6.7/[0-00]-01.png) [📷image-2](../img/Calculus 2 Lecture 6.7/[0-00]-02.png)

● [0:00](https://www.youtube.com/watch?v=Zd7wd24jeok&t=0). Introduction to Section 6.7: Indeterminate Forms of Limits.
     ◉ Concept of indeterminate forms and a simplified first approach.
          ○ Limits as a fundamental idea of calculus and their relation to derivatives.
               ■ A derivative is defined as a limit.
               ■ It represents the limiting value of a slope.
               ■ We let two points get arbitrarily close until the secant slope approaches a single value.
          ○ The origin of the derivative as the limit of a difference quotient.

● [1:32](https://www.youtube.com/watch?v=Zd7wd24jeok&t=92). First indeterminate form: $0/0$.
$\rule{0pt}{}$
     ◉ Evaluating $\displaystyle \lim_{x\to 𝒖}\dfrac{𝒇(𝒙)}{𝓰(𝒙)}$ when both numerator and denominator approach $0$.
     $\rule{0pt}{}$
          ○ If both the numerator and denominator go to $0$, the quotient is not automatically determined.
          ○ The expression must be analyzed more carefully.
     ◉ Proposed analysis: compare the behavior of the derivative ratio $\dfrac{𝒅𝒇}{𝒅𝒙}$ and $\dfrac{𝒅𝓰}{𝒅𝒙}$.
          ○ This leads to the idea behind L’Hôpital’s Rule.


● [3:02](https://www.youtube.com/watch?v=Zd7wd24jeok&t=182). Introduction to L’Hôpital’s Rule.
     ◉ Conceptual explanation in terms of the ratio of rates of change.
     ◉ Validity premise for indeterminate forms of type $0/0$.
          ○ If
               ■ $\displaystyle \lim_{x\to 𝒂}\dfrac{𝒇(𝒙)}{𝓰(𝒙)}=0/0$,
               $\rule{0pt}{}$
          ○ then another idea is:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to 𝒂}\dfrac{𝒇(𝒙)}{𝓰(𝒙)}=\displaystyle \lim_{x\to 𝒂}\dfrac{𝒇'(𝒙)}{𝓰'(𝒙)}$
               $\rule{0pt}{}$
          ○ Only if the original limit is truly of indeterminate form $0/0$.

● [3:23](https://www.youtube.com/watch?v=Zd7wd24jeok&t=203). 🧩 Example 1 — Evaluate $\displaystyle \lim_{x\to 2}\dfrac{4(𝒙^{2}-4)}{𝒙-2}$.
$\rule{0pt}{}$
     ◉ MANDATORY verification of the indeterminate form $0/0$.
          ○ Substituting $𝒙=2$ gives:
          $\rule{0pt}{}$
               ■ $\dfrac{4(2^{2}-4)}{2-2}=0/0$
               $\rule{0pt}{}$
     ◉ Traditional method: remove the removable discontinuity by factoring.
          ○ $𝒙^{2}-4=(𝒙-2)(𝒙+2)$
          ○ Therefore:
               ■ $\displaystyle \lim_{x\to 2}\dfrac{4(𝒙^{2}-4)}{𝒙-2}$
               $\rule{0pt}{}$
               ■ $=\displaystyle \lim_{x\to 2}\dfrac{4(𝒙-2)(𝒙+2)}{𝒙-2}$
               $\rule{0pt}{}$
               ■ $=\displaystyle \lim_{x\to 2}4(𝒙+2)$
               $\rule{0pt}{}$
               ■ $=16$
     ◉ [9:21](https://www.youtube.com/watch?v=Zd7wd24jeok&t=561). Solution using L’Hôpital’s Rule.
          ○ Apply L’Hôpital:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to 2}\dfrac{4(𝒙^{2}-4)}{𝒙-2}$
               $\rule{0pt}{}$
               ■ $\longrightarrow \displaystyle \lim_{x\to 2}\dfrac{\dfrac{𝒅}{𝒅𝒙}\big(4(𝒙^{2}-4)\big)}{\dfrac{𝒅}{𝒅𝒙}(𝒙-2)}$
               $\rule{0pt}{}$
          ○ Numerator derivative:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}\big[4(𝒙^{2}-4)\big]=4\cdot 2𝒙=8𝒙$
               $\rule{0pt}{}$
          ○ Denominator derivative:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[𝒙-2]=1$
               $\rule{0pt}{}$
          ○ Final evaluation:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to 2}\dfrac{8𝒙}{1}=16$

● [5:58](https://www.youtube.com/watch?v=Zd7wd24jeok&t=358). 🧩 Example 2 — Evaluate $\displaystyle \lim_{x\to 0}\dfrac{\sin 𝒙}{𝒙}$.
$\rule{0pt}{}$
     ◉ Fundamental trigonometric limit.
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\dfrac{\sin 𝒙}{𝒙}=0/0$
          $\rule{0pt}{}$
          ○ Classical proof using the Squeeze Theorem.
     ◉ [10:55](https://www.youtube.com/watch?v=Zd7wd24jeok&t=655). Application of L’Hôpital’s Rule.
          ○ Apply L’Hôpital:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to 0}\dfrac{\sin 𝒙}{𝒙}$
               $\rule{0pt}{}$
               ■ $\longrightarrow \displaystyle \lim_{x\to 0}\dfrac{\cos 𝒙}{1}$
               $\rule{0pt}{}$
          ○ Derivatives:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[\sin 𝒙]=\cos 𝒙$
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[𝒙]=1$
               $\rule{0pt}{}$
          ○ Final result:
          $\rule{0pt}{}$
               ■ $\dfrac{\cos(0)}{1}=1$

● [7:25](https://www.youtube.com/watch?v=Zd7wd24jeok&t=445). Formal statement of L’Hôpital’s Rule.
$\rule{0pt}{}$
     ◉ $\displaystyle \lim_{x\to 𝒖}\dfrac{𝒇(𝒙)}{𝓰(𝒙)}=\displaystyle \lim_{x\to 𝒖}\dfrac{\dfrac{𝒅}{𝒅𝒙}𝒇(𝒙)}{\dfrac{𝒅}{𝒅𝒙}𝓰(𝒙)}$.
     $\rule{0pt}{}$
     ◉ Important distinction: L’Hôpital’s Rule is not the Quotient Rule.
     




          
Ｉｎｆｉｎｉｔｙ ｏｖｅｒ Ｉｎｆｉｎｉｔｙ

● [📷image](../img/Calculus 2 Lecture 6.7/[12-30]-01.png) 

● [12:30](https://www.youtube.com/watch?v=Zd7wd24jeok&t=750). Extension to the indeterminate form $\infty/\infty$.
     ◉ Algebraic justification using reciprocals.
     $\rule{0pt}{}$
          ○ If $\displaystyle \lim_{x\to 𝒂}\dfrac{𝒇(𝒙)}{𝓰(𝒙)}$ gives the form $\infty/\infty$,
          $\rule{0pt}{}$
               ■ then rewriting the expression as
               $\rule{0pt}{}$
                    ▣ $\dfrac{(1/𝓰(𝒙))}{(1/𝒇(𝒙))}$
                    $\rule{0pt}{}$
                 transforms it into the form $0/0$.
          ○ This shows that the same idea behind L’Hôpital’s Rule also applies to $\infty/\infty$.

● [14:55](https://www.youtube.com/watch?v=Zd7wd24jeok&t=895). Formal statement including both indeterminate forms.
     ◉ i̲f̲ 
          ○ $\displaystyle \lim_{x\to 𝒂}\dfrac{𝒇(𝒙)}{𝓰(𝒙)}=0/0$ or $\infty/\infty$,
          $\rule{0pt}{}$
     ◉ t̲h̲e̲m̲
          ○ $\displaystyle \lim_{x\to 𝒂}\dfrac{𝒇(𝒙)}{𝓰(𝒙)}=\displaystyle \lim_{x\to 𝒂}\dfrac{𝒇'(𝒙)}{𝓰'(𝒙)}$,
                 $\rule{0pt}{}$
               ■ provided the limit on the right exists.


● [15:36](https://www.youtube.com/watch?v=Zd7wd24jeok&t=936). General scope of L’Hôpital’s Rule.
     ◉ Valid for one-sided limits:
          ○ $\displaystyle \lim_{x\to a^+}$
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to a^-}$
          $\rule{0pt}{}$
     ◉ Valid for limits at infinity:
          ○ $\displaystyle \lim_{x\to\infty}$
          $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to-\infty}$

● [16:00](https://www.youtube.com/watch?v=Zd7wd24jeok&t=960). Important note before applying the rule.
     ◉ You must verify first that the original expression is truly of indeterminate form.
          ○ The rule applies only to:
               ■ $0/0$
               ■ $\infty/\infty$ 
     ◉ Requirement of verifying the indeterminate form before applying L’Hôpital’s Rule
     $\rule{0pt}{}$
          ○ [17:36](https://www.youtube.com/watch?v=Zd7wd24jeok&t=1056). 🧩 Counterexample — Analyze $\displaystyle \lim_{x\to 0^+}\dfrac{\cos 𝒙}{𝒙}$. [📷image](../img/Calculus 2 Lecture 6.7/[17-36]-01.png)
               ■ Form check:
                    ▣ As $𝒙\to 0^+$, $\cos 𝒙\to 1$ and $𝒙\to 0$
                    ▣ Therefore the expression has the form $1/0\to\infty$, not an indeterminate form
               ■ Incorrect application of L’Hôpital’s Rule:
               $\rule{0pt}{}$
                    ▣ Differentiating would give $\displaystyle \lim_{x\to 0^+}\dfrac{-\sin 𝒙}{1}=0$
                    $\rule{0pt}{}$
                    ▣ This contradicts the actual behavior of the original limit
               ■ Key conclusion:
                    ▣ L’Hôpital’s Rule cannot be applied unless the original limit is first verified to be of type $0/0$ or $\infty/\infty$




          
Ｐｒａｃｔｉｃｅ Ｐｒｏｂｌｅｍｓ

● [19:48](https://www.youtube.com/watch?v=Zd7wd24jeok&t=1188). 🧩 Example — Exponential functions: $\displaystyle \lim_{x\to 0}\dfrac{𝒆^{𝒙}-1}{2𝒙}$. [📷image](../img/Calculus 2 Lecture 6.7/[19-48]-01.png)
$\rule{0pt}{}$
     ◉ You must verify first that the original expression is truly of indeterminate form.
          ○ As $𝒙\to 0$, $𝒆^{𝒙}-1\to 0$ and $2𝒙\to 0$
          ○ Therefore:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to 0}\dfrac{𝒆^{𝒙}-1}{2𝒙}=0/0$
               $\rule{0pt}{}$
     ◉ Apply L’Hôpital’s Rule.
          ○ Differentiate the numerator and denominator:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[𝒆^{𝒙}-1]=𝒆^{𝒙}$
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[2𝒙]=2$
               $\rule{0pt}{}$
     ◉ Evaluate the new limit.
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\dfrac{𝒆^{𝒙}}{2}=\dfrac{𝒆^{0}}{2}=\dfrac{1}{2}$
          $\rule{0pt}{}$
     ◉ Final result:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0}\dfrac{𝒆^{𝒙}-1}{2𝒙}=\dfrac{1}{2}$

          
● [22:11](https://www.youtube.com/watch?v=Zd7wd24jeok&t=1331). 🧩 Example — Logarithmic functions: $\displaystyle \lim_{x\to\infty}\dfrac{\ln 𝒙}{𝒙}$. [📷image](../img/Calculus 2 Lecture 6.7/[22-11]-01.png)
     ◉ You must verify first that the original expression is truly of indeterminate form.
          ○ As $𝒙\to \infty$, $\ln 𝒙\to \infty$ and $𝒙\to \infty$
          ○ Therefore:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to\infty}\dfrac{\ln 𝒙}{𝒙}=\infty/\infty$
               $\rule{0pt}{}$
     ◉ Apply L’Hôpital’s Rule.
          ○ Differentiate the numerator and denominator:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[\ln 𝒙]=\dfrac{1}{𝒙}$
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[𝒙]=1$
               $\rule{0pt}{}$
     ◉ Evaluate the new limit.
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to\infty}\dfrac{(1/𝒙)}{1}=0$
          $\rule{0pt}{}$
     ◉ Final result:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to\infty}\dfrac{\ln 𝒙}{𝒙}=0$
          
● [24:34](https://www.youtube.com/watch?v=Zd7wd24jeok&t=1474). 🧩 Example — Composite trigonometric functions: $\displaystyle \lim_{x\to \pi}\dfrac{2\sin^{2} 𝒙}{1+\cos 𝒙}$. [📷image](../img/Calculus 2 Lecture 6.7/[24-34]-01.png)
$\rule{0pt}{}$
     ◉ You must verify first that the original expression is truly of indeterminate form.
          ○ As $𝒙\to \pi$, $\sin \pi=0$ and $\cos \pi=-1$
          ○ Therefore:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to \pi}\dfrac{2\sin^{2} 𝒙}{1+\cos 𝒙}=0/0$
               $\rule{0pt}{}$
     ◉ Apply L’Hôpital’s Rule.
          ○ Differentiate the numerator using the Chain Rule:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[2\sin^{2} 𝒙]=4\sin 𝒙\cos 𝒙$
               $\rule{0pt}{}$
          ○ Differentiate the denominator:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[1+\cos 𝒙]=-\sin 𝒙$
               $\rule{0pt}{}$
     ◉ Simplify before evaluating.
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to \pi}\dfrac{4\sin 𝒙\cos 𝒙}{-\sin 𝒙}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{x\to \pi}[-4\cos 𝒙]$
          $\rule{0pt}{}$
     ◉ Final evaluation:
          ○ $-4\cos \pi=-4(-1)=4$
     ◉ Final result:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to \pi}\dfrac{2\sin^{2} 𝒙}{1+\cos 𝒙}=4$





Ｒｅｐｅａｔｅｄ Ａｐｐｌｉｃａｔｉｏｎ

● [27:50](https://www.youtube.com/watch?v=Zd7wd24jeok&t=1670). 🧩 Example — Repeated application of L’Hôpital’s Rule: $\displaystyle \lim_{x\to\infty}\dfrac{𝒙^{3}}{𝒆^{2𝒙}}$. [📷image](../img/Calculus 2 Lecture 6.7/[27-50]-01.png)
$\rule{0pt}{}$
     ◉ You must verify first that the original expression is truly of indeterminate form.
     $\rule{0pt}{}$
          ○ As $𝒙\to \infty$, $𝒙^{3}\to \infty$ and $𝒆^{2𝒙}\to \infty$
          ○ Therefore:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to\infty}\dfrac{𝒙^{3}}{𝒆^{2𝒙}}=\infty/\infty$
               $\rule{0pt}{}$
     ◉ First application of L’Hôpital’s Rule.
          ○ Differentiate the numerator and denominator:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[𝒙^{3}]=3𝒙^{2}$
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[𝒆^{2𝒙}]=2𝒆^{2𝒙}$
               $\rule{0pt}{}$
          ○ New limit:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to\infty}\dfrac{3𝒙^{2}}{2𝒆^{2𝒙}}$
               $\rule{0pt}{}$
     ◉ Second application of L’Hôpital’s Rule.
          ○ The new form is still $\infty/\infty$
          ○ Differentiate again:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[3𝒙^{2}]=6𝒙$
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[2𝒆^{2𝒙}]=4𝒆^{2𝒙}$
               $\rule{0pt}{}$
          ○ New limit:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to\infty}\dfrac{6𝒙}{4𝒆^{2𝒙}}$
               $\rule{0pt}{}$
     ◉ Third application of L’Hôpital’s Rule.
          ○ The new form is still $\infty/\infty$
          ○ Differentiate once more:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[6𝒙]=6$
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[4𝒆^{2𝒙}]=8𝒆^{2𝒙}$
               $\rule{0pt}{}$
          ○ New limit:
               ■ $\displaystyle \lim_{x\to\infty}\dfrac{6}{8𝒆^{2𝒙}}$
               $\rule{0pt}{}$
     ◉ Final evaluation:
          ○ As $𝒙\to \infty$, $𝒆^{2𝒙}\to \infty$
          ○ Therefore:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to\infty}\dfrac{6}{8𝒆^{2𝒙}}=0$
               $\rule{0pt}{}$
     ◉ Final result:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to\infty}\dfrac{𝒙^{3}}{𝒆^{2𝒙}}=0$

● [32:00](https://www.youtube.com/watch?v=Zd7wd24jeok&t=1920). 🧩 Example — Repeated application of L’Hôpital’s Rule: $\displaystyle \lim_{x\to 0}\dfrac{𝒙^{3}}{𝒙-\tan 𝒙}$. [📷image](../img/Calculus 2 Lecture 6.7/[32-00]-01.png)
$\rule{0pt}{}$
     ◉ You must verify first that the original expression is truly of indeterminate form.
          ○ As $𝒙\to 0$, $𝒙^{3}\to 0$ and $𝒙-\tan 𝒙\to 0$
          ○ Therefore:
               ■ $\displaystyle \lim_{x\to 0}\dfrac{𝒙^{3}}{𝒙-\tan 𝒙}=0/0$
               $\rule{0pt}{}$
     ◉ First application of L’Hôpital’s Rule.
          ○ Differentiate the numerator and denominator:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[𝒙^{3}]=3𝒙^{2}$
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[𝒙-\tan 𝒙]=1-\sec^{2} 𝒙$
               $\rule{0pt}{}$
          ○ New limit:
               ■ $\displaystyle \lim_{x\to 0}\dfrac{3𝒙^{2}}{1-\sec^{2} 𝒙}$
               $\rule{0pt}{}$
          ○ This is still of type $0/0$.
     ◉ Second application of L’Hôpital’s Rule.
          ○ Differentiate again:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[3𝒙^{2}]=6𝒙$
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[1-\sec^{2} 𝒙]=-2\sec^{2} 𝒙\tan 𝒙$
               $\rule{0pt}{}$
          ○ New limit:
               ■ $\displaystyle \lim_{x\to 0}\dfrac{6𝒙}{-2\sec^{2} 𝒙\tan 𝒙}$
               $\rule{0pt}{}$
          ○ This is still of type $0/0$.
     ◉ Third application of L’Hôpital’s Rule.
          ○ Differentiate the numerator:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[6𝒙]=6$
               $\rule{0pt}{}$
          ○ Differentiate the denominator using the Product Rule:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[-2\sec^{2} 𝒙\tan 𝒙]$
               $\rule{0pt}{}$
               ■ $=\dfrac{𝒅}{𝒅𝒙}[-2\sec^{2} 𝒙]\cdot\tan 𝒙+(-2\sec^{2} 𝒙)\cdot\dfrac{𝒅}{𝒅𝒙}[\tan 𝒙]$
               $\rule{0pt}{}$
               ■ $=(-4\sec^{2} 𝒙\tan 𝒙)\tan 𝒙-2\sec^{2} 𝒙\sec^{2} 𝒙$
               ■ $=-4\sec^{2} 𝒙\tan^{2} 𝒙-2\sec^{4} 𝒙$
          ○ New limit:
               ■ $\displaystyle \lim_{x\to 0}\dfrac{6}{-4\sec^{2} 𝒙\tan^{2} 𝒙-2\sec^{4} 𝒙}$
               $\rule{0pt}{}$
     ◉ Final evaluation:
          ○ At $𝒙=0$:
               ■ $\tan 0=0$
               ■ $\sec 0=1$
          ○ Therefore:
               ■ $\dfrac{6}{-4\cdot 1\cdot 0-2\cdot 1}=\dfrac{6}{-2}=-3$
               $\rule{0pt}{}$
     ◉ Final result:
          ○ $\displaystyle \lim_{x\to 0}\dfrac{𝒙^{3}}{𝒙-\tan 𝒙}=-3$




     
     
Ｏｔｈｅｒ Ｉｎｄｅｔｅｒｍｉｎａｔｅ Ｆｏｒｍｓ ∞ − ∞  and   0 · ∞

● [41:19](https://www.youtube.com/watch?v=Zd7wd24jeok&t=2479). Indeterminate form $\infty-\infty$. [📷image](../img/Calculus 2 Lecture 6.7/[41-19]-01.png)
     ◉ Strategy for $\infty-\infty$:
          ○ Rewrite the expression algebraically as a single fraction.
          ○ Then check whether the new form becomes $0/0$ or $\infty/\infty$.
          ○ Only after that can L’Hôpital’s Rule be applied.
          $\rule{0pt}{}$
     ◉ [43:15](https://www.youtube.com/watch?v=Zd7wd24jeok&t=2595). 🧩 Example — $\displaystyle \lim_{x\to 0^+}\Big(\dfrac{1}{𝒙}-\dfrac{1}{1-\cos 𝒙}\Big)$. [📷image-1](../img/Calculus 2 Lecture 6.7/[43-15]-01.png) [📷image-2](../img/Calculus 2 Lecture 6.7/[43-15]-02.png) [📷image-3](../img/Calculus 2 Lecture 6.7/[43-15]-03.png) 
     $\rule{0pt}{}$
          ○ The original form is $\infty-\infty$, so L’Hôpital’s Rule cannot be used immediately.
          ○ Rewrite using a common denominator:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to 0^+}\dfrac{(1-\cos 𝒙)-𝒙}{𝒙(1-\cos 𝒙)}$
               $\rule{0pt}{}$
          ○ Verify the new indeterminate form:
               ■ As $𝒙\to 0^+$, the numerator $\to 0$ and the denominator $\to 0$
               ■ Therefore the expression becomes $0/0$
          ○ Apply L’Hôpital’s Rule.
               ■ Numerator derivative:
               $\rule{0pt}{}$
                    ▣ $\dfrac{𝒅}{𝒅𝒙}[1-\cos 𝒙-𝒙]=\sin 𝒙-1$
                    $\rule{0pt}{}$
               ■ Denominator derivative:
               $\rule{0pt}{}$
                    ▣ $\dfrac{𝒅}{𝒅𝒙}[𝒙-𝒙\cos 𝒙]=1-[\cos 𝒙+𝒙(-\sin 𝒙)]$
                    $\rule{0pt}{}$
                    ▣ $=1-\cos 𝒙+𝒙\sin 𝒙$
          ○ Evaluate the new limit:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to 0^+}\dfrac{\sin 𝒙-1}{1-\cos 𝒙+𝒙\sin 𝒙}$
               $\rule{0pt}{}$
               ■ $=-1/0^+$
          ○ Final result:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to 0^+}\Big(\dfrac{1}{𝒙}-\dfrac{1}{1-\cos 𝒙}\Big)=-\infty$

          
● [52:40](https://www.youtube.com/watch?v=Zd7wd24jeok&t=3160). Indeterminate form $0\cdot\infty$. [📷image](../img/Calculus 2 Lecture 6.7/[41-19]-01.png)
     ◉ Strategy for $0\cdot\infty$:
          ○ Rewrite the expression as a quotient by using the reciprocal of one factor.
          ○ Then check whether the new expression becomes $0/0$ or $\infty/\infty$.
          ○ Only after that can L’Hôpital’s Rule be applied.
     ◉ [54:17](https://www.youtube.com/watch?v=Zd7wd24jeok&t=3257). 🧩 Example — Analyze $\displaystyle \lim_{x\to 0^+}\csc 𝒙\cdot \ln(1-\sin 𝒙)$. [📷image](../img/Calculus 2 Lecture 6.7/[52-40]-01.png)
     $\rule{0pt}{}$
          ○ Verify the original indeterminate form.
               ■ As $𝒙\to 0^+$, $\csc 𝒙=1/\sin 𝒙\to \infty$
               ■ As $𝒙\to 0^+$, $\ln(1-\sin 𝒙)\to \ln(1)=0$
               ■ Therefore the expression has the form $0\cdot\infty$
          ○ Rewrite as a quotient.
               ■ $\csc 𝒙=1/\sin 𝒙$
               ■ So:
                    ▣ $\displaystyle \lim_{x\to 0^+}\csc 𝒙\cdot \ln(1-\sin 𝒙)$
                    $\rule{0pt}{}$
                    ▣ $=\displaystyle \lim_{x\to 0^+}\dfrac{\ln(1-\sin 𝒙)}{\sin 𝒙}$
                    $\rule{0pt}{}$
          ○ Verify the new indeterminate form.
               ■ As $𝒙\to 0^+$, $\ln(1-\sin 𝒙)\to 0$ and $\sin 𝒙\to 0$
               ■ Therefore the quotient is now of type $0/0$
          ○ Apply L’Hôpital’s Rule.
               ■ Numerator derivative:
               $\rule{0pt}{}$
                    ▣ $\dfrac{𝒅}{𝒅𝒙}[\ln(1-\sin 𝒙)]=-\dfrac{\cos 𝒙}{1-\sin 𝒙}$
                    $\rule{0pt}{}$
               ■ Denominator derivative:
               $\rule{0pt}{}$
                    ▣ $\dfrac{𝒅}{𝒅𝒙}[\sin 𝒙]=\cos 𝒙$
                    $\rule{0pt}{}$
          ○ Simplify the new quotient.
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to 0^+}\dfrac{\big[-\cos 𝒙/(1-\sin 𝒙)\big]}{\cos 𝒙}$
               $\rule{0pt}{}$
               ■ $=\displaystyle \lim_{x\to 0^+}-\dfrac{1}{1-\sin 𝒙}$
               $\rule{0pt}{}$
          ○ Final evaluation.
          $\rule{0pt}{}$
               ■ $-\dfrac{1}{1-\sin 0}=-1$
               $\rule{0pt}{}$
          ○ Final result:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to 0^+}\csc 𝒙\cdot \ln(1-\sin 𝒙)=-1$




          
Ｅｘｐｏｎｅｎｔｉａｌ Ｉｎｄｅｔｅｒｍｉｎａｔｅ Ｆｏｒｍｓ   0⁰,   ∞⁰,   and   1^∞
 
● [58:03](https://www.youtube.com/watch?v=Zd7wd24jeok&t=3483). Exponential indeterminate forms: $0^{0}$, $\infty^{0}$, and $1^{\infty}$. [📷image](../img/Calculus 2 Lecture 6.7/[58-03]-01.png)
$\rule{0pt}{}$
     ◉ [1:00:13](https://www.youtube.com/watch?v=Zd7wd24jeok&t=3613). Logarithmic transformation method: $𝒇(𝒙)^{𝓰(𝒙)}=𝒆^{𝓰(𝒙)\ln 𝒇(𝒙)}$.

● [1:01:21](https://www.youtube.com/watch?v=Zd7wd24jeok&t=3681). 🧩 Case Study — $\displaystyle \lim_{x\to 0^+}𝒙^{𝒙}$. [📷image](../img/Calculus 2 Lecture 6.7/[1-01-21]-01.png)
$\rule{0pt}{}$
     ◉ Recognize the indeterminate exponential form.
          ○ As _$𝒙\to 0^+$,
               ■ $𝒙\to 0$_
               ■ $𝒙\to 0$
          ○ Therefore:
               ■ $𝒙^{𝒙}$ has the indeterminate form $0^{0}$
     ◉ Use the logarithmic-exponential transformation.
     $\rule{0pt}{}$
          ○ $𝒙^{𝒙}=𝒆^{\ln(𝒙^{𝒙})}$
          ○ $𝒙^{𝒙}=𝒆^{𝒙\ln 𝒙}$
     ◉ Use continuity of the exponential function.
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0^+}𝒙^{𝒙}=𝒆^{\displaystyle \lim_{x\to 0^+}𝒙\ln 𝒙}$
          $\rule{0pt}{}$
     ◉ Analyze the exponent.
          ○ As $𝒙\to 0^+$,
               ■ $𝒙\ln 𝒙=0\cdot (-\infty)$
          ○ Rewrite it as a quotient:
          $\rule{0pt}{}$
               ■ $𝒙\ln 𝒙=\dfrac{\ln 𝒙}{1/𝒙}$
               $\rule{0pt}{}$
          ○ This gives the indeterminate form:
          $\rule{0pt}{}$
               ■ $\dfrac{(-\infty)}{\infty}$
               $\rule{0pt}{}$
     ◉ Apply L’Hôpital’s Rule to the exponent.
          ○ Differentiate the numerator and denominator:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[\ln 𝒙]=1/𝒙$
               $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[1/𝒙]=-1/𝒙^{2}$
               $\rule{0pt}{}$
          ○ Therefore:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to 0^+}\dfrac{\ln 𝒙}{1/𝒙}=\displaystyle \lim_{x\to 0^+}\dfrac{1/𝒙}{-1/𝒙^{2}}$
               $\rule{0pt}{}$
               ■ $=\displaystyle \lim_{x\to 0^+}(-𝒙)$
               $\rule{0pt}{}$
               ■ $=0$
     ◉ Final evaluation.
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to 0^+}𝒙^{𝒙}=𝒆^{0}=1$      
    
● [1:15:15](https://www.youtube.com/watch?v=Zd7wd24jeok&t=4515). 🧩 Case Study — $\displaystyle \lim_{x\to \pi/2^-}(\tan 𝒙)^{\cos 𝒙}$. [📷image](../img/Calculus 2 Lecture 6.7/[1-15-15]-01.png)
     ◉ Verify the indeterminate form.
          ○ As $𝒙\to \pi/2^-$:
               ■ $\tan 𝒙\to \infty$
               ■ $\cos 𝒙\to 0$
          ○ Therefore:
               ■ $(\tan 𝒙)^{\cos 𝒙}$ has the indeterminate form $\infty^{0}$
     ◉ Exponential rewrite.
          ○ Let
               ■ $𝒚=(\tan 𝒙)^{\cos 𝒙}$
          ○ Then
               ■ $\ln 𝒚=\cos 𝒙\cdot \ln(\tan 𝒙)$
          ○ So
               ■ $𝒚=𝒆^{\cos 𝒙\cdot \ln(\tan 𝒙)}$
     ◉ Convert the exponent into a quotient.
     $\rule{0pt}{}$
          ○ $\cos 𝒙\cdot \ln(\tan 𝒙)=\dfrac{\ln(\tan 𝒙)}{\sec 𝒙}$
          ○ Therefore study
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to \pi/2^-}\dfrac{\ln(\tan 𝒙)}{\sec 𝒙}$ has the indeterminate form $\infty/\infty$ 
               $\rule{0pt}{}$
     ◉ Apply L’Hôpital’s Rule to the exponent.
          ○ Numerator derivative:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[\ln(\tan 𝒙)]=\dfrac{1}{\tan 𝒙}\cdot \sec^{2} 𝒙$
               $\rule{0pt}{}$
          ○ Denominator derivative:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[\sec 𝒙]=\sec 𝒙\tan 𝒙$
               $\rule{0pt}{}$
          ○ New quotient:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to \pi/2^-}\Big[\dfrac{(\sec^{2} 𝒙/\tan 𝒙)}{(\sec 𝒙\tan 𝒙)}\Big]$
               $\rule{0pt}{}$
     ◉ Trigonometric simplification.
     $\rule{0pt}{}$
          ○ $\Big[\dfrac{(\sec^{2} 𝒙/\tan 𝒙)}{(\sec 𝒙\tan 𝒙)}\Big]$
          $\rule{0pt}{}$
               ■ $=\dfrac{\sec 𝒙}{\tan^{2} 𝒙}$
               $\rule{0pt}{}$
               ■ $=\dfrac{(1/\cos 𝒙)}{(\sin^{2} 𝒙/\cos^{2} 𝒙)}$
               $\rule{0pt}{}$
               ■ $=\dfrac{\cos 𝒙}{\sin^{2} 𝒙}$
               $\rule{0pt}{}$
     ◉ Evaluate the exponent.
          ○ As $𝒙\to \pi/2^-$:
               ■ $\cos 𝒙\to 0$
               ■ $\sin^{2} 𝒙\to 1$
          ○ Therefore:
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to \pi/2^-}\dfrac{\cos 𝒙}{\sin^{2} 𝒙}=0$
               $\rule{0pt}{}$
     ◉ Final result.
          ○ $\displaystyle \lim_{x\to \pi/2^-}(\tan 𝒙)^{\cos 𝒙}$
          $\rule{0pt}{}$
               ■ $=𝒆^{0}$
               ■ $=1$
● [1:28:52](https://www.youtube.com/watch?v=Zd7wd24jeok&t=5332). 🧩 Case Study — $\displaystyle \lim_{x\to\infty}\Big(1-\dfrac{1}{𝒙}\Big)^{𝒙}$. [📷image](../img/Calculus 2 Lecture 6.7/[1-28-52]-01.png)
$\rule{0pt}{}$
     ◉ Identify the indeterminate form.
          ○ As $𝒙\to \infty$:
               ■ $1-\dfrac{1}{𝒙}\to 1$
               ■ $𝒙\to \infty$
          ○ Therefore:
          $\rule{0pt}{}$
               ■ $\Big(1-\dfrac{1}{𝒙}\Big)^{𝒙}$ has the form $1^{\infty}$
               $\rule{0pt}{}$
     ◉ Rewrite using the exponential method.
          ○ Let
               ■ $𝒚=\Big(1-\dfrac{1}{𝒙}\Big)^{𝒙}$
          ○ Then
               ■ $\ln 𝒚=𝒙\ln\Big(1-\dfrac{1}{𝒙}\Big)$
          ○ So
               ■ $𝒚=𝒆^{𝒙\ln\Big(1-\dfrac{1}{𝒙}\Big)}$
     ◉ Convert the exponent into a quotient.
     $\rule{0pt}{}$
          ○ $𝒙\ln\Big(1-\dfrac{1}{𝒙}\Big)=\dfrac{\ln\Big(1-\dfrac{1}{𝒙}\Big)}{(1/𝒙)}$
          $\rule{0pt}{}$
          ○ Therefore study
          $\rule{0pt}{}$
               ■ $\displaystyle \lim_{x\to\infty}\dfrac{\ln\Big(1-\dfrac{1}{𝒙}\Big)}{(1/𝒙)}$
               $\rule{0pt}{}$
     ◉ Verify the new indeterminate form.
          ○ As $𝒙\to \infty$:
               ■ $\ln\Big(1-\dfrac{1}{𝒙}\Big)\to \ln(1)=0$
               $\rule{0pt}{}$
               ■ $1/𝒙\to 0$
          ○ Therefore the exponent is now of type $0/0$
     ◉ Apply L’Hôpital’s Rule.
          ○ Differentiate the numerator:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}\Big[\ln\Big(1-\dfrac{1}{𝒙}\Big)\Big]=\dfrac{1}{\Big(1-\dfrac{1}{𝒙}\Big)}\cdot \dfrac{1}{𝒙^{2}}$
               $\rule{0pt}{}$
          ○ Differentiate the denominator:
          $\rule{0pt}{}$
               ■ $\dfrac{𝒅}{𝒅𝒙}[1/𝒙]=-\dfrac{1}{𝒙^{2}}$
               $\rule{0pt}{}$
     ◉ Simplify the quotient.
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to\infty}\dfrac{\Big[\dfrac{1}{\Big(1-\dfrac{1}{𝒙}\Big)}\cdot \dfrac{1}{𝒙^{2}}\Big]}{\Big[-\dfrac{1}{𝒙^{2}}\Big]}$
          $\rule{0pt}{}$
          ○ $=\displaystyle \lim_{x\to\infty}-\dfrac{1}{\Big(1-\dfrac{1}{𝒙}\Big)}$
          $\rule{0pt}{}$
          ○ $=-1$
     ◉ Evaluate the original limit.
          ○ $𝒚=𝒆^{-1}$
     ◉ Final result:
     $\rule{0pt}{}$
          ○ $\displaystyle \lim_{x\to\infty}\Big(1-\dfrac{1}{𝒙}\Big)^{𝒙}=\dfrac{1}{𝒆}$




     
Ｃｏｎｃｌｕｓｉｏｎ

● [1:39:52](https://www.youtube.com/watch?v=Zd7wd24jeok&t=5992). Summary of the goals and closing remarks on L’Hôpital’s Rule.



Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

[openstax🌐](https://openstax.org/books/calculus-volume-1/pages/4-8-lhopitals-rule)