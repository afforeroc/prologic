# Prologic (Propositional Logic Interpreter)
It's a interative interpreter of binary truth functions: conjunction, disjunction, material implication and biconditional.<br>
Here you can learn how to configure and run the app.

## Tutorial
This tutorial was designed to be done on a personal computer and their steps require using command-line interpreter, text edition, etc.

### Required software
* Command-line interpreter like Terminal, PowerShell, etc.
* Text editor like Notepad++, Visual Studio Code, etc.

### 1. Install Python and their necessary libraries
1.1 Install stable/latest version of [Python 3](https://www.python.org/downloads/).

1.2 Verify Python installation.
> Command-line
```
py -3 --version
```
```
pip3 --version
```

1.3 Install and verify PLY library.
> Command-line
```
pip3 install ply
```
```
pip3 show ply
```

> If you can't see the library version on Windows, launch a PowerShell window as an administrator and enter this following command. Later, try again to verify.
> Command-line
```
Set-ExecutionPolicy Unrestricted
```

### 2. Run the app
2.1 Run the app locally.
> Command-line
```
python prologic.py
```

2.2 Use the interpreter.
> Command-line 
```
>> T & F
F
>> T v F
T
>> T -> F
F
>> T <-> T
T
>> a = T

>> b = F

>> b -> a
T  
>> 
```

2.3 Stop the app with <kbd>ctrl</kbd> + <kbd>C</kbd>.

