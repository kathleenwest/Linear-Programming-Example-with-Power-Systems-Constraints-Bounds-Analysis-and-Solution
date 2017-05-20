% Week 2 Assignment
% Kathleen Williams
% Set Input data

% Objective Function
f = [20 25 30 0 18 26 32 0];

% Quantity
Aeq = [1 1 1 -1 0 0 0 0;
       0 0 0 0 1 1 1 -1;
       0 0 0 1 0 0 0 1];
beq = [0 0 100]';

lb = [0 0 0 15 0 0 0 10];
ub = [20 30 15 65 15 40 25 80];

A = [];
b = [];

% Call LP solver
[x,fval,exitflag,output,lambda]=linprog(f,A,b,Aeq,beq,lb,ub);

% Output results
%1. Optimal solution
x
%2. Objective function value
fval
%3. Shadow price for inequality constraints
lambda.ineqlin
%4. Reduced cost for lower bounds and upper bounds
lambda.lower
lambda.upper