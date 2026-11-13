# Morgonen på resan – Hua Hin 22 dec 2026–10 jan 2027

Statisk morgonrapport (`index.html`) med tidvatten och dagsplaner, plus live-väder från
[Open-Meteo](https://open-meteo.com/) som hämtas i webbläsaren:

- Väder per timme (temperatur, regnrisk, UV, vind/byar/riktning i knop) för Khao Takiab,
  och för Suvarnabhumi på Bangkok-dagarna.
- Våghöjd och period från Open-Meteo Marine API.
- Timgraf för vind och våg under tidvattenkurvan. Timmar med vind > 15 knop eller våg > 0,5 m
  markeras som "krabbigt för små barn" och räknas bort från badfönstret.
- Dagar bortom prognosen (~16 dagar) visar bara den statiska informationen.

Publiceras med GitHub Pages: Settings → Pages → Deploy from a branch → välj grenen och `/ (root)`.
