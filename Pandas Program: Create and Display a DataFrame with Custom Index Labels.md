# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
Add code here

import pandas as pd 

import numpy as np

exam_data  = {'name': ['Anastasia', 'Dima', 'Katherine', 'James', 'Emily', 'Michael', 'Matthew', 'Laura', 'Kevin','Jonas'], 

'score': [12.5, 9, 16.5, np.nan, 9, 20, 14.5, np.nan, 8, 19], 

'attempts': [1, 3, 2, 3, 2, 3, 1, 1, 2, 1], 

'qualify': ['yes', 'no', 'yes', 'no', 'no', 'yes', 'yes', 'no', 'no', 'yes']}

label=['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j'] 

df = pd.DataFrame(exam_data , index=label) 

print(df)

## Output

![447082225-a29cfb45-5438-4d79-818d-beef596994dc](https://github.com/user-attachments/assets/8a5d08dd-a4e2-4964-b49f-4f268a7985ba)


## Result

Thus the program to create and display a DataFrame using the Pandas library in Python from a given dictionary, and apply specific index labels to the rows is executed successfully.
