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

## Week 2
