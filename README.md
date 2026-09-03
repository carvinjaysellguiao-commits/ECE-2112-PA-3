# ECE-2112-PA-3
Made by: Carvin Jaysell D. Guiao | 2ECE-D
<br>
The following codes contain solution using Pandas. 

## A.Positional and Label-Based Slicing
The objective of this part is to develop the ability to explore and extract specific portions of a dataset using both positional indexing <code>iloc</code> and label-based column selection. 
<br>
**a. Displaying the shape and complete list of column names of cars**
```python
df['Model']

```
<code>df['Name']</code> indicates a positional label where it follows the certain column of the given dataset.
```python
df.shape

Expected Output:
(32, 12)
```
<code>df.shape</code> showcases the shape as it follows: <i>(rows, columns)</i>.
<br>
**b. Positional Slicing**
```python
df.iloc[0:6, 0:10]
cars_6_10 = df.iloc[0:6,0:10]
```

```python
df.iloc[:,[0,1,2,4,10 ]]
```
## B. Model Lookup
The objective of this section is to apply Boolean indexing to locate and retrieve spe3cific records in the dataset based on column values. It aims to strengthen skills in filtering data using conditions and extracting either complete rows or selected columns without relying on fixed row postions.

## C. Multi-Model Subsetting
The objective of this part is to create a new subset of data by filtering multiple specific entries simultaneously using conditional selection.
```python
selected_cars = pd.DataFrame({
  'Model': ['Datsun','Lotus Europa', 'Ferrari Dino'],
  'mpg': [22.8, 30.4, 19.7],
  'cyl': [4,4,6],
  'hp': [93, 113, 175],
  'gear': [4,5,5],

}
)
```
Thank you for reading!
To check the Jupyter Notebook, kindly open [here](). Thank you!
#### README Version History
September 3, 2026 - Initial README Upload and Draft
