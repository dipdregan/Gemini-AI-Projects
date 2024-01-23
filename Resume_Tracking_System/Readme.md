### ================= Jay SHIYA-RAM================


# Smart ATS - Resume Tracking System

## Introduction

Welcome to Smart ATS, your intelligent Application Tracking System powered by Gemini AI. This Streamlit app helps you evaluate and enhance resumes based on a given job description.

![Screenshot (241)](https://github.com/dipdregan/Gemini-AI-Projects/assets/58151564/cb607fe1-52e1-44c4-b218-a293f885b296)

![Screenshot (242)](https://github.com/dipdregan/Gemini-AI-Projects/assets/58151564/eed45fd9-7f8e-483c-86ed-ffb12b641fee)

## Getting Started

### Prerequisites

Before running the app, make sure you have the necessary dependencies installed. You can install them using:

```bash
pip install -r requirements.txt
```

### Running the App

1. Set up your Gemini AI API key by creating a `.env` file and adding your key:

   ```plaintext
   API_KEY=your_gemini_ai_key
   ```

2. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```

## Usage

1. Paste the job description in the provided text area.
2. Upload your resume in PDF format.
3. Click the "Submit" button to get the AI-driven evaluation.

## Features

- **Gemini AI Integration**: Utilizes the power of Gemini AI's Generative Models.
- **Resume Evaluation**: Provides percentage matching and identifies missing keywords.
- **User-Friendly Interface**: Simple and easy-to-use with a clean design.

## Workflow

1. **User Input**: Paste the job description and upload your resume.
2. **AI Evaluation**: The app uses Gemini AI to evaluate the resume based on the job description.
3. **Results Display**: The app presents the evaluation results, including JD match percentage and missing keywords.

## Project Structure

```plaintext
├── app.py               # Main Streamlit application
├── prompts.py           # File containing the input prompt
├── .env                 # Environment variable file (API key)
├── requirements.txt     # Dependencies file
├── README.md            # Project README file
└── images/              # Directory for project images
```

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to Gemini AI for providing the powerful Generative Models.

🚀 Happy Resuming! 📄✨

