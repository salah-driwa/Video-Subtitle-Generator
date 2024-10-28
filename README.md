# Video Subtitle Generator

A Python application that extracts audio from a video file, transcribes the audio into text using the Whisper model, and generates subtitles in SRT format. The application then creates a new video with the subtitles overlaid at the bottom.

## Features

- **Audio Extraction**: Extracts audio from video files.
- **Speech Recognition**: Uses the Whisper model for transcription.
- **Subtitle Creation**: Generates SRT subtitles and overlays them on the video.
- **Customizable Settings**: Adjust font size, color, and margin for subtitles.

## Requirements

- Python 3.x
- Libraries:
  - `moviepy`
  - `pysrt`
  - `whisper`
  - `Pillow`
  - `numpy`
  - `google.colab` (for Google Drive integration)

You can install the required libraries using pip:

```bash
pip install moviepy pysrt git+https://github.com/openai/whisper.git Pillow numpy
