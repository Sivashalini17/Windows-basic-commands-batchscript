# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.




## COMMAND AND OUTPUT
![Screenshot from 2025-05-18 22-23-52](https://github.com/user-attachments/assets/b962b586-92c1-4c4e-b947-e56f951d337c)

Remove the directory "my-folder"

## COMMAND AND OUTPUT
![Screenshot from 2025-05-18 22-25-20](https://github.com/user-attachments/assets/8f1c0595-d04b-47bd-8b51-2aa8b0801222)


Create the file Rose.txt

Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):


## COMMAND AND OUTPUT
![Screenshot from 2025-05-18 22-27-38](https://github.com/user-attachments/assets/3fd492a7-fe84-4a02-b3c0-38bfc9792735)


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
![Screenshot from 2025-05-18 22-30-15](https://github.com/user-attachments/assets/b3a28445-7a01-4081-97a5-4302bac09900)

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

![Screenshot from 2025-05-18 22-27-38](https://github.com/user-attachments/assets/77bab33c-a141-4f06-8063-23e5242f5bfe)


Remove the file hello1.txt

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## COMMAND AND OUTPUT
![Screenshot from 2025-05-18 22-31-06](https://github.com/user-attachments/assets/b9ff109b-0cf6-43be-89b7-43d76286141d)

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
![Screenshot from 2025-05-18 22-34-42](https://github.com/user-attachments/assets/76000ed3-2e62-47cc-8f07-edf064a58d44)

List out all the associated file extensions 

## COMMAND AND OUTPUT
![Screenshot from 2025-05-18 22-34-17](https://github.com/user-attachments/assets/1a893a29-fb1d-47bc-bd5d-ffeb0c30c128)


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

![Screenshot from 2025-05-18 22-40-29](https://github.com/user-attachments/assets/5e54d225-dab4-428f-8032-4857706f8841)

# RESULT:
The commands/batch files are executed successfully.
