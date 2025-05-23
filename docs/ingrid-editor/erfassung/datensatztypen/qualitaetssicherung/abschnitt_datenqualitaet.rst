
Abschnitt Datenqualität
^^^^^^^^^^^^^^^^^^^^^^^

Datendefizit
""""""""""""
.. figure:: ../../../../img/ige/erfassung/ige_metadaten/abschnitt-05_datenqualitaet/daten-defizit.png
   :alt: Feld Datendefizit
   :align: left
   :scale: 70
   :figwidth: 100%

Abb.: Feld Datendefizit

Eingabe einer Prozentangabe zum Anteil der Daten, die im Vergleich zum beschriebenen Geltungsbereich fehlen. Diese kann sich auf die Anzahl der Kartenblätter aber auch auf das Datendefizit einer Gesamtkarte beziehen.

Beispiel: 55

Wenn der Erfassungsgrad bei 100% liegt, ist in dem Feld Datendefizit 0% einzutragen. (Datendefizit = 100 – Erfassungsgrad) 


Datengenauigkeit
""""""""""""""""

.. figure:: ../../../../img/ige/erfassung/ige_metadaten/abschnitt-05_datenqualitaet/daten-genauigkeit.png
   :alt: Felder für die Datengenauigkeit
   :align: left
   :scale: 100
   :figwidth: 100%
 
Abb.: Felder für die Datengenauigkeit

**Höhengenauigkeit**

Angabe über die Genauigkeit der Höhe z.B. in einem Geländemodell.

Beispiel: 3 (m)


**Lagegenauigkeit**

Angabe über die Genauigkeit z.B. in einer Karte.

Beispiel: 3 (m)


Qualitätsinformationen
""""""""""""""""""""""

.. figure:: ../../../../img/ige/erfassung/ige_metadaten/abschnitt-05_datenqualitaet/qualitaetsinformationen-hinzufuegen.png
   :alt: Feld+ für weitere Qualitätsinformationen
   :align: left
   :scale: 90
   :figwidth: 100%
 
Abb.: Feld+ für weitere Qualitätsinformationen


1. Datenüberschuss
""""""""""""""""""

.. figure:: ../../../../img/ige/erfassung/ige_metadaten/abschnitt-05_datenqualitaet/daten-ueberschuss.png
   :alt: Feld Datenüberschuss
   :align: left
   :scale: 100
   :figwidth: 100%
 
Abb.: Feld Datenüberschuss


Auswahlmöglichkeit für das Feld Art der Messung:

- Number of duplicate feature instances
- Rate of excess items


Angaben zu den überschüssigen Features, Attributen oder ihren Relationen.

Beispiel: Anzahl der überflüssigen Elemente zur Anzahl der gesamten Elemente: 11,2%

.. hint:: Es wird nur eine Zahl angegeben; kein %-Zeichen.


2. Konzeptionelle Konsistenz
""""""""""""""""""""""""""""

.. figure:: ../../../../img/ige/erfassung/ige_metadaten/abschnitt-05_datenqualitaet/konsistenz-konzeptionelle.png
   :alt: Feld Konzeptionelle Konsistenz
   :align: left
   :scale: 100
   :figwidth: 100%
 
Abb.: Feld Konzeptionelle Konsistenz


Auswahlmöglichkeit für das Feld Art der Messung:

- Compliance rate with the rules of the conceptual schema
- Conceptual Schema compliance
- Number of invalid overlaps of surfaces


Angaben zu Fehlern bezüglich der Verletzung der Regeln des konzeptionellen Schemas

Beispiel: Anzahl der überlappenden Oberflächen innerhalb des Datensatzes: 23


3. Konsistenz des Wertebereichs
"""""""""""""""""""""""""""""""


.. figure:: ../../../../img/ige/erfassung/ige_metadaten/abschnitt-05_datenqualitaet/konsistenz-wertebereich.png
   :alt: Feld Konsistenz des Wertebereichs
   :align: left
   :scale: 100
   :figwidth: 100%
 
Abb.: Feld Konsistenz des Wertebereichs


Auswahlmöglichkeit für das Feld Art der Messung:

- Value domain non conformance rate


Angaben zur Übereinstimmung des Wertebereichs - Angegeben wird die Anzahl der Übereinstimmungen im Verhältnis zur Gesamtmenge der Elemente.


4. Formatkonsistenz
"""""""""""""""""""

.. figure:: ../../../../img/ige/erfassung/ige_metadaten/abschnitt-05_datenqualitaet/konsistenz-format.png
   :alt: Feld Formatkonsistenz
   :align: left
   :scale: 100
   :figwidth: 100%
 
Abb.: Feld Formatkonsistenz


Auswahlmöglichkeit für das Feld Art der Messung:

- Physical structure conflict rate


Angaben darüber, wie viele Elemente sich im Konflikt zu der physikalischen Struktur des Datensatzes befinden.


5. Topologische Konsistenz
""""""""""""""""""""""""""

.. figure:: ../../../../img/ige/erfassung/ige_metadaten/abschnitt-05_datenqualitaet/konsistenz-topologie.png
   :alt: Feld Topologische Konsistenz
   :align: left
   :scale: 100
   :figwidth: 100%
 
Abb.: Feld Topologische Konsistenz


Auswahlmöglichkeit für das Feld Art der Messung:

- Number of closed watercourse links
- Number of faulty point-curve connections
- Number of invalid overlaps of surfaces
- Number of invalid self-intersect errors
- Number of invalid self-overlap errors


Angaben zu topologischen Fehlern, die zwischen verschiedenen Unterelementen des Datensatzes auftreten.

Beispiel: Anzahl fehlender Verbindungen zwischen Unterelementen aufgrund von Undershoots/Überschreitungen.

 
6. Zeitliche Genauigkeit
""""""""""""""""""""""""

.. figure:: ../../../../img/ige/erfassung/ige_metadaten/abschnitt-05_datenqualitaet/genauigkeit-zeitlich.png
   :alt: Feld Zeitliche Genauigkeit
   :align: left
   :scale: 100
   :figwidth: 100%
 
Abb.: Feld Zeitliche Genauigkeit


Auswahlmöglichkeit für das Feld Art der Messung:

- Percentage of items that are correctly events ordered


Angabe der Anzahl der zeitlich korrekt zugeordneten Elemente zur Gesamtzahl der Elemente.


7. Korrektheit der thematischen Klassifizierung
"""""""""""""""""""""""""""""""""""""""""""""""

.. figure:: ../../../../img/ige/erfassung/ige_metadaten/abschnitt-05_datenqualitaet/klassifizierung-thematisch.png
   :alt: Feld Korrektheit der thematischen Klassifizierung
   :align: left
   :scale: 100
   :figwidth: 100%

Abb.: Feld Korrektheit der thematischen Klassifizierung


Auswahlmöglichkeit für das Feld Art der Messung:

- Misclassification rate


Angabe der Anzahl der thematisch falsch klassifizierten Elemente zur Gesamtanzahl der Elemente.


8. Genauigkeit nicht-quantitativer Attribute
"""""""""""""""""""""""""""""""""""""""""""""


.. figure:: ../../../../img/ige/erfassung/ige_metadaten/abschnitt-05_datenqualitaet/genauigkeit-nicht-quantitativer-attribute.png
   :alt: Feld Genauigkeit nicht-quantitativer Attribute
   :align: left
   :scale: 100
   :figwidth: 100%

Abb.: Feld Genauigkeit nicht-quantitativer Attribute


Auswahlmöglichkeit für das Feld Art der Messung:

- Number of incorrect attribute values
- Rate of incorrect classification for national identifier


Angabe der Anzahl der inkorrekten nicht-quantitativen Attributwerte im Verhältnis zur Gesamtzahl der Attribute.


9. Genauigkeit quantitativer Attribute
"""""""""""""""""""""""""""""""""""""""


.. figure:: ../../../../img/ige/erfassung/ige_metadaten/abschnitt-05_datenqualitaet/genauigkeit-quantitativer-attribute.png
   :alt: Feld Genauigkeit quantitativer Attribute
   :align: left
   :scale: 100
   :figwidth: 100%

Abb.: Feld Genauigkeit quantitativer Attribute


Auswahlmöglichkeit für das Feld Art der Messung:

- Attribute value uncertainty at 95 % significance level


Angabe der Anzahl der quantitativen Attribute, die inkorrekt sind.

Beispiel: Anzahl aller quantitativen Werte, die nicht mit 95% Wahrscheinlichkeit dem wahren Wert entsprechen.


10. Relative Positionsgenauigkeit
""""""""""""""""""""""""""""""""""

.. figure:: ../../../../img/ige/erfassung/ige_metadaten/abschnitt-05_datenqualitaet/relative-positionsgenauigkeit-1.png
   :alt: Feld Relative Positionsgenauigkeit
   :align: left
   :scale: 100
   :figwidth: 100%
 
Abb.: Feld Relative Positionsgenauigkeit


Auswahlmöglichkeit für das Feld Art der Messung:

- mean value of positional uncertainties (1D)
- mean value of positional uncertainties (2D)
- mean value of positional uncertainties (3D)


Genauigkeitsangabe bezüglich einer als richtig akzeptierten Bezugs- oder Sollposition



Qualitätsinformationen übersetzt
""""""""""""""""""""""""""""""""

Übersetzte Auswahlmöglichkeiten für das Feld Art der Messung.

1. Datenüberschuss

  - Anzahl doppelter Einträge
  - Rate überzähliger Elemente

2. Konzeptionelle Konsistenz

  - Übereinstimmungsrate mit den Regeln des konzeptionellen Schemas
  - Einhaltung des konzeptionellen Schemas
  - Anzahl ungültiger Überlappungen von Flächen

3. Konsistenz des Wertebereichs

  - Rate der Nichteinhaltung des Wertebereichs

4. Formatkonsistenz

  - Rate der Konflikte in der physischen Struktur

5. Topologische Konsistenz

  - Anzahl geschlossener Wasserläufe
  - Anzahl fehlerhafter Punkt-Kurven-Verbindungen
  - Anzahl ungültiger Flächenüberlappungen
  - Anzahl ungültiger Selbstüberschneidungen
  - Anzahl ungültiger Selbstüberlappungen
  - Anzahl ungültiger Splitter
  - Anzahl fehlender Verbindungen aufgrund von Brücken/Straßenkreuzungen
  - Anzahl fehlender Verbindungen aufgrund von Überständen
  - Anzahl fehlender Verbindungen aufgrund von Unterständen
  - Anzahl mehrteiliger Wasserläufe
  - Anzahl von Wasserläufen unter der Mindestlänge

6. Zeitliche Konsistenz

  - Prozentsatz korrekt zeitlich geordneter Elemente

7. Korrektheit der thematischen Klassifizierung

  - Fehlklassifizierungsrate

8. Genauigkeit nicht-quantitativer Attribute

  - Anzahl falscher Attributwerte
  - Rate falscher Klassifizierungen für nationale Kennungen

9. Genauigkeit quantitativer Attribute

  - Attributwert-Unsicherheit bei 95% Signifikanzniveau

10. Relative Positionsgenauigkeit

  - Mittelwert der Positionsunsicherheiten (1D, 2D, 3D)