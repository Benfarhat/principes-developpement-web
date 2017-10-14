# Internet et les réseaux en 10 minutes

## Introductions aux réseaux et à l'Internet


### Les réseaux

Un peu comme dans la vraie vie, on ne peut parler d'un réseau d'amis qu'a partir d'au moins deux personnes (qui ont un **lien** d'amitié ou encore un lien professionnel.
Pour les ordinateurs c'est pareil,**il faut au moins deux machines** liées (on dit également **interconnectées**) pour parler de réseau.

> un ordinateur + un ordinateur = 1 réseau

Toujours dans le même cas de figure, si on à deux groupes de personnes (par exemple les parents d'élèves et les enseignants) et qu'ils décident tous ensemble de se donner rendez vous, nous obtenons au final un seul groupe (composé dans le détails de sous groupes comme par exemple celui des femmes, des hommes, des enseignants, des parents, des informaticiens, des gestionnaires, etc...). Dans le domaine des réseaux informatique, si l'on a deux réseaux distincts et qu'on les interconnecte alors on obtient un grand réseau.

> 1 réseau + 1 réseau = 1 réseau.


Un réseau est donc **un ensemble d'ordinateurs interconnectés**. Pour généraliser on préferera parler d'**équipements** qui englobe les les ordinateurs, les serveurs, les imprimantes...

> Aujourd'hui, lorsqu'on parle d'interconnection entre les équipements, on converge vers la technologie IoT "Internet of Things" (ou en français, l'Internet des objets), les objets pouvant être une voiture, un réfigérateur ou encore un téléviseur. Vous comprendrez qu'il ne s'agit pas d'objets simple mais plutôt d'objet intelligent (dit Smart).

### Internet

Mine de rien on se rend compte qu'il existe dans le monde une multitude de réseaux informatiques, on peut imaginer qu'il s'agisse par exemple de:

- réseaux universitaire (interconnectant les universités), 
- réseaux hospitaliers (reliant les hopitaux, les dispensaires et éventuellement les cliniques), 
- réseaux entre les institutions gouvernementales (reliant les département et permettant de mener à bien les missions gouvernementales),
- réseaux inter-agences (interconnectant les agences bancaires, les assurances, les magasins d'une même enseigne)

Il existe un réseau à connaitre, c'est le réseau Estonien appelé "X-Road" qui pour simplifier permet d'interconnecter toutes les institutions d'un pays, publiques et privées (Nous verrons sa particularité plus loin).

Et bien dites vous qu'une grand majorité des réseaux d'un pays sont "connectés" entre eux et que tous les pays le sont également. Ainsi on se retrouve avec le plus grand réseau mondial, qui est la somme de tous les réseau qu'on appelle **le réseau des réseaux** ou encore Internet (avec un **I** majuscule).

> Σ réseaux = Internet 

### Réseaux publiques et réseaux privés.


Au niveau de l'Internet et des réseaux d'un pays, il y a des réseaux qui veulent être vu par les autres, on parle alors de **réseaux publiques**, et il y en a d'autres qui prèfèrent pour des raison de sécurité restez isolés (comme éventuellement les réseaux des agences commerciales, d'assurances ou bancaires), il s'agit alors de **réseaux privés**.

### Utilité des réseaux

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

Si une machine offre un service et consomme également ce service, on parle alors d'un environnement **pair à pair** (**peer-to-peer** ou **P2P** en anglais). 
L'utilisation du partage de fichiers dit **torrent** ou **magnet links** ou de flux multimédia (**streaming**) se base sur la technologie P2P (Exemple des outils de type **bitTorrent**).

Dans ce cas on ne parle plus de client ou de serveur mais de **pair** et de **noeud**.

L'avantage du bittorent est que d'une part tout le monde (les noeuds) est potentiellement un serveur est donc potentiellement une source d'information et d'autre part ce qui est recu provient de plusieurs sources et donc de recevoir (et respectivement d'envoyer) plus rapidement.
