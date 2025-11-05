# Henrik's VibeCode sesh
- Gjør dette før epleklubb (tar 10 minutter så går helt fint å gjøre det på kvelden også)

# Clone repo fra github:
- I terminal gå til mappe hvor du ønsker at koden skal ligge (gi beskjed om du trenger hjelp til terminal)
- git clone: git clone https://github.com/HenrikEple/epleVibeCode.git

## Sjekke om dere har installert. Om ikke installer: 
### Visual Studio Code: 
    - Install: https://code.visualstudio.com/
### Node: 
    - npm -v i terminal skal gi versjonsnummer
    - Install: https://nodejs.org/en/download
### Python 3: 
    - python3 -V i terminal skal gi versjonsnummer
    - Install: 
        - Install Homebrew: /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
        - Install python: brew install python
### Python virtualenv:
    - pip3 install virtualenv

## Installere chatGPT app:
- Appstore

## Tanker om 3D spill
Tanken er at vi alle skal lage et 3D-spill. Prøv å tenk ut en ide til et enkelt spill du kan lage. Tenk typ simple 3D-spill fra Flash-eraen.


# Vibe Coding: 
Alt under gjennomføres under Epleklubb

## Start en lokal testserver for å åpne testspillet laget i Babylon.js som ligger i mappen:
1. Trykk på "Terminal" -> "New terminal" i Visual  Studio Code.
2. Lag virtaulenv i mappen ved å skrive i terminal: python3 -m venv venv
2. Skriv følgende i terminalen for å lage et virtuelt python env: source venv/bin/activate
3. Skriv følgende i terminalen for å starte lokal webserver: python3 -m http.server 5000 (endre port om den allerede er i bruk.)
4. Trykk på lenken eller gå til http://[::]:portnummer/
5. Trykk på test_game.html på nettsiden som kommer opp.

## Gi åpningsinstruksjoner til chatGPT:
I’m participating in a coding session using Babylon.js.
My goal is to create a small browser-based 3D game starting from a simple flat map.
Please act as my Babylon.js coding partner — write clean, self-contained HTML/JS examples that can run directly in the browser without build tools.

My starting point: a basic index.html with a flat ground, light blue sky, camera angled slightly downward, and a hemispheric light.

Your tasks going forward:
	1.	Help me expand this base step by step depending on my idea (movement, physics, textures, shooting, collectibles, multiplayer, etc.).
	2.	When I ask for an update, show the entire working HTML file so I can copy and test it directly.
	3.	Keep explanations short and practical — focus on clear code.
	4.	Use only the core Babylon.js CDN (no external build systems or frameworks).
	5.	Assume I’ll run it locally using python3 -m http.server.

Let’s start from a simple flat map and evolve it into my own small 3D game idea.

### Velg å enten lime inn hele index.html for hver gang du gjør en iterasjon, eller bruk chatGPT sin integrasjon mot VSCode.

### Resten tar vi på sparket!!

# Velkommen
