
Taking Javascript30 course...
thanks to @wesbos for an awesome course...

#### removed `finished` files:
```python
for dirpath, dirnames, filenames in os.walk('.'): # instead of `.` you can give the path to the base course directory.
     for filename in filenames: 
         if 'FINISHED' in filename: 
             print(filename) 
             os.remove(dirpath+ '/' +filename) 
```
