# Stage Kritieke Incident Presentatie - GitHub Pages Deployment

## 🚀 Live Demo
Deze presentatie is direct beschikbaar na deployment op: `https://jouwgebruikersnaam.github.io/repository-naam`

## 📁 Wat zit er in deze map?

```
docs/
├── index.html              # Hoofdpresentatie (GitHub Pages automatisch startpunt)
├── dist/                   # RevealJS core bestanden
├── plugin/                 # RevealJS plugins (notes, markdown, highlight)
├── countdown-plugin/       # Timer functionaliteit
└── README.md              # Dit bestand
```

## 🔧 GitHub Pages Setup (Stap voor Stap)

### 1. Nieuwe Repository Maken
1. Ga naar GitHub.com
2. Klik "New Repository"
3. Naam: bijv. `stage-incident-presentatie`
4. Zet op **Public** (required voor gratis GitHub Pages)
5. Klik "Create repository"

### 2. Bestanden Uploaden

**Optie A: Via GitHub Website**
1. In je nieuwe repository, klik "uploading an existing file"
2. Sleep ALLE bestanden uit deze `docs/` map
3. Commit message: "Initial presentation upload"
4. Klik "Commit changes"

**Optie B: Via Git Command Line**
```bash
# In de docs/ map:
git init
git add .
git commit -m "Initial presentation upload"
git branch -M main
git remote add origin https://github.com/JOUWGEBRUIKERSNAAM/stage-incident-presentatie.git
git push -u origin main
```

### 3. GitHub Pages Activeren
1. Ga naar repository → **Settings** tab
2. Scroll naar **Pages** sectie (links menu)
3. **Source**: Deploy from a branch
4. **Branch**: main / docs
5. Klik **Save**

### 4. Wacht 2-5 minuten
GitHub bouwt je site. Je krijgt de URL: `https://jouwgebruikersnaam.github.io/repository-naam`

## ✨ Features van de Presentatie

### Timer Functionaliteit
- **'t' toets**: Start timer voor huidige slide
- **'r' toets**: Reset alle timers
- **Kleuren**: Blauw → Oranje (3 min) → Rood (1 min)

### Navigatie
- **Pijltjestoetsen**: Volgende/vorige slide
- **'s' toets**: Speaker notes weergeven
- **'f' toets**: Fullscreen
- **'b' toets**: Zwart scherm (pauze)

### Timers per Stap
1. **Inventariseren**: 10 minuten
2. **Toelichting**: 5 minuten
3. **Informatieronde**: 15 minuten
4. **Diagnose**: 8 minuten
5. **Oplossingen**: 8 minuten
6. **Keuze**: 5 minuten
7. **Reflectie**: 5 minuten

## 📱 Mobile Friendly
- Responsive design werkt op tablets/phones
- Timer en controls aangepast voor kleine schermen
- Touch gestures voor navigatie

## 🎯 Voor de Docent

### Presentatie Gebruiken
1. Open je GitHub Pages URL
2. Druk 'f' voor fullscreen
3. Gebruik 't' toets om timer te starten bij elke stap
4. Speaker notes ('s' toets) bevatten instructies

### Tips
- Test je presentatie altijd van tevoren
- Bookmarks je GitHub Pages URL
- Backup: download de hele `docs/` map

## 🔄 Updates Maken
1. Bewerk bestanden in je repository
2. Commit changes
3. GitHub Pages updated automatisch binnen paar minuten

## ❓ Troubleshooting

**Presentatie laadt niet:**
- Check of alle bestanden correct geüpload zijn
- Controleer GitHub Pages settings
- Wacht 5 minuten na wijzigingen

**Timer werkt niet:**
- Refresh de pagina
- Check browser console (F12) voor errors
- Gebruik 'r' toets om te resetten

**Mobile problemen:**
- Test op verschillende devices
- Check responsive design in browser dev tools

## 📋 Checklist voor Go-Live

- [ ] Repository is **Public**
- [ ] Alle bestanden geüpload (vooral `dist/` en `plugin/` mappen)
- [ ] GitHub Pages is geactiveerd
- [ ] URL werkt: `https://jouwgebruikersnaam.github.io/repository-naam`
- [ ] Timer functionaliteit getest
- [ ] Speaker notes werken ('s' toets)
- [ ] Mobile/tablet compatibiliteit getest

## 🎉 Je bent klaar!

Je presentatie is nu online beschikbaar voor:
- Studenten (kunnen meevolgen op hun apparaten)
- Collega docenten (kunnen presentatie hergebruiken)
- Jezelf (altijd toegankelijk, overal ter wereld)

**Pro tip:** Deel de URL van tevoren met studenten zodat zij kunnen meevolgen op hun eigen apparaat!