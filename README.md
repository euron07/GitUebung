# GitUebung

# Git Einführung

## Was ist Git?

Git ist ein verteiltes Versionskontrollsystem, das es Entwicklern ermöglicht, Änderungen an Dateien zu machen und zusammenzuarbeiten, ohne angst zu haben, Arbeit zu überschreiben. Es wurde 2005 von **Linus Torvalds**, dem Erfinder des Linux-Kernels, entwickelt. 

Mit Git können Teams:

- Änderungen an Codeversionen verwalten.
- Branches erstellen und zusammenführen.
- Änderungen nachverfolgen und frühere Versionen nutzen.
- Effektiv an Projekten zusammenarbeiten, ob lokal oder über Plattformen wie GitHub.

---

## Die wichtigsten Git-Befehle

```bash
# Initialisiert ein neues Git-Repository
git init

# Klont ein Repository aus dem Internet oder einem Netzwerk
git clone <repository-url>

# Zeigt den Status des Repositories an (Änderungen, Staging, etc.)
git status

# Fügt Dateien zum Staging-Bereich hinzu
git add <datei>  # Einzelne Datei
git add .        # Alle Dateien im aktuellen Verzeichnis

# Erstellt einen Commit mit einer Beschreibung der Änderungen
git commit -m "Deine Commit-Nachricht"

# Zeigt den Verlauf aller Commits an
git log

# Merged Änderungen von einem Branch in den aktuellen
git merge <branch-name>

# Erstellt/wechselt zu einem neuen Branch
git checkout -b <branch-name>
```

## Inhalte
- [Branches in Git](branches.md)
- [Linksammlung zu Git und Markdown](links.md)

# Code - Review 

Review von Eric Lücking am 26.11.2024