# LaTeX to DOCX Converter for LLM Outputs

A Python-based application that converts LaTeX documents (especially those generated by AI language models like ChatGPT or Claude) into Microsoft Word (DOCX) format. The application provides a user-friendly GUI interface and maintains formatting while converting mathematical equations.

## Features

- Converts LaTeX equations to native Word equations
- Maintains text formatting including bold text
- Preserves paragraph justification
- User-friendly GUI interface
- Real-time conversion
- Supports common LaTeX math environments
- Automatic opening of converted documents
- Times New Roman font with 11pt size

## Prerequisites

Before running the application, make sure you have the following installed:

- Python 3.7 or higher
- Microsoft Word (required for opening the converted documents)

## Required Packages

Install the required Python packages using pip:

```bash
pip install python-docx
pip install lxml
pip install latex2mathml
pip install tkinter
```

## Installation

1. Download the repository:

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Make sure both `latexdocx_gui.py` and `MML2OMML.XSL` are in the same directory.

## Usage

1. Ask ChatGPT or Claude or any other LLM about a scientific topic. Input **"convert your answer into latex format"** prompt. Then **"copy"** the latex code.

![image](https://github.com/user-attachments/assets/1367f886-066c-42fe-a160-8203ad5f2bb4)

2. Run the application:
```bash
python latexdocx_gui.py
```

3. The GUI window will appear with a text input area.

4. Paste your LaTeX content into the text area.

5. Click the "CONVERT TO MSWORD" button.

6. The converted document will automatically open in Microsoft Word. (If it is installed!)

## Supported LaTeX Features

- Mathematical equations (inline and display mode)
- Bold text using `\textbf{}`
- Basic text formatting
- Common mathematical symbols
- Subscripts and superscripts
- Matrices and arrays
- Greek letters
- Mathematical operators

## Limitations

- Does not support LaTeX packages and custom commands
- Limited support for complex table structures
- Does not support LaTeX figures and diagrams
- Some complex mathematical structures might not convert perfectly
- **This script is intended to work on Windows Platforms, Linux or Mac are not supported. LibreOffice or Openoffice are not supported.**

## Screenshot

![image](https://github.com/user-attachments/assets/5d281477-1bb2-4268-8b9f-c4ad218a3b6e)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Uses the MML2OMML.XSL stylesheet for MathML to Office Math ML conversion
- Built with Python and various open-source libraries

## Credits

https://github.com/python-openxml/python-docx/issues/320

## Contact

T.T. Bilgin - [LinkedIn Profile](https://www.linkedin.com/in/ttbilgin/)
