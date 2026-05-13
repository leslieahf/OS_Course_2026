# OS_Course_2026

Name : LESLIE OCLOO
ID : 64043

# ASSIGNMENT1
This file contains a simple Bash script for retrieving basic information about a Linux environment (tested on Google Colab).
The script displays the operating system name, the kernel version, the current logged-in user and the current working directory.

# ASSIGNMENT2
This file contains a program that interacts with the Linux file system (tested on Google Colab). The program accepts a directory path as input, lists all files inside it and retrieved and prints specific characteristics (size and permissions) for each file. I use the 'os' and the 'stat' libraries. I use many functions from these librairies such as : 
-'os.listdir' to list all the files inside the directory to provide an initial overview of the directory's content
-'os.scandir' to iterate through the directory more efficiently because it retrieves basic file information while listing the names, this avoids unnecessary system calls
-'file.stat' to retrieve the metadata (statistics) of the file and to obtain the data structure containing the size (st_size) and the mode (st_mode)
-'stat.filemode' to convert the raw permission bits returned by the kernel into a human-readable string format permissions, following the standard Linux read/write/execute notation

