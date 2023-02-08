# Atelier Automated Smart Management 

Dans cet atelier, vous apprendrez à tirer le meilleur parti de Red Hat Smart Management en concert avec Red Hat Ansible Automation Platform.

## Table des matières
- [Utilisation des cas](#use-cases)
- [Présentations](#presentations)
- [Planification du temps](#time-planning)
- [Diagramme du laboratoire](#lab-diagram)
- [Atelier Exercices](#Workshop-Exercises)

## Utilisation des cas

Cet atelier se concentre actuellement sur trois principaux points sensibles :
- Conformité (OpenSCAP Scanning) et gestion de la vulnérabilité
- Gestion des Patches/Paquetages
- Conversion CentOS vers RHEL

## Présentations

Les exercices sont auto-explicatifs et guident les participants tout au long du laboratoire. Tous les concepts sont expliqués lorsqu'ils sont introduits.

Il y a une présentation optionnelle disponible pour soutenir les ateliers et expliquer l'automatisation, les bases d'Ansible et les sujets des exercices en détail. La présentation de l'atelier est située au [Atelier automatisé de gestion intelligente](https://aap2.demoredhat.com/decks/ansible_smart_mgmt.pdf).

Jetez également un coup d'oeil à notre présentation sujr les meilleurs pratiques avec Ansible:
[Pratiques exemplaires disponibles](../../decks/ansible_best_practices.pdf)

## Planification du temps

Le temps nécessaire pour faire les ateliers dépend fortement de plusieurs facteurs : le nombre de participants, la familiarité avec Linux en général et le nombre de discussions entre eux.

Cela dit, les exercices eux-mêmes devraient prendre environ 4 heures. Chaque laboratoire dure environ 30 à 45 minutes. La présentation qui accompagne elle-même ajoute ~1 heure.

## Diagramme du laboratoire
![diagramme automatique de laboratoire de gestion intelligente](../../images/ansible_smart_mgmt_diagram.png#centreme)

### Environnement

| Role                    | Inventory name |
| ------------------------| ---------------|
| Automation controller   | ansible-1      |
| Satellite Server        | satellite      |
| Managed Host 1 - RHEL   | node1          |
| Managed Host 2 - RHEL   | node2          |
| Managed Host 3 - RHEL   | node3          |
| Managed Host 4 - CentOS | node4          |
| Managed Host 5 - CentOS | node5          |
| Managed Host 6 - CentOS | node6          |



## Atelier Exercices

* [Exercice 0: Configuiser l'environnement du laboratoire](0-setup/README.fr.md)
* [Exercice 1: Conformité / Gestion de la vulnérabilité](1-compliance/README.fr.md)
* [Exercice 2: Gestion du Patch / OS](2-patching/README.fr.md)
* [Exercice 3: CentOS à la conversion RHEL](3-convert2rhel/README.fr.md)
