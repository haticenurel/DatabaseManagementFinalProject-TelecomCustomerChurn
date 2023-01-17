# DatabaseManagementFinalProject-TelecomCustomerChurn
 telecom customer churn

This project uses a Kaggle dataset and MySQL to create and populate a database.

## Requirements

- MySQL
- Python 3.x
- Python libraries: csv
## Getting Started

1. Download the Kaggle dataset from [https://www.kaggle.com/datasets/shilongzhuang/telecom-customer-churn-by-maven-analytics].

2. Run the script `parsing_data.py` and `parsing_data2.py` to parse the dataset. This script will create a preprocessed version of the dataset in the form of a CSV file.

3. Create a new MySQL database and run the script `adding_population_to_city.sql` to create the necessary tables for city table.

4. Run the script `finding_dataset.py` to load the parsed dataset into the MySQL database.

5. Run the script `stored prosedures.sql` , `view.sql` and `result.sql`  to query the data and see the result.

6. You can see the entity of dataset with `newEntity.mwb`
## Note

- Make sure to update the database connection settings in the python scripts before running them.
- If you have any problem with the dataset, please refer to the kaggle website for the dataset
