# Novella

A personal Korean vocabulary and grammar library that writes short reading-practice stories from the words and grammar you already know.

**Live:** https://xerluxz.github.io/Novella/

## Features
- Vocabulary with reading, meaning, part of speech, proficiency level and example sentences
- Grammar library with example sentences
- AI-written short stories using only the vocabulary and grammar you pick
- Flashcard review
- Thai / English interface

## Setup
If the site owner added a shared key (`EMBEDDED_KEY` in `index.html`), no setup is needed. Otherwise:

1. Create an API key at https://openrouter.ai/keys
2. Open the app, go to **Settings**, paste the key, choose a Qwen model ending in `:free`, and press **Test connection**

## Privacy
Everything is stored in your own browser (localStorage), including the API key. Nothing is sent anywhere except the OpenRouter endpoint when you generate a story or examples. Use **Export** in Settings to back up your data.
