 Predictive Analytics – Customer Response Prediction

📌 Project Overview

This project focuses on predicting customer responses to a marketing campaign using **IBM SPSS Modeler** and the **CHAID decision tree algorithm**. It uses customer and RFM (Recency, Frequency, Monetary) data to identify potential customers who are more likely to respond to a campaign.

The project demonstrates the process of importing data, selecting records, building a predictive model, interpreting predictions, and exporting the final customer contact list.

🎯 Objectives

* Import and explore customer data.
* Select relevant records for model training.
* Define input variables and the target variable.
* Build a CHAID predictive model.
* Predict customer responses and analyze confidence values.
* Export the final list of potential customers.

🛠️ Tools & Technologies

* IBM SPSS Modeler
* Predictive Analytics
* CHAID Decision Tree Algorithm
* Customer Data Analysis
* RFM Analysis

📂 Dataset

**Input file:** `ACME customer and rfm data.sav`

The reference dataset contains 30,000 records and 12 fields.

The model uses gender and RFM-related fields as input variables, while `response` is the target variable.

*Note: The dataset is not included in this repository unless uploaded separately.*

⚙️ Project Workflow

1. **Data Import:** Import the customer dataset into IBM SPSS Modeler.
2. **Data Exploration:** Examine the records and fields using a Table node.
3. **Data Selection:** Select the records required for model training.
4. **Field Configuration:** Assign input and target roles to the relevant fields.
5. **Model Building:** Train the CHAID decision tree model.
6. **Model Interpretation:** Examine the decision tree and generated predictions.
7. **Customer Scoring:** Apply the trained model to the remaining customers.
8. **Data Filtering:** Retain the customer ID, predicted response, and confidence fields.
9. **Export Results:** Export the final output to a file named `customers_to_contact`.

📊 Expected Output

The final output contains:

* `customer_id` – Customer identifier.
* Predicted response – The response category predicted by the model.
* Confidence – The model's confidence in its prediction.

These results can help identify potential customers for targeted marketing campaigns.

📚 Key Learnings

* Understanding predictive analytics workflows.
* Preparing and selecting data for modelling.
* Working with the CHAID decision tree algorithm.
* Interpreting predicted classes and confidence values.
* Applying data analytics to customer targeting.

🚀 How to Use

1. Install and open IBM SPSS Modeler.
2. Load the `ACME customer and rfm data.sav` dataset.
3. Recreate the workflow using the source, Select, Type, CHAID, Table, Filter, and Flat File nodes.
4. Run the model and inspect the predictions.
5. Export the final customer contact list.

 👩‍💻 Author

**Kirti Singh**
BCA – Data Science and Artificial Intelligence

📝 Note

This project was developed as part of academic coursework in Predictive Analytics. The documented workflow demonstrates customer response modelling using IBM SPSS Modeler.
