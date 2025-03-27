
======
Rollen
======

Die Benutzerrechte im InGrid Editor werden in der Verwaltung der Benutzer des InGrid Editors in der Gruppenadministration festgelegt. Zunächst müssen Gruppen definiert werden, die spezifische Rechte für einen Bereich des Katalogs aufweisen, und anschließend werden die Benutzer einer oder mehreren Gruppen zugeordnet.

Dabei werden im InGrid Editor folgende Rechte (Rollen) unterschieden:

**1. Autor:** Er hat Zugriff auf einen Teil des Verzeichnisbaums, aber keine Berechtigung zur Benutzerverwaltung oder anderen Verwaltungsfunktionen.

**2. Metadaten-Administrator:** Er soll nur die Benutzerverwaltungsfunktionen bedienen und hat keinen Zugang zu anderen Administrationsfunktionen. Der Metadaten-Administrator hat ausschließlich Zugriff auf die Verwaltungsfunktionen für Benutzer und darf lediglich Benutzer mit der Rolle Metadaten-Autor erstellen. Die Rechte der erstellten Benutzer dürfen maximal denen des Metadaten-Administrators entsprechen, z. B. Beschränkung der Schreibrechte auf einen bestimmten Teilbaum des Katalogs.

**3. Katalog-Administrator:** Er ist befugt, sämtliche Verwaltungsfunktionen zu bedienen und kann Benutzer auf allen untergeordneten Hierarchieebenen mit Schreibrechten für beliebige Teilbäume erstellen.

Eine Stufe über dem Katalogadministrator befindet sich der Superadministrator, der vom Katalogadministrator bei technischen Problemen kontaktiert wird.


.. figure:: ../../../img/ige/administration/benutzerverwaltung/rollen.png
   :alt: Benutzerverwaltung - Rollen
   :scale: 60
   :figwidth: 100%

Abb.: Benutzerverwaltung - Rollen

Der Katalog-Administrator kann Autoren und Metadaten-Administratoren einrichten. Ein Metadaten-Administrator hat immer das Recht, die ihm nachgeordneten Autoren zu verwalten.


