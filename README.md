## L2T09 - Data Analysis - Data Cleaning

### Store Income Data Cleaning Task

In this task, data cleaning is focused upon. The "country" column is cleaned and the "date_measured" column is parsed  in the `store_income_data_task.csv` file. 

## Instructions

1. **Installations**
    - Ensure you have Python installed on your system. You can download it from the [Python website](https://www.python.org/downloads/).
    - Install Jupyter Notebook to run the provided notebook. You can install it using pip:
```
        pip install notebook
```
2. **Running the Notebook**
    - Clone this repository to your local machine using:
        ```
        git clone https://github.com/vswapna3202/L2T09.git
        ```
    - Navigate to the task's folder:
        ```
        cd L2T09 or cd <your_task_folder>
        ```
    - Start Jupyter Notebook:
        ```
        jupyter notebook
        ```
    - Open the Jupyter notebook named `store_income_task.ipynb`.

3. **Dataset**
- `store_income_data_task.csv`: Contains income data with columns including "country" and "date_measured".

4. **Data Analysis and cleaning process**
    - Loads the `store_income_data_task.csv` file into the notebook.
    - Examines all the unique values in the "country" column.
    - Converts the column entries to lowercase and remove any trailing white spaces.
    - Cleans up the "country" column so that there are three distinct countries.
    - Creates a new column called `days_ago` in the DataFrame that represents the number of days ago that the data was measured. Current date is obtained using `datetime.date.today()`.
