#### The following notes are a summary of the side notes in cryptozombies.io tutorial ["Making the zombie factory"] a.k.a: lesson 1.

## Chptr 2:
- Contracts: Solidity is encapsulated in contracts. 
- Every Solidity source should begin with Pragma and the version of any compiler your going to use.

## Chptr 3:
- State variables are permanently sotred in contracts storage. (is like writing to a DB).
    ex.: uint aNewVariable = 100; in this case we created a uint and set it equal to 100. </br> 
-->uint means unsigned integrers.

## Chptr 4: 
- Math Operators: 
    -->Addition: x + y
    -->Subtraction: x - y,
    -->Multiplication: x * y
    -->Division: x / y
    -->Modulus / remainder: x % y (for example, 13 % 5 is 3, because if you divide 5 into 13, 3 is the remainder)
    -->Exponential: x ** y  means => x^y.

## Chptr 5: 
Structs: (like in c) to use a complex data type. 
    ex.: struct Person{
        uint age;
        string name;
    }

## Chptr 6: 
<u>Arrays:</u> when you want a collection of sth, you can use an array. </br>
    2 types of arrays in Solidity </br>
        - fixed. ex.: uint[2] fixedArrayl; (declared a fixed array with the lenght of 2 elements);
        ex.2: string[5] stringArray; (a fixed array that can contain up to 5 strings); </br>
        - dynamic. ex.: uint[] dynamicArray; (it doesn't have an indicated lenght so you can keep adding elements and it keeps growing.); </br>

    - You can also create an array of structs like:
    Person[] people; // this array is dynamic -you can keep adding things-

    - you can also declare them public or private;
    The matter with public arrays, Solidity will (automatically) create a getter method for it.

## Chptr 7:
Function declarations: 