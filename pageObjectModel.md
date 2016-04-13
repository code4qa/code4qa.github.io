# Creating a **Page Object Model** of Java Classes for each web page and Methods for each field, and Classes of Actions. 

In this first example I will show how to create a page objects design in Eclipse with Java and Selenium. At this stage I will not be using TestNG which adds more complexity (and features).

## Create the project structure in Eclipse or other IDE

* Create a **Base** class.
* Create the login page objects class.
* Create the classes for any pages you want to navigate to.
* Create a **Utilities** class.
* Create the login page actions class
* Create the classes for any page actions you want to perform on page objects.
* Create the class with the **Main** that runs the test.

## The Base Class

I create a base class primarily to store the selenium web driver instance and some additional variables.
One key feature of this page objects model design is that I use class variables (static) and so I do not instanciate any objects.

