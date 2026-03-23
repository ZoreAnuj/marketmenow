# MarketMeNow

MarketMeNow is an agentic marketing automation system designed for startups. It explores how AI can autonomously execute core marketing workflows, reducing dependency on traditional agencies. This project serves as a technical exploration of AI-driven marketing orchestration.

## Key Features
*   **Multi-Agent Orchestration:** Coordinates specialized AI agents for research, content creation, and distribution.
*   **Automated Content Pipeline:** Generates and schedules marketing copy and social media posts.
*   **Integrated Tooling:** Connects with platforms like Canva and social media APIs for end-to-end execution.
*   **Configurable Workflows:** Allows customization of marketing strategies and agent responsibilities.

## Tech Stack
*   **Backend:** Python, FastAPI
*   **AI/Agents:** LangChain, OpenAI API
*   **Tools:** Canva API, Twitter/X API, Google Serper API
*   **Infrastructure:** Docker, PostgreSQL

## Getting Started
1.  Clone the repo: `git clone https://github.com/zoreanuj/marketmenow.git`
2.  Install dependencies: `pip install -r requirements.txt`
3.  Set up environment variables in a `.env` file (see `.env.example`).
4.  Run the application: `uvicorn app.main:app --reload`