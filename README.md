# Homematic-Skripte von AppProject

Fertige **HM-Skripte** (HomeMatic Script) für die Homematic-Zentrale **CCU3, RaspberryMatic/OpenCCU** – zum Kopieren in die WebUI. Zu jedem Skript gibt es eine ausführliche Schritt-für-Schritt-Anleitung auf **[appproject.de](https://appproject.de/Hausautomatisierung/)**.

## So verwendest du ein Skript

1. WebUI öffnen → *Programme und Verknüpfungen* → *Programme & Zentralenverknüpfung*.
2. Neues Programm anlegen, Bedingung festlegen und als Aktion *Skript* wählen.
3. Inhalt der passenden `.hms`-Datei einfügen und Platzhalter wie `XXX` oder `IP-DES-GERAETS` durch eigene Werte ersetzen.
4. Mit *Skript testen* prüfen, dann speichern.

Viele Skripte nutzen den **CUx-Daemon (CUxD)** – Installation: [CUxD auf der CCU installieren](https://appproject.de/Hausautomatisierung/CuX/Cux_Daemon.html).

## Programm-Export für die Fehlersuche

[`skripte/appproject-export.hms`](skripte/appproject-export.hms) gibt alle Programme, Systemvariablen, Geräte und Räume der CCU als Text aus – ohne Passwörter oder Schlüssel. Die Ausgabe kann im [AppProject Homematic-Assistenten](https://appproject.de/ki-assistent/) auf Fehler und Widersprüche geprüft werden.

## Skripte nach Anleitung

### [Erweiterte Astrofunktion für Homematic](https://appproject.de/Hausautomatisierung/Astrofunktion/Astrofunktion.html)

- [`astrofunktion-skript-1.hms`](skripte/astrofunktion-skript-1.hms) – skript-1

### [Bose SoundTouch als Homematic MP3-Funkgong](https://appproject.de/Hausautomatisierung/FunkGong/BoseSoundTouchHomematicFunkGong.html)

- [`bose-soundtouch-und-homematic-funkgong-skript-1.hms`](skripte/bose-soundtouch-und-homematic-funkgong-skript-1.hms) – skript-1

### [Bose SoundTouch mit Homematic steuern](https://appproject.de/Hausautomatisierung/Bose/BoseSoundTouchHomematic.html)

- [`bose-soundtouch-und-homematic-skript-1.hms`](skripte/bose-soundtouch-und-homematic-skript-1.hms) – skript-1

### [INSTAR IN-9020 Full HD im Test mit Homematic](https://appproject.de/Hausautomatisierung/Instar9020/Instar_9020_Full_HD.html)

- [`instar-9020-full-hd-skript-1.hms`](skripte/instar-9020-full-hd-skript-1.hms) – skript-1
- [`instar-9020-full-hd-skript-2.hms`](skripte/instar-9020-full-hd-skript-2.hms) – skript-2
- [`instar-9020-full-hd-skript-3.hms`](skripte/instar-9020-full-hd-skript-3.hms) – skript-3
- [`instar-9020-full-hd-skript-4.hms`](skripte/instar-9020-full-hd-skript-4.hms) – skript-4
- [`instar-9020-full-hd-skript-5.hms`](skripte/instar-9020-full-hd-skript-5.hms) – skript-5
- [`instar-9020-full-hd-skript-6.hms`](skripte/instar-9020-full-hd-skript-6.hms) – skript-6
- [`instar-9020-full-hd-skript-7.hms`](skripte/instar-9020-full-hd-skript-7.hms) – skript-7

### [CGI-Befehle für INSTAR HD Kameras mit Homematic](https://appproject.de/Hausautomatisierung/Instar/InstarCGI_HD/InstarBefehleHD.html)

- [`instar-und-homematic-1-instar-cgi-befehle-hd-skript-1.hms`](skripte/instar-und-homematic-1-instar-cgi-befehle-hd-skript-1.hms) – skript-1
- [`instar-und-homematic-1-instar-cgi-befehle-hd-skript-2.hms`](skripte/instar-und-homematic-1-instar-cgi-befehle-hd-skript-2.hms) – skript-2
- [`instar-und-homematic-1-instar-cgi-befehle-hd-skript-3.hms`](skripte/instar-und-homematic-1-instar-cgi-befehle-hd-skript-3.hms) – skript-3
- [`instar-und-homematic-1-instar-cgi-befehle-hd-skript-4.hms`](skripte/instar-und-homematic-1-instar-cgi-befehle-hd-skript-4.hms) – skript-4
- [`instar-und-homematic-1-instar-cgi-befehle-hd-skript-5.hms`](skripte/instar-und-homematic-1-instar-cgi-befehle-hd-skript-5.hms) – skript-5
- [`instar-und-homematic-1-instar-cgi-befehle-hd-skript-6.hms`](skripte/instar-und-homematic-1-instar-cgi-befehle-hd-skript-6.hms) – skript-6
- [`instar-und-homematic-1-instar-cgi-befehle-hd-skript-7.hms`](skripte/instar-und-homematic-1-instar-cgi-befehle-hd-skript-7.hms) – skript-7
- [`instar-und-homematic-1-instar-cgi-befehle-hd-skript-8.hms`](skripte/instar-und-homematic-1-instar-cgi-befehle-hd-skript-8.hms) – skript-8

### [CGI-Befehle für INSTAR VGA Kameras mit Homematic](https://appproject.de/Hausautomatisierung/Instar/InstarCGI_VGA/InstarBefehleVGA.html)

- [`instar-und-homematic-2-instar-cgi-befehle-vga-skript-1.hms`](skripte/instar-und-homematic-2-instar-cgi-befehle-vga-skript-1.hms) – skript-1
- [`instar-und-homematic-2-instar-cgi-befehle-vga-skript-2.hms`](skripte/instar-und-homematic-2-instar-cgi-befehle-vga-skript-2.hms) – skript-2
- [`instar-und-homematic-2-instar-cgi-befehle-vga-skript-3.hms`](skripte/instar-und-homematic-2-instar-cgi-befehle-vga-skript-3.hms) – skript-3
- [`instar-und-homematic-2-instar-cgi-befehle-vga-skript-4.hms`](skripte/instar-und-homematic-2-instar-cgi-befehle-vga-skript-4.hms) – skript-4

### [INSTAR HD Kamera mit Homematic steuern](https://appproject.de/Hausautomatisierung/Instar/Instar.html)

- [`instar-und-homematic-skript-1.hms`](skripte/instar-und-homematic-skript-1.hms) – skript-1
- [`instar-und-homematic-skript-2.hms`](skripte/instar-und-homematic-skript-2.hms) – skript-2

### [Netatmo Presence mit Homematic steuern](https://appproject.de/Hausautomatisierung/Netatmo_Presence/NetatmoPresenceHomematic.html)

- [`netatmo-presence-homematic-skript-1.hms`](skripte/netatmo-presence-homematic-skript-1.hms) – skript-1

### [Philips Hue mit Homematic steuern](https://appproject.de/Hausautomatisierung/Hue/PhilipsHueHomematic.html)

- [`philips-hue-und-homematic-skript-1.hms`](skripte/philips-hue-und-homematic-skript-1.hms) – skript-1

## Hinweise

- Ohne Gewähr: Skripte vor dem Einsatz testen, besonders bei sicherheitsrelevanten Funktionen.
- Fragen und Hilfe: [Homematic Support & Fernwartung](https://appproject.de/Hausautomatisierung/HM-Support/Homematic_Support.html) · Facebook-Gruppe [Homematic – Die intelligente Haussteuerung](https://www.facebook.com/groups/1800201390237440).
- Homematic ist eine Marke der eQ-3 AG. Dieses Projekt ist nicht mit eQ-3 verbunden.

Lizenz: MIT – siehe [LICENSE](LICENSE).
