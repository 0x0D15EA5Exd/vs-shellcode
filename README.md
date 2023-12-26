# vs-shellcode

Shellcode template is an Visual Studio in C++ to make shellcode on windows.

To use this template, you need ton copy the .zip in C:\Users\<username>\Documents\Visual Studio 2022\Templates\ProjectTemplates

    Feature :
    - All API Call is dynamicly solved with API Hashing (djb2), easy to edit with compile time hashing
    - You can use byte array, the .rdata section is merged at the end of .text section, easy to use with macro
    - Implementation of printf for easy debugging
