## Bivariate Calculatons


### Part 1

We will be doing two bivariate calculations. One by hand together and one using Python.

In this first step, we will calculate by hand.

| Test Score (out of 10) | Hours Playing Video Games |
|------------------------|---------------------------|
| 8                      |2                          |
| 3                      |2                          |
| 5                      |1.5                        |     
| 7                      |1                          |
| 1                      |2.5                        |
| 2                      |3                          |
| 6                      |1.5                        |
| 7                      |2                          |
| 4                      |2                          |
| 9                      |1.5                        |


As a reminder, here are the steps (refer to PowerPoint for graphics):

1. Calculate the x mean (x_bar) and y mean (y_bar)
x_bar = 5.2  y_bar = 1.9
2. subtract each value of x by the mean of x (x_i - x_bar) deviance of x
8-5.2 = 2.8                 
3-5.2 = -2.2                
5-5.2 = -0.2                
7-5.2 = 1.8                 
1-5.2 = -4.2                
2-5.2 = -3.2                
6-5.2 = 0.8                 
7-5.2 = 1.8                 
4-5.2 = 1.2                               
9-5.2 = 3.8                 
3. subtract each value of y by the mean of y (y_i - y_bar) deviance of y
2-1.9 = 0.1
2-1.9 = 0.1
1.5-1.9 = -0.4
1-1.9 = 0.9
2.5-1.9 = 0.6
3-1.9 = 1.1
1.5-1.9 = -0.4
2-1.9 = 0.1
2-1.9 = 0.1                 
1.5-1.9 = -0.4
4. multiply each value of (2) and (3) together for each x, y pair (x_i - x_bar) * (y_i - y_bar)
2.8 * 0.1 = .28
-2.2 * 0.1 = -0.22
-0.2 * -0.4 = -0.08
1.8 * 0.9 = 1.62
-4.2 * 0.6 = -2.52
-3.2 * 1.1 = -3.52
0.8 * -0.4 = -0.32
1.8 * 0.1 = 0.18
1.2 * 0.1 = 0.12
3.8 * -0.4 = -1.52

5. add all the values of (4) together
-5.98
6. square the values of (2) squared deviance of x
7.84
4.84
0.04
3.24
17.64
10.24
0.64
3.24
1.44
14.44
7. square the values of (3) squared deviance of y
0.01
0.01
0.16
0.81
0.36
1.21
0.16
0.01
0.01
0.16
8. Add the values of (6) and add up the values of (7) then multiply them together
63.6 * 2.9 = 184.44
9. Take the sqrt of (8)
13.58
10. Divide (5) by (9)
-5.98/184.44 = -0.032


### Part 2 Python Calculation

Open the `bivar.ipynb` file and follow the instructions in the notebook as you do the same calculations but using Python!

We will first do a step-by-step method and then use pandas to help us out with the same steps but in a more efficient manner.

