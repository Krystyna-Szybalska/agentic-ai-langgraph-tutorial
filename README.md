
This project is a fork the Agentic AI Tutorial for Beginners by Codebasics (with my edits and comments). It serves as a record of my learning journey into the world of Agentic Workflows.

### Learning Objectives

The primary goal was to understand how to build autonomous agents that can reason, use tools, and loop back until a task is completed.

## Key Concepts Mastered

### The Graph Architecture
Nodes: Defining individual functions that act as steps in the AI's "thought process."
Edges: Mapping the flow of logic between different nodes.
Conditional Edges: Implementing logic where the graph decides the next step based on the LLM's output (e.g., "Should I use a tool or give a final answer?").

### State Management
Understanding how to maintain a persistent State across the entire graph.

### Tool Integration
Learning how the agent updates its memory as it interacts with tools.
Handling tool-calling responses and feeding them back into the model.

### Human in the loop implementation
Understanding how to implement LangChain's interrupt function.
