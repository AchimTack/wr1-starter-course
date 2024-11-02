# 🤖 RoboTown Abenteuer - Session 4
## Hindernisse erkennen mit dem Ultraschall-Sensor

### 📜 Die Geschichte geht weiter...
Die Straßen von RoboTown sind heute besonders belebt! Um den nächsten Hinweis zum Schatz zu finden, muss dein Explorer Bot sicher durch den Verkehr navigieren. Zum Glück haben wir den Ultraschall-Sensor - das sind die "Augen" deines Roboters!

### 🎯 Was wir heute lernen:
- Wie der Ultraschall-Sensor funktioniert
- Wie dein Roboter Hindernisse erkennt
- Wie er selbstständig ausweichen kann

### 🛠️ Was du brauchst:
- Deinen Explorer Bot
- Einen Ultraschall-Sensor
- Kabel für den Sensor
- Verschiedene Hindernisse (Bücher, Schachteln, Bauklötze)

### 🔍 Der Ultraschall-Sensor - Dein Roboter-Auge
**Was macht der Sensor?**
- Er sendet unsichtbare "Schallwellen" aus
- Diese prallen von Hindernissen ab
- Der Sensor misst, wie lange die Wellen brauchen
- Daraus berechnet er den Abstand

**Wie ein Fledermaus-Radar!** 🦇

### 🎮 Los geht's!

#### 1️⃣ Den Sensor testen
**Baue dieses einfache Programm:**
1. "Wenn-Dann" Block
2. Als Bedingung:
   - "Wenn Ultraschall-Abstand < 20"
3. Im "Dann"-Teil:
   - LED rot setzen
   - Ton abspielen
   - 1 Sekunde warten
   - LED ausschalten

**🎈 Experimentiere:**
- Bewege deine Hand vor dem Sensor
- Teste verschiedene Abstände
- Probiere unterschiedliche Materialien aus

#### 2️⃣ Der vorsichtige Fahrer
**So baut man einen Roboter, der nicht gegen Wände fährt:**
1. "Wiederhole endlos" Block
2. Darin:
   1. "Wenn-Dann-Sonst" Block
   2. Bedingung: "Ultraschall-Abstand < 15"
   3. Dann:
      - Motoren stoppen
      - LED rot
      - Rückwärts fahren (1 Sekunde)
      - 90-Grad-Drehung
   4. Sonst:
      - LED grün
      - Vorwärts fahren

#### 3️⃣ Der schlaue Ausweicher
**Jetzt wird's spannend - der Roboter sucht seinen Weg!**
1. "Wiederhole endlos" Block
2. Darin:
   1. Vorwärts fahren
   2. "Wenn-Dann" Block
   3. Bedingung: "Ultraschall-Abstand < 20"
   4. Dann:
      - Stoppen
      - LED orange
      - Ton abspielen
      - "Wiederhole bis" Block:
         - Bedingung: "Ultraschall-Abstand > 30"
         - Langsam drehen
      - LED grün

### 🎯 Spannende Aufgaben:

#### 😊 Einfach:
1. **Der Warner:**
   - Fahre vorwärts
   - Wenn Hindernis näher als 20 cm:
     - Piepen und blinken
     - Stoppen

2. **Der Schüchterne:**
   - Wenn sich etwas nähert:
     - Rückwärts fahren
     - LED blau blinken

#### 🤔 Mittel:
1. **Der Parkwächter:**
   - Fahre im Kreis
   - Wenn Hindernis erkannt:
     - Stoppe
     - Spiele Melodie
     - Warte bis Hindernis weg ist

2. **Der Erforscher:**
   - Fahre geradeaus
   - Bei Hindernis:
     - Drehe rechts
     - Wenn auch hier Hindernis:
       - Drehe links
     - Weiter geradeaus

#### 🌟 Schwer:
1. **Der Labyrinth-Meister:**
   - Finde den Weg durch einen Hindernis-Parcours
   - Merke dir die Anzahl der Drehungen
   - Spiele am Ende eine "Gewinner-Melodie"

2. **Der Tänzer:**
   - Tanze, wenn die Bahn frei ist
   - Weiche aus, wenn sich etwas nähert
   - Kehre zur Tanzposition zurück

### 🎨 Block-Farben-Guide:
- Sensor-Blöcke sind DUNKELBLAU
- Bewegungs-Blöcke sind GRÜN
- Wenn-Dann-Blöcke sind GELB
- Schleifen-Blöcke sind ORANGE
- Sound & LED Blöcke sind LILA

### 💡 Tipps und Tricks:
- Teste verschiedene Abstände
- Bewege Hindernisse langsam
- Mach die Drehungen nicht zu schnell
- Halte den Sensor sauber

### 🌈 Kreativ-Challenge:
Baue einen Hindernis-Parcours:
- Verwende verschiedene Gegenstände
- Mach den Weg eng und kurvig
- Miss die Zeit, die dein Roboter braucht
- Versuche den Parcours zu optimieren

### 🎉 Gut gemacht!
Dein Roboter kann jetzt "sehen" und Hindernissen ausweichen! In der nächsten Session lernen wir, wie er Farben erkennen kann.

### 🤔 Fragen zum Nachdenken:
- Wo werden Ultraschall-Sensoren noch eingesetzt?
- Warum ist es wichtig, dass Roboter Hindernisse erkennen?
- Wie könnten Roboter noch "sehen" lernen?

### 📝 Roboter-Tagebuch:
Zeichne deinen Parcours auf und notiere:
- Welche Hindernisse waren schwierig?
- Was hat dein Roboter gut gemacht?
- Welche neuen Ideen hast du?

---
**💫 Bonus-Wissen:** Auch Delphine und Fledermäuse benutzen Ultraschall! Sie senden Klicks aus und hören das Echo, um ihre Beute zu finden oder im Dunkeln zu navigieren. Dein Roboter macht es genauso! 🐬 🦇

Viel Spaß beim Experimentieren! 🚀
