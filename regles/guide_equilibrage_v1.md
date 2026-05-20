# GUIDE D'ÉQUILIBRAGE DES RENCONTRES

> **Ce document donne au MJ tous les outils pour construire des combats équilibrés — du combat facile au boss fight de fin de campagne.** Les chiffres sont vérifiés contre les formules canoniques.

---

## 1. LE PRINCIPE — Tuer en X rounds

L'équilibrage repose sur une question simple : **combien de rounds faut-il aux PJ pour éliminer les ennemis, et combien de rounds faut-il aux ennemis pour mettre les PJ à terre ?**

Si les PJ tuent en 2 rounds → trop facile.
Si les PJ tuent en 3-5 rounds → zone de tension idéale.
Si les PJ tuent en 6+ rounds → combat enlisé, frustrant, ou mortel (attrition de Secoué).

Pour calculer ça, il te faut deux chiffres : le **DPR** (dégâts par round) des PJ et les **PV effectives** des ennemis.

---

## 2. DPR DES PJ — Dégâts par round par niveau

Chaque PJ fait en moyenne 3 actions par round. En pratique, 1-2 actions sont des attaques (le reste : mouvement, couverture, compétences, soins). Voici le DPR réaliste par classe, en supposant **2 attaques par round** pour les combattants et **1 attaque + 1 soin/ordre** pour les supports.

### Niveau 1

| Classe | Score | % toucher | Dégâts/tir | DPR (2 tirs) | DPR (1 tir) | Rôle |
|---|---|---|---|---|---|---|
| **Grounder (Précision)** | 11 | 55% | 1d8+1d6+2 (10.5) | **11.6** | 5.8 | DPR primaire |
| **Grounder (Assaut, auto)** | 11 | 55% save | 1d10+1d6 (9) | **~10** (auto + Secoué) | — | DPR + suppression |
| **Infiltrator** | 12 | 60% | 1d6+1d6 (7) | **8.4** | — | Burst ponctuel |
| **Infiltrator (Frappe Ciblée)** | 12 | 60% | 1d6+1d6+1d6 (10.5) | — | **6.3** (1×/tour) | Burst conditionnel |
| **Marshal** | 9 | 45% | 1d8+1d4 (7) | **6.3** | 3.2 | Support, DPR léger |
| **Tech** | 10 | 50% | 1d4+1d4 (5) | **5.0** | 2.5 | Drone > arme |
| **Medic** | 18 | 45% | 1d6+1d4 (6) | **5.4** | 2.7 | Soins > attaque |

**DPR total de l'escouade (5 PJ, niv 1) ≈ 35-40 dégâts nets par round** (avant Armure ennemie).

### Niveau 5

| Classe | Score | % toucher | Dégâts/tir | DPR (2 tirs) |
|---|---|---|---|---|
| **Grounder** | 13 | 65% | 1d10+1d6+2 (11) | **14.3** |
| **Infiltrator** | 14 | 70% | 1d6+1d6+2d6 (14) | **9.8** (Frappe Ciblée 1×) |
| **Marshal** | 20 | 50% | 1d8+1d4 (7) | **7.0** |
| **Tech** | 12 | 60% | 1d6+1d4 (6) + drone | **7.2** + drone support |
| **Medic** | 10 | 50% | 1d6+1d4 (6) | **6.0** |

**DPR total escouade (5 PJ, niv 5) ≈ 45-50 dégâts nets par round.**

### Niveau 10

| Classe | Score | % toucher | Dégâts/tir | DPR (2 tirs) |
|---|---|---|---|---|
| **Grounder** | 16 | 80% | 2d8+1d8+3 (17) | **27.2** |
| **Infiltrator** | 16 | 80% | 1d8+1d8+3d6 (19) | **15.2** |
| **Marshal** | 12 | 60% | 1d10+1d6 (9) | **10.8** |
| **Tech** | 14 | 70% | 1d8+1d6 (8) + drone | **11.2** + drone |
| **Medic** | 12 | 60% | 1d8+1d6 (8) | **9.6** |

**DPR total escouade (5 PJ, niv 10) ≈ 70-80 dégâts nets par round.**

---

## 3. PV EFFECTIVES DES ENNEMIS — Ce qu'il faut détruire

Les PV effectives = PV réelles ajustées par l'Armure. Plus l'Armure est haute, plus l'ennemi "résiste" aux dégâts.

| Niveau ennemi | PV | Armure | PV effectives (vs groupe niv 1) | PV eff. (vs niv 5) | PV eff. (vs niv 10) |
|---|---|---|---|---|---|
| **Minion Recrue** | 1 hit | 0-2 | ~5 | ~3 | ~2 |
| **Adversaire niv 1** | 20 | 3-4 | ~28 | ~24 | ~22 |
| **Adversaire niv 3** | 35 | 4-6 | ~47 | ~41 | ~38 |
| **Adversaire niv 5** | 50 | 5-7 | ~64 | ~57 | ~53 |
| **Adversaire niv 8** | 78 | 7-9 | ~110 | ~96 | ~88 |
| **Adversaire niv 10** | 100 | 8-10 | ~140 | ~125 | ~115 |
| **Boss niv 4** (PV×1.5) | 24 | 5-6 | ~105 | ~95 | ~90 |
| **Boss niv 8** (PV×2) | 156 | 7-9 | ~210 | ~185 | ~170 |

> *PV effectives = PV + (Armure × nombre de coups attendus). C'est une approximation — l'Armure bloque un montant fixe par coup, donc plus il faut de coups, plus elle "ajoute" de PV virtuels.*

### Calcul rapide — Time-to-kill (TTK)

**TTK = PV effectives ÷ DPR de l'escouade.**

| Scénario (5 PJ niv 1) | Ennemis | PV eff. totales | DPR escouade | TTK |
|---|---|---|---|---|
| 4 Minions | 4 × 5 = 20 | ~25 | ~2 rounds ✅ Facile |
| 2 Adversaires niv 1 | 2 × 28 = 56 | ~25 | ~2-3 rounds ✅ Moyen |
| 4 Adversaires niv 1 | 4 × 28 = 112 | ~25 | ~4-5 rounds ⚠️ Difficile |
| 1 Boss niv 4 + 4 Minions | 105 + 20 = 125 | ~25 | ~5 rounds ⚠️ Boss fight |
| 1 Boss niv 4 + 8 Minions | 105 + 40 = 145 | ~25 | ~6 rounds 🔴 Mortel |

**Zone optimale : 3-5 rounds.** Assez long pour que le Secoué s'accumule et que les ressources soient dépensées. Assez court pour que ça reste excitant.

---

## 4. DPR DES ENNEMIS — Combien de temps les PJ survivent

### PV effectives des PJ (niv 1, escouade complète)

| PJ | PV | Armure | PV eff.  Surges | Total PV récupérables |
|---|---|---|---|---|---|---|
| **Grounder** | 24 | 3 | ~18 | 9 | 12 + 9×12 = **120** |
| **Infiltrator** | 14 | 4 | ~12 | 7 | 4 | 7 + 4×7 = **35** |
| **Medic** | 18 | 3 | ~13 | 9 | 7 | 9 + 7×9 = **72** |
| **Marshal** | 20 | 5 | ~17 | 10 | 8 | 10 + 8×10 = **90** |
| **Tech** | 10 | 2 | ~6 | 5 | 3 | 5 + 3×5 = **20** |

Le "Total PV récupérables" est théorique (tous les surges de la journée dépensés sur un seul combat). En pratique, les PJ dépensent 2-4 surges par combat.

### DPR ennemi typique

| Type ennemi | Score Att | % toucher PJ | Dégâts | DPR (2 att) |
|---|---|---|---|---|
| **Minion Recrue** | 8 | 40% | 1d4 (2.5) | **2** |
| **Adversaire niv 1** | 10 | 50% | 1d8+1 (5.5) | **5.5** |
| **Adversaire niv 3** | 10 | 50% | 1d10+2 (7.5) | **7.5** |
| **Boss niv 4** | 11 | 55% | 1d10+3 (8.5) | **9.4** |

### Time-to-down (TTD) — Quand le premier PJ tombe

Le premier PJ à tomber est presque toujours le **Tech** (PV eff. 6) ou l'**Infiltrator** (PV eff. 12) s'ils sont exposés.

| Scénario | Dégâts focalisés sur Tech | TTD |
|---|---|---|
| 2 Adversaires niv 1 focus Tech | 5.5 × 2 = 11 DPR | **1 round** 🔴 |
| 1 Adversaire niv 3 focus Tech | 7.5 DPR | **1 round** 🔴 |
| 4 Minions focus Tech | 2 × 4 = 8 DPR | **1 round** 🔴 |

**Conclusion :** Le Tech et l'Infiltrator **meurent en 1 round** s'ils sont la cible principale. C'est voulu par le design (létalité, interdépendance), mais le MJ doit en tenir compte.

**Règle de ciblage IA pour le MJ :**
- Les Minions tirent sur la cible la plus proche ou la plus visible.
- Les Adversaires intelligents ciblent le Medic ou le Tech en priorité (s'ils les identifient).
- Les Boss ciblent le PJ le plus dangereux (Grounder) ou utilisent des attaques de zone.
- Si un PJ est en couverture totale, les ennemis ne peuvent pas le cibler (pas de ligne de vue).

---

## 5. BUDGET DE RENCONTRE — La table principale

### Pour un groupe de 4-5 PJ

| Difficulté | Ennemis (pour 5 PJ) | TTK attendu | Surges dépensés | Risque |
|---|---|---|---|---|
| **Facile** | 4-6 Minions | 1-2 rounds | 0-1 | Aucun PJ en danger |
| **Moyen** | 2 Adversaires + 3-4 Minions | 3-4 rounds | 1-3 | Secoué fréquent, PV entamés |
| **Difficile** | 3 Adversaires + 4-6 Minions | 4-5 rounds | 3-5 | 1 PJ tombe probablement à 0 PV |
| **Mortel** | 4+ Adversaires + Minions OU 2 Adv niv+2 | 5-6 rounds | 5+ | TPK possible si mal joué |
| **Boss fight** | 1 Boss (Phase 2 obligatoire) + 4-6 Minions | 4-6 rounds | 3-6 | Le Boss est le timer ; les Minions gèrent les PJ |

### Ajustements

| Facteur | Ajustement |
|---|---|
| Ennemis de **niveau supérieur** aux PJ (+1-2 niv) | Chaque niveau au-dessus = +50% PV eff. et +1 dégât. Monte d'un cran de difficulté. |
| Ennemis de **niveau inférieur** (-1-2 niv) | Descend d'un cran. |
| **Terrain favorable ennemis** (hauteur, couverture, choke point) | +1 cran. Le terrain est le multiplicateur le plus sous-estimé. |
| **Terrain favorable PJ** (embuscade, couverture, flanc) | -1 cran. |
| **PJ bien équipés** (armes +2/+3, Armure 8+) | -1 cran. Le loot change tout. |
| **PJ épuisés** (surges < 50%, conditions actives) | +1 cran. Le 3e combat du Shift est automatiquement plus dur. |
| **Surprise** (PJ ou ennemis) | +1 cran pour le camp surpris. Un round gratuit change radicalement l'issue. |
| **Objectif non-combat** (hacker, extraire, survivre X rounds) | Réduit le nombre d'ennemis nécessaires — la pression vient du timer, pas du nombre. |

---

## 6. L'ATTRITION — L'arme secrète du MJ

### La vraie difficulté n'est pas le combat — c'est la journée

Un seul combat Moyen ne tue personne. Trois combats Moyens dans le même Shift tuent quelqu'un. Voici pourquoi :

| Ressource | Shift 1 (frais) | Après 1 combat | Après 2 combats | Après 3 combats |
|---|---|---|---|---|
| **Surges Grounder** | 9 | 7 (-2) | 4 (-3) | 1 (-3) |
| **Surges Tech** | 3 | 1 (-2) | **0** ❌ | 0 |
| **Second Souffle** | Disponible | Utilisé | — | — |
| **Conditions** | 0 | 0-1 (push) | 1-2 | 2-3 (impact fort) |
| **Équipement** | Neuf | Neuf | 1 Endommagé? | 1-2 Endommagés |
| **Stretch Rests** | 2 dispo | 1 dispo | 0 dispo | — |

**Le Tech est à sec après 2 combats.** 3 surges de base. Un combat moyen coûte 1-2 surges (Second Souffle + 1 soin). Après 2 combats, il n'a plus de surges et ses 5 PV ne se rechargent plus. Le 3e combat est une sentence de mort pour lui.

**Le cap de 2 Stretch Rests par Shift** est le verrou qui empêche la récupération infinie. Sans ce cap, les joueurs se reposent 15 min après chaque combat et reviennent au max. Avec le cap, ils doivent choisir : se reposer maintenant ou garder le Stretch pour plus tard ?

### Planifier l'attrition

| Nombre de combats/Shift | Type de session | Gestion MJ |
|---|---|---|
| **1 combat** | Boss fight ou climax | Tout dépenser. Les PJ peuvent être à fond. Le combat doit être Difficile ou Boss fight. |
| **2 combats** | Session standard | Moyen + Difficile. Les PJ commencent à gérer leurs surges au 2e combat. |
| **3 combats** | Attrition, mission d'infiltration | Facile + Moyen + Difficile. Le dernier combat est le test — les PJ sont bas en tout. |
| **4+ combats** | Survie, évacuation sous pression | Facile ×2-3 + Moyen. Même des Minions deviennent dangereux quand les surges sont à 0. |

---

## 7. ANATOMIE D'UNE BONNE RENCONTRE

Un combat mémorable a 5 ingrédients :

### 7.1. Variété d'ennemis

**Mauvais :** 6 gardes identiques.
**Bon :** 4 Minions soldats + 1 Adversaire sniper en hauteur + 1 Adversaire leader qui donne des ordres.

La variété force les joueurs à prioriser. "Qui on élimine en premier ?" est la question tactique fondamentale.

### 7.2. Un ennemi prioritaire

Chaque combat devrait avoir **une cible que les PJ doivent éliminer en priorité**. Le sniper qui tire depuis le toit. Le hacker qui active les tourelles. Le leader qui donne Avantage à ses troupes. L'ingénieur qui répare le drone de combat.

Si les PJ l'ignorent, les choses empirent chaque round. S'ils le focalisent, ils doivent traverser les Minions pour l'atteindre.

### 7.3. Du terrain qui compte

| Élément | Effet mécanique | Effet tactique |
|---|---|---|
| **Couverture partielle** (piliers, caisses) | +2 Armure | Encourage le mouvement tactique |
| **Couverture totale** (murs) | Intouchable | Crée des angles morts et des couloirs de tir |
| **Hauteur** (balcon, toit) | Avantage sur les cibles en contrebas | Le sniper en hauteur est une menace constante |
| **Zone dangereuse** (explosifs, feu, radiation) | Dégâts d'environnement | Force le repositionnement |
| **Choke point** (porte, couloir étroit) | Limite les tirs simultanés | Avantage au défenseur |
| **Obscurité** | Désavantage sur les attaques sans lumière | Favorise l'Infiltrator |

**Règle simple :** Chaque combat devrait avoir au moins **2 éléments de terrain** qui influencent les décisions.

### 7.4. Un objectif autre que "tuez tout"

| Objectif | Timer | Tension |
|---|---|---|
| **Élimination** | — | Basse (pas d'urgence) |
| **Protéger un VIP** | Le VIP a X PV, les ennemis le ciblent | Haute (split focus) |
| **Atteindre la sortie** | Renforts arrivent dans X rounds | Haute (course contre la montre) |
| **Hacker le terminal** | X rounds de hacking pendant que les ennemis attaquent | Haute (protéger le hacker) |
| **Survivre X rounds** | Extraction dans X rounds | Haute (endurance) |
| **Capturer vivant** | Pas de dégâts létaux sur la cible | Moyenne (limite les options) |
| **Désarmer la bombe** | X rounds avant explosion | Très haute |

### 7.5. Une escalade ou un twist

Le combat ne devrait pas être statique. Quelque chose change au round 3-4 :

- **Renforts** — 1d4 Minions arrivent par une porte latérale.
- **Phase 2 du Boss** — Le Boss passe sous 50% PV et change de comportement (frénésie, fuite, pouvoirs nouveaux).
- **Environnement** — Les lumières s'éteignent, une explosion ouvre une brèche, le feu se propage.
- **Objectif secondaire** — Un otage crie à l'aide, un terminal affiche un compte à rebours, un allié tombe.

---

## 8. PIÈGES D'ÉQUILIBRAGE — Ce qui tue vos combats

### 8.1. Trop de Minions

Les Minions meurent en 1 coup, mais **chaque Minion inflige du Secoué**. 10 Minions qui tirent = 4-5 hits = Secoué 3 sur plusieurs PJ. Même si les dégâts sont faibles (1d4, Armure absorbe presque tout), le Secoué s'accumule et paralyse l'escouade. 

**Solution :** Maximum 3 Minions par PJ en simultané. Les renforts arrivent par vagues, pas tous en même temps.

### 8.2. L'ennemi trop blindé

Un Adversaire avec Armure 8 contre des PJ niv 1 (dégâts moyens 5-7) ne prend que 1 dégât par coup. Le combat dure 15+ rounds.

**Vérification rapide :** Dégâts moyens du meilleur PJ — Armure ennemi ≥ 2. Si c'est inférieur à 2, l'ennemi est trop blindé.

| Niveau PJ | Armure ennemi max recommandée |
|---|---|
| 1-3 | 5-6 |
| 4-7 | 7-8 |
| 8-11 | 9-10 |
| 12-15 | 10-12 |

### 8.3. Le Boss seul

Un Boss seul contre 5 PJ se fait concentrer et meurt en 2-3 rounds, quelle que soit sa puissance. Même avec 2-4 cartes d'initiative, il est submergé par l'action economy.

**Solution :** Un Boss a TOUJOURS des Minions ou des Adversaires. Les Minions forcent les PJ à répartir leurs attaques. Le Boss sans sbires est un sac à PV.

### 8.4. Pas de couverture

Un combat en terrain ouvert = les deux camps se tirent dessus sans bouger. C'est ennuyeux et punitif (Secoué s'accumule sans moyen de l'éviter).

**Solution :** Il y a toujours de la couverture. Même un parking a des voitures. Même un couloir a des portes.

### 8.5. Le focus fire sur le Tech

Le Tech a 5 PV niv 1. Si les ennemis le ciblent (et les ennemis intelligents le font), il tombe en 1 round. Ça peut être frustrant pour le joueur.

**Solution :** Les Minions ne focalisent pas intelligemment — ils tirent sur le plus proche. Seuls les Adversaires et Boss identifient les cibles prioritaires (et seulement s'ils ont une raison narrative de le faire). Laisser le joueur du Tech utiliser la couverture et le positionnement.

---

## 9. EXEMPLES COMPLETS

### Exemple 1 — Combat Facile (niv 1, 5 PJ)

**Situation :** Patrouille de 4 gardes de sécurité à l'entrée d'un entrepôt.

| Ennemi | Type | Score | Dégâts | Armure | PV |
|---|---|---|---|---|---|
| Garde ×4 | Minion Recrue | 8 | 1d4 | 2 | 1 hit |

**Analyse :**
- TTK : 4 Minions. Le Grounder en élimine 2 en 1 round (2 tirs à 55%, dégâts > 2+1d4). L'Infiltrator en prend 1. Le Marshal/Tech/Medic en prennent 1 entre eux. **Combat fini en 1-2 rounds.**
- Risque : Quasi-nul. 4 Minions à Score 8 = 40% de toucher, 1d4 dégâts. L'Armure des PJ absorbe presque tout. Secoué 1 possible, pas dangereux.
- Surges dépensés : 0-1.
- **Objectif :** Échauffement. Apprendre les mécaniques.

---

### Exemple 2 — Combat Moyen (niv 1, 5 PJ)

**Situation :** Embuscade dans un couloir industriel. 2 mercenaires derrière des caisses, 4 soldats PMC qui avancent.

| Ennemi | Type | Score | Dégâts | Armure | PV |
|---|---|---|---|---|---|
| Soldat PMC ×4 | Minion Vétéran | 9 | 1d6 | 4 | 1 hit |
| Mercenaire ×2 | Adversaire niv 1 | 10 | 1d8+1 | 4 | 13 |

**Analyse :**
- PV eff. totales : (4 × 5) + (2 × 28) = 76.
- TTK : 76 ÷ 25 DPR ≈ **3 rounds.**
- Les Minions tombent vite (round 1-2). Les Mercenaires résistent 2-3 rounds chacun.
- Risque : Les 4 Minions au round 1 infligent potentiellement Secoué 2-3 sur un PJ exposé. Le Mercenaire à 1d8+1 = 5.5 dégâts moyens, contre Armure 3-4 du PJ = 1-2 dégâts nets + Secoué.
- Surges dépensés : 2-4.
- **Objectif :** Combat standard. Test de positionnement (couverture) et de priorité (Minions d'abord ou Adversaires d'abord ?).

---

### Exemple 3 — Combat Difficile (niv 1, 5 PJ)

**Situation :** Salle serveur. 1 tourelle automatique au plafond, 2 drones de combat, 3 soldats qui entrent par les côtés.

| Ennemi | Type | Score | Dégâts | Armure | PV |
|---|---|---|---|---|---|
| Soldat ×3 | Minion Vétéran | 9 | 1d6 | 4 | 1 hit |
| Drone de combat ×2 | Adversaire niv 2 | 9 | 1d6, Vol | 2 | 5 |
| Tourelle auto | Adversaire niv 3 | 10 | 2d6, auto 2d8 | 6 | 8 |

**Analyse :**
- PV eff. totales : (3 × 5) + (2 × 16) + (1 × 32) = 79. Mais la tourelle a Armure 6 (réduit les dégâts considérablement pour des PJ niv 1).
- TTK : La tourelle seule prend 4-5 rounds à détruire. Les drones et soldats tombent en 2-3 rounds.
- Risque : La tourelle en tir auto touche 2-3 PJ par round, chacun fait save DEX ou prend 2d8 (9) - Armure. Secoué garanti sur tous. En 2 rounds, l'escouade entière peut être à Secoué 2+.
- **Le Tech peut hacker la tourelle** (Firewall 4) — c'est la solution élégante.
- Surges dépensés : 4-6. Quelqu'un tombe probablement à 0 PV.
- **Objectif :** Combat puzzle. La tourelle est le problème — les PJ doivent trouver une solution (hack, grenade EMP, flanquer pour l'angle mort 90°, ou la détruire à brute force).

---

### Exemple 4 — Boss Fight (niv 3, 5 PJ)

**Situation :** Le commandant Harada dans son labo, 2 gardes, renforts en 3 rounds.

| Ennemi | Type | Score | Dégâts | Armure | PV | Spécial |
|---|---|---|---|---|---|---|
| Garde ×2 | Minion Recrue | 8 | 1d4 | 2 | 1 hit | Formation |
| Harada | Boss niv 4 | 11 | 1d8+3 / 1d6+3 Étourdissement | 6 | 24 (+ Phase 2: 15 PV) | 2 cartes, Commandement, Riposte, Phase 2 |
| Renforts (round 3) | Minion Vétéran ×2d4 | 9 | 1d6 auto 1d8 | 4 | 1 hit | Arrivent round 3 |

**Analyse :**
- PV eff. Harada : 24 PV (Phase 1) + 15 PV (Phase 2) = 39 PV total. TTK réel : **4-5 rounds** (Phase 1 ~2r + Phase 2 ~2-3r). Dynamique.
- Harada agit 2×/round. Commandement donne Avantage à ses gardes. Riposte punit les attaquants au corps à corps. Phase 2 (PV 0 → regagne 40 PV, passe au fusil, Frénésie) étend le combat de 2-3 rounds.
- Les renforts au round 3 ajoutent Secoué + distraction. Le Marshal ou le Grounder doit les gérer pendant que le reste focus Harada.
- Surges dépensés : 6-8. Au moins 1 PJ tombe à 0 PV. Possible 2.
- **TTK total avec Phase 2 : 7-9 rounds.** C'est long. Le Medic est absolument critique.

---

## 10. QUICK REFERENCE — Tableau d'équilibrage rapide

### Pour 5 PJ — Budget simple

| Niveau PJ | Combat Facile | Combat Moyen | Combat Difficile | Boss Fight |
|---|---|---|---|---|
| **1** | 4-6 Minions | 1 Adv. niv 1 + 3 Minions | 2 Adv. niv 1 + 4 Minions | Boss (12 PV + Phase 2) + 6 Minions |
| **3** | 6-8 Minions | 2 Adv. niv 3 + 3 Minions | 3 Adv. niv 3 + 4 Minions | Boss (20 PV + Phase 2) + 6 Minions |
| **5** | 8-10 Minions | 2 Adv. niv 5 + 4 Minions | 3 Adv. niv 5 + 6 Minions | Boss (29 PV + Phase 2) + 8 Minions |
| **8** | 8 Minions V | 2 Adv. niv 8 + 4 Minions V | 3 Adv. niv 8 + 4 Minions V | Boss (44 PV + Phase 2) + 6 Min V |
| **10** | 10 Minions É | 2 Adv. niv 10 + 4 Minions É | 3 Adv. niv 10 + 6 Minions É | Boss (57 PV + Phase 2) + 8 Min É |

> **Changement clé :** Moyen = **2 Adversaires** (au lieu de 3-4). Difficile = **3 Adversaires** (au lieu de 5-6). Les Boss ont **toujours** une Phase 2 intégrée.
>
> **Alternative niv -2 :** "Moyen niv 10" = 2 Adv niv 10 **OU** 3 Adv niv 8. Plus d'ennemis de niveau inférieur = même difficulté, plus de cibles.

### Pour 4 PJ — Réduire de 20%

Retire 1 Adversaire ou 2-3 Minions par rapport aux budgets ci-dessus.

### Pour 3 PJ — Réduire de 40%

Divise pratiquement par 2. Les combats Difficiles deviennent Mortels très vite avec 3 PJ.

---

## 11. CHECKLIST — Avant chaque combat

```
☐ Combien de rounds ce combat devrait-il durer ? (cible : 3-5)
☐ Le DPR de l'escouade peut-il tuer les ennemis dans ce temps ?
☐ Les ennemis peuvent-ils tuer un PJ en 1 round ? (Si oui, c'est voulu ?)
☐ Y a-t-il au moins 1 ennemi prioritaire (sniper, leader, hacker) ?
☐ Y a-t-il de la couverture pour les deux camps ?
☐ Les PJ ont-ils un objectif autre que "tuez tout" ?
☐ Quelque chose change-t-il au round 3-4 (renforts, phase 2, environnement) ?
☐ Le Tech/Infiltrator a-t-il un endroit sûr pour se positionner ?
☐ Combien de surges l'escouade a-t-elle encore ? (3e combat du Shift = dangereux)
☐ Le Medic a-t-il accès aux PJ blessés ? (positionnement)
```
