Bash Scripting
(Bourne-Again SHell)


#!/bin/bash

#  	to comment out code, like //, and debugs

Variable Creation
-------- --------

e.g. name="Jammy" // no spacing unlike C

$ 	to use it 	e.g. echo $name
$#	number of arguments supplied to a script
$0	filename of current script

unset 	remove from array[]
	to set variable assign into array e.g. cars[3]=’toyota’


Operators
---------

Operator	Description

-eq		checks if the value of two operands are equal or not; if yes, then the condition becomes true.
-ne		checks if the value of two operands are equal or not; if values are not equal, then the condition becomes true.
-gt		checks if the value of left operand is greater than the value of right operand; if yes, then the condition becomes true.
-lt		checks if the value of left operand is less than the value of right operand; if yes, then the condition becomes true.
-ge		checks if the value of left operand is greater than or equal to the value of right operand; if yes, then the condition becomes true.
-f		check if file exists
-w		check if file writable
-r		check if we have access
-d		check if it's a directory