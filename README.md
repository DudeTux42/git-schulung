Freitag 23.02.24

## Ablauf 

**1. Gliederung.**

1. Einführung in Begrifflichkeiten.    
2. Installation.    
3. Git.    
4. GitHub.

**2. Was ist Git**.

- Versionskontrolle: Git ermöglicht das Verfolgen und Verwalten von Änderungen an Dateien über die Zeit, erleichtert Fehlerbehebung und Projektverlaufstracking.  
  
- Branching und Merging: Entwickler können isoliert neue Funktionen entwickeln und diese nahtlos in den Hauptcode integrieren.

 **3. Installation**. 

1. Geh auf die [Git Website](http://www.git-scm.com/downloads) und lade die windows version herunter,  
    für Linux nutze deinen Paketmager. Auf Mac-Os installiere Home-brew und schreibe brew install git ins terminal.
2. Wechsle Standard branch zu main.

**4. Konfiguration**.   

1. Terminal öffnen.
2. Bestimme Username:
```sh
git config --global user.name <username>
```
3. Bestimme User Email:
```sh
git config --global user.email <Email>
```

**5. Lokales Repo erstellen**. 
  
1. Im Terminal zu neu erstelltem Ordner navigieren.
2. Initialisiere den Ordner:
```sh
git init  
```
3. Neue Datei im Ordner erstellen.

**6. Status des Repos**.
1. Zeige den Status deines lokalen Repos:
```sh
git status
```

**7. Staging**.
1. Füge eine Datei zum Staging hinzu:
```shell
git add <Name von File>
```
- Das Staging in Git ist wie eine Vorbereitungszone für deine Änderungen, bevor du sie endgültig speicherst, und "git add" ist der Befehl, mit dem du deine Änderungen dieser Vorbereitungszone hinzufügst.

**8. Commit.**
1. Commite Änderungen:
```shell
git commit -m <Commit Message>
```

**9. Unterschiede zwischen Commits**.
1. Zeige eine chronologische liste aller Commits:
```sh
git log    
```
2. zeige Informationen zu einem bestimmten Commit:
```sh
git show <ID>
```
   
**10. Branches**.

1. Branch mit :
```sh
git branch <name> 
```
erstellen.  
 
3. Zu branch wechseln mit: ``
```sh
git checkout <name>    
```

5. Zu Main Branch wechseln (darauf hinweisen das die erstellte Datei nicht mehr da ist) :
```sh
git checkout main
```

7. Merge die beiden Branches mit :``
```sh
git merge <Zu mergender Branch>    
```
9. Branch löschen mit :``
```sh
git branch -d <name>    
```

**11. Frühere version herstellen**.

1. bis zu einem bestimmten commit (und file) alles zurücksetzten:
```sh
git checkout <id> <path to file> 
```

**12. Einen Commit rückgängig machen**.

- Falls Tippfehler in message :
```sh
git commit --amend    
```
- Letzten Commit zurücksetzten: ``
```sh
git revert HEAD    
```
- Zu einem bestimmten Commit zurück gehen mit: ``
```sh
git revert <ID>  
```

**13. Remote Repo**.

1. GitHub.com öffnen anmelden und neues Repo erstellen.
2. Hinweisen auf git ignore, public und private Repos.
3. Das Remote Repo mit dem Lokalen Repo verbinden:
```sh
 git remote add origin <link to GitHub>    
```
  
**14. Push/Pull**.
1. Pulle den Inhalt des Remote-Repo in dein Lokales Repository 
```sh
git pull <name von remote> <branch>
```

2. Falls du eine Meldung bekommst wie "Refusing to merge unrelated histories" dann liegt das daran das deine Historien der beide Repos zu unterschiedlich sind. Du kannst diesen Error lösen mit:
```sh
git pull <name von remote> <branch> --allow-unrelated-histories
```

3. Pushe den Inhalt deines Lokalen Repos zum Remote Repo in einen bestimmten Branch:
```shell
git push <name von Repo> <branch>
```  

**15. Git clone**.
1. Klone ein Remote Repo in den lokalen Speicher
```shell
git clone <URL von remote Repo>

```


