
Anwendung
=========

.. csv-table::
    :header: "Portal", "Editor"
    :widths: 30 30

	.. image:: ../../../img/ige/icons/objekte/portal/informationssystem.png, .. image:: ../../../img/ige/icons/objekte/ige/informationssystem.png

Mit der Objektklasse Informationssystem lassen sich im Metadatenkatalog Softwareprodukte, Webanwendungen oder zentrale Auskunfts- und Informationssysteme, beschreiben.

.. important:: Die Erfassung dieser Objektklasse erfolgt wie unter `Erfassung von Objekten <https://metaver-bedienungsanleitung.readthedocs.io/de/latest/metaver_ige/ige_erfassung/erfassung-objekte.html>`_ beschrieben. Lediglich der hier beschriebene Abschnitt Fachbezug beinhaltet für diese Objektklasse spezielle Eingabefelder.


Erfassung
---------

Abschnitt Fachbezug
^^^^^^^^^^^^^^^^^^^

.. image:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_abschnitt-04_fachbezug/ige-abschnitt_fachbezug.png
   :width: 700

.. image:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_anwendung/anwendung_kopf.png
   :width: 500

Abb.: Objektklasse Anwendung - Kopf der Erfassungsmaske


Art des Dienstes
''''''''''''''''

.. image:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_anwendung/fachbezug_art-des-dienstes.png


Abb.: Auswahlfeld - Art des Dienstes

In diesem Feld muss die Art des Dienstes ausgewählt werden. Es stehen folgende Einstellungen zur Verfügung: "Informationssystem", "nicht geographischer Dienst" und "Anwendung". 

Sollte es sich bei Ihrem Dienst um einen geographischen Dienst handeln, wählen Sie bitte bei der Erstellung einer neuen Objektklasse die Option "Geodatendienst" aus.

Beispiel: Informationssystem, nicht geographischer Dienst, Anwendung
 
 
Version
'''''''

.. image:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_anwendung/fachbezug_version.png


Abb.: Eingabezeile - Version

Angaben zu Version des beschriebenen Dienstes (Bitte tragen Sie alle Versionen ein, die vom Dienst unterstützt werden).

 
Systemumgebung
''''''''''''''

.. image:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_anwendung/fachbezug_systemumgebung.png


Abb.: Textfeld - Systemumgebung

Angaben zum Betriebssystem und der Software, ggf. auch Hardware, die zur Implementierung des Dienstes eingesetzt wird.

Beispiel:
Android: Mindestens Android minSdkVersion="15" (ab 4.0.3 Ice Cream Sandwich)
Für Android Wear Unterstützung wird mindestens 4.4W benötigt (KitKat Wear Edition, letzte Version vor 5.0 Lollipop) Verfügbar für Android-Geräte ab Android Version 2.3.3, optimiert für Version 4.0 und neuer.

 
Historie
'''''''''

.. image:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_anwendung/fachbezug_historie.png


Abb.: Textfeld -. Systemumgebung

Angabe zur Entwicklungsgeschichte. Hier können Vorläufer und Folgedienste bzw. -anwendungen oder -systeme genannt werden. Ebenso sind Angaben zu initiierenden Forschungsvorhaben oder -programmen von Interesse.

Beispiel: Version 2.9 veröffentlicht am 01.03.2018
Neue Funktionen: In-App-Notification, scollbare Objektinfo, Speicherung Kontaktdaten, Umkreissuche für Flächen - UMO-Dienst (die Abkürzung steht für Umweltobjekte z.B. Geotope, Naturdenkmäler, Natura 2000-Gebiete oder auch Badegewässer)

Beispiel: Messdaten, Sensordaten, Umweltdaten, POIs, Klimadaten (Zeitreihen), GPS*

Basisdaten
''''''''''

.. image:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_anwendung/fachbezug_basisdaten.png


Abb.: Textfeld - Basisdaten

Herkunft und Art der zugrundeliegenden Daten.
Im Allgemeinen sind dies die Datensätze, auf die der Dienst aufgesetzt ist. Allgemein sollen die Herkunft oder die Ausgangsdaten der Daten beschrieben werden, die in dem Dienst / der Anwendung bzw. dem Informationssystem benutzt, gespeichert, angezeigt oder weiterverarbeitet werden. Zusätzlich kann die Art der Daten (z. B. digital, automatisch ermittelt oder aus Umfrageergebnissen, Primärdaten, fehlerbereinigte Daten) angegeben werden.

Der Eintrag kann hier direkt über die Auswahl der Registerkarte "Text" erfolgen oder es können Verweise eingetragen werden, indem der Link "Verweis anlegen" angewählt wird.


Erläuterungen
'''''''''''''

.. image:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_anwendung/fachbezug_erlaeuterungen.png


Abb.: Textfeld - Erläuterungen

Zusätzliche Anmerkungen zu dem beschriebenen Dienst, der Anwendung oder dem Informationssystem. Hier können weitergehende Angaben z. B. technischer Art gemacht werden, die zum Verständnis des Dienstes, der Anwendung, des Informationssystems notwendig sind.

Beispiel:
Die App beinhaltet Umweltinformationen, Informationen zu Umwelterlebnissen. GPS für den Umweltassistenten und für eine standortgenaue Meldefunktion zur Artenerfassung und die Erfassung von Umweltbeeinträchtigungen verwendet.
