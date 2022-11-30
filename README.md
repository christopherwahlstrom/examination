# Individuellt projekt

Examinerande uppgift i fortsättningskursen UX/UI.

---

## Uppgift

Din uppgift är att bygga en användarvänlig webbapp, som demonstrerar dina kunskaper om *animation* och *datavisualisering*. Du ska använda React (eller Vue), TypeScript, chart.js och react-chartjs-2 (eller motsvarande för Vue).

Webbappen ska visa information om Nobelpristagare genom historien. Det ska finnas en vy med flikar, där varje flik visar olika diagram över datan. När användaren byter flik, ska övergången animeras. Användaren ska kunna välja vilken animation som ska användas. Observera att du får lägga till fler element som animeras, om du behöver det för att täcka in fler av animationens principer.

**Exempel** på animationer som kan användas:
+ fade in/out
+ slide in/out
+ rotera som när man vänder blad i en bok
+ faller ner som en rullgardin

När det gäller datan ska du visa flera **diagram**, ett per flik. Minst 4 diagram för G, minst 6 för VG. Linjer, staplar och pajer
1. Genomsnittliga prissumman per år
	1. ... med möjlighet att byta mellan dåvarande beloppet och ett som är justerat till dagens penningvärde (båda finns i datafilen)
1. Antalet pristagare inom de olika kategorierna, för ett valt år
	1. ... med möjlighet att välja årtal på ett användarvänligt sätt
1. Antalet pristagare totalt, fördelat på de olika kategorierna (cirkeldiagram)
1. Fördelningen mellan män och kvinnor bland pristagare (cirkeldiagram)
1. Hur många gånger som Nobelpriset delats ut, inom varje kategori
1. Hur många pristagare som kommer från olika länder
1. De Nobelpristagare som vunnit flest Nobelpris. Visa till exempel topp 10.


### Data
+ [json_award.json](json_award.json)
+ [json_laureates.json](json_laureates.json)

*Obs 1! Läs igenom diagramuppgifterna ovan **noga**. Det är lätt att missförstå och göra något som inte svarar exakt på frågan. Fråga läraren om något är osäkert.*

*Obs 2! Om du vill göra något annorlunda än uppgiften, måste du få godkänt av läraren i förväg!*

*Obs 3! Det kan finnas fel i datan. Kontrollera noga det du läser in från filerna, innan du försöker presentera det i ett diagram.*

---
## Presentation

Uppgiften presenteras för läraren på lektionstid sista kursveckan. I samband med presentationen får du direkt feedback på din kod. Om det behövs kan du presentera flera gånger, i mån av tid. Du ska:
+ Demonstrera appen
+ Visa att den uppfyller kraven i uppgiften
+ Förklara hur du har använt animationens principer när du designat animationer

[Boka tid för presentation här](https://docs.google.com/spreadsheets/d/1NhDyEoYzogeXU8-4Rqzn-pgzSRVCN4C04iL8EvmASfM/edit?usp=sharing).

---
## Inlämning

Uppgiften lämnas in på Moodle sista kursveckan. Din inlämning ska innehålla:
1. Länk till *publikt* GitHub-repo
1. Länk till publicerad app (om du väljer att publicera den - frivilligt)

Om du av någon anledning skulle missa presentationen, måste du ha med en skriftlig rapport i <code>README.md</code> i ditt GitHub-repo. Då får du inte heller någon feedback innan betygsättningen.

---
## Bedömning

**För G krävs:**
+ Kraven i uppgiften är uppfyllda
+ Genomförd presentation
+ Minst 4 diagram

**För VG krävs:**
+ Appen använder animeringens principer i sina animationer
+ Tydlig, läsbar och hanterbar kod
+ Minst 6 diagram

---
## Animationens principer
1. Squash and stretch
1. Anticipation
1. Staging
1. Straight ahead action and pose to pose
1. Follow through and overlapping action
1. Slow in and slow out
1. Arc
1. Secondary action
1. Timing
1. Exaggeration
1. Solid drawing
1. Appeal
