1. Git 

	- Git installeren
		- zeker toevoegen aan de PATH variabele
	- Github account aanmaken

2. Cursus web backend structuur

	- de volgende mappenstructuur aanmaken

		web-backend
			|- cursus (NOG NIET AANMAKEN -> dit gebeurt via Git)
			|- oplossingen

	- Op Github een repository "web-backend-oplossingen" aanmaken en deze linken aan je oplossingen map: https://github.com/pascalculator/web-backend#je-eigen-oplossingen-uploaden-naar-je-online-repository

	- De cursus via Git binnenhalen: https://github.com/pascalculator/web-backend#git-gebruiken-om-cursus-te-downloaden

		- Let op: de map "cursus" wordt automatisch aangemaakt met dit commando: ```git clone https://github.com/pascalculator/web-backend.git __cursus__```

3. Virtual hosts instellen

	- Howto: https://github.com/pascalculator/web-backend/raw/master/public/cursus/virtual-server-setup.pdf

	- Voorbeeld van een virtual host configuratie: https://raw.githubusercontent.com/pascalculator/web-backend/master/public/cursus/vhost-voorbeeld.txt

		- Mensen met Mac: lees bijgevoegde commentaar

	- Stel je virtual hosts zo in dat wanneer je naar 

		- http://web-backend.local surft in feite de map /web-backend/cursus/public wordt ingeladen

		- http://oplossingen.web-backend.local surft de map /web-backend/oplossingen wordt ingeladen



