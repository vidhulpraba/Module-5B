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

df1 = pd.DataFrame({
    'Name': ['Abi', 'Ravi'],
    'Age': [18, 19]
})

df2 = pd.DataFrame({
    'Name': ['Kavi', 'Siva'],
    'Age': [20, 21]
})

new_df = pd.concat([df1, df2], axis=0, ignore_index=True)

print("Joined DataFrame:")
print(new_df)
```

## Output
Joined DataFrame:
  Name  Age
0  Abi   18
1  Ravi  19
2  Kavi  20
3  Siva  21
## Result
### Python Program

```python
import pandas as pd

df1 = pd.DataFrame({
    'Name': ['Abi', 'Ravi'],
    'Age': [18, 19]
})

df2 = pd.DataFrame({
    'Name': ['Kavi', 'Siva'],
    'Age': [20, 21]
})

new_df = pd.concat([df1, df2], axis=0, ignore_index=True)

print("Joined DataFrame:")
print(new_df)
```

### Output

```text
Joined DataFrame:
  Name  Age
0  Abi   18
1  Ravi  19
2  Kavi  20
3  Siva  21
```

**Result:**
Thus, the Pandas program to join two DataFrames along rows and assign the combined data to a new DataFrame was successfully executed.
