# Weihnachts-Wichteln

Kleine Wichtel-Auslosung für die Weihnachtsfeier, eine einzelne HTML-Datei ohne Abhängigkeiten.

- Organisator öffnet die Seite, trägt die Namen ein und erstellt die Auslosung.
- Alle bekommen denselben Link plus einen persönlichen Code.
- Wer Name und Code eingibt, sieht, wen er beschenkt. Niemand zieht sich selbst, jeder wird genau einmal gezogen.

Die Zuordnung ist im Link verschlüsselt (AES-GCM, Schlüssel aus Name und Code). Es gibt keinen Server.
Läuft nur über https:// (z. B. GitHub Pages).
