ClassUsage 1.2
--------------

First usage of the class concept within this project of knowledge regaining in coding.

1   class a
2   {
3   public:
4   int a,b;
5   };
6 
7   a o;int r;
8
9   main()
10  {
11  r=o.a+o.b;
12  }



Usage:

The usage and the working of this program are very simple. In fact it is just a replica of the addition- programs published earlier.

Just set breakpoints at lines 10 and 12 and run the program.

Then set the variables

  o.a
  
and

  o.b
  
to the values that should be added together.

Mind that this addition just can be done with integer- numbers due to the limited code space.

continue the program to the breakpoint at line 12 and examine the result in variable r.


The speciality of this program is that the numbers were stored inside an object, not just in simple variables.

Still there is no implementation of a method doing the actual calculation because the new code space was rather used to make the code readable more easy. This method should be implemented in a later version of the program.




Version history
---------------

Version 1.2

Restructured the code by putting the content of the class into a new line to make the code readable more easily.


Version 1.1

Restructured the code to make it more easy to read and to maintain.
Also there is a little space between the class definition and the "running" code now.


Version 1.0

Initial version

