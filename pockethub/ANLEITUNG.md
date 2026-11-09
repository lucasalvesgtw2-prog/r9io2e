# PocketHub – Installation auf Android

PocketHub ist eine installierbare Web-App (PWA). Nach der Installation hat sie ein eigenes Icon auf dem Startbildschirm, öffnet im Vollbild und funktioniert auch offline – wie eine normale App.

## Diese Dateien gehören zur App

```
index.html
manifest.webmanifest
sw.js
icons/icon-192.png
icons/icon-512.png
icons/icon-maskable-512.png
```

Den Ordner `.claude` und diese Anleitung brauchst du nicht hochzuladen.

## Schritt 1: App online stellen (einmalig, kostenlos)

Android installiert Web-Apps nur von einer HTTPS-Adresse. Wähle eine Variante:

**Variante A – Netlify (am einfachsten)**
1. Am PC https://app.netlify.com/drop öffnen und ein kostenloses Konto anlegen.
2. Einen Ordner mit den 6 Dateien oben (inkl. Unterordner `icons`) in das Feld ziehen.
3. Du bekommst eine Adresse wie `https://irgendwas.netlify.app`.

**Variante B – GitHub Pages**
1. Auf github.com ein neues öffentliches Repository anlegen und die Dateien hochladen.
2. Settings → Pages → Branch `main` auswählen → Save.
3. Nach ca. 1 Minute ist die App unter `https://DEINNAME.github.io/REPO/` erreichbar.

## Schritt 2: Auf dem Handy installieren

1. Die Adresse in **Chrome** auf dem Android-Handy öffnen.
2. Menü **⋮** → **App installieren** (oder **Zum Startbildschirm hinzufügen**).
3. PocketHub vom Startbildschirm öffnen, Sprache wählen und deine 4-stellige PIN festlegen.

## Optional: Echte APK-Datei

Wenn die App online ist, kann https://www.pwabuilder.com daraus eine Android-APK bauen: Adresse eingeben → **Package for stores** → **Android** → herunterladen und auf dem Handy installieren.

## Wichtig zu wissen

- **Daten bleiben nur auf deinem Handy** und werden für immer gespeichert, bis du sie löschst. Nichts wird ins Internet geschickt (außer der Abruf der Wechselkurse).
- **Immer dieselbe Adresse benutzen.** Die Daten hängen an der Adresse der App.
- **Backup machen:** Einstellungen → *Backup exportieren*. Wenn du die App deinstallierst oder in Chrome die Website-Daten löschst, sind die Daten sonst weg.
- **PIN vergessen?** Geheime Notizen, Passwörter und Account-Details sind mit der PIN verschlüsselt und lassen sich ohne PIN nicht wiederherstellen. Du kannst die App dann nur zurücksetzen (alles wird gelöscht).
- **Sicherheit:** Eine 4-stellige PIN schützt gut vor neugierigen Blicken. Nach 5 falschen Versuchen sperrt die App für 30 Sekunden (danach immer länger). Für Bankdaten o. Ä. ist ein richtiger Passwort-Manager trotzdem sicherer.
- **Erinnerungen & Timer** klingeln zuverlässig, solange die App offen ist oder im Hintergrund läuft. Ist sie komplett geschlossen, siehst du verpasste Erinnerungen beim nächsten Öffnen. Erlaube Benachrichtigungen in der App, damit sie auch als Android-Benachrichtigung kommen.

## Funktionen

Kalender · Uhr mit Weltuhr, Stoppuhr und Timer · Erinnerungen (auch wiederholend) · Checklisten · Wochenplaner · To-dos mit Priorität · Notizen · Geheime Notizen (PIN) · Passwörter (PIN, mit Generator) · Rechner · Virtuelles Geld · Währungsrechner (Euro, aktuelle EZB-Kurse) · Brawl-Stars-Accounts (Bild + Titel, Details mit PIN) · Einstellungen: Sprache Deutsch/Englisch, Design hell/dunkel, Auto-Sperre, PIN ändern, Backup.
