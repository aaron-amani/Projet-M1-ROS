# Projet-M1-ROS
Simulations for TurtleBot3

Nous avons choisi de réaliser un robot chercheur de balle de basket avec ROS Kinetic. Passionné tout les deux de basket, une des problématique, quand on joue ou on s'entraîne tout seul sur un terrain, est qu’une fois qu’on réalise un tir, nous somme obligé de la récupérer le ballon par terre, atterri à X position, et revenir à notre position initiale, a contrario de perdre notre feeling sur le tir, qui peu affecté la qualité de l'entraînement. D'où notre idée de faire un robot chercheur de balle, qui détecte le ballon par terre a X position du terrain, évite les obstacle a jusqu'à la destination, récupère la ballon et le dépose devant le joueur.
Nous avons donc découper notre projet en sous objectif car c’est un projet ambitieux:
- Objectif 1 : Faire un robot qui évite les obstacle
- Objectif 2 : Faire un robot qui détecte une balle et qui avance vers lui (objet
sphérique de couleur rouge/orange)
- Objectif 3 : Faire un robot qui récupère une balle à l'aide d’un bras et le dépose à un
endroit
