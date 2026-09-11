# 1 — Rôle du paymaster ERC-4337

Le VerifyingPaymaster finance une UserOperation après validation par EntryPoint v0.7.
Il ne remplace ni le compte intelligent ni le bundler : il accepte ou refuse de payer le gas.
La signature du service engage une politique hors chaîne dont le contrat vérifie la preuve.
Le dépôt du paymaster dans EntryPoint est un actif exposé aux abus de validation et d’exécution.
Une opération sponsorisée reste soumise aux règles du compte, du nonce et de la chaîne cible.
Pour un utilisateur Bitcoin ou Ordinals arrivant sur Base, le sponsoring simplifie l’accès sans transférer la garde des actifs.
La frontière de confiance principale relie signer, paymaster, EntryPoint et bundler.

Suite : [domaine signé](02-domaine-signe.md).
