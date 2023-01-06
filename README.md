# Digital_Huge_Manitees
OCR and topic modelling for digital humanities
There's two parts: 
- getting text from digital files and 
- finding topics within those texts

#### You can view the website [here.](https://digitalhugmanitees.github.io/DH_Topic_Workshop/)

## [Link](https://colab.research.google.com/github/DigitalHugManitees/DH_Topic_Workshop/blob/main/OCR_text_analysis_on_Colab_v69.ipynb) to the OCR notebook
## [Link](https://colab.research.google.com/github/DigitalHugManitees/DH_Topic_Workshop/blob/main/LDA_with_ngrams_on_Colab_v26.ipynb) to the LDA Notebook


## Input
You will need high quality PDf files as input. They can be multi-page and they can be digital, scanned image only, or searchable types. This notebook was intended to provide usable text from scanned image PDF files commonly found in archives. 

## Output
This notebook will output a .txt file of all text in the document. Text can be incomplete due to damage on the original document, unusual typefaces, or scan quality issues. 
OUtput will also include an html file that is a topic map of the specified number of topics and terms within those topics. 
Individual documents can be identified by cluster from the output spreadsheet exported as a .csv. 

### dependencies
####OCR
If you decide to run on locally on your computer by downloading this notebook, it will be essential to create an environment with these dependencies. Read the documentation carefully, as there is an order in which these are installed. 
- pytesseract - https://pypi.org/project/pytesseract/
- tesseract - https://github.com/tesseract-ocr/tesseract
- pdf2image - https://github.com/Belval/pdf2image
#### LDA


### open license info
- [ ] license type and what you can do with it

### sources/References
This project would not have been possible without the innumerable contributors on github, stack exchange, and other sites. I've listed the core ones below that this project was built upon. 

https://www.geeksforgeeks.org/python-reading-contents-of-pdf-using-ocr-optical-character-recognition/
This notebook was adapted based on the above reference tutorial.

### sources on LDA
 - https://towardsdatascience.com/latent-dirichlet-allocation-lda-9d1cd064ffa2

### Authors and affiliations:
This notebook is based off a tutorial by Tarek Ghanoum (https://towardsdatascience.com/topic-modelling-in-python-with-spacy-and-gensim-dc8f7748bdbf).
It was modified by Anika Nissen (University of Duisburg-Essen (UDE)https://www.iis.wiwi.uni-due.de/team/anika-nissen/) with help from Dominic Rosati (scite.ai, https://scite.ai/authors/domenic-rosati-X4xWR8A) for improvement of the ngrams. 
Additional modifications by Poppy Riddle (Dalhousie University, https://github.com/poppy-nicolette) for deployment on Colab, collating files, annotating, assigning clusters to source files in the df, and exporting. 
