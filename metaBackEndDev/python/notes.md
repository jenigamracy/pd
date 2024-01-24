# Introduction to Python

**Modules**

1. [Getting Started with Python](#getting-started-with-python)
1. Basic Programming with Python
1. Programming Paradigms
1. Modules, Packages, Libraries, and Tools
1. Graded Assessment

## Getting Started with Python

### A wee bit of history

Charles Babbage
- 1822
- Cambridge

Ada Lovelace

### Setup

Encountered errors when trying to set up an interpreter.
- Had to set up a virtual environment first, and only then was I able to select an interpreter.

Also, got errors when running hello.py re: scripts and execution policies.
- Ran the first command in the terminal which got rid of the issue

```
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned 
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Unrestricted -Force
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy Bypass -Force
```

- note the other two are similar, but RemoteSigned is likely a better solution than Unrestricted or Bypass

