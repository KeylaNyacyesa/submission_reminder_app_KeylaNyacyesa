# submission_reminder_app_KeylaNyacyesa
Summative

# Submission Reminder App

## Overview
An application that uses shell scripting to provide an organized environment for tracking and reminding students about submission deadlines.

## Directory Structure

submission_reminder_Keyla/
├── app/
│   └── reminder.sh
├── assets/
│   └── submissions.txt
├── config/
│   └── config.env 
├── modules/
│   └── functions.sh
├── startup.sh
└── create_environment.sh

## Prerequisites
- Unix-like operating system (Linux)
- Bash shell
- Git


## Script Functionality

The startup.sh script performs the following actions:

Prints a message indicating the start of the submission reminder application.

Calls and executes reminder.sh located in the app/ directory.

Prints a success message upon execution.

## Usage

1. Start the application
   bash startup.sh
   

2. Verify execution permissions
   bash
   chmod +x startup.sh app/reminder.sh modules/functions.sh

   

## File Format Requirements

### submissions.txt
Ensure your student records follow this format:

student, assignment, submission status
   

## Troubleshooting
- Ensure all scripts have execution permissions
- Ensure all scripts have proper file formats

## Author
Keyla
