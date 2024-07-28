# Ollama Youtube Video Summarizer
![Captura de ecrã 2024-07-21, às 11 46 57](https://github.com/user-attachments/assets/81c4568b-34b8-479c-a18d-fadb82cde568)

A simple youtube summarizer using a local AI ollama server.
Today we have so much content online and so few time to be able to watch everything, that I've thought it would be cool to make a simple script to having a summary of the video previously to viewing it so I can decide if its worthy or not to see it. 

## Technology used
* Python
* [Ollama Server](https://ollama.com/)
* [ollama/ollama-python](https://github.com/ollama/ollama-python)
* [jdepoix/youtube-transcript-api](https://github.com/jdepoix/youtube-transcript-api/)

## Install
Remember that this relies on having already a running Ollama Server.

**1. Clone the repo**
```
git clone https://github.com/HariTrigger/OllamaYTSumm/
```
**2. Install the requirements**
```
cd OllamaYTSumm
pip install -r requirements.txt
```

## Run the script
```
python3 main.py
```

## To Do 
* Work the system prompt to get the best result possible with (hopefully) the most ammount of models.
* Make the script asynchronous so we can activate the Stream of the response from the server, and see it real time.
* Make a web UI so I don't deppend on the console to do this. (Didn't tought on how yet, suggestions are welcome)

### Disclaimer
This is a script I've made for fun and to solve my own problem while learning through it. 

## Contributions
Any contribution are welcome, and thanks in advance to the ones who do so...
