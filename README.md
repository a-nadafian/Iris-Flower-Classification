# The Tale of the Iris Flower: A Classification Adventure

This project is a data science exploration that tells a story through a Jupyter notebook. It uses the classic Iris dataset to build a K-Nearest Neighbors (KNN) model that can predict the species of an Iris flower based on its sepal and petal measurements.

## The Dataset

The Iris dataset is a famous multivariate dataset introduced by the British statistician and biologist Ronald Fisher. It contains 150 samples of Iris flowers, with 50 samples from each of three species:

-   Iris setosa
-   Iris versicolor
-   Iris virginica

Four features were measured from each sample:
-   Sepal length (in cm)
-   Sepal width (in cm)
-   Petal length (in cm)
-   Petal width (in cm)

## How to Run the Story

To follow this classification adventure, you'll need to set up your environment.

### 1. Clone the repository:
```bash
git clone <repository_url>
cd <repository_name>
```

### 2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\\Scripts\\activate`
```

### 3. Install the required libraries:
```bash
pip install -r requirements.txt
```

### 4. Open the Jupyter notebook:
```bash
jupyter notebook notebook/iris_classification_story.ipynb
```

## The Results

Our KNN model achieved a **perfect accuracy of 1.00 (100%)** on the test set, which means it correctly classified all the Iris flowers it had never seen before.

## Project Structure

The project is organized as follows:
```
├── data/
│   ├── raw/
│   │   └── IRIS.csv
│   └── processed/
├── notebook/
│   └── iris_classification_story.ipynb
├── LICENSE
└── README.md
```
-   **data/raw/**: Contains the original, untouched dataset.
-   **data/processed/**: Intended for cleaned or preprocessed data.
-   **notebook/**: Contains the main Jupyter notebook with the analysis.

This structure helps to keep the project organized and reproducible.
