# MarketMeNow

MarketMeNow is an agentic marketing automation system designed for startups. It explores how AI can autonomously execute core marketing workflows, reducing dependency on traditional agencies. This project serves as a technical exploration of automating content strategy, outreach, and campaign management.

## Key Features
*   **AI-Driven Content Ideation:** Generates marketing content and campaign ideas based on target audience and goals.
*   **Automated Outreach Workflows:** Orchestrates personalized email sequences and social media interactions.
*   **Campaign Performance Analysis:** Provides basic insights and metrics on executed marketing activities.
*   **Modular Agent Architecture:** Built with composable, single-responsibility agents for different marketing functions.

## Tech Stack
*   **Backend:** Python, FastAPI
*   **AI/ML:** LangChain, OpenAI API
*   **Database:** PostgreSQL
*   **Tools:** Various APIs for email, social media, and analytics

## Getting Started
1.  Clone the repo: `git clone https://github.com/zoreanuj/marketmenow.git`
2.  Install dependencies: `pip install -r requirements.txt`
3.  Set up environment variables (copy `.env.example` to `.env` and add your API keys).
4.  Run the application: `uvicorn app.main:app --reload`