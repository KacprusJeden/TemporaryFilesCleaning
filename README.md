# TemporaryFilesCleaning

This Python script automatically deletes temporary files and folders from the %TEMP% directory of the current user on Windows. This helps to free up storage space and improve system performance.

## Installation
#### Clone Repo
git clone https://github.com/KacprusJeden/TemporaryFilesCleaning.git   
cd TemporaryFilesCleaning
#### Optional - create and activate virtual environment
python -m venv venv  

## Running
python main.py


Script:   
 - Identifies the user's temporary directory (%TEMP%)
 - Goes through all the files and folders in that directory
 - Tries to delete every file and folder
 - Ignores files/folders that are currently in use or cannot be accessed

## Warning
- Some temporary files may be used by other processes and will not be deleted.
- The script is designed for Windows systems; It does not work on other operating systems.
