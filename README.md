# 💬 GenAI Chatbot with Streamlit

A sophisticated conversational AI chatbot built with Streamlit and powered by Groq's Llama 3.3 model. This application provides a user-friendly web interface for interactive conversations with advanced language models.

## 🚀 Features

- **Interactive Chat Interface**: Clean and intuitive Streamlit-based web UI
- **Persistent Chat History**: Maintains conversation context throughout the session
- **Advanced AI Model**: Powered by Llama 3.3 70B Versatile model via Groq API
- **Real-time Responses**: Fast and efficient message processing
- **Responsive Design**: Centered layout optimized for various screen sizes
- **Session Management**: Automatic chat history storage and retrieval

## 🛠️ Technology Stack

- **Frontend**: Streamlit
- **AI/ML**: LangChain + Groq API
- **Language Model**: Llama 3.3 70B Versatile
- **Environment Management**: Python-dotenv
- **Python Version**: 3.7+

## 📋 Prerequisites

Before running this application, ensure you have:

- Python 3.7 or higher installed
- A Groq API key (sign up at [Groq Console](https://console.groq.com/))
- Internet connection for API calls

## ⚙️ Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/abdull6771/Gen-ai-chatbot-with-streamlit
   cd "Gen-ai-chatbot-with-streamlit"
   ```

2. **Create a virtual environment** (recommended):

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**:
   - Copy the `.env.example` file to `.env` (if provided)
   - Or create a new `.env` file in the project root
   - Add your Groq API key:
   ```env
   GROQ_API_KEY=your_groq_api_key_here
   ```

## 🚀 Usage

1. **Start the application**:

   ```bash
   streamlit run chatbot.py
   ```

2. **Access the chatbot**:

   - Open your web browser
   - Navigate to `http://localhost:8501`
   - Start chatting with the AI assistant

3. **Interact with the chatbot**:
   - Type your message in the chat input box
   - Press Enter or click the send button
   - View the AI's response in real-time
   - Continue the conversation naturally

## 📁 Project Structure

```
GenAI Chatbot with Streamlit/
├── chatbot.py          # Main application file
├── requirements.txt    # Python dependencies
├── .env               # Environment variables (API keys)
└── README.md          # Project documentation
```

## 🔧 Configuration

The chatbot can be customized by modifying the following parameters in `chatbot.py`:

- **Model**: Change the model name in the `ChatGroq` initialization
- **Temperature**: Adjust the creativity/randomness (0.0 = deterministic, 1.0 = creative)
- **System Prompt**: Modify the assistant's behavior and personality
- **Page Configuration**: Update title, icon, and layout settings

## 🤖 Model Information

- **Model**: Llama 3.3 70B Versatile
- **Provider**: Groq
- **Temperature**: 0.0 (for consistent, factual responses)
- **Context**: Maintains full conversation history

## 🔐 Security Notes

- Keep your `.env` file secure and never commit it to version control
- Add `.env` to your `.gitignore` file
- Regularly rotate your API keys
- Monitor your API usage and costs

## 🐛 Troubleshooting

### Common Issues

1. **API Key Error**:

   - Ensure your Groq API key is correctly set in the `.env` file
   - Verify the API key is valid and has sufficient credits

2. **Import Errors**:

   - Make sure all dependencies are installed: `pip install -r requirements.txt`
   - Verify you're using the correct Python environment

3. **Streamlit Not Starting**:
   - Check if the port 8501 is available
   - Try running on a different port: `streamlit run chatbot.py --server.port 8502`

### Performance Tips

- Clear chat history periodically for better performance
- Monitor API usage to avoid rate limits
- Consider implementing caching for frequently asked questions

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/new-feature`)
5. Create a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [Streamlit](https://streamlit.io/) - For the amazing web framework
- [LangChain](https://langchain.com/) - For the powerful language model integration
- [Groq](https://groq.com/) - For providing fast inference infrastructure
- [Meta](https://ai.meta.com/) - For the Llama model architecture

## 📞 Support

For support, questions, or suggestions:

- Open an issue in this repository
- Contact: [your-email@example.com]
- Documentation: [Link to detailed documentation if available]

---

**Happy Chatting! 🎉**

_Built using Streamlit and Groq_
