<div align="center">

# Echoes of the Unheard

### An AI system that helps small businesses figure out which missed calls to return first

*Research Paper · SWDSI Conference · March 2026*
*Chaitra Neha Pulletikurthi · University of North Texas*

[![Read Paper](https://img.shields.io/badge/Read%20Paper-Live%20Site-blueviolet?style=for-the-badge)](https://chaitrapulletikurthi.github.io/AI_Agent_Article/)
[![Notebook](https://img.shields.io/badge/View-Notebook-orange?style=for-the-badge&logo=jupyter)](Agent.ipynb)

</div>

---


Small hospitality businesses — hotels, resorts, pet boarding facilities — miss a lot of phone calls during busy hours. The bigger issue is not the missed call itself, but not knowing *which* missed calls were actually important. Was it a one-time guest asking a simple question, or a high-value repeat customer ready to book?

Most tools only tell you *how many* calls came in. They don't tell you *which ones mattered*.

---


Design an AI system that could **listen to missed calls, understand what the caller wanted, and rank them** — so staff know exactly who to call back first without having to listen to every voicemail manually.

---


Built a five-step AI pipeline:

1. **Recorded the call** and screened it for basic safety
2. **Converted speech to text** in real time
3. **Used AI to extract signals** — how urgent was the caller? How positive or negative was their tone? Were they likely to spend money?
4. **Scored each call** using a weighted formula that balances all three signals
5. **Routed the call** — simple questions got an automated text reply, complex ones were flagged for a human to follow up

To test this in the real world, the framework was applied to **Pet Connect AI**, a voice receptionist prototype built for a pet resort. It handled incoming calls, scored leads, and helped staff prioritize their follow-ups.

---


Given three simultaneous missed calls, the system correctly ranked them by business priority — not by who called first. Staff could see at a glance which callback would have the most impact, saving time and recovering opportunities that would otherwise be lost.

---

## What's in This Repo

| File | What it is |
|------|------------|
| `index.html` | The published research article (live on GitHub Pages) |
| `Agent.ipynb` | Python notebook with the full implementation |
| `framework.png` | Visual diagram of the five-step pipeline |
| `dashboard.png` | Screenshot of the Pet Connect AI booking dashboard |

---

## Skills Demonstrated

`Python` · `NLP` · `Speech-to-Text` · `Agentic AI` · `Decision Analysis` · `Research & Writing` · `HTML/CSS`
