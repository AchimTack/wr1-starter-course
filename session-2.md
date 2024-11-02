# 🤖 RoboTown Abenteuer - Session 2
## Präzises Drehen & Navigation durch RoboTown

### 📜 Die Geschichte geht weiter...
Willkommen zurück, junger Roboter-Ingenieur! Die Straßen von RoboTown sind voller Kurven und Wendungen. Um der Schatzkarte zu folgen, muss dein Explorer Bot ganz genau drehen können. Zum Glück hat dein Roboter einen eingebauten Gyro-Sensor im Hub - das ist wie ein elektronischer Kompass!

### 🎯 Was wir heute lernen:
- Wie dein Roboter sich perfekt drehen kann
- Wie der Gyro-Sensor uns dabei hilft
- Wie wir den Roboter wieder gerade ausrichten können

### 🛠️ Was du brauchst:
- Deinen Explorer Bot von Session 1
- Einen Computer mit der Pybricks App
- Eine freie Fläche zum Testen (mindestens 1m x 1m)

### 🎮 Los geht's!

#### 1️⃣ Erste Drehungen
So lässt du deinen Roboter drehen:

1. Ziehe einen "Motoren steuern" Block in dein Programm
2. Wähle beide Motoren aus
3. Stelle ein:
   - Linker Motor: +50% Geschwindigkeit
   - Rechter Motor: -50% Geschwindigkeit
4. Füge einen "Warte" Block mit 1 Sekunde hinzu

**🎈 Probier es aus:**
1. Starte das Programm
2. Was passiert?
3. Verändere die Zeit im "Warte" Block - dreht sich dein Roboter weiter oder weniger weit?

#### 2️⃣ Der Gyro-Sensor ist dein Freund!
Jetzt wird's spannend! Der Gyro-Sensor in deinem Hub ist wie ein super-schlauer Helfer, der genau weiß, wie weit sich dein Roboter gedreht hat.

So baust du eine präzise 90-Grad-Drehung:

1. Ziehe einen "Gyro zurücksetzen" Block in dein Programm
2. Füge eine "Wiederhole bis"-Schleife hinzu
3. Als Bedingung wählst du: "Gyro-Winkel > 90"
4. In die Schleife kommen:
   - "Motoren steuern" Block (wie oben)
   - Langsame Geschwindigkeit (30%)
5. Nach der Schleife: "Motoren stoppen" Block

**🎈 Das musst du wissen:**
- `90` Grad ist eine Vierteldrehung (wie wenn du nach rechts abbiegst)
- `180` Grad ist eine halbe Drehung (du schaust nach hinten)
- `360` Grad ist eine ganze Drehung (wieder zum Start)

#### 3️⃣ Lass uns ein Quadrat fahren!
Jetzt wird's richtig cool - wir lassen deinen Roboter ein Quadrat fahren!

So geht's:
1. "Wiederhole 4 mal" Block
2. Darin:
   - "Motoren steuern" Block für Geradeausfahrt (beide +50%)
   - "Warte" Block (1 Sekunde)
   - Die Blöcke für die 90-Grad-Drehung von oben

### 🎯 Aufgaben zum Üben:

#### 😊 Einfach:
1. Lass deinen Roboter ein Dreieck fahren (drei Seiten, drei 120-Grad-Drehungen)
2. Programmiere eine komplette Drehung (360 Grad)

#### 🤔 Mittel:
1. Fahre ein "Z" - drei gerade Strecken, zwei 45-Grad-Drehungen
2. Lass deinen Roboter tanzen - abwechselnd drehen und fahren

#### 🌟 Schwer:
1. Programmiere einen "Stern" - fünf Spitzen mit jeweils 72-Grad-Drehungen
2. Lass deinen Roboter deinen Namen "schreiben"

### 💡 Tipps und Tricks:
- Mach die Drehungen langsam (kleine Zahlen bei der Geschwindigkeit)
- Teste deine Programme auf einer glatten Fläche
- Wenn dein Roboter nicht genau dreht, überprüfe ob:
  - die Räder sauber sind
  - der Roboter beim Start gerade steht
  - die Batterien noch gut sind

### 🌈 Kreativ-Challenge:
Erfinde deine eigene "Roboter-Tanzchoreografie"! Kombiniere:
- Verschiedene Drehungen
- Unterschiedliche Fahrstrecken
- Kurze und lange Pausen

### 🎨 Block-Farben-Guide:
- Bewegungs-Blöcke sind GRÜN
- Sensor-Blöcke sind BLAU
- Schleifen-Blöcke sind ORANGE
- Warte-Blöcke sind GELB

### 🎉 Gut gemacht!
Du hast gelernt, wie dein Roboter sich präzise drehen kann! In der nächsten Session lernen wir, wie dein Roboter selbst Entscheidungen treffen kann.

### 🤔 Fragen zum Nachdenken:
- Warum ist präzises Drehen wichtig für Roboter?
- Welche Alltagsaufgaben brauchen genaue Drehungen?
- Wie könnte ein Roboter ohne Gyro-Sensor drehen?

### 📝 Notizen:
Schreib auf, was heute gut geklappt hat und was nicht. Das hilft dir beim nächsten Mal!

---
**💫 Bonus-Wissen:** Der Gyro-Sensor misst nicht nur Drehungen, sondern kann auch erkennen, ob dein Roboter bergauf oder bergab fährt! Das werden wir in späteren Sessions nutzen...

Viel Spaß beim Experimentieren! 🚀
