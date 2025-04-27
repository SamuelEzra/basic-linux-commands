# Basic Linux Commands

### Project Overview
This mini project demonstrates the usage of basic Linux commands to create, manage, and manipulate files and directories in a development environment. The commands included in this project cover essential tasks such as listing files, creating directories, copying files, renaming files, and removing files and directories.

### Project Structure
The directory structure for this project is as follows:

```sh
basic-linux-commands/
├── README.md
├── test/
│   ├── test.txt
│   ├── test2.txt
│   └── test3/
├── test2/

```

Commands Used
Listing Files and Directories
- ls- Displays the contents of the current directory.
- Example:

```sh
ls
```

- ls test- Displays the contents of the `test` directory.
- Example:

```sh
ls test
```

### Creating Directories and Files
1.  ```sh
    mkdir test2
    ``` 
    - Creates a directory named `test2` in the current location.

2.  ```sh
    touch test/test2.txt
    ``` 
    - Creates an empty file named `test2.txt` inside the test directory.

3.  ```sh
    mkdir test/test3
    ```
    - Creates a subdirectory named `test3` within the test directory.

4.  ```sh
    touch test/test3/file3.txt
    ```
    - Creates an empty file named `file3.txt` inside the `test/test3` directory.


### Copying Files and Directories
1.  ```
    cp test/test2.txt test2/
    ```
    - Copies the `test2.txt` file from the `test` directory to the `test2` directory.

2.  ```sh
    cp -R test/test3 test/test2
    ```
    - Copies the `test3` directory and its contents recursively into the `test2` directory.


### Renaming Files
1.  ```sh
    mv test/test3/file3.txt test/test3/new_file3.txt
    ```
    - Renames `file3.txt` to `new_file3.txt` within the `test/test3` directory.


### Removing Files and Directories
1.  ```sh
    rm test/test3/new_file3.txt
    ```
    - Removes the file `new_file3.txt` from the `test/test3` directory.

2.  ```sh
    rm -r test/test3
    ```
    - Recursively removes the test3 directory and its contents.


Key Learnings
- How to navigate and manipulate file systems using Linux commands.
- Understanding the difference between removing files and directories using rm and rm -r.
- Creating efficient workflows with file and directory operations.

Conclusion
This project serves as a fundamental demonstration of Linux file system operations. Mastery of these basic commands is essential for anyone aspiring to work with Linux-based systems.


