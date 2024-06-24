# QR Code Generator

This QR Code Generator application allows users to create QR codes for any URL they provide. Built using Flask, it offers a simple and intuitive user interface designed for both desktop and mobile users. The application ensures a seamless and efficient experience, making it easy for anyone to generate QR codes quickly. With just a few clicks, users can enter a URL, generate a QR code, and use it for various purposes, such as sharing links, embedding on websites, or printing on promotional materials.

## Images

Here are some images of the application:

![Image1](imgs/Image1.png)
![Image2](imgs/Image2.png)


## Technologies Used

- Flask: A lightweight WSGI web application framework in Python.
- Python: The programming language used to develop the application.
- HTML/CSS: For the frontend design and layout.
- qrcode: A Python library for generating QR codes.
- Jinja2: A templating engine for Python, used by Flask to generate HTML.
- Bootstrap: For responsive design and styling.
- JavaScript: For handling interactive elements on the frontend.

## Features

- Generate QR codes from URLs
- Responsive design for both desktop and mobile
- Easy-to-use interface
- Includes navigation links to "About Me" and the project repository

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/RamonvCS/QRCODE-generator-may.git
    cd QRCODE-generator-may
    ```

2. **Create a virtual environment**:
    ```bash
    python -m venv venv
    ```

3. **Activate the virtual environment**:
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```bash
        source venv/bin/activate
        ```

4. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

5. **Run the application**:
    ```bash
    python main.py
    ```

6. **Open your browser and navigate to** `http://127.0.0.1:5000/`

## Usage

- Enter the URL you want to generate a QR code for in the input field.
- Click the "Generate QR" button to create the QR code.
- Click the "Reset" button to clear the input field and generated QR code.

## Project Structure

