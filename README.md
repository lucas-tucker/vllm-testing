This is a simple vLLM chatbot, which uses facebook/opt-125m to generate
20 token responses to prompts from the user. The chat is currently
memoryless. To run the bot, run the local-server as `python3 local-server.py`
and then `python3 llama-chat-agent.py` in a separate terminal. This will
run the vLLM instance locally, with a generation endpoint at local port 5000.