# C++ Build System for Sublime Text Editor
This build enables C++ to run on Sublime Text editor.

# Installing MinGW (C++ Compiler) 
(Skip this section, if already installed)
1. Download MinGW from https://sourceforge.net/projects/mingw-w64/ 
2. Install it in C:/MinGW (Recommended) drive.
3. Locate your bin folder (C:/MinGW/bin).
4. Copy this location of bin folder.

# Changing the Path of Environment Variables
1. Go to:- Start -> Control Panel -> System -> Advanced system settings -> Environment Variables.
2. Select "Path" under "User Variables" section and click on Edit.
3. Click on "New" and paste the location(MinGW - C++ compiler's directory) in the empty field.
4. Press OK.
5. Similarly, follow the same steps from 2-4 under the "System variables" section.

# Setting up Sublime
1. Go to:- Tools -> Build System -> New build system.
2. Copy the code from the "C++.sublime-build" file.
3. Save the file as "C++.sublime-build".
4. Again, go to:- Tools -> Build System. Make sure that C++ is selected.
5. Use "Ctrl + B" to build i.e. compile and run the C++ program.

