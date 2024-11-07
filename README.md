# Dynamic Information Retrieval Agent
This project is a dynamic AI-based information retrieval agent that allows users to extract specific data from the web based on user-defined prompts. The system can process CSV files or Google Sheets as input, fetch information using web search APIs, and use LLMs to parse and present results.

## Project Description
This project is a dynamic AI-based information retrieval agent that extracts specific data from the web.

## Setup Instructions
1. Install required libraries.
2. Set up environment variables.

## Usage Guide
Detailed steps to use the project.

### How to Use the Agent
1. Upload your CSV file or connect a Google Sheet.
2. Enter your query prompt with placeholders (e.g., "Retrieve the email for {company}").
3. Start the agent to fetch and display results. Results can be downloaded as a CSV.

- **SerpAPI**: Go to [serpapi.com](https://serpapi.com/), sign up, and get an API key.
- **OpenAI API**: Sign up on [openai.com](https://openai.com/) and create an API key.
- **Google Sheets API**: Enable the Sheets API in the Google Cloud Console and generate an API key.

### Setting up Environment Variables
Create a `.env` file in the project root and add your API keys as follows:
SERPAPI_KEY=your_serpapi_key
OPENAI_API_KEY=your_openai_key
SHEETS_API_KEY=your_sheets_key
