---
layout: post
title:  "Tankar om pre-compiling och preprocessors"
date:   2019-11-17 18.04 +0100
categories: blogg
---

För någon som mig, som inte är överdrivet förtjust i CSS, så är det är en klar förbättring att jobba med preprocessors.
Arbetet känns renare och enklare att hålla reda på när man kan jobba med variabler som sedan kan appliceras på en mängd olika element, istället för att behöva upprepa kod ett antal gånger. Vanlig CSS-kod kan dessutom snabbt bli ganska oöverskådlig och svårläst när man måste trycka in all CSS-kod i en enda fil som ska skickas till webbläsaren.
 
Det ska dock påpekas att det här är lite sanning med modifikationer, i och med att CSS förändras och förbättras, men min egen (väldigt knappa) erfarenhet med CSS har på många sätt varit väldigt frustrerande, av anledningar som sass (vilket är det jag har använt här) i stort sett eliminerar. 

I det här projektet har jag använt mig mycket av variabler för färgval samt en del struktur i _layout.scss. Bland annat så har färgschemat ändrats från originalet i Minima, en bakgrundsbild har lagts till i headern och diverse borders har korrigerats. 

Fördelarna är mycket det jag redan nämnt ovan i min jämförelse med vanlig CSS, men kortfattat är det mer överskådligt, det går att nästla kod, variabler är enkla att använda för t.ex. färgval och i min mening så känns det smidigare att arbeta med överlag.
Nackdelen kan vara att man lägger till fler steg i processen, vilket i sin tur kan leda till en större risk för fel och buggar. Dessa kan i sin tur vara svårare att felsöka då radnummerna kommer vara helt annorlunda mellan hemsidan och ens egen kod.