# Skole-discord bot
Her blir noe av dataen, f.eks. teksten som blir sendt som melding når man bruker kommandoen !hjelp, lagret og hentet fra. Dataen er lagret i JSON-filer.
## Basics av JSON
JSON er et filformat som lagrer data som et par, med navn og verdi.
Her er et eksempel:
```javascript
"bøker" : [
 "Episk bok" : {
  "sider" : 69,
  "forfatter" : "Magswag"
 },
 "Veldig wow bok" : {
  "sider" : 420,
  "forfatter" : "Mareliii"
 }
]
```
Det finnes to typer data-samlinger i JSON. Objekt og array, begge vist i eksempelet over. Et objekt er en samling av data-par, de kan også inneholde arrays. En array er en liste som kan inneholde fler objekter eller arrays, som videre kan inneholde enda flere objekter eller arrays.
I eksempelet over, er "bøker" en array som inneholder 2 bøker. De to bøkene er hvert sitt objekt, med unike data.
