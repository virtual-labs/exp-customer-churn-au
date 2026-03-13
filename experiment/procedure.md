
Follow these steps to complete the Customer Churn Prediction simulation using Decision Tree and Random Forest:

1. **Step 1: Dataset Exploration**
   - Observe the **Dataset Overview** section which appears when the simulation starts.
   - Review the raw features such as Customer ID, Contract Type, Tenure, and Monthly Charges.
   - Understand the target variable (**Churn**) and identify the patterns in the data.

   <div align="center">
       <img src="images/step-1.png" alt="Dataset Exploration" width="80%">
   </div>

2. **Step 2: Data Preprocessing**
   - Navigate to the **Preprocessing** section.
   
   <div align="center">
       <img src="images/step-2.png" alt="Data Preprocessing 1" width="80%">
   </div>

   - **Handle Missing Values**: Select the strategy to clean the dataset.
   - **Label Encoding**: Convert categorical text data (like "Contract") into numerical values so the model can process it.
   - **Feature Standardization**: Scale numerical features to a uniform range for better model performance.
   - *Note: All preprocessing steps must be completed to move to the next stage.*

   <div align="center">
       <img src="images/step-2.1.png" alt="Data Preprocessing 2" width="80%">
   </div>

3. **Step 3: Dataset Splitting**
   
   <div align="center">
       <img src="images/step-3.png" alt="Dataset Splitting 1" width="80%">
   </div>

   - Use the slider to divide your data into **Training** and **Testing** sets.
   - A common ratio is **80:20** (80% for training the model and 20% for evaluating it).
   - Observe how the records are distributed between the two sets.

   <div align="center">
       <img src="images/step-3.1.png" alt="Dataset Splitting 2" width="80%">
   </div>

4. **Step 4: Decision Tree Configuration**
   - Navigate to the **Decision Tree Setup** section.
   
   <div align="center">
       <img src="images/step-4.png" alt="Decision Tree Configuration 1" width="80%">
   </div>

   - Configure the **Maximum Depth** and other split criteria like **Gini** or **Entropy**.
   - Read the tips to understand how depth affects model complexity.

   <div align="center">
       <img src="images/step-4.1.png" alt="Decision Tree Configuration 2" width="80%">
   </div>

5. **Step 5: Train Decision Tree**
   - Click **Execute Training** to build the model.
   
   <div align="center">
       <img src="images/step-5.png" alt="Train Decision Tree 1" width="80%">
   </div>

   - Visualize the **Decision Tree Structure** and see how the model makes decisions at each node.
   - Review the **Feature Importance** scores to see which factors (like "Contract" or "Internet Service") impact churn the most.

   <div align="center">
       <img src="images/step-5.1.png" alt="Train Decision Tree 2" width="80%">
   </div>

6. **Step 6: Random Forest Configuration**
   - Navigate to **Random Forest Parameters**.
   
   <div align="center">
       <img src="images/step-6.png" alt="Random Forest Configuration 1" width="80%">
   </div>

   - Set the **Number of Trees** (Forest Size) and **Maximum Depth per tree**.
   - Select a **Feature Strategy** (like SQRT) to ensure diversity among the individual trees.
   - Read the educational tips provided for each parameter.

   <div align="center">
       <img src="images/step-6.1.png" alt="Random Forest Configuration 2" width="80%">
   </div>

7. **Step 7: Train Random Forest**
   - Click **Execute Training** to grow the forest.
   
   <div align="center">
       <img src="images/step-7.png" alt="Train Random Forest 1" width="80%">
   </div>

   - Observe the **Tree Voting Simulation** as multiple trees independently predict outcomes for a specific test customer.
   - Check the **Prediction Confidence** and the probability breakdown between "Stay" and "Churn."

   <div align="center">
       <img src="images/step-7.1.png" alt="Train Random Forest 2" width="80%">
   </div>

8. **Step 8: Model Comparison & Evaluation**
   - Review the final **Performance Metrics** (Accuracy, Precision, Recall) for both models.
   - Compare the **Decision Tree** results against the **Random Forest** results.
   - Read the **Lab Conclusion** and the **Final Evaluation** summary to understand why one model outperformed the other based on ensemble stability and variance.

   <div align="center">
       <img src="images/step-8.png" alt="Model Comparison & Evaluation" width="80%">
   </div>
