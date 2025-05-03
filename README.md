# Stündliche Wettervorhersage

Diese GitHub Page zeigt eine stündliche Wettervorhersage für zwei auswählbare Städte:

**Erfurt, Deutschland** und **Szeged, Ungarn**.

Die Daten werden stündlich automatisch aktualisiert und stammen von der [Open-Meteo API](https://open-meteo.com/).

## Funktionen

- Anzeige der Wetterdaten für die nächsten 24 Stunden
- Auswahl zwischen zwei Städten über ein Dropdown-Menü
- Darstellung folgender Informationen für jede Stunde:
  - Uhrzeit
  - Temperatur (°C)
  - Windgeschwindigkeit (km/h)
  - Wetterzustand (in Klartext)
  - Regenwahrscheinlichkeit (%)
- Automatische Aktualisierung der Daten einmal pro Stunde

## Verwendete Technologien

- HTML, CSS, JavaScript (kein Framework)
- [Open-Meteo Forecast API](https://open-meteo.com/)
- Gehostet über GitHub Pages

## Nutzung

1. Die Seite zeigt standardmäßig die Vorhersage für Erfurt.
2. Wähle im Dropdown-Menü eine andere Stadt (z.B. Szeged), um die entsprechende Vorhersage zu laden.
3. Die Daten aktualisieren sich stündlich automatisch im Hintergrund.

## Hinweise

- Die Zeitzone wird automatisch anhand der gewählten Stadt berechnet.
- Es werden keine Cookies oder Tracker verwendet.
- Die Seite ist bewusst minimal gehalten, um maximale Ladegeschwindigkeit zu gewährleisten.
