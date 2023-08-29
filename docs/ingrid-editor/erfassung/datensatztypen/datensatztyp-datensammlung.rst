
Datensammlung
=============

.. csv-table::
    :header: "Portal", "Editor"
    :widths: 20, 20

	 .. image:: ../../../img/ige/icons/datensatztypen/portal/datensammlung.png, .. image:: ../../../img/ige/icons/datensatztypen/ige/datensammlung.png

Der Datensatztyp "Datensammlung" beschreibt gemessene, aufbereitete oder erhobene Daten. Dazu gehören Messdaten, statistische Erhebungen, Modelldaten oder Anlagendaten. Dies betrifft Dienste und Anwendungen, Informationssysteme, die in der Regel auf eine oder mehrere Datenbanken zuzugreifen um die enthaltenen Daten zugänglich zu machen.

.. important::  Die Erfassung dieses Datensatztyps erfolgt gemäß den Anweisungen unter `Metadaten erfassen <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/erfassung-metadaten.html>`_. Der Abschnitt "Fachbezug" beinhaltet spezielle Eingabefelder für diesen Datensatztyp.

-----------------------------------------------------------------------------------------------------------------------


Abschnitt Fachbezug
-------------------

Feld: Objektartenkatalog
^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: ../../../img/ige/erfassung/ige_metadaten/datensatztypen/datensatztyp_datensammlung/fachbezug_objektartenkatalog.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Tabelle - Objektartenkatalog

An dieser Stelle besteht die Möglichkeit, den Klassifizierungsschlüssel zu benennen, der den Daten zugrunde liegt. Dabei ist die Eingabe mehrerer Kataloge mit zugehörigem Datum und Version möglich.

Beispiel:  Biotoptypenschlüssel Hamburg (tt.mm.jjjj), Version (xx.xx)


Feld: Inhalte der Datensammlung/Datenbank
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: ../../../img/ige/erfassung/ige_metadaten/datensatztypen/datensatztyp_datensammlung/fachbezug_inhalt.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Felder für Inhalte der Datensammlung


Feld: Parameter
"""""""""""""""
 
Angabe der wichtigen Parameter der Datenbank oder Datensammlung. Um einen qualifizierten Einblick in die beschriebene Datensammlung oder Datenbank zu erhalten, werden hier die wesentlichen Parameter der gespeicherten Daten aufgeführt. Im Falle von Messdaten werden die wichtigsten Messparameter wie z. NOx, SO2, Windgeschwindigkeit und pH-Wert angegeben. Bei statistischen Erhebungen werden Erhebungsgrößen wie Wasserverbrauch pro Kopf und Bevölkerungsdichte angeführt. Im Falle von Modelldaten werden die Modellparameter, wie z. Meeresspiegel, CO2-Gehalt der Luft und Welttemperatur, dargestellt.



Feld: Ergänzenden Angaben
"""""""""""""""""""""""""

Es können zusätzliche Angaben zu Parametern angegeben werden, wie zum Beispiel: Maßeinheiten, Genauigkeiten, Nachweisgrenzen, Probenmatrizen oder spezifische Angaben zur Messmethode.

Beispiel: organische Gase (Benzol, Toluol, Xylol (flüchtige Aromaten, BTX))


Feld: Methode / Datengrundlage
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: ../../../img/ige/erfassung/ige_metadaten/datensatztypen/datensatztyp_datensammlung/fachbezug_methode.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Tabelle - Methode/Datengrundlage

Angaben zu den verwendeten Methoden und der Datengrundlage. Hierbei sind die angewandten Methoden der Datenerhebung, wie z.B. Messmethode und Erhebungsmethode, zu nennen und zu beschreiben. Darüber hinaus können Informationen zur Qualität und zum Umfang der Datengrundlage angeführt werden.

Beispiel: kontinuierliche Messungen in vollautomatischen Messstationen
 

Feld: Erläuterungen
^^^^^^^^^^^^^^^^^^^^

.. figure:: ../../../img/ige/erfassung/ige_metadaten/datensatztypen/datensatztyp_datensammlung/fachbezug_erlaeuterungen.png
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Textfeld - Erläuterungen

Weitere Informationen zur Datensammlung bzw. zur Datenbank.

Beispiel: Datenbasis: 144 10-Minutenwerte pro Station, Messkomponente und Tag. Aus dieser Datenbasis können verdichtete Kenngrößen (Tagesmittelwerte, Jahresmittelwerte, 98-Perzentile, etc.) berechnet werden.