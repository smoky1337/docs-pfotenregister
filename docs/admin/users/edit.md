# Admin: Nutzer bearbeiten oder löschen

Passe bestehende Accounts an oder entferne sie.

## Aufruf
- Dashboard → **Benutzerverwaltung** (`/admin/list_users`) → Nutzer auswählen.

## Bearbeiten
1. **Bearbeiten** öffnen (`/admin/users/<id>/edit`).
2. Felder anpassen: Benutzername, Rolle, Name. Optional neues Passwort setzen (leer lassen, wenn unverändert).
3. **Speichern**. Änderungen gelten sofort.

## Löschen
- In der Nutzerliste **Löschen** (POST auf `/admin/users/<id>/delete`) ausführen → der Account wird entfernt.

## Hinweise
- Passwortänderungen überschreiben das alte Passwort sofort.
- Löschen ist endgültig; lege den Nutzer neu an, falls er später wieder Zugang braucht.
