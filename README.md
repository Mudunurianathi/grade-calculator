# grade-calculator

## Project Goal 
Problem: When I'm trying to figure out what I need on a final exam, I have to dig through the syllabus to find how much each category weighs and do the math by hand. This takes too long and is easy to get wrong, so I want a program that does it for me with fewer mistakes. It matters to me because I miscalculated this once for a class, and I don't want anyone else to go through that.

Solution: (I'm going to build a Java command-line program that takes the weighted categories of a class (like homework and exams), along with the user's current scores, and calculates the score they need on the final to reach a target letter grade. It will print that score as a number, so the user knows what they need on the final.)

## MVP Scope
Calculating the score needed on the final
Rejecting letters where numbers go 
Making sure that all the weights add up to 100%
Enter a target final grade
Enter the number of categories then each name, weight, and current score 
Print the score needed on the final

## Future Plans 
Let the user fix a mistake without restarting the program
Print a summary table of all the categories 
Multiple scores in one category

## Tech Stack
- Language: Java
- Libraries: java.util.Scanner, java.util.ArrayList, Math, String.format, NumberFormatException (Standard library only and my own Category Class)
- Data Storage: Held in memory
- Data source: User input
- Tools: GitHub

## Build Plan
1. Add Main.java to a src/ folder that prints a start message
2. Create a Category class with a name, weight, current score and getters
3. Ask for the number of categories and read each one’s name and weight into an ArrayList<Category> with scores for everything but the last one (final)
4. Reject letters and other items where there is supposed to be a number
6. Check that the weights add up to 100%
7. Convert the target letter into a percentage
8. Calculate the score needed on the final to reach the target percentage
9. Print the needed score
10. Test with the syllabus you did by hand, and then clean up the comments and README
