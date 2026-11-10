# HTML-oppgavetekst-Besøkdag-10.11.2026-
Oppgave for nettsidelaging på besøksdagen på Informasjonsteknologi og Medieproduksjon (IM), på Hamar katedralskole Tirsdag 10.11.2026

# TRENGER HJELP!!!
## Har du problemer underveis? Still spørsmål hvis du har noe du lurer på, så finner vi ut av det sammen!

## Startup
`1.` **Folder layout:**
> Lag en folder med ditt navn i mappen `Mappe for elevnettsider besøksdag 10.11.2026`. I den mappen du har laget, skal du igjen lage 3 filer: `index.html`, `style.css` og `script.js`.
> 
> Folder strukturen din skal se slik ut:
```markdown
{ditt navn}
  │
  ┝━━ [index.html]
  ┝━━ [style.css]
  ┝━━ [script.js]
```
\
`2.` **HTML-struktur:**
> I `index.html` skriv: 
```html
!
```
og så klikk **`enter`** da skal det se slik ut:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

# Oppgave

## 1.1

Bruk `hjelpeliste.md` og finn ut hvordan du viser tekst i HTML. 

## 1.2 – Lage en enkel Clicker

Målet med oppgaven er å lage en enkel nettside der du kan trykke på en knapp og få antall klikk til å øke med 1 for hvert trykk.

### Fremgangsmåte

`1.` **HTML – Lage overskrifter og tekst:**

> Først lager vi en overskrift med `<h1>` og en tekst under med `<p>`. Dette gjøres for å vise hva nettsiden handler om. F.eks:

```html
<h1>not cookie cliker</h1>
<p>not a cliker clone</p>
```

`2.` **HTML – Lage en knapp:**

> Deretter lager vi en knapp med `<button>`. Inni knappen skriver vi f.eks `Eksempel`, som er teksten som vises på knappen.
>
> Vi bruker også `onclick="Click()"`. Dette gjør at funksjonen `Click()` blir kjørt hver gang vi trykker på knappen.

```html
<button onclick="Click()">--</button>
```

`3.` **HTML – Vise antall klikk:**

> For å vise hvor mange ganger vi har trykket på knappen, bruker vi `<p>`

`4.` **JavaScript – Lage en variabel:**

> Nå begynner vi med JavaScript. Først lager vi en variabel som heter `clicks`. Vi setter verdien til `0`, fordi vi starter med null klikk.
>
> Vi bruker `let` fordi verdien skal kunne endres etter hvert som vi trykker på knappen.

```javascript
let clicks = 0;
```

**Formel:**

`clicks = 0`

`5.` **JavaScript – Lage en funksjon:**

> Deretter lager vi en funksjon som heter `Click()`. En funksjon er en samling med kode som kan kjøres når vi trenger den.
>
> Vi bruker denne funksjonen til å gjøre tallet større hver gang knappen blir trykket på.

```javascript
function Click() {

}
```

`6.` **JavaScript – Øke antall klikk:**

> Inni funksjonen skriver vi `clicks += 1`. Dette gjør at variabelen `clicks` øker med 1 hver gang funksjonen kjøres.

```javascript
clicks += 1;
```

**Formel:**

`clicks = clicks + 1`

> Dette betyr at hvis vi har 0 klikk fra før, blir det 1 etter første trykk. Hvis vi har 1 klikk, blir det 2 etter neste trykk.

`7.` **JavaScript – Vise tallet i konsollen:**

> Vi bruker `console.log(clicks)` for å skrive ut det nåværende antallet klikk i konsollen. Dette er nyttig for å sjekke om koden fungerer som den skal.

```javascript
console.log(clicks);
```

`8.` **JavaScript – Oppdatere nettsiden:**

> Til slutt må vi få det nye tallet til å vises på nettsiden. Derfor bruker vi `document.getElementById('c').innerHTML = clicks`.
>
> `document.getElementById('c')` finner HTML-elementet som har `id="c"`.
>
> `.innerHTML` brukes til å endre innholdet inni dette elementet.
>
> `= clicks` gjør at innholdet blir byttet ut med den nye verdien fra variabelen.

```javascript
document.getElementById('c').innerHTML = clicks;
```

`9.` **Resultat – Sette alt sammen:**

> Når vi har gjort alle stegene, skal koden fungere slik at hver gang vi trykker på knappen, øker tallet med 1. Det nye tallet vises automatisk på nettsiden.

---

## Formler og forklaringer

Disse formlene viser hvordan klikkeren fungerer:

| Kode | Forklaring |
|---|---|
| `clicks = 0` | Starter med 0 klikk. |
| `clicks += 1` | Øker antall klikk med 1. |
| `clicks = clicks + 1` | Samme formel som over. |
| `innerHTML = clicks` | Oppdaterer tallet på nettsiden. |

### Eksempel på hvordan klikkeren fungerer

| Antall trykk | Verdien til `clicks` |
|---|---|
| 0 | 0 |
| 1 | 1 |
| 2 | 2 |
| 3 | 3 |
| 4 | 4 |
| 5 | 5 |


## Kort oppsummert

HTML lager innholdet på nettsiden, mens JavaScript gjør at knappen fungerer. Variabelen holder styr på antall klikk, funksjonen øker tallet, og `innerHTML` sørger for at det nye tallet vises på nettsiden.

## 1.3 – Lage en Shop | ekstra oppgave
Prøv å lage en knapp som lar deg kjøpe oppgraderinger når du har nok 'clicks'
