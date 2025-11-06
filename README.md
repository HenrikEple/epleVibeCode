# Henrik's VibeCode sesh
Dette er en kort guide for å komme i gang før og under VibeCode-økten.  
Vi skal eksperimentere med å kode sammen med AI og lage små 3D-spill i Babylon.js.  
Poenget er å bygge trinnvis, teste underveis og ha det gøy med prosessen.

---

## Gjør dette før epleklubb (tar 10 minutter, så fint å gjøre det på kvelden også)

### 1. Clone repo fra GitHub
I terminal: gå til mappen hvor du ønsker at koden skal ligge.  
Gi beskjed om du trenger hjelp med terminal.

Kjør:
```
git clone https://github.com/HenrikEple/epleVibeCode.git
```

### 2. Sjekk at du har installert (eller installer hvis ikke)

#### Visual Studio Code
Installer: https://code.visualstudio.com/

#### Node
Sjekk:
```
npm -v
```
Installer: https://nodejs.org/en/download

#### Python 3
Sjekk:
```
python3 -V
```
Installer med Homebrew:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew install python
```

#### Python virtualenv
```
pip3 install virtualenv
```

#### ChatGPT app
Installer fra App Store.

---

## Tanker om 3D-spill
Vi skal alle lage hvert vårt lille 3D-spill.  
Tenk enkelt – som små Flash-spill fra gamle dager.  
Eksempler:  
- Et spill der du styrer en ball  
- En enkel labyrint  
- Et skytespill  
- Et lite romskipspill  

Poenget er å starte med noe helt grunnleggende, og så bygge videre steg for steg.

---

## Vibe Coding
Alt under gjøres under Epleklubb.

Vibe Coding handler om å kode sammen med AI, ikke å be den gjøre alt for deg.  
Du samarbeider med AI for å skape noe, og lærer ved å bygge i små og tydelige iterasjoner.

---

## Starte lokal testserver for Babylon.js-prosjektet

1. Åpne VS Code og trykk på "Terminal" → "New terminal".
2. Lag et virtuelt miljø:
```
python3 -m venv venv
```
3. Aktiver miljøet:
```
source venv/bin/activate
```
4. Start en lokal webserver:
```
python3 -m http.server 5000
```
(endre portnummer om 5000 er opptatt)
5. Åpne nettleser og gå til:
```
http://localhost:5000
```
6. Trykk på `test_game.html` for å åpne testspillet.

---

## Åpningsinstruksjoner til ChatGPT

Kopier og lim inn dette i ChatGPT før du begynner:

```
I’m participating in a coding session using Babylon.js.
My goal is to create a small browser-based 3D game starting from a simple flat map.
Please act as my Babylon.js coding partner — write clean, self-contained HTML/JS examples that can run directly in the browser without build tools.

My starting point: a basic index.html with a flat ground, light blue sky, camera angled slightly downward, and a hemispheric light.

Your tasks going forward:
  1. Help me expand this base step by step depending on my idea (movement, physics, textures, shooting, collectibles, multiplayer, etc.).
  2. When I ask for an update, show the entire working HTML file so I can copy and test it directly.
  3. Keep explanations short and practical — focus on clear code.
  4. Use only the core Babylon.js CDN (no external build systems or frameworks).
  5. Assume I’ll run it locally using python3 -m http.server.

Let’s start from a simple flat map and evolve it into my own small 3D game idea.
```

### Tips:
Velg om du vil lime inn hele index.html-filen hver gang du gjør en iterasjon, eller bruk ChatGPT sin VSCode-integrasjon om du har den.

---

## Hvordan skrive gode prompts i VibeCode

Dette er selve nøkkelen til at det fungerer bra.  
Vibe coding handler om å samarbeide med AI – ikke å gi kommandoer, men å bygge sammen.

### 1. Gi AI en tydelig rolle
Fortell hva du vil at AI skal være for deg.  
Eksempler:
- Act as my Babylon.js coding partner  
- Be my co-creator for a 3D maze game  
- Act as a game design tutor  

Det hjelper AI å svare i riktig tone og retning.

### 2. Gi nok bakgrunnsinformasjon
AI forstår best når du gir litt kontekst.  
Forklar:
- Hva slags spill du bygger  
- Hvilke verktøy du bruker  
- Hva du allerede har  
- Hva du prøver å oppnå  

Jo tydeligere du beskriver situasjonen, jo bedre blir svaret.

### 3. Gi konkrete eksempler
Hvis du sier “Add WASD movement like in a first-person game”,  
får du et klart og brukbart svar.  

Hvis du bare sier “Add movement”,  
må du som regel iterere mange ganger for å lande riktig.  

Eksempler hjelper AI å forstå nøyaktig hva du ser for deg.

### 4. Vær tydelig på hva du forventer som output
Fortell hvordan du vil ha svaret:  
- “Show me the full working HTML file.”  
- “Only show me the updated movement code.”  
- “Explain briefly how it works.”  

Da slipper du at AI gjetter formatet.

### 5. Bygg i små, tydelige iterasjoner
Den største feilen er å prøve å bygge alt på én gang.  
Lag heller små steg:
1. Start med et flatt plan og en kule  
2. Legg til bevegelse  
3. Legg til lys  
4. Legg til hindringer  
5. Legg til poengsystem  

Test etter hvert steg. Det gjør det lett å feilsøke og forstå.

### 6. Forvent mange justeringer
Du må iterere og justere.  
AI forstår ikke alltid alt perfekt første gang.  
Tenk at du bygger sammen, ikke at AI gjør alt for deg.  
Små iterasjoner skaper flyt og fremdrift.

---

## Praktiske tips underveis
- Lagre nye versjoner for hver større endring (`index_v2.html`, `index_v3.html`, osv.)
- Ikke vær redd for å ødelegge ting. Du lærer mest når du må fikse det.
- Spør AI om feilsøking om noe ikke virker: “Why is nothing showing up?”
- Hold koden ren, enkel og testbar.

---

## Oppsummering
Vibe coding handler om å komme i flyt sammen med AI.  
Du skriver, tester, justerer, og lærer underveis.  
Målet er ikke å få perfekt kode, men å bygge erfaring, eksperimentere og ha det gøy med prosessen.

---

Velkommen til VibeCode.
