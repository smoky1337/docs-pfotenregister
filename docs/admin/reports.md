# Admin: Berichte & Zahlungsexport

Der Bericht „Zahlungen exportieren“ erstellt eine tabellarische Ansicht aller Zahlungen in einem Zeitraum und bietet einen PDF-Download.

## Aufruf
- Dashboard → Button **Zahlungen exportieren** (öffnet Modal mit Datumswahl)  
- URL: `/admin/export_transactions` (GET mit `from` und `to` als `YYYY-MM-DD`)

## Schritte
1. Zeitraum wählen (Presets: 7/30/90/180 Tage, seit 01.01. oder „Alle“).
2. Export starten. Die Tabelle zeigt pro Zahlung: Datum, Gastnummer, Name, Futterbetrag, Zubehörbetrag, Kommentar.
3. Optional **Drucken/Als PDF speichern** klicken (`/admin/print_export_transactions`) – erzeugt ein PDF mit Summenzeile.

## Hinweise
- Es werden nur bestätigte Zahlungen im gewählten Zeitraum berücksichtigt.
- Summen für Futter und Zubehör werden automatisch berechnet.
- Datumseingaben müssen gültig sein (`YYYY-MM-DD`); sonst bricht der Export mit Hinweis ab.
