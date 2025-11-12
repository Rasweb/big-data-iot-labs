# Scenario: Smart Home Energy Analytics

### 

### Föreställ dig att du precis har börjat på EnergiSense AB – ett tech-företag som installerar smarta energisensorer i svenska hem.

Företaget vill använda **Big Data och Machine Learning** för att hjälpa hushållen spara el.

Du får tillgång till en dataset med miljontals sensormätningar.

Ditt uppdrag är att omvandla den här råa datan till **värdefulla insikter**:

- Hur ser hushållens energimönster ut?
- När använder de mest el?
- Kan vi förutsäga när energiförbrukningen kommer att öka?
- Kan vi upptäcka onormalt beteende?

### **Bakgrund**

Företaget har installerat **sensorer** i ett antal hushåll i Stockholm.

Varje sensor registrerar data som:

- tidpunkt (timestamp)
- rum (t.ex. kök, vardagsrum, badrum)
- energiförbrukning (i watt eller kWh)
- ibland temperatur, luftfuktighet eller rörelsesensor
- eventuellt information om väder eller hushållets status (aktivt/idle)

Målet är att hjälpa hushållen att **förstå, optimera och minska sin elförbrukning** — och samtidigt kunna **förutse ovanliga mönster**, som kan tyda på:

- slöseri (lampor på under natten)
- trasiga apparater
- onormalt hög energiförbrukning

### **Ditt uppdrag som Data Scientist på EnergiSense AB**

Du ska bygga en **end-to-end data pipeline** för IoT-sensordata:

| Steg | Labb | Beskrivning |
| --- | --- | --- |
| 1️⃣ | **Datainsamling & lagring** | Du får rå sensordata från EnergiSense API (simulerat via CSV). Du ska läsa in datan, förstå strukturen och spara den i ett strukturerat format. |
| 2️⃣ | **Datarensning (ETL)** | Datan innehåller saknade värden, konstiga mätningar (t.ex. negativa värden), fel tidsformat — du ska rensa och validera datan. |
| 3️⃣ | **Dataanalys & visualisering** | Identifiera energitrender: vilka rum förbrukar mest? Hur varierar förbrukningen över dygnet? Hur ser helg vs vardag ut? |
| 4️⃣ | **Machine Learning-prototyp** | Skapa en enkel modell som kan förutsäga framtida förbrukning eller klassificera “över normal”/“under normal” energianvändning. |
| 5️⃣ | **Diskussion & insikter** | Skriv en kort rapport/presentation: vad lärde ni er, och vilka beslut kan EnergiSense ta baserat på er analys? |
