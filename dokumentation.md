### Dokumentation – GitHub Teilprüfung 1 ###

# a) Repository initialisieren

Ein neues Git-Repository wurde lokal erstellt und initialisiert:

- Projektordner erstellt
- `git init` ausgeführt um das Repository zu initialisieren
- `README.md` erstellt und hinzugefügt
- Erster Commit mit der Nachricht "Initial commit: Add README.md" durchgeführt

# b) .gitignore

Eine `.gitignore`-Datei wurde erstellt mit folgenden Ausschlüssen:

- Temporäre Dateien (`*.tmp`, `*.temp`, `.DS_Store`)
- Log-Dateien (`*.log`, `logs/`)
- Abhängigkeiten (`node_modules/`, `vendor/`)
- Entwicklungsumgebung (`.env`, `.vscode/`, `.idea/`)

# c) Branches

Zwei Branches wurden erstellt:

- `develop` – für die allgemeine Entwicklung
- `feature-login` – für die Login-Funktionalität

Wechsel zwischen Branches erfolgt mit `git checkout <branchname>`.

# d) Merging

Der `feature-login`-Branch wurde in `develop` gemergt:

- `git checkout develop`
- `git merge feature-login`

Der Merge erfolgte als Fast-forward, da keine Konflikte vorlagen. Bei Konflikten würden diese manuell in den betroffenen Dateien gelöst, danach mit `git add` und `git commit` abgeschlossen.

# e) Remote Repository

Ein Remote-Repository wurde auf GitHub erstellt und verknüpft:

- Repository auf github.com erstellt
- Lokal verknüpft mit `git remote add origin <url>`
- `develop`-Branch gepusht mit `git push -u origin develop`


# f) Issue & Milestone

## Milestone erstellen
Um einen Milestone zu erstellen, navigiere ich im Repository zu "Issues" -> 
"Milestones" -> "New milestone". Dort vergebe ich einen aussagekräftigen Titel 
wie "v1.0 - Launch", setze ein Fälligkeitsdatum und füge eine kurze Beschreibung 
hinzu. Mit "Create milestone" wird der Milestone gespeichert.

## Issue erstellen
Um ein Issue zu erstellen, navigiere ich zu "Issues" -> "New issue". Ich vergebe 
einen klaren Titel, der die Anforderung beschreibt, und füge in der Beschreibung 
eine User Story ein, z.B. "Als Nutzer möchte ich mich einloggen können, um auf 
mein Konto zuzugreifen." Auf der rechten Seite wähle ich unter "Milestone" den 
zuvor erstellten Milestone "v1.0 - Launch" aus. Abschließend klicke ich auf 
"Create".

Das Issue ist damit dem Milestone zugeordnet und der Fortschritt des Projekts 
ist transparent nachverfolgbar.