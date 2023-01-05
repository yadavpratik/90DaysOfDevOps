#90DaysOfDevops

Basic of Linux

1.What is linux?

Linux is a free and open-source operating system that is widely used for running servers, desktops, smartphones, and other devices. Linux is known for its stability, security, and flexibility, and it can be customized to meet the needs of different users and environments. It is used in a variety of settings, including home computers, enterprise servers, scientific research, and Internet of Things (IoT) devices.

Basic linux commands:

2.What is the linux command to Check your present working directory.

pwd command is mainly used to check current working directory.

Syntax:
 $pwd

3.What is the linux command to List all the files or directories including hidden files.

ls command is used to list the all item present in current directory.

Syntax:
 $ls

ls-l(list in long format) command is used to list the item or file present in directory with extra information.

Syntax:
 $ls-l

List files in long format including hidden files
Type the ls -l -a or ls -a -l or ls -la or ls -al command to list files or directories in a table format with extra information including hidden files or directories:

Syntax:
 $ls-la

or

 $ls-al

4.Create a nested directory A/B/C/D/E

mkdir command is used to create a directory.

Syntax: 
 $mkdir [directory_name]

generally you have to use the mkdir command several times to create nested directory. However, there is a faster way to do this.

Command:
 $mkdir -p A/B/C/D/E

The -p flag tells the mkdir command to create the main directory first if it doesn’t already exist. The words in the brackets are part of the “brace expansion list”. Each of the items in the brace expansion list is appended separately to the preceding path (A/).








