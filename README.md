# language-detection 
in this project we used [**polyglot 16.7.4**](https://polyglot.readthedocs.io/en/latest/) library to detect 196 languages around the world
## Developers
- Ali-Mahdiyanjoo
- ghazal Sayadfar
- Moien Karami
- Sania Ezatti
- Mehrshad Soltan Mohammadi
- Fatima Arjmand
## features
- Tokenization (165 Languages)
- Named Entity Recognition (40 Languages)
- Part of Speech Tagging (16 Languages)
- Sentiment Analysis (136 Languages)
- Word Embeddings (137 Languages)
- Morphological analysis (135 Languages)
- Transliteration (69 Languages) 

## Quick Tutorial
> for detecting one line of sentence
```
python3 Language_detection.py --detect "Your sentence here"

```

> for detecting language used in file
```
python3 Language_detection.py ---path "Your file path here"

```
## Requirements

- polyglot>=16.7.4
- wheel>=0.23.0
- PyICU>=1.8
- pycld2>=0.3
- six>=1.7.3
- futures>=2.1.6
- morfessor>=2.0.2a1
- numpy>=1.6.1