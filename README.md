#Projet_maison_backup
Par Maxim Vezina
Pour la classe A23-247-5D5-GG - Utiliser des protocoles de communication
Donné par Antoine Legault
Dans la session d'automne 2023

Board central
-Sert de remplacement aux boards d'ATmega qui ne fonctionnent pas
-Les resistances de pullup sont optionels, chosisez celles que vous avez besoin
-Crystal aussi optionel, si vous ne la voulez pas, ne la soude pas (ses condensateurs non plus)
-Ne pas souder la resistance de reset si vous utilisez un pullup par code
-S'assurer de ne pas doubler les pullups avec un autre board
-Le robot se nomme ATmegamind et il aime danser :)

Board de MOSFET
-Sert a alimenter la lumiere et la serrure de porte
-Connecter la lumiere ou serrure au + et au -
-Connecter le pin GPIO ou vous l'avez besoin

Board de capteur de temperature
-S'assurer de ne pas doubler les pullups I2C avec un autre board

Board d'alimentation
-Soudez le fil rouge au VCC et celle blanche au GND
-Condensateurs de decouplge probablement pas necessaires, mais l'espace est inclus au cas ou
