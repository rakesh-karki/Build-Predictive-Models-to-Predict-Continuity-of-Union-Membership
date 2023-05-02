# Build Predictive Models to Predict Continuity of Union Membership
In this project, I will use a hypothetical trade union (UDSU) data to build predictive models which will be used to predict whether a person will remain in the union or not.       
There are two tables: **"UDSU_train.csv"** and **"UDSU_toPredict.csv"**. The "UDSU_train.csv" table is to train, test and validate the models while "UDSU_toPredict.csv" has the informaion of potential member to be evaluated for continuity of union membership. 

**The tables contains following variables:**    
- **DS_ID:** member ID number  
- **gender:** member sex  
- **management:** if the member holds management position  
- **USACitizen:** if the member is a USA citizen  
- **Married:** if the member is married  
- **MonthsInUnion:** how many months the member has been a Union member  
- **ContinuingEd:** if the member is continuing education  
- **Feature A, B, C, D, E, F:** fictitious features  
- **Connectivity:** member's inernet connectivity  
- **DuesFrequency:** union fees pay frequency  
- **PaperlessBill:** if the member receives paperless bill  
- **PaymentMethod:** method of union due payment  
- **MonthlyDue:** monthly membership due   
- **TotalDues:** total outstanding due  
- **LeftUnion:** still a union member; or no longer a member (only available in train DataFrame)    

**Analysis Flow:**
- **Part A: Set Up Environment:**
- **Part B: Load the Data:**  
- **Part C: Explore the data:**  
- **Part D: Data Cleaning:**  
- **Part E: Plot the data:**  
- **Part F: Data Standardization / Normalization:**  
- **Part G: PCA Analysis:**  
- **Part H: Build Logistic Regression Model:**  
- **Part I: Build the Decision tree:**  
- **Part J: Build the Random forest model:**  
- **Part K: Build Support Vector Machine (SVM) model:**  
- **Part L: Build Neural networks:**  
- **Part M: Identify the best predictive model and predict the label:**
