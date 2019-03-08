# Skole-discord bot
Her blir noe av dataen, f.eks. teksten som blir sendt som melding når man bruker kommandoen <b>!hjelp</b>, lagret og hentet fra. Dataen er lagret i JSON-filer.
## Basics av JSON
JSON er et filformat som lagrer data som par, med navn og verdi.
Her er et eksempel:
```javascript
{
 "bøker" : [
  {
  "tittel" : "Episk utrolig-amazing bok",
   "sider" : 69,
   "forfatter" : "Magswag"
  },
  {
    "tittel" : "Blazing 420-bok",
   "sider" : 420,
   "forfatter" : "Mareliii"
  }
 ]
}
```
Det finnes to typer data-samlinger i JSON. Objekt og array, begge vist i eksempelet over. Et objekt er en samling av data-par, de kan også inneholde arrays. En array er en liste som kan inneholde fler objekter eller arrays, som videre kan inneholde enda flere objekter eller arrays.
I eksempelet over, er "bøker" en array som inneholder 2 bøker. De to bøkene er hvert sitt objekt, med unike data.
## Når du redigerer
Når du redigerer JSON-filer må du passe på at du ikke har noen syntaks-feil. Basically skrivefeil, men bare i koden. Du kan bruke [denne nettsiden](http://jsonviewer.stack.hu/) for å se JSON-filen på en mer visuell måte og for å sjekke om den har noen feil.

Etter at du har lagret filen, tar det rundt 5 minutter før du ser oppdateringen i Discord.
