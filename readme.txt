ClassUsage 1.1
--------------

First usage of the class concept within this project of knowledge regaining in coding.

1   class a
2   {public:
3   int a,b;
4   };
5 
6   a o;int r;
7
8   main()
9   {
10  r=o.a+o.b;
11  }



Usage:

The usage and the working of this program are very simple. In fact it is just a replica of the addition- programs published earlier.

Just set breakpoints at lines 9 and 11 and run the program.

Then set the variables

  o.a
  
and

  o.b
  
to the values that should be added together.

Mind that this addition just can be done with integer- numbers due to the limited code space.

continue the program to the breakpoint at line 6 and examine the result in variable r.


The speciality of this program is that the numbers were stored inside an object, not just in simple variables.

Still there is no implementation of a method doing the actual calculation because the new code space was rather used to make the code readable more easy. This method should be implemented in a later version of the program.




Version history
---------------

Version 1.1

Restructured the code to make it more easy to read and to maintain.
Also there is a little space between the class definition and the "running" code now.


Version 1.0

Initial version

