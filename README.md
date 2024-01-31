# AI Mentor 

AI Mentor is a conversational chatbot developed using Streamlit and OpenAI's GPT-3.5-turbo. This chatbot is designed to act as an AI Technical Expert for Artificial Intelligence, providing guidance and assistance to users with their AI-related questions and concerns.

## Features

- **Natural Language Interaction:** Engage in natural language conversations with the AI Mentor.
- **AI Technical Expertise:** Provides informative and relevant responses to questions about artificial intelligence, machine learning, deep learning, natural language processing, computer vision, and related topics.
- **User Guidance:** Guides users through queries related to AI, maintaining a polite and professional tone.
- **Educational Focus:** Prioritizes assisting and educating students in the field of Artificial Intelligence, enhancing their learning experience.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Pip (Python package installer)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/[YourUsername]/AI-Mentor-ChatBot.git
   cd AI-Mentor-ChatBot
   ```

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

### Usage

Run the Streamlit app:

```bash
streamlit run ai_mentor_chatbot.py
```

The app will open in your default web browser, allowing you to interact with the AI Mentor chatbot.

## How It Works

1. **User Input:** Enter your queries in natural language through the text input.
2. **AI Response:** AI Mentor generates responses using OpenAI's GPT-3.5-turbo.
3. **Chat History:** View the chat history, including user queries and AI responses.
4. **Educational Guidance:** AI Mentor prioritizes guiding users through AI-related queries and maintaining a helpful and educational approach.

## Additional Information

- **OpenAI API Key:** Ensure that you have added your OpenAI API key in the appropriate place within the code.

```python
openai_api_key = st.secrets["OPENAI_API_KEY"]
```

## Guidelines

AI Mentor follows specific guidelines to provide a positive user experience:

- Greets the user and politely asks for their name.
- Provides informative responses to AI-related queries.
- Avoids discussions on sensitive, offensive, or harmful content.
- Politely steers the conversation back to AI if the user asks about unrelated topics.
- Maintains a patient and considerate tone while responding to user queries.
- Limits AI responses to a maximum of 100 words.
- Focuses on assisting and educating students in the field of Artificial Intelligence.

## Limitations

- The chatbot's quality of responses depends on the user's input and the content of the AI model.
- Long paragraphs in AI responses are limited to 100 words.

## Contributors

- [Muhammad Zain Attiq]
- [Muhammad Haris Tariq]

Feel free to contribute to the project by submitting issues or pull requests.


## Acknowledgments

- Special thanks to OpenAI for providing the GPT-3.5-turbo model and Streamlit for providing the go-to GUI.
- Inspired by the capabilities of language models for natural language interaction and education in AI.
