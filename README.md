# Building five different programs using bash interpreter script 
You can run commands in the terminal or put them in a file to be run as a script. Bash stands for bourne-again shell which sh stands for shell.

## The first program is questionnaire.sh

* This program ask user questions such as name, location and favorite website
* The program accepts inputs using READ method 
* The program prints out using ECHO method accepted input along some other sentences.
* Shebang is added as the first line in the file to show that its using bash interpreter
* Use command ./questionnaire.sh to execute the script
* If permission denied, use "chmod +x file name" to allow you execute.

## The second program is countdown.sh

* This program only accept positive numbers
* The script accept just one value, use command ./countdown.sh $1 to execute the script
* The program contdowns the positive number to zero (0) using either the for loop or while loop.
* The sleep command is set to 1 to slow down the counting of the numbers
* The building of this program demonstarte how to use flow statement in bash scripting

