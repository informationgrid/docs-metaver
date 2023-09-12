Operationen
^^^^^^^^^^^

.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/fachbezug_operation_aktualisieren.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Feld - Operationen

Angabe von Operationen für Webservices wie GetMap, GetCapabilities und getFeatureInfo. Neue Operationen können entweder über den GetCapabilities-Assistenten beim Erstellen des Objekts oder manuell über den Link "Operation hinzufügen" eingegeben werden. 


 
Operation bearbeiten
""""""""""""""""""""

.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/operationen_operation-bearbeiten.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Feld - Operation bearbeiten

Bestehende Operationen können bearbeitet werden, indem der entsprechende Eintrag in der Liste mit der rechten Maustaste angeklickt und aus dem Kontextmenü die Funktion „Zeile bearbeiten“ ausgewählt wird. (rechte Maustaste) gewählt wird. Es öffnet sich ein separater Dialog mit folgenden Feldern.


Name der Operation
""""""""""""""""""

.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/operationen_name-der-operation.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Feld - Name der Operation

`Auswahlliste - Name der Operation <https://metaver-bedienungsanleitung.readthedocs.io/de/latest/metaver_ige/ige_auswahllisten/auswahlliste_fachbezug_geodatendienst_operation_name.html>`_

Name der Funktion/Operation, die von einem Dienst bereitgestellt wird. Hier muss eine eindeutige Kennung für den beschriebenen Vorgang eingegeben werden.


Zugriffsadresse
"""""""""""""""

.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/operationen_operation.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Feld - Zugriffsadresse


Eindeutige URL, unter der die Operation aufgerufen werden kann.

Beispiel: https://my.host.com/cgi-bin/mapserv?map=mywms.map&


Unterstützte Plattformen
""""""""""""""""""""""""

.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/operationen_unterstuetzte-plattformen.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Auswahlliste - Unterstützte Plattformen


`Auswahlliste - Unterstützte Plattformen <https://metaver-bedienungsanleitung.readthedocs.io/de/latest/metaver_ige/ige_auswahllisten/auswahlliste_fachbezug_geodatendienst_operation_unterstuetzte-plattformen.html>`_


Angaben zur Art der Plattform oder Schnittstelle, über die der Dienst angesprochen werden kann.


.. note:: Beispiel: HTTPGet oder WebServices (WMS, WFS, Atom)


Parameter
"""""""""

.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/operationen_parameter.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Operation bearbeiten

Mögliche Parameter, die bei einem Aufruf der Operation übergeben werden können:

  - Parametername und gegebenenfalls Zuweisung eines Wertes (in der Form Name=Wert, siehe Beispiel unten)
  - Richtung des Datenflusses, der durch diesen Parameter erzeugt wird.
  - Textliche Beschreibung des Parameters.
  - Optionalität: Angabe, ob der Parameter angegeben werden muss oder nicht.
  - Angabe, ob eine Mehrfacheingabe des Parameters möglich ist.


Beispiel:

Name: REQUEST=GetCapabilities
Richtung:
Beschreibung: Name of request
Optional: Nein
Mehrfacheingabe: Nein


GetCapabilities-Request-Parameter angeben
"""""""""""""""""""""""""""""""""""""""""

.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/operationen_parameter-weglassen.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Parameter

.. important:: Im neuen InGrid Editor muss die URL in den Operationen korrekt angegeben werden.

Es ist darauf zu achten, dass in der URL nach dem Fragezeichen der Requestparameter angegeben wird. (z.B.: https://www.....de/wss/service/WMS_OpenData/guest?REQUEST=GetCapabilities&SERVICE=WMS) Ist die URL korrekt angegeben, so kann dies durch Drücken der Schaltfläche AKTUALISIEREN, am Anfang des Eingabeformulars, überprüft werden. Ist die URL korrekt, werden die Metadaten des Dienstes abgerufen. Andernfalls wird eine Fehlermeldung angezeigt.



Aufruf
""""""

.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/operationen_aufruf.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Aufruf

Eindeutiger Funktionsname, mit dem die Operation aufgerufen werden kann. Für OGC Web Services sind die jeweils spezifizierten REQUEST-Aufrufe zu verwenden.


Beispiel: GetMap oder GetCapabilities oder GetFeatureInfo


Beschreibung
""""""""""""


.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/operationen_beschreibung.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Beschreibung

Textliche Beschreibung der Funktionalität der Operation.

 
Beispiel: Die GetMap Operation des WMS gibt eine Raster-Repräsentation der in "Basisdaten" beschriebenen digitalen Karte zurück.


Abhängigkeiten
""""""""""""""


.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/operationen_abhaengigkeiten.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Abhängigkeiten


Die Namen der Operationen, die vor dem Ausführen der aktuellen Operation ausgeführt werden müssen, wenn die Operation als Teil einer Service Chain genutzt werden soll.


Beispiel: Die Operation "GetMap" ist abhängig von der Operation "GetCapabilities".


Durch das Anklicken der Schaltfläche "Hinzufügen" übernehmen Sie die geänderten Daten in die Tabelle "Operationen". Zum Löschen einer Operation aus der Tabelle wählen Sie die Funktion "Zeile Löschen" aus dem Kontextmenü (rechte Maustaste). 


Aktualisieren von Operationen und Metadaten
"""""""""""""""""""""""""""""""""""""""""""

.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/operationen_aktualisierung.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Aktualisierung

Unter der Tabelle Operationen befindet sich der Button "Aktualisieren". 
Dieser bewirkt, dass die Informationen in dem Metadatenobjekt aus dem Capabilities-Dokument des Dienstes auf den neuesten Stand gebracht werden. Die Aktualisierung erfolgt genau wie die Initialisierung eines neuen Objektes mit dem GetCapabilities-Assistenten. 


.. warning:: Alle im Assistenten ausgewählten Felder werden bei der Aktualisierung ohne Ausnahme überschrieben. Wenn im Vorfeld an einem der im Folgenden genannten Felder manuell Änderungen hinzugefügt wurden, so gehen diese verloren und müssen gegebenenfalls neu eingetragen werden!

.. hint:: Eine Aktualisierung über den Assistenten ist nur möglich, wenn der Dienst nicht geschützt ist. Sollen nur die Operationen aktualisiert werden, dürfen keine Metadaten im GetCapabilities-Assistenten ausgewählt werden!
 
 
.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/fachbezug/operationen_aktualisierung_hinweis.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Dieser Hinweis kann bei der Aktualisierung einer Operation erscheinen.