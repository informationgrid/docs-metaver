
Datendownloads mit einem ATOM-Feed bereitstellen
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

Folgende Voraussetzungen müssen erfüllt sein, damit ATOM-Feeds erstellt und über den `ATOM-Feed Client <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/ATOM-feed/client.html>`_ bereitgestellt werden können.

Die Felder (im Abschnitt Fachbezug) müssen wie folgt befüllt werden:

**Variante 1) Kopplung des Geodatendienstes mit einem Geodatensatz aus dem gleichen Katalog**

  1. Klassifikation des Dienstes: Dienst für den Zugriff auf Objekte
  2. Art des Dienstes: Download-Dienste
  3. Version des Dienstes: predefined ATOM
  4. Option: "Als ATOM-Download Dienst bereitstellen" muss aktiviert sein.
  5. Operationen - Name: Get Download Service Metadata, Beschreibung: eingetragen, Zugriffs-URL: entsprechende URL eintragen
  6. Dargestellte Daten: Geodatensatz
  7. Kopplungstyp: tight
  8. Es öffnet sich ein Fenster, aus der Ordnerstruktur muss der entsprechende Geodatensatz ausgewählt werden, mit dem der Downloaddienst gekoppelt werden soll.
  9. Dieser Geodatensatz muss mindestens einen Verweis vom Typ "Datendownload" besitzen.
  10. InGrid muss die Daten eingelesen (indexiert) haben.


**Variante 2) Kopplung des Geodatendienstes mit einem externem Geodatensatz**


  1. Klassifikation des Dienstes: Dienst für den Zugriff auf Objekte
  2. Art des Dienstes: Download-Dienste
  3. Version des Dienstes: predefined ATOM
  4. Option: "Als ATOM-Download Dienst bereitstellen" muss aktiviert sein.
  5. Operationen - Name: Get Download Service Metadata, Beschreibung: eingetragen, Zugriffs-URL: entsprechende URL eintragen
  6. Dargestellte Daten: Geodatensatz
  7. Kopplungstyp: tight
  8. Es öffnet sich ein Fenster, hier muss die URL zum entsprechenden Geodatensatz eingetragen werden, mit dem der Downloaddienst gekoppelt werden soll.
  9. Dieser Geodatensatz muss als URL die Zeichenkette "REQUEST=GetRecordById" enthalten.
  10. InGrid muss die Daten eingelesen (indexiert) haben.



**Variante 3) Direkter Verweis auf einen externem Geodatensatz**

  1. Klassifikation des Dienstes: Dienst für den Zugriff auf Objekte
  2. Art des Dienstes: Download-Dienste
  3. Version des Dienstes: predefined ATOM
  4. Es muss im Abschnitt Verweise eine "Download-URL" hinzugefügt werden.
  5. Dieser Verweis muss als URL die Zeichenkette "REQUEST=GetRecordById" enthalten.
  6. InGrid muss die Daten eingelesen (indexiert) haben.


Anmerkungen zur Download-URL
""""""""""""""""""""""""""""

Die Daten, welche für den Download bereitgestellt werden, müssen über das Internet verfügbar sein und über eine URL direkt abrufbar sein. Dabei ist es egal, ob die Daten gezippt oder ungezipt bereitgestellt werden.

Beispiel-Formate für den Daten-Download: .zip, .gml, .tif, .shp, ...

Beispiel-URL: https://www.host.de/.../downloads/name_der_datei.zip


GetFeature-Request werden dagegen nicht ausgewertet. Der Service-Feed enthält hierbei zwar den Verweis zum Daten-Feed, ruft man aber den Daten-Feed auf, so fehlt der Link zum Download. 


.. hint:: Die allgemeinen Felder sind wie unter `Metadaten erfassen <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/erfassung-metadaten.html>`_, die Spezialfelder wie unter `Datensatztyp / Geodatendienst <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/datensatztyp-geodatendienst.html>`_ beschrieben, zu befüllen.