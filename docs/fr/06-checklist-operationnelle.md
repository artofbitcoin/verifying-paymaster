# 6 — Checklist opérationnelle

Vérifier EntryPoint, chaîne, adresse du paymaster et version du format signé.
Bornder validAfter, validUntil, gas maximal, coût token et montant prélevable.
Documenter les rôles owner, signer et gestionnaire de bundlers ainsi que leur rotation.
Tester conceptuellement tokens atypiques, opérations concurrentes, revert de la cible et échec post-op.
Séparer refus de politique, signature invalide et panne du service d’autorisation.
Alerter avant que le dépôt EntryPoint ou la liquidité ERC-20 atteigne un seuil critique.
Ce parcours est documentaire : aucune installation, compilation, transaction ou exécution de tests.
Les comportements peuvent être confrontés à VerifyingPaymaster.sol, aux documents et aux tests du dépôt.
