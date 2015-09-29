# KdG: Web Backend (2015-2016)

docent: Pascal Nosenzo (pascal.nosenzo@kdg.be)

ECTS: [Web back-end WP 2](https://bamaflexweb.kdg.be/BMFUIDetailxOLOD.aspx?a=56428&b=1&c=1)

## Deadlines

- Deadlines voor de te maken opdrachten komen hier

## Cursus

De cursus vind je terug op de [Web Backend GitHub repository](https://github.com/pascalculator/web-backend). In de [README.md](https://github.com/pascalculator/web-backend/blob/master/README.md) vind je instructies terug over hoe je deze cursus moet installeren.

### Stappenplan voor de installatie:

1. Git 

	- [Git](https://git-scm.com/downloads) installeren

		- zeker toevoegen aan de PATH variabele

	- [Github](https://github.com/) account aanmaken

2. Cursus web backend structuur

	- de volgende mappenstructuur aanmaken

		```
		web-backend
			|- cursus (NOG NIET AANMAKEN -> dit gebeurt via Git)
			|- oplossingen
		```

	- Op Github een repository "web-backend-oplossingen" aanmaken en deze linken aan je oplossingen map. Bekijk [de instructies](https://github.com/pascalculator/web-backend#je-eigen-oplossingen-uploaden-naar-je-online-repository).

	- De [cursus via Git binnenhalen](https://github.com/pascalculator/web-backend#git-gebruiken-om-cursus-te-downloaden)

		- Let op: de map "cursus" wordt automatisch aangemaakt met dit commando: ```git clone https://github.com/pascalculator/web-backend.git cursus``` (let op het laatste woordje __cursus__. Dat is de naam van de map die aangemaakt zal worden.)

3. Virtual hosts instellen

	- [Instructies](https://github.com/pascalculator/web-backend/raw/master/public/cursus/virtual-server-setup.pdf)

	- Voorbeeld van een [virtual host configuratie](https://raw.githubusercontent.com/pascalculator/web-backend/master/public/cursus/vhost-voorbeeld.txt)

		- Deze virtual host config kan je integraal overnemen (mits de nodige aanpassingen), op voorwaarde dat je de laatste nieuwe versie van XAMPP (Apache) hebt draaien

		- Mensen met Mac: lees bijgevoegde commentaar

	- Stel je virtual hosts zo in dat wanneer je naar 

		- http://web-backend.local surft de lokale map /web-backend/cursus/public wordt ingeladen

		- http://oplossingen.web-backend.local surft de lokale map /web-backend/oplossingen wordt ingeladen

4. Je naam, email en url van GitHub account toevoegen aan dit bestand

	- Edit dit bestand door op het potloodje te klikken

	- Voeg je gegevens toe

	- Voer een [pull request](https://help.github.com/articles/using-pull-requests/) uit om de wijzigingen tot bij mij te krijgen
	
## Spelregels

- Deze cursus is zelfstudie: je doorloopt de slides, bekijkt de overeenstemmende voorbeelden en maakt vervolgens de opdrachten. Dat betekent niet dat je niet mag overleggen of vragen mag stellen. De docent is er om je te begeleiden en feedback te geven. Maak hier dus gebruik van!

- Je bent aanwezig tijdens de lessen zodat er persoonlijke begeleiding kan gegeven worden. Afwezigheden worden aan mij gemeld via mail én op de KdG-voorgestelde manier gemeld (via e-student services)

- Je gemaakte opdrachten komen op je publieke GitHub repository.

- Per gemaakte opdracht voer je minstens één commit uit, zodat het duidelijk is wanneer je aan welke oefening hebt gewerkt. 

- Deadlines worden gerespecteerd, zonder discussie.

- Je mag kleine dingen kopiëren of je door de voorbeeldopdrachten laten inspireren als je vast zit op voorwaarde dat je elke lijn code kan uitleggen. Integraal een oefening kopiëren en wat variabelen veranderen of commentaar bijschrijven, staat uiteraard gelijk aan plagiaat.

- Vroeger doorgaan tijdens de lessen is geen enkel probleem, mits je dit bij het begin van de les laat weten en je tijdens je aanwezigheid hebt laten zien waar je aan gewerkt hebt.

- Heb je foutjes gevonden of klopt er iets niet? Aanpassingen/verbeteringen (pull requests) aan de cursus worden beloond met minstens één extra punt op het eindtotaal én een eerbare vermelding op de [contributors](https://github.com/pascalculator/web-backend#contributors)-lijst van de cursus.

- Bij problemen (te hoge werkdruk, planning, ...) kan je mij dit in vertrouwen laten weten en dan zoeken we samen naar een oplossing. Het is belangrijk dat je dit -op voorhand- laat weten en niet bv. nadat een deadline is verstreken.

## Beoordeling

- Permanente evaluatie tijdens de lessen op basis van de opdrachten en betrokkenheid
	- Laat je zien dat je jezelf kan bijsturen?
	- Ben je kritisch ten opzichte van de oplossingen?
	- Ben je periodiek met de oefeningen bezig?
	- Verricht je opzoekingswerk?
	- Stel je voldoende vragen?
	- Haal je de deadlines of communiceer je tijdig wanneer dit niet lukt?
	- Deze evaluatie kan je ook altijd even komen raadplegen
	- 50% van het eindtotaal

- Resultaat van de tussentijdse opdrachten
	- Op het einde van elke periode volgt er een opdracht om te kijken wat je huidige kennis is. Deze wordt beoordeeld op:
		- Werkbaarheid
		- Gebruikte technieken comform met de cursus
		- Cleane code (indents, herbruikbaarheid: functies/classes, scheiding logica & html)
	- Deze opdracht moet individueel opgelost worden. Plagiaat/kopiëren wordt zwaar bestraft en krijgen een glansloze vermelding in de "Hall of shame".
	- 50% van het eindtotaal

Er wordt geen eindexamen voor Web Backend geörganiseerd.

## Feedback ivm cursus

Graag! Je mag mij altijd aanspreken tijdens de les of een mailtje sturen met eventuele verbeteringen ivm de cursus.

## Studenten

- Seppe Renty
	- email: seppe.renty@student.kdg.be
	- GitHub: https://github.com/sepperenty
