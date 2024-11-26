# Branches in Git

## Was sind Branches?

Ein Branch in Git ist ein separater Entwicklungszweig. Er erlaubt es, parallel zum Hauptzweig (oft `main`) an neuen Features oder fixxes zu arbeiten, ohne die Stabilität des maincodes in Gefahr zu bringen.

### Vorteile von Branches

- **Unabhängige Entwicklung:** Man kann Änderungen vornehmen, ohne die Hauptarbeit zu stören.
- **Einfache Zusammenführung:** Änderungen können jederzeit mit anderen Branches zusammengeführt werden (z. B. mit `merge`).
- **Experimentieren:** Branches sind perfekt perfekt für Experimente, weil sie leicht erstellt und gelöscht werden können.

---

### Wichtige Branch-Befehle

```bash
# Zeigt alle Branches an
git branch

# Erstellt einen neuen Branch
git branch <branch-name>

# Wechselt zu einem anderen Branch
git checkout <branch-name>

# Erstellt und wechselt direkt zu einem neuen Branch
git checkout -b <branch-name>

# Löscht einen Branch
git branch -d <branch-name>
```
## hilfreiches Video zu Git

[![Git in 100 Seconds](https://img.youtube.com/vi/hwP7WQkmECE/0.jpg)](https://www.youtube.com/watch?v=hwP7WQkmECE)

