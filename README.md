# Stack — Supplement Finder

Stack helps people find supplements that match their goals. They can tap a few quick filters or type out their situation in plain English.

**Live app:** https://greys-stack-app.netlify.app

## Features

- **Quick pick:** choose from 14 goals (muscle, endurance, sleep, focus, stress, gut health and more) and situations (vegan, no stimulants, budget, pregnant/nursing, on medication, under 18). Results are ranked by how many of your goals each supplement hits, then by evidence strength.
- **Describe it:** type a scenario like *"training for a half marathon, vegan, tired in the afternoons"* and get matched picks.
- **52 supplements:** each one has an evidence rating (strong / moderate / limited), a typical dose, when to take it, how it works, who it's best for, and cautions.
- **Safety flags:** items that need a doctor's input are flagged automatically when you pick a situation like pregnancy, blood thinners or prescriptions.
- **Where to buy:** store links (Costco, Target, Walmart, CVS, Walgreens, GNC, iHerb, Amazon, REI) plus a guide to third-party testing seals (NSF, USP, Informed Sport).
- **My stack:** save picks, see them sorted by time of day, get a rough monthly cost, catch combinations that don't mix, buy straight from the stack, and copy the list to show a doctor.
- **Installable:** add it to the iPhone home screen and it opens like an app.

## Tech

It's a single-page web app: plain HTML, CSS and JavaScript with no build step or dependencies. Data is saved in the browser with `localStorage`.

## Disclaimer

Stack is for general information only. It is not medical advice. Check with a doctor or pharmacist before starting any supplement.

---

Built by Grey with Claude.
