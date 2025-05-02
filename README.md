# Legal AI

## Overview
Legal AI is a web application that predicts the applicable legal sections for a given incident description. This tool is designed to assist law enforcement agencies, legal professionals, and researchers by automating the classification of FIRs based on relevant legal provisions.

## Features
- Multi-label classification of FIRs using **Gemini API**.
- User-friendly chat interface built with **Streamlit**.
- Real-time prediction of applicable FIR sections.
- Supports text-based FIR inputs.

## Technologies Used
- **Python**: Core programming language.
- **Streamlit**: For building the web-based user interface.
- **Gemini API**: For multi-label classification and FIR section prediction.
- **VS Code**: Development environment.

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- streamlit
- pandas
- docx
- google-generativeai
- pip (Python package manager)

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/FIR-Section-Predictor.git
   cd FIR-Section-Predictor
   ```
2. Create and activate a virtual environment (optional but recommended):
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the Streamlit application:
   ```sh
   streamlit run app.py
   ```

## Usage
1. Open the web app in your browser.
2. Enter the FIR details in the provided text box.
3. Click on **Predict** to get the suggested legal sections.
4. Review the predictions and use them for legal reference.

## Deployment

The project is deployed on Streamlit Cloud. 
You can access it here: https://firfirsectionpredictor-fxu9wbfgrqufbvb8yunhkb.streamlit.app/
