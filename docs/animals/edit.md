# Tier bearbeiten

Die Maske blendet nur Felder ein, die du sehen/bearbeiten darfst. Änderungen werden protokolliert.

## Aufruf & Rollen
- Gastdetail → Tierkarte → **Bearbeiten** (`/animals/<id>/edit`)
- Rollen: Admin, Editor

## Ablauf
1. Formular mit dynamischen Labels (aus Feldeinstellungen) öffnet sich.
2. Felder, die du nicht editieren darfst, sind schreibgeschützt.
3. Speichern

## Hinweise
- Systemfelder (ID, Gast-ID, erstellt am) sind gesperrt.
- Änderungen landen im Changelog des Gastes.
