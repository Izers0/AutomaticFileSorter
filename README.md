Automatic File Sorter
Automatically sort files in the download folder by file extension

Description
This Python script organises files in the downloads folder by their file extension. Each file is moved into a corresponding folder based on its type. If a folder for a specific file type does not exist the script will automatically create a new folder and move the file into it. The script can be scheduled to run using Windows Task Scheduler allowing users to control when the script is run.

Prerequisites
Python 3.12+ installed
Ensure Python is added to PATH during installation

Installation
Option 1: Download ZIP
Go to the repository: https://github.com/Izers0/AutomaticFileSorter
Click the green Code button
Click download ZIP
Extract the ZIP file to a folder on your computer

Option 2: Clone with Git:
In the terminal, run: git clone https://github.com/Izers0/AutomaticFileSorter.git

Dependencies
If an issue arises with the script not running, you may need to install plyer:
In the terminal, run: python -m pip install plyer

Note
Currently only designed for Windows (Task Scheduler Support)
Linux and macOS support may be added in the future

