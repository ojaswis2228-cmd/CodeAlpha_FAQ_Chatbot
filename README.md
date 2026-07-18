# 🎓 University Student Support FAQ Chatbot

This project was developed as part of the CodeAlpha Artificial Intelligence Internship.

## 📌 Project Overview

The University Student Support FAQ Chatbot is an AI-based chatbot that answers common student queries related to:

- Attendance
- Hostel facilities
- Semester fees
- Examinations
- Placements
- Library services
- Student portal
- Scholarships
- Internship letters

## 🧠 Technologies Used

- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorization
- Cosine Similarity
- Gradio
- Google Colab

## ⚙️ How It Works

1. The FAQ dataset is loaded using Pandas.
2. User questions are cleaned and converted into lowercase.
3. TF-IDF converts the questions into numerical vectors.
4. Cosine similarity compares the user query with stored FAQs.
5. The chatbot returns the most relevant answer.
6. If the similarity score is too low, a fallback response is displayed.

## 📂 Project Files

- `CodeAlpha_FAQ_Chatbot.ipynb` — Complete chatbot implementation
- `faqs.csv` — FAQ questions and answers
- `README.md` — Project documentation

## ▶️ How to Run

1. Open the notebook in Google Colab.
2. Run all cells.
3. Install the required libraries.
4. Launch the Gradio interface.
5. Enter a university-related question.

## ✨ Features

- Simple chat interface
- 35 university-related FAQs
- NLP-based question matching
- Confidence threshold for unknown questions
- Example questions for quick testing
- Interactive Gradio web interface

## 👩‍💻 Author

Ojaswi Singh
