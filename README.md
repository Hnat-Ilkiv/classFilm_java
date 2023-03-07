# classFilm_java
Description of the task

Create a class according to your option from the list below
Using the lombok library, you should implement set and get methods, constructors with arguments, a soak constructor, and an overridden toString() method
The written class must contain a public static method getInstance(), and a static field instance, the value of which will be returned by the getInstance method
The class should also have a main method in which to create an array of class objects using the
- the default constructor
- a constructor that receives all parameters
- 2 objects received when calling the getInstance method

Print to the console the identifiers of all objects from the array using a loop with a precondition

The laboratory task should be contained in the package ua.lviv.iot.algo.part1.lab1
The task implementation should be placed in the Github repository. To do this, create a separate branch, add your classes (commit, push) and create a Pull Request
Important: when creating a Github repository, you should select .gitignore for the Java language
After adding the code to the repository, make sure that only your implementation file (file with the java extension) is in the repository
The lab file should be located in the folder ua/lviv/iot/algo/part1/lab1, which corresponds to the name of the package
The written code must meet the accepted requirements in the Java language (Java code conventions)

Option 12.

Create a Film class that will have the following fields:
title: the name of the movie;
director: director of the movie;
year: year of release of the movie;
rating: the total rating of the movie.
marks: the number of marks given to the movie

The Film class must have the following public methods:
rate(int rating): a method that adds a rating to the movie's rating (a valid rating can be in the range from 1 to 10, all values greater than 10 are considered equal to 10), with 1 increasing the number of marks;
getCurrentRating(): returns the current rating of the movie, the total rating of the movie divided by the number of ratings is determined

