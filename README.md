# Pomodoro Timer
This Python-based Pomodoro timer uses the Tkinter library to provide a simple and intuitive GUI for managing work and break intervals.

**Overview**

This Pomodoro Timer is a productivity tool built using Python and Tkinter. It helps users manage their time effectively by implementing the Pomodoro Technique, which alternates work intervals (25 minutes) with short breaks (5 minutes). The graphical user interface (GUI) is simple and intuitive, making it easy to start, pause, and reset the timer as needed.

**Features**

Start and Reset Buttons: Easily control the timer with start and reset functionalities.
Work and Break Intervals: Automatically switches between work and break periods, with customizable durations.
Visual Countdown: Displays a countdown timer for the current session.
Session Indication: Visually indicates whether it's a work or break session.
Sound Notification: Alerts the user when it's time to switch between work and break intervals (optional feature).

**Usage**

- Start the Timer: click the "Start" button to begin the countdown for the work interval.
The timer will automatically switch to a break interval when the work period ends.

- Reset the Timer: click the "Reset" button to stop the current session and reset the timer to its initial state.

**Customization**

You can customize the duration of work and break intervals by modifying the respective variables in the main.py file:

WORK_MIN = 25  # Duration of work interval in minutes
BREAK_MIN = 5  # Duration of break interval in minutes

**Acknowledgments**

Inspired by the Pomodoro Technique created by Francesco Cirillo.
Developed using Python and the Tkinter library.
