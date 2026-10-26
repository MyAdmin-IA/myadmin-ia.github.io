# Pseudonymiseur

Outil web de pseudonymisation de textes, conçu pour la formation des personnels de Lyon 1 Université à la maîtrise de l'intelligence artificielle.

Page de l'outil : https://myadmin-ia.github.io/pseudonymiseur/

## Fonctionnement

- Le texte collé est traité entièrement dans le navigateur. Aucune donnée n'est envoyée sur le réseau et aucun serveur n'intervient.
- Les noms, adresses mail, liens, adresses postales, numéros (téléphone, IBAN, sécurité sociale, carte, identifiant), dates et entreprises sont remplacés par des codes, par exemple `Pseudo_Personne_001`.
- La table de correspondance reste sur le poste. Elle permet de restituer les données d'origine dans la réponse obtenue.
- Les réglages et les listes (prénoms, mots à conserver, villes, dictionnaire) sont enregistrés dans le navigateur de l'utilisateur.

## Contenu du dépôt

- `pseudonymiseur/index.html` : l'application complète en un seul fichier (HTML, CSS et JavaScript), sans bibliothèque ni ressource externe.

## Auteur

Manoël PYANET, directeur administratif du département composante Génie Électrique et des Procédés, Lyon 1 Université. Outil créé le 19 octobre 2026.
