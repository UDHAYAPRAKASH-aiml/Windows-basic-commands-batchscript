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


<img width="409" height="58" alt="Screenshot 2025-11-03 113044" src="https://github.com/user-attachments/assets/477b227f-c81c-4db9-90be-fcb47f9892f1" />


## COMMAND AND OUTPUT

Remove the directory "my-folder"


<img width="405" height="108" alt="Screenshot 2025-11-03 113057" src="https://github.com/user-attachments/assets/85ce4a23-88d9-4e3e-9f5f-8997355f0d3c" />


## COMMAND AND OUTPUT


Create the file Rose.txt


<img width="735" height="349" alt="Screenshot 2025-11-03 113222" src="https://github.com/user-attachments/assets/23dfe898-5fa8-4a68-ba74-470c9b7c280f" />

## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection


<img width="603" height="121" alt="Screenshot 2025-11-03 112937" src="https://github.com/user-attachments/assets/ac56590a-240b-49f1-b2e5-43cb88282605" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt


<img width="619" height="150" alt="Screenshot 2025-11-03 112942" src="https://github.com/user-attachments/assets/db841a93-e7b3-4937-a6d1-87dd7dc099ff" />

## COMMAND AND OUTPUT

Remove the file hello1.txt


<img width="485" height="229" alt="Screenshot 2025-11-03 112948" src="https://github.com/user-attachments/assets/0ffa369a-b24a-45f2-b101-b5b051140dc8" />

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory


<img width="485" height="229" alt="Screenshot 2025-11-03 112948" src="https://github.com/user-attachments/assets/aac83f22-0bdf-4843-9876-d41eff0ac6d0" />

## COMMAND AND OUTPUT

List out all the associated file extensions 


<img width="934" height="1062" alt="Screenshot 2025-11-03 112956" src="https://github.com/user-attachments/assets/5b4b2e01-8f8f-4c9a-a567-345c0a2c8556" />

## COMMAND AND OUTPUT




Compare the file hello.txt and rose.txt


<img width="570" height="197" alt="Screenshot 2025-11-03 113404" src="https://github.com/user-attachments/assets/3908ea8d-2739-4e57-8fdd-1fdd2f4f9811" />

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".
## OUTPUT



<img width="421" height="103" alt="Screenshot 2025-11-03 113832" src="https://github.com/user-attachments/assets/8d633f85-ff9b-4a0d-823f-d857021cd389" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="560" height="245" alt="image" src="https://github.com/user-attachments/assets/5c6b1004-9335-4631-8867-3ca067744756" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.


<img width="560" height="181" alt="image" src="https://github.com/user-attachments/assets/a72c2598-ce0e-4bb0-a254-2ffbaa499f51" />





## OUTPUT

<img width="550" height="190" alt="Screenshot 2025-11-03 113014" src="https://github.com/user-attachments/assets/363f9540-f7f8-4474-8402-fdd4b3c1ed62" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="560" height="78" alt="image" src="https://github.com/user-attachments/assets/3e1ccc11-5ab9-4b36-99aa-60e5aaaba853" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="448" height="519" alt="image" src="https://github.com/user-attachments/assets/deec53c7-7af5-4dc0-aac4-5cdeb123a981" />




# RESULT:
The commands/batch files are executed successfully.
