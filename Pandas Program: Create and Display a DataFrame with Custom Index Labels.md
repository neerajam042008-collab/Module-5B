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
```
import pandas as pd
l1=eval(input())
df=pd.DataFrame(l1)
print(df)
```

## Output
<img width="954" height="374" alt="Screenshot 2025-10-21 123819" src="https://github.com/user-attachments/assets/4728e3f6-c4a2-4d30-9338-8f5f9cd1a7b2" />

## Result
successfully created  a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.
