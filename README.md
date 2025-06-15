# PDF to JPG Converter (GDRFA Compliant)

This project is a web-based utility to convert pages of a PDF file into individual JPG images. It's specifically designed to meet the strict file size requirements of entities like Dubai's GDRFA (General Directorate of Residency and Foreigners Affairs), ensuring all output images are under 512 KB.

## Features

* **GDRFA Compliant**: Automatically and intelligently compresses each generated JPG to ensure it is under the 512 KB size limit without a major loss in quality.
* **Client-Side Processing**: All conversion and compression happens directly in your browser. Your files are never uploaded to a server, ensuring 100% privacy and security.
* **Multi-File Processing**: You can upload and convert multiple PDF files in a single batch operation.
* **Batch Download**: Download all the generated JPGs from every processed PDF in a single, convenient `.zip` file.
* **Individual Downloads**: Option to download each converted page separately if you only need specific ones.
* **Clear & Responsive UI**: The interface is clean, easy to use, and works perfectly on both desktop and mobile devices. It provides real-time feedback on the conversion process, including output file sizes and the compression quality applied.

## Technologies Used

* **Frontend**: HTML5, CSS3, JavaScript (ES6+)
* **Styling**: [Tailwind CSS](https://tailwindcss.com/) for rapid UI development.
* **Core Libraries**:
    * [**PDF.js**](https://mozilla.github.io/pdf.js/): A library by Mozilla for parsing and rendering PDF files in the browser.
    * [**JSZip**](https://stuk.github.io/jszip/): Used for creating `.zip` archives for the batch download feature.

## How to Use

1.  **Open the Tool**: Launch the `Converter.html` file in your web browser.
2.  **Select Files**: Click the upload area to select one or more PDF files, or simply drag and drop them into the designated zone.
3.  **Convert**: Once your files are selected, click the "Convert to JPG" button to start the process.
4.  **Review & Download**:
    * The converted images will appear below, showing the final file size and the quality level.
    * You can download images one by one using the "Download JPG" button on each card.
    * Alternatively, click the "Download All as ZIP" button to save all the converted images at once.
5.  **Clear**: Use the "Clear" button to reset the application and start over.

