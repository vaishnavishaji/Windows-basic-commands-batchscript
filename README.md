# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.
```
Developed by : Vaishnavi S.A
Register number : 212223220119
```
## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
![326433781-8d1d35dd-a285-4d32-8085-7f1b7e1e6a8b](https://github.com/vaishnavishaji/Windows-basic-commands-batchscript/assets/151444759/c36fc6df-a6c0-4c66-80e1-f66b8cb9eae1)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
![326433941-a001440f-2028-4b29-a1cb-b7afed6e3de2](https://github.com/vaishnavishaji/Windows-basic-commands-batchscript/assets/151444759/bce73e66-62f1-4960-8ca5-4666227e7be0)
![326434000-75bc2e37-fc3a-48b1-8a16-7c6b8741dcb6](https://github.com/vaishnavishaji/Windows-basic-commands-batchscript/assets/151444759/e6eac00c-1b63-473b-8f40-fc49dddfaa07)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
![326434156-78147ed4-bbe6-48df-8524-52868404323a](https://github.com/vaishnavishaji/Windows-basic-commands-batchscript/assets/151444759/bd12dc1e-9372-4753-8efb-3117ec5b6615)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
![326434309-33c8796d-1d41-4465-8a39-05c3a3ba14ca](https://github.com/vaishnavishaji/Windows-basic-commands-batchscript/assets/151444759/0c75cdc1-b4f1-4266-965c-412b832e6f4d)


## COMMAND AND OUTPUT
![326434490-e58b19a9-e3e5-4f4a-a9d7-5a68d5db234a](https://github.com/vaishnavishaji/Windows-basic-commands-batchscript/assets/151444759/285d52d7-d02c-4cbf-ad39-0ad51ed20d8a)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!

```




## OUTPUT
![326434791-9af7aa8f-66ad-4c49-9828-03b682ed8fc8](https://github.com/vaishnavishaji/Windows-basic-commands-batchscript/assets/151444759/d13cb8c9-f031-4f6b-a119-27c81a4e44c3)





# RESULT:
The commands/batch files are executed successfully.

