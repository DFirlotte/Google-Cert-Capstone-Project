# Google capstone project: Providing data-driven suggestion for HR

Project Overview:
Goals in this project are to analyze the data collected by the HR department and to build a model that predicts whether or not an employee will leave the company.

Business Understanding:
It's crucial to understand the factors causing employees to leave the company in order to retain those who have received training, saving the company time and resources.

Data Understanding:
The data consist of information colleceted from employees that contains 15,000 entries and 10 variables. The features included information on if the employee left or not, the average number of hours worked per month, the number of project the employee was contributing to, the employees department and the employees satisfaction level. 
The box plot below shows if the employee left or stayed depending on their average monthly hours and number of projects they were invovled in.
![Model](https://github.com/DFirlotte/Portfolio/assets/93957112/17a6c6cf-6495-4607-91cc-d6a6c91853e8)

Modeling and Evaluation:
A random forest model comprising 500 decision trees was used to determine feature importance for an employee leaving. The below plot shows that employee satisfaction, average monthly hours, number of projects and years with the company are important factors on if an employee is deciding to leave. The overall model performed with 98% accuracy and 98% precision.
![Model](https://github.com/DFirlotte/Portfolio/assets/93957112/fb5e81b7-1a8a-4499-9b39-95bc33f6e18d)

Conclusion:
It seems that the number of projects and the average monthly hours play significant roles that contribute to low employee satisfaction and ultimately result in employees leaving.
