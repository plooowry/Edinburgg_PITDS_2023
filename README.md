# Practical Introduction to Data Science 2023

My notes from the University of Edinburgh course "Practical Introduction to Data Science" (2023), kept as a Jupyter notebook.

## Contents

`0_Master_Notes_20230505.ipynb` covers Block 1 of the course:

- What data science is and why it matters
- Connecting to a remote course database over SSH through a jump host, and moving files between machines
- Downloading data with `wget`
- A short introduction to Python, NumPy and pandas, including vector and summation notation
- A pandas practical: loading a CSV, inspecting columns, counting records by group and plotting the result

## Running the notebook

```
pip install pandas matplotlib jupyter
jupyter notebook 0_Master_Notes_20230505.ipynb
```

The pandas examples read a CSV from a local path on my machine, so change the path to your own copy of the data before running those cells. The course database is only available to enrolled students.
