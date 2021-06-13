# Weekly nerd week 3
> In de verschillende vakken die je hebt gevolgd zijn technieken en werkwijzen aan bod gekomen die een "echte" frontender ook doet: prototypen, experimenteren, ingewikkelde code, simpele code, onderzoeken, testen, lezen, documenteren, en heel veel HTML, CSS en JS, op de client en op de server. Welke onderwerpen hebben de meeste indruk op je gemaakt? Een gastspreker of een test? Een inzicht tijdens een Discord-sessie met een van de student-assistenten? Schrijf per vak wat je hebt geleerd en wat je meeneemt als frontender.

### Web App From Scratch
Dit was het eerste vak van de minor (samen met CSS to the Rescue), en het heeft me direct enthausiast gemaakt voor de rest van de minor. Er kwamen allerlei leuke concepten in mijn hoofd op voor kleine web applicaties, en ik heb uiteindelijk gekozen voor een soort weer app. Ik vond het erg opmerkelijk dat het veel simpeler is om client-side routing van scratch te maken dan ik dacht. Ik heb er echt niet enorm veel code voor geschreven maar het werkte wel best goed.

### CSS to the Rescue
Door dit vak ben ik er wel echt achter gekomen dat vanilla CSS veel krachtiger is dan dat ik wist. Ik gebruik al een langere tijd voornamelijk SCSS en dit bevalt mij heel erg goed, maar nu zou ik sneller gewoon vanilla CSS gebruiken bij kleinere projectjes. Ik ben bij dit vak voor de 3D Rubik's cube opdracht gegaan, en heb ook wat 'formules' in mijn CSS staan om de Rubik's cube te maken. Ik was zelf best onder de indruk van alle verschillende CSS features die je eigenlijk amper tegenkomt bij 'normale' websites.

### Progressive Web Apps
Ik ben bij dit vak voor het eerst bewust met service workers aan de slag gegaan. Dit was nieuw voor mij en heb er hiermee voor gezorgd dat je de web applicatie kan 'installeren' en offline kunt bekijken. Verder ben ik tijdens dit vak voor het eerst met push notificaties aan de slag gegaan met de web-push dependency. Dit vond ik enorm leuk om te doen en het werkte ook erg goed. Het is zeker iets wat ik in de toekomst nog een keertje in iets zou willen verwerken. Alleen is het wel jammer dat het bijvoorbeeld op iOS niet werkt.

### Browser Technologies
Tijdens dit vak heb ik een poll website gemaakt, ik ben super erg de Progressive Enhancement wereld in gedoken en kwam er al vrij snel achter dat het vrij lastig kan zijn om 'on point' te zijn met je Progressive Enhancement. Uiteindelijk heb ik wel alles (wat mogelijk was) goed werkend gekregen zonder client-side JavaScript. Ik vond dit erg leuk en leerzaam om te doen, en neem dit ook echt heel erg mee in de toekomst omdat het erg belangrijk is dat de main features van een applicatie gewoon altijd werken.

### Real-Time Web
Ik vond dit echt het aller leukste vak van de hele minor. Ik ben helemaal los gegaan op het gebied van real time data afhandelen en states updaten. Ik had nooit eerder Socket.IO gebruikt met React maar het is echt super powerful. Het voelde zo tof om constant React state te updaten vanaf mijn back-end (waar alle logica stond qua data aanpassen etc.), alles werkt enorm goed en ik ben erg trots op het resultaat. Wat ik ook mooi vond om te zien is dat ik ook bij de GET en POST requests de gebruiker het gevoel geef alsof het real-time is. Dit kan ik natuurlijk doen omdat ik een front-end framework heb gebruikt (React), maar dit was voor mij eigenlijk ook nieuw omdat ik niet eerder met een eigen back-end heb gewerkt samen met React.

### Human Centered Design
De motivatie was ver te zoeken bij mij tijdens dit vak. Ik heb vaak echt een afkeer voor vakken waar je veel onderzoek en documentatie moet doen, dit vak zat daar vol mee. Maar ongeveer halverwege / twee derde van het blok ben ik er even goed voor gaan zitten en vond ik het eigenlijk echt enorm leuk. Wat wel jammer was is dat ik hierdoor niet super veel kon testen omdat ik pas zo laat lekker aan de slag ging, maar ik ben alsnog tevreden over het eindproduct en heb geleerd dat ik dingen soms misschien iets meer een kans of wat meer tijd moet geven voor mezelf.

## Mirabeau
- Het is niet verkeerd om SPA frameworks te gebruiken
- Zorg wel altijd voor SSR/SSG
- En zorg er ook voor dat je goed aan PE doet

### Next.js lost dit op in React:
- Geen SSR (Server Side Rendering)
- Slow initial page load
- SEO
- Gebruikers die JavaScript uit hebben geschakeld
Met Next.js kun je dus CSR en SSR.

### T-shaped front-end developer
- Expert in front-end development
- Ervaring/kennis met/in visual design
- Ervaring/kennis met/in interaction design

### Progressive Enhancement
- JavaScript
    - Altijd 'vanilla' behalve als er echt een SPA framework nodig is
    - Progressively enhance UX
- CSS
    - Mobile first
    - Progressively enhance UX
- HTML
    - Accessibility
    - SEO
    - Stop met het wiel opnieuw uitvinden
