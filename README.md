# Fetch More Jokes

I denne opgave skal du kombinere din viden om URL-parametre og fetch, så du kan lave en søgefunktion, der lader brugere søge efter en joke.

Du skal lave filerne

* index.html
* search-results.html
* app.js

I `index.html` skal der være en søge-formular. Den skal indeholde et søgefelt og en submit-knap.

På `search-results.html` skal der være et område, fx en `<div>`, hvor du kan udskrive søgeresultaterne.

I `app.js` skal du lave en funktion, som indeholder et fetch-kald til `https://icanhazdadjoke.com/j/search?term=x` hvor du udskifter `x` med det søgeord, som brugeren udfylder i søgeformularen på `index.html`.

Søgeresultaterne skal skrives ud som en liste vha. DOM-manipulation. Husk at udsætte side-effekterne til så sent som muligt.

## OBS
Hvis der _ikke_ er noget søgeresultat, skal der stå på resultatsiden:

> "Der blev ikke fundet nogen joke. Prøv igen."

## Resurser
API-dokumentation: https://icanhazdadjoke.com/api

MDN-dokumentation: https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch