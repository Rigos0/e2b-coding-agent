# Coding Agent

A coding agent that can clone a GitHub repository, plan and execute tasks, and interact with the user through a web interface. The agent is built with the E2B Python SDK and the frontend is a Next.js application.

The agent works in a secure E2B sandbox environment where all agent actions are executed.


![image](https://github.com/user-attachments/assets/e1d30f2e-028c-4fe9-8770-fc777976fd95)


## Getting Started

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/rigos0/coding-agent.git
    ```

2.  **Set up environment variables:**

    Create a `.env` file based on `.env.example` in the `coding-agent-backend` directory and add the required credentials and API keys.


3.  **Run the backend:**

    ```bash
    cd coding-agent/coding-agent-backend
    pip install -r requirements.txt
    uvicorn src.api.main:app --reload
    ```

4.  **Run the frontend:**

    ```bash
    cd coding-agent/coding-agent-frontend
    npm install
    npm run dev
    ```

5.  **Open your browser:**

    Navigate to [http://localhost:3000](http://localhost:3000) to start using the coding agent.
