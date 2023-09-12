
Option: InVekoS
---------------

InVekoS - Bedeutung
^^^^^^^^^^^^^^^^^^^

InVeKoS - Integriertes Verwaltungs- und Kontrollsystem in Agrarsektor


.. note:: Das InVeKoS ist ein System von Verordnungen zur Durchführung einer einheitlichen Agrarpolitik in den Mitgliedstaaten der Europäischen Union. Die schrittweise Einführung des Integrierten Verwaltungs- und Kontrollsystems durch die Europäische Kommission wurde im Zuge der Reform der Gemeinsamen Agrarpolitik (GAP) im Jahr 1992 beschlossen. Das InVeKoS ist ein wesentliches Instrument zur Kontrolle der Agrarausgaben der EU. Die durch das InVeKoS gewonnenen Daten fließen in das Rechnungsabschlussverfahren der EU ein. Konzeption, Koordinierung und Kontrolle des InVeKoS erfolgen durch die Europäische Kommission, die konkrete Umsetzung obliegt den EU-Mitgliedstaaten. (Quelle: `Wikipedia <https://de.wikipedia.org/wiki/Integriertes_Verwaltungs-_und_Kontrollsystem>`_)

.. hint:: Nachfolgend werden die Felder beschrieben, die nach der Aktivierung dieser Option zusätzlich in der Erfassungsmaske befüllt werden müssen.

-----------------------------------------------------------------------------------------------------------------------

Erfassung
^^^^^^^^^

Checkbox InVeKoS
""""""""""""""""

.. figure:: ../../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/option/invekos/checkbox-invekos.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Checkbox InVeKoS

-----------------------------------------------------------------------------------------------------------------------


Die EU-Kommission erwartet eine INSPIRE-Kompatibilität der GIS-InVeKoS-Daten. Dies bedeutet zunächst die Bereitstellung von Metadaten zu den relevanten Daten.

Die Anforderungen an die InVeKoS-Metadaten wurden von der GDI-DE im April 2023 bekannt gegeben. Demnach sind folgende Schlüsselwörter zu verwenden.

**InVeKoS/IACS**

Integrated Administration and Control System

**InVeKoS/IACS (GSAA)**

Geospatial Aid Application (Antrag auf raumbezogene Hilfe)

**InVeKoS/IACS (LPIS)**

Land Parcel Identification System (Identifizierung landwirtschaftlicher Parzellen)

In der Testsuite der GDI-DE ist die Testklasse bereits eingerichtet (`GDI-DE Testsuite <https://testsuite.gdi-de.org/#/quicktest>`_, Auswahl „ST34_INSPIRE…“) und somit eine Kompatibilitätsprüfung möglich.

-----------------------------------------------------------------------------------------------------------------------

Auswahlliste
'''''''''''''

**InVeKoS**

**Definition:**
Integriertes Verwaltungs- und Kontrollsystem gemäß Artikel 67 der Verordnung (EG) Nr. 1306/2013

**Beschreibung:**
Von den Mitgliedstaaten angewendetes System für bestimmte Zahlungen gemäß der Verordnung (EU) Nr. 1307/2013 und der Verordnung (EU) Nr. 1305/2013




**LPIS**

**Definition:**
System zur Identifizierung landwirtschaftlicher Parzellen, ein Teilsystem des Integrierten Verwaltungs- und Kontrollsystems (InVeKoS) wie in Artikel 68 der Verordnung (EG) Nr. 1306/2013 definiert. Subsystem des InVeKoS im Sinne von Artikel 68 der Verordnung (EG) Nr. 1306/2013.

**Beschreibung:**
Geodatensatz mit der Abgrenzung von Referenzparzellen, Arten landwirtschaftlicher Flächen und stabilen im Umweltinteresse genutzten Flächen.


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



**Landwirtschaftliche Fläche**

**Definition:**
Flächen, die als Ackerland, Dauergrünland, Dauerweideland oder Dauerkulturen genutzt werden.

**Beschreibung:**
Flächen, die von diesen Bodenbedeckungstypen oder deren Subtypen (enger gefasste Kategorien) mit ausgewiesenen Landschaftselementen und/oder Bäumen, die zu diesen Flächen gehören, genutzt werden.



**Referenzparzelle**

**Definition:**
Geografisch abgegrenzte Fläche, die eine eindeutige Identifizierung und einen für eine Beihilfezahlung ausgleichsfähigen Flächenwert aufweist

**Beschreibung:**
Grundlegende räumliche Einheit für die Verwaltung und geografische Lokalisierung landwirtschaftlicher Parzellen. Kann eine oder mehrere im InVeKoS erklärte landwirtschaftliche Parzellen enthalten und kann von einem oder mehreren Betriebsinhabern bewirtschaftet werden