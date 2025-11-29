# Admin: Feldsichtbarkeit & Erinnerungen

Im Einstellungsdialog gibt es zwei Tabs für Felder: **Feldsichtbarkeit** und **Erinnerungen**.

## Feldsichtbarkeit
- **Sichtbar**: Checkbox pro Feld, um es generell einzublenden.
- **Sichtbar für**: Rolle, die das Feld sehen darf (User/Editor/Admin).
- **Editierbar für**: Rolle, die das Feld bearbeiten darf.
- **UI-Label**: Anzeigename im Frontend.
- **Inline**: Feld in der kompakten Ansicht zeigen (z. B. Karten/Listen).
- **Reihenfolge**: Numerische Sortierung innerhalb des Modells.

**Ablauf**: Admin → Einstellungen → Tab *Feldsichtbarkeit* → Felder je Modell anpassen → *Feldsichtbarkeit speichern*.

## Erinnerungen
Nur für Datumsfelder verfügbar. Steuert Warnhinweise (z. B. ablaufende Nachweise).

- **Erinnerung aktiv**: Schalter je Feld.
- **Prüfintervall (Tage)**: z. B. 365 für jährliche Prüfung; 0 = warnen, sobald Datum überschritten.
- **Arten filtern**: Bei Tierfeldern optional Tierarten auswählen, für die die Erinnerung gilt (keine Auswahl = alle).

**Ablauf**: Admin → Einstellungen → Tab *Erinnerungen* → gewünschte Felder aktivieren → Intervall setzen → Speichern.

## Hinweise
- Rechte greifen additiv: Ein Feld kann sichtbar für „User“ sein, aber editierbar nur für „Admin“.
- Inline-Felder eignen sich für Schnellkarten; überfrachte die Ansicht nicht.
- Erinnerungen basieren auf gespeicherten Datumswerten; leere Felder erzeugen keine Warnungen.
