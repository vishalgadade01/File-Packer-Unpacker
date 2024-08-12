# File Packer-Unpacker System
This project is a simple File Packer-Unpacker system implemented in Java. It allows users to pack multiple text files into a single packed file and unpack them back to their original files. This utility is designed to efficiently bundle files for storage or transfer and restore them when needed.


# Features
Pack Files: Combine multiple text files from a directory into a single packed file.
Unpack Files: Extract and restore files from a packed file to their original state.
File Headers: Maintain metadata such as file names and sizes in the packed file.
Class Structure

# Packer
The Packer class is responsible for the packing activity. It reads multiple text files from a specified directory, adds headers with metadata, and writes the content into a single packed file.

# Packing

The user is prompted to enter the directory containing the text files and the name of the packed file to be created.
The Packer class reads each text file, creates a header containing the file name and size, and appends the content to the packed file.
The packed file contains all selected text files, ready for storage or transfer.

# Unpacking

The user is prompted to enter the packed file name.
The Unpacker class reads the packed file, extracts the headers to determine file names and sizes, and restores the files to their original state in the current directory.
