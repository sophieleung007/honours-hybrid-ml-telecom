# honours-hybrid-ml-telecom
# Honours Project: Hybrid Autoencoder + Random Forest for Telecom Anomaly Detection

This project applies a hybrid ML model combining deep learning (autoencoder) and traditional ML (random forest) to detect anomalies in telecom network infrastructure using telemetry and physical network inventory data.

## 🔍 Key Features
- 📡 **Domain**: Broadband infrastructure validation
- 🤖 **Tech**: Autoencoder (Keras), Random Forest (Scikit-learn)
- 📈 **Output**: Reconstruction error, classification metrics, confusion matrix
- ☁️ **Cloud-native**: Originally developed in Google Colab

## 🧪 Workflow
1. Preprocess and merge PNI and telemetry data
2. Train deep autoencoder on normal data
3. Extract compressed features + reconstruction error
4. Feed to Random Forest for classification
5. Evaluate with accuracy, precision, recall, F1

## 🖼️ Sample Output
- `autoencoder_loss.png`
- `confusion_matrix.png`

## 🔬 Built With
- Python, Keras, Scikit-learn, Pandas, NumPy, Matplotlib
- Developed in Google Colab![31482 Autoencoder Train and Validation Loss](https://github.com/user-attachments/assets/e86948c2-531f-4007-92cb-6ef8cb433a01)
![31482 Confusion Matrix](https://github![31482 Classification Report](https://github.com/user-attachments/assets/21701860-a5c8-4f5c-9b0c-86dd02709d20)
.com/user-attachments/assets/cdc976a0-cfcf-4203-bce5-53a9f725f0b4)
