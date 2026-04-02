🚀 Startup Idea Validator

AI-powered agent that critiques startup ideas with structured, investor-style analysis.
Built using Google ADK, Gemini (Vertex AI), and Cloud Run

🧠 Overview
Startup Idea Validator takes a startup idea in natural language and returns a clear, structured evaluation covering:
- Market potential
- Competitive landscape
- Unique positioning (USP)
- Key risks
- Final verdict with score
The goal is to simulate how a real investor or product thinker would break down an idea — quickly and honestly.

⚙️ How it works:
- User submits a startup idea
- Gemini analyzes the idea across multiple dimensions
- The agent structures the output into a readable critique
- Response is returned via a deployed Cloud Run endpoint

🧩 Tech Stack
- Google ADK → agent orchestration
- Gemini (Vertex AI) → core reasoning engine
- Cloud Run → serverless deployment
- Python → implementation
  
🌐 Live Deployment
https://startup-validator-789905849496.us-central1.run.app/dev-ui
