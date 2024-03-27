# Kita-Belegungsliste

Die Exceldatei ermöglicht es eine Übersicht über die Belegungslisten für eine Kita zu haben.

## Makro freigeben

Damit das Excel mit dem Makro arbeiten kann, muss die Datei entweder gemäss [Anleitung](https://support.microsoft.com/de-de/office/aktivieren-oder-deaktivieren-von-makros-in-microsoft-365-dateien-12b036fd-d140-4e74-b45e-16fed1a7e5c6) freigeschalten werden. Nicht allgemein für alle Dateien aktivieren, sondern nur für diese.

## Anleitung

Die Datei beinhaltet vier Makros, welche die Bedienung vereinfachen:

| Name           	        | Short-Key    		| Beschreibung  |
|---------------------------|-------------------|---------------|
| Jahresbelegung_erstellen	|-                  | Erstellt alle nötigen Tabblätter mit den Information aus dem Übersichtsblatt. |
| Person_Hinzufuegen	    |`Ctrl + Shift + N` | Fügt in der Kinder-Tabelle eine neue Zeile unterhalb der ausgewählten Zeile ein. |
| Person_Entfernen		    |`Ctrl + Shift + D` | Löscht die aktive Zeile. |
| Monat_Fuellen	            |`Ctrl + q`			| Ergänzt alle Formel, falls mal eine bei der Monatsübersicht gelöscht wird. |

### Jahresbelegung_erstellen			

Fülle die Spalten B2, B3, B4 und in der Tabelle A7 bis D7 für jede Gruppe eine Zeile aus. Anschliessend erstellst du über den Button "Belegung erstellen" alle nötigen Blätter für deine Belegungsliste. Solltest du den Button mal nicht sehen, vergrössere und verkleinere eine Spalte

### Person_Hinzufuegen	

Falls du in den Gruppenblätter wieder die korrekte Formen anlegen möchtest, kannst du dies mit Ctrl + q machen. Wähle anschliessend den gewünschten Bereich und das Makro füllt die Formen wieder korrekt ein.

### Person_Entfernen

Du kannst in den Gruppenblätter mit Ctrl + Shift + N eine neue Zeile einfügen. Einfach eine Zelle anklicken und das Makro fügt darunter eine neue Zeile ein und kopiert alle Formen von der übergeordneten Zeile.

### Monat_Fuellen

Du kannst mit Ctrl + Shift + D die aktive Zeile löschen, falls du eine Person aus der Liste entfernen möchtest

## Änderungen	

| Datum           	        | Änderungen  		| 
|---------------------------|-------------------|
| 26.03.2024	|Neues Makro um Belegung zu erstellen und Person zu entfernen.                 |
