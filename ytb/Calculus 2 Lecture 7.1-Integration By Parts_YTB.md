-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ ７．１ － Ｉｎｔｅｇｒａｔｉｏｎ Ｂｙ Ｐａｒｔｓ**---------------------------------


 




Ｉｎｔｒｏｄｕｃｔｉｏｎ

● [0:00]. Introduction to Chapter 7, Section 7.1: Integration by Parts.
     ◉ Review of previous methods: integration tables and u-substitution.
     ◉ Conceptual analysis: substitution as the inverse process of the Chain Rule.

     




Ｄｅｒｉｖａｔｉｏｎ ｏｆ ｔｈｅ Ｆｏｒｍｕｌａ

● [1:03]. Derivation of the Integration by Parts formula from the Product Rule. 
     ◉ Starting point: the Product Rule.
          ○ 𝒅/𝒅𝒙 [𝒇(𝒙)𝓰(𝒙)] = 𝒇′(𝒙)𝓰(𝒙) + 𝒇(𝒙)𝓰′(𝒙)
     ◉ Integrate both sides.
          ○ ∫ 𝒅/𝒅𝒙 [𝒇(𝒙)𝓰(𝒙)] 𝒅𝒙 = ∫ [𝒇′(𝒙)𝓰(𝒙) + 𝒇(𝒙)𝓰′(𝒙)] 𝒅𝒙
     ◉ Apply the Fundamental Theorem of Calculus.
          ○ ∫ 𝒅/𝒅𝒙 [𝒇(𝒙)𝓰(𝒙)] 𝒅𝒙 = 𝒇(𝒙)𝓰(𝒙)
     ◉ Separate the integrals.
          ○ 𝒇(𝒙)𝓰(𝒙) = ∫ 𝒇′(𝒙)𝓰(𝒙) 𝒅𝒙 + ∫ 𝒇(𝒙)𝓰′(𝒙) 𝒅𝒙
     ◉ Rearrangement.
          ○ ∫ 𝒇(𝒙)𝓰′(𝒙) 𝒅𝒙 = 𝒇(𝒙)𝓰(𝒙) − ∫ 𝓰(𝒙)𝒇′(𝒙) 𝒅𝒙
     ◉ [5:29]. Introduction of auxiliary notation.
          ○ Define:
               ■ 𝒖 = 𝒇(𝒙)
               ■ 𝓥 = 𝓰(𝒙)
          ○ Corresponding differentials:
               ■ 𝒅𝒖 = 𝒇′(𝒙) 𝒅𝒙
               ■ 𝒅𝓥 = 𝓰′(𝒙) 𝒅𝒙
     ◉ Standard formula.
          ○ ∫ 𝒖 𝒅𝓥 = 𝒖𝓥 − ∫ 𝓥 𝒅𝒖
     ◉ Practical note on choosing 𝒖 and 𝒅𝓥.
          ○ Choose 𝒖 so that 𝒅𝒖/𝒅𝒙 becomes simpler or “better”.
          ○ Choose 𝒅𝓥 so that ∫ 𝒅𝓥 can actually be computed.


          


Ｂａｓｉｃ  Ｅｘａｍｐｌｅｓ

● [11:51]. 🧩 Example 1 — Evaluate ∫ 𝒙𝒆ˣ 𝒅𝒙 
     ◉ Why simple substitution does not work.
          ○ There is no natural inner function whose derivative produces the remaining factor directly.
          ○ The product 𝒙𝒆ˣ suggests Integration by Parts instead.
     ◉ Criteria for choosing 𝒖 and 𝒅𝓥.
          ○ Heuristic rule:
               ■ Choose 𝒖 so that 𝒅𝒖/𝒅𝒙 becomes simpler or has lower degree.
               ■ Choose 𝒅𝓥 so that 𝓥 = ∫ 𝒅𝓥 is easy to compute.
          ○ Assignment:
               ■ 𝒖 = 𝒙
               ■ 𝒅𝓥 = 𝒆ˣ 𝒅𝒙
               ■ 𝒅𝒖 = 𝒅𝒙
               ■ 𝓥 = 𝒆ˣ
     ◉ Apply the formula:
          ○ ∫ 𝒖 𝒅𝓥 = 𝒖𝓥 − ∫ 𝓥 𝒅𝒖
          ○ ∫ 𝒙𝒆ˣ 𝒅𝒙 = 𝒙𝒆ˣ − ∫ 𝒆ˣ 𝒅𝒙
     ◉ Integrate the remaining term.
          ○ ∫ 𝒆ˣ 𝒅𝒙 = 𝒆ˣ
          ○ Therefore:
               ■ ∫ 𝒙𝒆ˣ 𝒅𝒙 = 𝒙𝒆ˣ − 𝒆ˣ + 𝓒
     ◉ Final result:
          ○ ∫ 𝒙𝒆ˣ 𝒅𝒙 = 𝒆ˣ(𝒙 − 1) + 𝓒

● [17:58]. 🧩 Example 2 — Evaluate ∫ 𝒙³ ln 𝒙 𝒅𝒙. 
     ◉ Common mistake: choosing 𝒖 = 𝒙³.
          ○ If 𝒖 = 𝒙³, then 𝒅𝒖 = 3𝒙² 𝒅𝒙
          ○ But then 𝒅𝓥 = ln 𝒙 𝒅𝒙, which is not convenient because ∫ ln 𝒙 𝒅𝒙 is exactly the harder part.
     ◉ Main obstacle:
          ○ ln 𝒙 is difficult to integrate if chosen as 𝒅𝓥.
     ◉ Correct choice:
          ○ 𝒖 = ln 𝒙
          ○ 𝒅𝓥 = 𝒙³ 𝒅𝒙
     ◉ Compute the parts:
          ○ 𝒅𝒖 = 1/𝒙 𝒅𝒙
          ○ 𝓥 = ∫ 𝒙³ 𝒅𝒙 = 𝒙⁴/4
     ◉ Apply the Integration by Parts formula:
          ○ ∫ 𝒙³ ln 𝒙 𝒅𝒙 = 𝒖𝓥 − ∫ 𝓥 𝒅𝒖
          ○ = ln 𝒙 · 𝒙⁴/4 − ∫ (𝒙⁴/4)(1/𝒙) 𝒅𝒙
     ◉ Simplify the remaining integral:
          ○ = 𝒙⁴/4 ln 𝒙 − (1/4) ∫ 𝒙³ 𝒅𝒙
          ○ = 𝒙⁴/4 ln 𝒙 − (1/4)(𝒙⁴/4)
     ◉ Final result:
          ○ ∫ 𝒙³ ln 𝒙 𝒅𝒙 = (1/4)𝒙⁴ ln 𝒙 − (1/16)𝒙⁴ + 𝓒



          


Ｒｅｐｅａｔｅｄ  Ｉｎｔｅｇｒａｔｉｏｎ   ｂｙ  Ｐａｒｔｓ  Ｅｘａｍｐｌｅ

● [28:42]. 🧩 Example 3 — Repeated use of Integration by Parts: Evaluate ∫ 𝒙² sin(2𝒙) 𝒅𝒙 
     ◉ First iteration of Integration by Parts.
          ○ Choose:
               ■ 𝒖 = 𝒙²
               ■ 𝒅𝓥 = sin(2𝒙) 𝒅𝒙
          ○ Then:
               ■ 𝒅𝒖 = 2𝒙 𝒅𝒙
               ■ 𝓥 = ∫ sin(2𝒙) 𝒅𝒙 = −(1/2) cos(2𝒙)
     ◉ Apply the formula.
          ○ ∫ 𝒙² sin(2𝒙) 𝒅𝒙 = 𝒖𝓥 − ∫ 𝓥 𝒅𝒖
          ○ = 𝒙² [−(1/2) cos(2𝒙)] − ∫ [−(1/2) cos(2𝒙)] (2𝒙) 𝒅𝒙
          ○ = −(1/2)𝒙² cos(2𝒙) + ∫ 𝒙 cos(2𝒙) 𝒅𝒙
     ◉ Second iteration on the remaining integral.
          ○ For ∫ 𝒙 cos(2𝒙) 𝒅𝒙, choose:
               ■ 𝒖 = 𝒙
               ■ 𝒅𝓥 = cos(2𝒙) 𝒅𝒙
          ○ Then:
               ■ 𝒅𝒖 = 𝒅𝒙
               ■ 𝓥 = ∫ cos(2𝒙) 𝒅𝒙 = (1/2) sin(2𝒙)
     ◉ Apply Integration by Parts again.
          ○ ∫ 𝒙 cos(2𝒙) 𝒅𝒙 = 𝒖𝓥 − ∫ 𝓥 𝒅𝒖
          ○ = 𝒙[(1/2) sin(2𝒙)] − ∫ (1/2) sin(2𝒙) 𝒅𝒙
          ○ = (1/2)𝒙 sin(2𝒙) − (1/2) ∫ sin(2𝒙) 𝒅𝒙
          ○ = (1/2)𝒙 sin(2𝒙) + (1/4) cos(2𝒙)
     ◉ Consolidate all terms.
          ○ ∫ 𝒙² sin(2𝒙) 𝒅𝒙
               ■ = −(1/2)𝒙² cos(2𝒙) + (1/2)𝒙 sin(2𝒙) + (1/4) cos(2𝒙) + 𝓒
     ◉ Key idea.
          ○ Each application of Integration by Parts lowers the power of 𝒙.
          ○ Repeating the method eventually reduces the problem to a basic trigonometric integral.



     


Ｃｉｒｃｕｌａｒ Ｉｎｔｅｇｒａｌｓ  ｂｙ   Ｐａｒｔｓ   Ｅｘａｍｐｌｅ


● [43:02]. 🧩 Example 4 — Circula integral: ∫ 𝒆ˣ sin(2𝒙) 𝒅𝒙. 
     ◉ Observation of the cyclic behavior of transcendental functions.
          ○ Repeated integration by parts brings back the original integral.
          ○ This creates a circular equation that must be solved algebraically.
     ◉ First application of Integration by Parts.
          ○ Choose:
               ■ 𝒖 = sin(2𝒙)
               ■ 𝒅𝓥 = 𝒆ˣ 𝒅𝒙
          ○ Then:
               ■ 𝒅𝒖 = 2 cos(2𝒙) 𝒅𝒙
               ■ 𝓥 = 𝒆ˣ
          ○ Apply the formula:
               ■ ∫ 𝒆ˣ sin(2𝒙) 𝒅𝒙 = 𝒆ˣ sin(2𝒙) − 2∫ 𝒆ˣ cos(2𝒙) 𝒅𝒙
     ◉ Second application on the new integral.
          ○ For ∫ 𝒆ˣ cos(2𝒙) 𝒅𝒙, choose:
               ■ 𝒖 = cos(2𝒙)
               ■ 𝒅𝓥 = 𝒆ˣ 𝒅𝒙
          ○ Then:
               ■ 𝒅𝒖 = −2 sin(2𝒙) 𝒅𝒙
               ■ 𝓥 = 𝒆ˣ
          ○ Apply the formula:
               ■ ∫ 𝒆ˣ cos(2𝒙) 𝒅𝒙 = 𝒆ˣ cos(2𝒙) + 2∫ 𝒆ˣ sin(2𝒙) 𝒅𝒙
     ◉ Substitute back into the first result.
          ○ ∫ 𝒆ˣ sin(2𝒙) 𝒅𝒙
               ■ = 𝒆ˣ sin(2𝒙) − 2[𝒆ˣ cos(2𝒙) + 2∫ 𝒆ˣ sin(2𝒙) 𝒅𝒙]
               ■ = 𝒆ˣ sin(2𝒙) − 2𝒆ˣ cos(2𝒙) − 4∫ 𝒆ˣ sin(2𝒙) 𝒅𝒙
     ◉ Solve algebraically by isolating the original integral.
          ○ Add 4∫ 𝒆ˣ sin(2𝒙) 𝒅𝒙 to both sides:
               ■ 5∫ 𝒆ˣ sin(2𝒙) 𝒅𝒙 = 𝒆ˣ sin(2𝒙) − 2𝒆ˣ cos(2𝒙)
          ○ Divide by 5:
               ■ ∫ 𝒆ˣ sin(2𝒙) 𝒅𝒙 = (1/5)𝒆ˣ[sin(2𝒙) − 2 cos(2𝒙)] + 𝓒
     ◉ Final result:
          ○ ∫ 𝒆ˣ sin(2𝒙) 𝒅𝒙 = (1/5)𝒆ˣ[sin(2𝒙) − 2 cos(2𝒙)] + 𝓒



          


Ｄｅｆｉｎｅｄ Ｉｎｔｅｇｒａｌｓ

● [59:00]. 🧩 Example 5 — Definite integral and geometric interpretation: ∫[1, 𝒆] ln 𝒙 𝒅𝒙. 
     ◉ Define the parts.
          ○ 𝒖 = ln 𝒙
          ○ 𝒅𝓥 = 𝒅𝒙
          ○ 𝒅𝒖 = (1/𝒙) 𝒅𝒙
          ○ 𝓥 = 𝒙
     ◉ Apply Integration by Parts.
          ○ ∫ ln 𝒙 𝒅𝒙 = 𝒖𝓥 − ∫ 𝓥 𝒅𝒖
          ○ = 𝒙 ln 𝒙 − ∫ 𝒙 · (1/𝒙) 𝒅𝒙
          ○ = 𝒙 ln 𝒙 − ∫ 1 𝒅𝒙
     ◉ Antiderivative obtained.
          ○ 𝒙 ln 𝒙 − 𝒙
     ◉ Evaluate at the bounds.
          ○ ∫[1, 𝒆] ln 𝒙 𝒅𝒙 = [𝒙 ln 𝒙 − 𝒙]₁ᵉ
          ○ = [𝒆 ln 𝒆 − 𝒆] − [1 ln 1 − 1]
          ○ = [𝒆(1) − 𝒆] − [0 − 1]
          ○ = 0 − (−1)
          ○ = 1
     ◉ Geometric interpretation.
          ○ The definite integral represents the area under the curve 𝒚 = ln 𝒙 from 𝒙 = 1 to 𝒙 = 𝒆.
     ◉ Final conclusion.
          ○ ∫[1, 𝒆] ln 𝒙 𝒅𝒙 = 1
          ○ Therefore, the area under ln 𝒙 on [1, 𝒆] is exactly 1.



          


Ｓｅｃａｎｔ Ｐｏｗｅｒｓ

● [1:06:25]. 🧩 Example 6 — Odd powers of secant: ∫ sec 𝒙 𝒅𝒙, ∫ sec³ 𝒙 𝒅𝒙, and ∫ sec⁵ 𝒙 𝒅𝒙 
     ◉ Preliminary basic integrals
          ○ ∫ sec 𝒙 𝒅𝒙 = ln|sec 𝒙 + tan 𝒙| + 𝓒
          ○ ∫ sec² 𝒙 𝒅𝒙 = tan 𝒙 + 𝓒
     ◉ Solve ∫ sec³ 𝒙 𝒅𝒙 by Integration by Parts
          ○ Decomposition strategy:
               ■ ∫ sec³ 𝒙 𝒅𝒙 = ∫ sec 𝒙 · sec² 𝒙 𝒅𝒙
          ○ Choose:
               ■ 𝒖 = sec 𝒙
               ■ 𝒅𝓥 = sec² 𝒙 𝒅𝒙
          ○ Then:
               ■ 𝒅𝒖 = sec 𝒙 tan 𝒙 𝒅𝒙
               ■ 𝓥 = tan 𝒙
          ○ Apply Integration by Parts:
               ■ ∫ sec³ 𝒙 𝒅𝒙 = sec 𝒙 tan 𝒙 − ∫ tan 𝒙 · sec 𝒙 tan 𝒙 𝒅𝒙
               ■ = sec 𝒙 tan 𝒙 − ∫ tan² 𝒙 sec 𝒙 𝒅𝒙
          ○ Use the Pythagorean identity:
               ■ tan² 𝒙 = sec² 𝒙 − 1
          ○ Substitute:
               ■ ∫ sec³ 𝒙 𝒅𝒙 = sec 𝒙 tan 𝒙 − ∫ (sec² 𝒙 − 1)sec 𝒙 𝒅𝒙
               ■ = sec 𝒙 tan 𝒙 − ∫ sec³ 𝒙 𝒅𝒙 + ∫ sec 𝒙 𝒅𝒙
          ○ Solve for the original integral:
               ■ 2∫ sec³ 𝒙 𝒅𝒙 = sec 𝒙 tan 𝒙 + ln|sec 𝒙 + tan 𝒙|
               ■ ∫ sec³ 𝒙 𝒅𝒙 = (1/2)sec 𝒙 tan 𝒙 + (1/2)ln|sec 𝒙 + tan 𝒙| + 𝓒
     ◉ Extension to ∫ sec⁵ 𝒙 𝒅𝒙
          ○ Decomposition strategy:
               ■ ∫ sec⁵ 𝒙 𝒅𝒙 = ∫ sec³ 𝒙 · sec² 𝒙 𝒅𝒙
          ○ Choose:
               ■ 𝒖 = sec³ 𝒙
               ■ 𝒅𝓥 = sec² 𝒙 𝒅𝒙
          ○ Then:
               ■ 𝒅𝒖 = 3sec³ 𝒙 tan 𝒙 𝒅𝒙
               ■ 𝓥 = tan 𝒙
          ○ Apply Integration by Parts:
               ■ ∫ sec⁵ 𝒙 𝒅𝒙 = sec³ 𝒙 tan 𝒙 − 3∫ tan² 𝒙 sec³ 𝒙 𝒅𝒙
          ○ Use tan² 𝒙 = sec² 𝒙 − 1:
               ■ ∫ sec⁵ 𝒙 𝒅𝒙 = sec³ 𝒙 tan 𝒙 − 3∫ (sec² 𝒙 − 1)sec³ 𝒙 𝒅𝒙
               ■ = sec³ 𝒙 tan 𝒙 − 3∫ sec⁵ 𝒙 𝒅𝒙 + 3∫ sec³ 𝒙 𝒅𝒙
          ○ Solve for the original integral:
               ■ 4∫ sec⁵ 𝒙 𝒅𝒙 = sec³ 𝒙 tan 𝒙 + 3∫ sec³ 𝒙 𝒅𝒙
          ○ Substitute the previous result for ∫ sec³ 𝒙 𝒅𝒙:
               ■ 4∫ sec⁵ 𝒙 𝒅𝒙 = sec³ 𝒙 tan 𝒙 + (3/2)sec 𝒙 tan 𝒙 + (3/2)ln|sec 𝒙 + tan 𝒙|
          ○ Final result:
               ■ ∫ sec⁵ 𝒙 𝒅𝒙 = (1/4)sec³ 𝒙 tan 𝒙 + (3/8)sec 𝒙 tan 𝒙 + (3/8)ln|sec 𝒙 + tan 𝒙| + 𝓒
     ◉ Key idea
          ○ Odd powers of secant are handled by peeling off a factor sec² 𝒙 and using Integration by Parts.
          ○ The identity tan² 𝒙 = sec² 𝒙 − 1 converts the remaining expression back into secant powers, creating a recurrence relation.



          


Ｒｅｄｕｃｔｉｏｎ Ｆｏｒｍｕｌａｓ

● [1:29:40]. Development and proof of the Reduction Formula. 
     ◉ NOTE: It is not only for sine. This is specifically the reduction formula for ∫ sinⁿx dx, but similar reduction formulas also exist for cosine, secant, and other families of integrals.
     ◉ Goal:
          ○ Reduce ∫ sinⁿ 𝒙 𝒅𝒙 to an integral involving sinⁿ⁻² 𝒙.
          ○ Assume 𝒏 ≥ 2.
     ◉ Split the integrand:
          ○ ∫ sinⁿ 𝒙 𝒅𝒙 = ∫ sinⁿ⁻¹ 𝒙 · sin 𝒙 𝒅𝒙
     ◉ Apply Integration by Parts.
          ○ Choose:
               ■ 𝒖 = sinⁿ⁻¹ 𝒙
               ■ 𝒅𝓥 = sin 𝒙 𝒅𝒙
          ○ Then:
               ■ 𝒅𝒖 = (𝒏−1) sinⁿ⁻² 𝒙 cos 𝒙 𝒅𝒙
               ■ 𝓥 = −cos 𝒙
     ◉ Substitute into the formula.
          ○ ∫ sinⁿ 𝒙 𝒅𝒙
               ■ = 𝒖𝓥 − ∫ 𝓥 𝒅𝒖
               ■ = −sinⁿ⁻¹ 𝒙 cos 𝒙 + (𝒏−1)∫ cos² 𝒙 sinⁿ⁻² 𝒙 𝒅𝒙
     ◉ Rewrite cos² 𝒙 in terms of sine.
          ○ Use:
               ■ cos² 𝒙 = 1 − sin² 𝒙
          ○ Then:
               ■ ∫ sinⁿ 𝒙 𝒅𝒙
               ■ = −sinⁿ⁻¹ 𝒙 cos 𝒙 + (𝒏−1)∫ (1 − sin² 𝒙) sinⁿ⁻² 𝒙 𝒅𝒙
     ◉ Expand the integral.
          ○ = −sinⁿ⁻¹ 𝒙 cos 𝒙 + (𝒏−1)∫ sinⁿ⁻² 𝒙 𝒅𝒙 − (𝒏−1)∫ sinⁿ 𝒙 𝒅𝒙
     ◉ Collect like terms.
          ○ Add (𝒏−1)∫ sinⁿ 𝒙 𝒅𝒙 to both sides:
               ■ 𝒏∫ sinⁿ 𝒙 𝒅𝒙 = −sinⁿ⁻¹ 𝒙 cos 𝒙 + (𝒏−1)∫ sinⁿ⁻² 𝒙 𝒅𝒙
     ◉ Divide by 𝒏.
          ○ ∫ sinⁿ 𝒙 𝒅𝒙 = −(1/𝒏) sinⁿ⁻¹ 𝒙 cos 𝒙 + ((𝒏−1)/𝒏)∫ sinⁿ⁻² 𝒙 𝒅𝒙
     ◉ Final Reduction Formula for sine:
          ○ ∫ sinⁿ 𝒙 𝒅𝒙 = −(1/𝒏) sinⁿ⁻¹ 𝒙 cos 𝒙 + ((𝒏−1)/𝒏)∫ sinⁿ⁻² 𝒙 𝒅𝒙
          
●  [1:48:13]. 🧩 Example —: ∫ sin⁴ 𝒙 𝒅𝒙. 
     ◉ Apply the Reduction Formula with 𝒏 = 4.
          ○ ∫ sin⁴ 𝒙 𝒅𝒙 = −(1/4) sin³ 𝒙 cos 𝒙 + (3/4) ∫ sin² 𝒙 𝒅𝒙
     ◉ Reduce the remaining integral ∫ sin² 𝒙 𝒅𝒙.
          ○ Apply the Reduction Formula again with 𝒏 = 2:
               ■ ∫ sin² 𝒙 𝒅𝒙 = −(1/2) sin 𝒙 cos 𝒙 + (1/2) ∫ 1 𝒅𝒙
               ■ = −(1/2) sin 𝒙 cos 𝒙 + (1/2)𝒙
     ◉ Substitute this result back into the first expression.
          ○ ∫ sin⁴ 𝒙 𝒅𝒙
               ■ = −(1/4) sin³ 𝒙 cos 𝒙 + (3/4)[−(1/2) sin 𝒙 cos 𝒙 + (1/2)𝒙]
     ◉ Distribute the factor 3/4.
          ○ ∫ sin⁴ 𝒙 𝒅𝒙
               ■ = −(1/4) sin³ 𝒙 cos 𝒙 − (3/8) sin 𝒙 cos 𝒙 + (3/8)𝒙 + 𝓒
     ◉ Final result.
          ○ ∫ sin⁴ 𝒙 𝒅𝒙 = −(1/4) sin³ 𝒙 cos 𝒙 − (3/8) sin 𝒙 cos 𝒙 + (3/8)𝒙 + 𝓒
     



Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

[openstax](https://openstax.org/books/calculus-volume-2/pages/3-1-integration-by-parts)



