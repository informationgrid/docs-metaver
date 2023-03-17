
Der InGrid ATOM-Feed Client
^^^^^^^^^^^^^^^^^^^^^^^^^^^

Da die Webbrowser Atom-Feeds für den Datendownload  nur mit Erweiterungen unterstützen, wurde als Alternative der Webbasierte Atom-Feed Client bereitgestellt. Die Übernahme der Atom-Dienste aus dem InGrid Editor in den Atom-Feed Client erfolgt im InGrid Editor durch das Aktivieren des Feldes "Als ATOM-Download Dienst bereitstellen".

Folgende Partner-Bundesländer verfügen über den Atom-Feed Client.

 - https://metaver.de/search/dls/ - Alle

 - https://metaver.de/search/dls/?partner=bb - Brandenburg
 
 - https://metaver.de/search/dls/?partner=hb - Hansestadt Bremen
 
 - https://metaver.de/search/dls/?partner=hh - Hansestadt Hamburg

 - https://metaver.de/search/dls/?partner=st - Sachsen-Anhalt


**Hinweis:** *Änderungen in der URL mit der Taste F5 (Seite neu laden) abschließen.*

Folgende Bedingungen müssen erfüllt sein, damit ein Atom-Feed im Atom-Feed Client erscheint:


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
  
  


  
  