# definite-integral-calculator
Program to calculate definite integral using main methods and determing the course of the first order derivative. 


GUI is divided into 3 modules: 

1) Calculating definite integrals
2) Comparing method results 
3) Visualization of the first order derivative graph



## Table of contents
* [Summary](#summary)
* [Methods used](#methods)
* [GUI tabs](#gui)
* [Compare results of definite integral](#compare-results)
* [Visualization of derivative graph](#visualization)

## Summary


## Methods

### Definite integral
1) Rectangle rule
2) Rectangle midpoint rule
3) Trapezoidal rule
4) Simpson rule
5) Monte Carlo

### Order derivative 
1) Backward differentiation
2) Central differentiation
3) Forward differentiation
4) All above with Richardson's extrapolation

## GUI

![Guiexample](./images/definite_integral_inputing_data1.jpg)

Image presents main tab of program wich will be shown after start, with 4 text inputs from wich data is begin loaded. 
Input on top serves a purpouse to aquire function of definite integral. Example of input:  
`
x^3 + 3x + 2
`

Where 'x' is function and number after '^' represents power of function. 

Input just below is designed to take number of definite integral's subintervals.

Third input's function is to take lower border.

The last one takes higher border.



![Guiexample](./images/order_derivative1.jpg)

Second example

## Compare-results

![Guiexample](./images/definite_integral_comparing_methods.jpg)

After user delivered data and pressed calculation, program offers ability to compare method  results. This image shows that. User can chose methods he wants to compare, add standard error or standard deviation. 

![Guiexample](./images/definite_integral_comparing_methods2.jpg)

Image shows results when all options are selected. 

# Visualization

![Guiexample](./images/order_derivative1.jpg)

This tab is designed for the first order integral dettermination. User can fill all inputs in order to start calculation or all data can be loaded from the file.

![Guiexample](./images/chart_derivative.jpg)

After loading data and pressing calculate button graph of function is being created.


![Guiexample](./images/chart_derivative.jpg)


![Guiexample](./images/chart_derivative_and.jpg)

User can hover mose over blue graph points/dots to chose tangent line to calculate. This image shows example of that.

![Guiexample](./images/chart_derivative_only.jpg)

This image shows option to show only tangent line with out graph.

![Guiexample](./images/chart_derivative2.jpg)

Here all options are selected, that allows to see graphical diffrences between diffrent methods.
