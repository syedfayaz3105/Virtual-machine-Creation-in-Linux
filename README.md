 # VIRTUAL MACHINE CREATION IN LINUX
  ## AIM
       To Install Virtualbox / VMware Workstation with different flavours of linux.
## PROBLEM STATEMENT
    Manually executing basic Linux tasks like file management, navigation, and arithmetic operations can be inefficient. This experiment aims to automate these tasks using Bash scripting, including:

1.Displaying the current directory, files, and system date.
2.Reading and displaying file contents.
3.Performing basic arithmetic operations.

## REQUIREMENTS
1.Oracle VM VirtualBox MAnager
2.Kali Linux
3.Mousepad (Text Editor)
4.Terminal

## ALGORITHM
 ### Steps 1:
 Open the terminal in Kali Linux.
 ### Steps 2:
 Use basic Linux commands to navigate and manage files.
 ### Steps 3:
 Create a Bash script using Mousepad.
 ### Steps 4:
 Write a script that performs arithmetic operations and reads a file.
 ### steps 5:
 Make the script executable.
 ### steps 6:
 Run the script and observe the output.
 
## COMMANDS
### Execute Basic Linux Commands in the Terminal
## Check the Current Working Directory
```
pwd
```
## Create a New Directory
```
mkdir my_experiment
```
## Navigate into the Directory
```
cd my_experiment
```
## List the Files in the Directory
```
ls
```
## Write Some Text into the File
```
echo "Hello, this is a test file." > myfile.txt
```
## Read the File Contents
```
cat myfile.txt
```
## Get the Current Date and Time
```
date
```
### Writing a Bash Script in Mousepad
## Open Mousepad
```
mousepad myscript.sh &
```
## Write the Bash Script
```
#!/bin/bash 

echo "Current Directory:"
pwd

echo "Files in this directory:"
ls

echo "Current Date and Time:"
date

read -p "Enter first number: " num1
read -p "Enter second number: " num2

sum=$((num1 + num2))
diff=$((num1 - num2))
prod=$((num1 * num2))
quot=$((num1 / num2))
rem=$((num1 % num2))

echo "Sum: $sum"
echo "Difference: $diff"
echo "Product: $prod"
echo "Quotient: $quot"
echo "Remainder: $rem"

```
## Make the Script Executable
```
chmod +x myscript.sh
```
## Run the Script
```
./myscript.sh
```

### REG NUMBER:212223230057
### NAME:Farhana H
## Configuration of Kali Linux on Oracle Virtual Box :

 ![421260654-7481ebf5-8edd-4cb2-87cc-e8e64ec9cafc](https://github.com/user-attachments/assets/3e41b937-cee7-48dd-a921-861cf2a871c7)
## output:

![421258284-cc481926-bcfc-4901-b74d-7f5c76beabd5](https://github.com/user-attachments/assets/cb56f5a8-36af-45d0-8935-87223b385fd1)


![421258755-ddc08a53-e155-4a5c-afa4-d4a9429696d3](https://github.com/user-attachments/assets/fb0ba605-5867-4923-a913-83e4abbe9293)


![421262652-a30e5d51-d55c-4ea1-8a39-6bc60e80b50b](https://github.com/user-attachments/assets/8de3afba-252e-44e6-84d8-df6e157bfad9)

## RESULT
Thus, this experiment helped in understanding the fundamentals of Linux commands and Bash scripting for automation and system management.

 

  


