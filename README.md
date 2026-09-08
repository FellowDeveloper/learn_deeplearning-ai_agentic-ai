Module 2 Ungraded Lab 2

Added iron.lua to execute python code from nvim
Used [this article](https://dev.to/rnrbarbosa/how-to-run-python-on-neovim-like-jupyter-3ln0) as a guide

Module 3 - Tool Use
TLDR; LLMs can use tools to execute what is needed (ex get current time function)
Earlier LLMs to call tool would be specially prompted to output something like
"CALL FUNCTION get_current_time"

LLM's output would be inspected and if it contains "CALL FUNCTION" the orchestrating process would call a function and feed then output back to LLM

Modern LLMs do not require this step.

Execute Code is a special tool. LLMs can write code to extend their functionality and execute that.
