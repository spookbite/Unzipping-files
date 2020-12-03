# Unzipping-files

### What you got to do:
1. Add the path to the folder containing zipped files in dir_name and run the code.
2. If you want to keep the zipped file after extracting the content from it, comment out this line -> os.remove(file_name)

### What the code does:
1. Changes the directory from working directory to the directory with zipped files
2. Loops through items in the directory
3. Gets the full path of files
4. Creates a zipfile object
5. Extracts files to directory
6. Closes the file and deletes the zipped file
