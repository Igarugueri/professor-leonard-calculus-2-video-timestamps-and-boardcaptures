-------------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ １０．５： Ｃａｌｃｕｌｕｓ ｏｆ Ｐｏｌａｒ Ｅｑｕａｔｉｏｎｓ**----------------------------------





１ - Ｃａｌｃｕｌｕｓ　ｏｆ　Ｐｏｌａｒ　Ｅｑｕａｔｉｏｎｓ


１．１ - Ａｒｅａ　Ｂｏｕｎｄ　ｂｙ　ａ　Ｐｏｌａｒ　Ｃｕｒｖｅ

● [0:17]. Goal — Find the area bound by a polar curve.
     ◉ Main idea:
          ○ in rectangular coordinates, area is built from rectangles
          ○ in polar coordinates, area is built from sectors
     ◉ Setup:
          ○ the curve is given by 𝒓 = 𝒇(𝜽)
          ○ the region runs from angle 𝜶 to angle 𝜷
     ◉ Sector area:
          ○ 𝓐 = (1/2)𝒓²𝜽
     ◉ Infinitesimal idea:
          ○ split the region into many tiny sectors
          ○ let the angle width 𝒅𝜽 go to zero
          ○ then the sum of all those tiny sector areas becomes an integral
     ◉ Final formula:
          ○ 𝓐 = ∫[𝜶,𝜷] (1/2)𝒓² 𝒅𝜽

● [3:58]. Why the formula works.
     ◉ The integral adds:
          ○ an infinite number of tiny sector areas
     ◉ Since the variable is angular,
          ○ the integration is with respect to 𝜽
     ◉ Meaning:
          ○ polar area is accumulated by angle, not by horizontal width
     ◉ Visual interpretation:
          ○ the bounded region is swept out from 𝜽 = 𝜶 to 𝜽 = 𝜷
          ○ while 𝒓 changes according to the curve 𝒓 = 𝒇(𝜽)


● [6:06]. 🧩 Example 1 — Find the area bound by 𝒓² = 4 cos(2𝜽). 
     ◉ Goal:
          ○ find the total area of the entire figure
     ◉ Rewrite:
          ○ 𝒓 = 2√(cos(2𝜽))
     ◉ Use previous graph knowledge:
          ○ one loop is traced from 𝜽 = 0 to 𝜽 = π/4
          ○ at 𝜽 = 0:
               ■ 𝒓 = 2
          ○ at 𝜽 = π/4:
               ■ 𝒓 = 0
     ◉ Symmetry:
          ○ the whole figure has 4 congruent pieces
     ◉ Strategy:
          ○ find the area of one piece from 0 to π/4
          ○ then multiply by 4
     ◉ Set up:
          ○ 𝓐 = 4∫[0,π/4] (1/2)𝒓² 𝒅𝜽
     ◉ Substitute 𝒓² = 4 cos(2𝜽):
          ○ 𝓐 = 4∫[0,π/4] (1/2)(4 cos(2𝜽)) 𝒅𝜽
          ○ 𝓐 = 8∫[0,π/4] cos(2𝜽) 𝒅𝜽
     ◉ Integrate:
          ○ 𝓐 = 8 · sin(2𝜽)/2 │[0,π/4]
          ○ 𝓐 = 4 sin(2𝜽) │[0,π/4]
     ◉ Evaluate:
          ○ 𝓐 = 4 sin(2·π/4) - 4 sin(2·0)
          ○ 𝓐 = 4 sin(π/2) - 4 sin(0)
          ○ 𝓐 = 4
     ◉ Final result:
          ○ 𝓐 = 4
     ◉ Final interpretation:
          ○ each of the four congruent pieces has area 1


● [13:57]. 🧩 Example 2 — Find the area bound by 𝒓 = 1 + cos(𝜽). 
     ◉ Goal:
          ○ find the total area of the cardioid
     ◉ Symmetry:
          ○ the graph is symmetric about the polar axis
     ◉ Strategy:
          ○ find the upper half from 0 to π
          ○ then multiply by 2
     ◉ Set up:
          ○ 𝓐 = 2∫[0,π] (1/2)(1 + cos(𝜽))² 𝒅𝜽
          ○ the factor 2 and the factor 1/2 cancel
          ○ so:
               ■ 𝓐 = ∫[0,π] (1 + cos(𝜽))² 𝒅𝜽
     ◉ Expand:
          ○ 𝓐 = ∫[0,π] (1 + 2 cos(𝜽) + cos²(𝜽)) 𝒅𝜽
     ◉ Use the power-reduction identity:
          ○ cos²(𝜽) = (1 + cos(2𝜽))/2
     ◉ Substitute:
          ○ 𝓐 = ∫[0,π] (1 + 2 cos(𝜽) + (1/2)(1 + cos(2𝜽))) 𝒅𝜽
     ◉ Simplify the integrand:
          ○ 𝓐 = ∫[0,π] (3/2 + 2 cos(𝜽) + (1/2) cos(2𝜽)) 𝒅𝜽
     ◉ Integrate:
          ○ 𝓐 = [ (3/2)𝜽 + 2 sin(𝜽) + (1/4) sin(2𝜽) ]│[0,π]
     ◉ Evaluate:
          ○ 𝓐 = [ (3/2)π + 2 sin(π) + (1/4) sin(2π) ] - [ 0 + 2 sin(0) + (1/4) sin(0) ]
          ○ 𝓐 = 3π/2
     ◉ Final result:
          ○ 𝓐 = 3π/2
     ◉ Final interpretation:
          ○ the total area enclosed by the cardioid is 3π/2



１．２ - Ａｒｅａ　Ｂｅｔｗｅｅｎ　Ｔｗｏ　Ｐｏｌａｒ　Ｃｕｒｖｅｓ

● [23:17]. Area between two polar curves.
     ◉ Suppose:
          ○ 𝒓₁ = 𝒇(𝜽)
          ○ 𝒓₂ = 𝒈(𝜽)
          ○ on the interval [𝜶, 𝜷]
     ◉ Main idea:
          ○ this is the polar version of big curve minus little curve
          ○ but instead of subtracting rectangular strips,
               ■ we subtract sector areas
     ◉ Recall:
          ○ the area bound by one polar curve is
               ■ ∫[𝜶,𝜷] (1/2)𝒓² 𝒅𝜽
     ◉ So for two curves:
          ○ first find the area of the outer sector-region
          ○ then subtract the area of the inner sector-region
     ◉ Outer curve:
          ○ the one farther from the pole
     ◉ Inner curve:
          ○ the one closer to the pole
     ◉ Set up with 𝒓₁ and 𝒓₂:
          ○ 𝓐 = ∫[𝜶,𝜷] (1/2)𝒓₁² 𝒅𝜽 - ∫[𝜶,𝜷] (1/2)𝒓₂² 𝒅𝜽
     ◉ Combine the integrals:
          ○ 𝓐 = ∫[𝜶,𝜷] (1/2)(𝒓₁² - 𝒓₂²) 𝒅𝜽
     ◉ Replace 𝒓₁ and 𝒓₂ by their functions:
          ○ 𝓐 = ∫[𝜶,𝜷] (1/2)(𝒇(𝜽)² - 𝒈(𝜽)²) 𝒅𝜽
     ◉ Meaning:
          ○ at each angle 𝜽,
               ■ take the big sector minus the little sector
          ○ then add all those sector differences from 𝜶 to 𝜷
     ◉ Important:
          ○ the bounds [𝜶, 𝜷] must describe the region you actually want
          ○ and on that interval you must know which curve is outer and which is inner
     ◉ Final interpretation:
          ○ this is the polar analogue of
               ■ upper function minus lower function
          ○ except here it becomes
               ■ outer radius squared minus inner radius squared


● [28:30]. 🧩 Example 3 — Find the area between 𝒓 = 3 and 𝒓 = 2 + 2 cos(𝜽).
     ◉ Goal:
          ○ find the region where the cardioid lies outside the circle
     ◉ Identify the curves:
          ○ 𝒓 = 3 is a circle of radius 3
          ○ 𝒓 = 2 + 2 cos(𝜽) = 2(1 + cos(𝜽))
          ○ so the second curve is a larger sideways cardioid
     ◉ First find the intersection angles.
          ○ set the two curves equal:
               ■ 3 = 2 + 2 cos(𝜽)
          ○ solve:
               ■ 1 = 2 cos(𝜽)
               ■ cos(𝜽) = 1/2
          ○ therefore:
               ■ 𝜽 = π/3
               ■ 𝜽 = 5π/3
     ◉ Important interval choice:
          ○ Leonard rewrites 5π/3 as −π/3
          ○ reason:
               ■ the desired shaded region is swept in the positive direction from −π/3 to π/3
          ○ so the natural interval is:
               ■ [−π/3, π/3]
     ◉ Outer minus inner on this interval:
          ○ outer curve = 2 + 2 cos(𝜽)
          ○ inner curve = 3
     ◉ Direct setup:
          ○ 𝓐 = ∫[−π/3, π/3] (1/2)[(2 + 2 cos(𝜽))² − 3²] 𝒅𝜽
     ◉ Symmetry shortcut:
          ○ the region is symmetric about the polar axis
          ○ so Leonard instead uses:
               ■ 𝓐 = 2∫[0,π/3] (1/2)[(2 + 2 cos(𝜽))² − 3²] 𝒅𝜽
          ○ the 2 and the 1/2 cancel
     ◉ Simplify the integrand:
          ○ (2 + 2 cos(𝜽))² = 4 + 8 cos(𝜽) + 4 cos²(𝜽)
          ○ so:
               ■ 𝓐 = ∫[0,π/3] [4 + 8 cos(𝜽) + 4 cos²(𝜽) − 9] 𝒅𝜽
               ■ 𝓐 = ∫[0,π/3] [−5 + 8 cos(𝜽) + 4 cos²(𝜽)] 𝒅𝜽
     ◉ Use power reduction:
          ○ cos²(𝜽) = (1 + cos(2𝜽))/2
          ○ then:
               ■ 4 cos²(𝜽) = 2 + 2 cos(2𝜽)
          ○ so the integral becomes:
               ■ 𝓐 = ∫[0,π/3] [−3 + 8 cos(𝜽) + 2 cos(2𝜽)] 𝒅𝜽
     ◉ Integrate:
          ○ 𝓐 = [−3𝜽 + 8 sin(𝜽) + sin(2𝜽)]₀^{π/3}
     ◉ Evaluate:
          ○ 𝓐 = −3(π/3) + 8 sin(π/3) + sin(2π/3)
          ○ 𝓐 = −π + 8(√3/2) + √3/2
          ○ 𝓐 = −π + 9√3/2
     ◉ Final result:
          ○ 𝓐 = (9√3)/2 − 𝝅
     ◉ Final interpretation:
          ○ this is the area of the part of the cardioid that extends outside the circle



１．３ - Ａｒｃ　Ｌｅｎｇｔｈ　ｏｆ　ａ　Ｐｏｌａｒ　Ｃｕｒｖｅ

● [49:34]. Arc length for 𝒓 = 𝒇(𝜽). 
     ◉ Goal:
          ○ find the distance along a polar curve from 𝜽 = 𝜶 to 𝜽 = 𝜷
     ◉ Formula:
          ○ 𝓛 = ∫[𝜶,𝜷] √(𝒓² + (𝒅𝒓/𝒅𝜽)²) 𝒅𝜽
     ◉ Structure of the formula:
          ○ square the radius term 𝒓
          ○ square the derivative term 𝒅𝒓/𝒅𝜽
          ○ add them
          ○ take the square root
          ○ integrate with respect to 𝜽
     ◉ Important:
          ○ this is the polar analogue of the arc length formulas from rectangular and parametric calculus
     ◉ Interpretation:
          ○ the formula measures the total length of the curve as the angle sweeps from 𝜶 to 𝜷
     ◉ Practical workflow:
          ○ ❶ compute 𝒅𝒓/𝒅𝜽
          ○ ❷ form 𝒓² + (𝒅𝒓/𝒅𝜽)²
          ○ ❸ simplify the square root as much as possible
          ○ ❹ integrate over [𝜶, 𝜷]



１．４ - Ｓｕｒｆａｃｅ　Ａｒｅａ　ｏｆ　Ｒｅｖｏｌｕｔｉｏｎ　ｉｎ　Ｐｏｌａｒ　Ｆｏｒｍ

● [52:39]. Surface area of revolution for a polar curve.
     ◉ Main idea:
          ○ surface area is built from
               ■ circumference × arc length element
     ◉ Recall the polar arc length element:
          ○ 𝒅𝒔 = √(𝒓² + (𝒅𝒓/𝒅𝜽)²) 𝒅𝜽
     ◉ So the general structure is:
          ○ 𝓢 = ∫ circumference · 𝒅𝒔
     ◉ Important idea:
          ○ the radius of the little circles of revolution is not the polar radius 𝒓 itself
          ○ it is the appropriate rectangular component of the point on the curve


● [55:40]. Revolution about the polar axis. 
     ◉ This is the 𝒙-axis analogue.
     ◉ Radius of each circle:
          ○ the distance to the polar axis is the 𝒚-coordinate
          ○ 𝒚 = 𝒓 sin(𝜽)
     ◉ Circumference term:
          ○ 2𝝅(𝒓 sin(𝜽))
     ◉ Formula:
          ○ 𝓢 = ∫[𝜶,𝜷] 2𝝅 · 𝒓 sin(𝜽) · √(𝒓² + (𝒅𝒓/𝒅𝜽)²) 𝒅𝜽
     ◉ Interpretation:
          ○ circumference of the circular slice × polar arc length element


● [58:30]. Revolution about the line 𝜽 = π/2. 
     ◉ This is the 𝒚-axis analogue.
     ◉ Radius of each circle:
          ○ the distance to the line 𝜽 = π/2 is the 𝒙-coordinate
          ○ 𝒙 = 𝒓 cos(𝜽)
     ◉ Circumference term:
          ○ 2𝝅(𝒓 cos(𝜽))
     ◉ Formula:
          ○ 𝓢 = ∫[𝜶,𝜷] 2𝝅 · 𝒓 cos(𝜽) · √(𝒓² + (𝒅𝒓/𝒅𝜽)²) 𝒅𝜽
     ◉ Interpretation:
          ○ circumference of the circular slice × polar arc length element

● Notes.
     ◉ N̲O̲T̲E̲ 1 — Why 𝒙 and 𝒚 appear.
          ○ even though the curve is given in polar form,
               ■ the radius of revolution is measured as a rectangular distance to the axis
          ○ around the polar axis, that distance is 𝒚
          ○ around the line 𝜽 = π/2, that distance is 𝒙
     ◉ N̲O̲T̲E̲ 2 — Main workflow.
          ○ ❶ Identify the axis of revolution.
          ○ ❷ Choose the correct radius:
               ■ 𝒓 sin(𝜽) for the polar axis
               ■ 𝒓 cos(𝜽) for the line 𝜽 = π/2
          ○ ❸ Compute 𝒅𝒓/𝒅𝜽.
          ○ ❹ Form the arc length factor:
               ■ √(𝒓² + (𝒅𝒓/𝒅𝜽)²)
          ○ ❺ Multiply by 2𝝅 times the appropriate radius.
          ○ ❻ Integrate from 𝜶 to 𝜷.
     ◉ N̲O̲T̲E̲ 3 — Conceptual summary.
          ○ same philosophy as in Calc 1:
               ■ circumference × length
          ○ only now everything is written in terms of 𝜽 and polar components



２．４.  １ - Ｅｘａｍｐｌｅ  4 

● [1:01:26]. 🧩 Example 4 —  Find the intersections of the polar curves 𝒓 = cos(𝜽) and 𝒓 = cos(2𝜽).
     ◉ Goal:
          ○ determine all geometric points where the two curves intersect
     ◉ Main workflow:
          ○ ❶ set the two equations equal to find intersections reached at the same angle 𝜽
          ○ ❷ solve for the possible angle values
          ○ ❸ compute the corresponding radius 𝒓 for each valid angle
          ○ ❹ check separately whether both curves also pass through the pole 𝒓 = 0
     ◉ Why the extra pole check is necessary:
          ○ in polar coordinates, the same geometric point can be reached with different angle values
          ○ so two curves may both pass through the origin even if that does not appear from setting the equations equal

● [1:02:50]. Set the curves equal.
     ◉ Same-angle intersection condition:
          ○ cos(𝜽) = cos(2𝜽)
     ◉ Use the identity:
          ○ cos(2𝜽) = 2 cos²(𝜽) - 1
     ◉ Substitute:
          ○ cos(𝜽) = 2 cos²(𝜽) - 1
     ◉ Rearrange:
          ○ 0 = 2 cos²(𝜽) - cos(𝜽) - 1
     ◉ Factor:
          ○ 0 = (2 cos(𝜽) + 1)(cos(𝜽) - 1)

● [1:05:26]. Solve the factored equation.
     ◉ Case 1:
          ○ cos(𝜽) - 1 = 0
          ○ cos(𝜽) = 1
          ○ 𝜽 = 0
     ◉ Find the corresponding radius:
          ○ 𝒓 = cos(0) = 1
     ◉ First intersection point:
          ○ (1, 0)
     ◉ Case 2:
          ○ 2 cos(𝜽) + 1 = 0
          ○ cos(𝜽) = -1/2
          ○ 𝜽 = 2π/3 and 4π/3
     ◉ Find the corresponding radius:
          ○ 𝒓 = cos(2π/3) = -1/2
          ○ 𝒓 = cos(4π/3) = -1/2
     ◉ Additional intersection points:
          ○ (-1/2, 2π/3)
          ○ (-1/2, 4π/3)
          
● [1:07:08]. Important interpretation.
     ◉ Do not stop after finding only 𝜽.
     ◉ A polar intersection point must be written as:
          ○ (𝒓, 𝜽)
     ◉ So after solving for 𝜽,
          ○ always substitute back to get 𝒓
     ◉ Warning:
          ○ do not mix radius values from one case with angles from another case
          ○ each point must come from one consistent solved case

● [1:08:45]. Why negative radii look strange.
     ◉ A point like:
          ○ (-1/2, 2π/3)
     ◉ Means:
          ○ start at angle 2π/3
          ○ then move in the opposite direction because the radius is negative
     ◉ So negative-𝒓 points are valid polar points,
          ○ not mistakes

● [1:10:03]. Special check — Does either curve pass through the pole?
     ◉ For 𝒓 = cos(𝜽):
          ○ 𝒓 = 0 when cos(𝜽) = 0
          ○ 𝜽 = π/2, 3π/2
     ◉ For 𝒓 = cos(2𝜽):
          ○ 𝒓 = 0 when cos(2𝜽) = 0
          ○ 𝜽 = π/4, 3π/4, 5π/4, 7π/4
     ◉ Therefore:
          ○ both curves pass through the pole
     ◉ Important:
          ○ they reach the origin at different angle values
          ○ so this intersection does not necessarily appear when solving cos(𝜽) = cos(2𝜽)

● [1:11:32]. Pole intersection.
     ◉ Since both curves pass t hrough 𝒓 = 0,
          ○ the origin is also an intersection point
     ◉ Final extra intersection:
          ○ 𝒓 = 0

● [1:12:02]. Final list of intersections.
     ◉ Intersections found from equal-angle solving:
          ○ (1, 0)
          ○ (-1/2, 2π/3)
          ○ (-1/2, 4π/3)
     ◉ Additional pole intersection:
          ○ 𝒓 = 0
     ◉ Final interpretation:
          ○ the total intersections are
               ■ (1, 0)
               ■ (-1/2, 2π/3)
               ■ (-1/2, 4π/3)
               ■ and the pole 𝒓 = 0

● Notes & Strategy.
     ◉ N̲O̲T̲E̲ 1 — In polar coordinates, equal geometric points do not always require equal angles.
     ◉ N̲O̲T̲E̲ 2 — Setting 𝒇(𝜽) = 𝒈(𝜽) only finds intersections that occur with the same parameter angle.
     ◉ N̲O̲T̲E̲ 3 — Always check the pole separately when solving intersection problems in polar form.
     ◉ N̲O̲T̲E̲ 4 — Final answer must be a list of points, not just angle values.





３ - Ｎｏｔｅｓ　＆　Ｓｔｒａｔｅｇｙ

● N̲O̲T̲E̲ 1 — How to think about polar area.
     ◉ rectangular area adds thin rectangles
     ◉ polar area adds thin sectors
     ◉ the variable of accumulation is 𝜽

● N̲O̲T̲E̲ 2 — Main workflow for area bound by one polar curve.
     ◉ ❶ Identify the graph or the relevant traced piece.
     ◉ ❷ Find the correct angle interval [𝜶, 𝜷].
     ◉ ❸ Use symmetry whenever possible.
     ◉ ❹ Apply:
          ○ 𝓐 = ∫[𝜶,𝜷] (1/2)𝒓² 𝒅𝜽

● N̲O̲T̲E̲ 3 — Main workflow for area between two polar curves.
     ◉ ❶ Find the intersection angles first.
     ◉ ❷ Determine which interval traces the desired region.
     ◉ ❸ Identify the outer curve and the inner curve.
     ◉ ❹ Apply:
          ○ 𝓐 = ∫[𝜶,𝜷] (1/2)(outer² - inner²) 𝒅𝜽
     ◉ ❺ Use symmetry to simplify the bounds whenever possible.

● N̲O̲T̲E̲ 4 — Why interval choice matters.
     ◉ in polar problems, the bounds are angles
     ◉ choosing the wrong angular interval can produce the wrong region
     ◉ always think geometrically about the direction of the sweep

● N̲O̲T̲E̲ 5 — The pole can be an intersection even when equal-angle solving misses it.
     ◉ two polar curves may reach the origin at different angle values
     ◉ so solving 𝒓₁ = 𝒓₂ does not always capture every intersection
     ◉ always check separately whether both curves pass through 𝒓 = 0




Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Polar Coordinates
     ◉ [Openstax🌐](https://openstax.org/books/calculus-volume-2/pages/7-3-polar-coordinates)

● Area and Arc Length in Polar Coordinates
     ◉ [Openstax🌐](https://openstax.org/books/calculus-volume-2/pages/7-4-area-and-arc-length-in-polar-coordinates)