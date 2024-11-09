# Iris Flower Classification

This project classifies iris flowers into species based on their physical attributes using a machine learning model.

## Project Overview
The Iris Flower Classification project uses the classic Iris dataset to classify iris flowers into three species: *Setosa*, *Versicolor*, and *Virginica*. The project explores the data, visualizes patterns, and applies the K-Nearest Neighbors (KNN) algorithm to predict species based on features like sepal length, sepal width, petal length, and petal width.

## Dataset
The dataset used is the [Iris Dataset](https://www.kaggle.com/datasets/uciml/iris), which contains 150 samples and 5 attributes (including species).

### Dataset Attributes
- **Id**: Sample identifier
- **SepalLengthCm**: Sepal length in cm
- **SepalWidthCm**: Sepal width in cm
- **PetalLengthCm**: Petal length in cm
- **PetalWidthCm**: Petal width in cm
- **Species**: Species of iris (*Setosa*, *Versicolor*, *Virginica*)

## Project Structure
- `Iris_Flower_Classification.ipynb`: Jupyter notebook containing the data exploration, visualization, and model training.
- `Iris.csv`: Dataset in CSV format.

## Libraries Used
- `pandas` for data handling and manipulation
- `matplotlib` and `seaborn` for data visualization
- `scikit-learn` for machine learning algorithms and model evaluation

## Exploratory Data Analysis (EDA)
The project includes:
- **Data Inspection**: Display of the first few rows and summary statistics.
- **Pair Plot**: Visualizes relationships between attributes and highlights class separations.
  
## Model Training and Evaluation
- **Algorithm**: K-Nearest Neighbors (KNN) with `n_neighbors=3`.
- **Training & Testing**: The data is split into training (70%) and testing (30%) sets.
- **Performance Metrics**:
  - **Accuracy**: Model accuracy on the test set.
  - **Classification Report**: Precision, recall, and F1-score for each species.

## Results
The model achieves satisfactory classification performance. Detailed metrics include accuracy and classification report, which can be viewed in the notebook.

## Usage
To run the notebook:
1. Install the required libraries.
2. Open `Iris_Flower_Classification.ipynb` in Jupyter Notebook.
3. Execute each cell to reproduce the results.

### Example Commands
If you need to install dependencies:
```bash
pip install pandas matplotlib seaborn scikit-learn
