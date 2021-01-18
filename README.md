# NicolasJobard_3_18012021
Projet 3 de la formation Développeur Web d'OpenClassrooms.
## Intitulé du projet
Dynamisez une page web avec des animations CSS.
## Scénario du projet
En tant que développeur junior au sein de la startup Ohmyfood!, développer un site 100% mobile répertoriant les menus de restaurants gastronomiques, et le présenter au CTO.
## Objectifs
* Mettre en place une structure de navigation pour un site web;
* Mettre en oeuvre des effets CSS graphiques avancés;
* Assurer la cohérence graphique d'un site web.
## Contraintes
### Techniques
#### Ecriture du code
* Pas de JavaScript;
* Pas de framework mais utilisation de SASS;
* Aucun code CSS appliqué via un attribut style dans une balise HTML;
* Approche mobile-first -> intégration à partir des maquettes mobiles;
* Sur tablette et desktop, le site devra s’adapter, liberté pour leur mise en page;
* L’ensemble devra être responsive;
* Compatibilité avec les dernières versions desktop de Chrome et Firefox;
* Aucune erreur ni alerte au validateur W3C HTML et CSS.
#### Contenu attendu
* Contenu des pages
	* Page d’accueil (x1)
		* Affichage de la localisation des restaurants (à terme il sera possible de choisir la localisation),
		* Courte présentation de l’entreprise,
		* Une section contenant les 4 menus sous forme de cartes cliquables redirigeant vers la page du menu;
	* Pages de menu (x4)
		* 4 pages contenant chacune le menu d’un restaurant;
	* Footer
		* Identique sur toutes les pages,
		* Au clic sur “Contact”, renvoi vers une adresse mail;
	* Header
		* Présent sur toutes les pages,
		* Sur la page d’accueil, il contient le logo du site,
		* Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil.
* Effets graphiques et animations
	* Les effets accessibles au clic ou au survol sont visibles sur la maquette;
	* Boutons :
		* Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir,
		* L’ombre portée devra être plus visible,
		* Un bouton "J’aime" en forme de cœur, pour permettre à terme aux visiteurs de sauvegarder leurs menus préférés, qui devra se remplir progressivement au clic (l’effet peut être apparaître au survol sur desktop au lieu du clic);
	* Page d’accueil :
		* Un aperçu d'un “loading spinner” devant :
			* apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil,
			* couvrir l'intégralité de l'écran,
			* utiliser les animations CSS (le design de ce loader n’est pas défini, proposition doit être cohérente avec la charte graphique du site);
	* Pages de menu :
		* À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps (soit un par un, soit par groupe “Entrée”, “Plat” et “Dessert”, exemple de l’effet attendu fourni),
		* Le visiteur peut ajouter les plats en cliquant dessus, faisant apparaître une petite coche à droite du plat qui devra coulisser de la droite vers la gauche (l’effet peut apparaître au survol sur desktop au lieu du clic),
		* Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension (exemple de l’effet attendu fourni).
### Identité graphique
* Les images sont fournies;
* Polices :
	* Logo et titres: Shrikhand
	* Texte: Roboto.
* Couleurs :
	* Primaire : #9356DC
	* Secondaire : #FF79DA
	* Tertiaire : #99E2D0
## Livrables
* Un lien vers le repository (doit être accessible et le code versionné);
* Un lien vers la page web hébergée en ligne, pour présenter la maquette.