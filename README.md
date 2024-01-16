# PyhidraNotebook

Pyhidra is a Python library that provides direct access to the Ghidra API within a native CPython interpreter using [jpype](https://jpype.readthedocs.io/en/latest). As well, Pyhidra contains some conveniences for setting up analysis on a given sample and running a Ghidra script locally. It also contains a Ghidra plugin to allow the use of CPython from the Ghidra user interface.

In this script, we will learn how to use basic functions provided by pyhidra. Furthermore, we will discover the function related to binary analysis


* **Task 1:** wirte a inherit launcher class to implement log service
* **Task 2:** Create or open a project with given path and name 
* **Task 3:** import a program with path and name and get the flat api
    * flatapi is a interface to export many useful functions without determine the class of it
* **Task 4:** set the correct base address of the binary file
* **Task 5:** create a function based on the vector table 
* **Task 6:** Save the program and close the project
