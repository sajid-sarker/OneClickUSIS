# OneClickUSIS
A simple web scraping app that checks if seats are available for selected courses on USIS

First create a .txt file and name it "course_input.txt".

Type the course and the intended section with a space between them. Each course should should be in a new line.
Separate the desired section numbers by spaces. Leave blank to search for all sections.

Sample:

![image](https://github.com/user-attachments/assets/3ae8cc8e-477d-4712-a31c-680996d7e8a6)


Make sure the txt file is in the same directory as the program.

Possible changes:
1. The default interval between checks is 90 seconds. That can be changed in the main function.
   
2. If you wish to show extra data, uncomment the selected info code in the named tuple and in the check availability function.
