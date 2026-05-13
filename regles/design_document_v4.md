# PROJET : Système Core Moderne/Sci-Fi — Document de Design v4
## "La méthode Nimble appliquée à Ultramodern5"

> **Changements v4 :** 15 niveaux (au lieu de 20). Proficiency +1/+2/+3 (au lieu de +2 à +6). Loot comme deuxième jambe de progression (+0 à +3). Push de jet (Dragonbane-style). 4 conditions liées aux 4 stats. Dégradation d'équipement (Neuf/Endommagé/Détruit). 3 augmentations de stats. Ennemis difficiles uniquement via Désavantage. 5 classes core (au lieu de 11). Formules canoniques v2 fait foi pour tous les chiffres.

---

## DÉCISIONS VERROUILLÉES

| Question | Décision |
|----------|----------|
| Caractéristiques | **4 stats pures : STR, DEX, WIT, EMP** (valeurs directes 7-11, roll-under). Bonus = valeur - 8. |
| Compétences | **20 skills** (13 générales + 7 trained-only ★). Basées sur UM5, réparties sur 4 stats. Perception (WIT) ≠ Intuition (EMP). |
| Résolution | **Roll-under d20.** Score = stat + proficiency + bonus loot. Seuil = Score - Difficulté. Rouler ≤ seuil = touché. |
| Toucher | **Pas de défense passive.** Difficulté = 0 par défaut. Les ennemis difficiles imposent **Désavantage** (pouvoirs de monstre, conditions), jamais de difficulté numérique. Couverture partielle = +2 Armure (pas un malus au jet). |
| Niveaux | **15 niveaux.** Trois arcs : Recrue (1-5), Vétéran (6-10), Élite (11-15). |
| Proficiency | **+1 (niv 1-5), +2 (niv 6-10), +3 (niv 11-15).** Jambe stable de la progression. |
| Loot | **Deuxième jambe de progression.** Bonus +0 à +3 via armes, viseurs, implants. Volatile — sujet à rotation (dégradation, vol, destruction). |
| Push de jet | **Dragonbane-style.** Relancer un jet raté. Coût : condition (Désavantage sur 1 stat) OU dégradation d'équipement. |
| Conditions | **4 conditions sur 4 stats :** Épuisé (STR), Déstabilisé (DEX), Confus (WIT), Stressé (EMP). Chaque condition = Désavantage sur tous les jets de la stat. |
| Dégradation loot | **3 états : Neuf → Endommagé → Détruit.** Endommagé = bonus divisé par 2. Détruit = inutilisable. |
| Stat increases | **3 augmentations** aux niveaux 4, 8, 12 (stat au choix, pas de restriction principale/secondaire). |
| Dégâts | Dés d'arme + bonus de dégâts (stat 8-9 = +1d4, stat 10-12 = +1d6, stat 13+ = +1d8. PJ uniquement). **Minimum 1 dégât** par attaque réussie. |
| Armure | **Passive** — toujours active. Couverture partielle ajoute +2 à l'Armure. |
| Mouvement | **Grille tactique, 6 cases de base** (Nimble). Sprint = 2 actions. |
| Tir automatique | **2 actions.** Jusqu'à 3 cibles, save DEX, dégâts "auto" (dé supérieur). **Shaken garanti** même sur save réussi. |
| Munitions | **Abstraction narrative.** Pas de tracking. Outil scénaristique du MJ si besoin. |
| Mêlée | Réaction possible au corps à corps pour parer. |
| Shaken | Niveaux 1/2/3. Chaque hit = +1 niveau. Dure **1 round max**. Save STR ou WIT début de tour (pas de diff). |
| Économie d'actions | 3 actions par tour (modèle Nimble). |
| Initiative | **Cartes d'initiative (Dragonbane).** Retirage chaque round. Boss = 2+ cartes. |
| Gestion du temps | **Round (~10s), Stretch (~15min), Shift (~6h).** 4 shifts/jour. |
| Catégories d'ennemis | **Minion** (1 touche = mort), **Adversaire** (PV/Blessures normaux), **Boss** (2+ cartes, réactions). |
| Tech Levels | Système TL 0-5 d'Ultramodern5 intégré. |
| Crafting | Basé sur le toolkit Genesys (Hard Points, Qualités, Attachments). |
| Classes | **5 classes core** : Grounder, Infiltrator, Medic, Marshal, Tech. |
| Points de vie | **Pool unique : PV + PV.** PV = ablation. Blessures = blessures réelles. Crits infligent 1 Blessure → PV. |
| Vigueur | **Indice de durabilité par classe** (6, 8, 10). Valeur fixe, pas de dé. |
| Guérison | **Healing Surges** (inspiré 4e). Modèle restrictif : déclencheurs obligatoires. |
| Repos | **Restrictif.** Second Wind 1×/combat. Stretch Rest = 1 surge. Shift Rest = tout revient. Max 2 Stretch entre chaque Shift. |
| Compatibilité 5e | Oui, comme Nimble — conversion rapide des modules et monstres existants. |

---

## 1. CARACTÉRISTIQUES — 4 STATS PURES

> **Changement v3 :** Le modèle 4+2 (STR/DEX/INT/CHA + CON/WIL) est abandonné. CON et WIL sont supprimés. Le système passe à 4 stats pures exprimées en **valeurs directes** (7-11, inspiré Dragonbane) pour le roll-under. Le bonus (valeur - 8) remplace les modificateurs D&D 5e.

### Les 4 stats

| Stat | Abréviation | Domaine | Sauvegarde |
|------|-------------|---------|------------|
| **Force** | STR | Mêlée, puissance brute, endurance, résistance physique. Absorbe l'ancien rôle de CON. | Résistance corporelle : poisons, maladies, drogues, torture physique, températures extrêmes, mouvement forcé. "Est-ce que ton corps tient ?" |
| **Dextérité** | DEX | Tir, réflexes, esquive, agilité, discrétion, armes légères. | Réflexes : explosions, pièges, embuscades, terrain instable. "Est-ce que tu esquives ?" |
| **Esprit** | WIT | Acuité mentale, observation, analyse, raisonnement, concentration, hacking, tactique, sciences, médecine, ingénierie. Perception du *monde*. | Résistance mentale analytique : illusions, hacking neural, confusion, désinformation, maintien de concentration. "Est-ce que ton esprit résiste ?" |
| **Empathie** | EMP | Intelligence sociale, lecture émotionnelle, connexion humaine, leadership, négociation, intimidation sociale. Perception des *gens*. | Résistance émotionnelle : peur, charme, intimidation, manipulation, interrogatoire, torture psychologique. "Est-ce que tu résistes à la pression sociale ?" |

### Deux axes de perception

Le système distingue deux types de perception fondamentalement différents :

- **WIT → Perception de l'environnement.** Observer une scène de crime, repérer un piège, détecter une anomalie dans un système, voir le mouvement à 500m. C'est l'esprit analytique appliqué au monde physique.
- **EMP → Perception des gens.** Sentir qu'on te ment, percevoir la tension dans une pièce, lire les intentions d'un interlocuteur, sentir le moral d'une équipe. C'est l'intelligence sociale appliquée aux êtres humains.

### Format des valeurs (roll-under, inspiré Dragonbane)

> **Changement v3 :** Les stats ne sont plus des modificateurs (+2, +1...) mais des **valeurs directes** (10, 9...) qu'on utilise dans le roll-under. La valeur de stat EST le nombre de base pour le roll-under. Plus la valeur est haute, mieux c'est.

**Correspondance avec les modificateurs D&D 5e (pour conversion) :**

| Valeur stat | Équivalent mod D&D 5e | Signification |
|---|---|---|
| 7 | -1 | Faible |
| 8 | +0 | Moyen |
| 9 | +1 | Bon |
| 10 | +2 | Très bon |
| 11 | +3 | Exceptionnel |

**Formule de conversion depuis D&D 5e :** Valeur = 8 + modificateur D&D. Un monstre D&D avec STR 16 (+3) → STR 11 chez nous.

**Arrays de création (distribuer sur STR / DEX / WIT / EMP) :**

| Array | Valeurs |
|-------|---------|
| Standard | 10, 10, 8, 7 |
| Balanced | 10, 9, 9, 8 |
| Min-Max | 11, 9, 7, 7 |

**Exemple :** Un Infiltrateur prend l'array Standard et distribue : STR 7, DEX 10, WIT 10, EMP 8. Il est agile et observateur, mais pas costaud ni charismatique.

### Bonus de stat

Le **bonus** d'une stat = **valeur - 8**. C'est l'équivalent du modificateur D&D 5e. Il intervient dans les formules de dégâts, PV, Blessures, Healing Surges, etc.

| Valeur | Bonus |
|---|---|
| 7 | -1 |
| 8 | 0 |
| 9 | +1 |
| 10 | +2 |
| 11 | +3 |

**Exemple :** STR 10 → bonus STR = +2. Utilisé pour les PV, les Blessures, les Healing Surges.

### Bonus de dégâts

Le bonus de stat intervient pour les PV, Blessures, Healing Surges, etc. Mais les **dégâts des armes** utilisent un système à seuils séparé, inspiré de Dragonbane. La stat utilisée dépend de l'arme : **DEX** pour les armes à distance, **STR** pour la mêlée (ou DEX si finesse).

| Valeur de stat d'arme | Bonus de dégâts |
|---|---|
| 7 | Aucun |
| 8-9 | **+1d4** |
| 10-12 | **+1d6** |
| 13+ | **+1d8** |

> **Ce bonus s'applique uniquement aux PJ.** Les monstres utilisent leurs dégâts fixes.

**Exemple :** Un Grounder (DEX 10) tire avec un fusil d'assaut (1d8). Ses dégâts = 1d8 + 1d4. Quand sa DEX atteindra 13 (via progression), ses dégâts passeront à 1d8 + 1d6.

> **Note de design :** Ce système crée une vraie progression de dégâts. Au niveau 1 (stats 7-11), seuls les persos avec 10+ dans leur stat d'arme ont un bonus. Un personnage qui monte sa DEX de 11 à 13 (vers le niveau 5-6) passe du d4 au d6 — un saut satisfaisant.

### Sauvegardes (4 saves, format Nimble)

Chaque classe a 1 save avantagé (+) et 1 save désavantagé (–), les 2 autres sont neutres :

- **STR Save** — résister aux effets physiques (ancien rôle de CON + STR)
- **DEX Save** — réflexes, esquive
- **WIT Save** — résister aux effets mentaux analytiques (ancien rôle partiel de WIL + INT)
- **EMP Save** — résister aux effets émotionnels/sociaux (ancien rôle partiel de WIL + CHA)

### EMP et les cybernétiques (note de design futur)

EMP est la stat qui pourra se dégrader avec la cybernétisation (inspiré Cyberpunk 2020/RED). Chaque implant réduit l'EMP max ou impose un malus. Un Street Samurai avec plein de chrome a STR 13, DEX 13... et EMP 8. Il est une machine de guerre mais il ne peut plus connecter avec personne — vulnérable à la manipulation émotionnelle, à la peur, au breakdown mental. Ce mécanisme est optionnel et réservé aux settings cyberpunk.

### Jet de sang-froid pour Shaken (v4 — 1 round)

Le joueur fait un jet de **STR ou WIT** (roll-under, pas de difficulté) au début de son tour. Réussite = Shaken effacé, tour normal. Échec = effets de Shaken ce tour, puis réinitialisation à 0 en fin de tour. Voir section 6 pour le détail complet.

---

## 2. RÉSOLUTION — D20 ROLL-UNDER

> **Changement v3 :** Le système passe du roll-over (d20 + mod ≥ DC) au **roll-under** (d20 ≤ seuil calculé). C'est l'inverse mathématique de D&D 5e. L'avantage principal : le joueur sait instantanément s'il réussit en voyant son dé, sans attendre que le MJ annonce un résultat.
>
> **Inspiration :** Dragonbane (Free League) utilise un roll-under pur (d20 ≤ skill level). Notre système y ajoute la progression de proficiency de D&D 5e et la réduction d'Armure.

### Score de Compétence

Chaque compétence, chaque arme, chaque save a un **Score** inscrit sur la fiche du personnage :

**Score = Valeur de stat + proficiency (si formé) + bonus loot (si applicable)**

C'est le nombre de référence. Le joueur le calcule une fois à la création et le met à jour quand sa proficiency, ses stats, ou son équipement changent. Sans proficiency, la valeur de stat brute EST le score (+ bonus loot éventuel).

> **Changement v4 :** Le Score intègre désormais le **bonus loot** — c'est la deuxième jambe de progression. Un fusil +2 ajoute +2 au Score de Tir. Un deck de hacking +1 ajoute +1 au Score de Hacking. Ce bonus est volatile (l'équipement peut être endommagé, détruit, volé).

#### Table des Scores par niveau (formé, sans loot)

| Valeur stat | Non-formé | Prof +1 (niv 1-5) | Prof +2 (niv 6-10) | Prof +3 (niv 11-15) |
|---|---|---|---|---|
| 7 | 7 | 8 | 9 | 10 |
| 8 | 8 | 9 | 10 | 11 |
| 9 | 9 | 10 | 11 | 12 |
| 10 | 10 | 11 | 12 | 13 |
| 11 | 11 | 12 | 13 | 14 |
| 12 | 12 | 13 | 14 | 15 |
| 13 | 13 | 14 | 15 | 16 |

Les scores nus vont de **7 à 16** — dans la même plage que Dragonbane (1-18). Avec le loot (+0 à +3), le score peut monter jusqu'à 19. Propre et lisible sur une fiche.

### La formule de résolution

Pour toute action avec opposition ou difficulté :

```
Seuil = Score de Compétence - Difficulté
Rouler d20 ≤ Seuil = Réussite
```

La **difficulté** est un modificateur appliqué par le MJ ou par les circonstances. En combat, la difficulté pour toucher est **0** (pas de défense passive). Hors combat, c'est un chiffre fixé par le MJ selon la situation (Firewall pour le hacking, difficulté de serrure, etc.).

Pour une action sans difficulté particulière :

```
Seuil = Score de Compétence (pas de réduction)
Rouler d20 ≤ Seuil = Réussite
```

### Pas de défense passive — Philosophie

Il n'y a **pas de chiffre de défense passif** sur les cibles. Une balle ne "rate" pas parce que la cible est agile — elle rate parce que le tireur n'est pas assez bon, ou parce que la cible est derrière un obstacle.

**Ce qui rend un ennemi dur à éliminer, c'est :**
- Son **Armure** (meilleure armure, cybernétiques)
- Ses **PV/Blessures** (plus de points de vie)
- Ses **capacités** (réactions, actions multiples, résistances)
- Sa **catégorie** (Minion → Adversaire → Boss)

**Ce qui rend un tir difficile, c'est la situation :**
- La **couverture** (+2 Armure si partielle, pas de tir si totale)
- Les **conditions** (obscurité, fumée → Désavantage)

### Couverture

La couverture n'est pas un malus au jet. Elle **protège physiquement** la cible en ajoutant à l'Armure :

| Couverture | Effet |
|---|---|
| **Aucune** | Rien |
| **Partielle** (muret, voiture, arbre, angle de mur) | **+2 Armure** |
| **Totale** (mur complet, bunker fermé, véhicule blindé) | **Pas de ligne de tir** — impossible de viser |

### Modificateurs situationnels — Avantage / Désavantage

Les modificateurs ne sont jamais des +1/-2. C'est toujours **Avantage** (avantage, 2d20 garde le plus bas) ou **Désavantage** (désavantage, 2d20 garde le plus haut) :

| Situation | Effet |
|---|---|
| Obscurité, fumée, brouillard | **Désavantage** sur les attaques à distance |
| Cible au sol (prone) | **Avantage** en mêlée, **Désavantage** à distance |
| Viser (1 action dépensée) | **Avantage** sur le prochain tir |
| Shaken (tout niveau) | **Désavantage** sur toutes tes actions |
| Surprise | **Avantage** + tu choisis ta carte d'initiative |

Le MJ a un seul levier : Avantage, Désavantage, ou normal. Pas de calcul.

### Exemple d'attaque complète

Un Gunslinger (DEX 10, proficient en armes de poing, prof +1 au niv 1) tire sur un mercenaire (Armure 5, derrière un muret = couverture partielle → Armure effective 7).

1. **Score de Tir** du Gunslinger : 10 (DEX) + 1 (prof) = **11**
2. **Difficulté :** 0 (pas de défense passive)
3. **Seuil** = 11 - 0 = **11**
4. Le joueur roule d20 → **9** → 9 ≤ 11 → **Touché !**
5. Dégâts : 1d8 (arme) + 1d4 (bonus dégâts, DEX 10) = ex: 5 + 3 = **8**
6. Armure effective du mercenaire : 5 (armure) + 2 (couverture) = **7**
7. Dégâts nets : 8 - 7 = **1 PV perdu**
8. Le mercenaire passe à **Shaken 1** (Désavantage sur toutes ses actions).

Le joueur connaît son Score (12), pas de Défense à demander au MJ. Il roule, il touche ou pas. L'Armure + couverture gèrent la protection.

### Grille de probabilités — Score vs Difficulté

| Score | Diff 0 (normal) | Diff 2 (rare) | Diff 4 (très rare) |
|---|---|---|---|
| 8 | 40% | 30% | 20% |
| 10 | 50% | 40% | 30% |
| 12 | 60% | 50% | 40% |
| 13 | 65% | 55% | 45% |
| 15 | 75% | 65% | 55% |
| 17 | 85% | 75% | 65% |

> **Note :** La difficulté > 0 est réservée aux skill checks hors combat (crocheter une serrure, pirater un système, etc.) et au Firewall (hacking). En combat, la difficulté pour toucher est **toujours 0** — la protection vient de l'Armure.

### Évolution avec les niveaux — Les deux jambes de progression

> **Changement v4 :** La proficiency passe de +2/+6 (20 niveaux) à **+1/+2/+3** (15 niveaux). La progression du toucher repose sur deux sources parallèles : la proficiency (stable, prévisible) et le loot (dynamique, volatile). Les ennemis difficiles à toucher imposent **Désavantage** via des pouvoirs de monstre, jamais une difficulté numérique.

**Jambe 1 — Proficiency (stable) :** Monte avec le niveau, jamais perdue.

| Niveaux | Proficiency |
|---|---|
| 1–5 | +1 |
| 6–10 | +2 |
| 11–15 | +3 |

**Jambe 2 — Loot (volatile) :** Bonus de +0 à +3 via armes, viseurs, implants, etc. Sujet à rotation — le loot se casse, se perd, se fait voler ou détruire (voir section 9).

| Niveau | Prof | DEX (Grounder) | Loot attendu | Score total | % toucher | Notes |
|---|---|---|---|---|---|---|
| 1 | +1 | 10 | +0 | 11 | 55% | Recrue formée |
| 5 | +1 | 11 | +1 | 13 | 65% | Fin du premier arc |
| 6 | +2 | 11 | +1 | 14 | 70% | Vétéran |
| 10 | +2 | 12 | +2 | 16 | 80% | Spécialiste |
| 11 | +3 | 12 | +2 | 17 | 85% | Élite |
| 15 | +3 | 13 | +3 | 19 | 95% | Légende (avec meilleur loot) |

**Courbe nue (sans loot) :** niv 1 = 55%, niv 15 = 80%. Le personnage niv 15 nu rate encore 1 attaque sur 5. Le loot pousse à 95%, mais ce bonus est volatile — un personnage dépouillé reste compétent, pas surpuissant.

**Impact de Désavantage (le levier principal pour les ennemis dangereux) :**

| Score | Normal | Désavantage (2d20 haut) | Double Désavantage (3d20 haut) |
|---|---|---|---|
| 11 | 55% | 30% | 17% |
| 14 | 70% | 49% | 34% |
| 16 | 80% | 64% | 51% |
| 19 | 95% | 90% | 86% |

Un boss avec "Champ de distorsion — impose Désavantage" réduit un héros niv 15 de 80% (nu) à 64%. Double Désavantage (rare, réservé aux boss) est dévastateur. C'est le seul levier pour rendre les ennemis difficiles à toucher — pas de difficulté numérique en combat.

### Jets de sauvegarde — Même logique

Les saves utilisent le même système roll-under. Le Score de Save = valeur de stat (+ proficiency si le personnage est formé à ce save). **Les saves n'ont pas de difficulté** — c'est toujours un roll-under pur.

**Exemple :** Une grenade impose un Save DEX.

| Personnage | DEX | Prof? | Score Save | Chance |
|---|---|---|---|---|
| Techie (DEX 7, non-formé) | 7 | Non | 7 | 35% |
| Heavy (DEX 8, non-formé) | 8 | Non | 8 | 40% |
| Heavy (DEX 8, formé +1) | 8 | Oui | 9 | 45% |
| Soldat (DEX 10, formé +1) | 10 | Oui | 11 | 55% |

> **Design :** Les saves sans difficulté sont cohérents avec le combat (attaques = diff 0, protection = Armure). La stat du personnage EST sa capacité à résister. Un personnage avec DEX élevée esquive mieux — c'est tout. La puissance de l'effet vient des **dégâts**, pas de la probabilité de toucher.
| Infiltrateur (DEX 11, formé +1) | 11 | Oui | 12 | 8 → 40% | Correct |
| Infiltrateur niv 8 (DEX 11, formé +2) | 11 | Oui | 13 | 9 → 45% | Bon |

Les grenades sont dangereuses pour tout le monde. L'Infiltrateur expérimenté s'en sort une fois sur deux, le Techie est en danger de mort. C'est voulu.

### Skill checks (hors combat)

Pour les actions sans opposition directe, le MJ fixe une difficulté :

| Difficulté | Valeur |
|---|---|
| Pas de difficulté | 0 |
| Légère | 1-2 |
| Moyenne | 3-4 |
| Difficile | 5-6 |
| Très difficile | 7-8 |
| Quasi impossible | 9-10 |

**Exemple :** Crocheter une serrure (difficulté 3). Le Techie a WIT 10, proficient en Engineering, prof +1 → Score 11. Seuil = 11 - 3 = **8**. Roule 8 ou moins → 40%.

### Trained-only skills

Pour les 6 skills "trained only" (Computer Use, Demolitions, Engineering, Medicine, Sciences, Sleight of Hand) : si tu n'es PAS formé, tu ne peux tout simplement pas tenter le jet. Pas de seuil à calculer — l'action est impossible sans entraînement.

### Liste des 20 compétences

Le système utilise 20 compétences réparties sur les 4 stats. Chaque compétence a un Score = stat + proficiency (si formé). Les 13 compétences générales sont utilisables par tout le monde (formé = avec proficiency, non-formé = stat brute). Les 7 compétences spécialisées (★) nécessitent une formation — impossible d'essayer sans.

**STR — Force**

| Compétence | Description |
|---|---|
| **Athlétisme** | Escalade, nage, sauts, efforts physiques soutenus, forcer une porte, maintenir une prise. |

**DEX — Dextérité**

| Compétence | Description |
|---|---|
| **Acrobaties** | Équilibre, roulades, chutes contrôlées, manœuvres aériennes, traverser un terrain instable. |
| **Discrétion** | Se déplacer sans être vu ni entendu, filer une cible, se fondre dans la foule. |
| ★ **Escamotage** | Pickpocket, tours de passe-passe, dissimuler un objet, crocheter une serrure mécanique. Formé uniquement. |
| **Pilotage** | Conduire des véhicules terrestres, piloter des vaisseaux, poursuites, manœuvres d'évitement. |

**WIT — Esprit**

| Compétence | Description |
|---|---|
| **Perception** | Observer l'environnement, repérer un piège, détecter un mouvement, fouiller une pièce. Perception du *monde* (pas des gens → EMP). |
| **Investigation** | Analyse logique, déductions, recherche d'indices, recouper des informations, résoudre un puzzle. |
| **Connaissance** | Culture générale, histoire, géographie, religion, nature, politique. Savoir encyclopédique. |
| **Survie** | Orientation, pistage, chasse, trouver de l'eau, lire la météo, naviguer en terrain hostile. |
| ★ **Informatique** | Hacking, programmation, contourner la sécurité, recherche en base de données, modifier du matériel informatique. Formé uniquement. |
| ★ **Démolitions** | Poser et désamorcer des explosifs, évaluer des structures, saboter. Formé uniquement. |
| ★ **Ingénierie** | Construire, réparer et modifier des appareils, véhicules, armes, armures, exo-armures, électronique. Formé uniquement. |
| ★ **Médecine** | Premiers soins, chirurgie de terrain, diagnostic, pharmacologie, stabiliser un mourant. Formé uniquement. |
| ★ **Sciences** | Chimie, physique, biologie, balistique, analyse forensique, xénobiologie. Formé uniquement. |
| ★ **Tactique** | Planification militaire, lecture du champ de bataille, évaluation de forces, stratégie, logistique. Formé uniquement. |

**EMP — Empathie**

| Compétence | Description |
|---|---|
| **Intuition** | Lire les intentions d'un interlocuteur, sentir un mensonge, évaluer le moral, percevoir la tension. Perception des *gens* (pas du monde → WIT). |
| **Persuasion** | Convaincre, négocier, inspirer, motiver, faire appel à la raison ou aux émotions. Inclut le leadership de terrain. |
| **Tromperie** | Mentir, bluffer, déguiser ses intentions, créer une fausse identité, feindre. |
| **Intimidation** | Effrayer, menacer, imposer sa volonté par la pression sociale ou physique. Peut utiliser STR au lieu d'EMP si purement physique (au choix du MJ). |
| **Représentation** | Jouer un rôle, chanter, divertir, attirer l'attention, créer une diversion sociale. |

> **Note de design :** La liste est basée sur UM5 avec quelques fusions. History + Nature + Religion → Connaissance. Computer Use → Informatique. Les skills UM5 non conservées (Animal Handling, Arcana) sont remplacées par des skills plus pertinentes pour le modern/sci-fi. La distinction Perception (WIT, le monde) / Intuition (EMP, les gens) est le pilier du système à 4 stats.

### Le 1 et le 20

- **1 = Réussite critique.** Réussite automatique + effet bonus. En attaque : les dégâts infligent 1 Blessure en plus et infligent 1 Blessure en plus des dégâts (après Armure), puis jet sur la Table de Blessures Critiques.
- **20 = Échec critique.** Échec automatique + possible effet négatif (au choix du MJ ou table optionnelle).

> **Note :** Dans un système roll-under, le 1 est le meilleur résultat possible et le 20 le pire. C'est l'inverse de D&D 5e, mais cohérent avec la logique roll-under de Dragonbane.

### Avantage / Désavantage

Identique à D&D 5e / Dragonbane (avantage/désavantage) :

- **Avantage (Avantage) :** Roule 2d20, garde le **plus bas** (meilleure chance de passer sous le seuil).
- **Désavantage (Désavantage) :** Roule 2d20, garde le **plus haut** (pire chance de passer sous le seuil).
- Les avantages et désavantages s'annulent mutuellement (1 avantage + 1 désavantage = jet normal).

### Pourquoi roll-under ?

1. **Le joueur sait immédiatement.** Pas besoin d'attendre "est-ce que ça touche ?". Tu vois ton dé, tu connais ton seuil, c'est réglé.
2. **Échelle lisible.** Les Scores vont de 7 à 17. Des chiffres petits, faciles à manipuler.
3. **Compatible avec tout le design existant.** L'Armure, le Shaken, les PV/Blessures, les Healing Surges — rien ne change. Seul le moment du "touché/raté" est inversé.
4. **L'armure est clairement séparée.** Toucher = roll-under (passer ou rater). Armure = absorption (dégâts réduits). Le joueur comprend les deux couches distinctement.
5. **La difficulté est réservée aux skill checks.** Difficulté d'un skill check, Firewall pour le hacking — c'est un nombre qu'on soustrait du Score. En combat, la difficulté est toujours 0 (attaques ET saves).

---

## 3. ÉCONOMIE D'ACTIONS, INITIATIVE & TEMPS

### Actions (sur son tour)

| Coût | Exemples |
|------|----------|
| 1 action | Attaque (tir simple), se déplacer, recharger, viser (Avantage au prochain tir), évaluer (Assess), interagir, cantrip/pouvoir mineur, se relever |
| 2 actions | **Tir Automatique** (arme auto-fire), Pouvoir/capacité majeur, sprint (double mouvement), premiers soins, hacking, utiliser un gadget complexe |
| 3 actions | Capacité ultime, action très complexe |

### Réactions (hors tour — coûte 1 action de ton prochain tour)

Chaque réaction coûte **1 action**, retirée de ton prochain tour. Chaque type de réaction est limité à **1×/round**. Tu peux empiler plusieurs réactions différentes (ex: Parade + Interposition = 2 actions brûlées → prochain tour avec 1 action seulement). Si tu as déjà dépensé 3 actions en réactions, ton prochain tour est perdu.

| Réaction | Effet | Contexte |
|----------|-------|----------|
| **Parade** | Jet d'arme de mêlée pour bloquer l'attaque. Réussite = attaque annulée. | **Mêlée uniquement.** 1×/round. |
| **Interposition** | Tu prends l'attaque à la place d'un allié adjacent | Universel. 1×/round. |
| **Attaque d'opportunité** | Frappe un ennemi qui quitte ta zone de mêlée | Mêlée uniquement. 1×/round. |
| **Riposte** (capacité de classe) | Contre-attaque après avoir été touché | Certaines classes seulement. 1×/round. |
| **Snap Out Of It** | Réduit le niveau de Shaken d'un allié adjacent de 1 | Universel. 1×/round. |

### Tir Automatique (Autofire)

Les armes avec la propriété **Auto-fire** peuvent tirer en mode automatique. Chaque arme auto-fire possède **deux valeurs de dégâts** : dégâts simples et dégâts auto (le dé monte d'un cran en auto).

**Tir Simple (1 action) :** Jet d'attaque normal (roll-under). Touché = dégâts simples (+ bonus de dégâts de stat) + Shaken +1 niveau. Raté = rien.

**Tir Automatique (2 actions) :** Désigne jusqu'à **3 cibles** à portée. L'attaquant **ne fait pas de jet d'attaque**. Chaque cible fait un **save DEX** (roll-under, difficulté 0).

| Résultat du save DEX | Effet |
|---|---|
| **Échec** | Dégâts auto de l'arme (+ bonus de dégâts de stat). Armure s'applique. |
| **Réussite** | Pas de dégâts. |
| **Dans les deux cas** | La cible gagne **Shaken +1 niveau** (les balles sifflent, c'est de la suppression). |

> **Exemple :** Un Grounder avec un fusil d'assaut (1d8 simple / 1d10 auto, DEX 10 → +1d4 dégâts) tire en automatique sur 3 soldats. Chaque soldat fait un save DEX. Ceux qui échouent prennent 1d10 + 1d4 (Armure s'applique). Les trois deviennent Shaken +1, qu'ils aient esquivé ou non.

> **Design note :** Le tir automatique est qualitativement différent du tir simple. C'est les cibles qui décident si elles esquivent (save DEX), pas toi qui décides si tu touches (jet d'attaque). Très efficace contre les cibles lentes (DEX basse), faible contre les cibles agiles (DEX haute). Le Shaken garanti est la vraie valeur — même sur un save réussi, tu fais monter le Shaken. C'est la suppression.

### Munitions — Abstraction narrative

**Pas de tracking de munitions.** Les balles sont une ressource narrative, pas un compteur mécanique. Si le MJ veut créer de la tension ("vous êtes à court de munitions"), c'est un outil scénaristique, pas une mécanique de combat. Approche inspirée de Genesys.

### Initiative — Cartes d'initiative (inspiré Dragonbane)

Au début de **chaque round**, chaque participant tire une carte numérotée (1-10). On agit dans l'ordre : 1 d'abord, 10 en dernier. L'ordre change à chaque round.

| Catégorie | Cartes tirées |
|---|---|
| **PJ** | 1 carte chacun |
| **Minions** (groupe) | 1 carte pour le groupe entier — tous agissent au même moment |
| **Adversaire** | 1 carte chacun |
| **Boss** | **2 cartes minimum** — agit 2 fois par round, à deux moments différents |
| **Boss majeur** | 3 cartes |
| **Boss extrême** (rare) | 4 cartes — réservé aux rencontres finales |

**Surprise :** Si tu surprends l'ennemi, tu **choisis** ta carte au lieu de la tirer.

**Attendre :** Tu peux échanger ta carte avec quelqu'un qui n'a pas encore agi. Il ne peut pas refuser.

**Réaction et initiative :** Les réactions ne modifient pas ta carte d'initiative. Elles coûtent des actions de ton prochain tour (voir section Réactions ci-dessus).

### Gestion du temps — Round / Stretch / Shift (inspiré Dragonbane)

| Unité | Durée | Correspond à... |
|---|---|---|
| **Round** | ~10 secondes | 1 tour de combat. Tous les participants agissent une fois. |
| **Stretch** | ~15 minutes | Explorer une pièce, fouiller un lieu, crocheter une serrure, repos court. |
| **Shift** | ~6 heures | Un trajet, une infiltration complète, un repos long. |

**4 Shifts par jour :** Matin, Jour, Soir, Nuit.

**Repos et récupération :**

| Type de repos | Durée | Effet |
|---|---|---|
| **Second Wind** | 1 round (en combat) | Dépense 1 Healing Surge, récupère Surge Value en PV. 1×/combat. |
| **Stretch Rest** (repos court) | 1 stretch (15 min) | Dépense **1 Healing Surge** (max). Soigne **1 condition**. Max 2 Stretch Rests entre chaque Shift. |
| **Shift Rest** (repos long) | 1 shift (6h), lieu sûr | Toutes les surges reviennent. PV au max. 1 Blessures récupéré (2 avec soins). Toutes conditions soignées. Équipement Endommagé réparable. |

**Voyage :** ~15 km/shift à pied, ~30 km/shift en véhicule. Max 2 shifts de voyage/jour (un 3ème = Épuisé).

### Mouvement & Positionnement (grille tactique)

Le combat se joue sur une **grille de cases** (1 case = ~1,5m / 5 ft). Inspiré de Nimble.

**Vitesse de base :** **6 cases** (sauf modification par classe, armure ou condition).

| Action de mouvement | Coût | Effet |
|---|---|---|
| **Se déplacer** | 1 action | Déplacement jusqu'à ta Vitesse (6 cases). Diagonales comptent comme adjacentes. |
| **Sprint** | 2 actions | Double déplacement (12 cases). Pas d'attaque possible ce tour. |
| **Se relever** (depuis prone) | 1 action | Tu passes de prone à debout. |
| **Se jeter au sol** (prone) | Action gratuite | Tu te mets prone volontairement. |

**Terrain difficile :** Coûte 2 cases de mouvement par case traversée (gravats, boue, eau, végétation dense).

**Passage :** Tu peux traverser les cases d'alliés normalement. Traverser une case ennemie coûte double (terrain difficile) et tu ne peux pas y terminer ton mouvement.

**Mêlée :** Pour attaquer au corps à corps, tu dois être dans une case adjacente à ta cible (y compris diagonalement).

**Tir à distance en mêlée :** Si un ennemi est dans une case adjacente à toi, tes attaques à distance se font avec **Désavantage**.

**Portée des armes :** Chaque arme a une portée en **cases**. Au-delà de la portée normale mais en dessous du double, le tir se fait avec **Désavantage**. Au-delà du double : impossible.

### Couverture (en combat)

La couverture ne modifie PAS le jet d'attaque — elle protège physiquement en ajoutant à l'Armure.

| Couverture | Effet | Exemples |
|---|---|---|
| **Aucune** | Rien | En plein milieu d'une rue |
| **Partielle** | **+2 Armure** | Derrière un muret, une voiture, un arbre, un angle de mur |
| **Totale** | **Pas de ligne de tir** — impossible d'être ciblé | Derrière un mur complet, dans un bunker fermé |

**Se mettre à couvert :** Se déplacer derrière un élément du décor (dans le cadre de son mouvement normal). Si le couvert est à portée de mouvement, ça ne coûte pas d'action supplémentaire — c'est inclus dans le déplacement.

**Se cacher :** Nécessite une couverture (partielle ou totale). Coûte 1 action + jet de Discrétion (diff 3, ou diff 1 si couverture totale). Tant que tu es caché, les ennemis ne peuvent pas te cibler. Ta première attaque depuis une position cachée se fait avec **Avantage**, puis tu es révélé.

**Prone (au sol) :**
- Les attaques de mêlée contre toi ont **Avantage**.
- Les attaques à distance contre toi ont **Désavantage**.
- Tes propres attaques à distance n'ont pas de malus (sauf armes lourdes au MJ).

---

## 4. ARMURE & COUVERTURE

### Principe fondamental
L'armure est **toujours active**. Tu portes un gilet pare-balles, il absorbe. Pas besoin de "réaction" pour appliquer ta protection contre un tir. C'est un combat à distance principalement — les balles ne te demandent pas si tu es prêt.

### Fonctionnement mécanique

**Armure (Absorption) :** Chaque armure a une valeur d'Armure. Les dégâts reçus sont réduits de cette valeur.

| Type d'armure | Armure | Exemples (nomenclature UM5) |
|---------------|------|----------------------------|
| Aucune | 0 | Vêtements civils |
| Légère | 2-4 | Gilet tactique léger, veste renforcée |
| Moyenne | 5-7 | Gilet pare-balles, armure balistique |
| Lourde | 8-10 | Armure de combat complète, exo-armure légère |
| Exo-armure | 11+ | Powered armor, exo-armure lourde (TL3+) |

### Règle du minimum 1

**Toute attaque réussie inflige au minimum 1 point de dégâts aux PV**, même si l'Armure dépasse les dégâts. Un couteau contre une armure lourde c'est 1 dégât — ça ne va pas tuer, mais ça fatigue. Les PV représentent la chance et la fatigue, pas la chair. Chaque impact use.

### Couverture = bonus à l'Armure

Voir section 3 (Mouvement & Positionnement) pour le détail complet. En résumé : couverture partielle = **+2 Armure**, couverture totale = **pas de ligne de tir**.

### Parade en mêlée
Au corps à corps uniquement, un personnage peut utiliser sa réaction "Parade" pour tenter de bloquer une attaque (jet d'arme de mêlée). Cela coûte 1 action du prochain tour. En cas de réussite, l'attaque est annulée.

**Même si l'armure absorbe TOUS les dégâts → le personnage doit quand même faire un jet de Shaken** (voir section 6). L'impact existe, même si la balle n'a pas pénétré.

---

## 5. VIGUEUR, VITALITY POINTS & WOUND POINTS

> **Source :** Inspiré du système PV/Blessures de Star Wars d20 (Revised Core Rulebook, WotC 2002), du système Healing Surges de D&D 4e, adapté à notre mécanique Armure/Shaken. CON supprimé — la durabilité repose sur la **Vigueur** (indice de classe) + **STR** (condition physique personnelle).

### Vigueur — L'indice de durabilité de classe

> **Design Intent :** La Vigueur ne représente pas "tu es né costaud." C'est "ton parcours t'a endurci." C'est l'accumulation d'expérience face à la douleur, au stress physique, au danger. Un Heavy a Vigueur 10 parce qu'il a passé des années sur le terrain — il a pris des balles, dormi dans la boue, fait des marches forcées. Son corps *sait* ce que c'est qu'encaisser. Un Techie a Vigueur 6 parce que son parcours c'est des labos, des écrans, des salles serveur climatisées — son corps n'a jamais été confronté à la violence physique prolongée.
>
> **Vigueur = ce que ta classe t'a appris à endurer. Bonus STR (= STR - 8) = ce que toi, personnellement, tu apportes en plus.** Les deux s'additionnent partout : Blessures, PV par niveau, surge value.

La Vigueur est un **chiffre fixe par classe** (6, 8, 10 ou 12) — ce n'est pas un dé qu'on lance. Un seul nombre, trois fonctions :

| Classe | Vigueur | Justification |
|--------|---------|---------------|
| **Grounder** | 10 | Soldat de première ligne, endurci par le terrain |
| **Infiltrator** | 8 | Spécialiste ops clandestines, entraîné mais pas tank |
| **Medic** | 8 | Soignant de terrain, habitué au feu mais pas combattant |
| **Marshal** | 8 | Commandant de terrain, cerveau tactique (pas tank) |
| **Tech** | 6 | Ingénieur/hacker, vie d'arrière-ligne |

> **Changement v4 :** Les 11 classes UM5 sont réduites à **5 classes core**. Le Heavy (Vig 12), le Gunslinger, le Sniper, le Martial Artist, le Face et le Civilian sont absorbés ou reportés. Le Marshal passe de Vig 10 à **Vig 8** (c'est un cerveau, pas un tank).

### Philosophie PV/Blessures

Les points de vie sont séparés en **deux barres distinctes** qui représentent des choses fondamentalement différentes :

- **Points de Vie (PV)** = Chance, fatigue, éraflures, "near-misses". C'est l'entraînement du personnage qui transforme un tir létal en un impact de rien du tout. Les PV **augmentent avec le niveau** — un vétéran encaisse plus de "presque" qu'une recrue. Les PV se **récupèrent via les Healing Surges**.
- **Blessures** = Blessures réelles. Chair, os, sang. Quand tu perds des Blessures, quelque chose de grave s'est passé dans ton corps. Les Blessures sont **fixes** — ils ne montent pas avec le niveau (comme Star Wars d20). Les Blessures se **récupèrent lentement** (repos uniquement).

### Calcul des PV et Blessures

| Pool | Formule | Progression |
|------|---------|-------------|
| **PV (Vitality)** | **Niveau 1 :** Vigueur + bonus STR. **Niveaux suivants :** (Vigueur ÷ 2 + bonus STR + 1) par niveau (min 3). PJ uniquement. | Augmente à chaque niveau. Représente l'expérience au combat. |
| **Blessures (Wound)** | = **Vigueur + bonus STR.** | **Ne monte JAMAIS avec le niveau.** Fixe à la création. Peut augmenter uniquement si STR augmente (augmentations, talents, cybernétiques). |

**Exemples :**

| Personnage | Classe | Niveau | Vigueur | STR (valeur) | Bonus STR | PV | Blessures |
|------------|--------|--------|---------|-------------|-----------|----|----|
| Recrue | Grounder (Vig 10) | 1 | 10 | 10 | +2 | 12 | 12 |
| Vétéran | Grounder (Vig 10) | 5 | 10 | 10 | +2 | 12 + 4×8 = 44 | 12 |
| Élite | Grounder (Vig 10) | 15 | 10 | 10 | +2 | 12 + 14×8 = 124 | 12 |
| Espion | Infiltrator (Vig 8) | 5 | 8 | 8 | 0 | 8 + 4×5 = 28 | 8 |
| Hacker | Tech (Vig 6) | 10 | 6 | 7 | -1 | 5 + 9×4 = 41 | 5 |

### Healing Surges — Le système de guérison

> **Source :** Directement inspiré de D&D 4e. Toute guérison de PV passe par les Healing Surges. Le concept central : un soldat entraîné (haute Vigueur, STR élevé) récupère mieux et plus souvent qu'un civil.

**Nombre de Healing Surges par jour** = base classe + bonus STR :

| Classe | Base Surges | Profil |
|--------|-------------|--------|
| **Grounder** | 7 + STR | Combattant front-line. Le plus de surges perso. |
| **Marshal** | 6 + STR | Leader. Partage/déclenche les surges des autres. |
| **Medic** | 6 + STR | Soigneur. Déclenche les surges des alliés. |
| **Infiltrator** | 5 + STR | Furtif. Évite les coups, moins besoin de réserve. |
| **Tech** | 4 + STR | Arrière-ligne. Le plus fragile. |

**Healing Surge Value** (combien tu récupères par surge) = **Vigueur + bonus STR**, fixe, toujours identique. Pas de lancer de dé — zéro aléatoire, tu peux planifier tes décisions tactiques en toute confiance.

| Exemple | Vigueur | STR | Surges/jour | Surge Value | Total récupérable/jour |
|---------|---------|-----|-------------|-------------|----------------------|
| Grounder (STR 10, bonus +2) | 10 | +2 | 9 | 12 PV | 108 PV |
| Marshal (STR 9, bonus +1) | 8 | +1 | 7 | 9 PV | 63 PV |
| Infiltrator (STR 7, bonus -1) | 8 | -1 | 4 | 7 PV | 28 PV |
| Tech (STR 8, bonus 0) | 6 | 0 | 4 | 6 PV | 24 PV |

Le tank a le double de récupération totale du Techie. C'est ce qui encourage le Heavy à prendre les coups : il en tire un bien meilleur rendement.

**Comment dépenser une Healing Surge — Modèle restrictif :**

> **Changement v4 :** Les surges sont une ressource finie et précieuse. On ne les dépense pas librement — il faut un **déclencheur**. C'est ce qui rend le Medic et le Marshal indispensables.

| Déclencheur | Quand | Coût | Effet |
|---|---|---|---|
| **Second Wind** | En combat (1 action) | 1 Surge du personnage | Récupère Surge Value en PV. **1×/combat.** |
| **Stretch Rest** | Hors combat (~15 min) | 1 Surge du patient | Récupère Surge Value en PV. **1 seule fois par Stretch.** |
| **Stim Pack** | En combat ou hors combat (1 action) | 1 Surge du patient + consomme le stim | Récupère Surge Value en PV. Le stim est la clé. |
| **Pouvoir Medic** | En combat ou Stretch (1 action du Medic) | 1 Surge du patient | Le Medic active la surge d'un allié adjacent. Bonus possibles selon niveau. |
| **Pouvoir Marshal** | En combat (capacité de classe) | 1 Surge de l'allié ciblé | Le Marshal galvanise un allié — "Debout soldat !" |
| **Objet spécial (TL élevé)** | Variable | 1 Surge + l'objet | Nano-injecteur, auto-chirurgien, etc. |

**Contraintes :** Max **2 Stretch Rests** entre chaque Shift Rest. Surges ne se régénèrent **que** sur un Shift Rest (6-8h). Personne ne crée de surges supplémentaires (sauf capacités très rares de haut niveau). **Les surges ne soignent PAS les PV.** Jamais.

**Shift Rest (6-8h) :** PV au maximum. Toutes les Surges reviennent. Shaken effacé. Toutes conditions effacées. Blessures : récupère **1 Blessures** naturellement (2 avec soins médicaux). Critiques mineurs guérissent automatiquement. Équipement Endommagé peut être réparé (jet d'Engineering).

**Règle critique :** Si tu n'as plus de surges, tu ne peux plus te soigner en PV. La seule option est un Shift Rest.

### Flux de dégâts — Comment ça marche en jeu

```
Attaque touche → Dégâts bruts → Armure (passive) → Dégâts nets
                                                            │
                        ┌───────────────────────────────────┤
                        │                                   │
                   COUP NORMAL                        COUP CRITIQUE
                        │                              (Nat 1)
                        ▼                                   │
                   PV absorbent                             ▼
                   (chance, fatigue)                   Bypass PV →
                        │                             Blessures directement
                        │                                   │
                  PV tombent à 0?                           ▼
                        │                             Jet de STR Save
                   OUI ──┤                            + Table de
                        ▼                             Blessures
                   Overflow → Blessures                      Critiques
                   + Table de
                   Blessures Critiques
```

### Les règles détaillées

**1. Dégâts normaux → PV d'abord**
Quand une attaque touche (non-critique), les dégâts nets (après Armure) sont soustraits des **PV**. Tant que le personnage a des PV, il ne subit aucune blessure réelle — il esquive, l'armure absorbe, il a de la chance.

**2. Coup critique (Nat 1) → Blessures directement**
Sur un Nat 1 (Réussite critique), les dégâts nets (après Armure) **infligent 1 Blessure en plus** et frappent directement les **Blessures**. C'est la balle qui trouve la faille de l'armure, le tir parfait qui traverse le gilet. Pas de multiplicateur de dégâts — les dégâts normaux suffisent quand ils visent les PV.

**3. PV à 0 → Overflow vers Blessures**
Quand les PV tombent à 0, les dégâts restants de l'attaque qui les a vidés **débordent vers les Blessures**. À partir de ce moment, **toute attaque suivante frappe directement les Blessures**. Le personnage n'a plus de marge — chaque coup est potentiellement mortel.

*Exemple : Elena a 14 PV et 10 PV. Elle prend 16 dégâts (après Armure). 14 dégâts vident ses PV, les 2 restants frappent ses Blessures → 8 PV.*

**4. PV à 0 → Mourant**
À 0 Blessures, le personnage est **Mourant** : inconscient et en train de mourir.

**Blessures (roll-under, début de chaque tour) :**
- **d20 ≤ 10 :** Réussite. Accumule 1 réussite.
- **d20 > 10 :** Échec. Accumule 1 échec.
- **Nat 1 (Réussite critique) :** Tu te relèves avec **1 PV** et Shaken 2.
- **Nat 20 (Échec critique) :** Compte comme **2 échecs.**
- **3 réussites** = stabilisé (inconscient, 0 Blessures, plus Mourant).
- **3 échecs** = mort.
- Subir des dégâts pendant Mourant = **1 échec automatique** (réussite critique ennemie = 2 échecs).
- Un allié peut stabiliser avec **1 action** + jet de **Médecine** (pas de difficulté).

### Interaction PV/Blessures × Armure × Shaken

| Mécanique | Interaction avec PV/Blessures |
|-----------|----------------------|
| **Armure** | S'applique **avant** la répartition PV/Blessures. Les dégâts nets après Armure vont aux PV (normal) ou Blessures (crit/Dying). L'armure protège toujours. |
| **Shaken** | Se déclenche sur **toute attaque qui touche**, indépendamment de PV/Blessures. Même si l'armure absorbe tout et que les PV prennent les dégâts, le Shaken monte de +1 niveau. En cas de tir automatique, Shaken monte même si la cible réussit son save DEX. |
| **Cover** | Les bonus d'Armure de la couverture protègent les PV comme les PV. Se mettre à couvert est encore plus vital quand les PV sont bas. |
| **Vicious (qualité)** | Ajoute +X×10 au jet sur la Table de Blessures Critiques quand des dégâts Blessures sont infligés. |

### Récupération — PV via Surges, Blessures via repos

| Pool | Récupération | Méthode |
|------|-------------|---------|
| **PV** | **Healing Surges uniquement.** Chaque surge récupère Vigueur + bonus STR. Nombre de surges limité par jour (base classe + bonus STR). | Second Wind, potions, Médic, repos court (dépenser surges), repos long (toutes surges + PV max). |
| **Blessures** | **1 Blessures par jour de repos.** 2 Blessures/jour avec repos complet au lit + soins médicaux (jet de Médecine par un soignant). | Repos long, soins médicaux, médicaments, cybernétique médicale. |
| **Blessures (soins de terrain)** | Un jet de Medicine réussi restaure **1d4 Blessures** (1/jour par patient, nécessite kit médical du bon TL). | Le Medic est indispensable. |
| **Blessures (nanotech TL4+)** | Les nanotech médicaux peuvent restaurer **2d6 Blessures** en 1 heure. Très rare et très cher. | Réservé aux settings haute technologie. |

**Conséquence narrative :** Les PV se rechargent entre les rencontres via les surges. Les Blessures persistent pendant **des jours**. Un coup critique dans la Session 3 peut encore affecter le personnage en Session 5. Et les surges s'épuisent au fil de la journée — même si tu récupères ta PV entre les combats, ta réserve de surges diminue. Le 4e combat de la journée est plus dangereux que le 1er.

### PNJ et Minions

| Type de PNJ | PV | Blessures |
|-------------|----|----|
| **Minion** (soldat basique, drone, zombie) | **0 PV.** Tout dégât tue. | — |
| **PNJ standard** (mercenaire, garde) | **PV normaux** (voir table Monster Builder) | **Blessures = Vigueur + STR** |
| **PNJ d'élite** (boss, rival) | **PV normaux** (souvent élevés) | **Blessures = Vigueur + STR** (souvent boostés par augmentations) |
| **Mook (classe PNJ non-combattante)** | **0 PV** — comme Star Wars d20. Un diplomate, un technicien, un civil n'a que ses PV. Un seul tir les met à terre. | **Blessures = Vigueur + STR** (souvent 5-8) |

> **Implication tactique :** Les gardes de sécurité (Mooks) tombent en un coup. Le sergent vétéran (PNJ standard) encaisse plusieurs rounds. Le boss en exo-armure (PNJ d'élite) a une montagne de PV à traverser... sauf si quelqu'un place un Nat 1 (Réussite critique).

### Table de Blessures Critiques

Voir **Section 13** pour la table complète. En résumé :

Un jet sur la Table de Blessures Critiques se fait quand :
1. Un **coup critique (Nat 1 — Réussite critique)** inflige des dégâts aux Blessures, OU
2. Les **PV tombent à 0** et des dégâts débordent vers les PV.

Le jet : **d100 + 10 par blessure critique déjà subie + Vicious bonus** (qualité d'arme). L'escalade est brutale : un personnage déjà blessé risque la mutilation ou la mort sur le prochain crit.

---

## 6. SHAKEN — L'ÉTAT DE CHOC

### Principe

Shaken est un **statut à niveaux** (1, 2, 3) qui ne dure **qu'un seul round**. C'est l'état de choc, la perte momentanée de repères quand les balles sifflent autour de toi.

### Déclenchement

Quand un personnage est **touché par une attaque** (le jet d'attaque réussit, ou le save échoue en cas de tir automatique), **qu'il ait subi des dégâts effectifs ou que l'armure ait tout absorbé**, il gagne **+1 niveau de Shaken** (max 3). Pas de save pour résister — c'est automatique.

- **Pas Shaken → Shaken 1**
- **Shaken 1 → Shaken 2** (hit supplémentaire)
- **Shaken 2 → Shaken 3** (encore un hit, maximum)

> **Cas spécial — Tir automatique :** Le tir automatique cause Shaken **même si la cible réussit son save DEX** et ne prend pas de dégâts. Les balles sifflent, c'est la suppression. C'est le seul cas où Shaken s'applique sans touché.

### Récupération — Début de ton tour

**Au début de ton tour**, si tu es Shaken, tu fais un **save de sang-froid (STR ou WIT, au choix du joueur, roll-under, pas de difficulté).** C'est une action gratuite.

- **Réussite :** Tu n'es plus Shaken. Agis normalement.
- **Échec :** Tu subis les effets de ton niveau de Shaken pendant ce tour.

**Shaken ne persiste jamais au-delà du tour.** À la fin de ton tour, ton compteur de Shaken se réinitialise à 0, que tu aies réussi ou raté le save. Seuls les hits reçus **depuis ton dernier tour** comptent pour le prochain round.

### Effet Shaken par niveau (si save raté)

| Niveau | Effet |
|---|---|
| **Shaken 1** | **Désavantage** sur tous les jets ce tour |
| **Shaken 2** | **Double Désavantage** sur tous les jets ce tour |
| **Shaken 3** (max) | **Double Désavantage** sur tous les jets ce tour + **perd 1 action** (2 au lieu de 3) |

> **Note :** Tu gardes tes actions (sauf Shaken 3), mais tout est fait avec Désavantage. C'est punitif mais tu restes actif.

> **Aide d'un allié — Snap Out Of It :** En réaction, un allié adjacent peut te donner **Avantage** sur ton save de sang-froid. Ça coûte 1 action du prochain tour de l'allié.

### Séquence illustrée

```
ROUND 1 — Tours ennemis (avant Marcos) :
  Tir 1 touche Marcos → SHAKEN 1
  Tir 2 touche Marcos → SHAKEN 2

ROUND 1 — Tour de Marcos :
  Début de tour → Save de sang-froid (STR ou WIT, pas de diff)
  Échec → Shaken 2 = Double Désavantage sur tous ses jets ce tour.
  Marcos utilise ses 3 actions (avec Double Désavantage).
  Fin de tour → Shaken réinitialisé à 0.

ROUND 2 — Tours ennemis :
  Marcos est en couverture totale → aucun tir ne le touche → pas de Shaken.

ROUND 2 — Tour de Marcos :
  Pas Shaken → agit normalement.
```

### Pourquoi Shaken 1 round

Le Shaken qui dure 1 round simplifie le tracking (pas de compteur persistant) tout en gardant l'impact tactique. Un personnage sous un barrage soutenu accumule Shaken chaque round — le save de sang-froid est le moment de tension. La question n'est pas "combien de tours pour s'en remettre" mais "est-ce que tu encaisses le choc maintenant ?"

### Interaction Tir simple × Tir automatique × Aim

| Approche | Dégâts | Shaken infligé | Rôle tactique |
|----------|--------|----------------|---------------|
| **Aim** (2 actions, 1 tir, Avantage) | Élevé | +1 Shaken si touché | Percer les blindés, abattre les cibles prioritaires |
| **Tir simple ×3** (3 actions, 3 tirs) | Moyen par tir | +1 Shaken par hit (max +3) | Volume, pêche aux crits |
| **Tir automatique** (2 actions, save DEX) | Dégâts auto (+ élevés) | **Shaken garanti même sans dégâts** | Suppression, contrôle de zone |

Le Heavy arrose en auto pour verrouiller. Le Sniper vise pour percer. Le Grounder s'adapte. Ni l'un ni l'autre n'est obsolète.

### Immunités & résistances

- Certaines capacités de classe (ex : le Heavy, le Veteran) donnent Avantage au jet de sang-froid ou réduisent le niveau de Shaken reçu.
- Certaines armures (exo-armures stabilisées, TL4+) peuvent réduire le Shaken reçu de 1 niveau.
- Certains avantages de classe : "Battle Hardened" (Avantage permanent au sang-froid), "Nerves of Steel" (immunité au Shaken 1 — seul Shaken 2+ t'affecte), "Unshakeable" (immunité totale au Shaken, très rare et réservé aux capacités de haut niveau).

### Impact tactique

Ce système crée naturellement du **feu de suppression** — même si tu ne blesses pas l'ennemi (tir automatique, save réussi), tu le forces à monter en Shaken. Ça encourage le tir de couverture, le positionnement, et le travail d'équipe (un tire en automatique pour empiler Shaken, l'autre flanque pour finir). Et ça donne une raison mécanique claire de **se mettre à couvert** : un tour sans hit = pas d'escalade du Shaken = récupération plus facile.

---

## 6b. PUSH DE JET — FORCER LE DESTIN (nouveau v4)

> **Source :** Dragonbane (Free League). Quand tu rates un jet, tu peux tenter à nouveau — mais à un coût. Le push crée un mécanisme d'autocontrôle : plus tu forces, plus tu t'affaiblis.

### Règle

Quand tu **rates** un jet de compétence, d'attaque, ou de save, tu peux choisir de **pousser le jet** (push). Tu relances le d20. Le nouveau résultat s'applique, quel qu'il soit. Tu ne peux pas pousser un Échec critique (Nat 20).

**Coût immédiat (choisir UN des deux) :**

**Option A — Condition.** Tu subis immédiatement une **condition** liée à une des 4 stats (voir 6c). Tu choisis laquelle, mais tu dois pouvoir la justifier narrativement.

**Option B — Dégradation d'équipement.** Une pièce d'équipement de ton choix passe à l'état **Endommagé** (si déjà endommagé, elle est **Détruite**). Tu décris comment ça arrive.

### Restrictions

- Tu ne peux pas pousser un Échec critique (Nat 20).
- Tu ne peux pas pousser un jet déjà poussé.
- Pousser un jet est volontaire — personne ne t'y oblige.
- Tous les dés sont relancés (y compris Avantage/Désavantage).

> **Philosophie :** Pousser un jet, c'est forcer le destin. Soit ton corps paie (condition), soit ton matériel paie (dégradation). Le joueur choisit ce qu'il est prêt à sacrifier. C'est un choix tactique profond — est-ce que tu risques ta cybernétique à +2 pour réussir ce hack, ou tu préfères devenir Stressé ?

---

## 6c. CONDITIONS — 4 STATS, 4 CONDITIONS (nouveau v4)

Chaque condition donne **Désavantage sur tous les jets liés à une stat** (attaques, saves, compétences utilisant cette stat).

| Stat | Condition | Exemples narratifs |
|---|---|---|
| **STR** | **Épuisé** | Muscles fatigués, souffle court, mains tremblantes |
| **DEX** | **Déstabilisé** | Équilibre perturbé, réflexes ralentis, vision floue |
| **WIT** | **Confus** | Pensées embrouillées, déconcentré, surcharge cognitive |
| **EMP** | **Stressé** | Nerfs à vif, irritable, détaché émotionnellement |

### Accumulation

- Tu ne peux pas avoir la même condition deux fois.
- Si tu as déjà les 4 conditions, tu ne peux plus pousser de jets.
- Les conditions de monstre/environnement s'empilent avec les conditions de push.

### Guérison des conditions

- **Stretch Rest (15 min) :** Soigne **1 condition** au choix.
- **Shift Rest (6-8h) :** Soigne **toutes** les conditions.
- **Pouvoir de classe :** Certaines capacités (Medic, Marshal) peuvent soigner 1 condition en combat.

### Interaction Conditions × Shaken

Les conditions et le Shaken sont des mécaniques **séparées** qui se cumulent :
- **Shaken** = Désavantage sur **tout** (état de choc global). Se récupère par save STR début de tour.
- **Conditions** = Désavantage sur **une stat spécifique**. Se récupère par repos ou pouvoir de classe.

Un personnage Shaken 1 ET Confus a : Désavantage sur tout (Shaken) + Désavantage supplémentaire sur les jets WIT (Confus). Sur un jet WIT, il a **double Désavantage** (3d20 garde le plus haut).

---

## 7. TECH LEVELS — SYSTÈME D'ULTRAMODERN5

Directement repris d'UM5. Le Tech Level (TL) définit le niveau technologique du setting et de chaque objet.

### Échelle des Tech Levels

| TL | Similitude | Véhicules | Armes | Médical |
|----|-----------|-----------|-------|---------|
| **0** | Pré-industriel → mi-18e siècle | Gliders, vapeur archaïque | Propulseurs chimiques, mousquets | Guérison naturelle, chirurgie basique |
| **1** | 19e → début 20e siècle | Combustion interne, hélices | Revolvers, fusils à verrou | Vaccins, début génétique |
| **2** | Mi-20e → futur proche | Électronique, fly-by-wire | Suivi informatique, calibres avancés | Scanners, IRM, rayons X |
| **3** | Début 21e siècle avancé | VTOL, jets sans ailes, maglev | Railcanons, laser prototype, exo-armure proto | La plupart des maladies curables, nanotech labo |
| **4** | Haute technologie | Robots avancés, ramjets, exo-armure mass-prod | Lasers "tunables", plasma | Nanotech soigne tout, régénération |
| **5** | Indistinguable de la magie | Anti-gravité commune | Disrupteurs, désintégrateurs | Reconstruction corporelle complète |

### Application aux objets et au jeu

| TL de l'objet | Rareté par défaut |
|---------------|------------------|
| TL 0 et TL 1 | Commun |
| TL 2 | Peu commun (Uncommon) |
| TL 3 | Rare |
| TL 4 | Très rare |
| TL 5 | Légendaire |

**Règle de coût UM5 :** Le prix d'un objet = prix de base TL1 × (TL × 10). Si le setting est TL3, les objets TL3 et inférieurs coûtent 50% moins cher. Les objets au-dessus du TL du setting gardent leur prix mais deviennent très difficiles à trouver.

**Le MJ n'est pas obligé de fixer un seul TL.** Un setting peut avoir des armes TL2, des véhicules TL3, et des mecha TL4. Tant que ça sert le thème.

---

## 8. CLASSES — 5 CORE, MÉTHODE NIMBLE

> **Changement v4 :** Les 11 classes UM5 sont réduites à **5 classes core**. Le Heavy, Gunslinger, Sniper, Martial Artist, Face et Civilian sont absorbés ou reportés à une extension future. Cette réduction permet de concentrer l'effort de design et de s'assurer que chaque classe a une identité mécanique forte et unique.

### Les 5 classes core

| Classe | Vigueur | Stat principale | Rôle | Verbe |
|--------|---------|----------------|------|-------|
| **Grounder** | 10 | STR ou DEX | Soldat polyvalent, front-line | Tenir et frapper |
| **Infiltrator** | 8 | DEX | Ops clandestines, dégâts burst | Frapper et disparaître |
| **Medic** | 8 | WIT | Soins, déclencheur de surges allié | Maintenir en vie |
| **Marshal** | 8 | EMP | Ordres tactiques, leader de terrain | Diriger et galvaniser |
| **Tech** | 6 | WIT | Drones, hacking, gadgets, contrôle | Contrôler le terrain |

### Filiation UM5 → 5 core

| Classe core | Absorbe les archétypes UM5 | Ce qui est couvert |
|-------------|---------------------------|-------------------|
| **Grounder** | Grounder, Heavy (sous-classe Tête de Pont), Sniper (sous-classe Éclaireur) | Toutes armes à feu, tank, tir de précision, suppression |
| **Infiltrator** | Infiltrator, Gunslinger, Martial Artist | Stealth, burst damage, mobilité, combat rapproché |
| **Medic** | Medic | Soins, déclencheur de surges, soutien de terrain |
| **Marshal** | Marshal, Face | Leadership, ordres, galvanisation, social |
| **Tech** | Techie | Hacking, drones, gadgets, ingénierie, contrôle de terrain |

### Structure de classe sur 15 niveaux (template Nimble-ifié)

| Niveau | Contenu type |
|---|---|
| **1** | Features de base + mécanique signature + mécanique de ressource |
| **2** | Feature secondaire |
| **3** | **Sous-classe** (choix entre 2-3 options) + feature de sous-classe |
| **4** | **Stat +1** (au choix) |
| **5** | Feature majeure de classe |
| **6** | Feature de classe ou pick-list |
| **7** | **Sous-classe feature** |
| **8** | **Stat +1** (au choix) |
| **9** | Feature majeure de classe |
| **10** | Feature de classe ou pick-list |
| **11** | **Sous-classe feature** |
| **12** | **Stat +1** (au choix) |
| **13** | Feature majeure de classe |
| **14** | Feature de classe ou pick-list |
| **15** | **Capstone** de classe + sous-classe capstone |

### Saves par classe

| Classe | Saves proficients | Saves désavantagés |
|--------|----------------|-------------------|
| **Grounder** | STR, DEX | WIT, EMP |
| **Infiltrator** | DEX, WIT | STR, EMP |
| **Medic** | WIT, EMP | STR, DEX |
| **Marshal** | STR, EMP | DEX, WIT |
| **Tech** | WIT, DEX | STR, EMP |

### Le Grounder — Classe de référence

Le Grounder est la première classe entièrement rédigée sur 15 niveaux (voir **classe_grounder_v3.md**). Résumé :

- **Mécanique signature :** Doctrine de Tir (Assaut ou Précision, swappable par Shift)
- **Mécanique de ressource :** Élan de Combat (max = prof : 1/2/3)
- **Arsenal à choix :** Fraternité d'Armes (6 picks, capacités Élan 0/1/2)
- **Sous-classes :** Tête de Pont (tank, aggro) / Éclaireur (mobilité, frappes chirurgicales)
- **Progression clé :** Genou à Terre (2), Double Tap (5), Triple Tap (9), Quadruple Tap (13)
- **Capstone (15) :** Soldat Imparable + All In

### Classes restantes — Esquisse

**Infiltrator :** Stealth + burst damage. Ressource : Shadow Points. Sous-classes : Cleaner / Ghost.

**Medic :** Déclencheur de surges allié. Ressource : Triage Points. Sous-classes : Field Surgeon / Combat Medic.

**Marshal :** Ordres tactiques. Ressource : Command Points. Sous-classes : Stratège / Meneur.

**Tech :** Drones + hacking + gadgets. Ressource : Tech Points. Sous-classes : Hacker / Engineer.


---

## 9. LOOT — DEUXIÈME JAMBE DE PROGRESSION

> **Changement v4 :** Le loot n'est plus juste du butin — c'est une **jambe de progression** parallèle à la proficiency. Les bonus numériques (+0 à +3) poussent le Score au-delà du plafond nu. Mais le loot est **volatile** : il se casse, se perd, se fait voler. La rotation du loot est la boucle de gameplay centrale.

### Le loot comme progression

| Rareté | Bonus numérique | Qualités spéciales | Acquisition typique |
|--------|----------------|-------------------|-------------------|
| **Standard** (blanc) | +0 | 0–1 qualité | Acheté, trouvé, début de campagne |
| **Rare** (bleu) | +1 à +2 | 1–2 qualités | Loot de session, récompense de mission |
| **Légendaire** (or) | +2 à +3 | 2–3 qualités | Événement narratif majeur, boss loot |

**Rythme :** 1–2 pièces de loot intéressantes par session (philosophie ICRPG). Pas juste "+1 au tir" mais des objets qui changent la façon de jouer, avec un nom, une histoire, et un effet mécanique.

### Dégradation du loot — 3 états

Chaque pièce d'équipement notable (armes, armures, implants, gadgets — pas les consommables) a un état :

| État | Effet | Visuel fiche |
|---|---|---|
| **Neuf** (✓) | Fonctionne normalement. Bonus plein. | Case vide |
| **Endommagé** (⚠) | **Le bonus numérique est réduit de moitié** (arrondi inf). Qualités spéciales fonctionnent encore. | Case cochée 1× |
| **Détruit** (✗) | L'objet est **inutilisable**. Plus aucun bonus ni qualité. | Case cochée 2× |

**Exemples :**

| Objet | Neuf | Endommagé | Détruit |
|---|---|---|---|
| Fusil d'assaut +2, Pierce 1 | +2 au Score, Pierce 1 | +1 au Score, Pierce 1 | Inutilisable |
| Implant cybernétique +3 STR | +3 STR | +1 STR | Dysfonctionnel |
| Armure tactique (Armure 5) | Armure 5 | Armure 2 | Ne protège plus |

### Sources de dégradation

- **Push de jet (volontaire) :** Le joueur choisit de dégrader une pièce d'équipement au lieu de prendre une condition (voir section 9b).
- **Critique ennemi (Réussite critique) :** Le MJ peut choisir de dégrader un équipement de la cible au lieu du bonus de dégâts.
- **Pouvoirs spéciaux :** EMP (grille l'électronique), acide (ronge l'armure), hacker (jam une cybernétique), etc.
- **Jam temporaire :** Certaines attaques "jamment" un équipement pour X tours (fonctionne comme Endommagé) sans le dégrader réellement.
- **Fumble (Échec critique) :** La table de fumble peut inclure "ton arme est endommagée".
- **Environnement :** Explosions, chutes, conditions extrêmes.

### Réparation

| Action | Durée | Résultat |
|---|---|---|
| **Réparation de terrain** (Engineering, diff 3) | 1 Stretch | Endommagé → Neuf |
| **Réparation d'atelier** (Engineering, diff 1) | 1 Shift | Endommagé → Neuf |
| **Reconstruction** (Engineering, diff 5, pièces) | 1 Shift | Détruit → Endommagé |
| **Remplacement** | Variable (loot, achat, craft) | Détruit → nouvel objet |

### Boucle de gameplay

**Acquérir du loot → l'utiliser → le perdre/casser → en acquérir du nouveau.** La rotation est constante. Un personnage niv 15 avec un fusil +3 légendaire tient à ce fusil — mais un critique ennemi peut l'endommager. Il doit trouver un atelier, un Tech allié, ou un nouveau fusil. C'est la tension.

### Philosophie
Comme ICRPG : chaque session offre du loot intéressant. Pas juste "+1 au tir" mais des objets qui changent la façon de jouer, avec un nom, une histoire, et un effet mécanique.

### Structure des tables de loot

On crée des tables par contexte, chacune avec 20 entrées (d20 roll) :

1. **Loot urbain** — Ce qu'on trouve en ville, marchés noirs, appartements
2. **Loot militaire** — Bases, convois, champs de bataille
3. **Loot corporatif** — Bureaux, labos, coffres d'entreprise
4. **Loot tech/hacker** — Serveurs, ateliers, épaves de drones
5. **Loot médical** — Hôpitaux, labos pharmaceutiques, cliniques clandestines
6. **Loot alien/anomalie** — Sites de crash, zones contaminées, artefacts
7. **Loot véhicule** — Épaves, garages, hangars
8. **Loot de contrebande** — Cargaisons piratées, caches secrètes

### 3 niveaux de rareté

| Rareté | Couleur | Description |
|--------|---------|-------------|
| **Standard** | Blanc | Fonctionnel, utile, pas de pouvoir spécial |
| **Rare** | Bleu | Un pouvoir cool, un trait spécial, un avantage situationnel |
| **Légendaire** | Or | Change la donne. Définit un personnage. Unique. |

### Exemples de loot (noms UM5, qualités Genesys)

| d20 | Objet | Rareté | TL | Qualités & Effet |
|-----|-------|--------|----|------------------|
| 1-3 | Munitions perforantes standard | Standard | 2 | Pierce 2. Ignore 2 points d'Armure. |
| 4-5 | Gilet tactique renforcé | Standard | 2 | Armure 5, Deflection 1. Léger. |
| 6-7 | ESP Maelstrom (compact) | Rare | 2 | 1d8, Auto-fire, 400 coups. Bascule en rafale pour toucher plusieurs cibles. |
| 8-9 | Kit médical de terrain TL3 | Rare | 3 | Soigne 2d8+INT, retire 1 Wound, Limited Ammo 3. |
| 10-11 | God's Eye sniper scope | Rare | 2 | Attachment : Accurate 2, Pierce 2. Lunette de précision. |
| 12-13 | Gyrojet Lancejet | Rare | 2 | 1d12, Auto-fire (2d8), Guided 2. Roquettes auto-guidées. |
| 14-15 | Ion Cannon (portable) | Rare | 3 | 1d10 lightning, Stun 3, Disorient 2. Surcharge électronique. |
| 16-17 | Exo-armor frame (légère) | Rare | 3 | Armure 9, Enhanced Lifting Servos, Cumbersome 3. -5ft speed. |
| 18-19 | Railcannon | Légendaire | 4 | 1d10 piercing, Pierce 5, Auto-fire, Slow-Firing 1. Tir magnétique dévastateur. |
| 20 | Arc Rifle | Légendaire | 4 | 1d12 lightning, Stun 4, Concussive 1, Burn 1. Shaken automatique. |

---

## 10. CRAFTING — BASÉ SUR GENESYS (HARD POINTS + QUALITÉS)

### Le système en résumé

Chaque objet a des **Hard Points** (slots de modification). On peut y installer des **Attachments** (modifications) qui ajoutent des **Qualités** (propriétés spéciales).

### Hard Points par objet

| Type d'objet | Hard Points |
|--------------|------------|
| Arme légère (pistolet) | 1-2 |
| Arme moyenne (fusil) | 2-3 |
| Arme lourde | 3-4 |
| Armure légère | 1-2 |
| Armure moyenne | 2-3 |
| Armure lourde / Exo | 3-5 |
| Gadget / Outil | 1-2 |
| Véhicule | 4-8 |

### Qualités d'items — NOMENCLATURE GENESYS

> **Source :** Toutes les qualités ci-dessous proviennent du système Genesys (FFG), adaptées mécaniquement à notre résolution d20.
> **Noms des armes :** Les intitulés des armes eux-mêmes (ESP Maelstrom, Railcannon, Arc Rifle, etc.) proviennent d'Ultramodern5.

Les qualités sont soit **Passives** (toujours actives) soit **Actives** (à déclencher). Les qualités actives se déclenchent sur un **résultat de 1-2 sur le d20** ou en dépensant une action bonus, sauf mention contraire. Chaque qualité a un **Rating** (indice numérique) qui affecte sa puissance.

#### Qualités d'arme

| Qualité | Type | Rating | Effet (adapté d20) |
|---------|------|--------|--------------------|
| **Accurate** | Passive | 1-2 | +1 au Score d'attaque par rang. Arme précise par design ou technologie. |
| **Auto-fire** | Active | — | Tir en rafale. L'attaquant subit désavantage au jet. Sur touché, peut dépenser un résultat de 1-2 pour infliger un touché additionnel (même cible ou cible adjacente). Chaque touché inflige les dégâts de base. |
| **Blast** | Active | X | Explosion / dispersion. Sur touché, chaque personnage engagé avec (adjacent à) la cible subit X dégâts. Sur miss, peut se déclencher sur résultat 1-2 : la cible ET les adjacents subissent X dégâts. |
| **Breach** | Passive | X | Perce les blindages lourds. Ignore X × 10 points d'Armure (principalement véhicules/exo-armure). Chaque rang de Breach = ignorer 1 point d'armure véhicule ou 10 Armure personnel. |
| **Burn** | Active | X | Dégâts persistants (feu, acide, plasma). Sur déclenchement, la cible subit les dégâts de base de l'arme au début de chacun de ses tours pendant X rounds. La victime peut utiliser 1 action pour un save DEX afin d'éteindre les flammes. |
| **Concussive** | Active | X | Choc violent. Sur déclenchement, la cible est **Staggered** (ne peut effectuer d'actions, seulement se déplacer) pendant X rounds. Extrêmement puissant — Rating max recommandé : 1-2. |
| **Cumbersome** | Passive | X | Arme lourde/encombrante. Nécessite STR ≥ X pour être maniée correctement. Pour chaque point de STR manquant, désavantage aux jets d'attaque. |
| **Defensive** | Passive | X | L'objet augmente la défense au corps à corps. +X à l'Armure contre les attaques de mêlée uniquement. |
| **Deflection** | Passive | X | L'objet augmente la défense à distance. +X à l'Armure contre les attaques à distance uniquement. |
| **Disorient** | Active | X | Désoriente la cible. Sur déclenchement, la cible subit désavantage à tous ses jets de compétence pendant X rounds. |
| **Ensnare** | Active | X | Immobilise la cible (filet, mousse, grappin). Sur déclenchement, la cible ne peut plus se déplacer pendant X rounds. La cible peut utiliser 1 action pour un save STR afin de se libérer. |
| **Guided** | Active | X | Projectile auto-guidé. Si l'attaque rate, le tireur peut retenter un jet d'attaque à la fin du round (diff X). Peut se déclencher à chaque round suivant tant que le projectile est en vol. |
| **Inaccurate** | Passive | X | Arme imprécise. Désavantage aux jets d'attaque (ou -X au jet si Rating > 1). Utilisé pour équilibrer des armes puissantes. |
| **Inferior** | Passive | — | Fabrication médiocre. L'arme génère automatiquement un effet négatif mineur (au choix du MJ) à chaque utilisation. |
| **Knockdown** | Active | — | Renverse la cible. Sur déclenchement, une cible touchée est mise **à terre** (prone). |
| **Limited Ammo** | Passive | X | Munitions limitées. L'arme peut tirer X fois avant de devoir être rechargée (1 action). Pour les grenades : Limited Ammo 1 = usage unique. |
| **Linked** | Active | X | Armes couplées (tourelles, doubles canons). Sur touché, peut infliger jusqu'à X touchés additionnels sur la même cible (chaque touché = dégâts de base). |
| **Pierce** | Passive | X | Pénétration. Les touchés de cette arme ignorent X points d'Armure. Si Pierce > Armure de la cible, le surplus n'a pas d'effet additionnel. |
| **Prepare** | Passive | X | Préparation requise. L'utilisateur doit dépenser X actions de préparation avant de pouvoir utiliser l'arme (déployer trépied, verrouiller cible, etc.). |
| **Reinforced** | Passive | — | Indestructible. L'arme est immunisée à l'effet Sunder. Sur une armure : le porteur est immunisé aux effets Pierce et Breach. |
| **Slow-Firing** | Passive | X | Rechargement lent. Après avoir tiré, l'arme ne peut pas être utilisée pendant X rounds (refroidissement, recharge capaciteurs). |
| **Stun** | Active | X | Choc neuronal. Sur déclenchement, inflige X points de Strain (stress/fatigue) en plus des dégâts normaux. Le Strain n'est pas réduit par l'Armure. |
| **Stun Damage** | Passive | — | Dégâts non-létaux. Tous les dégâts de cette arme sont convertis en Strain au lieu de blessures. La cible tombe inconsciente si son Strain dépasse son seuil, mais ne meurt pas. |
| **Sunder** | Active | — | Destruction d'équipement. Sur déclenchement, le tireur peut choisir de détruire/endommager une pièce d'équipement de la cible au lieu d'infliger des dégâts normaux. |
| **Unwieldy** | Passive | X | Difficile à manier. Nécessite DEX ≥ X pour être utilisée correctement. Pour chaque point de DEX manquant, désavantage aux jets d'attaque. |
| **Vicious** | Passive | X | Blessures aggravées. Ajoute +X×10 au jet sur la table des Blessures Critiques quand un crit est infligé. Rend les crits plus dévastateurs. |

#### Qualités d'armure (Genesys + ajouts SF)

| Qualité | Type | Effet |
|---------|------|-------|
| **Reinforced** | Passive | Immunise l'Armure du porteur aux effets Pierce et Breach. Armure "impénétrable". |
| **Deflective Plating** | Passive | +X Armure contre les attaques à distance uniquement. |
| **Defensive** | Passive | +X Armure contre les attaques de mêlée uniquement. |
| **Sealed** | Passive | Protection environnementale : vide spatial, gaz toxiques, radiations, pression. |
| **Enhanced Lifting Servos** | Passive | Augmente la capacité de port de charges. Réduit la qualité Cumbersome des armes portées de 2. |
| **Intimidating Visage** | Passive | Avantage aux jets d'intimidation quand l'armure est portée. |
| **EMP Shielding** | Passive | Immunise l'armure et les systèmes intégrés aux effets EMP/Pincher. |
| **Stabilized** | Passive | Avantage aux jets de sang-froid (Shaken). L'armure absorbe les chocs et stabilise le porteur. |
| **Stealth Coating** | Passive | Avantage aux jets de discrétion. Revêtement anti-détection. |
| **Vacuum Sealed** | Passive | Permet de survivre dans le vide spatial. Inclut réserve d'oxygène. |

#### Principe de design : Distribution des dés, fiabilité et pénétration d'armure

> **RÈGLE FONDAMENTALE — Le nombre de dés de dégâts d'une arme est un indicateur de qualité, indépendamment de la moyenne de dégâts.**

Dans un système Armure (réduction d'armure), la **distribution** des dégâts est aussi importante que leur **moyenne**. Deux armes avec la même moyenne de dégâts peuvent avoir des performances radicalement différentes contre une armure.

**Le principe :** Un dé unique produit une distribution plate (chaque résultat est équiprobable). Plusieurs dés produisent une courbe en cloche (les résultats proches de la moyenne sont beaucoup plus fréquents). Contre une Armure fixe, la courbe en cloche **perce plus souvent** parce que ses résultats se concentrent au-dessus du seuil d'absorption.

**Démonstration contre Armure 5 :**

| Arme | Moyenne | Distribution | % de tirs absorbés (0 net) | Dégâts nets moyens |
|------|---------|-------------|---------------------------|-------------------|
| 1d10 | 5.5 | Plate | **50%** (résultats 1-5) | 2.75 |
| 2d4+1 | 6.0 | Cloche douce | **25%** (résultats 3-5) | 3.25 |
| 2d6 | 7.0 | Cloche | **16%** (résultats 2-5) | 4.47 |
| 3d4 | 7.5 | Cloche serrée | **~10%** (résultats 3-5) | 5.06 |

À moyenne comparable, passer de 1 dé à 2 dés **divise par deux** le taux d'absorption. Passer à 3 dés le divise par cinq. Le nombre de dés mesure la **fiabilité de pénétration** de l'arme, pas juste sa puissance brute.

**Ce que ça signifie pour le design d'armes :**

- **1 dé (1d6, 1d8, 1d10, 1d12)** = Arme brute, primitive, ou à haut risque / haut reward. Capable de coups dévastateurs (max élevé) mais aussi de ratés complets contre l'armure. Profil typique des armes TL0-1 : mousquets, revolvers, armes artisanales, armes alien imprévisibles.
- **2 dés (2d4, 2d6, 2d8)** = Arme fiable, manufacturée, standardisée. Les dégâts se concentrent autour de la moyenne, l'armure est percée de façon constante. Profil typique des armes TL2-3 : fusils d'assaut modernes, armes de précision, armes à énergie de première génération.
- **3+ dés (3d4, 3d6, 2d8+bonus)** = Arme technologiquement supérieure, redoutable. Perce l'armure de façon quasi-garantie, dégâts prévisibles et constants. Profil typique des armes TL4-5 : railcannons, lasers tunables, plasma, armes à particules.

**La technologie ne donne pas juste "plus de dégâts" — elle donne de la fiabilité.**

**Application au crafting et au loot :** Un Attachment ou une qualité d'arme peut transformer le profil de dés d'une arme sans changer sa moyenne. Par exemple, un "Barrel Stabilizer" transforme 1d12 → 2d6 (même moyenne 7, mais pénétration d'armure radicalement meilleure). C'est un upgrade extrêmement précieux qui n'apparaît pas dans les chiffres bruts — il faut le comprendre pour l'apprécier. Ce type de modification est un marqueur de maîtrise du système pour les joueurs expérimentés.

**Corrélation TL ↔ Profil de dés (guide pour le MJ) :**

| TL | Profil de dés typique | Philosophie |
|----|-----------------------|------------|
| 0-1 | 1 dé (1d6 à 1d12) | Imprévisible, artisanal, brutal |
| 2 | 1 dé + bonus fixe (1d8+2, 1d10+3) | Manufacturé, le bonus fixe garantit un plancher |
| 3 | 2 dés (2d6, 2d8) | Standardisé, fiable, perce les armures courantes |
| 4 | 2 dés + bonus ou 3 dés (2d8+3, 3d6) | Haute technologie, perce presque tout |
| 5 | 3+ dés (3d8, 4d6) | Dévastateur, pénétration quasi-garantie |

#### Notes de design (issues de Genesys)

- **Nombre de qualités par arme :** Maximum 3-4 qualités par arme. N'hésite pas à n'en mettre qu'une seule, voire aucune.
- **Pierce vs Breach :** Ne jamais mettre les deux sur la même arme. Pierce = anti-personnel, Breach = anti-véhicule/exo.
- **Cumbersome + Unwieldy :** Jamais de Rating 1 (tous les personnages ont minimum 1 en STR/DEX, donc ça ne fait rien).
- **Vicious :** Puissant. Ne pas mettre de Rating supérieur à 5. Au-delà, un crit peut tuer instantanément un personnage en pleine santé.
- **Burn et Ensnare :** Rating 1-3 recommandé, 4 max très rare.
- **Concussive :** Rating 1 seulement dans 99% des cas. Extrêmement punitif.
- **Limited Ammo :** En combat, les rencontres durent 4-5 rounds. Un Rating supérieur à 5 signifie que le rechargement n'entrera jamais en jeu.
- **Guided :** Rating 2-4 recommandé. Rating 1 = le projectile ne touche quasi jamais en second tir. Rating 5 = meilleur que le tir initial.

### Processus de Crafting

1. **Prérequis :** Proficiency en Engineering/Mechanics + Kit d'ingénierie du bon TL
2. **Choix de la base :** Type d'objet + stats par défaut
3. **Ajout d'Attachments :** Chaque attachment coûte des Hard Points + matériaux + temps
4. **Jet de Crafting :** WIT + Engineering vs. difficulté (basée sur rareté/TL de l'objet) — roll-under
   - Succès → objet créé
   - Échec → matériaux consommés, résultat partiel
   - Nat 1 (Réussite critique) → trait bonus gratuit ou qualité supérieure
   - Nat 20 (Échec critique) → matériaux détruits, possible défaut dangereux
5. **Combiner des objets (avancé) :** Sacrifier un objet pour transférer un trait vers un autre. Difficulté plus élevée.

### Influence du TL sur le crafting (UM5)
Le TL de ton kit d'ingénierie agit comme multiplicateur sur ta vitesse de construction. Un kit TL3 permet de travailler 3× plus vite qu'un kit TL1. Tu ne peux pas crafter un objet d'un TL supérieur à ton kit.

---

## 11. MONSTRES & PNJ — MONSTER BUILDER (MÉTHODE NIMBLE)

### Philosophie
Comme Nimble : des stat blocks minimalistes, lisibles en un coup d'œil, avec des pouvoirs/variantes qui les rendent uniques. Le MJ ne devrait jamais avoir besoin de plus de 5 secondes pour comprendre un PNJ.

**Pas de défense passive.** Ce qui rend un ennemi dangereux, c'est son Armure, ses PV/Blessures, ses capacités, et sa catégorie.

### Trois catégories d'ennemis

| Catégorie | PV/Blessures | Initiative | Réactions | Ce qui les rend dangereux |
|---|---|---|---|---|
| **MINION** | **Aucun.** 1 touche = éliminé. | 1 carte par groupe | Jamais | Le nombre. Attaque groupée. |
| **ADVERSAIRE** | PV + Blessures normaux | 1 carte chacun | Seulement si capacité spéciale | Stats, Armure, armes. Comparable à un PJ. |
| **BOSS** | PV + Blessures élevés | **2+ cartes** (agit plusieurs fois/round) | Oui (parade, riposte, esquive) | Multiple tours, capacités spéciales, Armure élevée. |

### Stat block par défaut
Sauf indication contraire, un PNJ/monstre : taille moyenne, pas d'armure, speed 6, attaques Reach 1, lance 1d20 pour toutes les sauvegardes.

### Table de construction rapide

> **Note :** Les HP dans cette table représentent les **PV** du PNJ. Les Blessures = Vigueur + bonus STR du PNJ (typiquement 6-15).

| Niveau PNJ | PV (no armor) | PV (med armor) | PV (heavy armor) | Blessures | Dégâts/round | Score Attaque | Armure typique |
|---|---|---|---|---|---|---|---|
| 1/4 | 12 | 9 | 7 | 10 | 3 | 8 | 0-2 |
| 1/2 | 18 | 15 | 11 | 10 | 7 | 9 | 2-3 |
| 1 | 26 | 20 | 16 | 12 | 11 | 9 | 3-4 |
| 2 | 34 | 27 | 20 | 12 | 13 | 10 | 4-5 |
| 3 | 41 | 33 | 25 | 14 | 15 | 10 | 4-5 |
| 5 | 58 | 46 | 35 | 14 | 19 | 11 | 5-7 |
| 8 | 91 | 73 | 55 | 16 | 26 | 12 | 6-8 |
| 10 | 118 | 94 | 71 | 16 | 30 | 13 | 7-9 |
| 12 | 160 | 128 | 96 | 18 | 37 | 14 | 8-10 |
| 15 | 220 | 176 | 132 | 20 | 45 | 16 | 9-12 |

> **Note v4 :** Les Scores Attaque des PNJ reflètent la nouvelle échelle prof +1/+2/+3. Un PNJ niv 15 a un Score de 16 (80% de toucher), comparable à un héros niv 15 nu. Les pouvoirs de monstre (Désavantage, capacités spéciales) créent la difficulté — pas un Score plus élevé.

### Armure des PNJ (simplifiée comme Nimble)
- **Pas d'armure :** Dégâts normaux
- **Armure Moyenne (M) :** Ignore les modificateurs de stats, seuls les dés comptent
- **Armure Lourde (H) :** Ignore les modificateurs ET divise les dés par 2

### Pouvoirs de monstres/PNJ — Liste de variantes

Adapté de Nimble pour le contexte moderne/SF :

| Pouvoir | Effet |
|---------|-------|
| **Aggressive** | +2 speed si se déplace vers un ennemi |
| **Blindfire** | Peut tirer sans ligne de vue (avec Désavantage) |
| **Covering Fire** | Force un jet de Shaken sur les ennemis dans une zone, même sans toucher |
| **Cybernetic** | Un implant spécial (vision thermique, bras renforcé, etc.) |
| **Drone Support** | Contrôle 1-3 drones minions |
| **EMP Burst** | Désactive l'électronique dans X cases, 1/rencontre |
| **Formation** | Armure augmente de 1 par allié adjacent |
| **Frenzy** | Dégâts augmentent quand PV < 50% |
| **Hacker** | Peut pirater les équipements des héros |
| **Medic** | Soigne un allié de Xd6 PV, 1/tour |
| **Mounted** | En véhicule, +speed, +dégâts après mouvement |
| **Pack Tactics** | Avantage à l'attaque si un allié est adjacent à la cible |
| **Phase 2** (Boss) | Quand PV tombent à 0, regagne X PV et change de pattern d'attaque |
| **Shielded** | Champ de force : ignore les X premiers dégâts par tour |
| **Sniper** | +dégâts à longue portée, peut tirer sans révéler sa position |
| **Suicide Bomber** | Explose à la mort, dégâts de zone |
| **Suppressor** | Attaques forcent Désavantage sur la cible au prochain tour |
| **Tactical Retreat** | Fuit quand PV < 25%, peut revenir avec des renforts |

### Minions
- **Pas de PV/Blessures à tracker.** Tout dégât tue un minion.
- **1 carte d'initiative pour le groupe.** Tous agissent au même moment.
- **Attaque simple.** 1 dé de dégât, rate sur un 20 (Échec critique).
- **Attaque groupée.** 3 minions sur une cible = combine les dés en une seule attaque.
- **Exemples :** Gardes de sécurité, soldats basiques, drones, zombies/infectés.

### Adversaires
- **PV et Blessures normaux.** On les tracke individuellement.
- **1 carte d'initiative chacun.** Agissent normalement.
- **Pas de réaction** sauf si une capacité spéciale le précise.
- **Exemples :** Mercenaire, sniper, hacker, officier.

### Boss (Nemesis)
- **PV et Blessures élevés.** PV = table × 1.5, Armure = table + 1.
- **2+ cartes d'initiative.** Agissent 2 fois (ou plus) par round.
- **Peuvent utiliser des réactions** (parade, esquive, riposte).
- **Capacités spéciales** : Phase 2, appel de renforts, régénération, actions légendaires.
- **Exemples :** Officier d'élite, cyborg de guerre, IA de combat, commandant ennemi.

### Exemple de stat block — Adversaire

```
MERCENAIRE VÉTÉRAN — Adversaire, Niveau 3
PV: 33 | Blessures: 12 (Vig 10 + bonus STR 2) | Speed: 6 | Armure: 5 (gilet balistique)
Initiative: 1 carte | Saves: STR 10 (+1 prof) = 11

ATTAQUE: Fusil d'assaut Score 10 — 2d8+4 (Range 12)
         Couteau Score 10 — 1d6+3 (Reach 1)

POUVOIRS:
• Covering Fire (1 action) — Tous les ennemis dans un cône de 3 cases
  doivent faire un jet de Shaken (difficulté 4).
• Pack Tactics — Avantage si un allié est adjacent à la cible.
• Tactical Retreat — Fuit sous couvert si PV < 10.
```

### Exemple de stat block — Boss

```
COMMANDANT NEXAGEN — Boss, Niveau 5
PV: 60 | Blessures: 18 | Speed: 6 | Armure: 8 (armure tactique TL3)
Initiative: 2 cartes (agit 2×/round) | Saves: STR 10 (+1 prof), WIT 11 (+1 prof)

ATTAQUE: Pistolet lourd Score 11 — 1d10+4 piercing (Range 10)
         Matraque électrique Score 10 — 1d8+3 + Stun (Reach 1)

POUVOIRS:
• Commandement (1 action) — Tous les alliés à 6 cases gagnent Avantage pendant 1 round.
• Appel de renforts (2 actions) — 1d4 gardes minions arrivent en 2 rounds.
• Phase 2 — Quand PV tombent à 0, regagne 30 PV. Perd Commandement, gagne Frenzy.
• Riposte (réaction) — Quand raté en mêlée, contre-attaque gratuite.
```

---

## 12. HACKING & FIREWALL

### Principe

Le hacking fonctionne exactement comme le combat physique, avec le même roll-under :

- **Combat physique :** Score d'attaque → touché si ≤ seuil → Armure réduit les dégâts
- **Hacking :** Score de Hacking vs **Firewall** du système → protections réduisent l'effet

Le Firewall est la **défense numérique**. C'est une valeur liée à un objet (un routeur, un serveur, un implant, un drone) — pas à une créature.

### Score de Hacking

**Score = WIT + proficiency** (si proficient en Computer Use, skill trained-only)

Un personnage non-formé en Computer Use ne peut tout simplement pas hacker. C'est un skill trained-only.

### Firewall — La défense numérique

Le Firewall est un **chiffre fixe** attaché à chaque système, appareil, ou réseau. Plus le TL ou la sécurité est élevée, plus le Firewall est haut.

| Type de système | Firewall | Exemples |
|---|---|---|
| Pas de sécurité | 0 | Terminal public, appareil civil non-protégé |
| Sécurité basique | 1-2 | Ordinateur personnel, drone commercial, véhicule civil |
| Sécurité standard | 3-4 | Réseau d'entreprise, terminal militaire de base, implant standard |
| Sécurité renforcée | 5-6 | Serveur corporatif, drone militaire, système de sécurité de base |
| Sécurité haute | 7-8 | Infrastructure critique, réseau militaire classifié, IA de défense |
| Sécurité maximale | 9-10 | Banque de données top-secret, noyau d'IA souveraine, système black-ops |

### Résolution

```
Seuil = Score Hacking - Firewall du système
Rouler d20 ≤ Seuil = Réussite
```

**Exemple :** Un Techie (WIT 10, prof +2 en Computer Use) tente de pirater un drone militaire (Firewall 4).
Score = 10 + 2 = 12. Seuil = 12 - 4 = **8**. Roule 8 ou moins → 40%.

### Actions de hacking

| Action | Coût | Effet |
|---|---|---|
| **Scanner** | 1 action | Identifier le Firewall d'un système, ses protections, ses vulnérabilités |
| **Intrusion** | 2 actions | Pénétrer un système (jet de hacking vs Firewall) |
| **Contrôle** | 1 action | Une fois dedans : ouvrir une porte, désactiver une alarme, lire des données |
| **Sabotage** | 2 actions | Détruire des données, planter un virus, surcharger un système |
| **Prise de contrôle** | 2 actions | Prendre le contrôle d'un drone, tourelle, véhicule (jet opposé si opérateur) |

### Détection et contre-mesures

Chaque action de hacking après l'intrusion a une chance d'être détectée. Le système fait un "jet de détection" : difficulté = bonus WIT du hacker (= WIT - 8). Si le système détecte l'intrusion, il peut verrouiller le hacker (déconnexion) ou activer des contre-mesures (ICE).

### Lien avec le TL

| TL | Firewall typique | Notes |
|---|---|---|
| 0-1 | 0 | Pas de systèmes informatiques |
| 2 | 1-3 | Systèmes basiques, facilement piratables |
| 3 | 2-5 | Systèmes modernes, sécurité variable |
| 4 | 4-8 | IA défensives, cryptage avancé |
| 5 | 6-10 | Systèmes quasi-impénétrables |

---

## 13. TABLE DE BLESSURES CRITIQUES

> **Source :** Basée sur la table de Genesys (FFG), rendue plus punitive. Le cumul Genesys est conservé : chaque blessure critique déjà subie ajoute +10 au prochain jet. La qualité d'arme **Vicious X** ajoute +X×10 au jet.

### Déclenchement

Un jet sur cette table se fait quand :
1. Un **Nat 1 (Réussite critique)** inflige des dégâts aux Blessures, OU
2. Les **PV tombent à 0** et des dégâts débordent vers les PV.

### Jet : d100 + 10 par crit déjà subi + Vicious bonus

| d100 | Sévérité | Nom | Effet |
|---|---|---|---|
| 01-05 | Mineure | **Éraflure** | 1 point de stress. Aucun effet durable. |
| 06-10 | Mineure | **Ralenti** | Le personnage agit en dernier à son prochain tour. |
| 11-15 | Mineure | **Lâcher prise** | Le personnage lâche ce qu'il tient (arme, objet). |
| 16-20 | Mineure | **Sonné** | Perd 1 action au prochain tour. |
| 21-25 | Mineure | **Déséquilibré** | Désavantage au prochain jet. |
| 26-30 | Mineure | **Impact moral** | Le personnage est Shaken (s'il ne l'est pas déjà). |
| 31-35 | Mineure | **Staggered** | Le personnage ne peut pas agir (seulement se déplacer) jusqu'à la fin de son prochain tour. |
| 36-40 | Mineure | **Douleur vive** | Difficulté +2 au prochain jet. |
| 41-45 | Modérée | **À terre** | Le personnage est mis à terre (prone) et subit 1 PV. |
| 46-50 | Modérée | **Commotion légère** | Désavantage à tous les jets WIT et EMP jusqu'à soins (Medicine difficulté 2). |
| 51-55 | Modérée | **Blessure démoralisante** | Désavantage à tous les jets EMP jusqu'à soins (Medicine difficulté 2). |
| 56-60 | Modérée | **Blessure agonisante** | Désavantage à tous les jets STR et DEX jusqu'à soins (Medicine difficulté 2). |
| 61-65 | Modérée | **Désorienté** | Le personnage est Désorienté (désavantage à tout) jusqu'à soins. |
| 66-70 | Modérée | **Hémorragie légère** | 1 Blessures perdu par round pendant 3 rounds. Un jet de Medicine (difficulté 2) stoppe l'hémorragie. |
| 71-75 | Modérée | **Entravé** | Vitesse réduite de moitié jusqu'à soins (Medicine difficulté 2). |
| 76-80 | Modérée | **Surpassé** | L'attaquant peut immédiatement effectuer une attaque gratuite supplémentaire. |
| 81-85 | Modérée | **Épuisé** | Le personnage ne peut plus dépenser de Healing Surges jusqu'à un repos court. |
| 86-90 | Modérée | **Compromis** | Difficulté +2 à tous les jets jusqu'à soins (Medicine difficulté 3). |
| 91-95 | Grave | **Au bord du gouffre** | Le personnage perd 2 Blessures au début de chacun de ses tours jusqu'à soins (Medicine difficulté 3). |
| 96-100 | Grave | **Membre estropié** | Un membre (au choix du MJ) est inutilisable jusqu'à soins. Difficulté +2 à tout jet nécessitant ce membre. Medicine difficulté 3 pour soigner. |
| 101-105 | Grave | **Mutilé** | Un membre est **définitivement perdu** (sauf prothèse/cybernétique). Le personnage ne peut plus effectuer d'actions nécessitant ce membre. |
| 106-110 | Grave | **Blessure horrifique** | Tirer 1d4 : 1 = STR, 2 = DEX, 3 = WIT, 4 = EMP. La stat est réduite de 1 (permanent) jusqu'à soins (Medicine difficulté 4). |
| 111-115 | Grave | **Immobilisé** | Le personnage ne peut plus se déplacer jusqu'à soins (Medicine difficulté 3). |
| 116-120 | Grave | **Aveuglé** | Le personnage ne peut plus voir. Double désavantage à tout, triple désavantage à Perception. Jusqu'à soins (Medicine difficulté 4). |
| 121-125 | Grave | **Paralysé** | Le personnage est Staggered (pas d'actions, seulement mouvement) jusqu'à soins (Medicine difficulté 4). |
| 126-130 | Dévastatrice | **Blessure atroce** | Tirer 1d4 : 1 = STR, 2 = DEX, 3 = WIT, 4 = EMP. La stat est **définitivement** réduite de 1 (minimum 6). Prothèse/cybernétique peut compenser. |
| 131-140 | Dévastatrice | **Hémorragie critique** | Le personnage perd 1 Blessures et subit difficulté +2 à tout au début de chaque tour. Pour chaque 5 Blessures perdus au-delà du seuil, il subit une blessure critique supplémentaire (relancer). Medicine difficulté 5 pour stopper. |
| 141-150 | Dévastatrice | **La fin approche** | Le personnage meurt à la fin du prochain round complet à moins que la blessure ne soit soignée. Medicine difficulté 5. |
| 151+ | Fatale | **Mort** | Le personnage est mort. Aucun soin ne peut le ramener. |

### Cumul et escalade

Le système Genesys de cumul est conservé et rendu explicite :

- **1ère blessure critique :** jet normal (d100)
- **2ème blessure critique :** d100 + 10
- **3ème blessure critique :** d100 + 20
- **Avec une arme Vicious 3 :** d100 + 30 en plus

Un personnage avec 3 blessures critiques non-soignées qui se prend un crit d'une arme Vicious 2 roule : d100 + 30 + 20 = d100 + 50. Même un résultat bas de 51 donne 101 → **Mutilé**. L'escalade est brutale et voulue.

### Soigner les blessures critiques

Les blessures critiques restent actives même si leur effet temporaire a expiré. Elles comptent pour le cumul (+10) tant qu'elles ne sont pas soignées par un jet de Medicine de la difficulté indiquée.

- **1 jet de Medicine par blessure critique par jour.**
- Sans kit médical : difficulté +2.
- Se soigner soi-même : difficulté +2.

---

## 14. FEUILLE DE ROUTE RÉVISÉE

### Phase 1 : Core Mechanics (playtest kit) ← ON EST ICI
1. ✅ **4 stats pures (STR/DEX/WIT/EMP)** — verrouillé v3
2. ✅ **D20 roll-under** (Score = stat + prof + loot, Seuil = Score - Difficulté) — verrouillé v4
3. ✅ 3 actions + réactions — verrouillé
4. ✅ Armure passive + **pas de défense passive** + **minimum 1 dégât** — verrouillé v4
5. ✅ Points de Vie / Blessures (pool unique de PV) — verrouillé v3
6. ✅ Shaken (sang-froid = STR Save) — verrouillé v3
7. ✅ Tech Levels (UM5) — verrouillé
8. ✅ 20 compétences (UM5 + 4 modernes) — verrouillé v3
9. ✅ Qualités d'items Genesys — verrouillé
10. ✅ **Vigueur** (indice de durabilité par classe) — verrouillé v3
11. ✅ **Healing Surges** (modèle restrictif) — verrouillé v4
12. ✅ **Roll-under + initiative cartes + gestion temps Dragonbane** — verrouillé v4
13. ✅ **Hacking / Firewall** — verrouillé v3
14. ✅ **Table de Blessures Critiques** — verrouillé v3
15. ✅ **15 niveaux, prof +1/+2/+3** — verrouillé v4
16. ✅ **Loot comme deuxième jambe de progression (+0 à +3)** — verrouillé v4
17. ✅ **Push de jet (Dragonbane-style)** — verrouillé v4
18. ✅ **4 conditions (Épuisé/Déstabilisé/Confus/Stressé)** — verrouillé v4
19. ✅ **Dégradation du loot (Neuf/Endommagé/Détruit)** — verrouillé v4
20. ✅ **5 classes core** (Grounder rédigé, 4 en esquisse) — verrouillé v4
21. ✏️ **PROCHAIN :** Rédiger Infiltrator, Medic, Marshal, Tech sur 15 niveaux

### Phase 2 : Classes (niveaux 1-15)
- Rédiger les 4 classes restantes (Infiltrator, Medic, Marshal, Tech)
- Chaque classe suit le template 15 niveaux avec mécanique de ressource unique
- Sous-classes à 2-3 options chacune

### Phase 3 : Équipement, Loot & Crafting
- Tables d'armes UM5 simplifiées (avec bonus +0 à +3 et états de dégradation)
- Tables de loot par biome (8 tables × 20 entrées)
- Système de crafting Genesys adapté (Engineering skill, Hard Points)

### Phase 4 : GM Toolkit
- Monster/NPC Builder (Nimble-style, avec pouvoirs qui imposent Désavantage)
- Règles véhicules simplifiées
- Règles hacking (optionnel, pour settings cyberpunk)
- Guide "Build Your Setting" avec TL comme curseur principal

### Phase 5 : Polissage
- Ancêtres/Origines (Humain, Augmenté, Synthétique, Alien...)
- Aventure d'introduction
- Guide de conversion 5e
- Playtest Kit final

---

## 15. PROCHAINE ÉTAPE

### Changements v4 — Résumé

- **Niveaux :** 20 → **15**. Trois arcs de 5 niveaux (Recrue/Vétéran/Élite).
- **Proficiency :** +2 à +6 → **+1 / +2 / +3** (paliers à 1-5 / 6-10 / 11-15).
- **Loot comme progression :** Le Score intègre maintenant **stat + prof + bonus loot (+0 à +3)**. Le loot est la deuxième jambe de progression, volatile et sujette à rotation.
- **Push de jet :** Mécanique Dragonbane — relancer un jet raté, coût = **condition OU dégradation d'équipement**.
- **4 conditions :** Épuisé (STR), Déstabilisé (DEX), Confus (WIT), Stressé (EMP). Chaque condition = Désavantage sur la stat liée.
- **Dégradation du loot :** 3 états (Neuf → Endommagé → Détruit). Endommagé = bonus /2. Détruit = inutilisable.
- **Stat increases :** 4+4 → **3 au choix** (niveaux 4, 8, 12).
- **Ennemis :** Les ennemis difficiles à toucher utilisent des **pouvoirs qui imposent Désavantage**, jamais de difficulté numérique en combat.
- **5 classes core :** 11 classes UM5 → **5** (Grounder, Infiltrator, Medic, Marshal, Tech). Marshal passe de Vig 10 à **Vig 8**.
- **Healing Surges :** Modèle D&D 5e → **modèle restrictif** (déclencheurs obligatoires, 1 surge max par Stretch Rest, max 2 Stretch entre Shifts).
- **Terminologie :** Les termes anglais Boon/Bane sont remplacés par **Avantage/Désavantage** dans tout le système.

### Changements v3 — Résumé (historique)

- **Stats :** 4+2 → 4 pures (STR/DEX/WIT/EMP). CON et WIL supprimés. Valeurs directes (7-11). Bonus = valeur - 8.
- **Résolution :** Roll-over → Roll-under. Score = stat + proficiency. Seuil = Score - Difficulté.
- **Pas de défense passive.** Difficulté = 0 en combat. Couverture = +2 Armure.
- **Minimum 1 dégât** par attaque réussie.
- **Critique :** Nat 1 = Réussite critique (crit), Nat 20 = Échec critique (fumble).
- **Vigueur :** Indice de durabilité par classe. Valeur fixe.
- **PV/Blessures :** Niveau 1 = Vigueur + STR. Blessures fixe.
- **Healing Surges :** Nombre = base classe + STR. Valeur = Vigueur + STR.
- **Saves :** 4 saves (STR/DEX/WIT/EMP). Roll-under.
- **Shaken :** Sang-froid = STR Save.
- **Skills :** 20 skills UM5 redistribuées sur 4 stats. 7 trained-only.

### Prochains livrables

1. **Rédiger les 4 classes restantes sur 15 niveaux** : Infiltrator, Medic, Marshal, Tech
2. **Mettre à jour le Playtest Kit** avec les nouvelles formules (15 niveaux, prof +1/+2/+3)
3. **Tables de loot avec bonus numériques** et états de dégradation intégrés
4. **Formules canoniques v2** fait foi pour tous les calculs (voir formules_canoniques_v2.md)
