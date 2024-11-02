# 🤖 RoboTown Abenteuer - Session 6
## Die große Schatzsuche!

### 📜 Die Geschichte geht weiter...
Der große Tag ist gekommen! Alle Hinweise führen zu einem geheimen Ort in RoboTown. Dein Explorer Bot hat alles gelernt, was er für diese letzte Mission braucht. Bist du bereit für das größte Abenteuer?

### 🎯 Was wir heute lernen:
- Wie wir alle gelernten Fähigkeiten kombinieren
- Wie wir mit Variablen zählen und speichern
- Wie wir eigene Programmblöcke erstellen
- Wie wir Fehler finden und beheben

### 🎓 Bisher gelernte Fähigkeiten:
- 🚗 Fahren und Drehen (Session 1+2)
- 🔄 Schleifen und Bedingungen (Session 3)
- 👀 Hindernisse erkennen (Session 4)
- 🎨 Farben folgen (Session 5)

### 🎮 Los geht's!

#### 1️⃣ Variablen - Unser Roboter-Gedächtnis
**Was sind Variablen?**
- Wie eine Box, in der der Roboter sich Zahlen merkt
- Zum Beispiel: Wie viele Schätze gefunden wurden

**So benutzt du Variablen:**
1. "Variable erstellen" Block:
   - Name: "gefundeneSchaetze"
   - Startwert: 0
2. "Variable ändern" Block:
   - Plus 1 wenn Schatz gefunden
   - Minus 1 wenn falsch
3. "Wenn Variable = X" Block:
   - Prüfe, ob genug Schätze gefunden

#### 2️⃣ Eigene Blöcke - Deine Roboter-Superkräfte
**Erstelle diese Hilfsblöcke:**

1. **"Schatz_Suchen" Block:**
```
1. Vorwärts fahren
2. Wenn Hindernis:
   - Ausweichen
3. Wenn Farbe = Rot:
   - Schatz prüfen
```

2. **"Ausweichen" Block:**
```
1. Stoppen
2. Rückwärts (1 Sekunde)
3. Gyro auf 0 setzen
4. Drehen bis Weg frei
```

3. **"Schatz_Prüfen" Block:**
```
1. Melodie spielen
2. LED blinken
3. Variable erhöhen
4. Nachricht senden
```

#### 3️⃣ Das große Schatzsucher-Programm

**Teil 1: Vorbereitung**
1. Variablen erstellen:
   - "gefundeneSchaetze" = 0
   - "zeit" = 0
2. Eigene Blöcke vorbereiten
3. Start-Melodie abspielen

**Teil 2: Hauptprogramm**
1. "Wiederhole bis gefundeneSchaetze = 3" Block
2. Darin:
   - "Schatz_Suchen" Block aufrufen
   - Zeit erhöhen
   - Status anzeigen

**Teil 3: Erfolg feiern!**
1. Gewinner-Melodie
2. Buntes LED-Feuerwerk
3. Zeit anzeigen

### 🎯 Die großen Herausforderungen:

#### 😊 Einfache Schatzsuche:
1. **Der erste Schatz:**
   - Folge der schwarzen Linie
   - Ein Hindernis umfahren
   - Roten Punkt finden

2. **Der schnelle Finder:**
   - Zwei Schätze in unter 1 Minute
   - Zeit mit Variable zählen
   - Erfolgsmelodie spielen

#### 🤔 Mittlere Schatzsuche:
1. **Der schlaue Sammler:**
   - Drei verschiedene Farb-Schätze
   - Reihenfolge merken
   - Hindernissen ausweichen

2. **Der Zeit-Agent:**
   - Zeitlimit von 2 Minuten
   - Warntöne bei wenig Zeit
   - Abbruch wenn Zeit um

#### 🌟 Profi-Schatzsuche:
1. **Der Master-Finder:**
   - Fünf versteckte Schätze
   - Komplexer Parcours
   - Mehrere Farbcodes
   - Zeitlimit

2. **Das Team-Abenteuer:**
   - Zwei Roboter arbeiten zusammen
   - Nachrichten senden
   - Gemeinsam Schätze finden

### 💡 Tipps zum Fehlersuchen:
1. **Teste in kleinen Schritten:**
   - Erst ein Teil
   - Dann mehr dazu
   - Alles einzeln prüfen

2. **Häufige Fehler:**
   - Sensor zu weit weg
   - Batterie schwach
   - Falsche Reihenfolge

3. **Lösung finden:**
   - Programme vergleichen
   - Langsamere Bewegungen
   - Mehr Wartezeit

### 🎨 Block-Farben-Guide:
- Variablen-Blöcke sind ROT
- Eigene Blöcke sind VIOLETT
- Sensor-Blöcke sind BLAU
- Bewegungs-Blöcke sind GRÜN
- Wenn-Dann-Blöcke sind GELB

### 🌈 Die ultimative Challenge:
Baue deinen eigenen Schatz-Parcours:
- Verstecke Hinweise
- Plane Hindernisse
- Erfinde Farbcodes
- Miss die Zeit
- Lade Freunde ein!

### 🎉 HURRA - Du bist ein Roboter-Meister!
Du hast es geschafft! Du kannst:
- Programme schreiben
- Sensoren nutzen
- Probleme lösen
- Roboter steuern
- Eigene Ideen umsetzen

### 🤔 Letzte Gedanken:
- Wo können Roboter noch helfen?
- Was möchtest du als nächstes bauen?
- Welche Abenteuer warten noch?

### 📝 Das letzte Roboter-Tagebuch:
Schreibe auf:
- Dein größter Erfolg
- Die schwierigste Aufgabe
- Deine coolste Idee
- Dein nächstes Projekt

---
**💫 Bonus-Wissen:** Echte Roboter-Ingenieure machen genau das gleiche wie du: Sie lösen Probleme Schritt für Schritt, testen ihre Ideen und verbessern ihre Programme immer weiter. Du bist jetzt einer von ihnen! 🚀

### 🎓 Dein Abschluss-Zertifikat
*Hier könnte dein Lehrer/deine Lehrerin ein echtes Roboter-Meister-Zertifikat für dich ausfüllen!*

Herzlichen Glückwunsch zu deinem Erfolg! 🌟
