# Data Normalization & PCA Analysis

This project demonstrates several fundamental data preprocessing techniques and dimensionality-reduction methods using Python, NumPy, Pandas, and scikit-learn. The notebook walks through multiple normalization methods and applies Principal Component Analysis (PCA) to explore variance across features in a survey dataset.

## Tech Stack
- Python  
- NumPy  
- Pandas  
- Scikit-Learn  

## Features

### **Normalization Techniques**
- **Min–Max Normalization:**  
  Rescales values to a defined range (1 to 7) using `MinMaxScaler`.

- **Z-Score Standardization:**  
  Converts values to standard normal form (mean = 0, std = 1) using `StandardScaler`.

- **Decimal Scaling:**  
  Scales values by powers of 10 so all results fall within (–1, 1).

### **PCA (Principal Component Analysis)**
- Loads survey data with Pandas.  
- Extracts **12 principal components** using scikit-learn’s `PCA`.  
- Creates a DataFrame containing all transformed PCA components.  
- Outputs explained variance values for each component.
## How to Run

1. Download or clone the repository.
2. Make sure the CSV file (`survey_data.csv`) is in the same folder as the notebook.
   - The notebook automatically reads this file.
3. Open the notebook:
   `data_normalization.ipynb`
4. Run all cells in order.

If needed, install dependencies:

```bash
pip install numpy pandas scikit-learn
