# License Plate Recognition System (LPRS)

This project is a MATLAB-based License Plate Recognition System (LPRS) built using App Designer. It leverages image processing techniques and Optical Character Recognition (OCR) to detect and extract license plate numbers from uploaded vehicle images.

## 🚗 Features

- Upload vehicle images through a GUI
- Detect license plates using MSER and stroke width variation
- Recognize text using built-in OCR functions
- Extract Malaysian license plate numbers using regular expressions
- Identify the state or plate category based on prefix (e.g., A = Perak, B = Selangor)
- Display original image and cropped license plate region

## 🛠️ Technologies Used

- **MATLAB** with App Designer
- **Image Processing Toolbox**
- **Computer Vision Toolbox**


## 📁 Project Structure

- `LPRS.m`: Main app file
- `UIAxes`: Displays uploaded image
- `UIAxes_2`: Displays cropped plate
- GUI components: Buttons, labels, text fields for interaction

## 📌 How to Run

1. Open MATLAB
2. Make sure Image Processing and Computer Vision Toolboxes are installed
3. Run the `LPRS` class file
4. Interact with the app to upload images and detect plates
