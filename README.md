## HTML to WORD Batch GUI Images Intact converter

### Project Overview
HTMLtoWord-FolderConvert.py is a Python script designed to convert HTML files into Microsoft Word (.docx) format. It utilizes libraries such as BeautifulSoup for parsing HTML, python-docx for creating Word documents, and PIL for handling images encoded in base64 within the HTML. The script supports batch processing, allowing users to convert all HTML files within a selected folder.

### Key Features
- Batch conversion of HTML files to Word documents
- Handling of text formatting and alignment
- Conversion of HTML headings to Word styles
- Inclusion of images encoded in base64
- Support for bullet points, tables, figures, and mathematical elements
- Customizable font size and style for the entire document

## Installation Guide

### Prerequisites
- Python 3.x
- pip (Python package installer)

### Required Python Libraries
- BeautifulSoup4
- python-docx
- Pillow (PIL Fork)

### Installation Steps

#### 1. Install Python and pip
Ensure you have Python and pip installed on your system. You can download Python from the official website and pip is included by default from Python 2.7.9+ and Python 3.4+.

#### 2. Clone the Repository or Download the Script
- Use Git to clone the repository containing the script, or
- Download the script file directly to your local machine.

#### 3. Install Required Libraries
Open your terminal or command prompt and navigate to the directory containing the script. Install the required libraries using pip:

```bash
pip install beautifulsoup4
pip install python-docx
pip install pillow
```

#### 4. Run the Script
Execute the script with Python:

```bash
python HTMLtoWord-FolderConvert.py
```

#### 5. Follow the Prompts
- The script will prompt you to select a folder containing your HTML files.
- Once a folder is selected, the script will process all HTML files and save the converted Word documents in a subfolder named "HTMLtoWORD" within the selected directory.

### Troubleshooting
If you encounter any errors during installation or execution:
- Check if you have the correct version of Python installed.
- Ensure all required libraries are installed correctly.
- Verify the HTML files are well-formed and accessible.

### Support and Contributions
For support, questions, or contributions, users can open an issue or pull request on the GitHub repository where the script is hosted.
