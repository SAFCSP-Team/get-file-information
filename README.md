### Get File Information

#### Objective
Understand how to access a file's information, such as the file's name, size, and path.

#### Concepts
These concepts are the main used concepts in the project solution, kindly read the provided resources if any is new to you.

These concepts are the main ones used in your project solution


| Concepts                     | Resources                                                                                                            |
|------------------------------|----------------------------------------------------------------------------------------------------------------------|
| Accessing a file/directory   | [Dev.Java ](https://dev.java/learn/java-io/)                                                                         |
| System Properties            | [Java Documenation of System Properties](https://docs.oracle.com/javase/tutorial/essential/environment/sysprop.html) |


#### Problem
Print out a file's information (name, size, type, owner, created at, and path).


#### Implementation
Do the implementation of the `printFileInfo` method, to print the `note.txt` file information:
1. Initialize a variable with the `Path` data type, and assign it `Paths.get(/* file path*/)`.
2. Pass the variable that you have just created to the `printFileInfo(/* path variable */)` method.
3. In the `printFileInfo()` method, assign the variables to the correct value based on their name.
4. print the file information (name, owner, type, size).

>* fileName
>* fileOwner
>* fileType
>* fileSize


```java
    public static void printFileInfo(Path filePath) throws IOException {
        Path fileName = null;
        UserPrincipal fileOwner = null;
        String fileType = null;
        long fileSize = 0;
        /* Your code here */
        
        System.out.println("File Name: "+fileName);
        System.out.println("File Type: "+fileType);
        System.out.println("File Size: "+fileSize+" bytes");
        System.out.println("File Owner: "+fileOwner);

    }
```
