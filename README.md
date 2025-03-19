# CSS To The Rescue
## Week 1
Er zijn 3 opdrachten waar ik uit mag kiezen, ik kies voor de eerste opdracht (Control panel) waar ik een bruikbare UI maak voor een (kleine) game.
#### Idee 1
⚔️ Mijn eerste idee was om een pokemon styled bossbattle te maken waar ik vecht tegen Sanne, "Ufuk used JavaScript", "Sanne did not find this effective"

![pokemon bossfight](https://static.wikia.nocookie.net/essentialsdocs/images/7/70/Battle.png/revision/latest?cb=20220523172438)

#### Idee 2
🩹 Mijn tweede idee is een satisfying makeover game waar je een soort "huidspecialist" bent die de patient verzorgt. Ik ben uiteindelijk niet voor dit idee gegaan omdat ik dit idee niet genoeg vond aansluiten aan de opdracht zelf

![Pimple game](https://www.gamenora.com/upload/games/thumbnails/Acne%20Be%20Gone.webp)

#### Idee 3 (gekozen)
👗 Mijn derde idee is een character customization game, vaak zie je dit soort dingen voordat je een spel begint om je eigen karakter te maken. Ik heb gekozen voor dit idee omdat ik vondt dat het idee genoeg aansluitingen zou hebben voor uitbreiding mocht dat nodig zijn, ook vond ik het passen bij de opdracht omdat het toch wat meer UI gericht is dan de andere ideeën.

![Character customization](https://images.axios.com/kavKMlNPJbLVGHcLApCnWdQ3NBo=/0x0:2144x1206/1920x1080/2022/11/21/1669063661762.png)

### Onderzoek
Sanne liet ons ooit een project van hem zien waar hij zichzelf had gemaakt en zichzelf emoties heeft gegeven door het animeren van de wenkbrauwen, mond, ogen etc.

![sinds1971](https://github.com/user-attachments/assets/0ff21a5d-2803-489a-8dfa-b1dd84d30897)

Ik heb grondig gekeken naar hoe zijn code van het project in elkaar zit en zag al snel dat Sanne **elementen en de pseudoclasses hiervan heeft gestyled**. Ik heb hier zeker inspiratie van genomen en de mentaliteit overgenomen om niet overal div's te spammen.

De componenten die nodig zijn om dit idee te realiseren zijn dus eigenlijk menselijke eigenschappen, zoals een hoofd, oren, ogen, neus, een mond, wenkbrauwen etc.

![sinds1971](https://github.com/user-attachments/assets/3cdd56da-c089-48d6-bebc-2dec0c8623ed)

### Technieken die ik ga gebruiken
Na wat onderzoek gedaan te hebben kwam ik er achter dat ik deze technieken nodig had om het gewenste doel te behalen:

https://cmda-minor-web.github.io/css-to-the-rescue-2425/samples.html
- :has()
- Filters & Masks
- Animeren
- Vormpjes maken

### Week 1 progress
![week1progress](https://github.com/user-attachments/assets/f42dbe18-91db-4d4e-8748-39a0cb9e0ad5)

Wat ik vooral leerde hier is om na te denken hoe ik componenten moet stylen.
Een mooi voorbeeld hiervan is de **ul li** voor de ogen 👀, dit zijn inprincipe 2 list items, die ik naast elkaar heb geplaatst met flexbox en dan gap gebruik om ze afstand van elkaar te laten hebben.

Ik heb het gevoel dat dit de juiste keuze was omdat we de pseudo element ::before hebben kunnen gebruiken om de wenkbrauw toe te voegen en de ::after om de bijbehorende oor 👂 toe te voegen aan de kant van het hoofd.

#### Voortgangsgesprek feedback
- Leuk idee
- Rijk aan uitbreidingsmogelijkheden
- Tips met border-radius gebruik om gewenste vormen te realiseren

## Week 2

*In week 2 was ik ziek na de maandag waardoor ik ook het 2e voortgangsgesprek heb gemist.*

### Onderzoek
- Border-radius gebruik: [Bron](https://css-tricks.com/the-shapes-of-css/)
- Workshop van Sanne: Vormpjes maken met CSS
- Komkommer gradient: [Bron](https://cssgradient.io/)

### Voortgang
Ik heb de personage kunnen maken na veel handmatig de waardes heen en weer aan te passen totdat ik blij was met de styling.
![Week2 progress](https://github.com/user-attachments/assets/1f802fea-9428-4b6d-b57f-0e9e00462b86)

### Week 3

### Onderzoek
- CSS only carousel: [Bron](https://css-tricks.com/css-only-carousel/)
- :has() gebruik [Bron](https://www.w3schools.com/cssref/sel_has.php)
- Clip-path: [Bron](https://developer.mozilla.org/en-US/docs/Web/CSS/clip-path)
- Squiggly line use: [Bron](https://developer.mozilla.org/en-US/docs/Web/CSS/Subsequent-sibling_combinator)

### Progress
In week 3 was ik vooral bezig met de UX kant van mijn project, dit was dus labels en inputs maken, die properties van de CSS overschrijft zodra er een radio button wordt gechecked.
Hierdoor kan ik met de juiste selectors een "UI" creëeren zonder het gebruik van JavaScript.

Wat ik dus doe voor bijvoorbeeld de huidskleur veranderen is de variabele in de root een andere value geven dan voorgaand.
![huidskleur](https://github.com/user-attachments/assets/52242fb3-0b67-4d2f-8b7d-b654271a99ca)

Voor de haarstijl heb ik clip-path leren gebruiken. Wat hier vooral complex was dat ik clip-path moest gebruiken wat ik niet eerder heb aangeraakt. Na wat hulp van Nils Binder en wat bronnen hebben we samen onze eerste haarstyle kunnen maken.
![haarstyle](https://github.com/user-attachments/assets/7dbee0c2-4df0-47bb-9a08-28623cae8318)

Ook heb ik een komkommer animatie gemaakt
![komkommer animatie](https://github.com/user-attachments/assets/0958654b-7127-4e27-8b31-121c43435f3e)


![Week3](https://github.com/user-attachments/assets/0105ee8e-c1fc-4b12-b015-698a10bb454d)

#### Voortgangsgesprek feedback
- UI laten zien welke optie geselecteerd is
- Feedforward laten zien, op hover dat de style al zichtbaar is
- CSS nesting meer gebruiken
- Opschonen code met onnodig "&" gebruik
- Inputs en labels in elkaar nesten zodat ID niet gebruikt hoeft te worden
- Animatie komkommer een hapje nemen
- Meer en betere comments
- Responsive

### Week 4

In week 4 moest ik vooral gas geven na dat ik (voor mijn gevoel) veel feedback kreeg
Ik begon met de labels en inputs op de juiste manier te nesten

- [x] Inputs en labels in elkaar nesten zodat ID niet gebruikt hoeft te worden

Before

![labelseninputs](https://github.com/user-attachments/assets/aeecf1f1-17f6-4e47-8c00-951d045eb228)
![labelseninputs](https://github.com/user-attachments/assets/4b1a9f59-7411-44da-bb4c-784e209b0ad1)

After

![labelseninputsnesting](https://github.com/user-attachments/assets/3460ef6c-6ebc-49c2-a858-84386bd7a080)


- [x] UI laten zien welke optie geselecteerd is
- [x] Feedforward laten zien, op hover dat de style al zichtbaar is

Daarna ben ik bezig geweest om de UI te verbeteren en heb ik de feedforward kunnen toepassen na wat hulp van Jamie T

![feedforward](https://github.com/user-attachments/assets/0cd40a67-d669-4b9f-bb3c-1169980589b0)
![image](https://github.com/user-attachments/assets/2422b51a-fe94-46f7-b27b-552bcaa2e053)

Ook heb ik wat comments geplaatst in mijn CSS om het wat overzichtelijker te maken
- [x] Meer en betere comments

![image](https://github.com/user-attachments/assets/9440a1a1-e859-40e0-8217-717c002df14e)

- [x] CSS nesting meer gebruiken
- [x] Opschonen code met onnodig "&" gebruik
![image](https://github.com/user-attachments/assets/3ad3703c-0126-4677-804f-9572b7d27a59)

Na deze dingen gefixt te hebben heb ik nog weinig tijd gehad om de puntjes op de i te zetten. Ik heb nog de komkommer animatie verbeterd waar de personage 2 hapjes neemt uit de komkommer.
Dit heb ik gedaan met het gebruik van clip path in een animatie zelf.
![komkommer](https://github.com/user-attachments/assets/e90ce455-d1d7-4f18-881f-aa47c7990036)


![clippath](https://github.com/user-attachments/assets/511d5a4d-2d9a-45e9-b546-899b613b8884)

Het was hier belangrijk om dezelfde aantal punten te behouden in de clip-path zodat de animatie ook werkelijk geanimeerd is

- [x] Responsive
en als laatst heb ik nog wat responsivity toegevoegd
![responsivity](https://github.com/user-attachments/assets/6d8b9a5f-903f-4a57-961d-eb2c34689f43)

**Bedankt voor het lezen**
