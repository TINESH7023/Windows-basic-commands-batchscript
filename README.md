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


## COMMAND

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
```
mkdir %userprofile%\Desktop\MyLab
cd %userprofile%\Desktop\MyLab
type nul > MyFile.txt

```

## OUTPUT:

![image](https://github.com/shoaib3136/Windows-basic-commands-batchscript/assets/117919362/f4a46931-a18f-4409-911e-e6c1b1a927f1)



## COMMAND

List the contents of the "MyLab" directory.
```
dir %userprofile%\Desktop\MyLab
```

## Output:

![image](https://github.com/shoaib3136/Windows-basic-commands-batchscript/assets/117919362/69c9ead1-f1e9-40e9-8da5-d3a792c597e9)



## COMMAND

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

Move the "MyLab" directory to the "Documents" folder.

```
mkdir %userprofile%\Desktop\Backup
copy MyFile.txt %userprofile%\Desktop\Backup

```


## OUTPUT
![image](https://github.com/shoaib3136/Windows-basic-commands-batchscript/assets/117919362/e1e94b04-a9ac-46da-b030-4c96877b7a3d)



## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup

```
## OUTPUT:
![image](https://github.com/shoaib3136/Windows-basic-commands-batchscript/assets/117919362/f229b016-199a-41f2-900c-7d8704b48ef7)


```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx

```







## OUTPUT:
![image](https://github.com/shoaib3136/Windows-basic-commands-batchscript/assets/117919362/d644b3de-673d-4ee2-8ca8-3cb595e4d128)






# RESULT:
The commands/batch files are executed successfully.

