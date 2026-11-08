# Meryem HR Game — GitHub Pages versie

**Alle bestanden in deze map horen samen in de hoofdmap (root) van de GitHub-repository.** Er is bewust geen `assets`-submap, omdat alle afbeeldingen en mp3-bestanden eerder los in de hoofdmap van `NovaMery/mery_HR_game` werden geüpload.

## Belangrijkste reparaties
- Homepage-panda en resultatenmascotte laden via correcte relatieve paden.
- Alle GIFs, afbeeldingen en mp3-bestanden gebruiken bestanden die in deze ZIP zitten; geen externe hosting nodig.
- Muziekknop op de homepage: klik op **Start muziek**. Browservereisten laten muziek pas na een klik beginnen.
- Ook bij het kiezen van een hoofdstuk begint de muziek automatisch na die klik.
- Rustige muziek speelt 75 seconden, dan Rat Dance 42 seconden; dit wisselt doorlopend af.
- Soundboard-reacties spelen via een apart audiokanaal over de achtergrondmuziek heen.
- Muziek aan/uit werkt zonder de quiz te onderbreken.
- Bij iedere vraag horen precies vier opnieuw gemixte antwoordopties. Score, feedback en herhaling van fouten blijven werken.

## Updaten in je bestaande GitHub-repository
1. Open `https://github.com/NovaMery/mery_HR_game`.
2. **Het snelst:** upload uit dit ZIP alleen de twee gewijzigde bestanden `index.html` en `script.js`, en overschrijf de bestaande versies. De rest van de bestanden staat al los in je repository.
3. **Of alles opnieuw uploaden:** upload de **inhoud** van deze uitgepakte map in de root van de repository, niet de ZIP zelf en niet een bovenliggende map.
4. Klik **Commit changes** en wacht tot GitHub Pages opnieuw publiceert.
5. Open `https://novamery.github.io/mery_HR_game/` en vernieuw met Ctrl+F5 als je nog de oude versie ziet.

## Controle
- `index.html`, `script.js`, `questions.js`, `style.css` en `panda-bag.png` moeten direct in de root staan.
- De geluidsbestanden `intro-calm.mp3`, `Rat Dance.mp3` en de overige mp3s staan ook direct in de root.
- De GitHub Pages instelling is `main` / `/(root)`.
- Na publiceren moeten afbeeldingen, muziek en quiz-knoppen op desktop en mobiel werken.
- Voortgang wordt alleen op het toestel van elke speler in de browser bewaard.

Noot: de browser kan zonder gebruikersklik geen muziek automatisch afspelen.


## Audiofix v3
- De lange foutengeluiden zijn verkort tot ongeveer 2 seconden en hebben een fade-out.
- Er is maar één effectgeluid tegelijk, met pauzes tussen de effecten.
- De lange foutensound speelt niet bij elke fout opnieuw.
- Achtergrondmuziek blijft onafhankelijk van meme- en soundboardgeluiden.
- GIFs worden bij elke reactie opnieuw geladen.
- Na upload kunnen browsers door cache nog de vorige versie tonen; vernieuw met Ctrl+F5.


## Versie 4 — telefoon en GIF-reacties
- Na 60 seconden zonder antwoord speelt alleen het eerste korte fragment van ‘Your phone is ringing’ (ongeveer 3,16 seconden per lus).
- Het fragment herhaalt zolang niemand klikt of een toets indrukt; ieder gebruikerscontact stopt het onmiddellijk.
- Na 120 seconden volgt de aparte twee-minutenreactie.
- Chill/Rat Dance gaat onafhankelijk door; meme-sounds onderbreken de muziek niet.
- Reactieafbeeldingen wisselen meer af; beide geüploade GIFs worden ook gebruikt.
- Bij GitHub Pages zijn alle bestanden in de hoofdmap nodig; upload minimaal script.js, index.html en phone-reminder.mp3.
