# Heart Disease Prediction Project

This project demonstrates a complete machine learning workflow for predicting heart disease using a real-world dataset. The notebook covers data cleaning, outlier removal, feature encoding, scaling, model selection, hyperparameter tuning with GridSearchCV, and dimensionality reduction with PCA.

## Features

- Loads and explores the heart disease dataset
- Removes outliers using Z-score
- Encodes categorical and ordinal features appropriately
- Scales features with MinMaxScaler
- Compares multiple models: SVM, Random Forest, Logistic Regression, Multinomial Naive Bayes
- Uses GridSearchCV for hyperparameter tuning
- Applies PCA for dimensionality reduction

## Requirements

- Python 3.x
- pandas
- scikit-learn
- scipy
- numpy

Install dependencies with:
```bash
pip install pandas scikit-learn scipy numpy
```

## Usage

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/heart-disease-prediction.git
    cd heart-disease-prediction
    ```
2. Make sure `heart.csv` is in the project directory.
3. Open `Heart_project.ipynb` in Jupyter Notebook or VS Code.
4. Run the notebook cells to follow the workflow and see results.

## Project Structure

- `Heart_project.ipynb` — Main notebook with code and explanations
- `heart.csv` — Dataset file (not included; obtain from a public source if needed)

## License

This project is licensed under the MIT License.
