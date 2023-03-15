
Der InGrid ATOM-Feed Client
^^^^^^^^^^^^^^^^^^^^^^^^^^^

Da die Webbrowser Atom-Feeds kaum noch direkt unterstützen, wurde als Alternative der InGrid Atom-Feed Client bereitgestellt. Die Übernahme der Atom-Dienste aus dem InGrid Editor in den Atom-Feed Client erfolgt im InGrid Editor durch das Aktivieren des Feldes "Als ATOM-Download Dienst bereitstellen".

**Beispiel URL:** https://metaver.de/search/dls/#?partner=st 

**Hinweis:** *Änderungen in der URL mit der Taste F5 (Seite neu laden) abschließen.*

**Beispiel:** https://metaver.de/search/dls/#?serviceId=F3B1E711-7F7F-4E16-A15F-5C39ED0CF9F9&partner=st 

**Beispiel:** https://metaver.de/search/dls/#?serviceId=F3B1E711-7F7F-4E16-A15F-5C39ED0CF9F9&datasetId=E7222818-65AB-4482-9850-73A4744C2BFE&partner=st
 
Folgende Bedingungen müssen erfüllt sein, so dass ein Dienst mit seinen Download-Referenzen angezeigt wird:


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