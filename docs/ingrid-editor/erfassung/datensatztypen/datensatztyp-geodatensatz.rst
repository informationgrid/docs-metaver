
Geodatensatz
============

.. csv-table::
    :header: "Portal", "Editor"
    :widths: 20, 20

    .. image:: ../../../img/ige/icons/datensatztypen/portal/geodatensatz.png, .. image:: ../../../img/ige/icons/datensatztypen/ige/geodatensatz.png

Der Datensatztyp Geodatensatz dient der Beschreibung von Daten mit direktem oder indirektem Raumbezug (digital oder analog).

Beispiele: GIS-Daten, analoge Karten oder Kartenwerke

Die Metadaten werden nach der ISO-Norm 19115 „Geographic Information – Metadata“ erfasst.


.. hint:: Die Erfassung dieses Datensatztyps erfolgt wie unter `Metadaten erfassen <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/erfassung-metadaten.html>`_  beschrieben. Der hier beschriebene Abschnitt Fachbezug beinhaltet für diesen Datensatztyp spezielle Eingabefelder.

-----------------------------------------------------------------------------------------------------------------------

Erfassung
---------

Typ
"""
Unter Typ werden weitere Eigenschaften des Metadatensatzes festgelegt.

Es können folgende Optionen gewählt werden:
    
Typ: `INSPIRE-relevant, <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/option/inspire-relevant.html>`_
`AdV kompatibel,  <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/option/adv-kompatibel.html>`_
`Open Data, <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/option/opendata.html>`_
`(InVeKoS) <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/option/invekos.html>`_ (Erläuterungen zu diesen Optionen)

.. image:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatensatz/typ_optionen.png

Abb.: Optionen


Auswahlfeld: Datensatz/Datenserie
"""""""""""""""""""""""""""""""""

Es wird unterschieden, ob es sich bei den beschriebenen Daten um einen einzelnen Datensatz mit bestimmtem räumlichen Bezug oder um eine Datenserie mit einheitlichem thematischen Bezug und mehreren Datensätzen mit unterschiedlichem räumlichen Bezug handelt.

.. image:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatensatz/fachbezug_datensatz-datenserie.png
 
Abb.: Auswahlfeld Datensatz / Datenserie

-----------------------------------------------------------------------------------------------------------------------

Abschnitt Allgemeines
^^^^^^^^^^^^^^^^^^^^^

.. hint:: Dieser Abschnitt ist unter `Metadaten erfassen <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/erfassung-metadaten.html>`_ beschrieben.


-----------------------------------------------------------------------------------------------------------------------

Abschnitt Verschlagwortung
^^^^^^^^^^^^^^^^^^^^^^^^^^

FelD: ISO 19115 - Themenkategorie
""""""""""""""""""""""""""""""""""

Die Norm ISO 19115 - Geographic Information – Metadata

.. note:: Die ISO 19115 definiert einen international gültigen Standard zur Beschreibung geographischer Informationen und zugehöriger Dienstleistungen. Mit dieser Norm soll es ermöglicht werden, Geodaten anhand von Metadaten so zu beschreiben, dass damit ihre Eignung für bestimmte Anwendungszwecke beurteilt, oder auch sinnvolle Präsentations- und Verarbeitungsmethoden abgeleitet werden können. Das Schema der ISO 19115 beinhaltet u. a. Informationen über den Inhalt, räumlich-zeitliche Bezüge, Datenqualität, Datenzugangsmöglichkeit oder Nutzungsrechte. (Quelle: `Wikipedia <https://de.wikipedia.org/wiki/ISO_19115>`_)


Dieses Feld verlangt die Angabe von Themen, welche die Daten beschreiben.
Die Auswahl erfolgt über die vorgegebene Auswahlliste.

`Auswahlliste - ISO 19115 Themenkategorien <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/auswahllisten/auswahlliste_verschlagwortung_iso-themenkategorie.html>`_

.. image:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatensatz/verschlagwortung_iso-themenkategorie.png

Abb.: Auswahlfeld ISO Themenkategorie


Optionale Verschlagwortung
''''''''''''''''''''''''''

.. hint:: Die Erfassung von freien bzw. optionalen Schlagworten und die Schlagwortanalyse sind unter `Metadaten erfassen <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/erfassung-metadaten.html#abschnitt-verschlagwortung>`_ beschrieben.


-----------------------------------------------------------------------------------------------------------------------

Abschnitt Fachbezug
^^^^^^^^^^^^^^^^^^^

Feld: Fachliche Grundlage
"""""""""""""""""""""""""

(INSPIRE-Pflichtfeld für Datasets und Data series)

In diesem Feld soll eine kurze Zusammenfassung zur Erstellung der zu beschreibenden Geodaten erfolgen. Hierzu können die Datengrundlage, die Methode der Datenerhebung und der Verarbeitungsprozess erwähnt werden. Der Eintrag soll in Textform erfolgen. 

.. hint:: Für genauere Angaben sind die Felder Datenquelle und Herstellungsprozess zu verwenden.

Beispiele:

Kombination verschiedenster Vektordatenquellen zu einem harmonisierten digitalen kartographischen Modell.

Die Grunddatenerfassung erfolgte durch Digitalisierung der Übersichtskarte 1:500 000 (ÜK500). Die fortlaufende Aktualisierung erfolgt durch Auswertungen der jüngsten Editionen des
ATKIS Basis-DLM der Bundesländer, der Digitalen Topographischen Karte 1:200 000 (DTK200) und anderen Quellen.

.. image:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatensatz/fachbezug_fachliche-grundlage.png
   :width: 500

Abb.: Eingabefeld Fachliche Grundlage


.. tip:: Das Eingabefeld lässt sich an der rechten unteren Ecke vergrößern.


Feld: Identifikator der Datenquelle
"""""""""""""""""""""""""""""""""""

Hier muss ein eindeutiger Name (Identifikator) für die im Geodatensatz beschriebene Datenquelle (z.B. eine Karte) vergeben/eingetragen werden. Der Identifikator soll aus einem Namensraum (=codespace), sowie einem Code bestehen. (INSPIRE-Pflichtfeld).
Wenn der Identifikator keinen Namensraum enthält, so wird dem Identifikator bei der Abgabe der Metadaten derjenige Wert vorangestellt, welcher im Bereich Katalogverwaltung/Katalogeinstellungen unter "Namensraum des Katalogs" eingetragen ist.
Der Identifikator kann von Hand eingetragen werden oder mit Hilfe des Buttons "Erzeuge ID". Bei der automatischen Erzeugung wird eine UUID als Identifikator in dieses Feld eingetragen. Da diese UUID keinen Namespace enthält, wird bei dieser Variante immer der Namensraum aus der Katalogverwaltung hinzugefügt.


Hier muss ein Identifikator (ein eindeutiger Name) für die hier beschriebene Ressource (den Datensatz) vergeben werden. Dieser muss unverändert bleiben. Er soll eine auflösbare URL sein, die den Direktzugriff auf das XML des Daten-Metadatensatzes ermöglicht. Der Identifikator setzt sich aus einem Namensraum, einem Schrägstrich und einer lokalen ID zusammen (namespace/localId). (Pflichtfeld).

Soll der Identifikator den im Editor voreingestellten Namensraum beinhalten, ist die Eingabe einer lokalen ID ausreichend. Für die Erzeugung kann der Button "Erzeuge ID" verwendet werden. Der endgültige Identifikator wird anschließend unter dem Feld angezeigt. Ist durch den Katalogadministrator kein Namensraum definiert, wird ein Defaultwert (https://registry.gdi-de.org/id/) verwendet.

Alternativ kann hier eine aufrufbare URL als individueller Identifikator manuell eingegeben werden. Diese wird unverändert übernommen.

Beispiel:

| Namensraum: https://registry.gdi-de.org/id/de.bund.bkg.csw
| lokale ID: 1371b05a-055b-4749-8390-95cda942f40c
| Identifikator: https://registry.gdi-de.org/id/de.bund.bkg.csw/1371b05a-055b-4749-8390-95cda942f40c


.. image:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatensatz/fachbezug_identifikator_01.png
   :width: 500
 
Abb.: Feld Identifikator der Datenquelle


Feld: Digitale Repräsentation
"""""""""""""""""""""""""""""
(optionales INSPIRE-Feld)

Es kann eine Angabe der Methode erfolgen, mit der räumliche Daten präsentiert werden. Die Auswahl erfolgt über eine vorgegebene Liste.

Auswahlliste: Raster, Gitter, Stereomodell, Text, Tabelle, TIN, Vektor, Video


.. image:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatensatz/fachbezug_digitale-repaesentation.png
   :width: 500

 
Abb.: Auswahlfeld Digitale Repräsentation


Feld: Erstellungsmaßstab
""""""""""""""""""""""""
(optionales INSPIRE-Feld)

Angabe des Erstellungsmaßstabes, der sich auf die erstellte Karte und/oder Digitalisiergrundlage bei Geodaten bezieht. 
 - Maßstab 1:x: Maßstab der Karte, z.B. 1:12 
 - Bodenauflösung (m): Einheit geteilt durch Auflösung multipliziert mit dem Maßstab (Angabe in Meter, Fließkommazahl) 
 - Scanauflösung (DPI): Auflösung z.B. einer eingescannten Karte, z.B. 120dpi (Angabe in dpi, Integerzahl)

Beispiel: Bodenauflösung: Auflösungseinheit in Linien/cm; Einheit: z.B. 1 cm geteilt durch 400 Linien multipliziert mit dem Maßstab 1:25.000 ergibt 62,5 cm als Bodenauflösung

.. image:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatensatz/fachbezug_erstellungsmassstab.png
 
Abb.: Feld Erstellungsmaßstab


Feld: Darstellender Dienst
""""""""""""""""""""""""""

Geodatensätze können mit Geodatendiensten gekoppelt werden. Das heißt, dass in einem Portal von einem Geodatensatz auf einen Geodendienst verwiesen wird und umgekehrt.
Die Datenkopplung erfolgt in einem Geodatendienst. Der gekoppelte Dienst wird in der Erfassungsmaske des Geodatensatzes angezeigt.

.. image:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatensatz/fachbezug_darstellender-dienst.png
 
Abb.: Feld Darstellender Dienst


Feld: Datengrundlage
""""""""""""""""""""

Angabe der Unterlagen (Luftbilder, Karten, Datensammlungen), die bei der Erstellung der Karte oder der Geoinformation (des digitalen Datenbestandes) Verwendung finden.

.. image:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatensatz/fachbezug_datengrundlage.png
 
Abb.: Feld Datengrundlage - Beispiel: Kartieroriginale der Pflanzenerfassung


Feld: Herstellungsprozess
"""""""""""""""""""""""""

Angabe der Methode, die zur Erstellung des Datenobjektes geführt hat. Der Eintrag kann in Textform erfolgen, indem die Registerkarte "Text" ausgewählt wird.

.. image:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatensatz/fachbezug_herstellungsprozess.png
 
Abb.: Feld Herstellungsprozess - Beispiel: Feldkartierung


Symbolkatalog
"""""""""""""

Für die Präsentation genormter Objekte und Sachverhalte können für die Nutzer der Daten zur Herstellung von Karten abgestimmte Symbole vorgegeben werden. Die Angabe einer oder mehrerer analoger oder digitaler Symbolpaletten mit zugehörigem Datum (Pflichteintrag) und Version (Optional) ist hier möglich.

Beispiel: Planzeichenverordnung, Datum 03.08.2023, Version 6.0

.. image:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatensatz/fachbezug_symbolkatalog.png
 
Abb.: Feld Symbolkatalog


Schlüsselkatalog
""""""""""""""""

An dieser Stelle besteht die Möglichkeit, den Daten zugrunde liegende Klassifizierungsschlüssel zu benennen. Dabei ist die Eingabe mehrerer Kataloge mit zugehörigem Datum (Pflichteintrag) und Version (Optional) möglich. Das Feld Schüsselkatalog wird zum Pflichtfeld, wenn in der Tabelle Sachdaten/Attributinformationen ein Eintrag vorgenommen wurde.

Beispiel: Biotoptypenschlüssel, Datum 03.08.2023, Version 6.0

.. image:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatensatz/fachbezug_schluesselkatalog.png
 
Abb.: Feld Schlüsselkatalog

.. hint:: Mit einem Eintrag unter Sachdaten/Attributinformation werden die Eingabefelder zum Schlüsselkatalog zu Pflichtfeldern. Bitte geben Sie dort den Schlüsselkatalog an, welcher das eingetragene Attribut verzeichnet.


Sachdaten/Attributinformation
"""""""""""""""""""""""""""""

Angabe der mit der Geoinformation/Karte verbundenen Sachdaten. Bei Bedarf kann hier eine Auflistung der Attribute des Datenbestandes erfolgen. Die hauptsächliche Nutzung dieses Feldes ist für digitale Geoinformationen vorgesehen.

.. image:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatensatz/fachbezug_sachdaten-attributinformation.png
 
Abb.: Feld Sachdaten/Attributinformation - Beispiel: Baumkartei

.. hint:: Mit einem Eintrag unter Sachdaten/Attributinformation werden die Eingabefelder zum Schlüsselkatalog zu Pflichtfeldern. Bitte geben Sie dort den Schlüsselkatalog an, welcher das eingetragene Attribut verzeichnet.

-----------------------------------------------------------------------------------------------------------------------

Abschnitt Datenqualität
^^^^^^^^^^^^^^^^^^^^^^^

..note:: Die optionalen Felder zur `Datenqualität sind hier <https://metaver-bedienungsanleitung.readthedocs.io/de/latest//img/ige/erfassung/ige_objektklassen/qualitaetssicherung/ige_auswahllisten/abschnitt_datenqualitaet.html>`_ beschrieben.

-----------------------------------------------------------------------------------------------------------------------

..note:: Die Abschnitte Raumbezugsystem, Zeitbezug, Zusatzinformation, Verfügbarkeit und Verweise sind ausführlich unter `Erfassung von Objekten <https://metaver-bedienungsanleitung.readthedocs.io/de/latest/img/ige/erfassung/erfassung-objekte.html>`_  beschrieben, da sie auf mehrere Datensatztypen zutreffen.

-----------------------------------------------------------------------------------------------------------------------

Abschnitt Zusatzinformation
^^^^^^^^^^^^^^^^^^^^^^^^^^^
  
Feld Zeichensatz des Datensatzes
""""""""""""""""""""""""""""""""

.. image:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatensatz/zusatzinformation_zeichensatz.png
 
Abb.: Feld Zeichensatz des Datensatzes

Angaben zu dem im beschriebenen Datensatz benutzten Zeichensatz z.B. UTF-8.

`Auswahlliste Zeichensatz des Datensatzes <https://metaver-bedienungsanleitung.readthedocs.io/de/latest/img/ige/ige_auswahllisten/auswahlliste_zusatzinformation_zeichensatz.html>`_
  

Feld Konformität
""""""""""""""""

.. image:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatensatz/zusatzinformation_konformitaet.png
 
Abb.: Feld Konformität

Hier muss angegeben werden, zu welcher Durchführungsbestimmung der INSPIRE-Richtlinie bzw. zu welcher anderweitigen Spezifikation die beschriebenen Daten konform sind. (INSPIRE-Pflichtfeld)

Dieses Feld wird bei der Auswahl der "INSPIRE-Themen" oder der "Art des Dienstes" automatisch befüllt. Es muss dann nur der Grad der Konformität manuell eingetragen werden.

Beschreibung unter der Option `INSPIRE-relevant <https://metaver-bedienungsanleitung.readthedocs.io/de/latest/img/ige/erfassung/ige_objektklassen/option/inspire-relevant.html>`_.










Vektorformat
''''''''''''

.. image:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatensatz/fachbezug_vektorformat.png
 
Abb.: Feld Vektorformat

.. hint:: Dieses Feld ist nur aktiv nach Auswahl von "Vektor" im Feld "Digitale Repräsentation".

Es können hier Topologie Informationen, Geometrietyp (Angabe der geometrischen Objekte, zur Beschreibung der geometrischen Lage) und Elementanzahl (Angaben der Anzahl der Punkt- oder Vektortypelemente) angegeben werden.

Auswahlliste Topologieinformation: 3D-Oberfläche, Flächen, Flächen flächendeckend, Geometrie ohne Topologie, geschlossene Linien eben, geschlossene Linien flächendeckend, Körper, Linien, topologisches Gebilde ohne geometrischen Raum