# Chapitre 2 — L'IA Générative

## 1. Introduction

Nous avons vu que l'Intelligence Artificielle permet à une machine d'analyser, de comprendre et de prendre des décisions.
Aujourd'hui, une nouvelle génération d'IA va plus loin : elle est capable de créer de nouveaux contenus.
C'est ce que l'on appelle **Intelligence Artificielle Générative** (*Generative AI*).

---

### Définition

L'**Intelligence Artificielle Générative (Generative AI)**) est une technologie capable de générer
 du contenu original (texte, image, code, musique, vidéo, etc.) à partir d'une simple instruction appelée Prompt.

---

### Schéma général

```text
        [ UTILISATEUR ]
              │
              ▼ Écrit une instruction
        [ LE PROMPT ]
(Ex. : "Rédige un e-mail professionnel")
              │
              ▼ Est traité par
    [ IA GÉNÉRATIVE ]
(Ex. : ChatGPT, Claude, Midjourney)
              │
              ▼ Génère
     [ CONTENU ORIGINAL ]
(Texte, Image, Code, Musique, etc.)
```

Le fonctionnement est relativement simple.

1. L'utilisateur formule une demande appelée **Prompt**.
2. Le modèle d'IA analyse cette demande.
3. L'IA génère un contenu correspondant à l'instruction reçue.
4. L'utilisateur peut ensuite modifier son Prompt afin d'améliorer le résultat obtenu.

Cette interaction entre l'utilisateur et l'IA constitue aujourd'hui le fonctionnement de la majorité des outils d'IA Générative.

---

# 2. Les raisons de son explosion

L'IA Générative est devenue possible grâce à la combinaison de **quatre avancées technologiques majeures**.

| Pilier                                | Rôle                                                                           | Exemples                                                                |
|---------------------------------------|--------------------------------------------------------------------------------|-------------------------------------------------------------------------|
| **Powerful Language Models (LLM)** 🧠 | Les modèles d'IA capables de comprendre le langage et de générer du contenu.   | GPT, Llama, Mistral                                                     |
| **Big Data** 📚                       | Les énormes quantités de données utilisées pour entraîner les modèles.         | Livres, sites web, articles, code...                                    |
| **GPU / TPU** 💪                      | La puissance de calcul nécessaire pour entraîner les modèles d'IA.             | NVIDIA GPU, Google TPU                                                  |
| **Cloud Computing** ☁️                | L'infrastructure qui héberge les modèles et les rend accessibles via Internet. | Microsoft Azure, Amazon Web Services (AWS), Google Cloud Platform (GCP) |

Ces quatre éléments sont complémentaires. Sans l'un d'eux, l'IA Générative moderne ne pourrait pas fonctionner à l'échelle actuelle.

> **À savoir :** Les modèles d'IA sont généralement accessibles via le **Cloud** (Internet). Cependant, des outils comme **Ollama** permettent aujourd'hui d'exécuter certains modèles (comme **Llama** ou **Mistral**) directement sur le GPU de son ordinateur, sans connexion Internet une fois le modèle téléchargé.
---

# 3. Les grandes familles de modèles

Il existe plusieurs familles de modèles d'IA Générative. 
Chaque modèle possède un objectif particulier selon le type de contenu qu'il doit produire.

| Modèle               | Rôle                                                          |
|----------------------|---------------------------------------------------------------|
| **GPT**              | Génère du texte à partir d'un Prompt.                         |
| **BERT**             | Comprend et analyse le langage naturel.                       |
| **GAN**              | Génère des images réalistes grâce à deux réseaux de neurones. |
| **DALL·E**           | Génère des images à partir d'une description textuelle.       |
| **Stable Diffusion** | Génère et modifie des images à partir d'un texte.             |
| **Midjourney**       | Génère des images artistiques à partir d'un texte.            |
---

# 4.L'évolution de l'IA Générative

L'IA Générative ne s'est pas construite en un jour.
Depuis 2014, plusieurs innovations majeures ont permis de créer des modèles toujours plus performants.

| Date     | Innovation                                             | Contribution                                                                           | Exemple                            |
|----------|--------------------------------------------------------|----------------------------------------------------------------------------------------|------------------------------------|
| **2014** | **GAN**(Ian Goodfellow)                                | Première génération d'images réalistes par l'IA.                                       | StyleGAN                           |
| **2017** | **Transformer**(Google)                                | Nouvelle architecture qui révolutionne le traitement du langage. Base des LLM modernes | Attention Is All You Need          |
| **2018** | **BERT**(Google)                                       | Comprend et analyse le langage naturel.                                                | Recherche d'information            |
| **2018** | **GPT**(OpenAI)                                        | Génère du texte à partir d'un prompt.                                                  | ChatGPT                            |
| **2019** | **StyleGAN**                                           | Améliore fortement le réalisme des images générées.                                    | Visages artificiels                |
| **2020** | **GPT-3**                                              | Premier LLM très performant.                                                           | Génération de texte                |
| **2021** | **CLIP & DALL·E**                                      | Associent texte et image.                                                              | DALL·E                             |
| **2022** | **ChatGPT & DALL·E 2**                                 | Démocratisent l'IA Générative auprès du grand public.                                  | ChatGPT                            |
| **2023** | **GPT-4, Gemini, Llama, Stable Diffusion, Midjourney** | Explosion des modèles multimodaux et open source.                                      | GPT-4, Gemini, Llama 3, Midjourney |

### 📌 À retenir
```text
2014 → GAN
      │
      ▼
2017 → Transformer ⭐
      │
      ▼
2018 → BERT + GPT
      │
      ▼
2020 → GPT-3
      │
      ▼
2022 → ChatGPT
      │
      ▼
2023 → Explosion de l'IA Générative
```

### ⭐ Point clé :
Le **Transformer (2017)** est la technologie qui a rendu possible les modèles modernes d'IA Générative,
tels que **GPT, BERT, Llama, Gemini, Claude et Mistral**.

---

# 5. Les limites majeures à garder en tête

L'IA Générative est un outil puissant,
mais elle possède des **limites techniques** et présente des **limites d'utilisation** que tout utilisateur doit connaître.

#### A. Les limites techniques
#### Les hallucinations
L'IA peut générer des fausses informations tout en donnant l'impression qu'elles sont exactes.
#### L'esprit critique
Les réponses de l'IA doivent toujours être vérifiées avant d'être utilisées, en particulier pour des informations importantes.

#### B. Les limites d'utilisation
#### La confidentialité (RGPD)
Ne partagez jamais de données personnelles, confidentielles ou sensibles avec une IA en ligne.
#### Le droit d'auteur (Copyright)
Les contenus générés par l'IA peuvent soulever des questions de propriété intellectuelle.
#### L'impact environnemental
L'entraînement et l'utilisation des modèles d'IA consomment d'importantes quantités d'électricité et d'eau.

---
# 6. Transition vers le Prompt Engineering
Pour générer un contenu (**Output**), l'IA Générative a besoin d'une instruction appelée **Prompt**.
Le chapitre suivant est consacré au Prompt Engineering : l'art de communiquer efficacement avec une IA.




