# C
Everything related to C

<!-- VARIABLES -->

Learnt loads in the first lesson itself. 

C code block starts with int main () {}

decimal base 10 values are declared with int. printed as %d (% specifies the type of format. d specifies that it is decimal base 10)

if there's a decimal it will be declared with float. printed as %.1f. the ".1" let's it know to retrun the value to the first decimal point.

single letters are declared with a char. single characters will have single quotes. printed as %c

multiple characters (strings) are printed as char[]. this is to show an array of letters. printed as %s

char[] is similar of "let" in JS. in that it is mutable. can be reassigned.

char* is similar to const. immutable.

to declare a value to a variable and to change it: 

int x = 10;

x = 20;


to change of a name:

int main () {
  char name [] = "Ramiz";
  name [0] = 'K';
}

this will print Kamiz

