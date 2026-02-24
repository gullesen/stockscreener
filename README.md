# 📈 StockScreener Pro
**En lettvektig, lynrask teknisk analyse-app bygget for iPhone 15 Pro Max.**

Denne appen visualiserer aksjeanalyser generert av et Python-script. Appen er bygget som en **Progressive Web App (PWA)**, som betyr at den kjører rett i nettleseren, men føles som en installert app når den legges til på hjemskjermen.

---

## 🚀 Rask Oppstart

### 1. Oppsett av data
Appen henter data fra en **GitHub Gist**. Sørg for at din `aksjer.json` er tilgjengelig og at URL-en i `index.html` peker til din "Raw" Gist-lenke.

### 2. Installasjon på iPhone (Gratis)
1. Åpne din GitHub Pages-URL i **Safari**.
2. Trykk på **Del-ikonet** (firkanten med pil opp).
3. Velg **"Legg til på hjem-skjerm"**.
4. Åpne appen fra hjemskjermen for en fullskjerm-opplevelse uten nettleserlinjer.

---

## 🛠 Funksjonalitet

* **Søk & Filtrering:** Finn raskt din ticker i sanntid.
* **Dynamisk Sortering:** * **Ticker:** Alfabetisk oversikt.
    * **RSI:** Finn oversolgte eller overkjøpte aksjer (Toveis: lavest/høyest først).
    * **Volum:** Sorter etter de største volumutbruddene.
    * **Risk/Reward:** Ranger trades etter beste forhold mellom oppside og nedside.
* **Detaljvisning:** Klikk på et aksjekort for å få opp grafer og alle tekniske indikatorer.

---

## 📊 Indikatorforklaringer

For å få maksimalt ut av screeneren, brukes følgende tekniske indikatorer:

| Indikator | Forklaring |
| :--- | :--- |
| **RSI (14)** | Måler momentum. Under 30 = Oversolgt (billig). Over 70 = Overkjøpt (dyrt). |
| **MACD Trend** | Bestemmer trendretning basert på glidende snitt. Bull (grønn) eller Bear (rød). |
| **Risk/Reward** | Potensiell gevinst delt på potensiell risiko. Bør være > 2.0. |
| **Volumøkning** | Dagens volum mot 20-dagers snitt. Bekrefter styrken i kursbevegelsen. |
| **EMA 20/200** | Eksponentielle gjennomsnitt. EMA 200 er ofte det viktigste støttenivået. |
| **Bollinger Bånd** | Viser volatilitet. Brudd på båndene indikerer ofte ekstreme bevegelser. |



---

## 👨‍💻 Teknisk Stabel

* **Backend:** Python (Analyse av markedsdata).
* **Frontend:** HTML5, CSS3 (iOS-optimalisert), og JavaScript.
* **Grafer:** Chart.js for visualisering av prishistorikk.
* **Hosting:** GitHub Pages (Gratis og stabilt).

---

## 📝 Utviklingslogg

* **V3.7:** Implementert modal-basert detaljside med priskurve-grafer.
* **V3.5:** Lagt til toveis sorteringslogikk med visuelle piler.
* **V1.0:** Første web-versjon etter overgang fra SwiftUI (Swift Playgrounds).

---
*Lykke til med tradingen!* 🚀
