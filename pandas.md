# Pandas
- we import it as pd.
- `import pandas as pd`
### series
The most basic building block in Pandas is a Series. A Series is a one-dimensional labeled array. Unlike a NumPy array, where you can only look up data using positions (0, 1, 2...), a Pandas Series allows you to give each row a custom name or label, known as an Index.

### dataframe
A Series is great for a single attribute, but what if you want to track multiple stats for these players (like jersey number, goals scored, and matches played)?
Enter the DataFrame. A DataFrame is a 2-dimensional tabular data structure with labeled axes (rows and columns).
The Analogy: If a Pandas Series is a single column in an Excel sheet, a Pandas DataFrame is the entire spreadsheet. Every row represents a single record (e.g., an athlete), and every column represents a specific feature or attribute of that record.

#### Loading Data:
The most common way to store tabular data is in a CSV (Comma-Separated Values) file. Pandas makes reading these incredibly easy with pd.read_csv().
