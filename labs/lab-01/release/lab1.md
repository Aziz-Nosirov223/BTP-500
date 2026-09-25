Part A
5.
  Yes, my teammate also guessed the same function runtime as me for the sum to goal function. The function's runtime is O(n^2).
```python
  def sum_to_goal(numbers_list, goal):
    for i in range(len(numbers_list)):
      for j in range(len(numbers_list)):
        if (i != j):
          if (numbers_list[i] + numbers_list[j] == goal):
            return numbers_list[i] * numbers_list[j]
    return None
```
