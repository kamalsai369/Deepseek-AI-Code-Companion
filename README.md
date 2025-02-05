<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DeepSeek Code Companion</title>
    <style>
        body { font-family: Arial, sans-serif; line-height: 1.6; background-color: #f4f4f4; padding: 20px; }
        .container { max-width: 800px; margin: auto; background: #fff; padding: 20px; border-radius: 10px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); }
        h1, h2, h3 { color: #333; }
        code { background: #eee; padding: 3px 5px; border-radius: 5px; }
        pre { background: #222; color: #fff; padding: 10px; border-radius: 5px; overflow-x: auto; }
        ul { padding-left: 20px; }
    </style>
</head>
<body>
    <div class="container">
        <h1>🧠 DeepSeek Code Companion</h1>
        <p>🚀 Your AI Pair Programmer with Debugging Superpowers</p>
        <hr>
        
        <h2>🌟 About DeepSeek</h2>
        <p>DeepSeek is an AI-powered coding assistant designed to simplify your coding experience by providing:</p>
        <ul>
            <li>💡 Concise solutions to coding queries</li>
            <li>🐞 Debugging assistance with step-by-step suggestions</li>
            <li>📝 Code documentation and explanations</li>
            <li>🚀 Solution design guidance</li>
        </ul>
        
        <h2>⚙️ Key Features</h2>
        <ul>
            <li>✨ AI Model-Powered</li>
            <li>🐍 Python Expertise</li>
            <li>📋 Real-Time Debugging</li>
            <li>📖 Customizable Prompts</li>
            <li>💻 Interactive UI</li>
        </ul>
        
        <h2>🚀 Installation</h2>
        <h3>1️⃣ Download and Install Ollama</h3>
        <pre><code>curl -fsSL https://ollama.ai/install.sh | sh  # For macOS/Linux</code></pre>
        <p>For Windows, download and install from <a href="https://ollama.ai/">Ollama's website</a>.</p>

        <h3>2️⃣ Run the Ollama Model</h3>
        <pre><code>ollama run deepseek-r1:1.5b</code></pre>

        <h3>3️⃣ Clone the Repository</h3>
        <pre><code>git clone https://github.com/your-username/deepseek-code-companion.git
cd deepseek-code-companion</code></pre>

        <h3>4️⃣ Set Up a Virtual Environment</h3>
        <pre><code>python -m venv venv
source venv/bin/activate  # For macOS/Linux
venv\Scripts\activate     # For Windows</code></pre>

        <h3>5️⃣ Install Dependencies</h3>
        <pre><code>pip install -r requirements.txt</code></pre>

        <h3>6️⃣ Run the Application</h3>
        <pre><code>streamlit run app.py</code></pre>

        <h2>🔧 How It Works</h2>
        <p>DeepSeek leverages AI-powered prompt chains, a customizable LLM engine, session state management, and a sleek UI for the best coding experience.</p>
        
        <h2>💡 What's Next?</h2>
        <ul>
            <li>🌐 Expand support for additional programming languages</li>
            <li>🤖 Integrate with external debugging tools</li>
            <li>📊 Add visualization features</li>
            <li>🎨 More UI themes and configurations</li>
        </ul>
        
        <h2>🛠️ Contributing</h2>
        <p>We welcome contributions! Follow these steps:</p>
        <ol>
            <li>Fork the repository.</li>
            <li>Create a new branch for your feature/bugfix.</li>
            <li>Submit a pull request with detailed notes.</li>
        </ol>
        
        <h2>📜 License</h2>
        <p>This project is licensed under the MIT License.</p>
    </div>
</body>
</html>
