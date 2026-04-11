<div align="center">

# 🚲✨ Twitch CoPilot — Benutzer-Anleitung

### Interaktive Bike Navigation — Overlay für OBS, Moblin & Streaming-Apps

**Chat-gesteuerte Routen · POI-Entdeckung · Community-Abstimmung · Live-Übersetzung**

**von [nicetoTECHyou](https://github.com/nicetoTECHyou)**

[![Version](https://img.shields.io/badge/Version-4.2.1-9146FF)](./CHANGELOG.md)
[![PWA Ready](https://img.shields.io/badge/PWA-Installable-9146FF?logo=pwa&logoColor=white)](https://web.dev/learn/pwa/)

<br>

[![App Ready to use](https://img.shields.io/badge/APP-READY%20TO%20USE-blue?style=for-the-badge&logo=rocket&logoColor=white)](https://nicetotechyou.github.io/TwitchCoPilot/)

<br>

[![Anleitung](https://img.shields.io/badge/DOKUMENTATION-VOLLST%c3%84NDIGE%20ANLEITUNG-purple?style=for-the-badge&logo=twitch&logoColor=white)](https://github.com/nicetoTECHyou/TwitchCoPilot/blob/main/Anleitung.md)

</div>

---

## 🚀 Schnellstart

**Du brauchst nichts zu installieren. Keinen Server. Keine Datenbank. Nichts.**

1. Öffne **[nicetotechyou.github.io/TwitchCoPilot/](https://nicetotechyou.github.io/TwitchCoPilot/)** im Browser
2. Erlaube den Standortzugriff (für GPS-Navigation)
3. Plane eine Route und los geht's!

### Als App installieren (optional)

- **Android Chrome:** Menü (⋮) → "Zum Startbildschirm hinzufügen"
- **iOS Safari:** Teilen (↑) → "Zum Startbildschirm"
- **Desktop Chrome/Edge:** Install-Icon in der Adressleiste

---

## 📺 Overlay im Stream einrichten

### OBS Studio

1. Rechtsklick auf eine Quelle → **Hinzufügen** → **Browser**
2. URL: `https://nicetotechyou.github.io/TwitchCoPilot/?overlay=true`
3. Breite: `1920`, Höhe: `1080`
4. "Lokale Datei" deaktivieren → **OK**

### Moblin (Handy-Streaming)

1. Widgets → Web-Widget hinzufügen
2. URL: `https://nicetotechyou.github.io/TwitchCoPilot/?overlay=true`
3. Größe anpassen

### Multi-Device-Sync (Handy + PC)

1. **Overlay-Gerät** (PC): Overlay-URL öffnen → Raum-Code erscheint
2. **Navi-Gerät** (Handy): App öffnen → Einstellungen → OBS Sync → Code eingeben → Verbinden
3. Alle Navi-Daten strömen live zum Overlay (GPS, Speed, Route, Chat, Voting, Wetter)

Funktioniert mit **OBS, Moblin, Streamlabs** und jeder App die Browser-Sources unterstützt.

---

## 🗺️ Overlay-Elemente (alle ein-/ausschaltbar)

| Element | Beschreibung |
|---------|-------------|
| Geschwindigkeit | Aktuelle km/h mit farblicher Anzeige |
| Routen-Info | Reststrecke, ETA, Auf-/Abstieg |
| Wetter | Temperatur und Wetter-Beschreibung |
| Chat-Feed | Letzte Chat-Nachrichten scrollend |
| Voting | Aktive Abstimmung mit Fortschrittsbalken |
| Minimap | Kleine Karte mit Route + GPS-Position |
| Nav-Pfeil | Nächste Abbiegung |
| Fortschritt | Horizontaler Routen-Fortschrittsbalken |

### Edit-Modus

Klicke auf **✏️** (Stift-Icon) im Overlay um Elemente per Drag & Drop zu verschieben. Größen über die Einstellungen anpassbar (50%-200%).

---

## 💬 Chat-Befehle (für Zuschauer)

| Befehl | Beschreibung |
|--------|-------------|
| `!help` | Alle Befehle anzeigen |
| `!navi [Adresse]` | Wegpunkt vorschlagen |
| `!poi [Kategorie]` | POIs suchen |
| `!wetter` | Wetter an GPS-Position |
| `!route` | Aktuelle Route anzeigen |
| `!vote [Frage]` | Abstimmung starten |
| `!tts <Text>` | Text per TTS sprechen |
| `!translate <Sprache> <Text>` | Übersetzen (30+ Sprachen) |

---

## 📁 Dateien in diesem Paket

| Datei | Beschreibung |
|-------|-------------|
| `index.html` | Einstiegsseite der App |
| `assets/` | CSS + JS (gebundelt, minimiert) |
| `manifest.webmanifest` | PWA-Manifest |
| `sw.js` | Service Worker (Offline-Funktion) |
| `README.md` | Diese Datei — Kurzanleitung |
| `CHANGELOG.md` | Versionshistorie |
| `VERSION` | Aktuelle Versionsnummer |
| `Anleitung.md` | **Vollständige Anleitung** (alle Features im Detail) |

---

## 🔗 Links

| | |
|---|---|
| 🌐 **Live App** | [nicetotechyou.github.io/TwitchCoPilot/](https://nicetotechyou.github.io/TwitchCoPilot/) |
| 📖 **Vollständige Anleitung** | [Anleitung.md](./Anleitung.md) |
| 📋 **Changelog** | [CHANGELOG.md](./CHANGELOG.md) |
| 💻 **GitHub Repository** | [nicetoTECHyou/TwitchCoPilot](https://github.com/nicetoTECHyou/TwitchCoPilot) |

---

## 📜 Lizenz

CC BY-NC-SA 4.0 — Open Source, Non-Commercial. Siehe GitHub für Details.

<div align="center">

**Built with 💜 for the bike streaming community**

**by nicetoTECHyou**

</div>
