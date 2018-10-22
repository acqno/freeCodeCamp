---
title: Arrays
---

# Arrays

An array is used to store a collection of data of the same type. This can be used as a single variable that holds multiple values, or a collection of variables.

## Rules of Arrays

Arrays start from zero. The first element of an array is 0, the second element is 1, the third element 2, and so on.

Arrays must be of the same data type. You can use any data type in an array (e.g. int, double, float, string, enum)

A new Array must first be declared and initialised before it can be called and accessed.

## Declaring an Array

Use the following format for declaring arrays:
`dataType [] nameOfArray;`

## Initializing an array

Use the following format for initializing an array. This method also declares the array and states how many values are to be stored into the array.

`dataType [] nameOfArray = new nameOfArray[numberOfElements];`

An array can also be initialized at declaration, in which case the number of elements does not need to be supplied because it is already initialzed with the values in the list. For example: 

`string[] weekdays = {"Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"};`

It is also possible to initialize an array outside of the declaration. The `new` operator must be used when assigning the array to the variable. For example: 

```csharp

int[] evenNum;
evenNum = new int[] {2, 4, 6, 8};
```

## Assigning values to an array

You can assign a value into an element directly by using the format below:

`nameOfArray[2] = 50;`

This will assign the value of 50 directly into element [2]


You can assign multiple values at once while declaring the array using the format below:

`dataType [] nameOfArray = {5,17,19,92};`

This will assign the value of 5 into element [0], 17 into element [1], 19 into element [2] and 92 into element [3].

You can declare, initialize and assign values in the array all at once by using the format below:

`dataType [] nameOfArray = new nameOfArray[numberOfElements] {value1,value2,value3,value4};`

You can store an array directly into another array by using the format below:

`int [] nameOfArray = new nameOfArray[4] {2,9,56,1280};`
`int [] nameOfSecondArray = nameOfArray;`

## Advantages

* Can be easily accessed in a random manner
* Can be easily manipulated

## Disadvantages

* The only disadvantage is that the size of an array is fixed. (Hence, a list can be used in case of a dynamic sizing.)
