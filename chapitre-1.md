# Chapitre 1 — Introduction à l'Intelligence Artificielle et à l'IA Distribuée

## 1. Introduction à l'Intelligence Artificielle (AI)

### Pourquoi l'IA nous concerne tous
* **Pourquoi l'IA concerne tout le monde.**
* **Son importance pour la recherche scientifique.**

### Définition et concept
#### 📘 Définition
**L'Intelligence Artificielle (Artificial Intelligence - AI)** est une discipline de l'informatique qui cherche à doter les systèmes informatiques de capacités intellectuelles semblables à celles des êtres humains ou des êtres vivants.

### L'idée principale
> Les chercheurs se sont inspirés du cerveau humain pour créer des algorithmes d'Intelligence Artificielle.
> C'est de cette idée qu'est née l'Intelligence Artificielle.

### Algorithme clé
* **Artificial Neural Network (ANN)** → Réseau de neurones artificiels

---

## 2. La notion d'Agent autonome

### Définition
#### 📘 Définition
Un **Agent** est une entité autonome capable de prendre des décisions par elle-même.

### L'idée principale
> Un Agent vit dans un environnement, interagit avec d'autres agents et agit selon une organisation.

### Les 3 dimensions de l'Agent
```text
                  +----------------------+

                  |        Agent         |
                  |  (Entité autonome)   |
                  +----------+-----------+
                             |
      +----------------------+----------------------+

      |                      |                      |
      ▼                      ▼                      ▼
+-------------+      +---------------+      +----------------+

| Environment |      |  Interaction  |      | Organization   |
|             |      |               |      |                |
| - Outils    |      | - MCP         |      | - Workflow     |
| - Ressources|      | - A2A         |      | - Coordination |
+-------------+      +---------------+      +----------------+
```

#### 🌍 L'Environnement (Environment)
> Un agent évolue dans un environnement contenant les ressources (outils) nécessaires à l'accomplissement de sa tâche.

#### 🤝 L'Interaction
> Un agent peut communiquer et collaborer avec d'autres agents grâce à des protocoles de communication (ex. : MCP, A2A).

#### 🏢 L'Organisation (Organization)
> Les agents suivent une organisation (workflow) afin de coordonner leur travail.

### Synthèse de la section
#### 📝 Résumé
> Un Agent est une entité autonome qui vit dans un environnement, communique avec d'autres agents et travaille selon une organisation.

### Transition
> Nous venons de voir qu'un agent est une entité autonome. La question suivante est donc : que se passe-t-il lorsqu'on fait collaborer plusieurs agents ? C'est précisément le rôle de l'Intelligence Artificielle Distribuée que nous verrons au point suivant.

---

## 3. L'Intelligence Artificielle Distribuée (DAI)

### Définition et implémentation
#### 📘 Définition
L'Intelligence Artificielle Distribuée (DAI) est une branche de l'IA qui exploite l'intelligence collective de plusieurs agents, elle est généralement implémentée à l'aide de Systèmes Multi-Agents (SMA).

### La mécanique de la DAI
#### 💡 Idée principale
> L'objectif est de créer plusieurs agents autonomes. Chaque agent possède sa propre intelligence et une tâche précise. Les agents collaborent ensuite pour résoudre un problème ou atteindre un objectif commun.

#### 📝 À retenir
> Un seul agent = Intelligence individuelle.
> Plusieurs agents qui collaborent = Intelligence collective (DAI).

#### 🖼️ Schéma
```text
                  Intelligence Artificielle Distribuée (DAI)
                                  │
                                  ▼
                +--------------------------------------+

                | Intelligence Collective              |
                +--------------------------------------+
                                  │
                ┌─────────────────┼─────────────────┐
                ▼                 ▼                 ▼
           +---------+       +---------+       +---------+

           | Agent 1 |       | Agent 2 |  ...  | Agent n |
           +---------+       +---------+       +---------+
                │                 │                 │
                └─────────────────┴─────────────────┘
                                  │
                                  ▼
               Collaboration au sein d'un SMA
                                  │
                                  ▼
               Résolution d'un problème commun
```

#### 📖 Explication du schéma
> L'Intelligence Artificielle Distribuée repose sur plusieurs agents autonomes. Chaque agent réalise une tâche spécifique grâce à sa propre intelligence. En collaborant au sein d'un Système Multi-Agent (SMA), ils mettent en commun leurs capacités pour atteindre un objectif commun ou résoudre un problème complexe.

### L'Intelligence Individuelle
#### 📘 Définition
L'intelligence individuelle correspond à l'intelligence d'un seul agent autonome.

#### 💡 Idée principale
> Un seul agent prend ses propres décisions et accomplit sa tâche de manière autonome, sans collaboration avec d'autres agents.

#### 🖼️ Schéma
```text
        Intelligence Individuelle

                +---------+

                |  Agent  |
                +---------+
                     │
                     ▼
          Prend ses décisions
                     │
                     ▼
          Réalise sa tâche seul
```

#### 📖 Explication du schéma
> L'intelligence individuelle repose sur un seul agent. Il prend ses décisions de manière autonome et exécute sa tâche sans l'aide d'autres agents.

### Synthèse
#### 📝 À retenir
> 1 Agent = Intelligence individuelle. L'agent raisonne seul pour atteindre son objectif.
