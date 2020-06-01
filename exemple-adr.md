# ADR #0000 : utilisation des ADR pour le suivi des décisions d'architecture pour le projet XYZ

## Suivi

* Auteur(s) : Jon Snow
* Email(s) : jon.snow@northofthewall.com
* version : v1.0
* Date de création : 2019-01-02

## Contexte

Le projet **XYZ** est une application web qui doit exposer une API à usage de nos clients. Cette application doit être développée sous la forme d'un __microservice__ et pourra être la première à utiliser les technologies Y et X. Elle fait donc l'objet d'un suivi particulier afin de pouvoir en tirer des enseignements et des retours d'expérience.

L'équipe projet travaille avec un Kanban et des *user stories* dans le cadre d'une démarche itérative et agile.

## Décision

Utiliser des **ADR** pour suivre les choix de conception significatifs de l'application. 

Les **ADR** seront rédigés en **Markdown** et placés avec la documentation dans les sources. Le processus d'écriture et de validation des **ADR** dans l'équipe est similaire au processus de développement habituel : soit l'**ADR** est créé dans le cadre du développement d'une *feature* et fait partie des fichiers de cette *feature*, soit si c'est un **ADR** *hors feature*, il y a création d'une branche spécifique  et soumission d'une MR pour intégration dans la branche ```Master```.

## Etat

Acceptée

## Conséquences

* Toutes décisions de conception suffisamment significatives doit faire l'objet d'un **ADR**. 
  * Il faudra que l'équipe fasse preuve de discipline et de constance à cet égard, car la pratique n'a d'intérêt que sur le long terme et si elle est pratiquée de manière consistante.
  * Il faudra également que l'équipe se mette d'accord sur ce qui est une décision significative.
* Les **ADR** font parties des supports attendus pour alimenter les réunions de suivis d'architecture tout au long du projet. Il faut bien calibrer l'utilisation des **ADR**, afin de les écrire pour les choix de conception au bon niveau d'abstraction, sinon il y aura trop d'**ADR** pour des décisions mineures ou pas assez sur des choix de conception trop génériques.
* Les **ADR** sont un support important pour l'établissement du REX du projet et contribueront à alimenter les points de conception et d'architecture.

## Informations légales

[![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/). Ce travail est sous licence [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)