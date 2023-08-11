# BizCardX: Extracting Business Card Data with OCR

BizCardX is a Python application developed using Streamlit that allows users to upload images of business cards and extract relevant information from them using the easyOCR library. The extracted information includes company name, cardholder name, designation, mobile number, email address, website URL, area, city, state, and pin code. The extracted information is displayed in an intuitive graphical user interface (GUI). Users can also save the extracted information along with the business card image into a database.

## Table of Contents

- [Technologies](#technologies)
- [Problem Statement](#problem-statement)
- [Approach](#approach)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Technologies

- Python
- Streamlit
- easyOCR
- SQLite (or MySQL)
- Image processing techniques

## Problem Statement

The primary objective of this project is to develop a user-friendly application that simplifies the process of extracting and managing information from business cards. The main challenges include image processing, OCR integration, GUI development, and database management.

## Approach

1. **Installation**: Install the necessary packages including Python, Streamlit, easyOCR, and a database management system (SQLite or MySQL).

2. **Design the User Interface**: Create an interactive Streamlit GUI that guides users through uploading business card images and extracting information. Use widgets like file uploaders, buttons, and text boxes for user interaction.

3. **Image Processing and OCR**: Utilize easyOCR to extract relevant information from uploaded images. Apply image processing techniques like resizing and thresholding to enhance image quality before processing.

4. **Display Extracted Information**: Present the extracted information in a clean and organized manner within the Streamlit GUI, using widgets like tables and labels.

5. **Database Integration**: Implement integration with a database (SQLite or MySQL) to store both the extracted information and the uploaded business card image. Utilize SQL queries to manage database operations.

6. **Testing and Improvement**: Thoroughly test the application to ensure its functionality. Continuously enhance the application by fixing bugs, optimizing code, and introducing new features.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/BizCardX.git
cd BizCardX
```

2. Install the required packages:

```bash
pip install streamlit easyocr # Add any other necessary packages
```

3. Run the application:

```bash
streamlit run app.py
```

## Usage

1. Upload a business card image using the file uploader.
2. Click on the "Extract Information" button to process the image and display the extracted information.
3. Review the displayed information and click the "Save to Database" button to store the information and image in the database.
4. Use the application's user interface to read, update, and delete information stored in the database.

## Contributing

Contributions are welcome! If you have any improvements or features to add, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Commit your changes: `git commit -am 'Add a new feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Submit a pull request.
