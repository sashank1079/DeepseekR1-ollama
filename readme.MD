# 🧳 Travel Advisor

## Overview

Travel Advisor is an AI-powered application designed to provide users with expert travel advice and recommendations. Built using Streamlit and LangChain, this application leverages advanced language models to offer personalized travel tips and insights.

## Features

- 🌍 Expert travel advice and recommendations
- 🧠 AI-driven insights using LangChain and Ollama
- 💬 Interactive chat interface for seamless user interaction
- 🎨 Customizable UI with Streamlit

## DeepSeek-R1 Model

The Travel Advisor application utilizes the `deepseek-r1` model, a powerful language model designed to provide accurate and insightful travel advice. This model is integrated into the application to enhance the quality of responses and ensure users receive the best possible recommendations.

- **Model Version**: `deepseek-r1:1.5b`
- **Capabilities**: 
  - Provides expert travel advice
  - Offers personalized recommendations
  - Enhances user interaction with AI-driven insights

  You can download other models on ollama and add them to models list in `app.py`

## Installation

To set up the Travel Advisor application, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sashank1079/travel-advisor.git
   cd travel-advisor
   ```

2. **Create a virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**:
   ```bash
   streamlit run app.py
   ```

## Usage

- Launch the application using the command above.
- Interact with the AI travel advisor through the chat interface.
- Select different models and configurations from the sidebar to customize your experience.

## Configuration

- The application uses the `deepseek-r1:1.5b` model by default.
- You can modify the model and other settings in the sidebar.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- Built with [Streamlit](https://streamlit.io/)
- Powered by [LangChain](https://python.langchain.com/) and [Ollama](https://ollama.ai/)
