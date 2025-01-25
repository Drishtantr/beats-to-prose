# Prose Generator

This project uses Google Gemini and spaCy to generate immersive prose based on a sequence of story beats, characters, settings, genre, and prose style. It allows for seamless transformation of a simple story outline into a detailed narrative.

## Requirements

You need the following dependencies to run the project:

```bash
pip install -q -U google-generativeai spacy nltk python-dotenv
python -m spacy download en
```

## Setup

Store your API key in a .env file. Add the following line to the file:

```bash
API_KEY=your_api_key_here
```

## API

```bash
POST /generate_prose/
Accepts a JSON body with beats, characters, setting, genre, and prose_style.
Returns the generated prose narrative.
```
