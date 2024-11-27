# my__project

1. in GitHub angemeldet

2. neues Repository inkl. README erstellt durch Klick auf Button „+ Neu“

3. URL des erstellten Repositorys: https://github.com/ClaudiaCorsten/My__Project.git

4. Mein Terminal Git Bash (Windows) geöffnet

5. verfügbare SSH-Schlüssel überprüft

- ls ~/.ssh/

  (rsa Schlüssel vorhanden)


6. -

7. -


8. in Verzeichnis „RepoTest“ gewechselt, in dem das Git-Repo erstellt werden soll

- cd RepoTest


9. GitHub-Repo „My__Project“ auf meinen lokalen Rechner geklont

- git clone https://github.com/ClaudiaCorsten/My__Project.git


10. ins geklonte Verzeichnis navigiert

- cd My__Project


11. Git mit meinem Namen und E-Mail konfiguriert

- git config user.name „ClaudiaCorsten“

- git config user.email „c-corsten@t-online.de“


12. Neue Datei „html_file.txt hinzugefügt und einen Initial-Commit erstellt

- git add html_file.txt

- git commit -m „Initialer Commit“


13. neuen Branch mit Namen „feature“ erstellt

- git checkout -b feature

14. eine weitere Datei („my_changes.txt) hinzugefügt und einen Commit auf dem „feature“-Branch erstellt

- git add my_changes.txt

- git commit -m „Neue Funktion hinzugefügt“


15. „html_file.txt“ in „html_file_1.txt“ umbenannt
Änderung bestätigt und einen Commit auf dem „feature“-Branch durchgeführt

- git add html_file.txt

- git commit -m „Hauptdatei aktualisiert“


16. zurück zum „main“-Branch gewechselt

- git checkout main


17. html_file.txt geändert und einen Commit auf dem „main“-Branch durchgeführt

- git add html_file.txt

- git commit -m „Hauptdatei aktualisiert“


18. Versuch, den „feature“-Branch ind den „main“-Branch zu mergen

- git merge feature

	Merge-Konflikt ist aufgetreten!


19.  merging abbrechen, damit weitere Eingaben möglich sind

- git merge –quit


20. neuen „Titel“-Branch erstellt und darauf gewechselt

- git switch -c titel

durch löschen von Zeilen, die nicht übernommen werden sollen und entfernen von Markern, Konflikt gelöst


21. zu „main“-Branch gewechselt

- git switch main


22. Commits in GitHub veröffentlicht

- git push
