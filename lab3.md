**Use Vim,nano, to edit the editing_final_lab.txt file. Use the
lab_file shell variable. Enter the visual mode of Vim. Remove
the last seven characters from the first column on the first
line. Preserve only the first four characters of the first
column.**


**commands**


nano $lab_file

Press Esc (to ensure Normal Mode)

Press 0 (jump to start of first line)

Press v (start visual mode)

Press → 4 times to select first 4 characters

Press y (copy them)

Press → 7 times to move cursor after 4th char and highlight next 7 chars

Press v again if needed (Visual Mode), highlight those 7 characters

Press d (delete)

Press 0 to return to start of line

Press P (paste back first 4 characters)

esc to escape and come to normal mode tha :wq to save and exit

![Alt Text](imges/lab3.png)
