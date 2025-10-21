# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```

import pandas as pd
df1=pd.DataFrame({
    's_id':['S1','S2','S3','S4','S5'],
    'name':['Dan','Ryder','Bryce','Bernal','Kwame'],
    'marks':[200, 210, 190, 222,199]
})
df2=pd.DataFrame({
    's_id':['S4','S5','S6','S7','S8'],
    'name':['Scart','Willy','Dani','Kaise','Madeeha'],
    'marks':[201,200,198,219,201]
})
res=pd.concat([df1,df2],axis=0)
print("Original DataFrames:")
print(df1)
print("-------------------------------------")
print(df2)
print()
print("Join the said two dataframes along rows:")
print(res)
```

## Output
<img width="857" height="721" alt="Screenshot 2025-10-21 124046" src="https://github.com/user-attachments/assets/4f85ff17-4508-4231-b10f-b9712b418fd2" />

## Result
successfully created  a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.
