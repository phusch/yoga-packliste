JEANETTES YOGA-PACKLISTE – iPHONE-WEB-APP – V1.0

Inhalt:
index.html – interaktive Packliste
manifest.webmanifest – App-Name, Startansicht und Icons
sw.js – Offline-Nutzung nach Erstaufruf
icon-192.png, icon-512.png, apple-touch-icon.png – App-Icons

VERÖFFENTLICHEN MIT GITHUB PAGES (neues, separates Repo):
1. Bei GitHub ein neues Repository, z. B. jeanette-yoga-bezau, erstellen.
   Das Repo für GitHub Pages bei einem Free-Konto öffentlich anlegen.
   Achtung: Inhalte sind dann öffentlich zugänglich (Name, Ort und Reisedatum).
2. Die 6 Dateien aus diesem Ordner direkt in die oberste Ebene des Repositorys hochladen (nicht den Ordner selbst).
3. Settings → Pages → Build and deployment → Deploy from a branch; Branch main, Folder /(root), Save.
4. Die von GitHub Pages angezeigte URL in Safari auf dem iPhone öffnen.
5. Teilen → Zum Home-Bildschirm → Hinzufügen. Ab dann Icon antippen.

PERSISTENZ / GRENZEN:
Abgehakte Punkte und eigene Einträge werden lokal im Speicher der jeweiligen
Website/App gespeichert, nicht in GitHub. Sie bleiben beim normalen Schließen
erhalten; sie können durch Löschen der Website-Daten oder bei Gerätewechsel
verloren gehen. Für wichtige Listen unter „Sicherung speichern (JSON)“ exportieren.
Safari-Tab und installierte Home-Bildschirm-App können getrennte Speicher haben.
Zum Umzug daher über JSON exportieren/importieren. Keine Cloud-Synchronisation.

Die HTML-Datei allein kann ohne Webserver als Vorschau genutzt werden, aber
die PWA-Installation und Offline-Funktion erfordern eine HTTPS-Veröffentlichung.
Bestehende GitHub-Apps bleiben unberührt.
