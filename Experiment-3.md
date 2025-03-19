Experiment-3
Use vim, nano to edit the editing_final_lab_file.txt file. Use the lab_file shell 
variable. Enter the visual mode of vim. Remove the last seven characters from the 
first column on the first line. Preserve only the four characters of the first column.

Approach-
Use vim or nano to open editing_final_lab_file.txt using the lab_file shell variable.
In vim, enter visual mode, highlight the last seven characters of the first column on the first line, delete them, and keep the first four characters intact.

![image](https://github.com/user-attachments/assets/9ac5d4a3-9c5f-4e8d-aeec-fee27d9aa02d)
after entering the vim, entered the following text.
![image](https://github.com/user-attachments/assets/50d68dc4-611f-4c6b-8066-d9b776edf845)
Used d to delete the highlighted characters.
![image](https://github.com/user-attachments/assets/2abf5193-ccd6-4309-b856-122adf133022)
used d$ to elete everything from the cursor to the end of the line.
![image](https://github.com/user-attachments/assets/5b04a47b-223a-4df0-b6fd-925b91c5d308)
using nano command
![image](https://github.com/user-attachments/assets/96970c13-4b24-4f82-8bde-be2b791b7ced)
after doing the changes
![image](https://github.com/user-attachments/assets/3e5fcf23-566e-47fa-aa6d-3be2093c218c)

commands used
lab_file="editing_final_lab.txt"
echo $lab_file
vim $lab_file
nano $lab_file

