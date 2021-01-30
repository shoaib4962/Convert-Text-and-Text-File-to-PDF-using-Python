Convert Text and Text File to PDF using Python
PDFs are one of the most important and widely used digital media. PDF stands for Portable Document Format. It uses .pdf extension. It is used to present and exchange documents reliably, independent of software, hardware, or operating system. Converting a given text or a text file to PDF (Portable Document Format) is one of the basic requirements in various projects that we do in real life. So, if you don’t know how to convert a given text to PDF then this article is for you. In this article, you will come to know the way to convert text and text file to PDF in Python.

FPDF is a Python class that allows generating PDF files with Python code. It is free to use and it does not require any API keys. FPDF stands for Free PDF. It means that any kind of modification can be done in PDF files.

The main features of this class are:

Easy to use
It allows page format and margin
It allows to manage page header and footer
Python 2.5 to 3.7 support
Unicode (UTF-8) TrueType font subset embedding
Barcode I2of5 and code39, QR code coming soon …
PNG, GIF and JPG support (including transparency and alpha channel)
Templates with a visual designer & basic html2pdf
Exceptions support, other minor fixes, improvements and PEP8 code cleanups
To install the fpdf module type the belwo command in the terminal.

pip install fpdf

Approach:
Import the class FPDF from module fpdf
Add a page
Set the font
Insert a cell and provide the text
Save the pdf with “.pdf” extencsion
