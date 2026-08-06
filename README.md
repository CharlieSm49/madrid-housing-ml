# CBF Python and Machine Learning Project
## Predicting Average House Prices in Madrid Neighbourhoods Using Socioeconomic Indicators

This project aims to develop and evaluate a machine learning model that predicts average property prices across Madrid neighbourhoods using socioeconomic indicators.

## Description

The project combines two official datasets published by Madrid City Council: the Panel of Socioeconomic Indicators of Districts and Neighbourhoods of Madrid and Average Declared Housing Price (€ per m²) by District and Neighbourhood.

The project provides an initial exploration of the relationship between socioeconomic characteristics and housing prices across Madrid neighbourhoods. While these relationships do not establish causation, they can help identify socioeconomic factors associated with differences in housing prices and neighbourhood conditions.

The model focuses on 2025 data from 130 residential neighbourhoods, using 15 socioeconomic features to predict average housing price per square metre. A Linear Regression model was trained using an 80:20 train-test split, followed by model evaluation and identification of potential improvements. With the addition of historical data, future versions could explore how changes in socioeconomic conditions relate to housing prices over time.

### Selected Features

- Population density (inhabitants per hectare)
- Population aged 25+ with higher education or technical qualifications (%)
- Registered housing as a percentage of total registered premises
- Average disposable income per person
- Average annual net household income
- Registered unemployment rate
- Population growth rate (%)
- Average household size
- Average age
- Ageing index (% aged 65+)
- Social welfare and equality vulnerability index
- Economic and employment vulnerability index
- Education and culture vulnerability index
- Urban environment and mobility vulnerability index
- Health vulnerability index

## Tools and Libraries

This project used Python as the programming language. Key tools and libraries included:

### Tools
- Jupyter Notebook: Used to explore and clean the datasets, perform analysis, and develop and evaluate the machine learning model.
- Microsoft Excel: Used to support the initial analysis and selection of relevant socioeconomic indicators.

### Python Libraries
- Pandas: Data manipulation, cleaning and analysis.
- NumPy: Numerical operations.
- Matplotlib: Data visualisation.
- Seaborn: Statistical data visualisation.
- Scikit-learn: Data preprocessing, model development and evaluation.

## Getting Started

### Prerequisites

- Python
- pip
- Jupyter Notebook

### Installation

Install the required Python packages:

`pip install -r requirements.txt`

### Project Structure

- `data/` – original and cleaned datasets
- `notebooks/` – data exploration, preparation and modelling notebooks
- `outputs/` – files produced during analysis
- `requirements.txt` – required Python packages
- `report` - accompanying project report

### Executing the Program

Run the notebooks in numerical order from the `notebooks/` directory.

## Author

Charlie Smith – @CharlieSm49

## Version History

0.1 – Initial Release

## Acknowledgments

- A special thank you to Obe (CBF Teaching Instructor) for their teaching, guidance and coding examples throughout the course
- Coding Black Females
- Madrid City Council – source datasets
- Google Translate
- W3Schools
- GeeksforGeeks
- CodeSignal