# Archiv

**Ein Arbeitsplatz für die Forschung mit historischen Quellen — lokal auf Ihrem Rechner.**

Archiv ist für alle, die mit digitalisierten Büchern, Zeitschriften,
Handschriften, Plänen und Bildern arbeiten: Quellen sammeln und beschreiben,
sie lesen und durchsuchen, Stellen markieren und kommentieren, Zusammenhänge
sichtbar machen und daraus einen Text mit sauberen Belegen schreiben. Alles in
einer Anwendung, ohne Konto und ohne Cloud.

**[Neueste Version herunterladen →](https://github.com/BorisBorisson/archiv-releases/releases/latest)**

---

## Was Archiv kann

**Sammlung.** PDFs und Bilder aufnehmen und beschreiben: Medienart (Buch,
Zeitschrift, Zeitung, Sammelwerk, Handschrift, Bild, Plan, Hochschulschrift,
Webseite) mit den passenden Feldern, Abschnitte und farbige Schlagwörter. Für
Digitalisate des Münchener Digitalisierungszentrums (MDZ) und von bavarikon
genügt der Link, und die Angaben werden übernommen.

**Lesen.** Ein Leser für Scans, Karten und Tafeln: stufenloser Zoom bis ins
Detail, auswählbarer Text, Inhaltsverzeichnis aus den Lesezeichen des PDFs.
Textstellen, Bildbereiche und Notizen werden farbig markiert und kommentiert —
und als gewöhnliche PDF-Anmerkungen in die Datei geschrieben, sodass sie auch
in jedem anderen PDF-Programm sichtbar sind.

**Texterkennung.** Lokal und ohne Internet, auch für Fraktur. Archiv erkennt
Spalten, Kopfzeilen, Randnotizen und Fußnoten und bringt den Text in die
richtige Lesereihenfolge. Erkannter Text lässt sich von Hand korrigieren und
wird als unsichtbare Textebene in das PDF geschrieben. Der Text, den das
Digitalisat bereits mitbringt, bleibt erhalten und kann jederzeit
wiederhergestellt werden. Ganze Bücher werden im Hintergrund erkannt, während
Sie weiterarbeiten.

**Recherche.** Volltextsuche über das ganze Projekt — Quellen, Markierungen,
Notizen und Seitentext. Die Suche findet auch historische Schreibweisen
(„Tür“ findet „Thür“), ohne den Text selbst zu verändern, und mit „/16“ die
Anmerkung 16 samt den Stellen, die auf sie verweisen.

**Ideenfläche und Verbindungen.** Unbegrenzte Arbeitsflächen für Ausschnitte,
Bilder und Notizen. Begriffe in `[[doppelten Klammern]]` verknüpfen
Markierungen über alle Quellen hinweg; die Ansicht „Verbindungen“ zeigt das
entstehende Netz aus Begriffen und Quellen.

**Schreiben.** Eine Textverarbeitung für wissenschaftliche Arbeiten:
fortlaufend nummerierte Fuß- oder Endnoten, Zitate und Belege per Ziehen aus
den eigenen Markierungen, die Prüfung jedes Zitats gegen die Quelle,
Literaturverzeichnis, Abbildungen, Tabellen und Querverweise, Seitenansicht
mit Kopf- und Fußzeilen, Formatvorlagen und gesicherte Fassungen. Fünf
Zitierstile in deutscher Fassung: Chicago, „wie Anm.“, APA 7, MLA 9 und
Harvard. Export als Word-Datei mit echten Fußnoten, als PDF und als Markdown;
jedes Dokument liegt zusätzlich laufend als Word-Datei im Projektordner.

---

## Ihre Daten bleiben bei Ihnen

- **Kein Konto, keine Cloud.** Ein Projekt ist ein gewöhnlicher Ordner: eine
  Projektdatei (`.Archiv`) und daneben Ihre PDFs, Bilder und Word-Dateien.
  Sie können ihn sichern, kopieren oder mitnehmen wie jeden anderen Ordner.
- **Offene Formate.** Markierungen und erkannter Text stehen in den PDFs
  selbst, Texte liegen als `.docx` vor — lesbar auch ohne Archiv.
- **Internet nur für zwei Dinge:** die Suche nach Updates und das Abrufen von
  Angaben, wenn Sie den Link eines Online-Archivs eingeben. Texterkennung,
  Suche und alles andere laufen auf Ihrem Rechner.

---

## Installieren

| System | Datei | Voraussetzungen |
|---|---|---|
| **Windows** | `Archiv-Setup.exe` | Windows 10 oder 11, 64 Bit |
| **Mac** | `Archiv-macos-arm64.dmg` | Mac mit Apple-Chip (M1 oder neuer), macOS 15 (Sequoia) oder neuer |

**Windows:** `Archiv-Setup.exe` herunterladen und starten. Archiv wird nur für
Ihr Benutzerkonto installiert und braucht keine Administratorrechte. Beim
ersten Start kann Windows SmartScreen warnen: *Weitere Informationen* →
*Trotzdem ausführen*.
Für die Texterkennung braucht Archiv unter Windows zusätzlich das Programm
**Tesseract** ([Installer der UB Mannheim](https://github.com/UB-Mannheim/tesseract/wiki)).
Die Erkennungsmodelle, auch für Fraktur, bringt Archiv selbst mit; alle
anderen Funktionen arbeiten auch ohne Tesseract.

**Mac:** `Archiv-macos-arm64.dmg` öffnen und Archiv in den Ordner *Programme*
ziehen. Beim ersten Start meldet macOS, dass Archiv nicht geöffnet werden
kann: *Systemeinstellungen* → *Datenschutz & Sicherheit* → *Dennoch öffnen*.
Danach nie wieder. Die Texterkennung ist auf dem Mac bereits enthalten.

Die `.zip`-Dateien jeder Version sind für die automatischen Updates bestimmt;
zum Installieren dienen die Installer.

---

## Updates

Archiv hält sich selbst aktuell: Es sucht beim Start und alle sechs Stunden
nach einer neuen Version, lädt sie im Hintergrund und bietet in der Titelleiste
*Update bereit → Jetzt neu starten* an — oder setzt sie beim nächsten Schließen
ein. Jedes Update ist digital signiert; eine nicht signierte oder veränderte
Version lädt Archiv nicht.

---

## Stand der Entwicklung

Archiv befindet sich in einer frühen Phase (Version 0.0.x). Es wird täglich
benutzt und laufend weiterentwickelt; Funktionen und Oberfläche können sich
noch ändern. Bitte sichern Sie wichtige Projektordner regelmäßig. Vor jeder
Umstellung des Projektformats legt Archiv selbst eine Sicherungskopie der
Projektdatei an.

Fehler und Wünsche können als [Issue](https://github.com/BorisBorisson/archiv-releases/issues)
gemeldet werden.

---

<sub>**Über dieses Projekt.** Archiv wird von einer einzelnen Person
entwickelt. Der Programmcode ist zum großen Teil mit KI-Unterstützung
entstanden (Claude von Anthropic): Konzept, Entscheidungen und Prüfung liegen
beim Entwickler, jede Änderung durchläuft eine umfangreiche automatische
Testsuite. Der Quellcode ist nicht öffentlich; dieses Repository enthält nur
die fertigen Versionen. Archiv wird ohne Gewähr bereitgestellt.</sub>
