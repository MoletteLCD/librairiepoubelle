<h1 align="center">  Librairie Poubelle </h1>

<h2 align="center">  Document regroupant différentes ressources informatiques, et d'autres sujets à venir. </h2>

<h2 align="center">  Base de la Logique et Algorithmique </h2>

*[Disclaimer]* *Document non exhaustif, écrit sur un coup de tête, veuillez excuser les erreurs, je rajouterais une bibliographie en français et anglais pour ceux qui souhaitent creuser.*

### **Ce document n'est pas une roadmap pour devenir développeur web, système etc.. c'est une entrée dans le monde de la programmation.**

## [Debutant]

<b> Logique Formelle </b> 

<i> Table de Vérité et équivalence logique </i>

<p align="center"> <img src="https://i.ytimg.com/vi/twD3hsB_Zl0/sddefault.jpg"/> </p>

<i> Logique Propositionnelle utilisée en Algorithmique </i>

<p align="center"> <img src="https://slideplayer.fr/slide/13671425/84/images/7/Connaissances+et+Raisonnement.jpg" width="1000" height="500"/></p>
                                                                                             

**Playlist Grafikart Algorithmique: https://www.youtube.com/watch?v=fgcGdkhtUcE&list=PLU1uhUPH-DQDup76tvg6XnRjkR719AaFA**

* Cours d'Algorithme : https://openclassrooms.com/fr/courses/4366701-decouvrez-le-fonctionnement-des-algorithmes

## Partie Web

### Base de la programmation avec le langage Python:

* APPRENDRE PYTHON : TUTO COMPLET DÉBUTANT https://www.youtube.com/watch?v=LamjAFnybo0

* APPRENDRE PYTHON : LES ALGORITHMES [TUTO PROGRAMMATION DÉBUTANT] https://www.youtube.com/watch?v=dcSmvs6wadg

* Apprenez les bases du langage Python https://openclassrooms.com/fr/courses/7168871-apprenez-les-bases-du-langage-python

* Apprenez la programmation orientée objet avec Python https://openclassrooms.com/fr/courses/7150616-apprenez-la-programmation-orientee-objet-avec-python

* Documentation officielle Python : https://docs.python.org/fr/3/

### Web, HTML/CSS/JS - HTTP

*Comprendre et connaître HTTP, c'est comprendre comment le web fonctionne, comment les sites interagissent, l'architecture serveur/client*

#### Modèle OSI ou TCP/IP pour Open Systems Interconnection | Transport Control Protocol / Internet Protocol


<p align="center"> <img src="https://linux-note.com/wp-content/uploads/2014/11/modele-osi-vs-tcp.png"/> </p>



**Le modèle OSI (anciennenement TCP/IP) est le modèle standard d'interconnection entre les systèmes, il est à la base du fonctionnement dans l'architecture Serveur/Client qui est utilisée sur le Web, il se décline ainsi:**

- 7. Application (Navigateur)
- 6. Présentation
- 5. Session
- 4. Transport (*Protocole TCP (mode connecté, quand je contacte un serveur) Protocole UDP (quand je stream une vidéo (ne donnez plus votre argent à Netflix))*
- 3. Réseau (*Adresse IP, divisée en classes A/B/C/D/E,chez nous elles sont en 192.168.x.x/24 en général)* 
- 2. Liaison de données (*Adresse Mac, ici sont échangées des Trames)*
- 1. Physique (*Carte Wi-Fi physique (électronique), câble réseau, Puce 4G/5G, Fibre Optique)*

*Guide Mozilla* 

* HTTP https://developer.mozilla.org/fr/docs/Web/HTTP
* HTML https://developer.mozilla.org/fr/docs/Web/HTML
* CSS https://developer.mozilla.org/fr/docs/Web/CSS
* JavaScript https://developer.mozilla.org/fr/docs/Web/JavaScript

*Cours vidéo*

HTML/CSS : 
* Partie 1 https://www.youtube.com/watch?v=8FqZZrbnwkM&t=8s
* Partie 2 https://www.youtube.com/watch?v=HN4-7k0zC-Y
* Partie 3 https://www.youtube.com/watch?v=RUFK0mT0q2E

JavaScript : https://www.youtube.com/watch?v=UEHyHxqbtyg

HTTP : https://www.youtube.com/watch?v=sz3gXm5v_G0

Django Web Framework : https://www.youtube.com/watch?v=Bn0k9DDYBZM 
- Framework définition: https://www.journaldunet.fr/web-tech/dictionnaire-du-webmastering/1203355-framework/

#### Architecture Serveur/Client


<p align="center"> <img src="https://romainlebreton.github.io/ProgWeb-CoteServeur/assets/ClientServeur.png"/> </p>


#### Anatomie d'une Requête/Reponse en Architecture S/C


<p align="center"> <img src="https://ars.els-cdn.com/content/image/3-s2.0-B9781597499613000030-f03-08-9781597499613.jpg"/> <p>


Une requête se compose de drapeau (flags) suivants :

- SYN
- SYN/ACK
- ACK

SYN - SYN/ACK - ACK : Permet au client d'initier la connexion, le serveur lui retourne (SYN/ACK) une initiation de connexion, tout en validant qu'il accepte la requête initiale (SYN) du client, le client lui valide la demande du serveur (ACK), et la connexion est établie, ceci est le 3 Way Handshake ou la poignée de main en 3 modes.
  


## Partie Système

### Anatomie d'un système d'exploitation (Operating System)

<p align="center"> <img src="http://www.courstechinfo.be/OS/Images/StructureEnCouches_001.gif"/> </p>

- Matériel (Hardware) : Processeur, Mémoire vive (Random Access Memory), Disque Dur (Hard Drive Disk / Solid State Drive)
- Système d'exploitation : Logiciel permettant à l'utilisateur d'interagir avec le matériel, exemple avec le Processeur à qui j'envoie des commandes via un langage de programmation, pour qu'il execute des opérations.
- Applications : Navigateur Web (Google Chrome), Suite Office Microsoft etc...

Cette représentation imagée, est appellée abstraction, pour une meilleure compréhension du fonctionnement de l'ordinateur, bien évidémment on ne vous demande pas d'être un mécano pour conduire votre bolide !



## Les Langages

### Langages dit Compilés

#### Rust

### Langages dit Interprétés

#### Python

## Cours Programmation Système

#### Langage C : Pile, Tas, Pointeurs (Stack, Heap, Pointers)

*En général, les Pointeurs, la Pile/Tas, sont les notions les plus difficiles à cerner, mais lorsque vous les avez acquises, vous débloquez la compréhension de votre machine, son fonctionnement en mémoire et donc vous possédez une meilleure manière de rendre le programme performant.*

- Pile, Tas (Stack, Heap) et Pointeurs - Programmation en C https://youtu.be/xClAutDf6jE

