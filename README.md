# Backing-up-data
# Daily Backup Script

This Python script is designed to automate the process of backing up a specified folder, such as your screenshots, to a designated backup location every day at 8 PM. It utilizes the `shutil` library for file operations and the `schedule` library to manage the timing of the backup tasks.

## Features

Automatic Daily Backups: The script schedules a daily task to copy the contents of a specified folder to a backup directory at a designated time, ensuring that you always have the latest files saved.
  
Date-Based Folder Organization: Backups are organized in folders named after the current date, making it easy to track and manage multiple backups over time.

Error Handling: The script includes error handling to manage common issues, such as attempting to copy to a directory that already exists or encountering permission issues.

## Requirements

To run this script, you'll need:

- Python 3.x installed on your machine.
- The `schedule` library for scheduling tasks. You can install this library using pip:

```bash
pip install schedule
