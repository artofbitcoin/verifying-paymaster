# 2 — Domaine signé et anti-rejeu

Une autorisation de sponsoring doit engager le hash de UserOperation et le contexte du paymaster.
La chaîne, l’adresse du contrat et la version EntryPoint empêchent la réutilisation sur un autre déploiement.
Les fenêtres validAfter et validUntil bornent la durée pendant laquelle le sponsor accepte le risque.
Un changement de calldata, de coûts de gas ou de paymasterData doit invalider l’autorisation attendue.
L’encodage doit être canonique entre le service signataire et Solidity.
Une signature valide ne suffit pas si le signer a été révoqué ou si la politique a changé.
Les erreurs de domaine doivent échouer fermement avant toute dépense du dépôt.

Suite : [bundlers autorisés](03-bundlers-et-signer.md).
