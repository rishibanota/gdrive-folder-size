# Google Drive Folder Size Calculator

Calculate the total size of a Google Drive folder (including subfolders).

## Features
- Works with folder links
- Recursively calculates size
- Shows total files and folders
- Supports shared drives

## Installation

pip install -r requirements.txt

## Setup

1. Create Google Cloud project
2. Enable Google Drive API
3. Download credentials.json
4. Place it in project folder

## Usage

python sizecalculator.py "GOOGLE_DRIVE_LINK"

Example output:

Name: My Folder
Size: 12.5GB
Files: 320
Folders: 45
