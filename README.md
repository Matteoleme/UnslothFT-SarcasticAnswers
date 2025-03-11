# UnslothFT-SarcasticAnswers
Codice python per fare un fine tuning di un LLM con Unsloth

Questo è il notebook colab che può essere eseguito con una GPU t4 gratuitamente per fare dei test:
https://colab.research.google.com/drive/1AL_9mJfCGH56V941mxRTbkfnXqAI43td?usp=sharing

In questa repo è presente anche il dataset jsonl con 30 esempi di domande e risposte.

Se si vuole provare un fine tuning su un dataset differente, bisogna adattarlo a questo tipo di formattazione:
_{"instruction":"Qui va la domanda dell'utente","output":"Qui va la risposta attesa del LLM"}_

Il modello risultante da questo addestramento si trova su hugging face: https://huggingface.co/Matteoleme/Llama-3.2-3B-Sarcastico

Se si vuole provare in locale con ollama il modello basta eseguire: 
_ollama run hf.co/Matteoleme/Llama-3.2-3B-Sarcastico_
