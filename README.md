##Sample Environment
--

This is my sample environment so I can create projects easily and quickly. Feel free to contribute.

Here is a simple batch file that will download the repository and renames it to an input you specify, in one you. You have to add the filepath of your directory:

```
cd C:\Projects
@echo off
set /p foldername="Enter folder name: " pause
Echo The folder will be renamed to %foldername% 
git clone https://github.com/kangaskahn/environment.git
rename environment %foldername%
```

There you go, a new project in a single click!