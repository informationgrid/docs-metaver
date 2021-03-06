
Glossar-Geometadaten
====================

Daten-Dienste-Kopplung
----------------------
   - dient der Verküpfung (Verlinkung) von Geodatensätzen mit Godatendiensten. Die Verknüpfung funktioniert als Verweis vom Geodatensatz auf den Geodatendienst und umgekehrt.
   
GDI
---
   - ist die Abkürzung für Geodateninfrastruktur.


Geodatendienst
--------------
Internet-Dienstleistung für die Darstellung einer digitalen Karte
  - ist ein vernetzbarer, raumbezogener Web-Services
  - macht Geodaten in strukturierter Form zugänglich
  - kann mehrere Kartenlayer enthalten
  
  
Geodatenressourcen
------------------
Werden alle Daten genannt, die man innerhalb einer
Geodateninfrastruktur als Daten mit räumlichem Bezug (Geodaten) sieht. Üblicherweise
unterscheidet man zwischen Geodaten (zum Beispiel Shape- oder Tiff-Dateien), Diensten
(zum Beispiel WMS, WFS, CSW) und Fachinformationssystemen (zum Beispiel Viewer für
ein spezielles Fachthema). Gelegentlich können aber auch Tabellen oder Listen Merkmale
aufweisen, die sie für die Nutzung in einer Geodateninfrastruktur qualifizieren. Um allen
möglichen Datenquellen gerecht zu werden, spricht man im Fachjargon von
„Geodatenressourcen“. Gleichzeitig zeigt dieser Begriff, dass Geodaten in Ihren
unterschiedliche Ausprägungen durchaus als „Rohstoff“ zu sehen sind, die es gilt, weiter zu
nutzen, zu verarbeiten oder zu veredeln.


GetCapabilities [en]
--------------------
Hierbei wird nach den Fähigkeiten des WMS gefragt. Als Antwort wird ein XML-Dokument an
den Benutzer zurückgeschickt, das neben allgemeinen Angaben zum Anbieter des WMS die
unterstützten Ausgabeformate des WMS zu den verschiedenen Anfragen sowie die
abfragbaren Layer für die Karte beinhaltet.


GetMap [en]
-----------
Diese Anfrage liefert ein georeferenziertes Rasterbild (Karte) vom WMS zurück. Innerhalb
der Anfrage können u.a. Optionen über die gewünschten Kartenlayer, die gewünschte
Darstellung der Layer, dem zugrundeliegenden Koordinatensystem, dem Kartenausschnitt,
der Größe der Kartenausgabe und dem Ausgabeformat gemacht werden.


GetFeatureInfo [en]
-------------------
Ein WMS kann freiwillig Anfragen zu dem dargestellten Kartenausschnitt beantworten. Als
Ausgabe liefert er festgelegte thematische Informationen der zugrundeliegenden Daten.


Identifikator der Datenquelle
-----------------------------
Verweis auf eine Geodatenquelle (Ressource)
  - wird manuell bei der Datenerfassung in den Metadatenkatalog eingetragen
  - die Datenquelle (digitale Karte) erhält dadurch eine eindeutige Kennzeichnung
  - die Datenquelle kann in unterschiedlichen Anwendungen eindeutig identifiziert werden
  
  
ISO-Norm 19115
--------------
  - legt Standards für die Beschreibung von Geo-Informationen mit Metadaten fest
  - beschreibt den Mindestumfang und die Kategorien von Metadaten
  - unterscheidet zwischen verpflichtenden und optionalen Metadaten
  - beinhaltet Festlegungen für Geo-Datendienste


ISO-Norm 19119
--------------
  - ist ein Standard für Schnittstellen von Geodatendiensten
  - schafft die Voraussetzungen für den Austausch und die Darstellung von Geoinformationen über unterschiedliche Internet-Anwendungen
 
 
Kartenlayer
-----------
Kartenebenen oder -schichten (z.B. eine Ebene mit Straßen, eine Ebene mit Gewässern)


OGC - Open Geospatial Consortium [en]
--------------------------------------
  - ist eine gemeinnützige Organisation
  - Mitglieder: Regierungsorganisationen, private Industrie und Universitäten
  - treibt die Entwicklung von raumbezogener Informationsverarbeitung (insbesondere Geodaten) voran
  - legt allgemeingültige Standards (ISO) zum Zweck der Interoperabilität von Daten fest
  - Ressource - Daten-Quelle (zu beschreibende Daten)


WFS - WebFeatureService [en] - Downloaddienst
----------------------------------------------
   - ist ein Dienst zum herunterladen von Geodaten über das Internet.
   
   
WKT - Well-known text [en]
--------------------------
   - ist ein Eingabeformat eines Datenbankfeldes für Geometriedaten in einer Datenbank mit räumlicher Erweiterung (z.B. Punkte, Linien, Polygone, ...). WKT ist aus der Simple Features Spezifikation des OGC hervorgegangen. 


WMS - WebMapService [en] - Darstellungsdienst
---------------------------------------------
   - ist ein Dienst zum Abrufen von Auszügen aus Landkarten über das Internet.
