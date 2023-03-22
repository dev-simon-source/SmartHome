# SmartHome
## Installation
- Hier kommt eine detallierte Beschreibung für die Installation.
- Für die Installation wird Docker Compose verwendet, um eine unabhängigkeit des verwendeten Systems und Machine zu gewährleisten.

## Github
### Regeln
- nicht direkt auf den Main-Branch commiten oder pushen
- nicht commiten ohne zuvor den lokalen branch auf den neusten Stand gebracht zu haben (um merge konflikte zu vermeiden)
- auf dem eigenen Branch arbeiten und nur in absprache auf anderen arbeiten
- alle 2 Wochen werden die Branches aktualisiert, damit jeder aktuell arbeiten kann

### Befehle
- Änderungen auf den Branch pushen
```bash
git add filename
git commit -m "Nachricht für den Commit"
git push
```
Bespiel:
```bash
git add paper/main.tex
git commit -m "Hinzufügen eines neuen Kapitels"
git push
```
- Veränderte Dateien anzeigen lassen
```bash
git status
```
- Branch wechseln
```bash
git checkout branchname
```

- Branch updaten
```bash
git update
```