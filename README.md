# Games-Python
Ensemble de jeux programmés avec Python

Connect 4:
1. Connect4.py contient le jeu de base où deux joueurs peuvent s'affronter
2. Connect4pygame.py contient ce même format du jeu mais avec une interface graphique réaliste supplémentaire implémentée avec pygame
3. Connect4_RadomAI permet à un joueur de jouer contre l'ordinateur qui joue au hasard avec cette même interface graphique
4. Connect4_AI implémente une intelligence artificielle un peu plus évoluée (défini un score pour chacun de ses coups possibles basé sur la configuration suivante du board : il s'agit d'un minimax de profondeur égale à 1)
5. Connect4_AIMinimax implémente l'algorithme minimax avec un élagage alpha-beta qui accélère le temps d'execution à chaque tour de l'IA
