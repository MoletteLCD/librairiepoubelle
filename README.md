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
___

### Base de la programmation avec le langage Python:
___

* APPRENDRE PYTHON : TUTO COMPLET DÉBUTANT https://www.youtube.com/watch?v=LamjAFnybo0

* APPRENDRE PYTHON : LES ALGORITHMES [TUTO PROGRAMMATION DÉBUTANT] https://www.youtube.com/watch?v=dcSmvs6wadg

* Apprenez les bases du langage Python https://openclassrooms.com/fr/courses/7168871-apprenez-les-bases-du-langage-python

* Apprenez la programmation orientée objet avec Python https://openclassrooms.com/fr/courses/7150616-apprenez-la-programmation-orientee-objet-avec-python

* Documentation officielle Python : https://docs.python.org/fr/3/

### Web, HTML/CSS/JS - HTTP
___

*Comprendre et connaître HTTP, c'est comprendre comment le web fonctionne, comment les sites interagissent, l'architecture serveur/client*

#### Modèle OSI ou TCP/IP pour Open Systems Interconnection | Transport Control Protocol / Internet Protocol
___

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
___

<p align="center"> <img src="https://romainlebreton.github.io/ProgWeb-CoteServeur/assets/ClientServeur.png"/> </p>


#### Anatomie d'une Requête/Reponse en Architecture S/C
___

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

___

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

<h3 align="center"> Le Compilateur </h3>



Ressources:

- https://alibabatech.medium.com/gcc-vs-clang-llvm-an-in-depth-comparison-of-c-c-compilers-899ede2be378 *GCC vs CLang - LLVM : une comparaison en profondeurs des compilateurs C/C++ 


<h4 align="center"> Fondamentaux du Système d'Exploitation : Noyau </h4>

<p align="center"><img src="https://img.phonandroid.com/2016/05/kernel-explication-schema.jpg"></p>

- Le Kernel ou Noyau est un logiciel faisant la jonction entre le matériel et l'utilisateur, c'est lui qui gère les échanges entre par exemple les données que le navigateur envoie vers le serveur à travers le modèle OSI, la couche applicative 7 demande au Kernel la possibilité d'utiliser la carte réseau située en couche 1.

- C'est donc le logiciel dont la conception demande plus de précision, ce dernier est écrit en langages compilés pour des questions de performance et de sécurité.

- Le Kernel possède son propre mode, appelé Kernel Mode.

Dans la section linux, j'expliquerais le rôle du kernel mode plus en détail, par ailleurs toute explication sur le fonctionnement de l'OS sera basée sur Linux, car il est Open Source et bien détaillé, un ouvrage sur le sujet : *How Linux Works 3d Ed, No Starch Press.

##### Kernel 
___

Quelques informations à ce sujet:

1. le kernel possède en mémoire son propre espace, différent de l'espace utilisateur : kernel space / user space.
2. le kernel space possède des permissions propres au kernel, une permission est une sorte de liberté spéciale, par exemple en user space je peux exécuter du code mais qui n'aura pas un grand impact en général (sauf cas particuliers), hors en kernel space un code exécuté peut avoir un impact critique car les permissions ne sont pas les mêmes.
3. le kernel orchestre le tout, il dirige le processeur vers les prochaines tâches à exécuter, ce dernier gère:
  - Les appels Système (System Calls)
  - Gestion de Processus (Process Management)
  - Gestion de Mémoire (Memory Management)
  - Pilotes matériels
4. les processus communiquement avec le kernel via les appels systèmes pour pouvoir utiliser les ressources matérielles.
5. le kernel lui dans sa gestion des processus communique au processeur les tâches à exécuter, et le processeur alloue (prête) un temps d'exécution, un cpu time, qu'on appelle slice aussi et le CPU bascule entre chacun des processus (context switching) pour les faire s'exécuter simultanément pour nous, mais comme l'exécution est très rapide, tout cela est transparent pour nous. 

Le chapitre 1 de **How Linux Works** l'explicite et le détaille. 


<h3 align="center"> Le Processeur CPU </h3>


- Qu'est-ce qu'un processeur
- Architecture CPU


#### Qu'est-ce qu'un processeur

Cours: https://www.courstechinfo.be/Techno/CPU.html

Un processeur ou CPU (Central Processing Unit) est une puce, possédant des transistors, un élement électronique capable d'un courant faible 0/5v pour faire passer/couper le courant lors des instructions, le 0 correspond au 0 en binaire et le 5 au 1 en binaire, la fréquence du processeur est mesurée en Hertz, Giga Hertz (GHz), celle-ci mesure le nombre d'opérations qu'il peut traiter, par ailleurs l'architecture du processeur fait sa force.

#### Architecture CPU

L'architecture du CPU est liée à ce qu'on appelle les jeux d'instructions, une instruction est une commande passée et exécutée/interprétée par le CPU pour faire très simple. On distingue deux type d'architecture:

- CISC : Complex Instruction Set Computer
- RISC : Reduced Instruction Set Computer

L'architecture CISC permet d'avoir un jeu d'instruction large, l'architecture RISC elle permet d'avoir un jeu réduit. 

L'architecture CISC est la plus répandue, néanmoins elle pose des problèmes de rapidité d'exécution, tandis que la RISC palie au problème de rapidité. On retrouve l'archtecture RISC chez Apple M1 la dernière puce, dans les raspberry Pi aussi.

<p align="center"><img src="http://www.dugied.net/hardware2007/sites/mon/img/schema%20archi.gif"></p>

Informations:

- Comment Apple a détruit Intel ? : https://www.youtube.com/watch?v=cLVuk14ivD4
- Introduction aux architecteurs des processeurs : https://www.youtube.com/watch?v=s1XGQJq_lCs
- Cours présentation processeurs : http://www.dugied.net/hardware2007/sites/mon/cpu/2.html


Par ailleurs, les processeurs ont aussi d'autres particularités, notamment les bits les processeurs dit x64 et x86, qui représentent les bits utilisés, x86 pour du 32 bit, x64 pour du 64 bit, c'est le nombre de bit utilisé par instructions. Concernant les instructions RISC, elles sont présentes sur les processeurs d'architecture ARM (Raspberry Pi par exemple) https://fr.wikipedia.org/wiki/Architecture_ARM . 

*Vous retrouverez plus en détail dans la partie anglais, des cours vidéos, des ouvrages sur cela.*

<h2 align="center"> Cours Programmation Système </h2>



*Disclaimer: n'étant pas programmeur pro, veuillez excuser mes erreurs si j'en commet, je suis novice encore sur ce sujet !*


<h3 align="center"> Points communs entre langages </h3>


Le point commun à tout les langages c'est : le langage ! Plus sérieusement, la syntaxe est la base commune et les instructions passées au CPU à exécuter, le socle commun est donc traduire pour avoir un résultat.

Quelques mots clés à retenir sous forme de tableau :

|Type                   | mot clé       |
|-----------------------|--------------:|
|chaine de caractère    | str           |
|nombre entier          | int (integer) |
|nombre à virgule       | float         |
|booléen                | True/False    |

Exemple en code Python:

```
chaineDeCaractere = 'Je suis une chaine de caractère'
nombreEntier = 1
nombreVirgule = 1.0
booleanTrue = True

# affiche le str
print(type(chaineDeCaractere))

# affiche le int
print(type(nombreEntier))

# affiche le float
print(type(nombreVirgule))

# affiche le boolean
print(type(booleanTrue))

```
Résultat:

```
<class 'str'>
<class 'int'>
<class 'float'>
<class 'bool'>

```

D'autre mots clés associés à des notions communes au langages existent comme: 

- variables : var
- constantes : const
- importer : import
- le type : type
- l'affichage : print, printf
- arguments : args

Ceci est une liste non exaustive et il faudra se référer à la documentation et au mots clés des différents langages.

Par ailleurs, il existe ce qu'on appelle des paradigmes (l'utilisation du mot paradigme est reprise des travaux du scientifique Thomas Kuhn dans '*La Structure des Révolutions Scientifiques*' pour viser ce qu'on peut communément appeler une vision des choses) en programmation, nous avons par exemple:

- La programmation fonctionnelle : orientée mathématiques.
- La programmation orientée objet : exemple une voiture est composée de 4 roues, un moteur, un chassis, un pare-brise, des essuie glace, celle-ci constitue un objet de classe voiture, composée de propriétés (moteur, roues etc..) appelée attributs, et de méthodes (accelérer, ralentir etc..).
- La programmation procédurale : utilisation de fonctions données pour telle ou telle tâche. 

La programmation orientée Objet est l'un des paradigme les plus utilisé et le plus commun en programmation.


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
