# Tkinter Examples and Screenshots

## Tkinter Button

### Source code example

```python
import tkinter as tk

window = tk.Tk()
window.title("Button Example")
window.geometry("280x50")

btn = tk.Button(window, text="A button", fg="red", bg="yellow")
btn.pack()

window.mainloop()

```

### Screenshot
![Tkinter Button Example](tkinter_button.png "Tkinter Button Example")


## Tkinter Menu and Menubutton

## Tkinter Scale

## Tkinter OptionMenu

## Tkinter Dialogs

## Tkinter Checkbutton
```python
import tkinter as tk

window = tk.Tk()
window.title("Checkbutton Example")
window.geometry("280x50")

state = tk.IntVar()
check_btn = tk.Checkbutton(window, text="Check Button Example Blablabla", variable=state)
check_btn.pack()

window.mainloop()

```

### Screenshot
![Tkinter Checkbutton Example](tkinter_check-button.png "Tkinter Checkbutton Example")


## Tkinter LabelFrame and RationButton

## Tkinter PanedWindow

## Tkinter Canvas

# Exercise
 - Create a fork of this repository
 - Clone your fork locally
 - Add a source code example and a screenshot to one of the topics
 - Commit and push your changes to your fork
 - Create a pull request for your changes
