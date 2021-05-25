## Introduction

The purpose of this paper is to explain the concepts learned in Module 07 on functions, specifically the 3 types 1) scalar, 2) inline table-value, and 3) multi-statement table-value.

### Explain when you would use a SQL UDF.

SQL functions can either be built-in functions or user defined functions (UDFs). UDFs are custom functions and can be used when built-in functions don’t provide the specific functionality we need. An example of when a UDF would be used is for check constraints, see Figure 1.

![Figure 1](https://user-images.githubusercontent.com/84373004/119450289-84b7ba80-bce8-11eb-8560-f9aa70de6afa.png)
*Figure 1: UDF as a check constraint*
*Reference: Taken from Module07lab*

### Explain the differences between Scalar, Inline, and Multi-Statement Functions.

There are 3 types of UDFs, scalar, inline table-value, and multi-statement table-value. Both inline and multi-statement are table-value meaning they return tables as outputs while scalar functions return a single value. The difference between inline and multi-statement is multi-statement can accept more than one statement. 
The 3 types also differ in their syntax. For scalar, there needs to be a return/end block and the schema name must be included, see Figure 2a. For inline, there is no return/end block, see Figure 2b. For multi-statement, there needs to be a return/end block, see Figure 2c.

![Figure 2a](https://user-images.githubusercontent.com/84373004/119450364-a153f280-bce8-11eb-8e46-dc7d75128df9.png)
*Figure 2a: Scalar function example*
*Reference: Taken from Module07 demo*

![Figure 2b](https://user-images.githubusercontent.com/84373004/119450367-a153f280-bce8-11eb-943c-9c954886d1cc.png)
*Figure 2b: Inline function example*
*Reference: Taken from Module07 demo*

![Figure 2c](https://user-images.githubusercontent.com/84373004/119450369-a1ec8900-bce8-11eb-9909-6dcbe6c364d8.png)
*Figure 2c: Multi-statement function example*
*Reference: Taken from Module07 demo*

### Summary

To recap, Module 07 focuses on the different types of functions and this paper specifically addresses UDFs, when they are used and the different types of UDFs.
