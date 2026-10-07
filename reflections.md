Introduction to Agentic AI

Tech Stack
Course backend uses Python and jupytor notebooks

 `requirements.txt` to set up locally
 '

Python's venv to secure API tokens and manage python libraries

Communication with LLMs handled by AISuite package which allows
- sending messages to LLMs
- receiving responses from LLMs
- specifying tools LLMs can use
- intercepting intermediate messages (ex tool invocation and results)
- selecting LLM models
- specifying temperature??, 
- inspecting output and sending messages to agents and getting responses

## Agentic System Design Patterns
### Reflection
- LLM can reflect and criticue results and suggest improvements. This can often improve results and even tiny/worse  models can perform well
-

### Tool Use
- LLM's abilities can be enhanced with tools.
- Write code is especially interesting tool - LLMs can use a wide variety of libraries to perform tasks (ex find answers about data statistics)

### Multiple Agents

#### Reasons to use Multi Agent Workflows

Similar to hiring a team instead of individual. Specialized agents can handle specific tasks better instaead of using one agent to do all tasks. Can potentially be easier to fine tune and tweak individual agents.

Multi Agent Workflows

