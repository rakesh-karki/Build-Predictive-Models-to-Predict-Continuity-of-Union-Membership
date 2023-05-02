# Build Predictive Models to Predict Continuity of Union Membership
 In this project, We will use a hypothetical trade union (UDSU) data to build various models and which will be used to predict whether a person will remain in the union.       
We have two tables: **"UDSU_train.csv"** and **"UDSU_toPredict.csv"**. We will use the "UDSU_train.csv" table to train and validate the models. We will then select the best performing model and use it to predict the target variable (**"LeftUnion"** > **yes** or **no**: whether a person will remain in the union) based on the member data we have captured in 'UDSU_toPredict.csv".   

**The DataFrame contains following variables:**    
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
