
Datendownloads mit einem ATOM-Feed bereitstellen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

In der Geodateninfrastruktur handelt es sich bei einem ATOM-Downloaddienst um einen Service zum Herunterladen von Geodaten, der hauptsächlich im Kontext der Open Data Geodatenbereitstellung oder im Rahmen der Umsetzung der INSPIRE-Richtlinie zum Einsatz kommt.

 
Was ist ein ATOM-Feed?
""""""""""""""""""""""

Ein ATOM-Feed ist ein (XML-) Format, das Benutzern ermöglicht, sich über neue Inhalte einer Website zu informieren.

Benutzer können einen ATOM-Feed mithilfe eines Browser-Plugins für ATOM-Feed-Reader abonnieren. Es ist ratsam, eine Browsererweiterung zu verwenden, um dies problemlos durchzuführen und die automatischen Updates zu erhalten.

Ein Atom-Feed erlaubt mithilfe eines Atom-Feed-Readers oder eines `ATOM-Feed Clients <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/ATOM-feed/client.html>`_ eine plattformunabhängige Beschreibung und den Download von Geodaten.


Abschnitt Fachbezug
^^^^^^^^^^^^^^^^^^^

.. important:: Für ATOM-Downloaddienste, die im ATOM-Feed Client erscheinen sollen, muss im Geodatensatz (im Abschnitt "Verweise") eine Download-URL eingetragen werden.


Erfassung/Erzeugung eines ATOM-Feeds
""""""""""""""""""""""""""""""""""""

Damit ATOM-Feeds über den `ATOM-Feed Client <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/ATOM-feed/client.html>`_ bereitgestellt werden können, müssen bestimmte Voraussetzungen erfüllt sein.


Die Felder im Abschnitt Fachbezug sollen wie folgt ausgefüllt werden:

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

Die für den Download bereitgestellten Daten müssen über das Internet verfügbar sein und über eine URL direkt abrufbar sein. Dabei spielt es keine Rolle, ob die Daten gezippt oder ungezippt zur Verfügung gestellt werden.

Beispiel-Formate für den Daten-Download: .zip, .gml, .tif, .shp, ...

Beispiel-URL: https://www.host.de/.../downloads/name_der_datei.zip


GetFeature-Requests werden nicht ausgewertet. Der Service-Feed enthält den Verweis zum Daten-Feed, jedoch fehlt der Download-Link, wenn der Daten-Feed aufgerufen wird. 


.. hint:: Das Ausfüllen der allgemeinen Felder erfolgt gemäß den Angaben unter `Metadaten erfassen <https://metaver-bedienungsanleitung.readthedocs.io/de/hmdk/ingrid-editor/erfassung/erfassung-metadaten.html>`_. Für die Spezialfelder sind die Vorgaben unter `Datensatztyp / Geodatendienst <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/datensatztyp-geodatendienst.html>`_ zu beachten.


.. important:: Sollten Schwierigkeiten bei der Erstellung eines ATOM-Download-Services auftreten, kontaktieren Sie bitte über das `METAVER Kontaktformular <https://metaver.de/kontakt>`_ Ihren zuständigen Katalogadministrator (bitte das Bundesland angeben).