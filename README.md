# PAN Validation Project

This project validates Indian PAN (Permanent Account Number) cards from a given dataset using Python and Jupyter Notebook. It applies a series of checks to ensure each PAN number conforms to the correct format, making it useful for data cleaning and verification.

---

### Files

* `PAN_VALIDATION.xlsx` - The dataset containing PAN numbers to be validated.
* `PAN Number Validation - Problem Statement.pdf` - The original problem statement for this project.
* `PAN_validation.ipynb` - The main Jupyter Notebook containing the Python code for validation.
* `requirements.txt` - A list of all necessary Python libraries to run this project.
* `README.md` - This file, providing an overview and instructions for the project.

---

### How to Run

1.  **Clone the repository** to your local machine or download the project files.
2.  **Install dependencies**: Open your terminal or command prompt and navigate to the project directory. Run the following command to install all the required libraries:
    ```
    pip install -r requirements.txt
    ```
3.  **Run the notebook**: Open the `PAN_validation.ipynb` file in a Jupyter Notebook environment. Run each cell sequentially to perform the validation and see the results.

---

### Sample Output

The project processes the provided dataset and adds a new column showing whether each PAN is valid or not.

| PAN Number | Is Valid |
| :--- | :--- |
| ABCDE1234F | True |
| XYZ1234567 | False |
| PQRST9876U | True |

This project successfully validated all entries, identifying `[]` valid and `[932]` invalid PAN numbers. The final results are saved in a `results/` folder, as indicated in the notebook.
