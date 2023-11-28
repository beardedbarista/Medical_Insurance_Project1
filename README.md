# Medical_Insurance_Project1
This is a repository for the Codecadamy Medical Insurance Portfolio Project 1 (Data Science).
# Medical Insurance Cost Analysis
This project analyzes a dataset containing medical insurance cost information to extract insights and discover the impacts of various attributes on the insurance charges.
## Data Description
The dataset used (`insurance.csv`) includes the following columns:
- `age`: The age of the patient.
- `sex`: The gender of the patient.
- `bmi`: The Body Mass Index of the patient.
- `children`: The number of children/dependents covered by the insurance.
- `smoker`: The smoking status of the patient.
- `region`: The residential region of the patient.
- `charges`: Individual medical costs billed by health insurance.
## Purpose
The main objectives of this project are to:
- Load and review the medical insurance data.
- Calculate the average insurance cost and examine how different factors such as smoking status and region affect the insurance charges.
- Determine the number of patients with and without children.
- Calculate the average cost per child for the patients covered.
## Project Files
- `Medical Insurance Project 1.py`: The main Python script containing all functions and analyses performed on the insurance dataset.
## Functions Implemented
- `load_insurance_data()`: Loads the insurance data from a CSV file and stores each column in a separate list.
- `calculate_average_insurance_charges()`: Calculates the average of the insurance charges.
- `calculate_smoker_effect()`: Computes the cost difference in insurance charges between smokers and non-smokers.
- `calculate_with_child_count()`: Determines the count of patients with and without children.
- `region_count()`: Calculates the number of patients living in each region.
- `calculate_cost_per_child()`: Works out the average insurance cost incurred per child.
## Results
The analysis provides valuable insights, such as the impact of smoking on insurance costs, the average cost per child, and a breakdown of patients by region and parental status. The results from each function are printed and can be used to inform insurance policy adjustments and health awareness programs.
## How to Run
To execute this project, you should have Python installed on your machine along with the necessary libraries (`csv`, `pandas`).
1. Clone this repository or download the `Medical Insurance Project 1.py` file and the `insurance.csv` dataset.
2. Run `Medical Insurance Project 1.py` using a Python interpreter.
3. View the printed analysis results on your console.
## Libraries Used
- `csv`: For reading the CSV file and parsing its contents.
- `pandas`: For loading, manipulating, and analyzing the data.
## Conclusion
By understanding the factors that affect medical insurance costs, we can better prepare for future health expenses and adjust insurance policies to reflect the risks associated with different patient profiles.
