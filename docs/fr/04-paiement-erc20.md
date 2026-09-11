# 4 — Prépaiement et règlement ERC-20

Le paymaster peut vérifier un solde ERC-20 et prélever des tokens pour couvrir le sponsoring.
Solde, allowance et coût estimé représentent des notions différentes et doivent rester séparés.
Un token à frais, rebasant ou non standard peut rompre l’hypothèse montant demandé égale montant reçu.
Le prépaiement en validation réduit le risque de non-paiement mais déplace le risque vers l’utilisateur si l’exécution échoue.
Le règlement post-op doit être borné et ne jamais dépasser l’autorisation signée.
Les décimales et le taux de conversion gas/token doivent porter une fraîcheur et une limite de glissement.
Pour un actif enveloppé lié à Bitcoin, la solvabilité du wrapper reste indépendante du fonctionnement du paymaster.

Suite : [griefing](05-griefing-et-limites.md).
