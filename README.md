# Agentic AI Consulting System

This project builds a multi-agent (Agentic) AI system to solve a real-world business consulting problem. The system evaluates whether a traditional global retailer (ABC) should add a personalized online styling business model similar to XYZ Personalized Styling.

Instead of asking a single LLM to answer the question directly, this system uses four coordinated AI agents, each with a specific role. The agents collaborate autonomously to analyze financial data, strategy, operations, and market positioning before delivering a final recommendation.

⸻

System Overview

The system consists of:
	1.	Planner Agent
	2.	Financial Analyzer Agent
	3.	Strategic Analyzer Agent
	4.	Synthesizer Agent

Each agent has a clearly defined responsibility, creating a structured workflow similar to how a real consulting team would operate.

⸻

1. Planner Agent

The Planner Agent acts as the project manager.

It:
	•	Breaks down the overall consulting question into subtasks
	•	Determines which analyses need to be performed
	•	Assigns tasks to the appropriate analyzer agents
	•	Defines the workflow (sequential vs. parallel tasks)

Rather than immediately generating an answer, the planner ensures the problem is structured before execution.

⸻

2. Financial Analyzer Agent (RAG Pipeline)

This agent focuses strictly on financial evaluation using Retrieval-Augmented Generation (RAG).

It analyzes:
	•	Revenue trends
	•	Gross margins
	•	Operating expenses
	•	Cash flows
	•	Inventory implications
	•	Cost structure differences
	•	Financial feasibility of adding XYZ’s model

It uses structured financial data and contextual company information to generate data-driven insights.

⸻

3. Strategic Analyzer Agent (RAG Pipeline)

This agent focuses on strategy, brand, and operational impact.

It evaluates:
	•	Brand alignment risks
	•	Competitive positioning
	•	Digital transformation fit
	•	Operational complexity
	•	Supply chain differences
	•	Customer retention implications
	•	Cannibalization risk

It determines whether adding the online styling model strengthens or weakens ABC’s long-term positioning.

⸻

4. Synthesizer Agent

The Synthesizer Agent acts as the final decision layer.

It:
	•	Combines outputs from both analyzer agents
	•	Resolves conflicting insights
	•	Weighs financial versus strategic tradeoffs
	•	Produces a final recommendation with justification

The output resembles a structured consulting report rather than a raw LLM response.

⸻

Why a Multi-Agent System?

Compared to giving the question directly to a single LLM, this agentic system:
	•	Enforces structured reasoning
	•	Separates financial and strategic analysis
	•	Reduces hallucinations through RAG
	•	Produces more organized output
	•	Mimics real-world team collaboration

The result is a more explainable, modular, and extensible AI decision system.

⸻

Project Context

This system was built as part of an advanced Agentic AI assignment focused on designing a multi-agent LLM system for a complex consulting task.
