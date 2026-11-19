# 51 kostenlose Video-Effekte für Claude

Kostenlose Video-Effekte für Instagram Reels, TikTok und YouTube Shorts, direkt in Claude Code. Zieh dein Video in Claude, tippe `/effects` und den Namen eines Effekts. Mehr ist es nicht.

Ein Freebie von **THE DIGITAL SHIFT**. Angepasst und weiterentwickelt von **Bianca Steinberger**.

## Voraussetzung

Dieser Skill ist eine Ergänzung und läuft nur, wenn du Folgendes schon hast:

1. **Claude Code** (App oder Terminal), installiert und einsatzbereit.
2. Deinen **Claude Cutter**, bereits installiert und eingerichtet.

Ohne diese beiden Dinge funktionieren die Effekte nicht. Installiere zuerst den Claude Cutter und dann diese Effekte.

## Installation

Öffne die Terminal-App (oder das Terminal in Claude Code) und füge ein:

```bash
git clone https://github.com/sotti88/claude_cutter_effekte ~/.claude/skills/effects
```

Unter Windows (PowerShell) nimmst du `$HOME\.claude\skills\effects` statt `~/.claude/skills/effects`.

Starte danach Claude Code neu. Fertig.

## So benutzt du es

1. Öffne Claude Code (App oder Terminal).
2. Zieh dein Video in den Chat.
3. Tippe den Effekt, den du willst:

```
/effects orbit von Sekunde 3 bis 6
/effects spotlight wenn ich "Licht aus" sage, mit dem Wort Claudit hinter mir
/effects comment-box am Ende, tippt CLAUDE
/effects glass-widgets für die ersten 3 Sekunden
```

Beim allerersten Mal richtet sich Claude selbst ein (etwa 2 Minuten). Es braucht `ffmpeg` und Python und installiert beides für dich, falls es fehlt.

Claude prüft zuerst ein paar Einzelbilder, korrigiert alles, was dein Gesicht verdeckt, und rendert dann `deinvideo_effects.mp4` direkt neben dein Original. Dein Ton bleibt unverändert.

Du kannst mehrere Effekte auf einmal kombinieren: *„Füge locked-on von 6 bis 10 s hinzu, dann orbit von 10 bis 13 s und dann einen Reject-Stempel bei ‚Nein'."*

## Die 51 Effekte

| # | Tippe das | Was passiert |
|---|---|---|
| 1 | `noise` | Reels stapeln sich hinter deinem Kopf |
| 2 | `lineup` | Nummerierte Kacheln fächern sich über deinem Kopf auf |
| 3 | `locked-on` | Eckklammern rasten auf deinem Gesicht ein und die Kamera folgt dir |
| 4 | `orbit` | Deine Reels kreisen um deinen Kopf, oben hinter dir |
| 5 | `lean-in` | Ein schneller Zoom auf ein Wort |
| 6 | `backdrop-word` | Ein riesiges Wort fällt hinter dir ins Bild |
| 7 | `spotlight` | Das Licht geht aus, nur du bleibst beleuchtet |
| 8 | `the-bill` | Deine Anweisungen werden wie ein Kassenbon ausgedruckt |
| 9 | `moody` | Ein stimmungsvoller Farblook |
| 10 | `swipe` | Ein Vorher-Nachher-Schieberegler |
| 11 | `todo` | Eine Checkliste neben deinem Kopf, die sich abhakt, während du sprichst |
| 12 | `comment-box` | Ein Instagram-Kommentar tippt sich selbst und wird abgeschickt |
| 13 | `tap` | Ein „Folgen"-Button wechselt zu „Gefolgt" |
| 14 | `pause-point` | Standbild mit handgezeichnetem Pfeil |
| 15 | `uninstall` | Ein glitchender Deinstallations-Balken zerlegt das Bild |
| 16 | `reel-frame` | Dein Video schrumpft zu einer Reel-Karte |
| 17 | `shortcut-rain` | Tastaturtasten regnen hinter dir herab |
| 18 | `reject-stamp` | Ein großer roter Stempel knallt aufs Bild |
| 19 | `countdown-flip` | Eine 3-2-1-Flipuhr über deinem Kopf |
| 20 | `rabbit-hole` | Der Raum hinter dir verschwindet wie in einem Tunnel |
| 21 | `cover-star` | Du wirst zum Magazin-Cover |
| 22 | `scribble` | Marker-Kritzeleien zeichnen sich selbst um dich herum |
| 23 | `glass-widgets` | Milchglas-Widgets und Mini-Artefakte schweben um deinen Kopf |
| 24 | `red-collage` | Du in Schwarz-Weiß, ein riesiges rotes Wort dahinter, drei Zeilen knallen rein |
| 25 | `split-headline` | Eine Schlagzeilen-Karte rutscht herunter und schiebt dich in die untere Bildhälfte |
| 26 | `pastel-word` | Lavendelfarbener Raum, ein riesiges Wort hinter dir, einer Profilkarte wird gefolgt |
| 27 | `check-pills` | Raum mit Kariertpapier-Look, deine Reels hinter dir angepinnt, blaue Pillen werden angeklickt |
| 28 | `timeline` | Ein dunkelroter Filmlook mit Schnitt-Zeitleiste und leuchtendem Abspielkopf |
| 29 | `headline-box` | Ein Zoom mit einer klaren zweizeiligen Schlagzeile |
| 30 | `profile-wall` | Das Raster deiner Reels füllt die Wand, während ein Zähler hochläuft |
| 31 | `tier-list` | Eine Tier-Liste fällt ein und Claude fliegt in die S-Stufe |
| 32 | `broll-split` | B-Roll oben mit Preisschild-Sticker, du darunter |
| 33 | `phone-fan` | Deine Reels fächern sich auf wie ein Blatt aus Handys |
| 34 | `dot-reveal` | Dein Bild baut sich aus leuchtenden Punkten auf und wird dann scharf |
| 35 | `headline-wall` | Deine Schlagzeilen stapeln sich hinter deinem Kopf, dann springt eine Gesamtzahl nach vorne |
| 36 | `checklist` | Eine Claude-Aufgabenliste unter deinem Kinn, jeder Schritt wird grün abgehakt |
| 37 | `liquid-glass-graph` | Eine Liquid-Glass-Karte mit einem steigenden Graphen und hochzählender Zahl |
| 38 | `carousel-spin` | Deine Reels drehen sich in einem 3D-Karussell um dich |
| 39 | `match-cut` | Zeitungsseiten schneiden auf ein Wort und sitzen fest hinter deinem Kopf |
| 40 | `apple-toggles` | iPhone-Schalter springen unter deinem Kinn an, Zeile für Zeile |
| 41 | `led-sign` | Das Licht geht aus und ein leuchtendes LED-Schild schreibt sich hinter dir selbst |
| 42 | `slow-push` | Ein langsamer, filmischer Zoom, während der Raum unscharf wird |
| 43 | `over-the-shoulder-zoom` | Zoom in eine Bildecke, ein Liquid-Glass-Graph poppt neben deinem Kopf auf, dann die andere Ecke mit einem zweiten Graphen |
| 44 | `messages` | iMessage-Benachrichtigungen poppen nacheinander mit sanftem Leuchten auf |
| 45 | `place-in-grid` | Du schrumpfst in die Mitte deines 3×3-Profilrasters, deine Reels poppen mit Aufrufzahlen um dich herum auf |
| 46 | `tape-label` | Ein gelber Klebestreifen mit deinem Satz landet auf deiner Brust |
| 47 | `select-resize` | Ein blauer Auswahlrahmen greift deine Zahl und ein Cursor zieht sie größer |
| 48 | `wave-trim` | Die stillen Stellen deiner Stimme werden im Bild weggeschnitten, bis nur noch deine Worte übrig sind |
| 49 | `huge-strike` | Ein riesiges Serifen-Wort füllt die Wand hinter dir, dann streicht eine rote Linie es durch |
| 50 | `crayon-write` | Ein roter Wachsmalstift schreibt dein Wort hinter deinen Kopf und unterstreicht es |
| 51 | `fan-build` | Deine Reel-Cover werden Karte für Karte hinter deinem Kopf zu einem Fächer ausgeteilt |

Bonus-Looks: `/effects glitter-spotlight` (goldene Strahlen und Funkeln), `cover-star look=editorial` (ein klassisches Magazin-Cover) und `liquid-glass-graph look=bento` (ein gläsernes Dashboard um dich herum).

Jeder Effekt folgt deinem Gesicht. Alles, was dein Gesicht verdecken würde, wandert stattdessen hinter deinen Kopf.

**Tipps**
- Vertikale Handyvideos, in denen du im Bild bist, funktionieren am besten.
- Sag das Timing in normalen Worten („wenn ich ‚Achtung' sage"). Claude findet die genaue Sekunde.
- Du willst deine eigenen Reels in `orbit`, `noise`, `phone-fan` oder `profile-wall`? Gib Claude einen Ordner mit Screenshots.
- Diagramme, Zähler und Schlagzeilen sollten deine echten Zahlen verwenden. Sag Claude, welche das sind.
- Gerendert wird in 1080p. Auf Wunsch auch in 4K (dauert länger).

## Ehrliche Hinweise
- Das sind **Starter-Versionen**. Sounddesign, Untertitel und feines Timing sind nicht enthalten.
- Es erstellt einen Entwurf, du gibst ihn frei. Schau dir das Ergebnis an, bevor du postest.
- Es werden keine Sounds oder Untertitel hinzugefügt. Die ergänzt du in CapCut.

## Wenn etwas schiefgeht
Sag Claude einfach, was du siehst („das Wort verdeckt mein Gesicht", „es ist zu schnell"). Claude passt den Plan an und rendert neu.

## Mehr von THE DIGITAL SHIFT
Dieses Freebie kommt von **THE DIGITAL SHIFT**. Wenn du lernen willst, wie du KI und Claude für dein Business und deine Inhalte einsetzt, schau bei uns vorbei.

👉 **[thedigitalshift.at/deinstart](https://thedigitalshift.at/deinstart)**

Instagram: **@thedigitalshift**

## Credits und Lizenz
Gesichtserkennung: [OpenCV YuNet](https://github.com/opencv/opencv_zoo) (MIT). Personen-Freisteller: [MediaPipe Selfie Segmenter](https://ai.google.dev/edge/mediapipe/solutions/vision/image_segmenter) (Apache 2.0). Schriften: Archivo Black, Instrument Serif, Space Mono, Inter, Anton, Montserrat (SIL OFL) und Permanent Marker (Apache 2.0); die Lizenzen liegen in `fonts/`. Code: MIT, siehe `LICENSE`.
