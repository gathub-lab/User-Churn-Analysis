# User-Churn-Analysis
## 1. Introduction
### Introduction to the dataset
- Churn user refers to the cohort of users who have stopped using the services, If our churn rate is high, this could mean we are spending a lot of money on user acquisition but not getting the maximum ROI from the user.
- By identifying what the issues are, we can improve user retention — and subsequently revenue.
- This data set includes a dimension table containing information about users of a telecommunications network company, including fields of demographic information and information related to user churn.
### Data dictionary
![image](https://github.com/gathub-lab/User-Churn-Analysis/assets/116141004/18c5c34c-9926-4ddd-93d0-74e9a3fe8dcc)

### Request
- Create an overview dashboard for managers to see the churn situation of users and identify the user churn group, thereby offering solutions to improve this situation.
- Based on the generated analysis to provide insights and solutions.

## 2. Design Thinking Method
**Apply 5 steps of Design Thinking**
### Step 1 - Empathize
![image](https://github.com/gathub-lab/User-Churn-Analysis/assets/116141004/b826c4f9-144e-40ed-801d-5ad6c92d5ac1)

### Step 2 - Define
![image](https://github.com/gathub-lab/User-Churn-Analysis/assets/116141004/afb4d4f7-d89f-44a0-9b10-f177ddd757c0)

### Step 3 - Ideate
![image](https://github.com/gathub-lab/User-Churn-Analysis/assets/116141004/9b0dbf74-4db6-401d-b689-b536080f9b8f)

### Step 4 - Prototype
![image](https://github.com/gathub-lab/User-Churn-Analysis/assets/116141004/beb172dc-8ca0-450a-8dc9-4eeae5ebd765)

### Step 5 - Review
![image](https://github.com/gathub-lab/User-Churn-Analysis/assets/116141004/63a59e22-ae55-4e89-b2eb-94a6b6a5d260)

## 3. Visualization
**Page 1 - Customer Overview**
![image](https://github.com/gathub-lab/User-Churn-Analysis/assets/116141004/8447b6be-0b8e-434c-a482-ccde4c9135fa)

**Page 2 - Customer Dashboard**
![image](https://github.com/gathub-lab/User-Churn-Analysis/assets/116141004/c9069d53-4053-4a65-9777-0f7b9c4e0b87)

**Page 3 - Churn Reason**
![image](https://github.com/gathub-lab/User-Churn-Analysis/assets/116141004/3ebb719f-aec5-4432-b96e-f72fe3bf9f74)

## 4. Insight
- Customer Overview will give a detailed view of the users of this telecommunications network with a total of 6678 users
- In the first line metric cards, the most notable is the CSC index (total number of calls to the call center / total number of customers) 92% in the Customer group and 239% in the Churner group, which shows that the customers who left are the customers who called the call center the most.
- The UDP measure of the Churner group is very high with 80.35%, indicating the problem with the Data Unlimited package.
- 95.5% of customers leaving are new customers, they have used less than 10 months
- Customers using month-to-month contracts have the highest churn rate, 87.92%
- Customers using the Direct Debit payment method had the highest churn rate, 71.10%

**The 3 reasons customers churn the most are:**
+ Competitor make better offers - 30.86%
+ Competitor had better devices - 30.24%
+ Attitude of support person - 20.67%

## 5. Recommendations
1. Improve customer service attitude and call quality (training/replacing personnel/increasing number of personnel, etc.), reducing CSC measure of Churner group.
2. Encourage customers to use Group because Group users have a low abandonment rate of 5.51% (promotion for new customers to buy in groups, free group calls and messages, etc.)
3. Encourage customers to use long-term contracts (Promotion for customers signing 1-year and 2-year contracts, etc.)
4. Encourage customers to use Credit Card and Paper Check payment methods (Partnership with banks, promotions when customers pay cards, etc.)
5. AVG of Monthly Download is less than 10GB/month, in Churner user group using 14.2% higher than average, indicating that churn customers need to improve data package (create data package under 10 GB, loyalty point feature used to exchange data, etc.)
6. Improve Offer and Device to increase competitiveness.
