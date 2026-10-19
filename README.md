# Devoir-Robotique-EIC---Robot-d-cision-intelligente

Ce que j’ai appris
J’ai appris à utiliser un capteur de luminosité (LDR) avec un ESP32 dans Wokwi pour mesurer la lumière et commander automatiquement une LED. J’ai compris comment lire une valeur analogique grâce à l’ADC de l’ESP32, puis la comparer à un seuil de 2000 avec une condition if/else.
Fonctionnement du programme
Au démarrage, le programme initialise la communication série à 115200 bauds et configure la LED comme une sortie. Ensuite, dans la fonction loop(), l’ESP32 lit continuellement la valeur du capteur LDR connecté à la broche 34 et affiche cette valeur dans le moniteur série. Si la valeur est supérieure à 2000, la LED s’allume et le programme affiche « SOMBRE : LED allumée ». Dans le cas contraire, la LED s’éteint et le programme affiche « CLAIR : LED éteinte ». Enfin, une pause de 500 millisecondes est effectuée avant la prochaine lecture.
Difficultés rencontrées
Au début, j’ai été surpris de constater que, dans mon montage, l’obscurité produisait une valeur élevée, tandis qu’une forte luminosité donnait une valeur plus faible. J’ai également dû comprendre le câblage du capteur et choisir un seuil adapté après plusieurs essais. Ces tests m’ont permis de mieux comprendre comment un capteur, une condition logique et une sortie numérique fonctionnent ensemble pour automatiser une action.


Lien du Devoir:  https://wokwi.com/projects/478025500401416193

