**Nom et prénom :** Takwa Ben Rhouma  
**Date :** 16 octobre 2026  
**Thème choisi :** L'IA générative

---

### 1. Ma tâche

**Quelle tâche ai-je demandé à l'IA de réaliser ?**  
Décrire en quelques lignes la tâche choisie.

**Exemple :**  
Je souhaite utiliser une IA générative pour préparer une explication simple de la notion d'IA générative, destinée à des élèves du secondaire (débutants).

---

### 2. Première tentative — Prompt V1

**Mon premier prompt :**  
Explique ce qu'est l'IA générative de manière très simple.

**Réponse obtenue :**  
L'IA générative est une branche de l'IA capable de créer du contenu original à partir de modèles appris sur de grandes bases de données. Au lieu de simplement analyser ou classer des données, elle génère de nouvelles informations en prédisant la suite la plus probable.

**Analyse de la réponse :**

* **Qu'est-ce qui est satisfaisant ?**  
  La réponse est correcte et précise. Elle explique bien la différence entre analyser et créer.  
* **Qu'est-ce qui pourrait être amélioré ?**  
  Le vocabulaire est un peu théorique et abstrait pour des débutants. Il manque un exemple concret.

---

### Qu'est-ce qui manque dans mon prompt ?

Cocher les éléments absents ou insuffisamment précisés :
* [x] Rôle
* [x] Contexte
* [x] Tâche précise
* [ ] Contraintes
* [ ] Format de sortie
* [x] Public cible

---

### 3. Deuxième tentative — Prompt V2

**Mon prompt amélioré :**  
Tu es un expert en technologie. Explique la notion d'IA générative à un débutant et ne dépasse pas 50 mots.

**Réponse obtenue :**  
En tant qu'expert, l'IA générative est une technologie capable de produire de nouveaux contenus (textes, images, sons) à partir d'exemples existants. Contrairement aux ordinateurs classiques qui exécutent seulement des règles fixes, l'IA générative apprend des motifs dans des milliards de données pour créer des choses originales.

---

### 4. Comparaison V1 / V2

* **Précision :** V1 : 1/2 | V2 : 2/2  
* **Pertinence :** V1 : 1.5/2 | V2 : 2/2  
* **Respect des contraintes :** V1 : 1/2 | V2 : 2/2  
* **Respect du format :** V1 : 1/2 | V2 : 2/2  
* **Clarté :** V1 : 1.5/2 | V2 : 2/2  
* **Total :** **V1 : 6/10** | **V2 : 10/10**  

**Pourquoi V2 est-elle meilleure ?**  
La version V2 est bien meilleure car elle intègre un rôle précis, un public cible défini et des instructions claires, ce qui permet d'obtenir une réponse plus adaptée et mieux structurée.

**Ai-je réellement obtenu une meilleure réponse ?**  
[x] Oui | [ ] Non | [ ] Partiellement  

**Justification :**  
Le vocabulaire est beaucoup plus adapté aux débutants.

---

### 5. Expérience Zero-shot / One-shot / Few-shot

#### 5.1 Zero-shot
* **Prompt :** Donne des exemples d'applications de l'IA générative.  
* **Réponse de l'IA :** ChatGPT, Gemini, Copilot.

#### 5.2 One-shot
* **Prompt :** Donne des exemples sous forme de nom et d'usage.  
  *Exemple : ChatGPT -> Générer du texte*  
* **Réponse de l'IA :**  
  ChatGPT -> Générer du texte  
  Gemini -> Générer du texte / Analyser et générer du code / Comprendre et analyser des images.

#### 5.3 Few-shot
* **Prompt :**  
  ChatGPT -> Générer du texte  
  Gemini -> Analyser des documents  
  Donne ainsi un 3ème exemple.  
* **Réponse de l'IA :**  
  DALL-E -> Générer des images à partir de texte.

---

### Comparaison

**Qu'avez-vous remarqué entre les trois approches ?**  
Plus on fournit d'exemples, plus la réponse de l'IA est précise et structurée.

**Selon vous, dans quelle situation le few-shot est-il utile ?**  
Il est très utile lorsqu'on souhaite obtenir un format de sortie très spécifique ou un style d'écriture particulier.

---

### 6. Auto-critique légère

**J'ai demandé à l'IA :**  
Analyse ta réponse précédente. Identifie deux points forts, deux faiblesses et propose deux améliorations.

**Résultat de l'auto-critique :**  
L'IA a identifié que ses explications étaient claires, mais qu'elle aurait pu ajouter un exemple visuel ou une analogie concrète.

**Est-ce que cette auto-critique garantit que la réponse me donne la bonne réponse ?**  
[ ] Oui | [x] Non

**Pourquoi ?**  
L'IA peut parfois passer à côté d'erreurs logiques, une vérification humaine reste indispensable.

---

### 7. Mon prompt final

Après les différentes expériences, rédiger une version finale améliorée :

> Tu es un expert en vulgarisation scientifique et technologique. Explique le concept de l'IA générative à un élève du secondaire (débutant). Structure ta réponse avec : une définition claire, une analogie concrète de la vie quotidienne, et trois exemples d'outils avec leurs usages. Contraintes : Utilise un vocabulaire simple, évite le jargon technique non expliqué, et ne dépasse pas 10 lignes.

**Quels éléments ai-je ajoutés ou modifiés ?**  
* [x] Rôle
* [x] Contexte
* [x] Tâche
* [x] Contraintes
* [x] Format
* [x] Exemples / few-shot
* [x] Critères de qualité
* [x] Vérification

---

### 8. Mon gabarit de prompt réutilisable

* **RÔLE :** Tu es un expert en vulgarisation scientifique et technologique.
* **CONTEXTE :** Le contexte est la préparation d'un cours d'initiation pour des débutants.
* **TÂCHE :** Ta tâche est d'expliquer un concept technologique complexe simplement.
* **CONTRAINTES :** Respecte les contraintes suivantes :
  * Vocabulaire simple
  * Éviter le jargon technique non expliqué
  * Limiter la réponse à 10 lignes
* **FORMAT :** Présente la réponse sous la forme suivante :  
  Définition, puis analogie, puis exemples.
* **CRITÈRES DE QUALITÉ :** La réponse doit être :
  * Claire
  * Percutante
  * Adaptée au public visé

---

### VÉRIFICATION
Indique les éléments incertains ou nécessitant une vérification. N'invente pas de source.

---

### 9. Ma réflexion personnelle

1. **Quel élément du prompt a eu le plus d'impact sur la réponse ?**  
   L'ajout du rôle et du public cible.
2. **Quelle erreur ai-je commise dans mon premier prompt ?**  
   Il était trop vague et manquait de précisions.
3. **Qu'ai-je appris en comparant V1 et V2 ?**  
   Un prompt structuré évite les réponses trop génériques de l'IA.
4. **Quand le few-shot est-il utile ?**  
   Pour imposer un format de réponse strict grâce à des exemples.
5. **Pourquoi faut-il vérifier une réponse produite par une IA ?**  
   L'IA peut générer des informations incorrectes.
6. **Dans quel autre domaine pourrais-je réutiliser mon gabarit ?**  
   Marketing / résumés / création de fiches de révision.

---

### 10. Auto-évaluation avant remise

* **Mon rôle est clairement défini :** Oui
* **Mon contexte est suffisamment précis :** Oui
* **Ma tâche est clairement formulée :** Oui
* **Mes contraintes sont explicites :** Oui
* **Le format de sortie est précisé :** Oui
* **J'ai testé au moins deux versions du prompt :** Oui
* **J'ai comparé les résultats :** Oui
* **J'ai expérimenté zéro-shot / one-shot / few-shot :** Oui
* **J'ai utilisé l'auto-critique de manière critique :** Oui
* **J'ai construit un gabarit réutilisable :** Oui
* **Je peux expliquer les améliorations apportées :** Oui

---

### À retenir

Un bon prompt ne consiste pas seulement à poser une question.  
**Rôle + Contexte + Tâche + Contraintes + Format**

Et surtout :  
**Je teste -> j'évalue -> j'améliore -> je vérifie.**
