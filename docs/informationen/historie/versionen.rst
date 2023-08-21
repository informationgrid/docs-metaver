
InGrid Versionen
================

Version der Bedienungsanleitung
   - InGrid-Version: 1.4.1-126, 09.08.2023, 18:19
   - letzte Änderung: 21.08.2023
   - Status: in Bearbeitung


Installierte IGE-NG-Testversion AP5
- InGrid-Version: 1.3.1-193

auf metaver.de
   - InGrid-Version: 6.1.1
   - Update wurde installiert am: 10.05.2023


Installierte InGrid-Version auf test.metaver.de
   - InGrid-Version: 6.1.1
   - Update wurde installiert am: 10.05.2023
   - Datenbestand vom: 04.10.2022


InGrid-Version von Entwicklern für die Installation breitgestellt
   - InGrid Portal-Version: 6.1.1
   - InGrid Editor-Version: 6.1.1
   - Release: 



**Änderungen in den InGrid Versionen (IGE Classic)**

(Ausfühliche Informationen auf GitHub: https://www.ingrid-oss.eu/latest/about/history.html)


Version IGE-NG: 1.3.1-193, 12.06.2023, 12:00

--------------------------------------------------------------------------------------------------------------

Version 6.0.1.1, Release 02.03.2023

   - IGE: Korrektur Regionalschlüssel erfassen - Minimallösung

Version 6.0.0, Release 13.01.2023

   - Upgrade von JAVA 8 auf JAVA 17
   - Aktualisierung der verwendeten Elasticsearch Version

Liste der Änderungen

   - IGE: AdV-Checkbox nur in Objektarten Geodatendienst, Geodatensatz und Anwendung sichtbar machen
   - IGE: Anpassung der Liste "AdV-Produktgruppe"
   - IGE: Hilfetext zum Feld "Durch die Ressource abgedeckte Zeitspanne" anpassen
   - IGE: Regionalschlüssel erfassen - Minimallösung
   - PORTAL: Portalanzeige Koordinatensysteme


Profil MetaVer

    - MAPCLIENT: Kartenclient METAVER - Webatlas farbe/grau ersetzen durch basemap.de Web Raster farbe/grau
    - PORTAL: Verbesserung Startseite MetaVer - Feld für Wartungsarbeiten einfügen


InGrid Editor Version 5.14.4 (24.11.2022)
	

Version 5.12 (12.04.2022)
   
    - IGE: Manuelle Erfassung der Regionalschlüssel in den Raumbezügen
    - IGE/Portal: Leaflet - Karte Raumbezüge - Austausch OSM Karte gegen TopPlusOpen Light grau
    - Mapclient: Standard Hintergrundkarte: TopPlusOpen Light grau, Auswahl: TopPlusOpen Light grau, TopPlusOpen Light farbig, TopPlusOpen grau, TopPlusOpen farbig, Webatlas grau, Webatlas farbig
	 

Version: 5.11.2 (18.02.2022)
   
    - IGE: Feld Kurzbezeichnung unter die Tabelle Vorschaugrafik verschoben
    - IGE: Umgang mit WKT-Geometrien (Well known text) verbessert - Konvertierung WKT - GML
    - IGE: Feld "Fachliche Grundlage" - Label, Hilfetext und Verpflichtung überarbeiten
    - IGE: Angabe in XML-Element "geographicIdentifier" (Raumbezug) - differenzierter befüllen
    - IGE: Erweiterung der Liste der Referenzsysteme (EPSG 4327)
    - IGE: Anpassung der OpenData Kategorien an den GovData Standard
    - IGE: CodeListService um Getter für CodeListEntry ergänzt
    - Portal: Anpassung der Zeitbezüge in "Durch die Ressource abgedeckte Zeitspanne"
    - Portal: Verweise auf externe Webseiten in einen neuen Tab öffnen
    - Portal: Button Karte - Karte in einen neuen Tab öffnen
    - Mapclient: Erweiterung der Druckfunktion mit der Auswahl DPI
    - Mapclient: Geschützte Dienste können über die bestehende Import-Funktion des Mapclients hinzugefügt werden (gilt für WMS, WMTS, KML und GPX).


Version: 5.10.1.2 (13.12.2021)
	
    - Mapclient: Import von geschützten Diensten

Version: 5.10 (21.10.2021)
   
    - IGE: Anpassung der Zeitbezüge in "Durch die Ressource abgedeckte Zeitspanne"
    - IGE: Extern-gekoppelte Datensätze werden regelmäßig analysiert
    - IGE: Namensnennung 3.0 Deutschland (CC BY 3.0 DE) in Codeliste "Nutzungsbedingungen" aufnehmen
    - Portal:
      
		**Umsetzung Verbesserung der Suche in den InGrid Komponenten**
		
		Durch den Boost auf Suchfelder können Ergebnisse abhängig davon, wo der Suchbegriff vorkommt, gewichtet werden.
		Suche als Such-Phrase - Suche nach Titeln, die Zeichen mit einer Sonderfunktion (z.B. Bindestrich oder Doppelpunkt) innerhalb der Suche beinhalten.
		Bessere Durchmischung der Ergebnisse aus verschiedenen Quellen.
	  
		**Ersetzen des Analyzers**
		
		Hierdurch werden auch Wortteile gefunden, die durch die bisherige Worttrennung nicht erfasst wurden.
		Wortteile am Anfang des Wortes können stärker gewichtet werden als Wortteile, die im Wort enthalten sind.
			

Version: 5.9.2 (11.10.2021)
   
    - Portal: ReDesign MetaVer
    - Portal: Umsetzung der Konzeption der verbesserten Darstellung von Detaildaten im Portal 
    - Portal: Verbesserung der Barrierefreiheit von metaver.de
    - Mapclient: Verbesserte Hintergrundkarten für MetaVer - Umstellung von OSM auf TopPlusOpen (BKG)
    - Mapclient: nach dem Laden eines WMS die Struktur der Layer anzeigen
    - Mapclient: Komprimierung von weiteren URL Parametern beim Aufruf von WMS Karten mit vielen Layern
    - Mapclient: Beim Hinzufügen eines Kartendienstes aus der Suche oder Detaildarstellung können die Layer jetzt interaktiv gewählt werden 
    - Mapclient: Per Button-Klick können alle Layer hinzugefügt werden
    - Mapclient: Einzelne Layer können direkt mittels ihres Identifiers hinzugefügt werden (ohne vorherige Auswahl)
    - Mapclient: alle geladene Layer deaktiviren / alle geladenen Layer löschen    
    - IGE: Neue Opendata-Lizenzen für die Codeliste "Nutzungsbedingungen"
    - IGE: Vorschaugrafiken können im IGE abgelegt und verwaltet werden
    - IGE: Tabelle für Vorschaugrafiken eingefügt
	 

Version: 5.8.1  (26.05.2021)
   
    - IGE: WCS-Dienst mit GetCapabilities-Assistent erfassen
    - IGE: Zusätzlicher Wert in Codeliste “Datenformat - Name” (GeoTIFF)
    - IGE: Validierung GML+Version für INSPIRE-relevante Datensätze entfernen
    - IGE: Erfassung von Metadaten in English
    - Portal: Anpassung des Kontaktformulars für das Ticketsystem Zammad
	 
 
Version: 5.7 (09.02.2021)
   
    - IGE: Abgabe von gekoppelten Daten über den Dienste-Datensatz, wenn Kopplung über Kataloggrenzen hinweg erfolgt
    - IGE: Anpassung der Codeliste “Provider”
	 
   
Version: 5.6.4 (05.12.2020) 
   
    - IGE: Erweiterung der Codlist "Nutzungsbedingungen" (Lizenzen) um den Eintrag "Nutzung der Daten nur nach Rücksprache mit dem Dateneigentümer"
    - IGE: Qualitätsangaben erweitern - neue MD-Felder
    - IGE: Maßstabsangabe für Objektart Dienst im Katalog ausgeben
    - IGE: Capabilities Assistent soll WFS Capabilities nach Spezifikation 2.0.2 verarbeiten können
    - IGE: Verhalten der Checkbox "OpenData" - nur wenn Checkbox "INSPIRE-relevant" aktiviert, dann das Feld Zugriffsbeschränkungen automatisch mit "Es gelten keine Zugriffsbeschränkungen" befüllen
    - IGE: Feld "Datengrundlage" in mehrzeiliges Feld ändern
    - Portal: Darstellung von InGrid Editor-Ordnern in der Datenkatalogansicht
    - Portal: Umbenennung des Änderungsdatums in der Portaldarstellung
	 
   
Version: 5.5.1 (29.09.2020)
   
    - Portal: Darstellung von mehreren Vorschaugrafiken
    - Mapclient: Erweiterung Import von WMTS mit GetFeatureInfo-Funktion


 




