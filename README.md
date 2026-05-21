**Project**: Iris Flower Classification

**Description**: Simple K-Nearest Neighbors classifier trained on the Iris dataset. The script `Iris_Flower_Classification.py` loads `Iris.csv`, trains a KNN model, prints accuracy and a classification report, and displays a confusion-matrix heatmap.

**Requirements**:
- **Python**: 3.8+
- **Dependencies**: see `requirements.txt` for packages and minimum versions.

**Setup**:
1. (Optional) Create and activate a virtual environment.

```bash
python3 -m venv .venv
source .venv/bin/activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

**Run**:

```bash
python3 Iris_Flower_Classification.py
```

**Files**:
- `Iris_Flower_Classification.py`: Main script that trains and evaluates the model.
- `Iris.csv`: Dataset (must be present in the same directory).
- `requirements.txt`: Python package dependencies.

**Notes**:
- The script displays a confusion matrix heatmap using `seaborn` and `matplotlib`.
- If you want to save the trained model, I can add code to persist it (e.g., with `joblib`).
