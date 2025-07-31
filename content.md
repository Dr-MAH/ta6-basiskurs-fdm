<!--
link : ./resources/oer-design_GL.css
icon : ./resources/icon_4Culture.png
version: 0.5
author: Martin Albrecht-Hohmaier, Katharina Bergmann, Vincent Fröhlich, Alexander Stark, Andrea Polywka
narrator: Deutsch female
comment: Dieser Kurs ist eine Open Educational Resource der NFDI4Culture Arbeitsgruppe Cultural Research Data Academy (CRDA). Gefördert durch die Deutsche Forschungsgemeinschaft (DFG),Projektnummer: 441958017.
-->

# Basiskurs Forschungsdatenmanangement für Geistes- und Kulturwissenschaften

Eine Open Educational Resource der NFDI4Culture Arbeitsgruppe [Cultural Research Data Academy (CRDA)](https://nfdi4culture.de/id/E1826)

<img src= "../resources/NFDI4C_Logo_DyptichText.png" width=50% height=70%>

Gefördert durch die Deutsche Forschungsgemeinschaft (DFG).<br>
Projektnummer: 441958017

---

Wir freuen uns, wenn unsere Materialien nachgenutzt werden, deshalb steht dieser Kurs unter einer Lizenz, die die Nachnutzung ermöglicht: <!--- Hier Lizenz einfügen --->

## Welche Inhalte bietet dieser Kurs?

 1. Der Forschungsdatenbegriff
 2. Forschungsdatenmanagement
 3. Der Datenlebenszyklus
 4. FAIR Principles
 5. CARE Principles
 6. Metadaten
 7. Normdaten und kontrollierte Vokabulare
 8. Sichern und Speichern
 9. Lizenzen
10. Datenmanagement-Pläne

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
<sub>(aus den Leitlinien zum Umgang mit Forschungsdaten  der Deutsche Forschungsgemeinschaft, 2023)</sub>

---

Wir haben unser Verständnis in diesem knappen Merksatz zusammengefasst:

> Daten werden zu Forschungsdaten, wenn sie wissenschaftlichen Richtlinien entsprechend erfasst, beschrieben, kontextualisiert oder kommentiert werden.

## Datenformate
Daten sollten möglichst nie in proprietären Datenformaten vorliegen. <br>


<!---
Evtl. Quiz zu Datenformaten, [AP] Vielleicht können wir die Angaben aus der FAIR-Bibel nehmen? Habe einfach mal den Textabschnitt reinkopiert:
--->

**Empfehlungen für Dateiformate (aus Kailus, Angela: Handreichung für ein FAIRes Management kulturwissenschaftlicher Forschungsdaten, 2023)**

Verwenden Sie möglichst weit verbreitete und mit einem ISO-Standard verbundene Dateiformate. Sie sollten nicht proprietär, also nicht an eine Software oder einen Hersteller gebunden, mit unterschiedlichen Programmen verwendbar und mit einer offenen Lizenz versehen sein und über eine frei zugängliche Dokumentation einschließlich der technischen Spezifikationen verfügen. Sie erlauben eine verlustfreie Speicherung ohne Kompression und sie sind einfach dekodierbar oder unmittelbar lesbar.
Konsultieren Sie Ihre Datenplattform, welche Dateiformate dort entgegengenommen bzw. empfohlen werden.

Für die Kulturwissenschaften und für Kulturerbe-Sammlungen empfehlen wir die Verwendung folgender Standard-Dateiformate:<br>

Text

    Extensible Markup Language (XML) 1.1, mit XML Schema Definition (XSD)
    Resource Description Framework in Attributes (RFDa) für das Einbetten von RDF-Statements in XML
    JavaScript Object Notation (JSON)
    JavaScript Object Notation for Linked Data (JSON LD)
    Comma-Separated Values (CSV)
    Textdatei (TXT) (Codierung UTF-8)
    Präsentationsformat: Portable Document Format A (PDF-A)

Musik

    Music Encoding Initiative (MEI)
    MusicXML
    Parsons Code
    Präsentationsformat: Portable Document Format A (PDF-A)

Bild (Rastergrafiken)

    Rohdaten: Digital Negative (DNG)
    Master: baseline Tagged Image File Format (TIFF), unkomprimiert; TIFF mit Lempel-Ziv-Welch-Komprimierung (TIFF-LZW)
    Joint Photographic Experts Group (JPEG 1 und JPEG 2000), verlustfrei komprimiert, lizenzfreie Bereiche
    Präsentationsformate (Derivate): JPEG, JPEG 2000, Portable Network Graphics (PNG)

Bild (Vektorgrafiken) und CAD

    Scalable Vector Graphics (SVG)

Audio

    Archivformat: Waveform Audio File-Format (WAV) in Verbindung mit Pulse Code Modulation (PCM); Free Lossless Audio Codec (FLAC)
    Präsentationsformat: MPEG-2 Audiolayer III (MP3)

Video/Film

    Archivformate:
        Moving Picture Experts Group Motion JPEG 2000 (MJPEG2000)
        Moving Picture Experts Group, Standard MPEG-4
        Digital Picture Exchange (DPX), SMPTE 268M-2003, v 2.0
        Material Exchange Format (MXF), SMPTE 377M
        Codec FFV1 / Container MKV
        TIFF mit FFV1 in Matroshka codiert
    Präsentationsformat: MP4 (MPEG-4, part 14)
    weitere Empfehlungen der nestor AG Media

etc.

#### <font color=#8B0000> 🎨 Forschungsdaten in der Kunstgeschichte </font>
Kunsthistorische Forschungsdaten sind, wie das Fach selbst, sehr divers. <br>
Sie umfassen unter anderem:

- Bilder: Fotografien, Scans
- Audiovisuelle Daten: Videos
- Textdaten: Texte, Notizen
- Bild- oder Video-Annotationen
- Tabellen

---


#### <font color=PURPLE> 🎬 Forschungsdaten in der Medienwissenschaft </font>
<!---
Ich habe das irgendwie nicht hinbekommen mit dem Fußnoten -.-'
Kein Ding, KB regelt!
---> 
Medienwissenschaftliche Forschungsdaten zeichnen sich durch sehr heterogene Materialien aus. Darunter zählen „alle schriftlichen und bildlichen Aufzeichnungen sowie Material- und Quellensammlungen", mitunter auch Koppelungen von "fremden und eigenen Daten, d.h. von Originalquellen und eigenen Annotationen, Zeichnungen o.ä."<sup>1</sup>

Digitalisierte Filme, einzelne Videoausschnitte, filmografische Metadaten, Sequenzprotokolle, Annotationen, Informationen zur Dokumentation des Analyseverfahrens (Ausführungen zum theoretischen Hintergrund, Bibliografie der verwendeten Forschungsliteratur, Nennung der Beteiligten), Reflexion der ausgewählten Kategorien, Hinweise zu den verwendeten Softwareprogrammen)."<sup>2</sup>

---
<p style="text-color:LightGray">
1: Goller, Marion; Heftberger, Adelheid (2018) Die Öffnung von Forschungsdaten in den Film- und Medienwissenschaften: praktische und urheberrechtliche Herausforderungen. In: Fachinformationsdienst für internationale und interdisziplinäre Rechtsforschung, 16. Mai 2018 https://doi.org/10.17176/20180515-233758, hier S. 1. <br>

2: Dang, Sarah-Mai: Forschungsdatenmanagement in der Filmwissenschaft. Daten, Praktiken und Erkenntnisprozesse. In: montage AV. Zeitschrift für Theorie und Geschichte audiovisueller Kommunikation, Jg. 29 (2020), Nr. 1, S. 119-140. DOI: http://dx.doi.org/10.25969/mediarep/21687, hier S. 121.
</p>

#### <font color=GREEN> 🎵 Forschungsdaten in der Musikwissenschaft </font>

### Exkurs: Video- und Bildannotation

Video- und Bildannotationstools sind lokale oder webbasierte Anwendungen für die Annotationen, d. h. Markierung und Kommentierung (audio-)visueller Inhalte. <br>
Einige dieser Tools lassen manuelle oder (semi-)automatische Annotation von Bild und Ton zu. <br>

---

Nutzungsszenarien von Videoannotationstools:

- Identifikation von Objekten, Personen oder Ereignissen
- Zeitbezogene Analyse von Bild und Ton
- Qualitative oder quantitative Datenanalyse
- Visualisierung von Annotationen

Annotationstools für AV-Material (Auswahl):

- ELAN (Eudico Linguistik Annotator)
- EXMARaLDA: annotation and transcription for oral corpora
- VIAN (Visual Video Annotation and Analysis)
- Advene (Annotate Digital Video, Exchange on the Net)

---

Nutzungsszenarien von Bildannotationstools:

Annotationstools Bild (Auswahl):

- mirador

## Forschungsdatenmanagement

<!---
Hier muss noch mehr hin. Etwas wenig Inhalt bisher. [AP] Ich füge mal ein paar Stichpunkte aus unserem Skript vom letzten FFK-Kurs bei
---> 
Forschungsdatenamangement (FDM) umfasst alle Aktivitäten im Zusammenhang mit ...

- der Aufbereitung,
- Speicherung,
- Archivierung,
- und Nutzung

... von Forschungsdaten.

FDM begleitet den gesamten Forschungsprozess und professionell standardisierte FDM-Prozesse verringern den zukünftigen Aufwand bei einer eigenen oder fremden Nachnutzung der Daten.

Das Risiko eines Datenverlusts wird durch FDM-Maßnahmen wie Datendokumentation, Datensicherung und eine geeignete Langzeitarchivierung (LZA) gering gehalten. Daten können so noch nach Jahrzehnten genutzt werden.

Gerade die vielseitigen technischen Möglichkeiten erfordern allerdings eine erhöhte Beachtung der Themen Datenschutz und Urheberrecht

Ebenso sollten rechtliche und ethische Aspekte beachtet werden, um die gute wissenschaftliche Praxis zu wahren, wie Alex soeben genauer erläutert hat.



### Forschungsdatenmanagement – Aber wieso?

- Der Umgang mit Forschungsdaten ist Teil guter wissenschaftlicher Arbeit.

> Kodex [„Leitlinien zur Sicherung guter wissenschaftlicher Praxis“](https://www.dfg.de/de/grundlagen-themen/grundlagen-und-prinzipien-der-foerderung/gwp) der DFG

- Fördermittelgeber erwarten einen strukturierten Umgang mit Forschungsdaten

  * häufig gefordert oder gewünscht ist hier ein Datenmanagementplan (DMP).

### Der Datenlebenszyklus I

<img src="../resources/FD_LZ.jpg" width=50% height=auto>
<p>
<sub> Graphische Darstellung eines DLZ, Creator: CRDA, CC0 </sub>
</p>

### Der Datenlebenszyklus II

<!---
Bei den Stationen kann gerne weiter ergänzt werden! [AP] Habe ein paar Beispiele ergänzt
--->

- Der Datenlebenszyklus (DLZ) beschreibt den "Lebenskreislauf" von Forschungsdaten
- Er kann dabei, ausgehend von seinem Detailgrad und der Art der Daten, leicht von dem hier angegebenen abweichen
- Stationen:

  1. Forschungsvorhaben planen 
  * Ein erster Datenmanagementplan wird erstellt
  2. Daten erheben
  * Unbereinigten Daten, die während der Forschungsarbeit entstehen
  3. Daten aufbereiten und analysieren
  * Bereinigte Daten
  * Analysen und Datenaufbereitungen (z.B. Digitalisierungs-, Transkriptions-, und Annotationsprozesse; Datenanalyse: Metadaten))
  4. Daten teilen und publizieren
  * Datenpublikation während oder nach dem Forschungsvorhaben (z.B. über Open Access-Plattformen)
  5. Daten archivieren
  * Archivierung ausgewählter Daten
  6. Daten nachnutzen
  * Eigene oder fremde Nachnutzung der veröffentlichten Datens (z.B. Datenablage anhand von Repositorien)

## FAIR und CARE
Die Akronyme FAIR und CARE werden gerne in einem Atemzug genutzt, es ist aber wichtig ihre sehr unterschiedlichen Anwendungsbereiche und Entstehungskontexte zu betrachten!

<!---
hier Erklärung/Erläuterung einfügen
--->

### Die FAIR Principles I

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

### Die FAIR Principles II

- FAIR steht für findable, accesssible, interoparable und reusable; übersetzt also für: auffindbar, zugreifbar, interoperabel und nachnutzbar.
- Wurden entwickelt um Datenproduzent:innen und -herausgeber:innen im Umgang mit Forschungsdaten zu unterstützen
- Betreffen nicht nur die Daten an sich, sondern auch die benuzten Algorithmen, Tools und Workflows
- Helfen dabei die FD für eine möglichst optimale Nachnutzung aufzubereiten
- Es gibt verschiedene Leitfäden die bei der Anwendung der Prinzipien Helfen 
  
  * NFDI4Culture FAIR-Check

### CARE Principles

Die CARE-Prinzipien wurden 2019 von der Global Indigenous Data Alliance als Ergänzung zu den FAIR-Prinzipien erarbeitet, um die Beteiligung indigener Gruppen an Entscheidungsprozessen zu stärken. Es geht um koloniale Kontexte und daraus resultierende ungleiche Machtverhältnisse.

Die Prinzipien sind für jene Forschenden relevant und sollten von ihnen in jedem Fall beachtet werden, die ethnologisch Forschen oder mit Daten aus kolonialen Kontexten beschäftigen.

CARE steht für Collective Benefit, Authority of Control, Responsibility und Ethics. Übersetzt also: Kollektiver Nutzen, Kontrollbefugnisse, Verantwortung und Ethik

- Kooperationen mit Ursprungscommunities u. a. 

  * gemeinsame Bearbeitung von Objekten
  * gleichberechtigten Zugang zu den Daten ermöglichen
  * indigene Ethik einbeziehen
- eigenes Handeln und Darstellung von Objekten/Forschungsgegenständen regelmäßig hinterfragen
- wenn nötig, öffentlichen Zugang zu Daten einschränken
- kulturelle Metadaten, z. B. Bezeichnungen aus Herkunftskontexten; Provenienzangaben in den Metadaten; Auswahl der Metadaten transparent machen
- Nutzung von Disclaimern
- Nutzung von Notices, dass indigene Daten verwaltet werden
- Nutzung von Traditional Knowledge Labels (z. B. Kennzeichnung als weibliches Wissen, sakralen Kontext etc.)

### Kultur- und Geisteswissenschaftliche Anwendungsfälle der CARE Principles
In ethnologisch forschenden Bereichen, etwa der Musikethnologie, sind die CARE Prinzipien eine wichtige Leitlinie beim Umgang mit ihren Forschungsdaten. <br>
Folgend seien einige Anwendungsfälle aufgezeigt, die den Nutzen der CARE Prinzipien illustrieren:

<!--- Hier noch ergänzen: Bisher das Material von Andrea und Alex aus dem FFK-Kurs --->
- (Forschungs-)Daten zu Filmmaterial aus kolonialen Kontexten

  - bspw. Amateurfilme, wissenschaftliche Filme, Travelogues, „Kulturfilme“
- (Forschungs-)Daten zu Tonmaterial aus kolonialen Kontexten
  
  - bspw. Phonographenwalzen aus Wachs aus ethnologischen Forschungskontexten, u. a. auch aus Kriegsgefangenenlagern des Ersten Weltkriegs
- (Forschungs-)Daten zu geraubten Kulturgütern aus kolonialen Kontexten

  - bspw. 3D-Digitalisate von geraubten Objekten

## Metadaten

> Merksatz: "Metadaten sind Daten, die andere Daten beschreiben"

Metadaten können in verschiedene Kategorien unterteilt werden.
Eine übliche Aufteilung ist:

- deskriptive Metadaten enthalten beschreibende Informationen über den Inhalt des Objekts, sie dienen der Identifizierung von Objekten oder Daten
- administrative Metadaten enthalten Informationen zum Objekt, die über seinen Inhalt hinausgehen wie z. B. Rechteinformationen und Details des analogen Objekts
- strukturelle Metadaten beschreiben den Metadatensatz an sich und seine Beziehung zur digitalen Datei
- technische Metadaten beschreiben die technischen Eigenschaften einer digitalen Datei Ergänzt werden kann diese Liste durch
- Archivmetadaten, die noch einmal spezieller zusammengestellte Informationen enthalten, die für die Archivierung relevant sind

<img src= "../resources/Metadaten.png" width=50% height=70%> <br>
<sub>Andrea Polywka, Alexander Stark: Metadaten Schaubild</sub>

### Metadaten – warum?

- Alle Arten von Forschungsdaten sollten stets mit Metadaten versehen werden
- Metadaten halten Daten verständlich und machen sie leichter auffindbar, da sie 
  
  * weiterführende, maschinenlesbare Informationen zu den Daten bereitstellen
  * und Datensätze untereinander in Beziehung setzen.
- Metadaten sollten gesondert als Metadatenpublikation veröffentlicht werden, um auch unabhängig von dem betreffenden Datum abrufbar zu sein.

### Metadaten Standards
Dies sind einige fachübergreifende Standards:

- Dublin Core
- EXIF (Bildmetadaten)
- PREMIS
- METS MODS

Für alle Metadaten gilt, dass sie strukturiert erfasst sein sollten und den Standards des jeweiligen Fachs entsprechen

- hier gibt es mehr fachspezifische denn medienspezifische Standards. Warum? 
  
  * Einzelne Fächer stellen unterschiedliche Fragen an dieselben Medien und arbeiten anders mit ihnen

#### <font color=PURPLE> 🎬 Metadatenstandards der Medienwissenschaft </font>
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

- zum vereinfachen die Darstellung komplexer Zusammenhänge
- zur Vermeidung von Mehrdeutigkeiten und falschen Zuordnungen vor allem für Maschinen, die anders als Menschen nicht aus dem Kontext schließen können
- Die Verwendung von Normdaten ermöglicht besseren Austausch und bessere Nachnutzbarkeit der Daten.

Ein kontrolliertes Vokabular ist eine Sammlung von Normdaten, es verknüpft auch Synonyme, die zum selben Suchergebnis führen und Übersetzungen in andere Sprachen.

> Video-Tipp: NFDI4Culture Video-Tutorial zu Normdaten! https://av.tib.eu/media/60986
<div style="position: relative; width: 100%; aspect-ratio: 16 / 9;">
  <iframe src="https://av.tib.eu/player/60986" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe>
</div>

### Kontrollierte Vokabulare

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

- Vermeiden proprietärer Datenformate
- 3-2-1-Regel: 3 Kopien, auf 2 Medien, mindestens 1 davon dezentral gespeichert
- Passwortverschlüsselung der Daten
- sinnvolles und konsistentes Dateiablagesystem in einer READ.me-Datei kann das System auf oberster Ebene erläutert werden

### Sichern oder Archivieren – Wo liegt der Unterschied?

Sichern:

- Sicherung aller Daten (Backup) um Datenverlust vorzubeugen
Archivieren:

- Sicherung ausgewählter Daten, Langzeitspeicherung „endgültiger“ Daten

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

---
## Interaktive Module

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