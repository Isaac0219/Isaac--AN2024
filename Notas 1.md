Enteros 
|:d0|d1|d2|d3:|





```python
total = 0.0
for i in range(1000):
    total += 0.1
print(f"Espected Result: 100.0\nActual Result: {total}")
```

    Espected Result: 100.0
    Actual Result: 99.9999999999986



```python
def iternum(n):
    result =1
    for i in range(n):
        result += 0.1
    for i in range(n):
        result -= 0.1
    return result
iternum(10000)
```




    0.9999999999999561




```python
format(iternum(10000000), '0.30f')
```




    '0.999999999959817587047439246817'




```python
0.3 == 0.1+0.1+0.1
```




    False




```python

```
