# Tournois - Roadmap

## Phase 1 : Structure de base [BACK]

- [ ] Creer le service tournament (Fastify)
- [ ] Definir les types : Tournament, Match, Player
- [ ] Implémenter createTournament(playerCount: 4 | 8)
- [ ] Generer le bracket initial (arbre binaire)

## Phase 2 : Gestion des joueurs [BACK + FRONT]

- [ ] [FRONT] UI saisie d'alias (chaque joueur entre son pseudo)
- [ ] [BACK] Endpoint POST /tournament/join avec alias
- [ ] [BACK] Valider les alias (uniques, non vides)
- [ ] [BACK] Demarrer le tournoi quand tous les joueurs sont inscrits

## Phase 3 : Bracket [BACK + FRONT]

- [ ] [BACK] Generer les matchs du premier tour (random ou seeded)
- [ ] [FRONT] Afficher le bracket visuel (arbre des matchs)
- [ ] [FRONT] Montrer qui joue contre qui
- [ ] [FRONT] Mettre a jour le bracket apres chaque match

## Phase 4 : Deroulement des matchs [BACK]

- [ ] Annoncer le prochain match (notification aux 2 joueurs)
- [ ] Lancer la partie Pong via le game server existant
- [ ] Recuperer le resultat du match
- [ ] Faire avancer le gagnant dans le bracket
- [ ] Gerer les demi-finales et finale

## Phase 5 : Fin de tournoi [BACK + FRONT]

- [ ] [BACK] Declarer le vainqueur
- [ ] [FRONT] Afficher le classement final (1er, 2e, 3e)
- [ ] [BACK] Sauvegarder les resultats (pour blockchain plus tard)
- [ ] [FRONT] Option "Nouveau tournoi"

