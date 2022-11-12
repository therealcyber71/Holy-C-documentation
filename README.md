# Holy C documentation

## About
This Readme will hopefully serve as a Documentation for the Holy C language outside of Temple OS \
Got something to add? Feel free to make a pull request and I'll review it.

**Prerequisites**
* Some basic C knowledge
* Assembly?! (Optional)
* Setting up a virtual machine

## What we'll be covering

* [Hello World](https://www.youtube.com/watch?v=_k92KAVjkdc&ab_channel=CyberWasBored)
* Data Types
* Conditional Statements
* Iteration statements
* User defined functions
* Classes and Objects
* What you can do with Holy C
* Some basic Algorithms and other exercises


I'll also be uploading the tutorials on my YouTube channel!



## Hello world

In Holy C there is no "`printf`" or "`cout`" statement, adding strings in double quotes itself acts as an output statement.

### Hello World in the terminal

For example
```HolyC
C:/Home>"Hello World";
```
Output:
```HolyC
Hello World0.000117s // where 0.000117s is the execution time
```

The code can be written in the terminal itself, it's almost similar to using the Python terminal as the command prompt or the powershell on Windows, due to this awesome
feature, HolyC can be used as a Porgramming language as well to write terminal commands.

It is also worth noting that statements after `//` are not read by the compiler, hence they are used as comments.


### Hello world in a HolyC file
To write to a file, you must first create it
```HolyC
C:/Home>Ed"NewFile.HC";
```
A similar blank page should appear, you write your code in the blank space: 

![NewFileHC](https://github.com/The-Holy-Church-of-Terry-Davis/Holy-C-documentation/blob/main/imgs/NewFileHC.png?raw=true)

Write the previously mentioned code here:

![HelloWorldHC](https://raw.githubusercontent.com/The-Holy-Church-of-Terry-Davis/Holy-C-documentation/main/imgs/HelloWorldHC.png)


Hit the `F5` key to run the file, upon succesful execution you should get an output in the terminal with "Hello World" and the execution time.

And you have your first Hello World Program in Holy C, Terry would be proud!


## Data Types and Variables

### Types of Data
This chart here should help you understand the different data types available in HolyC and understand its corresponding type in C \

![TheChart](https://raw.githubusercontent.com/The-Holy-Church-of-Terry-Davis/Holy-C-documentation/main/imgs/TheChart.png)


`I` indicates signed integer data type, `U` indicates unsigned integer data type.
Signed integers allows you to store +ve as well as -ve integers, whereas unsigned allows you to store only +ve values.

Let's get started with a simple variable declaration then!
```HolyC
C:/Home>I32 score;
C:/Home>score = 69; //noice
```

Output: `Address and value of the variable "score" will be displayed.`

By referring to the chart, you can do a lot more with these data types, now let's try adding two variables \
```HolyC
C:/Home>I32 fvar = 20;
C:/Home>I32 svar = 40;
C:/Home>I32 sum = fvar + svar;
C:/Home>sum;
```

Output: `Address and value of the variable "sum", i.e. 60, will be displayed.`

You can add, multiply, divide, subtract, floor divide (getting remainders), and do a lot more with variables.


Now we'll try printing a string, you'll notice that all the data types say "integers", that's why we'll use the `U8` or the `I8`, since the corresponding C data type is `char`

