In C/C++ the number of digits a long long int can have is a maximum of 20. And the question is to store the 22 digit number which is not easy to store in any kind of primitive type. So to deal with this type of problem let’s design a new data type which is going to be called BigInt In this article, a few basic operations are being implemented on the new data type.

    Add two big integers.
    Subtract two big integers
    Multiply two big integers.
    Divide two big integers.
    Modulo two big integers
    Raise a big integer to a power
    The square root of a big integer
    Comparison between two big integers to check which is greater and which is smaller.
    Find the number of digits in the big integer.
    Print the big integer.
    Convert an integer to a big integer.

Applications Of BigInt:
Below are some basic applications of the new data type, BigInt:

    Calculating the Fibonacci number of a large number.
    Calculating the Catalan number of a large number
    Calculating the Factorial of a big integer.

Approach:
To create a new data type of big integers following concepts are being implemented:

    C++ strings in that we can store our numbers in the form of characters (in reverse order for efficiency purposes) such that using strings we can store very big numbers also.
    For the addition/subtraction operation of two big integers, use the basic math for addition which says that add the corresponding two digits and if some carry is generated add it to the sum of the next digits and repeat this process until all digits are added/subtracted.
    Similarly, for the multiplication of two numbers, use the basic mathematics approach which states that multiply every digit of one number with the other complete number and at last add all the numbers we get in multiplication.
    The following operations are being performed on BigInt-
        Defining some big integers.
        Checking the number of digits in the big integer.
        Post/Pre Incrementation or Decrementation
        Adding two big integers.
        Subtracting two big integers.
        Multiplying two big integers.
        Divide two big integers
        Modulo of two big integers
        The square root of a big integer (floor integer value)
        Raise a big integer to a power
        Converting a simple integer to a big integer.
        Calculating Fibonacci up to 10 000. (even 100000 but slower)
        Calculating Factorial up to 1 000.
        Calculating Catalan up to 1 000.
        Checking which big integer is greater and which is smaller.
