# Agent Practice

Part of my Generative AI Engineer learning journey.

## What I practiced
- Built a simple agent that decides which tool to run
- Tools: add, multiply, salary_date
- The decision is returned as JSON (tool name and arguments), like an LLM tool call
- Error handling: unknown tool, missing numbers, and tool failure do not crash the agent

## How it works
1. The agent reads the question and decides: answer directly or call a tool
2. My code runs the chosen tool
3. The result is returned to the user

## What I learned
- In tool calling, the model only chooses the tool and its inputs; my code runs it
- An agent should handle missing inputs and unknown tools safely

## Tools
Python, JSON, Google Colab

## Next
Replacing the rule-based decision with an LLM and adding tools to my RAG chatbot
