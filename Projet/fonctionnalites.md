# Fonctionnalités de Bill Quote

## Rôles
- Utilisateur inscrit et connecté : possibilité d'effectuer et de rechercher des factures/devis. De rechercher, modifier ou supprimer un client.
- Utilisateur non inscrit : Possibilité de s'inscrire.

## Utilisateur inscrit
- L'utilisateur doit s'authentifier pour avoir accès aux différentes fonctionnalités de l’application 

## Utilisateur connecté 

-   L’utilisateur peut s’inscrire et s’authentifier avec la possibilité de se déconnecter 
-   Effectuer une nouvelle facture ou un nouveau devis
-   Rechercher une facture ou un devis déjà effectué
-   L’utilisateur peut ajouter un nouveau client ou en supprimer 
-   Possibilité de prévisualiser la facture ou le devis avant de le télécharger.
-   Pouvoir modifier une facture ou un devis 

## Utilisateur non inscrit
- Possibilité de s'inscrire 

## Utilisateur Administrateur
- Possibilité de suprimer un compte utilisateur



# Entités

- Utilisateur-Société
- Client
- Factures
- Devis 

# Attributs

- Utilisateur: Id_soc, nom_société, nom_gerant, prenom_gerant, mail_soc, tel_soc, mdp, img-logo, adresse, code_postale, ville, role
- Facture: id_facture, numero_facture, date_enregistrement
- Devis: id_devis, numero_devis, date_enregistrement
- client: id_client, nom_client, prenom_client, societe_client, mail_client, tel_client