# Lecturer notes for Day 1

Start with an introduction of the course:

* Who I am (not too long)
* Who the participants are (show graphs)
* What's on the website
* What the course will be like
* The shared notes
* Sticky notes
* We'll have a break in the middle
* Tell me if it's too fast or too slow


## Starting Python and the Jupyter notebook

* Using the Python REPL
* Putting commands on a .py file (use print but explain later)
* About Jupyter notebook
* Starting the notebook server
* The notebook file (.ipynb)
* Edit vs command mode
* Types of cells
* Markdown primer

### Exercise

Make a notebook with:

* A title
* A markdown cell with a level 2 heading and some text (anything you want)
* A markdown cell with an image and some text
* A markdown with a nested list like so:
    1. bla
    2. meh
        * something
        * else
    3. foo
* A code cell with Python code (you can use some of things we typed before)


## Variables and data types

* Operations with integers and floating point
    * Ex: Fahrenheit to Celsius Tc = (Tf - 32)*5/9
    * Q: Do we need parenthesis around the division?
* Division
* Variables (and naming them)
    * Ex: Fahrenheit to Celsius with variables
    * Question:
        * Fill out table (in markdown) with variable values:

            x = 1.0
            y = 3.0
            swap = x
            x = y
            y = swap
* print
* Strings
* Adding and multiplying strings
* Indexing and slicing
* Lists (creating, indexing, and appending)
* Splitting strings

### Exercise

Given the variables:

    location = "City, State, Country"
    temperature_celsius = 42

Write some code that prints out:

    Current temperature:
        city: City
        country: Country
        temp. in C: 42
        temp. in F: 107.6

Use variables to store the quantities you want to print.
