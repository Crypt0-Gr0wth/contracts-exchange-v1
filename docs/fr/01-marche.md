# 1. Architecture du marché LooksRare

LooksRare v1 sépare le contrat d’échange, les gestionnaires de devises et les stratégies d’exécution. Un ordre décrit l’actif vendu, le moyen de paiement, le destinataire et les paramètres de validité. Le contrat central vérifie la signature et orchestre le transfert des NFT et des fonds.

Cette séparation permet d’ajouter des stratégies de vente sans réécrire le règlement de base. Le dépôt contient aussi les bibliothèques de transferts et les contrôles d’administration.

[Chapitre suivant : ordres et signatures](02-ordres.md).
