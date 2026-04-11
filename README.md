<div align="center">

# 🚲✨ Twitch CoPilot

### Interaktive Bike Navigation für Jedermann — mit Chat-Anbindung für Twitch Streamer

**Dein Chat steuert deine Route · POIs entdecken · Community-Abenteuer · Live-Übersetzung in 30+ Sprachen**

**von [nicetoTECHyou](https://github.com/nicetotechyou)**

<br>

[![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)](https://react.dev)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![Vite](https://img.shields.io/badge/Vite-8-646CFF?logo=vite&logoColor=white)](https://vitejs.dev)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![MapLibre](https://img.shields.io/badge/MapLibre_GL-5.22-1AAC71?logo=maplibre&logoColor=white)](https://maplibre.org)
[![Zustand](https://img.shields.io/badge/Zustand-5-764ABC?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiNmZmZmZmYiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIj48cGF0aCBkPSJtMyAxMSAxOC02LTktMCIvPjxwYXRoIGQ9Im0zIDE1IDE4IDYtOSAwIi8+PC9zdmc+&logoColor=white)](https://github.com/pmndrs/zustand)
[![tmi.js](https://img.shields.io/badge/tmi.js-1.8.5-5C3A7E)](https://github.com/tmijs/tmi.js)
[![Version](https://img.shields.io/badge/Version-4.3.2-9146FF)](./CHANGELOG.md)
[![PWA Ready](https://img.shields.io/badge/PWA-Installable-9146FF?logo=pwa&logoColor=white)](https://web.dev/learn/pwa/)
[![License](https://img.shields.io/badge/License-CC_BY_NC_SA_4.0-green)](#-lizenz)

<br>

[![App Ready to use](https://img.shields.io/badge/APP-READY%20TO%20USE-blue?style=for-the-badge&logo=rocket&logoColor=white)](https://nicetotechyou.github.io/TwitchCoPilot/)
&nbsp;&nbsp;
[![Anleitung](https://img.shields.io/badge/DOKUMENTATION-ZUR%20ANLEITUNG-purple?style=for-the-badge&logo=twitch&logoColor=white)](https://github.com/nicetoTECHyou/TwitchCoPilot/blob/main/Anleitung.md)

<br>
<br>

<img src="https://img.shields.io/badge/Installieren-0%20€-success?style=flat-square" /> &nbsp;
<img src="https://img.shields.io/badge/Account_nötig-NEIN-success?style=flat-square" /> &nbsp;
<img src="https://img.shields.io/badge/API_Key_nötig-NEIN-success?style=flat-square" /> &nbsp;
<img src="https://img.shields.io/badge/Deutsch_&_Englisch-✓-informational?style=flat-square" /> &nbsp;
<img src="https://img.shields.io/badge/100%25_Open_Source-✓-9146FF?style=flat-square" />

</div>

---

## 🚀 In 30 Sekunden loslegen

Twitch CoPilot ist eine Web-App — **nichts installieren, nichts registrieren**. Einfach öffnen und losfahren.

> **1.** App offnen: [**nicetotechyou.github.io/TwitchCoPilot**](https://nicetotechyou.github.io/TwitchCoPilot/)
>
> **2.** Start und Ziel eingeben — Route wird berechnet
>
> **3.** Auf dem Handy zum Startbildschirm hinzufugen (PWA) — fertig

**Als Streamer?** Twitch-Zugangsdaten in den Einstellungen eingeben — der Bot verbindet sich automatisch und reagiert auf Chat-Befehle.

---

## 🗺️ Was ist Twitch CoPilot?

Twitch CoPilot verwandelt deine Fahrradtour in ein **interaktives Live-Streaming-Erlebnis** — oder dient einfach als vollwertige Bike-Navigation fur Jedermann. Dein Twitch-Chat kann Ziele vorschlagen, uber Routen abstimmen, POIs entdecken und deine Navigation steuern — alles in **Echtzeit**.

Mit dem integrierten **Universal-Ubersetzer** werden Chat-Nachrichten und TTS-Ansagen in **30+ Sprachen** ubersetzt — komplett kostenlos, kein API-Key notig.

Gebaut als **vollstandig offline-fahige PWA** mit Service-Worker-Caching fur Karten, Routen und API-Daten.

---

## 🧭 Navigation

| | |
|---|---|
| 🗺️ **6 Kartenstile** | Strasse, Satellit, Topographisch, Dunkel, Hillshade + **✦ Sterne** — Live-Sternkarte mit Sternbildern, Planeten & Mond |
| 📍 **7 Routing-Profile** | Fast Bike, Trekking, MTB, Safety, Car, Walk — powered by [BRouter](https://brouter.de) |
| 🔀 **Via-Stopps** | Unbegrenzte Zwischenstopps per Rechtsklick auf die Karte |
| 🅰️ **3 Routenoptionen** | Kurzeste, Schnellste, Alternativ — immer die passende Wahl |
| 📊 **Hohendaten** | Auf-/Abstieg automatisch von BRouter geparst |
| 📤 **Export/Import** | JSON (1:1 Route), GPX, KML, TCX — kompatibel mit Garmin, Wahoo, Komoot |
| 🎯 **GPS-Tracking** | Live-Position mit Puls-Animation + Auto-Center |
| 🎮 **Demo-Modus** | 120s simulierte Fahrt — einfach ausprobieren, kein GPS notig |
| 🔄 **Auto-Rerouting** | Kommst du von der Route ab? Wird automatisch neu berechnet |
| 🔊 **TTS-Navigation** | Abbiegeansagen bei 500m, 200m, 50m + Ankunftsansage per Stimme |

---

## 📺 Twitch-Chat-Steuerung

Deine Zuschauer steuern deine Navigation direkt per Chat — der Bot reagiert auf Befehle in Echtzeit.

```
┌─────────────────────────────────────────────────────────┐
│                    TWITCH CHAT                           │
│                                                          │
│  Zuschauer:  !navi Brandenburger Tor                     │
│       │                                                  │
│       ▼                                                  │
│  ┌─────────┐     ┌──────────┐     ┌──────────────────┐  │
│  │ tmi.js   │────▶│  Bot     │────▶│  Wegpunkt        │  │
│  │ IRC Bot  │     │  prüft   │     │  erscheint auf   │  │
│  │          │◀────│  & antw. │     │  der Karte ✅    │  │
│  └─────────┘     └──────────┘     └──────────────────┘  │
│                                                          │
│  Bot:  ✅ @viewer Wegpunkt hinzugefügt: Brandenburger Tor│
└─────────────────────────────────────────────────────────┘
```

### 💬 Alle Chat-Befehle

**Navigation & Info**

| Befehl | Beschreibung | Beispiel |
|--------|-------------|----------|
| `!navi [Adresse]` | Adresse als Wegpunkt vorschlagen | `!navi Brandenburger Tor` |
| `!poi [Kategorie]` | POIs in der Nahe suchen | `!poi ladesaeule` |
| `!wetter` | Aktuelles Wetter an GPS-Position | `!wetter` |
| `!position` | Aktuelle GPS-Position anzeigen | `!position` |
| `!stats` | Fahrstatistiken (Speed, Distanz, Hohe) | `!stats` |
| `!route` | Aktuelle Route mit Fortschritt | `!route` |
| `!notfall` | Krankenhauser & Polizei in der Nahe | `!notfall` |

**Community & Fun**

| Befehl | Beschreibung | Beispiel |
|--------|-------------|----------|
| `!vote [Frage]` | Ja/Nein-Abstimmung starten | `!vote Pause machen?` |
| `!vote start [F] \| [O1] \| [O2]` | Multi-Option-Abstimmung | `!vote start Essen? \| Döner \| Pizza \| Sushi` |
| `!tts <Text>` | Text per Stimme sprechen | `!tts Hallo Chat!` |
| `!tts-t <Text>` | Text ubersetzen + sprechen | `!tts-t Hello Chat!` |
| `!translate <Sprache> <Text>` | Universal-Ubersetzer (30+ Sprachen) | `!translate en Guten Morgen` |
| `!rank` | Command-Ranking der Zuschauer | `!rank` |
| `!help` | Alle verfugbaren Befehle | `!help` |
| `!version` | Aktuelle Version anzeigen | `!version` |

---

## 📡 Multi-Device-Sync & Overlay

Fahrst du mit dem Handy und streamst von einem zweiten Gerat? Kein Problem — Twitch CoPilot synchronisiert alle Navi-Daten in Echtzeit uber MQTT.

**Unterstutzt:** OBS, Moblin, Streamlabs und jede App die Browser-Sources nutzt.

```
┌──────────────────┐         MQTT         ┌──────────────────┐
│   📱 NAVI-GERÄT   │                      │  🖥️ OVERLAY-GERÄT │
│                  │    Raum-Code          │                  │
│  • GPS-Position  │──────────────────▶   │  • Speedometer   │
│  • Geschwindigkeit│     Echtzeit        │  • Route + Karte │
│  • Routendaten   │                      │  • Twitch Chat   │
│  • Wetter        │◀──────────────────   │  • Voting        │
│                  │                      │  • Wetter        │
│  Handy auf dem   │    nicetotechyou.     │  OBS / Moblin /  │
│  Fahrrad 🚲      │    github.io/...     │  Streamlabs 🎬   │
└──────────────────┘                      └──────────────────┘
```

### Einrichtung in 3 Schritten

**Schritt 1 — Overlay-Gerat** (PC, Laptop oder zweites Handy):

Overlay-URL als **Browser-Source** in deiner Streaming-Software offnen:
```
https://nicetotechyou.github.io/TwitchCoPilot/?overlay=true
```
> Ein Raum-Code erscheint automatisch auf dem Overlay.

**Schritt 2 — Navi-Gerat** (Handy auf dem Rad):

App offnen und den Raum-Code eingeben:
```
App → Einstellungen → OBS Sync → Code eingeben → Verbinden
```
```
https://nicetotechyou.github.io/TwitchCoPilot/
```

**Schritt 3 — Losfahren:**

Alle Navi-Daten stromen live zum Overlay — Speed, Route, Chat, Voting, Wetter. Alles automatisch.

### Overlay-Elemente

Jedes Overlay-Element kann **einzeln ein-/ausgeschaltet** und in der **Grosse skaliert** werden:

| Element | Beschreibung |
|---------|-------------|
| ⚡ **Speedometer** | Aktuelle Geschwindigkeit + Durchschnitt |
| 🗺️ **Minimap** | Kleine dunkle Karte mit Route + GPS-Radius |
| 📍 **Nav-Pfeil** | Richtungsanzeige zur nachsten Abzweigung |
| 💬 **Chat** | Twitch-Chat-Nachrichten im Overlay |
| 🗳️ **Voting** | Aktive Abstimmungen mit Ergebnis |
| 🌤️ **Wetter** | Temperatur und Windgeschwindigkeit |
| 📐 **Fahr-Info** | ETA, Distanz, Hohe, km heute |

---

## 🌐 Universal-Ubersetzer

Dein internationales Publikum? Kein Problem — Chat-Nachrichten werden automatisch ubersetzt.

```
🇩🇪 Zuschauer:   "wie spät ist es?"
         │
         ▼  !translate de auto ON
┌──────────────────┐
│  MyMemory API    │
│  (kostenlos,     │
│   kein Key)      │
└──────┬───────────┘
       ▼
🇬🇧 Chat:  "what time is it?"  ← automatically shown
```

- **30+ Sprachen** unterstutzt — DE, EN, FR, ES, IT, PT, NL, PL, RU, JA, ZH, KO, AR, TR, SV + mehr
- **3 Modi:** `!translate <sprache>` = Auto-Ubersetzung AN / `!translate <sprache> <text>` = Einmal / `!translate off` = AUS
- **TTS-Integration:** `!tts-t` ubersetzt UND spricht den Text in der Streamer-Sprache

---

## 🔍 POI-Entdeckung

16 Kategorien — echte OpenStreetMap-Daten mit detaillierten Popups.

| | | | |
|---|---|---|---|
| ⚡ Ladesaule | 🍕 Restaurant | ☕ Cafe | 🛒 Supermarkt |
| 🏥 Krankenhaus | 💊 Apotheke | ⛺ Camping | 🏛️ Sehenswurdigkeit |
| ⛽ Tankstelle | 💧 Trinkwasser | 🔧 Fahrradwerkstatt | 🚓 Polizei |
| 🚒 Feuerwehr | 🏧 ATM | 🥐 Backerei | + mehr |

- **Kartensuche** per Rechtsklick auf die Karte
- **POI-Shortcuts** als Schnellfilter-Overlay
- **!notfall** Chat-Befehl zeigt Krankenhauser & Polizei sofort

---

## 📱 Mobile & PWA

Twitch CoPilot ist eine **Progressive Web App** — installieren wie eine normale App, aber ohne App Store.

| | |
|---|---|
| 📲 **Installierbar** | Zum Startbildschirm hinzufugen — iOS, Android, Desktop |
| 🗺️ **Offline-Karten** | Service Worker cached Kartentiles fur 30 Tage |
| 📱 **Mobile-First** | Touch-optimiert, kein unerwunschtes Zoomen, Vollbild-Karte |
| 🔐 **HTTPS-Ready** | Erforderlich fur GPS auf mobilen Geraten |
| 🌙 **Dark/Light** | 5 Farbthemen: Twitch, Fahrrad, Electric, Sunset, Pink |
| 🌍 **DE/EN** | Vollstandige Deutsch/Englisch-Ubersetzung (200+ Texte) |

### ⌨️ Tastenkurzel

| Taste | Funktion |
|-------|----------|
| `Leertaste` | Navigation starten/stoppen |
| `D` | Demo-Modus starten |
| `M` | Karte zentrieren |
| `F` | Vollbild |
| `Esc` | Panel schliessen |

---

## 🎛️ Themes

Wahle dein Farbthema in den Einstellungen:

| Theme | Beschreibung |
|-------|-------------|
| 🟣 **Twitch** | Klassisch Lila — perfekt fur Streaming |
| 🟢 **Fahrrad** | Grun — naturverbunden, frisch |
| 🔵 **Electric** | Blau — technisch, clean |
| 🟠 **Sunset** | Orange — warm, energiegeladen |
| 🩷 **Pink** | Pink — auffallend, stylisch |

---

## ❓ Haufig gestellte Fragen

<details>
<summary><strong>📌 Was brauche ich um Twitch CoPilot zu nutzen?</strong></summary>
<br>

Nichts ausser einem Browser. Die App lauft im Browser — auf dem Handy, Tablet oder PC. Fur GPS brauchst du HTTPS (funktioniert automatisch auf der gehosteten Version). Fur die Twitch-Integration brauchst du einen Twitch-Account und einen OAuth-Token (wird in den Einstellungen generiert).

</details>

<details>
<summary><strong>📌 Kostet das etwas?</strong></summary>
<br>

Nein. Twitch CoPilot ist **100% kostenlos** — keine In-App-Kaufe, keine Werbung, keine Premium-Features. Alle APIs die genutzt werden (BRouter, Nominatim, Overpass, Open-Meteo, MyMemory) sind kostenlos und offen. Das Projekt ist unter CC BY-NC-SA 4.0 lizenziert.

</details>

<details>
<summary><strong>📌 Muss ich mich registrieren?</strong></summary>
<br>

Nein. Kein Account, keine Registrierung, keine E-Mail-Adresse. Einfach die App offnen und loslegen. Nur fur die Twitch-Integration brauchst du deine Twitch-Zugangsdaten — die bleiben auf deinem Gerat (localStorage), nichts wird an uns gesendet.

</details>

<details>
<summary><strong>📌 Funktioniert das auch ohne Twitch?</strong></summary>
<br>

Ja! Twitch CoPilot ist eine vollstandige Bike-Navigation — auch ohne Stream. Routen berechnen, GPS-Tracking, POI-Suche, Wetter, Export/Import — alles funktioniert ohne Twitch. Die Chat-Befehle sind ein Bonus fur Streamer.

</details>

<details>
<summary><strong>📌 Wie funktioniert das Overlay beim Streaming vom Handy?</strong></summary>
<br>

Wenn du mit Apps wie **Moblin** oder **Streamlabs** vom Handy streamst, offne die Overlay-URL auf einem **zweiten Gerat** (z.B. einem Laptop oder Tablet) als Browser-Source in deiner Streaming-Software. Dein Handy auf dem Rad sendet die Navi-Daten uber MQTT an das Overlay-Gerat. Der Raum-Code koppelt beide Gerate.

</details>

<details>
<summary><strong>📌 Welche Browser werden unterstutzt?</strong></summary>
<br>

Chrome 90+, Firefox 90+, Safari 15+, Edge 90+. Fur GPS-Funktionen wird Chrome empfohlen. TTS (Text-to-Speech) funktioniert am besten in Chrome.

</details>

<details>
<summary><strong>📌 Kann ich meine ownen Routen importieren?</strong></summary>
<br>

Ja! Unterstutzte Formate: **JSON** (1:1 identische Route), **GPX**, **KML**, **TCX**. Du kannst auch eine berechnete Route exportieren und auf einem anderen Gerat importieren — z.B. Route auf dem PC planen, als JSON an dich selbst per WhatsApp senden, auf dem Handy offnen und losfahren.

</details>

---

## 📋 Versionshistorie

Alle Anderungen sind detailliert in der [CHANGELOG.md](./CHANGELOG.md) dokumentiert.

| Typ | Format | Beispiel |
|-----|--------|----------|
| **Patch** | x.x.Z | Bug Fixes |
| **Minor** | x.Y.0 | Grosse Fixes, Security |
| **Major** | X.0.0 | Neue Features, Breaking Changes |

---

## 🔗 Links

| | |
|---|---|
| 🚀 **App starten** | [nicetotechyou.github.io/TwitchCoPilot](https://nicetotechyou.github.io/TwitchCoPilot/) |
| 📖 **Anleitung** | [Anleitung.md](./Anleitung.md) |
| 📋 **Changelog** | [CHANGELOG.md](./CHANGELOG.md) |
| 🛠️ **Entwickler-Doku** | [README.SOURCE.md](./README.SOURCE.md) |
| 💻 **Quellcode** | [GitHub Repository](https://github.com/nicetoTECHyou/TwitchCoPilot) |

---

## 📜 Lizenz

Dieses Projekt ist **Open Source** und darf frei verwendet, studiert und modifiziert werden — jedoch **nicht kommerziell verwertet**.

**CC BY-NC-SA 4.0**

- ✅ Quellcode einsehen, lernen und modifizieren
- ✅ Privat nutzen und weitergeben (nicht-kommerziell)
- ✅ Eigene Projekte darauf aufbauen (nicht-kommerziell)
- ❌ Nicht verkaufen oder als kostenpflichtiges Produkt verwenden
- 📝 Namensnennung erforderlich: "Basierend auf TwitchCoPilot von [nicetoTECHyou](https://github.com/nicetotechyou)"
- 🔄 Abgeleitete Werke mussen unter derselben Lizenz stehen

Kommerzielle Nutzung? [Kontaktiere uns](https://github.com/nicetoTECHyou) fur eine separate Vereinbarung.

---

<div align="center">

**Built with 💜 for the bike streaming community**

**by [nicetoTECHyou](https://github.com/nicetoTECHyou)**

</div>
