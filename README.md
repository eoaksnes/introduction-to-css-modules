# Introduction to CSS modules

See slides: [http://eoaksnes.github.io/introduction-to-css-modules](http://eoaksnes.github.io/introduction-to-css-modules/)

## Ingress

CSS er flott. Det er et veldig kraftig verktøy for styling av nettsider, men det har noen store problemer f.eks. globalt scope. Dette var ikke et så stort problem da nettsteder var mye mindre og ikke så komplekse. Det er derimot ett stort problem nå som vi har store komplekse web-applikasjoner, der trenden nå er å lage gjenbrukbare komponenter som er isolerte i fra hverandre. CSS moduler er en måte å håndtere problemet med globalt scope på.

En CSS modul er en vanlig CSS-fil der alle klassenavn er scoped lokalt som standard til en komponent. Nøkkelordet her er scoped lokalt. Med CSS moduler blir dine klassenavn det samme som f.eks lokale variabler i JavaScript. Dette gjør at man kan bruke samme klassenavn i flere komponenter uten at det bli navnkonflikter, og du trenger ikke å finne opp et unikt klassenavn selv. Det er ingen BEM stil klassenavngivning. Du kan bruke enkle klassenavn med generiske navn, siden du ikke trenger å bekymre deg for påvirke det globale scopet.

## Demo code

See `css-modules-demo/`