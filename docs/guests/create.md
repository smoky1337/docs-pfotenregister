# Gast registrieren

Formular mit 3 Schritten: persönliche Daten → Bedürftigkeit → Vertreter. Pflichtfelder sind mit * markiert.

## Aufruf & Rollen
- Startseite Schnellzugriff oder Gästeliste → **Neuen Gast erfassen** (`/guest/register`)
- Rollen: Admin, Editor

## Pflichtfelder & Automatik
- Pflicht: Vorname, Nachname, Adresse (immer), ggf. weitere laut Feldeinstellungen.
- Mitglied seit: Wenn leer, wird das heutige Datum gesetzt.
- Gästennummer/ID: werden automatisch generiert.

## Ablauf
1. **Persönliche Angaben**: Name, Adresse, Ort/PLZ, Kontakt, Geburtsdatum, Geschlecht, Status. Weiter nur, wenn Pflichtfelder gesetzt sind.
2. **Bedürftigkeit**: Art der Bedürftigkeit, gültig bis, Dokumente/Notizen. Weiter nur, wenn Bedürftigkeit gefüllt ist.
3. **Vertreter (optional)**: Name, Adresse, Telefon, E-Mail.
4. Abschluss wählen:
   - **Gast speichern**  → zurück zur Detailseite.
   - **Gast speichern und Tier erfassen**  → Tier-Anlage öffnet sich.

## Hinweise
- Felder erscheinen nur, wenn sie in den Feldeinstellungen global sichtbar sind.
- Doppelte Gäste (gleicher Name + Adresse) werden blockiert.
- Abbrechen-Modal schützt vor versehentlichem Verwerfen.
