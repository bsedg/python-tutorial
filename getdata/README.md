# Data Retrieval
These tutorials focus on a simple concept, retrieving data.  Data as an example here could be weather temperatures, weather description, or a twitter message.

## Variables, Lists, Dictionaries

### Variables

```python
url = 'www.google.com'

x = 30
y = 2.0

z = x / y # z = 15.0
```

For more documentation, check out [Python Introduction](http://docs.python.org/2/tutorial/introduction.html#an-informal-introduction-to-python).

### Lists

Use lists to store strings:
```python
items = []
items.append('item-1')
items.append('item-2')

print items
#displays>['item-1', 'item-2']
```

Use lists to store numbers, or integers (int):
```python
numbers = [ 2, 4, 6, 8, 10 ]
print numbers
#displays>[2, 4, 6, 8, 10]

numbers[0] = 1 # change the first element in list, zero based
print numbers
#displays>[1, 4, 6, 8, 10]
```

For more documentation, check out [Python Lists](http://docs.python.org/2/tutorial/datastructures.html#more-on-lists).

### Dictionaries
A dictionary in python 
```python
test_scores = {}
test_scores['student1'] = 92.0
test_scores['student2'] = 84.5

print test_scores
#displays>{'student2': 84.5, 'student1': 92.0}

print test_scores['student2']
#displays>84.5
```

For more documentation, check out [Python Dictionaries](http://docs.python.org/2/tutorial/datastructures.html#dictionaries).

## REST APIs, JSON Data Format

### REST APIs

### JSON Data Format
