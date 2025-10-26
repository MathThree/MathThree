## Mathieu Timmerman,
### Passionné d'informatique, je suis fraîchement diplômé de l'ENSICAEN (Caen, France), école d'ingénierie avec une spécialisation en informatique en double diplôme avec l'UQAC pour une maîtrise en informatique (option jeux vidéo).
### Je suis enthousiamé par le développement informatique, j'aime apprendre plus dans ce domaine que ce soit mettre en place d'interfaces graphiques, de logiciels, travailler sur le développement de gameplay dans le domaine de simulations interactives. J'ai travaillé dans de nombreux langages et framework, comme les langages C++, C, C# principalement, des langages de script comme Python (NumPy, Matplotlib, ...), le framework Qt pour les interfaces d'applications bureautiques et Web.
### J'aime aussi répondre aux attentes d'un utilisateur pour savoir ce qu'il veut avant même qu'il me le disent et rendre son expérience plus simple et rapide d'utilisation.

##### Si vous voulez me contacter, vous pouvez envoyer un mail à cette adresse : *timmer[dot]mathieu[at]gmail[dot]com*

## Mes projets
- [Prototype de TPS - 2024](#prototype-de-tps---2024)
- [Application AR pour l'apprentissage de la langue des signes - 2024](#application-ar-pour-lapprentissage-de-la-langue-des-signes---2024)
- [Jeu d'infiltration - 2024](#jeu-dinfiltration---2024)
- [Jeu sérieux (Serious game) - 2024](#jeu-sérieux-serious-game---2024)

# Prototype de TPS - 2024

Ce projet a été développé sur Unreal Engine (Blueprints et C++) avec une équipe de 4 personnes. Le but était de mettre en place un prototype de jeu de tir à la troisième personne (TPS).
Pour contextualiser, le jeu prend place dans un monde post-apocalyptique, dans lequel le joueur contrôle un personnage féminin depuis une base en Antarctique. Dans cette base, le personnage peut contrôler différents avatars pour mener à bien chaque mission, comme éliminer des ennemis ou libérer des otages.

Nous avons donc travaillé sur la mise en place des actions basiques du personnage principal, il peut donc marcher, courir, se baisser et escalader de petites structures ainsi que l'utilisation d'armes à feu.
En parallèle, nous avons travaillé sur la mise en place d'IA que le joueur doit affronter. Ces IA peuvent tirer, faire des rondes, se mettre à couvert, détecter le joueur, se mettre en alerte et alerter ses alliés.
Finalement, la mise en place de cartes étaient attendue pour avoir un environnement convenu pour le contexte choisi en début de projet.

Dans ce projet, j'étais en charge de la logique IA, j'ai aussi travaillé en duo sur la partie arme, qui concernait le joueur et les IA ennemis.

Ce projet m'a permis d'améliorer considérablement mes compétences en développement d'IA avec l'utilisation de behaviour trees (arbres de comportement).

<p align="center">
  <img src="https://github.com/user-attachments/assets/6b36211f-175e-4c26-bba4-532b1906ff2b" alt="Capture d'écran 2024-08-18 171357" width="500"></p>
<p align="center">
  <em>Dans le menu principal, le joueur peut choisir son personnage et sélectionner son arme et sa tenue, qui affectent ses statistiques.</em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e2ad459e-b1f5-4441-926c-2d9c87ae58d9" alt="Capture d'écran 2024-08-18 172116" width="500">
</p>
<p align="center">
  <em>En jeu, la santé du joueur et ses munitions sont visibles en bas à gauche, ainsi que le statut de la mission en haut à gauche.</em>
</p>

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

# Jeu d'infiltration - 2024

Dans ce projet nommé *Deadly workspace* et développé sur Unreal Engine (Blueprints et C++), j'ai travaillé dans une équipe de 3 personnes sur un jeu à la première personne.
Le contexte du jeu est simple, le joueur (employé de jour) ayant raté l'horaire de fermeture doit sortir de son lieu de travail en allant récupérer la seule clef du bâtiment au dernier étage en passant chaque étage.

La secrétaire propose au joueur de l'aider à récupérer la clef s'il effectue du travail supplémentaire à chaque étage du bâtiment, ce que le joueur accepte.
À chaque étage, le joueur doit effectuer des tâches pour passer au suivant. Les tâches consistent à lancer des téléchargements de données, photocopies et impressions à effectuer.
Le joueur n'étant pas autorisé à être présent la nuit, les employés de nuit qui chercheront à l'attaquer.

L'objectif est donc de ne pas se faire prendre, le joueur peut donc se cacher sous des meubles, faire du bruit pour attirer les autres employés avec les objets de tâche (ordinateurs et imprimantes). Courir est la dernière issue possible.

Dans ce projet, nous voulions donner un thème stressant, en gardant un thème plutôt sombre. Cependant nous avons gardé des lumières à des endroits stratégiques pour indiquer un objectif ainsi qu'au niveau de l'ascenseur pour lui donner un aspect réconfortant.

J'ai travaillé sur la mise en place des IA en utilisant des behaviour trees (arbres de comportement). Pour enrichir le gameplay, je me suis également penché sur l'utilisation de sens, pour que les IA puissent voir et entendre le joueur.
En parallèle, je me suis intéressé aux objets interactifs, comme les objets pour mener à bien les objectifs du joueur ou qui peuvent l'aider comme des appâts, les machines à café pour donner des bonus au joueur et enfin l'ascenseur pour passer à l'étage suivant.

J'étais aussi en charge de l'équipe, cela m'a permis d'améliorer mes compétences en gestion de projet surtout d'un point de vue de gestion d'équipe.

<p align="center">
  <img src="https://github.com/user-attachments/assets/67d4eec6-3ed2-4dea-b675-7d1fe6579d3c" alt="Capture d'écran 2024-08-18 180012" width="500">
</p>
<p align="center">
  <em>Le menu principal du jeu : le joueur est dans l'ascenseur du bâtiment, cela permet de fluidifier le passage du menu au jeu. Le menu pause est aussi dans l'ascenseur.</em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/779cc43e-8069-4e2c-861f-add6232e603f" alt="Capture d'écran 2024-08-18 180532" width="500">
</p>
<p align="center">
  <em>La secrétaire au rez-de-chaussée proposant l'accord au début du jeu.</em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d764badd-0b0c-411a-a023-a81c29ac7907" alt="Capture d'écran 2024-08-18 180724" width="500">
</p>
<p align="center">
  <em>Le joueur utilisant la photocopieuse, tout en pouvant suivre l'avancement de l'objectif.</em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/16397baf-bf0a-4d5e-a783-2e97c7aef88a" alt="Capture d'écran 2024-08-18 181209" width="500">
</p>
<p align="center">
  <em>Le joueur peut se cacher sous les tables et bureaux, pour ne pas se faire détecter par les autres employés.</em>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/ea2e60e7-7b77-40f5-adb7-dec9551ba32a" alt="Capture d'écran 2024-08-18 181440" width="500">
</p>
<p align="center">
  <em>Les employés de nuit peuvent également interagir avec les objets actifs comme la photocopieuse, cela arrête la tâche en cours.</em>
</p>

# Jeu sérieux (Serious game) - 2024

Ce projet nommé *FarmLife* a été développé en équipe de 4 sur Unreal Engine (Blueprints et C++). Ce jeu sérieux apporte des connaissances sur la permaculture, le but étant de faire découvrir et partager quelques informations sur ce domaine.

Dans ce jeu, le joueur peut planter des graines de différents légumes et fruits sur différentes cases. Chaque plante apporte des points, le joueur doit donc atteindre le meilleur score en se servant des principes de la permaculture.

Nous avons développé la logique des plantes et des relations qu'elles peuvent avoir entre elles.

J'ai principalement travaillé sur les systèmes de menu principal et pause. J'ai également géré le système de sauvegarde et le tutoriel en début de jeu qui est particulièrement important pour un jeu sérieux (serious game).

Vous pouvez retrouver la vidéo de démonstration du jeu ici : https://drive.google.com/file/d/1e87CB4bOnXGxp8pcAktCF0vC4OBKJQoj/view?usp=sharing
