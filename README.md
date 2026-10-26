# Montpellier à domicile

Calendrier 2026/2027 des matchs à domicile du MHSC (foot), du MHR (rugby), du MHB (hand) et du Montpellier Volley.

Page publique : https://sylvainlefevre.github.io/SportMontpellier/

## Organisation

| Fichier | Rôle |
|---|---|
| `index.html` | La page. Elle ne contient aucune donnée et charge `data/matches.json`. |
| `data/matches.json` | Tous les matchs, avec pour chacun le statut de vérification et les sources. |
| `MISE_A_JOUR.md` | La procédure suivie chaque semaine (règle des deux sources). |
| `CHANGELOG.md` | Le journal des modifications, passage par passage. |

## Mise à jour

Une tâche planifiée revérifie le calendrier chaque mercredi matin et pousse les changements sur `main`. Une date ou un horaire n'est affiché comme confirmé que si deux sources indépendantes concordent.

Pour corriger un match à la main : modifier son entrée dans `data/matches.json`, puis commit et push. La page se met à jour en une à deux minutes.
