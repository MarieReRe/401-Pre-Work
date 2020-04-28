# History of .NET and C# 28/04.2020

### What is C#?
- C# is a object-oriented programming language developed by Microsoft in 2002 
- It is general purpose and can be used for windows desktop applications and games but is becoming increasingly popular for mobile development too. 

### C# Versions
There are many versions of C# now and I am sure there will be more to come as this language evolves. As for now, with the current versions I found this nifty little image to help layout the versions and the changes to those versions. There has since been a version 7.1, 7.2, and 7.3. We are now onto version 8.0. 
![](images/c%23-history.png)

#### 7.1 Version: New Features
- async Main method
- default literal expressions
- Inferred tuple element names
- Pattern matching on generic type parameters

#### 7.2 Version: New Features
- Techniques for writing safe efficient code: Syntax improvements
- Non-trailing named arguments
- Leading underscores in numeric literals
- private protected access modifier
- conditional ref expressions

#### 7.3 Version: New Features
**Safe Code -** is executed and managed by the CLR and provide security to the application when written in the .NET Framework. 

**Unsafe Code -** can create issues with stability and security. Unsafe is a keyword to denote that a secion of code is not managed by the Common Language Runtime *(CLR)* of the .NET Frameworkr unmanaged code. 



This version had two main themes which included features that enable safe code to be as performant as unsafe code and incremental improvements to existing features. 


#### CLR what is it responsible for? 
- Managing the memory for the objects
- Performing Type verification
- doing garbage collection


##### Resources on information unknown: 
https://docs.microsoft.com/en-us/dotnet/csharp/write-safe-efficient-code
https://www.c-sharpcorner.com/UploadFile/f0b2ed/understanding-unsafe-code-in-C-Sharp/
https://www.c-sharpcorner.com/blogs/safe-and-unsafe-concept-of-c-sharp

#### 8.0 Version: New Features
- Readonly members
- Default interface methods
- Pattern matching enhancements:
    - Switch expressions
    - Property patterns
    - Tuple patterns
    - Positional patterns
- Using declarations
- Static local functions
- Disposable ref structs
- Nullable reference types
- Asynchronous streams
- Asynchronous disposable
- Indices and ranges
- Null-coalescing assignment
- Unmanaged constructed types
- Stackalloc in nested expressions
- Enhancement of interpolated verbatim strings



