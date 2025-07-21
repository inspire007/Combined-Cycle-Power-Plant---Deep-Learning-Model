# **Power Output Prediction Using ANN** ⚡️

This repository contains an Artificial Neural Network (ANN) model that predicts the power output of a combined cycle power plant based on environmental and operational data. The model achieves an **R² score of 93.56%**, indicating its strong performance.

## **Overview** 🌟

This project uses an Artificial Neural Network (ANN) to predict the **net hourly electrical energy output** (MW) of a combined cycle power plant. By using key environmental and operational features, the model provides accurate power output predictions. The model achieves an **R² score of 93.56%** on the test data.

## **Dataset** 📊

The dataset used is from the **UCI Machine Learning Repository** and includes 9568 rows of data with the following features:

- **Temperature** (°C)
- **Exhaust Vacuum** (mm Hg)
- **Ambient Pressure** (bar)
- **Relative Humidity** (%)

The target variable is the **Energy Output** (MW).

The dataset is publicly available at: [UCI Repository - Combined Cycle Power Plant Dataset](https://archive.ics.uci.edu/dataset/294/combined+cycle+power+plant).

## **Model Architecture** 🧠

The ANN model consists of:

- **Input Layer**: 4 nodes (one for each feature)
- **Hidden Layers**: 2 layers with ReLU activation functions
- **Output Layer**: 1 node with a linear activation function for continuous output

The model is designed to predict the energy output based on the input features.

## **Results** 📈

- **MSE Score**: 17.95%
- The model demonstrates strong accuracy in predicting the power output of the plant using environmental parameters.

## **Future Improvements** 🚀

- Implement **Hyperparameter tuning** to further optimize the model.
- Experiment with **deeper architectures** or other machine learning models (e.g., Random Forest, XGBoost).
- Use **ensemble methods** for even better prediction accuracy.

## **License** 📝

This project is licensed under the MIT License.
