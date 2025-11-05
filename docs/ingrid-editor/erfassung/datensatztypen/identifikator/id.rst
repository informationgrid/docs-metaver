Identifikatoren (ID) unterscheiden
-----------------------------------

Der InGrid Editor beinhaltet zwei Identifikatoren (ID).

Diese werden unterschieden in den Identifikator der Metadaten und im Datensatztyp "Geodatensatz" (im Abschnitt Fachbezug) in den Identifikator der Datenquelle.


Identifikator der Metadaten (Metadatensatz-ID)
----------------------------------------------

Der Identifikator der Metadaten ist eine UUID.

Eine UUID (Universally Unique Identifier) ist eine 128 Bit lange Zufallszahl. Sie wird dazu benutzt, Informationen in Computersystemen eindeutig zu identifizieren. UUIDs sind gut geeignet, um Objekte zu identifizieren, ohne dass man eine zentrale Registrierungsstelle braucht. Eine UUID hat 36 Stellen und wird mit Bindestrichen getrennt. Sie sieht zum Beispiel so aus: 123e4567-e89b-12d3-a456-426614174000.

Der Identifikator der Metadaten befindet sich im Kopf jedes Metadatensatzes und wird bei dessen Erstellung automatisch generiert. Mithilfe dieser ID kann der Metadatensatz eindeutig identifiziert werden. So lässt sich beispielsweise feststellen, ob dieser Metadatensatz in einem Portal einmal oder mehrfach vorhanden ist. Auf diese Weise können doppelte Metadatensätze herausgefiltert werden.

.. figure:: ../../img/ige/allgemein/metadatensatz-id.png
   :alt: Metadatensatz-ID
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Metadatensatz-ID im Kopf eines Metadatensatzes

.. hint:: Mithilfe des Identifikators der Metadaten kann nach einem bestimmten Metadatensatz gesucht werden. Hierzu wird die ID im Portal in die Suchleiste eingetragen und die Suche gestartet.

.. important:: Der Identifikator der Metadaten ist nicht mit dem Identifikator der Datenquelle gleichzusetzen! Da sie unterschiedlichen Zwecken dienen, müssen sie voneinander abgegrenzt werden.


Identifikator der Datenquelle (Daten-ID)
----------------------------------------

Der Identifikator der Datenquelle wird nur im Datensatztyp „Geodatensatz” verwendet. Er kennzeichnet die Datenquelle eindeutig. Dies ist aus mehreren Gründen wichtig.


Funktion und Zweck des Identifikators
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

**Eindeutige Zuordnung:** Mithilfe des Identifikators kann eine spezifische Geodatengrundlage (z. B. eine Karte oder ein Kartenlayer) eindeutig identifiziert werden – unabhängig von Veränderungen an anderen Metadaten oder den Daten selbst.

**Vermeidung von Dopplungen:** Durch den Einsatz eines einmaligen, unveränderlichen Identifikators (wie einer UUID) lassen sich doppelte Daten und Kopien vermeiden. Dies erleichtert die Verwaltung der Daten und gewährleistet deren Integrität – also Genauigkeit, Vollständigkeit, Konsistenz und Zuverlässigkeit – über ihren gesamten Lebenszyklus hinweg.

**Verlässliche Verweise:** In Anwendungen, Portalen oder bei Datenaustauschprozessen ist eine eindeutige Referenz auf die Datenquelle wichtig, um Verwechslungen oder falsche Zuordnungen zu vermeiden. Der unveränderte Identifikator unterstützt zudem die Nachvollziehbarkeit der Herkunft und etwaiger Versionen der Datenquelle. Dies ist insbesondere bei Updates oder Kopien von Geodatensätzen von Bedeutung.

**Zusammenfassung:** Der Identifikator der Datenquelle in einem Metadatensatz dient also in erster Linie dazu, die Datenquelle eindeutig zu erkennen, zu verknüpfen und zu verwalten. Er bildet das Fundament für eine zuverlässige, lückenlose Nachverfolgung und den sicheren Austausch von Geodaten. Dies ist essenziell für die Qualitätssicherung und Interoperabilität im Geodatenmanagement.


.. hint:: Der Identifikator der Datenquelle wird nicht automatisch angelegt. Er muss entweder manuell in das entsprechende Feld eingetragen oder über den Schalter „ERZEUGE ID“ generiert werden.


Den Identifikator der Datenquelle eintragen oder generieren
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Der Identifikator der Datenquelle besteht aus einer URI.

.. hint:: Eine URI (Uniform Resource Identifier) ist eine standardisierte Zeichenkette, die man benutzt, um etwas im Internet oder in einem Datenraum eindeutig zu identifizieren.

Die URI besteht aus dem Namensraum und dem Identifikator der Datenquelle. Der Namensraum sieht zum Beispiel so aus: https://registry.gdi-de.org/id/de.st/. Der Namensraum steht in den Katalogeinstellungen und wird vom Metadatenkatalogadministrator verwaltet. Der Identifikator der Datenquelle wird im Datensatztyp "Geodatensatz" im Abschnitt "Fachbezug" eingetragen oder erzeugt.

.. figure:: ../../img/ige/allgemein/daten-id.png
   :alt: Daten-ID
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: Daten-ID im Datentyp "Geodatensatz"

.. figure:: ../../img/ige/allgemein/inspire-daten-id.png
   :alt: INSPIRE-Daten-ID
   :align: left
   :scale: 50
   :figwidth: 100%

Abb.: INSPIRE-Daten-ID im Datentyp "Geodatensatz"



Identifikator (ID) der Datenquelle - Beispiele:

| Generierte Daten-ID: 8c68ed4c-aa22-4e54-99ee-08a964103301
| händisch eingetragene INSPIRE-Daten-ID: lvermgeo.lu.alkis



URI - Beispiele:

| https://registry.gdi-de.org/id/de.st/8c68ed4c-aa22-4e54-99ee-08a964103301
| https://registry.gdi-de.org/id/de.st/lvermgeo.lu.alkis

Die manuell eingetragene ID wird von der datenhaltenden Stelle vergeben und kennzeichnet den Datensatz in der INSPIRE-Registry der GDI-DE eindeutig.

.. hint:: Die INSPIRE Registry ist eine zentrale Zugriffsplattform für mehrere zentral verwaltete Register, die im Zusammenhang mit der INSPIRE-Richtlinie der Europäischen Union verwendet werden. Sie dient dazu, eindeutige und persistente Bezeichner (Identifikatoren) für verschiedene Elemente der INSPIRE-Infrastruktur bereitzustellen.
