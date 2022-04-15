# useful_note

## useful settings for Go2Shell
Go2Shell is a very useful tool when you try to access console via finder.  
It will help you to go right into the folder you're browsing.  
For details, please check the official website of Go2Shell.  
### enter virtual envrionment directly
1. Open a terminal and type in "open -a Go2Shell --args config" to open the config pannel for Go2Shell
2. The initial script there would likely to be "cd %PATH%; clear; pwd"
3. Backup your current settings and then customize it with the shell script knowledge you have.  
   Here is the script I used to enter the virtual environment that exits under venv subfolder.  
   ```bash
   
   cd %PATH%; clear; pwd; if test -d venv; then echo "Venv found and enter python virtual environment "; source venv/bin/activate; else echo "Normal mode"; fi;  
   
   ```
   The reason why I use it like this is that I adopted the best practice from pycharm virtuanl environment management by creating venv folder in each project.  
   
## useful note for router

## useful note for cooking