# Agentsphere - NIAT 

This repository contains examples for learning Google's Agent Development Kit (ADK), a powerful framework for building LLM-powered agents.

## Getting Started

### Setup Environment

You only need to create one virtual environment for all examples in this course. Follow these steps to set it up:

```bash
# Create virtual environment in the root directory
python -m venv .venv

# Activate (each new terminal)
# macOS/Linux:
source .venv/bin/activate
# Windows CMD:
.venv\Scripts\activate.bat
# Windows PowerShell:
.venv\Scripts\Activate.ps1

# Install dependencies
pip install -r requirements.txt
```

Once set up, this single environment will work for all examples in the repository.

### Setting Up API Keys

1. Create an account in Google Cloud https://cloud.google.com/?hl=en
2. Create a new project
3. Go to https://aistudio.google.com/apikey
4. Create an API key
5. Assign key to the project
6. Connect to a billing account

Each example folder contains a `.env.example` file. For each project you want to run:

1. Navigate to the example folder
2. Rename `.env.example` to `.env` 
3. Open the `.env` file and replace the placeholder with your API key:
   ```
   GOOGLE_API_KEY=your_api_key_here
   ```

utputs through feedback loops.

## Official Documentation

For more detailed information, check out the official ADK documentation:
- https://google.github.io/adk-docs/get-started/quickstart

## Support

[www.learnapart.online](https://learnapart.online/workshops)

In the community you'll find:
- Weekly coaching and support calls
- Early access to code from YouTube projects
- A network of AI developers of all skill levels ready to help
- Behind-the-scenes looks at how these apps are built
