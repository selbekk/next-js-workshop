# Next.js workshop

Denne workshopen vil lære deg å lage server-side rendered React-apper med Next.js.

## Server side? What?

I tillegg til å være et veldig kraftig verktøy for å lage frontenden din mer interaktiv,
kan React også kjøre helt uten nettleser. Man kan rett og slett be React returnere en 
string (eller en stream) med HTMLen det ellers ville insertet i DOMen din.

Dette gir en rekke fordeler. I likhet med andre server-side rendrete websider, får man 
bedre søkbarhet for søkemotorer (eller for deling i sosiale medier), og ikke minst raskere
tid til siden er tegna hos brukeren. Til slutt vil appen din fungere uten JavaScript i det
hele tatt - det er ganske kult for en JavaScript-app.

##  Kan man ikke gjøre det selv?

Joda, det går fint an å gjøre dette helt uten hjelp - men det er ikke helt rett frem. Man 
må løse routing for både backend og frontend, og man må hente inn data før man returnerer 
responsen til serveren. Det er med andre ord en hel haug med feller å falle i, 

## Hva er Next.js?

Next.js er et bibliotek som løser de aller fleste problemene man møter på med server-side 
rendring av React-apper. Det er et slags tynt lag over React, og kommer komplett med 
routing og dev-server. Det er faktisk så populært at det er de-facto standarden for 
server-side rendering av apper i dag - men vi bruker det ikke så mye i Bekk, enda).

Det er Next.js vi skal leke oss med i dag - så her vil du bli godt kjent med hva som er 
mulig i alle fall. Kanskje det blir en ny favoritt?

Du finner hjemmesiden deres på [nextjs.org](https://nextjs.org/).

## Oppgaver

Next.js har en fantastisk tutorial som tar deg gjennom det mest grunnleggende i Next.js.
Det er denne tutorialen vi skal følge i dag, for å komme ordentlig i gang. 

[Gå til oppgavene!](https://nextjs.org/learn/)

### Ekstra oppgaver

Om du skulle bli ferdig med Next.js sin tutorial - eller om du har tatt den før, finner du her noen 
ekstra utfordringer. Det er ikke forventa at du kommer så langt - men bare sånn just in case :)

#### Lag en blogg

Pass på, Sophie Elise, her kommer jeg! Lag en blogg som viser frem bloggartikler skrevet i markdown-format. 

1. Lag en ny app med `npx create-next-app markdown-blogg`
2. Lag en mappe "content" og fyll den med Markdown.artikler.
3. Legg til litt meta-informasjon med front-matter-markup helt øverst i markdown-filene
4. List opp de 5 nyeste artiklene på forsiden
5. Lag en post-side som viser hele appen

#### Bruk styled-components

Ta utgangspunkt i bloggen i forrige oppgave. Style den ved hjelp av styled-components! Du må legge til en 
babel-plugin, og redefinere `pages/_document.js`. [Her er et eksempel](https://github.com/zeit/next.js/tree/canary/examples/with-styled-components).



