# consorcios
Repositório destinado a organizar dados sobre consórcios públicos no Brasil

pasta principal

\\Sasworkspace1\DIEST\Consórcio Intermunicipais\Ives\Ives - CNPJs

para listar as pastas prontas:

cd "\\Sasworkspace1\DIEST\Consórcio Intermunicipais\Ives\Ives - CNPJs"


To create a file listing all folder (directory) names in a given location on Windows, you can use the Command Prompt or PowerShell. Below are both methods:

✅ Using Command Prompt (cmd.exe)
Open Command Prompt (Win + R, type cmd, press Enter).

Navigate to the directory where you want to list folders, for example:

cd C:\Users\YourUsername\Documents

Run the following command to list only directories and save them to a text file:

dir /ad /b > folder_list.txt 
  /ad: lists directories only.
  /b: bare format (just names, no details).

> folder_list.txt: saves output to a file.

The file folder_list.txt will appear in the current folder.

✅ Using PowerShell
Open PowerShell.

Navigate to the target folder:

**powershell**

Run this command:

Get-ChildItem -Directory | Select-Object -ExpandProperty Name | Out-File "folder_list.txt"

This creates a file folder_list.txt with just the names of all subfolders.

