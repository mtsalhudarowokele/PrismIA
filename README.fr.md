# PrismIA - Méthodologie de Recrutement Assistée par IA

> Un cadre expérimental explorant comment l'IA peut réduire les biais et améliorer l'efficacité des flux de travail d'acquisition de talents.

## À Propos de ce Projet

En tant que recruteur junior apprenant les outils de recrutement alimentés par l'IA, j'ai conçu cette méthodologie pour comprendre comment les grands modèles de langage (Claude, GLM, GPT) pourraient systématiquement assister les décisions de recrutement tout en minimisant les biais inconscients.

**Ce que c'est :** Une collection de 8 prompts système implémentant une approche structurée et basée sur des preuves pour l'évaluation des candidats.

**Ce que ce n'est pas :** Un logiciel de production ou une méthodologie éprouvée. Il s'agit d'un projet d'apprentissage développé à travers la recherche personnelle et l'expérimentation.

## Motivation

Après avoir travaillé avec des modèles d'IA depuis 2022 et complété mon premier placement (pro bono, 3 heures du sourcing à la recommandation), je voulais formaliser le processus que j'avais utilisé. Le recrutement traditionnel repose souvent sur l'instinct - je voulais explorer si l'IA pouvait aider à prendre des décisions plus objectives et basées sur les données.

## Caractéristiques Principales

- **Système de Notation sur 100 Points** : Grilles d'évaluation transparentes (30% comportemental, 70% technique)
- **Double Points de Contrôle des Biais** : Étapes de révision intégrées qui remettent en question le raisonnement subjectif
- **Flux de Travail en 8 Étapes** : De l'analyse sémantique du CV jusqu'à la sélection finale
- **Évaluation Multi-Modale** : Protocoles d'évaluation textuelle, comportementale et technique
- **Cadre Asynchrone** : Conçu pour les flux de travail d'embauche en mode distant

## Prompts Système

| Prompt | Objectif | Caractéristique Clé |
|--------|---------|-------------|
| `RecruiterRP.md` | Simulation d'entrevue | Jeu de rôle réaliste avec notation dynamique |
| `CandidateRP.md` | Scénarios du point de vue du candidat | Développement de l'empathie pour les recruteurs |
| `CVAnalysis.md` | Analyse de CV | Analyse sémantique NLP au-delà des mots-clés |
| `Communication.md` | Engagement des candidats | Messagerie personnalisée automatisée |
| `Outreach-PreQualifScreening.md` | Contact initial + présélection | Filtrage par critères éliminatoires |
| `Assessment.md` | Tests techniques/comportementaux | Cadre d'évaluation complet |
| `InterviewFeedback.md` | Analyse post-entrevue | Collecte de rétroaction structurée |
| `IntreviewDebate.md` | Cadre de discussion | Prise de décision collaborative |

## Comment Utiliser

Ces prompts sont conçus pour être utilisés avec des assistants IA (GPT-4, Claude 3.5 Sonnet, etc.) :

1. Choisissez le prompt approprié pour votre étape de recrutement
2. Copiez le prompt système dans votre assistant IA
3. Suivez le flux de travail structuré décrit dans le prompt
4. Documentez les scores et décisions pour la révision des biais

**Note :** Ce sont des prompts expérimentaux que j'ai développés pendant mon apprentissage. Ils n'ont pas été testés dans des environnements de production.

## Technologies Référencées

- **LLMs (par ordre de préférence)** : Claude 4.5 Sonnet 32k, GLM 4.6, GPT 5 High
- **Méthodologie** : Cadre Universel de Présélection Asynchrone
- **Évaluation** : Grilles de notation transparentes sur 100 points

## Limites

- **Aucun test en production** : Développé par la recherche personnelle, non validé dans de vrais pipelines d'embauche
- **Perspective junior** : Créé par quelqu'un qui apprend le recrutement par IA, pas un praticien senior
- **Cadre théorique** : Se concentre sur la conception de la méthodologie plutôt que sur l'implémentation

## Apprentissages

En construisant ce projet, j'ai acquis une compréhension de :

- L'ingénierie de prompts structurée pour des flux de travail complexes
- Les stratégies d'atténuation des biais dans la prise de décision assistée par IA
- L'équilibre entre l'automatisation par IA et le jugement humain
- L'importance de critères d'évaluation transparents

## Améliorations Futures

- [ ] Tester les prompts avec de vraies données de candidats (anonymisées)
- [ ] Ajouter des métriques de validation quantitative
- [ ] Développer des guides d'intégration pour les plateformes ATS
- [ ] Créer des versions simplifiées pour différents niveaux de séniorité
- [ ] Ajouter le support multilingue (français/anglais)

## Contribuer

Les commentaires et suggestions sont les bienvenus ! En tant que personne en début de carrière en recrutement, je suis ouvert à l'apprentissage auprès de praticiens expérimentés.

Si vous voyez des domaines d'amélioration :
- Ouvrez un problème (issue) décrivant le problème
- Suggérez des améliorations de la méthodologie
- Partagez votre expérience si vous testez ces prompts

## Contexte

Ce projet représente environ 40 heures de recherche et développement itératifs en octobre 2025. Il synthétise des concepts issus de :

- Tests de modèles d'IA
- 21+ analyses précises de profils de candidats générés par IA durant la validation de la méthodologie
- Étude de cadres modernes d'acquisition de talents

## Auteur

**Gabriel Jossic**  
Recruteur Junior Alimenté par l'IA | Rimouski, QC  
[LinkedIn](https://www.linkedin.com/in/gabriel-jossic) | gabriel@jossic.net

---

*Construit avec curiosité sur la façon dont l'IA peut rendre l'embauche plus équitable et efficace.*
