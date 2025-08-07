 Multi-Language Programming Practice Repository

Welcome to the **Multi-Language Programming Practice** repository!  
This repository contains a collection of programs written in **C**, **C++**, **Java**, and **Python**, covering a wide range of basic and intermediate programming topics.

---
Description

This project is designed for students, educators, and programmers who want to:
- Practice and compare syntax across different programming languages
- Learn fundamental programming concepts
- Prepare for technical interviews and academic exams

All programs are structured and well-commented for ease of understanding.

---
Languages Used

- **C** – Procedural programming, memory management, pointers
- **C++** – Object-oriented programming, STL (Standard Template Library)
- **Java** – Class-based, platform-independent, object-oriented
- **Python** – High-level, dynamically typed, easy to read
- 
 How to Install Dev C++ on Windows
🔹 Step 1: Download Dev C++
Go to the official or trusted website:

https://sourceforge.net/projects/orwelldevcpp/

Or use https://www.bloodshed.net/devcpp.html (for older versions)

Click on the “Download” button.

🔹 Step 2: Run the Installer
Locate the downloaded file (usually in your Downloads folder).

Double-click the .exe file to launch the setup.

Choose your language (English is default) → Click OK.

Click Next to agree with the license terms.

Choose the installation location (or leave it as default).

Click Install.

🔹 Step 3: Complete Installation
Once the installation is finished, click Finish.

Launch Dev C++ from the desktop or start menu.

🔹 Step 4: Configure Dev C++ (First Time Use)
When it opens the first time, choose:

Language: English

Theme: Classic (or choose any)

Compiler: Default is TDM-GCC 4.9.2 (recommended)

Click OK.

✅ You're Ready to Use Dev C++
Now you can:

Click File > New > Source File

Write your C or C++ program

Save the file with .c or .cpp extension

Click Execute > Compile & Run or press F11



- To write the first C program, open the C console and write the following code:

Example
#include <stdio.h>    
int main(){    
printf("Hello C Language");    
return 0;   
}  
C Integer Types Example
Let us take an example to illustrate the Integer types in C.

Example
#include <stdio.h>  
  
int main() {  //main function  
    // Integer types  
    short int a = 45;         // short int  
    unsigned short int b = 7545; // unsigned short int  
    int c = 2154455;          // int value  
    unsigned int d = 441454581; // unsigned int  
    long int e = 24525366552;     // long int  
    unsigned long int f = 4294967295; // unsigned long int  
    long long int g = 854223755457775807; // long long int  
    unsigned long long int h = 8565225254522331615U; // unsigned long long int  
  
    printf("short int a = %hd\n", a);  
    printf("unsigned short int b = %hu\n", b);  
    printf("int c = %d\n", c);  
    printf("unsigned int d = %u\n", d);  
    printf("long int e = %ld\n", e);  
    printf("unsigned long int f = %lu\n", f);  
    printf("long long int g = %lld\n", g);  
    printf("unsigned long long int h = %llu\n", h);  
  
    return 0;  
}  
Output:

In this example, we discussed the several types of integers that perform several operations in C.
C Character Type Example
Let us take an example to illustrate the character type in C.

Example
#include <stdio.h>  
  
int main() {  //main function  
  char word = 'T';  
  printf("%c", word);  
  return 0;  
}  

