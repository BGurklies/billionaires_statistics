# Billionaires Statistics

## Table of Contents

- **[Getting Started](#getting_started)** <br>
- **[Introduction](#introduction)** <br>
- **[Objectives of the Analysis](#analysis_objectives)** <br>
- **[Data Source and Acknowledgments](#data_source)** <br>
- **[Results](#results)** <br>
- **[Sample Visualizations](#sample_visuals)** <br>
- **[License](#license)** <br> 

<a id="getting_started"></a>
## Getting Started 
To get started with this project, follow the steps below:

### Prerequisites

Ensure you have the following installed on your local machine:

- [Python](https://www.python.org/downloads/release/python-390/) (version 3.9 recommended)
- [Jupyter Notebook](https://jupyter.org/)

### Configuration

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/BGurklies/billionaires_statistics.git

2. Set up a virtual environment (optional but recommended):
   ```bash
   # Create a virtual environment
   python -m venv venv
   ```
   ```bash
   # Activate the virtual environment
   source venv/bin/activate   # For Linux/macOS
   ```
   ```bash
   .\venv\Scripts\activate    # For Windows
   ```
3. Install the required Python packages:
   ```bash
   pip install pandas matplotlib seaborn
   ```
4. Launch the Notebook:
   ``` bash
   jupyter notebook billionaires_statistics.ipynb
   ```
<a id="introduction"></a>
## Introduction 
This project analyzes the 2023 Billionaires Statistics dataset. It begins with data cleaning, including standardizing column names, handling missing values, removing duplicates, and addressing data quality issues. The cleaned data is then used for an exploratory data analysis (EDA) to examine patterns and relationships within the dataset.

<a id="analysis_objectives"></a>
## Objectives of the Analysis
The analysis explores demographic characteristics, the geographic distribution of billionaires, industry representation, and selected economic indicators. It also examines relationships between billionaire statistics and country-level economic metrics.

<a id="data_source"></a>
## Data Source and Acknowledgments

The dataset used in this project is the **2023 Billionaires Statistics Dataset**, available on [Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/billionaires-statistics-dataset).

### Acknowledgments

This project uses the following open-source libraries:

- **Pandas** for data cleaning and analysis
- **Matplotlib** and **Seaborn** for data visualization

<a id="results"></a>
## Results 
### Wealth Distribution
- The dataset comprises 2,384 billionaires with a mean net worth of approximately $4.77 billion, ranging from $1 billion to $211 billion.
- The top 5 industries dominating the billionaire landscape are Finance & Investments, Technology, Manufacturing, Fashion & Retail, and Healthcare, collectively representing around 56.38% of the total billionaires.

### Demographics
- Age Distribution: The age of billionaires ranges from 18 to 101 years, with a mean age of 64.99 years. The majority fall within the 56 to 74 age range.
- Gender Disparity: Male billionaires significantly outnumber female billionaires, constituting approximately 88.21% of the total billionaires.

### Self-Made Success
- The majority of billionaires are self-made, representing approximately 70.42% of the total billionaires.

### Top 5 Countries and Wealth Source Distribution
- The United States, China, India, Germany, and Russia are notable countries in terms of billionaire count.
  - In the United States, 537 billionaires are self-made, while 213 inherited their wealth.
  - China has 489 self-made billionaires and 15 with inherited wealth.
  - India, Germany, and Russia also showcase varying patterns of inherited and self-made billionaires.

### Correlation Analysis
- Net worth shows positive correlations with tertiary education enrollment and age, while it has negative correlations with country population and total tax rate.
- Age exhibits negative correlations with country population and total tax rate.
- Life expectancy in a country correlates positively with gross tertiary education enrollment and negatively with country population and total tax rate.
- Gross tertiary education enrollment shows positive correlations with GDP and negative correlations with country population and total tax rate.

<a id="sample_visuals"></a>
## Sample Visualizations

![Sample Visualization 1](media/univariate_analysis/Approximate_Distribution_of_Billionaires_Final_Worth_Worldwide_U.png)
![Sample Visualization 2](media/multivariate_analysis/Relative_Distribution_of_Billionaires_by_Industry_Age_and_Gender_Worldwide_M.png)
![Sample Visualization 3](media/multivariate_analysis/Billionaires_Correlations_between_Economic_and_Demographic_Indicators_Worldwide_M.png)

<a id="license"></a>
## License
This Project is [MIT](LICENSE) licensed.
