
Option: AdV kompatibel
----------------------

AdV - Bedeutung
^^^^^^^^^^^^^^^

AdV: Arbeitsgemeinschaft der Vermessungsverwaltungen

.. note:: Mit der Aktivierung dieser Option, wird die Kompatibilität der Metadaten mit dem Metadatenprofil der Arbeitsgemeinschaft der Vermessungsverwaltungen (AdV) sichergestellt. Die Metadaten werden über die CSW-Schnittstelle an das `AdV Metainformationssystem (AdV-MIS) <https://advmis.geodatenzentrum.de/>`_ abgegeben. 

.. hint:: Im Folgenden werden die Felder beschrieben, die nach Aktivierung dieser Option zusätzlich in der Erfassungsmaske angezeigt werden.


-----------------------------------------------------------------------------------------------------------------------

Erfassung
^^^^^^^^^

Checkbox AdV kompatibel
"""""""""""""""""""""""

.. figure:: ../../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/option/adv-kompatibel/checkbox-adv-kompatibel.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Checkbox AdV kompatibel

Wenn die Checkbox "AdV-kompatibel" aktiviert ist, dann werden die Anforderungen des AdV-Metadatenprofils umgesetzt.

Folgende Eigenschaften ändern sich bei der Aktivierung der Checkbox AdV kompatibel:
 - Abschnitt Verschlagwortung: Aktivierung der Tabelle "AdV-Produktgruppe"
 - Aktivierung des Schlagwortes "AdVMIS" in der ISO-XML

-----------------------------------------------------------------------------------------------------------------------

Abschnitt Verschlagwortung
""""""""""""""""""""""""""

.. figure:: ../../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/option/adv-kompatibel/verschlagwortung_adv-produktgruppe.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Tabelle "AdV-Produktgruppe" - (Pflichtangaben)

`Auswahlliste - AdV-Produktgruppe <https://metaver-bedienungsanleitung.readthedocs.io/de/latest/metaver_ige/ige_auswahllisten/auswahlliste_verschlagwortung_adv_produktgruppe.html>`_


.. figure:: ../../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/option/adv-kompatibel/iso-xml-keyword-advmis.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: ISO-XML - Angabe des Schlüsselwortes "AdVMIS"