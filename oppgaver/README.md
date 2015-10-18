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
Her kommer en oppgave om styling av nettsider. 

# Prosjekt 3:  Egen nettside med videoer fra YouTube
Denne oppgaven har ingen oppgavetekst, så denne blir litt vanskeligere. Du skal
lage en helt egen nettside som inneholder top 10 videoer fra YouTube om et tema
du velger selv. Liker du MineCraf? Justin Bieber? T.I.L? T.U.I.L? Hest? Finn
fram videoene fra YouTube og lag en side som lister opp disse. Ta gjerne med en
liten beskrivelse av hvorfor videoene er med på lista! 

Tips til hvordan man legger inn en YouTube-video finner dere her: [http://kodeklubben.github.io/web/lesson8/lesson8.html](http://kodeklubben.github.io/web/lesson8/lesson8.html). 

# Prosjekt 4: Litt programmering
Her kommer det en oppgave hvor dere skal lære litt om programmeringsspråket JavaScript. 
