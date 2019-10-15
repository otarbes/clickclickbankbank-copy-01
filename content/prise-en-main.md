+++
img_path = ""
layout = "page"
subtitle = ""
title = "Prise en main"
[menu.secondary]
weight = 1

+++
## Création de compte

### **ÉTAPE 1: CRÉER UN COMPTE**

Allez sur [ClickClickBankBank.com](https://app.clickclickbankbank.com/sign-up), choisissez votre forfait et rentrez les informations demandées.

![](/images/step1b.png)

![](/images/step1.png)

Une fois cette étape effectuée, vous recevrez un courriel de confirmation.

### **ÉTAPE 2: API AMAZON PRODUCT ADVERTISING**

* Enregistrez vous pour utiliser l'API Amazon Product Advertising depuis votre compte Partenaires.
* Créez vos identifiants API
* Sauvegardez les sur votre ordinateur

### **ÉTAPE 3: CRÉEZ UN NOUVEAU SCAN**

Cliquez sur le bouton "Nouveau Scan" en haut à droite de votre Tableau de bord.

Remplissez le formulaire:

* Domaine: URL à vérifier
* Clé API Amazon
* Clé Secrète Amazon
* Pays Amazon: Sélectionnez le pays Amazon lié à votre clé API.
* ID Partenaire: Sans ID partenaire, vos liens ne sont pas reliés à votre compte et vous ne toucherez pas de commissions. Cet ID doit être sous la forme ccbb-21 (les 2 derniers chiffres peuvent différer selon le pays)
* Cloaking: Si vous utilisez un plugin de cloaking de vos liens (AAWP ou EasyAzon par exemple), veuillez intégrer la structure de vos liens ici. Si vous utilisez par exemple [https://monsite.com/go/super-produit-amazon,](https://monsite.com/go/super-produit-amazon, "https://monsite.com/go/super-produit-amazon,") entrez dans le champ [https://monsite.com/go/](https://monsite.com/go/ "https://monsite.com/go/") comme ça nous saurons que ce sont des liens d'affiliation Amazon. Merci de laisser vide si vous n'utilisez pas de cloaking.

Et c'est tout !

![](/images/newscan.png)

Vous serez ensuite redirigé vers votre Tableau de Bord, et vous pourrez suivre la progression du scan toutes les 15 secondes.

## Rapports détaillés

Une fois votre scan terminé, vous aurez accès à plusieurs rapports.

**SOMMAIRE**

![](/images/rapport.png)

* URLs scannées : C'est le nombre d'URL que nous avons trouvées. Dépendant de votre structure technique de site, cela peut correspondre à votre nombre de pages ou non.
* Total produits : Le nombre de produits Amazon scanné.
* Total des liens : Le nombre de liens d'affiliation Amazon scannés.
* Total des liens uniques : Le nombre de liens d'affiliation Amazon dédupliqués, une fois tous les doublons supprimés.

Sur le diagramme graphique vous trouverez un bilan de votre dernier scan :

* Disponible: Le pourcentage de produits Amazon en stock.
* Supprimé: Le pourcentage de produits supprimés du site Amazon (erreur 404).
* Stock épuisé: Le pourcentage de produits Amazon en rupture de stock.
* Erreur: Le pourcentage de produits retournés avec une erreur par l'API. Parfois l'API Amazon renvoie une erreur pour certains produits, si vous avez un pourcentage élevé merci de nous [contacter](mailto:support@clickclickbankbank.com).

### **RAPPORT DE SCAN**

![](/images/rapport_detail.png)

* Filtrer par ASIN : Entrez n'importe quel ASIN et vérifiez son statut immédiatement.
* Trier par : Vous pouvez filtrer par le statut de produit suivant : Disponible, Supprimé, En rupture de stock, Erreur.
* Nom : Nom du produit tel qu'indiqué sur Amazon
* ASIN : Code produit d'Amazon
* Lien : Lien direct vers la page produit Amazon
* Statut : Statut du produit tel qu'indiqué dans l'API Amazon Product Advertising
* Stock : Inventaire disponible comme indiqué dans l'API Amazon Product Advertising.
* Lien Amazon : Lien affiché sur votre site web

### **RAPPORT DE LIENS**

Lorsque vous cliquez sur un lien depuis votre rapport de scan, vous pouvez avoir accès à des informations plus détaillés sur celui-ci.

La première partie de ce rapport vous donnera les informations suivantes :

* Nom du produit relié au lien
* Son statut d'inventaire
* Le stock disponible
* Son ASIN

![](/images/link report 1.png)

Vous aurez aussi accès à des informations complémentaires pour être sûr de modifier toutes les pages et les liens concernés si besoin :

* Date du scan
* Domaine
* Pages contenant le lien. Si plusieurs pages contiennent ce lien elles seront listées ici

![](/images/link report 2.png)

Par ailleurs, si d'autres liens pour le même produit sont détectés, ils seront listés dans cette dernière section du rapport.

![](/images/link report 3.png)