## Mathieu Timmerman,
### Passionné d'informatique, je suis diplômé de l'ENSICAEN (Caen, France), école d'ingénierie avec une spécialisation en informatique en double diplôme avec l'UQAC pour une maîtrise en informatique (option jeux vidéo).
### Je suis enthousiasmé par le développement informatique, j'aime apprendre plus dans ce domaine que ce soit la mise en place d'interfaces graphiques, de logiciels, travailler sur le développement de gameplay dans le domaine de simulations interactives. J'ai travaillé dans de nombreux langages et frameworks, comme les langages C++, C, C# principalement, des langages de script comme Python (NumPy, Matplotlib, ...), le framework Qt pour les interfaces d'applications bureautiques et Web.
### J'aime aussi répondre aux attentes d'un utilisateur pour savoir ce qu'il veut avant même qu'il me le disent et rendre son expérience plus simple et rapide d'utilisation.

##### Si vous voulez me contacter, vous pouvez envoyer un mail à cette adresse : *timmer[dot]mathieu[at]gmail[dot]com*

## Mes projets
- [Jeu des reines (**démo en ligne**) - 2025](#jeu-des-reines-démo-en-ligne---2025)
- [Application AR pour l'apprentissage de la langue des signes - 2024](#application-ar-pour-lapprentissage-de-la-langue-des-signes---2024)
- [Jeu sérieux (Serious game) - 2024](#jeu-sérieux-serious-game---2024)

# Jeu des reines (démo en ligne) - 2025

Je travaille actuellement sur un projet personnel en utilisant le framework Qt et le langage C++, pour améliorer mes compétences dans ce domaine et confirmer mes acquis.
Ce projet est fonctionnel sur navigateur, si vous voulez le tester dès maintenant vous pouvez cliquer sur ce lien ici : https://maththree.github.io/MathThree/queens_game.html

Ce projet est toujours en cours d'évolution, il n'a donc pas encore toutes les fonctionnalités voulues.

Cette application disponible en ligne et également en tant qu'application bureautique permet de jouer au jeu des reines, jeu de logique à un joueur.

Dans ce jeu, vous disposez d'une grille de taille NxN avec N zones, vous devez placer N reines sans qu'aucune reine soit en conflit avec une autre.
Deux reines sont en conflit si elles sont dans la même zone, la même ligne, la même colonne et/ou en contact direct (cases adjacentes et en diagonale).

Pour vous aider, vous pouvez placer un point dans les cases qui selon vous ne devraient pas avoir de reine.
Dans les paramètres, il est possible d'activer l'aide qui permet de placer automatiquement des points dès que vous placez une reine dans une case (selon les règles de conflit énoncées précédemment).

De plus, vous pouvez changer de niveaux ainsi que le thème d'affichage parmi les choix disponibles.

Vous pouvez retrouver l'ensemble du code source de mon projet sur Github : https://github.com/MathThree/queens_game

Il a été créé avec Qt 5.12 et passé sur Qt 6.9 pour accéder à la compilation WebAssembly qui me permet de vous proposer une version en ligne.

Différentes fonctionnalités seront mises en place dans l'avenir comme la possibilité de vider la grille ainsi que de pouvoir annuler et/ou rétablir une action, la possibilité de créer ses propres grilles depuis l'interface.

### [Testez-le dès maintenant !](https://maththree.github.io/MathThree/queens_game.html)

# Application AR pour l'apprentissage de la langue des signes - 2024

Ce projet développé sur Unity (C#) dans une équipe de 5 personnes, propose une application AR (Réalité Augmentée) pour l'apprentissage de la langue des signes. Le but était de travailler en AR, nous avons donc porté notre attention sur la reconnaissance gestuelle.

Dans un premier temps, nous devions répondre à la problématique de reconnaissance gestuelle et de comment détecter un signe.
Ensuite, après avoir trouvé une solution, nous avons travaillé en parallèle sur la mise en place de niveaux pour apprendre la langue des signes, en gardant pour objectif d'être simple d'utilisation et ludique.
Dans notre prototype, nous avions mis en place l'enseignement de l'alphabet de la langue des signes française (LSF).

Le plus grand challenge dans ce projet était l'utilisation de casques VR, qui nous permettaient seulement de voir le dos de la main, donc la reconnaissance des signes n'était pas toujours évidente car les doigts pouvaient être cachés.
Nous avions aussi la chance d'avoir une personne sourde dans notre équipe pour nous expliquer comment la langue des signes fonctionne.

J'ai apprécié le travail effectué pour mettre en place les niveaux de l'application, le fait de chercher et trouver la meilleure façon pour mettre en place nos idées.

<p align="center">
  <img src="https://github.com/user-attachments/assets/42204ac0-2af7-4feb-a3a8-7f86a9e216a7" alt="Capture d'écran 2024-08-18 174321" width="500">
</p>
<p align="center">
  <em>Exemple de niveau dans lequel aucun signe n'est attendu, juste une explication sur le fonctionnement de l'application.</em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/ec68ffcf-6ab3-44d2-af8c-5adee3456618" alt="Capture d'écran 2024-08-18 174126" width="500">
</p>
<p align="center">
  <em>Exemple de niveau dans lequel l'utilisateur doit signer la lettre A (LSF).</em>
</p>

# Jeu sérieux (Serious game) - 2024

Ce projet nommé *FarmLife* a été développé en équipe de 4 sur Unreal Engine (Blueprints et C++). Ce jeu sérieux apporte des connaissances sur la permaculture, le but étant de faire découvrir et partager quelques informations sur ce domaine.

Dans ce jeu, le joueur peut planter des graines de différents légumes et fruits sur différentes cases. Chaque plante apporte des points, le joueur doit donc atteindre le meilleur score en se servant des principes de la permaculture.

Nous avons développé la logique des plantes et des relations qu'elles peuvent avoir entre elles.

J'ai principalement travaillé sur les systèmes de menu principal et pause. J'ai également géré le système de sauvegarde et le tutoriel en début de jeu qui est particulièrement important pour un jeu sérieux (serious game).

Vous pouvez retrouver la vidéo de démonstration du jeu ici : https://drive.google.com/file/d/1e87CB4bOnXGxp8pcAktCF0vC4OBKJQoj/view?usp=sharing
