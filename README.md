# Least-Squares

Steps To find the line of best fit for N points:

  Step 1: For each (x,y) point calculate x2 and xy

  Step 2: Sum all x, y, x2 and xy, which gives us Σx, Σy, Σx2 and Σxy (Σ means "sum up")

  Step 3: Calculate Slope m:
  
                                      m =  (N Σ(xy) − Σx Σy)/(N Σ(x**2) − (Σx)**2))   (N is the number of points.)

  Step 4: Calculate Intercept b:

                                      b =  Σy − m Σx/N

Step 5: Assemble the equation of a line

                                      y = mx + b

Done!

Second is the polyfit function method from the numpy library!
