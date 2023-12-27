
# TesserXtract.AI

**This Flask application empowers users to seamlessly upload image files like invoices or receipts, extract text using robust OCR technologies, and efficiently isolate key fields using precise regular expressions and multiprocessing to streamline data extraction and enhance productivity.**

<img width="1517" alt="Screenshot 2023-12-27 at 8 09 23 PM" src="https://github.com/giruu/TesserXtract.AI/assets/37336192/4623710a-93b2-4c6f-8fb3-fc61449ff9a5">

## **Key Features**

- **Image Upload:** Effortlessly upload multiple image files for processing.
- **OCR Integration:** Leverages Tesseract, a powerful open-source OCR engine, to accurately extract text from images.
- **Field Extraction:** Precisely isolates specific fields of interest using meticulously crafted regular expressions.
- **JSON Output:** Delivers extracted field values in a structured JSON format, promoting compatibility with downstream applications.
- **Multiprocessing:** Optimizes performance by concurrently processing multiple image uploads, enhancing efficiency.

## **Technical Highlights**

- **Python:** Built upon the versatile Python programming language.
- **Flask:** Utilizes the lightweight Flask web framework for streamlined development.
- **Tesseract:** Integrates the robust Tesseract OCR library.
- **Regular Expressions:** Harnesses the power of regular expressions for accurate field extraction.
- **Error Handling:** Gracefully manages potential errors for smooth operation.
- **Asynchronous Processing:** Explores asynchronous task queues for further performance optimization (in development).

## **Installation and Setup**

1. **Prerequisites:**
   - Python 3.x
   - Tesseract OCR (install separately)
   - Required Python libraries (listed in requirements.txt)
2. **Create a virtual environment (recommended):**
   - `python -m venv venv`
   - Activate the virtual environment:
     - Windows: `venv\Scripts\activate.bat`
     - Linux/macOS: `source venv/bin/activate`
4. **Clone TesserXtract.AI:**
   - Clone the repository:
   
   ```bash
   git clone https://github.com/giruu/TesserXtract.AI.git
   ```
   Navigate to the cloned directory:
   
   ```bash
   cd TesserXtract
   ```
3. **Install dependencies:**
   - `pip install -r requirements.txt`

## **Running the Application**

1. **Start the Flask development server:**
   - `flask run`
2. **Access the application:**
   - Open your web browser and navigate to `http://127.0.0.1:5000/` (or the specified port)

## **Usage**

1. **Upload images:** Use the file upload interface to select multiple image files.
2. **View results:** The extracted field values will be displayed in JSON format.


## **Additional Information**

- **Error Handling:** The application incorporates error handling for file uploads, OCR processing, and field extraction.
- **Asynchronous Processing:** Asynchronous task queues are being explored to further optimize performance, especially for large-scale image processing.

**For any questions or assistance, feel free to open an issue or contact the developer.**
