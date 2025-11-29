# Zahlung erfassen

Direkte Zahlung oder offene Buchung (Checkbox „bezahlt“) pro Gast.

## Aufruf & Rollen
- Gastdetail → Bereich **Zahlungen** → Formular „Zahlung erfassen“ (`/payments/new_direct/<guest_id>/`)
- Rollen: Admin, Editor (nur wenn Zahlungsmodul aktiv)

## Schritte
1. Beträge eingeben: `futter_betrag` und/oder `zubehoer_betrag`.
2. Kommentar ergänzen (frei).
3. Checkbox **bezahlt** setzen, wenn Geld erhalten. Wenn nicht gesetzt, bleibt die Zahlung offen.
4. Speichern → Zahlung wird angelegt (Datum = heute).

## Hinweise
- Zahlungen welche noch nicht Bezahlt sind, können später als bezahlt markiert oder gelöscht werden.
- Zahlungen welche verbucht sind, sind fest; löschen ist dann gesperrt.
