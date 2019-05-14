# optimization-algorithms-project
The project provides the generic neighbourhood-based solver + GUI interface for NP-hard tasks on a example of 2BP problem. 

## Task
Implement generic neighbourhood-based search algorithms:

- Local search
- Simulated annealing
- Tabu search

The algorithms are applied to solve a 2BP problem with parametrized number and size of square bins,
and the number and size of filling rectangles. 

## Installation
```
git clone https://github.com/VladYushchenko/optimization-algorithms-project.git
```
You need to have `Qt5` library and `qmake` installed on your machine, which includes QtWidgets, QtGui and QtCore.

For more detailed instruction on Qt5 installation please see [this link](https://www.qt.io/download).

## Usage
### Linux
Create the build and create 

```
mkdir build
cd ./build 
qmake -makefile ../Opt.pro
```
This creates the makefile from the corresponding project file. 

Then use `make` command to create executable named *Opt*.

```
make
./Opt
```
