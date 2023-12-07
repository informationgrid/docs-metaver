
Option: InVekoS
---------------

InVekoS - Bedeutung
^^^^^^^^^^^^^^^^^^^

InVeKoS - Integriertes Verwaltungs- und Kontrollsystem in Agrarsektor


.. note:: Das InVeKoS ist ein System von Verordnungen zur Durchführung einer einheitlichen Agrarpolitik in den Mitgliedstaaten der Europäischen Union. Die schrittweise Einführung des Integrierten Verwaltungs- und Kontrollsystems durch die Europäische Kommission wurde im Zuge der Reform der Gemeinsamen Agrarpolitik (GAP) im Jahr 1992 beschlossen. Das InVeKoS ist ein wesentliches Instrument zur Kontrolle der Agrarausgaben der EU. Die durch das InVeKoS gewonnenen Daten fließen in das Rechnungsabschlussverfahren der EU ein. Konzeption, Koordinierung und Kontrolle des InVeKoS erfolgen durch die Europäische Kommission, die konkrete Umsetzung obliegt den EU-Mitgliedstaaten. (Quelle: `Wikipedia <https://de.wikipedia.org/wiki/Integriertes_Verwaltungs-_und_Kontrollsystem>`_)

Nachfolgend wird die Funktionalität InVeKoS beschrieben.

-----------------------------------------------------------------------------------------------------------------------

Erfassung
^^^^^^^^^

Auswahlfeld InVeKoS
"""""""""""""""""""

.. figure:: ../../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/option/invekos/auswahlfeld-invekos.png
   :align: left
   :scale: 100
   :figwidth: 100%

Abb.: Auswahlfeld InVeKoS

-----------------------------------------------------------------------------------------------------------------------


Die EU-Kommission erwartet eine INSPIRE-Kompatibilität der GIS-InVeKoS-Daten. Dies bedeutet zunächst die Bereitstellung von Metadaten zu den relevanten Daten.

Die Anforderungen an die InVeKoS-Metadaten wurden von der GDI-DE im April 2023 bekannt gegeben.

Folgende Funktionalitäten sind hinterlegt.

**InVeKoS/IACS** - Integrated Administration and Control System

**InVeKoS/IACS (GSAA)** - Geospatial Aid Application (Antrag auf raumbezogene Hilfe)

Dem Datensatz werden folgende Schlagworte hinzugefügt:

| InVeKoS: InVeKoS + GSAA
| Gemet: Gemeinsame Agrarpolitik
| ISO-Themenkategorie: Landwirtschaft
| INSPIRE-Themen: Bodennutzung


**InVeKoS/IACS (LPIS)** - Land Parcel Identification System (Identifizierung landwirtschaftlicher Parzellen)

Dem Datensatz werden folgende Schlagworte hinzugefügt:

| InVeKoS: InVeKoS + LPIS
| Gemet: Gemeinsame Agrarpolitik
| ISO-Themenkategorie: Landwirtschaft
| INSPIRE-Themen: Bodenbedeckung

In der Testsuite der GDI-DE ist die Testklasse bereits eingerichtet (`GDI-DE Testsuite <https://testsuite.gdi-de.org/#/quicktest>`_, Auswahl „ST34_INSPIRE…“) und somit eine Kompatibilitätsprüfung möglich.

-----------------------------------------------------------------------------------------------------------------------

Erläuterungen
"""""""""""""

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