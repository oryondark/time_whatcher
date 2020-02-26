# time_whatcher
you can try that you would like to measure consuming time in function your model.


```python

w = Watch(td=True)
def fibonacci_test(r):
    for i in range(0, r):
        for j in range(0, r):
            j

# 
# 1 arg : function object name 
# 2 arg : type of seq-list where input argments 
# 3 arg : debug-name
w.watch(fibonacci_test, [10000], name='fibo_test')
```

This function means that i want make to time checking but best code intuition my model.<br>

Comp.
```python
debug_start = time.time()
x = input_1
y = input_2
in_my_function(x, y)

print("debug : ", in_my_function(x,y)
```

``` python
# Wow!
consumed1, _ = w.watch(fibonacci_test, [10000], name='fibo_test1')
consumed2, _ = w.watch(fibonacci_test, [200], name='fibo_test2')
consumed3, _ = w.watch(fibonacci_test, [300], name='fibo_test3')
```
