# Demo-dashboard-java

  >*Chaque développeur réfléchi en premier sur un plan de continuité d'activité ou un plan de reprise d'activité en cas de pannes pour un système d’information mais aussi dans le sens de système de secours et c'est dans ce cadre que nous l'avons instaurez dans votre programme java utilisant mysql comme SGBD.* 

## Pour commencer

Il prend en paramètre les informations qui nous permet de faire une sauvegarde directement d’une interface java et la faire pour de la partie mysql (Base des données) :

### Pré-requis

Les applications nécessaires pour contribuer au dévéloppement de ce projet :

- Netbeans (https://www.oracle.com/technetwork/java/javase/downloads/jdk-netbeans-jsp-3413139-esa.html)
- Xampp (https://www.apachefriends.org/fr/download.html)

### Installation

Les étapes pour installer le programme sont :
1. **Télécharger le dossier**
2. **Importer le projet**
3. **Changer les paramètres de connexion**
4. **Executer le projet**

ET si vous souhaitez constituer un executable par la suite il faut faire le ``clean and build ``

## Mode ligne de commande

La commande ``Execute Commond `` est une  commande du système d'exploitation que vous spécifiez comme argument de la commande, puis affiche la sortie de la commande dans MySQL Shell. C'est généralement une commande qui est utilisé par les personnes qui s'y connaisse bien en informatique.
Comme pour notre cas, faire le backup en mode ligne de commande, on tappe la commande ci dessous en respectant les arguments de ce dernier :

``Execute Commond - C:\xampp\mysql\bin\mysqldump -h localhost --port 3306 -u root --password=MQ4k4z22MhB6vD8GvsrY87du75KiNW --add-drop-database -B hopital -r "D:\hospitalBackupFolder\backup1629034169007.sql``

## GUI Solution

L'application se presente comme suit à l'ouverture


_les composants de construction :_

* [java.swing](https://www.javatpoint.com/java-swing) - Palette (front-end)

_Cette partie graphique va nous aider à :_

- Simplifier la communication des informations à l'utilisateur
- Fournir des éclaircissements supplémentaires pour permettre un engagement transparent à l'utilisateur
- Éclairer des informations inattendues, sous-estimées ou inconnues auparavant
- Offrir une évasion divertissante de la réalité, au moins pour une courte période
- etc.

## Contributions

J’accorde aux utilisateurs les droits d'utiliser, d'étudier, de modifier et de distribuer le logiciel et son code source à quiconque et à n'importe quelle fin.

## Versions

Ceci correspond à un état donné de l'évolution du logiciel et j'utilise le versionnage. Ci dessous les versions produites

**Dernière version stable :** 1.0

## Auteurs
le(s) auteur(s) du projet est(sont) :
* **Kalema daniel jonathan** _alias_ [@kalemadaniel](https://github.com/kalemadaniel)

## License

Ce projet est sous licence **``open source``** 
