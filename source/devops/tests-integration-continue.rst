Tests & intégration continue
============================

L’intégration continue est un ensemble de pratiques visant à améliorer la qualité de livraison d’une application en vérifiant à chaque modification de code source, que le résultat des modifications n’entraine pas de régressions (c'est-à-dire d’anomalies supplémentaires liées à l’ajout de code).

Pour mettre en œuvre des plateformes d’intégration continue, il existe de nombreux outils open source de qualité tels que Continiuum ou Hudson. Autour des ces outils, on trouve également des solutions de rendu graphique (affichage des résultats).


Tests
~~~~~

Selenium IDE
------------

:Site: http://seleniumhq.org/projects/ide
:Porteur: une communauté
:Licence: Apache

Selenium est un outil de tests d'interfaces. Le projet a débuté en 2004 chez ThoughtWorks à Chicago grâce à Jason Huggins, lequel voulait tester les temps de réponse de diverses applications (Python, Plone, etc.).

Selenium IDE permet d'enregistrer des tests d'interfaces depuis Firefox puis de les sauvegarder afin de les rejouer avec Selenium. Cet outil est très utile pour vérifier qu'une interface est conforme à ce qui est attendu. De plus, il peut être intégré à une plateforme d'intégration continue afin d'automatiser les tests d'interfaces. Selenium IDE n'est pas seulement un outil d'enregistrement : il s'agit d'un environnement de développement intégré (IDE). L'utilisateur peut choisir d'utiliser sa capacité d'enregistrement, ou peut modifier les scripts à la main.



Squash
------

:Version : 1.3.0
:Site : www.squashtest.com
:Porteur : une communauté
:Licence : LGPL v2

La suite open source Squash se compose de plusieurs outils dédiés à l’industrialisation des tests fonctionnels.

Squash TM est un outil open source de gestion de référentiels de tests. Nativement "multi-" et "inter-" projets, il permet de gérer l'ensemble des étapes d'une recette, de la gestion des exigences à l'exécution des campagnes de test. Squash TM est un outil "full web" proposant une interface qui se veut ergonomique et intuitive.

Squash TA est un outillage open source d'automatisation des tests fonctionnels et d'industrialisation de leurs exécutions. Compatible avec plusieurs automates open source (Selenium, Sahi...), Squash TA propose une bibliothèque de fonctions pour gérer les tests automatisés d'applications Web, de webservices, de batchs, et les jeux de données associés (base de données ou fichiers).

Outre Squash TM et Squash TA, la suite open source Squash se compose de Squash Data pour la gestion des jeux de données et Squash SC pour le pilotage et l'administration de Centres de Services Qualité Logicielle.


Autres
------

- JUnit: http://www.junit.org/
- PHPUnit: https://phpunit.de/



Integration continue
~~~~~~~~~~~~~~~~~~~~

Jenkins
-------

:Site: https://www.jenkins.io
:Porteur: une communauté
:Licence: MIT et Creative Commons.


Jenkins est un outil d'intégration continue, fork du projet Hudson développé à l'origine par Sun.

Jenkins permet d'automatiser la construction de projets et de générer des rapports de tests et de qualité. Jenkins est majoritairement utilisé dans le marché des solutions d'intégration continue. Le grand atout de Jenkins est son écosystème composé de centaines de plugins, ainsi que son interface plus simple et moins austère que celle de Continuum par exemple. Les générations de projets peuvent être initiées par différents moyens (mécanismes de planification similaires au cron, des systèmes de dépendances entre générations, ou par des requêtes sur certaines URL spécifiques).

Jenkins est écrit en Java.


Autres
------

- Gitlab CI: https://docs.gitlab.com/ee/ci/
- Buildbot: https://buildbot.net/
- SourceHut CI: https://builds.sr.ht/
- Tox: https://tox.readthedocs.io/


Analyse statique de code
~~~~~~~~~~~~~~~~~~~~~~~~

PMD
---

:Site: http://pmd.sourceforge.net
:Porteur: une communauté
:Licence: BSD

PMD, connu également sous le nom de "Project Mess Detector", ou de "Project Meets Deadline" est un outil d'analyse statique de code destiné à détecter les erreurs de programmation les plus courantes.

En utilisant un système de règles extensibles, PMD est capable de détecter les try-catch vides, le code mort, code sur-compliqué, copié-collé de code (grâce au plugin CPD). PMD est également capable de calculer la complexité cyclomatique d'un code, indicateur intéressant dans l'évaluation de la qualité logicielle.

PMD analyse le code source Java. Il existe un équivalent en PHP (PHPMD, a.k.a. PHP Mess Detector). Les règles peuvent s'écrire à travers des expressions XPath ou des classes Java (ou PHP pour PHPMD).


Autres
------

- Sonar: http://www.sonarsource.org/
- Checkstyle: http://checkstyle.sourceforge.net/
- FindBugs: http://findbugs.sourceforge.net/
- Flake8: https://flake8.pycqa.org/en/latest/
- Pylint: https://www.pylint.org/
