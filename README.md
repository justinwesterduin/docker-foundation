# Foundation voor PHP met Docker

## Overzicht

Dit project is opgezet om een PHP-applicatie te kunnen ontwikkelen met Docker.
Het maakt gebruik van Docker voor containerisatie, Docker Compose
voor het beheren van meerdere containers, en Composer voor het
beheren van PHP-afhankelijkheden.

## Structuur

Het project bestaat uit de volgende bestanden en mappen:

* **Dockerfile**: Dit bestand bevat instructies voor het bouwen van een Docker-image voor de applicatie.
* **docker-compose.yaml**: Dit bestand definieert de services, netwerken en volumes voor de Docker-containers. Het maakt het gemakkelijk om het project in meerdere containers te draaien.
* **.dockerignore**: Dit bestand bevat patronen voor bestanden en mappen die moeten worden genegeerd bij het kopiëren van bestanden naar de Docker-image.
* **composer.json**: Dit bestand bevat de configuratie voor Composer, een tool voor het beheren van PHP-afhankelijkheden.
* **public/index.php**: Het ingangspunt voor de applicatie. Dit is waar de uitvoering begint.
* **public/.htaccess**: Het Apache-configuratiebestand voor het definiëren van URL-rewriting en andere serverinstellingen.
* **public/**: Deze map bevat de openbare bestanden van de applicatie, zoals CSS, JavaScript en afbeeldingen.
* **app/**: Deze map bevat de broncode van de applicatie.

## Installatie

Om dit project lokaal te draaien, volg je deze stappen:

* Zorg ervoor dat Docker is geïnstalleerd op je systeem.
* Voer het commando `docker-compose up -d` uit om de containers te starten.
* Open je webbrowser en ga naar http://localhost:8080 om de applicatie te bekijken.
