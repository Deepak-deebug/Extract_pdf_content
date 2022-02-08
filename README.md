# Extract PDF content
Extract PDF content from all the url’s present in the following .csv file By using **EasyOCR**.use GPU OR TPU to run the program .  
## Getting Started
### Dependencies
 OCR with 80+ supported languages and all popular writing scripts including Tamil, Latin, Chinese, Arabic, Devanagari, Cyrillic and etc.
    
    !pip install easyocr

Precompiled command-line utilities (based on Poppler) for manipulating PDF files and converting them to other formats.
    
    !apt-get install poppler-utils

A python (3.6+) module that wraps pdftoppm and pdftocairo to convert PDF to a PIL Image object

    !pip install pdf2image

If your are using opencv version 4.5.5 Then easyocr will not work properly So uninstall it and install opencv == 4.5.2.52

    !pip uninstall opencv-python-headless==4.5.5.62
    !pip install opencv-python-headless==4.5.2.52

### Data Set Link
https://github.com/Deepak-deebug/Extract_pdf_content/blob/main/Data%20Engineer%20Task%20-%20Data%20Engineer%20Task.csv

## Sources

https://www.jaided.ai/easyocr/tutorial/

