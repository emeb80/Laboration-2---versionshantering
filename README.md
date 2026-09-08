# Laboration 2 - Versionshantering

## Webbplatsen
Webbplatsen består av 3 sidor med länkning för varje sida. 
- Hobbysidan innehåller en länk till extern sida som öppnas i nytt fönster.
- Kontaktsidan innehåller kontaktformulär samt funktion för att ta emot aviseringar.

## Teknisk specifikation
- Sidan är byggd med enbart HTML

## Länkar
https://labtwo.netlify.app/

https://emeb80.github.io/Laboration-2---versionshantering/

## Frågor & Svar
Git add = lägger till ändrade filer i stageing area add. lägger till samtliga filer.
Git commit= kopierar filerna från stageingarea till den lokala repon. 
Man kan säga att git add lägger till filerna i vänteläge medan git commit lägger till dessa permanent i den lokala repon.

Branch arbetar man med för att behålla koden stabil under tiden, det vill säga en fungernde version. Att ha en branch innbär att flera utvecklare kan arbeta samtidigt och att det inte påverkar koden under tiden. Det är även ett sätt att inte ladda upp nya versioner till webbhotellet hela tiden utan att man samlar på sig ändringar och sedan när man känner sig klar och har testat så det blir bra så laddar man upp en gång, istället för efter varje ändring. 

En merge innebär att jag "smälter samman" min gren med en annan gren, som i det här arbetet, där dev smälter samman med main och blir den nya koden, det nya main.

På GitHub pages är sidan statisk och det är mer sätt sätt att visa upp en sida, man kan lagra sin kod där, och det som visas är den senaste versionen, den kod jag har pushat senast.
Via Netlify (webbhotell)  är det en levande/fungerande sida som den som har adressen till kan använda, sidan kan användas fullt ut med html, css, java etc.

Om något inte skall visas i versionshanteringen används gitignore. Jag skapar en textfil som heter .gitignore i projektets rotmap. sedan lägger jag  en lista med de filer jag vill exkludera.

