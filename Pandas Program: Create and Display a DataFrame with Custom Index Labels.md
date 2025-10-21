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
```

import pandas as pd
d=pd.DataFrame({'s_id':['S1','S2','S3','S4','S5'],'name':['Dan','Ryder','Bryce','Bernal','Kwame'],'marks':[200, 210, 190, 222,199]})
print(d)
```

## Output
<img width="1920" height="1080" alt="Screenshot (140)" src="https://github.com/user-attachments/assets/46d76834-6abf-490d-a1bb-275a096cff8c" />

## Result
