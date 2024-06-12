# Gemini Quizify

## Overview
Gemini Quizify is an AI-generated quiz tool designed to provide educators and students with an accessible and effective means to reinforce their understanding of various topics. By leveraging AI technology, the tool dynamically generates quizzes based on user-provided documents, offering instant feedback and detailed explanations. This approach facilitates deeper comprehension and retention of knowledge, ultimately enhancing the learning experience.

## Features
- **Dynamic Quiz Generation**: Create quizzes tailored to user-provided PDFs.
- **Instant Feedback**: Receive immediate feedback on quiz responses to aid in understanding and retention.
- **Detailed Explanations**: Gain comprehensive explanations for each quiz question to deepen knowledge.
- **User-Friendly Interface**: Easily navigate through the quiz with a seamless user interface built with Streamlit.
- **Customizable Quizzes**: Select topics and the number of questions to tailor the quiz to individual learning needs.

## Tech Stack
- **Google Cloud & Vertex AI**: Utilized for setting up the project, managing authentication, and leveraging advanced AI capabilities.
- **Streamlit**: Employed for creating a user-friendly interface for document ingestion and quiz interaction.
- **PyPDFLoader**: Used for processing PDFs and extracting content to generate quizzes.
- **Vertex AI Embeddings & Langchain**: Implemented for embedding documents and generating context-aware quiz questions.
- **Chroma DB**: Utilized for transforming and storing data to facilitate efficient quiz question generation.

### Acknowledgements
A special thank you to Radical AI for providing the foundation of this project. Their support and resources have been invaluable in developing Gemini Quizify, ensuring that we can offer a robust and effective learning tool for students and learners worldwide.
