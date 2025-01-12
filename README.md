Name:Aniket Sambhaji Date
Company:CODTECH IT SOLUTIONS PVT.LTD
Intern ID :CT12WEYM Domain:Data Science. 
Duration:December 2024-march 2025
Mentor: Muzammil ahamad


 overview of the object:-
 

Objective:
The objective of this project is to apply optimization techniques, specifically Linear Programming (LP), to a real-world business problem in manufacturing. We aim to maximize the company's profit while adhering to constraints such as limited raw materials and labor resources. The solution will be implemented using Python, specifically leveraging the PuLP library, to demonstrate the setup, solution, and insights derived from the optimization process.

Business Problem:
A company manufactures two products, Product A and Product B, with different profit margins and different requirements for raw materials and labor. The company has limited resources available for production, including a fixed amount of raw material and labor hours. The goal is to determine the optimal number of units of each product to manufacture in order to maximize the overall profit, while respecting the resource limitations.

Problem Statement:
Products:
Product A and Product B, each yielding a specific profit per unit.
Resources:
Raw materials and labor are limited.
Each product requires a certain amount of raw material and labor to produce.
Objective:
Maximize the total profit from producing these products while adhering to resource constraints.
Optimization Model:
Decision Variables:

𝑥
𝐴
x 
A
​
 : Number of units of Product A to produce.
𝑥
𝐵
x 
B
​
 : Number of units of Product B to produce.
Objective Function:

Maximize profit:
𝑍
=
20
𝑥
𝐴
+
30
𝑥
𝐵
Z=20x 
A
​
 +30x 
B
​
 
where:
20 is the profit per unit of Product A.
30 is the profit per unit of Product B.
Constraints:

Raw Material: Each unit of Product A uses 3 units of raw material, and each unit of Product B uses 4 units. The total raw material used cannot exceed 240 units:
3
𝑥
𝐴
+
4
𝑥
𝐵
≤
240
3x 
A
​
 +4x 
B
​
 ≤240
Labor: Each unit of Product A requires 2 hours of labor, and each unit of Product B requires 3 hours. The total labor hours cannot exceed 180 hours:
2
𝑥
𝐴
+
3
𝑥
𝐵
≤
180
2x 
A
​
 +3x 
B
​
 ≤180
Non-Negativity: The number of units for each product must be non-negative:
𝑥
𝐴
≥
0
,
𝑥
𝐵
≥
0
x 
A
​
 ≥0,x 
B
​
 ≥0
Solution Approach:
To solve this problem, we will:

Model the Problem: Define the linear programming model using Python and the PuLP library.
Define Variables and Constraints: Set up the decision variables, objective function, and constraints in the LP model.
Solve the Problem: Use a solver to compute the optimal solution.
Interpret Results: Extract the optimal number of units for each product and the maximum profit.
Python Libraries:
PuLP: A Python library that simplifies the creation and solving of linear programming problems. It will be used to define the LP model and solve the optimization problem.
Solver: PuLP provides access to various solvers like CBC, GLPK, and others to solve the LP model.
Steps to Implement:
Setup the LP Problem: Use PuLP to define the problem as a maximization problem (maximize profit).
Define Variables and Constraints: Specify decision variables (product quantities), constraints (resource limits), and the objective (maximize profit).
Solve the LP Model: Use the LP solver to find the optimal solution.
Extract and Present Results: Output the optimal production plan (number of units for each product) and the total profit.
Expected Output:
The solution will give:

The optimal number of units to produce for Product A and Product B.
The maximum possible profit the company can achieve.
A summary of resource utilization, ensuring that the constraints (raw material and labor hours) are satisfied.
Deliverables:
Problem Setup:
Detailed description of the business problem, mathematical formulation, and objectives.
Python Code:
Code implementation using the PuLP library to solve the linear programming problem.
Results:
Optimal production quantities for each product and the resulting total profit.
Analysis and Insights:
Interpretation of the solution, including insights into resource allocation, profitability, and potential business decisions.
Business Impact:
Efficiency: The optimization solution ensures that the company maximizes its profit by producing the right quantities of products within available resource limits.
Resource Management: It helps the company allocate resources (raw material and labor) effectively, ensuring that neither is wasted.
Data-Driven Decision Making: The model empowers the company to make informed decisions about production planning based on available resources.
