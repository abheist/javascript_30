
Taking Javascript30 course...
thanks to @wesbos for an awesome course...

#### removed `finished` files:
```python
for i, j, k in os.walk('.'): # instead of `.` you can give the path to the base course directory.
     for f in k: 
         if 'FINISHED' in f: 
             print(f) 
             os.remove(i+ '/' +f) 
```
