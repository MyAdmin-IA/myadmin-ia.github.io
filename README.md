# Pseudonymiseur

Outil web de pseudonymisation de textes, conçu pour la formation des personnels de Lyon 1 Université à la maîtrise de l'intelligence artificielle.

Page de l'outil : https://myadmin-ia.github.io/pseudonymiseur/

## Fonctionnement

- Le texte collé est traité entièrement dans le navigateur. Aucune donnée n'est envoyée sur le réseau et aucun serveur n'intervient.
- Les noms, adresses mail, liens, adresses postales, numéros (téléphone, IBAN, sécurité sociale, carte, identifiant), dates et entreprises sont remplacés par des codes, par exemple `Pseudo_Personne_001`.
- La table de correspondance reste sur le poste. Elle permet de restituer les données d'origine dans la réponse obtenue.
- Les réglages et les listes (prénoms, mots à conserver, villes, dictionnaire) sont enregistrés dans le navigateur de l'utilisateur.
- Un classeur Excel (.xlsx, .xlsm) peut être déposé tel quel : ses textes et les dates saisies dans ses cellules sont codés, le classeur codé est téléchargé avec ses onglets, formules et mises en forme intacts, et le classeur renvoyé par l'outil se restitue de la même façon, toujours dans le navigateur. Restent en clair : les noms d'onglets, les cellules saisies comme nombres, le texte écrit dans une formule et les dates calculées par une formule.
- Une page « Prompts » donne deux modèles de consigne à copier, l'un pour un texte, l'autre pour un classeur Excel : ils demandent à l'outil d'intelligence artificielle le travail voulu et lui interdisent de toucher aux codes. La page affiche le texte et le copie dans le presse-papiers, sans rien envoyer.

## Contenu du dépôt

- `pseudonymiseur/index.html` : l'application complète en un seul fichier (HTML, CSS et JavaScript), sans bibliothèque ni ressource externe.

## Auteur

Manoël PYANET, directeur administratif du département composante Génie Électrique et des Procédés, Lyon 1 Université. Première version le 28 septembre 2026, sous la forme d'un classeur Excel ; version web depuis le 19 octobre 2026.
