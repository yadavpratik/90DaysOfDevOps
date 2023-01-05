#90DaysOfDevOps

Linux Shell Scripting for DevOps Engineers.

What is Kernel?
the kernel is the central part of an operating system that manages the system’s resources and communicates with hardware. 

What is shell?
A shell is a command-line interpreter that allows users to interact with an operating system by entering commands as text.
The shell is a program that reads commands from the user and executes them.
It is a user interface to the operating system, and it is often one of the first programs a user interacts with when using a computer.

What is shell scripting?
A shell script is a computer program designed to be run by a Unix shell, a command-line interpreter. The various dialects of shell scripts are considered to be scripting languages. Typical operations performed by shell scripts include file manipulation, program execution, and printing text.

1. What is Shell Scripting for DevOps.

In the context of DevOps, shell scripting is often used to automate tasks, such as deploying code, running tests, and managing infrastructure.
Shell scripts can be used to build, deploy, and test software, as well as manage servers and other infrastructure components.
They are a powerful tool for automating tasks and streamlining workflows in a DevOps environment

2. What is #!/bin/bash? can we write #!/bin/sh as well?

#!/bin/bash is called a shebang and it is used to specify the path to the interpreter for the script. The script will be executed by the interpreter specified after the shebang.

In this case, #!/bin/bash specifies that the script should be executed with the bash interpreter. bash is a Unix shell and command language.

Yes, we can also use #!/bin/sh as the shebang. sh stands for the Bourne shell, which is a Unix shell that was one of the first Unix shells. It is still widely used as a default shell on many systems.

So, if you use #!/bin/sh as the shebang, the script will be executed with the sh interpreter

3. Write a Shell Script which prints I will complete #90DaysOofDevOps challenge.
Here is a simple shell script that prints the message "I will complete #90DaysOofDevOps challenge"

```#!/bin/bash
echo "I will complete #90DaysOofDevOps challenge."```

To run this script, save it to a file with a .sh extension (e.g. 90DaysOofDevOps.sh) and make it executable using the chmod command:

`chmod +x script.sh`

Tu run the above script execute below command:

`./script.sh`

4. Write a Shell Script to take user input, input from arguments and print the variables.

Here is a shell script that takes user input, input from arguments, and prints the variables:

```
#!/bin/bash

# Take user input and assign it to a variable
echo "Enter a value: "
read userInput

# Print the variables
echo "userInput: $userInput"
```


To run this script, save it to a file with a .sh extension (e.g. input.sh) and make it executable using the chmod command:

`chmod +x input.sh`

To run the script execute below command:

`./input.sh`

5. Write an Example of If else in Shell Scripting by comparing 2 numbers

Here is an example of an if...else statement in a shell script that compares two numbers:
```
#!/bin/bash

# Get the two numbers to compare from the command line arguments
num1=$1
num2=$2

# Compare the two numbers
if [ $num1 -gt $num2 ]
then
  echo "$num1 is greater than $num2"
else
  echo "$num1 is not greater than $num2"
fi

```

To run this script, save it to a file with a .sh extension (e.g. compare.sh) and make it executable using the chmod command:

`chmod +x compare.sh`

To run script excute below command:

./compare.sh 5 10


Output:

5 is not greater than 10
