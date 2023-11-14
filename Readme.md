<!DOCTYPE html>
<hmtl lang="en">
<head>
   <title>  Exercice 1 </title>
</head>

<body>
    <h1><u> Exercice 01 </u></h1>
    <h4> Novembre 13, 2023 </h4>
    <h2> Situation Probleme: </h2>
    <p> Après la numérisation du journal de presse écrite grâce aux solutions que vous avez apportées
dans le projet 1, l'entreprise a connu une très forte hausse du nombre de ses utilisateurs. Après
avoir effectué une enquête, il est apparu que les utilisateurs se plaignent de petits bugs,
notamment la taille de certains textes qui sont très peu lisibles, ainsi que la taille des images
que vous avez insérées. Le journal vous a contacté pour remédier à ce problème en créant une
version 2 de ce projet répondant aux attentes des utilisateurs. Vu les délais très courts pour
cela, vous demandez l'aide d'un autre développeur pour vous aider à finaliser cette version le
plus tôt possible. Le journal vous demande également d'inclure : </p>

<h3> Questions </h3>
    <ol>
       <li> Quel est l’outil qui vous permettra de versionner votre code <li>
        <b> Reponse:</b> </br>
        L'outil GIt nous permettra de versionner notre code.
        <li> Quel est l’outil qui vous permettra de collaborer avec le second développeur </li>
        <b> Reponse:</b> </br>
        L'outil Github nous permettra de collaborer avec le second développeur
        <li> Définir les termes suivant : VCS , GIT , GITHUB </li>
        <b> Reponse:</b> </br>
        VCS (Version Control System) : Un système de contrôle de version est un outil utilisé par les développeurs pour enregistrer et gérer les modifications apportées au code source d'un projet logiciel. <br>
        Git : Git est un système de contrôle de version distribué très populaire. C'est un logiciel qui permet aux développeurs de gérer et de suivre les modifications apportées à leur code source. 
        GitHub : GitHub est une plateforme d'hébergement de code basée sur Git. C'est un service en ligne qui permet aux développeurs de stocker leurs dépôts Git et de collaborer sur des projets logiciels.
        <li> Quelle est la difference entre Git et Github </li> 
        <b> Reponse:</b> </br>
        Git est l'outil de contrôle de version lui-même, qui fonctionne localement sur l'ordinateur du développeur, tandis que GitHub est une plateforme en ligne qui utilise Git pour héberger et faciliter la collaboration sur des projets logiciels.
        <li> Pourquoi un vcs est un outil indispensable pour le développeur </li>
        <b> Reponse:</b> </br>
         Un VCS (Version Control System) est un outil indispensable pour les développeurs car il permet de gérer les versions du code source. Il offre plusieurs avantages clés :
       <ul>
       <li> <b>Historique des modifications </b>: Un VCS enregistre chaque modification apportée au code, ce qui permet aux développeurs de suivre l'évolution du projet et de revenir facilement à des versions précédentes si nécessaire. </li>
       <li> <b>Collaboration simplifiée </b>: Un VCS facilite la collaboration entre plusieurs développeurs en permettant à chacun de travailler sur des branches séparées, de fusionner les modifications et de résoudre les conflits éventuels. <li>
       <li></b> Résolution des problèmes </b>: Lorsqu'un problème survient, un VCS permet de trouver la source du problème en analysant les modifications apportées au code et en identifiant les causes potentielles. </li>
       <li> <b>Expérimentation et exploration </b>: Avec un VCS, les développeurs peuvent créer des branches pour expérimenter de nouvelles fonctionnalités ou des modifications sans affecter la branche principale du projet. </li>
       </ul>
       <li> Définir SSH et dire à quoi il sert </li>
       <b> Reponse:</b> </br>
        SSH est un protocole de communication sécurisé qui permet de controller à distance des systèmes informatiques de manière sécurisée et de configurer les serveurs.
       <li> Quel sont les clés utilisés en SSH  </li>
       <b> Reponse:</b> </br>
       En SSH (Secure Shell), il existe deux types de clés utilisées pour établir une connexion sécurisée :
       <ul> 
       <li>la clé privées et </li> 
       <li>la clé publique.  </li>
       </ul>
       <li> Expliquer le processus de connexion à Github en utilisant le SSH </li>
       <b> Reponse:</b> </br>
       <b>Génération des clés SSH </b>: Tout d'abord, vous devez générer une paire de clés SSH sur votre ordinateur local. Cela se fait généralement à l'aide de la commande ssh-keygen dans votre terminal. La commande générera une clé privée et une clé publique.
       <b>Ajout de la clé publique à votre compte GitHub </b>: Une fois que vous avez généré vos clés SSH, vous devez ajouter la clé publique à votre compte GitHub. Pour cela, accédez aux paramètres de votre compte GitHub, puis à la section "Clés SSH". Cliquez sur "Ajouter une clé SSH" et collez votre clé publique dans le champ prévu à cet effet.
      <li> Quelle est la difference entre le Local repository et le Remote repository </li>
      <b> Reponse:</b> </br>
      le local repository est la copie du projet sur l'ordinateur local du développeur, où il effectue ses modifications et ses opérations locales, tandis que le remote repository est la copie du projet sur un serveur distant, utilisé pour la collaboration, le partage et la synchronisation du code entre les membres de l'équipe.
      </ol>
       <!-- Paritie Exercice pratique -->
      <hr>
      <h2> Exercice Pratique 1 : </h2>
      <ol>
      <li> A quoi sert les commandes suivantes : 
      <ul>
      <li> <b> git init : </b> Cette commande est utilisée pour initialiser un nouveau référentiel Git local dans un répertoire</li>
      <li> <b> git clone: </b> Cette commande est utilisée pour créer une copie locale d'un Git remote repository. </li>
      <li> <b> git push:  </b> Cette commande est utilisée pour envoyer vos modifications locales vers un Git remote repositoty. </li>
      </ul>
      </ol>  
</body>

</html>