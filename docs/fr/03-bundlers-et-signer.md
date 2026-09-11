# 3 — Bundlers autorisés et rotation du signer

Le contrat peut restreindre le sponsoring à certains bundlers.
Cette liste réduit la surface opérationnelle mais crée une dépendance de disponibilité et de gouvernance.
L’ajout ou le retrait d’un bundler doit être observable et réservé au rôle prévu.
Le signer de vérification doit être distinct des clés de déploiement et de trésorerie.
Une rotation sûre annonce une période de transition ou invalide explicitement les signatures anciennes.
Le mode sans restriction ne doit pas être activé par défaut lors d’une migration.
Les procédures d’urgence doivent préciser qui peut couper le sponsoring sans déplacer les fonds des utilisateurs.

Suite : [paiement ERC-20](04-paiement-erc20.md).
