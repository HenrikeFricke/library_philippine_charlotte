# library_philippine_charlotte

Datenset zur Erschließung der Privatbibliothek von Fürstin Philippine Charlotte von Braunschweig Lüneburg. Die Erschließung beruht auf zwei Bücherverzeichnissen aus dem 18. Jahrhundert. Die Da-ten umfassen die Volltextdaten, die um Normdaten angereicherten Daten sowie die Daten der Visua-lisierungen der Inhalte. Die Daten sind Teil einer Masterarbeit des Studiengangs "Digitales Datenma-nagement" der FH Potsdam, Alle Daten stehen unter CC BY Lizenz.

Kontakt zur Datenerstellerin Henrike Fricke-Steyer: henrike.fricke@gmail.com

------------------------------------------------------------------------------------------------------------------
Datenmanagementplan (DMP)

27.03.2022


Gliederung :
1. Allgemein	1
2. Inhaltliche Einordnung	1
3. Technische Einordnung	2
4. Datennutzung	4
5. Metadaten und Referenzierung	5
6. Rechtliche und ethische Fragen	6
7. Speicherung und Langzeitarchivierung	6



 
1. Allgemein

Kontakt zur Datenerstellerin Henrike Fricke-Steyer: henrike.fricke@gmail.com
1.1 Thema
1.1.1. Wie lautet die primäre Forschungsfrage der Abschlussarbeit?
Wie kann eine digitale Erschließung und –beforschung eines frühneuzeitlichen Bibliotheksverzeichnisses unter Verwendung bestehender digitaler Methoden und damit verbundener Tools erfolgen?
1.1.2. Bitte geben Sie einige Schlagwörter  zur Forschungsfrage bzw. Fragestellung an.
Bibliothekskatalog, Datenanalyse, Forschungsdatenmanagement, Fürstin, Bibliothek, Bestandserschließung, Philippine Charlotte <Braunschweig-Lüneburg, Herzogin>
1.2.3. Welchen Regeln oder Richtlinien (FHP, HUB) zum Umgang mit den in der Abschlussarbeit erhobenen Forschungsdaten folgen Sie für den DMP? Bitte referenzieren Sie diese hier inklusive Version bzw. Veröffentlichungsjahr.
- FAIR-Prinzipien, GO FAIR (2016) 
- CARE-Prinzipien für indigene Data Governance, Global Indigenous Data Alliance (2019)
- Leitlinie zum Umgang mit Forschungsdaten, FH Potsdam (2021)
- Kodex: Leitlinien zur Sicherung guter wissenschaftlicher Praxis, Deutschen Forschungsgemeinschaft (2019)
- Empfehlungen zur wissenschaftlichen Integrität, Wissenschaftsrats (2015) 

2. Inhaltliche Einordnung
2.1 Datensatz
2.1.1 Um welche Arten von Daten handelt es sich? Bitte in wenigen Zeilen kurz beschreiben.
Datensatz 1 = transkribus_pcb_praunscherkatalog_2023-02-20: Volltext- und Strukturdaten des Digitalisates des Praun’schen Katalogs

Datensatz 2 = primaerdaten_pcb_katalogende18jh_cc_by_vanessa_bieberstein_2023-01-27: Volltext- und Strukturdaten des Digitalisates des Kataloges Ende 18. Jah.

Datensatz 3 = sruantwort_pcb_manifestationsebene_2023-02-02: Bibliografische Daten Manifestationsebene, abgerufen an der SRU-K10Plus-Schnittstelle 

Datensatz 4 = sruantwort_pcb_exemplarebene_2023-02-02: Bibliografische Daten Exemplarebene, abgerufen an der SRU- K10Plus-Schnittstelle

Datensatz 5 = openrefine_pcb_sammlung_2023-02-20: Aus Datensatz 1-4 generiertes Datenset, bereinigt und zusätzlich angereichert via Openrefine, Verknüpfungen zu GND, TGN und Wikidata
Datensatz 6 = finalisiertesdatenset_pcb_sammlung_2023-02-20: Aus Datensatz 5 generiertes Datenset, bereinigt und zusätzlich mit Daten angereichert via Openrefine, Datensätze der gesamten Sammlung

Datensatz 6.1 = finalisiertesdatenset_pcb_sammlung_2023-02-20: Aus Datensatz 5 generiertes Datenset, bereinigt und zusätzlich mit Daten angereichert via Openrefine, eingeschränkt auf die Datensätze des Praun’schen Kataloges

Datensatz 6.2 = finalisiertesdatenset_pcb_praunscherkatalog_2023-02-20: Aus Datensatz 5 generiertes Datenset, eingeschränkt auf die Datensätze des Kataloges Ende des 18. Jh.

Datensatz 7 = geobrowser_pcb_sammlung_EAEA0-CF94-3610-CE92-0_2023-02-19: Orts- und Zeitdaten im Geobrowser

Datensatz 8 = libreto_pcb_praunscherkatalog_2023-02-25: Aus Datensatz erstelltes Importdatenset zur Weiterverarbeitung in LibReTo

2.2 Datenursprung
2.2.1 Werden die Daten selbst erzeugt oder nachgenutzt?
Datensatz 1: Die Volltextdaten des Praun’schen Kataloges wurden mit Hilfe von Transkribus erzeugt

Datensatz 2: Die Volltextdaten des Kataloges Ende des 18. Jh. wurden nachgenutzt

Datensatz 3,4: Die bibliographischen Daten wurden aus dem GVK abgerufen

Datensatz 5,6, 6.1,6.2,7,8: Aus Datensatz 1-4 generiertes Datenset

2.2.2 Wenn die Daten nachgenutzt werden, wer hat die Daten erzeugt? Bitte mit Angabe des Identifiers, falls vorhanden, z.B. DOI.
Datensatz 2: Die Daten des Kataloges Ende des 18. Jh. wurden im Rahmen folgender Bachelorarbeit erhoben: Bieberstein, Vanessa: Veränderung in der Aufstellung der privaten Bibliothek und Kaufverhalten der Herzogin Philippine Charlotte von Braunschweig-Lüneburg im Spiegel ihrer handschriftlichen Kataloge. Leipzig 2021. Schriftliche Einwilligung vorhanden, Daten lizenziert: CC BY.

2.3. Reproduzierbarkeit
2.3.1 Sind die Daten reproduzierbar, d. h. ließen sie sich, wenn sie verloren gingen, erneut erstellen oder erheben?
Ja, das gilt für alle Datensätze. 

2.4 Nachnutzung
2.4 Für welche Personen, Gruppen oder Institutionen könnte dieser Datensatz (für die
Nachnutzung) von Interesse sein? Für welche Szenarien ist dies denkbar?
Der Datensatz ist insbesondere für Forscher*innen der Geistes- und Kulturwissenschaften von Interesse, bspw. Sammlungsforschung, Provenienzforschung, Bücherverzeichnisse in der Frühen- Neuzeit sowie Bildungsforschung, Buchwissenschaft.

3. Technische Einordnung
3.1 Datenerhebung
3.1.1 Wann erfolgt(e) die Erhebung bzw. Erstellung der Daten?
Datensatz 2: 2021

Datensatz 1,3,4,5,6,6.1,6.2,7: Oktober 2022 – Februar 2023

3.1.2 Wann erfolgt(e) die Datenbereinigung / -aufbereitung bzw. Datenanalyse?
Datensatz 5,6,6.1,6.2,7, 8: Januar– Februar 2023

3.1 Datengröße
3.1.1 Was ist die tatsächliche oder erwartete Größe der Daten(typen)?
Datensatz 1: DOCX 323 KB, TXT 166 KB, XML 3826 KB
Datensatz 2: DOCX 557 KB, XLSX 148 KB
Datensatz 3: CSV 354 KB
Datensatz 4: CSV 232 KB
Datensatz 5: CSV 1280; XLSX 858 KB HTML 2655 KB
Datensatz 6: CSV 1260 KB, XLSX 1718 KB
Datensatz 6.1: CSV 896 KB
Datensatz 6.2: CSV 1018 KB
Datensatz 7: CSV  416 KB, KML 685 KB
Datensatz 8: CSV 536 KB

3.2 Formate
3.2.1 In welchen Formaten  liegen die Daten vor?
Datensatz 1: DOCX, TXT, XML
Datensatz 2: DOCX, XLSX
Datensatz 3: CSV
Datensatz 4: CSV
Datensatz 5: CSV, XLSX, HTML
Datensatz 6: CSV, XLSX
Datensatz 6.1: CSV
Datensatz 6.2: CSV
Datensatz 7: CSV, KML
Datensatz 8: CSV

3.3 Werkzeuge
3.3.1 Welche Instrumente, Software, Technologien oder Verfahren werden zur Erzeugung, Erfassung, Bereinigung, Analyse und/oder Visualisierung der Daten genutzt? Bitte (falls möglich) mit Versionsnummer und Referenz in Form einer Adresse jeweils angeben.
Datensatz 1: Transkribus Expert Client, Version v1.19.3, https://readcoop.eu/de/transkribus/; Microsoft Excel, Version 2016
Datensatz 2: Microsoft Word und Excel, Version 2016
Datensatz 3: Jupyter Notebook 6.3.0 (anaconda3); SRU-Schnittstellenabruf: http://sru.k10plus.de/opac-de-627?version=1.1; Microsoft Excel, Version 2016
Datensatz 4: Jupyter Notebook 6.3.0 (anaconda3); SRU-Schnittstellenabruf: http://sru.k10plus.de/opac-de-23?version=1.1; Microsoft Excel, Version 2016
Datensatz 5: OpenRefine, Version 3.6.2., https://openrefine.org/; Microsoft Excel, Version 2016
Datensatz 6, 6.1, 6.2: Microsoft Excel, Version 2016
Datensatz 7: DARIAH-DE-Geobrowser, Version 4.0.19, https://geobrowser.de.dariah.eu; Microsoft Excel, Version 2016
Datensatz 8: LibReTo, https://github.com/hbeyer/libreto-transform und https://bibliotheksrekonstruktion.hab.de/; Microsoft Excel, Version 2016

3.3.2 Welche Software, Verfahren oder Technologien sind notwendig, um die Daten zu nutzen?
Datensatz 1: Transkribus Expert Client; Tabellenkalkulationsprogramm, z.B. Microsoft Excel oder OpenOffice Calc
Datensatz 2,3,4,5,6,6.1,6.2: Tabellenkalkulationsprogramm, z.B. Microsoft Excel oder OpenOffice Calc
Datensatz 7: Geodatenverarbeitendes-Kartenprogramm, z.B. DARIAH-DE-Geobrowser oder Google Earth, Tabellenkalkulationsprogramm, z.B. Microsoft Excel oder OpenOffice Calc
Datensatz 8: LibReTo, Tabellenkalkulationsprogramm, z.B. Microsoft Excel oder OpenOffice Calc

3.4 Versionierung
3.4.1 Werden verschiedene Versionen der Daten erzeugt (z. B. durch verschiedene Weiterberabeitungsprozesse bzw. Bereinigung von Daten)?
Ja, daher Datensätze 1-8. Versionen der einzelnen Datensätze 1-8 sind bisher nicht vorhanden.

4. Datennutzung
4.1 Datenorganisation
4.1.1 Gibt es eine Strategie zur Benennung der Daten? Wenn ja, bitte skizzieren Sie sie kurz.
Ja: verwendung_pcb_kurztitel_erstellungsdatum.format

4.2 Datenspeicherung und -sicherheit
4.2.1 Wer darf (zukünftig) auf die Daten zugreifen?
Alle Interessierten. Die Daten werden unter Creative Commons — Namensnennung 2.0 (CC BY) lizenziert.
4.2.2 Wie und wie oft werden Backups der Daten erstellt? 
Bei jeder neuen Version der Datensätze wurde ein Backup gemacht und lokal sowie in der FHP-Cloud gesichert.


4.3 Interoperabilität
4.3.1 Sind die Datenformate im Sinne der FAIR-Prinzipien interoperabel, d.h. geeignet für den Datenaustausch und die Nachnutzung zwischen bzw. von unterschiedlichen Forschenden, Institutionen, Organisationen und Ländern?
Ja.
4.4 Weitergabe und Veröffentlichung
4.4.1 Ist es geplant, die Daten nach Abgabe der Abschlussarbeit zu veröffentlichen oder zu teilen?
Ja.
4.4.2 Wenn nicht, skizzieren Sie kurz rechtliche und/oder vertragliche Gründe und freiwillige Einschränkungen.
Trifft nicht zu.
4.4.3 Wenn ja, unter welchen Nutzungsbedingungen oder welcher Lizenz sollen die Daten veröffentlicht bzw. geteilt werden?
Creative Commons — Namensnennung 2.0 (CC BY). Diese Lizenz erlaubt Dritten, ein Werk zu verbreiten, zu remixen, zu verbessern und darauf aufzubauen, auch kommerziell, solange der Urheber des Originals genannt wird. 

4.5 Qualitätssicherung
4.5.1 Welche Maßnahmen zur Qualitätssicherung (z. B. Plausibilitätsprüfung von Datenwerten) werden für die Daten ergriffen?
Abgleich der Daten über Normdaten: PPN, GND, TGN. Plausibilitätsprüfung über Visualisierungen. Stichprobenüberprüfungen durch Expert*innen.

4.6 Datenintegration
4.6.1 Falls Daten aus verschiedenen Quellen (z. B. Anpassung Skalierung, Zeiträume, Ortsangaben) integriert werden, wie wird dies gewährleistet?
Offene Standardisierte Schnittstellen (SRU, OAI-PMH) ausschließliche Nutzung von persistent-adressierbaren Quellen, ausschließliche Nutzung von nichtkommerziellen Quellen.

5. Metadaten und Referenzierung
5.1 Metadaten
5.1.1 Welche Informationen sind für Außenstehende notwendig, um die Daten zu verstehen (d. h. ihre Erhebung bzw. Entstehung, Analyse sowie die auf ihrer Basis gewonnenen Forschungsergebnisse nachvollziehen) und nachnutzen zu können?
Der Forschungsdatenmanagementplan, Kurzbeschreibung auf GitHub (readme-Dateien).
5.1.2 Welche Standards, Ontologien, Klassifikationen etc. werden zur Beschreibung der Daten und Kontextinformation genutzt?
Abgleich der Daten über Normdatenstandards: PPN, GND, TGN. Ontologie: LibReTo.

6. Rechtliche und ethische Fragen
6.1 Personenbezogene Daten
6.1.1 Enthalten die Daten personenbezogene Informationen?
Ja, ausschließlich von historischen Personen.
6.2 Sensible Daten
6.2.1 Enthalten die Daten "Angaben über die rassische und ethnische Herkunft, politische Meinungen, religiöse oder philosophische Überzeugungen, Gewerkschaftszugehörigkeit, Gesundheit oder Sexualleben" (BDSG §3, Abs.9 )?
Trifft nicht zu.
6.2.2 Werden die Daten anonymisiert oder pseudonymisiert?
Trifft nicht zu.
6.2.3 Haben Sie eine "informierte Einwilligung" der Betroffenen eingeholt? Fügen Sie bitte ein Template -der Einverständniserklärung als Anlage bei.
Trifft nicht zu.
6.2.4 Wenn keine "informierte Einwilligung" eingeholt wird, begründen Sie dies bitte.
Trifft nicht zu.
6.2.5 Wo und wie sind die "informierten Einwilligungen" abgelegt?
Trifft nicht zu.
6.2.6 Bis wann werden die (unanonymisierten bzw. unpseudonymisierten) Originaldaten spätestens sicher vernichtet?
Trifft nicht zu.

6.3 Urheber- oder verwandte Schutzrechte
6.3.1 Werden Daten genutzt und/oder erstellt, die durch Urheber- oder verwandte Schutzrechte geschützt sind?
Trifft nicht zu.

7. Speicherung und Langzeitarchivierung
7.1 Wo werden die Daten (einschließlich Metadaten, Dokumentation und ggf. relevantem Code bzw. relevanter Software) während Phase der Erarbeitung der Abschlussarbeit gespeichert?
Lokale Speicherung auf Festplatte, Speicherung in der FHP-Cloud, Speicherung auf externen USB-Stick.
7.2 Wo werden die Daten (einschließlich Metadaten, Dokumentation und ggf. relevantem Code bzw. relevanter Software) nach dem Ende der Abschlussarbeit gespeichert bzw. archiviert ?
Speicherung und Publikation auf: 
- FHP-Cloud https://fhpcloud.fh-potsdam.de/s/BoDWp7nty6x4tHS 
- GitHub https://github.com/HenrikeFricke/library_philippine_charlotte
- Zenodo https://doi.org/10.5281/zenodo.7657319
7.3 Handelt es sich dabei um ein zertifiziertes Repositorium oder Datenzentrum (z.B. durch das CoreTrustSeal , nestor-Siegel  oder ISO 16363 )? (Wurden mehrere Langzeitarchivierungsoptionen ausgewählt, kann die Frage bejaht werden, wenn dies auf mindestens eine der Optionen zutrifft).
Trifft nicht zu.
