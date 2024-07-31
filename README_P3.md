
## AI Mental Health Sentiment Analysis Project

### Project Overview
This project aims to provide insights into users' mental health states based on their textual statements. By leveraging machine learning and natural language processing techniques, we can predict and analyze mental health statuses to offer valuable support and guidance.

### Team Responsibilities
1. **Data Preprocessing**:
   - Marcellus is responsible for cleaning and preprocessing the dataset, ensuring the data is ready for training and analysis.
   
2. **Model Training**:
   - Dwann trained a linear Support Vector Classifier (SVC) model to classify mental health statuses based on textual input.

3. **OpenAI Prompts Integration**:
   - Kyle developed prompts using OpenAI's language model to enhance model predictions and provide meaningful responses based on the predicted mental health statuses.

4. **Gradio App Integration**:
   - Kanish integrated the trained model into a Gradio app, creating an interactive user interface where users can input their statements and receive corresponding mental health status predictions.

### How It Works
- **User Interface**: The Gradio app features two textboxes. Users can enter their statements in the input textbox, and the predicted mental health status will be displayed in the output textbox.
- **Prediction Process**: The app processes user inputs through the trained linear SVC model and provides insights into the user's mental state.
- **Model Integration**: The app combines the power of the trained machine learning model with OpenAI's language model prompts to deliver accurate and helpful mental health predictions.

### Usage
1. **Launch the Gradio App**:
   - Run the Gradio app to start the local server.
2. **Input Statement**:
   - Enter your statement about your mental state in the provided textbox.
3. **Receive Prediction**:
   - View the predicted mental health status in the output textbox.

### Example Statements
- "I have been feeling very anxious and stressed lately."
- "I am experiencing severe depression and can't find motivation."
- "I feel normal and haven't had any mental health issues recently."
- "I've had suicidal thoughts and feel hopeless."
- "I'm struggling with bipolar disorder and my mood swings are intense."

### Purpose
The goal of this project is to offer a tool that can help users gain insights into their mental health by analyzing their statements. This can provide a starting point for seeking further support or understanding one's mental state better.

