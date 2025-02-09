# MovieSync: Automatic Subtitle Generator

## Overview
MovieSync is an **AI-powered automatic subtitle generator** that extracts audio from YouTube videos, transcribes the speech, removes inappropriate words, and translates the subtitles into regional languages. This project ensures accurate and efficient subtitle generation while maintaining cost-effectiveness and high-quality results.

## Features
### ✅ Automatic YouTube Video Processing
- Downloads YouTube videos and extracts the corresponding audio for processing.

### ✅ Speech-to-Text Conversion
- Converts speech into an **English transcription** using state-of-the-art speech recognition models.

### ✅ Censorship & Content Filtering
- Automatically detects and removes offensive words from the transcribed text to maintain content appropriateness.

### ✅ Multi-Language Subtitle Translation
- Translates English subtitles into **regional languages** for a wider audience.

### ✅ Efficient Chunking & Processing
- Splits audio into smaller segments to improve transcription accuracy and optimize API usage.

## How It Works
MovieSync follows a structured pipeline to generate subtitles efficiently:

1. **Download YouTube Video**: The video is fetched using its URL and stored locally.
2. **Trim Silence**: Silent portions of the video are removed to enhance processing efficiency.
3. **Extract Audio**: The audio is separated from the video file.
4. **Segment Audio**: The extracted audio is divided into smaller segments (e.g., 1-minute clips).
5. **Transcription**: Speech is converted into an English text transcription.
6. **Censorship**: Offensive words are detected and filtered out.
7. **Translation**: The cleaned transcription is translated into the selected regional language.
8. **Evaluation & Refinement**: The generated subtitles are reviewed, and improvements are made for accuracy.

## Technologies Used
MovieSync is built using advanced AI and NLP technologies for accurate subtitle generation.

- **Python** – Core development language.
- **YouTube API** – Fetches video content.
- **FFmpeg** – Processes and trims audio.
- **Whisper (OpenAI)** – High-accuracy speech-to-text transcription.
- **Google Translate API** – Translates subtitles into multiple languages.
- **Regex & NLP** – Used for filtering offensive words and content moderation.
- **Logging & Error Handling** – Ensures robustness and maintainability.

## Installation
To set up MovieSync, follow these steps:

### Step 1: Clone the Repository
```bash
git clone https://github.com/tanaydwivedi095/MovieSync.git
cd MovieSync
```

### Step 2: Install Dependencies
Ensure you have **Python 3.8+** installed, then run:
```bash
pip install pytube ffmpeg openai googletrans regex numpy
```

### Step 3: Run the Application
Execute the Jupyter Notebook to process a YouTube video:
```bash
jupyter notebook
```
Open the `.ipynb` file and follow the instructions to input a video URL and generate subtitles.

## Usage
MovieSync provides an interactive AI-powered workflow to generate subtitles:

1. **Provide a YouTube Video URL**.
2. **Choose a target language** for translation.
3. **Run the script** to process the video, transcribe speech, and generate subtitles.
4. **Save and use** the generated subtitles for your content.

### Example
#### **Input:**
- YouTube Video: *Educational Documentary*
- Target Language: *Spanish*

#### **Output:**
- Extracted English subtitles
- Translated Spanish subtitles
- Filtered, clean content

## Future Enhancements
Planned improvements for MovieSync include:

- **Enhanced AI-Based Censorship** for better filtering accuracy.
- **Support for Additional Languages** beyond Google Translate’s capabilities.
- **Subtitle Synchronization with Timestamps** for precise alignment.
- **Batch Processing for Multiple Videos**.
- **Web-Based Interface for Easier Access**.

## Contributing
We welcome contributions! To contribute:
1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature-branch`).
3. Commit your changes and push the branch (`git push origin feature-branch`).
4. Open a pull request for review.

## License
This project is licensed under the **MIT License**, allowing for open-source contributions and modifications.

---
MovieSync provides a **seamless and efficient subtitle generation process**, making video content **more accessible** across different languages. 🎬🌍

