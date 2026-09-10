# AI Business Assistant 
# Partie 1 — Anatomie d’un prompt

## Problème

> Je souhaite analyser les retours de clients d'une entreprise.

## Prompt

Tu es un analyste spécialisé dans l'analyse des retours clients.

Analyse les commentaires clients que je vais te fournir.

Pour chaque commentaire, identifie :

* le sentiment exprimé : positif, négatif ou neutre ;
* les problèmes rencontrés par le client ;
* les points positifs éventuels ;
* les recommandations que l'entreprise pourrait prendre en compte.

Présente les résultats sous forme de tableau avec les colonnes suivantes :

| Commentaire | Sentiment | Problèmes | Points positifs | Recommandations |

Contraintes :

* base-toi uniquement sur les informations présentes dans les commentaires ;
* n'invente aucune information ;
* si une information n'est pas présente, indique « Non précisé » ;
* utilise un langage clair et professionnel.

Commentaires à analyser :

« Le service est rapide et le personnel est très sympathique. »

« J'ai attendu trois jours avant de recevoir ma commande. »

« L'application est intéressante mais elle plante régulièrement. »
