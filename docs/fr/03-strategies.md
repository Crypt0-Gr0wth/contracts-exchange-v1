# 3. Stratégies de vente et gestion des devises

Les stratégies décrivent la manière dont un ordre est exécuté : prix fixe, vente groupée ou logique spécialisée. L’ExecutionManager autorise seulement les stratégies enregistrées et le CurrencyManager limite les devises acceptées. Les transferts utilisent les interfaces adaptées aux ERC-20, ERC-721 et ERC-1155.

Cette modularité concentre les permissions dans des gestionnaires et réduit le risque qu’une stratégie inconnue puisse déplacer des actifs. Les frais et leurs destinataires font partie du règlement final.

[Chapitre suivant : limites et périmètre](04-limites.md).
