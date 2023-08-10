
Der ATOM-Feed Client
^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: ../../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatendienst/atom-feed-client/atom-feed-client.png

Abb.: `Alle ATOM-Feed Client Nutzer <https://metaver.de/search/dls/>`_

Da die Webbrowser Atom-Feeds für den Datendownload  nur mit Erweiterungen unterstützen, wurde als Alternative der Webbasierte Atom-Feed Client bereitgestellt. Die Übernahme der Atom-Dienste aus dem InGrid Editor in den Atom-Feed Client erfolgt im InGrid Editor durch das Aktivieren des Feldes "Als ATOM-Download Dienst bereitstellen".

Der ATOM-Feed Client wurde an die Besonderheiten der Bundesländer und der Downloadserver angepasst. Folgende Bedingungen müssen erfüllt sein, damit ein Atom-Feed im Atom-Feed Client erscheint:


**Kopplung mit Geodatensatz**

  1. Der anzuzeigende Service muss von der Art “Download-Dienste” sein.
  2. Es muss die Option “Als ATOM-Download Dienst bereitstellen” aktiviert sein.
  3. Es muss mindestens eine Referenz auf ein Objekt vom Typ “Geodatensatz” vorhanden sein.
  4. Dieser Geodatensatz muss mindestens einen Verweis vom Typ “Download” besitzen.
  5. Ein angeschlossenes iPlug-DSC muss die Daten des IGC indexiert haben.


**Kopplung mit externem Datensatz**

  1. Der anzuzeigende Service muss von der Art “Download-Dienste” sein.
  2. Es muss die Option “Als ATOM-Download Dienst bereitstellen” aktiviert sein.
  3. Es muss mindestens ein externer Datensatz in den “gekoppelten Daten” hinzugefügt werden.
  4. Dieser Datensatz muss als URL die Zeichenkette “REQUEST=GetRecordById” enthalten.
  5. Ein angeschlossenes iPlug-DSC muss die Daten des IGC indexiert haben.


**Direkter Verweis auf externem Datensatz**

  1. Der anzuzeigende Service muss von der Art “Download-Dienste” sein.
  2. Es muss die Option “Als ATOM-Download Dienst bereitstellen” aktiviert sein.
  3. Es muss mindestens ein Verweis vom Typ “Datendownload” hinzugefügt werden.
  4. Dieser Verweis muss als URL die Zeichenkette “REQUEST=GetRecordById” enthalten.
  5. Ein angeschlossenes iPlug-DSC muss die Daten des IGC indexiert haben.


Folgende Partner-Bundesländer verfügen über den ATOM-Feed Client.

.. figure:: ../../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatendienst/atom-feed-client/atom-feed-client_bb.png

Abb.: `ATOM-Feed Client Brandenburg <https://metaver.de/search/dls/?partner=bb>`_


.. figure:: ../../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatendienst/atom-feed-client/atom-feed-client_hb.png
 
Abb.: `ATOM-Feed Client Hansestadt Bremen <https://metaver.de/search/dls/?partner=hb>`_


.. figure:: ../../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatendienst/atom-feed-client/atom-feed-client_hh.png

Abb.: `ATOM-Feed Client Hansestadt Hamburg <https://metaver.de/search/dls/?partner=hh>`_


.. figure:: ../../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatendienst/atom-feed-client/atom-feed-client_st.png

Abb.: `ATOM-Feed Client Sachsen-Anhalt <https://metaver.de/search/dls/?partner=st>`_


.. hint:: Änderungen in der URL des ATOM-Feed Clients mit der Taste F5 (Seite neu laden) abschließen. 
