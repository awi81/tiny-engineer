# Farben für meinen Tiny Engineer

Vorschauen sind aus einem Foto des Originals umgefärbt, keine echten Drucke. Die Mengen stammen aus Bambu Studio (P2S, 0,16 mm, 20 % Füllung) und gelten pro Roboter.

| Bild | Inhalt |
| --- | --- |
| [farbideen.jpg](farbideen.jpg) | Neun Farbkombinationen zur Auswahl |
| [variante1-bambu.jpg](variante1-bambu.jpg) | Variante 1: Weiß, Schwarz, Silbergrau, Anthrazit, blaugraues „Glas“ |
| [variante2-fusion.png](variante2-fusion.png) | Variante 2 im CAD-Modell (Fusion) |
| [variante2-tasse.png](variante2-tasse.png) | Tasse „I ♥ IT“ im CAD-Modell |
| [variante2-dasfilament.jpg](variante2-dasfilament.jpg) | Variante 2: Farben von dasfilament.de, Tasse „I ♥ IT“ |

## Variante 2 (dasfilament.de)

| Teile | Farbe | Filament | pro Roboter |
| --- | --- | --- | --- |
| Head, Chest, Hat, Belly, Neck, Mug, AiEmblem | Weiß | PLA Weiß | 60 g |
| UpperArm (2×), ForearmLeft/Right, Coffee, Chair, SeatLeft, SeatRight, Schrift auf der Tasse | Schwarz | PLA Schwarz | 76 g |
| Desk, DeskPad (Unterplatte mit Ecken), LampBase | Anthrazit | PLA Anthrazit V2 | 90 g |
| LaptopCase, LaptopScreen, Bell, LampCap | Alu-Silber | PETG Alu-Silber | 16 g |
| DeskTop (Tischplatte) | Glas | PETG Transparent Blau | 30 g |
| Henkel und Herz der Tasse, LampButton | Feuerrot | PLA Feuerrot | < 1 g |

Filamente (1,75 mm, Preise vom 30.09.2026):

| Filament | Link | Menge für 3 Roboter | Kauf |
| --- | --- | --- | --- |
| PLA Weiß | [1 kg](https://dasfilament.de/produkt/pla-filament-175-mm-weiss-1-kg/) | 180 g | 1 kg, 15,99 € |
| PLA Anthrazit V2 | [1 kg](https://dasfilament.de/produkt/pla-filament-175-mm-anthrazit-v2-1-kg/) | 271 g | 1 kg, 16,99 € |
| PLA Schwarz | [1 kg](https://dasfilament.de/produkt/pla-filament-175-mm-schwarz-1-kg/) | 229 g | 1 kg, 15,99 € |
| PLA Feuerrot | [Probe](https://dasfilament.de/produkt/pla-filament-175-mm-feuerrot-50-g-sample/) | 3 g | 50-g-Probe, 2,95 € |
| PETG Alu-Silber | [Probe](https://dasfilament.de/produkt/petg-filament-50-g-sample-175-mm-alu-silber/) | 49 g | 2 Proben, 5,90 € |
| PETG Transparent Blau | [1 kg](https://dasfilament.de/produkt/petg-filament-175-mm-transparent-blau-1-kg/) | 91 g | 1 kg, 21,00 € (2 Proben wären zu knapp) |
| PETG Natur (optional, hellerer Glaston) | [Probe](https://dasfilament.de/produkt/petg-filament-50-g-sample-175-mm-natur/) | ~15 g | 50-g-Probe, 2,95 € |
| Farbmuster-Set (68 Plättchen: 34 PLA, 30 PETG, 3 TPU) | [Set](https://dasfilament.de/produkt/farbplaettchen-farbmuster-set-swatches/) | – | 19,94 € |

Das Farbmuster-Set zeigt jede Farbe in Stufen von 0,2 bis 2 mm Dicke. Damit lässt sich vor dem Kauf prüfen, wie durchsichtig Transparent Blau und Natur bei der Plattenstärke wirken.

## Offene Punkte

- **Glasplatte:** Unter der Tischplatte liegen die anthrazitfarbene Unterplatte und der oben geschlossene Tischkorpus; Elektronik sieht man nicht. Die Platte wirkt deshalb dunkelblau. Für ein helles Eisblau die untersten 2–3 Schichten in PETG Natur drucken (Farbwechsel per Pause). PLA haftet schlecht auf PETG.
- **Klingel:** Den Knopf oben bildet der Kopf der M2×16-Schraube, mit der die Klingel am Tisch befestigt wird.
- **Lampenschirm:** In Transparent Blau leuchtet die Lampe blau. Für weißes Licht PETG Natur nehmen.
- **Tasse „I ♥ IT“:** fertig im Modell, Dateien in [../tasse/](../tasse/). Schrift und Herz sind 0,4 mm erhaben, gegenüber dem Henkel. Beim Einsetzen zeigt der Henkel nach hinten. `Tasse_ILoveIT_Teile.3mf` öffnet Bambu Studio als ein Objekt mit sechs Teilen (Tasse, Henkel, Herz, drei Buchstaben); jedem Teil die Farbe zuweisen. Mehrfarbig in einem Druck geht nur mit Farbwechsler (AMS); ohne AMS die weiße Tasse drucken und Schrift, Herz und Henkel bemalen.
