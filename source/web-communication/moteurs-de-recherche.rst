Moteurs de recherche
====================

Les moteurs de recherche sont, comme les systèmes d’exploitation et les bases de données, des pierres angulaires de notre quotidien.

Ils permettent de retrouver et d’accéder à des ressources (au sens large : pages web, images, vidéos, fichiers, etc.) indexées avec un ensemble de mots clés.

Les moteurs de recherche sont généralement composés de deux services : l’indexation et la  recherche.

Les moteurs de recherche se différencient généralement par leurs capacités d’indexation (format, rapidité, algorithme de pertinence) et leurs fonctions de traitements linguistiques (pluriels, conjugaisons, phonétique, etc.).

Dans l’univers de l’open source, le marché est dominé par les moteurs de recherche Lucene et Solr. On les retrouve très souvent associées aux meilleures applications web.

Apache Lucene
-------------

:Site: http://lucene.apache.org/
:Porteur: une fondation (Apache)
:Licence: Apache

Porté par la fondation Apache, le projet Lucene est la solution retenue, entre autres, par Wikipedia, pour l’indexation et la recherche de ses contenus. Lucene est sans aucun doute l’outil de recherche le plus connu, le plus utilisé et le plus dynamique du marché de l’open source. Il a été crée par Doug Cutting en mars 2000.

Lucene se définit avant tout comme une bibliothèque de recherche et d'indexation de contenus. Comme la plupart des moteurs de recherche, Lucene se base sur le concept de l’indexation automatique, c'est-à-dire en traitant une seule fois les données d’entrée et en leur donnant de multiples liens. Coté fonctionnel, Lucene support la recherche de formes approximatives d'un même mot (féminin, pluriel, conjugaison), la gestion des synonymes, la pertinence paramétrable, etc. Le tout avec un niveau de performances exceptionnels.

Lucene est écrit en Java. Il peut être intégré au sein d’applications écrites dans différents langages : Java, Python, Ruby, Perl, PHP, C++, etc.


Apache Solr
-----------

:Site: https://lucene.apache.org/solr/
:Porteur: une fondation (Apache)
:Licence: Apache

Solr est une surcouche de Lucene qui ajoute des fonctionnalités et facilite le déploiement de certaines fonctions de Lucene reconnues comme trop techniques. Son développement a été initié par CNET Networks lesquels ont décidé en 2006 de publier leur travail.

Solr est un serveur de recherche d'entreprise permettant de centraliser les opérations d'indexation et de services de résultats. Solr est capable de communiquer avec les autres applications via de nombreux protocoles basés sur des standards ouverts, il dispose également d’une interface d’administration en mode Web. L’une des caractéristiques majeures de Lucene est la capacité à indexer les contenus par champ, ou par attribut, c’est à dire qu’un document n’est pas analysé comme un simple ensemble de mots, il est constitué de champs, chaque champ étant une suite de mots (terms). Solr permet de tirer pleinement parti de cette fonctionnalité. Ce fonctionnement permet une gestion beaucoup plus fine de la pertinence, et de la recherche avancée.


OpenSearchServer
----------------

:Site: https://www.open-search-server.com/
:Porteur: un éditeur (Jaeksoft)
:Licence: GPL

OpenSearchServer est un serveur de recherche, créé par Emmanuel Keller. La première version open source est sortie en 2008.

OpenSearchServer a été développé en interne dans le cadre du site l'Usine Nouvelle. Basé sur Lucene, il se différencie de SolR par une interface d'administration graphique accessible en HTTP, une capacité de crawling de site très avancée (gestion des threads, exclusion de pages, programmation de l'indexation, etc...), un système d'indexation de base de données et un crawler de fichiers. OpenSearchServer peut également facilement s'interfacer avec toute application, à travers une interface REST. De plus, OpenSearchServer peut être étendu facilement à travers des modules spécifiques qui viendront enrichir ses fonctionnalités. OpenSearchServer est également capable d'interpréter le contenu de plusieurs formats de fichiers (OpenOffice, Ms Office, PDF, etc...).

La société Jaeksoft, basée sur Paris, assure la majeure partie des développements et fournit du support sur l'outil.

OpenSearchServer est basé sur Lucene et écrit en Java.


Autres
------

Parmi les produits de l’univers Moteurs de recherche, on peut compléter la liste avec les outils ci-dessous :

- Xapian: http://xapian.org/
- Sphinx: https://sphinxsearch.com/
- Whoosh: https://pypi.org/project/Whoosh/
- Apache Nutch: http://nutch.apache.org/

