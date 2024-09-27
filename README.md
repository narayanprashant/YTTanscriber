**YouTube Transcript Summarizer**:

This project is designed to extract transcripts from YouTube videos and summarize them efficiently. Using the power of Google Generative AI for text summarization, the project simplifies the process of digesting long YouTube content. Additionally, it utilizes Streamlit for building an interactive web-based interface, making the summarization accessible and user-friendly.


**Features**:

1.YouTube Transcript Retrieval: Automatically fetches transcripts from YouTube videos using the youtube-transcript-api.

2.Summarization: Utilizes Google Generative AI to summarize the transcripts, providing key insights from long-form video content.

3.Interactive UI: Built with Streamlit, the app offers an intuitive interface where users can input a YouTube video URL, fetch the transcript, and get a concise summary.

4.Environment Management: Utilizes a .env file to handle sensitive information like API keys for secure operation.

**File Descriptions**:

1.app.py: The main script that runs the Streamlit application. It handles the UI, fetches YouTube transcripts, and summarizes them using AI.

2.requirement.txt: Lists all the dependencies required for the project, including pandas, youtube-transcript-api, streamlit, and python-dotenv​(requirement).

3. .env: This file stores environment variables such as API keys required to interact with external services. Ensure this file is properly configured before running the app.

**Dependencies**:

The project relies on several key libraries:

1.pandas: Data manipulation.

2.youtube-transcript-api: For fetching YouTube video transcripts.

3.streamlit: For creating the web interface.

4.google-generativeai: For text summarization.

5.python-dotenv: To manage environment variables.

6.pathlib: For file and directory management.

You can install all these dependencies using the requirements.txt file.

**How to Use**:

1.Input the URL of a YouTube video into the web app.

2.The app will retrieve the transcript of the video.

3.Once the transcript is fetched, the app will summarize it and display the key points.
