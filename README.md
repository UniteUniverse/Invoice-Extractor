# Invoice Extractor

## Overview
Invoice Extractor is a Streamlit-based application that utilizes Google's Gemini Pro Vision model to extract and interpret information from invoice images. The application takes an uploaded invoice image as input and generates a response based on the extracted data.

## Features
- Upload invoice images in JPG, JPEG, or PNG formats
- Extracts and interprets text from invoices using gemini-1.5-flash
- User-friendly Streamlit interface
- Uses environment variables for secure API key management

## Installation
### Prerequisites
Ensure you have the following installed on your system:
- Python 3.8+
- pip (Python package manager)
- A Google API key (stored in a `.env` file)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/UniteUniverse/Invoice-Extractor.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Invoice-Extractor
   ```
3. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Set up the `.env` file and add your Google API key:
   ```plaintext
   GOOGLE_API_KEY=your_api_key_here
   ```

## Usage
1. Run the application:
   ```bash
   streamlit run app.py
   ```
2. Upload an invoice image via the Streamlit UI.
3. Enter a query related to the invoice.
4. Click on "Tell me about the invoice" to generate a response.

## Project Structure
```
Invoice-Extractor/
│── app.py                # Main application script
│── requirements.txt      # Required dependencies
│── .env                  # Environment variable file (not to be shared)
│── README.md             # Project documentation
```

## Dependencies
- Streamlit
- Pillow
- Google Generative AI SDK
- Python Dotenv

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

## Contact
For more information, visit the project repository: [Invoice Extractor](https://github.com/UniteUniverse/Invoice-Extractor)

