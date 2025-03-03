Pandas.DataFrame
===
DataFrame([data, index, columns, dtype, copy]) - Two-dimensional, size-mutable, potentially heterogeneous tabular data.

Attributes and underlying data
---

```
DataFrame.index - The index (row labels) of the DataFrame.
DataFrame.columns - The column labels of the DataFrame.
DataFrame.dtypes - Return the dtypes in the DataFrame.
DataFrame.info([verbose, buf, max_cols, ...]) - Print a concise summary of a DataFrame.
DataFrame.select_dtypes([include, exclude]) - Return a subset of the DataFrame's columns based on the column dtypes.
DataFrame.values - Return a Numpy representation of the DataFrame.
DataFrame.axes - Return a list representing the axes of the DataFrame.
DataFrame.ndim - Return an int representing the number of axes / array dimensions.
DataFrame.size - Return an int representing the number of elements in this object.
DataFrame.shape - Return a tuple representing the dimensionality of the DataFrame.
DataFrame.memory_usage([index, deep]) - Return the memory usage of each column in bytes.
DataFrame.empty - Indicator whether Series/DataFrame is empty.
DataFrame.set_flags(*[, copy, ...]) - Return a new object with updated flags.
