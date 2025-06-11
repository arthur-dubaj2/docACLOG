# Gestion commerciale



## Devis

Fiche Devis : 

![image-20250604144150503](img/image-20250604144150503.png)

Un devis contient deux points d'informations principaux : 

- [Client](clients.md)
  > L'ajout d'un client à une commande peut se faire via son nom, par sa société ou par son code. Il est également possible de créer un nouveau client directement via la fiche commande ![image-20250604144711878](img/image-20250604144711878.png), ou d'en choisir un existant![image-20250604144652728](img/image-20250604144652728.png).

- [Produits / Prestations]()

  > Les produits s'ajoutent via la liste de produits existants ![image-20250604144949399](img/image-20250604144949399.png) ou via un scan du code-barres.
  >
  > L'outil crayon  ![image-20250603112458622](img/image-20250603112458622.png) permet d'ajouter un produit _à la main_ au sein de la commande.
  >
  > On peut également supprimer un produit de la commande via le bouton ![image-20250604145042284](img/image-20250604145042284.png).



Les différents renseignements restant sont explicites. Il est également possible d'ajouter des observations (visibles ou non ![image-20250604145703079](img/image-20250604145703079.png)par le client) au devis.

Une fois un ou plusieurs devis créées. L'utilisateur peut accéder à la liste des devis :

![image-20250611101103261](img/image-20250611101103261.png)



Depuis cette liste, l'utilisateur peut interagir avec les devis déjà créés. Le bouton modifier ![image-20250611101251808](img/image-20250611101251808.png) donne accès à la fiche du devis . Le bouton dupliquer ![image-20250611101422072](img/image-20250611101422072.png)permet de créer une copie du devis sélectionné et de l'ajouter à la liste. Le bouton Imprimer ![image-20250611101457475](img/image-20250611101457475.png) permet la génération d'une version pdf du devis, destinée à l'impression. Le bloc notes ![image-20250611101757298](img/image-20250611101757298.png) permet d'ajouter des commentaires, reliés à un devis. Le bouton e-mail ![image-20250611101935580](img/image-20250611101935580.png) permet d'envoyer la version pdf du devis par mail.



## Commandes

Fiche commande :

![image-20250603105510828](img/image-20250603105510828.png)



Une commande contient trois points d'information:

- [Client](clients.md)

  > L'ajout d'un client à une commande peut se faire via son nom, par sa société ou par son code. Il est également possible de créer un nouveau client directement via la fiche commande ![image-20250604144711878](img/image-20250604144711878.png), ou d'en choisir un existant![image-20250604144652728](img/image-20250604144652728.png).

- [Adresse de Livraison](clients.md#adresse-de-livraison)

  > L'adresse de livraison peut s'ajouter via la fiche de commande, on peut également sélectionner une adresse existante ![image-20250604145826593](img/image-20250604145826593.png)ou choisir comme adresse de livraison l'adresse associée au client.

- [Produits / Prestations]()

  > Les produits s'ajoutent via la liste de produits existants ![image-20250604144949399](img/image-20250604144949399.png) ou via un scan du code-barres.
  >
  > L'outil crayon  ![](img/image-20250603112458622.png) permet d'ajouter un produit _à la main_ au sein de la commande.
  >
  > On peut également supprimer un produit de la commande via le bouton ![image-20250604145042284](img/image-20250604145042284.png).

Les différents renseignements restants sont explicites, les types de commande étant définis par l'utilisateur.



Le bouton ![image-20250604150125607](img/image-20250604150125607.png) permet d'ajouter des commentaires (visibles ou non par le client ![image-20250604145703079](img/image-20250604145703079.png)) à la commande.



Enfin le bouton transférer ![image-20250603112922121](img/image-20250603112922121.png)permet la transtion directe vers une [facture](#facture) ou un [bon de livraison](#bon-de-livraison).

Fiche de commande complète :

![image-20250603113655622](img/image-20250603113655622.png)



La liste des commandes offre les mêmes fonctionnalités que la liste des [Devis](#devis). La seule option suppplémentaire est la création d'un acompte ![image-20250611102333377](img/image-20250611102333377.png) permettant de définir un montant, un mode de règlement, ainsi qu'un commentaire. Pour pouvoir enregister l'acompte, la case _Acquitté_ doit être cochée. Une fois l'acompte enregistré, son montant est soustrait du _Solde Restant à payer_ dans la fiche commande.

![image-20250611102805070](img/image-20250611102805070.png)

La poubelle ![image-20250611102952230](img/image-20250611102952230.png)permet la suppression d'un acompte déjà enregistré.

## Bons de livraison

Un bon de livraison s'organise de la même manière qu'une commande, et dérive souvent directement de celle-ci.

Une commande contient trois points d'information:

- [Client](clients.md)

  > L'ajout d'un client à une commande peut se faire via son nom, par sa société ou par son code. Il est également possible de créer un nouveau client directement via la fiche commande ![image-20250604144711878](img/image-20250604144711878.png), ou d'en choisir un existant![image-20250604144652728](img/image-20250604144652728.png).

- [Adresse de Livraison](clients.md#adresse-de-livraison)

  > L'adresse de livraison peut s'ajouter via la fiche de commande, on peut également sélectionner une adresse existante ![image-20250604145826593](img/image-20250604145826593.png)ou choisir comme adresse de livraison l'adresse associée au client.

- [Articles]()

  > Les articles s'ajoutent via la liste de produits existants ![image-20250604144949399](img/image-20250604144949399.png) ou via un scan du code-barres.
  >
  > L'outil crayon  ![image-20250603112458622](img/image-20250603112458622.png) permet d'ajouter un produit _à la main_ au sein de la commande.
  >
  > On peut également supprimer un produit de la commande via le bouton ![image-20250604145042284](img/image-20250604145042284.png).

Les différents renseignements restants sont explicites, les modes de livraison étant définis par l'utilisateur. 

L'outil de recherche ![image-20250603115017227](img/image-20250603115017227.png)permet de rechercher des produits via leur numéro de commande.



Bon de livraison transféré depuis la commande précédente :

![image-20250603115151164](img/image-20250603115151164.png)

La liste des bons de livraisons offre globalement les mêmes possibilités que la liste des [Devis](#devis). En plus, celle-ci permet l'impression d'étiquettes via la bouton étiquettes ![image-20250611103430078](img/image-20250611103430078.png). Le règlage de la position de départ des étiquettes permet d'imprimer les étiquettes de plusieurs commandes sur la même planche.  Enfin, le bouton colis ![image-20250611103649273](img/image-20250611103649273.png) permet la gestion des différents colis en cours de livraison via leur numéro de tracking : 

![image-20250611103751444](img/image-20250611103751444.png)

## Factures et Avoirs

Une facture, comme un avoir, se construit de la même manière qu'un devis : 

![fiche_facture](img/image-20250604150551033.png) ![fiche_avoir](img/image-20250604150623589.png)

Une fois dans les listes respectives des avoirs/factures, on retrouve des fonctionnalités connues, mais également un outil en plus spécifique à chaque document.

Pour les **Factures**, le logiciel permet d'ajouter un ou plusieurs règlements via le bouton ![image-20250611105422825](img/image-20250611105422825.png). Une fois un règlement ajouté à la facture, celle-ci est considérée comme partiellement réglée. Quand la somme des règlements atteint le montant de la facture, celle-ci est considérée comme acquittée. Quand la facture provient d'une [Commande](#commande) pour laquelle un acompte a été versé, il est possible de laisser le reste du règlement en suspens, en refusant de  reprendre la saisie : ![image-20250611110827116](img/image-20250611110827116.png) .



Pour les **Avoirs**, le logiciel permet de calculer le montant de l'avoir restant à consommer via un clic sur le bouton : ![image-20250611110951307](img/image-20250611110951307.png).



## Transfert

Tous ces documents étant dépendant les uns des autres, il est possible de générer certains d'entre eux depuis d'autres.

Les dépendances se hiérarchisent comme suit :

- Un [Devis](#devis) permet de générer la [Commande](#commandes) ainsi que la [Facture](#factures-et-avoirs) associée.

  > Cette génération se fait via le bouton ![image-20250611111458278](img/image-20250611111458278.png) 

- Une [Commande](#commandes) permet la génération de la [Facture](#factures-et-avoirs) ainsi que du [Bon de Livraison](#bons-de-livraison) associée.

  > Cette génération se fait via le bouton ![image-20250611111831437](img/image-20250611111831437.png).

- Un [Bon de Livraison](#bons-de-livraison) permet la génération de la [Facture](#factures-et-avoirs) associée.

  > Cette génération se fait via un clic-droit sur le bon de livraison au sein de la liste.

- Une [Facture](#factures-et-avoirs) permet la génération de l'[Avoir](#factures-et-avoirs) associé.

  > Cette génération se fait via un clic-droit sur la Facture au sein de la liste.

### Exemple de transfert

**Devis** :

 ![devis_transfert](img/image-20250611115734697.png)

**Commande**:

 ![commande_transfert](img/image-20250611120008788.png) 

**Facture**:

 ![facture_transfert](img/image-20250611120139649.png)

**Avoir** :

 ![avoir_transfert](img/image-20250611120324027.png) 

**Bon de Livraison**:

 ![bdl_transfert](img/image-20250611120439540.png) 



## Règlements en attente

L'outil **Règlements en attente** liste les différentes factures attendant un règlement. La liste contient également les avoirs dont le montant n'a pas encore été intégralement dépensé, le montant restant à dépenser étant indiqué en négatif.

Une liste d'outils servant à relancer les clients concernés par ces règlements est disponible via ce menu .

- On peut générer une facture via ![image-20250611113838585](img/image-20250611113838585.png).

- On peut générer un Impayé client, indiquant la somme totale que le client doit actuellement à l'entreprise, via ![image-20250611113926638](img/image-20250611113926638.png).

- On peut générer une lettre de relance via ![image-20250611114111081](img/image-20250611114111081.png).

  > Il existe deux modèles de lettres de relance. Le modèle 1 correspond à une première relance, tandis que le modèle 2 sert de dernier avertissement avant l'initiation de procédures judiciaires.

- On peut effectuer une relance par e-mail via le bouton ![image-20250611115034872](img/image-20250611115034872.png). Cette option génère un mail possèdant en pièce jointe une facture ou une lettre de relance, au choix.

- La relance SMS ![image-20250611115510526](img/image-20250611115510526.png)permet de sélectionner les clients à relancer et de les joindre via leur téléphone portable.



