🧠 DeepSeek Code Companion

🚀 Your AI Pair Programmer with Debugging Superpowers

🌟 About DeepSeek

DeepSeek is an AI-powered coding assistant designed to simplify your coding experience by providing:

💡 Concise solutions to coding queries

🐞 Debugging assistance with step-by-step suggestions

📝 Code documentation and explanations

🚀 Solution design guidance

DeepSeek is powered by LangChain and Ollama, making it a robust tool for coders, developers, and learners alike.

⚙️ Key Features

✨ AI Model-Powered:Built using Ollama's large language model, providing seamless natural language processing for your coding needs.

🐍 Python Expertise:DeepSeek specializes in Python but is versatile enough to assist across multiple programming domains.

📋 Real-Time Debugging:Identify and fix bugs in your code with actionable insights.

📖 Customizable Prompts:Configure the AI's behavior to suit your workflow.

💻 Interactive UI:Powered by Streamlit for an engaging, modern, and sleek user interface.

🚀 Installation

1️⃣ Download and Install Ollama

DeepSeek relies on Ollama for AI processing. Install Ollama from the official website:

curl -fsSL https://ollama.ai/install.sh | sh  # For macOS/Linux

For Windows, download and install from Ollama's website.

2️⃣ Run the Ollama Model

Ensure Ollama is running by executing the following command:

ollama run deepseek-r1:1.5b

3️⃣ Clone the Repository

git clone https://github.com/your-username/deepseek-code-companion.git
cd deepseek-code-companion

4️⃣ Set Up a Virtual Environment

python -m venv venv
source venv/bin/activate  # For macOS/Linux
venv\Scripts\activate     # For Windows

5️⃣ Install Dependencies

pip install -r requirements.txt

6️⃣ Run the Application

Ensure the Ollama server is running locally on http://localhost:11434. Then, launch DeepSeek using:

streamlit run app.py

🎨 UI Showcase

Main Screen

🧠 DeepSeek welcomes you with:

A modern dark mode UI

An interactive chat experience

Sidebar Configurations

Choose between AI models.

View model capabilities in one glance.

Quick access to Ollama and LangChain.

🔧 How It Works

AI-Powered Prompt Chain:

Leverages ChatPromptTemplate to dynamically build prompts based on the conversation.

Ensures the context is preserved for better responses.

Customizable LLM Engine:

Uses ChatOllama with a temperature of 0.3 for concise, strategic solutions.

Session State Management:

Tracks the message history for seamless user experience.

Custom Styling with CSS:

Dark mode theme to reduce eye strain and improve focus.

💡 What's Next?

🌐 Expand support for additional programming languages.

🤖 Integrate with external debugging tools (e.g., PyLint, Black).

📊 Add visualization features for data structures and flow diagrams.

🎨 More UI themes and configurations.

🛠️ Contributing

We welcome contributions! Follow these steps to contribute:

Fork the repository.

Create a new branch for your feature/bugfix.

Submit a pull request with detailed notes.

📜 License

This project is licensed under the MIT License.

