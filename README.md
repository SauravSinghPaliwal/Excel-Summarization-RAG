# Summarize App

Welcome to the **Excel-Summarization-RAG** repository! This project is designed to leverages LlamaIndex and IBM's Docling for RAG over excel sheets. You can also use it for ppts and other complex docs,

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [NVIDIA NIM API Setup](#nvidia-nim-api-setup)


## Features

- Feature 1: Upload Excel files and view it.
- Feature 2: Start chating to your excel file.
- Feature 3: Summarize and modify your excel file.

## Installation

To get started, clone the repository and install the necessary dependencies.

### Prerequisites

Ensure you have the following installed on your machine:

- Python 3.8 or above
- pip (Python package installer)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/SauravSinghPaliwal/Excel-Summarization-RAG.git
   cd Excel-Summarization-RAG
   ```

2. Create a Python virtual environment:

   - On Windows:

     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```

   - On Linux/MacOS:

     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```

3. Install the required dependencies:

   ```bash
   pip install -q --progress-bar off --no-warn-conflicts -r requirements.txt python-dotenv
   ```

## Usage

1. Set up your environment variables by creating a `.env` file in the project root. Refer to the `.env.example` file for guidance.

2. Run the main script:

   ```bash
   streamlit run summarize_app.py
   ```

3. NVIDIA_API_KEY="enter your api key"

## NVIDIA NIM API Setup

1. Go to [build.nvidia.com](https://build.nvidia.com) and create an account if you don’t have one.

2. Navigate to `meta/llama-3.2 7-b` and generate an API key.

3. Save the generated API key in a secure location, such as a notepad, as it can be used for all models available on the build.nvidia.com platform.

4. Use this API key to configure your application for seamless integration with NVIDIA NIM APIs.


