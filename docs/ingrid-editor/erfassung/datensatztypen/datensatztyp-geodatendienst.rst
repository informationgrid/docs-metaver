
Geodatendienst
==============

.. csv-table::
    :header: "Portal", "Editor"
    :widths: 20, 20

    .. figure:: ../../../img/ige/icons/datensatztypen/portal/geodatendienst.png, .. image:: ../../../img/ige/icons/datensatztypen/ige/geodatendienst.png

Ein Geodatendienst ist ein in der Regel über das Internet angebotener Dienst, mit dessen Hilfe man Geodaten anschauen, einbinden, bearbeiten oder abfragen kann. Geodatendienste sind Webservices, die raumbezogene Informationen verarbeiten und vom Open Geospatial Consortium (OGC) auf Basis von ISO-Normen international standardisiert wurden.

Einem Geodatendienst kann ein Geodatensatz zu geordnet werden, dieser beschreibt die Daten die im Geodatendienst enthalten sind. Einem Geodatendienst können auch mehrere Geodatensätze zugeordnet werden, diese beschreiben dann die Layer, die im Geodatendienst enthalten sind. 
Einem Geodatensatz können unterschiedliche Geodatendienste zugeordnet werden (z.B. WMS-, WFS-, Atom-Dienste), der Geodatensatz beschreibt dann die Daten, die durch die Geodatendienste bereitgestellt werden.

Wenn ein Geodatensatz einem Geodatendienst zugeordnet wird, dann werden diese Metadatensätze miteinander gekoppelt (Datenkopplung). Das bedeutet, der Geodatensatz verweist durch eine Verlinkung auf den Geodatendienst und der Geodatendienst wiederum verweist durch eine Verlinkung auf den Geodatensatz.

`Liste der verschiedenen Dienstarten <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/auswahllisten/auswahlliste_geodatendienst_dienstarten.html>`_


.. note:: Die Erfassung dieses Datensatztyps erfolgt wie unter `Metadaten erfassen <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/erfassung-metadaten.html>`_  beschrieben. Der hier beschriebene Abschnitt Fachbezug beinhaltet für diesen Datensatztyp spezielle Eingabefelder.

-----------------------------------------------------------------------------------------------------------------------

Erfassung
---------

Abschnitt Erweiterte Erfassung
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Der GetCapabilities-Assistent
"""""""""""""""""""""""""""""

.. figure:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatendienst/assistent/getcapabilties-assistent_symbol.png
   :width: 5%
   
Abb.: GetCapabilitie-Assistent - Symbol (Zauberstab) aus der Symbolleiste

.. seealso:: Hier wird die Erfassung von Metadaten mit dem `GetCapabilities-Assistent <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/erfassungsassistent/getcapabilitie-assistent.html>`_  beschrieben.


-----------------------------------------------------------------------------------------------------------------------


Feld: Typ
"""""""""

Unter Typ können weitere Eigenschaften (Eingabefelder) für den Metadatensatz festgelegt werden.

.. seealso:: Beschreibungen zu den Optionen: `INSPIRE-relevant | <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/option/inspire-relevant.html>`_ `AdV kompatibel | <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/option/adv-kompatibel.html>`_ `Open Data <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/option/opendata.html>`_

.. `(InVeKoS) <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/option/invekos.html>`_

.. figure:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatensatz/typ_optionen.png
   :width: 100%

Abb.: Optionen für weitere Eigenschaften


-----------------------------------------------------------------------------------------------------------------------

Abschnitt Allgemeines
^^^^^^^^^^^^^^^^^^^^^

.. hint:: Dieser Abschnitt ist unter `Metadaten erfassen <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/erfassung-metadaten.html>`_ beschrieben.

-----------------------------------------------------------------------------------------------------------------------

Abschnitt Verschlagwortung
^^^^^^^^^^^^^^^^^^^^^^^^^^

.. hint:: Dieser Abschnitt ist unter `Metadaten erfassen <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/erfassung-metadaten.html>`_ beschrieben.

.. seealso:: Beschreibungen zu den Optionen: `INSPIRE-relevant | <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/option/inspire-relevant.html>`_ `AdV kompatibel | <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/option/adv-kompatibel.html>`_ `Open Data <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/option/opendata.html>`_

.. `(InVeKoS) <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/option/invekos.html>`_

-----------------------------------------------------------------------------------------------------------------------

Abschnitt Fachbezug
^^^^^^^^^^^^^^^^^^^

Feld Klassifikation des Dienstes
""""""""""""""""""""""""""""""""

.. figure:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatendienst/fachbezug_klassifikation.png
   :width: 70%

Abb.: Feld - Klassifikation des Dienstes

`Auswahlliste - Klassifikation des Dienstes <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/auswahllisten/auswahlliste_fachbezug_geodatendienst_klassifikation.html>`_


Aus der vorgegebenen Auswahlliste ist der Eintrag zu wählen, der auf den Dienst zutrifft. Bei WebMapDiensten (WMS) kann beispielsweise „Dienst für den Zugriff auf grafische Darstellungen ausgewählt werden. Dieses Feld dient in erster Linie der Identifikation eines Dienstes durch den recherchierenden Nutzer. 


Feld Art des Dienstes
"""""""""""""""""""""

In diesem Pflichtfeld kann die Art des Dienstes ausgewählt werden. Über das Feld werden die zur weiteren Befüllung auszuwählenden Angaben zu Operationen gesteuert (siehe Tabelle unter Punkt: Name der Operation).

.. figure:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatendienst/fachbezug_dienstart.png
   :width: 70%

Abb.: Feld - Art des Dienstes

Beispiel Darstellungsdienst: Dienst für den Zugriff auf grafische Daten

Beispiel Downloaddienst: Download-Dienste


`Auswahlliste - Art des Dienstes <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/auswahllisten/auswahlliste_fachbezug_geodatendienst_art.html>`_

.. hint:: Die Auswahl der Dienstart hat Auswirkungen auf das Feld Konformität. Je nach gewählter Art des Dienstes wird das Feld Konformität schon vorbelegt (gilt nicht für alle Dienstarten).

Beispiel: Darstellungsdienst (automatischer Eintrag in Konformität/Spezifikation: "Technical Guidance for the implementation of INSPIRE View Services")


Feld Version des Dienstes
""""""""""""""""""""""""

Angaben zur Version der Spezifikation, die dem Dienst zugrunde liegt

Bitte alle Versionen eintragen, die vom Dienst unterstützt werden.

.. figure:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatendienst/fachbezug_dienstversion.png
   :width: 40%

Abb.: Feld - Version des Dienstes

Beispiele Darstellungsdienste: OGC: WMS 1.3.0, OGC: WMS 1.1.1, OGC: WMTS 1.0.0

Beispiele Downloaddienste: OGC: WFS 2.0, WFS 1.1.0, predefined ATOM


Option Als ATOM-Download Dienst bereitstellen
"""""""""""""""""""""""""""""""""""""""""""""

.. figure:: ../../../img/ige/erfassung/ige_metadaten/ige_datensatztypen/datensatztyp_geodatendienst/atom-downloaddienst/fachbezug_als-atomdownloaddienst-bereitstellen.png
   :width: 30%

Abb.: Checkbox - Als ATOM-Download Dienst bereitstellen 

Bei aktivierter Option, wird dieser Datensatz im Portal als Download angeboten.

.. seealso:: Beschreibung der Funktion `Als ATOM-Download Dienst bereitstellen <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/atom-feed/bereitstellung.html>`_


Der ATOM-Feed Client
""""""""""""""""""""

.. seealso:: Beschreibung des `Atom-Feed Clients <https://metaver-bedienungsanleitung.readthedocs.io/de/igeng/ingrid-editor/erfassung/datensatztypen/atom-feed/client.html>`_


Operationen
"""""""""""

Erfassung der Dienste URL.

.. figure:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/operationen/fachbezug_operation_aktualisieren.png

Abb.: Feld - Operationen

.. seealso:: Bescheribung der Funktion `Operationen <https://metaver-bedienungsanleitung.readthedocs.io/de/latest/metaver_ige/ige_erfassung/ige_objektklassen/operationen/operationen_beschreibung.html>`_



Erstellungsmaßstab
""""""""""""""""""

.. figure:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/fachbezug_erstellungsmaßstab.png

Abb.: Erstellungsmaßstab

Angabe des Erstellungsmaßstabes, der sich auf die erstellte Karte und/oder Digitalisiergrundlage bei Geodaten bezieht. Maßstab: Maßstab der Karte, z.B 1:12 Bodenauflösung: Einheit geteilt durch Auflösung multipliziert mit dem Maßstab (Angabe in Meter, Fließkommazahl) Scanauflösung: Auflösung z.B. einer eingescannten Karte, z.B. 120dpi (Angabe in dpi, Integerzahl). Es handelt sich um ein optionales INSPIRE-Feld.

Beispiel: Bodenauflösung: Auflösungseinheit in Linien/cm; Einheit: z.B. 1 cm geteilt durch 400 Linien multipliziert mit dem Maßstab 1:25.000 ergibt 62,5 cm als Bodenauflösung


Systemumgebung
''''''''''''''

.. figure:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/fachbezug_systemumgebung.png

Abb.: Erstellungsmaßstab

Angaben zum Betriebssystem und der Software, ggf. auch Hardware, die zur Implementierung des Dienstes eingesetzt wird.


Historie
''''''''

.. figure:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/fachbezug_historie.png

Abb.: Historie

Angaben zur Implementierungsgeschichte des Dienstes.


Beispiel: 11.12.03: Installation des UMN Mapserver 3.0 auf Linux 2.2.005.04.04: Upgrade Linux 2.2.0 auf Linux 2.6.0 Modellversuch beim Gewerbeaufsichtsamt Osnabrück 1991; Einführung 1993


Erläuterungen
'''''''''''''

.. figure:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/fachbezug_erlaeuterungen.png

Abb.: Erläuterungen

Zusätzliche Anmerkungen zu dem beschriebenen Dienst. Hier können weitergehende Angaben z. B. technischer Art gemacht werden, die zum Verständnis des Dienstes notwendig sind.

.. note:: Beispiel: Der Datensatz ist eine Shape-Datei, die alle Grundwassermessstellen in Sachsen-Anhalt mit Lage und Kennung beinhaltet.


-----------------------------------------------------------------------------------------------------------------------

Daten-Dienstekopplung
^^^^^^^^^^^^^^^^^^^^^

Dargestellte Daten
''''''''''''''''''

.. figure:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/datenkopplung/fachbezug_daten-dienste-kopplung_dargestellte-daten.png

Abb.: Dargestellte Daten


`Datenkopplung im Geodatensatz <https://metaver-bedienungsanleitung.readthedocs.io/de/latest/metaver_ige/ige_erfassung/ige_objektklassen/objektklasse-geodatensatz.html#darstellender-dienst>`_


Das Metadatenfeld „Dargestellte Daten“ bzw. „Gekoppelte Daten auswählen“ ist für den Objekttyp „Geodatendienst“ von besonderer Bedeutung. Ziel ist es, hier alle Metadatensätze zu Geodaten aufzulisten, die Bestandteil des Geodatendienstes sind. Auf diese Weise erfolgt eine Kopplung der Daten und Dienste und dieses wiederum hat den nutzerfreundlichen Vorteil, dass sich der User gefundene Daten sofort über einen Link (im Datensatz) im Kartenviewer ansehen kann (siehe Daten-Dienste-Kopplung).

.. figure:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/datenkopplung/fachbezug_daten-dienste-kopplung_portalansicht.png

Abb.: Datenkopplung in der Portalansicht

 
Datenkopplung
'''''''''''''

.. figure:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/datenkopplung/fachbezug_daten-dienste-kopplung_dargestellte-daten.png

Abb.: Datenkopplung

.. figure:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/datenkopplung/fachbezug_daten-dienste-kopplung_objekt-auswaehlen.png

Abb.: Gekoppelte Daten auswählen


Zum Eintragen von verknüpften Daten kann nun unterhalb der Tabelle auf den Button „Gekoppelte Daten auswählen“ geklickt werden. In dem daraufhin erscheinenden Dialog aus dem Hierarchiebaum bitte den Datensatz auswählen, der mit dem Dienst gekoppelt werden soll.

Mit einem Klick auf den Button „Zuweisen“ wird die gekoppelte Datensatz beim Dienst-Objekt eingetragen. Zeitgleich erhält der Datensatz automatisch einen Eintrag zum gekoppelten Dienst (Feld: "Darstellender Dienst"). 


Kopplungstyp
''''''''''''

.. figure:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/datenkopplung/fachbezug_daten-dienste-kopplung_kopplungstyp.png

Abb.: Kopplungstyp

Die Art der Kopplung vom Dienst (Service) zu den Daten. Der Typ "tight" bewirkt, dass ein Verweis zu einem Datensatz existieren muss.

Kopplungstypen: 

 - loose - Suchdienste
 - mixed - Suchdienste, kaskadierende Dienste
 - tight - Verweis zu einem Datensatz


Bedingung für das Gelten dieser Konvention: Es besteht eine Verbindung zu einer ebenfalls mit Metadaten beschriebenen Datenquelle. In den Dienst-Metadaten ist neben den verknüpften Daten-Metadaten auch die Art der Kopplung anzugeben (ISO 19119, SV_CouplingType). Dabei sind die Werte „eng“ (tight), „gemischt“ (mixed) und „lose“ (loose) zulässig.

Es ist davon auszugehen, dass in der Regel ein WMS „eng“ (tight), kaskadierende Dienste „gemischt“ (mixed) und Downloaddienste ebenfalls „eng“ (tight) gekoppelt sind. Je nach Struktur der Katalogtopologie können Suchdienste sowohl „lose“, „eng“ oder „gemischt“ gekoppelt sein

*Quelle: GDI-DE, Konventionen zu Metadaten, Arbeitskreis Metadaten, 05.02.2020, Version: 2.0.3*



Katalog-übergreifende Daten-Dienste-Kopplung
''''''''''''''''''''''''''''''''''''''''''''

.. figure:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/datenkopplung/fachbezug_daten-dienste-kopplung_externer-datensatz.png

Abb.: Daten-Dienste-Kopplung

Daten eines externen Metadatenkatalogs können mit Diensten der Objektklasse "Geodatendienst" gekoppelt werden. Die Kopplung ist bislang jedoch nur mit Datensätzen möglich, bei denen die Daten über einen Verweis vom Typ Datendownload zum Download bereitgestellt werden.

 
Die Kopplung wird für den Geodatendienst im InGrid-Editor in der Rubrik Fachbezug unter dem Punkt Dargestellte Daten eingetragen.

 
Nach einem Klick auf den Button „Gekoppelte Daten auswählen“ öffnet sich ein Dialogfenster. Liegt der Datensatz, mit dem der Dienst gekoppelt werden soll, in einem externen Metadatenkatalog vor, so ist die zweite Registerkarte „Externer Datensatz“ auszuwählen.

Im Feld "GetRecordById URL" muss der GetRecordById-Request zum Aufruf des externen Datensatzes (XML-Dokument) angegeben werden.

Beispiel für GetRecordById-Requests: https://www.host.de/csw?request=getrecordbyid&service=csw&version=2.0.2&id=fd218f68-d2b4-11d5-88c8-000102dccf41&elementsetname=full

Über die Angabe dieses Requests wird die katalogübergreifende Daten-Dienste-Kopplung ermöglicht. Nach Eingabe der URL und Klick auf „Analysieren“ erfolgt eine Auswertung des XML-Dokumentes. Mit dem Button „Zuweisen“ wird der externe Datensatz mit dem Dienst gekoppelt.

.. figure:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/datenkopplung/fachbezug_daten-dienste-kopplung_externer-datensatz.png

Abb.: Detailansicht einer erfolgreichen Daten-Dienste-Kopplung im Portal am Beispiel des INSPIRE.WMS ST Schutzgebite Naturschutz.


Checkbox "Zugang geschützt"
'''''''''''''''''''''''''''

.. figure:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/fachbezug_zugang-geschuetzt.png
   :width: 200

Abb.: Zugang geschützt

.. figure:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/fachbezug_zugang-geschuetzt-portal.png
   :width: 300

Abb.: Zugang geschützt - Portalansicht

Die Checkbox "Zugang geschützt" sollte aktiviert werden, wenn der Zugang zu dem Dienst z.B. durch ein Passwort geschützt ist. Bei aktiviertem Kontrollkästchen wird kein direkter Link (Zeige Karte) aus dem Portal zu dem Dienst generiert. In der Portalansicht erscheint am Dienst eine Grafik als Vorhängeschloss.


-----------------------------------------------------------------------------------------------------------------------

Abschnitt Zusatzinformation
^^^^^^^^^^^^^^^^^^^^^^^^^^

Konformität
'''''''''''

.. figure:: ../../../img_ige/metaver_ige/ige_erfassung/ige_objekte/ige_objektklassen/objektklasse_geodatendienst/fachbezug/fachbezug_konformitaet.png

Abb.: Konformität

Hier muss angegeben werden, zu welcher Durchführungsbestimmung der INSPIRE-Richtlinie bzw. zu welcher anderweitigen Spezifikation die beschriebenen Daten konform sind. (INSPIRE-Pflichtfeld)

Dieses Feld wird bei der Auswahl der "INSPIRE-Themen" oder der "Art des Dienstes" automatisch befüllt. Es muss dann nur der Grad der Konformität manuell eingetragen werden.

.. important:: Bitte entsprechend den Empfehlungen des AdV-Metadatenprofils nur die Werte "konform" und "nicht konform" im Feld "Grad der Konformität" verwenden. Für alle nicht INSPIRE-Objekte, sollte hier die „INSPIRE-Richtlinie“ mit dem Wert „nicht evaluiert“ ausgewählt werden.


.. hint:: Die Abschnitte Raumbezugsystem, Zeitbezug, Zusatzinformation, Verfügbarkeit und Verweise sind ausführlich unter `Erfassung von Objekten <https://metaver-bedienungsanleitung.readthedocs.io/de/latest/metaver_ige/ige_erfassung/erfassung-objekte.html>`_  beschrieben, da sie auf mehrere Metadatentypen zutreffen.




