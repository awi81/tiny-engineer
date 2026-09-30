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
| UpperArm (2×), ForearmLeft/Right, Coffee, Chair, SeatLeft, SeatRight, Tisch hinten (unter dem Stuhl), Schrift auf der Tasse | Schwarz | PLA Schwarz | 89 g |
| Desk (vorderer Teil), DeskPad (Unterplatte mit Ecken), LampBase | Anthrazit | PLA Anthrazit V2 | 77 g |
| LaptopCase, LaptopScreen, Bell, LampCap | Alu-Silber | PETG Alu-Silber | 16 g |
| DeskTop (Tischplatte), LampDiffuser (Lampenschirm) | Glas | PETG Natur (glasklar) | 31 g |
| Henkel und Herz der Tasse, LampButton | Feuerrot | PLA Feuerrot | < 1 g |

Filamente (1,75 mm, Preise vom 30.09.2026):

| Filament | Link | Menge für 3 Roboter | Kauf |
| --- | --- | --- | --- |
| PLA Weiß | [1 kg](https://dasfilament.de/produkt/pla-filament-175-mm-weiss-1-kg/) | 180 g | 1 kg, 15,99 € |
| PLA Anthrazit V2 | [1 kg](https://dasfilament.de/produkt/pla-filament-175-mm-anthrazit-v2-1-kg/) | 231 g | 1 kg, 16,99 € |
| PLA Schwarz | [1 kg](https://dasfilament.de/produkt/pla-filament-175-mm-schwarz-1-kg/) | 267 g | 1 kg, 15,99 € |
| PLA Feuerrot | [Probe](https://dasfilament.de/produkt/pla-filament-175-mm-feuerrot-50-g-sample/) | 3 g | 50-g-Probe, 2,95 € |
| PETG Alu-Silber | [Probe](https://dasfilament.de/produkt/petg-filament-50-g-sample-175-mm-alu-silber/) | 49 g | 2 Proben, 5,90 € |
| PETG Natur | [1 kg](https://dasfilament.de/produkt/petg-filament-175-mm-natur-1-kg/) | 93 g | 1 kg, 21,00 € (2 Proben wären zu knapp) |
| Farbmuster-Set (68 Plättchen: 34 PLA, 30 PETG, 3 TPU) | [Set](https://dasfilament.de/produkt/farbplaettchen-farbmuster-set-swatches/) | – | 19,94 € |

Das Farbmuster-Set zeigt jede Farbe in Stufen von 0,2 bis 2 mm Dicke. Damit lässt sich vor dem Kauf prüfen, wie durchsichtig PETG Natur bei der Plattenstärke wirkt.

## Offene Punkte

- **Glasplatte:** PETG Natur ist glasklar (PLA Natur wirkt gelblich). Darunter liegen die anthrazitfarbene Unterplatte und der oben geschlossene Tischkorpus; Elektronik sieht man nicht, ein Sichtschutz ist nicht nötig.
- **Klingel:** Den Knopf oben bildet der Kopf der M2×16-Schraube, mit der die Klingel am Tisch befestigt wird.
- **Lampenschirm:** aus derselben Rolle PETG Natur. Im Original weiß oder durchscheinend.
- **Tisch:** Der Tischkorpus ist farblich geteilt: hinten unter dem Stuhl schwarz, vorn anthrazit. Druckdatei [../tisch/Tisch_Farbtrennung_Teile.3mf](../tisch/Tisch_Farbtrennung_Teile.3mf) (ein Objekt, drei Teile), gedruckt in einem Durchgang mit AMS.
- **Tasse „I ♥ IT“:** fertig im Modell, Dateien in [../tasse/](../tasse/). Schrift und Herz sind 0,4 mm erhaben, gegenüber dem Henkel. Beim Einsetzen zeigt der Henkel nach hinten. `Tasse_ILoveIT_Teile.3mf` öffnet Bambu Studio als ein Objekt mit sechs Teilen (Tasse, Henkel, Herz, drei Buchstaben); jedem Teil die Farbe zuweisen. Gedruckt wird sie mit AMS in einem Durchgang.
