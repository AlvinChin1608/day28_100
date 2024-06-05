# day28_100
I am currently engaged in a 100-day Python Bootcamp, which I am documenting and sharing my progress on GitHub. The boot camp is designed to progressively intensify, allowing me to deepen my understanding and proficiency in Python programming.

Additionally, I have chosen to include the beginner, intermediate and advanced in my documentation to provide a valuable reference for my future growth and development.

------------------
# TKinter Break Timer Project
## Overview
In this project, I created a break timer application using Python's Tkinter library. The application is designed to help users manage their work and break intervals effectively. The timer follows the Pomodoro technique, providing 25 minutes of focused work followed by a 5-minute break, and a longer break after four work sessions.

## Key Learnings
**TKinter Basics**
- __Creating a Window:__ Used __Tk()__ to initialize the main application window.
- __Setting Window Properties:__ Configured the window title, size, and background color using methods like __title()__, __minsize()__, and __config()__.

**Widgets and Layout**
- __Labels:__ Used Label widgets to display static text and dynamic countdowns. Learned to customize labels with different fonts, colors, and alignments.
- __Canvas:__ Utilized a Canvas widget to display images and text. This was particularly useful for creating a visually appealing timer display.
- __Buttons:__ Added Button widgets to start and reset the timer, associating them with command functions to handle user interactions.
- __Grid Layout:__ Employed the __grid()__ method to place widgets in specific rows and columns. This helped in organizing the layout effectively.
  - Note: Pack() would put everything together, so it would display but not with grid(). Is either this or that.. or it won't work
**Timer Mechanism**
- __Global Variables:__ Used global variables to track the number of repetitions (reps) and manage the timer state.
- __Timer Logic:__ Implemented the core timer functionality using a combination of methods:
  - __count_down():__ A recursive function to handle the countdown logic, updating the timer display every second.
  - __start_timer():__ Managed the work and break intervals, updating the label to reflect the current session (work, short break, long break).
  - __reset_timer():__ Stopped the current timer, reset the display, and cleared any progress marks.

**Advanced Tkinter Usage**
- __Dynamic Label Updates:__ Learned to update label text dynamically using the __config()__ method.
- __Canvas Updates:__ Used __itemconfig()__ to change the text on a Canvas widget during the countdown.
- __Callbacks and Timing:__ Leveraged __window.after()__ to create non-blocking delays for the countdown function, allowing the GUI to remain responsive.





