# Mathematical-Modeling

This is a collection of python programs that model different mathematical phenomena. To quickly find the right file, just look up the file name below and put it in the repo's 'Go to file' button on top.

## Summation Formulae
These model summation formulae for constants and the first n natural numbers (along with their squares and cubes). The code can be found in `SumFormulae.py`

## Farey's Algorithm
Not the complete algorithm for generating Farey sequences, but it kind of works - there are some extra terms in the sequence it spits out. The code can be found in `Farey.py`

## Wave function of a particle in a box with infinitely high walls
This soultion to the time independent Schrödinger equation in 1 dimension is ploted out for the first 5 lowest possible energies in `InfiniteWall.py`

## Legendre Polynomials
The first 5 solutions to [Legendre's differential equation](https://en.wikipedia.org/wiki/Legendre_polynomials#Definition_via_differential_equation).

![Legendre's differntial equation](./images/LegDiffEqn.png)

The first plot renders the polynomial expansion of these solutions as a function of x, while the second plot renders them as functions of the trigonometric (sin(x), cos(x) & tan(x)) and hyperbolic (sinh(x), cosh(x) & tanh(x)) functions. The code is in `LegendrePoly.py`

![Legendre polynomials](./images/LegPoly.png)

## Brachistochrone Plots
The Brachistochrone curve solves a problem posed by Jean Bernoulli in 1696. The problem translates to:

"If two points A and B are given in a vertical plane, to assign a mobile particle Mthe path AMB along which, descending under
its own weight, it passes from the point A to B in the **briefest possible time**."<sup>1</sup>

The code in `brachistochrone.py` plots the brachistochrone curves from A(0,0) to several different B locations.

![Brachistochrone plots](./images/Brach.png)

<sup>1</sup> L.N.Hand & J.D. Finch, Analytical Mechanics

## Monte Carlo Integration
This is a numerical method based on the relationship between the mean value of a function over an interval [a,b], and the integal of the function over the same interval. For a sufficiently large N,

![Monte Carlo Integration Formula](./images/MonteCarloInt.png)

Using this to numerically integrate sin(x) using 1000 x-values:

![Monte Carlo in action](./images/MonteSS.png)

The code for generating this figure can be found in `MonteCarloInt.py`

## Dependencies
Requirements.txt will be uploaded soon.

