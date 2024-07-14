|[Rapports hebdomadaires](#rapports-hebdomadaires)|[Rapport final](#rapport-final)|
---
![Mona logo](Mona-Logo.svg)
# **Été 2024** - Sarah Heng

*Présentation du projet:* Application mobile permettant de découvrir l’art public et de prendre des photos et de critiquer. Je participe dans le développement mobile de l’application tandis que ma camarade s’occupe du développement serveur. Je m’ajoute à l’équipe dans le cadre du projet informatique IFT3150.

Les langages utilisés sont Vue.JS, HTML, JavaScript, Framework Ionic et TypeScript. J'utiliserai VSCode, WebStorm, Postman ainsi que le terminal de l'ordi. Je dois utiliser un MacBook fourni par l'organisme afin de pouvoir déployer pour iOS.

Les objectifs sont que 
- [ ] Je dois me familiariser avec le code et apprendre les nouveaux langages en premier. 
- [ ] Et ensuite, programmer et faire de la documentation en participant à la mise à jour de l'interface dans l'application mobile.

Mon professeur superviseur est Guy Lapalme.

Le projet s'étale du 1er mai au 25 août 2024.
Me familiariser avec le code et apprendre de nouveaux langages devrait prendre un mois et quelques semaines et le restant du temps servira à participer à la mise à jour de l'interface dans l'application mobile.

## <a name="rapports-hebdomadaires"></a>Rapports hebdomadaires:

### 01/05-08/05 - Semaine 1
J'ai assisté à une réunion virtuelle d'introduction avec Lena et Guy Lapalme dans laquelle on n'a pas encore assigné les rôles de développement web versus développement mobile, mais on a reçu des consignes sur quoi faire comme utiliser l'application MONA par soi-même et regarder les sites web des anciens étudiants ayant participé au projet. Ensuite, j'ai participé à une rencontre avec Kim, Corélie et les 3 autres étudiantes en histoire de l’art. J'ai appris sur le projet et le but du petit organisme un peu. J'ai fait une rencontre avec Kim pour faire le setup sur MacBook, car pour développer pour IOS, il est nécessaire d'avoir un MacBook, ce qui est nouveau pour moi, étant habituée avec Windows. Cela me fait découvrir l'environnement Apple.

### 09/05-16/05 - Semaine 2
J’ai lu les business objectives sur Miro pour la nouvelle interface à développer pour la rencontre avec la designer UI/UX Barbara. Je me suis aussi un peu familiarisée avec la nouvelle interface sur Figma.
J’ai essayé d’exécuter la configuration pour le projet affichée sur la page GitHub, mais il y a des problèmes d’accès administrateur sur l'ordinateur alors j’ai demandé à Kim.
J'ai lu la [documentation du GitHub de mona-mobile](https://github.com/MaisonMONA/mona-mobile/wiki).

### 17/05-22/05 - Semaine 3
J’ai des difficultés avec l’installation de dépendances pour le code mona-mobile.
Je viens de voir que c’est TypeScript qui est utilisé et non JavaScript, alors je me donne le but d’apprendre TypeScript. Je suis en train d’apprendre Vue.JS qui est utilisé dans le code avec lequel je dois travailler.

J’ai pris un rendez-vous avec Kim pour continuer l’installation et nous avons réussi. Il fallait installer HomeBrew, Java 17 (solution que Kim avait trouvé sur Internet) et exécuter les commandes de configuration sur le README de la page GitHub mona-mobile. Finalement, l’émulateur marche et je peux me mettre à coder/me familiariser avec le code.

Je re-essaie par moi-même et je tombe encore sur des problèmes pour le démarrage de l’application, l’émulateur Android qui était coincé sur la page de démarrage. Malgré cela, j’ai trouvé une manière de pouvoir voir le résultat du code afin d’apprendre avec le code Vue.js et Ionic Framework, ainsi que TypeScript inclu.

Finalement, j’ai repris un rendez-vous avec Kim et elle m'a expliqué qu'il fallait juste supprimer l’émulateur dans Android Studio et retélécharger, car il y a des bugs parfois.

Je me familiarise avec le code et j’essaie de résoudre un issue pour débutants.

Avec ces problèmes rencontrés cette semaine, j'apprends que l'on peut chercher dans Internet pour trouver des solutions à des problèmes que d'autres utilisateurs ont pu rencontrer. J'ai aussi appris un peu comment setup un nouvel ordi puisque le MacBook était complètement nouveau, rien n'était installé. 

D'ailleurs, <u>en plus d'apprendre Vue.JS, Kim m'a dite qu'il est important d'apprendre le diagramme de cycles de Vue.JS 'composition' et d'apprendre Ionic Framework et de comprendre ses presets (semblables à Bootstrap)</u>, car c'est utilisé dans le projet. 

### 23/05-29/05 - Semaine 4
Le 23 mai, on a fait une rencontre avec Lena et Corélie pour partager ce qu’on a fait jusqu'à présent. Lena nous a dites que ça prend du temps de se familiariser avec le code au début, alors, je prévois que c'est cela qui m'attend. 

J’ai envie d’apprendre en expérimentant avec le code, mais j’ai peur de faire des erreurs dans le code. Alors, j’ai dupliqué la branche sur laquelle je travaille, mais je rencontre un problème: en faisant des changements, en changeant de branches dans l’éditeur, je vois que le changement affecte les autres branches, ce que je ne veux pas.
Sur la branche test, j’ai alors écrit "test" à côté d’"Inscription" sur la page Register et commit pour voir quel sera le résultat. En vérifiant entre les différentes branches, je vois que les autres branches ne sont pas affectées. Alors, c’est bon, je sais que les modifications dans la branche test n’affectent pas les autres branches, du moins, après commit.
En faisant des changements dans la branche test et en essayant de changer de branche encore, je reçois un message d’avertissement de WebStorm que mes changements pourraient être overwritten. Je demande à ChatGPT de m’aider à comprendre le message et savoir quoi faire ensuite. Je sais maintenant que je peux faire ‘git stash’ pour sauvegarder mes modifications dans une branche et changer à une autre branche.
Je vois encore que les changements dans la branche test n’affectent pas les autres branches.

Avec ce problème rencontré, j'ai appris plus sur Git.

J’apprends comment faire un site web sur GitHub Pages cette semaine en apprenant Markdown comme Lena nous a montrées lors de la rencontre. Je regarde des vidéos sur Markdown et je lis dans Internet comment l'utiliser. Je continue aussi à apprendre [Vue.JS sur w3school](https://www.w3schools.com/vue/).

J'ai fait une rencontre avec Kim pour demander comment fonctionnent les messages d'erreurs sur la page d'inscription (qui est le problème de débutant que j'ai décidé de prendre) et elle m'a parlé de l'API du serveur MONA et de Postman permettant de comprendre l'API. Je compte donc apprendre à utiliser Postman. J'ai appris que les appels API ont rapport avec le serveur MONA alors il faudra que je lise la [documentation de mona-serveur sur GitHub](https://github.com/MaisonMONA/mona-server/wiki/Auth-API-Endpoints).

<u>D'ailleurs, lors de la rencontre du 23 mai, Lena m'a dite qu'il sera important d'observer les utilisateurs lors des activités de médiation afin de voir comment ils utilisent l'application mobile afin de l'améliorer.</u>

Cette semaine, j'ai appris comment faire un site web sur GitHub Pages avec Markdown.

### 30/05-05/06 - Semaine 5
J'ai finalement fini de lire Vue.JS sur w3schools en "option" au lieu de "composition", mais Kim a dit que c'est correct aussi, car "option" est plus beginner-friendly. Je vais maintenant apprendre Ionic Framework sur [le site web de documentation d'Ionic Framework](https://ionicframework.com/docs/) et avec les vidéos YouTube afin de pouvoir comprendre le code de mona-mobile.

Il faut d'ailleurs que je lise [la documentation de l'API de mona-serveur](https://github.com/MaisonMONA/mona-server/wiki/Auth-API-Endpoints) pour comprendre l'issue de messages d'erreurs à améliorer.

### 06/06-12/06 - Semaine 6
En faisant un tutoriel d'Ionic Framework, je vois qu'il a du TypeScript, alors, <u>je décide d'apprendre TypeScript sur YouTube et w3schools</u>, mais en regardant un tutoriel de TypeScript sur YouTube, je vois qu'il faut savoir JavaScript, donc, <u>je décide de me rafraîchir sur JavaScript et HTML</u> puisque ça fait un bout que je les ai utilisés.

### 13/06-19/06 - Semaine 7
J'ai fini le tutoriel de HTML dans w3schools, mais en parlant avec Lena et Kim un peu, je devrais plutôt apprendre en explorant le code plutôt que lire la documentation des langages.

J'ai fini 3 issues en plongeant dans le code. Soit de changer les messages d'erreurs en ion-toast, corriger le bug de titre dans la liste qui se colle à droite et ajouter un enter key listener. J'ai aussi fait deux revues de code que Kim m'a assignées.
Cela m'a permis d'apprendre comment débugger et m'a permise de mieux comprendre le code.

### 20/06-26/06 - Semaine 8
Cette semaine, j'ai commencé la nouvelle interface, plus précisément, la barre de navigation et j'ai résolu d'autres issues. Je me suis attaquée à l'issue de d'augmenter la taille du pin sélectionné sur la carte, ce qui requiert de comprendre un peu plus OpenLayers, d'explorer le code dans Utils.ts et de comprendre le code de MapContainer.

Je pense que mes objectifs pour ce projet dorénavant sera d'implémenter la partie Home de la nouvelle interface, d'autres parties de l'interface aussi j'espère et de résoudre plusieurs issues. 

### 27/06-03/07 - Semaine 9

Cette semaine, j’ai fait une rencontre avec Guy Lapalme, Lena et l’équipe informatique. Il faudra que je planifie le temps pour le reste du projet informatique qui finira le 21 août et il me faudra faire le rapport final. Nous pensions que nous serions prêts pour un release, mais ce n’est pas le cas à cause de bug d’images qui ne se montrent pas à cause de mise à jours de dépendances.

Parmi les issues sur lesquels j’ai travaillés, le rayon d’approximation de la localisation de l’utilisateur, le rayon ne montrait pas réalistement l’approximation, alors, j’ai corrigé pour que le rayon d’approximation soit montré réalistement en mètres sur la carte. Ainsi, cet issue est corrigé. J’ai aussi fini la nouvelle barre de navigation et son apparence, mais je veux m’attarder plus dessus pour comprendre plus CSS et faire qu’elle corresponde plus au nouveau design de l’interface. Il faudra ensuite que je continue le développement de la nouvelle interface.

Il faudra que je prenne connaissance et que j’apprenne à faire des tests pour l’interface soit Cypress et Vitest.

J'ai fini de faire correspondre l'apparence de la barre de navigation au nouveau design de l'interface. J'ai lu de la documentation de CSS me semblant pertinant pour réaliser l'apparence de la barre de navigation et cela m'a faite comprendre mieux CSS comme box model et flex box.

### 04/07-10/07 - Semaine 10

J'ai fait que le bouton pour recentrer change d'apparence selon comment l'écran est centré par rapport à l'emplacement de l'utilisateur. Ce fut compliqué de trouver comment détecter lorsque l'écran était décentré, mais j'ai trouvé en lisant la documentation d'OpenLayers pour comprendre mieux et en trouvant des réponses sur StackOverflow. 
Puis, je me demandais quoi mettre pour déclencher la fonction qui change l'apparence du bouton recentrer. Au début, j'avais mis que la fonction déclenche chaque fois que View change (soit que le viewport change sur la carte), mais cela affectait beaucoup la performance. Alors, j'ai réfléchi à comment l'apparence du bouton changerait normalement dans d'autres interfaces comme Google Maps par exemple et j'ai finalement décidé de mettre comme déclencheur de la fonction du bouton recenter lorsque l'utilisateur finit un mouvement sur la carte, ce qui est mieux pour l'expérience utilisateur et pour la performance puisque la fonction s'active moins souvent inutilement genre.

J'ai commencé à travailler sur la page Profil, mais en regardant le design de la nouvelle interface, je ne suis pas sûre de ce qu'on veut garder ou non, alors, je traiterai de cela lors du meeting avec Barbara le lundi 8 juillet. Lena m'a demandée de faire des captures d'écrans de la carte avec des zooms différents et des tailles de pins différents puisqu'on trouvait que les pins étaient trop grands, alors j'ai fait cela.

J'ai eu un meeting avec Barbara, Lena et Kim dans lequel nous faisons le point sur ce qu'on veut dans l'interface. Je m'attaquerai donc à faire la modale sur la carte des découvertes à proximité.

Oh non, je viens de merge incorrectement deux branches à la branche de développement principale dev et il y a des bugs qui font que l'application ne fonctionne pas bien là. J'ai essayé de faire une nouvelle branche à partir de dev, de revert la branche au commit juste avant les merges des deux branches et j'ai essayé de re-merge une branche à la fois, mais cela ne marche pas. Heureusement, en faisant des recherches, j'ai vu qu'on peut revert les merges, ce que j'ai fait, mais, dans mon cas, il faut que j'attende la validation de Kim.
De cette expérience, j'ai appris comment retourner à une ancienne version du code sur Git et comment merge localement.

### 11/07-17/07 - Semaine 11

J'ai fait deux déploiements cette semaine, un sur iOS et l'autre sur Android.

J'essaie de faire la modale de découvertes à proximité sur la carte, mais il me reste des pépins après avoir réglé d'autres problèmes tels que la modale empêche par défaut d'interagir avec les éléments en arrière-plan (la solution était de mettre :backdrop-breakpoint="1" pour que le backdrop n'apparaisse jamais). Un des pépins qui reste est, qu'une fois ouverte, la modale reste sur l'écran même après avoir changé d'onglet de navigation. Je me demande si utiliser un ion-accordion conviendrait mieux à la situation.


## <a name="rapport-final"></a>Rapport final:
À venir...
