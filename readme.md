# OCR Django Application

This is a Django web application for extracting text from images using Tesseract OCR.

## Installation

1. Clone the repository:

    ```bash
    git clone <repository_url>
    ```

2. Navigate to the project directory:

    ```bash
    cd OCR-django-app
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Install Tesseract OCR:
    - You will need Tesseract for this.

    - **Ubuntu/Debian**:

      ```bash
      sudo apt update
      sudo apt install tesseract-ocr
      ```

    - **macOS**:

      ```bash
      brew install tesseract
      ```

    - **Windows**:

      Download and install from [Tesseract-OCR](https://github.com/tesseract-ocr/tesseract).

5. Set up environment variables:
   
   Create a `.env` file in the root directory of your project and add the following environment variables:

    ```plaintext
    SECRET_KEY=<your_secret_key>
    ```

6. Apply migrations:

    ```bash
    python manage.py migrate
    ```

7. Start the development server:

    ```bash
    python manage.py runserver
    ```

## Usage

- Visit the homepage and upload an image.
- Select the language of the text in the image.
- Click on the "Scan" button to extract text from the image.
- The extracted text will be displayed on the page.

## Dependencies

- Django: Web framework for building the application.
- Tesseract OCR: Open-source OCR engine for text recognition from images.

## Contributions

Contributions to this project are welcome and encouraged! If you'd like to contribute, fork this repositor:

`git clone https://github.com/ASACHIT/OCR-django-app.git`