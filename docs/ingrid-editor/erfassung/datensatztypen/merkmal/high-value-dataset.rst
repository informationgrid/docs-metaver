
---------------------------------
Merkmal: High-Value-Dataset (HVD)
---------------------------------

Grundlage
^^^^^^^^^

Der öffentliche Sektor verfügt über eine Vielzahl von Informationen - z. B. Statistiken, Satellitenbilder, Umwelt- und Mobilitätsdaten -, die für das Gemeinwohl und/oder die Wirtschaft von Nutzen sein können. Um das gesamtgesellschaftliche und wirtschaftliche Potenzial besonders relevanter Daten auszuschöpfen und gleichzeitig deren Nutzung zu regeln, hat die Europäische Kommission 2013 die EU-Richtlinie über offene Daten und die Weiterverwendung von Informationen des öffentlichen Sektors, kurz PSI-Richtlinie (nach dem englischen Titel »Re-use of Public Sector Information«), verabschiedet. Ziel ist es, den Zugang zu Daten des öffentlichen Sektors zu vereinfachen.

(Quelle: Fraunhofer FOKUS / Offene Daten in der EU: Studie zu "High Value Datasets")

Im Jahr 2019 wurde die PSI-Richtlinie überarbeitet: Die überarbeitete Richtlinie sieht unter anderem die Definition von hochwertigen Datensätzen, sogenannten High Value Datasets (HVD), vor.

High-Value-Datasets (HVD) sind besonders hochwertige Datensätze, die von öffentlichen Stellen kostenfrei und unter einer offenen Lizenz zur Verfügung gestellt werden sollen. Die Europäische Kommission hat eine Liste solcher Datensätze veröffentlicht, die ab dem 9. Juni 2024 gelten soll. Diese Datensätze sind in der Metadatenbeschreibung als solche zu kennzeichnen und die entsprechende Kategorie ist anzugeben. Die Metadaten der HVDs müssen die für die jeweilige Kategorie spezifizierten Eigenschaften enthalten

..important:: High-Value-Datasets (HVD) sollen von Behörden oder öffentlichen Unternehmen als Open Data kostenlos, maschinenlesbar und über Schnittstellen zur Verfügung gestellt werden. Gegebenenfalls können sie auch als Massendownload zur Verfügung gestellt werden. Beispiele für maschinen lesbare Datenformate sind CSV, JSON oder XML.

-----------------------------------------------------------------------------------------------------------------------

Erfassung
^^^^^^^^^

Merkmal: High-Value-Dataset
"""""""""""""""""""""""""""

Das Merkmal High-Value-Dataset wird nur für den Datensatztyp "Geodatensatz" verwendet.

.. figure:: ../../../../img/ige/erfassung/ige_metadaten/datensatztypen/merkmale/merkmal_hvd.png
   :alt: Merkmal High-Value-Dataset + Merkmal Offene Lizenz
   :align: left
   :scale: 70
   :figwidth: 100%

Abb.: Merkmal High-Value-Dataset + Merkmal Offene Lizenz

.. hint:: Wird das Merkmal "High-Value-Dataset" aktiviert, dann wird automatisch auch das Merkmal `"Offene Lizenz" <https://metaver-bedienungsanleitung.readthedocs.io/de/latest/ingrid-editor/erfassung/datensatztypen/merkmal/opendata.html>`_ aktiviert.

Wenn das Merkmal "Open Data / Offene Lizenz" ausgewählt und der Metadatenkatalog über die Schnittstelle DCAT-AP.de an `GovData <https://www.govdata.de/>`_ angebunden ist, werden die als "Open Data" gekennzeichneten Metadaten an dieses Portal übergeben. In einem weiteren Schritt werden diese Daten von `data.europa.eu <https://data.europa.eu/de/trening/what-open-data>`_, einem Portal der Europäischen Kommission, geharvested (geerntet).


Wird das Merkmal "High-Value-Dataset" gewählt, so:

  - werden alle Zugriffsbeschränkungen entfernt
  - wird die Angabe einer Opendata-Kategorie unter "Verschlagwortung" verpflichtend
  - wird dem Datensatz beim Export in ISO19139 Format automatisch das Schlagwort "opendata" hinzugefügt


.. figure:: ../../../../img/ige/erfassung/ige_metadaten/datensatztypen/merkmal_beschreibung/hvd/hvd-kategorien.png
   :alt: HVD-Kategorien
   :align: left
   :scale: 90
   :figwidth: 100%

Abb.: HVD-Kategorien in der Verschlagwortung des Metadatentyps Geodatensatz