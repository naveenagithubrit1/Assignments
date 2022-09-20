```python
1. What exactly is []?
Sol.
   [] -- This refers to an empty list. It dpesn't have any elements in it.
```


```python
2. In a list of values stored in a variable called spam, how would you assign the value 'hello' as the
third value? (Assume [2, 4, 6, 8, 10] are in spam.)
Sol.
    spam[2] = 'hello'
```


```python
spam = [2,4,6,8,10]
spam[2] = 'hello'
spam
```




    [2, 4, 'hello', 8, 10]




```python
Let's pretend the spam includes the list [a,b,c,d] for the next three queries.
3. What is the value of spam[int(int('3' * 2) / 11)]?
```


```python
spam = ['a','b','c','d']
spam[int(int('3' * 2) / 11)]
```




    'd'




```python
4. What is the value of spam[-1]?
```


```python
spam[-1]
```




    'd'




```python
5. What is the value of spam[:2]?
```


```python
spam[:2]
```




    ['a', 'b']




```python
Let's pretend bacon has the list [3.14, 'cat', 11, 'cat', True] for the next three questions.
6. What is the value of bacon.index('cat')?
```


```python
bacon = [3.14,'cat',11,'cat',True]
bacon.index('cat')
```




    1




```python
7. How does bacon.append(99) change the look of the list value in bacon?
Sol. This adds value 99 as the last element in list.
```


```python
bacon.append(99)
bacon
```




    [3.14, 'cat', 11, 'cat', True, 99]




```python
8. How does bacon.remove('cat') change the look of the list in bacon?
Sol. It will remove the first occured element 'cat' in a list bacon
```


```python
bacon.remove('cat')
bacon
```




    [3.14, 11, 'cat', True, 99]




```python
9. What are the list concatenation and list replication operators?
Sol. Operator for concatenation +
     Operator for replication *
```


```python
10. What is difference between the list methods append() and insert()?
Sol. append() function can add element only at the end of list.
     insert() function can insert element anywhere in the list.
```


```python
11. What are the two methods for removing items from a list?
Sol. The del statement and remove() methods can remove elements from list.
```


```python
12. Describe how list values and string values are identical.
Sol.Both lists and strings can be passed to len(), have indexes and slices, be used in for loops, be concatenated or replicated, 
and be used with the in and not in operators.
```


```python
13. What's the difference between tuples and lists?
Sol.Lists are mutable.They can perform value addition , removal and changing.This denoted with []
    tuples are immutable. Which means we can't perform any operations to the values.This denoted with ()
```


```python
14. How do you type a tuple value that only contains the integer 42?
sol . (42)
```


```python
15. How do you get a list value's tuple form? How do you get a tuple value's list form?
Sol. using list() and tuple() functions.
```


```python
l = [1,2,3,4]
tuple(l)
```




    (1, 2, 3, 4)




```python
t = (5,6,7,8)
list(t)
```




    [5, 6, 7, 8]




```python
16. Variables that "contain" list values are not necessarily lists themselves. Instead, what do they
contain?
Sol. They contain references to the list values.
```


```python
17. How do you distinguish between copy.copy() and copy.deepcopy()?
Sol. The copy.copy() function will do a shallow copy of a list, while the copy.deepcopy() function will do a deep copy of a list.
That is, only copy.deepcopy() will duplicate any lists inside the list.
```
