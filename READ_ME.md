\# Machine Learning Midterm Project



This project compares classification and K-Means clustering on the Breast Cancer Wisconsin and Wine datasets. Each dataset is analysed separately using three train/validation seeds, a fixed test set, unscaled features and StandardScaler-transformed features.



\## Datasets



Both datasets are loaded directly from scikit-learn:



\- Breast Cancer Wisconsin: `load\_breast\_cancer()`

\- Wine Classification: `load\_wine()`



No separate dataset download is required.



\## Requirements



\- Python 3.12.10

\- Package versions: see `requirements.txt`



\## Installation



From the project folder, create a virtual environment and install the dependencies:



```powershell

python -m venv .venv

.\\.venv\\Scripts\\python.exe -m pip install -r requirements.txt

