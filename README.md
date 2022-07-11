# DESIGNING-A-STOP-WATCH

Generally, we are all aware of the stopwatch. There is a possible way to create a stopwatch in python. Do you know how it is? We understand that the datetime module is already available in python. Making use of that module, we can create a stopwatch in python
We will learn to design a stopwatch in two different ways. They are

Using Tkinter
Without using Tkinter

Tkinter is a package that is very much useful in python. It is the standard python interference to GUI tool kit. If you want to check whether the Tkinter is correctly installed on your system,It will open some simple Tk interference to let you know that the Tkinter is properly installed. Now let us make use of the Tkinter module to design a stopwatch in python.
Why datetime module is important to a create stopwatch in python?

The DateTime module provides time objects that are similar to the Time objects. A date in Python is not an object, but we can import a module “datetime” to get a date and time. By using the date time and Tkinter module, we are going to design a stopwatch in python.
Code to create a simple stopwatch in python without Tkinter

Import time module to get the time objects. Create a while loop. Inside while loop creates try block that has some set of codes to run the stopwatch. While we press to enter, the stopwatch gets started and run until the user enters ctrl+c. After pressing enter user has to understand that stopwatch has begun. So that we give a print statement as stopwatch has started. We are creating another while loop to return the time elapsed during the run time.

We need to import the Tkinter module to create a stopwatch in python. Next to import the datetime module to get a time. Declaring count as global and initializing count as zero.

Create a class named stopwatch in python code. After creating a class, create a function to perform a reset operation. This function will reset the timing as 00:00:00, which is similar to restart the stopwatch.


Next, create a function named start to start the stopwatch. This function is helpful to start the stopwatch.

We need a stop function to stop the stopwatch. So we need to create another function named stop to perform the stop operation in the stopwatch.
