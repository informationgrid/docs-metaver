
Glossar allgemein
=================

Atom feed - [en]
----------------
Atom-Downloadservice - ist ein Dienst zum Herunterladen von Geodaten.
Atom Feed ist ein XML -Format, das von Nutzern verwendet werden kann, um über neue Inhalte einer Website informiert zu werden.
Nutzer können einen Atom-Feed abonnieren und mithilfe eines entsprechenden Atom-Feed-Readers oder eines Atom Feed Clients (InGrid) neue Inhalte von Websites in Kurzform betrachten,
und mithilfe des Feeds Dateien als Download anbieten.


Atom feed Client
----------------
   - ist eine Anwendung in METAVER zum Download von Daten. Diese Anwendung erkleichtert dem Nutzer den Umgang mit Atom feeds.


CSW - Catalogue Service Web [en] - (Katalogschnittstelle)
---------------------------------------------------------
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


Dublette
--------
   - ist ein mehrfach vorhandener Metadatensatz.


Harvesting [en] - Abernten
--------------------------
Im Rahmen des Harvestings werden Metadatensätze von einem Metadatenkatalog für einen anderen eingesammelt.
Das Original verbleibt im Original-Katalog und wird dort aktualisiert.
Durch den Metadatensatzidentifikator (UUID) und das hinterlegte
Datum der letzten Änderung am Metadatensatz ist sichergestellt, dass der Datensatz nicht
nur im Original-Katalog sondern auch - zeitversetzt - im harvestenden Katalog aktualisiert
wird. Metadaten sind damit die einzigen Daten in einer Geodateninfrastruktur, die gezielt
kopiert werden, um den Nutzern zur Verfügung zu stehen.
Durch ein Harvesting dürfen Metadaten eines fremden Katalogs niemals abgeändert werden.
Die meisten derzeit aktiven Kataloge halten sich an diese Vorgabe.


HTML - Hypertext Markup Language [en] 
-------------------------------------
   - dient der Strukturierung von Texten und Bildern (vorwiegend im Intranet/Internet).

  
InGrid - InformationGrid [en] 
-----------------------------
InGrid ist eine modular aufgebaute Software, die vielseitig eingesetzt werden kann: Kernkomponenten sind ein Web-Portal,
eine Suchmaschine, ein Metadatenkatalog mit Profilen für die Erfassung INSPRE-konformer Metadaten, offener Daten und UVP-Vorhaben,
eine Visualisierungskomponente für OGC Web Map Services, ein Client zur Visualisierung von Zeitreihen sowie diverse An- und Abfrageschnittstellen,
die für die Recherche der angeschlossenen Komponenten, aber auch für die Weiterleitung der Ergebnisse an externe Systeme zuständig sind.


Keyword [en]
------------
Schlüsselwort, Schlagwort oder Suchbegriff dient dem gezielten Auffinden von Informationen über die Suche.


Metadaten
---------
Metadaten oder Metainformationen sind strukturierte Daten, die Informationen über Merkmale anderer Daten enthalten.
Bei den durch Metadaten beschriebenen Daten handelt es sich oft um größere Datensammlungen wie z.B. Geodaten, Datenbanken, Literatur, Projekte, Organisationsstrukturen.


Metadatenkatalog
----------------
   - ist eine Datenbank, diese beinhaltet Metadaten.


Metadatensatz
-------------
Ein Medatadensatz beschreibt die eigentlichen Daten(Recource) 
Metadatensätze können unterschiedliche Objektklassen (-typen) darstellen.
In METAVER werden die Objektlassen Geodatensatz, Geodatendienst, Anwendung, Datenbank, Dokument, Projekt und Organisationseinheit verwendet.
Je nach gewählter Objektklasse ändert sich die Eingabemaste für die Metadaten im Editor.


METAVER - Metadatenverbund
--------------------------
   - Zentraler Zugangspunkt zu Metadaten der Länder: Brandenburg, Bremen, Hamburg, Hessen, Mecklenburg-Vorpommern, Saarland, Sachsen und Sachsen-Anhalt
   - Software: InGrid
   - beinhaltet unterschiedliche Metadaten (Umweltdaten und Geodaten)
   - Ursprung: Umweltverwaltung - Beschreibung von Umweltdaten / Umweltinformationen (Umweltdatenkatalog)


Netz [de]
---------
   - Web [en] - Netzwerk/Gespinst z.B. Word Wide Web
   - Net [en] - Netz/Netzwerk z.B. Internet
   - Grid [en] - Gitter/Raster z.B. InformationGrid (InGrid)


Suchoberfläche
--------------
Unter Suchoberfläche ist eine Anwendung, die die
technischen Requests (Anfragen) an die CSW-Schnittstelle schickt und die Responses
(Antworten) in Empfang nimmt. Einerseits kann ein Suchender über die Suchoberfläche
bestimmte Dinge auswählen (zum Beispiel Schlagwörter) oder eingeben (Suchbegriffe) und
die Suche auslösen. Die Suche schickt daraufhin die technische Anfrage an den oder die
angeschlossenen CSW-Schnittstellen und erhält eine Antwort. Im Idealfall sind in der Antwort
diejenigen Datenbeschreibungen aufgelistet, die der Suchanfrage entsprechen. Diese
werden dann dem Nutzer über eine Oberfläche in angemessener Form präsentiert. Üblich
ist, dass eine solche Suchoberfläche beispielsweise URLs als anklickbare Hyperlinks
interpretiert, denn die meisten Suchoberflächen sind Browseranwendungen. Denkbar ist
aber auch eine Suchoberfläche, die zum Beispiel direkt in einem Geoinformationssystem
implementiert ist. Suchoberflächen richten sich stets nach den Bedürfnissen der jeweiligen
Zielgruppe unter den Suchenden.


Umweltdatenkatalog
------------------
   - ist eine Datenbank mit umweltrelevanten Metadaten
   - Aufbau 1992 als Desktopanwendung
   - 2006 - 2015 als Browserbasierte Anwendung (Software InGrid) z.B. in Portal-U
   - ab 2015 Bildung der Länderkooperation METAVER,  Fortführung der Metadaten-/Umweltdatenkataloge
   - neben Umweltdatenkatalogen in METAVER (vorher Portal-U) existieren auch eigenständige InGrid Intallationen in einzelnen Ländern


UUID - Universal Unique IDentifer [en]
--------------------------------------
  - ist ein Univrerseller Eindeutiger Identifikator (ID) für den Metadatensatz.

z.B. Objekt ID: 430D6C0D-FB79-46BA-AB30-9B248A31C798
  - Die UUID für einen Metadatensatz wird automatisch beim Abspeichern durch das Erfassungssystem vergeben.
  - Der Metadatensatz kann in unterschiedlichen Anwendungen eindeutig identifiziert werden.
  - Ein mehrfaches Anzeigen des Metadatensatzes (Dubletten) in Anwendungen, kann vermieden werden.
  - Über die Objekt-ID können Metadatensätze miteinander verknüpft werden (Daten-Dienste-Kopplung).
  
z.B. Identifikator einer Datenquelle: 2ed0f592-f586-4e78-9df0-1c21047a4757
  - Der Identifikator der Datenquelle wird manuell in einem Geodatensatz vergeben oder erzeugt und dient der Identifikation eines Metadatensatzes aus unterschiedlichen Anwendungen.
  
Der Unterschied zwischen den beiden UUIDs besteht in der Verwendung von großen und kleinen Buchstaben.
Die Objekt-UUID darf nicht die gleiche sein wie die UUID des Identifikators der Datenquelle.


Webservices [en]
----------------
 - ist ein Dienst im Internet für die Zusammenarbeit zwischen verschiedenen Anwendungen.


XML - Extensible Markup Language [en] - Erweiterbare Auszeichnungssprache
-------------------------------------------------------------------------
   -  ist eine Auszeichnungssprache zur Darstellung hierarchisch strukturierter Daten im Format einer Textdatei, die von Menschen und von Maschinen lesbar ist.