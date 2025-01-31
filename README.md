## Overview
🚀 **Gen-AI Powered Cold Email Generator** – Revolutionizing business outreach with AI!  

This cutting-edge **AI-driven Cold Email Generator** seamlessly crafts highly personalized and impactful emails by analyzing job descriptions scraped from company career pages. Leveraging the power of **LLama-3.3, Groq Cloud, LangChain, and ChromaDB**, this tool intelligently extracts job postings and formulates professional cold emails that enhance engagement and conversion rates. Whether you're an AI enthusiast, business development professional, or recruiter, this tool streamlines communication, making outreach more **efficient, scalable, and results-driven**!  

## Tech Stack
- **LLama-3.3-70B** (via Groq Cloud) - LLM used for job extraction & email generation
- **LangChain** - Prompt engineering and AI pipeline
- **ChromaDB** - Vector database for portfolio management
- **Python** - Backend scripting
- **dotenv** - Secure API key management

## Project Structure
```
cold-email-generator/
│── app/  
│   │── resource/          # Contains necessary data files like portfolio.csv
│   │── .env               # Stores environment variables like API Key
│   │── chains.py          # AI processing logic (job extraction & email generation)  
│   │── main.py            # Main script for execution  
│   │── portfolio.py       # Portfolio data storage & retrieval via ChromaDB  
│   │── utils.py           # Utility functions (text cleaning, preprocessing)  
│── requirements.txt       # Python dependencies  
│── README.md              # Project documentation
```

## Installation
### Clone the Repository
```bash
git clone https://github.com/shouvik27/COLD-EMAIL-GENERATOR.git
cd app
```

### Running the application
### To start the application navigate to the app folder and then run the below command in terminal.
```python
python multilabel/main.py --config /pathtoconfig.yaml
```




