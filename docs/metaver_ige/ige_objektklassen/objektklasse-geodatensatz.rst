
Geodatensatz
============

Die Objektklasse Geodatensatz dient der Beschreibung von Daten mit direktem oder indirektem Raumbezug (digital oder analog). Beispiele: GIS-Daten, analoge Karten oder Kartenwerke

Werden die beschriebenen Daten über einen Webdienst (z.B. OGC Web-Mapping-Service (WMS)) bereitgestellt, sollte auf diesen Dienst, welcher als eigenes Objekt des Typs „Geodatendienst“ beschrieben ist, verwiesen werden (siehe Daten-Dienste-Kopplung).

Alle im Rahmen von INSPIRE zu erfassenden Geodaten müssen auch als Objektklasse „Geodatensatz“ angelegt werden.

Beispiele:

 - INSPIRE ST Geografische Bezeichnungen ATKIS Basis-DLM

 - INSPIRE ST Gewässernetz - Gewässerkundlicher Landesdienst

 - INSPIRE ST Umweltüberwachung - Gewässerkundlicher Landesdienst



Erfassung
---------


Nach dem Anlegen eines neuen Objektes stehen die Eingabefelder für das neue Objekt im rechten Inhaltsfenster zur Verfügung. Als erster Schritt sollten die Basisinformationen im Inhaltsfenster (siehe Screenshot) bearbeitet werden.

Objektname
Hier erfolgt die Angabe einer kurzen prägnanten Bezeichnung des beschriebenen Datensatzes. Der Objektname kann z.B. identisch mit dem Namen des Geodatendienstes sein, sofern dieser ausreichend kurz und aussagekräftig ist. Soweit ein gängiges Kürzel vorhanden ist, ist dieses Kürzel mit anzugeben. Der Eintrag für dieses Feld ist zwingend.

Beispiel: Digitales Landschaftsmodell 50 (DLM50)


Objektklasse
Je nachdem, welche Objektklasse bei der Erstellung des Metadatensatzes im Assistenten gewählt wurde, so werden im Inhaltsbereich entsprechende Eingabefelder angezeigt.

Hinweis:
Ein Wechsel der Objektklasse ist an dieser Stelle nicht mehr möglich.


Verantwortlicher
Hier ist standardmäßig der Erfasser eingetragen, der das Objekt angelegt hat (z.B. Max Mustermann). An dieser Stelle sollte die Person stehen, die sich für dieses Objekt verantwortlich fühlt und dafür sorgt, dass das Objekt aktuell gehalten wird. Meistens ist daher der Erfasser zugleich auch der richtige Verantwortliche. (Nähere Informationen zur Qualitätssicherung finden Sie unter der Rubrik Metadaten im Leitfaden der GDI-LSA "Qualitativ hochwertige Metadaten erfassen und pflegen – Hinweise für Metadatenerfasser" bzw. in der „Anleitung für die Erfassung von Metadaten“). 

Hinweis:
Wird bei eingeschalteter Qualitätssicherung das Verfallsdatum eines Objektes erreicht, so erhält der Verantwortliche eine E-Mail Benachrichtigung mit der Bitte, dieses Objekt zu aktualisieren.

Nach der Eingabe der Basisinformationen im Kopfbereich bietet es sich an, den Metadatensatz zwischen zu speichern. Grundsätzlich empfiehlt es sich, beim Ausfüllen der Felder von Zeit zu Zeit die eingegebenen Daten zu sichern, um beispielsweise bei einer abgelaufenen Session (Sitzung) die eingegeben Daten nicht zu verlieren. Das Zwischenspeichern ist jederzeit möglich, auch wenn noch nicht alle Pflichtfelder ausgefüllt sind.

Unter den ersten drei Eingabefeldern im Kopf werden automatisiert weitere Informationen zum Objekt angezeigt.

Erstellt am: Erstellungsdatum
Geändert am: Änderungsdatum
Objekt-ID: Die Objekt-ID wird nach dem ersten Speichern automatisch vergeben.
Von: Max Mustermann (Bearbeiter)

Hinweis:
Die Objekt-ID erscheint im Frontend-Metadatensatz in der Rubrik „Zusätzliche Info“, 
sie ist nicht zu verwechseln mit dem Identifikator der Datenquelle!


1.2	Abschnitt Allgemeines

Kurzbezeichnung
Angabe einer Abkürzung (Kurzbezeichnung) für den zu beschreibenden Geodatensatz.

Beispiele: FND (steht für: Flächennaturdenkmale), DTK25 (steht für: Digitale Topographische Karte im Maßstab 1: 25.000)


Vorschaugrafik
In dieses Feld kann eine WMS-Dienst URL oder eine URL zu einer Grafik angegeben werden. Wenn in den Metadatensatz eine Vorschaugrafik/Grafik eingetragen wurde, so wird diese in der Suchergebnisliste und in der Detailansicht unter "Allgemeines" dargestellt. 


Beispiel WMS-Request + Parameter: https://www.URL.de/../../../..?SERVICE=WMS&VERSION=1.3.0&REQUEST=GetMap&FORMAT=image/png&BBOX=600280,5880886,791921,5649149&HEIGHT=200&WIDTH=200&BGCOLOR=0xFFFFFF&EXCEPTIONS=application/vnd.ogc.se_inimage&TRANSPARENT=TRUE&STYLES=&CRS=EPSG:25832&LAYERS=%20lau_br_lsa

Beispiel Grafik-URL: https://www.URL.de/images/schutzgebiet.png

Dateibeschreibung
Geben Sie eine Beschreibung zu der gewählten Grafik ein. Diese Angabe ist für die barrierefreie Darstellung der Grafik auf der Portalseite wichtig.

Beispiel: Karte Landschaftsschutzgebiete Sachsen-Anhalt


 

Abb.: Anzeige der Vorschaugrafik (WMS) in der Suchergebnisliste auf der Portaloberfläche. Im Geodatensatz wird der Button "Karte", für den Aufruf des Kartenviewers, angezeigt. Die Metadaten lassen sich über den Button "XML" im Browser als XML-File anzeigen.


 

Abb.: Anzeige der Vorschaugrafik in der Detailansicht des Datensatzes - Über den Button "Zeige Karte" wird der Kartenviewer aufgerufen.

 

Beschreibung
Eintrag einer Aussagekräftigen fachlichen Inhaltsangabe zum beschreibenden Geodatensatz. Auf Verständlichkeit für fachfremde Dritte ist zu achten. Technische Einzelheiten in Verbindung mit der Datenverarbeitung sollten auf das Wesentliche beschränkt sein. Das Feld Beschreibungen muss ausgefüllt werden, es ist ein Pflichtfeld, sonst lässt sich der Metadatensatz nicht freigeben.

Hinweis: Empfohlen ist ein Absatz. Je mehr Inhalte eingegeben werden, umso mehr Schlüsselwörter sind auch für die Suche vorhanden. Kurze Sätze werden besser verstanden.

 

Adressen
An dieser Stelle sind Personen, Fachbereiche oder Institutionen anzugeben, die weitere Auskünfte zum aktuellen Objekt/Datensatz geben können. Es besteht dabei keine Verpflichtung zur Veröffentlichung von Personenbezogenen Daten (siehe Erfassungsanleitung Teil 2, Punkt: 1.1 Anlegen von Adressen, Feld: "Daten nicht anzeigen"). Die Angabe einer Institution oder eines Fachbereiches ist ausreichend. Bei Bedarf können diese Verweise geändert werden. In der linken Spalte ist kein freier Eintrag möglich, die Auswahl erfolgt über eine Dropdown-Liste. Zum Öffnen des Dropdownmenüs die entsprechende freie Zelle der Tabelle markieren und anschließend auf das kleine Dreieck am rechten Rand klicken. Es öffnet sich daraufhin die Dropdown-Liste mit den Auswahlmöglichkeiten:

Auswahlliste Art des Verweises
 - Anbieter 
 - Ansprechpartner 
 - Autor 
 - Bearbeiter 
 - Eigentümer 
 - Herausgeber	 - Nutzer
 - Projektleitung
 - Urheber
 - Vertrieb
 - Verwalter


Link Adresse hinzufügen
Über den Link "Adresse hinzufügen" wird der Verweis selbst angelegt. Als Auswahlmöglichkeit stehen alle in der Adressverwaltung des aktuellen Kataloges bereits eingetragenen Adressdaten zur Verfügung. 

Über das Kontextmenü (rechte Maustaste) ist es möglich Adressen aus einer Zeile zu kopieren und in eine weitere Zeile einzufügen.

Beispiel: 
Ansprechpartner: Max Mustermann 
Verwalter: Lieschen Müller

 

Adresse hinzufügen
In der Direkten Suche können Sie entweder nach der Einheit bzw. Institution, den Nachnamen, den Vornamen oder einer Kombination aus den Feldern suchen. Es wird immer eine Suche nach einer Teilzeichenkette durchgeführt. Werden Zeichenketten in mehreren Feldern angegeben, wird eine Adresse nur dann gefunden, wenn alle Zeichenketten übereinstimmen (UND-Verknüpfung).
Die gefundenen Adressen werden in der Trefferliste angezeigt. Durch ein einfaches Klicken auf einen Eintrag wird dieser markiert. Durch ein anschließendes Klicken auf "Übernehmen" wird die markierte Referenz auf die Adresse in das Objekt übernommen. 
Im Hierarchiebaum können Sie in der üblichen Weise navigieren. Ein einfacher Klick auf eine Adresse markiert diese. Durch ein anschließendes Klicken auf "Übernehmen" wird die markierte Referenz auf die Adresse in das Objekt übernommen.
Hinweis:
Die Adresszeilen sind auch zwischen verschiedenen Objekten und (Adress-) Elementen kopierbar. 

Adressen Kopieren und Einfügen
Eine Adresse wird kopiert, indem mit der rechten Maustaste eine Adresszeile angeklickt und die Option „Adresse kopieren“ gewählt wird. Die kopierte Adresse kann nun in einem beliebigen Objekt in einer leeren oder auch in einer befüllten Adresszeile eingetragen werden. Beim Einfügen in eine leere Zeile wird eine Kopie der Adresse samt Rolle eingetragen. Wird in einem bestehenden Eintrag eingefügt, so wird nur die Adresse ausgetauscht, die Rolle bleibt erhalten. 
 

INSPIRE-relevant
Dieses Feld definiert, wenn aktiviert, dass ein Metadatensatz für das INSPIRE-Monitoring vorgesehen ist.

Folgende Eigenschaften ändern sich bei der Aktivierung der Checkbox:
 - Hinzufügen des Schlagwortes "inspireidentifiziert" während der ISO-XML Generierung
 - Verpflichtende Angabe eines INSPIRE-Themas im Abschnitt "Verschlagwortung"

Die als INSPIRE-relevant markierten Datensätze werden im INSPIRE GeoPortal (https://inspire-geoportal.ec.europa.eu/) veröffentlicht.

konform
Geodatensatz wird an INSPIRE gemeldet und liegt im INSPIRE-DatenSchema vor. Der Grad der Konformität (im Abschnitt: "Zusatzinformation", Tabelle: Konformität) zur Spezifikation (VO 1089/2010) wird auf "true" gesetzt.

Hinweis: 
Dieses Feld erscheint nur, wenn in der Objektklasse "Geodatensatz" das Häkchen in das Feld "INSPIRE-relevant" gesetzt wurde.

nicht konform
Geodatensatz wird an INSPIRE gemeldet, liegt aber nicht im INSPIRE-DatenSchema vor. Der Grad der Konformität zur Spezifikation (VO 1089/2010) kann durch den Anwender (im Abschnitt: "Zusatzinformation", Tabelle: Konformität) nur auf "false" oder "nicht evaluiert" gesetzt werden.

Achtung:
Dieses Feld erscheint nur, wenn in der Objektklasse "Geodatensatz" das Häkchen in das Feld "INSPIRE-relevant" gesetzt wurde.

AdV kompatibel
Beim Anhaken der Checkbox "AdV kompatibel" werden die Anforderungen des AdV-Metadatenprofils umgesetzt (z.B. Automatisiertes Setzen des Schlüsselwortes "AdVMIS" in der Datenbank).

Open Data
Diese Checkbox kennzeichnet den Metadatensatz als "Open Data"-Objekt.
Es sind dann zusätzlich folgende Angaben verpflichtend:

 - In der (nur für OpenData) erscheinenden Tabelle "Kategorien" muss mindestens ein Wert eingetragen werden.
 - Unter Verweisen muss mindestens ein Verweis vom Typ "Datendownload" eingetragen werden.
 - Unter "Nutzungsbedingung" muss mindestens ein Eintrag vorhanden sein.

Hinweis:
Die Checkbox „Open Data“ ist derzeit für Sachsen-Anhalt nicht relevant, da für Open Data noch keine gesetzlichen Grundlagen existieren. 

1.3	Abschnitt Verschlagwortung

 

 

AdV Produktgruppe
Auswahl einer Produktgruppe bzw. eines Fachthemas der AdV.

Hinweis: 
Dieses Feld ist nur ein Pflichtfeld, wenn in das Feld "AdV kompatibel" ein Häkchen gesetzt wurde.

 

INSPIRE-Themen
Auswahl eines INSPIRE Themengebiets für die Verschlagwortung des Geodatensatzes (INSPIRE-Pflichtfeld).

Bei Eintragung oder Löschen eines INSPIRE-Themas werden im Pflichtfeld Spezifikation der Konformität automatisch Einträge vorgenommen bzw. entfernt.

Beispiel: Boden
(automatischer Eintrag im Abschnitt "Zusatzinformation", Feld: "Konformität": "VERORDNUNG (EG) Nr. 1089/2010 - INSPIRE Durchführungsbestimmung Interoperabilität von Geodatensätzen und -diensten: konform / nicht konform")

Achtung:
Dieses Feld ist nur ein Pflichtfeld, wenn in das Feld "INSPIRE-relevant" ein Häkchen gesetzt wurde.

Über ein Dropdownmenü öffnet sich die Liste aller INSPIRE-Themengebiete, aus der das zutreffende Thema auszuwählen ist. Handelt es sich bei den beschriebenen Daten um keinen INSPIRE-relevanten Geodatensatz, so ist "kein INSPIRE-Thema" aus der Liste auszuwählen. 

Auswahlliste INSPIRE-Themen
1.	Kein INSPIRE-Thema
2.	Adressen
3.	Atmosphärische Bedingungen
4.	Bewirtschaftungsgebiete/
Schutzgebiete/geregelte Gebiete und Berichterstattungseinheiten
5.	Biogeografische Regionen
6.	Boden
7.	Bodenbedeckung
8.	Bodennutzung
9.	Energiequellen
10.	Flurstücke/Grundstücke (Katasterparzellen)
11.	Gebäude
12.	Gebiete mit naturbedingten Risiken
13.	Geografische Bezeichnungen
14.	Geografische Gittersysteme
15.	Geologie
16.	Gesundheit und Sicherheit
17.	Gewässernetz	18.	Höhe
19.	Koordinatenreferenzsysteme
20.	Landwirtschaftliche Anlagen und Aquakulturanlagen
21.	Lebensräume und Biotope
22.	Meeresregionen
23.	Meteorologisch-geografische Kennwerte
24.	Mineralische Bodenschätze
25.	Orthofotografie
26.	Ozeanografisch-geografische Kennwerte
27.	Produktions- und Industrieanlagen
28.	Schutzgebiete
29.	Statistische Einheiten
30.	Umweltüberwachung
31.	Verkehrsnetze
32.	Versorgungswirtschaft und staatliche Dienste
33.	Verteilung der Arten
34.	Verteilung der Bevölkerung - Demografie
35.	Verwaltungseinheiten

 

INSPIRE - priority data set (optionales Feld)
Priority Data Sets sind jene Geodatensätze, die für die Berichterstattung im Rahmen der EU-Umwelt-Richtlinien bereitgestellt werden (Berichtsdatensätze). Dazu ist je nach Betroffenheit von den Umweltberichterstattungspflichten die entsprechende/-n Rechtsschrift/-en aus der Liste auszuwählen.

Auszug aus der Auswahlliste INSPIRE - priority data set
1.	Lärmbelastung durch Hauptverkehrsstraßen - Tag-Abend-Nacht-Lärmindex (Umgebungslärmrichtlinie) {en: Major roads noise exposure delineation day-evening-night (Noise Directive)}
2.	Lärmbelastung in Ballungsräumen - Tag-Abend-Nacht-Lärmindex (Umgebungslärmrichtlinie) {en: Agglomerations - noise exposure delineation day-evening-night (Noise Directive)}
3.	Location of boreholes {en: Location of boreholes}
4.	Kommunale Abwasserbehandlungsanlagen (Kommunalabwasserrichtlinie) {en: Urban waste-water treatment plants (Urban Waste Water Treatment Directive)}
5.	Schadstofffreisetzungen (Europäisches Schadstofffreisetzungs- und -verbringungsregister) {en: Actual pollutant 

Hinweis: Die vollständige Liste finden Sie als Anlage am Ende dieses Dokumentes.

 

INSPIRE - Räumlicher Anwendungsbereich (INSPIRE-Pflichtfeld)

Das Schlagwort "Räumlicher Anwendungsbereich" wird im Rahmen des INSPIRE-Monitorings verwendet, um die flächenmäßige Abdeckung der INSPIRE-relevanten Geodatensätze auszuwerten. INSPIRE-relevante Geodatensätze müssen aus den zur Auswahl stehenden Werten entweder mit "National", "Regional" oder "Lokal" beschrieben werden.

Auswahlfeld INSPIRE - Räumlicher Anwendungsbereich
 - Europäisch
 - Global	 - Lokal
 - National	 - Regional


 

ISO-Themenkategorie
Dieses Feld verlangt die Angabe der Hauptthemen, welche die Metadaten beschreiben.
Die Auswahl erfolgt über die vorgegebene Auswahlliste.

Für INSPIRE-konforme Metadaten über Daten ist die Angabe einer ISO-Themenkategorie notwendig. Um eine sachrichtige inhaltliche Zuordnung von INSPIRE-Themen zu ISO-Themenkategorien zu gewährleisten und es dem Erfasser möglichst einfach zu machen, übernimmt die InGrid Software die Zuordnung. Bei Auswahl eines INSPIRE Themas wird die entsprechende ISO-Kategorie automatisch hinzugefügt. Der Nutzer wird per Tooltip über den Automatismus informiert.
Beispiel:
Wird das INSPIRE-Thema "Adressen" ausgewählt, so wird automatisch die passende ISO-Themenkategorie "Ortsangaben" hinzugefügt.

Wird versucht eine ISO-Kategorie zu löschen, die an ein INSPIRE-Thema geknüpft ist, so wird dies verhindert und der Nutzer über einen Tooltip darüber informiert.

Umgekehrt gilt der Automatismus nicht: Beim Hinzufügen einer ISO Kategorie wird kein INSPIRE Thema gesetzt.

Auswahlliste ISO 19115 Themenkategorien
 - Atmosphäre
 - Bauwerke
 - Binnengewässer
 - Biologie
 - Geowissenschaften
 - Gesellschaft
 - Gesundheitswesen
 - Grenzen
 - Höhenangaben
 - Landwirtschaft	 - Meere
 - Militär und Aufklärung
 - Oberflächenbeschreibung
 - Ortsangaben
 - Planungsunterlagen, Kataster
 - Umwelt
 - Ver- und Entsorgung, Kommunikation
 - Verkehrswesen
 - Wirtschaft

Hinweis: Der Inhalt der Themen-Auswahlliste stammt aus der ISO 19115 und kann nicht erweitert werden. 


 

Optionale Schlagworte
Eingabe von mindestens drei Schlagworten, die im Thesaurus verzeichnet sind. Die Verschlagwortung dient dem themenbezogenen Wiederauffinden (Retrieval) der Objekte über den Thesaurus-Navigator. Dazu müssen Schlagworte aus dem Thesaurus ausgewählt werden, die das Objekt so genau wie möglich, aber auch so allgemein wie nötig beschreiben. So sollte mindestens ein Schlagwort in der Thesaurus-Hierarchie einen relativ allgemeinen Aspekt des Objektes beschreiben und mindestens ein Schlagwort das Objekt so speziell wie möglich beschreiben. Die Auswahl kann über den "Verschlagwortungsassistent" oder den "Thesaurus-Navigator" vorgenommen werden - siehe Verlinkung.

 

Abb.: Beispiel für eine Verschlagwortung

Hinweis: Die optionalen Schlagworte sind nur sichtbar, wenn der Abschnitt Verschlagwortung weiter ausgeklappt wird.

Umwelt-Thesaurus (UMTHES)
Die Verschlagwortung über den Umwelt-Thesaurus dient dem themenbezogenen Wiederauffinden der Objekte über den Thesaurus-Navigator. Dazu müssen Schlagworte aus dem Thesaurus (UMTHES) ausgewählt werden, die das Objekt so genau wie möglich, aber auch so allgemein wie nötig beschreiben. So sollte mindestens ein Schlagwort in der Thesaurus-Hierarchie einen relativ allgemeinen Aspekt des Objektes beschreiben und mindestens ein Schlagwort das Objekt so speziell wie möglich beschreiben. Die Auswahl kann über den "Verschlagwortungsassistent" oder den "Thesaurus-Navigator" vorgenommen werden (siehe Verlinkung).

Die Eingabe von mindestens drei Schlagworten, die im Umwelt-Thesaurus verzeichnet sind wird empfohlen.

Beispiel für "UMTHES": Luftbild, Bildflug, Orthophoto


Freie Schlagworte eintragen
Hier erfolgt die Eingabe von Schlagworten die nicht im Thesaurus vorhanden sind.
Es sollen prägnante Begriffe und Termini, die in engem Zusammenhang mit dem Objekt stehen und die nicht im Thesaurus vorhanden sind, eingetragen werden. Dies können spezielle Fachgebiete, (Mess-Methoden, Bestandteile o.ä. sein. Die Freien Suchbegriffe sind ergänzend zu den Thesaurus-Suchbegriffen anzugeben. Wenn Sie hier einen Thesaurusbegriff eingeben, wird dieser automatisch als Thesaurusbegriff (UMTHES) erkannt und gekennzeichnet. Abschließend den Button "Hinzufügen" betätigen.
Das eingegebene Schlagwort wird dadurch automatisch in die obere Tabelle übernommen. Ein Hinweis in der rechten Tabellenspalte zeigt an, ob das Schlagwort bereits im Umweltthesaurus (UMTHES) enthalten ist, oder ob das Schlagwort ein „freies Schlagwort“ (FREE) ist.

Beispiel für "FREE": DOP Sachsen-Anhalt, Befliegung

Hinweis:
Mehrere Schlagworte können in das Textfeld, durch Komma getrennt, angegeben werden, Zusammengehörige Worte werden in Anführungszeichen gesetzt.

 

 

Verschlagwortungsassistent
Mit STRG+Mausklick können Sie einen oder mehrere Schlagwörter markieren.
 
Über die Schaltfläche ">" werden die ausgewählten Schlüsselwörter aus der "Vorschlagsliste" in die Liste "Übernehmen" transportiert. Durch Betätigen der Schaltfläche ">>" können alle Begriffe mit einmal in die rechte Liste übernommen werden. 

Die Schaltfläche "<" verschiebt die markierten Begriffe wieder aus der rechten Liste in die linke Liste. Die Schaltfläche "<<" verschiebt alle Begriffe aus der rechten Liste auf die linke Seite. 

Mit einem Klick auf die Schaltfläche "Übernehmen" werden alle Begriffe aus der Liste "Übernehmen" dem Metadatensatz als Schlagworte hinzugefügt. 


 
Abb.: Link Thesaurus-Navigator
 
Abb.: Thesaurus-Navigator

Bei der Auswahl der Schlagworte kann der „Thesaurus-Navigator“ helfen.

Der "Thesaurus-Navigator" ist unterteilt in: die Suche, den Hierarchiebaum, die Ergebnisliste und die Liste der Deskriptoren.

 

In die Suchzeile geben Sie einen beliebigen Suchbegriff ein.
Abschließend betätigen Sie den Button "In Thesaurus suchen".

Es erscheint der gewählte Suchbegriff in der Ergebnisliste. Betätigt man das blaue Symbol vor dem Suchbegriff, wechselt die Ansicht in den Hierarchiebaum (an die Stelle, an der dieser Suchbegriff eingeordnet ist). 

 

Im Strukturbaum können weitere Suchbegriffe ausgewählt werden. Durch Betätigen des Buttons „Hinzufügen“, werden die Schlagworte in die Liste der Deskriptoren übernommen. 

Abschließend betätigen Sie den Button „Übernehmen“. Die gewählten Begriffe werden jetzt in die Tabelle "Optionalen Schlagworte" eingetragen.


1.4	Abschnitt Fachbezug

 

 

Fachliche Grundlage
Im Feld „fachliche Grundlage“ sollte auf Dokumente verwiesen werden, die Grundlage der fachlichen Inhalte der Karte oder Datensammlung sind. Außerdem können Regeln für die Erfassung (Geo-Information) bzw. Darstellung (Karte) angegeben werden. Dieses Dokument kann eine Erläuterung der gesetzlichen Grundlagen darstellen, jedoch auch selbständigen Charakters sein. Möglich ist eine Eintragung in Textform, indem die Karteikarte "Text" ausgewählt wird. Außerdem ist es möglich, durch Auswahl der Registerkarte "Verweise", ein Verweis zu einem anderen Objekt im aktuellen Katalog herzustellen.


 

Identifikator der Datenquelle
Hier muss ein eindeutiger Name (Identifikator) für die im Geodatensatz beschriebene Datenquelle (z.B. eine Karte) vergeben/eingetragen werden. Der Identifikator soll aus einem Namensraum (=codespace), sowie einem Code bestehen. (INSPIRE-Pflichtfeld).
Wenn der Identifikator keinen Namensraum enthält, so wird dem Identifikator bei der Abgabe der Metadaten derjenige Wert vorangestellt, welcher im Bereich Katalogverwaltung/Katalogeinstellungen unter "Namensraum des Katalogs" eingetragen ist.
Der Identifikator kann von Hand eingetragen werden oder mit Hilfe des Buttons "Erzeuge ID". Bei der automatischen Erzeugung wird eine UUID als Identifikator in dieses Feld eingetragen. Da diese UUID keinen Namespace enthält, wird bei dieser Variante immer der Namensraum aus der Katalogverwaltung hinzugefügt.
Beispiele:
 
Abb.: Beispiel: ID aus MetaVer

 
Abb.: Beispiel: ID aus der Registry

Datensatz/Datenserie
Bei Daten dieser Klasse ist zwischen einem "Datensatz" und einer "Datenserie" zu unterscheiden. Katalogintern ist stets der Datensatz vorausgewählt.

 


Datensatz
Als Datensatz wird eine in sich abgeschlossene Sammlung von Geodaten (Daten mit Raumbezug) bezeichnet, z.B. ein digitaler Bestand zu einem bestimmten fachlichen Thema.

Beispiel:
Stadtplanwerk, bestehend aus 8 Einzelblättern: Das Stadtplanwerk als solches ist eine Datenserie. Jedes einzelne der 8 Blätter hingegen kann als Datensatz beschrieben werden.


Datenserie
Eine Datenserie stellt eine Folge oder Gruppierung von gleichartigen Datenbeständen dar, die sich z.B. im abgedeckten räumlichen Bereich oder in der zeitlichen Aussage zum Gültigkeitszeitraum unterscheiden.

Beispiel:
Komplexe Darstellung der städtischen Verwaltungsstruktur aus unterschiedlichen dargestellten Grenzen: Es werden die Grenzen der Müllabfuhrbezirke, die Grenzen der Wahlbezirke, der Stadteile, der Schuleinzugsgebiete usw. inhaltlich gezeigt. Alle diese Grenzen für sich genommen könnten als Datensatz beschrieben werden. Die komplexe aufbereitete Darstellung, die diese unterschiedlichen Grenzen vereint, also der Geodatensatz "Komplexe Darstellung der städtischen Verwaltungsstruktur" an sich, wäre in diesem Falle jedoch eine Datenserie.

 


Digitale Repräsentation
Angabe der Methode, räumliche Daten zu präsentieren. Die Auswahl erfolgt über eine vorgegebene Liste.

Beispiele: Raster, Gitter, Stereomodell, Text, Tabelle, TIN, Vektor, Video


 

Vektorformat
Es können hier Topologie Informationen, Geometrietyp (Angabe der geometrischen Objekte, zur Beschreibung der geometrischen Lage) und Elementanzahl (Angaben der Anzahl der Punkt- oder Vektortypelemente) angegeben werden.

Achtung: Dieses Feld ist nur aktiv nach Auswahl von "Vektor" im Feld "Digitale Repräsentation". 

 

Erstellungsmaßstab
Angabe des Erstellungsmaßstabes, der sich auf die erstellte Karte und/oder Digitalisiergrundlage bei Geodaten bezieht. 
 - Maßstab 1:x: Maßstab der Karte, z.B. 1:12 
 - Bodenauflösung (m): Einheit geteilt durch Auflösung multipliziert mit dem Maßstab (Angabe in Meter, Fließkommazahl) 
 - Scanauflösung (DPI): Auflösung z.B. einer eingescannten Karte, z.B. 120dpi (Angabe in dpi, Integerzahl)

Beispiel:
Bodenauflösung: Auflösungseinheit in Linien/cm; Einheit: z.B. 1 cm geteilt durch 400 Linien multipliziert mit dem Maßstab 1:25.000 ergibt 62,5 cm als Bodenauflösung

 

Symbolkatalog
Für die Präsentation genormter Objekte und Sachverhalte können für die Nutzer der Daten zur Herstellung von Karten abgestimmte Symbole vorgegeben werden. Die Angabe eines oder mehrerer analoger oder digitaler Symbolpaletten mit zugehörigem Datum (Pflichteintrag) und Version (Optional) ist hier möglich.

Beispiel: Planzeichenverordnung, Datum 01.01.1998, Version 1.0

 

Schlüsselkatalog
An dieser Stelle besteht die Möglichkeit, den Daten zugrunde liegende Klassifizierungs-schlüssel zu benennen. Dabei ist die Eingabe mehrerer Kataloge mit zugehörigem Datum (Pflichteintrag) und Version (Optional) möglich. 

Beispiel: Biotoptypenschlüssel, Datum 01.01.2016, Version 2.0

Achtung:
Das Feld Schüsselkatalog wird zum Pflichtfeld, wenn in der Tabelle Sachdaten/Attributinformationen ein Eintrag vorgenommen wurde.

Um die Verpflichtung wieder zu entfernen, muss die beschriebene Zeile in der Tabelle "Sachdaten" komplett gelöscht werden (Zeile markieren, rechte Maustaste – Kontextmenü "Zeile löschen"). Es reicht nicht aus, einfach den Text in der Zelle zu löschen.

 

Angabe der mit der Geo-Information/Karte verbundenen Sachdaten. Bei Bedarf kann hier eine Auflistung der Attribute des Datenbestandes erfolgen. Die hauptsächliche Nutzung dieses Feldes ist für digitale Geo-Informationen vorgesehen.

Beispiel: Baumkartei

Achtung: 
Mit einem Eintrag unter Sachdaten/Attributinformation wird die Tabelle Schlüsselkatalog zum Pflichtfeld. Bitte geben Sie dort den Schlüsselkatalog an, welcher das eingetragene Attribut verzeichnet.

 

Darstellender Dienst
Georeferenzierte Daten, die Basisdaten eines OGC Web-Dienstes sind, können über dieses Feld einen Verweis auf einen beschriebenen OGC Web-Dienst erhalten. Diese Geodaten sind in der Regel eng mit dem Dienst verknüpft ("tightly coupled") und über den verknüpften OGC Web Service direkt erreichbar.

Werden beispielsweise die fachlichen Inhalte eines WMS-Dienstes beschrieben, sollte an dieser Stelle unbedingt ein Verweis zu dem WMS-Dienst vorgenommen werden. Durch diese Verknüpfung kann sich der Nutzer die Daten direkt in der Kartenkomponente des MDK über den WMS-Dienst anzeigen lassen (siehe Daten-Dienste-Kopplung). 

Zum Eintragen eines gekoppelten Dienstes kann nun unterhalb der Tabelle „Darstellender Dienst“ auf den Button "Gekoppelten Dienst auswählen" geklickt werden. 

In dem daraufhin erscheinenden Dialog muss aus dem Hierarchiebaum der Dienst ausgewählt werden, mit dem die Daten gekoppelt werden sollen. Es können nur Objekte des Typs „Geodatendienst“ selektiert werden. 
Mit einem Klick auf den Button „Zuweisen“ wechselt der Editor automatisch zu diesem Geodatendienst-Objekt. Es öffnet sich daraufhin ein neues Fenster mit der Information, dass man zu dem ausgewählten Dienst weitergeleitet worden ist. 

 
Es wurde außerdem der Verweis zu den eigentlichen Daten im Dienste-Objekt eingetragen.

Durch ein „Zwischenspeichern“ wird die Kopplung zwischen den Daten und dem Dienst übernommen, in dem automatisch beide Metadatenobjekte (Daten und Dienst) gespeichert werden. 

Sowohl beim Metadatenobjekt der Daten als auch beim Objekt des Dienstes ist nun die Kopplung eingetragen. 

 

Beispiel: Eintrag im Geodatendienst
Verweis auf Datensatz: „ATKIS-DGM1 Sachsen-Anhalt“: 

 

Beispiel: Eintrag im Geodatensatz
Verweis auf Geodatendienst: „ATKIS-DGM1 Sachsen-Anhalt (ATOM-Downloaddienst)“
Verweis auf Geodatendienst: „ATKIS-DGM1 Sachsen-Anhalt (WMS 1.3)“

Hinweis: Um eine Kopplungs-Beziehung wieder zu entfernen, muss diese im Dienste-Objekt gelöscht werden.


 

Datengrundlage
Angabe der Unterlagen (Luftbilder, Karten, Datensammlungen), die bei der Erstellung der Karte oder der Geo-Information (des digitalen Datenbestandes) Verwendung finden. Der Eintrag kann in Textform erfolgen, indem die Karteikarte "Text" ausgewählt wird. Außerdem kann durch Auswahl der Registerkarte "Verweise" ein Verweis zu einem anderen Objekt im aktuellen Katalog erstellt werden.

Beispiel: Kartieroriginale der Pflanzenerfassung


 

Herstellungsprozess
Angabe der Methode, die zur Erstellung des Datenobjektes geführt hat. Der Eintrag kann in Textform erfolgen, indem die Registerkarte "Text" ausgewählt wird. Außerdem kann durch Auswahl der Registerkarte "Verweise" ein Verweis erstellt werden.

Beispiel: Feldkartierung

1.5	Abschnitt Datenqualität

 

 

Datendefizit
Eingabe einer Prozentangabe zum Anteil der Daten, die im Vergleich zum beschriebenen Geltungsbereich fehlen. Diese kann sich auf die Anzahl der Kartenblätter aber auch auf das Datendefizit einer Gesamtkarte beziehen.

Beispiel: 55
Wenn der Erfassungsgrad bei 100% liegt, ist in dem Feld Datendefizit 0% einzutragen. (Datendefizit = 100 – Erfassungsgrad) 


 

Höhengenauigkeit
Angabe über die Genauigkeit der Höhe z.B. in einem Geländemodell.

Beispiel: 3 (m)

Lagegenauigkeit
Angabe über die Genauigkeit z.B. in einer Karte.

Beispiel: 3 (m)

Hinweis:
Die folgenden Eingabefelder erscheinen bei der Auswahl (Verschlagwortung) der INSPIRE-Themen: Adressen, Gewässernetz, Schutzgebiete, Verwaltungseinheiten und Verkehrsnetze.

 

Datenüberschuss
Angaben zu den überschüssigen Features, Attributen oder ihren Relationen.

Beispiel: Anzahl der überflüssigen Elemente zur Anzahl der gesamten Elemente: 11,2% 

Hinweis: Es wird nur eine Zahl angegeben; kein %-Zeichen.


 

Konzeptionelle Konsistenz
Angaben zu Fehlern bezüglich der Verletzung der Regeln des konzeptionellen Schemas

Beispiel: Anzahl der überlappenden Oberflächen innerhalb des Datensatzes: 23


 

Konsistenz des Wertebereichs
Angaben zur Übereinstimmung des Wertebereichs - Angegeben wird die Anzahl der Übereinstimmungen im Verhältnis zur Gesamtmenge der Elemente.


 

Formatkonsistenz
Angaben darüber, wie viele Elemente sich im Konflikt zu der physikalischen Struktur des Datensatzes befinden.

 

Zeitliche Genauigkeit
Angabe der Anzahl der zeitlich korrekt zugeordneten Elemente zur Gesamtzahl der Elemente.


 

Topologische Konsistenz
Angaben zu topologischen Fehlern, die zwischen verschiedenen Unterelementen des Datensatzes auftreten.

Beispiel: Anzahl fehlender Verbindungen zwischen Unterelementen aufgrund von Undershoots/Overshoots.


 

Korrektheit der thematischen Klassifizierung
Angabe der Anzahl der thematisch falsch klassifizierten Elemente zur Gesamtanzahl der Elemente.


 

Genauigkeit nicht-quantitativer Attribute
Angabe der Anzahl der inkorrekten nicht-quantitativen Attributwerte im Verhältnis zur Gesamtzahl der Attribute.


 

Genauigkeit quantitativer Attribute
Angabe der Anzahl der quantitativen Attribute, die inkorrekt sind.

Beispiel: Anzahl aller quantitativen Werte, die nicht mit 95% Wahrscheinlichkeit dem wahren Wert entsprechen.


1.6	Abschnitt Raumbezugsystem

 

 

Geothesaurus Raumbezug
Im Abschnitt Geothesaurus-Raumbezug wird die räumliche Ausdehnung des betreffenden Objektes angezeigt. Es wird ein Begrenzungsrechteck (Bounding Box) aus geografischen Koordinaten ("Min" und "Max") angegeben, in dem die Ressource liegt.

Als Ausdehnung wird bei neuen Objekten automatisch standardmäßig das Bundesland Sachsen-Anhalt eingetragen. Diesen Eintrag können Sie bei Bedarf löschen (Zeile markieren, rechte Maustaste, "Zeile löschen"). 

Zur Eingabe eines anderen geografischen Bereichs wählen Sie den "Geothesaurus-Navigator". Sie öffnen ihn durch einen Klick auf den Link.

Über den Geothesaurus-Navigator kann nach den Koordinaten der räumlichen Einheit gesucht werden.
 
Geothesaurus-Navigator
Eingabe der Räumlichen Einheit, deren Koordinaten gesucht werden sollen.

Geben Sie in das Suchfeld den geografischen Begriff (oder einen Teil des Begriffs) ein den Sie suchen. Nach dem Klicken auf die Schaltfläche „In Geo-Thesaurus suchen“ wird nach diesem Begriff im SNS (Semantic Network Service des Umweltbundesamtes) gesucht und die Ergebnisse werden unter Auswahl aufgelistet. Sie können einen oder mehrere Begriffe dieser Liste markieren und über die Schaltfläche "Übernehmen" als Raumbezug dem Objekt hinzufügen. Neben den geografischen Begriffen werden damit automatisch auch die Koordinaten des geografischen Bereiches in das Objekt übernommen. 

Hinweis: Für eine breitere Suche können Sie Wildcards verwenden, z.B. Harz* oder *Talsperre.

Sollte der gewünschte geografische Begriff nicht vorhanden sein, besteht die Möglichkeit, diesen zusammen mit den Koordinaten manuell einzutragen. Wählen Sie unter der Tabelle "Freier Raumbezug" den Link "Raumbezug hinzufügen".

Hinweise:
Der Link "Raumbezug hinzufügen" ist nur sichtbar, wenn die optionalen Felder eingeblendet sind.


 

Umgerechnete Koordinaten
Umrechnung der unter Geothesaurus-Raumbezug ausgewählten Daten in die in der Auswahllist zur Verfügung stehenden Koordinatensysteme.


Freier Raumbezug
Informationen über die räumliche Zuordnung des in dem Objekt beschriebenen Datenbestand. Es können frei wählbare Raumbezugs-Koordinaten hinzugefügt werden. Der Wertebereich im WGS ist folgendermaßen definiert:

- Breite (Latitude): -90 bis 90
- Länge (Longitude): -180 bis 180

 
Raumbezug hinzufügen
In dem sich öffnenden Dialog können Sie einen freien Raumbezug in dem Koordinatensystem angeben, welches Sie (im Dialogfester unten) ausgewählt haben. 

Mit einem Klick auf die Schaltfläche „Hinzufügen“ werden die Angaben in das Feld „Freier Raumbezug“ des Objektes übernommen. 
 

erben
Über den Link "erben" können alle freien Raumbezüge des übergeordneten Objektes übernommen werden. Dabei werden nur neue Raumbezüge übernommen.



Raumbezugsystem
Über ein Dropdownmenü erfolgt an dieser Stelle die Auswahl des Raumbezugssystems, welches in der Ressource verwendet wurde. 

Anmerkung:
Die Arbeitsgemeinschaft der Vermessungsverwaltungen der Länder der Bundesrepublik Deutschland (AdV) hat 1991 die Einführung des ETRS89 als Bezugssystem Lage und 1995 die Einführung von UTM als ebenes Koordinatensystem für ETRS89 beschlossen. Dies geschieht im Einklang mit den Empfehlungen der EU zur Realisierung eines europaweiten Raumbezuges und somit zur Schaffung einer einheitlichen Basis für die zukunftsfähige Geodateninfrastruktur in Europa. 

Beispiel: EPSG:4326 / WGS 84 / geographisch

Auswahlliste der Raumbezugssysteme
 - CRS 84: CRS 84 / mathematisch
 - DE_42/83 / GK_3
 - DE_DHDN / GK_3
 - DE_DHDN / GK_3_BW100
 - DE_DHDN / GK_3_HE100
 - DE_DHDN / GK_3_NW177
 - DE_DHDN / GK_3_RDN
 - DE_DHDN / GK_3_RP101
 - DE_DHDN / GK_3_RP180
 - DE_ETRS89 / UTM
 - DE_PD/83 / GK_3
 - DE_PD/83 / GK_9-15, Bezug 12. Meridian (BY)
 - DE_RD/83 / GK_3
 - EPSG 2176: ETRS89 / Poland CS2000 zone 5
 - EPSG 23031: ED50 / UTM Zone 31N
 - EPSG 23032: ED50 / UTM Zone 32N
 - EPSG 23033: ED50 / UTM Zone 33N
 - EPSG 2397: Pulkovo 1942(83) / Gauss-Kruger zone 3
 - EPSG 2398: Pulkovo 1942(83) / Gauss-Kruger zone 4
 - EPSG 2399: Pulkovo 1942(83) / Gauss-Kruger zone 5
 - EPSG 25831: ETRS89 / UTM Zone 31N (INSPIRE)
 - EPSG 25832: ETRS89 / UTM Zone 32N (INSPIRE)
 - EPSG 25833: ETRS89 / UTM Zone 33N (INSPIRE)
 - EPSG 25834: ETRS89 / UTM Zone 34N (INSPIRE)
 - EPSG 28462: Pulkovo 1942 / Gauss-Krüger 2N
 - EPSG 28463: Pulkovo 1942 / Gauss-Krüger 3N
 - EPSG 3034: ETRS89 / LCC Europa (INSPIRE)
 - EPSG 3035: ETRS89 / LAEA Europa (INSPIRE)
 - EPSG 3038: ETRS89 / ETRS-TM26
 - EPSG 3039: ETRS89 / ETRS-TM27
 - EPSG 3040: ETRS89 / ETRS-TM28
 - EPSG 3041: ETRS89 / ETRS-TM29
 - EPSG 3042: ETRS89 / ETRS-TM30
 - EPSG 3043: ETRS89 / ETRS-TM31
 - EPSG 3044: ETRS89 / UTM Zone 32N (N-E) (INSPIRE)
 - EPSG 3045: ETRS89 / UTM Zone 33N (N-E) (INSPIRE)
 - EPSG 3046: ETRS89 / ETRS-TM34
 - EPSG 3047: ETRS89 / ETRS-TM35
 - EPSG 3068: DHDN / Soldner Berlin
 - EPSG 31466: DHDN / Gauss-Krüger Zone 2
 - EPSG 31467: DHDN / Gauss-Krüger Zone 3
 - EPSG 31468: DHDN / Gauss-Krüger Zone 4
 - EPSG 31469: DHDN / Gauss-Krüger Zone 5
 - EPSG 32631: WGS 84 / UTM Zone 31N
 - EPSG 32632: WGS 84 / UTM Zone 32N
 - EPSG 32633: WGS 84 / UTM Zone 33N
 - EPSG 35832: ETRS89 / UTM zone 32N 8d
 - EPSG 35833: ETRS89 / UTM zone 33N 8d
 - EPSG 3857: WGS 84 / Pseudo-Mercator
 - EPSG 4178: Pulkovo 1942(83) / geographisch
 - EPSG 4230: ED50 / geographisch
 - EPSG 4258: ETRS89 / geographisch (INSPIRE)
 - EPSG 4284: Pulkovo 1942 / geographisch
 - EPSG 4314: DHDN / geographisch
 - EPSG 4326: WGS 84 / geographisch
 - EPSG 4647: ETRS89 / UTM Zone 32N (zE-N)
 - EPSG 4839: ETRS89 / LCC Deutschland (N-E)
 - EPSG 5650: ETRS89 / UTM Zone 33N (zE-N)
 - EPSG 5676: DHDN / Gauss-Krüger Zone 2 (E-N)
 - EPSG 5677: DHDN / Gauss-Krüger Zone 3 (E-N)
 - EPSG 5678: DHDN / Gauss-Krüger Zone 4 (E-N)
 - EPSG 5679: DHDN / Gauss-Krüger Zone 5 (E-N)
 - EPSG 8395: ETRS89 / Gauss-Krüger (CM 9E)
 

Höhe

Minimum / Maximum
Angabe der Werte für die Höhe über einem Punkt (siehe Pegel) eingegeben. Ist eine vertikale Ausdehnung vorhanden, so kann für das Maximum ein größerer Wert eingegeben werden. Sollte dies nicht der Fall sein, so ist die Eingabe eines Minimalwerts ausreichend, dieser Wert wird dann automatisch ebenso für den Maximalwert übernommen.

Beispiel: Minimum 100, Maximum 110


Maßeinheit
Angabe der Maßeinheit, in der die Höhe gemessen wird.

Beispiel: Meter


Vertikaldatum
Angabe des Referenzpegels, zu dem die Höhe relativ gemessen wird. In Deutschland ist dies i.A. der Pegel Amsterdam.

Beispiel: Pegel Amsterdam

Erläuterungen
Zusätzliche Angaben zum Raumbezug.

Beispiel: Die Koordinaten für die Fachliche Gebietseinheit sind ungefähre Angaben.


1.7	Abschnitt Zeitbezug

 

 

Zeitbezug der Ressource
In dieser Tabelle wird angegeben, wann die Ressource erstmalig erstellt, publiziert oder/und letztmalig geändert/aktualisiert wurde. Die Datumsangaben beziehen sich dabei nicht auf den Metadatensatz, sondern direkt auf die beschriebene Ressource. Es ist mindestens ein Eintrag erforderlich, es können jedoch auch alle drei Typen gleichzeitig angeben werden.

Beispiel: 22.01.2019 Erstellung
 

Erläuterung
Hier können z.B. die Angaben der Periodizität eingeschränkt, weitere Zeitangaben gemacht oder Unregelmäßigkeiten erklärt werden. Im Zusammenhang mit dem Eintrag im Feld Periodizität können hier Abstände, Perioden und Intervalle eingetragen werden, die sich nicht aus dem Zusammenhang der anderen Felder des Zeitbezuges erklären, z.B. Jahreszeiten, Dekaden, Tageszeiten.

Beispiel: Die Messungen erfolgten nur tagsüber.


 

Zeitspanne
Hier soll das Zeitspanne der Entstehung der eigentlichen Daten (z.B. Messdaten) eingetragen werden.


 

Periodizität
Auswahl/Angabe des Zeitzyklus der Datenerhebung. Der Eintrag muss aus der Auswahlliste erfolgen, die über den Pfeil am Ende des Feldes geöffnet wird. 

Achtung: Der Eintrag "unbekannt" sollte nicht mehr verwendet werden. 
Falls noch in Altdaten vorhanden, sollte dieses Wort durch sinnvolle Einträge ersetzt werden. Er stellt eine nicht ISO-konforme Erweiterung der Auswahlliste dar.

Auswahlliste der Periodizität
 - bei Bedarf
 - einmalig
 - halbjährlich	 - jährlich
 - kontinuierlich
 - monatlich	 - täglich
 - unbekannt
 - unregelmäßig	 - vierteljährlich
 - wöchentlich
 - zweiwöchentlich

Beispiel: täglich


 

Status
Stand der Ausführung des Projektes, der Messung etc. Der Editor nimmt alle bekannten Daten auf, diese können sich in unterschiedlichen Stadien ihrer Lebenszeit befinden, d.h. Projekte, Programme oder Messungen können in konkreter Planung sein, derzeit durchgeführt werden oder schon abgeschlossen sein.
Auswalliste Status
 - abgeschlossen
 - erforderlich
 - geplant
 - historisches Archiv	 - in Erstellung
 - in Produktion
 - kontinuierliche Aktualisierung
 - veraltet

Beispiel: abgeschlossen


 

Im Intervall
Angabe des zeitlichen Abstands (Frequenz) der Datenerhebung. Erfolgt die Datenerhebung kontinuierlich oder periodisch (siehe Feld Periodizität), so soll diese Angabe hier präzisiert werden. Es stehen Felder für den freien Eintrag einer Ziffer und eine Auswahlliste zur Verfügung, die zeitliche Intervalle vorgibt. Der Eintrag von 10 und Tage bedeutet: Die beschriebenen Daten werden bzw. wurden alle 10 Tage erhoben.

Auswahlliste der Intervalle
 - Jahre
 - Monate	 - Tage
 - Stunden	 - Minuten
 - Sekunden

Beispiel: Alle 6 Monate


1.8	Abschnitt Zusatzinformation

 


 

Sprache des Metadatensatzes
An dieser Stelle soll die Sprache ausgewählt werden, die bei der Beschreibung der Metadaten verwendet wurde. Es ist hier nicht die Sprache der eigentlichen Ressource gemeint! 

Standardeinstellung ist: Deutsch


 

Sprache der Ressource
Hier ist die Sprache anzugeben, die in der Ressource verwendet wird. Es ist an dieser Stelle nicht die Sprache der Metadaten gemeint! 

Standardeinstellung ist: Deutsch

 

Veröffentlichung
Das Feld "Veröffentlichung" ist sehr wichtig, denn es gibt den Status der Veröffentlichungsbreite an. Möglich sind folgende Werte, die über ein Dropdown-Menü ausgewählt werden können:
 
 - Internet
Das Objekt wird für das Internet veröffentlicht. 

 - Intranet
Das Objekt wird nur für das Intranet veröffentlicht, aber nicht für das Internet. 

Hinweis: Diese Option trifft derzeit für Sachsen-Anhalt nicht zu, da die Portal-/Erfassungssoftware nicht im Landesdatennetz installiert ist.

 - amtsintern
Das Objekt ist nur im Strukturbaum der Erfassungssoftware sichtbar, aber nicht im Intranet und auch nicht im Internet.



 

Es ist nicht möglich, einem Objekt eine höhere Freigabestufe zuzuordnen, als die des übergeordneten Objektes. Die abschließende Speicherung wird mit folgender Fehlermeldung verweigert.


 

Ebenfalls erscheint ein Warnhinweis, wenn die Veröffentlichungsbreite eines bereits abschließend gespeicherten Objektes, welches noch untergeordnete Objekte der gleichen Veröffentlichungsbreite besitzt, reduziert werden soll. 

 

Beispiel:
Das Objekt "Geodatensätze" hat im Screenshot die Veröffentlichungsbreite "Internet". Alle untergeordneten Objekte sind ebenfalls für das Internet freigegeben. Wird nun "Geodatensätze" auf die Veröffentlichung „amtsintern“ reduziert und der obige Warnhinweis mit "Speichern" bestätigt, so werden automatisch auch alle untergeordneten Objekte auf die Veröffentlichungsbreite "amtsintern" herabgesetzt. 


 

Zeichensatz des Datensatzes
Angaben zu dem im beschriebenen Datensatz benutzten Zeichensatz z.B. UTF-8.

Auswahlliste Zeichensatz des Datensatzes
 - 8859part1
 - 8859part2
 - 8859part3
 - 8859part4
 - 8859part5
 - 8859part6
 - 8859part7	 - 8859part8
 - 8859part9
 - 8859part10
 - 8859part11
 - 8859part12
 - 8859part13
 - 8859part14	 - 8859part15
 - big5
 - Ebcdic
 - EucJP
 - EucKR
 - GB2312
 - Jis	 - ShiftJIS
 - ucs2
 - ucs4
 - UsAscii
 - utf7
 - utf8
 - utf16


 

Konformität
Hier muss angegeben werden, zu welcher Durchführungsbestimmung der INSPIRE-Richtlinie bzw. zu welcher anderweitigen Spezifikation die beschriebenen Daten konform sind. (INSPIRE-Pflichtfeld)

Dieses Feld wird bei der Auswahl der "INSPIRE-Themen" oder der "Art des Dienstes" automatisch befüllt. Es muss dann nur der Grad der Konformität manuell eingetragen werden.


Achtung:
Bitte entsprechend den Empfehlungen des AdV-Metadatenprofils nur die Werte "konform" und "nicht konform" im Feld "Grad der Konformität" verwenden. Für alle nicht INSPIRE-Objekte, sollte hier die „INSPIRE-Richtlinie“ mit dem Wert „nicht evaluiert“ ausgewählt werden. 

 

XML-Export-Kriterium
Eintrag eines Selektionskriteriums zur Steuerung des Exports der Daten. Um eine Teilmenge von Objekten exportieren zu können, kann in diesem Feld ein diese Teilmenge identifizierendes Schlagwort eingegeben werden. In der Exportfunktion kann dann eines der Schlagworte aus diesem Feld angegeben werden und alle Objekte exportiert werden, für die in diesem Feld das entsprechende Schlagwort vergeben wurde. Die Eingabe mehrerer Schlagworte ist möglich. Die Schlagworte können frei eingegeben werden. Zur Verhinderung von Schreibfehlern sollte jedoch der Eintrag aus der Auswahlliste vorgezogen werden.

Beispiel: CDS

 

Rechtliche Grundlage
Angabe der rechtlichen Grundlage, die die Erhebung der beschriebenen Daten veranlasst hat. Hier können Kürzel von Gesetzen, Erlassen, Verordnungen usw. eingetragen werden, in denen z. B. die Methode oder die Form der Erhebung der im Objekt beschriebenen Daten festgelegt oder beschrieben wird. Es sind bei Bedarf mehrere Angaben möglich.

Beispiel: Umweltinformationsgesetz des Landes Sachsen-Anhalt

 

Herstellungszweck
Angabe eines Grundes für die Datenerhebung.

 

Eignung/Nutzung
Angaben über die Verwendungsmöglichkeiten, die diese Daten in Verbindung mit weiteren Informationen erfüllen können.

Beispiel: 
Präsentation des Raumordnungsprogramms auf Basis der topografischen Kartenwerke.

1.9	Abschnitt Verfügbarkeit

 

 

Zugriffsbeschränkungen
Das Feld Zugriffsbeschränkungen ist ein Feld, welches im Zusammenhang mit INSPIRE steht. Es beschreibt die Art der Zugriffsbeschränkung. Bei frei nutzbaren Daten bzw. Services soll der Eintrag "Es gelten keine Zugriffsbeschränkungen" ausgewählt werden (ISO: accessConstraints).

Beispiel: aufgrund der Rechte des geistigen Eigentums

Auswahlliste Zugriffsbeschränkungen
 - aufgrund der Rechte des geistigen Eigentums
 - aufgrund der Vertraulichkeit der Verfahren von Behörden
 - aufgrund der Vertraulichkeit personenbezogener Daten
 - aufgrund der Vertraulichkeit von Geschäfts- oder Betriebsinformationen
 - aufgrund des Schutzes einer Person
 - aufgrund des Schutzes von Umweltbereichen
 - aufgrund internationaler Beziehungen, der öffentliche Sicherheit oder der Landesverteidigung
 - aufgrund laufender Gerichtsverfahren
 - Es gelten keine Zugriffsbeschränkungen


 

Nutzungsbedingungen
Einschränkungen zum Schutz der Privatsphäre oder des geistigen Eigentums sowie andere besondere Einschränkungen oder Warnungen bezüglich der Nutzung der Ressource oder der Metadaten (ISO: useConstraints).

In das Feld Nutzungsbedingungen sollen die Bedingungen zur Nutzung des beschriebenen Datensatzes bzw. des Dienstes eingetragen werden. In die entsprechende Zeile kann ein beliebiger Text geschrieben werden.

Beispiel: Nutzungsbedingungen für das amtliche Vermessungswesen Sachsen-Anhalt

Es ist auch möglich, vordefinierten Text aus einer Liste auszuwählen. 

Auswahlliste Nutzungsbedingungen
 - Es gelten keine Bedingungen
 - Amtliches Werk, lizenzfrei nach §5 Abs. 1 UrhG
 - Andere Freeware Lizenz
 - Andere geschlossene Lizenz
 - Andere kommerzielle Lizenz
 - Andere offene Lizenz
 - Andere Open Source Lizenz
 - BSD Lizenz
 - Creative Commons CC Zero License (cc-zero)
 - Creative Commons Namensnennung (CC-BY)
 - Creative Commons Namensnennung - - Keine Bearbeitung 4.0 International (CC BY-ND 4.0)
 - Creative Commons Namensnennung - Nicht kommerziell (CC BY-NC)
 - Creative Commons Namensnennung - Nicht kommerziell 4.0 International (CC BY-NC 4.0)
 - Creative Commons Namensnennung - Weitergabe unter gleichen Bedingungen (CC-BY-SA)
 - Creative Commons Namensnennung - Weitergabe unter gleichen Bedingungen 4.0 International (CC-BY-SA 4.0)
 - Creative Commons Namensnennung -- Keine Bearbeitung 3.0 Unported (CC BY-ND 3.0)
 - Creative Commons Namensnennung – 4.0 International (CC BY 4.0)
 - Datenlizenz Deutschland Namensnennung 1.0
 - Datenlizenz Deutschland Namensnennung 2.0
 - Datenlizenz Deutschland Namensnennung nicht-kommerziell 1.0
 - Datenlizenz Deutschland – Zero – Version 2.0
 - eingeschränkte Geolizenz
 - Freie Softwarelizenz der Apache Software Foundation
 - Geolizenz Ia Namensnennung
 - GNU Free Documentation License (GFDL)
 - GNU General Public License version 3.0 (GPLv3)
 - Mozilla Public License 2.0 (MPL)
 - Nutzung der Daten nur nach Rücksprache mit dem Dateneigentümer
 - Nutzungsbestimmungen für die Bereitstellung von Geodaten des Bundes
 - Open Data Commons Attribution License (ODC-BY 1.0)
 - Open Data Commons Open Database License (ODbL)
 - Open Data Commons Public Domain Dedication and Licence (ODC PDDL)
 - Public Domain Mark 1.0 (PDM)

Bei frei nutzbaren Daten bzw. Diensten ist beispielsweise "Es gelten keine Bedingungen" aus der Liste zu verwenden. Aber auch die Lizenzen für Open Data-Objekte finden Sie in dieser Liste (Datenlizenz Deutschland). 

Haben Sie immer wiederkehrende Nutzungsbedingungen, die nicht in der Liste auftauchen, so wenden Sie sich bitte direkt an die Koordinierungsstelle Metadaten im Ministerium für Umwelt, Landwirtschaft und Energie (metadaten@mule.sachsen-anhalt.de). 
Wir erweitern die Liste gern um Ihren Eintrag. 

 

Anwendungseinschränkungen
Das Feld Anwendungseinschränkungen dient der Beschreibung, welche Einschränkung oder Eignung auf die Ressourcen oder Metadaten zutreffen (ISO: useLimitation).

Beispiel: Registrierung erforderlich

 

Datenformat
Angabe des Formats der Daten in DV-technischer Hinsicht, in welchem diese verfügbar sind. Das Format wird durch 4 unterschiedliche Eingaben spezifiziert. Wenn die erste Spalte befüllt wird, müssen auch die anderen Eintragungen vorgenommen werden. 

Name: Angabe des Formatnamens, wie z.B. "Date" 
Version: Version der verfügbaren Daten (z.B. "Version 8" oder "Version vom 26.02.2020") Kompressionstechnik: Kompression, in welcher die Daten geliefert werden (z.B. "WinZip", "keine") 
Bildpunkttiefe: BitsPerSample.

Beispiel: Formatkürzel: tif, Version: 8.0, Kompression: LZW, Bildpunkttiefe: 8 Bit

 

Bei der Auswahl des INSPIRE-Datenformates GML muss die Version eingetragen werden.

 

Medienoptionen
Angabe, auf welchen Medien die Daten zur Verfügung gestellt werden können. Hier können elektronische Datenträger als auch Medien in Papierform angegeben werden, auf denen die im Objekt beschriebenen Daten dem Nutzer zur Verfügung stehen. Es können mehrere Medien eingetragen werden. Medium: Angabe der Medien, auf denen der Datensatz bereitgestellt werden kann (ISO-Auswahlliste) Datenvolumen: Umfang des Datenvolumens in MB (Fließkommazahl) Speicherort: Ort der Datenspeicherung im Intranet/Internet, Angabe als Verweis.

Auswahlliste Medium
 - 0,5-Zoll Kassette
 - 3,5-Zoll Diskette
 - analoge Fotografie
 - Ausdruck
 - CD-ROM
 - DVD	 - DVD-ROM
 - E-Mail
 - Faxabruf
 - Infokiosk
 - Mikrofilm
 - Mobilfunk	 - Online Link
 - Rundfunk
 - Telefonverbindung
 - unbekannt (*)
 - Videotext
 - ZIP-Laufwerk

Beispiel: Medium: CD-ROM Datenvolumen: 700 MB Speicherort: Explorer Z:/Bereich_51/Metainformation/2020-02-26_Hilfetexte.doc


 

Bestellinformation
Angabe von generellen Informationen wie Bedingungen oder Konditionen zur Bestellung.

Beispiel: Die Lieferzeit beträgt 3 Wochen


1.10	Abschnitt Verweise

 

 

Verweis zu
Es gibt die Möglichkeit, Verweise von einem Objekt zu einem anderen Objekt oder zu einer Internetadresse (URL) zu erstellen. In dieser Tabelle werden alle Verweise zusammenfassend aufgeführt, welche im aktuellen Objekt angelegt wurden. Über dem Link "Verweise anlegen/bearbeiten" öffnet sich ein Dialog, mit dem weitere Einzelheiten zu den Verweisen eingesehen und editiert werden können. Es ist ferner möglich, weitere Verweise über diesen Dialog hinzuzufügen. Wenn Open-Data ausgewählt ist, muss mindestens ein Verweis vom Typ "Datendownload" vorhanden sein, bevor das Objekt veröffentlicht werden kann!

 

Verweis von
In dieser Tabelle werden alle Verweise von denjenigen Objekten aufgeführt, welche auf das aktuelle Objekt verweisen. Das Editieren oder Hinzufügen ist nicht möglich. Sollen die Verweise geändert oder ergänzt werden, so muss zu dem entsprechenden Objekt gewechselt werden.


Hinweis:
Das Anlegen von Verweisen ist im Teil 2 der Erfassungsanleitung unter 2. ausführlich beschrieben.



