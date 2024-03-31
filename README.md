# YouTube Video Summarizer

This is a Streamlit web application that summarizes YouTube videos using Youtube Transcript API and Google's Generative AI Gemini Pro.

## Overview

The YouTube Video Summarizer allows users to input a YouTube video URL and generates a summary of the video content based on its transcript. It utilizes Google's Generative AI Gemini Pro model to generate concise summaries of the video content.

## Installation

1. Clone this repository:

```bash
git clone https://github.com/shaadclt/Youtube-Video-Summarizer.git
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Set up your environment variables. You need to obtain a Google API key and set it as `GOOGLE_API_KEY` in a `.env` file.


## Usage

1. Run the Streamlit app:

```bash
streamlit run app.py
```

2. Access the web application at `http://localhost:8501` in your browser. Enter the YouTube video URL and click "Get Summary" to generate the video summary.


## Credits

This project was created by **Mohamed Shaad**. You can find me on [LinkedIn](https://www.linkedin.com/in/mohamedshaad/) and [GitHub](https://github.com/shaadclt).

## License

This project is licensed under the MIT License.
