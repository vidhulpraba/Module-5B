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

data = {
    'Name': ['Abi', 'Ravi', 'Kavi'],
    'Age': [18, 19, 18]
}

df = pd.DataFrame(data, index=['A', 'B', 'C'])

print(df)
```

## Output
  Name  Age
A  Abi   18
B  Ravi  19
C  Kavi  18
## Result
### Python Program

```python
import pandas as pd

data = {
    'Name': ['Abi', 'Ravi', 'Kavi'],
    'Age': [18, 19, 18]
}

df = pd.DataFrame(data, index=['A', 'B', 'C'])

print(df)
```

### Output

```text
  Name  Age
A  Abi   18
B  Ravi  19
C  Kavi  18
```

**Result:**
Thus, the Pandas program to create and display a DataFrame from a dictionary with specific index labels was successfully executed.

