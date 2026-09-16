# 2. Ordres et signatures

Un ordre signé engage un vendeur sur un ensemble de paramètres : collection, token, quantité, prix, devise, expiration et nonce. Le contrat reconstruit le condensat signé et refuse les ordres expirés, annulés ou déjà exécutés. Le nonce permet de révoquer une intention sans parcourir tous les ordres.

La sécurité dépend de la séparation entre domaine de signature, chaîne et contrat de règlement. Les structures et fonctions de validation dans les contrats d’échange sont les points d’entrée à relire.

[Chapitre suivant : stratégies et exécution](03-strategies.md).
