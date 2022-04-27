# Getting Started Guide

Many PCs and Macs will have python already installed.

To check if you have python installed on a Windows PC, search in the start bar for Python or run the following on the Command Line (cmd.exe):
```
python --version
```
if you can see version python is already installed in your system. else proceed to installation steps.


## installation

for installation steps based on your os refer to 

https://www.python.org/




## Basic ways to run python

Once the installation is complete, you should be able to run python interactively or run python files.


### 1. python interactive shell
```sh
# open command line and enter 
python3

# this will open a interactive python shell and every line starts with >>>>
# now enter following command to test
print("hello world")
# you should be able to see hello world printed out.

print(1+2+3)
# should print 5
```

### 2. python file
create a file named `test.py` in any location and add the following content

```python
print("hello world")
print(1+2+3)
```

now upon saving the file. run following command to execute python.

```sh
python test.py
```

