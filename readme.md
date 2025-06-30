# Basic File Handling Utility

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : GIRISH KUMAR

*INTERN_ID* : CT06DF2915

*DOMAIN* : Java Programming

*DURATION* : 6 WEEKS

*MENTOR* : Neela Santhosh Kumar
  
  
<br/><br/><br/>
## Description 

Code Structure and Functionality
1. File Writing Operations
The program demonstrates three distinct approaches to writing files. First, it uses the traditional FileWriter class to create a sample file with basic content including timestamps and descriptive text. This method is straightforward but less efficient for large files. Second, it employs BufferedWriter wrapped around FileWriter for improved performance when writing multiple lines, demonstrating how buffering can optimize I/O operations. Third, it showcases the modern NIO.2 approach using Files.write(), which provides a more concise API for simple file writing operations.
2. File Reading Operations
The reading demonstration covers four different techniques. The BufferedReader approach reads files line by line, which is memory-efficient for large files. The Scanner class provides more flexible reading capabilities with built-in parsing features. The NIO.2 Files.readAllLines() method loads entire files into memory as lists, suitable for smaller files that need complete processing. Finally, Files.readAllBytes() reads the entire file as a byte array, useful for binary operations or when you need the complete file content as a string.
3. File Modification Operations
This section demonstrates practical file modification techniques. The program reads an existing file, processes its content by adding line numbers and transforming specific lines (those containing "Java" are converted to uppercase), and writes the modified content to a new file. It also shows how to append content to existing files using the append mode of FileWriter, which is crucial for logging applications and incremental file updates.
4. Advanced File Operations
The advanced section provides file system information including file size, permissions, and modification dates. It performs content analysis by counting lines, words, and characters, demonstrating text processing capabilities. The program also implements search and replace functionality, showing how to modify file content programmatically.

### Output Images
![output images](https://github.com/girishkr9331/basic-File-handling-utility/blob/main/fileHandling1.png)
![output images](https://github.com/girishkr9331/basic-File-handling-utility/blob/main/fileHandling2.png)

<br/> <br/>
Instructions :
1. Navigate to the file directory.
2. Run in terminal :  
 javac main.java  
 java FileOps

The following files will be created:
- input.txt: Original file with sample content
- modified.txt: File with modified content
- output.txt: Summary of operations performed
