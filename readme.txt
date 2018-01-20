
 Steps to set up your project TODo????????
 1. Rename your-project.sln
 2. Click your-project.sln to open in Visual Studio
 3. Open Tools -> Create GUID -> Registry Format -> copy and add to "SolutionGuid ^= " in your-project.sln

 Folders Structure:
 docs - for documents that are created by the project
 inc  - .h or .hpp header files to be included
 lib  - .dll files that needed to be included
 rsc  - resources pictures icons etc
 src  - source files
 test - Test file and test data
 ext  - external libraries, follow the information from the library developer to add them 

 Inside Visual Studio
 1. Add a new or existing project to your solution
 2.
 3.
 4.
 5.
 TODO!!!!!
 Property pages -> all configurations in configuration properties
Change the following 
General
Output directory $(SolutionDir)build\$(ProjectName)\windows\$(Platform)\$(Configuration)\
*note: change windows to linux or OSX as needed
General
Intermediate directory $(SolutionDir)build\$(ProjectName)\windows$\(Platform)\$(Configuration)\intermediates\
*note: change windows to linux or OSX as needed
C/C++ General
additional include $(ProjectDir)\inc
Linker General
additional library directories $(ProjectDir)\libs
Linker Input
Additional Dependencies any lib you need to connect to a dll
