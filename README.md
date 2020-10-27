# Seating-Arrangement-Bot
Designs seating for the Examination using UiPath

Seating Planner Bot
This bot designs the seating for different LT's with the provided seating capacites. 
The bot works in the following manner:
• It takes two input files from user which contains student data(i.e. their roll numbers) and also takes one input file that contains each room specific seating capacity.
• Post Processing it store the data at the desired directory.

Prerequisites:-
1. There should be two input files every time and should contain formatted data of student.
2. There should be an input file containing each room specific capacities in a formatted data.
3. Uipath's latest version should be installed on the system.
4. MS Excel 2003+.

Installing the Bot:-
Installing the Bot is quite simple. All you need to do is to put the nupkg package file in the provided location- "C:\ProgramData\UiPath\Packages\".

Some Main Points to keep in mind:-
1. The input files need to be formatted, .i.e., they should have roll number cell name as "Registration Number" for each sheet.(You can check out the files which have been provided with the bot.)
2. The capacity file should have room capacities on each block on a different sheet in the same excel.
3. If bot gives the following error "Error Message:- There is no data in File one and File two", no need to panic it was put there intentionally and in future will find an alternative to it.

If you find any bugs or errors make sure to take a snapshot and let us know. The bot is still in developing phase and bound to have bug.
As for the future update we would like to add the feature to make an excel with section wise seating data.
