# HuggingFace-YT-Web-Summarizer

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/release/python-390/)
[![Streamlit](https://img.shields.io/badge/Streamlit-%230078D7-blue?style=flat&logo=streamlit&logoColor=white)](https://streamlit.io/)
[![LangChain](https://img.shields.io/badge/LangChain-%232AA198-blue?style=flat&logo=langchain&logoColor=white)](https://langchain.readthedocs.io/en/latest/index.html)
[![Hugging Face Transformers](https://img.shields.io/badge/Transformers-%23FFD200-black?style=flat&logo=huggingface&logoColor=black)](https://huggingface.co/transformers/)
[![LangSmith](https://img.shields.io/badge/LangSmith-%23000000-blue?style=flat&logo=langsmith&logoColor=white)](https://smith.langchain.com/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Models-blue)](https://huggingface.co/models)

**HuggingFace-YT-Web-Summarizer** is a robust Streamlit application designed to efficiently extract and summarize content from both YouTube videos and web pages. Leveraging the power of LangChain and Hugging Face's state-of-the-art models, including **Mistral-Small-24B-Base-2501**, this tool provides concise summaries, enhancing information accessibility and saving valuable time.


## 🚀 Features

-   **Versatile Content Extraction:**
    -   YouTube Video Summarization: Utilizes `pytube`, `youtube_transcript_api`, and `yt-dlp` to extract transcripts, even when subtitles are unavailable.
    -   Website Summarization: Employs `UnstructuredURLLoader` to fetch and process web content from various URLs.
-   **AI-Powered Summarization:** Leverages Hugging Face Transformer models, specifically **`mistralai/Mistral-Small-24B-Base-2501`**, to generate accurate and concise summaries, tailored to the content's core themes.
-   **LangChain Integration:** Seamlessly integrates LangChain for efficient document processing, chaining operations, and tool utilization.
-   **Interactive Streamlit UI:** Provides a user-friendly interface for easy interaction and intuitive navigation.
-   **LangSmith Tracing:** Integrates LangSmith for comprehensive tracking, debugging, and performance optimization of LangChain execution.
-   **Error Handling and Validation:** Implements robust error handling and input validation using `validators` to ensure smooth operation.

## 📦 Installation

1.  **Clone the repository:**

    ```bash
    git clone [https://github.com/laavanjan/HuggingFace-YT-Web-Summarizer.git](https://github.com/laavanjan/HuggingFace-YT-Web-Summarizer.git)
    cd HuggingFace-YT-Web-Summarizer
    ```

2.  **Create a virtual environment (recommended):**

    ```bash
    conda create -p venv
    conda activate venv/
    ```

3.  **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4.  **Set up your `.env` file with the required API keys:**

    ```
    LANGCHAIN_API_KEY=your_langchain_key
    LANGCHAIN_PROJECT=your_project_name
    HF_TOKEN=your_huggingface_api_key
    ```

## 🛠 Usage

1.  **Run the Streamlit app:**

    ```bash
    streamlit run app.py
    ```

2.  **Open the application in your web browser.**

3.  **Enter a YouTube video URL or Website URL in the provided text input.**

4.  **Click the "Summarize the Content from YT or Website" button.**

5.  **View the generated summary in the output area.**

## 🎯 How It Works

1.  The application receives a URL input from the user.
2.  Based on the URL type (YouTube or website), it employs the appropriate extraction method.
3.  Extracted text is processed and fed into the **`mistralai/Mistral-Small-24B-Base-2501`** Hugging Face Transformer model via LangChain.
4.  The model generates a concise summary, which is then displayed to the user.
5.  LangSmith traces the execution flow, allowing for detailed debugging and performance analysis.

## 🖼 Screenshots

*(Add screenshots here to showcase the application's interface and functionality)*

## 🔧 Technologies Used

-   Python
-   Streamlit
-   LangChain
-   Hugging Face Transformers (Specifically **`mistralai/Mistral-Small-24B-Base-2501`**) ([Hugging Face Models](https://huggingface.co/models))
-   YouTube Transcript API
-   yt-dlp
-   pytube
-   UnstructuredURLLoader
-   validators
-   LangSmith

## 📝 License

This project is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0).

## 📌 Author

Developed by Laavanjan | Faculty of IT, Batch 22

## 💡 Contributing

Contributions and suggestions are highly welcome! Feel free to fork the repository and submit a pull request. For significant changes, please open an issue to discuss them first.

## 📧 Contact

Laavanjan - [Your Email Address] - [Your LinkedIn Profile (Optional)]
