# Assignment 01 Notes
- To do
1. Repository created
2. Jupyter Notebook created
3. Read Chapter 1 and 2

## Important Notes from Chapter 1 and 2
### NumPy
- Numerical Python- numerical comuputing, algorithms, linear algebra operations

### Pandas
- blends data manipulation capabilities of spreadsheets and relational databases
- makes it easy to reshape, slice and dice, perform aggregations, and select subsets of data

### matplotlib
- most popular Python library for producing plots and other twodimensional data visualizations

### Important Concepts
- %run command

- magic commands

- For loop example
  [ sequence = [1, 2, None, 4, None, 5]
  total = 0
  for value in sequence:
    if value is None:
      continue
    total += value ]
    
- While loop example
  [ x= 256
  total = 0
  while x > 0:
    if total > 500:
      break
    total += x
    x = x // 2 ]
  
  
 - Range example
   [ sum = 0
    for i in range(100000):
       % is the modulo operator
      if i % 3 == 0 or i % 5 == 0:
        sum += i ]
