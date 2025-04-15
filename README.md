# 🛢️ Machine Learning Application in Oil & Gas

This project applies machine learning to classify rock facies based on well log data. Correct facies prediction is critical for understanding subsurface geology and optimizing hydrocarbon recovery in the oil and gas industry.

## 📌 Project Overview

- **Course**: Machine Learning Analyst, NorQuest College  
- **Project Focus**: Reservoir facies classification  
- **Objective**: Predict rock facies using supervised learning  
- **Dataset**: Synthetic well log dataset  
- **Final Model**: Random Forest Classifier

## 🧪 Workflow Summary

- Data cleaning and preprocessing  
- Label encoding of categorical variables  
- Standardization using `StandardScaler`  
- Addressing class imbalance with **SMOTE**  
- Model training and validation  
- Test set prediction using data from a separate well (`SHANKLE`)

## 🔍 Features Used

| Feature       | Description                                  |
|---------------|----------------------------------------------|
| `GR`          | Gamma Ray log (indicates lithology)          |
| `ILD_log10`   | Log-transformed resistivity                  |
| `DeltaPHI`    | Difference in porosity readings              |
| `PHIND`       | Neutron porosity                             |
| `PE`          | Photoelectric effect                         |
| `NM_M`        | Normalized matrix indicator                  |
| `RELPOS`      | Relative stratigraphic position              |
| `Formation`   | Encoded geological formation name            |
| `Well Name`   | Encoded well name                            |

> All features were scaled and encoded appropriately before training.

## 🛠️ Machine Learning Models

| Model                        | Notes                              |
|-----------------------------|------------------------------------|
| ✅ Random Forest Classifier | Best performance (used in final)   |
| Gradient Boosting Classifier| Tried, but performed worse         |

## ✔️ Final Model: Random Forest Classifier

- Provided the best classification report across multiple facies
- Handled imbalanced data well with **SMOTE**
- Verified on both validation and separate test well data

## 📈 Visualizations

- Confusion matrix for performance visualization  
- Facies log plot per depth for visual interpretation


