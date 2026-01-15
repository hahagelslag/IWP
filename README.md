# Vistolabs Chatbot

Een eenvoudige chatbot applicatie voor het analyseren van buurtonderzoek data.

## Beschrijving

Deze chatbot helpt bij het bekijken en analyseren van onderzoeksresultaten over hoe bewoners hun buurt ervaren. Het project biedt twee weergaven:
- **Individuele deelnemer**: Bekijk antwoorden van een specifieke deelnemer
- **Alle deelnemers overzicht**: Zie een samenvatting van alle deelnemers

## Installatie

1. Clone deze repository:
   ```bash
   git clone [repository-url]
   cd chatbottest
   ```

2. Geen dependencies nodig - het project gebruikt alleen Node.js standaard modules.

## Gebruik

1. Start de server:
   ```bash
   npm start
   ```
   Of:
   ```bash
   node server.js
   ```

2. Open je browser en ga naar:
   ```
   http://localhost:3000
   ```

3. De chatbot interface wordt nu weergegeven waar je:
   - Deelnemers kunt selecteren
   - Hun antwoorden kunt bekijken
   - Vragen kunt stellen aan de chatbot over de data

## Projectstructuur

```
.
├── index.html      # Hoofdpagina met chatbot interface
├── chat.js         # Chatbot logica
├── style.css       # Styling
├── server.js       # Node.js server
├── data.json       # Onderzoeksdata
├── package.json    # Project configuratie
└── images/         # Afbeeldingen
```

## Technologieën

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js (alleen standaard modules)
- **Data**: JSON

## Licentie

MIT
