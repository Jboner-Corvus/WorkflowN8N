# 🤖 Projet d'Assistant Robot Intelligent

![Icône MCP](https://placehold.co/128x128/f0f8ff/4285f4?text=mcp.png)
![Agent de flux de travail](https://placehold.co/800x200/cccccc/333333?text=Workflow_agent.bmp)

## ✅ Étape 1 : Prérequis - Les Outils Essentiels

Pour construire notre projet, nous avons besoin de trois éléments fondamentaux : la machine, un moyen de s'y connecter et une adresse pour la trouver.

### 1. Le Serveur (La Machine)
Il nous faut un ordinateur distant qui fonctionnera 24h/24.
* **Un Serveur Privé Virtuel (VPS)** : C'est un ordinateur que vous louez.
* **Système d'Exploitation Linux** : C'est le "cerveau" du serveur. Pour ce guide, nous utilisons spécifiquement **Ubuntu 22.04**, mais d'autres distributions Linux (comme Debian) fonctionneraient avec de légères adaptations.

### 2. La Connexion (La Clé d'Accès)
Pour communiquer avec notre serveur de manière sécurisée, nous utilisons le protocole SSH.
* **Un client SSH** : C'est le logiciel sur **votre ordinateur personnel** qui vous permet de vous connecter.
    * **Windows :** Le Terminal Windows, PowerShell, ou un outil comme [PuTTY](https://www.putty.org/).
    * **macOS / Linux :** L'application "Terminal" est déjà installée.

### 3. L'Adresse (Le Panneau Indicateur)
C'est l'adresse IP de votre serveur.

> **Salut !** Bienvenue dans ce projet de construction. Ici, tu vas apprendre à assembler un assistant robot intelligent qui peut discuter avec toi et t'aider à accomplir des tâches.

## Que fait ce robot ? 🧐

C'est un **agent conversationnel**. C'est un nom un peu savant pour dire que c'est un programme avec qui tu peux dialoguer. Le processus est simple :

1.  **Tu lui écris un ordre ou une question.**
2.  Le robot utilise son puissant processeur (une **Intelligence Artificielle de Google**) pour comprendre et réfléchir.
3.  Il a une bonne mémoire et **se souvient du contexte** de vos conversations précédentes.
4.  Il te **répond en français**, de manière claire et précise !

<br>

## La boîte à outils du Robot (Les Outils MCP) 🧰

Notre robot possède une "boîte à outils" spéciale qui lui donne des capacités uniques. Ces outils lui sont fournis par un ordinateur assistant, le **serveur MCP** (Maître de Contrôle du Projet).

---

#### 🕵️ L'outil d'identification
* **Nom de code :** `debugContextTool`
* **Description :** Cet outil permet au robot de vérifier qui lui parle. C'est un peu comme un badge de sécurité qui confirme ton identité.

---

#### 🐢 L'outil Marathon
* **Nom de code :** `asynchronousTaskSimulatorEnhanced`
* **Description :** Pour les longues missions, comme un grand calcul. Le robot lance la tâche, te prévient qu'il a commencé, et t'envoie le résultat seulement quand il a fini. Idéal pour les processus qui prennent du temps.

---

#### ⚡ L'outil Sprinter
* **Nom de code :** `synchronousExampleTool`
* **Description :** Pour les tâches très rapides. Le robot fait ce que tu demandes et te donne la réponse immédiatement !

<br>

## Créez vos propres Outils ! 🎨

> ### Le projet est modulaire !
> Le plus amusant, c'est que tu peux inventer et ajouter tes propres outils à la boîte à outils du robot pour lui donner de nouveaux super-pouvoirs !
>
> N'hésite pas à expérimenter et à étendre les capacités de ton assistant.