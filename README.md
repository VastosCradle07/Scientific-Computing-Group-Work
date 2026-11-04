BIT 2118 Scientific Computing: Group Work Submission
Tasks 2 to 20, each with the original program, a changed-parameter run, a modified real-world case, the captured outputs and graphs, and a written explanation.
Folder layout
Folder	Contents
`code/`	The 19 original programs (Task 2 to Task 20), cleaned and comment-free
`changed\_parameter/`	The same programs with one input or parameter changed (Instruction C)
`modified\_case/`	New programs solving a different but related real-world case (Instruction E)
`outputs/`	Text output of every program and every graph as a PNG
`docs/`	One markdown file per task: inputs, operation, change, interpretation, new case (Instructions B, C, D, E)
`PRESENTATION\_SUMMARY.txt`	Short plain-text summary for the presentation
Task index
Task	Topic and documentation	Modified real-world case
2	NumPy Arrays and Numerical Computation	IoT water-tank level monitoring
3	Mathematical Functions and Vectorization	Currency conversion plus VAT on two million transactions
4	Floating-Point Arithmetic and Numerical Errors	Banking: adding one million small deposits
5	Matrix Algebra and Matrix Operations	Drone waypoint path transformation (homogeneous coordinates)
6	Solution of Systems of Linear Equations	Traffic flow through three roads
7	Gaussian Elimination and LU Decomposition	Electrical circuit mesh currents with repeated voltage settings
8	Iterative Methods for Linear Systems	Steady-state heat along a 7-point rod
9	Eigenvalues and Eigenvectors	PageRank of a five-page website
10	Root Finding: Bisection and Fixed-Point Methods	Break-even analysis of a product with congestion cost
11	Root Finding: Newton-Raphson and Secant Methods	Finding the interest rate of a loan
12	Polynomial and Nonlinear Equation Solving	Drone path against a no-fly zone, and a projectile landing time
13	Interpolation	Filling missing sensor readings
14	Curve Fitting and Approximation	Mobile app user growth: exponential versus linear model
15	Numerical Differentiation	Acceleration from velocity data, plus step-size study
16	Numerical Integration	Total river water volume from flow measurements
17	Ordinary Differential Equations: Euler Method	Logistic population growth with different Euler step sizes
18	Numerical Solution of ODEs Using SciPy	SIR epidemic model
19	Numerical Optimization	Production planning: maximise profit
20	Random Numbers and Monte Carlo Methods	Project completion risk, plus estimating pi
How to run
```bash
pip install -r requirements.txt
cd code
python Task\_02\_numpy\_arrays.py
```
Run the programs from inside their own folder (`code`, `changed\_parameter` or `modified\_case`). Programs that draw graphs save a PNG into `outputs/` and then open the plot window.
Python 3.10 or newer and NumPy 2.0 or newer are needed, because `np.trapezoid` was added in NumPy 2.0.
Submission notes
The discussion is done as a group, but the GitHub repository is individual: create your own repository and upload this folder to it.
Upload your repository link and documentation through VLMS.
