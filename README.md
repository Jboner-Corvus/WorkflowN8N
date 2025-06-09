# ![Icône MCP](./assets/mcp.png) Projet d'Assistant Agent Intelligent

![Agent de flux de travail](./assets/Workflow_agent.bmp)

## ✅ Étape 1 : Prérequis - Les Outils Essentiels

Pour construire notre projet, nous avons besoin de trois éléments fondamentaux : la machine, un moyen de s'y connecter et une adresse pour la trouver.

### 1. Le Serveur (La Machine)
Il nous faut un ordinateur distant qui fonctionnera 24h/24.
* **Un Serveur Privé Virtuel (VPS)** : C'est un ordinateur que vous louez.
* **Système d'Exploitation Linux** : C'est le "cerveau" du serveur. Pour ce guide, nous utilisons spécifiquement **Ubuntu 22.04**.

### 2. La Connexion (La Clé d'Accès)
Pour communiquer avec notre serveur de manière sécurisée, nous utilisons le protocole SSH.
* **Un client SSH** : C'est le logiciel sur **votre ordinateur personnel** qui vous permet de vous connecter.
    * **Windows :** Le Terminal Windows, PowerShell, ou un outil comme [PuTTY](https://www.putty.org/).
    * **macOS / Linux :** L'application "Terminal" est déjà installée.

### 3. L'Adresse (Le Panneau Indicateur)
C'est l'adresse IP de votre serveur.

> **Salut !** Bienvenue dans ce projet de construction. Ici, tu vas apprendre à assembler un assistant agent intelligent capable non seulement de discuter avec toi, mais aussi de t'aider à accomplir des tâches.

## Que fait cet agent ? 🧐

C'est un **agent intelligent** qui va bien au-delà du simple dialogue. Il est conçu pour comprendre vos besoins et agir en conséquence. Le processus est simple :

1.  **Tu lui donnes un ordre, une question ou une tâche à accomplir.**
2.  L'agent utilise son puissant processeur (une **Intelligence Artificielle de Google**) pour comprendre, réfléchir et planifier une action.
3.  Il a une bonne mémoire et **se souvient du contexte** de vos conversations précédentes pour mieux vous assister.
4.  Il vous **répond**, mais peut aussi **agir** en utilisant sa boîte à outils pour exécuter des tâches concrètes.

## La boîte à outils de l'Agent (Les Outils MCP) 🧰

Notre agent possède une "boîte à outils" spéciale qui lui donne des capacités uniques. Ces outils lui sont fournis par un ordinateur assistant, le **serveur MCP** (Maître de Contrôle du Projet).

#### 🕵️ L'outil d'identification
* **Nom de code :** `debugContextTool`
* **Description :** Cet outil permet à l'agent de vérifier qui lui parle. C'est un peu comme un badge de sécurité qui confirme votre identité.

#### 🐢 L'outil Marathon
* **Nom de code :** `asynchronousTaskSimulatorEnhanced`
* **Description :** Pour les longues missions, comme un grand calcul. L'agent lance la tâche, vous prévient qu'il a commencé, et vous envoie le résultat seulement quand il a fini.

#### ⚡ L'outil Sprinter
* **Nom de code :** `synchronousExampleTool`
* **Description :** Pour les tâches très rapides. L'agent fait ce que vous demandez et vous donne la réponse immédiatement !

## Créez vos propres Outils ! 🎨

> ### Le projet est modulaire !
> Le plus amusant, c'est que vous pouvez inventer et ajouter vos propres outils à la boîte à outils de l'agent pour lui donner de nouveaux super-pouvoirs !
> N'hésitez pas à expérimenter et à étendre les capacités de votre assistant.

---
## 🚀 Au-delà de l'Agent : Vers l'Organisation Numérique

Ce projet est la première brique. Mais en assemblant plusieurs agents, chacun avec des compétences spécifiques, on peut créer bien plus qu'un assistant : une véritable **organisation numérique**.

Imaginez un **agent "manager"** qui reçoit un objectif complexe et le décompose en plusieurs sous-tâches. Il les distribue ensuite à des **agents "spécialistes"** :
* Un expert en recherche web.
* Un analyste de données.
* Un rédacteur technique.
* Un programmeur.

Ces agents collaborent pour accomplir une mission d'envergure. En maîtrisant la création d'un agent, vous faites le premier pas pour orchestrer demain une **entreprise entièrement numérique**.