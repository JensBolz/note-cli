Abschlussprojekt: note-cli
Du richtest ein vollständiges GitHub-Repository für note-cli ein – ein kleines Kommandozeilentool, mit dem man Notizen speichern, auflisten und löschen kann. Jede Notiz wird als einfache Textdatei unter .notes/db/ gespeichert, wobei der Dateiname der SHA-Hash des Inhalts ist – ohne Titel, ohne Endung. Eine Notiz ist schlicht ihr Inhalt. Den Code dafür bekommst du bereitgestellt. Du musst ihn nicht selbst schreiben und wirst auch nicht darüber befragt.

Die drei Commands:

note add <text> – Speichert die Notiz unter .notes/db/<hash>
note list – Listet alle gespeicherten Notizen mit ihrem Hash auf
note delete <hash> – Löscht die Notiz mit dem entsprechenden Hash
Repository-Struktur

Der main-Branch enthält die Basis des Projekts und soll folgende Commits in dieser Reihenfolge aufweisen:

„Initial commit" – README, Lizenz, .gitignore
„Add project structure" – grundlegende Ordnerstruktur
„Implement note add" – Notiz hinzufügen, gespeichert unter .notes/db/<hash>
„Implement note list" – alle gespeicherten Notizen auflisten
Zusätzlich gibt es zwei weitere Branches:

feature/delete – baut auf dem dritten Commit von main auf und implementiert note delete <hash>. Dieser Branch ist damit bewusst einen Commit hinter main.

gh-pages – enthält eine einfache statische Landingpage für note-cli, die über GitHub Pages erreichbar ist.

Was du einrichtest:

Rulesets, sodass niemand direkt auf main pushen kann
Ein Kanban-Board mit den Features als Issues, sinnvoll auf die Spalten verteilt
Ein kleines Wiki mit einer Seite, die den Aufbau des Tools beschreibt
Discussions eingerichtet
Dependabot aktiviert
Einen Webhook über webhook.site, der bei jedem Push eine Benachrichtigung auslöst
Codespaces eingerichtet, sodass der Mentor während der Prüfung beitreten kann
Was dich in der Prüfung erwartet:

Die Prüfung findet direkt im Repository statt, in Codespaces oder im GitHub Editor. Der Mentor führt dich situativ durch dein Repository – es gibt keine feste Reihenfolge und nichts auswendig zu Lernendes.

Du solltest die grundlegenden Git-Befehle sicher beherrschen, sowohl Porcelain als auch die einfachen Plumbing-Befehle. Ein Teil der Prüfung wird darin bestehen, gemeinsam den .git-Ordner zu öffnen und zu erklären, was dort liegt. Das ist kein neues Terrain, sondern genau das, was im Kurs besprochen wurde.

Es werden keine komplexen Operationen verlangt. Kein kompliziertes Rebase über viele Commits, keine kritischen Eingriffe in die Historie. Es geht darum, dass du weißt, was du tust – nicht darum, dich in Stresssituationen zu manövrieren. Fehler sind nicht das Problem. Wer einen Fehler macht, ihn erkennt und erklären kann, was schiefgelaufen ist, zeigt damit mehr Verständnis als jemand, der auswendig gelernte Schritte fehlerfrei abarbeitet.

Was zählt, ist dass du sicher und professionell durch dein eigenes Repository führen kannst – dass man dir ansieht, dass du weißt, was du tust und warum.