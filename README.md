```markdown
# PDF Translator and Audio Converter

## Overview

The **PDF Translator and Audio Converter** is a Python-based desktop application that allows users to translate the text content of a PDF file into different languages and convert the translated text into an audio file (MP3 format). The application is built using the `tkinter` library for the GUI and integrates several other libraries for text extraction, translation, and text-to-speech conversion.

## Features

- **PDF File Selection:** Allows users to browse and select a PDF file from their local system.
- **Language Selection:** Users can choose the target language for translation from a list of supported languages.
- **Translation and Conversion:** Translates the text content of the PDF file into the selected language and converts the translated text into an audio file.

## Supported Languages

The application currently supports the following languages for translation and audio conversion:

- English
- French
- German
- Spanish
- Italian
- Chinese
- Japanese

## Prerequisites

To run this application, you need to have Python installed on your system. Additionally, you need to install the following Python packages:

- `threading`
- `PyPDF2`
- `googletrans`
- `gtts`
- `tkinter`
- `pdfreader`

You can install the required packages using pip:

```bash
pip install PyPDF2 googletrans gtts pdfreader
```

> Note: `tkinter` is typically included with Python, so you might not need to install it separately.

## Usage

1. Clone or download the repository to your local machine.

2. Install the required packages by running the following command:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the application using the following command:

    ```bash
    python main.py
    ```

4. In the application window, select the PDF file you want to translate.

5. Choose the target language from the dropdown menu.

6. Click on the "Translate and Convert" button to start the translation and conversion process.

7. Once the process is complete, a success message will appear, and the translated audio file will be saved as `output.mp3` in the current directory.

## Project Structure

- `main.py`: The main script that runs the application.
- `README.md`: Documentation for the project.
- `requirements.txt`: A list of required packages.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- The application uses the `googletrans` library for translation.
- The `gtts` library is used for text-to-speech conversion.
- Special thanks to the open-source community for providing these libraries.
