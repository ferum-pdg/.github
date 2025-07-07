# Ferum
## Description
Application permettant de générer un plan d'entrainement personnalisé en fonction:
- des objectifs
- du niveau actuel
- de la disponibilité
- du risque de blessure

le tout disponible sur une application mobile.

### Besoins fonctionnels

1. Gestion des informations personnelles et de santé
    - L'utilisateur doit pouvoir créer un profil avec : poids, âge, taille.
    - L'utilisateur doit pouvoir signaler des blessures actuelles.
    - L'utilisateur doit pouvoir indiquer son activité physique actuelle.

2. Définition des objectifs
    - L'utilisateur doit pouvoir sélectionner au moins un objectif, par exemple : perte de poids ou prise de masse et définir une échéance pour l'atteindre.
    - L'utilisateur doit pouvoir mettre un objectif tel qu'un marathon ou semi-marathon à une date précise.
    - L'utilisateur doit pouvoir rentrer le temps qu'il souhaiterait effectuer pour un objectif d'endurance.

3. Evaluation du niveau actuel
    - L'utilisateur doit être capable d'entrer son niveau.

4. Disponibilité
    - L'utilisateur doit pouvoir indiquer ses jours/horaires disponibles pour s'entraîner.
    - Le système doit générer un plan adapté à cette disponibilité.

5. Connexion aux montres connectées
    - Le sytème doit pouvoir se connecter à des montres connectées et récupérer automatiquement le nombre de pas, la fréquence cardiaque, etc.

6. Génération du plan d'entraînement personnalisé.
    - Le système doit générer un plan d'entraînement basé sur :
        - Objectifs
        - Niveau actuel
        - Données de santé
        - Disponibilités hebdomadaires
        - Risque de blessure
        - Temps souhaité par l'utilisateur

7. Suivi et ajustements
    - L'utilisateur doit pouvoir suivre ses progrès.
    - Le système doit pouvoir ajuster le plan en fonction de la progression réelle.

8. Rappels
    - Le système doit pouvoir envoyer des rappels d'entraînement.

9. Interface utilisateur
    - L'utilisateur doit avoir une vue calendrier de son plan.
    - L'utilisateur doit pouvoir consulter les détails de chaque séance.

### Besoin non-fonctionnels


### Mockups



## Choix techniques
- Landing page: SvelteKit
- Backend: Java Enterprise, Quarkus
- App mobile: Flutter
- Site web: Flutter (ou SvelteKit) ->  nice to have
- Modèle IA: à voir ce qui est existant

## Processus de travail
