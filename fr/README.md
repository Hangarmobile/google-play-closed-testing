# Test fermé Google Play : le guide pratique

Les comptes développeur Google Play **personnels créés après le 13 novembre 2023** doivent faire un **test fermé avec au moins 12 testeurs, inscrits pendant 14 jours d'affilée**, avant de pouvoir publier en production. Ce dépôt est un guide gratuit et pratique pour passer cette étape du premier coup.

- [Checklist](CHECKLIST.md) : tout ce qu'il faut vérifier avant de demander l'accès à la production.
- [Plan sur 14 jours](PLAN.md) : quoi faire chaque jour du test.
- [Réponses au formulaire de production](ACCES-PRODUCTION.md) : les questions de Google, avec des exemples de réponses faibles et solides.
- [Modèle de suivi des testeurs](../templates/tester-log.csv) : un fichier CSV à ouvrir dans Google Sheets ou Excel.

## La règle en bref

| | |
|---|---|
| Qui | Comptes personnels créés après le 13/11/2023 (les comptes organisation et les anciens comptes personnels ne sont pas concernés) |
| Combien de testeurs | Au moins 12, inscrits à un test **fermé** (le test interne ne compte pas) |
| Combien de temps | Les 14 derniers jours, sans interruption. Un testeur qui se désinscrit puis se réinscrit recommence ses 14 jours |
| Ensuite | Demander l'accès à la production depuis le tableau de bord de la Play Console et remplir le formulaire. L'examen prend en général jusqu'à 7 jours |

La règle était de 20 testeurs jusqu'en décembre 2024. Beaucoup de tutoriels disent encore 20 : c'est 12 aujourd'hui.

## Pourquoi les tests sont refusés

Google cite un **engagement insuffisant des testeurs** parmi les raisons de demander plus de test. Les causes habituelles :

1. Des testeurs qui s'inscrivent une fois et n'ouvrent jamais l'appli.
2. Aucune nouvelle version publiée pendant les 14 jours.
3. Des réponses vagues dans le formulaire d'accès à la production.
4. Des testeurs qui abandonnent avant le 14e jour (recrutez-en 14 ou 15, pas 12 pile).

## Qui entretient ce guide

[Hangar](https://hangarmobile.com/). Nous faisons aussi [PlayTesterHub](https://playtesterhub.com/fr), un service de test fermé sur 12 vrais téléphones Android en France. Ce guide présente toutes les options, gratuites comprises.

Source officielle : [Aide Play Console, exigences de test pour les nouveaux comptes personnels](https://support.google.com/googleplay/android-developer/answer/14151465?hl=fr).
