# Hiring Agent ADK

A complete hiring automation system powered by AI agents to streamline technical candidate evaluation.

## 🔍 Features

### 🤖 5 Specialized AI Agents

- **RubricBuilder**: Creates evaluation criteria based on job descriptions
- **ResumeReviewer**: Analyzes candidate resumes against job requirements
- **GitHubValidator**: Verifies and validates GitHub account authenticity
- **GitHubReviewer**: Evaluates code quality and contributions
- **VerdictSynthesizer**: Compiles all evaluations into a final decision

### 🎛️ Core Components

- **Root Orchestrator**: Manages the entire evaluation workflow
- **Real-time GitHub API Integration**: Live account validation and metrics
- **Structured Evaluation Framework**: Objective, measurable criteria with scoring
- **End-to-End Workflow**: From job description to final HIRE/NO HIRE decision

## 🛠️ Technologies Used

- **Google ADK (Agent Development Kit)** - Agent framework
- **Gemini 3 Model** - LLM for agent intelligence
- **Python 3.8+** - Programming language
- **GitHub REST API** - Account validation
- **python-dotenv** - Environment management
- **requests** - HTTP client library

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Google Cloud account (for Gemini API)
- Basic understanding of Python and REST APIs
- GitHub account (optional, for testing)

## ⚡ Quick Start

1. Clone or navigate to the project directory:

   ```bash
   git clone https://github.com/ayush-yadavv/hiring-agent-adk.git
   cd hiring-agent-adk
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up environment variables:
   ```bash
   # Create .env file from example
   cp .env.example .env
   ```
4. Edit `.env` and add your API keys:

   ```
   GOOGLE_API_KEY=your_gemini_api_key
   GITHUB_TOKEN=your_github_token  # Optional
   ```

5. Run the application:

   ```bash
    # from parent directory (if using ADK web interface)
   cd ..
   adk web
   ```

## Configuration

Create a `.env` file in the project root with the following variables:

```
# Required: Gemini API Configuration
MODEL_NAME=gemini-flash-latest
GOOGLE_API_KEY=your_google_api_key_here

# Optional: GitHub Token (for higher rate limits)
# GITHUB_TOKEN=your_github_token_here
```

## Security

- Never commit your `.env` file to version control
- The `.gitignore` file is configured to exclude sensitive files
- Keep your API keys secure and never share them publicly

## Contributing

1. Fork the repository
2. Create a new branch for your feature
3. Commit your changes
4. Push to the branch
5. Submit a pull request
