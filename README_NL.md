# 🦙 Llama 3.1 8B gebruiken in Google Colab  Nederlandstalige tutorial

> Leer hoe je een open-source taalmodel laadt en gebruikt in Python  zonder eigen GPU, zonder hoge kosten, met volledige controle over je data.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1D5gGLi_jFcXpS6km7VYUTPK-jFxclWmA?usp=sharing)
[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## Wat is dit?

Dit is een **Nederlandstalige tutorial** voor software engineers die willen beginnen met open-source Large Language Models (LLM's). Je leert stap voor stap hoe je **Llama 3.1 8B Instruct** van Meta laadt en gebruikt via **Google Colab**  inclusief uitleg over prompts, parameters en een praktisch tekstcorrectie-voorbeeld.

De tutorial is speciaal bedoeld voor developers die:
- **nieuw zijn** met LLM's en open-source AI
- **privacygevoelige toepassingen** bouwen waarbij data niet naar externe servers mag
- **onafhankelijk** willen zijn van betaalde diensten zoals ChatGPT of Gemini

---

## Wat leer je?

- Wat LLM's zijn en wat het verschil is tussen open-source en gesloten modellen
- Hoe je Google Colab instelt met een gratis GPU
- Hoe je Llama 3.1 8B laadt met Unsloth
- Hoe je het model aanstuurt met `system`- en `user`-prompts
- Hoe je `temperature` en `max_new_tokens` aanpast
- Hoe je het model inzet voor tekstcorrectie en vraagbeantwoording

---

## Vereisten

| Wat | Details |
|-----|---------|
| **Voorkennis** | Basiskennis Python |
| **Google account** | Voor Google Colab |
| **Hardware** | Geen eigen GPU nodig  gratis T4 GPU via Colab |
| **Kosten** | Gratis (met de gratis versie van Google Colab) |

---

## Snel aan de slag

1. Klik op de **Open in Colab** badge bovenaan
2. Ga in Colab naar **Runtime → Change runtime type → T4 GPU**
3. Voer de cellen stap voor stap uit

Of clone de repo lokaal:

```bash
git clone https://github.com/JOUW-GEBRUIKERSNAAM/JOUW-REPO-NAAM.git
cd JOUW-REPO-NAAM
```

---

## Inhoud

```
📁 JOUW-REPO-NAAM/
├── llama31_tutorial_nl.ipynb   # Hoofdnotebook met de volledige tutorial
└── README.md                   # Dit bestand
```

---

## Overzicht van de tutorial

| Sectie | Onderwerp |
|--------|-----------|
| 1 | Introductie en leerdoelen |
| 2 | Wat zijn LLM's? Open-source vs. gesloten |
| 3 | Google Colab instellen met GPU |
| 4 | Unsloth installeren |
| 5 | Llama 3.1 8B laden |
| 6 | Eerste test: model gebruiken |
| 7 | System- en user-rollen in prompts |
| 8 | Parameters: `temperature` en `max_new_tokens` |
| 9 | Conclusie, vervolgstappen en veelvoorkomende problemen |

---

## Veelvoorkomende problemen

**GPU limiet bereikt?**  
De gratis Colab heeft een dagelijkse GPU-limiet. Wacht 24 uur of upgrade naar Colab Pro.

**Model laadt niet?**  
Hugging Face kan soms overbelast zijn. Wacht 5-10 minuten en probeer opnieuw.

**Model reageert langzaam?**  
Controleer of de GPU actief is via `!nvidia-smi` in een cel. Als er geen GPU-tabel verschijnt, stel de runtime opnieuw in.

---

## Vervolgstappen

Na deze tutorial kun je verdergaan met:
- Andere open-source modellen zoals Mixtral of DeepSeek-V2
-  Een REST API bouwen met Flask of FastAPI rondom het model
-  Een eigen chatbot of virtual assistant bouwen
- Grotere Llama-varianten draaien (70B) via Colab Pro of eigen server

---

## Licentie

Dit project valt onder de [MIT-licentie](LICENSE).

---

##  Author

[![GitHub](https://img.shields.io/badge/GitHub-Coder%20Shiyar-blue)](https://github.com/codershiyar)
[![YouTube](https://img.shields.io/badge/YouTube-Coder%20Shiyar-red)](https://youtube.com/@codershiyar)