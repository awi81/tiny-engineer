# Session-Handover 2026-10-02

Stichworte: Upstream-Issues und PR-Reviews (#31 behoben, #46 geprüft), Fusion-MCP eingerichtet, Farbvariante 2
mit eigenen Teilen (Tasse „I ♥ IT“, Konsolen-Bildschirm, Glas-Tischplatte), Einkaufsliste, Bambu-Studio-Druckprojekte
für Roboter 1 (Original) und Roboter 2 (Variante 2). Diese Datei dient als Übergabe an die nächste Session.

---

## Ausgangslage

- Repo `D:\workspace\tiny-engineer`, Klon von `jamro/tiny-engineer`; Remote `fork` = `awi81/tiny-engineer`.
- Branches:
  - `fix/keyboard-cut-profile` (`a7d5b9b`): Fix für Issue #31, offen als PR jamro/tiny-engineer#52.
  - `awi/farbvarianten` (auf dem Fork): eigener Bau, Ordner `mein-build/`. Wird nicht upstream vorgeschlagen.
  - `main`: 8 Commits hinter `origin/main`.
- Der Nutzer baut drei Roboter nacheinander (Modul-Variante, SG90). Drucker Bambu Lab P2S Combo (mit AMS) ist noch
  nicht gekauft, Bestellung von Elektronik und Filament steht bevor.

---

## Erledigt in dieser Session

| Commit | Bereich | Was |
|---|---|---|
| `a7d5b9b` | `3d_models/fusion/TinyEngineerTools/servo.py` | Laptop-Tasten bleiben beim Wechsel auf größeren Servo erhalten (Issue #31); PR #52 |
| – | jamro/tiny-engineer#46 | PCB-Review als Kommentar gepostet; jamro hat sich bedankt, prüft ~OE/GP5 zuerst |
| `3cb8f99` … `ae3c0c8` | `mein-build/farben`, `tasse`, `tischplatte`, `bildschirm` | Variante 2: Farben, eigene Teile, Vorschaubilder, Bestellliste |
| `6ca8049` | `mein-build/druckprojekte` | 15 Platten für drei V2-Roboter (abgelöst) |
| `f91f13e` | `mein-build/druckprojekte`, `farben/README.md` | 11 Platten für Roboter 1 (Original, PETG Burnt Copper) + Roboter 2 (V2), Bestellung 106,78 € |
| `4afadb8` | `mein-build/druckprojekte` | Original-Roboter bekommt auch den Konsolen-Bildschirm |

Außerhalb des Repos:

- Einkaufsliste (Word): `D:\workspace_temp\tiny-engineer\einkaufsliste\Tiny-Engineer-Einkaufsliste.docx`
  (Generator `build.js`); Elektronik für drei, Filament für zwei Roboter, gesamt ~267 €.
- Generator der Druckprojekte: `D:\workspace_temp\tiny-engineer\projekte\build_projects.py`
  (`TE_SET=2bots`, Ausgabe `out_2bots`), Übersicht `make_readme.py`.
- Fusion-Modell Variante 2: `D:\workspace_temp\tiny-engineer\fusion\TinyEngineer_variante2.f3d`.

---

## Offene Punkte für die nächste Session

### 1. Nach Lieferung des Druckers: Testteile

- Platte `01_Testteile` drucken. ServoSizingTester muss einen SG90 ohne Gewalt aufnehmen.
- ScrewSizingTest: Weicht der passende Lochdurchmesser von 2,1 mm ab, den Fusion-Parameter
  `screw_thread_diameter` ändern, Teile neu exportieren und `build_projects.py` mit `TE_SET=2bots` neu laufen lassen.

### 2. Proben ohne Spule

- 50-g-Proben von dasfilament sind lose Ringe. Für AMS auf eine leere 1-kg-Spule wickeln (Feuerrot für die Tasse,
  Transparent Blau für die Glasplatte).

### 3. Roboter 3

- Farbe offen. Wenn sie feststeht: neuen Plattensatz in `build_projects.py` anlegen (wie `PLATES_2BOTS`).

### 4. Upstream (nur auf Nachfrage)

- PR #52: nur zwei Bot-Hinweise (CodeRabbit, Randfall „Execute error“). Entscheidung: abwarten, bis jamro reagiert.
- PR #46: nichts zu tun.

### 5. Zurückgestellt

- Idee: Steuerung per USB statt WLAN (Memory `idea-usb-serial-control`).

---

## Wichtige Konventionen aus dieser Session (Memory-relevant)

- Upstream nur nach gezeigtem Entwurf und ausdrücklicher Freigabe posten; Pushes nur auf `fork`. Steht in Memory
  `no-upstream-posting`.
- Stand des Baus, Dateiorte und Stolperfallen der Bambu-Studio-CLI stehen in Memory `build-plan-3-robots`.

---

## Aktionen in der neuen Session — Empfehlung

1. Nach Lieferung: `D:\workspace\tiny-engineer\mein-build\druckprojekte\README.md` (Branch `awi/farbvarianten`)
   öffnen und mit Platte 01 starten; Ergebnis des Schrauben-Tests auswerten.
2. Bei Bedarf Schraubenmaß in Fusion ändern und Druckprojekte neu erzeugen.
3. Verdrahten (`docs/hardware/wiring.md`), flashen (`docs/flash.md`), montieren (`docs/3d/assembly.md`).
