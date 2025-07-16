#  Marks Adder - Jupyter Notebook

A simple Python project that reads a CSV file containing student roll numbers and marks.  
If a roll number appears multiple times, the notebook adds up the marks and saves the final result in a new CSV file.

---

##  Features

- Aggregates marks for repeated roll numbers
- Outputs the total marks per student
- Saves the result as `Final_Marks.csv`
- Beginner-friendly and easy to run in Jupyter

---

##  How It Works

1. Load the input CSV file (`Mini Project - Marks Adding.csv`)
2. Group the data by `Roll Num`
3. Use `.sum()` to total the marks
4. Save the results using `.to_csv()`

---

## ▶ How to Run

1. Clone the repo or download the files
2. Install dependencies:
   ```bash
   pip install pandas



   <img width="1086" height="674" alt="image" src="https://github.com/user-attachments/assets/8b5d60d1-4870-4bf8-8d14-749d6b27d945" />

