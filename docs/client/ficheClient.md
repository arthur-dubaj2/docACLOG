# Fiche Client



La fiche client présente toutes les caracéristiques définies lors de la création du client en premier plan.

![Capture d’écran du 2025-06-02 14-45-28](../img/CaptureClient5.PNG)



L'interface nous offre la possibilité de dénifir un **type** de client (principal et secondaire). Pour ce faire, il suffit de renseigner un **intitulé** désignant ce type de client ainsi qu'un **code comptable** (optionnel). La création de différents types de clients permet de définir des **catégories tarifaires**, ainsi que de **filtrer** l'affichage des clients dans les différents menus.



En bas de l'interface, un certain nombre d'**onglets** s'offent à l'utilisateur: 

- Les onglets _Règlement_ ainsi que _Banque_ permettent la définition des préférences de paiement du client.
- L'onglet _Divers_ permet de gérer des caractéristiques plus précises liées au client : ![Capture d’écran du 2025-06-02 14-56-12](../img/Capture d’écran du 2025-06-02 14-56-12.png)
- L'onglet _Facturation_ permet de rentrer les informations utiles dans le cat où le client représenté une société.
- L'onglet _Livraison_ permet l'ajout d'informations relatives aux potentiels bons de livraison
- L'onglet _Carte fidélité_ permet d'activer une carte de fidélité liée au client : ![](../img/Capture d’écran du 2025-06-02 15-27-21.png)
- L'onglet _Infos_ n'offre pas d'interaction mais donne accès au chiffres d'affaire généré par ce client.
- L'onglet _Historique_ donne accès à toutes les ventes/commandes impliquant le dit client.
- L'onglet _Bloc-Notes_ joue le rôle de post-it et mermet d'ajouter une annotation quelconque à la fiche.
- Enfin, l'onglet _Contact_ liste les différents moyens de [contacts](##contacts) du client et permet d'en ajouter.



## Modifier

L'outil de modificiation ouvre simplement la fiche client. L'utilisateur peut alors modifier tous les champs modifiables et ajouter de potentielles informations manquantes.

## Imprimer

Il existe trois types d'impression.

![image-20250602155901945](../img/image-20250602155901945.png)

### Imprimer

Un clic sur le bouton _Imprimer_ nous donne accès à quatre options: 

![image-20250602155259067](../img/image-20250602155259067.png)

- Imprimer la liste de tous les clients : 

  > Imprime le résumé de la fiche de chaque client, une par page

- Imprimer une partie des clients

  > Filtre les clients à imprimer en fonction de leur nom et du nom de leur société

- Imprimer la fiche en cours

  > Permet l'impression de la fiche client ou des chiffres annules du client sélectionné

- Imprimer étiquettes clients

  > A compléter



### Imprimer BDC

Un clic sur le bouton  _Imprimer BDC_ nous permet de choisir les dates de départ et de fin du [bon de commande]() associé à un client et d'imprimer ce dernier si il existe.



### Imprimer GenCode

**A completer**



## Bloc-Notes

L'outil _Bloc-Notes_ donne directement accès au bloc-notes de la [Fiche Client](#fiche-client).

![image-20250602161046878](../img/image-20250602161046878.png)



## Historique

Le bouton historique donne accès à un menu déroulant permettant de choisir le sujet de l'historique, celui-ci prenant en compte tous les clients définis.

- Historique des [Devis]()

- Historique des [Ventes]()/prestations

  > Ouvre l'historique de toutes les ventes/prestations effectuées pendant une période choisie par l'utilisateur

- Historique des [Commandes]()

- Historique des [BDL]()

- Historique des [Factures]()/[Avoirs]()

- Historique des [Cheque-cadeaux]()

- Historique des [Abonnements]()



## Adresse de Livraison

Ce bouton ouvre un menu permettant de Créer/modifier/supprimer des coordonées de livraisons indépendamments des clients, réliées à ceux-ci par leur nom :

![image-20250602162722540](../img/image-20250602162722540.png)



## Contacts

Ce menu permet d'accéder rapidement aux moyens de contacts associés à tous les clients.

![image-20250602163502788](../img/image-20250602163502788.png)

Pour ajouter un contact relié à un client, il faut passer par l'onglet contact de sa [Fiche Client](##fiche client).





## Webcam

Permet l'ajout d'une photo, via la webcam ou un import, associée à un client.

![image-20250602164003914](../img/image-20250602164003914.png)



## Mailing SMS

Permet le lancement d'une campagne SMS pour les clients possèdant un numéro de téléphone enregistré. Le lancement d'une campagne SMS nécessite l'achat de crédits SMS reliés au compte utilisateur.

![image-20250602163937911](../img/image-20250602163937911.png)

 

## Supprimer

Le clic-droit sur un client nous propose entre autre de le _supprimer_. Un avertissement apparaît. En effet, un client peut être impliqué dans un ou plusieurs processus en cours, tels qu'une facturation ou une livraison, et sa suppression peut entraîner des disfonctonnements vis à vis de ces processus. Il est donc nécessaire de s'assurer que chaque processus impliquant ce client est terminé avant de le _supprimer_.

