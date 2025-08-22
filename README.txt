=========================================================
README — Required Python Libraries and Installation Guide
=========================================================

These scripts process JSON/CSV files and plot data. To run these scripts 
on Windows, you need to install the following Python libraries:

---------------------------------------------------------
Required Libraries
---------------------------------------------------------
1. pandas        — For reading and handling CSV data
2. numpy         — For numerical calculations
3. matplotlib    — For plotting graphs
4. plotly        — For interactive charts
5. tkinter       — For Tcl/Tk GUI toolkit

---------------------------------------------------------
Installing Python
---------------------------------------------------------
1. Download and install Python (Windows installer):
   https://www.python.org/downloads/windows/

2. After installation, verify installation by opening "Command Prompt" 
   and run:python --version

   You should see the installed version.

---------------------------------------------------------
Installing Python Libraries
---------------------------------------------------------
Once Python is installed, use pip to install the libraries.

   py is the Python launcher

   -m tells Python to run a module as a script, instead of just 
   looking for a .py file

Open Command Prompt or PowerShell and run:

    py -m pip install pandas numpy matplotlib plotly

---------------------------------------------------------
(Optional) Verifying Installation
---------------------------------------------------------
1. Run Python from the command line:
   
   python

2. At the >>> prompt, type:

   >>> import pandas, numpy, matplotlib, plotly, tkinter
   >>> print("All libraries imported successfully!")

3. If you see no errors, you’re ready to run the scripts.

---------------------------------------------------------
Running the Provided Python Script
---------------------------------------------------------
1. Save the script as e.g. "example.py".
2. Place any files that the script will open such as "output.csv" 
       in the same folder.
3. Double-click the .py file to auto-run the script.

Optionally, if you want to view or change the code, open IDLE.

4. Click File -> Open...
5. Select the file to open.
6. When the .py file is opened, change any values necessary. 
7. Hit F5 to run or Click Run -> Run Module in the toolbar.

=========================================================

