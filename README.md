
## My Projects
| Project Name                           | Description                          | Link                                                                          |
|----------------------------------------|--------------------------------------|-------------------------------------------------------------------------------|
| honours-hybrid-ml-telecom              | Telecom anomaly detection            | [Link](https://github.com/sophieleung007)                                     |
| 42028-Project-Autonomous_Driving       | Autonomous driving AI                | [Link](https://github.com/adriankumar/42028-Project-Autonomous_Driving)       |
| Facial_Recognition_Facenet             | Facial recognition with Facenet      | [Link](https://github.com/sophieleung007/Facial_Recognition_Facenet)          |
| Traffic-Sign-Recognition               | Traffic sign recognition project     | [Link](https://github.com/sophieleung007/Traffic-Sign-Recognition)            |



# Hi, I’m sophieleung007!

## honours-hybrid-ml-telecom
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






## 42028-Project-Autonomous_Driving
I’m also a collaborator on the [42028-Project-Autonomous_Driving](https://github.com/adriankumar/42028-Project-Autonomous_Driving) project. The main branch ([view here](https://github.com/adriankumar/42028-Project-Autonomous_Driving/tree/main)) contains our core work. My contributions include:

- Designed the model architecture and evaluation components, implementing the `combined_weighted_mse_loss` function for flexible error penalization and an exponential sequence weighting system prioritizing recent predictions.
- Developed visualization tools in `model_visualisation.py`, including `plot_adjacency_matrix` for neuron connectivity and `plot_wiring_graph` for neural diagrams.
- Created evaluation tools like `load_model` for efficient model loading, `process_video_inference` for the inference pipeline, and plotting functions for training curves, hidden states, and prediction comparisons.
- Enhanced the user interface with `SteeringWheel` and `DrivingControl` classes for intuitive visualizations and interactive controls.
- Documented the convolutional head architecture, evaluation methodology, feature extraction, and layer parameters.

Check out our [showcase video](https://www.youtube.com/watch?v=FuSemjOSa5k) create by Yan Liang to see the project in action!

I’m currently working on my contributions in the [yans_branch](https://github.com/adriankumar/42028-Project-Autonomous_Driving/tree/yans_branch).





## Facial_Recognition_Facenet
I’m working on [Facial_Recognition_Facenet](https://github.com/sophieleung007/Facial_Recognition_Facenet), a project using Facenet with RMSprop for facial recognition. My contributions include:

- Implemented training and inference pipelines in a Jupyter Notebook, converted to a Python script.
- Developed facial matching with bounding box visualization.

Check out the [script](https://github.com/sophieleung007/Facial_Recognition_Facenet/blob/main/Augmented_0_3_RMSprop_Training_Facenet_.py) for details!
