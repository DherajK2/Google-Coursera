# Module 2 challenge: Users, Administrators, Groups and Permissions

1. **Question 1**:  
   Does an administrator user account on a computer have complete control over a machine?  
   **Answer**: Sometimes  

2. **Question 2**:  
   In Windows, what does UAC stand for?  
   **Answer**: User Account Control  

3. **Question 3**:  
   Which Windows PowerShell CLI command can be used to list the Users on a given computer?  
   **Answer**: Get-LocalUser  

4. **Question 4**:  
   On a Linux system, which file contains information about group memberships?  
   **Answer**: /etc/group  

5. **Question 5**:  
   Which of the following locations and/or methods can Administrators find and/or use to change user passwords on Windows systems? (Choose all that apply)  
   **Answer**:  
   - At the CLI, using the DOS style net user command.  
   - In the GUI, under Local Users and Groups in the Computer Management tool.  

6. **Question 6**:  
   What is the name of the privileged file on Linux that stores scrambled passwords?  
   **Answer**: /etc/shadow  

7. **Question 7**:  
   Which of the following methods can Administrators use to add a user in Windows? (Choose all that apply)  
   **Answer**:  
   - In the GUI, under Local Users and Groups in the Computer Management tool, right-click Users and select New User.  
   - At the CLI, use the DOS style net user username * /add command.  

8. **Question 8**:  
   Is it possible to have write access to a file in Windows without having read access to that same file?  
   **Answer**: No  

9. **Question 9**:  
   When examining the permissions on a file in Linux, you find the last three bits are `rw-`. What does this mean?  
   **Answer**: All users who are neither the file owner nor members of the group to which this file belongs have read and write permissions.  

10. **Question 10**:  
    In Windows, when setting the basic permission “Read,” which of the following special permissions are enabled? (Choose all that apply)  
    **Answer**:  
    - Read Attributes  
    - Read Data  
    - Read Permissions  
