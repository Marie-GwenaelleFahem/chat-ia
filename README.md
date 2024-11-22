# chat-ia

### Techo
Ollama => llama3.2
Python 

### Installation

1. Installer les dépendances du projet avec la commande suivante : 
```pip install -r requirements.txt```

2. Installer Ollama sur votre machine puis entrer la commande suivante : 
```ollama pull mxbai-embed-large```

3. Lancer l'upload du fichier PDF en local : 
```python upload.py```
    Ou bien python3 

4. Lancer la conversation avec l'IA : 
```python localrag.py```
Vous pouvez ajouter le model llama que vous utilisez à la suite de localrag.py 
    ex: python localrag.py --model llama3.2:1b

