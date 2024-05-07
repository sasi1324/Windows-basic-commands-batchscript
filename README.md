# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

NAME:RAMYA.P

REGISTER NUMBER: 212223240137

DEPARTMENT: AIML

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

## COMMAND AND OUTPUT

mkdir %userprofile%\Desktop\MyLab

![image](https://github.com/23014107/Windows-basic-commands-batchscript/assets/151625620/d10aa9ae-369a-46bd-a8e3-d8187b16f618)

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

## COMMAND AND OUTPUT

cd %userprofile%\Desktop\MyLab

![image](https://github.com/23014107/Windows-basic-commands-batchscript/assets/151625620/83be5476-0651-4446-b8a4-3a3ab1b550ca)

![image](https://github.com/23014107/Windows-basic-commands-batchscript/assets/151625620/4fa889b0-8ea9-404d-a289-97d4dc7da20a)

List the contents of the "MyLab" directory.

## COMMAND AND OUTPUT

dir %userprofile%\Desktop\MyLa
![image](https://github.com/23014107/Windows-basic-commands-batchscript/assets/151625620/eb00c02e-a2a2-4bed-9590-02f4effe3c34)

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT
mkdir %userprofile%\Desktop\Backup

copy MyFile.txt %userprofile%\Desktop\Backup

![image](https://github.com/23014107/Windows-basic-commands-batchscript/assets/151625620/0bc8d46c-8b17-4464-bae6-13db623a1ec8)

![image](https://github.com/23014107/Windows-basic-commands-batchscript/assets/151625620/12e972cc-769b-429a-8f4f-e7cd15cc2b55)

Move the "MyLab" directory to the "Documents" folder.

## COMMAND AND OUTPUT

mv Myfile.txt %userprofile%\Documents

![image](https://github.com/23014107/Windows-basic-commands-batchscript/assets/151625620/a126e4b4-2fba-4866-b58d-3780c549d856)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```

```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!
```

## OUTPUT

![image](https://github.com/23014107/Windows-basic-commands-batchscript/assets/151625620/1592f01e-94e5-4c37-acdc-66136d711cef)

# RESULT:
The commands/batch files are executed successfully.

