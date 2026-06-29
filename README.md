# Corner Grocer Inventory Tracker

## Project Summary

The Corner Grocer Inventory Tracker is a C++ console application designed to analyze grocery purchase records. The program reads a text file containing items purchased throughout the day and determines how frequently each item appears. The purpose of the program is to help the Corner Grocer understand customer purchasing patterns so they can organize their produce section more effectively.

The program provides a menu that allows users to search for individual item frequencies, view a complete list of item frequencies, display a text-based histogram, and exit the application. The program also creates a backup file containing the accumulated item frequency data.

## What I Did Particularly Well

One area I did well was designing the program using object-oriented programming principles. I created a separate class to manage the grocery tracking functionality instead of placing all of the code inside the main function. This made the program easier to understand and maintain.

I also implemented file input and output successfully. The program automatically reads the provided grocery data file and creates a backup file using the calculated frequency information. Using a map structure allowed the program to efficiently store and retrieve item counts.

## Areas for Enhancement

One improvement I could make would be adding stronger input validation and error handling. The current program handles basic menu choices, but additional validation could prevent unexpected input such as incorrect data types or missing files.

I could also improve the program by adding more detailed exception handling. This would make the application more secure and reliable by allowing it to gracefully respond to runtime errors instead of relying only on normal execution.

## Most Challenging Code and How I Overcame It

The most challenging part of this project was learning how to organize the program using classes and separate header and source files. Managing the relationship between the class declaration, class implementation, and main driver required careful attention.

I overcame this challenge by reviewing examples of object-oriented C++ programs, using course materials, and testing the program frequently after making changes. Debugging errors helped me better understand how different files work together in a C++ project.

## Transferable Skills

The skills from this project that will transfer to future programming projects include:

- Designing programs using object-oriented programming
- Reading and writing data files
- Using data structures such as maps
- Creating modular and reusable code
- Writing clear comments and documentation
- Developing programs based on user requirements

These skills will apply to larger applications where data processing, organization, and maintainability are important.

## Maintaining Readability, Maintainability, and Adaptability

I made the program maintainable by separating functionality into different files and using a dedicated class. The header file defines the class structure while the implementation file contains the program logic. This organization makes future updates easier because individual sections of the program can be modified without affecting the entire application.

I also used meaningful variable names, inline comments, and consistent formatting to improve readability. These practices make it easier for another developer to understand and continue working on the program.
