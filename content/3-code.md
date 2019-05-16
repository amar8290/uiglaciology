---
title: Code
nav: true
---

# Tips on coding
We generally use python.

google is key for learning how to code.  Tim also recommends [scipy-lectures.org](https://scipy-lectures.org/) as a good consistent primer on a lot of fundamental coding tasks.


# Helpful native Python functions
1. Loop Functions: useful when using `for` loops
- `zip`
zip function zips two lists of the same length together so that you can iterate through both at the same time. 
Example:

`numbers = [1,2,3,4,5]`
`letters = ['a','b','c','d','e']`
`for number,letter in zip(numbers, letters):`
  `print(number, letter)`
- This function is especially handy when plotting multiple subplots in one loop where you want to specify different axes labels, xticks, etc. 

- `enumerate`
2. Managing data types
- `list((data))`
- `np.array((data, dtype=int))`
- `np.array((data, dtype=np.float64))

# Helpful Python Modules
1. os module
- `os.listdir(directory_path)
- `os.path.join(path_stem, filename)


