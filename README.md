#devnexus2026

# "GenAI for Busy Java Developers" @ Devnexus 2026.
## Example Code

Small subset of code from my LinkedIn Learning courses and my Pearson/OReilly courses.
These are several examples from my Devnexus 2026 presentation.


- HelloWorldGoogle.java - simple 
demonstration of using a LangChain4j ChatModel to access Google Gemini
- PromptTechniques.java - demonstration of a structured prompt that guides an LLM.
- MyService.java - Simple demonstration of a LangChain4j AiService
- ChatService.java - Simple chatbot with and without conversational memory
Try these prompts "My name is Frank and I enjoy music", then ask the LLM what your name is and what you enjoy.
- GetEmbedding.java - Example of using an embedding service to retrieve an embedding 
vector for a given string.
- Collaboration.java - Using one LLM to judge the output from another LLM

These programs need API keys to run.
Visit these sites to register and get an API Key:

- [Google](aistudio.google.com)
- [Anthropic](console.anthropic.com)
- [Mistral](https://docs.mistral.ai/getting-started/quickstart)
- [OpenAI](platform.openai.com)

And in your IDE or terminal just add the specific key to your shell (or environment variables): 
- GOOGLE_API_KEY=[*put your key here*]
- MISTRAL_API_KEY=[*put your key here*]
- ANTHROPIC_API_KEY=[*put your key here*]