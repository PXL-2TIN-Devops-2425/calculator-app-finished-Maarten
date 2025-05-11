<ADD badge here>
[![Node.js CI](https://github.com/PXL-2TIN-Devops-2425/calculator-app-finished-Maarten/actions/workflows/node.js.yml/badge.svg)](https://github.com/PXL-2TIN-Devops-2425/calculator-app-finished-Maarten/actions/workflows/node.js.yml)

# Assignment 4: Pipelines in Jenkins


1. Maak een nieuw pipeline project aan zoals gezien in de les en begin met het hello world script zoals hieronder afgebeeld. De naam van dit project noem je devops-opdracht-2:

![alt_text](https://i.imgur.com/rnoMFXT.png "image_tooltip")

Voer de pipeline uit en zorg dat deze werkt.
2. Maak een nieuwe stage aan met de naam `deel 1`:
    1. Die de huidige working directory afdrukt.
    
2. Maak een nieuwe stage aan met de naam `deel 2`:
    1. Deze stage maakt een nieuwe map aan met de naam `halloween` en een bestand met de naam `.boo`
    2. Doe een listing van de huidige directory die bestanden (inclusief verborgen bestanden) in een lijstje toont en de bestandsgrootte weergeeft.

![alt_text](https://i.imgur.com/Hv9jkZE.png "image_tooltip")
Voer de pipeline succesvol uit en plaats in de file oplossing.md een screenshot onder punt (a) met het het bewijs van een werkende pipeline a.d.h.v. de console output

3. Vul de pipeline aan met een stage die `deel 3` heet en die de volgende commando's uitvoert:
    1. Maak voor elk teamlid een map met als naam je studentennummers
    2. maak in elke map een leeg bestand met als naam `VoornaamAchternaam`.
    3. Maak een zipfile met de naam 'groepsleden.zip' die de mappen met de bestanden in een `zip` file archiveert (geen `tar` of `7z` of ...)
    4. doe een ls vanuit je workspace directory die de structuur van je mappen toont.
 
 4. Voorzie vervolgens een stage  `deel 4`. Deze stage zorg ervoor dat de files en de directory elke keer succesvol aangemaakt kunnen worden (zorg dat de pipeline directory na elke build poging opgeruimd wordt).

![alt_text](https://i.imgur.com/Hv9jkZE.png "image_tooltip")
Voer de pipeline succesvol uit en plaats in de file oplossing.md een screenshot onder punt (b) met het het bewijs van een werkende pipeline a.d.h.v. de console output

5. Vul de pipeline aan met een script stage die  `checkout code` heet en die het volgende doet:
    1. de code uit deze git repo binnenhaalt: [https://github.com/PXL-2TIN-DevOps-Resources/Calculator-app](https://github.com/PXL-2TIN-DevOps-Resources/Calculator-app)

![alt_text](https://i.imgur.com/Hv9jkZE.png "image_tooltip")
Voer de pipeline succesvol uit en plaats in de file oplossing.md een screenshot onder punt (c) met het het bewijs van een werkende pipeline a.d.h.v. de console output

6. Zorg ervoor dat, als de pipeline succesvol is uitgevoerd je een echo doet van "winner!"

7. Neem de pipeline code die je gebouwd hebt en sla deze op in een file genaamd `jenkinsfile` en voeg deze toe aan de map van je opdracht, naast de file readme.md en oplossing.md.

![alt_text](https://i.imgur.com/Hv9jkZE.png "image_tooltip")
Push deze jenkinsfile naar de github repo.

# Deliverable
- De verschillende screenshots in de `oplossing.md` file. Deze screenshots bevatten de console output van de relevante stappen alsook de pipeline steps indien niet duidelijk.
- De pipeline als script in de file `Jenkinsfile` in deze repository **(geen Jenkinsfile resulteert in een 0 op deze opdracht)**.
- Zorg ervoor dat je nooit `sudo` gebruikt in je pipeline script. **Het gebruik van `sudo` resulteert in een 0 op deze opdracht.**

