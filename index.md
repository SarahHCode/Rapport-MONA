|[Rapports hebdomadaires](#rapports-hebdomadaires)|[Rapport final](#rapport-final))|
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
J'ai finalement fini de lire Vue.JS sur w3schools. Je vais maintenant apprendre Ionic Framework sur [le site web de documentation d'Ionic Framework](https://ionicframework.com/docs/) et avec les vidéos YouTube afin de pouvoir comprendre le code de mona-mobile.

Il faut d'ailleurs que je lise [la documentation de l'API de mona-serveur](https://github.com/MaisonMONA/mona-server/wiki/Auth-API-Endpoints) pour comprendre l'issue de messages d'erreurs à améliorer.



## <a name="rapport-final"></a>Rapport final:
À venir...