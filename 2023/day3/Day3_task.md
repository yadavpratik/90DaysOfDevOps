#90DaysOfDevOps

Basic of linux

Some usefull linux command for day-2-day activities.

1.linux command to view what’s written in a file.

Command : 
$cat [file_name] or $less [file_name]

2. To change the access permissions of files.

Command: $chmod 777 [file_filename]

3. To check which commands you have run till now.

Command: $history


4. To remove a directory/ Folder.

To remove file
Command: $rm [file_name]

To remove directory 
Command: $rmdir [dir_name]


5. To create a fruits.txt file and to view the content.

To create file fruits.txt
Command:
$echo fruits.txt
or
$vim fruits.txt

To view content
Command:
$cat fruits.txt
or
$less fruits.txt


6. Add content in devops.txt (One in each line) - Apple, Mango, Banana, Cherry, Kiwi, Orange, Guava.

Command: 
$echo -e "Apple\nMango\nBanana\nCherry\nKiwi\nOrange\nGuava" >> devops.txt

This command uses the echo command to print the specified string to the terminal, and the -e option tells echo to interpret backslash escapes (such as \n for a newline). The >> operator appends the output to the file "devops.txt" rather than overwriting it.


7. To Show only top three fruits from the file.

Command :$head -n 3 [file_name]


8. To Show only bottom three fruits from the file.

Command: $tail -n -3 [file_name]


9. To create another file Colors.txt and to view the content.

To create file
Command :
$echo Colors.txt

or

$vim Colors.txt

Command:
To view file

$cat Colors.txt

or

$less Colors.txt


10. Add content in Colors.txt (One in each line) - Red, Pink, White, Black, Blue, Orange, Purple, Grey.

Command:

$echo -e "Red\nPink\nWhite\nBlack\nBlue\nOrange\nPurple\nGrey" >>colors.txt

The -e flag tells the echo command to interpret backslash escapes, so that the newline character is recognized


11. To find the difference between fruits.txt and Colors.txt file.
Command:
$diff fruits.txt Colors.txt
