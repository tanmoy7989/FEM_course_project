# FEM_course_project
This started as a term project for the course 206D, Finite Element Methods. 
# Contents: femlib - a library with modules fem and pde. 

# fem : 
contains methods and class definitions for efficiently managing
triangular mesh data structures and linear Lagrange element based shape space. However, it is easy to add new shape spaces.

#pde:
The pde module contains code for assembling relevant finite element matrices for elliptic and parabolic pde problems. Onc
again, it is easy to add code for other families of partial differential equations.

The script simpattern.py is an application of this library in simulation of transport limited chemical patterns that arise
in isothermal autocatalytic reactions. Detailed discussion can be found in the project report. 
