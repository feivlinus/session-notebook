# Challenges: Git CLI and Remote

This is a challenge for the usage of Git with CLI

## Useful commands

```bash
git init
```

Für Neues Projekt/Ordner ein Repo erstellen

```bash
git add readme.md oder git add .
```

Neue Datei zum git-tracking hinzufügen oder alle hinzufügen für commit

```bash
git commit -m "added readme.md"
```

Datei bzw. Änderungen commiten

```bash
git status
```

Alle uncommitete Änderung anzeigen und oder alle nicht geaddete Dateien anzeigen

```bash
git diff .
```

```bash
git checkout main
```

```bash
git log
```

```bash
git restore .
```

Letzten Commit komplett wiederherstellen falls alles kaputt ist oder gelöscht wurde versehentlich

```bash
git remote add origin git@github.com:GitHubUsername/repository-name.git
git branch -M main
git push -u origin main
```

Lokale repo mit remote Repo verbinden(Zeile 1), branch einstellen(Zeile 2) und einstellen wo commits hingepusht werden sollen(Zeile 3).

```bash
git remote -v
```

```bash
git push -u
```

Commit auf remote Repo schieben

```bash
git switch -c newBranchName
```

Neuen Branch erstellen und in diesen wechseln.

```bash
git switch branchName
```

Zu Branch wechseln

```shell
git switch -c toDeletedBranchName
```

Branch löschen
