# basic-command-line

- `Arrow Up` and `Arrow Down`: This will show your previous and next commands
- `Tab`: This will auto-complete your 
- `Ctrl + C`: This will exit the current command
- `Ctrl + D`: This will close the terminal. Note: this command does not work on `Command line` and `Powershell`

# Basic Commands
*Some of the commands here works well on Bash and ZSH but does not work on `cmd` and `powershell`. I will try to write out all the commands and show the difference*

## List Files in Folder

- On windows command line and powershell
 > dir
- On Bash and Zsh
 > ls

## Create Folder and File
- Creating a folder is the same across all platform
> mkdir [folderName]
- While, creating a file is different. On windows
> type nul > [filename.extention]
- On Bash and Zsh
> touch [filename.extention]

## Navigating Through Folder
*Navigating through folders is the same across all the platform*
- To navigate into a folder
> cd [foldername]
- To go back to the previous folder
> cd ..