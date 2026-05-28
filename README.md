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
<img width="1099" height="55" alt="image" src="https://github.com/user-attachments/assets/78f0140a-7c98-49f2-9531-9e66bdbdc39e" />

Remove the directory "my-folder"
## COMMAND AND OUTPUT
<img width="1089" height="58" alt="image" src="https://github.com/user-attachments/assets/2c09e149-2611-456b-a190-8665b525476c" />

Create the file Rose.txt
## COMMAND AND OUTPUT
<img width="1087" height="442" alt="image" src="https://github.com/user-attachments/assets/e1874372-d1e8-40f3-a583-43b52bcdcbcd" />

Create the file hello.txt using echo and redirection
## COMMAND AND OUTPUT
<img width="348" height="82" alt="image" src="https://github.com/user-attachments/assets/6cd84be2-5461-46f9-8d26-2c19cf39ae2a" />

Copy the file hello.txt into the file hello1.txt
## COMMAND AND OUTPUT
<img width="1101" height="111" alt="image" src="https://github.com/user-attachments/assets/f3204b31-5847-4b9d-885e-4e63200259a2" />

Remove the file hello1.txt
## COMMAND AND OUTPUT
<img width="1047" height="39" alt="image" src="https://github.com/user-attachments/assets/bf3d4f4a-59bf-44d5-900f-73fd0090c7da" />

List out the file hello1.txt in the current directory
## COMMAND AND OUTPUT
<img width="1073" height="220" alt="image" src="https://github.com/user-attachments/assets/48eb5ddb-576d-4ca1-9862-f335b3f97fab" />

List out all the associated file extensions 
## COMMAND AND OUTPUT
<img width="1015" height="455" alt="image" src="https://github.com/user-attachments/assets/a86a8125-af9d-4c32-8529-f9420b22ef52" />

Compare the file hello.txt and rose.txt
## COMMAND AND OUTPUT
<img width="1102" height="257" alt="image" src="https://github.com/user-attachments/assets/4a3231cc-9b27-4544-b6a2-0d0a7592db41" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".
## OUTPUT
<img width="970" height="90" alt="image" src="https://github.com/user-attachments/assets/b33f7fb1-b390-4e1f-a288-f22807bcc0fc" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.
## OUTPUT
<img width="1036" height="286" alt="image" src="https://github.com/user-attachments/assets/b581ec5b-32be-40b2-b254-a6bbe8d182da" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.
## OUTPUT
<img width="982" height="217" alt="image" src="https://github.com/user-attachments/assets/3d7ad344-fa28-42e8-beec-fa63dfdea9d8" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="1096" height="407" alt="image" src="https://github.com/user-attachments/assets/c6cb3bff-2733-402d-9355-57649dbbf2bb" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.
## OUTPUT
<img width="925" height="470" alt="image" src="https://github.com/user-attachments/assets/6098d4d2-36a6-49ca-a6f7-347615134663" />



# RESULT:
The commands/batch files are executed successfully.

