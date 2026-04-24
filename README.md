# Automatic File Sorter

Automatically sort files in the Downloads folder by file extension.

## Description

This Python script organises files in the Downloads folder by their file extension. Each file is moved into a corresponding folder based on its type.

If a folder for a specific file type does not exist, the script will automatically create a new folder and move the file into it.

The script can be scheduled to run using Windows Task Scheduler, allowing users to control when the script runs.

## Prerequisites

- Python 3.12+ installed  
- Ensure Python is added to PATH during installation  

## Installation

### Option 1: Download ZIP
1. Go to the repository: https://github.com/Izers0/AutomaticFileSorter  
2. Click the green **Code** button  
3. Select **Download ZIP**  
4. Extract the ZIP file to a folder on your computer  

### Option 2: Clone with Git
In the terminal, run:

```bash
git clone https://github.com/Izers0/AutomaticFileSorter.git
```

## Dependencies

If an issue arises with the script not running, you may need to install `plyer`.

In the terminal, run:

```bash
python -m pip install plyer
```

## Notes

- Currently only designed for Windows (Task Scheduler support)  
- Linux and macOS support may be added in the future  
