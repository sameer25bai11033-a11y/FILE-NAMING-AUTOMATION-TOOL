Python-based tool that automatically renames multiple files using user-defined rules like prefixes, numbering, timestamps, and extensions to maintain consistent, meaningful names. It scans folders, previews changes, avoids name conflicts, and logs operations for easy organization and efficient file management
This Python tool streamlines renaming hundreds of files quickly and consistently. Customize file names with patterns, prefixes, suffixes, numbering, timestamps, or extensions. The tool previews changes before applying, prevents duplicate names, and records each operation for reliability and transparency.

Features
Rename files in bulk, with ruleset selection
Add prefixes, suffixes, sequential numbers, and date/time stamps
Preview renaming results before committing
Automatically handles name conflicts, avoiding overwrites
Keeps an operation log for auditing
Simple command-line interface for easy use

Installation
Clone this repository

Install required packages:
bash
pip install -r requirements.txt

Usage

Launch in terminal:

bash
python file_naming_tool.py
Select your target folder and configure renaming options via prompts

Review preview, confirm changes, and finish

Example
Rename photos in "images/" to "IMG_YYYYMMDD_01.jpg", "IMG_YYYYMMDD_02.jpg", etc.
