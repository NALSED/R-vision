## **Cours TSSR 24/25**

#### Sommaire :
##### 1) [Méthodes Agiles](https://github.com/NALSED/R-vision/blob/main/Fichier%20de%20r%C3%A9vision.md#1-m%C3%A9thodes-agiles-) :
 * ##### 1.1 Définition :
 * ##### 1.2 Etapes et Compositions : 
   * ##### 1.2.1  Sprint Backlog.
   * ##### 1.2.2 Sprint planning.
   * ##### 1.2.3 Daily scrum.
   * ##### 1.2.4 Sprint review.
 * ##### 1.3 Rôles et Définitions.
 ##### 2) [Git/Git-Hub](https://github.com/NALSED/R-vision/blob/main/Fichier%20de%20r%C3%A9vision.md#2-gitgit-hub-) : 
   * ##### 2.1 Git :
     * ##### 2.1.1 Dépot Distant.
     * ##### 2.1.2 Branche et Flow. 
     * ##### 2.1.3 Conflit Merge.
     * ##### 2.1.4 Clé SSH.
   * ##### 2.2 Git-Hub :
     * ##### 2.2.1 Clé SSH.
##### 3) [Réseau](https://github.com/NALSED/R-vision/blob/main/Fichier%20de%20r%C3%A9vision.md#2-gitgit-hub-) :
 * ##### 3.1 [Principes des réseaux](https://github.com/NALSED/R-vision/blob/main/Fichier%20de%20r%C3%A9vision.md#31-principes-des-r%C3%A9seaux-) :  
    * ##### 3.1.1 Introduction.
    * ##### 3.1.2 protocole réseau.
    * ##### 3.1.3 Modéle en couche.
    * ##### 3.1.4 Encapsulation.
    * ##### 3.1.5 Modèle OSI.
    * ##### 3.1.6 Modèle TCP\IP.
    * ##### 3.1.7 Matériel d'interconnection.
* ##### 3.2 [Ethernet](https://github.com/NALSED/R-vision/blob/main/Fichier%20de%20r%C3%A9vision.md#31-principes-des-r%C3%A9seaux-) :
   * ##### 3.2.1 Normes et Architecture.
   * ##### 3.2.2 Cablage et équipement.
     * ##### 3.2.2.1 La commutation. 
   * ##### 3.2.3 Adresse Mac.
   * ##### 3.2.4 Trame ethernet.
   * ##### 3.2.5 Protocole CSMA/CD.
   * ##### 3.2.6 Les VLAN.
* ##### 3.3 [IPv4](https://github.com/NALSED/R-vision/blob/main/Fichier%20de%20r%C3%A9vision.md#31-principes-des-r%C3%A9seaux-).
   * ##### 3.3.1 Protocole et Définitions.
   * ##### 3.3.2 Les Adresses.
     * ##### 3.3.2.1 Définitions.
     * ##### 3.3.2.2 CIDR.
     * ##### 3.3.2.3 Adresse réservées.
     * ##### 3.3.2.4 Les Masques.
     * ##### 3.3.2.5 Calculs.
  * ##### 3.3.3 Configurations du réseau :
    * ##### 3.3.3.1 Linux.
    * ##### 3.3.3.2 Microsoft.
  * ##### 3.3.4 Les paquets :
  * ##### 3.3.5 Les Protocoles connexes :

#### 1) Méthodes Agiles 
 * #####  1.1 Définitions
 ##### Création de **cycles répétitif**, ayant pour buts la **réalisations de projets complexes,** en intégrant un procédé **incrémentale**, des différentre étape de la réalisation, des solutions techniques, et des livrables. 
 * ##### 1.2 Etapes et Compositions
   * ##### 1.2.1 Le Product Backlog:
   ######  Il existe pendant **toute la durée du projet** et contient une **liste** de tout les éléments nécessaires à l'amélioration du produit.Ces éléments sont classés par ordre de priorité pour le client,ils évolue quotidiennement. Géré par le **Product Owner**
   * ##### 1.2.2  Sprint Backlog
   ###### Est un  **plan du sprint**, il construit le sprint **planning**, il contient les objectifs du sprint, la liste des éléments du product backlog choisi plan opérationnel pour réussir à finir cette liste pendant le sprint (planning détail technique).(Utilisation du **Definition of Done** niveau de qualité attendu).

   * ##### 1.2.3 Sprint planning
   ###### Planning du sprint, **Objectifs**, **points techniques**, Comment ces détails vont être réalisés.   
   * ##### 1.2.4 Daily scrum
   ###### **Réunions courtes**, Inspecter l'avancement et adapter le plan si besoin,Identifier les problèmes / Proposer des solutions, même heure, même lieu tous les jours.
   * ##### 1.2.5 Sprint review
   **Réunion pour examiner le résultat du sprint**, décider des adaptations nécessaires, ajustement du product backlog 
   * ##### 1.3 Rôles et Définitions
 ######  Un **Scrum master :** facilite l'application de la méthode Scrum, un **Product Owner :** porteur de la vision de la valeur du produit,Des développeurs : équipe pluridisciplinaire en charge de la réalisation du produit.
#### 2) Git/Git-Hub : 
   * ##### 2.1 Git
     * ##### 2.1.1 Dépot Distant
     ###### ((penser à passer en "main" pour pouvoir faire certaine action ( rendre la destination C:, safe aux yeux de git):)) 
    git config --global --add safe.directory C:/
###### Effacer tout dépot précédant 

    git remote rm origin.


 ###### **TOUJOURS ECRIRE APRES /c:**


  1) ###### lande@Admin MINGW64 /c (main) git remote add origin  [REMOTE_URL] : faire le liens entre le dépôt distant aux dépôt local  
  2) ###### lande@Admin MINGW64 /c (main)  : git remote -v ((vérifier le lien le dépôt local et à distance)) 
 3) ###### lande@Admin MINGW64 /c (main)  git clone [REMOTE FILE NAME] : ((clone le fichier depuis GuitHub à Git))
 4) ###### lande@Admin MINGW64 /c/my-awesome-project (main) git pull origin main ((ECRIRE DANS LE FICHIER SOURCE!!!))  clone les modifs
 5) ###### lande@Admin MINGW64 /c/my-awesome-project (main) nano ou echo ["MESSAGE"] > [FILE]
 6) ###### lande@Admin MINGW64 /c/my-awesome-project (main) git add [FILE]
 7) ###### lande@Admin MINGW64 /c/my-awesome-project (main) git commit -m <"NEW MESSAGE">
 8) ###### lande@Admin MINGW64 /c/my-awesome-project (main) git push origin main

 * ##### 2.1.2 Branche et Flow 
   intro: 	après création de différentes branches, on peux visionner l'avancement via Insights puis 	Network en bas à Gauche.


###### ((TOUJOURS ECRIRE DANS LE FICHIER CIBLE!!!!))

###### après avoir clone le commit:
1) ###### lande@Admin MINGW64 ~/git/website-flow (main)  git branch ((donne la branche ou l'on se trouve)) 					2) lande@Admin MINGW64 ~/git/website-flow (main) git branch [NEWBRANCH]
3) ###### lande@Admin MINGW64 ~/git/website-flow (main) git checkout [OTHERBRANCH]
4) ###### Modification via le tuto précédent et push sur GitHub
   * ##### 2.1.3 Conflit Merge
  ###### Quand un conflit apparait entre un dépôt distant et un dépôt local:(( après git pull))
     git pull origin main
###### ((MESSAGE ERREUR)) Le conflits se sont inscrit dans le dossier README
   
>remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 897 bytes | 44.00 KiB/s, done
From github.com:NALSED/A
  branch            main       -> FETCH_HEAD
   56d5465..9d7d130  main       -> origin/main
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.

###### Edition
    nano README.md

> "<<<<<<< HEAD"
		[LOCALE]
		[ici va s'afficher les différences de la branche dans laquelle je me trouve, en l'occurrence local]	
		"======="
		[REMOTE]
		[ici va s'afficher les différences de l'autre branche en l'occurrence le poste sur GitHub] 
		 ">>>>>>> main"

###### Quand le choix est fait supprimer la partie indésirable.
###### **Toujours penser à commit les modifs, sinon probléme de branch et update...**
1) ###### lande@Admin MINGW64 ~/git/A (main) git add README.md		
2) ###### lande@Admin MINGW64 ~/git/A (main) git commit -m "[TEXT]	
3) ###### lande@Admin MINGW64 ~/git/A (main) git pull origin main ((UPDATE LES DEUX VERSION))
4) ###### lande@Admin MINGW64 ~/git/A (main) git push origin main ((C'EST BUENOS!!))

* ##### 2.1.4 Clé SSH.
###### Utiliser gh_2.57.0_windows_amd64 avec le tuto pour créer un clé SSH entre GitHub et Git
 * ##### 2.2 Git-Hub
    * ##### 2.2.1 Clé SSH
     PHOTO
##### 3) Réseau :
 * ##### 3.1 Principes des réseaux :  
    * ##### 3.1.1 Introduction.
 ###### Un **réseau** est un **ensemble d’éléments reliés** les uns aux autres et entre lesquels** circulent des informations**
###### Il est constitué :
###### - De **supports physiques** (câbles) - médium
###### - **D'équipements d'interconnexion**
###### - **D'hôtes** - les ordinateurs qui profitent des services du réseau
##### Différents selon la taille et la portée:
###### - Le PAN (Personal Area Network) → échelle d'une personne
###### - Le LAN (Local Area Network) → échelle d'un bâtiment
###### - Le MAN (Metropolitan Area Network) → échelle d'une ville
###### - Le WAN (Wide Area Network) → échelle pays/continent
###### - Le GAN (Global Area Network) → échelle mond 
 * ##### 3.1.2 protocole réseau.
    * ##### 3.1.3 Modéle en couche.
    * ##### 3.1.4 Encapsulation.
    * ##### 3.1.5 Modèle OSI.
    * ##### 3.1.6 Modèle TCP\IP.
    * ##### 3.1.7 Matériel d'interconnection.
* ##### 3.2 Ethernet :
   * ##### 3.2.1 Normes et Architecture.
   * ##### 3.2.2 Cablage et équipement.
     * ##### 3.2.2.1 La commutation. 
   * ##### 3.2.3 Adresse Mac.
   * ##### 3.2.4 Trame ethernet.
   * ##### 3.2.5 Protocole CSMA/CD.
   * ##### 3.2.6 Les VLAN.
* ##### 3.3 IPv4.
   * ##### 3.3.1 Protocole et Définitions.
   * ##### 3.3.2 Les Adresses.
     * ##### 3.3.2.1 Définitions.
     * ##### 3.3.2.2 CIDR.
     * ##### 3.3.2.3 Adresse réservées.
     * ##### 3.3.2.4 Les Masques.
     * ##### 3.3.2.5 Calculs.
  * ##### 3.3.3 Configurations du réseau :
    * ##### 3.3.3.1 Linux.
    * ##### 3.3.3.2 Microsoft.
  * ##### 3.3.4 Les paquets :
  * ##### 3.3.5 Les Protocoles connexes :





























































 
