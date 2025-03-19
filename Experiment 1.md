Experiment 1 
Use the touch command to create sets of empty practice files to use during this lab. In each set replace, replace X with the numbers 1 through 6. Create six files with names of 
the form songX.mp3, snapX.jpg and filmX.avi. Create three subdirectories for organizing your files and name the subdirectories friends, family and work. Use a single command to 
create all three subdirectories at the same time. 
Approach- Use the touch command with brace expansion to create the files and the mkdir command with space-separated names to create the directories.
![image](https://github.com/user-attachments/assets/65caf1cb-12de-44dc-9f87-3662f8985d9a)
commands used:
touch song{1..6}.mp3 snap{1..6}.jpg film{1..6}.avi
mkdir family friends work
