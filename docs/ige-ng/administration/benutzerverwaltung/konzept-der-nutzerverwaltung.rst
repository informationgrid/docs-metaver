Konzept der Benutzerverwaltung
==============================

Der InGrid-Editor ist eine Komponente der Portal-Software InGrid. Durch die Verknüpfung der Benutzerverwaltungen von METAVER und des InGrid-Editors ergibt sich der Vorteil, dass sich ein Benutzer nur einmal zentral im Portal anmelden muss.

Die InGrid-Benutzerrechte, werden in der Gruppenadministration der InGrid Editor-Benutzerverwaltung festgelegt. Zunächst werden Gruppen definiert, die spezifische Rechte für einen Teilbereich des Katalogs aufweisen und anschließend die Benutzer einer oder mehreren Gruppen zugeordnet.

Im InGrid Editor werden hierbei folgende Rechte (Rollen) unterschieden:

**1. Katalog-Administrator:** Es gibt nur einen Benutzer mit diesen Rechten. Er hat das Recht alle Verwaltungsfunktionen bedienen zu dürfen und kann Benutzer auf allen darunterliegenden Hierarchieebenen mit Schreibrechten auf beliebige Teilbäume erstellen.

**2. Metadaten-Administrator:** Er darf von den Verwaltungsfunktionen nur die Benutzerverwaltung bedienen. Er darf Benutzer mit der Rolle Metadaten-Autor erstellen. Die Rechte dieser Benutzer dürfen aber maximal den Rechten des jeweiligen Metadaten-Administrators entsprechen (z.B. Schreibrechte nur auf einen Teilbaum des Katalogs).

**3. Metadaten-Autor:** Er hat Schreibrechte auf einen Teilbaum des Kataloges, hat aber keinen Zugang zur Benutzerverwaltung oder zu anderen Verwaltungsfunktionen.

Der Katalog-Administrator kann Metadaten-Autoren unter beliebigen Metadaten-Administratoren einrichten. Ein Metadaten-Administrator hat immer das Recht, die ihm nachgeordneten Metadaten-Autoren zu administrieren.
