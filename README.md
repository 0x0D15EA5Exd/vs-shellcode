# vs-shellcode

Shellcode template is an Visual Studio in C++ to make shellcode on windows.

To use this template, you need ton copy the .zip in C:\Users\<username>\Documents\Visual Studio 2022\Templates\ProjectTemplates

    Feature :
    - All API Call is dynamicly solved with API Hashing (djb2), easy to edit with compile time hashing
    - You can use byte array, the .rdata section is merged at the end of .text section, easy to use with macro
    - Implementation of printf for easy debugging



When you create project in visual studio :
![alt text](https://raw.githubusercontent.com/RtlDallas/vs-shellcode/main/img/vstudio_search.PNG)
The code when you open the project, you need to code here :
![alt text](https://github.com/RtlDallas/vs-shellcode/blob/main/img/vstudio_view.PNG)

