# DocxToMdConverter
This program is used to convert Word files (.docx) to Markdown files (.md).

## Requirements
- [Python 3.12](https://www.python.org/downloads/release/python-3120/)
- customtkinter `pip install customtkinter`
- pypandoc `pip install pypandoc`

## Usage
1. Run the command prompt as an administrator in the directory where the Python file is located, and then execute the command `py main.py`.
2. Select the .docx file for conversion (you can download a sample from the repository) and choose the location where the output file should be saved.
3. Click the Convert button. If everything works correctly, a message indicating successful conversion will appear, and the .md file will be saved in the specified location.

**Important!** The first run of the program may take some time as it will install the necessary software ([pandoc](https://pandoc.org/)) unless it is already installed on the computer.