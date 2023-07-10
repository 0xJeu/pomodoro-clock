# Pomodoro Clock

<img width="649" alt="Screenshot 2023-06-19 at 2 03 04 PM" src="https://github.com/0xJeu/pomodoro-clock/assets/129988927/952d18a3-4b38-4f78-b58c-f30464390cb3">

# Pomodoro Timer

This Python code implements a Pomodoro Timer using the Tkinter library. The Pomodoro Technique is a time management method that uses a timer to break work into intervals, traditionally 25 minutes in length, separated by short breaks.

## How It Works

- The code creates a graphical user interface (GUI) window using Tkinter.

- It defines constants for colors, font, and time intervals.

- The `clock_reset()` function cancels the current timer and resets the UI elements to their initial state.

- The `start_button_clicked()` function is called when the "Start" button is clicked. It calculates the duration of the current interval (work time, short break, or long break) and calls the `count_down()` function.

- The `count_down()` function handles the countdown mechanism. It updates the timer display and starts a recursive call to itself using `window.after()` until the countdown reaches zero. When the countdown ends, it calls `start_button_clicked()` again and updates the checkmark labels.

- The GUI layout consists of a canvas to display the timer, buttons for starting and resetting, and labels for the timer status and checkmarks.

## How to Use

To use this code, follow these steps:

1. Make sure you have Python installed on your system.

2. Import the necessary modules (`tkinter` and `math`).

3. Copy the provided code into a Python file (e.g., `pomodoro_timer.py`).

4. Save an image file named "tomato.png" in the same directory as the Python file. This image will be displayed in the GUI.

5. Open a terminal or command prompt and navigate to the directory where the Python file is saved.

6. Run the Python file using the command: `python pomodoro_timer.py`.

7. The Pomodoro Timer GUI window will open.

8. Click the "Start" button to start the timer.

9. Click the "Reset" button to reset the timer.

10. The timer will cycle between work time, short breaks, and long breaks according to the Pomodoro Technique.

## Acknowledgments

This code demonstrates the implementation of a Pomodoro Timer using Tkinter. Feel free to modify and customize it according to your preferences and requirements.
