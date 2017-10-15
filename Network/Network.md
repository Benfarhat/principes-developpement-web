# Internet et les réseaux en 10 minutes

## Introductions aux réseaux et à l'Internet

### Définition des réseaux

Un peu comme dans le monde réel, on ne peut pas parler d'un réseau ou d'un groupe d'amis qu'à partir d'au moins deux personnes (qui ont un **lien** d'amitié ou encore un lien professionnel.
En informatique c'est pareil,**il faut au moins deux machines** liées (on dit également **interconnectées**) pour avoir un réseau.

> **un ordinateur + un ordinateur = 1 réseau**

Toujours dans le même cas de figure, si on à deux groupes de personnes et qu'ils décident tous ensemble de se donner rendez vous au même endroit, nous obtenons au final un seul groupe (composé dans le détails de sous groupes comme par exemple celui des femmes, des hommes, des enseignants, des parents, des informaticiens, des gestionnaires, etc...). 
Dans le domaine des réseaux informatique, si l'on a deux réseaux distincts et qu'on les interconnecte alors on obtient un plus grand réseau.

> **1 réseau + 1 réseau = 1 réseau**

Dans la définition du réseau, **un ensemble d'ordinateurs interconnectés** peut être généralisé en préférant le terme d'**équipements** interconnectés ou de **noeuds**.
Un noeud englobe les éléments suivant: 

- les **stations de travail** (PC, MAC, ...)
- les **serveurs** (qui ont plus de puissance que les stations de travail)
- les **équipements réseaux** (qui sont des équipements pouvant être contactés sur le réseau sans passer par un intermédiaire)


### Qu'est ce que l'Internet

Mine de rien on se rend compte qu'il existe dans le monde une multitude de réseaux informatiques, on peut imaginer qu'il s'agisse par exemple de:

- réseaux universitaire (interconnectant les universités et éventuellement les centres de recherches), 
- réseaux hospitalier (reliant les hopitaux, les dispensaires et également les cliniques), 
- réseaux entre les institutions gouvernementales (reliant les département et permettant de mener à bien les missions gouvernementales),
- réseaux inter-agences (interconnectant les agences bancaires, les assurances, les magasins d'une même enseigne)

Il existe un réseau à connaitre, c'est le réseau Estonien appelé "X-Road" qui pour simplifier permet d'interconnecter toutes les institutions d'un pays, publiques et privées (Nous verrons sa particularité plus loin).

Et bien dites vous qu'une grand majorité des réseaux d'un pays sont "connectés" entre eux et que tous les pays le sont également. Ainsi on se retrouve avec le plus grand réseau mondial, qui est la somme de tous les réseau qu'on appelle **le réseau des réseaux** ou encore Internet (avec un **I** majuscule).

> **Σ réseaux = Internet** 


### Réseaux publiques et réseaux privés.


Au niveau des gestionnaires des réseaux d'un pays, il y en a qui veulent que leurs réseaux soient vu par les autres et donc soient connectés à l'Internet, on parle alors de **réseaux publiques**, et il y en a d'autres qui prèfèrent pour des raison de sécurité restez isolés (comme éventuellement les réseaux des agences commerciales, d'assurances ou bancaires), on parle alors de **réseaux privés**.

> Lorsqu'on parle de connecter un réseau à l'Internet, cela ne veut pas forcément dire que tout sera publique. Au point de jonction entre le réseau d'un organisme et Internet, se trouve un ensemble d'équipements de sécurité et de technologies qui permettront de dire qui fait quoi et qui accède à quoi.

#### Le FSI ou FAI

L'organisme qui s'occupe de connecter un réseau à l'Internet (un réseau qui sera dit publique) est appelé FSI (Fournisseur de Service Internet) ou FAI (Fournisseur d'Accès à l'Internet).
 Pour la petite histoire, du fait de l'explosion de la bulle Internet, de nombreux FAI on fait faillite et ont dut s'adapter pour survivre, ainsi il n'est pas rare de voir des rachats de ces organismes par des entreprises de télécommunications ou encore une restructuration interne pour étendre ces activités et rentabiliser leurs projets.


### Internet Intranet et Extranet

- Internet est comme nous l'avons vu le réseau mondial.
- Intranet est un réseau à porté local réservé à une zone bien délimité (un étage, une entreprise, une maison)
- Extranet est l'interconnexion d'un réseaux externe à un réseau interne.

### Cloud

Pour faire simple, dans chaque organisme, il y a en principe un serveur qui peut contenir des applications, des données ou des services.
Le problème avec cette façon de faire est qu'il a du mal à gérer la mobilité.

Si un organisme met ses serveurs, son stockage et ses ressources informatiques  et Services à dispositions sur Internet alors l'organisme à fait un premier par fair le Cloud (nuage en français) ou plus communément appelé le **Cloud Computing**.

> Le cloud vous permet par exemple d'avoir un espace de stockage pour toutes vos photos, vos vidéos et d'y avoir accès partout dans le monde. Mieux encore, si votre ordinateur tombe en panne, il suffit d'en prendre un autre et de le connecter au cloud pour y avoir accès.
 
Dans la réalité, ce sont de grandes sociétés qui louent leur ressources informatiques sur Internet, ce qui est plus rentable aux yeux des sociétés et des entreprises qui n'auront plus à gérer la partie achat, configuration, maintenance, connexion et extension, ainsi que la partie recrutement et formation du personnel necessaire. Aujourd'hui il suffit de souscrire à un des 3 modèles de services du cloud computing:

- **IaaS (Infrastructure as a Service)**: Si vous avez besoin d'un serveur, le cloud computing vous en fournit en quelques minutes sans se soucier si ce dernier tombera en panne.
- **PaaS (Plateform as a Service)**: Le cloud computing vous permet d'avoir à disposition la plateforme de votre choix, Cela peut être un système d'exploitation (le logiciel qui fait fonctionné les machines) ou alors un environnement de programmation ou encore de traitement vidéo.
- **Saas (Software as a Service)**: Le cloud vous propose l'utilisation d'un service à distance comme par exemple un éditeur de texte.



## Classification des réseaux

Il y a plusieurs type de classification, présentons ici les plus connus


### Selon le type de support
Il y a deux types de connexions, les connexions **filaires** et les connexions **sans fils**

#### Connexions filaires

Les connexions filaires se font via:

- Un **cable coaxial**
- Une **paire torsadée** (ou paire téléphonique)
- Une **fibre Optique**
La difference entre ces 3 supports de transmissions réside dans la fiabilité (perte d'information), la vitesse (le débit), la distance et le coût.

#### Connexions sans fils

Les connexions sans-fil se font via:
L'infra-rouge
Le bluetooth
Le Wifi
Le Wimax
La transmission satellite

### Selon la distance

Pour faire simple:

- Si ca ne dépasse pas les quelques mètres on parle de **PAN (Personal Area Network)**, Comme par exemple la connexion bluetooth entre deux smartphones, ...
- Si c'est dans une zone géographique très limité (comme pour l'Intranet) on parle de réseau **LAN (Locale Area Network)**,
- Si le réseau s'étend à uquelques dizaines de kilomètres, on parle de réseau **MAN (Metropolitan Area Network)**,
- Si le réseau s'étend à un pays ou plus encore on parle de **WAN (Wide Area Network)** ou réseau étendue, Notez qu'Internet est un WAN.

### Selon son schéma

Il s'agit ici de la topologie des réseaux, ou comment les équipements sont connecté

#### La connection en bus

Il y a un seul support de communication que tous les équipements se partage, il est simple d'utilisation mais très peu fiable car si le support de communication est endommagés, l'ensemble du réseau est paralysé.

#### La connexion en anneau (Token Ring)

Sachez qu'elle existe dans les réseaux de types IBM, tous les ordinateurs forment un anneau qui peut faire plusieurs kilomètres, et seul celui qui à un jeton peut communiquer. Par analogie, les rond-point automobile sont plus fluide que les carrefours.

#### La connexion en étoile

Tous les équipements ont un cable dédié qui les connectent à un élement centrale (un peu comme les prises électriques des maisons qui sont connecté à un élément central qui est en principe le compteur électrique).
Dans cette topologie si un cable se déchire, une seule machine est en panne.Par contre si l'élement centrale qui interconnecte tous les équipements tombe en panne, le réseau entier est paralysé


#### La connexion en maille

Chaque ordinateur a un cable qui va vers les autres ordinateurs, ainsi si un cable est coupé, un ordinateur ne peut plus commmunique avec un seul ordinateur et continuera à émettre et recevoir avec le reste.
Le problème de cette topologie est très couteuse. si par exemple vous faites partie d'un réseau de 100 ordinateurs, sachez qu'il faudrait 99 cables qui sont connectés à votre machine.
On utilise plutot cette topologie à plus grand échelle pour interconnecter les réseaux entre eux.





### Le Cloud c'est quoi?

### Nouveaux concepts d'interconnexion des objets

De nos jours, deux nouveaux concepts font parler d'eux et doivent être connu si ce n'est pour la culture générale:
l'IoT (Internet of things) et le M2M (Machine to Machine)

Nous sommes tous connectés, il suffit de voir autour de nous, chacun a son smartphone, sa tablette ou encore sa montre dite connecté, qu'il consulte régulièrement. La technologie veut que nous allions au dela et que tous les objets de la vie puissent être connectés, cela est valable également dans le domaine industriel ou chaque objet doit avoir un capteur ou senseur et puissent envoyer les données récupérées pour qu'elles soient traitées, analysées et améliore les décisions du futurs. La façon avec laquelle un accès distant sera proposé à ces objets ou capteurs fait la différence entre l'IoT et le M2M

L'IoT repose sur une identification de chaque objet via l'EPC (Electronic Product Code) et le RFID (Méthode de récupération et mémorisation des données à distances) en envoyant cela sur une plateforme Cloud.

La technologies M2M fonctionne sur un espace plus réduite via un réseau de télécommunication mobile (GPRS / 2.5G ou UMTS / 3G)



Depuis quelques années, lorsqu'on parle d'interconnection entre les équipements, on introduit la notion d'**IoT "Internet of Things"** (ou en français, l'Internet des objets) pour décrire une notion ambitieuse et futuriste qui veut que tous les objets de la vie comme par exemple une voiture, un réfigérateur, une montre, ou encore un téléviseur puissent être connectés. 
> Vous comprendrez qu'il ne s'agit pas d'objets simple mais plutôt d'objet intelligent (dit Smart). 
> 
> Il est bon de savoir que connecter des objets est bien plus complexe que la connexion entre stations de travail et est souvent liées à des technologies tels que le RFID (méthode de mémorisation et récupération des données à distances) ou l'EPC (un moyen d'identification unique des objets). 





## Besoin des réseaux

A présent nous savons que les équipements sont connectés mais pourquoi?
Il y a une seule grande raison: **LE PARTAGE**.
il peut s'agir:

- du partage de **ressources**
- du partage de **données**


#### Partage de ressources

Le partage des ressources permet l'utilisation d'un périphérique entre plusieurs machines. Par exemple, le fait d'utiliser une imprimante pour un service financier et comptable est un partage de ressources. Le routeur/modem internet permet de partager une connexion internet entre plusieurs équipements (ordinateurs de bureau, portatifs, smartphones et tablettes, console de jeux, recepteurs/box, etc...).

il y a également le partage des ressources interne d'une machine comme par exemple le processeur. 
Ce type de partage appelé "**calcul partagé**" est très utilisé lorsqu'une tache très "lourde" demanderais trop de temps pour être executé par un seul ordinateur (ou un seul serveur). On peut citer comme exemple:

- le cas du rendu graphique et vidéo dans le monde du cinéma, la **grappe de serveurs** qui  distribue le temps et la puissance de calcul est appelé "**Ferme de Rendu**" (ou Render Farm en anglais).
- en cryptanalyse, le "crack" d'un mot de passe (trouver un mot de passe) par brute force (tester toute les combinaisons possibles) qui demande plusieurs années pour tester la totalité des combinaisons peut être accélérer en  distribuant les tests (noté qu'il y a 5.4 x 10<sup>12</sup> possibilités de trouvés un mot de passe de 9 lettres en minuscules et 1.0 x 10<sup>14</sup> possibilités si le mot de passe contient des chiffres).
- l'analyse de données scientifiques telles que les données astronomiques recu par une sonde spatial ou climatologiques pour les prédictions de trajet des cyclones, ou encore physique, nanotechnologique ou biologiques. Dans ce cas on utilise la puissance de calcul proposée par des bénévoles qui ont juste à installer un programme tel que BOINC.

#### Partage de données

Pour différencier avec le précédent partage, on va dire que dans ce cas de figure, ce qui est partagé n'est pas physiquement palpable. Le partage de données permettrais par exemple pour un bureau d'avocats d'avoir sur un seul serveur l'ensemble des textes legislatifs et réglementaires dont ils ont besoin. Pas besoin de faire une copie sur chaque ordinateur et le plus est qu'ils ont juste a mettre à jour seulement le serveur de données sans se soucier des autres équipements de l'organisation.

### Hautes disponibilités

Le partages des ressources et des données est cruciale au sein de l'entreprise, une panne informatique est toujours mal vue et est généralement préjudiciable pour l'organisme. Pour éviter cela, plusieurs techniques permettent d'améliorer les disponibilité informatique comme la **redondance** des équipements critique, le **clustering**, l'utilisation de disque en **RAID**.

#### Les clusters

On dédouble généralement les équipements critique d'un organisme. Cette redondance est intelligente (il ne s'agit pas de simple copie).  On parle de **cluster**, l'avantage des clusters est que si une des machines du cluster tomber en panne, les utilisateurs ont toujours accès aux informations ou ressources via les machines restante. Notez que les équipements en cluster partage un certains nombre d'information.

> Si une entreprise à besoin de récupérer les réclamations des clients par téléphone, alors le fait de rajouter un autre numéro de téléphone n'est pas souvent la meilleure solution. L'idéale est d'avoir des lignes dites groupés. En appelant la hotline de l'entreprise, nous pouvons tomber sur l'un des X agents qui ont le même numéro de téléphone, et si jamais un téléphone tombe en panne, le service de la hotline n'en sera pas perturbé. C'est le même principe pour les **cluster**.

Un cas évident de mise en clustering est l'hébergement d'un site web. Il faut noter qu'en interne les équipements qui font du clustering ont plusieurs processeurs (si un processeur tombe en panne, l'équipement continue à fonctionner), plusieurs disques mais également plusieurs sources d'alimentation électrique.

> Il y a deux modes de fonctionnement en cluster:
> - actif-actif: les deux machines travaillent en même temps
> - actif-passif: une machine travail alors que la seconde reste en pose jusqu'a ce que la première machine ne répond plus.


***Attention:** On trouve parfois la notion de **Stack** (ou stacking) au niveau des équipements réseaux. Deux élements en stack ne veulent pas dire en cluster. Le stack est une sorte de partage des taches qui bien sur sont indépendantes. Si un équipement ne répond plus, seul la motier des taches sont bloqués.* 
> *Dans un magasin, il arrive qu'une ou plusieurs caisses tombent en panne. Dans le cas du fonctionnement en cluster, les clients seraient redirigé vers l'une des caisses fonctionnelles, dans le cas des équipements stacks, les clients doivent attendre que la caisse redeviennent fonctionnelle.
C'est un moindre mal ou parfois on préfère une paralysie partielle des infrastructures qu'une paralysie totale.*

### Environnements des machines du réseau

#### Client-serveur et de protocoles de communication

##### Serveur

Si une machine partage une ressources ou une donnée, alors cette machine à le rôle de **serveur**. 

> Dans un café celui qui prend les commandes et fournit ce qui a été demandé est appelé serveur.

##### Protocole de communication

Tout ce qui est partagé se fait dans la règle de l'art en utilisant une norme ou un protocole de communication, dans ce cas le partage d'un élement est appelé **service**.

> Un protocole de communication est un ensemble de règles à suivre pour bénéficier (on dit également consommer) d'un service. Par exemple si votre argent est à la banque, il ne suffit pas d'aller au domicile du banquier pour prélever votre argent, ou alors de le contacter par téléphone ....
> il faut suivre les règles de communication (le protocole) qui dit par exemple qu'on doit se rendre à une agence bancaire, pendant les horaires de travail, respecter la file d'attente et avoir les pièces d'identité nécessaire pour s'authentifier. Le même protocole permet également de dire qu'il est possible de prélever son argent en se rendant un à distributeur automatique de billet munie de sa carte bancaire et de son compte, etc...

##### Client

Les machines qui consommeront les services proposé par le serveur sont appelé **client**

> Un client n'est pas souvent un humain, il peut s'agir d'un petit logiciel appelé **agent** ou **bot** (contraction de robot). 
> Par exemple une entreprise qui est doté d'une passerelle dite antivirale (la machine qui récupère et partage les mises à jour des antivirus) doit installer sur chaque machine un **agent** qui va s'occuper de demander et d'installer les mises à jour de manière transparente sans géner l'utilisateur des taches répétitives.

Il existe plusieurs types de client que l'on peut résumer comme suit

- le **client léger** ou tout le travail est effectuer par le serveur, accéder à son compte de messagerie via un navigateur est une utilisation classique d'un client léger (on parle dans ce cas d'un **client web**),
- le **client lourd** ou le travail est partagé entre le serveur et le client, utiliser outlook, thunderbird ou lotus notes, c'est utiliser des client lourd, une partie du traitement se fait au niveau du serveur et une autre au niveau du client, notez que l'utilisation d'un client lourd est partiellement possible lorsque le serveur est en maintenance (on peut continuer à lire ces mails, les classers, créer de nouveaux modèles, ...),
- le **client riche** est un compromis entre les deux précédents types, puisqu'il s'agit d'un client léger plus évolué. Les entreprises qui ont besoin de statistiques journalièrez peuvent faire développer un client riche qui communique avec le serveur (qui a les données) pour recevoir les  informations du serveur dans un format standardisé  afin d'offrir via un environnement (ou **IHM interface homme machine** ) enrichi qui utilise l'**environnement d'exécution Java (JRE)**, les outils necessaires pour visualiser les informations du serveur (via une datavisualisation qui se fera sur le client).

##### Client et serveur en même temps

Si une machine offre un service et consomme également ce service, on parle alors d'un environnement d'**égal à égal** ou **pair à pair** (**peer-to-peer** ou **P2P** en anglais). 
L'utilisation du partage de fichiers dit **torrent** ou **magnet links** ou de flux multimédia (**streaming**) se base sur la technologie P2P (Exemple des outils de type **bitTorrent**).

Dans ce cas on ne parle plus de client ou de serveur mais de **pair** et de **noeud**.

L'avantage du bittorent est que d'une part tout le monde (les noeuds) est potentiellement un serveur est donc potentiellement une source d'information et d'autre part ce qui est recu provient de plusieurs sources et donc de recevoir (et respectivement d'envoyer) plus rapidement.

## Architecture des clients-serveurs

### Quelques définitions

- Un **tier** veut dire "zone" ou "niveau".
- Une **requête** est une demande du client vers le serveur
- Une **réponse** est le résultat qu'envoi un serveur suite à une demande

### Architecture 2-tier

L'architecture 2 tier (ou à deux niveaux) est un architecture ou une partie  offrent des services (comprenez donc qu'elle est constitué d'un serveur) et une autre demande et consomme les services du serveur à savoir les clients.
On appelle également cette architecture l'**architecture client-serveur**
> Un site web est un exemple simple d'architecture à deux niveaux. le premier étant celui des clients (ou des internautes) et le second celui du serveur.

### Architecture 3-tier

L'architecture 3-tier est comme pour l'architecture 2-tier auquel nous avons rajouté une seconde zone de serveurs pour lui affecter quelques taches qui aurait pu être attribué à la premier zone.
> Un serveur web offre plusieurs service dont:
> 
> - le service web qui lis les requête des utilisateurs et envoie des réponses (les pages web) aux demandeurs c'est la **couche présentation**, 
> - le service qui s'occupe des données, qu'on appelle le gestionnaire de base de donnée (**SGBD**) a pour tache d'enregistrer les nouvelles pages du sites, d'extraire le contenu des pages demandés, de faire de la recherche dans ces pages ou encore des calculs. C'est la couche accès aux données
> Imaginez qu'un site soit consulter par plusieurs centaines de personnes au même moment et hors "heures de pointes", alors la partie dite base de donnée sera affecté à un autre serveur dans le 3ème niveau.

### Architecture d'égal à égal

Comme vu précédemment, il s'agit du cas ou tous les équipements peuvent être client ou serveur. Il n'y a donc pas de serveur dédié et surtout pas de point critique. L'inconvénient qu'on lui attribue est la difficulté de l'administrer.

## Diffusion et transmission des informations

### Selon le sens

Dans le cas d'un communication **duplex** (dans les deux sens) il y a deux type de diffusions;

Communication **full-duplex**: la communication peut se faire en même temps
Communication **half-duplex**: la communication se fait à l'alternat. (comme dans lors d'une communication téléphonique, l'**appelant** et l'**appelé** ne parle jamais en même temps).

> Un connexion full duplex est bien sur plus rapide, imaginer un route avec 10 voitures d'un coté et 10 voitures de l'autres. Si la route est à deux voies, alors les véhicules peuvent circuler simplement sans s'arrêter
> Par contre s'il s'agit d'une vois unique alors un véhivule ne peut s'engager sur la voie que si elle est vide, sous risque de **collisions**.

### Selon le destinataire

- Si l'on envoi un message à un seul destinataire on parle de transmission **unicast**,
- Si le message est pour un groupe de destinataire on parle alors de transmission **multicast**,
- Si l'on envoi le message au plus proche d'un groupe ou le plus "efficace" on parle de transmission **anycast**
- Et enfin si le message est destiné à tout le monde, il s'agit d'une transmission **broadcast**.