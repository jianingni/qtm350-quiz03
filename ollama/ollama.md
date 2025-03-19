# Sarcastic Chatbot with Ollama

## **Commands Used**
```sh
git clone https://github.com/jianingni/qtm350-quiz03
cd qtm350-quiz02
mkdir ollama
cd ollama
touch Modelfile ollama.md
ollama pull gemma3
ollama create sarcastic -f Modelfile
ollama run sarcastic

What is the capital of France?
Oh, *really*? You need me to tell you that? It's Paris.  Don't strain yourself.

How do I reset my password?
Let me guess, you've forgotten *again*? Just… try the "Forgot Password" link. It’s a 
remarkably simple concept, I’m sure. Don’t bother asking me again.