Tomato Farming Advisory AI System: Disease Detection, Adaptive Chatbot & Early Warnings
📌 Project Overview
The Tomato Farming Advisory AI System is an AI-powered tool designed to assist smallholder and commercial tomato farmers in identifying diseases from leaf images, offering treatment advice, and providing real-time guidance through a smart chatbot. It also integrates early warnings for pests, drought, and potential outbreaks using satellite and local data.

The project combines computer vision, natural language processing, and real-time advisory features to ensure farmers make timely, informed, and cost-effective decisions that improve yield, reduce crop losses, and promote sustainable agriculture.

✨ Key Features of the Project
🔍 AI-based Disease Detection using tomato leaf images.

🤖 Adaptive Chatbot Assistant trained on tomato farming practices, FAQs, and local farming strategies.

⚠️ Early Warning System for drought, pest outbreaks, and climate threats.

💬 User-friendly Interface for uploading leaf images and chatting with the assistant.

🌍 Localized Advisory using Swahili-English hybrid for rural accessibility.

☁️ Streamlit-based Web App Deployment with minimal setup requirements.

🛠️ Project Implementation Steps
1. Define the Problem and Scope
Many farmers lack access to timely diagnosis of plant diseases, expert advice, or forecasts for threats like drought or pests.

This project targets tomato farming — a high-value but vulnerable crop — with a digital assistant combining multiple AI technologies.

2. Data Collection
Collected and used datasets of tomato leaf images labeled with disease types (e.g., bacterial spot, early blight, late blight, etc.).

Acquired text data on best tomato farming practices, symptoms, and treatment guides for chatbot training.

Sourced local climate and pest outbreak data for early warning integration.

3. Model Selection
Chose MobileNetV2 as a lightweight, accurate CNN architecture for disease classification.

Used a Fine-Tuned Tfidf + Retrieval-based NLP chatbot or a LLM-based assistant for advisory responses.

Integrated external APIs or datasets for weather/drought alerts.

4. Model Training and Evaluation
Preprocessed image data (resizing, normalization, augmentation).

Trained the CNN model for multi-class classification using TensorFlow/Keras.

Evaluated the model using accuracy, confusion matrix, precision-recall metrics.

Tested chatbot responses for context relevance and farming correctness.

5. Build a User Interface
Designed a Streamlit web interface with:

Leaf image upload section.

Disease prediction output.

Chat window for advisory interaction.

Alert section for early warnings.

6. Deployment
Deployed the app using Streamlit Cloud for easy access via browser.

GitHub repository structured with clear folders for models, UI, assets, and documentation.

7. Testing and Validation
Conducted unit and integration testing.

Verified real-life usability with simulated farmer scenarios.

Collected feedback from potential end-users (e.g., agronomists, students).

8. Documentation and Reporting
Prepared user and technical documentation.

Included README, project report, and model cards.

All dependencies listed in requirements.txt.

🧩 Handling Challenges
Model Accuracy vs Speed: Balancing lightweight models with high classification accuracy.

Dataset Diversity: Limited disease images from African contexts; addressed using augmentation and transfer learning.

Chatbot Relevance: Ensuring chatbot remains factual, regionally accurate, and simple.

Deployment Constraints: Ensured small model size for deployment within Streamlit’s memory limits.

Internet Access Gaps: Worked on making the app offline-capable in future iterations.

✅ Expected Outcomes
Quick, accurate diagnosis of tomato leaf diseases.

Improved farming decisions from real-time advisory via chatbot.

Reduced crop losses and improved productivity.

Broader adoption of digital tools by farmers with low technical experience.

A scalable solution adaptable to other crops and regions.

💡 Why This Project?
Agricultural productivity is key to food security, especially in Sub-Saharan Africa.

Tomatoes are a staple crop yet suffer from preventable diseases.

Farmers often lack access to agronomists and expert advice in real-time.

This project bridges that gap with an easy-to-use, AI-powered assistant that empowers farmers with actionable insights.
