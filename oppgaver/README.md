# Prosjekt 1 - Din første nettside 
I denne oppgaven skal vi lage vår helt første nettside! Vi skal starte helt fra
scratch og lage en nettside om deg og ting du liker. Du kommer til å lære de
vanligste HTML-taggene som lar deg lage lister, sette inn bilder, sette in
linker og til og med en video fra YouTube!


## Steg 1: Sette opp noen mapper og filer
Det første du må gjøre er å sette opp en mappe hvor vi kan ha nettsiden vår.

- Lag en ny mappe på f.eks skrivebordet med navnet `Prosjekt-1`. 
- Åpne programmet `Notepad++` eller et annet tekstprogram (et program som lar
  deg redigere tekstfiler. Eksempler er Notisblokk, Notepad++ eller TextEdit) 
- Lagre den tomme fila som `index.html` i mappa du laget i steget over. Navnet
  `index.html` er ikke tilfeldig. Dette er et standard navn som gis til alle
  startsider, f.eks forsiden av Facebook, NRK eller Instagram. 

## Steg 2: De første taggene 
Det første vi skal gjøre er å sette opp et skall vi kan lage nettsiden. Da
trenger vi taggene `html`, `head` og `body`. `html` brukes til å definere
nettsida, hele nettsida kommer innenfor disse. I `head` kan vi bla. legge inn regler
for hvordan nettsida skal se ut og `body` brukes til å inneholde alt det vi ser
på nettsida

- Lag nettsida som vist under: 

```
<html>
    <head>
    </head>
    <body>
    </body>
</html>
```

Legg merke til at vi har åpne-tags og lukke-tags. `<html>` åpner og `</html>`
lukker. 

- Inne i `<body>` skriver du "Hei, jeg heter NAVN!" hvor du erstatter NAVN med
  ditt eget navn. Hvis du heter Bjørn skal fila se slik ut: 
```
<html>
    <head>
    </head>
    <body>
        Hei, jeg heter Bjørn! 
    </body>
</html>
```

- Om du har et navn som inneholder bokstene Æ, Ø eller Å vil du se at sida ser
  litt rar ut. For å få den til å forstå norske bokstaver må vi legge inn en
  liten tag i `<head>`-taggen: 

```
<meta charset="UTF-8">
```


## Steg 3: Se hvordan det ser ut i en nettleser! 

Nå vil vi ta en titt på hvordan nettsida ser ut. Åpne mappa du laget og
dobbelklikk på fila `index.html`. Nå skal en nettleser ha åpnet seg og du kan 


## Steg 4: Lag en liste med ting du liker
La oss lage en liste med ting du liker. For å lage en nummerert liste må vi lære
oss `ul` og `li` taggene. `ul` er for å lage en liste og `li` brukes til å lage
hvert av punktene i lista. Åpne tekstprogrammet igjen og legg til en liste under
teksten du la inn.

Først må vi sette opp lista vår: 

```
<ul> 
</ul>
```

Så må vi legge inn ting i lista: 

```
<ul>
    <li> Første ting </li>
    <li> Andre ting </li> 

</ul>
```

Legg inn ting du liker med taggene `<li> </li>`. Når du har lagt inn et par ting
du liker skal fila se slik ut: 

```
<html>
    <head>
        <meta charset="UTF-8">
    </head>
    <body>
        Hei, jeg heter Bjørn! 
        
        Her er et par ting jeg liker: 
        <ul> 
            <li> Programmering </li>
            <li> Taco </li> 
            <li> Musikk </li> 
        </ul>
    </body>
</html>
```




## Steg 5: Litt finere nettside

Sida ser jo grei ut, men la oss endre litt på utseende. For å lage overskrifter
kan vi bruke taggene `h1`, `h2`, `h3` osv. og for å lage en tekstparagraf kan vi
bruke `p`. 

- Pakk inn overskrifta i en `<h1>`-tag slik at det ser ut som dette: 

```
<h1> Hei, jeg heter Bjørn! </h1> 
```

- Så lager vi en litt mindre overskrift til favorittingene dine: 

```
<h3> Her er et par ting jeg liker </h3> 
```

## Steg 6: Nummerert liste med favoritter
La oss legge inn en liste med noen favoritter, f.eks fotballspillere, mat,
biler, sykler, band, revyer, filmer, gutter eller jenter. En nummerert liste
ligner veldig på en unummerert liste, men nå bruker vi `ol`-taggen for å lage
lista og ikke `ul` som over. 

- Skriv en overskrift over favorittene og legg dem inn i en liste: 
```
<h3> Min favorittmat </h3> 
<ol>
    <li>Taco</li>
    <li>Hamburger</li>
    <li>Pizza</li>
    <li>Kokt kveite</li>
</ol> 
```

## Steg 7: Legg til en link til favoritten
Klarer du å legge inn linker i favorittlista din? Hvis du laget en liste over
mat, kan du kanskje linke til en oppskrift? Hvis du la inn en liste over filmer
kan du kanskje linke til en anmeldelse eller trailer? For å legge inn en link må
vi bruke `a` taggen: 

```
<a href="http://COPY-PASTE-SIDA-DU-VIL-LINKE-TIL-HER"> Synlig tekst </a> 
```

da vil teksten "Synlig tekst" vises og om man trykker på den blir man sendt
vidre til nettsida du la inn. Prøv å legg inn linker selv! 

Her er et eksempel på å linke til oppskrifter: 
```
<ol>
    <li><a href="http://www.klikk.no/mat/spise/article511911.ece">Taco</a></li>
    <li><a href="http://oppskrift.klikk.no/hamburger/1055/">Hamburger</a></li>
    <li><a href="http://oppskrift.klikk.no/pizza/2267/">Pizza</a></li>
    <li><a href="http://oppskrift.klikk.no/superrask-tomatsuppe/4046/">Tomatsuppe</a></li>
</ol> 
```

## Steg 8: Legg inn et bilde! 

Siste steg i dette prosjektet er å legge inn et bilde. Da trenger vi å lære oss
om `img` taggene. Disse ligner veldig på `a` taggen for å legge inn en link, men
i stedet for at vi blir sendt vidre til bildet får vi nettleseren til å vise det
i stedet. 

Under listen med favorittene kan du legge til et bilde av noe du syns er gøy,
kanskje en artig gif? 

```
<h3> Hvordan det føles å være ferdig med første prosjekt </h3> 
<img src="http://i.imgur.com/aZPFg2t.gif"></img> 
```



# Prosjekt 2: Publiser nettsiden på internett! 
Nå som vi har laget en enkel side om oss selv er det på tide å legge den på
nett! I dette prosjektet skal du ende opp med en link du kan dele med andre som
viser nettsida di. Jeg har delt min nettside [her](http://bl.ocks.org/fjukstad/raw/88baf748161cdd97fd7b/). 

## Steg 1: Lag en konto på Github.com
Det første du må gjøre er å lage deg en konto på nettsiden
[github.com](http://github.com). Github er en nettside som folk rundt om i hele
verden bruker til å dele kode med hverandre. Her finner du bla. mye av koden som
ligger bak sider som [Finn.no](https://github.com/finn-no),
[Facebook](https://github.com/facebook), eller
[Spotify](https://github.com/spotify). 

- Gå til [github.com](https://github.com/) og lag en ny konto. 

## Steg 2: Logg inn og lag en gist
Det neste vi skal gjøre er å logge inn på Github med brukeren du nettopp laget
og lage en `gist`. En `gist` er lett måte å dele kode med andre, hvor man kan
laste opp filer og får en link man kan dele med andre.

- Gå til nettsiden [github.com](https://github.com/), logg inn og trykk på
  "Gist" øverst på sida. 

Nå har du blitt sendt vidre til sida [gist.github.com](http://gist.github.com)
og du kan starte med å gjøre din første nettside offentlig. 

- Dra inn `index.html`-fila du laget i Prosjekt 1 i nettsiden. Når du slipper
  den vil du se at koden din har blitt satt inn.
- Endre beskrivelsen i ruta "Gist description..." til noe som passer sida di.
  F.eks "Min første nettside". 
- Trykk på "Create Public Gist" og du blir sendt vidre til en side som har en
  url som ligner på `https://gist.github.com/BRUKERNAVN/1234-LANG-STRENG`. f.eks 
  [https://gist.github.com/fjukstad/88baf748161cdd97fd7b](https://gist.github.com/fjukstad/88baf748161cdd97fd7b). 

Hvis du deler denne linken med andre kan de se på og laste ned koden, men vi ser
jo ikke hvordan nettsida blir når den åpnes. Dette skal vi fikse i steg 3! Noter
ned det som står bak `gist.github.com/` i adressen, det trenger vi i neste steg! 

## Steg 3: Publiser nettsida! 
For å få nettsida online skal vi bruke en side som heter
[bl.ocks.org](http://bl.ocks.org/). Dette er en side som er laget for å se på
`gist`s som vi laget i steg 2. 

- Åpne en nettleser, skriv inn `bl.ocks.org/` + `ditt github brukernavn`  +
  `/raw/` + `den lange tekststrengen fra lenken i steg 2`, og trykk enter. Hvis du skrev riktig har du en lenke som ser slik ut:
[http://bl.ocks.org/fjukstad/raw/88baf748161cdd97fd7b/](http://bl.ocks.org/fjukstad/raw/88baf748161cdd97fd7b/)
og du blir sendt vidre til nettsida du lagde. Fungerte det? 

# Prosjekt 2: Styling av nettsider 
I denne oppgaven skal vi få nettsida til å bli litt finere! For å plassere og
sette farge på ting har vi et språk som heter CSS (Cascading style sheets). 

## Steg 1: Legge til styles
CSS som beskriver hvordan nettsida vår ser ut legger vi inne i `head` taggen
øverst i HTML-en. 

- Åpne index.html fra forrige oppgave i et tekstprogram (f.eks Notepad++)
- I `head` taggen legger du til

```
<style>

body {
    background-color: pink;
}

</style> 
```

slik at starten på `index.html` ser slik ut: 

```
<html>
    <head>
        <meta charset="UTF-8">

        <style>
            body {
                background-color: pink;
            }
        </style>

        .
        .
        .
```

- Åpne index.html i en nettleser og se at bakgrunnsfargen ble rosa. 

## Steg 2: Overskrifter 
La oss lage de små overskfitene grønn. Da kan vi legge inn en regel for alle
`h3` taggene: 

``` 
h3 {
    color: green;
}
```

Kodesnutten over skal legges inn under koden vi la inn i steg 1. Men hva om vi
vil at én av overskfitene skal være blå? La oss lage overskriften som står over
bildet blå. I CSS-en vår nå har vi sakt at alt som er markert med `h3` skal være
grønt, men nå vil vi at én av de skal være blå.  Da trenger vi å gi overskrifta
en `id` som vi kan bruke i CSS-en vår. 

- I `index.html` gå til overskrifta over bildet og endre `h3` taggen litt: 

```
<h3 id="overskrift"> Hvordan det føles å være ... 
``` 

se at vi har lagt inn `id="overskrift"`
- Legg til CSS-en vår legge til

``` 
#overskrift {
    color: blue;
}
```

i CSS-en vår øverst i index.html. 


## Steg 3: Sentrering av bilder og tekst
La oss få bildet og overskrifta til å ligge sentrert på sida. I HTML bruker vi
`div` tagger for å dele opp forskjellige deler av sida. 

- Pakk inn overskrifta og bildet i en `div` med `id=bilde`: 

```
<div id="bilde">
    
    <h3 id="overskrift"> Hvordan det føles ...
    <img src="....

</div> 
```

- legg til en regel i CSS-en: 

```
#bilde { 
    text-align: center;
}
```

- Sjekk at overskrifta og bildet kommer midt på sida. 

## (BONUS) Steg 4: Gjør nettsida finere
Nå ser egentlig ikke nettsida ut. Kan du gjøre den finere? Her er det bare å
prøve seg fram med farger og layout! Nederst på sida finner du noen ressurser
til både HTML og CSS. 

## (BONUS) Steg 5: Gjør nettsida tilgjengelig online! 

Gå tilbake til prosjekt 2 og last opp denne sida på nettet! 


# Prosjekt 3:  Egen nettside med videoer fra YouTube

Dette er det siste prosjektet hvor vi skal lage en nettside som består av flere
HTML-filer som inneholder litt tekst om deg selv og noen YouTube-videoer.
Nettsida om deg selv kan du gjenbruke fra Prosjekt 1 eller starte med en helt ny
side. Her kommer vi kun til å gi dere et enkelt eksempel. Dere må selv finne ut
av hva dere vil ha på sida og være litt kreativ i bruk av farger. 

Hvis du vil se en demo av hvordan sida kan se ut kan du se
[her](http://bl.ocks.org/fjukstad/raw/ebb02d8f4bd48b6e26b0/).


## Steg 1: Lag en mappe og noen tomme filer.
Det første vi må gjøre er å sette opp en tom mappe for nettsida vår i tillegg
til noen tomme HTML-filer vi kan legge innhold i. 

- Lag en mappe som heter `nettside` og legg den et sted du husker, f.eks på
  Skrivebordet
- I denne mappa lager du 3 filer som heter `index.html`, `om.html` og
  `videoer.html`. Om du vil gjenbruke sida du laget om deg selv kan du kopiere
  den inn i mappa og kalle den `om.html`. 
- I alle de nye filene legger du inn: 

```
<html>
    <head> 
        <meta charset="UTF-8">
        <style>
        </style>
    </head>
    
    <body>
    </body>
</html> 
```

Husk at du ikke skal legge dette inn i `om.html` om du gjenbruker sida fra
Prosjekt 1. Nå har vi tre HTML filer vi kan begynne å legge inn innhold i! 


## Steg 2: Velkomstside
Nå skal vi få satt opp en velkomstside som sier hei og har lenker til de andre
sidene.

- Åpne `index.html` i et tekstprogram
- Lag en overskrift og en velkomstmelding: 

```
<h1> Overskrift (sett inn noe her) </h1> 
<p> 
    Her kan du skrive en fin velkomstmelding 
</p> 
```
Koden over skal inn i `body` taggen på HTML-sida. 

- Sjekk at du får inn en overskrift 

Vi vil gjerne at teksten skal være på midten, så da kan vi pakke alt inn i en
`div` og sentrere den med litt CSS.

- Pakk overskriften inn i en `div` og lag en CSS regel: 

```
<div id="tekst">
    <h1> Overskrift .....

</div> 
```

og CSS-regelen blir da: 

```
#tekst { 
    text-align: center;
}
```

- Sjekk at det blir sentrert på sida.

Nå må vi få inn en navigasjonsmeny på toppen! 

- Lag et nytt `div` element over overskriften som vi kaller `nav`. Inne i denne
  lager vi noen lenker til de andre sidene: 

```
    <div id="nav"> 
        <a class="nav-link" href="index.html">Hjem</a> / 
        <a class="nav-link" href="om.html">Om</a> /
        <a class="nav-link" href="videoer.html">Videoer</a>
    </div> 
```

Denne koden setter opp en `div` med tre linker (`a` elementene) som hver peker
til hver sin side. Hjem-lenken peker til `index.html`, altså fila vi redigerer.
Om-lenken peker til `om.html` som skal handle om deg. Videoer-lenken peker til
`videoer.html` som vi skal fylle ut senere. 

- For å få det til å se litt finere ut kan vi flytte menyen til midten av siden: 

```
#nav { 
    text-align: center;
}
```

- Og siden vi har satt en at hver av `a` taggene tilhører klassen `nav-link` kan
  vi si at de skal alltid være svart og ikke være understreket: 

```
.nav-link {
    text-decoration: none;
    color: black;
}
```

Du kan selvfølgelig velge hvilken farge du vil at lenkene skal være, velg gjerne
noe annet enn svart! 

For å flytte overskrifta litt ned kan du legge inn denne CSS regelen til `div`
taggen til menyen: 

```
    margin-bottom: 50px;
```

## Steg 3: Lag en side om deg selv
Om du ikke har laget en side om deg selv må du gjøre det! Hvis du allerede har
en side klar trenger du kun å legge til en navigasjonsmeny helt øverst på sida. 

- Til de som ikke har en side om seg selv: Åpne `om.html` i et tekstprogram og følg beskrivelsen i Prosjekt 1. 
- De som allerede har en side: Åpne `om.html` i et tekstprogram og lim inn
  `div`-en med menyen i tillegg til CSS-reglene i `style`-delen av headeren. 



## Steg 4: YouTube-videoer! 
Nå skal vi lage en side med et par YouTube videoer!! 

- Åpne `videoer.html` som du lagde i steg 1. 
- Legg til samme meny og CSS-regler som du har på de andre sidene. Det betyr at
  `body`-en av siden din skal starte med

```
<div id="nav"> 
    <a class="nav-link" href="index.html">Hjem</a> / 
    <a class="nav-link" href="om.html">Om</a> /
    <a class="nav-link" href="videoer.html">Videoer</a>
</div> 
```

og i `style`-en skal du ha 

```
#nav { 
    text-align: center;
    margin-bottom: 50px;
}

.nav-link {
    text-decoration: none;
    color: black;
}

```

eller det du hadde i `index.html`. 


Når du har lagt inn menyen øverst skal vi legge til videoer. Hver video legger
vi en `div` som inneholder en overskrift, selve videoen, en beskrivelse av
videoen, og en strek på skjermen for å dele opp sida. Hvilke tagger du vil bruke
kan du velge selv, her er et eksempel: 

```
<div id="video"> 
    <h3> Musikkvideo fra Resirkulert </h3>

    <iframe width="560" height="315" src="https://www.youtube.com/embed/UbDcMur37iQ?rel=0" frameborder="0" allowfullscreen></iframe>

    <p>
        Her er en musikkvideo fra Kåfjord-bandet <a
        href="https://www.facebook.com/Storfjordband">Resirkulert </a> 
    </p> 

    <hr> 
</div>
```

Fortsett med å legge inn flere av disse helt til du har lagt til så mange
videoer du vil ta med. For å få de sentrert og med litt luft mellom seg kan du
legge til CSS regelen: 

```
#video {
    text-align: center; 
    margin-top: 20px;
    margin-bottom: 20px; 
}
```

# Ressurser
- [HTML tags](https://developer.mozilla.org/en/docs/Web/HTML/Element) 
- [CSS referanse](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference) 
