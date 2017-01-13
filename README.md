# Xcode-python
How to use Xcode IDE for Python development

Open Xcode and start with creating a new project:
From the templates, choose Cross-platform > External Build System
Give it a name. You can update Organizatin Name and Identifier if you want.
Make sure you enter a correct path for Python bin. For Python 3.x it's usually `/usr/bin/pythonw`.
Click Next and save it.
Open scheme editor, select Run from the left hand pane, and Info tab from the detail pane.
From Executable menu, select Other... and navigate to where your Python executable binary is locate. That's the same location you entered in step 4, e.g. `/usr/bin/pythonw`. You can also use Shit + Command + G and paste the address in the dialog box.
Uncheck Debug executable box.
Still in Run menu, select Arguments tap, and add a new entry to Arguments Passed on Launch. This is the name of the file where you'll write your Python code in it. You'll create the file later.
Still in Run menu, select Options tab, and check the box for Use custom working directory. Enter the path to the directory where you have saved your project.
Close scheme editor. 
In Xcode navigation pane, under your project, add a new file. Select Empty from the templates.
Make sure the target is check and that you save the file in the same directory where the project file is located.
Now you can start writing Python code: 

Run it!
