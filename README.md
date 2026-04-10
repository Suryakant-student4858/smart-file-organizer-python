# Smart File Organizer

A Python automation script that automatically organizes files into categorized folders.

## Features

- Scans a directory and sorts files by type
- Supports images, videos, audio, documents, code, archives, data, fonts, and executables
- Handles duplicate filenames safely
- Generates timestamped logs
- Produces a summary report after each run
- Includes dry-run mode for previewing changes
- Handles permission errors and invalid paths gracefully

## Technologies Used

- Python
- pathlib
- shutil
- logging
- argparse

## How to Run
python task1_automation_script.py

Run with a custom folder: python task1_automation_script.py --path /your/folder
Example Use Cases
Organizing Downloads folder
Cleaning desktop files
Managing project assets
Sorting media files automatically
Future Improvements
GUI version
File type detection using MIME types
Automatic scheduling
Cloud storage integration
