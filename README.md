# Linear-Programming-Example-with-Power-Systems-Constraints-Bounds-Analysis-and-Solution
This is a simple Linear Programming LP Example with a generic power system, constraints, and determines optimal solution

Completion of LP Formulation

Variables:

	There are 8 variables in my generator model problem: x1, x2, x3, x4, x5, x6, x7, x8. They are defined as given below:
  
Variable	Definition

x1	G1 Bidding Quantity 20 MW Step

x2	G1 Bidding Quantity 30 MW Step

x3	G1 Bidding Quantity 15 MW Step

x4	G1 = x1 + x2 + x3 or total MW to be bid by G1

x5	G2 Bidding Quantity 18 MW Step

x6	G2 Bidding Quantity 26 MW Step 

x7	G2 Bidding Quantity 32 MW Step

x8	G2 = x5 + x6 + x7 or total MW to be bid by G2



Objective Function:

The objective of the problem is to minimize cost of combined bids of both generators.

The objective function is the sum of the unit price of the MW multiplied by the quantity to be bid added to the other bid ranges and their respective products.

Note: In the MATLAB portion of the model, the x4 and x8 variables are set equal to 0 since it is not in the problem definition to minimize these.

Constraints  

Optimal Solution

Accepted Quantity

The accepted quantity from each generator range is shown below and in the MATLAB results (attached):


Cost to Supply Load

The minimized cost under the optimal model  to supply 100 MW load is $2,330.00. The cost to supply load by generator G1 will be $1150 from G2, $1180.


