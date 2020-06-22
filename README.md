## Data Preprocessing Project

E-MAIL: dannygarcia193@gmail.com         
Data completed: January, 2020

**Project Name:** Analyzing Borrower’s Risk of Defaulting

**Project description:** Hello this is my submission for the Data Preprocessing Project from the Data Analytics Program by Yandex. 
The goal of this "hypothetical" project is to prepare a report for a bank’s loan division. 
Of special consideration, customer’s marital status and number of children were taken into account to determine whether 
a customer will default on a loan. 

This "HYPOTHETICAL" report was considered when building a credit scoring of a potential customer. 

In this project I put to work my analytical thinking as well as my coding, and preprocessing skills.

### 1. Summary of Analysis

Business Questions: 
1. Is there a relation between having kids and repaying a loan on time? 
    - For the first graph (see figure 1), with the ratio of percentage being roughly a percentage and a half away from each other, it is reasonable to conclude that there is no concrete relationship between having kids and repaying loan in time.
2. Is there a relation between marital status and repaying a loan on time? 
    - In the next graph (see figure 2), we can see that among all the marital status variables, surprisingly, those with a widower status are more likely to not be in debt. Individuals with a divorced and married status are also more likely to pay their loans on time. Those under a civil partnership and unmarried marital status, however, seem to have a higher likelihood of not paying of their loan in time. Thus its reasonable to assume that marital status does share a relationship with the timeliness of loan repayment.
3. Is there a relation between income level and repaying a loan on time?  
    - Following that, the bar graph (see figure 3), it's surprising to observe that for the most part, the debt ratios for all but the middle income class category remain relatively equal. Based on these mean ratios, it's safe to assume that a weak relationships exist between the timeliness of loan repayment and income class with people in the middle income class paying off their debt at a quicker rate.
4. How do different loan purposes affect on-time repayment of the loan?
    - Lastly, from the result of the last bar graph (see figure 4), the real estate mean ratio value seems to be the most different from the others but not on a large scale. We can only conclude however that a potential positive relationship may exist between people who take out a loan for real estate purposes and their timeliness of repayment.


### 2. Conclusion
> After a variety of data preprocessing steps, we were able to condense and transform the four main columns of interest (income class, purpose, children, and marital status) into the appropriate types of variables to be able to answer the business questions. From our analysis, we were able to point out marital status, income class, and loan purpose as having an existing relationship between the timeliness of loan repayment.

> Individuals taking out loan for real estate purposes on average tend to pay their loan in a timely manner in comparison to those taking out their loans for wedding, car purchasing, and education reasons. In addition, widowers are more likely than any other type of marital status group (married, unmarried, divorced, civil partnership) to pay back their loans on time. Moreover, individuals who identified as being unmarried or in a civil partnership had a higher likelihood of repaying their loan on time in comparison to the other marital status. Lastly, individuals in the middle income class payed off their loans at a higher rate in comparison to the other income classes (high, highest, and low).

Special consideration should be given to the aforementioned variables.

### 3. Figures

#### Figure 1. Child (0 being no debt, 1 being unpaid loan)
<img src="images/child.png?raw=true" width="75%" height="50%"/>

#### Figure 2. Marital Status  (0 being no debt, 1 being unpaid loan)
<img src="images/marital_status.png?raw=true" width="75%" height="50%"/>

#### Figure 3. Income Class (no debt, 1 being unpaid loan)
<img src="images/income_class.png?raw=true" width="75%" height="50%"/>

#### Figure 4. Loan Purpose  (0 being no debt, 1 being unpaid loan)
<img src="images/loan_purpose.png?raw=true" width="75%" height="50%"/>



