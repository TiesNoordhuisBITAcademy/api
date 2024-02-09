# opdrachten

1. Maak een html pagina met een like knop.
2. Schrijf javascript code die bij het laden van de pagina, de json van https://tiesnoordhuisbitacademy.github.io/api/post.json haalt en de data in de html pagina weergeeft.
3. Schrijf javascript code die bij het klikken van de like knop, het aantal likes in de json verhoogt.

## opdracht 1
Maak een html pagina met een like knop. Je kan de volgende code gebruiken als startpunt:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Post</title>
  </head>
  <body>
    // Hier komen de elementen voor je post en like knop
  </body>
</html>
```

## opdracht 2
Schrijf javascript code die bij het laden van de pagina, de json van https://tiesnoordhuisbitacademy.github.io/api/post.json haalt en de data in de html pagina weergeeft. Je kan de volgende code gebruiken als startpunt:

```javascript
fetch(// Zet hier je URL)
    .then(respons => response.json())
    .then(data => {
        // gebruik hier de data
    })
```

## opdracht 3
Schrijf javascript code die bij het klikken van de like knop, het aantal likes in de json verhoogt. Je kan de volgende code gebruiken als startpunt:

```javascript
document.getElementById(// zet hier het id van de like knop)
    .addEventListener('click', //zet hier de functie die het de likes omhoog doet)
```