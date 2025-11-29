# Zahlung als bezahlt markieren

Schließt eine offene Zahlung ab, setzt `paid=true` und das Bezahldatum auf heute.

## Aufruf & Rollen
- Gastdetail → offene Zahlung → **Als bezahlt markieren** (`/payments/<id>/mark_as_paid/`)
- Rollen: Admin, Editor

## Schritte
1. Offene Zahlung auswählen.
2. **Als bezahlt markieren** klicken.
3. Zahlung wird abgeschlossen; Bezahldatum gesetzt.

## Hinweise
- Bereits bezahlte Zahlungen können nicht erneut markiert werden.
- Nutze offene Zahlungen, wenn der Betrag erst später eingeht, und schließe sie dann hier ab.
