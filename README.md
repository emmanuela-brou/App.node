DESCRIPTION 
    Il s'agit d'un programme réalisé avec JavaScript et exécuté dans Node.js
Ce programme consiste à convertir en nombre une chaîne de caractère,tout en insérant un nombre dans le terminal Node.js.

TECHNOLOGIES UTILISEES 
    pour ce programme, nous avaons utilisé :
- JavaScript pour la saisir du code
- Node.js pour l'exécution du code
- Readline qui est un module de Node.js qui sert à poser une question puis à attendre une reponse ecrite par l'utilisateur. 

DEROULEMENT 
    le programme suit la logique suivante :
- Importation du module readline de Node.js pour permettre au programme de lire ce que l'utilisateur écrit dans le terminal ;
- Création de l'interface rl qui va permettre de recevoir ce que l'utilisateur saisi (input), et d'afficher des informations dans le terminal (output) ;
- Poser une question à l'utilisateur avec la commande [rl.question ("entrer un nombre :", (answer) => )] et attendre sa reponse. NB : answer est une variable qui recevra la reponse donnée tout d'abord en chaîne de valeur ;
- Convertir la reponse en nombre : la chaîne de valeur est par la suite convertir en véritable nombre grâce à la commande [const number = Number(answer);].
- Affiche du résultat : la commande console.log() permet d'afficher un message dans le terminal.
- Fermeture de l'interface : on saisi la commande [rl.close] pour dire que le code est terminé, alors qu'il ferme l'interface readline.

OBJECTIF 
    l'objectif de cet exercice est de se familiariser avec le package, le module readline et de savoir convertir une chaîne de valeur en nombre réel.



