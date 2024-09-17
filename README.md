# Image to Text Converter

## Overview

The Image to Text Converter is a web application that uses optical character recognition (OCR) technology to extract text from images. Users can upload an image, process it to extract text using Tesseract.js, and download the text as a `.txt` file.

## Features

- **Image Upload:** Select an image file to process.
- **Text Extraction:** Click a button to convert the image to text using Tesseract.js.
- **Display Extracted Text:** View the extracted text in a textarea.
- **Text File Download:** Download the extracted text as a `.txt` file.
- **Responsive Design:** The application is designed to be visually appealing and responsive on different devices.

## Technologies Used

- **HTML/CSS:** For structuring and styling the web page.
- **JavaScript:** For handling functionality and interactivity.
- **Tesseract.js:** An OCR library for text recognition from images.

## Installation

To use the Image to Text Converter, you don't need to install anything locally. You can simply download or clone the repository and open the `index.html` file in a web browser.

### Cloning the Repository

```bash
git clone https://github.com/yourusername/image-to-text-converter.git
cd image-to-text-converter
```

### Opening the Application

Open `index.html` in your preferred web browser.

## Usage

1. **Upload an Image:**
   - Click the "Choose Image" button to select an image file from your computer.
   - The name of the selected file will be displayed in the input field next to the button.

2. **Convert the Image:**
   - Click the "Convert" button to start the OCR process.
   - A loading spinner will appear while the text is being extracted.

3. **View and Download Extracted Text:**
   - Once the text extraction is complete, the extracted text will be displayed in the textarea.
   - Click the download link to save the text as a `.txt` file.

## Example

Here is a sample screenshot of the application:
![image](https://github.com/user-attachments/assets/cb05798f-0f9d-4f69-859a-1d9863bcaf03)


## Code Snippets

**HTML Structure:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Meta tags, title, and link to external scripts and styles -->
</head>
<body>
    <!-- Main container with heading, file input, convert button, loader, and textarea -->
    <footer> <!-- Footer with copyright information --> </footer>
    <script>
        // JavaScript functionality for image handling, text extraction, and file download
    </script>
</body>
</html>
```

**CSS Styles:**

- Modern design with animations and transitions.

**JavaScript Functionality:**

```javascript
// Event listener for file input change to update file name display
// Event listener for convert button to initiate OCR and handle results
// Function to download the extracted text as a .txt file
```

**Tesseract.js Integration:**

- Uses `Tesseract.recognize()` to process the image and extract text.

## Challenges and Solutions

- **Handling Large Image Files:** Implemented a loading spinner to manage performance and user experience.
- **Cross-Browser Compatibility:** Followed standard HTML, CSS, and JavaScript practices to ensure compatibility.

## Future Improvements

- **Image Preprocessing:** Add steps like resizing and enhancing for better OCR accuracy.
- **Error Handling:** Enhance error handling for image file issues and OCR failures.
- **Additional Features:** Support for multiple languages and advanced text editing capabilities.

## Acknowledgments

- **Tesseract.js**: For providing the OCR functionality.
- **Poppins Font**: For typography used in the design.

## Contact

For any questions or feedback, please contact [Shubham Tiwari](mailto:your-email@example.com).
