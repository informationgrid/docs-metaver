
Datendownloads mit einen ATOM-Feed bereitstellen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

In der Geodateninfrastruktur ist ein ATOM-Downloaddienst ein Dienst für den Download von Geodaten, der meist im Zusammenhang mit der Geodatenbereitstellung als Open Data bzw. der Geodatenbereitstellung nach der INSPIRE-Richtlinie verwendet wird.

 
Was ist ein ATOM-Feed?
""""""""""""""""""""""

Ein ATOM-Feed ist ein (XML-) Format, das von Benutzern verwendet werden kann, um über neue Inhalte einer Website informiert zu werden.

Benutzer können einen ATOM-Feed, mit Hilfe eines ATOM-Feed-Readers (Browsererweiterung) abonnieren.

Ein ATOM-Feed ermöglicht, mit Hilfe eines ATOM-Feed-Readers oder des `ATOM-Feed Clients <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/ATOM-feed/client.html>`_, eine plattformunabhängige Beschreibung und den Download von Geodaten.


Abschnitt Fachbezug
^^^^^^^^^^^^^^^^^^^

.. important:: Für ATOM-Downloaddienste, die im ATOM-Feed Client erscheinen sollen, muss im Objekttyp Geodatensatz (im Abschnitt "Verweise") eine Download-URL angelegt werden.


Erfassung/Erzeugung eines ATOM-Feeds
""""""""""""""""""""""""""""""""""""

Folgende Voraussetzungen müssen erfüllt sein, damit ATOM-Feeds erstellt und über den `ATOM-Feed Client <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/ATOM-feed/client.html>`_ bereitgestellt werden können:

**a) Kopplung des Geodatendienstes mit einem Geodatensatz aus dem gleichen Katalog**

  1. Als *Klassifikation des Dienstes* muss "Dienst für den Zugriff auf Objekte" ausgewählt werden.
  2. Als *Art des Dienstes* muss "Download-Dienste" ausgewählt werden.
  3. Als *Version des Dienstes* muss "predefined ATOM" ausgewählt werden.
  4. Es muss die *Option* "Als ATOM-Download Dienst bereitstellen" aktiviert sein.
  5. Unter *Operationen* müssen als *Name* "Get Download Service Metadata" gewählt, die Beschreibung eingetragen und eine entsprechende URL eingetragen werden.
  6. Als *Dargestellte Daten* muss "Geodatensatz auswählen" ausgewählt werden.
  7. Als *Kopplungstyp* muss "tight" angegeben sein.
  8. Aus der erscheinenden Ordnerstruktur muss der entsprechende Geodatensatz ausgewählt werden, mit dem der Downloaddienst gekoppelt werden soll.
  9. Dieser Geodatensatz muss mindestens einen Verweis vom *Typ* "Datendownload" besitzen.
  10. InGrid muss die Daten eingelesen (indexiert) haben.


**b) Kopplung des Geodatendienstes mit einem externem Geodatensatz**

  1. Als *Klassifikation des Dienstes* muss "Dienst für den Zugriff auf externe Daten und Programme" gewählt werden.
  2. Als *Art des Dienstes* muss "Download-Dienste" ausgewählt werden.
  3. Als *Version des Dienstes* muss "predefined ATOM" gewählt werden.
  4. Es muss die *Option* "Als ATOM-Download Dienst bereitstellen" aktiviert sein.
  5. Unter *Operationen* müssen als *Name* "Get Download Service Metadata" gewählt, die Beschreibung eingetragen und eine entsprechende URL eingetragen werden.
  6. Als *Dargestellte Daten* muss "Geodatensatz auswählen" ausgewählt werden. 
  7. Als *Kopplungstyp* muss "tight" angegeben sein.
  8. In dem erscheinenden Fenster muss die URL zum entsprechenden Geodatensatz eingetragen werden, mit dem der Downloaddienst gekoppelt werden soll.
  9. Dieser Geodatensatz muss als URL die Zeichenkette "REQUEST=GetRecordById" enthalten.
  10. InGrid muss die Daten eingelesen (indexiert) haben.


**c) Direkter Verweis auf einen externem Geodatensatz**

  1. Als *Klassifikation des Dienstes* muss "Dienst für den Zugriff auf externe Daten und Programme" gewählt werden.
  2. Als *Art des Dienstes* muss "Download-Dienste" ausgewählt werden.
  3. Als *Version des Dienstes* muss "predefined ATOM" gewählt werden.
  4. Es muss mindestens ein Verweis vom Typ “Datendownload” hinzugefügt werden.
  5. Dieser Verweis muss als URL die Zeichenkette “REQUEST=GetRecordById” enthalten.
  6. InGrid muss die Daten eingelesen (indexiert) haben.


Anmerkungen zur Download-URL
""""""""""""""""""""""""""""

Die Daten, welche für den Download bereitgestellt werden sollen, müssen über das Internet verfügbar sein und über eine URL direkt abrufbar sein. Dabei ist es egal, ob die Daten gezippt oder ungezipt bereitgestellt werden.

Beispiel: Formate für den Daten-Download: .gml, .tif, .shp, .zip

GetFeature-Request werden dagegen nicht ausgewertet. Der Service-Feed enthält hierbei zwar den Verweis zum Daten-Feed, ruft man aber den Daten-Feed auf, so fehlt der Link zum Download. 

Beispiel: https://www.host.de/.../downloads/name_der_datei.zip