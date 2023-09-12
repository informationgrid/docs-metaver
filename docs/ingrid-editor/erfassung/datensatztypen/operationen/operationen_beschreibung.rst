
Operationen
^^^^^^^^^^^

.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/fachbezug_operationen.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Feld - Operationen


In der Regel werden Geodatendienste mit dem GetCapabilities Assistent erstellt, da beim Aufruf des Dienstes die Metadaten angezeigt werden, die in den Editor übernommen werden können. Wenn der Dienst korrekt erstellt wurde und einen Identifikator für die Datenquelle enthält, können auch gleich die Geodatensätze angelegt werden.
(Beispiel: https://www.....de/wss/service/.._..._..._WMS_OpenData/.....?REQUEST=GetCapabilities&SERVICE=WMS)

Wenn der Metadatensatz ohne den Assistenten erstellt wurde, müssen die Felder für die Operationen ausgefüllt werden. Dabei ist darauf zu achten, dass die URL korrekt angegeben wird. Das bedeutet, dass nach dem Fragezeichen der Requestparameter für den Dienst angegeben werden muss.

Nach Eingabe der URL kann der Dienst über den Button "AKTUALISIEREN" am Anfang des Eingabeformulars aufgerufen werden. Wenn die URL korrekt eingegeben wurde, werden die Metadaten des Dienstes angezeigt und können in den Editor übernommen werden.

.. figure:: ../../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/fachbezug_funktionen.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Funktionen


.. hint:: Werden die Operationen aus dem Dienst in den Metadatensatz übernommen, stehen die Funktionen (z.B. WMS GetMap, GetFeatureInfo) nur im Editor zur Verfügung. Im Portal werden sie nicht angezeigt.