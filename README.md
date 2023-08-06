# SVM-and-PCA
In-depth- Implementation Support Vector Machine and PCA

1.) Advance code file

**Support Vector Machines** are one of the best machine learning methods when getting the correct answer is a higher priorty than understanding why you get the correct answer.

They work really well with relatively small datasets and they do not require much optimization.

This code file will cover: -

**• Importing Data from a File**

  • Missing Datà 
  • identifying Missing Data 
  • Dealing with Missing Data

**• Downsampling Data**

**• Formatting the Data for Support Vector Machines**

**• Splitting data into Dependent and Independent Variables**

**• One-Hot-Encoding**

**• Centering and Scaling the Data**

**• Building a Preliminary Support Vector Machine**

**• Opimizing Parameters with Cross Validation**

**• Using Cross Validation to find the best Values for Gamma and Regularization**

**• Building, Evaluating, Drawing and Interpreting the Final Support Vector Machine**

**Datasource: -** https://archive.ics.uci.edu/dataset/350/default+of+credit+card+clients

**Dataset**
This research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. This study reviewed the literature and used the following 23 variables as explanatory variables:
X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.
X2: Gender (1 = male; 2 = female).
X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).
X4: Marital status (1 = married; 2 = single; 3 = others).
X5: Age (year).
X6 - X11: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows: X6 = the repayment status in September, 2005; X7 = the repayment status in August, 2005; . . .;X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
X12-X17: Amount of bill statement (NT dollar). X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005; . . .; X17 = amount of bill statement in April, 2005. 
X18-X23: Amount of previous payment (NT dollar). X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .;X23 = amount paid in April, 2005.
