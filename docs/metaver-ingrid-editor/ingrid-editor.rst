
Allgemeines zum InGrid Editor
=============================

Aufbau der Benutzeroberfläche
-----------------------------

Die Benutzeroberfläche setzt sich zusammen aus: 

1. Navigationsleiste
2. Toolbar (Symbolleiste)
3. Strukturbaum
4. Erfassungsmaske

[Grafik]

Strukturbaum
------------

Der InGrid Editor verfügt über einen Strukturbaum. Er unterteilt sich in Objekte und Adressen.

[Grafik]

Plus- und Minuszeichen
'''''''''''''''''''''''
Durch Klicken auf die Pluszeichen wird der Strukturbaum geöffnet bzw. durch Anklicken der Minuszeichen wieder geschlossen. Die Ordnung innerhalb einer Hierarchiestufe erfolgt alphabetisch nach Objektname bzw. Adresstitel und kann durch Verschieben oder Einfügen nicht geändert werden.

[Grafik]

Icon im Strukturbaum
--------------------

Objekte und Adressen
'''''''''''''''''''''

Der InGrid Editor beinhaltet unterschiedliche Objekt- und Adresstypen. Jeder Typ besitzt ein eigenes Symbol (Icon), welches im Strukturbaum des Editors und in der Portalansicht neben dem Objektnamen bzw. dem Adresstitel dargestellt wird. 

Hinweis:
Die blauen und roten Symbole werden im Strukturbaum des InGrid Editors verwendet (Backend), die schwarzen Symbole in der Portalansicht (Frontend).

**Objekte**

Portal	Editor	Objektklasse
 	 	        Geodatensatz
 	 	        Geodatendienst
 	 	        Anwendung
 	 	        Datenbank
 	 	        Dokument
 	 	        Projekt
 	 	        Organisationseinheit


**Adressen**

Portal	Editor	Adresstyp
 	 	        Institution
 	 	        Einheit
 	 	        Person


Ordner
''''''

Der Strukturbaum wird mit Ordnern erstellt.

**Hinweis:**
In einer zukünftigen neuen Version der Software kann die Struktur nur noch mit Ordnern angelegt werden. Die Möglichkeit eine Struktur mit Objektklassen aufzubauen entfällt.

[Grafik]


Bearbeitungsstand
'''''''''''''''''

Neben dem Objekttyp bzw. dem Adresstyp zeigen die Icons im Editor zusätzlich den jeweiligen Bearbeitungsstand an. 

[Icons]

Blau	Objekt bzw. Adresse ist veröffentlicht
Rot	Objekt bzw. Adresse ist in Bearbeitung (Icon mit Buchstaben „B“ für Bearbeitung)
Blau / Rot	Wird ein blaues Icon rot überlagert, so gibt es eine veröffentlichte Version des Objektes bzw. der Adresse und eine bearbeitete Version 


Veröffentlichungsbreite
'''''''''''''''''''''''

Jedem Objekt und jeder Adresse im Metadatenkatalog muss eine Veröffentlichungsbreite angegeben werden (Feld: „Veröffentlichung“).

Der Editor enthält folgende drei Auswahlmöglichkeiten:

[Icons]

- Internet
- Intranet (Landesdatennetz - im Metadatenkatalog Sachsen-Anhalt nicht möglich)
- amtsintern

Im Strukturbaum wird die Veröffentlichungsbreite der jeweiligen Objekte angezeigt. Die Veröffentlichungsbreite „Internet“ wird nicht gesondert markiert, die Veröffentlichungsbreite „Intranet“ wird mit einem kleinen blauen Quadrat links unterhalb des Objekttypensymbols dargestellt und „amtsintern“ mit einem kleinen roten Quadrat. 

**Internet**
Das Objekt/die Adresse wird im Internet im MetadatenVerbund (MetaVer) unter www.metaver.de/ veröffentlicht. Durch die Veröffentlichung auf www.metaver.de/ werden die Daten automatisch auch für andere Informationssysteme bereitgestellt. Hierzu zählen zum Beispiel das Geoportal Deutschlands (Geoportal.de) www.geoportal.de/, in dem Geodaten aus ganz Deutschland recherchiert werden können und das INSPIRE GEOPORTAL https://inspire-geoportal.ec.europa.eu/, das die europaweite Suche nach Geodatenressourcen im Geltungsbereich von INSPIRE ermöglicht.

**Intranet**
Das Objekt/die Adresse darf nicht im Internet, sondern nur im Intranet veröffentlicht werden. 

Hinweis:
Die Funktion „Intranet“ ist für den Metadatenkatalog Sachsen-Anhalt nicht relevant, da der Metadatenkatalog nicht über das Intranet erreichbar ist.

**amtsintern**
Das Objekt/die Adresse ist nur im Editor einsehbar. Das Objekt/die Adresse wird weder im Internet noch im Intranet angezeigt. Personen ohne Zugang zum InGrid Editor können diese Objekte/die Adressen nicht recherchieren. 


Ausgegraute Objekte/Adressen im Strukturbaum
''''''''''''''''''''''''''''''''''''''''''''

Teilweise werden im Strukturbaum Objekte oder Adressen nicht schwarz, sondern nur in grau angezeigt. Dieses hängt mit der Zuweisung von Berechtigungen zusammen. Ändern kann ein Erfasser nur die Objekte/Adressen, die im Strukturbaum schwarz dargestellt sind.

 

Das IGE-Kontextmenü
--------------------

[Grafik]

Wenn ein Objekt im Strukturbaum markiert wurde, kann das Kontextmenü mit der rechte Maustaste geöffnet werden.

**Neu anlegen**
Dient dem Anlegen einer neuen Adresse oder eines neuen Objektes im Strukurbaum.

**Ordner erstellen**
Mit Ordner erstellen kann im Strukturbaum eine Hierarchie aufgebaut werden. Unter dem letzten Ordner werden dann die Objekte angelegt. 

**Vorschau und Druckansicht**
Die Druckfunktion ist unter dem Punkt „Drucken von Teilbäumen und Suchergebnissen“ ausführlich beschrieben.

**Objekte/Adressen/Teilbäume ausschneiden**
Adressen und Objekte oder Teile des Strukturbaumes lassen sich über diese Funktion ausschneiden.

**Objekte/Adressen kopieren**
Adressen und Objekte lassen sich über diese Funktion kopieren.

**Teilbaume kopieren**
Teile des Strukturbaumes lassen sich über diese Funktion kopieren.

**Einfügen**
Funktion für das Einfügen von ausgeschnittenen oder kopierten Adressen, Objekten und Teilbäumen.

**Teilbaum neu laden**
Werden mehrere Adressen oder Objekte auf einer Ebene nacheinander angelegt, so stehen diese nicht alphabetisch geordnet untereinander. Über diese Funktion kann die darüber liegende Adresse oder das Objekt angeklickt werden und der Teil-Baum wird im IGE neu geladen. Nach dem Laden stehen die Adressen/Objekte alphabetisch geordnet im Strukturbaum.

**Löschen**
Löschen von Adressen, Objekten oder Teilbaumen aus dem Strukurbaum.

- Ändern auf Internet
- Ändern auf Intranet
- Ändern auf amtsintern

Mit diesen Funktionen wird die Veröffentlichungsbreite der Adressen / Objekte geregelt.


IGE-Toolbar (Symbolleiste)
--------------------------

[Grafik]

Hier im Einzelnen die zur Verfügung stehenden Werkzeuge: 

**Neu anlegen**

Dient dem Anlegen einer neuen Adresse oder eines neuen Objektes im Strukurbaum.

**Neuen Ordner anlegen**

Mit Ordner erstellen kann im Strukturbaum eine Hierarchie aufgebaut werden. Unter dem letzten Ordner werden dann die Objekte angelegt.

**Vorschau und Druckansicht**

Die Druckfunktion ist unter dem Punkt „Drucken von Teilbäumen und Suchergebnissen“ ausführlich beschrieben.

**ISO-XML Anzeige**

Zeigt das erstellte Metadatenobjekt als ISO-XML an. 

[Grafik]


Objekte / Adresse / Teilbaum ausschneiden
Objekt / Adresse kopieren
Teilbäume kopieren
Einfügen (Objekt / Adresse / Teilbaum)

Zwischenspeichern
Rückgängig
Änderungen am aktuellen Objekt / Adresse verwerfen

Abschließendes Speichern & Veröffentlichen
Ausgewähltes Objekt / Adresse / Teilbaum löschen
Änderungen anzeigen

Kommentar ansehen / hinzufügen

Klicken, um zum vorherigen Objekt / Adresse zu gehen.
Gedrückt halten für Verlauf
Klicken, um zum nächsten Objekt / Adresse zu gehen.
Gedrückt halten für Verlauf

Alle Felder aufklappen / nur Pflichtfelder aufklappen

Hilfe


Erläuterung der Toolbar-Funktionen
----------------------------------

Objekt / Adresse löschen
^^^^^^^^^^^^^^^^^^^^^^^^


