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

## COMMAND AND OUTPUT

<img width="677" height="52" alt="image" src="https://github.com/user-attachments/assets/3443e302-5ab5-46f5-b12a-7569a16b6349" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="770" height="55" alt="image" src="https://github.com/user-attachments/assets/cbda3f4a-7c77-464a-82e0-25e68aa98ada" />

Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="948" height="161" alt="image" src="https://github.com/user-attachments/assets/8471b178-6d00-401d-8e03-90aefe631c27" />
<img width="882" height="237" alt="image" src="https://github.com/user-attachments/assets/ab9de350-9b0c-4243-9ab3-aae37e7e22b3" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="690" height="113" alt="image" src="https://github.com/user-attachments/assets/74f304ed-a757-4d85-b51a-fec6e5eabb71" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="851" height="82" alt="image" src="https://github.com/user-attachments/assets/c9368595-f7d2-48a1-aa7d-8f27c0f9cc9f" />

Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="680" height="48" alt="image" src="https://github.com/user-attachments/assets/cf015b9f-1e1c-4126-a41d-7eb116f7429c" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="882" height="133" alt="image" src="https://github.com/user-attachments/assets/455e9f6e-223b-4642-8189-6c6ae2f269ad" />

List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="717" height="633" alt="image" src="https://github.com/user-attachments/assets/2efb39f9-7dd3-48ad-a0c7-b845259500f7" />

Compare the file hello.txt and rose.txt


## COMMAND AND OUTPUT

<img width="905" height="187" alt="image" src="https://github.com/user-attachments/assets/81eb8d2b-ce39-45be-98cd-f67e5eeb6689" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="571" height="172" alt="image" src="https://github.com/user-attachments/assets/bf0d1593-5e50-4e01-afd4-f10514213cd2" />

Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT


<img width="655" height="237" alt="image" src="https://github.com/user-attachments/assets/74f8d20d-0d79-4a53-838d-e98bfc1bd0d7" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="511" height="190" alt="image" src="https://github.com/user-attachments/assets/48016707-9255-439e-b42e-a01993acc42d" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="477" height="95" alt="image" src="https://github.com/user-attachments/assets/f579d24d-1546-49fe-8003-242815e6e920" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="640" height="422" alt="image" src="https://github.com/user-attachments/assets/a51175ab-f278-4909-91f2-d006a1b8895c" />

# RESULT:
The commands/batch files are executed successfully.
