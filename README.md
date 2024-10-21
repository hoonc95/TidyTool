# TidyTool
#### (formerly called simply "Desktop Organizer")
Script, designed to automate File Organization on a specified directory ("_~/Desktop_" used in this example ).  
Scans selected directory for files -  based on supported file types (_e.g., audio, documents, images, videos_) - to categorize into selected directories.  
The GUI - built with tkinter - features a simple window with a title, input field, and file browse capabilities, to configure the file organization.  
Logs were configured to provide details about moved files and retreive relocated files.

## Key functions:  
1. ``` make_unique ```  
to handle duplicate filenames  
2. ``` move_file ```  
to relocate files  
3. ``` process_file ```  
to determine the appropriate destination for each file

## Building Blocks:
``` import tkinter ```  
for a simple GUI conformation  
``` import os ```  
for file system operations  
``` import shutil ```  
for high-level file handling

![Screenshot 2024-06-19 at 3 44 00 PM](https://github.com/hoonc95/Data_Analytics_Portfolio/assets/168390796/03b585c3-21bc-45e1-89f4-bf03d267aea7)
```diff
BEFORE (⬆) | AFTER (⬇)
```
![Screenshot 2024-06-19 at 3 44 14 PM](https://github.com/hoonc95/Data_Analytics_Portfolio/assets/168390796/bc7eb833-ccd3-40d8-b1b7-3ba2bfd10666)
## Full Python Script
![desktop_organizer py](https://github.com/hoonc95/Data_Analytics_Portfolio/assets/168390796/d9cae3e1-69b5-436f-a29b-1a318438607e)
