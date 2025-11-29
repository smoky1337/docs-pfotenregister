# Tier löschen

Löscht den Tierdatensatz endgültig. Keine Sperre durch Zahlungen o. Ä.

## Aufruf & Rollen
- Gastdetail → Tierkarte → **Löschen** (`/animals/<id>/delete`)
- Rollen: Admin, Editor

## Ablauf
1. Löschen bestätigen.
2. Tier wird entfernt; Changelog-Eintrag wird angelegt.
3. Rücksprung zur Gastansicht.

## Empfehlung
- Nur bei Fehlanlage/Testdaten löschen; sonst Status-Feld auf inaktiv setzen, damit Historie erhalten bleibt.
