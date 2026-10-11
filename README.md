# Robotique-et-IA-2
Devoir d'assistant Robotique et IA de SAINT JUSTE Jn Rooths vinski


### Objectif du projet

C'est de créer un petit assistant électronique. Vous tapez des mots dans l’ordinateur (par exemple ROUGE ON), et la carte Arduino exécute l’ordre : elle allume une lampe, bouge un moteur, fait sonner un buzzer, puis écrit sur un petit écran pour confirmer.

### Les Composantes Utiliser 

- Un Arduino Mega 2560
- Un LCD 16x2 
-LED rouge, verte, jaune
- 4 Résistance 220 Ω
- Un Servomoteur	
- Un Buzzer
- Un Bouton poussoir 


### Foctionnement du projet

Pensez à un petit robot qui obéit à des ordres écrits.

Vous écrivez une commande dans le moniteur série, qui est la fenêtre où l’on tape du texte pour parler à la carte.
L’Arduino Mega lit cette commande et cherche ce qu’elle veut dire.

Elle agit :
-les 3 LED (rouge, verte, jaune) s’allument ou s’éteignent ;
-le servomoteur tourne à 0°, 90° ou 180° ;
-le buzzer sonne ou s’arrête.
-Elle confirme sur l’écran LCD avec un message comme LED rouge ON  ou Servo 90 deg.
-Le bouton sert de sécurité, quand on appuie dessus, toutes les LED s’éteignent et le buzzer s’arrête d’un coup.

##Résultat obtenu

Le résultat obtenu est que chaque commande tapée provoque la bonne réaction sur le circuit et la bonne confirmation sur l'écran. 

###Lien wokwi

https://wokwi.com/projects/477511493004467201
