# Module 5 challenge: Process Management


1. **Question 1**  
   Which of the following statements are true about child processes in Windows? Select all that apply.  
   **Answer**:  
   - A child process is dependent on its parent process until the child process is terminated.  
   - A child process inherits environment variables and settings from its parent.  
   - A child process can be terminated by running the `taskkill /pid` command in the CLI.  

2. **Question 2**  
   In Linux, what process has the PID of 1?  
   **Answer**: init  

3. **Question 3**  
   Which of the following methods can be used to get information on processes that are running in Windows? Select all that apply.  
   **Answer**:  
   - From the CLI, use the `tasklist` command.  
   - From the PowerShell prompt, use the `Get-Process` commandlet.  
   - Use the Windows Task Manager.  

4. **Question 4**  
   When using the `ps -ef` command to read process information in Linux, what is the process’ PPID?  
   **Answer**: The Process Identification number of its parent  

5. **Question 5**  
   Which of the following statements are true about SIGINT? Select all that apply.  
   **Answer**:  
   - It can be sent at the CLI by pressing the CTRL+C keys.  
   - It is an interrupt signal that can be sent to a process that is running.  
   - It is a signal that exists in both Windows and Linux.  

6. **Question 6**  
   Which of the following options are available in Process Explorer after right-clicking a running process in the top window pane? Select all that apply.  
   **Answer**:  
   - Kill Process  
   - Suspend  

7. **Question 7**  
   In Linux, what signal puts a process into a suspended state?  
   **Answer**: SIGTSTP  

8. **Question 8**  
   What happens to background apps while a foreground app is in use on iOS and Android?  
   **Answer**: The OS will suspend background mobile apps.  

9. **Question 9**  
   In Windows, what information is displayed by the Resource Monitoring tool? Select all that apply.  
   **Answer**:  
   - Process information along with data about the resources that the process is consuming  
   - System hardware properties  
   - Information about particular resources on the system (like CPU, Memory, and Network usage)  

10. **Question 10**  
    Which of the following Linux commands lists open files and what processes are using them?  
    **Answer**: `lsof`
