# Kata: Conditional Actions

Diese Aufgabe zielt darauf ab, bedingte Anweisungen in Python zu üben.

## Aufgabe

Erstelle eine Datei `conditional_actions.py` im Root-Verzeichnis deines Repositories.

Schreibe eine Funktion `check_number`, die eine Ganzzahl `n` akzeptiert. Die Funktion soll folgende bedingte Aktionen ausführen:

- Wenn `n` ungerade ist, gib "Weird" zurück.
- Wenn `n` gerade ist und im inklusiven Bereich von 2 bis 5 liegt, gib "Not Weird" zurück.
- Wenn `n` gerade ist und im inklusiven Bereich von 6 bis 20 liegt, gib "Weird" zurück.
- Wenn `n` gerade ist und größer als 20, gib "Not Weird" zurück.

### Beispiele

- `check_number(3)` sollte "Weird" zurückgeben.
- `check_number(4)` sollte "Not Weird" zurückgeben.
- `check_number(18)` sollte "Weird" zurückgeben.
- `check_number(22)` sollte "Not Weird" zurückgeben.

Punkte: 20
