# Angular PDF Tutoriel - Export PDF en Angular avec JSPDF

## Description
Dans ce tutoriel PDF Angular, je vais partager avec vous comment exporter un fichier PDF dans une application Angular en utilisant le package **jsPDF**.

Nous pouvons générer des PDF pour divers documents tels que des factures, des rapports, des formulaires, etc. Dans une application Web, nous pouvons créer des PDF en utilisant les méthodes d'impression du navigateur, un outil tiers, et nous pouvons également télécharger le PDF du côté client.

## Il existe quelques autres packages PDF disponibles tels que:

* jsPDF
* PDFMake
* ng2-pdf-viewer

Cependant, dans cet tutoriel, nous allons nous concentrer uniquement sur le plugin générateur jsPDF pour exporter le PDF dans Angular

## jsPDF
### Définition
Le **jsPDF** est un module basé sur JavaScript, il est utilisé pour générer des PDF côté client, et il offre le grand nombre de méthodes qui vous permettent de personnaliser facilement la vue PDF.

Vous pouvez consulter la documentation officielle 
[ici](https://rawgit.com/MrRio/jsPDF/master/docs/module-addImage.html#~addImage)

## Qu'est-ce qu'un fichier PDF?
Adobe a formulé le PDF vers les années 1990. Il a deux objectifs principaux. Le premier objectif était que les utilisateurs puissent ouvrir les documents sur n'importe quel matériel ou système d'exploitation. Le deuxième objectif était que chaque fois qu'un utilisateur ouvre un document PDF qui doit avoir la même apparence.

Les fichiers PDF incluent du **texte**, des **images**, des **polices intégrées**, des **hyperliens**, des **vidéos**, des **boutons interactifs**, des **formulaires**, etc.

## Configurer le projet angular
Utilisez la commande via Angular CLI pour créer un tout nouveau projet Angular.
<code>ng new angular-pdf</code>

Ensuite, démarrez l'application angular dans votre **IDE préféré**.

## Installer Bootstrap
Pour gérer la partie UI, nous devons installer la bibliothèque Bootstrap dans Angular. Nous utiliserons le composant d'interface utilisateur de la table Bootstrap, ce tableau contiendra les données que nous convertirons en PDF.
<code>npm install bootstrap</code>

Incluez le chemin CSS Bootstrap dans la table des styles du fichier angular.json.

<code>
	<pre>
		"styles": [
		    "src/styles.css",
		    "node_modules/bootstrap/dist/css/bootstrap.min.css"
		]
	</pre>
</code>

Utilisez la commande suivante pour démarrer l'application dans le navigateur.
<code>ng serve --open</code>

## Installer le package jsPDF
Ensuite, installez le package jsPDF dans votre application angular à l'aide de la commande ci-dessous.
<code>npm install jspdf</code>

[Référence](https://www.positronx.io/angular-pdf-tutorial-export-pdf-in-angular-with-jspdf/)