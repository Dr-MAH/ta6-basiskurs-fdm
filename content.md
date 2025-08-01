<!--
link : ./resources/oer-design_GL.css
icon : ./resources/icon_4Culture.png
version: 0.5
author: Martin Albrecht-Hohmaier, Katharina Bergmann, Vincent Fröhlich, Alexander Stark, Andrea Polywka
narrator: Deutsch female
comment: Dieser Kurs ist eine Open Educational Resource der NFDI4Culture Arbeitsgruppe Cultural Research Data Academy (CRDA). Gefördert durch die Deutsche Forschungsgemeinschaft (DFG), Projektnummer 441958017. <br> Wir nutzen hierfür den Markdown-Dialekt LiaScript. <br> Der Kurs steht unter der CC-BY-Lizenz
-->

<!--- Link zum How To-Dokument: https://cloud.nfdi4culture.de/f/3313403  --->

# Basiskurs Forschungsdatenmanangement für Geistes- und Kulturwissenschaften

Eine Open Educational Resource der NFDI4Culture Arbeitsgruppe [Cultural Research Data Academy (CRDA)](https://nfdi4culture.de/id/E1826)

<img src= "../resources/NFDI4C_Logo_DyptichText.png" width=50% height=70%>

Gefördert durch die Deutsche Forschungsgemeinschaft (DFG).<br>
Projektnummer: 441958017

---

Wir freuen uns, wenn unsere Materialien nachgenutzt werden, deshalb steht dieser Kurs unter einer Lizenz, die die Nachnutzung ermöglicht: [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## Welche Inhalte bietet dieser Kurs?

 1. Der Forschungsdatenbegriff
 2. Datenformate
 3. Forschungsdatenmanagement
 4. Der Datenlebenszyklus
 5. FAIR Principles
 6. CARE Principles
 7. Metadaten
 8. Normdaten und kontrollierte Vokabulare
 9. Sichern und Speichern
 10. Lizenzen
 11. Datenmanagement-Pläne
<br>
- Weiterführende Literatur
- Zusatzmaterial

### Abkürzungen in diesem Kurs

- DLZ = Datenlebenszyklus
- DMP = Datenmanagementplan
- FD = Forschungsdaten
- FDM = Forschungsdatenamangement
- LZA = Langzeitarchivierung

## Der Forschungsdatenbegriff

Wenn wir uns mit dem Thema Forschungsdatenmanagement auseinandersetzen, dann sollten wir klären, was eigentlich unter dem Begriff "Forschungsdaten" zu verstehen ist.

---

Die DFG beschreibt es so:

„Ein fachspezifisch adäquater Umgang mit Forschungsdaten, die wissenschaftlichen Projekten zugrunde liegen oder bei deren Durchführung entstehen, ist ein wesentlicher Bestandteil qualitätsorientierter und anschlussfähiger Forschung. Zu Forschungsdaten zählen u. a. Messdaten, Laborwerte, audiovisuelle Informationen, Texte, Surveydaten oder Beobachtungsdaten, methodische Testverfahren sowie Fragebögen.“
<sub>([aus den Leitlinien zum Umgang mit Forschungsdaten  der Deutsche Forschungsgemeinschaft, 2023](https://www.dfg.de/de/grundlagen-themen/grundlagen-und-prinzipien-der-foerderung/forschungsdaten))</sub>



---

Wir haben unser Verständnis in diesem knappen Merksatz zusammengefasst:

> Daten werden zu Forschungsdaten, wenn sie wissenschaftlichen Richtlinien entsprechend erfasst, beschrieben, kontextualisiert oder kommentiert werden.

## Datenformate
Jede Software hat ein vorgegebenes Dateiformat, in dem es seine Daten speichert. Doch ist das in den allermeisten Fällen nicht das einzige nutzbare Datenformat, in einigen Fällen auch nicht das beste für den jeweiligen (Forschungs-)Kontext. <br>
Grundsätzlich sollten Daten möglichst nie in proprietären Datenformaten gespeichert, gar archiviert werden. Zudem kann darauf geachtet werden, dass die Dateiformate resourcenschonend sind, indem sie etwa geringere Mengen Speicherplatz beanspruchen, als alternative Formate. <br>

---

**Empfehlungen für Dateiformate** <br>
<sub>(aus [Kailus 2023](https://docs.nfdi4culture.de/ta2-fair-handreichung/empfehlungen-dateiformate#10-empfehlungen-f%C3%BCr-dateiformate))</sub>

Verwenden Sie möglichst weit verbreitete und mit einem ISO-Standard verbundene Dateiformate. Sie sollten nicht proprietär, also nicht an eine Software oder einen Hersteller gebunden, mit unterschiedlichen Programmen verwendbar und mit einer offenen Lizenz versehen sein und über eine frei zugängliche Dokumentation einschließlich der technischen Spezifikationen verfügen. Sie erlauben eine verlustfreie Speicherung ohne Kompression und sie sind einfach dekodierbar oder unmittelbar lesbar.
Konsultieren Sie Ihre Datenplattform, welche Dateiformate dort entgegengenommen bzw. empfohlen werden.

Für die Kulturwissenschaften und für Kulturerbe-Sammlungen empfehlen wir die Verwendung folgender Standard-Dateiformate:<br>
<br><br>
**Text**

- Extensible Markup Language (XML) 1.1, mit XML Schema Definition (XSD)
- Resource Description Framework in Attributes (RFDa) für das Einbetten von RDF-Statements in XML
- JavaScript Object Notation (JSON)
- JavaScript Object Notation for Linked Data (JSON LD)
- Comma-Separated Values (CSV)
- Textdatei (TXT) (Codierung UTF-8)
- Präsentationsformat: Portable Document Format A (PDF-A)
<br><br>

**Musik**

- Music Encoding Initiative (MEI)
- MusicXML
- Parsons Code
- Präsentationsformat: Portable Document Format A (PDF-A)
<br><br>

**Bild (Rastergrafiken)**

- Rohdaten: Digital Negative (DNG)
- Master: baseline Tagged Image File Format (TIFF), unkomprimiert; TIFF mit Lempel-Ziv-Welch-Komprimierung (TIFF-LZW)
- Joint Photographic Experts Group (JPEG 1 und JPEG 2000), verlustfrei komprimiert, lizenzfreie Bereiche
- Präsentationsformate (Derivate): JPEG, JPEG 2000, Portable Network Graphics (PNG)
<br><br>

**Bild (Vektorgrafiken) und CAD**

- Scalable Vector Graphics (SVG)
<br><br>

**Audio**

- Archivformat: Waveform Audio File-Format (WAV) in Verbindung mit Pulse Code Modulation (PCM); Free Lossless Audio Codec (FLAC)
- Präsentationsformat: MPEG-2 Audiolayer III (MP3)
<br><br>

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



#### <font color=#f55249> 🎨 Forschungsdaten in der Kunstgeschichte </font>
Kunsthistorische Forschungsdaten sind, wie das Fach selbst, sehr divers. Sie umfassen u. a. Notizen, Exzerpte, Fotografien, Tabellen, Skizzen, Transkriptionen, Textversionen, Rekon­struk­tionen. <br>
Je nach fachlicher Ausrichtung braucht es andere Dateiformate und Analysetools, um mit ihnen umzugehen. Beispielsweise werden an 3D-Rekonstruktionen von Plastiken und Statuen andere Fragestellungen gestellt, als an Architektur-Rekonstruktionen; an Buchmalerei andere Fragen als an Ölgemälde. <br>

Die deutschsprachige Kunstgeschichte hat sich bisher nicht auf einen einheitlichen Umgang mit Forschungsdaten und feste Standards geeinigt. Doch steigt auch unter Kunsthistorikern das Bewusstsein um die Relevanz guten Forschungsdatenmanagements. Mit dem [Münchner Memorandum „Forschungs­daten in der Kunst­geschichte: 10 Thesen“](https://doi.org/10.11588/artdok.00009194) liegt jedoch seit 2024 ein Paper vor, das auf Initiative des Deutschen Verbandes für Kunstgeschichte e. V., der Universitätsbibliothek Heidelberg / arthistoricum.net und des Zentralinstituts für Kunstgeschichte erarbeitet wurde, und aus Sicht des Faches in Deutschland aktuelle Anforderungen, Positionen und Impulse zur weiteren Entwicklung digitaler kunsthistorischer Forschungsdaten und ihrer Infrastruktur formuliert.

#### <font color=#d618c0> 🎬 Forschungsdaten in der Medienwissenschaft </font>

Medienwissenschaftliche Forschungsdaten zeichnen sich durch sehr heterogene Materialien aus. Darunter zählen „alle schriftlichen und bildlichen Aufzeichnungen sowie Material- und Quellensammlungen", mitunter auch Koppelungen von "fremden und eigenen Daten, d. h. von Originalquellen und eigenen Annotationen, Zeichnungen o. ä." ([Goller, Heftberger 2018, S.1](https://doi.org/10.17176/20180515-233758))

Digitalisierte Filme, einzelne Videoausschnitte, filmografische Metadaten, Sequenzprotokolle, Annotationen, Informationen zur Dokumentation des Analyseverfahrens (Ausführungen zum theoretischen Hintergrund, Bibliografie der verwendeten Forschungsliteratur, Nennung der Beteiligten), Reflexion der ausgewählten Kategorien, Hinweise zu den verwendeten Softwareprogrammen)." ([Dang 2020, S. 119–140](http://dx.doi.org/10.25969/mediarep/21687))

#### <font color=GREEN> 🎵 Forschungsdaten in der Musikwissenschaft </font>

Auch musikwissenschaftliche Forschungsdaten sind sehr divers, umfassen sie schließlich jegliche Daten, die im Verlauf von wissenschaftlichen Arbeitens entstehen – seien sie in unterschiedlichster Form digital (PDFs, Codierungen, Aufnahmen etc.) oder analog, wie auch deren digitale Reproduktionen.  
 <br> 
Sie umfassen 

- Notentexte (handschriftlich oder gedruckt) sowie weitere Textzeugen wie Skizzen, Briefe etc.
- visuelle und audiovisuelle Quellen (Fotos, Videos, Interviews etc.)
- rein digitale Textzeugen (Emails, Webseiten, etc.)
- Datenbanken
- Annotation und Metadaten 

---

### Exkurs: Video- und Bildannotation

Video- und Bildannotationstools sind lokale oder webbasierte Anwendungen für die Annotationen, d. h. Markierung und Kommentierung (audio-)visueller Inhalte. <br>

---

Nutzungsszenarien von Videoannotationstools:

- Identifikation von Objekten, Personen oder Ereignissen
- Zeitbezogene Analyse von Bild und Ton
- Qualitative oder quantitative Datenanalyse
- Visualisierung von Annotationen

---
Einige dieser Tools lassen manuelle oder (semi-)automatische Annotation von Bild und Ton zu. <br>
<br><br>
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

## Forschungsdatenmanagement

<!---
[KB] Hier muss noch mehr hin. Etwas wenig Inhalt bisher. [AP] Ich füge mal ein paar Stichpunkte aus unserem Skript vom letzten FFK-Kurs bei
---> 
Forschungsdatenamangement (FDM) umfasst alle Aktivitäten im Zusammenhang mit ...

- der Aufbereitung,
- Speicherung,
- Archivierung,
- und Nutzung von Forschungsdaten.

FDM begleitet den gesamten Forschungsprozess und standardisierte FDM-Prozesse verringern den zukünftigen Aufwand bei einer eigenen oder fremden Nachnutzung der Daten. <br>

FDM-Maßnahmen wie Datendokumentation, Datensicherung und eine geeignete Langzeitarchivierung (LZA) verringern auch das Risiko von Datenverlusten. Daten können durch geeignete FDM-Maßnahmen bestenfalls noch nach Jahrzehnten genutzt werden.<br>

Die vielseitigen technischen Möglichkeiten erfordern allerdings auch eine erhöhte Beachtung der Themen Datenschutz und Urheberrecht. Ebenso sollten rechtliche und ethische Aspekte beachtet werden, um die gute wissenschaftliche Praxis zu wahren [s. a. CARE-Principles](#17).

Der fachgerechte Umgang mit Forschungsdaten ist zudem Teil guter wissenschaftlicher Arbeit und Fördermittelgeber erwarten einen strukturierten Umgang mit Forschungsdaten, bspw. in Form eines Datenmanagementplan (DMP).

> Kodex [„Leitlinien zur Sicherung guter wissenschaftlicher Praxis“](https://www.dfg.de/de/grundlagen-themen/grundlagen-und-prinzipien-der-foerderung/gwp) der DFG



## Der Datenlebenszyklus 
<!---
MAH: Ich würde die Graphik und die folgenden Stationen nicht voneinader trennen, sondewrn auf einewr Seite bringen.
--->

<img src="../resources/FD_LZ.png" width=50% height=auto>
<p><br>
<sub> Graphische Darstellung eines DLZ, Creator: CRDA, CC0 </sub>
</p>
<br>



<!---
Bei den Stationen kann gerne weiter ergänzt werden! [AP] Habe ein paar Beispiele ergänzt
--->

- Der Datenlebenszyklus (DLZ) beschreibt den "Lebenskreislauf" von Forschungsdaten.
- Er kann dabei, ausgehend von seinem Detailgrad und der Art der Daten, leicht von dem hier angegebenen abweichen.
- Die grundsätzlichen Stationen sind:

  1. Forschungsvorhaben planen: Ein erster Datenmanagementplan wird erstellt.
  2. Daten erheben: Während der Forschungsarbeit entstehen Unbereinigten Daten. 
  3. Daten aufbereiten und analysieren: Die Daten werden bereinigt; Analysen und Datenaufbereitungen <br>
     (z. B. Digitalisierungs-, Transkriptions-, und Annotationsprozesse; Datenanalyse: Metadaten)
  4. Daten teilen und publizieren: Datenpublikation während oder nach dem Forschungsvorhaben <br>
     (z. B. über Open Access-Plattformen)
  5. Daten archivieren: Archivierung ausgewählter Daten für längere Zeiträume.
  6. Daten nachnutzen: Die veröffentlichten Daten können selbst oder durch andere nachgenutzt werden.

<!--- [KB] Wir könnten hier auch noch ein Quiz einbauen, á la: Was macht man an welcher Station des DLZ / MAH: sehr gute Idee :-)--->



## FAIR und CARE
Die Akronyme FAIR und CARE stehen für zwei wichtige Regelwerke im Kontext guten Forschungsdatenmanagement, sie werden in den folgenden Abschnitten genauer betrachtet.

Die beiden Akronyme werden gerne in einem Atemzug genutzt, es ist aber wichtig ihre sehr unterschiedlichen Anwendungsbereiche und Entstehungskontexte zu betrachten! <br><br>
Die FAIR-Prinzpien fokussieren überwiegend auf technische Aspekte und sind auf quasi jeden Datensatz anwendbar.<br><br>
Die CARE-Prinzipien hingegen stehen für einen angemessenen Umgang mit Daten, die indigene Gemeinschaften betreffen. Im Gegensatz zu FAIR liegt der Fokus also explizit nicht auf die Erleichterung des Datenaustauschs, sondern auf die Wahrung der Interessen indigener Gemeinschaften, was in einigen Fällen die FAIR-heit der Daten reduzieren kann.

Lest in den nächsten Kapiteln genauer nach, wofür FAIR und CARE stehen!

<!---
hier Erklärung/Erläuterung einfügen // MAH: welche?
--->

### Die FAIR-Prinzipien

FAIR steht für **f**indable, **a**ccesssible, **i**nteroparable und **r**eusable; übersetzt also für: auffindbar, zugreifbar, interoperabel und nachnutzbar.

Die Prinzipien wurden entwickelt, um Datenproduzent:innen und -herausgeber:innen im Umgang mit Forschungsdaten zu unterstützen. Sie betreffen nicht nur die Daten an sich, sondern auch die benuzten Algorithmen, Tools und Workflows.

Es gibt verschiedene Tools, die Wissenschaftler:innen dabei unterstützen, den FAIR-Gehalt ihrer Daten zu ermitteln:

- [NFDI4Culture FAIR-Check](https://nfdi4culture.de/id/E5080)
- [FAIR Assessment Tool von TKDM](https://tkfdm.github.io/FAIR-Data-Assessment-Tool/)

### QUIZ

<!---
MAH: Sollten die Quiz-Seiten eine eigene Überschrift bekommen? Und sie sollten in der Einleitung erwähnt werden!
--->

Wofür stehen die Buchstaben in FAIR?

**F wie ...**

- [[x]] findable
- [[ ]] free
- [[ ]] fantastic
- [[ ]] freely usable

**A wie ...**

- [[ ]] archivable
- [[ ]] addressable
- [[x]] accessable
- [[ ]] alternative

**I wie ...**

- [[ ]] integrate
- [[x]] interoparable
- [[ ]] interesting
- [[ ]] intellectual

**R wie ...**

- [[ ]] reproduce
- [[ ]] repurpuse
- [[ ]] redirectable
- [[x]] reusable

### Die CARE-Prinzipien

Die [CARE-Prinzipien](https://doi.org/10.5334/dsj-2020-042) wurden 2019 von der Global Indigenous Data Alliance als Ergänzung zu den FAIR-Prinzipien erarbeitet, um die Beteiligung indigener Gruppen an Entscheidungsprozessen zu stärken. Es geht darum, koloniale Kontexte und daraus resultierende ungleiche Machtverhältnisse zu identifizieren und zu berücksichtigen.

Die Prinzipien sind für jene Forschende relevant und sollten von ihnen in jedem Fall beachtet werden, die ethnologisch Forschen oder sich mit Daten aus kolonialen Kontexten beschäftigen.

CARE steht für Collective Benefit, Authority of Control, Responsibility und Ethics. Übersetzt also: Kollektiver Nutzen, Kontrollbefugnisse, Verantwortung und Ethik.
Vergleiche hierzu auch die [NFDI4Culture-Kommunikationsleitlinie zu den CARE-Prinzipien für indigene Datensouveränität](https://nfdi4culture.de/id/E6467)

---

Kooperationen mit Ursprungscommunities können den CARE-Prinzipien folgend u. a. wie folgt aussehen: 

- gemeinsame Bearbeitung von Objekten
- gleichberechtigten Zugang zu den Daten ermöglichen
- indigene Ethik einbeziehen
- eigenes Handeln und Darstellung von Objekten/Forschungsgegenständen regelmäßig hinterfragen
- wenn nötig, öffentlichen Zugang zu Daten einschränken
- kulturelle Metadaten, z. B. Bezeichnungen aus Herkunftskontexten; Provenienzangaben in den Metadaten; Auswahl der Metadaten transparent machen
- Nutzung von Disclaimern
- Nutzung von Notices, dass indigene Daten verwaltet werden
- Nutzung von Traditional Knowledge Labels (z. B. Kennzeichnung als weibliches Wissen, sakralen Kontext etc.)

### Kultur- und Geisteswissenschaftliche Anwendungsfälle der CARE-Prinzipien
In ethnologisch forschenden Bereichen, etwa der Musikethnologie, sind die CARE-Prinzipien eine wichtige Leitlinie beim Umgang mit Forschungsdaten. <br><br>
Folgend seien einige Anwendungsfälle aufgezeigt, die den Nutzen der CARE Prinzipien illustrieren:

<!--- Hier noch ergänzen: Bisher das Material von Andrea und Alex aus dem FFK-Kurs / Material von Barbara Alge?--->
- Forschungsdaten zu Filmmaterial aus kolonialen Kontexten

  - bspw. Amateurfilme, wissenschaftliche Filme, Travelogues, „Kulturfilme“
- Forschungsdaten zu Tonmaterial aus kolonialen Kontexten
  
  - bspw. Phonographenwalzen aus Wachs aus ethnologischen Forschungskontexten, u. a. auch aus Kriegsgefangenenlagern des Ersten Weltkriegs

- Forschungsdaten zu geraubten Kulturgütern aus kolonialen Kontexten

  - bspw. 3D-Digitalisate von geraubten Objekten

## Metadaten

Metadaten sind Daten, die andere Daten beschreiben. Sie sind in vielerlei Hinsicht relevant, etwa um die Auffindbarkeit von Daten zu erhöhen oder Daten zu beschreiben, die ihrerseits nur unter eingeschränkten Zugang oder gar nicht verfügbar sind.

<br>

> Merksatz: "Metadaten sind Daten, die andere Daten beschreiben"

<br>

Metadaten können in verschiedene Kategorien unterteilt werden.
Eine übliche Aufteilung ist:

- **Deskriptive Metadaten**: Sie enthalten beschreibende Informationen über den Inhalt des Objekts, sie dienen der Identifizierung von Objekten oder Daten
- **Administrative Metadaten**: Sie enthalten Informationen zum Objekt, die über seinen Inhalt hinausgehen wie z. B. Rechteinformationen und Details des analogen Objekts
- **Strukturelle Metadaten**: Sie beschreiben den Metadatensatz an sich und seine Beziehung zur digitalen Datei
- **Technische Metadaten**: Sie beschreiben die technischen Eigenschaften einer digitalen Datei Ergänzt werden kann diese Liste durch
- **Archivmetadaten**: Sie beinhalten spezieller zusammengestellte Informationen, die für die Archivierung relevant sind

<img src= "../resources/Metadaten.png" width=50% height=70%> <br>
<sub>Andrea Polywka, Alexander Stark: Metadaten Schaubild</sub>

### Metadaten – warum?

- Alle Arten von Forschungsdaten sollten stets mit Metadaten versehen werden
- Metadaten halten Daten verständlich und machen sie leichter auffindbar, da sie 
  
  * weiterführende, maschinenlesbare Informationen zu den Daten bereitstellen
  * und Datensätze untereinander in Beziehung setzen.
- Metadaten sollten gesondert als Metadatenpublikation veröffentlicht werden, um auch unabhängig von dem betreffenden Datum abrufbar zu sein.

### Metadaten Standards
Auch für Metadaten gibt es Standards, die ihre Vergleichbarkeit sicherstellen und vor allem ihre Nutzbarkeit für Suchmaschinen erhöhen.

Dies sind einige fachübergreifende Standards:

- Dublin Core
- EXIF (Bildmetadaten)
- PREMIS
- METS MODS

Für alle Metadaten gilt, dass sie strukturiert erfasst sein sollten und den Standards des jeweiligen Fachs entsprechen.

---

Warum gibt es mehr fachspezifische denn medienspezifische Standards? 

- Einzelne Fächer stellen unterschiedliche Fragen an dieselben Medien und arbeiten anders mit ihnen; das hat teilweise den Effekt, dass sie teils unterschiedliche Metadaten erfassen und sich dadurch historisch verschiedene Standards entwickelt haben!

#### <font color=#d618c0> 🎬 Metadatenstandards der Medienwissenschaft </font>
In Deutschland gibt es (noch) keinen allgemein genutzten/akzeptierten Metadaten-Standard für audiovisuelle Metadaten. <br>
Damit Metadaten FAIR sind und bleiben, sollten sie sich an bestehenden Schemata orientieren.

Eine Auswahl  von in der  Archivierung gebräuchlichen Normen und Standards für die Erschliessung:

- ISAD (G)
- PREMIS
- METS
- Dublin Core (DC)
- PBCore
- EBUCore
- MPEG-7 Multimedia Content Description Interface

## Normdaten

**Was sind Normdaten?**

- Eine Normdatei oder kontrolliertes Vokabular ist ein Verzeichnis strukturierter Datensätze.
- Jedem Normdatum wird eine feste Nummer als Identifikator zugeordnet.

---

**Wozu brauche ich Normdaten?**

- Zum vereinfachen die Darstellung komplexer Zusammenhänge
- Zur Vermeidung von Mehrdeutigkeiten und falschen Zuordnungen vor allem für Maschinen, die anders als Menschen nicht aus dem Kontext schließen können
- Die Verwendung von Normdaten ermöglicht besseren Austausch und bessere Nachnutzbarkeit der Daten.

Ein **kontrolliertes Vokabular** ist eine Sammlung von Normdaten, es verknüpft auch Synonyme, die zum selben Suchergebnis führen und liefern dazu oft Übersetzungen in andere Sprachen.

> Video-Tipp: NFDI4Culture Video-Tutorial zu Normdaten! https://av.tib.eu/media/60986
<div style="position: relative; width: 100%; aspect-ratio: 16 / 9;">
  <iframe src="https://av.tib.eu/player/60986" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
</div>

### Kontrollierte Vokabulare in Geistes- und Kulturwissenschaften

Eine Auswahl kontrollierter Vokuabulare für die Geistes- und Kulturwissenschaften:

- Deutsche Nationalbibliothek – Gemeinsame Normdatei (GND)
- Virtual International Authority File (VIAF)
- International Standard Name Identifier (ISNI)
- Getty Vokabulare
  
  * Thesaurus of Geographic Names (TGN)
  * Art & Architecture Thesaurus (AAT)
  * Union List of Artists Names (ULAN)
- Wikidata

## Sichern und Speichern

Die vorigen Kapitel haben schon eingies vorwegennommen, was beim Speichern von Daten sinnvoll und wichtig ist, folgend seien weitere Aspekte aufgeführt, die für die Speicherung von Daten relevant sind:

- Vermeiden proprietärer Datenformate [s. a. Datenformate](#5)
- 3-2-1-Regel: 3 Kopien, auf 2 Medien, mindestens 1 davon dezentral gespeichert
- Passwortverschlüsselung der Daten
- Sinnvolles und konsistentes Dateiablagesystem

  - In einer READ.me-Datei kann das System auf oberster Ebene erläutert werden; das ist gerade bei der Arbeit in geteilten Dateiablagesystem empfehlenswert

### Sichern vs. Archivieren

Speichern und Archivieren, dass kann im ersten Moment sehr ähnlich klingen, also wo liegt der Unterschied?

Sichern meint die Sicherung aller Daten (Backup) um Datenverlust vorzubeugen

Archivieren hingegen ist die Sicherung und **Langzeitarchivierung** ausgewählter, "endgültiger" Daten. Archivieren geschieht also zumeist erst nach dem Abschluss eines Forschungsprojektes, oder dem Abschluss eines eigenständigen Moduls in einem Projekt.

### Daten publizieren

Vorteile bei der Veröffentlichung von Forschungsdaten

- Es können neue Kooperationen weltweit entstehen.
- Forschungsergebnisse werden durch die Veröffentlichung von Daten und deren Zitierung sichtbarer.
- Öffentlich zugängliche Daten können zu neuen oder ergänzenden Hypothesen anregen.
- Wissenschaftliche Integrität wird gestärkt.
- Durch das Teilen von Daten wird eine offene Wissenschaftskultur befördert.
- Einmalige Daten gehe nicht verloren, sondern stehen für weitere Forschungen zur Verfügung.
- Kosten werden gespart.

### Daten zitieren

Öfter noch als das Veröffentlichen, begegnet einem im Forschungsalltag die Frage nach dem Zitieren von Daten!

Aber warum sollte man Daten zitieren?

- Richtiges Zitieren ist Teil guten wissenschaftlichen Arbeitens.

  * Auch Daten sollten gut und richtig zitiert werden.

Wie zitiere ich richtig?

- Grundsätzlich so zitieren, wie andere Publikationen zitiert werden.
- Genannt werden sollten also Autoren/Herausgeber, der Titel und das Veröffentlichungsdatum.
- Ergänzt wird dies bestenfalls um eine DOI, die direkt zum Datensatz führt!
- Ein Beispiel von forschungsdaten.info:

  * Autoren (Veröffentlichungsdatum): Titel, Publikationsagent, PID

### Repositorien – Die Daten-Speicher

- Repositorien sind Speicherorte für digitale Forschungsergebnisse und -daten
- Sie machen Daten für die Öffentlichkeit oder einen beschränkten Kreis an Nutzer:innen verfügbar.
- Es werden dauerhafter „Identifikatoren“ zur besseren Zitation und Auffindbarkeit der Daten vergeben
- Es wird zumeist zwischen generischen, fachspezifischen und institutionellen Repositorien unterschieden.
- Es gibt Siegel/Zertifikate für gute Langzeitarchive: CoreTrustSeal (CTS); nestor Siegel/DIN 31644; ISO 16363

---

Wo finde ich ein geeignetes Repositorium?

- Re3data
- DFG RIsources
- NFDI4Culture Repositorien-Überblick
- ... auch der NFDI4Culture Helpdesk hilft gerne weiter!

Kulturwissenschaftliche Repositorien – eine Auswahl

- DARIAH-DE – Digital Research Infrastructure for the Arts and Humanities
- CLARIN-D – Digitale Forschungsinfrastruktur für Sprachressourcen in den Geisteswissenschaften
- IANUS – Forschungsdatenzentrum Archäologie und Altertumswissenschaften
- TextGrid Repository – Langzeitarchiv für geisteswissenschaftliche Forschungsdaten
- RADAR4Culture

<font color=PURPLE> 🎬 Medienwissenschaft </font>

- media/rep/ <br>
🢡 Data Sets können beispielsweise über das Fachrepositorium media/rep/ publiziert werden, Data Papers im NECSUS Journal

<font color=GREEN> 🎵 Musikwissenschaft </font>
- musiconn.publish

### Persistent Identifier (PI)

- Persistent Identifiers sind Codes, die eine digitale Ressource eindeutig benennen.
- Sie dienen der besseren und nachhaltigeren Auffindbarkeit und helfen  „tote“ Links zu vermeiden

Beispiele

- Digital Object Identifier (DOI) 
  
  * für digitale Objekte (Artikel, Datensätze, …)
  * Verweist permanent auf den Datensatz, „haltbarer“ als URL und erhöht und verbessert dadurch Zitationen.
- Open Researcher and Contributer ID (ORCID) 
  
  * Personen ID
  * Erleichtert die Identifikation von Personen, präsentiert die wiss. Laufbahn, kann eigenhändig angelegt werden (Vor- und Nachteil).

### Langzeitarchivierung

- Archivieren meint meist ± 10 Jahre Speicherzeit
- Metadaten halten die archivierten Daten verständlich.
- Verwendete Software sollte mit archiviert oder zumindest sollte in den Metadaten verzeichnet werden, welche Software genutzt wurde.
- Möglichst keine proprietäre Software/Datenformate nutzen.

Nicht alle Forschungsdaten aus einem Projekt müssen archiviert werden.

- Einmal archivierte Daten werden nicht mehr verändert!
- Sollten Veränderungen vorgenommen werden, dann sollte eine neue Version der Daten gespeichert werden, die deutlich als solche gekennzeichnet ist.

### CC-Lizenzen

- CC-Lizenzen decken die meisten Nutzungsszenarien ab und liegen in zahlreichen Sprachen vor.
- CC-Lizenzen sind modular aufgebaut und bestehen aus folgenden Bestandteilen: 
  
  * BY: Namensnennung des Urhebers
  * NC: nicht kommerzieller Gebrauch
  * ND: nicht bearbeiten oder verändern
  * SA: Weitergabe unter selben Bedingungen
- Sie sind beliebig kombinierbar, solange sie sich nicht widersprechen.
- Mit CC0 / Public Domain werden alle Rechte am Werk abgegeben.
- CC-Lizenzen sind nur mit Link zur Lizenz-Ressource gültig.
- Einmal vergebene Lizenzen können nicht zurückgezogen oder verschärft werden!

#### Das CC-Lizenzen Quiz

Nicht jede CC-Lizenz-Kategorie ist mit jeder anderen kombinierbar. Testen Sie sich selbst und erkennen Sie auch unzulässige Lizenz-Kombinationen?

**Was erhählt man bei der Kombination von CC-BY und CC-BY-SA?**

- [[ ]] CC-BY
- [[x]] CC-BY-SA
- [[ ]] unzulässig
- [[ ]] anderes

---

**Was erhählt man bei der Kombination von CC-BY-SA und CC-BY-NC?**

- [[ ]] CC-BY-SA
- [[ ]] CC-BY-NC 
- [[ ]] CC-BY-NC-SA
- [[x]] unzulässig

---

Hinweis: Die Lösung ist unzulässig, da
<!--- Ja, warum eigentlich? --->
---

---

**Was erhählt man bei der Kombination von CC-BY und CC-BY-ND?**

- [[ ]] CC-BY
- [[ ]] CC BY-NA
- [[ ]] unzulässig
- [[ ]] andere

---

Hinweis: Die Lösung ist unzulässig, da
<!--- Ja, warum eigentlich? --->
---

## Der Datenmanagementplan (DMP)

> Ein DMP beschreibt den strukturierten Umgang mit Daten. Er bestimmt, wie mit Daten verfahren wird – während und nach dem Projekt – und sollte deshalb ein lebendes Dokument sein, dass sich Projekt anpassen und verändern darf

- Fördergeber können Vorgaben machen, aber ein DMP muss nicht grundsätzlich einem bestimmten Aufbau folgen.
- Der Forschungsdaten-Lebenszyklus kann als Orientierung dienen.
- Ein DMP verbessert die Nachnutzbarkeit von Daten und das Management von Daten und Wissen, etwa bei Personalwechseln.

Hilfe und Unterstützung:

- Die meisten Fördergeber bieten Checklisten zur Orientierung an.
- Zur Orientierung hilft es auch, sich DMPs anderer Projekte anzusehen.
  
  * z. B. auf Zenodo finden sich zahlreiche Beispiele
- Auch der NFDI4Culture Helpdesk hilft weiter.

Was macht einen guten DMP aus?

- DMPs sollten gut strukturiert sein ⇒ hier helfen Tools und Checklisten.
- „So kurz wie möglich, so lang wie nötig.“
- Alle Projektbeteiligte sollten den DMP kennen und Zugriff darauf haben.
- Idealerweise wird der DMP zu Projektende mit veröffentlicht.

> Wichtig: DMPs wachsen mit dem Projekt! Der DMP aus dem Projektantrag darf verändert werden, wenn sich Situationen während der Projektlaufzeit ändern oder auffällt, dass ursprünglich Geplantes so nicht umgesetzt werden kann.

### Das RDMO-Tool

RDMO, steht für Research Data Management Organiser und ist ein freies Open Source Tool für die Erstellung von Datenmanagementplänen

- Wie ist das Vorgehen und wie wird RDMO genutzt? 
  
  * Auswahl eines Fragenkatalogs
  * Schritt-für-Schritt-Abarbeiten der Fragen
  * Auswurf des „fertigen“ Plans in verschiedenen Dateiformaten
- Institutionen können RDMO-Instanzen einrichten, Funktionen und Design sind dabei individualisierbar.

Es gibt ein RDMO-Demo-Programm auf der RDMO-Website, dass jede:r Interessierte nutzen kann.

- Accounts können kostenlos erstellt werden
- Das "Demo" im Namen mag fehlleiten, es ist hat aber volle Funktionalität, nur keine individualisierten Funktionen, welche die Instanzen von Institutionen haben können

## Exkurs: Ökologisch nachhaltiges Datenmanagement
<!--- [KB] Ich schreib hier noch weiter --->
Dieser Exkurs wäre es wert, eine ganz eigene Lernressource zu werden, dennoch wollen wir in diesem kleinen Exkurs gerne auf Maßnahmen aufmerksam machen, die dabei helfen können, die Forschungsdaten nicht nur nachhaltig im Sinne von FAIR, sondern auch ökologisch nachhaltig zu managen.

## Weiterführende Literatur
**Dang 2020**<br>
Dang, Sarah-Mai: Forschungsdatenmanagement in der Filmwissenschaft. Daten, Praktiken und Erkenntnisprozesse. In: montage AV. Zeitschrift für Theorie und Geschichte audiovisueller Kommunikation, Jg. 29 (2020), Nr. 1, http://dx.doi.org/10.25969/mediarep/21687

**Goller, Heftberger 2018**<br>
Goller, Marion / Heftberger, Adelheid (2018) Die Öffnung von Forschungsdaten in den Film- und Medienwissenschaften: praktische und urheberrechtliche Herausforderungen. In: Fachinformationsdienst für internationale und interdisziplinäre Rechtsforschung, 2018, https://doi.org/10.17176/20180515-233758

**Kailus 2023**<br>
Kailus, Angela: Handreichung für ein FAIRes Management kulturwissenschaftlicher Forschungsdaten, 2023, https://nfdi4culture.de/go/E3625

## Zusatzmaterial: Interaktive Module
Dieses Kapitel stellt einige Übungen und Aktivierungsmethoden vor, die in der Lehre genutzt werden können und die vorliegende OER ergänzen.

### Übung zum Thema "Datenlebenszyklus"
<!--- [AP] Quelle: Methodensammlung für TA2-Glamkursreihe --->
- *Anregegung aus dem Train-the-Trainer von fdm.nrw*: Kurze Übung, max. 15. Min.: Auf einem Conceptboard "Überschriften" des DLZ verschieden farbig angeben und dazu ungeordnet auf weißen Post-Its Schlüsselbegriffe/Schlagwörter und Inhalte aus DMPs angeben. Die TN müssen dann die Begriffen mit den zugehörigen Überschriften verknüpfen. Wenn die TN mit der Auswahl sicher sind, dann können die Post-Its der Farbe der Überschrift angeglichen werden. Anschließend Ergebnisse im Plenum diskutieren. (nur bis zu einer best. Gruppengröße sinnvoll, ansonsten Kleingruppen, denn wenn alle TN einer Gruppe 20+ auf dem Conceptboard gleichzeitig Post-Its verschieben ist es mehr Chaos als Lerneffekt)

### Übung zum Thema "Kontrollierte Vokabulare" (GLAM-Fokus)
<!--- [AP] Quelle: Methodensammlung für TA2-Glamkursreihe --->
- Zu Beginn des Kurses als Aktivierung mit Mentimeter den Kenntnisstand der TN abfragen, bzgl. der in diesem WS besprochenen Themen. Z.B.: WordCloud mit der Frage: Welche kontrollierten Vokabulare werden an ihrer Einrichtung genutzt; oder (anonyme! das auch betonen bei Stellen der Frage) Abfrage mit der Ausgabe eines Balkendiagramms, z.B. zu der Frage: Wie gut ist die Qualität meiner Sammlungsdaten

### Rechercheaufgabe FDM-Policies (10 Min.)
<!--- [AP] Hier müsste man Alex fragen, ob es okay ist, dass wir unsere interaktiven Aufgaben aus dem FFK-Kurs veröffentlichen! --->

- Wenn man sich als frische/r Doktorand:in die Frage stellt, wie man mit seinen Forschungsdaten umgehen soll bzw. welche Regeln man befolgen muss, wird man bei der Suche schnell erschlagen von den vielen (häufig generischen) Antworten, die man dazu findet - bspw. die FAIR- und CARE-Prinzipien. Deshalb lohnt es sich, erstmal zu recherchieren, ob die Institution, bei der man angestellt ist, 1. eine eigene Beratungsstelle zum Umgang mit Forschungsdaten hat und 2. ob eure Institution vielleicht sogar schon eine eigene Forschungsdaten-Policy verabschiedet hat, an die ihr euch grundsätzlich halten müsstet. Und genau das wollen wir jetzt mal machen: 
- Hat Eure Universität eine eigene FD-Policy?
- Welche FD-Beratungsstellen gibt es an Euren Universitäten?

### Teilnehmer-Aktivierung
<!--- [AP] Quelle: Methodensammlung für TA2-Glamkursreihe --->
Zu Beginn des Kurses

* Erfahrung: Direkt zu Beginn möglichst die Teilnehmer aktiv mit einbeziehen, das hilft erfahrungsgemäß dabei, dass bei späteren aktiven Parts, Gruppenarbeit, etc. weniger Leute abspringen. (Also jenes Phänomen von Online-Veranstaltungen, dass wenn man aktive Mitarbeit der Teilnehmer:innen ankündigt, ein großer Block der TN das Meeting verlässt.)
* Erfahrung: Möglichst wenige Fragen auf einmal stellen, eher schrittweise die Fragen anführen, die man bei einem Aktiv-Teil den Teilnehmern stellen möchte
* Aus dem TtT: Zum Einstieg grafische Elemente verwenden, beispielsweise kann ein Ablaufplan des Kurses präsentiert werden und jede:r Teilnehmer:in darf ihre/seine Ideen zu und Erwartungen an den genannten Bereichen notieren und was ihnen noch fehlt (z.B. über die Live-Kommentar-Funktion von Zoom)


- Aus dem Train-the-Trainer: Wenn man Begriffe oder Ergebnisse von vorherigen Workshops abfragen oder rekapitulieren lassen möchte -> Wheel of Names (! Manchmal merkwürdige Werbung, Alternative ist uns, wenn vorhanden, gerade leider unbekannt)
- Aus dem Train-the-Trainer: (nur bei kleinen Gruppen zeit-technisch sinnvoll) Vorstellungsrunde mit Name, Einrichtung, Profession/Fach und einem "random fact"; wer eine Verbindung zu sich sieht hebt die Hand und ist dann als nächstes dran 
  * Notiz: Vorstellungsrunden lohnen bei großen Gruppen und bei kurzen Veranstaltungen von wenigen Stunden wenig. Ab 2-tägigen Veranstaltungen und bei moderater Gruppengröße können sie aber helfen, die Gruppe zu stärken und Hemmschwellen zu senken

### Tools für interaktive Online-Sessions
<!--- [AP] Quelle: Methodensammlung für TA2-Glamkursreihe --->

* Mentimeter (für Umfragen & WordCloud)
* Conceptboard/Miro (für Kleingruppenarbeit, Conceptboard datenschutzrechtlich besser)
* Wheel of Names (als Aktivierungsmethode: Unverfängliche Fragen eingeben, hier können die Teilnehmer:innenn das Rad drehen und Fragen beantworten (ist eine kommerziell betriebene Seite, die mit Werbebannern versehen ist)
  * kann auch fachspezifisch umgewidmet werden
* Tools können auch direkt in Zoom genutzt werden, wie etwa für Umfragen, als Kommentarfunktion, um ein häufiges Wechseln der Oberfläche geringzuhalten