# Bulk File Renamer and Organizer

## Overview

The File Organizer Tool provides a command-line interface for managing and organizing files. Below are the commands you can use to invoke different options within the tool.

#### Usage

1. **Run the Tool:**
   - Execute the following command to run the file organizer tool.
     ```bash
     python main.py
     ```

2. **Selecting and Filtering Files:**
   - When prompted, enter filter values for file selection interactively.
     ```bash
     Enter the path (Press enter to select the current path): /path/to/your/directory
     ```
   - Input filter criteria for file size, filename, and extension as required.

3. **Organizing Files:**
   - After file selection, you will be prompted to choose an organization method:

     - **Option 1: Rename Files In Place**
       ```bash
       Choose the method to reorganize:
       1. Rename in-place
       2. Rename and move to new folder
       3. Delete Files
       : 1
       ```

     - **Option 2: Rename and Copy to a New Folder**
       ```bash
       Choose the method to reorganize:
       1. Rename in-place
       2. Rename and move to new folder
       3. Delete Files
       : 2
       ```

     - **Option 3: Delete Files**
       ```bash
       Choose the method to reorganize:
       1. Rename in-place
       2. Rename and move to new folder
       3. Delete Files
       : 3
       ```

4. **Renaming Files In Place:**
   - If you chose option 1, enter a new filename when prompted.
     ```bash
     Enter the value for 'filename' argument: new_file_name
     ```

5. **Rename and Copy to a New Folder:**
   - If you chose option 2, enter a new filename and folder name when prompted.
     ```bash
     Enter the value for 'filename' argument: new_file_name
     Enter the value for 'folder-name' argument: /path/to/your/new/folder
     ```

6. **Deleting Files:**
   - If you chose option 3, confirm deletion by entering 'Y'.
     ```bash
     Deleting 5 files, press Y to confirm: Y
     ```

#### Examples

1. **Renaming Files In Place:**
   ```bash
   python main.py
   Choose the method to reorganize:
   1. Rename in-place
   2. Rename and move to new folder
   3. Delete Files
   : 1
   Enter the value for 'filename' argument: new_file_name
   ```

2. **Rename and Copy to a New Folder:**
   ```bash
   python main.py
   Choose the method to reorganize:
   1. Rename in-place
   2. Rename and move to new folder
   3. Delete Files
   : 2
   Enter the value for 'filename' argument: new_file_name
   Enter the value for 'folder-name' argument: /path/to/your/new/folder
   ```

3. **Deleting Files:**
   ```bash
   python main.py
   Choose the method to reorganize:
   1. Rename in-place
   2. Rename and move to new folder
   3. Delete Files
   : 3
   Deleting 5 files, press Y to confirm: Y
   ```

#### Notes

- Follow the on-screen prompts to interactively navigate through the file organization process.  
- Customize the commands based on your specific file organization requirements and directory paths.
