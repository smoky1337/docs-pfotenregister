# Gast ansehen (Detail)

Die Detailseite zeigt dynamisch nur die Felder, die in den Feldeinstellungen freigegeben sind. Du findest Gastdaten, Vertreter, Tiere, Ausgaben, Zahlungen, Dokumente und Nachrichten.

## Inhalt & Blöcke
- **Erinnerungen**: Optionaler, roter Akkordeonblock mit überfälligen/fehlenden Datumsfeldern (Einstellbar im Erinnerungsseinstellungen).
- **Nachrichten**: Oben-Rechts: Dropdown mit offenen Nachrichten, per Klick „erledigt“.
- **Status/Name**: Grün: aktiv/ Rot:inaktiv; Benachrichtigungsicon für offene Nachrichten.
- **Inline-Felder**: Vom Admin als „inline“ markierte Gastfelder (z. B. Adresse, Kontakt).
- **Weitere Infos**: Accordion mit den restlichen Gastfeldern.
- **Notizen**: Anzeige + Button „Notizen bearbeiten“ (speichert direkt).
- **Vertreter**: Accordion mit Vertreterfeldern, wenn vorhanden.
- **Tiere**: Karten mit Tierinfos, Foodtags, Buttons für bearbeiten/löschen.
- **Futterausgaben**: Historie mit Datum, Notizen, Tags; Buttons für Ausgabe starten/bearbeiten/löschen.
- **Zahlungen** (wenn aktiv): Liste inkl. offen/bestätigt; Gegenbuchung/Bestätigen je nach Status.
- **Dokumente**: Anhänge zum Gast.
- **Änderungshistorie**: ChangeLog-Einträge.

## Aktionen
- **Bearbeiten**: Öffnet Formular mit editierbaren Feldern (rechteabhängig).
- **Tier hinzufügen**: Leitet zum Tier-Formular.
- **Futter ausgeben**: Startet Ausgabe-Dialog.
- **Zahlung/Vormerkung**: Buttons im Zahlungsbereich.
- **Gästekarte drucken**: PDF-Download via `/guest/<id>/print_card`.

## Hinweise
- Sicht-/Editierbarkeit richtet sich nach den Feldeinstellungen (Visibility/Editability).
- Erinnerungen entstehen aus Datumsfeldern mit Intervall in den Einstellungen.
- Offene Nachrichten werden im Glockenmenü angezeigt; „erledigt“ setzt Abschlussdatum und entfernt diese aus dieser Ansicht.
