# Absenteeism-In-Employees

![absenteeism_h](https://user-images.githubusercontent.com/59203913/147377899-44ec27ac-0c43-4528-8d89-46cc2adc39c8.jpg)


* A Machine Learning model to predict if an employee is going to be excessively absent.

* The dataset contains the absenteeism records & the stated reasons of 700 employees over a period of 1 year. Our Machine Learning model has analyzed the relationship between   all the features to predict if an employee is going to be absent for more than 3 days in a month or not, which is considered as a benchmark for excessive absenteeism.

* **Features in the dataset are:**    <br />
 1.   ID                         <br />
 2.   Reason for Absence          <br />
 3.   Date                       <br />
 4.   Transportation Expense      
 5.   Distance to Work          
 6.   Age                       
 7.   Daily Work Load Average   
 8.   Body Mass Index           
 9.   Education                 
 10.  Children                  
 11.  Pets                      
 12.  Absenteeism Time in Days  <br />
 
 * **Algorithms used:**     <br />
 1. Logistic Regression  <br />
 2. Naive Bayes            <br />
 3. Support Vector Machines  <br />
 4. Decision Tree                <br />
 5. Decision Tree with Pre Pruning  <br />
 6. Decision Tree with post pruning <br />
 7. Random Forest               <br />
 8. K - Nearest Neighbors      <br />
 9. Ada Boost	           <br />
 10.	XG Boost           <br />
 
 * **Procedure:**        <br />
   1. Loading the dataset
 
   2. Preprocessing the data - Checking for missing values, outliers, checking if the dataset is balanced, removing unnecessary features, checking the presence of 
   multicollinearity, converting the data into a more understandable format, & standardization of the data.
   
   3. Splitting the dataset for training & testing.
   
   4. Implemented the above mentioned algorithms & compared their accuracy scores. Decision Tree has given the highest accuracy (82%).
   
   5. Implemented Stratified K-Fold Cross Validation with the above algorithms. Ada Boost & XG Boost have given the highest accuracy (75%).
   
   6. Performed Hyperparameter Tuning using Grid Search CV which has given the best results. Ada Boost & XG Boost have given the highest accuracy (95%).   

   7. Ada Boost with Grid Search CV has been selected as the optimal model for our problem. 
 
 
 
