# 🤖 RoboTown Abenteuer - Session 5
## Farbcodes und Geheimbotschaften

### 📜 Die Geschichte geht weiter...
Wahnsinn! Du hast eine geheime Botschaft gefunden: "Folge den farbigen Markierungen, sie führen zum Schatz!" In RoboTown gibt es bunte Linien und Farbpunkte - dein Explorer Bot muss lernen, diese zu erkennen und ihnen zu folgen!

### 🎯 Was wir heute lernen:
- Wie dein Roboter Farben erkennt
- Wie er einer Linie folgen kann
- Wie er auf verschiedene Farben reagiert

### 🛠️ Was du brauchst:
- Deinen Explorer Bot
- Einen Farbsensor
- Farbiges Klebeband (schwarz, rot, grün, blau)
- Weißes Papier als Unterlage

### 🎨 Die Farben und ihre Bedeutung
**Geheimer Farb-Code von RoboTown:**
- 🔴 ROT = Stopp & Nachdenken
- 🟢 GRÜN = Volle Fahrt voraus!
- 🔵 BLAU = Drehe rechts
- ⚫ SCHWARZ = Folge mir!
- ⚪ WEISS = Freie Fahrt

### 🎮 Los geht's!

#### 1️⃣ Farben erkennen
**Baue dieses erste Testprogramm:**
1. "Wiederhole endlos" Block
2. "Wenn-Dann-Sonst" Block mit mehreren Optionen:
   - Wenn Farbe = ROT:
     - LED rot
     - Ton abspielen
     - Stoppen
   - Wenn Farbe = GRÜN:
     - LED grün
     - Fröhlicher Ton
     - Vorwärts fahren
   - Wenn Farbe = BLAU:
     - LED blau
     - Drehe nach rechts

**🎈 Probier es aus:**
- Halte verschiedene farbige Karten unter den Sensor
- Beobachte die LED-Farben
- Höre auf die verschiedenen Töne

#### 2️⃣ Der Linienfolger
**So folgt dein Roboter einer schwarzen Linie:**
1. "Wiederhole endlos" Block
2. Darin:
   - "Wenn-Dann-Sonst" Block
   - Bedingung: "Farbe = SCHWARZ"
   - Dann:
     - Rechter Motor etwas schneller
   - Sonst:
     - Linker Motor etwas schneller

#### 3️⃣ Botschaften senden
In RoboTown können Roboter sich Nachrichten schicken! Das geht so:
1. "Wenn Farbe erkannt" Block
2. "Sende Nachricht" Block
3. Andere Programmteile können auf diese Nachricht warten
4. "Wenn Nachricht empfangen" Block startet neue Aktionen

### 🎯 Spannende Aufgaben:

#### 😊 Einfach:
1. **Der Farb-DJ:**
   - Spiele für jede Farbe einen anderen Ton
   - Zeige die Farbe auf dem LED-Display
   - Warte 2 Sekunden
   - Bereit für die nächste Farbe

2. **Der Ampel-Roboter:**
   - Bei Rot: Stoppen
   - Bei Gelb: Langsam fahren
   - Bei Grün: Normal fahren

#### 🤔 Mittel:
1. **Der Farb-Sammler:**
   - Zähle, wie oft du jede Farbe siehst
   - Sende eine Nachricht bei jeder neuen Farbe
   - Spiele nach 5 Farben eine Melodie

2. **Der Tanz-Roboter:**
   - Verschiedene Tänze für verschiedene Farben
   - Sende "Tanz-Start" Nachricht
   - Andere Roboter können mittanzen!

#### 🌟 Schwer:
1. **Der Code-Knacker:**
   - Merke dir eine Farb-Reihenfolge
   - Wenn die richtige Kombination kommt:
     - Spiele "Schatz gefunden" Melodie
     - Sende "Erfolg" Nachricht

2. **Der Superlinienfolger:**
   - Folge der schwarzen Linie
   - Reagiere auf Farbpunkte am Weg
   - Sende Nachrichten bei besonderen Farben
   - Kehre zum Linienfolgen zurück

### 🎨 Block-Farben-Guide:
- Farb-Sensor-Blöcke sind BLAU
- Nachrichten-Blöcke sind LILA
- Bewegungs-Blöcke sind GRÜN
- Wenn-Dann-Blöcke sind GELB
- Schleifen-Blöcke sind ORANGE

### 💡 Tipps und Tricks:
- Halte den Farbsensor nah an der Linie
- Nicht zu schnell fahren
- Gute Beleuchtung ist wichtig
- Teste die Farben vorher

### 🌈 Kreativ-Challenge:
Erfinde dein eigenes Farb-Spiel:
- Lege einen Farb-Parcours
- Verstecke "Schatz-Farben"
- Erfinde Geheim-Codes
- Lass zwei Roboter zusammenarbeiten

### 🎪 Farb-Zirkus-Show:
- Baue eine Show mit verschiedenen Stationen
- An jeder Station reagiert der Roboter anders
- Verbinde alles mit Nachrichten
- Führe die Show deiner Familie vor!

### 🎉 Gut gemacht!
Dein Roboter kann jetzt Farben erkennen und sogar Nachrichten senden! In der nächsten Session kommt die große Schatzsuche!

### 🤔 Fragen zum Nachdenken:
- Wo findest du im Alltag Farbcodes?
- Wie erkennen Menschen Farben?
- Wozu könnten Roboter Farberkennung noch nutzen?

### 📝 Roboter-Tagebuch:
Male deinen Farb-Parcours:
- Welche Farben hast du benutzt?
- Was hat dein Roboter gemacht?
- Welche neuen Ideen hast du?

---
**💫 Bonus-Wissen:** Wusstest du, dass einige Tiere ganz anders Farben sehen als wir? Bienen können ultraviolettes Licht sehen, und Hunde sehen weniger Farben als Menschen. Dein Roboter sieht Farben wieder anders - er misst, wie das Licht von den Farben reflektiert wird! 🐝 🐕

Viel Spaß beim Experimentieren mit Farben! 🌈
