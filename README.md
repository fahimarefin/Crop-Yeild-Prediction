
# Crop Yield Prediction

### Overview

This project tackles the problem of crop yield prediction using machine learning. Predicting agricultural yield is crucial for managing risks, planning production, and ensuring food security. Weather conditions, pesticide usage, and historical data are key factors influencing crop yield.

In this project, we predict the yield for the top 10 most consumed crops worldwide, including:

- **Cassava**
- **Maize**
- **Plantains**
- **Potatoes**
- **Rice (Paddy)**
- **Sorghum**
- **Soybeans**
- **Sweet Potatoes**
- **Wheat**
- **Yams**

This is a **regression problem**, and various machine learning models are explored to improve predictive accuracy.

### Project Structure

- **Data Preprocessing**: Handling of missing values, feature scaling, and encoding categorical data.
- **Model Training**: Models used include:
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - Support Vector Machine (SVM)
  - Decision Tree Regressor
  - Neural Networks using Keras
- **Evaluation Metrics**: Performance of the models is measured using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R-Squared (R²)

### Requirements

To run this project, the following Python libraries are required:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `keras`
- `tensorflow`

You can install the necessary dependencies by running:

```bash
pip install -r requirements.txt
```

### Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/crop-yield-prediction.git
```

2. Navigate to the project directory:

```bash
cd crop-yield-prediction
```

3. Run the notebook:

```bash
jupyter notebook Crop_Yield_Prediction.ipynb
```

### Dataset

The dataset used in this project contains information about the yield of the top 10 most consumed crops along with various influencing factors like weather and pesticide use. You can load the dataset within the notebook.

### Results

After training the models, the performance is evaluated, and the best model is selected based on the lowest error metrics and highest R² score.

### Future Work

- Expanding the dataset to include more crops and additional influencing factors.
- Incorporating deep learning models for improved accuracy.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
