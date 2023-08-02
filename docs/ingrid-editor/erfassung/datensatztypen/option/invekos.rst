
Option: InVekoS
---------------

InVekoS - Bedeutung
^^^^^^^^^^^^^^^^^^^

InVeKoS - Integriertes Verwaltungs- und Kontrollsystem


Grundlage
^^^^^^^^^

InVeKoS ist ein System von Verordnungen zur Durchsetzung einer einheitlichen Agrarpolitik in den Mitgliedstaaten der Europäischen Union. Die schrittweise Einführung des Integrierten Verwaltungs- und Kontrollsystems durch die Europäische Kommission wurde im Zuge der Reform der Gemeinsamen Agrarpolitik (GAP) im Jahre 1992 beschlossen.

InVeKoS ist ein wesentliches Kontrollinstrument für die Agrarausgaben der EU. Die durch das InVeKoS ermittelten Daten fließen in das Rechnungsabschlussverfahren der EU ein.

Die Konzeption, Koordinierung sowie Kontrollfunktionen des InVeKoS erfolgen durch die Europäische Kommission, für die konkrete Umsetzung sind die EU-Mitgliedstaaten zuständig.

(Quelle: `Wikipedia <https://de.wikipedia.org/wiki/Integriertes_Verwaltungs-_und_Kontrollsystem>`_)

-----------------------------------------------------------------------------------------------------------------------

Die EU-Kommission erwartet eine INSPIRE-Kompatibilität der GIS-InVeKoS-Daten. Zunächst bedeutet dies die Bereitstellung von Metadaten zu den relevanten Daten.

Die Anforderungen an InVeKoS-Metadaten wurden seitens der GDI-DE im April 2023 kommuniziert. Demnach sind Keywords einer entsprechenden codelist (INSPIRE-registry unter https://inspire.ec.europa.eu/metadata-codelist/IACSData) zu verwenden.

In die Systeme und Teilsysteme gemäß Artikel 68 der Verordnung (EU) Nr. 1306/2013 eingegebene Geodaten.

InVeKoS besteht aus elektronischen Datenbanken der Teilsysteme. Das System zur Identifizierung landwirtschaftlicher Parzellen (besser bekannt als LPIS – System zur Identifizierung landwirtschaftlicher Parzellen) und die Teilsysteme Beihilfeanträge und Zahlungsanträge des InVeKoS enthalten die Geodatenkomponenten.

InVeKoS/IACS - Integrated Administration and Control System
InVeKoS/IACS (GSAA) - Geospatial Aid Application (Antrag auf raumbezogene Hilfe)
InVeKoS/IACS (LPIS) - Land Parcel Identification System (Identifizierung landwirtschaftlicher Parzellen)

In der Testsuite der GDI-DE ist die Testklasse bereits eingerichtet (`GDI-DE Testsuite <https://testsuite.gdi-de.org/#/quicktest>`_, Auswahl „ST34_INSPIRE…“) und somit eine Kompatibilitätsprüfung möglich.


Erfassung
^^^^^^^^^

Checkbox InVeKoS
''''''''''''''''

.. image:: ../../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/option/invekos/checkbox-invekos.png
  :width: 150

Abb.: Checkbox InVeKoS

-----------------------------------------------------------------------------------------------------------------------

Auswahlliste
'''''''''''''

**GSAA**

**Definition:**
Geodatenbezogener Beihilfeantrag als Teil des Teilsystems „Beihilfeanträge“ des InVeKoS gemäß Artikel 68 der Verordnung (EG) Nr. 1306/2013.

**Beschreibung:**
Abgrenzung landwirtschaftlicher Parzellen mit Kulturpflanzen oder Kulturgruppen gemäß den Angaben des Betriebsinhabers in einem bestimmten Jahr


**Im Umweltinteresse genutzte Fläche**

**Definition:**
In die Systeme und Teilsysteme gemäß Artikel 68 der Verordnung (EU) Nr. 1306/2013 eingegebene Geodaten.

**Beschreibung:**
Das Integrierte Verwaltungs- und Kontrollsystem (InVeKoS) besteht aus elektronischen Datenbanken der Teilsysteme. Das System zur Identifizierung landwirtschaftlicher Parzellen (besser bekannt als LPIS – System zur Identifizierung landwirtschaftlicher Parzellen) und die Teilsysteme Beihilfeanträge und Zahlungsanträge des InVeKoS enthalten die Geodatenkomponenten.


**InVeKoS**

**Definition:**
Integriertes Verwaltungs- und Kontrollsystem gemäß Artikel 67 der Verordnung (EG) Nr. 1306/2013

**Beschreibung:**
Von den Mitgliedstaaten angewendetes System für bestimmte Zahlungen gemäß der Verordnung (EU) Nr. 1307/2013 und der Verordnung (EU) Nr. 1305/2013


**Landwirtschaftliche Fläche**

**Definition:**
Flächen, die als Ackerland, Dauergrünland, Dauerweideland oder Dauerkulturen genutzt werden.

**Beschreibung:**
Flächen, die von diesen Bodenbedeckungstypen oder deren Subtypen (enger gefasste Kategorien) mit ausgewiesenen Landschaftselementen und/oder Bäumen, die zu diesen Flächen gehören, genutzt werden.


**LPIS**

**Definition:**
System zur Identifizierung landwirtschaftlicher Parzellen, ein Teilsystem des Integrierten Verwaltungs- und Kontrollsystems (InVeKoS) wie in Artikel 68 der Verordnung (EG) Nr. 1306/2013 definiert. Subsystem des InVeKoS im Sinne von Artikel 68 der Verordnung (EG) Nr. 1306/2013.

**Beschreibung:**
Geodatensatz mit der Abgrenzung von Referenzparzellen, Arten landwirtschaftlicher Flächen und stabilen im Umweltinteresse genutzten Flächen.


**Referenzparzelle**

**Definition:**
Geografisch abgegrenzte Fläche, die eine eindeutige Identifizierung und einen für eine Beihilfezahlung ausgleichsfähigen Flächenwert aufweist

**Beschreibung:**
Grundlegende räumliche Einheit für die Verwaltung und geografische Lokalisierung landwirtschaftlicher Parzellen. Kann eine oder mehrere im InVeKoS erklärte landwirtschaftliche Parzellen enthalten und kann von einem oder mehreren Betriebsinhabern bewirtschaftet werden