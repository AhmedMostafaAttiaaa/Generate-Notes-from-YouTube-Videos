# YouTube Notes Generator

Create detailed and comprehensive notes from YouTube videos using Gemini-1.5-Pro and Gemini-1.5-Flash.

## 🚀 Features

- Professional Notes Generation: Extract in-depth and structured notes from YouTube videos.
- Audio-Based Understanding: Leverages audio analysis rather than plain transcripts for improved context.
- Powered by Advanced LLMs: Utilizes Gemini-1.5-Pro or Gemini-1.5-Flash for exceptional results.
- User-Friendly Interface: Built with Streamlit for a smooth and intuitive user experience.
- Customizable Prompts Based on Video Type:
      TUTORIAL_ONLY: Tailored for tutorial-based videos.
      CLASS_LECTURE: Designed for academic lectures.


## 🛠️ Installation

1. Install ffmpeg:
   
   ```bash
   sudo apt-get install ffmpeg
   ```

2. Clone the repository:

   ```bash
   git clone https://github.com/di37/youtube-notes-generator.git
   cd youtube-notes-generator
   ```

3. Create and activate a Conda environment:

   ```bash
   conda create -n yt_notes_generator python=3.11
   conda activate yt_notes_generator
   ```

4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the application:

   ```bash
   streamlit run app.py
   ```

2. Open your web browser and navigate to the URL provided by Streamlit (usually `http://localhost:8501`).

3. Paste a YouTube URL and click Generate Notes to get comprehensive notes for the video.


