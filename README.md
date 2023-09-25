# GUI Based Timer And Stop Watch System
During my Code Clause Internship Program I have created a GUI Timer and Stop Watch project where user can start the time whenever user want as well as also stop the time whenever the user want .Along with this user can also reset the time whenever he want .There are 2 buttons displayed on the display when we run the code ,i.e., Stop and reset.

//Brief Explanation of code:-


=> The Main class serves as the entry point for your program. When you run this program, it prints "Stop Watch!" to the console and then creates an instance of the myclass class, which initializes and displays the stopwatch GUI as explained in the previous response.


=> This Tiemer and stop watch Java project is a simple implementation of a stopwatch with a graphical user interface (GUI) using Java Swing. It allows you to start, stop, and reset the stopwatch. Let's go through the main components and functionality of this project:



This Java project is a simple implementation of a stopwatch with a graphical user interface (GUI) using Java Swing. It allows you to start, stop, and reset the stopwatch. Let's go through the main components and functionality of this project:

1- Imports: The code begins by importing necessary Java Swing and AWT libraries for creating the GUI and handling events.

2- Class Declaration: The myclass class is declared, which implements the ActionListener interface. This means it must implement the actionPerformed method to respond to events triggered by buttons.

3- Instance Variables:

* JFrame frame: The main window for the application.
* JButton start: A button for starting and stopping the stopwatch.
* JButton reset: A button for resetting the stopwatch.
* JLabel time: A label to display the elapsed time.
* JLabel title: A label displaying the title "STOP WATCH."
* int elapsedtime, int sec, int min, int hrs: Variables to keep track of elapsed time, seconds, minutes, and hours.
* boolean started: A flag to track whether the stopwatch is running.
* String secstring, String minstring, String hrsstring: Strings to format the time display.



4- Timer: A Timer object is used to update the stopwatch display every 1000 milliseconds (1 second). The actionPerformed method of the Timer is overridden to update the time label.

5- Constructor (myclass): The constructor sets up the GUI components, including labels and buttons, and configures their properties like font, position, and size. It also adds event listeners to the start and reset buttons.

6- actionPerformed Method: This method is called when an action event occurs, such as clicking a button. It handles button clicks for the "START" and "RESET" buttons:

When the "START" button is clicked, it either starts the stopwatch or stops it, depending on its current state.

When the "RESET" button is clicked, it resets the stopwatch.

7- Start, Stop, and Restart Methods:

start(): This method starts the timer when the stopwatch is started.

stop(): This method stops the timer when the stopwatch is stopped.

restart(): This method stops the timer and resets all time-related variables to zero when the stopwatch is reset.

8-Main Method: The code to create an instance of the myclass class is missing from your provided code. Typically, in the main method, you would create an instance of the myclass class to initialize and display the stopwatch.



This Java project creates a simple stopwatch with basic start, stop, and reset functionality in a graphical user interface. Users can interact with the buttons to control the stopwatch, and the elapsed time is displayed in the format "HH:MM:SS".
