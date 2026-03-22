# MarketMeNow

MarketMeNow is an agentic marketing automation system designed for startups. It explores how AI can autonomously handle core marketing workflows, reducing dependency on traditional agencies. This project serves as a technical exploration of AI-driven marketing orchestration.

## Key Features
*   **Multi-Agent Orchestration:** Coordinates specialized AI agents for content, social, and analytics tasks.
*   **Automated Content Pipeline:** Generates and schedules marketing copy and social posts.
*   **Campaign Performance Tracking:** Monitors key metrics and provides actionable insights.
*   **Modular & Extensible Design:** Allows easy integration of new platforms and data sources.

## Tech Stack
*   **Backend:** Python, FastAPI
*   **AI/ML:** LangChain, OpenAI API
*   **Infrastructure:** Docker, PostgreSQL
*   **Tools:** GitHub Actions, Pydantic

## Getting Started
1.  Clone the repo: `git clone https://github.com/zoreanuj/marketmenow.git`
2.  Install dependencies: `pip install -r requirements.txt`
3.  Set environment variables (see `.env.example`).
4.  Run the application: `uvicorn app.main:app --reload`