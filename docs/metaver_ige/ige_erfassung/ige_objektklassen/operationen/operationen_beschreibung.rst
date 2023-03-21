Operationen
^^^^^^^^^^^

.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/fachbezug_operation_aktualisieren.png

Abb.: Feld - Operationen

Angabe von Operationen bezüglich Webdiensten wie GetMap, GetCapabilities und getFeatureInfo. Neue Operationen können entweder über den GetCapabilities-Assistenten beim Neuanlegen des Objektes eingetragen werden, oder aber manuell über den Link "Operation hinzufügen". 

 
Operation bearbeiten
'''''''''''''''''''''

.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/operationen_operation-bearbeiten.png

Abb.: Feld - Operation bearbeiten

Bestehende Operation können bearbeitet werden, indem der entsprechende Eintrag in der Liste mit der rechten Maustaste angeklickt und die Funktion „Zeile bearbeiten“ aus dem Kontextmenü ausgewählt wird. (rechte Maustaste). Es öffnet sich ein separater Dialog mit folgenden Feldern.


Name der Operation
''''''''''''''''''

.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/operationen_name-der-operation.png


Abb.: Feld - Name der Operation

`Auswahlliste - Name der Operation <https://metaver-bedienungsanleitung.readthedocs.io/de/latest/metaver_ige/ige_auswahllisten/auswahlliste_fachbezug_geodatendienst_operation_name.html>`_

Name der von einem Dienst bereitgestellten Funktion/Operation. Hier muss ein eindeutiger Bezeichner für die beschriebene Operation eingegeben werden.


Zugriffsadresse
'''''''''''''''

.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/operationen_operation.png

Abb.: Feld - Zugriffsadresse


Eindeutige URL über die die Operation aufgerufen werden kann.


Beispiel: https://my.host.com/cgi-bin/mapserv?map=mywms.map&


Unterstützte Plattformen
''''''''''''''''''''''''

.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/operationen_unterstuetzte-plattformen.png


Abb.: `Auswahlliste - Unterstützte Plattformen <https://metaver-bedienungsanleitung.readthedocs.io/de/latest/metaver_ige/ige_auswahllisten/auswahlliste_fachbezug_geodatendienst_operation_unterstuetzte-plattformen.html>`_


Angaben zur Art der Plattform bzw. Schnittstelle über die der Dienst angesprochen werden kann.


.. note:: Beispiel: HTTPGet oder WebServices (WMS, WFS, Atom)


Parameter
'''''''''


.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/operationen_parameter.png

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


GetCapabilities-Request-Parameter weglassen
'''''''''''''''''''''''''''''''''''''''''''

.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/operationen_parameter-weglassen.png

Abb.: Parameter weglassen


Der GetCapabilities-Assistent füllt für Objekte des Typs Geodatendienst u.a. auch die Tabelle „Operationen“ aus. Die Zugriffsadresse endet mit: „?“. 
Dies ist eine Forderung der ISO. 

Die Request-Parameter (z.B. REQUEST=GetCapabilities&SERVICE=WMS) sollen daher auch nicht manuell nachgetragen werden. Für die Darstellung in der Detailansicht im Portal werden die Parameter automatisch an die Zugriffsadresse angehängt - auch für gekoppelte Daten.

Sollten die Parameter noch in Geodatendiensten, Tabelle "Operationen" vorhanden sein, so sind diese zu löschen. Streng genommen sind die Objekte, bei denen die Parameter in der Zugriffsadresse enthalten sind, nicht ISO-konform.


Aufruf
''''''

.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/operationen_aufruf.png

Abb.: Aufruf

Eindeutiger Funktionsname über den die Operation aufgerufen werden kann. Bei OGC Web-Diensten sind die jeweiligen spezifizierten REQUEST-Aufrufe zu verwenden.


Beispiel: GetMap oder GetCapabilities oder GetFeatureInfo


Beschreibung
''''''''''''


.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/operationen_beschreibung.png

Abb.: Beschreibung

Textliche Beschreibung der Funktionalität der Operation.

 
Beispiel: Die GetMap Operation des WMS gibt eine Raster-Repräsentation der in "Basisdaten" beschriebenen digitalen Karte zurück.


Abhängigkeiten
''''''''''''''


.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/operationen_abhaengigkeiten.png

Abb.: Abhängigkeiten


Die Namen der Operationen, die vor dem Ausführen der aktuellen Operation ausgeführt werden müssen, wenn die Operation als Teil einer Service Chain genutzt werden soll.


Beispiel: Die Operation "GetMap" ist abhängig von der Operation "GetCapabilities".


Durch das Anklicken der Schaltfläche "Hinzufügen" übernehmen Sie die geänderten Daten in die Tabelle "Operationen". Zum Löschen einer Operation aus der Tabelle wählen Sie die Funktion "Zeile Löschen" aus dem Kontextmenü (rechte Maustaste). 


Aktualisieren von Operationen und Metadaten
'''''''''''''''''''''''''''''''''''''''''''

.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/operationen_aktualisierung.png

Abb.: Aktualisierung

Unter der Tabelle Operationen befindet sich der Button "Aktualisieren". 
Dieser bewirkt, dass die Informationen in dem Metadatenobjekt aus dem Capabilities-Dokument des Dienstes auf den neuesten Stand gebracht werden. Die Aktualisierung erfolgt genau wie die Initialisierung eines neuen Objektes mit dem GetCapabilities-Assistenten. 


.. warning:: Alle im Assistenten ausgewählten Felder werden bei der Aktualisierung ohne Ausnahme überschrieben. Wenn im Vorfeld an einem der im Folgenden genannten Felder manuell Änderungen hinzugefügt wurden, so gehen diese verloren und müssen gegebenenfalls neu eingetragen werden!

.. hint:: Eine Aktualisierung über den Assistenten ist nur möglich, wenn der Dienst nicht geschützt ist. Sollen nur die Operationen aktualisiert werden, dürfen keine Metadaten im GetCapabilities-Assistenten ausgewählt werden!
 
 
.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/fachbezug/operationen_aktualisierung_hinweis.png
 
Abb.: Dieser Hinweis kann bei der Aktualisierung einer Operation erscheinen.
