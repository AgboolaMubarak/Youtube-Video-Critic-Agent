# Youtube-Video-Critic-Agent
An AI-powered agent that watches YouTube videos, analyzes the transcript, and provides a critical summary along with a sentiment score.

****

###  Features
* **Summarization & Critique:** Uses **Google Flan-T5** to generate concise summaries and constructive criticism of the video content.
* **Sentiment Analysis:** Uses **DistilBERT** (`distilbert-base-uncased-finetuned-sst-2-english`) to gauge the emotional tone of the video (Positive/Negative).
* **Automated Transcript Fetching:** Extracts video text directly via the YouTube API.

###  Tech Stack
* **Python**
* **Hugging Face Transformers**
* **Google Flan-T5** (LLM for text generation)
* **DistilBERT** (Sentiment Analysis)
* **LangChain** (Optional, if you used it for chaining)

###  How to Run

You can run this project directly in the browser using Google Colab.

<!-- REPLACE THE LINK BELOW WITH THE LINK TO YOUR SPECIFIC NOTEBOOK IN YOUR REPO -->
[![Open In Colab]](https://colab.research.google.com/drive/1NAGd7zy8xMEs5CR7FYC4KYlq5pP_v_kv?usp=sharing))

1. Click the "Open in Colab" badge above.
2. Add your Hugging Face API token when prompted (or in the secrets tab).
3. Run the cells to install dependencies and start the agent.
4. Input a YouTube URL and watch the agent work!
