**Multilingual Invoice Extractor**
=============================================

**Project Overview**
---------------------

This project demonstrates an Invoice Extractor application using Google's Gemini Vision Pro API integrated with a Streamlit web application. The app allows users to upload invoice images and input prompts to extract and interpret information from the invoices using advanced AI capabilities. The AI model can understand and process invoices, providing accurate responses to user queries.

**Features**
------------

* **User-Friendly Interface**: A Streamlit-based web application provides a simple and intuitive interface for uploading images and entering prompts.
* **Image Uploading**: Users can upload invoice images in various formats (jpg, jpeg, png).
* **Image Display**: Uploaded images are displayed on the web page for user confirmation.
* **AI-Driven Responses**: The application uses Google's Gemini Vision Pro API to analyze the uploaded invoices and generate responses based on user queries.
* **Dynamic Prompting**: Users can input custom prompts to guide the AI in extracting specific information from the invoices.

**Technology Stack**
--------------------

* **Streamlit**: For building the web interface.
* **PIL (Python Imaging Library)**: For handling image uploads and display.
* **Google Generative AI**: Specifically, the Gemini Vision Pro model for image analysis and response generation.
* **dotenv**: For loading environment variables securely.

**Installation and Setup**
-------------------------

### Clone the repository:
```bash
git clone https://github.com/Anuraggupta96/Multilingual-Invoice-Extractor.git
cd invoice-extractor# Multilingual-Invoice-Extractor

2. Install dependencies:
```bash
   pip install -r requirements.txt

3. Set up your environment variables::
   
- Create a .env file in the root directory of your project.
- Add your Google API key in the .env file:
   ```bash
   GOOGLE_API_KEY=your_google_api_key_here

## Application Execution
1. **Run the Streamlit app:**

   ```bash
   streamlit run vision.py

2. **Open your web browser and go to the local URL provided (e.g., http://localhost:8501).**

