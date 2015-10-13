# Hvordan bygger man sin egen nettside? 
Denne kjøres interaktivt sammen med elevene. Man koder nettsida mens de sitter
og følger med. 

- Lag en tom fil med navnet `index.html`
- Åpne den i Chrome og se at det er helt hvitt
- Legg til vanlige HTML tags og snakk litt om de: 

```
<!DOCTYPE html> 
<html>
<p> Hei </p> 
</html>
```

- La oss lage et par overskrifter!

```
<h1> Dette er en overskrift </h1> 
<h2> Mindre overskrift </h2> 

```

- Lag en liste med ting 

```
<ul>
    <li> Første ting </li>
    <li> Andre ting </li> 
</ul> 

```

- Hva skjedde med Ø-en? Vi må si at vi skal bruke UTF-8 enkoding på nettsida. 
- Lag en `head` tag og legg inn at vi skal bruke UTF-8. 

```
<head>
<meta charset="UTF-8">
</head>
```

- La oss prøve å få sida til å se litt finere ut. Kan vi få p-en til å være blå,
  og lista til å være rød? 

```
<style>

p {
    color: blue;
}

li {
    color: red;
}
</style> 
```


- La oss legge inn et bilde! Søk opp et kattebilde og legg det inn! 

```
<p>
Her kommer et kattebilde! </br> 
<img src="http://dreamatico.com/data_images/kitten/kitten-2.jpg"></img> 
</p> 
```

- Det er litt stort, så la oss gjøre det mindre 

```
img {
    width: 50%;
    height: 50%;
    
}
```

- Hva med å sentrere det? 

```
<p id="katt">
Her kommer et kattebilde! </br> 
... 
```

```
#katt {
    text-align: center;
}

```


