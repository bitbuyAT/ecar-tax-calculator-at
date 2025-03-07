# Motorbezogene Versicherungssteuer für Elektrofahrzeuge

Dieses Projekt stellt eine einfache Webanwendung zur Berechnung der motorbezogenen Versicherungssteuer für Elektrofahrzeuge dar. Die Anwendung verwendet HTML, JavaScript und [Tailwind CSS](https://tailwindcss.com/) für das Styling.

## Funktionen

- **Eingabefelder:** Der Benutzer kann die im Zulassungsschein ausgewiesene Dauerleistung (in kW) und das Fahrzeugleergewicht (in kg) eingeben.
- **Steuerberechnung:** 
  - **Leistungsteil:** Es wird die Dauerleistung abzüglich 45 kW (mindestens 10 kW verbleibend) herangezogen. Für die ersten 35 kW gilt ein Satz von 0,25 €/kW, für die nächsten 25 kW 0,35 €/kW und für jeden weiteren kW 0,45 €/kW.
  - **Gewichtsteil:** Vom Fahrzeugleergewicht werden 900 kg abgezogen (mindestens 200 kg verbleibend). Für die ersten 500 kg gilt ein Satz von 0,015 €/kg, für die nächsten 700 kg 0,030 €/kg und für jeden weiteren kg 0,045 €/kg.
- **Aufschlüsselung:** Nach der Berechnung kann über einen "Mehr Infos" Button eine detaillierte Aufschlüsselung der Steuerberechnung inklusive der verwendeten Formeln angezeigt werden.

## Gesetzlicher Hintergrund

Die Berechnungsgrundlagen basieren auf dem aktuellen Gesetzesentwurf zur Besteuerung von Elektrofahrzeugen. Bitte beachten Sie, dass sich der Gesetzestext noch ändern kann. Für den aktuellen Stand des Gesetzesentwurfs besuchen Sie bitte folgenden Link:

[Gesetzesentwurf – Parlament.gv.at](https://www.parlament.gv.at/dokument/XXVIII/I/34/fnameorig_1671562.html)

## Nutzung

1. Klonen oder laden Sie dieses Repository.
2. Öffnen Sie die `index.html`-Datei in Ihrem Browser.
3. Geben Sie die Dauerleistung und das Fahrzeugleergewicht ein.
4. Klicken Sie auf **Berechnen**, um die Steuer zu ermitteln.
5. Nutzen Sie den **Mehr Infos** Button, um die Berechnungsdetails einzusehen.

## Lizenz

Dieses Projekt wird unter der [Unlicense](LICENSE) veröffentlicht.  
Das bedeutet, dass jeder das Projekt für beliebige Zwecke frei nutzen, kopieren, modifizieren und verbreiten darf – selbstverständlich ohne jegliche Gewähr, da das Projekt "as-is" ohne Haftungsausschluss bereitgestellt wird.
