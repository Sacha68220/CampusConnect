# CampusConnect

> Plateforme permettant aux étudiants de découvrir les événements universitaires et de s'y inscrire.

![Statut](https://img.shields.io/badge/statut-en%20conception-orange)

## Sommaire

- [Présentation](#présentation)
- [État du projet](#état-du-projet)
- [Fonctionnalités envisagées](#fonctionnalités-envisagées)
- [Outils de l'équipe](#outils-de-léquipe)
- [Documentation](#documentation)
- [Contribuer](#contribuer)
- [Équipe](#équipe)

## Présentation

Les événements du campus (conférences, ateliers, forums, activités associatives…) sont aujourd'hui annoncés sur des canaux dispersés. **CampusConnect** vise à les centraliser en un seul endroit.

**Objectifs :**

- Centraliser l'offre d'événements universitaires.
- Aider les étudiants à trouver rapidement les événements qui les intéressent.
- Simplifier l'inscription tout en respectant la capacité de chaque événement.
- Donner aux organisateurs une visibilité sur les participants.

## État du projet

🟠 **Phase de conception.**

Le projet est développé dans le cadre d'un module de gestion de projet Agile (Scrum). À ce jour :

| Élément | État |
|---|---|
| User Stories et Product Backlog | ✅ Rédigés (Jira) |
| Spécifications fonctionnelles | 🟡 En cours (Confluence) |
| Diagrammes UML | ✅ Première version (`uml/`) |
| Code de l'application | ⬜ Pas encore commencé |

Il n'existe donc **pas encore d'application à installer ni à exécuter**. Cette section sera mise à jour lorsque le développement démarrera.

## Fonctionnalités envisagées

> Aucune de ces fonctionnalités n'est implémentée à ce jour.

| Fonctionnalité | Acteur | User Story Jira |
|---|---|---|
| Consulter les événements à venir | Étudiant | CC-1 |
| Rechercher et filtrer les événements (date, catégorie, lieu) | Étudiant | CC-2 |
| S'inscrire à un événement | Étudiant | CC-3 |
| Annuler son inscription | Étudiant | CC-4 |
| Créer, modifier et annuler un événement | Organisateur | CC-5 |
| Consulter la liste des inscrits | Organisateur | CC-6 |

## Outils de l'équipe

| Outil | Usage |
|---|---|
| **Jira** | Product Backlog, User Stories, Sprints, suivi des tâches |
| **Confluence** | Documentation fonctionnelle, technique, Agile et guide utilisateur |
| **GitHub** | Versionnement de la documentation, des diagrammes et, plus tard, du code |
| **PlantUML** | Diagrammes UML sous forme de fichiers texte versionnables |

## Documentation

- 📘 **Espace Confluence CampusConnect :** [lien à insérer]
- 📄 **Spécification « S'inscrire à un événement » (SPEC-01) :** [lien Confluence à insérer]
- 🗂️ **Product Backlog Jira :** [lien à insérer]

**Diagrammes UML (sources modifiables) :**

- [Diagramme de cas d'utilisation](uml/cas-utilisation.puml)
- [Diagramme de classes](uml/classes.puml)
- [Diagramme de séquence — Inscription](uml/sequence-inscription.puml)

Pour les visualiser : coller le contenu d'un fichier `.puml` sur [plantuml.com](https://plantuml.com/fr/) ou utiliser l'extension PlantUML de votre éditeur.

## Contribuer

1. **Partir d'une User Story Jira** : toute modification doit être rattachée à une clé `CC-x`.
2. **Créer une branche** nommée d'après la story : `CC-3-specification-inscription`.
3. **Messages de commit** clairs, préfixés par la clé Jira : `CC-3 Ajoute le scénario alternatif "événement complet"`.
4. **Ouvrir une Pull Request** vers `main` et demander la relecture d'au moins un autre membre.
5. **Garder la cohérence** : si une règle métier change, mettre à jour la page Confluence, la story Jira et les diagrammes concernés.
6. **Ne jamais committer** de données personnelles ou confidentielles (vraies listes d'étudiants, identifiants…).

## Équipe

| Rôle | Membre |
|---|---|
| Product Owner | [Nom] |
| Scrum Master | [Nom] |
| Développeurs | [Noms] |
