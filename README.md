# AdvBiTrans: A Hybrid BiLSTM-Transformer with Adversarial Training for Botnet Detection in IIoT

This repository contains the complete implementation of our paper **"AdvBiTrans"**, a robust and accurate deep learning framework for botnet detection in Industrial Internet of Things (IIoT) environments.

---

## 📂 Project Structure
AdvBiTrans_experiment/ │ 
├── CIC-DDoS2019/ │ 
  ├── 1.Data_Preprocessing.ipynb │ 
  ├── 2.Feature_Selection_PCCS.ipynb │ 
  ├── 3.Mult_Model_xx.ipynb │ 
  └── Picture/ │ 
├── N-BaIoT/ │ 
  ├── 1.Data_Resaving.ipynb │ 
  ├── 2.Data_Preprocessing.ipynb │ 
  ├── 3.Feature_Selection_PCCS.ipynb │ 
  ├── 4.Mult_Model_xx.ipynb │ 
  └── Picture/ │
├── requirements.txt 
└── README.md

## 📋 Description

The project includes:

- 📊 **Data preprocessing** for CIC-DDoS2019 and N-BaIoT datasets
- 🧪 **Feature selection** using Pearson Correlation Coefficient Strategy (PCCS)
- 🤖 **Model training and evaluation** for AdvBiTrans, 1D-CNN, MLP, LightGBM, TabNet, and XGBoost
- 🔐 **Adversarial training** using PGD (Projected Gradient Descent)
- 📈 Performance metrics including Accuracy, F1, Inference Time, Memory Usage, FLOPs
Note: Mult_Model_xx is named according to the number of features to train the model, the model and parameters are consistent.
---

## 🛠️ Requirements

Run the following to install the required Python packages:

```bash
pip install -r requirements.txt


## 📊 Datasets
