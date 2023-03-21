
Download-Dienste als ATOM-Feed bereitstellen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
 
Atom-Feed - ASF - Atom Syndication Format
'''''''''''''''''''''''''''''''''''''''''

Dieses XML-Format, ermöglicht den plattformunabhängigen Austausch von Informationen z. B. für Web-Feeds.

INSPIRE-relevante Daten, welche durch Daten-Metadaten beschrieben sind, müssen über Download-Dienste verfügbar gemacht werden. Zu den möglichen Download-Diensten zählen auch die sogenannten ATOM-Feeds. 
Mit der InGrid-Software wird die automatische Bereitstellung von Download-Diensten basierend auf ATOM-Feeds realisiert. Auf diesem Weg ist es möglich, die Anforderungen durch INSPIRE hinsichtlich der Download-Dienste zu erfüllen.
 
Die Grundidee dabei ist, dass vom Metadaten-Erfasser im InGrid-Editor Serivce-Metadaten für einen oder mehrere Download-Dienste angelegt werden. Mit diesen Objekten werden Daten-Metadaten als gekoppelte Ressourcen verknüpft. Für jeden dieser Download-Service-Metadatensätze wird durch einen Webservice (bzw. eine Service-Fassade) ein solcher Download-Dienst automatisch bereitgestellt. Hierzu wird dynamisch der Service-Feed erzeugt. 

Alle an dieses Service-Metadatenobjekt gekoppelten Daten-Metadaten werden im Service-Feed eingetragen. Für jeden Daten-Metadatensatz kann sodann ein Daten-Feed abgerufen werden, dessen URL als entry-Element des Service-Feeds annonciert wird. Im Daten-Feed werden alle Download-Optionen für diesen Datensatz eingetragen. 

Folgende Voraussetzungen müssen durch den Metadaten-Erfasser erfüllt sein, damit automatisiert ATOM-Feeds erstellt werden können. 


Art des Dienstes
''''''''''''''''

Neben den üblichen Pflichtfeldern ist darauf zu achten, dass bei "Art des Dienstes" der Wert "Download-Dienste" ausgewählt und die darunter liegende Checkbox "Als ATOM-Download-Dienst bereitstellen" gesetzt wird. 

Als ATOM-Download Dienst bereitstellen
'''''''''''''''''''''''''''''''''''''''

Bei aktivierter Option, wird dieser Datensatz im Portal als Download angeboten. Zusätzlich wird die in den Katalogeinstellungen hinterlegte "ATOM-Downloadservice-URL" automatisch in das ISO-Format unter "distributionInfo/*/linkage" abgebildet.

 
Version des Dienstes
'''''''''''''''''''''

Angaben zu Version der dem Dienst zugrunde liegenden Spezifikation.

Eintrag: predefineted ATOM

 
Name der Operation
'''''''''''''''''''

Bei ATOM-Downloaddiensten, die nicht über den InGrid Editor generiert und die im Rahmen von INSPIRE bereitgestellt werden, ist als Name der Operation "Get Download Service Metadata" auszuwählen.

Zugriffsadresse
''''''''''''''''

Eindeutige URL über die die Operation aufgerufen werden kann.

**Beispiel:** https://www.host.de/.../downloads/name_der_datei.zip


Unterstützte Plattformen
''''''''''''''''''''''''
Angaben zur Art der Plattform bzw. Schnittstelle über die der Dienst angesprochen werden kann.
Auswahl: WebService


Download-URL
''''''''''''

Die Daten, welche für den Download bereitgestellt werden sollen, müssen über das Internet verfügbar sein und über eine URL direkt abrufbar sein. Dabei ist es egal, ob die Daten gezippt oder ungezipt bereitgestellt werden.

 
**Beispiel:** *Formate für den Daten-Download: .shp, .zip*

GetFeature-Request werden dagegen nicht ausgewertet. Der Service-Feed enthält hierbei zwar den Verweis zum Daten-Feed, ruft man aber den Daten-Feed auf, so fehlt der Link zum Download. 

**Beispiel:** GetFeature-Request: https://www.geodatenportal.sachsen-anhalt.de/wss/service/INSPIRE_LAU_Schutzgebiete_WFS/guest? 