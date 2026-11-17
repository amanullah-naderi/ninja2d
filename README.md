# Super Ninja 2D – "Die Flucht aus der Höhle des Lichts"

Ein 2D-Jump-and-Run-Spiel, entwickelt im Rahmen des Moduls **Interaktive Technologien / Interaktionsgestaltung** (Wintersemester 24/25) an der **Fachhochschule Erfurt**.

---

## Spielidee & Story

Der Spieler schlüpft in die Rolle eines Ninjas und muss sich aus einer wunderschönen, aber trügerischen und illusorischen Höhle befreien. Um den Ausgang zu erreichen, müssen verschiedene Wächter, Monster und schließlich der mächtige Endboss (der Höhlendrache) besiegt werden. 

* **Besonderheit:** Das Level-Design nutzt eine friedliche, fast magische Atmosphäre mit Licht- und Nebeleffekten, die sich bei Kämpfen in eine düstere Kulisse verwandelt. Man kann im nächsten Level nur aufsteigen, wenn alle Feinde des aktuellen Bereichs besiegt wurden!

---

## Features & Spielmechaniken

* **Steuerung:**
  * **Bewegung:** Mit den Pfeiltasten (Links / Rechts) bewegen.
  * **Sprung:** Mit der Leertaste springen (ein **Dreifachsprung** ist im Spiel integriert).
  * **Kampf:** Per Mausklick führt der Spieler einen Nahkampfangriff mit dem Schwert aus, um Gegner und Illusionen zu durchbrechen.
* **Level- & Gegnerstruktur (1–4 Levels):**
  * **Level 1:** Einstieg in die Höhle mit ersten Gegnern („Jins“).
  * **Level 2:** Begegnung mit schwereren Gegnern („Damon“).
  * **Level 3:** Konfrontation mit dem „Drachen.
  * **Level 4:** Der große Endboss-Kampf gegen den „Höhlendrachen.
* **UI & HUD:**
  * Voll funktionsfähiges Hauptmenü (*Play*, *Settings*, *Quit*, *Sound*, *Restart*).
  * Live-Anzeige für gesammelte Münzen und besiegte Gegner.
  * Lineares Health-System (Leben füllt sich unter bestimmten Bedingungen im Kampf wieder auf).
* **Audio & Ästhetik:**
  * Dynamisches Sounddesign (Hintergrundmusik, Kampfgeräusche, Soundeffekte für Münzen und Spieler-Aktionen).

---

## Technische Umsetzung (Unity)

* **Engine:** Unity (mit Nutzung der **Universal Render Pipeline - URP** für optimierte Licht- und Grafikeffekte).
* **Skripting:** Vollständig in **C#** implementiert.
* **Grafik & Animationen:** 2D-Pixel-Art-Assets, Sprite-Animationen und Partikeleffekte für Treffer-Feedback.

---

## Starten des Projekts

1. Repository klonen:
   ```bash
   git clone [https://github.com/amanullah-naderi/super-ninja-2d.git](https://github.com/amanullah-naderi/super-ninja-2d.git)
