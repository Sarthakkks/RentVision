# 🏠 RentVision

Predictive Analytics-Based House Rent Prediction System using IBM SPSS Modeler and CHAID Algorithm.

---

# 📌 Project Overview

RentVision is a machine learning and predictive analytics project developed using IBM SPSS Modeler and the CHAID decision tree algorithm.

The system performs:
- Data cleaning
- Data preprocessing
- Partitioning of dataset
- Predictive modeling
- User input-based rent prediction

The project analyzes various housing features such as:
- BHK
- Property Size
- Bathroom Count
- City
- Furnishing Status
- Area Type
- Tenant Preference

to predict house rent and identify important rental trends.

---

# 🎯 Objective

The main objectives of this project are:

- To analyze historical house rent data
- To clean and preprocess raw housing datasets
- To divide data into training and testing datasets
- To build a predictive CHAID model
- To predict rent based on user-provided inputs
- To identify factors affecting rental prices

---

# 🛠 Technologies Used

| Technology | Purpose |
|---|---|
| IBM SPSS Modeler | Predictive Analytics & Modeling |
| CHAID Algorithm | Decision Tree Prediction |
| Excel Dataset | Data Source |
| GitHub | Project Hosting |
| User Input Node | Manual Prediction Input |

---

# 📂 Dataset Information

The dataset contains the following fields:

| Attribute | Description |
|---|---|
| BHK | Number of Bedrooms |
| Rent | Target Variable |
| Size | Property Size (sq.ft.) |
| Bathroom | Number of Bathrooms |
| City | City Name |
| Area Type | Super Area / Carpet Area |
| Furnishing Status | Furnished / Semi-Furnished / Unfurnished |
| Tenant Preferred | Preferred Tenant Type |
| Point of Contact | Contact Type |

---

# 📊 Data Cleaning Process

The dataset was preprocessed using multiple SPSS Modeler nodes:

| Node | Purpose |
|---|---|
| Data Audit Node | Analyze data quality and missing values |
| Select Node | Remove invalid records |
| Fill Node | Handle missing numerical values |
| Type Node | Define input and target fields |
| Partition Node | Split dataset into training and testing data |

---

# ⚙️ Type Node Configuration

## Input Fields
- BHK
- Size
- Bathroom
- City
- Furnishing Status
- Area Type
- Tenant Preferred
- Point of Contact

## Target Field
- Rent

---

# 🔄 Workflow

```text
Excel Source
      ↓
Data Audit Node
      ↓
Select Node
      ↓
Fill Node
      ↓
Type Node
      ↓
Partition Node
      ↓
CHAID Node
      ↓
Golden Nugget Model
      ↓
User Input
      ↓
Prediction Table
```

---

# 🧠 Model Building Process

The dataset was divided into:
- 70% Training Data
- 30% Testing Data

using the Partition Node.

The CHAID algorithm was then applied to:
- Train the prediction model
- Identify decision rules
- Predict rent values

The generated golden nugget model was later connected with User Input Node to perform manual rent prediction.

---

# 📸 Workflow Screenshot

![Workflow](screenshots/full-stream-workflow.png)

---

# 📊 Data Audit Analysis

![Data Audit](screenshots/data-audit-analysis.png)

---

# 🧾 User Input Prediction

The User Input Node was used to manually provide:
- BHK
- Size
- Bathroom
- City
- Furnishing Status
- Point of Contact

The trained CHAID model predicted the expected house rent successfully.

---

# 📈 Predicted Output Example

| BHK | Size | Bathroom | City | Furnishing Status | Predicted Rent |
|---|---|---|---|---|---|
| 2 | 1200 | 2 | Mumbai | Furnished | ₹74,424 |

---

# 🔍 Key Findings

The CHAID model identified the following major factors affecting rent:

1. Property Size
2. City Location
3. Bathroom Count
4. Furnishing Status

The project successfully demonstrated:
- Data preprocessing
- Predictive analytics
- Machine learning workflow
- User-driven rent prediction

---

# ✅ Results

The predictive analytics model was successfully implemented using IBM SPSS Modeler.

The CHAID algorithm effectively analyzed housing features and generated accurate rent predictions.

The project also demonstrated:
- Data cleaning
- Partitioning
- User input prediction
- Decision tree modeling

---

# 🏁 Conclusion

This project demonstrates the practical implementation of predictive analytics in the real estate domain using IBM SPSS Modeler.

By applying the CHAID algorithm, the system successfully:
- Cleaned and processed housing data
- Built a predictive model
- Predicted rent using user inputs
- Identified major factors affecting rental prices

The project highlights how machine learning techniques can support real estate analytics and decision-making.

---

# 📁 Project Structure

```text
RentVision/
│
├── data/
│   └── house_rent_dataset.xlsx
│
├── screenshots/
│   ├── full-stream-workflow.png
│   ├── data-audit-analysis.png
│   ├── partition-node.png
│   ├── user-input-prediction.png
│   └── prediction-output.png
│
├── model/
│   └── rentvision_model.str
│
└── README.md
```

---

# 👨‍💻 Team Members

| Name | Enrollment Number | Specialization |
|---|---|---|
| Sarthak Bajpai | 24100BTCSFBI17552 | FSDB |
| Sarthak Choudhary | 24100BTCSDSI17485 | DS |
| Noumish Panadiwal | 24100BTCSDSI17479 | DS |
