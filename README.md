# Text2Hand - A Text to Handwriting Converter 

Text2Hand is a Streamlit web application that converts typed text, Word documents, or PDFs into beautiful handwritten images. It's perfect for students looking to enhance assignments or anyone who enjoys the charm of handwritten notes without manual effort.


![image](https://github.com/pranjalprateek6/Text2Hand-Text-to-Handwritting-Converter/assets/88288212/2582038e-f7ef-45c8-a5d4-5025a6e8456c)

![image](https://github.com/pranjalprateek6/Text2Hand-Text-to-Handwritting-Converter/assets/88288212/2463efb8-75b2-44b9-b6bc-2d2c756cb18a)



## Features

- **File Upload:** Upload text files (`.txt`), Word documents (`.docx`), or PDF files (`.pdf`).
- **Text Input:** Alternatively, enter text directly into the app.
- **Customization:** Adjust horizontal and vertical sizes, choose whether to start with a gap and generate unique handwritten images.
- **Download:** Download the generated handwritten image as a PNG file.

## How to Use

1. **Upload or Enter Text:** Choose a file or type directly into the app.
2. **Adjust Settings:** Customize the horizontal and vertical sizes using sliders. Optionally, select the "Start with Gap" checkbox.
3. **Generate Handwritten Image:** Click the "Generate Handwritten Text" button to create the image.
4. **Download Image:** Once generated, download the handwritten image using the "Download Image" button.

## Instructions for Running Locally
1. Keep the fonts folder and your text file in the same directory as the program.
2. If you want to create a program for your handwriting, add cropped images for each character in the fonts folder separately.
3. Name the images with the ASCII number corresponding to the character.
* For Example:
* For the alphabet 'A' name of the cropped image should be '65.png'

## Technologies Used

- Python
- Streamlit
- PIL (Python Imaging Library)
- PyPDF2
- docx2txt

