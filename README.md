![31482 Classification Report](https://github.com/user-attachments/assets/9c286839-8724-4b35-8c43-63d0204e2adc)
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
- Developed in Google Colab!


![31482 Autoencoder Train and Validation Loss](https://github.com/user-attachments/assets/18b6fc9c-a8eb-478d-8ce0-4da681dac327)
![31482 Confusion Matrix](https://github.com/user-attachments/assets/96571a10-8758-4718-9ce8-01ec225ed25b)
![31482 Classification Report](https://github.com/user-attachments/assets/12d47727-48ae-45b7-91c5-9b1e03053d04)

