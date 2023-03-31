Code runner - settings icon - extensions settings 

Code runner: run in terminal - tick

Code runner: save all files before run - tick


Code runner - executor map 

Edit in settings.json - 

"c": "cd $dir && gcc $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",

.exe

"c": "cd $dir && gcc $fileName -o $fileNameWithoutExt.exe && $dir$fileNameWithoutExt.exe",

.exe


"cpp": "cd $dir && g++ $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",


    "C_Cpp.default.cppStandard": "c++20",
    
    "C_Cpp.default.cStandard": "c11",
    
    "terminal.integrated.defaultProfile.windows": "Git Bash",
    
    "code-runner.terminalRoot": "/",
    
    "window.zoomLevel": 1,

This pc - c drive - mingw - bin - copy the path

Edit the system environment variable - environment variable - path (double click) - new - paste the path - ok - ok - ok


Code runner - settings icon - extension keyboard shortcuts - run code - Ctrl + F9

Or search by run code and edit - Ctrl + F9

Settings.json - 

        "c": "cd $dir && gcc $fileName -o $fileNameWithoutExt.exe && $dir$fileNameWithoutExt.exe < input.txt > output.txt",
        
        "cpp": "cd $dir && g++ $fileName -o $fileNameWithoutExt.exe && $dir$fileNameWithoutExt.exe < input.txt > output.txt",


input.txt

output.txt

Split right 

Split down


