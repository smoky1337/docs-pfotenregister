# Ausgleichszahlung (Gegenbuchung)

Erzeugt eine negative Buchung, die eine vorhandene Zahlung neutralisiert.

## Aufruf & Rollen
- Gastdetail → Zahlung → **Ausgleich** (`/payments/<id>/create_offset`)
- Rollen: Admin, Editor

## Ablauf
1. Zahlung auswählen.
2. „Ausgleich“ auslösen → System erstellt einen Eintrag mit negativen Beträgen und Kommentar „Ausgleich für Zahlung #…“.
3. Beide Buchungen (positiv und negativ) bleiben sichtbar.

## Hinweise
- Nutze Ausgleich statt Löschen, wenn eine bezahlte Buchung falsch ist.
- Für offene, unbezahlte Zahlungen kannst du stattdessen löschen oder als bezahlt markieren.
