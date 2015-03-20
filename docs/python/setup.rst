****************************
Setting up Finch with Python
****************************

This page will describe how to set up your computer to program the Finch
robot with Python.

==============
Install Python
==============

If you have not already done so, you will need to install the Python interpreter
on your computer.  If you are not sure whether you have Python installed on your 
computer, search for "Python" via Spotlight search on the Mac (Cmd + space) or via the search
on Windows (Windows key).  If the Python command line program does not show up, you
probably do not have Python installed.

Go to the `official Python downloads page <https://www.python.org/downloads/>`_ to
download Python for your platform.  You can download either a 2.7 or a 3.x version, 
since the Finch Python code indicates it has been tested on both.  Whichever version
you download, make sure you look at the correct  version of the documentation when 
you are looking for help programming in Python.

==============================
Download Finch Python Files
==============================

You will need to download the Finch Python software package.  The same package supports
Windows, Mac OSX, and Linux because it contains libraries compatible with each of those
platforms.  The package is just a zip file containing python files and dynamic libraries
which communicate with the Finch Robot over USB.  The BirdBrain Robot Server is **not**
required for programming the Finch with Python.

For Windows, Mac, or Linux, download `the Finch Python package <https://dl.dropboxusercontent.com/u/9303915/FinchPython120.zip>`_.  If that link is broken or out of date, find the most
current link from `the Finch robot downloads page <http://www.finchrobot.com/downloads>`_.

==============================
Unzip the Finch Python Package
==============================

Once you've downloaded the Finch Python package, open the containing directory in Finder/Explorer
and extract the zip file.  You may want to move the directory containing the Finch Python package
into your *Documents* or *My Documents* directory.

==============================
Running Python Programs
==============================

Option 1 (Easy): Use IDLE (Python Integrated DeveLopment Environment)
	Open the directory containing the Finch Python files in Explorer/Finder, and then right-click the
	file to "Edit with IDLE" or "Open with IDLE".

	Alternatively, open the IDLE program on your computer, and then select, "File" -> "Open", and navigate
	to the Python file you would like to open.  You can edit files in the provided text editor and run
	them via "Run" -> "Run module".

Option 2 (Harder): Use Terminal Application
	Once you've unzipped the Finch Python package, open the "Terminal" program in Mac OSX or the 
	"Command Prompt" in Windows.  Navigate to the directory containing your Finch Python files.
	Use "cd" (Mac OSX) or "CD" (Windows) to change directories in these programs.  For example,
	in Windows,

		CD Documents\\CoderDojo\\FinchPython120\\

	Or for Mac OSX

		cd Documents/CoderDojo/FinchPython120/

	Then, once you are in that directory in your terminal application, type "python" followed by 
	the name of the python file you would like to execute to execute a python program.  For example:

		python musicexample.py

========================
Getting Help with Python
========================

There are plenty of great resources out there on the web for learning to program in Python.
See `the official Python documentation page <https://www.python.org/doc/>`_ for a starting point.

In addition, since Python is an interpreted language, you can run the interpreter and type
commands interactively to see what they do.  Within the interpreter you can also use the *help* 
function on Python modules, classes, functions, and objects to learn more about what they do. 

Finally, if you have a specific question about how to do something in Python, chances are
somebody has already asked that question on StackOverflow or some similar site.  Just do
a google search for your question and see what you can find.

===============
Other Resources
===============

See the `official Finch Python page <http://www.finchrobot.com/software/python>`_ for more information on using Python to program the Finch.

Also see `this page <http://www.finchrobot.com/Creating%2C%20Compiling%2C%20and%20Running%20Programs%20for%20Finch/compiling-python-programs>`_
on running your Python Finch programs, which covers Windows, Mac OSX, and Linux.