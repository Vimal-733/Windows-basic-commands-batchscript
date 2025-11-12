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

mkdir %userprofile%\Desktop\MyLab

<img width="806" height="54" alt="Screenshot 2025-11-12 154720" src="https://github.com/user-attachments/assets/742406cd-6cfd-4cb1-9989-2c05489afa2e" />


Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="785" height="99" alt="Screenshot 2025-11-12 154742" src="https://github.com/user-attachments/assets/f2d81b85-e871-4953-add0-f6ed39c2bef3" />







## COMMAND AND OUTPUT

<img width="791" height="102" alt="Screenshot 2025-11-12 154809" src="https://github.com/user-attachments/assets/bbc92608-f7a6-4858-884a-fe7dce999317" />



Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="806" height="318" alt="Screenshot 2025-11-12 154838" src="https://github.com/user-attachments/assets/5e47ff12-565c-4081-a2fd-03c971595f47" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="812" height="99" alt="Screenshot 2025-11-12 154903" src="https://github.com/user-attachments/assets/5d2576f0-2481-4e09-b15c-720c349f55e5" />


Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="809" height="121" alt="Screenshot 2025-11-12 154926" src="https://github.com/user-attachments/assets/38916b74-0372-4978-99e6-330ccc4b1f48" />


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="802" height="199" alt="Screenshot 2025-11-12 154950" src="https://github.com/user-attachments/assets/1e787edd-5532-43f7-9c3a-d25f72a8e5df" />




## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".


# command
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```

# output

<img width="1018" height="257" alt="image" src="https://github.com/user-attachments/assets/89fc36f4-111e-4d0f-bfce-4daeb7e6dc3f" />

# command

```
  @echo off
  mkdir %userprofile%\Desktop\DocBackup
  copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
  del %userprofile%\Documents\*.docx
  echo Backup and deletion completed successfully!
```

# output

<img width="1027" height="255" alt="image" src="https://github.com/user-attachments/assets/29e37395-c002-4353-aab2-b472d34343b1" />

## result
The commands/batch files are executed successfully.

