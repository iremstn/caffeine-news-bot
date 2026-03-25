# ☀️ Caffeine News Bot

Ein N8N Telegram Bot der täglich um 08:00 Nachrichten zusammenfasst. Da heutzutage sehr viele Menschen bilingual aufgewachsen sind, bietet dieser Bot die Möglichkeit, Nachrichten aus zwei verschiedenen Ländern zu erhalten! 

https://t.me/CaffeineN8NBot

## Features
- Onboarding via Telegram Inline Buttons
- Länderauswahl: 🇩🇪 Deutschland, 🇹🇷 Türkei, 🇫🇷 Frankreich, 🇰🇷 Südkorea
- KI-Zusammenfassung via OpenRouter LLM
- Zweisprachige News (Deutsch + Zweitsprache)
- Täglich um 08:00 Uhr

## Tech Stack
- N8N (Self-hosted)
- Telegram Bot API
- RSS Feeds (Tagesschau, Hurriyet, Le Monde, YNA)
- OpenRouter API
- Google Sheets API

## Setup
1. N8N installieren
2. Telegram Bot via @BotFather erstellen
3. OpenRouter API und Google Sheets API Key holen
4. Workflow JSON importieren
5. Credentials eintragen

## Workflow 1: Speicherung der Daten
![Workflow Screenshot](./Workflow1)

## Workflow 2: Schedule + Nachricht versenden

![Workflow Screenshot](./Workflow2)

## Telegram-Bot
![Workflow Screenshot](./Telegram1)




