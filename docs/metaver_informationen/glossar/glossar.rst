
Glossar
=======

Glossar allgemein
-----------------

**Atom Feed**

Die Bereitstellung von Daten im Atom-Format bezeichnet man auch als Atom-Feed. Atom-Feed ist ein XML-Format, dass von Nutzern verwendet werden kann, um Daten aus dem Internet herunterzuladen. (Bekannt sind solche Dienste auch als RSS-Feed.) Nutzer können einen Atom-Feed (Atom-Channel) abonnieren und mithilfe eines entsprechenden Atom-Feed-Readers (Browser-Erweiterung) Daten aus dem Internet herunterladen. Ein Feed endet mit der Bezeichnung ".atom". Diese Endung kann man auch durch .xml ersetzen. Da in den Webbrowsern die Erweiterung für den Atom-Feed Reader kein Standard ist, wurde der Atom-Feed Client entwickelt. Der Atom-Feed Client wurde im METAVER an die Bundesländer angepasst. Über den Atom-Feed Client werden die Atom-Feeds verwaltet und die Daten (z.B. .zip, .gml) als Download bereitgestellt.



**CSW - Catalogue Service Web**

Bei einer CSW-Schnittstelle handelt es sich um eine standardisiert abfragbare Schnittstelle,
die Datenbeschreibungen (Metadaten) abgibt. Die Anfrage wird wie auch bei anderen OGC-
Diensten „Request“, die Antwort „Response“ genannt. Eine Katalogschnittstelle kann auf
Anfrage benennen, welche Fähigkeiten sie besitzt (GetCapabilities), über wie viele
Datenbeschreibungen sie verfügt (DescribeRecords) und es können neben weiteren
Möglichkeiten gezielt bestimmte Datenbeschreibungen unter Angabe des
Metadatensatzidentifikators abgerufen werden (GetRecordById). Alles in allem ist die
Kommunikation mit einer CSW-Schnittstelle um ein Vielfaches komplexer als beispielsweise
die Kommunikation mit einem WMS (WebMapService), der Kartenbilder und
Sachinformationen ausliefern kann. Aus diesem Grunde ist es sinnvoll, für die
Kommunikation mit einem CSW eine auf die eigenen Bedürfnisse angepasste zum Beispiel
webbasierte Suchoberfläche in einem Browser zu verwenden.


**Dublette**

Eine Dublette ist eine Kopie eines Datensatzes. Ist der Datensatz mehrfach in einer Anwendung vorhanden, spricht man von einer Dublette.


**Grid**

Grid steht für Gitter/Raster z.B. InformationGrid in der Software InGrid.


**Harvesting (Abernten)**

Im Rahmen des Harvestings werden Metadatensätze von einem Metadatenkatalog für einen anderen eingesammelt.
Das Original verbleibt im Original-Katalog und wird dort aktualisiert.
Durch den Metadatensatzidentifikator (UUID) und das hinterlegte
Datum der letzten Änderung am Metadatensatz ist sichergestellt, dass der Datensatz nicht
nur im Original-Katalog sondern auch - zeitversetzt - im harvestenden Katalog aktualisiert
wird. Metadaten sind damit die einzigen Daten in einer Geodateninfrastruktur, die gezielt
kopiert werden, um den Nutzern zur Verfügung zu stehen.
Durch ein Harvesting dürfen Metadaten eines fremden Katalogs niemals abgeändert werden.
Die meisten derzeit aktiven Kataloge halten sich an diese Vorgabe.


**HTML - Hypertext Markup Language**

HTML dient der Strukturierung von Texten und Bildern (vorwiegend im Intranet/Internet).

  
**InGrid - InformationGrid**

InGrid ist eine modular aufgebaute Software, die vielseitig eingesetzt werden kann: Kernkomponenten sind ein Web-Portal,
eine Suchmaschine, ein Metadatenkatalog mit Profilen für die Erfassung INSPRE-konformer Metadaten, offener Daten und UVP-Vorhaben,
eine Visualisierungskomponente für OGC Web Map Services, ein Client zur Visualisierung von Zeitreihen sowie diverse An- und Abfrageschnittstellen,
die für die Recherche der angeschlossenen Komponenten, aber auch für die Weiterleitung der Ergebnisse an externe Systeme zuständig sind.


**Keyword**

Ein Keyword, Schlüsselwort, Schlagwort oder Suchbegriff dient dem gezielten Auffinden von Informationen über die Suche.


**Metadaten**

Metadaten oder Metainformationen sind strukturierte Daten, die Informationen über Merkmale anderer Daten enthalten.
Bei den durch Metadaten beschriebenen Daten handelt es sich oft um größere Datensammlungen wie z.B. Geodaten, Datenbanken, Literatur, Projekte, Organisationsstrukturen.


**Metadatenkatalog**

Der Metadatenkatalog ist eine Datenbank, diese beinhaltet Metadaten.


**Metadatensatz**

Ein Medatadensatz beschreibt die eigentlichen Daten(Recource) 
Metadatensätze können unterschiedliche Objektklassen (-typen) darstellen.
In METAVER werden die Objektlassen Geodatensatz, Geodatendienst, Anwendung, Datenbank, Dokument, Projekt und Organisationseinheit verwendet.
Je nach gewählter Objektklasse ändert sich die Eingabemaste für die Metadaten im Editor.


**METAVER - Metadatenverbund**

 - METAVER ist ein zentraler Zugangspunkt zu Metadaten der Länder: Brandenburg, Bremen, Hamburg, Hessen, Mecklenburg-Vorpommern, Saarland, Sachsen und Sachsen-Anhalt
 - Zum Einsatz kommt die Software: InGrid.
 - METAVER beinhaltet unterschiedliche Metadaten (Umweltdaten und Geodaten)
 - Ursprung: Umweltverwaltung - Beschreibung von Umweltdaten / Umweltinformationen (Umweltdatenkatalog)


**Suchoberfläche**

Unter Suchoberfläche ist eine Anwendung, die die technischen Requests (Anfragen) an die CSW-Schnittstelle schickt und die Responses (Antworten) in Empfang nimmt. Einerseits kann ein Suchender über die Suchoberfläche bestimmte Dinge auswählen (zum Beispiel Schlagwörter) oder eingeben (Suchbegriffe) und
die Suche auslösen. Die Suche schickt daraufhin die technische Anfrage an den oder die angeschlossenen CSW-Schnittstellen und erhält eine Antwort. Im Idealfall sind in der Antwort diejenigen Datenbeschreibungen aufgelistet, die der Suchanfrage entsprechen. Diese werden dann dem Nutzer über eine Oberfläche in angemessener Form präsentiert. Üblich ist, dass eine solche Suchoberfläche beispielsweise URLs als anklickbare Hyperlinks interpretiert, denn die meisten Suchoberflächen sind Browseranwendungen. Denkbar ist aber auch eine Suchoberfläche, die zum Beispiel direkt in einem Geoinformationssystem implementiert ist. Suchoberflächen richten sich stets nach den Bedürfnissen der jeweiligen Zielgruppe unter den Suchenden.


**Umweltdatenkatalog**

 - Der Umweltdatenkatalog ist eine Datenbank mit umweltrelevanten Metadaten.
 - Der Aufbau erfolgte an 1992 als Desktopanwendung.
 - Von 2006 - 2015 als Browser basierte Anwendung (Software InGrid) z.B. in Portal-U.
 - Ab 2015 Bildung der Länderkooperation METAVER,  Fortführung der Metadaten- bzw.Umweltdatenkataloge.
 - Neben Umweltdatenkatalogen in METAVER (vorher Portal-U) existieren auch eigenständige InGrid Installationen in einzelnen Ländern.


**UUID - Universal Unique IDentifer**

Die UUID ist ein Univrerseller Eindeutiger Identifikator (ID) für den Metadatensatz.

z.B. Objekt ID: 430D6C0D-FB79-46BA-AB30-9B248A31C798
 - Die UUID für einen Metadatensatz wird automatisch beim Abspeichern durch das Erfassungssystem vergeben.
 - Der Metadatensatz kann in unterschiedlichen Anwendungen eindeutig identifiziert werden.
 - Ein mehrfaches Anzeigen des Metadatensatzes (Dubletten) in Anwendungen, kann vermieden werden.
 - Über die Objekt-ID können Metadatensätze miteinander verknüpft werden (Daten-Dienste-Kopplung).
  
z.B. Identifikator einer Datenquelle: 2ed0f592-f586-4e78-9df0-1c21047a4757
Der Identifikator der Datenquelle wird manuell in einem Geodatensatz vergeben oder erzeugt und dient der Identifikation eines Metadatensatzes aus unterschiedlichen Anwendungen.
  
Der Unterschied zwischen den beiden UUIDs besteht in der Verwendung von großen und kleinen Buchstaben.
Die Objekt-UUID darf nicht die gleiche sein wie die UUID des Identifikators der Datenquelle.


**Webservice**

Ein Webservice ist ein Dienst im Internet für die Zusammenarbeit zwischen verschiedenen Anwendungen.


**XML - Extensible Markup Language - Erweiterbare Auszeichnungssprache**

XML ist eine Auszeichnungssprache zur Darstellung hierarchisch strukturierter Daten im Format einer Textdatei, die von Menschen und von Maschinen lesbar ist.
   
   

Geo-Glossar
-----------

**Daten-Dienste-Kopplung**

Die Daten-Dienste-Kopplung dient der Verküpfung (Verlinkung) von Geodatensätzen mit Godatendiensten. Die Verknüpfung funktioniert als Verweis vom Geodatensatz auf den Geodatendienst und umgekehrt.


**GDI**

GDI ist die Abkürzung für Geodateninfrastruktur.


**Geodatendienst**

 - ist ein vernetzbarer, raumbezogener Web-Services
 - macht Geodaten in strukturierter Form zugänglich
 - kann mehrere Kartenlayer enthalten
  
  
**Geodatenressourcen**

Werden alle Daten genannt, die man innerhalb einer Geodateninfrastruktur als Daten mit räumlichem Bezug (Geodaten) sieht. Üblicherweise unterscheidet man zwischen Geodaten (zum Beispiel Shape- oder Tiff-Dateien), Diensten (zum Beispiel WMS, WFS, CSW) und Fachinformationssystemen (zum Beispiel Viewer für
ein spezielles Fachthema). Gelegentlich können aber auch Tabellen oder Listen Merkmale aufweisen, die sie für die Nutzung in einer Geodateninfrastruktur qualifizieren. Um allen möglichen Datenquellen gerecht zu werden, spricht man im Fachjargon von „Geodatenressourcen“. Gleichzeitig zeigt dieser Begriff, dass Geodaten in Ihren unterschiedliche Ausprägungen durchaus als „Rohstoff“ zu sehen sind, die es gilt, weiter zu nutzen, zu verarbeiten oder zu veredeln.


**GetCapabilities**

Hierbei wird nach den Fähigkeiten des WMS gefragt. Als Antwort wird ein XML-Dokument an den Benutzer zurückgeschickt, das neben allgemeinen Angaben zum Anbieter des WMS die unterstützten Ausgabeformate des WMS zu den verschiedenen Anfragen sowie die abfragbaren Layer für die Karte beinhaltet.


**GetMap**

Diese Anfrage liefert ein georeferenziertes Rasterbild (Karte) vom WMS zurück. Innerhalb der Anfrage können u.a. Optionen über die gewünschten Kartenlayer, die gewünschte Darstellung der Layer, dem zugrundeliegenden Koordinatensystem, dem Kartenausschnitt, der Größe der Kartenausgabe und dem Ausgabeformat gemacht werden.


**GetFeatureInfo**

Ein WMS kann freiwillig Anfragen zu dem dargestellten Kartenausschnitt beantworten. Als Ausgabe liefert er festgelegte thematische Informationen der zugrundeliegenden Daten.


**Identifikator der Datenquelle**

Verweis auf eine Geodatenquelle (Ressource)
 - wird manuell bei der Datenerfassung in den Metadatenkatalog eingetragen
 - die Datenquelle (digitale Karte) erhält dadurch eine eindeutige Kennzeichnung
 - die Datenquelle kann in unterschiedlichen Anwendungen eindeutig identifiziert werden
  
  
**ISO-Norm 19115**

 - legt Standards für die Beschreibung von Geo-Informationen mit Metadaten fest
 - beschreibt den Mindestumfang und die Kategorien von Metadaten
 - unterscheidet zwischen verpflichtenden und optionalen Metadaten
 - beinhaltet Festlegungen für Geo-Datendienste


**ISO-Norm 19119**

 - ist ein Standard für Schnittstellen von Geodatendiensten
 - schafft die Voraussetzungen für den Austausch und die Darstellung von Geoinformationen über unterschiedliche Internet-Anwendungen
 
 
**Kartenlayer**

Kartenebenen oder -schichten (z.B. eine Ebene mit Straßen, eine Ebene mit Gewässern)


**OGC - Open Geospatial Consortium**

 - ist eine gemeinnützige Organisation
 - Mitglieder: Regierungsorganisationen, private Industrie und Universitäten
 - treibt die Entwicklung von raumbezogener Informationsverarbeitung (insbesondere Geodaten) voran
 - legt allgemeingültige Standards (ISO) zum Zweck der Interoperabilität von Daten fest
 - Ressource - Daten-Quelle (zu beschreibende Daten)


**WFS - WebFeatureService - Downloaddienst**

Der WFS ist ein Dienst zum herunterladen von Geodaten über das Internet.
   
   
**WKT - Well-known text**

WKT ist ein Format eines Datenbankfeldes für Geometriedaten in einer Datenbank mit räumlicher Erweiterung (z.B. Punkte, Linien, Polygone, ...). WKT ist aus der Simple Features Spezifikation des OGC hervorgegangen. 


**WMS - WebMapService - Darstellungsdienst**

Ein WMS ist ein Dienst zum Abrufen von Auszügen aus (Land-) Karten über das Internet.



Datenformate / Beschreibung
---------------------------

**Geo-Formate**

 - GeoPackage

 - FlatGeobuf
 
 - GeoJSON -  ist ein offenes Format, um geografische Daten nach der Simple-Feature-Access-Spezifikation zu repräsentieren. Dafür wird die JavaScript Object Notation verwendet
 
 - INTERLIS 1 - ist eine Datenbeschreibungssprache und ein Transferformat mit besonderer Berücksichtigung von Geodaten und der modellbasierten Methode
 
 - INTERLIS 2 - ist eine Datenbeschreibungssprache und ein Transferformat mit besonderer Berücksichtigung von Geodaten und der modellbasierten Methode
 
 - S-57 Base-Datei - ist eine internationale Norm zur Beschreibung von nautischen, hydrografischen und bathymetrischen Daten
 
 - TAB - Mapinfo - Tab (Büromaterial), ein Vorsprung in Karten und Mappen als Ordnungs- und Sortierhilfe
 

**ESRI**

 - .shp - Shapedatei -  ist ein auch in der Datenqualität einfaches Format für vektorielle Geodaten und Quasi-Standard im Umfeld von Desktop-Geoinformationssystemen mit dem größten Umfang verfügbarer Kartendaten.
 - ARC/INFO-Coverage - ist ein georelationales Datenmodell, das Vektordaten speichert; das heißt sowohl die räumlichen (Standort) als auch die attributiven (beschreibenden) Daten für geografische Merkmale.
 - E00-Austauschformat -  ArcInfo Interchange File ( ArcInfo-Export-Format ) ist ein proprietäres ESRI-Dateiformat, das die Übertragung verschiedener Arten von Geodaten, die in ESRI-Software verwendet werden, zwischen ESRI-Systemen unterstützen soll. - Wurde durch das ESRI Arc Geodatabase GeoDB-Datenmodell ersetzt
 - 3D-Shape
 
 
**QGIS**

 - .qgs


**Google**
 
 - GSV - Google Street View
 
 
**Microsoft**
 
 - SDB - SDB Dateien gehören meistens zu Windows von Microsoft. Die Dateinamenerweiterung SDB wird typischerweise mit Dateien assoziiert, die 3D-Modelle enthalten, die mit SAP2000, einer Software zur Strukturanalyse, erstellt wurden. 


**CAD-Formate**

 - .dxf - AutoCAD - Drawing Interchange File Format (AutoCAD)
 - .dgn - Microstation
 - Geoconcept - Anbieter spezieller Software-Lösungen für Vermessungsaufgaben auf der Basis von Autodesk®-Produkten


**Auszeichnungssprachen**

 - .html - Hypertext Markup Language
 - .gml - Geography Markup- ist eine Auszeichnungssprache zum Austausch raumbezogener Objekte.
 - .kml - Keyhole Markup Language
 - .xml - Extensible Markup Language
 - .gpx - GPS-Austauschformat - Datenformat zur Speicherung von Geodaten (ursprünglich hauptsächlich GPS-Daten), das von der Firma TopoGrafix entwickelt wurde. Es basiert auf dem allgemeinen XML-Standard. Ein XML Schema beschreibt die Elemente und den Aufbau des GPS Exchange Formats.

 - CityGML -  City Geography Markup Language

 
**Schemadefinitionen**
 
 - .xsd - XML Schema Definition
 
 
**Feed (XML) - Formate**
 
- .rss
- GeoRSS -  ist ein Standard, um mittels Web-Feeds eine Georeferenzierung zu übertragen. GeoRSS kann dabei durch Erweiterung von RSS 1.0, RSS 2.0 oder Atom benutzt werden.
- .atom
 

**Foto- / Grafikformate**

 - .bmp - Bitmap
 - .gif - Graphics Interchange Format
 - .jpg / .jpeg - Joint Photographic Experts Group
 - .png - Portable Network Graphics
 - .svg - Scalable Vector Graphics
 - .tiff - Tagged Image File Format
 
 
**Dokumentenformate**

Adobe

 - .pdf - Portable Document Format
 
Microsoft

 - .docx - MS-Word
 - .xlsx - MS-Excel


(Open)-Office

 - .ods - Open-Document-Tabelle


**ASCII - Formate**

 - ASCII - American Standard Code
 - GRID-ASCII
 - XYZ-ASCII-Rasterdatenformat
  
 
**X-Standardformate**
 
 - XPlanGML - raumbezogene Planwerke

 
**Datenbankformate**

 - PostgreSQL-SQL-Dump
 - SpartiaLite - GIS-Erweiterung für SQLite
 - SQLite - ist eine gemeinfreie Programmbibliothek, die ein relationales Datenbanksystem enthält. SQLite wird in Mobiltelefonen, in Browsern, Skype und vielen anderen Anwendungen eingesetzt.
 - MIF - Mapinfo - Karten- und Datenbank-Dateiformat für MapInfo-Software
 - EDBS - Einheitliche Datenbankschnittstelle
 - EPS - Encapsulated Postscript

 
**Programmiersprachen**

 - .json - JavaScript Object Notation
 - .php -  Hypertext Preprocessor“, ursprünglich „Personal Home Page Tools“ - ist eine Skriptsprache mit einer an C und Perl angelehnten Syntax, die hauptsächlich zur Erstellung dynamischer Webseiten oder Webanwendungen verwendet wird.
 
  
**Schnittstellen**
 
 - CSW - Catalogue Service for the Web - Internet-gestützte Veröffentlichung von Informationen über Geoanwendungen, Geodienste und Geodaten (Metadaten) in einer Geodateninfrastruktur. Wichtig ist, dass dieser Dienst selbst keine Geodaten enthält, sondern lediglich beschreibende Metadaten. Dieser Geodienst wurde durch das Open Geospatial Consortium (OGC) spezifiziert und unter der Version 2.0.0 veröffentlicht.
 
 - DCAT.AP - ist das gemeinsame deutsche Metadatenmodell zum Austausch von offenen Verwaltungsdaten. 
 
 - REST - Representational State Transfer 
 - SOAP - Simple Object Access Protocol
 - NAS - Normbasierte Austauschschnittstelle
 
 
**Künstliche Intelligenz**
 
 - AI - Artficial Intelligence - künstliche Intelligenz
  
 
**Komprimierungsformate**

 - .zip - (zipper - Reißverschluss) - Format für verlustfrei komprimierte Dateien


**sonstige**
  
 - GRID - Gitter, Raster
 
 - .csv - Comma-separated - Komma getrennte Werte

 

 
