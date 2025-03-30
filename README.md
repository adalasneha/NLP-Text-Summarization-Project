📌 NLP Text Summarization Project

🚀 Overview

This project implements text summarization using Natural Language Processing (NLP) techniques. It supports:

Extractive Summarization (TextRank algorithm)
Abstractive Summarization (using BART Transformer model)
TF-IDF for keyword extraction
POS Tagging & Chunking
A Streamlit UI for user interaction

📂 Dataset Used

CNN/DailyMail Dataset (from datasets library)
Automatically downloaded in the script

🛠️ Installation & Setup

🔹 Install Dependencies

pip install datasets nltk spacy scikit-learn transformers streamlit pyngrok

🔹 Run the Summarization Code

python app.py

🔹 Deploy with Streamlit & ngrok in Google Colab

!streamlit run app.py &>/dev/null &
from pyngrok import ngrok
public_url = ngrok.connect(port="8501")
print("Public URL:", public_url)

📜 Features

✅ Text Summarization (Extractive & Abstractive)
✅ TF-IDF Keyword Extraction
✅ POS Tagging & Chunking
✅ Interactive Streamlit UI
✅ Deployable via Google Colab & GitHub

📌 How to Use

Enter the text you want to summarize in the UI.
Click 'Summarize' to generate the summary.
View the Extractive & Abstractive Summaries.

📎 Example Input Text

Artificial Intelligence (AI) has rapidly transformed the way we interact with technology. NLP enables machines to understand, interpret, and generate human language...

📌 Example Output

Generated Summary: NLP enables machines to process human language with high accuracy using techniques like tokenization, POS tagging, and machine translation.

📤 Upload to GitHub

git init
git add .
git commit -m "Initial commit - NLP Text Summarization"
git branch -M main
git remote add origin https://github.com/adalasneha/NLP-Text-Summarization.git
git push -u origin main

🏆 Future Improvements

Support for more languages
Integration with GPT models for better summaries
Enhancements to UI & UX

📌 Contributing

Feel free to fork, improve, and contribute to this project!

📜 License

This project is licensed under the MIT License.



📌 Contributing

Feel free to fork, improve, and contribute to this project!

📜 License

This project is licensed under the MIT License.
