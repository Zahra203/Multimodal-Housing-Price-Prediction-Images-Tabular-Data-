#  Multimodal Housing Price Prediction (Images + Tabular Data)

This project predicts housing prices by combining **structured tabular data** and **house images** in a single **multimodal machine learning** model.

## Objective
Predict housing prices using **both**:
-  **House images** (processed via CNN)
-  **Structured tabular features** (processed via MLP)

##  Features
- **CNN (Convolutional Neural Network)** → Extracts image features.
- **MLP (Multi-Layer Perceptron)** → Processes tabular features.
- **Feature Fusion** → Concatenates image + tabular embeddings.
- **Regression Head** → Predicts price.
- **Evaluation Metrics** → MAE (Mean Absolute Error) and RMSE (Root Mean Squared Error).

##  Model Architecture
- [Image] → CNN → Image Embedding
- [Tabular Features] → MLP → Tabular Embedding
- Image Embedding + Tabular Embedding → Fusion Layer → Regression Output
  
  ##  Evaluation
- MAE — Mean Absolute Error
- RMSE — Root Mean Squared Error

  ## File Structure
  - House Prediction(tabular+Images).ipynb
  - House Price Prediction Dataset.csv
  - labels.csv (which contain image dataset)

