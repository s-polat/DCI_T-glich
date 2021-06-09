# Anleitung des Githubs

## Arbeitsschritte

### Repository erstellen
Auf Github.com > "new repository"
Owner: Entweder ich elber oder eine Gruppe (D02-2)
Add a README file -> Hilfreich
Rechte vergeben: Settings > manage access.
Mitarbeiter müsen auf "accept" klicken.

### Lokale Kopie erstellen
Haupt-Ordner für Projekte erstellen oder benutzen (mkdir/cd).
Benötigt: die git Adresse (Auf Gitub unter grüner Button "code")
```bash 
git clone adresse
```
**! Achtung: "main" branch**

### Eigenen Branch erstellen
#### Variante A: Terminal
```bash
git checkout -B branch_name
```
ODER
```bash
git branch branch_name
git checkout branch_name
```
#### Variante B: VS Code
Unten links auf "main" (mit Netzwerk-Symbol) klicken.  
Oben dann auf "+ create new branch".  
Name eingeben.  

### Nach der Arbeit: Commit + push
#### Variante A: Terminal
```bash
git add .
git commit -m "Eine Nachricht"
git pull
git push
```
#### Variante B: VS Code
Links im Menu auf Source Control.  
Datei mit "+" hinzufügen.  
Nachricht eingeben und Haken drücken.
unten links auf die wolke oder später auf das Kreislauf-symbol zum updaten und hochladen.

### Arbeit ganz fertig: Pull Request
Auf github: Projekt > Branch-Wechsler.
Branch wählen. Contribute > Open Pull Request.
Reviewer hinzufügen.
Wenn alles ok ist -> mergen
Bei Konflikten -> Resolve Conflicts.

#### Resolve Conflicts
```
<<<<<< Meine Änderung
....
====== Ab hier Original
....
>>>>>>
```
Die Sonderzeichen/Zeilen löschen und Ergebnis überprüfen.  
Klick auf "Mark as resolved"  
Klick auf "Commit"  

#### Merge Pull Request
Wenn alles ok ist !


#### Repository Löschen
!Achtunghier wird wirklich alles gelöscht.  
Settings > manage access > manage  
