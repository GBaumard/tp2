# Answers

Nom : BAUMARD
Prénom : Gaëtan

# 1.
Citez deux avantages du PaaS sur le IaaS ?  
* On a pas à gérer l'installation de patchs ou autres sur notre environement lorsque l'on change la version de notre application.
* On a pas à gérer la version ou la montée de version de l'environement sur lequel on travaille.

# 2.
Quelle est la différence entre le PaaS et le Serverless ?  
Pour le PaaS nous avons nos VMs dédiées elle ne sont pas censées disparaitres sans que nous l'ayons demandé. Le Serverless quand à lui propose des machines virtuelles actuellement non utilisées à un prix très attractif cependant si quelqu'un décide de paye plus cher que vous l'utilisation d'une VM il la récupère automatiquement. Donc les Serverless existent pour proposer un service très temporaire (comme un lourd calcul pour un laboratoire de recherche par exemple).

# 3.
Que veut dire Serverless ?  
cela veux dire "sans serveurs" mais en réalité c'est plutôt "sans serveurs attribués" car ce que nous louons est éphémère. mais surtout car ce que nous payons n'est pas un serveur que nous payerions à l'avance mais plutôt des performances que nous payons après utilisation.

# 4.
Citez les trois propriétés désirable du Serverless ?  
* Ephémère, les VMs ne vivent que le temps de délivrer le resultat demandé
* Gestion fine, on ne paye que ce que l'on utilise et le temps que l'on l'utilise
* Piloté par événements

# 5.
Comment s'appelle la plus petite unité de compute déployable en Serverless ?  
On appelle ça une fonction
