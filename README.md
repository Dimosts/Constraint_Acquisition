# Constraint_Acquisition
Constraint Acquisition Executable file

A description of the system can be found in the pdf file.

Some example benchmarks are provided. In order to run the executable with the benchmarks, they must be in a folder named "benchmarks/"

The constraints are given to the system as follows:

<relation_identifier> <variables> <constants>

The numbers corresponding to each relation are the following:
  
0 : != , 1 : = , 2 : > , 3 : < , 4 : >= , 5 : <= , 		
6 : x1 - x2 = 1, 7 : x2 - x1 = 1, 8 : |x1 - x2| = 1		
9 : |x1 - x2| != |x3 - x4|								
10 : |x1 - x2| = |x3 - x4|								
11 : |x1 - x2| > arg3									
12 : |x1 - x2| = arg3									
13 : x1 - x2 = x3									
14 : |x1 - x2| > |x3 - x4|								
15 : |x1 - x2| < |x3 - x4|								
16 : |x1 - x2| < arg3									
17 : |floor(x1/3) - floor(x2/3)| > arg3					
