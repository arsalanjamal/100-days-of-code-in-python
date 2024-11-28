# Day 3 - Modules and pip in Python!

A **module** is like a code library, which can be used to borrow code written by somebody else in our Python program. There are two types of modules in Python:

## Types of Modules in Python:

- **Built-in Modules**: These modules are ready to import and use and ship with the Python interpreter. There is no need to install such modules explicitly.
- **External Modules**: These modules are imported from a third-party file or can be installed using a package manager like `pip` or `conda`. Since this code is written by someone else, we can install different versions of the same module over time.

## The pip Command

`pip` is used as a package manager to install Python modules. Let’s install a module called `pandas` using the following command:

```bash
pip install pandas

Using a Module in Python (Usage)
We use the import syntax to import a module in Python. Here is an example code:

python
Copy code
import pandas
# Read and work with a file named 'words.csv'
df = pandas.read_csv('words.csv')
print(df)  # This will display the first few rows from the words.csv file
Similarly, we can install other modules and look into their documentation for usage instructions. We will find ourselves doing this often in the later part of this course.

vbnet
Copy code
