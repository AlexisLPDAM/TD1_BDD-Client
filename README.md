# TD1_BDD-Client
RenduTD1

Etude API GitHub :

	Service 1 : L'authentification
	Service 2 : Rate Limiting Pour les demandes non authentifiées 
	Service 3 : Cross Origin Resource Sharing  
	Service 4 : Récupérer des emojis pour github 
	Service 5 : Client Errors

Etude API Méteo :

	Service 1 : Demander la météo sur une ville grâce au nom sur une période de 3H à 5 jours
	Service 2 : Demander la météo sur une ville grâce au coordonnées GPS sur une période de 3H à 5 jours
	Service 3 : Demander la météo sur une ville grâce à l'ID sur une période de 3H à 5 jours
	Service 4 : Demander les température min/max pour une ville
	Service 5 : Demander un support multilingues

API GitHub

	Requêtes GET : https://api.github.com/users/octocat/orgs
	Reponse Serveur : []
	Requêtes GET : https://api.github.com/repos/vmg/redcarpet/issues?state=closed
	Reponse Serveur :  Info sur le projet en JSON
	Requêtes GET : https://api.github.com/organizations?since=135
	Reponse Serveur :  Réponse en JSON
		

# Application Client : METEO

Application Météo : Fonctionnalités (Via API :http://api.tameteo.com/)
	
		Déterminer la météo automatiquement au démarrage de l'application grâce aux données GPS (Si activé, Mobile & WEB)
		Déterminer la météo pour un code postal précis rentrée par l'utilisateur (Mobile & WEB)
		Explorer les différentes météo dans le monde via une carte (Mobile & WEB)
		Voir la météo sur plusieurs jour en indiquant un indice de confiance (Mobile & WEB)
		Avoir un support multilingues (Mobile & WEB)
		Base de données MySQL (WEB)
		Base de données SQLite (Mobile)
		
		
	