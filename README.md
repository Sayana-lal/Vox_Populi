# Vox Populi

## Overview

Vox Populi is a platform designed to allow employees to share their honest experiences anonymously. Using IBM Watsonx, the platform analyzes these stories to provide companies with actionable insights into employee sentiments, recurring issues, and potential biases, fostering a more inclusive and supportive work environment.

## Features

- Anonymous feedback via text, voice, or video.
- AI-powered analysis of emotions, issues, and biases.
- Multilingual support for diverse workforces.
- Summarized reports with actionable insights for companies.

## Installation

### Prerequisites

- Python 3.7 or higher
- IBM Watsonx API credentials

### Steps

1. **Clone the repository:**
    bash
    git clone https://github.com/yourusername/vox-populi.git
    cd vox-populi

2. **Create a virtual environment:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies:**
    bash
    pip install -r requirements.txt
    
4. **Set up IBM Watsonx credentials:**
    - Obtain your API credentials from the [IBM Watsonx](https://www.ibm.com/watson) website.
    - Create a `.env` file in the root directory and add your credentials:
        WATSONX_API_KEY=your_api_key
        WATSONX_URL=your_service_url
        

## Usage

1. **Start the server:**
    bash
    python app.py

2. **Access the application:**
    - Due to deployment issue we cannot connect the model to the website
