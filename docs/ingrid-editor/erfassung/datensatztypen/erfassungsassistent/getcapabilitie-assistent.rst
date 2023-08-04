

Der GetCapabilitie-Assistent
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: ../../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatendienst/assistent/getcapabilties-assistent_symbol.png
   :width: 50
   
Abb.: GetCapabilitie-Assistent - Symbol (Zauberstab)

Wird für einem Geodatendienst ein neuer Metadatensatz erstellt, kann für die Erfassung der Metadaten der getCapabilties-Assistent (Symbol Zauberstab in der Symbolleiste) verwendet werden.

Der GetCapabilities-Assistent ist ein Erfassungsassistent, der Metadatenerfasser bei der Erstellung von Metadaten zu Geodatendiensten unterstützt.

Startern Sie den Assistenten über das Symbol Zauberstab in der Symbolleiste. Geben Sie in das Fenster die getCapability-URL des Dienstes ein und betätigen Sie den Button "ÜBERNEHMEN".


.. figure:: ../../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatendienst/assistent/getcapabilties-assistent_url.png

   
Abb.: GetCapabilitie-Assistent - URL Eingabe


Der Assistent ruft den Dienst über die eingetragene URL ab und zeigt alle in der getCapability verfügbaren Metadaten an. Der Erfasser kann dann die Metainformationen auswählen, die in das Erfassungsformular übernommen werden sollen.


.. figure:: ../../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatendienst/assistent/getcapabilties-assistent_metadaten.png


Abb.: GetCapabilitie-Assistent - Metadaten


Der getCapabilties-Assistent ruft die Metadaten aus der XML des Geodatendienstes ab. Diese können für das Befüllen des Datensatztyps "Geodatendienst" verwendet werden.

.. figure:: ../../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatendienst/assistent/getcapabilties-assistent_metadaten-auswahl.png

   
Abb.: GetCapabilitie-Assistent - Metadatenauswahl


.. figure:: ../../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatendienst/assistent/getcapabilties-assistent_metadaten-uebernommen.png

   
Abb.: GetCapabilitie-Assistent - übernommene Metadaten


Der "getCapabilities Assistent" unterstützt folgende Dienste-Typen:

 - WMS - Web Map Service
 - WMTS - Web Map Tile Service
 - WFS - Web Feature Service
 - WCS - Web Coverage Service
 - WCS-T - Web Coverage Service – Transaktion
 - CSW - Catalogue Service for the Web
 
Eine Ausnahme ist der Atom-Feed, dieser kann nicht über den GetCapabilitie Assistent abgerufen bzw. erstellt werden.









Geben Sie die getCapability-URL des Dienstes ein und betätigen Sie den Button "Erstellen". Der Assistent ruft den Dienst über die eingetragene URL ab und zeigt alle in der getCapability verfügbaren Informationen an. Der Erfasser kann dann die Metainformationen auswählen, die in ddas Objekt übernommen werden sollen.

Für die automatische Erzeugung von Geodatensätzen aus den Layern der WMS Dienste müssen diese einen Identifier unter dem Pfad folgenden Pfaden haben:

 - WMS Version 1.3.0: /wms:WMS_Capabilities/wms:Capability/wms:Layer/.../wms:Identifier
 - WMS Version 1.1.1: /WMT_MS_Capabilities/Capability/Layer/.../Identifier

Mit Start wird der Assistent gestartet, die Informationen vom Service abgerufen und ein neues Objekt mit den erhaltenen Informationen erstellt.

Mit der Funktion Abbrechen am Ende der Seite schließen Sie den Assistenten und starten mit einem leeren Objekt.
