# Number-Systems

### Decimal Number System

Humans express numbers in a decimal format which is also called the base 10 number system.
Decimal numbers = {0,1,2,3,4,5,6,7,8,9}

In general, the base N number system will consist of numbers from 0 to N-1.

Example
Base 2 number system has numbers from 0 to 1. i.e. 0 to (2 - 1).
Base 8 number system has numbers from 0 to 7. i.e. 0 to (8- 1).

### Positional Decimal Numbers
To represent numbers above 9, we are using positional decimal numbers.

Example
(18)10 consist of two decimal numbers which are 1 and 8.
Here,
The position of 8 is 0.
The position of 1 is 1.
Position count starts from the right side of a number.


18
= 1*(101) + 8*(100)
= 1*10+8*1
= 10+8
= (18)10

Example
145
The position of 5 is 0.
The position of 4 is 1.
The position of 1 is 2.


(145)10
= 1*(102) + 4*(101) + 5*(100)
= 100+40+5
= (145)10



### Real Numbers
When it comes to the real numbers or numbers with fractional parts, the position after the dot(.) will be counted as -1, -2 and so on.
Example
(125.67)10
The position of 6 is -1.
The position of 7 is -2.
The position of 5 is 0.
The position of 2 is 1.
The position of 1 is 2.


125.67
= 1*(102) + 2*(101) + 5*(100) + 6*(10-1) +7*(10-2)
= 100 + 20 + 5 + 0.6 + 0.07
= 125.67



### Binary Number System
The computer can understand only the binary number system which is also called the base 2 number system.
Binary number system = {0,1}.


Humans express numbers in positional decimal format. But the computer can’t store decimal numbers directly.
The computer automatically converts the decimal number to binary format before using it.
Whatever be the data, the computer always converts it into its only known language which is binary.

 


How to convert decimal numbers into binary numbers?
Decimal to the Binary Conversion formula.
In general, decimal to any number system conversion procedure will be,
1. Take the number modulo base i.e. number % base
2. Write down the result. i.e. remainder
3. Divide the number by base i.e. number/base
4. repeat the process until the number is greater than 0. (number > 0)

Finally, rewrite all remainders in reverse order.


Let's convert (22)10 into Binary format,
Here, base value = 2

 ![image](https://user-images.githubusercontent.com/89007620/150343111-102a88fe-8a42-43a2-bc15-6daa25df1f2a.png)

