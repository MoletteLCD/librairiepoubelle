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
* Introduction à l'algorithmique : Cours et exercices corrigés, 2e édition : https://fr1lib.org/book/668241/f51a1a?dsource=recommend
* Algorithmes : notions de base https://fr1lib.org/book/2649347/fd9684?dsource=recommend

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

Bibliographie:
-  Architecture de l'ordinateur : Portes logiques, circuits combinatoires, arithmétique binaire, circuits séquentiels et mémoires. Exemple d'architecture https://fr1lib.org/book/1129280/ede356?dsource=recommend (Pour les plus téméraires)


<h2 align="center"> Les Langages </h2>

<h3 align="center"> Langages dit Compilés </h3>

- Les langages dit compilés, sont des langages dit de bas niveau, c'est à dire que ces derniers sont au plus près du processeur si je puis me permettre, un système d'exploitation est écrit (je vous l'ai dis en haut c'est un logiciel) dans un langage bas niveau compilé car il doit interagir avec le matériel via des logiciels appelés pilotes (drivers). Dans la suite j'expliquerais le fonctionnement du système d'exploitation à travers une composante clé appelée Kernel ou Noyau.

- Pour expliquer ce qu'est un langage compilé, parlons langage au sens commun du terme, je vous écris en français, dans une syntaxe française dont vous comprenez la sémantique en français, pour être plus clair moi écrire français et toi lire et comprendre moi français, jusque ici tout est clair, néanmoins pour l'ordinateur ça l'est moins, notre malfrat d'acier, de silice et d'or ne comprend que les 0/1, merci Leibnitz ! Alors comment donc l'ordinateur comprend mon programme écrit pour afficher Hello World ? Il fait de la traduction ou translation binaire, c'est à dire qu'il va prendre le code écrit dans un lanage, le changer en une suite de 0 et de 1 et l'exécuter, c'est à dire interpréter les commandes et donner un résultat. Ne vous inquiétez pas l'ordinateur n'y comprends rien, il n'est pas apte à comprendre la sémantique, mais la syntaxe oui. En image voyons le processus :

<p align="center"> <img src="https://miro.medium.com/max/1230/1*J5fqmdDTjrmZaZO7Ctd6sg.png"> </p>

1. Le préprocesseur permet de rassembler et de comprendre le code utilisé en en-tête avec les #include

``` 
#include <stdio.h>
#include <stdlib.h>

int main() {

  printf("Hello World ! \n");
 }
 
 ```
2. Le compilateur permet de transformer le tout en code assembleur (un autre langage de bas niveau) 
3. L'assembleur collecte le tout et le transforme en code compréhensible pour la machine soit 0/1 (.obj)
4. Le Linker fait les liens entre les librairies statiques .lib et le code en .obj et donne un .exe ou un fichier à lancer.

Parmi les langages dit compilés, on trouve le langage C, C++, Rust (qui est le plus récent).

Exemple de code en rust:
```
// Arrays - Fixed list where elements are the same data types

pub fn run() {

    use std::mem;

    // let numbers: [i32; 5] = [1,2,3,4,5];
    let mut numbers: [i32; 5] = [1,2,3,4,5];
    
    // Re-assign value
    numbers[2] = 20;

    println!("{:?}", numbers); // :? debug pour tout afficher

    // Get single value
    println!("Single value: {}", numbers[0]);

    // Get array length
    println!("Array length: {}", numbers.len());
    
    // Array are stack allocated
    println!("Array occupies {} bytes", mem::size_of_val(&numbers));

    // Get slice
    let slice: &[i32] = &numbers[0..2]; // & > refere à
    println!("Slice: {:?}", slice);


}
```
Lors de la compilation de mon programme des erreurs sont apparues, le compilateur m'en a fait part:

```
[Running] 
error[E0601]: `main` function not found in crate `arrays`
  --> arrays.rs:3:1
   |
3  | / pub fn run() {
4  | |
5  | |     use std::mem;
6  | |
...  |
28 | |
29 | | }
   | |_^ consider adding a `main` function to `arrays.rs`

error: aborting due to previous error

For more information about this error, try `rustc --explain E0601`.

[Done] exited with code=1 in 0.11 seconds
```
Les erreurs du compilateur sont une aubaine, prenez les en considération sans trop devenir fous :-).


<h3 align="center"> Langages dit Interprétés </h3>

- Les langages dit interprétés, sont des langages qui peuvent être exécutés à la volée, c'est à dire qu'ils sont exécutés sans passer par une phase de compilation à la main (en réalité c'est plus complexe, voyez par vous-mêmes), on peut donc les réecrire rapidement et les relancer aussi facilement qu'un allumage de lampe.

- Néanmoins, la réalité est toute autre, le langage interprété passe par une même phase de compilation mais moins compliquée, c'est ce qu'on appelle une machine virtuelle qui va lire le code, l'exécuter et nous donner le résultat, on perd en performance mais on gagne en rapidité.

Python ainsi que Java sont des langages interprétés.

Exemple en Python:

```
from http import HTTPStatus

print(list(HTTPStatus))

[Running] python -u "/"
[<HTTPStatus.CONTINUE: 100>, <HTTPStatus.SWITCHING_PROTOCOLS: 101>, <HTTPStatus.PROCESSING: 102>, <HTTPStatus.OK: 200>, 

```
Le programme m'affiche des valeurs, à savoir les codes HTTP (cf. HTTP avec Mozilla)

En image:

<p align="center"><img src="https://www.guru99.com/images/1/053018_0616_CompilervsI1.png"></p>

<h2 align="center"> Cours Programmation Système </h2>

<h3 align="center"> Langage C </h3>

Cours:

- Apprenez à programmer en C https://openclassrooms.com/fr/courses/19980-apprenez-a-programmer-en-c
- Programmer en Langage C (PDF) : https://fr1lib.org/book/2830378/36f79f
- Algorithmes et Structures de Données Génériques en C (PDF) : https://fr1lib.org/book/703921/b352ef


Cours vidéo:

- Apprendre à programmer en C. https://youtu.be/nZGap0SnVjs
- Playlist Langage C https://www.youtube.com/watch?v=90hGCMC3Chc&list=PLrSOXFDHBtfEh6PCE39HERGgbbaIHhy4j


<h4 align="center"> Langage C : Pile, Tas, Pointeurs (Stack, Heap, Pointers) </h4>

*En général, les Pointeurs, la Pile/Tas, sont les notions les plus difficiles à cerner, mais lorsque vous les avez acquises, vous débloquez la compréhension de votre machine, son fonctionnement en mémoire et donc vous possédez une meilleure manière de rendre le programme performant.*

- Pile, Tas (Stack, Heap) et Pointeurs - Programmation en C https://youtu.be/xClAutDf6jE




<h1 align="center"> Ressources en Anglais </h1>

***Pour cette partie là, il y aura plus amples ressources, car l'abondance en anglais de cours de qualité est magistrale, néanmoins la partie française sera modifiée si de nouvelles trouvailles atterissent et enrichissent le contenu.***
