---
title: "Fundamentals of file systems"
teaching: 20
exercises: 10
questions:
- "What is a filesystem?"
- "What is a file?"
- "How do we tell the type of a file?"
objectives:
- "Explain the basics of filesystems"
- "Explain what a file is"
keypoints:
- "Filesystems vary across computer systems"
- "File types are not always obvious"
---

## Introduction: What is a file system?

Stub content.




## What is a file?
More content.


## How do we tell the type of a file?

The most visible identifier of a file's type is the file extension that is often found appended to a file's name.  While this gives a useful indication, and can be used by the operating system to determine which application will open the file, there are several reasons that this is  not sufficient for digital preservation work. First, not all operating systems make the file extension visible by default.  Second, file extensions are not always correct, they can be intentionally or accidentally changed, leaving a file the appears to be unopenedbale.  Lastly, the file extension provides no indication of the file type version or software generation needed to access the file.


The commandline tool [file](http://man7.org/linux/man-pages/man1/file.1.html) performs multiple typesof tests to classify and return informatation about the file's type.

**Usage**:  Open terminal, type the ```file``` command followed by the filename

 ```$ file  test.txt```  

**Output**:  
    ``` test.txt: ASCII text ```  



### Additional Utilities:
 Droid

More content.
