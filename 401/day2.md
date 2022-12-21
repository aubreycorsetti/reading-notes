# Day 2 Notes

## FileIO & Exceptions

### Read & Write Files in Python

• What is a file?
  > A file is a contiguous set of bytes used to store data.
  > Most modern file systems are made up of 3 main parts: Header (file name, size, type, etc), Data (contents of the file written by the creator/editor) and End of File aka EOF (special character that indicated the end of the file).

• Opening and Closing a file
  > ex: file = open('my_example.txt')
  > ex: finally: reader.close()

### __file__

  > this is a special attribute, similar to __name__. It is the pathname of the file from which the module was loaded, if it was loaded from a file.

### Python Exceptions

• Exception Error
  > displays as whatever type of error that occured (EX:ZeroDivisionError). This type of error occurs whenever syntactically correct Python code results in an error. The last line of the message indicated what type of exception error you ran into.

• Raise an Exception
  > EX: raise Exception('x should exceed 5. The value of x was:{}')

### Things I want to know more about

I would like to get comfortable writing python.

### Key Takeaways

• raise allows you to throw an exception at any time.
• assert enables you to verify if a certain condition is met and throw an exception if it isn’t.
• In the try clause, all statements are executed until an exception is encountered.
• except is used to catch and handle the exception(s) that are encountered in the try clause.
• else lets you code sections that should run only when no exceptions are encountered in the try clause.
• finally enables you to execute sections of code that should always run, with or without any previously encountered exceptions.
• A try clause is executed up until the point where the first exception is encountered.
• Inside the except clause, or the exception handler, you determine how the program responds to the exception.
• You can anticipate multiple exceptions and differentiate how the program should respond to them.
• Avoid using bare except clauses.

#### Sources

https://realpython.com/read-write-files-python/

https://realpython.com/python-exceptions/

Click to return [Home!](../README.md)
