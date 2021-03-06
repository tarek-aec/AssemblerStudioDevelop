Assembler Studio Develop
======================

Assembler Studio Develop was the assembly editor and simple IDE (Integrated Development Environment) for SIC and SIC XE machines make building and highlighting code.

## Technology Stack
- This project developed in C# using Microsoft .Net 3.5 Framework
- Microsoft Visual Studio 2010
- Highliter RichTextBox Component and UserControl
- MDI Windows Form Application

## SIC and SIC XE Machines
SIC: which stands for Simplified Instructional Computer is a hypothetical architecture that was used used by 
Leland Beck in his book 'System Software' to explain the concepts of assemblers, compilers and 
operating systems. SIC/XE,(the XE stands for Extra Equipment), is an extension of SIC which has higher 
memory, greater number of registers and additional instructions. 

## Sample code
sample SIC and SIC XE assembly code:
```assembly
    LDA FIVE
    STA ALPHA
    LDCH CHARZ
    STCH C1
    
    ALPHA RESW 1
    FIVE WORD 5
    CHARZ BYTE C'Z'
    C1 RESB 1
```
You may find sample code [here](https://github.com/tarek-aec/AssemblerStudioDevelop/blob/master/bin/Debug/SIC%20XE.txt) to test Assembler Studio Develop.

## License
Assembler Studio Develop project licensed under [MIT](http://opensource.org/licenses/MIT) license.
