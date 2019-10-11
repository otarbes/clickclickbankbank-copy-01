+++
draft = true
img_path = ""
layout = "page"
subtitle = "Questions les plus fréquentes"
title = "FAQ"

+++
## Questions Générales

### Pré-requis techniques

Du fait que notre application n'est en aucun cas connectée à votre site web, elle fonctionne avec tous les types de sites web et plateformes CMS.

La seule condition préalable est que votre hébergeur n'ait pas mis en place de règles agressives de limitation de débit (_rate limiting_). La limitation de débit est un outil fréquemment utilisé pour se défendre contre les attaques DDoS au niveau du réseau et des applications contre les sites Web.

Si c'est le cas, demandez à votre hébergeur d'ajouter la liste blanche le user-agent suivant : AffiliateLink.

Si vous avez rencontré un problème inattendu, ne vous inquiétez pas. La plupart du temps, cela peut être corrigé rapidement en [nous contactant](mailto:support@clickclickbankbank.com).

N'hésitez pas à nous contacter et nous serons heureux de vous aider.

Afin d'utiliser notre outil, il est également impératif que vous ayez déjà accès à l'API officielle Amazon Product Advertising. Veuillez vérifier dans votre compte Amazon Affiliate pour vous assurer que vous êtes en mesure de créer des clés API avant d'acheter notre outil.

### Est-ce que vous avez une démo ou une version d’essai gratuite?

Nous n’avons pas de lien de démonstration ou d’essai gratuit mais notre [équipe de support](mailto:support@clickclickbankbank.com) est disponible pour répondre à toutes vos questions.

Nous offrons cependant une garantie satisfait ou remboursé de 7 jours, ce qui vous permet de tester l'outil et voir si cela vous convient.

### Quelle est votre politique de retour/annulation ?

Nous accepterons votre demande de remboursement pendant les 7 premiers jours après la création de votre compte ou par la suite si vous n’avez pas commencé à scanner un domaine dans votre compte.  
Vous pouvez modifier ou annuler votre plan à tout moment dans votre tableau de bord.

***

## Démarrage rapide

### Mise en route

Vous trouverez ici un petit tutoriel pour commencer avec ClickClickBankBank. Veuillez noter qu'il ne s'agit pas d'une documentation complète.

**ÉTAPE 1: CRÉER UN COMPTE**

Allez sur [ClickClickBankBank.com](https://app.clickclickbankbank.com/sign-up), choisissez votre forfait et rentrez les informations demandées.

![](/images/step1b.png)

![](/images/step1.png)

Une fois cette étape effectuée, vous recevrez un courriel de confirmation.

**ÉTAPE 2: API AMAZON PRODUCT ADVERTISING**

* Enregistrez vous pour utiliser l'API Amazon Product Advertising depuis votre compte Partenaires.
* Créez vos identifiants API
* Sauvegardez les sur votre ordinateur

**ÉTAPE 3: CRÉEZ UN NOUVEAU SCAN**

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

### Rapports détaillés

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

**RAPPORT DÉTAILLÉ**

![](/images/rapport_detail.png)

* Filtrer par ASIN : Entrez n'importe quel ASIN et vérifiez son statut immédiatement.
* Trier par : Vous pouvez filtrer par le statut de produit suivant : Disponible, Supprimé, En rupture de stock, Erreur.
* Nom : Nom du produit tel qu'indiqué sur Amazon
* ASIN : Code produit d'Amazon
* Lien : Lien direct vers la page produit Amazon
* Statut : Statut du produit tel qu'indiqué dans l'API Amazon Product Advertising
* Stock : Inventaire disponible comme indiqué dans l'API Amazon Product Advertising.
* Lien Amazon : Lien affiché sur votre site web

  ### À quelle fréquence les liens sont-ils vérifiés?

  Comme dirait [Chevallier & Laspalès](https://www.youtube.com/watch?v=ZyBF9gCHl2Y) : « C’est vous qui voyez ! ». Nous ne voulons pas vous forcer à scanner vos liens tous les 2, 7, ou 15 jours si vous ne le souhaitez pas, juste pour utiliser vos crédits. Le lancement d’un scan se fait manuellement, et les résultats disponibles en quelques minutes seulement.

***

## API Amazon Product Advertising

### Créer vos clés API Amazon Product Advertising

**Créer vos identifiants d'API**

![](/images/amazon-associates-api-tools.png)

Vos identifiants peuvent être créés directement dans votre compte Amazon Partenaires.

Dans le cas où vous utilisez un autre programme local d'Associés, votre url pourrait être différente.

![](/images/amazon-associates-credentials.png)

Si vous n'avez pas encore d'identifiants, veuillez cliquer sur le bouton "Ajouter des identifiants".

Si vous ne pouvez pas créer d'identifiants API, votre compte Partenaires ne répond peut être pas encore à toutes les exigences. Les nouveaux affiliés doivent avoir généré au moins 3 ventes avant d'avoir accès à l'API.

**Télécharger les identifiants API**

![](/images/amazon-associates-credentials-download.png)

Une fois les identifiants générés, vous pouvez les voir et les télécharger.

Veuillez noter que vous ne pourrez plus consulter ces informations ensuite, elles seront masquées dans votre compte. C'est pourquoi nous vous conseillons de les télécharger et les sauvegarder sur votre ordinateur.

**Gestion des identifiants API**

![](/images/amazon-associates-credentials-manage.png)

Toutes les informations d'identification précédentes seront affichées dans votre compte Amazon Partenaires.

Les informations d'identification API existantes peuvent être supprimées, mais vous ne pouvez plus les consulter pour les copier de nouveau par exemple.

Si vous ne connaissez plus vos identifiants API, veuillez en créer un nouveau (notez qu'il y a une limite maximale de 2 paires d'identifiants API actives).

### Erreur Amazon API – Causes fréquentes

Dans le cas où l'application n'a pas été en mesure d'établir une connexion à l'API Amazon, voici quelques-unes des causes les plus fréquentes :

* Vous ne vous êtes pas encore inscrit à l'API Amazon Product Advertising
* L'identifiant API et/ou la clé secrète ne sont pas valides
* L'ID Partenaire que vous utilisez n'est pas le même que celui associé à votre clé API

### Inscription à l’API Amazon Product Advertising

Si vous ne vous êtes pas encore inscrit à l'API Amazon Product Advertising, voici comment procéder.

Brésil	[http://associados.amazon.com.br/gp/associates/apply/main.html](http://associados.amazon.com.br/gp/associates/apply/main.html "http://associados.amazon.com.br/gp/associates/apply/main.html")

Canada	[https://associates.amazon.ca/gp/flex/advertising/api/sign-in.html](https://associates.amazon.ca/gp/flex/advertising/api/sign-in.html "https://associates.amazon.ca/gp/flex/advertising/api/sign-in.html")

Chine	[https://associates.amazon.cn/gp/advertising/api/detail/main.html](https://associates.amazon.cn/gp/advertising/api/detail/main.html "https://associates.amazon.cn/gp/advertising/api/detail/main.html")

France	[https://partenaires.amazon.fr/gp/flex/advertising/api/sign-in.html](https://partenaires.amazon.fr/gp/flex/advertising/api/sign-in.html "https://partenaires.amazon.fr/gp/flex/advertising/api/sign-in.html")

Allemagne [https://partnernet.amazon.de/gp/flex/advertising/api/sign-in.html](https://partnernet.amazon.de/gp/flex/advertising/api/sign-in.html "https://partnernet.amazon.de/gp/flex/advertising/api/sign-in.html")

Inde	[http://affiliate-program.amazon.in/gp/associates/apply/main.html](http://affiliate-program.amazon.in/gp/associates/apply/main.html "http://affiliate-program.amazon.in/gp/associates/apply/main.html")

Italie	[https://programma-affiliazione.amazon.it/gp/advertising/api/detail/main.html](https://programma-affiliazione.amazon.it/gp/advertising/api/detail/main.html "https://programma-affiliazione.amazon.it/gp/advertising/api/detail/main.html")

Japon	[https://affiliate-program.amazon.com/gp/flex/advertising/api/sign-in-jp.html](https://affiliate-program.amazon.com/gp/flex/advertising/api/sign-in-jp.html "https://affiliate-program.amazon.com/gp/flex/advertising/api/sign-in-jp.html")

Mexique	[https://afiliados.amazon.com.mx/gp/advertising/api/detail/main.html](https://afiliados.amazon.com.mx/gp/advertising/api/detail/main.html "https://afiliados.amazon.com.mx/gp/advertising/api/detail/main.html")

Espagne	[https://afiliados.amazon.es/gp/flex/advertising/api/sign-in.html](https://afiliados.amazon.es/gp/flex/advertising/api/sign-in.html "https://afiliados.amazon.es/gp/flex/advertising/api/sign-in.html")

Royaume-Uni	[https://affiliate-program.amazon.co.uk/gp/flex/advertising/api/sign-in.html](https://affiliate-program.amazon.co.uk/gp/flex/advertising/api/sign-in.html "https://affiliate-program.amazon.co.uk/gp/flex/advertising/api/sign-in.html")

États-Unis	[https://affiliate-program.amazon.com/gp/flex/advertising/api/sign-in.html](https://affiliate-program.amazon.com/gp/flex/advertising/api/sign-in.html "https://affiliate-program.amazon.com/gp/flex/advertising/api/sign-in.html")

![](/images/amazon-affiliate-wordpress-plugin-docs-signup-amazon-api.png)

Sur cette page, cliquez sur "S'inscrire" à droite et remplissez le formulaire d'inscription. Il est possible d'utiliser votre compte Amazon 'client' existant si cela ne vous dérange pas.

***

## Programme d’Affiliation

### Qu'est-ce que le programme d'affiliation ClicklickBankBank et comment fonctionne-t-il ?

Le programme d'affiliation ClickClickBankBank est un partenariat basé sur le partage des revenus, où l'affilié (vous) génère du trafic vers le site web ClickClickbankbank.com (nous, notre ou nos) en échange de commissions. Lorsque le visiteur de votre site Web clique sur le lien de référence (tel que défini dans les conditions de notre programme d'affiliation ClickClickBankBank) vers notre site Web et effectue un achat, vous recevez une commission pour chaque abonnement ClickClickBrankBank qu'il souscrit.

Pour vous aider à atteindre cet objectif, nous fournissons une variété de matériel promotionnel en 2 langues, suivi, rapports, paiements mensuels rapides et un excellent support client.

### Qu'est-ce que j'obtiens en tant qu'affilié ?

En tant qu'affilié, vous aurez accès à votre propre compte personnel. Vous pouvez vous connecter à tout moment et accéder à nos bannières et liens, voir comment vos liens de référence fonctionnent : combien de visites, de ventes d'abonnements et de refacturations nous sont parvenus via votre lien de référence et bien sûr vous pourrez également voir votre solde et combien d'argent vous avez gagné sur une période donnée.

### Qui peut adhérer à votre programme d'affiliation ?

Toute personne ayant un site Web actif au moment de l'inscription peut s'inscrire au programme d'affiliation ClickClickBankBankBank, à l'exception des sites Web qui contiennent de la pornographie, un langage ou un contenu offensant, interdit ou explicite, de la violence, des propos haineux, des activités illégales, des jeux de hasard, des coupons, des aubaines ou rabais, qui violent des droits ou lois de propriété intellectuelle, qui contiennent du contenu diffamatoire ou dénigrant ou qui établissent un lien avec un contenu mentionné ici. Veuillez noter que vous devez être âgé d'au moins 18 ans pour vous inscrire. Nous nous réservons également le droit de refuser ou de révoquer l'adhésion à des domaines parqués, à des sites Web ayant peu ou pas de contenu original, ou à ceux qui sont inactifs.

Si vous n'avez pas de site Web, vous pouvez toujours partager votre lien de référence par e-mail, publier des vidéos ou promouvoir ClickClickBankBank sur les réseaux sociaux, tels que Facebook, Twitter, etc. Nous avons des affiliés dans le monde entier et la plupart de nos affiliés vendent nos services dans le monde entier. Le processus d'inscription est entièrement gratuit et ne prend que quelques minutes de votre temps.

### Qu'est-ce que le lien de référence ?

Un lien de référence est le lien qui mène à www.clickclickbankbank.com et qui contient votre numéro d'identification de référence ClickClickBankBank (REF ID).

### Où puis-je utiliser le lien de référence ?

Vous pouvez l'utiliser sur votre site web, blog, dans vos emails non spam, profils sociaux et dans vos messages, envoyés par l'intermédiaire de messagers (le SPAMMING est interdit et sévèrement puni).

### Combien vais-je gagner en vous apportant des clients ?

En participant à notre programme d'affiliation, vous gagnerez une commission de 30% sur tous les nouveaux achats d'abonnement ClickClickBankBank qui sont passés par votre lien de référence. Les commissions sont récurrentes, donc vous recevrez 30% de ce que votre filleul nous paie chaque mois jusqu'à ce qu'il cesse de payer pour notre abonnement.

Veuillez noter que ceci ne s'applique qu'aux nouveaux utilisateurs que vous parrainez pour la première fois. Les anciens abonnés ClickClickBankBankBank et les abonnés existants ne sont pas admissibles.

### Puis-je gagner des commissions avec mes propres achats ?

Bien essayé, mais non. Vous ne recevrez pas de commission pour l'achat d'un abonnement ClickClickBankBankBank via votre propre lien de référence. De plus, si vous vous inscrivez juste pour obtenir le rabais de 30% pour vous-même, votre compte sera bloqué et vous ne recevrez pas de commission pour cet achat ou tout autre achat futur.

### Comment attribuez-vous une commission s'il y a plusieurs affiliés impliqués ?

Nous utilisons un modèle d'attribution de cookie, donc si un utilisateur a initialement atterri sur notre site Web à partir de votre lien de référence, alors vous recevrez une commission sur tous leurs achats sur www.clickclickbankbank.com, à condition que la période de vie cookie (90 jours) n'ait pas expiré.

### Comment et quand suis-je payé ?

Les commissions sont versées lorsque le seuil minimal de 50 $ est atteint. Si vous ne l'avez pas encore atteint, le montant sera transféré à la prochaine période de paiement. Les paiements sont effectués les 10e et 25e jours de chaque mois, lorsque le solde de votre compte atteint 50 $ ou plus pour les transactions des mois précédents. Il peut y avoir de légers écarts par rapport à ces dates, si le 10e ou le 25e jour tombe un week-end ou un jour férié. Dans de tels cas, veuillez vous attendre à recevoir le paiement de la commission le lundi (après le week-end) ou le premier jour ouvrable suivant un jour férié. Les paiements sont traités par PayPal.

### Comment puis-je suivre mes gains ?

Vous pouvez vous connecter à votre profil d'affilié ClickClickBankBank à tout moment pour accéder à vos statistiques et obtenir des informations actualisées sur toute commission que vous avez gagnée. Dans vos statistiques, vous pourrez voir la date, les visites, les visites uniques, les inscriptions, les ventes, le montant des ventes, les refacturations (paiements répétés), le montant des refacturations et votre profit. De plus, vous pouvez voir votre solde actuel et tous les paiements que nous vous avons déjà versés.

### À qui dois-je m'adresser pour toute question ou demande spéciale?

Si vous avez une question spécifique ou une proposition de collaboration, n'hésitez pas à nous écrire directement à affiliates@clickclickbankbank.com.