# 5 — Griefing et limites économiques

Un attaquant cherche moins à voler qu’à faire payer au sponsor des validations ou exécutions inutiles.
La politique hors chaîne doit plafonner gas, fréquence, compte, cible et méthode autorisée.
Une opération qui revert peut néanmoins consommer du gas sponsorisé selon le chemin atteint.
Les quotas doivent être atomiques ou résistants aux soumissions concurrentes de la même autorisation.
Le bundler ne doit pas pouvoir substituer un contexte non engagé par la signature.
Le monitoring suit dépôt EntryPoint, taux de rejet, coût par compte et concentration par cible.
Un coupe-circuit doit arrêter de nouvelles autorisations avant épuisement du dépôt.

Suite : [checklist opérationnelle](06-checklist-operationnelle.md).
