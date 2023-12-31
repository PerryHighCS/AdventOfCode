# Advent-of-Code Java Template for GitHub Codespaces
This is a template to aid in solving Advent of Code puzzles in Codespaces.

# To Use
In order to download your input files, you will need to update the environment
variables. [See this documentation](https://docs.github.com/en/codespaces/managing-codespaces-for-your-organization/managing-secrets-for-your-repository-and-organization-for-github-codespaces#adding-secrets-for-a-repository)
to create a YEAR variable with the year being solved (AOC_YEAR=2023) and your 
session cookie (AOC_SESSION=5FC3BD23.....) 

[This picture shows the current steps to get your session cookie from the web inspector for adventofcode.com](https://github.com/PerryHighCS/AdventOfCode/blob/master/SessionCookie.png)

Each __Day*XX*Solution__ class has a main method which will run your solutions.
Solutions come in 3 parts:

1. prepare

    Each class has a prepare method that will receive your input file for the 
    day. This is where you should parse that input into a form you can use.
    
2. part1

    The part1 method should solve the first part of the problem for the day.
    It should return the solution as a String.
    
3. part2

    Once part1 is solved, part 2 should solve the second part of the problem.
    It should return the solution as a String.

If you want to try your solution against the sample input provided in the
problem description, you need to copy it into a file in a folder named
__input/sample/day*XX*/__ where **_XX_** is the day number with a leading 0 if necessary
(01 for Dec 1st). Name the file whatever you want, but put the name in the
**SAMPLE_INPUT_FILENAME** String for the proper __Day*XX*Solution__ class.
