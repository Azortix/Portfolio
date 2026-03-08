## Bonjour et bienvenue!

Vous trouverez ci-dessous des liens et précisions sur différents projets sur lesquels j'ai travaillé.  
N'hésitez pas à y jeter un coup d'œil ! ⚆⚆

## 📜 Sommaire
### 1. [Scripting Project](#scripting)
### 2. [Infrastructure construction](#infra)
### 3. [Homelab](#homelab)

## </> 1. Scripting Project
<span id="scripting"></span>

Vous retrouverez le dépôt de ce projet scripting [ici](https://github.com/Azortix/Scripting-project#)  
Le but étant de développer un **script Bash** qui s'exécute sur un serveur Debian, utilisé pour administrer des machines clientes Ubuntu.  
Un second script, cette fois en **PowerShell**, s'exécutant sur un Windows Server pour administrer des machines clientes Windows.  

Ces scripts permettent d'automatiser une ou plusieurs actions. Ils permettent ainsi un gain de temps conséquent. De plus, de nombreuses fonctionnalités sont incorporées dans les scripts, offrant une multitude de possibilités et sont donc plutôt complets en terme d'administration.  

Ces fonctionnalités correspondent à des actions faites sur les clients, ou bien des informations sur ceux-ci. Elles sont résumées ci dessous :

De la **gestion d'utilisateur**, avec leur création, le changement de mot de passe, l'ajout d'utilisateur à certains groupes.  
De la **gestion de logiciels**, avec l'installation ou désinstallation de logiciels et/ou paquets ainsi qu'obtenir un listing de ceux présents. Mais aussi l'exécution de script à distance.  
De la **gestion de la sécurité**, avec l'activation de parefeu, ou l'ajout de règles spécifiques. Ou encore la gestion des droits de certains utilisateurs sur des dossiers.  
De la **prise d'information du système**, avec les informations de l'utilisation de la RAM, ROM, CPU.  
De la **journalisation** des informations demandées, et des actions faites. Tout en permettant la recherche de celles-ci.  

Ces actions et informations sont possibles via **ssh** avec les credentials demandés en début de script. Evidemment, un déplacement libre à l'intérieur de celui-ci est possible grace aux **menus**.

## 🌐 2. Infrastructure construction
<span id="infra"></span>
Vous retrouverez le dépôt de ce projet de construction d'une infrastructure [ici](https://github.com/Azortix/Infra-construction)  
Ce projet a pour objectif de travailler sur la conception et construction d'une infrastructure réseau pour une entreprise fictive en partant du tout début.  
Durant trois mois, plusieurs serveurs et services ont été mis en place sur un **serveur Proxmox**.

En commançant par la construction d'un domaine **Active Directory**, avec les services de **DHCP**, **DNS**. L'implémentation via script des utilisateurs dans l'AD.  
La mise en place de **GPO** de sécurité ou standard. Des dossiers partagés avec la gestion du partage et des règles NTFS de sécurité.  
La gestion d'un **parefeu pfsense** et des règles à mettre en place.  
La mise en place de redondance via **RAID** et de **sauvegardes** des données voulues.  
La création d'un **site web** accessible.
L'implémentation d'un PC d'administration comportant toute une série d'outils de **prise en main à distance** que ce soit en **GUI**, **CLI** par SSH, ou d'autres pour des besoins variés.  
La **supervision** de l'ensemble du parc informatique ainsi que la gestion de **tickets pour du support utilisateur**.  
L'installation de services de communications, que ce soit par **mail** via webmail/client de messagerie ou par **softphone**.
La **gestion des mises à jour** via un serveur WSUS centralisé permettant le téléchargement des mises à jours avant de les tester et de les installer.  
La mise en place d'un **serveur bastion**, ainsi que d'un **VPN** point-to-point et site-to-site.  
En faisant des **audits** et les **correctifs** nécessaires.  

Ce projet m'a permis de me familiariser avec Proxmox, et surtout de profiter d'une mise en situation concrète enrichissante, avec les installations et configurations de tous ces services. Composant une architecture complète et sécurisée de plusieurs machines virtuelles et conteneurs.



## 🖥️ 3. Homelab
<span id="homelab"></span>
Je monte un homelab complet me permettant d'utiliser des outils divers, de m'amuser, et de continuer de découvrir un tas de nouveaux outils.  

J'utilise l'hyperviseur Proxmox VE qui me permet de créer des VM et LXC selon mes envies.  
Voici les différents dépots des documentations du projet global :  

### 🤖 3.1 Home Assistant
Durant ce projet, je me suis interessé à Home Assistant. Il s'agit d'une plateforme open-source de domotique qui permet de contrôler, centraliser et automatiser les appareils d’une maison intelligente.

Compatible avec de nombreux appareils et ecosystèmes. Tout se fait localement, sans dépendance au cloud.

Le dépôt propose une approche complète :

**Déploiement** : Guides d'installation manuelle et automatisée par script.  
**Sécurisation** : Gestion des accès et chiffrement.  
**Continuité de service** : Mise en place d'une stratégie de sauvegarde hebdomadaire automatisée et externalisée.  
**Automatisation** : Création de scénarios pour le confort et une meilleure gestion énergétique.  
Au-delà de la maîtrise de l'écosystème IoT, ce projet développe ma capacité à architecturer une solution robuste et sécurisée.  

L'accès au dépôt se fait [ici](github.com/Azortix/Home_Assistant_OS).
