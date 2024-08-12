Packer-Unpacker CUI Module
Overview
The Packer-Unpacker CUI Module is a simple command-line utility written in Java that allows users to pack multiple text files from a directory into a single packed file and unpack them back to their original form. This tool is useful for bundling files together for easy storage or transmission.

Features
Packing: Combines multiple text files (.txt) from a specified directory into a single packed file.
Unpacking: Extracts and restores files from the packed file to their original state.
File Headers: Maintains headers in the packed file to store metadata such as file names and sizes.
How It Works
Packing
The user specifies the directory containing text files and the name of the packed file to be created.
The program reads each text file, creates a header for each file (including its name and size), and appends the file's content to the packed file.
The packed file is created in the specified location, containing all selected text files.
Unpacking
The user specifies the packed file to be unpacked.
The program reads the header information from the packed file to determine the original file names and sizes.
Each file is recreated with its original name and content in the current directory.
