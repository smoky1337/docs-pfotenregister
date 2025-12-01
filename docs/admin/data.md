# Admin: Daten importieren & exportieren

Über diese Seiten lädst du größere Datenmengen ein oder sicherst sie als Excel.

## Daten importieren (Excel → Gäste & Tiere)
- **Aufruf**: Dashboard → *Daten importieren* (`/admin/import`)
- **Format**: Excel `.xlsx` mit den Sheets `gaeste` und `tiere`. Nutze die bereitgestellte Vorlage.
- **Ablauf**:
      - Vorlage herunterladen und ausfüllen. 
      - Datei hochladen → Vorschau öffnet sich.
      - Vorschau prüfen (Gäste + Tiere). Warnungen erscheinen, z. B. bei doppelten Nummern oder fehlender Gastnummer.
      - **Import bestätigen**. Erfolgreiche Datensätze werden angelegt.
- **Tipps**:
      - Pflichtspalten in der Vorlage befüllen (Nummer, Vorname, Nachname, Adresse).
      - Gastnummern müssen eindeutig sein; Tiere brauchen eine gültige Gastnummer.
      - Fehlerfreie Zeilen werden importiert, fehlerhafte übersprungen.

## Daten exportieren (Excel)
- **Aufruf**: Dashboard → *Daten exportieren* (`/admin/export`)
- **Was exportiert wird**: Tabellen Gäste, Tiere, Zahlungen, Nachrichten, Vertretungen – jeweils mit wählbaren Spalten.
- **Ablauf**:
    - Tabellen im Akkordeon aufklappen, gewünschte Spalten anhaken (Checkboxen).
    - Optional Kopfzeile aktiv lassen, damit Spaltennamen in der Datei stehen.
    - **Export starten** → XLSX wird mit einem Sheet pro Tabelle erzeugt.
- **Tipps**:
    - Mindestens eine Spalte muss ausgewählt sein, sonst startet der Export nicht. 
    - Datumsfelder werden ISO-formatiert (`YYYY-MM-DD`).
    - Verwende den Export regelmäßig als Backup oder zur Weitergabe an Behörden.
