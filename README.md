# 💥 Buckshot Roulette Probability Calculator 🧨

*Read this in [German / Deutsch](#-deutsche-version)*

A smart, mobile-friendly probability calculator and tactical assistant for the game **Buckshot Roulette**. Stop guessing and start winning with math, chain-reaction logic, and real-time RNG tracking.

### 🌐 Live Demo
* **English Version:** [Click here to play](https://sambaweb.github.io/buckshot-roulette-calculator/)
* **German Version:** [Klick hier zum Spielen](https://sambaweb.github.io/buckshot-roulette-calculator/index_de.html)

### ✨ Features
* **Dynamic Probabilities:** Real-time percentage calculation for the next shot (Live / Blänk).
* **Expected Value (EV) Engine:** Analyzes entire remaining boards to mathematically determine the most profitable targets.
* **Smart Item Recommendations & Stealing:** Context-aware item priorities, including an Adrenaline stealing hierarchy that tells you exactly what to take from the dealer.
* **Inventory Tracking & Death Combos:** Track player and dealer items interactively. The app warns you instantly if the dealer holds a lethal combo.
* **Law of Large Numbers (LLN) Tracker:** Tracks global RNG trends across all your rounds to see if the game favors live or blank shells.
* **Mobile-First Design:** Fully optimized for smartphones. No zooming, no accidental scrolling—it feels like a native app.
* **Inverter Support:** Accurately recalculates the remaining shell pool when you invert a known shell.

### 🔄 Changelog
* **v8.1.0:** Massive visual and tactical overhaul. Dealer health now perfectly mirrors the player (depleting center-out). Introduced Adrenaline steal hierarchies and a blaring red "Death Combo Warning" when the Dealer holds a lethal chain of items. Automated setup constraints now prevent invalid starting magazines. 
* **v7.7.1:** Fixed an Expected Value (EV) calculation bug where the algorithm did not accurately deduct the negative follow-up state (Dealer's turn) when firing a live shell. Targets are now rated completely flawlessly.

### 🚀 How to Use
1. Enter the starting shells (Live/Blänk) and health points.
2. Track your items and the dealer's items via the dropdowns.
3. If you use a Glass/Phone, click the corresponding shell circle to set it to **Red (Live)** or **Green (Blänk)**.
4. Follow the smart advice to shoot the dealer or yourself (based on highest EV)!
5. Click the action buttons to log the result or use items.

### 🛠️ Credits / Behind the Scenes
Concept, deep chain-reaction logic, and tactical game strategy designed by Sambaweb (me). Code generation, UI implementation, and pair-programming in collaboration with Google Gemini.

---

# 🇩🇪 Deutsche Version

Ein smarter, für Handys optimierter Probabilitätsrechner und Taktik-Assistent für das Spiel **Buckshot Roulette**. Schluss mit Raten – gewinne durch reine Mathematik, Ketteneffekt-Logik und Echtzeit-RNG-Tracking.

### 🌐 Live Demo
* **Englische Version:** [Hier klicken](https://sambaweb.github.io/buckshot-roulette-calculator/)
* **Deutsche Version:** [Hier klicken](https://sambaweb.github.io/buckshot-roulette-calculator/index_de.html)

### ✨ Features
* **Dynamische Wahrscheinlichkeiten:** Echtzeit-Prozentrechnung für den nächsten Schuss (Scharf / Plätzer).
* **Expected Value (EV) Engine:** Analysiert das gesamte verbleibende Board, um mathematisch die profitabelsten Ziele zu bestimmen.
* **Smarte Item-Tipps & Diebstahl-Prio:** Das Tool sagt dir genau, *wann* du welches Item am klügsten einsetzt. Die Adrenalin-Logik sagt dir exakt, was du dem Dealer stehlen musst (Priorität abhängig von deinen restlichen Blitzen).
* **Inventar-System & Todeskombo-Warnung:** Tracke deine Items und die des Dealers interaktiv. Das Tool schlägt Alarm, sobald der Dealer eine tödliche Item-Kombination in der Hand hält.
* **Gesetz der großen Zahl (LLN):** Trackt die globale RNG-Tendenz über all deine Runden hinweg.
* **Mobile-First Design:** Komplett für Smartphones optimiert. Kein lästiges Zoomen, kein Verrutschen – fühlt sich an wie eine native App.
* **Inverter-Logik:** Berechnet den restlichen Patronen-Pool absolut fehlerfrei neu, wenn du eine bekannte Patrone invertierst.

### 🔄 Changelog
* **v8.1.0:** Riesiges Taktik- und UI-Update. Die Blitze des Dealers schalten sich nun gespiegelt (von der Mitte nach außen) ab. Adrenalin-Steal-Prioritäten und eine rote, pulsierende Warnung bei tödlichen Dealer-Kombos hinzugefügt. Das Setup korrigiert unmögliche Eingaben jetzt automatisch in Echtzeit.
* **v7.7.1:** EV-Berechnungs-Bug behoben: Der Algorithmus beachtet jetzt präzise den negativen Folgezustand (Zusätzlicher Zug des Dealers), wenn eine scharfe Patrone abgefeuert wird. Die Zielempfehlungen sind nun mathematisch makellos.

### 🚀 Bedienung
1. Trage die Start-Patronen (Scharf/Plätzer) und die Lebenspunkte ein.
2. Pflege dein Inventar und das des Dealers über die Dropdowns.
3. Wenn du eine Lupe oder ein Handy nutzt, klicke auf den entsprechenden Kreis, um ihn auf **Rot (Scharf)** oder **Grün (Plätzer)** zu setzen.
4. Folge der smarten Taktik-Empfehlung (basierend auf dem höchsten EV)!
5. Nutze die Action-Buttons, um das Ergebnis einzutragen oder Items zu nutzen.

### 🛠️ Credits / Behind the Scenes
Konzept, tiefgreifende Ketteneffekt-Logik und Taktik-Design (sowie der legendäre "Blänk"-Gag) von Sambaweb. Code-Generierung, UI-Design und Pair-Programming in Zusammenarbeit mit Google Gemini.
