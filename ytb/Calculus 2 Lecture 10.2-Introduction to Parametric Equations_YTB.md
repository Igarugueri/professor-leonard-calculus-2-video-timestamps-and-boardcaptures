-----------------------------------**Ｃａｌｃｕｌｕｓ ２ Ｌｅｃｔｕｒｅ １０．２： Ｉｎｔｒｏｄｕｃｔｉｏｎ ｔｏ Ｐａｒａｍｅｔｒｉｃ Ｅｑｕａｔｉｏｎｓ**-------------------------------—





１ - Ｔｈｅｏｒｙ


１．１  Ｂｒａｖｅ　Ｎｅｗ　Ｗｏｒｌｄ　—　Ｐｌａｎｅ　Ｃｕｒｖｅｓ　＆　Ｐａｒａｍｅｔｒｉｃ　Ｅｑｕａｔｉｏｎｓ


● [0:00]. Introduction to a “Brave New World” of Calculus.
     ◉ Goal:
          ○ transition from sequences and series to plane curves, parametric equations, and polar coordinates
     ◉ Main idea:
          ○ parametric equations give a way to describe curves that are difficult or impossible to write as ordinary functions

● [0:55]. Definition — Plane curve.
     ◉ Meaning:
          ○ the motion of an object in a plane
     ◉ Important:
          ○ this is a two-dimensional curve
          ○ it is different from a curve in 3-space
          

１．２  Ｐｒｏｂｌｅｍｓ　ｗｉｔｈ　Ｄｅｆｉｎｉｎｇ　Ｐｌａｎｅ　Ｃｕｒｖｅｓ　ａｓ　Ｏｒｄｉｎａｒｙ　Ｆｕｎｃｔｉｏｎｓ

● [2:20]. Problems with defining a plane curve like a normal function.
     ◉ Problem 1:
          ○ many plane curves are not functions
          ○ for example, circles fail the vertical line test
     ◉ Problem 2:
          ○ many curves cannot be explicitly defined in terms of a single variable
     ◉ Problem 3:
          ○ an ordinary rectangular equation does not tell where the object is at a given time
     ◉ Problem 4:
          ○ an ordinary function does not give the direction of motion
     ◉ Main conclusion:
          ○ rectangular equations often describe the path
          ○ but they do not describe the motion along the path


１．３  Ｐａｒａｍｅｔｒｉｃ　Ｅｑｕａｔｉｏｎｓ

● 

● [9:42]. Definition — Parametric equations.
     ◉ Main idea:
          ○ define both 𝒙 and 𝒚 as functions of a third variable
     ◉ Standard form:
          ○ 𝒙 = 𝒇(𝑻)
          ○ 𝒚 = 𝒈(𝑻)
     ◉ Meaning:
          ○ for each value of t, the equations produce one point (𝒙, 𝒚)
     ◉ Important:
          ○ 𝒙 and 𝒚 are not defined in terms of each other
          ○ both are defined in terms of the same parameter
     ◉ For evample at 𝑻 = 1 tour x is 3 and youy y is 5

● [14:50]. Core terminology of parametric systems.
     ◉ Parameter:
          ○ 𝑻
     ◉ Meaning of the parameter:
          ○ the independent variable on which both 𝒙 and 𝒚 depend
     ◉ Parameter interval:
          ○ 𝐈 = [𝒂, 𝒃]
     ◉ Meaning of the interval:
          ○ it tells where the motion starts and where it stops
     ◉ Orientation:
          ○ the direction in which the object moves as the parameter increases

● [15:50]. Interpretation of the parameter.
     ◉ 𝑻 is usually thought of as time
     ◉ This is only an interpretation:
          ○ 𝑻 may be negative
          ○ it is still just the parameter

● [17:03]. Initial and terminal points.
     ◉ 𝑻 èrtenciente a [𝒂, 𝒃] tiene un nitial point a y terinal oint b
     ◉ Initial point:
          ○ i̲f̲ 𝑻 = 𝒂
               ■ t̲h̲e̲n̲ (𝒙, 𝒚) = (𝒇(𝒂), 𝒈(𝒂))
     ◉ Terminal point:
          ○ i̲f̲ 𝑻 = 𝒃
               ■ t̲h̲e̲n̲ (𝒙, 𝒚) = (𝒇(𝒃), 𝒈(𝒃))
     ◉ Important:
          ○ the curve is traced from the initial point to the terminal point
          ○ si empezamos en un punto y terminamos en otro esto da  this gives the trajectory a specific orientation





２ - Ｅｘａｍｐｌｅｓ


２．１ - Ｅｘａｍｐｌｅ　１　—　Ｐａｒａｂｏｌｉｃ　Ｔｒａｊｅｃｔｏｒｙ

● [23:11]. 🧩 Example 1 — 𝒙 = 𝑻² - 4, 𝒚 = 2𝒕 on -1 ≤ 𝑻 ≤ 2.
     ◉ ❶ Make a 𝒕-table.
          ○ choose values of 𝑻 in the interval
          ○ compute the corresponding points (𝒙, 𝒚)
          ○ for example:
               ■ 𝑻 = -1    →   (𝒙, 𝒚) = (-3, -2)
               ■ 𝑻 = -1/2  →   (𝒙, 𝒚) = (-15/4, -1)
               ■ 𝑻 = 0     →   (𝒙, 𝒚) = (-4, 0)
               ■ 𝑻 = 1/2   →   (𝒙, 𝒚) = (-15/4, 1)
               ■ 𝑻 = 1     →   (𝒙, 𝒚) = (-3, 2)
               ■ 𝑻 = 2     →   (𝒙, 𝒚) = (0, 4)
     ◉ ❷ Plot the points in the 𝒙𝒚-plane.
     ◉ ❸ Connect the points with a smooth curve.
     ◉ ❹ Identify the motion.
          ○ Initial Point:
               ■ 𝑻 = -1  →  (𝒙, 𝒚) = (-3, -2)
          ○ Terminal Point:
               ■ 𝑻 = 2  →  (𝒙, 𝒚) = (0, 4)
          ○ Orientation:
               ■ the motion goes upward along the curve

● [33:04]. Eliminating the parameter.
     ◉ Solve for 𝑻 from 𝒚 = 2𝒕:
          ○ 𝑻 = 𝒚/2
     ◉ Substitute into 𝒙 = 𝒕² - 4:
          ○ 𝒙 = (𝒚/2)² - 4
     ◉ Rectangular form:
          ○ 𝒙 = 𝒚²/4 - 4
     ◉ Warning:
          ○ this rectangular equation describes the whole parabola
          ○ but the parameter interval gives only a specific piece of it
          

２．２ - Ｅｘａｍｐｌｅ　２　—　Ｓｑｕａｒｅ　Ｒｏｏｔ　＆　Ｎａｔｕｒａｌ　Ｄｏｍａｉｎ

● 

● Natural domain.
     ◉ i̲f̲ no interval is given,
          ○ t̲h̲e̲n̲ use the natural domain for 𝒕

● [37:02]. 🧩 Example 2 — 𝒙 = √𝒕, 𝒚 = 𝑻
     ◉ ❶ Find the natural domain for 𝒕.
          ○ since √𝒕 is defined only for 𝑻 ≥ 0,
               ■ the natural domain is 𝑻 ≥ 0
               ■ so the parameter interval is 𝐈 = [0, ∞)
     ◉ ❷ Eliminate the parameter.
          ○ 𝒙 = √𝒕
          ○ square both sides:
               ■ 𝑻 = 𝒙²
          ○ substitute into 𝒚 = 𝒕
               ■ 𝒚 = 𝒙²
     ◉ ❸ Restrict the rectangular curve.
          ○ since 𝑻 ≥ 0 and 𝒙 = √𝒕,
               ■ 𝒙 ≥ 0
          ○ so we keep only the right half of the parabola 𝒚 = 𝒙²
     ◉ ❹ Identify the motion.
          ○ Initial Point:
               ■ 𝑻 = 0  →  (𝒙, 𝒚) = (0, 0)
          ○ Terminal Point:
               ■ none
          ○ Orientation:
               ■ the object moves from the origin toward positive infinity along the right half of the parabola
               

２．３ - Ｅｘａｍｐｌｅ　３　—　Ｓａｍｅ　Ｐａｔｈ，Ｄｉｆｆｅｒｅｎｔ　Ｍｏｔｉｏｎ

● [42:10]. 🧩 Example 3 — 𝒙 = 𝑻, 𝒚 = 𝑻².
     ◉ ❶ Eliminate the parameter.
          ○ since 𝒙 = 𝑻,
               ■ substitute into 𝒚 = 𝑻²
               ■ 𝒚 = 𝒙²
     ◉ ❷ Identify the natural domain.
          ○ there are no restrictions on 𝑻
          ○ so the parameter interval is 𝐈 = (-∞, ∞)
     ◉ ❸ Interpret the motion.
          ○ i̲f̲ 𝑻 → -∞,
               ■ t̲h̲e̲n̲ 𝒙 → -∞ and 𝒚 → ∞
          ○ i̲f̲ 𝑻 = 0,
               ■ t̲h̲e̲n̲ (𝒙, 𝒚) = (0, 0)
          ○ i̲f̲ 𝑻 → ∞,
               ■ t̲h̲e̲n̲ 𝒙 → ∞ and 𝒚 → ∞
     ◉ Final interpretation:
          ○ the rectangular path is the same as in Example 2:
               ■ 𝒚 = 𝒙²
          ○ but the motion is different
          ○ the object starts high in the second quadrant
          ○ moves down toward the origin
          ○ then continues up into the first quadrant
     ◉ Main lesson:
          ○ the same rectangular curve can correspond to different motions
          

２．４ - Ｅｘａｍｐｌｅ　４　—　Ｔｒｉｇｏｎｏｍｅｔｒｉｃ　Ｃｉｒｃｌｅｓ

● [46:14]. 🧩 Example 4 — 𝒙 = 𝒂 cos(θ), 𝒚 = 𝒂 sin(θ), with 𝒂 > 0.
     ◉ Parameter:
          ○ θ is the parameter
     ◉ Given:
          ○ 𝒙 = 𝒂 cos(θ)
          ○ 𝒚 = 𝒂 sin(θ)
     ◉ Isolate the trig parts:
          ○ cos(θ) = 𝒙/𝒂
          ○ sin(θ) = 𝒚/𝒂
     ◉ Use the Pythagorean identity:
          ○ cos²(θ) + sin²(θ) = 1
     ◉ Substitute:
          ○ (𝒙/𝒂)² + (𝒚/𝒂)² = 1
     ◉ Rectangular form:
          ○ 𝒙² + 𝒚² = 𝒂²
     ◉ Conclusion:
          ○ the curve is a circle of radius 𝒂 centered at the origin

● [54:58]. Points and orientation for 𝐈 = [0, π].
     ◉ Initial Point:
          ○ θ = 0  →  (𝒙, 𝒚) = (𝒂, 0)
     ◉ Midpoint check:
          ○ θ = π/2  →  (𝒙, 𝒚) = (0, 𝒂)
     ◉ Terminal Point:
          ○ θ = π  →  (𝒙, 𝒚) = (-𝒂, 0)
     ◉ Orientation:
          ○ counterclockwise
     ◉ Final interpretation:
          ○ only the top half of the circle is traced

● [1:02:10]. Interval variations.
     ◉ i̲f̲ 𝐈 = [0, 2π]
          ○ t̲h̲e̲n̲ the object traces one full circle
          ○ and makes one full counterclockwise revolution
     ◉ i̲f̲ 𝐈 = [0, 4π]
          ○ t̲h̲e̲n̲ the object traces two full circles
          ○ and makes two full counterclockwise revolutions
          

２．５ - Ｅｘａｍｐｌｅ　５　—　Ｅｌｌｉｐｓｅｓ

● [1:05:17]. 🧩 Example 5 — 𝒙 = 4 cos(θ), 𝒚 = 3 sin(θ), with 𝐈 = [0, 2π].
     ◉ Given:
          ○ 𝒙 = 4 cos(θ)
          ○ 𝒚 = 3 sin(θ)
     ◉ Isolate the trig parts:
          ○ cos(θ) = 𝒙/4
          ○ sin(θ) = 𝒚/3
     ◉ Use the Pythagorean identity:
          ○ 1 = cos²(θ) + sin²(θ)
     ◉ Substitute:
          ○ 1 = (𝒙/4)² + (𝒚/3)²
     ◉ Rectangular form:
          ○ 1 = 𝒙²/16 + 𝒚²/9
     ◉ Conclusion:
          ○ the curve is an ellipse
     ◉ Geometry:
          ○ x-radius = 4
          ○ y-radius = 3

● Points and orientation for 𝐈 = [0, 2π].
     ◉ Initial Point:
          ○ θ = 0  →  𝒙 = 4, 𝒚 = 0
          ○ so the initial point is (4, 0)
     ◉ Midpoint checks:
          ○ θ = π/2  →  𝒙 = 0, 𝒚 = 3
          ○ θ = π    →  𝒙 = -4, 𝒚 = 0
          ○ θ = 3π/2 →  𝒙 = 0, 𝒚 = -3
     ◉ Terminal Point:
          ○ θ = 2π  →  𝒙 = 4, 𝒚 = 0
          ○ so the terminal point is (4, 0)
     ◉ Orientation:
          ○ counterclockwise
     ◉ Final interpretation:
          ○ the object traces the full ellipse once
          ○ it starts and ends at (4, 0)
               

２．６ - Ｅｘａｍｐｌｅ　６　—　Ａｄｖａｎｃｅｄ　Ｔｒｉｇｏｎｏｍｅｔｒｉｃ　Ｃｕｒｖｅ

● [1:17:13]. 🧩 Example 6 — 𝒙 = sin(𝑻), 𝒚 = sin(2𝑻), with 𝐈 = [0, 2π].
     ◉ Use the double-angle identity:
          ○ sin(2𝑻) = 2 sin(𝑻) cos(𝑻)
     ◉ Since 𝒙 = sin(𝑻),
          ○ 𝒚 = 2𝒙 cos(𝑻)
     ◉ Solve for cos(𝑻):
          ○ cos(𝑻) = 𝒚/(2𝒙)
     ◉ Use the Pythagorean identity:
          ○ 1 = cos²(𝑻) + sin²(𝑻)
     ◉ Substitute:
          ○ 1 = (𝒚/(2𝒙))² + 𝒙²
     ◉ Multiply by 4𝒙²:
          ○ 4𝒙² = 𝒚² + 4𝒙⁴
     ◉ Rectangular form:
          ○ 0 = 4𝒙⁴ - 4𝒙² + 𝒚²

● [1:24:14]. Visual analysis and symmetry.
     ◉ The equation contains only even powers of 𝒙.
          ○ therefore the curve is symmetric about the 𝒚-axis
     ◉ The variable 𝒚 appears squared.
          ○ therefore the curve is symmetric about the 𝒙-axis
     ◉ Strategy:
          ○ plot the part of the curve for 𝑻 in [0, π/2]
          ○ then use symmetry across both axes

● Plot [0, π/2] and use symmetry.
     ◉ Useful points:
          ○ 𝑻 = 0      →   𝒙 = 0,        𝒚 = 0
          ○ 𝑻 = π/6    →   𝒙 = 1/2,      𝒚 = √3/2
          ○ 𝑻 = π/4    →   𝒙 = √2/2,     𝒚 = 1
          ○ 𝑻 = π/3    →   𝒙 = √3/2,     𝒚 = √3/2
          ○ 𝑻 = π/2    →   𝒙 = 1,        𝒚 = 0

● Final shape and motion.
     ◉ Shape:
          ○ a figure-eight curve
     ◉ Motion:
          ○ the object starts at (0, 0)
          ○ traces the right loop first
          ○ returns to the origin at 𝑻 = π
          ○ then traces the left loop
          ○ and returns to the origin at 𝑻 = 2π

● N̲O̲T̲E̲ — Strategy for eliminating the parameter in trig parametric equations.
     ◉ First try to isolate the parameter.
     ◉ i̲f̲ that is not possible,
          ○ t̲h̲e̲n̲ isolate a trigonometric expression involving the parameter,
          ○ and use an identity to relate the expressions
     ◉ In this example:
          ○ do not try to isolate 𝑻 with an inverse trig function
          ○ instead, isolate sin(𝑻) or cos(𝑻)
          ○ then use the Pythagorean identity



          

Ｎｏｔｅｓ　＆　Ｓｔｒａｔｅｇｙ

● Main workflow for graphing a parametric curve.
     ◉ ❶ Find the rectangular path if possible(find a curve that you can sketch
          ○ eliminate the parameter
          ○ or use trig identities to relate 𝒙 and 𝒚
     ◉ ❷ Sketch the curve described by the rectangular equation.
     ◉ ❸ Use the parameter interval to find:
          ○ the initial point
          ○ the terminal point
          ○ the direction of motion
     ◉ ❹ Remember:
          ○ the rectangular equation gives the path
          ○ the parameter interval tells which part of the path is traced
          ○ and in which direction

● N̲O̲T̲E̲ — Same path does not mean same motion.
     ◉ Different parametric equations may describe the same rectangular curve.
     ◉ However:
          ○ they may start at different points
          ○ move in different directions
          ○ or trace only part of the curve



 
Ａｄｄｉｔｉｏｎａｌ　ｒｅｓｏｕｒｃｅｓ

● Parametric Equations
     ◉ [openstax🌐](https://openstax.org/books/calculus-volume-2/pages/7-1-parametric-equations)