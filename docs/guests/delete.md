# Gast löschen

Entfernt Gast, Tiere, Futterhistorie und Changelog. Nur Admin und nur, wenn keine Zahlungen existieren.

## Aufruf
- Gästeliste → Dropdown → „Löschen/Deaktivieren“ (aktive) bzw. „Löschen/Aktivieren“ (inaktive) → Modal bestätigen.

## Bedingungen
- Wenn Zahlungen zum Gast vorhanden sind, wird das Löschen blockiert („buchhalterisch relevant“). In diesem Fall nur deaktivieren.

## Wirkung
- Tiere, FoodHistory, Changelog werden mitgelöscht.
- Payments bleiben bestehen – daher Löschung gesperrt, wenn sie existieren.

## Datenschutz 
Sollte ein Gast trotz getätigter Zahlungen aus den System entfernt werden, können DSGVO-relevante Informationen gegen Anonymisierte ausgetauscht werden. 