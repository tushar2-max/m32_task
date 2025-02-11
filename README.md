# 🤖 Chatbot Project

## 🌟 Overview
This project is a chatbot application utilizing a Large Language Model (LLM) to provide intelligent responses. The chatbot is designed to leverage OpenAI's API key for processing natural language queries and employs a vector database for efficient storage and retrieval of conversational context.

## 📂 Project Structure
```
├── .git/                 # Git repository
├── chatbotAcademy/       # Core application logic
├── chatbotApp/           # Chatbot application module
├── static/               # Static files
├── venv/                 # Virtual environment
├── .env                  # Environment variables
├── .gitignore            # Git ignore file
├── db.sqlite3            # SQLite database
├── manage.py             # Django management script
├── requirements.txt      # Project dependencies
```

## ⚙️ Prerequisites
Before running the chatbot, ensure you have the following:
- 🐍 Python installed (version 3.8 or higher recommended)
- 🔑 OpenAI API key
- 💾 Virtual environment set up
- 📦 Required dependencies installed

## 🚀 Installation
1. Clone the repository:
   ```sh
   git clone <repository-url>
   cd chatbotProject
   ```

2. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

4. Set up the environment variables:
   - Create a `.env` file in the root directory
   - Add the following content:
     ```sh
     OPENAI_API_KEY=<your-openai-api-key>
     ```

5. Run migrations and start the server:
   ```sh
   python manage.py migrate
   python manage.py runserver
   ```

## 🔥 Features
- 🤖 **LLM-based chatbot**: Uses OpenAI's API for intelligent conversation.
- 🗃️ **Vector Database**: Stores and retrieves conversational context efficiently.
- 🌐 **Web Interface**: Built using Django for seamless interaction.

## 🛠️ Usage
Once the server is running, you can access the chatbot via:
```
http://127.0.0.1:8000/
```

## 🔮 Future Enhancements
- 🔗 Integrate additional AI models for improved responses
- 🧑‍🤝‍🧑 Implement multi-user chat support
- 🎨 Enhance UI with frontend frameworks like React

## 📜 License
This project is open-source and available under the MIT License.

## 📩 Contact
For any inquiries or contributions, feel free to reach out! 🚀

