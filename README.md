# Handwritten-image-to-text
A mini project made for my internship with best enlist converts a scanned image of handwritten text to text and stores important details in a text file

Converts image to text using tesseract library, although the accuracy is not very good for cursive handwriting it has about 88% for non-cursive handwriting. For cursive it is recommended to use google API, which I couldn't access, although ive written code for google API version as well.

After converting to extract important information, I divided the text into sentences nltk library and if a sentence has more than 1 word starting with a capital letter it will be considered important and stored in a text file.
