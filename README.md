
# Analysis of House Listing Dataset

This repository contains a Jupyter Notebook that performs statistical analysis on a House Listing Dataset. The analysis includes inference on features like property type, dimensions, age, locality, etc.

## Dataset

The input CSV file named `train.csv` used for the analysis includes the columns as described in `data_description.txt`.

## Contents

- **`main.ipynb`**: The Jupyter Notebook performing data preprocessing, analysis, and visualization.
- **Input CSV Files** i.e. `train.csv`: Dataset file containing the information used for analysis.

## Features of the Notebook

1. **Exploratory Data Analysis (EDA)**:
   - Descriptive statistics of the dataset.
   - Visualization of trends and correlations.
2. **Statistical Inference**:
   - Hypothesis testing.
   - Analysis of property-related features.
3. **Recommendations**:
   - Suggestions based on findings.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/samar-080301/house_price_EDA
   ```
2. Navigate to the repository folder:
   ```bash
   cd house_price_EDA
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook main.ipynb
   ```
5. Run the notebook cells sequentially.

## Dependencies

Ensure the following Python libraries are installed:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`

You can install them using:
```bash
pip install pandas numpy matplotlib seaborn scipy
```

## Outputs

The notebook generates:
- Summary statistics of the dataset.
- Graphical visualizations (e.g., bar charts, scatter plots).
- Insights into property features and trends.

## Author

**Samar Pratap Singh**  
MBA Student | Data Analysis Enthusiast  

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
