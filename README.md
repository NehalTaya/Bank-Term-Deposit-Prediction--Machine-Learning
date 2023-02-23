## Bank-Term-Deposit-Prediction-Machine-Learning

**Background**

A European bank is conducting a marketing campaign and we want to determine which input variables 
affect the desired outcome of a client taking out a term deposit

**Bank Marketing dataset**

Input variables:

1. age (numeric).
2. job : type of job (categorical: "admin.", "unknown", "unemployed", "management", "housemaid",
"entrepreneur", "student", "blue-collar", "selfemployed", "retired", "technician", "services").
3. marital : marital status (categorical: "married", "divorced", "single"; note: "divorced" means 
divorced or widowed).
4 .education (categorical: "unknown", "primary", "secondary", "tertiary").
5. default: has credit in default? (binary: "yes", "no").
6. balance: average yearly balance, in euros (numeric) .
7. housing: has housing loan? (binary: "yes", "no").
8. loan: has personal loan? (binary: "yes", "no")
Related with the last contact of the current campaign:
9. contact: contact communication type (categorical: "unknown", "telephone", "cellular") .
10. day: last contact day of the month (numeric).
11. month: last contact month of year (categorical: "jan", "feb", "mar", …, "nov", "dec").
12. duration: last contact duration, in seconds (numeric).
Other attributes:
13. campaign: number of contacts performed during this campaign and for this client (numeric, 
includes last contact).
14. pdays: number of days that passed by after the client was last contacted from a previous 
campaign (numeric, -1 means client was not previously contacted).
15. previous: number of contacts performed before this campaign and for this client (numeric).
16. poutcome: outcome of the previous marketing campaign (categorical: "unknown", "other",
"failure", "success").

**Output variable (desired target):**

17. y - has the client subscribed a term deposit? (binary: "yes","no")

**Techniques used for Analysis**

1. Visualization: Generate charts to display relationships

a. Scatterplots

2. Statistical analysis: Generate statistical analysis that is appropriate

a. Descriptive statistics

b. Correlation matrix

c. VIF

d. Factor Analysis

a. Logit

b. Perceptron

c. SVM

d. Neural networks

e. K-nearest neighbor

f. Naïve Bayes

g. Decision trees

h. Random forest

**DESCRIPTIVE STATISTICS**

![image](https://user-images.githubusercontent.com/100436462/221043261-6bd1c777-95ab-460f-be94-92d2e367c821.png)

**CORRELATION MATRIX**

![image](https://user-images.githubusercontent.com/100436462/221043352-cffddb73-f234-47f9-a73f-bd179a022af8.png)

**VIF ANALYSIS**

![image](https://user-images.githubusercontent.com/100436462/221043486-45d95d2f-f864-45a0-b6a1-737dbf831176.png)

**VIF DESCRIPTION**

![image](https://user-images.githubusercontent.com/100436462/221043574-1d6e1d2c-29d2-48b3-bb6a-b0b6dc80813d.png)

**FACTOR ANALYSIS**

![image](https://user-images.githubusercontent.com/100436462/221043645-552a79d9-c2e6-46ab-aa8a-662957bfd3ff.png)

**LOGIT ANALYSIS**

![image](https://user-images.githubusercontent.com/100436462/221043748-200a103f-f396-41db-a5d6-f372e7f52fd1.png)

**SVM**

![image](https://user-images.githubusercontent.com/100436462/221043854-dc9a6d35-61e7-47d6-ae68-51a7249b284f.png)

![image](https://user-images.githubusercontent.com/100436462/221043901-0e674fbe-0d38-491b-bd14-32e8098b9449.png)

**NEURAL NETWORK**

![image](https://user-images.githubusercontent.com/100436462/221044064-73ad130b-6002-4254-a89f-a26c56eeeb29.png)

**KNN**

![image](https://user-images.githubusercontent.com/100436462/221044137-f1da0ede-44b0-4f8a-9f49-15861c5a7711.png)

![image](https://user-images.githubusercontent.com/100436462/221044185-a2310346-29ee-4ce9-b431-e2e141d29930.png)

**NAIVE BAYES**

![image](https://user-images.githubusercontent.com/100436462/221044339-ec2715e1-34ad-44fe-8f88-b9985ce923c9.png)

![image](https://user-images.githubusercontent.com/100436462/221044392-22c35b8d-dc4e-491f-a20b-8a46e0ffaa62.png)

**DECISION TREES**

![image](https://user-images.githubusercontent.com/100436462/221044487-23997854-6c69-4ab8-8de2-99f435858445.png)

**RANDOM FOREST**

![image](https://user-images.githubusercontent.com/100436462/221044636-97e214ac-f842-4bcd-8982-d39ba0572877.png)

**CONCLUSION**

![image](https://user-images.githubusercontent.com/100436462/221044777-ee16671d-3c4a-4c08-ad98-1453157e7827.png)

![image](https://user-images.githubusercontent.com/100436462/221044822-e83c41dc-e46e-4283-baf3-61bac7d22435.png)

**INSIGHTS FOR THE BANK**

![image](https://user-images.githubusercontent.com/100436462/221044896-98fe7e2f-7706-419b-9a35-b71f74be1999.png)

