Voice-Driven AI Chatbot for Early Childhood Education
Project Overview
This project develops a voice-enabled AI chatbot designed to facilitate interactive learning for children aged 3-7. By leveraging advanced technologies like Retrieval-Augmented Generation (RAG), LangChain, and the Gemini API, the system delivers a mobile-first, engaging educational experience. The chatbot supports multilingual interaction, dynamic content delivery, and voice-based communication.

Key Features
Voice Input: Captures and transcribes children's spoken queries into text.
AI-Powered Responses: Uses RAG and LangChain with the Gemini API to analyze queries and generate contextually accurate responses.
Text-to-Speech Output: Converts AI-generated text responses into audio for an interactive experience.
Mobile App: A child-friendly, visually dynamic mobile application tailored for intuitive learning.
Multilingual Support: Seamlessly handles queries in Urdu and English.
File Processing: Allows the upload of PDFs and MP4 files for extracting content and generating responses.
Technologies Used
Frontend: React Native for mobile app development.
Backend: LangChain with Node.js for query processing and response generation.
Database: Cloud-based database for user interactions and logs.
APIs: Gemini API, Google Speech-to-Text, Google Text-to-Speech
AI Model: RAG for enhanced query understanding and context retrieval.
Setup and Usage
Clone the repository.
Install dependencies using npm install.
Configure API keys for Gemini, Google services, and LangChain.
Build and run the mobile app:
For Android: react-native run-android
For iOS: react-native run-ios
Interact with the app via voice commands or file uploads.
Prototype Instructions
Open the Colab Notebook (provided in the repository) for initial testing.
Enable microphone access for voice input or upload a file for processing.
Run the notebook cells step-by-step and observe the chatbot's functionality.
Troubleshooting
Ensure microphone and internet permissions are enabled on the mobile device.
Verify API credentials if responses are not generated.
Check for stable internet connectivity during API interactions.
Re-upload files if processing errors occur.
Contributors
Muhammad Haider Hamayoun: Speech recognition and app deployment.
Tuba Saleem: Backend integration and LangChain workflows.
Husna Sarwar: AI integration with Gemini API and chatbot logic.
Muhammad Umar Qureshi: Mobile app development (React Native) and UI/UX.
