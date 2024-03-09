# Attrition Forecasting for Merger and Acquisition (Individual work)
[Code](https://github.com/SoumyaO/Attrition-forecasting-for-merger/blob/main/OgotiSoumyaSMM750.ipynb)

Data-driven planning for merger and acquisition. (INSEAD Case Study)

## Context:
During the process of merger and acquisition of a company, the headcount of employees in the company being merged may need to be reduced. To meet regulatory requirements and ensure compliance severance package agreements are given to employees. The aim is to objectively categorise employees into groups, without discrimination, and determine which groups to offer RCC to, but at the same time minimise cost of severance.

## Process:
This was done in two stages.

Stage 1:
- Identifying the factors that determine whether an employee accepts an RCC
- Modelling the probabilty of an employee accepting a severance, if offered; using Logistic Regression, CART, Random Forest, Gradient Boost. Employed PCA for feature selection.

Stage 2: 
- Using the above determined factors, formed groups of employeed objectively without discrimination (gender, age etc.)
- Using Linear Programming in Microsoft Excel Solver, determined which groups to offer severance to, considering the constraints involved such as avoiding mass exodus, stable empoyee proportion in each department, savings etc.
