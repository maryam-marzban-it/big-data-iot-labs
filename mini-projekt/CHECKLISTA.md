#  CHECKLISTA FÖR MINI-PROJEKT

Använd denna checklista för att säkerställa att ni har gjort allt!

---

Deadline: Torsdag 4 december kl 23:59
Redovisning: Fredag 5 december##  INNAN NI BÖRJAR

---

## STEG 1: DATAINSAMLING (10p)

- [ ] Importerat pandas
- [ ] Laddat in cleaned_iot_data.csv
- [ ] Visat första 5 raderna med `.head()`
- [ ] Visat antal rader med `len(data)`
- [ ] Listat alla kolumner med `.columns`
- [ ] Skrivit 2-3 meningar om vad datan innehåller

---

## STEG 2: DATARENSNING (15p)

- [ ] Kollat efter saknade värden med `.isnull().sum()`
- [ ] Kollat efter duplikater med `.duplicated().sum()`
- [ ] Visat statistik med `.describe()`
- [ ] Kollat om det finns konstiga värden (outliers)
- [ ] Skrivit slutsats om datakvalitet

---

## STEG 3: DATAANALYS (40p)

### Analys 1
- [ ] Valt vilken analys att göra
- [ ] Skrivit kod för analysen
- [ ] Skapat en graf med matplotlib
- [ ] Lagt till titel, labels, legend på grafen
- [ ] Skrivit 2-3 meningar om resultatet

### Analys 2
- [ ] Valt vilken analys att göra
- [ ] Skrivit kod för analysen
- [ ] Skapat en graf med matplotlib
- [ ] Lagt till titel, labels, legend på grafen
- [ ] Skrivit 2-3 meningar om resultatet

### Analys 3
- [ ] Valt vilken analys att göra
- [ ] Skrivit kod för analysen
- [ ] Skapat en graf med matplotlib
- [ ] Lagt till titel, labels, legend på grafen
- [ ] Skrivit 2-3 meningar om resultatet

---

## STEG 4: PREDIKTIV MODELL (25p)

### Val av features
- [ ] Valt minst 3 features (X)
    - temprature
    - wind speed
    - humidity
- [ ] Valt target (Y = air_pullation_index)
- [ ] Förklarat VARFÖR ni valde dessa features
    - vi har valt tempratu för att ju värmare det är är det mer molekyl röresle och mer torrhet vilket kan leda till mer      air_pollution_index
    - wind speed bidrar väldigt mycket till luftförorening, vinden kan ta med sig förorenat luft vidare till en plats.
    - humidity 


### Bygg modell
- [ ] Importerat sklearn
- [ ] Delat data i träning/test (80/20)
- [ ] Skapat LinearRegression()
- [ ] Tränat modellen med `.fit()`
- [ ] Gjort prediktioner med `.predict()`

### Utvärdera
- [ ] Beräknat R² score
- [ ] Beräknat MAE
- [ ] Skapat graf: prediktioner vs verkliga värden
- [ ] Diskuterat om modellen är bra/dålig (3-5 meningar)
- [ ] Förklarat VARFÖR den blev bra/dålig

---

## STEG 5: REKOMMENDATIONER (10p)

### Rekommendation 1
- [ ] Skrivit titel
- [ ] Förklarat varför (baserat på vilken analys?)
- [ ] Beskrivet åtgärd (vad ska göras?)
- [ ] Beskrivet effekt (vad händer?)

### Rekommendation 2
- [ ] Skrivit titel
- [ ] Förklarat varför
- [ ] Beskrivet åtgärd
- [ ] Beskrivet effekt

### Rekommendation 3
- [ ] Skrivit titel
- [ ] Förklarat varför
- [ ] Beskrivet åtgärd
- [ ] Beskrivet effekt

---

## INNAN INLÄMNING

### Tekniskt
- [ ] Kört hela notebooken från början (Restart & Run All)
- [ ] Alla celler körs utan fel
- [ ] Alla grafer visas korrekt
- [ ] Filnamn: Mini_Projekt_[Ditt_Namn].ipynb

### Innehåll
- [ ] Alla TODO är borttagna eller ifyllda
- [ ] Kod är kommenterad
- [ ] Text är på svenska
- [ ] Inga "Lorem ipsum" eller placeholder-text kvar
- [ ] Slutsats är skriven

### Formatering
- [ ] Markdown-celler är snygga
- [ ] Grafer har titlar och labels
- [ ] Text är läsbar
- [ ] Inget onödigt output (t.ex. jättelånga listor)

---

## INLÄMNING

- [ ] Sparat filen med rätt namn
- [ ] Laddat upp på Canvas
- [ ] Fått bekräftelse på uppladdning
- [ ] Innan deadline: Torsdag 4 december kl 23:59

---

## REDOVISNING

### Förberedelse
- [ ] Valt vilken graf att visa
- [ ] Förberett vad ni ska säga (5 min)
- [ ] Testat att öppna er notebook

### På redovisningen
- [ ] Ha notebooken öppen
- [ ] Visa 1 graf
- [ ] Förklara R² score
- [ ] Presentera 3 rekommendationer
- [ ] Svara på frågor

---

##  PROBLEM?

Om ni fastnar:
1. Kolla i Lab 1-4 efter liknande exempel
2. Fråga i Canvas diskussionsforum
3. Maila läraren
4. Kom på handledningstid

---

##  SISTA TIPS

✅ **Börja tidigt!**  
✅ **Håll det enkelt!**  
✅ **Testa ofta!**  
✅ **Fråga om ni är osäkra!**

---

**LYCKA TILL!** 
