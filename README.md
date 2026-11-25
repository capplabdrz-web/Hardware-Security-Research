# Hardware-Security-Research

Machine Learning for Hardware Security Research

This work investigates an attack-agnostic, closed-loop machine learning framework for identifying security relevant anomalies on the Hardware Hacking (HaHa) educational platform.

Dataset 1: CAPPLab_HWSec_Dataset_01.xlsx

Dataset 1 was generated from Hardware Hacking (HaHa) board’s 10,000 standard operations and 500 Trojan-activated operations. The data acquisition and fusion stage contained 10,500 data points with 54 initial features. Preprocessing removed 32 administrative features (i.e., low-impact features for training machine learning models), including session identifiers and host-computer timestamps. Correlation-based feature selection removed five additional highly correlated features. The resulting dataset contained 10,500 data points with 16 features (excluding the label). Because the initial Trojan-activated sample was small, we used the synthetic minority over-sampling technique (SMOTE) to increase the Trojan class to 1,000 records, producing a balanced dataset of 11,000 records for model ingestion.

Dataset 2: CAPPLab_HWSec_Dataset_02 (coming up)

