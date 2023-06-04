# CLOCK
The code starts by importing the necessary modules.
The first module is the tkinter library, which provides basic functionality for creating graphical user interfaces (GUIs).
Next, the strftime function is imported to retrieve system time.
Next, a window is created and given a title of “Clock.”
A function called time() is then created to display the current time on the label widget.
This function uses the strftime() function to format the time string according to system conventions.
The last part of this code sets up styling for the label widget so that it will look nicer.
Finally, an instance of Label is created and placed at the center of the window.
The time() function is executed, and your output should look like this: Clock: Tue Dec 12 08:00:00 2016
The code creates a window and assigns it the title “Clock”.
The time() function is then called to display the current time on the label widget.
The lbl.config() function is used to set the text of the label widget.
The after() function is used to delay displaying the time for 1000 milliseconds.
Finally, the style of the label widget is modified with lbl.pack().
