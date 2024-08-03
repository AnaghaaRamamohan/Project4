# Project4
OPTICAL CHARACTER RECOGNITION USING TESSERACT ON RASPBERRY PI

# Objectives and Scope
The Optical Character Recognition (OCR) project using Tesseract aims to transform images of printed or handwritten text into machine-readable and editable text formats. The key objectives include:

1.Accessibility Improvement:
Enhance accessibility for visually challenged individuals by simplifying texts with various backgrounds.

2.Font and Handwriting Recognition:
Translate different fonts and handwriting styles into readable text formats, leveraging Tesseract’s extensive training on diverse datasets.

3.Document Digitization:
Convert physical documents or images into electronic text formats, making them easily accessible and editable.

4.Text Segmentation:
Achieve clean segmentation of foreground text from background to improve accuracy in text recognition.

5.Integration Capabilities:
Facilitate integration with other applications and programming languages (Python, Java, C++) to automate OCR tasks and enhance workflow efficiency.

# Working

1.Image Acquisition:
The project starts by reading an image using the Python Imaging Library (PIL).

2.Text Recognition:
Pytesseract: A Python wrapper for the Tesseract OCR engine is employed to recognize text from the image. This tool integrates seamlessly with Python and is widely used for OCR tasks.

3.Process Overview:
Pillow Package: Used to open the image and store it in a variable.

Pytesseract image_to_string() Method: Applied to detect and extract text from the image, which is then stored as a string.

Text Output: The extracted text is printed to the shell of the Raspberry Pi 4 for verification.

4.Noise Reduction:
OpenCV: Utilized to remove noise from the image and enhance the quality before processing with Tesseract, ensuring better OCR accuracy.

5.Text Utilization:
The recognized text can be used for various applications, including text-to-speech conversion, data analysis, and further processing.
