# PdfConnect: Transform Your PDF Interactions Using ChatGPT-PDFBot! 📑

Welcome to PdfConnect, a revolutionary Streamlit web application that allows you to interact with your PDF documents in a whole new way. Chat with your PDFs, ask questions, get document summaries, and extract valuable insights using the powerful OpenAI GPT-3.5 Turbo.

## Features:

- **Chat with Your PDFs:** Engage in natural language conversations with your documents. Ask questions, seek information, and receive detailed responses.

- **Effortless Document Summarization:** Obtain quick and accurate summaries of your entire document. Save time and get to the heart of the content effortlessly.

- **Intuitive PDF Interaction:** Navigate your documents with ease – smoothly upload, interact, and explore your PDFs for a delightful and seamless experience.

- **AI-Powered Information Retrieval:** Let ChatGPT handle the heavy lifting. Extract relevant information from your PDFs, saving you valuable time.

## Demo

https://github.com/alisa-30/PdfConnect/assets/95209452/ac3dba93-be4b-4463-bd33-0b888bf3be40

## Prerequisites:

Before running PdfConnect, ensure the following:

- **Python:** Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).

- **OpenAI API Key:** Obtain an OpenAI API key by registering on the [OpenAI platform](https://platform.openai.com/). The API key is required for utilizing OpenAI's services in the project.

## Setup:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/alisa-30/PdfConnect.git
    ```

2. **Navigate to the cloned directory:**

    ```bash
    cd PdfConnect
    ```

3. **Create an .env file:**

    Create a file named `.env` in the project root directory and add the following line, replacing `YOUR_OPENAI_API_KEY` with your actual OpenAI API key:

    ```env
    OPENAI_API_KEY=YOUR_OPENAI_API_KEY
    ```

    Save the file.

4. **Install the required dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

5. **Run the application:**

    ```bash
    streamlit run app.py
    ```

## Dependencies:

- Streamlit
- OpenAI GPT-3.5 Turbo
- Tesseract OCR
- Poppler
- Other Python libraries (specified in `requirements.txt`)

## Support and Contributions:

- If you encounter any issues or have suggestions, feel free to [open an issue](https://github.com/alisa-30/PdfConnect/issues).

- Contributions are welcome! Fork the repository, make your changes, and submit a pull request.

## License:

This project is licensed under the [MIT License](LICENSE).

---

Unleash the power of AI on your PDFs with ChatGPT-PDFBot and make your document interactions a breeze! 📄💬
