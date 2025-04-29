# Common Code Queries and Their Meanings

This file provides explanations for common code queries often used in data analysis and visualization, especially with libraries like pandas and matplotlib.

---

## 1. `plt.df`

- This is not a standard or common usage in matplotlib or pandas.
- Likely a typo or shorthand. Usually, `plt` refers to `matplotlib.pyplot`, which is used for plotting.
- Example usage of `plt`:
  ```python
  import matplotlib.pyplot as plt
  plt.plot([1, 2, 3], [4, 5, 6])
  plt.show()
  ```
- If you see `plt.df`, it might be a mistaken reference to a DataFrame object or a custom attribute. Verify the context in the code.

---

## 2. `df.shape`

- `df` usually refers to a pandas DataFrame.
- `.shape` is an attribute that returns a tuple representing the dimensionality of the DataFrame.
- The tuple is in the form `(number_of_rows, number_of_columns)`.
- Example:
  ```python
  import pandas as pd
  df = pd.DataFrame({'A': [1, 2], 'B': [3, 4]})
  print(df.shape)  # Output: (2, 2)
  ```

---

## 3. `df.head()`

- Returns the first 5 rows of the DataFrame by default.
- Useful for quickly inspecting the data.
- Example:
  ```python
  df.head()
  ```

---

## 4. `df.info()`

- Provides a concise summary of the DataFrame including the number of non-null entries, data types, and memory usage.
- Example:
  ```python
  df.info()
  ```

---

## 5. `plt.plot()`

- A function from `matplotlib.pyplot` used to plot data points on a 2D graph.
- Example:
  ```python
  plt.plot([1, 2, 3], [4, 5, 6])
  plt.show()
  ```

---

## 6. `df.describe()`

- Generates descriptive statistics of the DataFrame’s numeric columns such as count, mean, std, min, max, and quartiles.
- Example:
  ```python
  df.describe()
  ```

---

## 7. `plt.show()`

- Displays the current figure that has been created using matplotlib plotting functions.
- Example:
  ```python
  plt.plot([1, 2, 3], [4, 5, 6])
  plt.show()
  ```

---

## 8. `df.columns`

- Returns the column labels of the DataFrame.
- Example:
  ```python
  print(df.columns)
  ```

---

## 9. `df['column_name']`

- Accesses a specific column in the DataFrame.
- Example:
  ```python
  df['A']
  ```

---

## 10. `df.loc[]` and `df.iloc[]`

- `df.loc[]` is label-based indexing to access rows and columns by labels.
- `df.iloc[]` is integer position-based indexing to access rows and columns by integer position.
- Examples:
  ```python
  df.loc[0, 'A']    # Access value at row label 0 and column 'A'
  df.iloc[0, 1]     # Access value at first row and second column
  ```

---

This file can be extended with more common queries and their explanations as needed.
