# ArrayandStrings

Aim: To study and implement C++ Arrays and Strings 

Theory:

Array-
An array stores a fixed-size sequential collection of elements of the same type. All arrays consist of contiguous memory locations. The lowest address corresponds to the first element and the highest address to the last element.
For example, an array containing 5 integer values of type int called foo could be represented as:
where each blank panel represents an element of the array. In this case, these are values of type int. These elements are numbered from 0 to 4, being 0 the first and 4 the last; In C++, the first element in an array is always numbered with a zero (not a one), no matter its length.

DECLARING ARRAY-
To declare an array in C++, we must specify the type of elements and the number of elements required by an array −
type arrayName [ array_size ];
The array_size must be an integer constant greater than zero and type can be any valid
C++ data type.

INITIALISING ARRAY-
You can initialize C++ array elements either one by one or using a single statement as follows −
int arr[5] = {1000, 2, 3, 17, 50};
The number of values between braces { } cannot be larger than the number of
elements that we declare for the array between square brackets [ ].

ACCESSING ARRAY ELEMENTS-
An element is accessed by indexing the array name. This is done by placing the index of the element within square brackets after the name of the array. For example −
int num = arr[9];
The above statement will take the 10th element from the array named arr and assign
the value to num variable.

Strings:
A string is a sequence of characters used as an object of the class. The string class stores the characters as a sequence of bytes with the functionality of allowing access to the single-byte character. A string is different from an array of characters. 
