# Education Predicting Internship Selection

A data analysis and machine learning project that explores whether educational and personal factors can help predict internship selection outcomes.

## Project Overview

This project uses the internship selection dataset to:

- Explore the structure and quality of the data
- Identify patterns in student education and background factors
- Prepare data for machine learning
- Train and evaluate classification models
- Analyze the factors associated with internship selection

The complete analysis is provided in the Jupyter notebook included in this repository.

## Repository Contents

- `Internship_Selection_Dataset.csv` - Dataset used for exploration, preprocessing, and modeling.
- `PADV activity (2).ipynb` - Jupyter notebook containing the data analysis and prediction workflow.
- `README.md` - Project documentation.

## Getting Started

### Requirements

- Python 3.9 or later
- Jupyter Notebook or JupyterLab
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

### Installation

Install the required Python packages with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/arjun3337/Education-Predicting-Internship-Selection.git
   cd Education-Predicting-Internship-Selection
   ```

2. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Open `PADV activity (2).ipynb` and run the cells from top to bottom.

Keep `Internship_Selection_Dataset.csv` in the same folder as the notebook so the data loads correctly.

## Workflow

The notebook follows a typical machine learning workflow:

1. Load and inspect the dataset
2. Clean and prepare the data
3. Perform exploratory data analysis
4. Select and transform features
5. Train prediction models
6. Evaluate model performance
7. Interpret the results

## Notes

Model results depend on the preprocessing choices, feature selection, random state, and train-test split used in the notebook. Predictions should be treated as analytical estimates rather than guaranteed internship outcomes.

## Author

Arjun P

## License

This project is provided for educational and research purposes.
