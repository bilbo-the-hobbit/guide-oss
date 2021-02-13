Décisionnel : Suite
===================

Les suites décisionnelles regroupent généralement les deux catégories présentées précédemment ; c'est-à-dire l’ETL et le reporting.

Ainsi, le périmètre des suites décisionnelles est très vaste : exécution des rapports, analyse OLAP, aide à la création de requêtes, ETL, module de gestion du workflow de publication, etc..


Rapid-Miner
-----------

:Site: http://rapid-i.com/
:Porteur: un éditeur (Rapid-I)
:Licence: AGPL et proprietaire

Rapid-Miner est une suite décionnelle complète conçue pour le Big Data. Rapid-Miner comporte un module d'analyse de données, de reporting, un module OLAP, un module Hadoop, et un ETL. Il intègre tous les outils de business intelligence y compris les modules R et la bibliothèque Weka. Son interface utilisateur permet de dessiner des chaînes de traitement et des rapports à la souris. Son moteur de calcul est capable de répartir les calculs sur un cluster.

Rapid-Miner est issu de la recherche universitaire allemande et est aujourd'hui largement diffusé dans les banques et compagnies outre-Rhin où il parvient à remplacer le leader du marché sur le segment du décisionnel. Rapid-Miner s'interface avec de nombreuses bases de données et notamment Vectorwise pour atteindre de très hautes performances sur les fermes de données.


SpagoBI
-------

:Site: https://www.spagoworld.org/
:Porteur: un éditeur (Engineering Ingegneria Informatica)
:Licence: LGPL

SpagoBI est une suite décisionnelle développée par la société italienne Engineering Ingegneria Informatica. Ce projet a été initié en 2005.

Le périmètre des fonctionnalités de SpagoBI comprend, à l’instar de Pentaho et Jasperserver : exécution des rapports JasperReports (réalisés avec iReport) et BIRT, l’analyse OLAP avec Mondrian, un composant d’aide à la création de requêtes (Query By Example, QbE), gestion des métadonnées, analyse géo-localisée, etc. L’ETL utilisé par défaut est Talend. Cette suite propose en plus un module de gestion du workflow de publication (états de brouillon non visibles dans le portail web).


JasperSoft
----------

:Site: https://www.jaspersoft.com/
:Porteur: un éditeur (JasperSoft)
:Licence: GPL et propriétaire

JasperServer est la plateforme décisionnelle de JasperSoft, société qui développe également le générateur d’états JasperReports disponible depuis 2001. Cette plateforme propose des fonctionnalités de reporting et d’analyse.

En version community, JasperServer propose la conception et génération de rapports (avec IReport). Dans sa version commerciale, il propose la création de domaines métier, couches sémantiques et techniques au dessus des bases SQL relationnelles, permettant à la fois de définir un lexique métier, de s’abstraire de la technique et du SQL, ainsi que d’ajouter simplement une sécurité d’accès aux données. Une autre fonctionnalité majeure consiste en la création de rapport Ad Hoc, c’est-à-dire que l’utilisateur final peut créer ses propres rapports via une interface web conviviale. De plus, à l’instar des autres plateformes BI, Jasper propose la création de cube OLAP (brique Mondrian) et intègre Talend en tant qu’ETL.


Pentaho
-------

:Site: https://www.pentaho.com/
:Porteur: un éditeur (Pentaho)
:Licence: GPL et propriétaire

Pentaho est une suite logicielle qui permet la distribution de fonctionnalités et documents décisionnels à un grand nombre de personnes par l'intermédiaire d'une interface Web. Le projet a été initié en 2007.

A l’instar de JasperServer, Pentaho regroupe toutes les fonctionnalités d’une suite BI : l’ETL (Pentaho Data Integration), l’analyse OLAP (Mondrian), le reporting Ad Hoc, la couche métadonnée, et le reporting classique (Pentaho Report Designer). Les différences sont les suivantes : le reporting Ad Hoc est disponible dès la version communautaire mais est beaucoup moins évolué que celui du JasperServer commercial, le reporting n’inclut pas encore les tableaux croisés dynamiques et la gestion de la sécurité des données est plus complexe à mettre en place. Globalement, la suite Pentaho est plus complète que la suite Jasper en version communautaire, mais la tendance s’inverse en version commerciale, JasperServer proposant des fonctionnalités très intéressantes (Domaines, Ad Hoc évolué,…)


Autres
------

- KNIME: https://www.knime.com/
- Eclipse BIRT: https://www.eclipse.org/birt/
