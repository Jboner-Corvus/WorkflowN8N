# 🤖 Projet d'Assistant Robot Intelligent

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
 C'ests l'adresse IP de votre serveur. 


<div style="background-color: #f0f8ff; border-left: 6px solid #4285f4; padding: 15px; margin-top: 20px; margin-bottom: 20px; border-radius: 5px;">
  <strong>Salut !</strong> Bienvenue dans ce projet de construction. Ici, tu vas apprendre à assembler un assistant robot intelligent qui peut discuter avec toi et t'aider à accomplir des tâches.
</div>

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
* **Nom de code :** `<code>debugContextTool</code>`
* **Description :** Cet outil permet au robot de vérifier qui lui parle. C'est un peu comme un badge de sécurité qui confirme ton identité.

---

#### 🐢 L'outil Marathon
* **Nom de code :** `<code>asynchronousTaskSimulatorEnhanced</code>`
* **Description :** Pour les longues missions, comme un grand calcul. Le robot lance la tâche, te prévient qu'il a commencé, et t'envoie le résultat seulement quand il a fini. Idéal pour les processus qui prennent du temps.

---

#### ⚡ L'outil Sprinter
* **Nom de code :** `<code>synchronousExampleTool</code>`
* **Description :** Pour les tâches très rapides. Le robot fait ce que tu demandes et te donne la réponse immédiatement !

<br>

## Créez vos propres Outils ! 🎨

<div style="background-color: #e6ffed; border: 1px solid #34a853; border-radius: 8px; padding: 20px; text-align: center;">
  <h3>Le projet est modulaire !</h3>
  <p>Le plus amusant, c'est que tu peux inventer et ajouter tes propres outils à la boîte à outils du robot pour lui donner de nouveaux super-pouvoirs !</p>
  <p>N'hésite pas à expérimenter et à étendre les capacités de ton assistant.</p>
</div>