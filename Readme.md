# Research Assistant Agent

This project uses a custom-built research assistant agent powered by **Google Gemini** and various tools to generate concise and well-researched articles on various topics. 

## Features

- **Search and Research**: The agent searches for the top two links related to a given topic and extracts relevant article content from those links.
- **Article Generation**: Based on the extracted data, the agent generates a short, informative, and well-structured article in the style of a New York Times researcher.
- **Real-time Article Generation**: The agent streams the process of collecting data and generating the article, giving users real-time feedback.

## Prerequisites

Before using the Research Assistant Agent, ensure you have the following:

- **Python 3.7+**
- **.env file**: For securely storing the Google API key.

## Setup

1. **Clone the Repository**

   Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-repo/research-assistant-agent.git
   cd Ai-Research-Agent

2. **Create a Virtual Environment**

It's a good practice to set up a virtual environment for the project:

```bash 
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows
```
3. **Install Dependencies**
Install the required dependencies using pip:
```bash
pip install -r requirements.txt

```
4. **Set Up API Key**
 
Create a .env file in the project root if not already present, and add your Google API key like this:
```bash
GOOGLE_API_KEY=your-api-key-here