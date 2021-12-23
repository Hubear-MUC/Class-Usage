ClassUsage 2.0
--------------

To make the program able to do user interaction the previously developed destructor had to be modified to this:

1  number::~number()
2  {
3    out(c+d);
4  }

The previous version with the  return() - statement caused too much consumption of code space which was intended to be saved.


Usage:

Just invoke the program.

As the addition- programs done earlier it will ask you for two numbers by using a prompt (in :) and then add them together.

The result will be shown with an output- prompt (out :)

The special thing of this program is the usage of a class which contains the data fields for storing the two numbers.

The input routine for asking for the two input- numbers is done by the constructor, the output by the destructor, so indeed a complete usage of a class is implemented.





Version history
---------------

Version 2.0

New implementation of usage of a class and its object.
Implemented user interaction to make the usag of a debugger for working with the program obsolete.


Version 1.2

Restructured the code by putting the content of the class into a new line to make the code readable more easily.


Version 1.1

Restructured the code to make it more easy to read and to maintain.
Also there is a little space between the class definition and the "running" code now.


Version 1.0

Initial version

