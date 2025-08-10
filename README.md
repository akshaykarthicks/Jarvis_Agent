# Jarvis 🤖

A modular, extensible Python agent framework for building intelligent assistants and automation tools. Jarvis is designed for rapid prototyping and easy integration of custom prompts, tools, and workflows.

## 🚀 Features

- **🧠 Agent Framework**: Easily create and run intelligent agents with minimal setup
- **📝 Prompt Management**: Modular prompt system for flexible agent behavior and responses
- **🔧 Tool Integration**: Seamlessly plug in custom tools for automation and data processing
- **⚡ Extensible Design**: Add new capabilities with minimal code changes and maximum flexibility
- **📱 Voice AI Integration**: Built-in support for LiveKit voice AI capabilities

---

## 📋 Prerequisites

- Python 3.8 or higher
- [pip](https://pip.pypa.io/en/stable/) package manager
- Git (for cloning the repository)

---

## 🛠️ Installation

### 1. Clone the Repository
```bash
git clone <your-repo-url>
cd Jarvis
```

### 2. Set Up Virtual Environment (Recommended)
```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# On macOS/Linux:
source venv/bin/activate
# On Windows:
venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

---

## 🎯 Quick Start

### Basic Usage
Run the main agent with default settings:
```bash
python agent.py
```

### Mobile App Development
Create an Android voice assistant app using LiveKit:
```bash
lk app create --template android-voice-assistant \
  --sandbox <token_server_sandbox_id> \
  --api-key <your_api_key> \
  --api-secret <your_secret_key>
```

---

## 📁 Project Structure

```
Jarvis/
├── agent.py            # Main entry point for the agent
├── prompts.py          # Prompt templates and logic
├── tools.py            # Tool definitions and integrations
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
└── venv/              # Virtual environment (optional)
```

### File Descriptions

- **`agent.py`**: Core agent logic and main execution loop
- **`prompts.py`**: Configurable prompt templates for different agent behaviors
- **`tools.py`**: Custom tool implementations and third-party integrations
- **`requirements.txt`**: All Python package dependencies

---

## 🔗 Useful Resources

### LiveKit Documentation
- [**Voice AI Getting Started**](https://docs.livekit.io/agents/start/voice-ai/) - Complete guide for voice AI integration
- [**CLI Setup**](https://docs.livekit.io/home/cli/cli-setup/) - Command-line interface configuration
- [**LiveKit Sandbox**](https://cloud.livekit.io/projects/p_1p1xfqksh5k/sandbox) - Online development environment

---

## ⚙️ Customization

### Modifying Agent Behavior
Edit `prompts.py` to customize how your agent responds:
```python
# Example prompt modification
SYSTEM_PROMPT = "You are a helpful assistant specialized in..."
```

### Adding New Tools
Extend functionality by adding tools in `tools.py`:
```python
def my_custom_tool(input_data):
    # Your tool logic here
    return processed_result
```

---

## 🤝 Contributing

We welcome contributions! Here's how to get started:

### Development Workflow
1. **Fork** the repository on GitHub
2. **Clone** your fork locally
3. **Create** a new branch for your feature:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Make** your changes following our guidelines
5. **Test** your changes thoroughly
6. **Commit** with clear, descriptive messages
7. **Push** to your fork and submit a **Pull Request**


---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---


