<!--
link : ./resources/oer-design_GL.css
icon : ./resources/icon_4Culture.png
version: 0.9
author: Martin Albrecht-Hohmaier, Katharina Bergmann, Vincent Fröhlich, Alexander Stark, Andrea Polywka
attribute: Der Kurs steht unter der CC-BY-Lizenz
language: de
narrator: Deutsch female
comment: Dieser Kurs ist eine Open Educational Resource der NFDI4Culture Arbeitsgruppe Cultural Research Data Academy (CRDA). Gefördert durch die Deutsche Forschungsgemeinschaft (DFG), Projektnummer 441958017. <br> Dieser Kurs ist unter Zuhilfenahme des Markdown-Dialekts LiaScript entstanden.
-->

# Basiskurs "Forschungsdatenmanangement für Geistes- und Kulturwissenschaften"

Eine Open Educational Resource der NFDI4Culture Arbeitsgruppe [Cultural Research Data Academy (CRDA)](https://nfdi4culture.de/id/E1826)

Mitarbeitende an diesem Projekt:<br>
[Martin Albrecht-Hohmaier](https://orcid.org/0000-0002-5279-7408), [Katharina Bergmann](https://orcid.org/0000-0002-0758-9917), [Vincent Fröhlich](https://orcid.org/0000-0001-8477-2689), [Andreas Münzmay](https://orcid.org/0000-0002-8373-4055), [Andrea Polywka](https://orcid.org/0000-0003-0003-6719), [Daniel Röwenstrunk](https://orcid.org/0000-0001-6271-2095), [Alexander Stark](https://orcid.org/0000-0003-4893-5924) 

<!--- Hier sollte noch Daniel erwähnt werden. --->

<img src= "../resources/NFDI4C_Logo_DyptichText.png" width=50% height=70%>

Gefördert durch die Deutsche Forschungsgemeinschaft (DFG).<br>
Projektnummer: 441958017

---

Wir freuen uns, wenn unsere Materialien nachgenutzt werden, deshalb steht dieser Kurs unter einer Lizenz, die die Nachnutzung ermöglicht: [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## Welche Inhalte bietet dieser Kurs?
Alle generischen Inhalte dieses Kurses werden ergänzt um fachspezifische Module. Diese tragen farbliche abgegrenzte Überschriften, um sie gut von den übrigen Inhalten unterscheiden zu können. Sie können beim Bearbeiten des Kurses übersprungen werden, bzw. dann bearbeitet werden, wenn sie sich für das Fach und die Inhalte interessieren.

**Inhalt**

 1. Forschungsdatenmanagement [>](#1. forschungsdatenmanagement) 
 2. Der Forschungsdatenbegriff [>](#2. der-forschungsdatenbegriff)
 3. Datenformate [>](#3. datenformate)
 4. Der Datenlebenszyklus [>](#4. der-datenlebenszyklus)
 5. Versionsverwaltung [>](#5. versionsverwaltung)
 6. Metadaten [>](#6. metadaten)
 7. Normdaten [>](7. #normdaten)
 8. FAIR und CARE [>](#8. fair-und-care)
 9. Sichern, Speichern, Publizieren und Archivieren [>](#9. sichern,-speichern,-publizieren-und-archivieren)
 10. Creative Commons Lizenzen[>](#10. creative-commons-lizenzen) 
 11. Der Datenmanagement-Plan [>](#11. der-datenmanagementplan)
 12. Datendokumentation [>](#12. dokumentation)
<br>
- Weiterführende Literatur [>](#weiterführende-literatur)
- Zusatzmaterial [>](#zusatzmaterial-interaktive-module)

### Abkürzungen in diesem Kurs

<!--- KB: Brauchen wir das? --->

- CRDA = Cultural Research Data Academy
- DFG = Deutsche Forschungsgemeinschaft
- DLZ = Datenlebenszyklus
- DMP = Datenmanagementplan
- FD = Forschungsdaten
- FDM = Forschungsdatenamangement
- LZA = Langzeitarchivierung

## 1. Forschungsdatenmanagement

Forschungsdatenamangement (FDM) umfasst alle Aktivitäten im Zusammenhang mit ...

- der Aufbereitung,
- Speicherung,
- Archivierung,
- und Nutzung

... von Forschungsdaten.

Der vorliegende Kurs wird die Grundlagen dieser Aspekte des Forschungsdatenmanagements betrachten.

---

FDM begleitet den gesamten Forschungsprozess und standardisierte FDM-Prozesse verringern den zukünftigen Aufwand bei einer eigenen oder fremden Nachnutzung der Daten.<br>FDM-Maßnahmen wie Datendokumentation, Datensicherung und eine geeignete Langzeitarchivierung (LZA) verringern zudem das Risiko von Datenverlusten. Außerdem steigern sie die Reproduzierbarkeit und Nachnutzbarkeit der Daten. Durch geeignete FDM-Maßnahmen können Daten bestenfalls noch nach Jahrzehnten genutzt werden.

Die vielseitigen technischen Möglichkeiten erfordern allerdings auch eine erhöhte Beachtung der Themen Datenschutz und Urheberrecht. Ebenso sollten weitere rechtliche und ethische Aspekte beachtet werden, um die gute wissenschaftliche Praxis zu wahren (s. a. [CARE-Principles](#die-care-prinzipien).)

Der fachgerechte Umgang mit Forschungsdaten ist zudem Teil guter wissenschaftlicher Arbeit und Fördermittelgeber erwarten einen strukturierten Umgang mit Forschungsdaten, festgehalten bspw. in Form eines Datenmanagementplans [DMP](#der-datenmanagementplan-dmp).

> Kodex [„Leitlinien zur Sicherung guter wissenschaftlicher Praxis“](https://doi.org/10.5281/zenodo.14281892) der DFG

## 2. Der Forschungsdatenbegriff

Wenn wir uns mit dem Thema Forschungsdatenmanagement auseinandersetzen, dann sollten wir klären, was eigentlich unter dem Begriff "Forschungsdaten" zu verstehen ist.

---

Die Deutsche Forschungsgemeinschaft (DFG) beschreibt es so:

„Ein fachspezifisch adäquater Umgang mit Forschungsdaten, die wissenschaftlichen Projekten zugrunde liegen oder bei deren Durchführung entstehen, ist ein wesentlicher Bestandteil qualitätsorientierter und anschlussfähiger Forschung. [...] Zu Forschungsdaten zählen u. a. Messdaten, Laborwerte, audiovisuelle Informationen, Texte, Surveydaten oder Beobachtungsdaten, methodische Testverfahren sowie Fragebögen.“
<sub>[Zitat der Deutschen Forschungsgemeinschaft (DFG) zum Umgang mit Forschungsdaten, 2023](https://www.dfg.de/de/grundlagen-themen/grundlagen-und-prinzipien-der-foerderung/forschungsdaten)</sub>

---

Wir haben unser Verständnis in diesem knappen Merksatz zusammengefasst:

> Digitale Daten werden zu Forschungsdaten, wenn sie wissenschaftlichen Richtlinien entsprechend erfasst, beschrieben, kontextualisiert oder kommentiert werden.

#### <font color=#a2d0eb> 🎬 Forschungsdaten in der Film- und Medienwissenschaft </font>

Innerhalb der Fachdisziplin der Medien- und Filmwissenschaft zeigen sich Forschungsdaten in unterschiedlichen Formen und Eigenschaften.

Medienwissenschaftliche Forschungsdaten zeichnen sich in der Regel durch ein äußerst heterogenes Material aus. Darunter zählen alle schriftlichen und bildlichen Aufzeichnungen sowie Material- und Quellensammlungen, mitunter auch Koppelungen von fremden und eigenen Daten, d. h. von Originalquellen und eigenen Annotationen, Zeichnungen o. ä. (vgl. [Goller / Heftberger 2018](https://doi.org/10.17176/20180515-233758)).

"Für die Filmwissenschaft [lässt sich] allein mit Blick auf Filmkorpora eine ähnliche Datenvielfalt feststellen: digitalisierte Filme, einzelne Videoausschnitte, filmografische Metadaten, Sequenzprotokolle, Annotationen, Informationen zur Dokumentation des Analyseverfahrens (Ausführungen zum theoretischen Hintergrund, Bibliografie der verwendeten Forschungsliteratur, Nennung der Beteiligten), Reflexion der ausgewählten Kategorien, Hinweise zu den verwendeten Softwareprogrammen" ([Dang 2020, S. 121](http://dx.doi.org/10.25969/mediarep/21687)).

Einen guten Einblick in die Vielfalt des Forschungsdaten-Begriffs in der Film- und Medienwissenschaft, bietet der Open Media Studies Blog in den Beiträgen aus seiner [Sonderreihe Forschungsdaten](https://mediastudies.hypotheses.org/tag/sonderreihe-forschungsdaten).

#### <font color=#d1bcf5> 🎨 Forschungsdaten in der Kunstgeschichte </font>
Kunsthistorische Forschungsdaten sind, wie das Fach selbst, sehr divers. Sie umfassen u. a.:

- Notizen
- Exzerpte
- Fotografien
- Annotationen
- Tabellen
- Skizzen
- Transkriptionen
- Textversionen
- Rekon­struk­tionen

Je nach fachlicher Ausrichtung braucht es andere Dateiformate und Analysetools, um mit ihnen umzugehen. Beispielsweise werden an 3D-Rekonstruktionen von Plastiken und Statuen andere Fragestellungen formuliert als an Architektur-Rekonstruktionen; an Buchmalerei andere Fragen als an Ölgemälde.

Die deutschsprachige Kunstgeschichte hat sich bisher nicht auf einen einheitlichen Umgang mit Forschungsdaten und feste Standards geeinigt. Doch steigt auch unter Kunsthistoriker:innen das Bewusstsein um die Relevanz guten Forschungsdatenmanagements. Mit dem [Münchner Memorandum „Forschungs­daten in der Kunst­geschichte: 10 Thesen“](https://doi.org/10.11588/artdok.00009194) liegt seit 2024 ein Paper vor, das auf Initiative des Deutschen Verbandes für Kunstgeschichte e. V., der Universitätsbibliothek Heidelberg / arthistoricum.net und des Zentralinstituts für Kunstgeschichte erarbeitet wurde, und aus Sicht des Faches in Deutschland aktuelle Anforderungen, Positionen und Impulse zur weiteren Entwicklung digitaler kunsthistorischer Forschungsdaten und ihrer Infrastruktur formuliert.

#### <font color=#99e089> 🎵 Forschungsdaten in der Musikwissenschaften </font>

Musikwissenschaftliche Forschungsdaten sind sehr divers, sie umfassen schließlich jegliche Daten, die im Verlauf von wissenschaftlichen Arbeitens entstehen – seien sie in unterschiedlichster Form digital (PDFs, Codierungen, Aufnahmen etc.) oder analog, wie auch deren digitale Reproduktionen.  

Sie umfassen u. a.:

- Notentexte und Textzeugen wie Skizzen, Briefe etc. (handschriftlich oder gedruckt)
- visuelle und audiovisuelle Quellen (Fotos, Videos, Interviews etc.)
- rein digitale Textzeugen (Emails, Webseiten, etc.)
- Datenbanken
- Annotation und Metadaten 
- Musikinstrumente und sonstige involvierte Hardware oder Objekte (Computer, Räume, etc.)

Vergleiche hierzu u. a. das ausführliche [Positionsapier](https://www.musikforschung.de/wp-content/uploads/2024/05/DFG-Forschungsdaten_GfM.pdf) der DFG mit der Gesellschaft für Musikforschung.

---

Musikbibliographische Forschungsdaten sind Teil der Recherche, der Beratung und der Vermittlung, z. B. bei: 


- Katalogisierung / Bestandserschließung, etwa bei der Erfassung, Analyse, Beschreibung, Kommentierung oder Auszeichnung (Materialität, Formate/Maße, Autor:in, Datierung, ...) von Beständen
- Bereitstellung von Daten digitaler Musikbibliotheken
- Digitalen Editionen und musikwissenschaftlichen Gesamtausgaben
- digitalen Werkverzeichnissen
- (verknüpften) Dateien und ihre Formaten (AV-Dateien, PDFs, MEI/TEI ...)
- Repositorien 
- urheberrechtlichen Aspekten


## 3. Datenformate
Jede Software hat ein vorgegebenes Dateiformat, in dem sie mit ihr erzeugte Daten speichert. Doch ist das in einigen Fällen nicht das einzige nutzbare Datenformat, in einigen Fällen auch nicht das beste für den jeweiligen (Forschungs-)Kontext. <br>
Grundsätzlich sollten Daten möglichst nie in proprietären Datenformaten gespeichert, gar archiviert werden. Proprietäre Datenformate sind solche, die von Hersteller:innen für eine bestimmte Software erstellt wurden und meist nur mit dieser nutzbar sind. Sie sind also keine offenen Standards und erschweren oder verhindern dadurch die Nachnutzbarkeit und Langzeitarchivierung der in ihrem Format gespeicherten Daten.<br>
Zudem sollte darauf geachtet werden, dass die gewählten Dateiformate ressourcenschonend sind, indem sie etwa geringere Mengen Speicherplatz beanspruchen als alternative Formate.

---
**Empfehlungen für Dateiformate** <br>
<sub>(zitiert aus [Kailus 2023](https://docs.nfdi4culture.de/ta2-fair-handreichung/empfehlungen-dateiformate#10-empfehlungen-f%C3%BCr-dateiformate))</sub>

Verwenden Sie möglichst weit verbreitete und mit einem ISO-Standard verbundene Dateiformate. Sie sollten nicht proprietär, also nicht an eine Software oder einen Hersteller gebunden, mit unterschiedlichen Programmen verwendbar und mit einer offenen Lizenz versehen sein und über eine frei zugängliche Dokumentation einschließlich der technischen Spezifikationen verfügen. Sie erlauben eine verlustfreie Speicherung ohne Kompression und sie sind einfach dekodierbar oder unmittelbar lesbar.<br>
Konsultieren Sie Ihre Datenplattform, welche Dateiformate dort entgegengenommen bzw. empfohlen werden.

Für die Kulturwissenschaften und für Kulturerbe-Sammlungen kann die Verwendung folgender Standard-Dateiformate empfohlen werden:
<br><br>

**Text**

- Extensible Markup Language (XML) 1.1, mit XML Schema Definition (XSD)
- Resource Description Framework in Attributes (RFDa) für das Einbetten von RDF-Statements in XML
- JavaScript Object Notation (JSON)
- JavaScript Object Notation for Linked Data (JSON LD)
- Comma-Separated Values (CSV)
- Textdatei (TXT) (Codierung UTF-8)
- Präsentationsformat: Portable Document Format A (PDF-A)
<br>

**Musik**

- Music Encoding Initiative (MEI)
- MusicXML
- LilyPond
- Humdrum
- Parsons Code
- ...
<br>

**Bild (Rastergrafiken)**

- Rohdaten: Digital Negative (DNG)
- Master: baseline Tagged Image File Format (TIFF), unkomprimiert; TIFF mit Lempel-Ziv-Welch-Komprimierung (TIFF-LZW)
- Joint Photographic Experts Group (JPEG 1 und JPEG 2000), verlustfrei komprimiert, lizenzfreie Bereiche
- Präsentationsformate (Derivate): JPEG, JPEG 2000, Portable Network Graphics (PNG)
<br>

**Bild (Vektorgrafiken) und CAD**

- Scalable Vector Graphics (SVG)
<br>

**Audio**

- Archivformat: Waveform Audio File-Format (WAV) in Verbindung mit Pulse Code Modulation (PCM); Free Lossless Audio Codec (FLAC)
- Präsentationsformat: MPEG-2 Audiolayer III (MP3)
<br>

**Video/Film**

- Archivformate:

  - Moving Picture Experts Group Motion JPEG 2000 (MJPEG2000)
  - Moving Picture Experts Group, Standard MPEG-4
  - Digital Picture Exchange (DPX), SMPTE 268M-2003, v 2.0
  - Material Exchange Format (MXF), SMPTE 377M
  - Codec FFV1 / Container MKV
  - TIFF mit FFV1 in Matroshka codiert
- Präsentationsformat: MP4 (MPEG-4, part 14)
- Weitere Empfehlungen bietet die [nestor AG Media.](https://wiki.dnb.de/display/NESTOR/Digitalisierungsempfehlungen)


### Exkurs: Video- und Bildannotation

Video- und Bildannotationstools sind lokale oder webbasierte Anwendungen für die Annotationen, d. h. Markierung und Kommentierung (audio-)visueller Inhalte. <br>
In vielen kulturwissenschaftlich forschenden Fachdisziplinen ist ihre Nutzung als Methode verbreitet.<br>
Daneben beruhen Techniken wie Computer Vision und maschinelles Lernen stark auf annotierten Bild- und AV-Materialien.

---

Nutzungsszenarien von Videoannotationstools:

- Identifikation von Objekten, Personen oder Ereignissen
- Zeitbezogene Analyse von Bild und Ton
- Qualitative oder quantitative Datenanalyse
- Visualisierung von Annotationen
- Vorannotation von Tanz und Performances (s. Projekt [#vortanz](https://vortanz.ai/))

---

<!--- Einige dieser Tools lassen manuelle oder (semi-)automatische Annotation von Bild und Ton zu. --->

Annotationstools für AV-Material (Auswahl):

- ELAN (Eudico Linguistik Annotator)
- EXMARaLDA: annotation and transcription for oral corpora
- VIAN (Visual Video Annotation and Analysis)
- Advene (Annotate Digital Video, Exchange on the Net)

---

Annotationstools Bild (Auswahl):

- heiANNO – Heidelberger Annotationsmodul
- mirador
- CVAT (Computer Vision Annotation Tool)
- labelme

## 4. Der Datenlebenszyklus 

<img src="../resources/FD_LZ.png" width=50% height=auto> <br>
<sub> Graphische Darstellung eines DLZ, Creator: CRDA, [CC0](https://creativecommons.org/publicdomain/zero/1.0/) </sub>

Der Datenlebenszyklus (DLZ) beschreibt den "Lebenskreislauf" von Forschungsdaten. Er kann dabei, ausgehend von seinem Detailgrad und der Art der Daten, leicht von dem hier angegebenen abweichen.

Die grundlegenden Stationen sind:

  1. **Forschungsvorhaben planen**
  2. **Daten erheben**
  3. **Daten aufbereiten und analysieren**
  4. **Daten teilen und publizieren**
  5. **Daten archivieren**
  6. **Daten nachnutzen**

Im Quiz auf der nächsten Seite erfahren Sie mehr dazu, was die einzelnen Stationen beinhalten!

### Quiz: Was können die Stationen des Forschungsdaten-Lebenszyklus beinhalten?
Bei allen Fragen können mehrere Antworten korrekt sein.
<br><br>

**Forschungsvorhaben planen**

[[x]] Erstellen eines Datenmanagementplans (DMP)
[[x]] Lokalisieren vorhandener Daten
[[ ]] Videos annotieren
[[ ]] Objekte digitalisieren
[[ ]] Interviews verschriftlichen

**Daten erheben**

[[x]] Bild- oder Audiodaten annotieren
[[ ]] Liste mit ToDo's erstellen
[[x]] Interviews durchführen
[[x]] Noten transkribieren
[[ ]] regelmäßig ins Kino gehen

**Daten aufbereiten**

[[x]] Digitale Objekte/Digitalisate mit Metadaten anreichern
[[ ]] Objekte digitalisieren
[[ ]] Dateiordner aufräumen und mit AV-, Bild- und Textdateien füllen
[[x]] Daten bereinigen
[[x]] Daten interpretieren

**Daten teilen und publizieren**

[[x]] Urheberrechte für die eigenen Ergebnisse festlegen
[[ ]] Excel-Liste mit Publikationstitel erstellen
[[ ]] eigene Publikationen lokal abspeichern
[[x]] Zugänge/Zugriffsmöglichkeiten auf Forschungsdaten kontrollieren
[[x]] bisherige Forschung auf geeigneten Repositorien veröffentlichen

**Daten archivieren**

[[ ]] Datenmanagementplan erstellen
[[ ]] AV-, Bild- und Textdateien auf einem USB-Stick abspeichern
[[x]] Daten in geeignete Formate migrieren
[[ ]] Liste mit Forschungsdaten erstellen und an geeignete Archive versenden
[[x]] Daten auf geeignete Medien migrieren

**Daten nachnutzen**

[[ ]] Forschungsergebnisse über Social Media-Kanäle teilen
[[x]] bisherige Forschung rezensieren
[[x]] Daten für Lehre und Lernen verwenden
[[ ]] Forschungsdaten in öffentlichen Cloud-Systemen abspeichern
[[x]] für weitere Forschung auf bisherigen Ergebissen anknüpfen

## 5. Versionsverwaltung
Nicht nur für das kollaborative Arbeiten, sondern ganz grundsätzlich für die Organisation bei der Arbeit mit Forschungsdaten, ist eine Versionsverwaltung der Daten von essentieller Wichtigkeit. 
Einfach gesagt bedeutet das, die Schritte der Arbeit und Ergebnisse zu dokumentieren, um bspw. im Zweifelsfall an früheren Punkten erneut ansetzen zu können.

...

<!--- [MAH] So weit nur ein erster Vorschlag, hier könnte Daniel noch einiges ergänzen und zu seinen Folien überleiten. --->

## 6. Metadaten

Metadaten sind Daten, die andere Daten beschreiben. Sie sind in vielerlei Hinsicht relevant, etwa um die Auffindbarkeit von Daten zu erhöhen oder Daten zu beschreiben, die ihrerseits nur unter eingeschränkten Zugang oder gar nicht verfügbar sind.<br>
Dabei ist die Nutzung von [Normdaten und kontrollierten Vokabularen](#normdaten) wichtig, um qualitätvolle Metadaten zu erhalten.

<br>

> Merksatz: "Metadaten sind Daten, die andere Daten beschreiben."

<br>

Metadaten können in verschiedene Kategorien unterteilt werden.
Eine übliche Aufteilung ist:

- **Deskriptive Metadaten**:<br>Sie enthalten beschreibende Informationen über den Inhalt des Objekts, sie dienen der Identifizierung von Objekten oder Daten
- **Administrative Metadaten**:<br>Sie klären verwaltungsrelevante und rechtliche Rahmenbedingungen, dafür enthalten sie Informationen zum Objekt, die über seinen Inhalt hinausgehen wie z. B. Rechteinformationen und Details des analogen Objekts
- **Strukturelle Metadaten**:<br>Sie erläutern die Datenstruktur, die Organisation, Hierarchie und Beziehung zu anderen Ressourcen.
- **Technische Metadaten**:<br>Sie beschreiben die technischen Eigenschaften einer digitalen Datei, sie werden oft automatisch durch die Erfassungssoftware erstellt, können, und sollten in einigen Fällen, erweitert werden.

Ergänzt werden kann diese Liste durch

- **Archivmetadaten**:<br>Sie beinhalten spezieller zusammengestellte Informationen, die für die Archivierung relevant sind

<img src= "../resources/Metadaten.png" width=50% height=70%> <br>
<sub>Andrea Polywka, Alexander Stark: Metadaten Schaubild, [CC0](https://creativecommons.org/publicdomain/zero/1.0/)</sub>

### Metadaten und Metadaten-Standards

Alle Arten von Forschungsdaten sollten stets mit Metadaten versehen werden. Metadaten halten Daten verständlich und machen sie leichter auffindbar, da sie maschinell ausgelesen und verarbeitet werden können und so z. B. Datensätze untereinander in Beziehung gesetzt werden können.

Metadaten sollten gesondert als Metadatenpublikation veröffentlicht werden, um auch unabhängig von ihren zugehörigen Daten abrufbar zu sein.<br>
Das ist vor allem in solchen Fällen sinnvoll, wo Daten aus rechtlichen oder ethischen Gründen (s. [CARE-Prinzipien](#die-care-prinzipien)) nicht frei zugänglich publiziert werden können.

---

Auch für Metadaten gibt es Standards, die ihre Vergleichbarkeit sicherstellen und vor allem ihre Nutzbarkeit für Suchmaschinen erhöhen.

Dies sind einige fachübergreifende Standards:

- Dublin Core
- EXIF (Bildmetadaten)
- PREMIS
- METS MODS

Für alle Metadaten gilt zudem, dass sie strukturiert erfasst sein sollten und den Standards des jeweiligen Fachs entsprechend.<br><br>
Detailiertere Informationen zu Metadatenstandanrds liefert u. a. [Kailus 2023](https://docs.nfdi4culture.de/ta2-fair-handreichung/empfehlungen-zu-metadatenstandards#12-empfehlungen-zu-metadatenstandards). <br><br>
Eine Auswahl fachspezifischer Standards findet sich auf den folgenden Unterseiten.

---

Warum gibt es mehr fachspezifische denn medienspezifische Standards? 

- Einzelne Fächer stellen unterschiedliche Fragen an dieselben Medien und arbeiten anders mit ihnen; das hat teilweise den Effekt, dass sie unterschiedliche Metadaten erfassen und sich dadurch historisch verschiedene Standards entwickelt haben!

#### <font color=#a2d0eb> 🎬 Metadatenstandards der Film- und Medienwissenschaft </font>
In Deutschland gibt es (noch) keinen allgemein genutzten/akzeptierten Metadaten-Standard für audiovisuelle Metadaten. <br>
Damit Metadaten FAIR sind und bleiben, sollten sie sich an bestehenden Schemata orientieren.

Eine Auswahl von in der Archivierung gebräuchlichen Normen und Standards für die Erschliessung:

- ISAD (G)
- PREMIS
- METS
- Dublin Core (DC)
- PBCore
- EBUCore
- MPEG-7 Multimedia Content Description Interface

#### <font color=#d1bcf5> 🎨 Metadatenstandards der Kunstgeschichte </font>
Eine Auswahl an Standards, die in der kunsthistorischen Forschung Anwendung finden:

- Categories for the Description of Works of Art (CDWA)
- Lightweight Information Describing Objects (LIDO) für deskriptive und administrative Metadaten von 2D- und 3D-Objekten
- Das Schema der Text Encoding Initiative (TEI)
- Extensible Metadata Plattform (XMP) für technische Metadaten von 2D- und 3D-Objekten

---

Zu LIDO s. a.:<br>

- **Fichtel 2024**: LIDO-Schulung [>](https://nfdi4culture.de/go/E5247)
- **Knaus / Stein / Kailus 2019**: LIDO-Handbuch für die Erfassung und Publikation von Metadaten zu kulturellen Objekten: Band 1: Graphik [>](https://doi.org/10.11588/arthistoricum.382.544)
- **Knaus / Kailus / Stein 2022**: LIDO-Handbuch für die Erfassung und Publikation von Metadaten zu kulturellen Objekten: Band 2: Malerei und Skulptur [>](https://doi.org/10.11588/arthistoricum.1026)
- **Rössel / Stenger / Kailus / Stein 2025**: LIDO-Handbuch für die Erfassung und Publikation von Metadaten zu kulturellen Objekten: Band 3: Architektur und andere ortsfeste Werke [>](https://doi.org/10.11588/arthistoricum.1407)

#### <font color=#99e089> 🎵 Metadatenstandards der Musikwissenschaften </font>

Musik-Metadaten enthalten Informationen über Audio-, Video, Notendateien etc.

Eine Auswahl an Standards, die in der musikwissenschaftlichen Forschung Anwendung finden:

- DDEX ERN-Standard zur Ablieferung von Netzpublikationen, also auch Musikdateien mit Metadaten an die Deutschen Nationalbibliothek, der auch für den Datenaustausch in der Musikindustrie verwendet wird [(vgl. hierzu)](https://www.dnb.de/DE/Professionell/Sammeln/Unkoerperliche_Medienwerke/ddexERN.html).  
- MEI [(Music Encoding Initiatve)](https://music-encoding.org/) ist primär eine XML-Musik-Codierung, die aber in Anlehnung an die TEI (Text Encoding Initiative) für die Edition/Publikation von Musiknotationen in ihrem Header äußerst umfangreiche Möglichkeiten bietet,  detailiert Metadaten mitzuliefern, bspw. über Autoren/Komponisten, philologische Werkkontexte wie Quellenbeschreibungen, beteilgte Personen und Orte, Formate etc. [(vgl. hierzu)](https://music-encoding.org/guidelines/v4/content/metadata.html). Dabei orientiert sich MEI stark an bestehenden Metadatenstandards wie [MARC](https://www.dnb.de/DE/Professionell/Metadatendienste/Exportformate/MARC21/marc21_node.html) (Machine-Readable Cataloging) oder [FRBR](https://www.ifla.org/wp-content/uploads/2019/05/assets/cataloguing/frbr/frbr-deutsch.pdf) (Functional Requirements for Bibliographic Records).

- METS/MODS ist ein Metadatenformat für den Austausch von Daten zu digitalisierten Drucken. Es verwendet Elemente der Metadatenstandards Metadata Encoding and Transmission Format [(METS)](https://www.loc.gov/standards/mets/) und Metadata Object Description Schema [(MODS)](https://www.loc.gov/standards/mods/), die vom [Network Development and MARC Standards Office der Library of Congress](https://www.loc.gov/marc/ndmso.html) entwickelt werden. Während METS die administrativen und strukturellen Eigenschaften von Digitalisaten beschreibt, wird MODS für die bibliografische Beschreibung der Drucke verwendet [(vgl. hierzu)](https://pro.deutsche-digitale-bibliothek.de/glossar/metsmods-format). 


### QUIZ: Metadaten

**Füllen Sie die Lücken im folgenden Text aus.**

Zu Beginn dieses Kapitels wurden verschiedene Kategorien von Metadaten vorgestellt.<br>[[Administrative | (Deskriptive) | Strukturelle | Technische]] Metadaten beschreiben das Objekt inhaltlich, nennen z. B. Titel und Autor:in, wohingegen [[(administrative) | deskriptive | strukturelle | technische]] Metadaten verwaltungsrelevante und rechtliche Rahmenbedingungen enthalten. Typische Inhalte von [[administrativen | deskriptiven | (strukturellen) | technischen]] Metadaten sind Relationen zwischen Daten. Informationen, wie Dateigröße, -format oder verwendete Software und Hardware finden sich hingegen in den [[administrativen | deskriptiven | strukturellen | (technischen)]] Metadaten.

## 7. Normdaten

**Was sind Normdaten?**

Normdaten sind strukturierte Datensätze, die wissenschaftlich geprüft und frei verfügbar sind.<br>
Jedem Normdatum ist ein eindeutiger Identifikator zugeordnet, mit einer eindeutig referenzierbaren URI, einem Union Resource Identifier.

Ein Normdatum ist mit vielen weiteren Normdaten verknüpft und setzt dadurch die Informationen mit einander in Verbindung.<br>
Damit das klappt, braucht es neben den Identifikatoren auch weitere Regeln und Standards für Normdaten. MARC 21 ist ein solcher weit verbreiteter, internationaler Standard. Er kann als XML konvertiert werden und ist als RDF (Resource Description Framework) ausspielbar.<br>
RDF seinerseits ist wieder Grundlage des Semantic Web.

Ein **kontrolliertes Vokabular** ist eine Sammlung von Normdaten, es verknüpft auch Synonyme, die zum selben Suchergebnis führen und liefert dazu oft Übersetzungen in andere Sprachen.

---

**Wir benötigen Normdaten ...**

- für die Vereinfachung der Darstellung komplexer Zusammenhänge,
- zur Vermeidung von Mehrdeutigkeiten und falschen Zuordnungen vor allem für Maschinen, die anders als Menschen nicht aus dem Kontext schließen können, wie bspw. bei ...

  - variierenden Schreibweisen von Namen oder
  - gleichen Städtenamen (z. B.: Paris in Frankreich und Paris in Texas).

**Die Verwendung von Normdaten ermöglicht also besseren Austausch und bessere Nachnutzbarkeit von Daten!**

> Video-Tipp: NFDI4Culture Video-Tutorial zu Normdaten! https://av.tib.eu/media/60986
<div style="position: relative; width: 100%; aspect-ratio: 16 / 9;">
  <iframe src="https://av.tib.eu/player/60986" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
</div>

### Kontrollierte Vokabulare in Geistes- und Kulturwissenschaften

Eine Auswahl kontrollierter Vokuabulare für die Geistes- und Kulturwissenschaften:

- Deutsche Nationalbibliothek – Gemeinsame Normdatei (GND)
- Virtual International Authority File (VIAF)
- Open Researcher and Contributor ID (ORCID)
- Research Organization Registry (ROR)
- Crossref Funder Registry
- International Standard Name Identifier (ISNI)
- Getty Vokabulare
  
  * Thesaurus of Geographic Names (TGN)
  * Art & Architecture Thesaurus (AAT)
  * Union List of Artists Names (ULAN)

- Iconclass
- Wikidata

## 8. FAIR und CARE
Die Akronyme FAIR und CARE stehen für zwei wichtige Richtlinien im Kontext guten Forschungsdatenmanagements, sie werden in den folgenden Abschnitten genauer betrachtet.

---

**FAIR und CARE – zwei sehr unterschiede Kontexte**

Wenngleich die beiden Akronyme gerne in einem Atemzug genannt werden, ist es wichtig, ihre sehr unterschiedlichen Anwendungsbereiche und Entstehungskontexte zu berücksichtigen!

Die FAIR-Prinzpien fokussieren sich überwiegend auf technische Aspekte und Datenqualität. Sie sind auf nahezu jeden Datensatz anwendbar.

Die CARE-Prinzipien stehen hingegen für einen angemessenen Umgang mit Daten, die indigene Gemeinschaften betreffen. 

Im Gegensatz zu FAIR liegt der Fokus also bei CARE explizit nicht auf der Erleichterung des Datenaustauschs, sondern auf der Wahrung der Interessen indigener Gemeinschaften, was in einigen Fällen auch die FAIR-heit der Daten reduzieren kann.

Lesen Sie in den nächsten Kapiteln nach, wofür die Akronyme FAIR und CARE im Einzelnen stehen!

### Die FAIR-Prinzipien

FAIR steht für **f**indable, **a**ccesssible, **i**nteroparable und **r**eusable; übersetzt also für: auffindbar, zugänglich, interoperabel und nachnutzbar.

Zu jedem Hauptziele liefern die FAIR-Prinzipien je ein Set an Bedingungen. Wenn Sie mehr dazu wissen wollen, empfehlen wir die NFDI4Culture-Handreichung zu diesem Thema: [Kailus 2023](https://docs.nfdi4culture.de/ta2-fair-handreichung/) bzw. diese [Kapitel](https://docs.nfdi4culture.de/ta2-fair-handreichung/vier-grundlegende-praemissen-zum-verstaendnis-der-fair-prinzipien) daraus.

Die Prinzipien wurden entwickelt, um Datenproduzent:innen und -herausgeber:innen im Umgang mit Forschungsdaten zu unterstützen und die Daten für die Nachnutzung zu optimieren. Sie betreffen nicht nur die Daten an sich, sondern auch die benuzten Algorithmen, Tools und Workflows, die im Zusammenhang mit den Daten stehen.<br>

Es gibt zahlreiche Leitfäden für FAIRes Forschungsdatenmanagement und neuerdings auch mehr und mehr Tools, die Wissenschaftler:innen dabei unterstützen, den FAIR-Gehalt ihrer Daten zu ermitteln, u. a.:

- [NFDI4Culture FAIR-Check](https://nfdi4culture.de/id/E5080)
- [FAIR Assessment Tool von TKDM](https://tkfdm.github.io/FAIR-Data-Assessment-Tool/)
- [FAIR Data Self-Assessment Tool](https://ardc.edu.au/resource/fair-data-self-assessment-tool/)
- [FAIR Data Maturity Model](https://doi.org/10.5281/zenodo.5834115)
- [F-UJI – Automated FAIR Data Assessment Tool](https://www.f-uji.net/)

### QUIZ zu den FAIR-Prinzipien

<!---
**Beginnen wir einfach: Wofür stehen die Buchstaben in FAIR?**

F steht für [[findable]], A für [[accessible]], I für [[interoperable]] und R für [[reusable]].
--->

---

**Die Bedingungen der FAIR-Prinzipien**

Jeder Buchstabe von FAIR hat ein Set an Bedingungen, die umgesetzt werden sollen.<br>
Können Sie die folgenden Sets an Bedingungen den richtigen Buchstaben zuordnen?
<br><br>

- (Meta-)Daten nutzen eine formale, zugängliche, gemeinsam genutzte und breit anwendbare Sprache für die Wissensrepräsentation
- (Meta-)Daten enthalten Vokabulare, welche den FAIR-Prinzipien folgen
- (Meta-)Daten enthalten qualifizierte Verweise auf andere (Meta-)Daten
[[Findable | Accessible | (Interoperable) | Reusable]]

---

- (Meta-)Daten wird ein global eindeutiger und persistenter Identifikator zugewiesen
- Daten werden mit umfangreichen Metadaten beschrieben
- Metadaten enthalten eindeutig und explizit den Identifikator der Daten, die sie beschreiben
- (Meta-)Daten werden in einer durchsuchbaren Ressource registriert oder indiziert
[[(Findable) | Accessible | Interoperable | Reusable]]

---

- (Meta-)Daten sind detailliert beschrieben und enthalten präzise, relevante Attribute
- (Meta-)Daten enthalten eine eindeutige, zugreifbare Angabe einer Nutzungslizenz
- (Meta-)Daten enthalten detaillierte Provenienz-Informationen
- (Meta-)Daten entsprechen den fachgebietsrelevanten Community-Standards
[[Findable | Accessible | Interoperable | (Reusable)]]

---

- (Meta-)Daten sind über ihren Identifikator mithilfe eines standardisierten Kommunikationsprotokolls abrufbar
- Das Protokoll ist offen, kostenlos und universell implementierbar
- Das Protokoll unterstützt bei Bedarf Verfahren zur Authentifizierung und Rechteverwaltung
- Metadaten bleiben verfügbar, auch wenn die zugehörigen Daten nicht (mehr) verfügbar sind
[[Findable | (Accessible) | Interoperable | Reusable]]

<!---
Können Sie diese Bedigungen ihren richtigen Buchstaben zuordnen? Bitte erst dann auf "Prüfen" klicken, wenn alle Kästchen den Feldern auf der linken Seite zugeordnet wurden.
<br><br>
<font color=red> Das muss noch besser erklärt und zudem geprüft werden; das ist ziemlich schwer ... ohne die einzelnen Prinzipien im Detail angeschaut zu haben, ist das nicht lösbar; der Platz im linken Feld muss ggf. größer sein, damit alle Antowrten reinpassen; oder weniger Antworten? Das Ergebnis/die Punktevergabe muss noch angepasst werden, keine Abzüge bei falschen Antworten!  </font><br><br>

<iframe src="./resources/FAIR-Drag-and-Drop.html" width=100% height=100%></iframe>
--->

### Die CARE-Prinzipien

Die [CARE-Prinzipien](https://doi.org/10.5334/dsj-2020-042) wurden 2019 von der Global Indigenous Data Alliance als Ergänzung zu den FAIR-Prinzipien erarbeitet, um die Beteiligung indigener Gruppen an Entscheidungsprozessen zu stärken. Es geht darum, koloniale Kontexte und daraus resultierende ungleiche Machtverhältnisse zu identifizieren und zu berücksichtigen.

Die Prinzipien sind vorrangig für jene Forschende relevant und sollten von ihnen in jedem Fall beachtet werden, die ethnologisch forschen oder sich mit Daten aus kolonialen Kontexten beschäftigen.

CARE steht für Collective Benefit, Authority of Control, Responsibility und Ethics. Frei übersetzt also: Kollektiver Nutzen, Datenkontrolle, Verantwortung und Ethik.

- **Collective Benefit**<br>Die Daten und Forschung mit und an ebendiesen, soll auch Nutzen für die Ursprungscommunities haben. Die Umsetzung dessen kann sehr verschieden aussehen und z. B. aus Investitionen in Infrastrukturen der Community bestehen.
- **Authority of Control**<br>Rechte und Interessen indigener Communities sollen gewahrt sein sowie Befugnisse in der Kontrolle der Daten gewährt werden. Die indigenen Communities sind als aktive Partner im Forschungsprozess zu verstehen.
- **Responsibility**<br>Forschende haben die Verantwortung, die Daten zu verwalten und mit ihnen umzugehen, so, wie es mit den Ursprungscommunities festgelegt wurde. Dazu gehört auch die Berücksichtigung dessen, was die Forschungsergebnisse für die Communities bedeuten und die Verpflichtung ihnen die Daten in verständlicher und nützlicher Form zur Verfügung zu stellen.
- **Ethics**<br>Die Rechte der Communities sollten über den gesamten Forschungsprozess hinweg gewahrt und ihre Würde respektiert sowie ihre Weltanschauung berücksichtigt werden.

> Lesetipp: [NFDI4Culture-Kommunikationsleitlinie zu den CARE-Prinzipien für indigene Datensouveränität](https://nfdi4culture.de/id/E6467)

---

Kooperationen mit Ursprungscommunities können den CARE-Prinzipien folgend u. a. wie folgt aussehen: 

- gemeinsame Bearbeitung von Objekten
- gleichberechtigten Zugang zu den Daten ermöglichen
- indigene Ethik einbeziehen
- das eigene Handeln und die Darstellung von Objekten/Forschungsgegenständen regelmäßig hinterfragen
- öffentlichen Zugang zu Daten einschränken, wenn nötig
- kulturelle Metadaten, z. B. Bezeichnungen aus Herkunftskontexten, Provenienzangaben in den Metadaten, Auswahl der Metadaten transparent machen
- Nutzung von Disclaimern, die Herkunft und Bedeutung, sowie Zugriffseinschränkungen auf die Daten beschreiben
- Nutzung von Hinweisen darauf, dass indigene Daten verwaltet werden
- Nutzung der [Traditional Knowledge Labels](https://localcontexts.org/labels/traditional-knowledge-labels/)

  - mit ihnen können u. a. geschlechtsspezifische Restriktionen angezeigt werden, Daten als weibliches Wissen oder als aus sakralen Kontext stammend gekennzeichnet werden 

### Kultur- und Geisteswissenschaftliche Anwendungsfälle der CARE-Prinzipien
In ethnologisch forschenden Bereichen, etwa der Musikethnologie, sind die CARE-Prinzipien eine wichtige Leitlinie beim Umgang mit Forschungsdaten.<br>
Aber auch in Projekten, in denen mit personenbezogenen Daten gearbeitet wird, etwa im Kontext von Interviews oder Studien, können sie eine wichtige Leitlinie sein, wenngleich nicht vergessen werden sollte, dass es ihre intendierte Verwendung ist, eine Leitlinie für die Arbeit und Forschung in und mit indigenen Communities zu sein.

Folgend seien einige Anwendungsfälle aufgezeigt, die den Nutzen der CARE Prinzipien illustrieren:

<!--- Hier noch ergänzen: Bisher nur das Material von Andrea und Alex aus dem FFK-Kurs / Material von Barbara Alge?--->

- Forschungsdaten zu Filmmaterial aus kolonialen Kontexten

  - bspw. Amateurfilme, wissenschaftliche Filme, Travelogues, „Kulturfilme“
  
- Forschungsdaten zu Tonmaterial aus kolonialen Kontexten
  
  - bspw. Phonographenwalzen aus Wachs aus ethnologischen Forschungskontexten, u. a. auch aus Kriegsgefangenenlagern des Ersten Weltkriegs

- Forschungsdaten zu geraubten Kulturgütern aus kolonialen Kontexten

  - bspw. 3D-Digitalisate von geraubten Objekten

## 9. Sichern, Speichern, Publizieren und Archivieren

Die vorherigen Kapitel haben schon einiges vorweggennommen, was beim Speichern von Daten sinnvoll und wichtig ist, wie die Anreicherung mit Metadaten (s. Kap. [6. Metadaten](#6. metadaten)).
Folgend einige konkrete Tipps für die Datenspeicherung:

- Vermeiden proprietärer Datenformate (s. Kap. [Datenformate](#datenformate))
- 3-2-1-Regel: 3 Kopien, auf 2 Medien, mindestens 1 davon dezentral gespeichert
- Passwortverschlüsselung der Daten
- Sinnvolles und konsistentes Dateiablagesystem

  - In einer READ.me-Datei kann das System auf oberster Ebene erläutert werden; das ist gerade bei der Arbeit in geteilten Dateiablagesystemen und/oder bei größeren Arbeitsgruppen empfehlenswert

### Daten publizieren

Daten sollten publiziert werden, denn sie sind Forschungsergebnisse. Sie sind die Grundlage der Forschung und die Basis für das abschließende Forschungsprodukt, sei es ein Buch, ein Paper oder ähnliches.<br>
Publizierte Forschungsdaten können zudem nachgenutzt werden und befördern dadurch nicht nur die Wissenschaft, sie machen sie auch nachhaltiger und vernetzter.

Wie Datenpublikationen aussehen können, zeigen Beispiele aus der Film- und Medienwissenschaft, die im Repositorium [media/rep/](https://mediarep.org/communities/7e880a5a-5bcd-49b7-9b0e-ce4851b8d7bf) veröffentlicht sind.

---

**Vorteile bei der Veröffentlichung von Forschungsdaten:**

- Forschungsergebnisse werden durch die Veröffentlichung von Daten und deren Zitierung sichtbarer.
- Einmalige, nicht reproduzierbare Daten gehen nicht verloren, sondern stehen für weitere Forschungen zur Verfügung.
- Öffentlich zugängliche Daten können zu neuen oder ergänzenden Hypothesen anregen.
- Es können neue Kooperationen weltweit entstehen.
- Wissenschaftliche Integrität wird gestärkt.
- Durch das Teilen von Daten wird eine offene Wissenschaftskultur befördert.
- Kosten werden gespart, indem publizierte Daten nachgenutzt werden können.

### Daten zitieren

Oft stellt sich im Forschungsalltag die Frage nach dem Zitieren von Daten.

**Wie bei Texten sollte man auch Daten zitieren und nachweisen!**

- Richtiges Zitieren ist Teil guten wissenschaftlichen Arbeitens.

  * Daten sollten gut und richtig zitiert werden, denn auch sie sind Forschungsergebnisse.

**Wie zitiere ich Daten richtig?**

- Grundsätzlich werden sie so ähnlich zitiert, wie andere Arten an Publikationen auch.
- Genannt werden sollten also Autor:innen bzw. Herausgeber:innen, der Titel und das Veröffentlichungsdatum.
- Ergänzt wird dies bestenfalls um den Publikationagenten und einen Persistent Identificator (s. Kap. [PID](#persistent-identifier-pid)), etwa mittels DOI, womit man direkt zum Datensatz weitergeleitet wird!
- Ein Beispiel von [forschungsdaten.info](https://forschungsdaten.info/):

  * Autoren (Veröffentlichungsdatum): Titel, Publikationsagent, PID
  
### Persistent Identifier (PID)

Persistent Identifiers (PIDs) sind Codes, die eine digitale Ressource eindeutig benennen. Sie dienen der langfristigen, nachhaltigen Adressierung von Daten und erhöhen dadurch ihre Auffindbarkeit stark. Der PID verweist auf die Ressource, sie selbst kann dabei physisch an verschiedenen Orten liegen.<br>
PIDs werden von zentralen Institutionen oder Organisationen verwaltet, die eine dauerhafte Referenzierung der Objekte im Internet versichern.

Beispiele für gängige PIDs im Wissenschaftskontext sind:

- Digital Object Identifier (DOI) 
  
  * für digitale Objekte (Artikel, Datensätze, …)
  * vergleichbar mit einer ISBN im Analogen
  * Verweist permanent auf eine Ressource und verbessert dadurch Zitationen.
  
    - Anbieter von DOIs versichern die Permanenz der digitalen Adresse
  
- Open Researcher and Contributer ID (ORCID) 
  
  * Personen ID
  * Erleichtert die Identifikation von Personen
  * präsentiert die wiss. Laufbahn, listet Publikationen und kann eigenhändig angelegt werden

### Repositorien – die Daten-Speicher

Repositorien sind Speicherorte für digitale Forschungsergebnisse und -daten. Sie machen Daten für die Öffentlichkeit oder einem ausgewählten Kreis an Nutzer:innen verfügbar.

Neben FAIR- und CARE-Prinzipien, die sich um die Daten selbst drehen, liefern die sogenannten TRUST-Prinzipien (Transparency, Responsibility, User Focus, Sustainabilty, Technology) in Bezug auf Repositorien Anhaltspunkte für gute Datensicherung und [Archivierung](#langzeitarchivierung).

**Was sind Hinweise auf gute Repositorien?**

- Es werden dauerhafte Identifikatoren zur besseren Zitation und Auffindbarkeit der Daten vergeben.
- Es gibt Siegel und Zertifikate für gute Langzeitarchive: CoreTrustSeal (CTS); nestor Siegel/DIN 31644; ISO 16363.

**Wo finde ich ein geeignetes Repositorium?**

Es gibt verschiedene Portale, die Repositorien listen und diese Auflistungen durchsuchbar machen, in vielen Fällen zeigen diese Portale direkt die wichtigsten Eckdaten der Repositorien an, sowie eventuelle Siegel und Zertifikate, die sie halten.<br>
Es wird zumeist zwischen generischen, fachspezifischen und institutionellen Repositorien unterschieden.<br>
Einige dieser Portale sind: 

- Re3data [>](https://www.re3data.org/)
- DFG RIsources [>](https://risources.dfg.de/index.html#q=*&sort=RI_SORT_DE%20asc&rows=10&RI_EXT=Y)
- NFDI4Cultures kuratierte Repositorieliste [>](https://nfdi4culture.de/services/details/curated-repository-list.html)

---

**Kulturwissenschaftliche Repositorien – eine Auswahl**

- DARIAH-DE – Digital Research Infrastructure for the Arts and Humanities
- CLARIN-D – Digitale Forschungsinfrastruktur für Sprachressourcen in den Geisteswissenschaften
- IANUS – Forschungsdatenzentrum Archäologie und Altertumswissenschaften
- TextGrid Repository – Langzeitarchiv für geisteswissenschaftliche Forschungsdaten
- RADAR4Culture
- SLUBArchiv.digital
- TIB AV-Portal
- TIB Preservation-as-a-Service

Die folgenden Unterseiten listen eine Auswahl weiterer fachspezifischer Repositorien auf.


#### <font color=#a2d0eb> 🎬 Repositorien für die Film- und Medienwissenschaft </font>

- media/rep/ <br>

  - Data Sets und Data Papers können beispielsweise über das Fachrepositorium media/rep/ publiziert werden, Data Papers darüber hinaus auch im NECSUS Journal
  
- arthistoricum.net @ heiDATA
- heidICON – Heidelberger Objekt- und Multimediadatenbank
- prometheus – A distributed digital image archive for research and teaching

#### <font color=#d1bcf5> 🎨 Repositorien für die Kunstgeschichte </font>

- ART-Dok
- arthistoricum.net @ heiDATA
- arthistoricum.net – ART-Books
- Bildindex der Kunst und Architektur
- Deutsche Fotothek
- heiARCHIVE
- heidICON – Heidelberger Objekt- und Multimediadatenbank
- Kompakkt
- prometheus – A distributed digital image archive for research and teaching

#### <font color=#99e089> 🎵 Repositorien für die Musikwissenschaft </font>

- musiconn.publish

- musiconn (SLUB Dresden), diverse Services, u. a. 

  - musiconn.publish, Veröffentlichung und Langzeitarchivierung musikalischer Fachliteratur
  - musiconn.performance, Publikation von Forschungsdaten und -ergebnissen (tematisch eingeschränkt auf den Bereich musikalischer AufführungenI

- RISM (Répertoire International des Sources Musicales), Dokumentation schriftlicher musikalischer Quellen

- RADAR4Culture

<!---
#### <font color=#edba82> 🎭 Repositorien für die Theaterwissenschaften </font>

- Deutsche Fotothek
- Kompakkt
- arkumu.nrw
--->

### Speichern vs. Archivieren

Speichern und Archivieren, das kann im ersten Moment sehr ähnlich klingen, also wo liegt der Unterschied?

**Speichern / Sichern** meint die Sicherung aller Daten (Backup) um Datenverlust vorzubeugen

**Archivieren** hingegen ist die Sicherung und **Langzeitarchivierung** ausgewählter, "endgültiger" Daten. Archivieren geschieht also zumeist erst nach dem Abschluss eines Forschungsprojektes, oder dem Abschluss eines eigenständigen Moduls in einem Projekt.

| Speichern | Archivieren |
| :---: | :---: |
| Kopie auf ein anderes Medium | Daten die nachdem sie ins Archiv übergegangen sind unverändert bleiben |
| Vorbeugen von Datenverlust, Sichern des aktuellen Arbeitsstandes | Langzeitsicherung für Nachnutzungsszenarien oder aus rechtlichen Gründen |
| Lokale Speicherorte, USB-Sticks, Discs, Cloud-Dienste | langlebige Medien z. B. Magnetband |

### Langzeitarchivierung

Langzeitarchivierung meint in der Regel eine Aufbewahrungsgarantie von mindestens 10 Jahren, so fordert es u. a. auch die DFG bei ihrer Förderung von Forschungsprojekten. ([DFG 2025, S. 22](https://doi.org/10.5281/zenodo.14281892))

--- 

Anders als Backups, die den Zustand der Daten zu einem bestimmten Zeitpunkt sichern, ist die Langzeitarchivierung (LZA) auf einen dauerhaften Erhalt der Daten ausgelegt und nicht für den alltäglichen Zugriff. Deshalb sind archivierte Daten nicht zwangsläufig direkt abrufbar, wenn sie etwa auf Magnetbändern oder anderen in der LZA genutzten Medien gesichert werden.

Auch mit Datenpublikation sollte die Archivierung nicht verwechselt werden. Bei der Publikation steht im Vordergrund, dass die Daten schnell abrufbar und nutzbar sind, was mit dem Anspruch der Langzeitspeicherung und zuverlässigen Verfügbarmachung nicht immer im Einklang steht. Es gibt aber viele Datenrepositorien, die eine Archivierung direkt mitbedenken und die Daten in archivierbaren Formaten sichern.

---

Damit die Daten später noch verständlich sind und damit ihre Auffindbarkeit ehöht wird, ist auch bei archivierten Daten eine gute Beschreibung mit Metadaten unerlässlich. (s. Kap. [Metadaten](#metadaten))

Es werden nicht alle Daten aus einem Projekt archiviert. Es muss immer entschieden werden, welche Daten erhaltenswert sind. Bestenfalls sind die Richtlinien dafür in einem Projekt bereits im Datenamanagementplan festgehalten.

<!--- Es gibt verschiedene Ansätze, erhaltenswerte Eigenschaften zu bestimmen. Den provenienzbasierten Ansatz und den nutzergruppenbasierten Ansatz, welche sich auch kombinieren lassen, man spricht dann auch vom Preservation Intent.<br>
Der provenienzbasierten Ansatz blickt auf die vermutete oder die überlieferte Absicht, die bei der Erstellung des Objektes verfolgt wurde. Der nutzergruppenbasierten Ansatz hingegen schaut, welche Anforderungen die Community zukünftig an das Objekt stellen könnte.<br> --->
Wie bei der Publikation von Daten sind auch bei der Archivierung rechtliche und ethische Aspekte zu beachten. Eine ausführliche Besprechung dieser Themen würde jedoch den Rahmen dieses Kurses sprengen.

Die TRUST-Prinzipien (Transparency, Responsibility, User Focus, Sustainabilty, Technology), die bei den [Repositorien](#repositorien--die-daten-speicher) schon erwähnt wurden, gelten auch für Langzeitarchive.<br>
Digitale Langzeitarchive unterscheiden sich in Umfang ihrer angebotenen Services und der Qualität. Zertifikate können Nutzenden die Auswahl eines für sie geeigneten Archivs erleichtern.<br>
Zu den bekanntesten und meistgenutzten Zertifikaten für digitale Langzeitarchive und Repositorien gehören das nestor-Siegel und das CoreTrustSeal. Ihre Kriterienkataloge sind publiziert und online verfügbar.

> Weitere Informationen finden sich in dieser NFDI4Culture Guideline zur Langzeitarchivierung: [Heseler / Büttner / Arnold 2024](https://nfdi4culture.de/id/E5342)

**Einige Merksätze:**

- Nicht alle Forschungsdaten aus einem Projekt müssen archiviert werden.
- Es sollten möglichst keine proprietäre Software und Datenformate genutzt werden (s. Kap. [Datenformate](#datenformate)).
- Verwendete Software sollte mit archiviert oder zumindest sollte in den Metadaten verzeichnet werden, welche Software genutzt wurde.
- Einmal archivierte Daten werden nicht mehr verändert!

## 10. Creative Commons Lizenzen

Wenngleich auf rechtliche Aspekte in diesem Kurs nicht erschöpfend eingegangen werden kann, sei exemplarisch auf eine weit verbreitete Form der Lizensierung von Forschungsdaten geschaut.

Publizierte und archivierte Daten sollten stets unter einer Lizenz stehen, die ihre Möglichkeiten zur Nachnutzung beschreibt.<br>
Die Creative-Commons-Lizenzen (CC-Lizenzen) bieten ein verbreitetes, angesehenes und leicht zu händelndes Lizenz-System.

- CC-Lizenzen decken die meisten Nutzungsszenarien ab und liegen in zahlreichen Sprachen vor.
- Sie liefern für Laien verständliche Erklärungen der Lizenzen, sowie einen rechtlich fundierten Lizenzvertrag.
- CC-Lizenzen sind modular aufgebaut und bestehen aus folgenden Bestandteilen: 
  
  * BY: Namensnennung des Urhebers
  * NC: nicht kommerzieller Gebrauch (Non Commercial)
  * ND: nicht bearbeiten oder verändern (No Derivatives)
  * SA: Weitergabe unter selben Bedingungen (Share Alike)
- Mit CC0 / Public Domain werden alle Rechte am Werk abgegeben.
- Diese Lizenzen sind beliebig kombinierbar, solange sie sich nicht widersprechen, das würde sie ungültig machen.
- CC-Lizenzen sind nur mit einer Verlinkung der entsprechenden Lizenz-Urkunde auf der Creative-Commons-Website gültig.
- Einmal vergebene Lizenzen können nicht zurückgezogen oder verschärft werden!

<!--- 

Das ist einiges inhaltlich falsch, vergleiche https://de.creativecommons.net/was-ist-cc/
Habe erst noch die zweite Frage korrigiert, aber die dritte noch gelassen, weil das angeblich unzulässig ist; aber CC-BY-ND ist ja schon die Kombination von CC-BY und CC-ND! 

### Das CC-Lizenzen Quiz // DAS KANN NICHT SO BLEIBEN!
Nicht jede CC-Lizenz-Kategorie ist mit jeder anderen kombinierbar. Testen Sie sich selbst, erkennen Sie auch unzulässige Lizenz-Kombinationen? <br>
<sub> (Übernommen aus den Train-the-Trainer-Folien der DINI/nestor-AG Forschungsdaten) </sub>

**Was erhählt man bei der Kombination von CC-BY und CC-BY-SA?**

- [( )] CC-BY
- [(x)] CC-BY-SA
- [( )] unzulässig
- [( )] anderes

---

**Was erhählt man bei der Kombination von CC-BY-SA und CC-BY-NC?**

- [( )] CC-BY-SA
- [( )] CC-BY-NC 
- [(x)] CC-BY-NC-SA
- [( )] unzulässig
***
<br>CC-BY-SA erlaubt zwar die kommerzielle Nutzung, sie wird aber durch die Komnbination mit CC-BY-NC ausgeschlossen; die Kombination ist also eine gültige Ergänzung, aber kein Widerspruch [(vgl.)](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.de).
***

 

**Was erhählt man bei der Kombination von CC-BY und CC-BY-ND?**

- [( )] CC-BY
- [( )] CC BY-NA
- [(x)] unzulässig
- [( )] andere
***
Warum ist es unzulässig?<br>CC-BY erlaubt die Bearbeitung, CC-BY-ND verbietet diese aber explizit, somit widersprechen sich die beiden Lizenzen und können nicht kombiniert werden.
***
--->

## 11. Der Datenmanagementplan

> Merksatz:<br>Ein Datenmanagementplan (DMP) beschreibt den strukturierten Umgang mit Daten. Er bestimmt, wie mit Daten im Laufe des Projekts verfahren wird und sollte deshalb ein **lebendes Dokument** sein, dass während des Projekts angepasst und verändert werden darf.

Datenmanagementpläne helfen dabei den Umgang mit Daten in Projekten zu planen. Außerdem sind DMPs eine gute Grundlage und Anlaufstelle für Fragestellungen rund um die Datenhaltung, die bei der Arbeit in einem Forschungs-Team entstehen.

- Fördergeber können Vorgaben machen, aber ein DMP muss nicht grundsätzlich einem bestimmten Aufbau folgen.

  - Der Forschungsdaten-Lebenszyklus kann dabei als Orientierung dienen.
  - Die meisten Fördergeber bieten Checklisten an, die bei der Erstellung von DMPs unterstützen sollen und auf die Anforderungen des Fördergebers ausgelegt sind.
  
- Ein DMP verbessert die Nachnutzbarkeit von Daten und das Management von Daten und Wissen, etwa bei Personalwechseln.
- Zur Orientierung kann es helfen, DMPs anderer Projekte zu konsultieren.

---

**Was macht einen guten DMP aus?**

- DMPs sollten gut strukturiert sein.
- „So kurz wie möglich, so lang wie nötig.“
- Alle Projektbeteiligte sollten den DMP kennen und Zugriff darauf haben.
- Idealerweise wird der DMP zu Projektende ebenfalls veröffentlicht.

### Das RDMO-Tool

RDMO, steht für Research Data Management Organiser und ist ein freies Open Source Tool für die Erstellung von Datenmanagementplänen. Es stellt anhand von Frgaenkatalogen Muster für fach- bzw. datenspezifische Forschungsdaten zur Verfügung.

- Wie ist das Vorgehen und wie wird RDMO genutzt? 
  
  * Auswahl eines passenden Fragenkatalogs
  * Schritt für Schritt abarbeiten der Fragen
  * Als Ergebnis erhält man einen „fertigen“ Plan in verschiedenen Dateiformaten.
- Institutionen können RDMO-Instanzen einrichten, Funktionen und Design sind dabei individualisierbar.

Die RDMO-Website bietet ein Demo-Programm an, das nach Anmeldung kostenlos genutzt werden kann. Accounts können kostenlos erstellt werden.

---
Ab sofort stellt unser Konsortium einen Research Data Management Organiser (RDMO) für Forschende und Kulturschaffende der Architektur-, Kunst- und Musik- bis hin zu Theater-, Tanz-, Film- und Medienwissenschaft zur Verfügung. 

https://rdmo.nfdi4culture.de/

Nach dem Login und einmaliger Freischaltung Ihres NFDI4Culture Accounts, können verschiedene Vorlagen, z. B. von Fördergebern wie der DFG oder der Europäischen Kommission, für einen DMP ausgewählt werden.  

## 12. Dokumentation
Der Datenmanagement-Plan beschreibt, wie in dem Projekt die Daten behandelt werden und wächst mit dem Projekt. <br>
Eine Dokumentation hingegen beschreibt und dokumentiert Prozesse und Daten im Projekt. Da sich dieser Kurs um das Datenmanagement handelt, sei hier ein Fokus auf die **Datendokumentation** gelegt.

Eine gute Datendokumentation erhöht die Nachnutzbarkeit der Daten erheblich, die Daten werden FAIRer (s. a. [FAIR-Prinzipien](#die-fair-prinzipien)). <br>
Das gilt nicht nur für die Nachnutzung Dritter, sondern auch die Nutzung der Daten durch die Datenerzeugenden selbst.

Es bietet sich an, Daten direkt nach ihrer Erhebung zu dokumentieren. Wichtige Informationen könnten verloren gehen, wenn die Dokumentation erst zum Ende eines Projektes erstellt wird, zudem würde so die alltägliche Arbeit mit den Daten erschwert, läge konkretes Wissen über die Daten doch nur bei den Datenerzeugenden selbst. <br>
Zudem sind gegen Ende von Forschungsprojekten häufig Zeit und Resourcen knapp, wodurch die Gefahr besteht, dass die Dokumentation nicht aureichend erstellt wird. <br><br> 
In jedem Projekt ist individuell zu entscheiden, welche Arten der Dokumentation am geeignetsten sind. Es gibt jedoch einige Leitlinien, an denen sich orientiert werden kann.

---

Bestandteile einer guten Datendokumentation:

- Informationen zur Erhebung der Daten

  - verwendete Methoden
  - Einheiten
  - Zeiträume und Orte der Erhebung
  - verwendete Technik (Hardware, Software)
- Maßnahmen zur Datenbereinigung
- Struktur der Daten und deren Beziehungen zueinander
- Erläuterung von Variablen, Labels und Codes
- Unterschiede zwischen verschiedenen Versionen
- Informationen über Zugang und Nutzungsbedingungen
- Speicherorte der Daten

---

Formen von Dokumentationen:

- Dokumentation durch Metadaten (s. a. Kapitel [6. Metadaten](#6. metadaten))
- READ.me-Dateien
- Data Dictionaries
- Codebooks

  - Erklärungen für Codes und Label

---

**Was passiert, wenn ich Daten nicht richtig dokumentiere?**

- Daten werden schlecht oder gar nicht gefunden
- Entstehung der Daten ist nicht nachvollziehbar, was die Interpretation erschwert oder sogar verhindert
- Fehlende Informationen zur Erhebung und Kontext verhindern die Nachnutzung
- Verwechslung von Daten (ältere Versionen, gleichnamige Dateien etc.)

## Weiterführende Literatur und Links
<p style="font-size:25px"><b><u>Literatur</u></b></p>

**Dang 2020**<br>
Dang, Sarah-Mai: Forschungsdatenmanagement in der Filmwissenschaft. Daten, Praktiken und Erkenntnisprozesse. In: montage AV. Zeitschrift für Theorie und Geschichte audiovisueller Kommunikation, Jg. 29 (2020), Nr. 1, http://dx.doi.org/10.25969/mediarep/21687

**Fichtel 2024**<br>
Fichtel, Barbara: LIDO-Schulung, 2024, https://nfdi4culture.de/go/E5247

**Fischer / Petri 2022**<br>
Fischer, Veronika / Petri, Grischka: Bildrechte in der kunsthistorischen Praxis – ein Leitfaden, zweite, überarbeitete und erweiterte Auflage, 2022, https://doi.org/10.11588/ARTDOK.00007769

**Goller / Heftberger 2018**<br>
Goller, Marion / Heftberger, Adelheid (2018) Die Öffnung von Forschungsdaten in den Film- und Medienwissenschaften: praktische und urheberrechtliche Herausforderungen. In: Fachinformationsdienst für internationale und interdisziplinäre Rechtsforschung, 2018, https://doi.org/10.17176/20180515-233758

**Heseler / Büttner / Arnold 2024**<br>
Heseler, Jörg / Büttner, Alexandra / Arnold, Matthias, Grundlagen der digitalen Langzeitarchivierung. Eine Handreichung zur digitalen Langzeitarchivierung aus Perspektive der NFDI4Culture Community, 2024, https://nfdi4culture.de/id/E5342

**Imeri / Rizzolli 2022**<br>
Imeri, Sabine / Rizzolli, Michaela (2022): CARE Principles for Indigenous Data Governance: Eine Leitlinie für ethische Fragen im Umgang mit Forschungsdaten?, in: O-Bib. Das Offene Bibliotheksjournal 9, 2 (2022), S. 1–14, https://doi.org/10.5282/o-bib/5815

**Kailus 2023**<br>
Kailus, Angela: Handreichung für ein FAIRes Management kulturwissenschaftlicher Forschungsdaten, 2023, https://nfdi4culture.de/go/E3625

**Klimpel / Rack 2023**<br>
Rack, Fabian / Klimpel, Paul: Audiovisuelle Materialien in Forschung und Lehre
– eine Übersicht zu urheberrechtlichen Aspekten, 2023, https://docs.nfdi4culture.de/ta6-
audiovisuelle-materialien-urheberrecht-in-forschung-und-lehre

**Klimpel 2021**<br>
Klimpel, Paul: „Urheberrechtsreform 2021: neue Chancen für das kulturelle Erbe“, 2021, https://nbn-resolving.org/urn:nbn:de:0297-zib-84315

**Knaus / Stein / Kailus 2019**<br>
Knaus, Gudrun / Stein, Regine / Kailus, Angela: LIDO-Handbuch für die Erfassung und Publikation von Metadaten zu kulturellen Objekten: Band 1: Graphik, herausgegeben von Deutsches Dokumentationszentrum für Kunstgeschichte – Bildarchiv Foto Marburg und Christian Bracht, Heidelberg: arthistoricum.net, 2019 (LIDO-Handbuch, Band 1), https://doi.org/10.11588/arthistoricum.382.544

**Knaus / Kailus / Stein 2022**<br>
Knaus, Gudrun / Kailus, Angela / Stein, Regine: LIDO-Handbuch für die Erfassung und Publikation von Metadaten zu kulturellen Objekten: Band 2: Malerei und Skulptur, herausgegeben von Deutsches Dokumentationszentrum für Kunstgeschichte – Bildarchiv Foto Marburg und Christian Bracht, Heidelberg: arthistoricum.net, 2022 (LIDO-Handbuch, Band 2), https://doi.org/10.11588/arthistoricum.1026

**Krause et al. 2024**<br>
Krause, Celia / Bergmann, Katharina / Hausen, Daniela Adele / Riedel, Roman / Windeck, Jürgen: Qualitätskriterien für DMP-Vorlagen, 2024, https://doi.org/10.5281/zenodo.13347687

**Lin et al. 2020**<br>
Lin, Dawei / Crabtree, Jonathan / Dillo, Ingrid / Downs, Robert R. / Edmunds, Rorie / Giaretta, David / De Giusti, Marisa / L’Hours, Hervé / Hugo, Wim / Jenkyns, Reyna / Khodiyar, Varsha / Martone, Maryann E. / Mokrane, Mustapha / Navale, Vivek / Petters, Jonathan / Sierman, Barbara / Sokolova, Dina V. / Stockhause, Martina / Westbrook, John: „The TRUST Principles for digital repositories“, in: Scientific Data, 7(1), 2020, https://doi.org/10.1038/s41597-020-0486-7

**Rössel / Stenger / Kailus / Stein 2025**<br>
Rössel, Julia / Stenger, Viola / Kailus, Angela / Stein, Regine: LIDO-Handbuch für die Erfassung und Publikation von Metadaten zu kulturellen Objekten: Band 3: Architektur und andere ortsfeste Werke, herausgegeben von Christian Bracht, Heidelberg: arthistoricum.net, 2025 (LIDO-Handbuch, Band 3), https://doi.org/10.11588/arthistoricum.1407

**Rothfritz / Burkart 2020**<br>
Rothfritz, Laura / Burkart, Christine: FAIR Data Maturity Model (dt. Übersetzung), 2020, https://doi.org/10.5281/zenodo.5834115

**Stellmacher / Vettermann 2025**<br>
Stellmacher, Martha / Vettermann, Oliver: NFDI4Culture-Kommunikationsleitlinie zu den CARE-Prinzipien für indigene Datensouveränität, 2025, https://nfdi4culture.de/id/E6467

**Vettermann / Petri 2023**<br>
Vettermann, Oliver / Petri, Grischka: Should I CARE about FAIR – Ein juristischer Blick auf die Prinzipien des Forschungsdatenmanagements, in: Recht und Zugang 4, 1 (2023), S. 5–29, https://doi.org/10.5771/2699-1284-2023-1-5

**Wilkinson et. al 2016**<br>
Wilkinson, Mark D./ Dumontier, Michel / Aalberg, Isbrand J. / Appleton, Gabrielle /
Axton, Myles / Baak, Arie / Blomberg, Niklas et al. (2016): The FAIR Guiding Principles
for scientific data management and stewardship, Scientific Data 3 (2016),
https://doi.org/10.1038/sdata.2016.18

---
<p style="font-size:25px"><b><u>Links</u></b></p>

Deutschen Forschungsgemeinschaft (DFG): Checkliste zum Umgang mit Forschungsdaten, 2021, https://www.dfg.de/resource/blob/174732/forschungsdaten-checkliste-de.pdf

Deutschen Forschungsgemeinschaft (DFG): Dokumente zum fachspezifischen Umgang mit Forschungsdaten, https://www.dfg.de/de/grundlagen-themen/grundlagen-und-prinzipien-der-foerderung/forschungsdaten/empfehlungen

**DFG 2025**<br>
Deutschen Forschungsgemeinschaft (DFG): Leitlinien zur Sicherung guter wissenschaftlicher Praxis, Aufl. 3 (2025), https://doi.org/10.5281/zenodo.3923601

Münchner Memorandum „Forschungs­daten in der Kunst­geschichte: 10 Thesen“, 2024, https://doi.org/10.11588/artdok.00009194

Sonderrreihe Forschungsdaten, Open Media Studies Blog, https://mediastudies.hypotheses.org/tag/sonderreihe-forschungsdaten

## Zusatzmaterial: Interaktive Module
Dieses Kapitel stellt einige Übungen und Aktivierungsmethoden vor, die in der Lehre genutzt werden können und die vorliegende OER ergänzen.

### Übung zum Thema "Datenlebenszyklus"

- *Anregegung aus dem Train-the-Trainer von fdm.nrw*: Kurze Übung, max. 15. Min.: <br>
Auf einem Conceptboard "Überschriften" des DLZ verschieden farbig angeben und dazu ungeordnet auf weißen Post-Its Schlüsselbegriffe/Schlagwörter und Inhalte aus DMPs angeben. <br>
Die TN müssen dann die Begriffen mit den zugehörigen Überschriften verknüpfen. Wenn die TN mit der Auswahl sicher sind, dann können die Post-Its der Farbe der Überschrift angeglichen werden.<br> Anschließend Ergebnisse im Plenum diskutieren. <br>
Die Übung ust nur bis zu einer bestimmten Gruppengröße sinnvoll, ansonsten besser Kleingruppen, denn wenn alle Teilnehmer einer Gruppe 20+ auf dem Conceptboard gleichzeitig Post-Its verschieben, ist es mehr Chaos als Lerneffekt.

### Übung zum Thema "Kontrollierte Vokabulare" (GLAM-Fokus)

- Zu Beginn des Kurses als Aktivierung mit Mentimeter den Kenntnisstand der TN abfragen, bzgl. der in diesem WS besprochenen Themen; z. B.: WordCloud mit der Frage: Welche kontrollierten Vokabulare werden an ihrer Einrichtung genutzt? oder (anonyme! das auch betonen bei Stellen der Frage) Abfrage mit der Ausgabe eines Balkendiagramms, z. B. zu der Frage: Wie gut ist die Qualität meiner Sammlungsdaten?

### Rechercheaufgabe FDM-Policies (10 Min.)

- Wenn man sich als Doktorand:in, Early Career Researcher, GLAM-Mitarbeiter:in, etc. die Frage stellt, wie man mit den eigenen Forschungsdaten umgehen soll bzw. welche Regeln man befolgen muss, wird man bei der Suche schnell erschlagen von den vielen (häufig generischen) Antworten, die man dazu findet - bspw. die FAIR- und CARE-Prinzipien. Deshalb lohnt es sich, erstmal zu recherchieren, ob die Institution, bei der man angestellt ist,<br>
1. eine eigene Beratungsstelle zum Umgang mit Forschungsdaten hat und<br> 
2. ob eure Institution vielleicht sogar schon eine eigene Forschungsdaten-Policy verabschiedet hat, an die ihr euch grundsätzlich halten müsstet. <br>
Und genau das wollen wir jetzt mal machen: 

- Hat Eure Universität oder Institution eine eigene FD-Policy?
- Welche FD-Beratungsstellen gibt es an Euren Universitäten oder Institutionen?

### Teilnehmer-Aktivierung

Zu Beginn des Kurses

* Erfahrung: Direkt zu Beginn möglichst die Teilnehmer aktiv mit einbeziehen, das hilft erfahrungsgemäß dabei, dass bei späteren aktiven Parts, Gruppenarbeit, etc. weniger Leute abspringen. (Also jenes Phänomen von Online-Veranstaltungen, dass wenn man aktive Mitarbeit der Teilnehmer:innen ankündigt, ein großer Block der TN das Meeting verlässt.)
* Erfahrung: Möglichst wenige Fragen auf einmal stellen, eher schrittweise die Fragen anführen, die man bei einem Aktiv-Teil den Teilnehmern stellen möchte
* Aus dem TtT: Zum Einstieg grafische Elemente verwenden, beispielsweise kann ein Ablaufplan des Kurses präsentiert werden und jede:r Teilnehmer:in darf ihre/seine Ideen zu und Erwartungen an den genannten Bereichen notieren und was ihnen noch fehlt (z.B. über die Live-Kommentar-Funktion von Zoom)


- Aus dem Train-the-Trainer: Wenn man Begriffe oder Ergebnisse von vorherigen Workshops abfragen oder rekapitulieren lassen möchte -> Wheel of Names (! Manchmal merkwürdige Werbung, Alternative ist uns, wenn vorhanden, gerade leider unbekannt)
- Aus dem Train-the-Trainer: (nur bei kleinen Gruppen zeit-technisch sinnvoll) Vorstellungsrunde mit Name, Einrichtung, Profession/Fach und einem "random fact"; wer eine Verbindung zu sich sieht hebt die Hand und ist dann als nächstes dran 
  * Notiz: Vorstellungsrunden lohnen bei großen Gruppen und bei kurzen Veranstaltungen von wenigen Stunden wenig. Ab 2-tägigen Veranstaltungen und bei moderater Gruppengröße können sie aber helfen, die Gruppe zu stärken und Hemmschwellen zu senken

### Tools für interaktive Online-Sessions


* Mentimeter (für Umfragen & WordCloud)
* Conceptboard/Miro (für Kleingruppenarbeit, Conceptboard datenschutzrechtlich besser)
* Wheel of Names (als Aktivierungsmethode): Unverfängliche Fragen eingeben, hier können die Teilnehmer:innenn das Rad drehen und Fragen beantworten (ist eine kommerziell betriebene Seite, die mit Werbebannern versehen ist), kann auch fachspezifisch umgewidmet werden.
* Tools können auch direkt in Zoom genutzt werden, wie etwa für Umfragen, als Kommentarfunktion, um ein häufiges Wechseln der Oberfläche geringzuhalten.