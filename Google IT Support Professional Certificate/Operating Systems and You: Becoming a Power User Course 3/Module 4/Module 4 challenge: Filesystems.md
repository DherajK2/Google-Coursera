# Module 4 challenge: Filesystems


1. **Question 1**  
   What happens when you format a filesystem on a partition?  
   **Answer**: The partition becomes a volume.  

2. **Question 2**  
   How many GPT partitions can you have on a disk?  
   **Answer**: As many as you want  

3. **Question 3**  
   When partitioning a disk and formatting a filesystem, what happens if you choose the “full format” option? Select all that apply.  
   **Answer**:  
   - The formatting process will take longer.  
   - Windows will scan the target drive for errors and bad sections.  

4. **Question 4**  
   In Linux, what information will be displayed about a computer’s disks when the `sudo parted -l` command is executed in the CLI? Select all that apply.  
   **Answer**:  
   - The partition table types for each disk  
   - The number of partitions on each of the computer’s disks  
   - The sizes of the disk partitions  

5. **Question 5**  
   What can the Windows Memory Manager do? Select all that apply.  
   **Answer**:  
   - Map virtual memory to physical memory  
   - Copy pages of memory to be read as needed by programs  

6. **Question 6**  
   In Linux, when running `parted` in interactive mode, what happens when you enter the command `mkpart primary linux-swap 5GiB 100%`? Select all that apply.  
   **Answer**:  
   - You create a new disk partition.  
   - You format a disk partition for swap space.  

7. **Question 7**  
   What file attributes are stored in the Master File Table (MFT)? Select all that apply.  
   **Answer**:  
   - Whether or not a file is read-only  
   - File data locations  
   - File creation time stamps  

8. **Question 8**  
   What is the Linux equivalent to Window’s Master File Table (MFT)?  
   **Answer**: inode table  

9. **Question 9**  
   Which command will run the check disk utility and fix any problems it finds on a Windows file system?  
   **Answer**: `chkdsk /F`  

10. **Question 10**  
    What might occur if you were to run `fsck` on a mounted partition?  
    **Answer**: It could damage the file system.
