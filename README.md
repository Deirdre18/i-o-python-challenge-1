(Solution Code from Code Institute tutorial - Challenge 1 (I/O))

# Challenge 1

Experiment with the "w+" access mode. Write some example code to understand how it works.

## Output from Console:

~/workspace $ python3
Python 3.4.3 (default, Nov 17 2016, 01:08:31) 
[GCC 4.8.4] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> f = open('myfile.txt', 'w+')
>>> f.write('Hello, World\n')
13
>>> f.seek(0)
0
>>> data = f.read()
>>> 