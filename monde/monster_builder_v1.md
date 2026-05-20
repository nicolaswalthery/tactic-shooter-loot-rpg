# MONSTER BUILDER v1 — Construire des ennemis en 30 secondes

> **Philosophie :** Comme Nimble et Dragonbane — des stat blocks minimalistes, lisibles en un coup d'œil, avec des pouvoirs qui rendent chaque ennemi unique. Le MJ ne devrait jamais avoir besoin de plus de **5 secondes** pour comprendre un PNJ. Un stat block tient sur une carte index.
>
> **Référence :** Design document v4, formules canoniques v2, conditions v1, blessures critiques v1.

---

## 1. LES TROIS CATÉGORIES

Chaque ennemi appartient à **une** catégorie. C'est la première décision — elle détermine tout le reste.

### MINION — Chair à canon

> *Gardes de sécurité, soldats basiques, drones autonomes, zombies, pirates bas-niveau.*

| Règle | Détail |
|---|---|
| **PV/Blessures** | Aucun. **1 touche = éliminé.** Toute attaque réussie tue un Minion, peu importe les dégâts. |
| **Initiative** | **1 carte par groupe** (tous les Minions du groupe agissent au même moment). |
| **Réaction** | Jamais. Un Minion ne pare pas, n'esquive pas. |
| **Attaque** | Score d'attaque unique. 1 dé de dégât. Rate automatiquement sur un Échec critique (Nat 20). |
| **Saves** | Tous à 8 (sauf indication contraire). Pas de proficiency. |
| **Danger** | **Le nombre.** Seuls, ils sont négligeables. En groupe, ils submergent. |

**Attaque Groupée :** Quand 3+ Minions attaquent la même cible au même tour, ils combinent leurs dés en **une seule attaque**. 3 gardes avec des pistolets (1d6 chacun) = 1 attaque à 3d6. Le Score d'attaque reste celui d'un seul Minion.

**Seuil de groupe :** Un MJ ne devrait jamais tracker plus de **2-3 groupes de Minions** dans une même rencontre. Chaque groupe = 3-6 individus.

---

### ADVERSAIRE — L'ennemi standard

> *Mercenaire vétéran, officier de sécurité, sniper, hacker ennemi, créature dangereuse.*

| Règle | Détail |
|---|---|
| **PV/Blessures** | Normaux. On les tracke individuellement. |
| **Initiative** | **1 carte chacun.** Agissent normalement (3 actions). |
| **Réaction** | **Non**, sauf si un pouvoir spécial le précise. |
| **Attaque** | 1-2 profils d'attaque. Score et dégâts normaux. |
| **Saves** | Profil normal (1-2 saves avantagés selon le concept). |
| **Danger** | Stats, Armure, armes, positionnement. Comparable à un PJ. |

**Un Adversaire = un PJ en termes de complexité.** Il a des PV à tracker, un Score d'attaque, une Armure, et potentiellement 1-2 pouvoirs. C'est le pain quotidien des rencontres.

---

### BOSS (Nemesis) — Le combat mémorable

> *Officier d'élite, cyborg de guerre, IA de combat, commandant ennemi, créature alpha.*

| Règle | Détail |
|---|---|
| **PV/Blessures** | Élevés. Souvent **2-3×** ceux d'un Adversaire du même niveau. |
| **Initiative** | **2+ cartes.** Agit 2 fois (ou plus) par round, à des moments différents. |
| **Réaction** | **Oui.** Parade, esquive, riposte — comme un PJ. |
| **Attaque** | 2-3 profils d'attaque. Score élevé. Attaques spéciales. |
| **Saves** | 2+ saves avantagés. Souvent immunisé à certaines conditions. |
| **Danger** | Multi-tours, capacités spéciales, Armure élevée, Phase 2. |

**Cartes multiples :**
| Type de Boss | Cartes d'initiative |
|---|---|
| Boss standard | 2 cartes |
| Boss majeur | 3 cartes |
| Boss extrême (finale de campagne) | 4 cartes |

**Réactions de Boss :** Un Boss a **1 réaction par tour d'un PJ** (pas par round). Ça signifie qu'un Boss face à 4 PJ peut potentiellement réagir 4 fois par round. C'est ce qui le rend dangereux face à un groupe.

---

## 2. TABLE DE CONSTRUCTION RAPIDE

### Comment lire cette table

1. Choisis un **niveau** pour ton PNJ (= le niveau de PJ qu'il est censé affronter).
2. Lis la ligne correspondante pour les PV, Blessures, dégâts, Score d'attaque et Armure.
3. Ajoute 1-2 **pouvoirs** de la liste (section 4).
4. Choisis un **template** (section 3) pour gagner du temps.

### Table — Adversaire standard

| Niv | PV | Blessures | Score Att. | Dégâts/action | Armure | Save moyen |
|---|---|---|---|---|---|---|
| ¼ | 6 | 9 | 1d6 (3) | 0-2 | 8 |
| ½ | 9 | 9 | 1d6+1 (4) | 2-3 | 8 |
| 1 | 13 | 10 | 1d8+1 (5) | 3-4 | 9 |
| 2 | 15 | 10 | 1d8+2 (6) | 4-5 | 9 |
| 3 | 19 | 10 | 1d10+2 (7) | 4-5 | 10 |
| 4 | 22 | 11 | 1d10+3 (8) | 5-6 | 10 |
| 5 | 26 | 11 | 2d6+2 (9) | 5-7 | 11 |
| 6 | 29 | 12 | 2d6+3 (10) | 6-7 | 11 |
| 7 | 34 | 12 | 2d8+2 (11) | 6-8 | 12 |
| 8 | 37 | 13 | 2d8+3 (12) | 7-8 | 12 |
| 9 | 43 | 13 | 2d10+2 (13) | 7-9 | 13 |
| 10 | 47 | 14 | 2d10+3 (14) | 8-9 | 13 |
| 11 | 52 | 14 | 3d6+3 (13) | 8-10 | 14 |
| 12 | 59 | 15 | 3d6+4 (14) | 9-10 | 14 |
| 13 | 66 | 15 | 3d8+3 (16) | 9-11 | 15 |
| 14 | 73 | 16 | 3d8+4 (17) | 10-11 | 15 |
| 15 | 80 | 16 | 3d10+4 (20) | 10-12 | 16 |

### Ajustements par catégorie

| Catégorie | PV | Blessures | Score Att. | Armure | Pouvoirs |
|---|---|---|---|---|---|
| **Minion** | 0 | 0 | Table -1 | Table -2 | 0-1 |
| **Adversaire** | Table | Table | Table | Table | 1-2 |
| **Boss** | Table × 1.5 | — | Table +1 | Table +1 | 3-5 |

> **Exemple :** Boss niv 5. PV = 19 × 1.5 = **29**. Blessures = 7 × 1.5 = **11**. Score Att. = 11 + 1 = **12**. Armure = 5-7 + 1 = **6-8**. **Phase 2 recommandée** (+15-20 PV). 3-5 pouvoirs. 2 cartes d'initiative.

### Minions — Chiffres simplifiés

| Niv Minion | Score Att. | Dégâts | Armure |
|---|---|---|---|
| Recrue (niv 1-3) | 8 | 1d4 | 0-2 |
| Vétéran (niv 4-7) | 9 | 1d6 | 2-4 |
| Élite (niv 8-11) | 10 | 1d8 | 4-6 |
| Extrême (niv 12-15) | 11 | 1d10 | 6-8 |

---

## 3. TEMPLATES — Construire un ennemi en 30 secondes

Un template est un profil-type prêt à l'emploi. Choisis un template, ajoute le niveau, c'est jouable.

### Template : Soldat

> *Garde de sécurité, milicien, PMC, troupe régulière.*

- **Stats clés :** STR 9, DEX 9
- **Armure :** Gilet balistique (Armure = table)
- **Armes :** Fusil d'assaut (dégâts table, range 12, auto dé+1) + couteau (1d4+STR, reach 1)
- **Saves avantagés :** STR
- **Pouvoirs suggérés :** Tactique de Meute, Couverture de Feu, Retraite Tactique
- **Comme Minion :** Score 8-10, dégâts 1d6, pas d'auto

### Template : Tireur d'élite

> *Sniper, marksman, chasseur de primes.*

- **Stats clés :** DEX 10-11, WIT 9
- **Armure :** Légère (Armure table -2, min 2)
- **Armes :** Fusil de précision (dégâts table +2, range 20, Précis) + pistolet (1d6, range 8)
- **Saves avantagés :** DEX
- **Pouvoirs suggérés :** Tireur Embusqué, Première Balle, Repositionnement

### Template : Brute / Tank

> *Mercenaire lourd, mutant, exo-soldat, mech-pilote.*

- **Stats clés :** STR 11-12, DEX 7
- **Armure :** Lourde (Armure table +2)
- **Armes :** Arme lourde OU mêlée lourde (dégâts table +3) + poing (1d6+STR)
- **Saves avantagés :** STR
- **Pouvoirs suggérés :** Frénésie, Charge, Résistance, Intimidation

### Template : Opérateur furtif

> *Assassin, infiltrateur ennemi, éclaireur.*

- **Stats clés :** DEX 10-11, WIT 9
- **Armure :** Légère (Armure table -2, min 2)
- **Armes :** Pistolet silencieux (dégâts table, range 8, Silencieux) + lame (1d6+DEX, Vicieux)
- **Saves avantagés :** DEX, WIT
- **Pouvoirs suggérés :** Embuscade, Disparition, Frappe Ciblée

### Template : Hacker / Tech

> *Technicien ennemi, opérateur de drones, spécialiste guerre électronique.*

- **Stats clés :** WIT 10-11, DEX 8
- **Armure :** Légère (Armure table -2, min 1)
- **Armes :** Pistolet (1d6, range 8) + drone armé (1d6, range 10, Score = WIT du hacker)
- **Saves avantagés :** WIT
- **Pouvoirs suggérés :** Soutien Drone, Hack Ennemi, Brouilleur, Surcharge

### Template : Leader / Officier

> *Commandant, sergent, chef de gang, officier corpo.*

- **Stats clés :** EMP 10-11, STR ou DEX 9
- **Armure :** Moyenne (Armure table)
- **Armes :** Pistolet lourd (dégâts table, range 10) OU fusil (dégâts table, range 12)
- **Saves avantagés :** EMP, STR
- **Pouvoirs suggérés :** Commandement, Appel de Renforts, Galvanisation, Présence

### Template : Créature / Monstre

> *Animal mutant, xéno, drone de combat, robot, entité alien.*

- **Stats clés :** STR 10-13, DEX 8-10 (variable)
- **Armure :** Naturelle (peau épaisse, carapace, blindage)
- **Armes :** Griffes/Morsure/Tentacules (dégâts table, reach 1-2) + attaque spéciale
- **Saves avantagés :** STR (souvent immunisé à Secoué)
- **Pouvoirs suggérés :** Frénésie, Charge, Terreur, Poison, Régénération

### Template : Véhicule / Tourelle

> *Tourelle automatisée, drone lourd, véhicule armé, mech.*

- **Stats clés :** — (pas de stats classiques)
- **Armure :** Blindage (Armure table +4)
- **Armes :** Arme montée (dégâts table × 1.5, range 15+)
- **Saves :** Immunisé aux conditions mentales (Secoué, Stressé, Confus). Vulnérable EMP.
- **Pouvoirs suggérés :** Blindage, Suppression, EMP Vulnérable, Tourelle Automatique

---

## 4. POUVOIRS — Le catalogue

Les pouvoirs sont ce qui rend chaque ennemi unique. Sans pouvoirs, un Adversaire niv 3 est un sac de PV avec un fusil. Avec 2 pouvoirs bien choisis, c'est une menace mémorable.

**Règle :** 1-2 pouvoirs par Adversaire. 3-5 par Boss. 0-1 par Minion (surtout des passifs).

### Pouvoirs offensifs

| Pouvoir | Effet | Catégorie |
|---|---|---|
| **Tactique de Meute** | Avantage à l'attaque si un allié est adjacent à la cible. | Minion, Adversaire |
| **Charge** | Si se déplace de 4+ cases en ligne droite avant d'attaquer : +1d6 dégâts. | Adversaire, Boss |
| **Frénésie** | Quand PV < 50% : +2 dégâts sur toutes les attaques. | Adversaire, Boss |
| **Frappe Ciblée** | +1d6 dégâts quand attaque avec Avantage ou depuis couvert. | Adversaire |
| **Première Balle** | Au premier round, si agit avant la cible : Avantage + dégâts doublés. | Adversaire |
| **Tir Perforant** | Les attaques à distance ignorent 2 points d'Armure. | Adversaire, Boss |
| **Multiattaque** | Peut faire 2 attaques différentes avec 2 actions (au lieu de la même). | Boss |
| **Attaque de Zone** | L'attaque touche toutes les cibles dans une Zone 2 (save DEX pour demi-dégâts). | Boss |
| **Exécution** | +2d6 dégâts contre les cibles Chancelant ou à 0 PV. | Boss |
| **Déchiquetage** | Sur un Réussite critique (Nat 1) : dégâts normaux + 1 Blessure + entrée sur table de blessures critiques. | Boss |

### Pouvoirs défensifs

| Pouvoir | Effet | Catégorie |
|---|---|---|
| **Blindage** | Ignore les X premiers dégâts par tour (X = Armure ÷ 2). | Adversaire, Boss |
| **Résistance (type)** | Demi-dégâts d'un type spécifique (Balistique, Feu, Lightning, etc.). | Adversaire, Boss |
| **Immunité (type)** | Ignore un type de dégâts ou de condition. | Boss |
| **Bouclier Énergétique** | +3 Armure. Se brise après avoir absorbé 15 dégâts. Se régénère après 1 round sans dégâts. | Boss |
| **Esquive Réflexe** | 1×/round, réaction : annule une attaque qui le touche (le PJ gâche son action). | Boss |
| **Régénération** | Récupère X PV au début de chaque tour (X = niveau). S'arrête si dégâts Fire ou Acid. | Boss |
| **Parade** | Réaction mêlée : jet d'arme de mêlée pour annuler une attaque. | Adversaire, Boss |
| **Couverture Mobile** | +2 Armure quand se déplace (bouclier balistique, hologramme). | Adversaire |

### Pouvoirs de contrôle

| Pouvoir | Effet | Catégorie |
|---|---|---|
| **Couverture de Feu** | 1 action : toutes les cibles dans un cône de 3 cases font un jet de Secoué (diff 3). Même sans toucher. | Adversaire, Boss |
| **Suppression** | Quand touche une cible : la cible a Désavantage à sa prochaine action. | Adversaire, Boss |
| **Grappin / Immobilisation** | Sur une touche mêlée : la cible est Immobilisée (save STR pour se libérer, 1 action). | Adversaire, Boss |
| **Terreur** | 1 action : toutes les cibles à 6 cases font un save EMP . Échec = Stressé. | Boss |
| **Hack Ennemi** | 1 action : jet WIT vs Firewall d'un implant ou d'un équipement électronique d'un PJ. Succès = l'objet dysfonctionne 1 round. | Adversaire, Boss |
| **Brouilleur** | Passif : pas de communication sans fil à 6 cases. Les drones dans la zone perdent le contact. | Adversaire |
| **EMP Burst** | 1×/combat : désactive toute l'électronique dans une Zone 3 pendant 2 rounds. Save WIT pour les implants. | Boss |
| **Cri de Guerre** | 1 action : tous les alliés à 6 cases gagnent Avantage pendant 1 round. | Adversaire (Leader), Boss |

### Pouvoirs tactiques

| Pouvoir | Effet | Catégorie |
|---|---|---|
| **Formation** | Armure +1 par allié adjacent (max +3). | Minion, Adversaire |
| **Retraite Tactique** | Fuit quand PV < 25%. Peut revenir avec des renforts après 1d4 rounds. | Adversaire |
| **Repositionnement** | Après avoir attaqué, se déplace de 3 cases gratuitement (pas d'attaque d'opportunité). | Adversaire |
| **Commandement** | 1 action : un allié à 6 cases gagne Avantage ou peut se déplacer gratuitement. | Adversaire (Leader), Boss |
| **Appel de Renforts** | 2 actions : 1d4 Minions arrivent en 1d4 rounds. 1×/combat. | Boss |
| **Galvanisation** | 1 action : un allié à 6 cases récupère 2d6 PV. | Adversaire (Leader), Boss |
| **Soutien Drone** | Contrôle 1-3 drones Minions. Les drones agissent sur le tour du contrôleur. | Adversaire, Boss |
| **Tireur Embusqué** | Ne peut pas être repéré tant qu'il ne tire pas. Après un tir : jet de Discrétion gratuit pour rester caché. | Adversaire |
| **Bombardier Suicide** | Quand éliminé : explose. Zone 2, dégâts = dégâts d'attaque × 2. Save DEX. | Minion |

### Pouvoirs de Boss exclusifs

| Pouvoir | Effet |
|---|---|
| **Phase 2** | Quand PV tombent à 0 la première fois : regagne 50% de ses PV max, change de pattern d'attaque (nouvelles armes, nouvelle posture, nouveaux pouvoirs). |
| **Réactions Multiples** | Peut réagir 1× par tour de PJ (pas 1× par round). Face à 4 PJ = 4 réactions potentielles. |
| **Présence Oppressante** | Tous les PJ à 4 cases ont Désavantage aux jets de sang-froid (Secoué). |
| **Champ de Distorsion** | Tous les PJ qui l'attaquent ont Désavantage. Les attaques qui ratent de 1-2 sont renvoyées vers un allié aléatoire. |
| **Adaptation** | Après avoir subi 2 attaques du même type, gagne Résistance à ce type de dégâts. Force les PJ à varier. |
| **Inévitable** | Ne peut pas être ralenti, immobilisé, ou repoussé. Ignore le terrain difficile. Avance toujours. |
| **Serviteur Fidèle** | Quand touché par une attaque, peut rediriger les dégâts vers un Minion adjacent. |

---

## 5. BUILDS PRÊTS À JOUER

### Minions

---

#### GARDE DE SÉCURITÉ — Minion, Niv 1 (Recrue)

```
Score Att: 8 | Dégâts: 1d4 (pistolet léger, range 8) | Armure: 2 (gilet de sécurité)
Saves: tous 8 | Speed: 6
Pouvoir: Formation (+1 Armure par allié adjacent, max +3)
```

*Les gardes de base de n'importe quel complexe. Dangereux uniquement en nombre. En groupe de 5 avec Formation, leur Armure monte à 5 — soudainement, ils sont un vrai problème.*

---

#### DRONE DE PATROUILLE — Minion, Niv 1 (Recrue)

```
Score Att: 8 | Dégâts: 1d4 (laser léger, range 10) | Armure: 1 (coque plastique)
Saves: tous 8 | Speed: Vol 8
Pouvoir: — | Immunité: Secoué, Stressé, Confus (machine)
Vulnérabilité: EMP (détruit automatiquement)
```

*Petit drone volant avec une caméra et un laser de défense. Facile à détruire, mais il alerte la sécurité s'il te repère. Le Tech peut le hacker.*

---

#### SOLDAT DE CHOC — Minion, Niv 5 (Vétéran)

```
Score Att: 9 | Dégâts: 1d6 (fusil d'assaut, range 12, auto 1d8) | Armure: 4 (gilet tactique)
Saves: tous 8 | Speed: 6
Pouvoir: Tactique de Meute (Avantage si allié adjacent à la cible)
```

*Troupes entraînées d'une PMC ou d'un gouvernement. En escouade de 4 avec Tactique de Meute, ils frappent avec Avantage — mortels pour un groupe de niv 3-5.*

---

#### INFECTÉ / ZOMBIE — Minion, Niv 3 (Recrue agressive)

```
Score Att: 8 | Dégâts: 1d6 (griffes/morsure, reach 1) | Armure: 0
Saves: STR 9, autres 7 | Speed: 4
Pouvoir: Frénésie (+2 dégâts... mais ils sont toujours en frénésie)
Vulnérabilité: Tir à la tête (crit = destruction immédiate, pas de Blessures)
```

*Lents, stupides, mais ils arrivent en vagues de 10+. Le vrai danger c'est la submersion.*

---

### Adversaires

---

#### MERCENAIRE VÉTÉRAN — Adversaire, Niv 3

```
PV: 35 | Blessures: 10 | Speed: 6 | Armure: 5 (gilet balistique)
Initiative: 1 carte | Saves: STR 10, DEX 9, WIT 8, EMP 8

ATTAQUE:
  Fusil d'assaut — Score 10 | 1d10+2 (range 12, auto 1d12+2)
  Couteau — Score 10 | 1d4+2 (reach 1)

POUVOIRS:
• Tactique de Meute — Avantage si un allié est adjacent à la cible.
• Retraite Tactique — Fuit sous couvert si PV < 10. Peut revenir avec 1d4 gardes Minions.
```

---

#### SNIPER CORPO — Adversaire, Niv 5

```
PV: 45 | Blessures: 10 | Speed: 6 | Armure: 3 (armure légère furtive)
Initiative: 1 carte | Saves: STR 8, DEX 11, WIT 10, EMP 8

ATTAQUE:
  Fusil de précision — Score 12 | 2d8+3 (range 20, Précis)
  Pistolet — Score 11 | 1d6+1 (range 8)

POUVOIRS:
• Tireur Embusqué — Ne peut pas être repéré tant qu'il ne tire pas. Jet de Discrétion gratuit après chaque tir.
• Première Balle — Au premier round, si agit avant la cible : Avantage + dégâts doublés.
• Repositionnement — Après avoir tiré, se déplace de 3 cases gratuitement.
```

*Le cauchemar des PJ qui avancent à découvert. Le trouver est le vrai challenge — le tuer est facile une fois sa position révélée.*

---

#### OPÉRATEUR DE DRONES — Adversaire, Niv 4

```
PV: 30 | Blessures: 8 | Speed: 6 | Armure: 2 (armure légère)
Initiative: 1 carte | Saves: STR 7, DEX 8, WIT 11, EMP 8

ATTAQUE:
  Pistolet — Score 9 | 1d6 (range 8)
  Drone armé × 2 — Score 11 (WIT) | 1d6 (range 10, vol 8)

POUVOIRS:
• Soutien Drone — Contrôle 2 drones Minions. Chaque drone a PV 5, Armure 1, Speed Vol 8.
  Les drones agissent sur son tour. Si l'opérateur est éliminé, les drones restent sur leur dernière instruction.
• Hack Ennemi — 1 action : jet WIT 11 vs Firewall d'un équipement PJ. Succès = l'objet dysfonctionne 1 round.
```

*Faible en personne, dangereux à travers ses drones. La priorité tactique : le trouver et l'éliminer, ou détruire ses drones d'abord ?*

---

#### EXÉCUTEUR CORPO — Adversaire, Niv 7

```
PV: 68 | Blessures: 14 | Speed: 6 | Armure: 8 (armure tactique corpo)
Initiative: 1 carte | Saves: STR 10, DEX 10, WIT 9, EMP 9

ATTAQUE:
  Fusil à rail — Score 13 | 2d8+4 (range 15, Perforant 2)
  Matraque électrique — Score 12 | 1d8+3 + Étourdissement 1 (reach 1)

POUVOIRS:
• Tir Perforant — Les attaques à distance ignorent 2 points d'Armure.
• Suppression — Quand il touche : la cible a Désavantage à sa prochaine action.
• Couverture Mobile — +2 Armure quand il se déplace (bouclier holographique).
```

*L'agent envoyé par la corpo pour régler les problèmes. Bien armé, bien protégé, méthodique. Un combat frontal est coûteux.*

---

#### HACKER BLACKHAT — Adversaire, Niv 5

```
PV: 28 | Blessures: 8 | Speed: 6 | Armure: 2 (armure légère)
Initiative: 1 carte | Saves: STR 7, DEX 9, WIT 12, EMP 8

ATTAQUE:
  Pistolet — Score 9 | 1d6 (range 8)
  Hack offensif — Score 12 (WIT) | Spécial (voir pouvoirs)

POUVOIRS:
• Hack Ennemi — 1 action : jet WIT 12 vs Firewall d'un implant ou équipement électronique PJ.
  Succès = l'objet dysfonctionne 1 round (perd bonus d'implant, arme s'enraye, comms coupées).
• Brouilleur — Passif : pas de communication sans fil à 6 cases.
• Retraite Tactique — Fuit si PV < 10 et plante une mine de données (piège virtuel).
```

*Ne le sous-estime pas. Il ne tire pas bien, mais il peut rendre ton fusil +2 inutile pendant un round, couper les comms du Marshal, et faire crasher le drone du Tech. Ciblez-le en priorité.*

---

#### CRÉATURE MUTANTE — Adversaire, Niv 6

```
PV: 60 | Blessures: 14 | Speed: 8 | Armure: 4 (peau épaisse)
Initiative: 1 carte | Saves: STR 12, DEX 9, WIT 6, EMP 6

ATTAQUE:
  Griffes — Score 12 | 2d6+4 (reach 1)
  Morsure — Score 11 | 2d8+3 (reach 1, si cible Immobilisée : auto-critique)

POUVOIRS:
• Charge — Si se déplace de 4+ cases en ligne droite avant d'attaquer : +1d6 dégâts.
• Grappin — Sur une touche mêlée : la cible est Immobilisée (save STR, 1 action pour se libérer).
• Frénésie — Quand PV < 30 : +2 dégâts sur toutes les attaques. Speed +2.
Immunité: Secoué (pas de peur, pas de morale)
```

*Rapide, brutale, et elle ne recule jamais. La Charge + Grappin + Morsure est un combo dévastateur : charge de loin, immobilise, et au prochain tour la morsure fait un crit automatique sur une cible immobilisée.*

---

### Boss

---

#### COMMANDANT NEXAGEN — Boss, Niv 5

```
PV: 100 | Blessures: 18 | Speed: 6 | Armure: 9 (armure tactique lourde TL3)
Initiative: 2 cartes (agit 2×/round) | Saves: STR 11, DEX 9, WIT 10, EMP 12

ATTAQUE:
  Pistolet lourd — Score 12 | 2d6+3 (range 10)
  Matraque étourdissante — Score 11 | 1d8+3 + Chancelant 1 round (reach 1)

POUVOIRS:
• Commandement (1 action) — Tous les alliés à 6 cases gagnent Avantage pendant 1 round.
• Appel de Renforts (2 actions) — 1d4 gardes Minions arrivent dans 2 rounds. 1×/combat.
• Phase 2 — Quand PV tombent à 0 : regagne 50 PV, sort un fusil d'assaut (Score 12, 2d8+3 auto 2d10+3).
  Perd Commandement, gagne Frénésie (+2 dégâts).
• Réaction : Riposte — Quand un PJ le rate en mêlée, contre-attaque gratuite.
```

*Phase 1 : un leader qui commande et envoie des sbires. Phase 2 : un combattant enragé qui a jeté sa radio et pris un fusil d'assaut. Le combat change de nature quand il bascule — préviens tes joueurs.*

---

#### CYBORG DE GUERRE "FENRIR" — Boss, Niv 8

```
PV: 156 | Blessures: 21 | Speed: 8 | Armure: 11 (exo-armure cybernétique intégrée)
Initiative: 2 cartes | Saves: STR 14, DEX 10, WIT 8, EMP 7

ATTAQUE:
  Bras-canon — Score 14 | 2d10+5 (range 12, Perforant 2)
  Poing cybernétique — Score 14 | 2d8+5 + Chancelant (reach 1)
  Salve de roquettes (1×/combat) — Zone 3, 3d8, save DEX pour demi

POUVOIRS:
• Inévitable — Ne peut pas être ralenti, immobilisé ou repoussé. Ignore le terrain difficile.
• Résistance (Balistique) — Demi-dégâts des armes à projectiles conventionnelles.
• Frénésie — Quand PV < 78 : +3 dégâts, Speed 10.
• Régénération (8) — Récupère 8 PV au début de chaque tour. S'arrête si dégâts Fire ou EMP.
• Réaction : Parade (mêlée) ou Esquive Réflexe (1×/round, annule 1 attaque à distance).
Immunité: Secoué, Stressé, Confus (machine + chair = aucune empathie)
```

*Le Terminator de votre campagne. Il avance, il encaisse, il régénère. Astuce : les dégâts Fire arrêtent la régénération. L'EMP peut désactiver temporairement le bras-canon (Hack Ennemi). Les PJ doivent collaborer — le Grounder ne peut pas tanker ça seul.*

---

#### IA DÉFENSIVE "AEGIS" — Boss, Niv 10

```
PV: 200 | Blessures: — (pas de corps physique, PV uniquement) | Speed: 0 (immobile, réseau)
Initiative: 3 cartes | Saves: STR —, DEX —, WIT 16, EMP —

ATTAQUE:
  Tourelles automatisées × 3 — Score 14 | 2d8+3 chacune (range 15)
  Verrouillage portes — Automatique : ferme/ouvre les portes du complexe à volonté
  Hack offensif — Score 16 (WIT) vs Firewall implants/équipement PJ

POUVOIRS:
• Soutien Drone — Contrôle 6 drones Minions (Score 10, 1d6, Armure 1, Vol 8, PV 0).
  Remplace les drones détruits : 2 nouveaux drones par round (max 6 actifs).
• Hack Ennemi — Cible TOUS les équipements électroniques des PJ à 20 cases. 1 action.
• Adaptation — Après avoir subi 2 attaques du même type, gagne Résistance à ce type.
• Champ de Distorsion — Tous les PJ dans le complexe ont Désavantage sur les attaques contre les tourelles.
• Phase 2 — Quand PV tombent à 0 : active le protocole d'auto-destruction.
  Les PJ ont 10 rounds pour s'échapper. Pendant ces 10 rounds, AEGIS continue de contrôler
  tourelles et drones avec Frénésie (+3 dégâts).
Immunité: Toutes les conditions. Pas de corps = pas de mêlée, pas de Secoué, pas de Stressé.
Vulnérabilité: Le noyau physique est quelque part dans le complexe. Le trouver (Investigation/Hacking)
  et le détruire (Armure 15, PV 30) tue AEGIS instantanément.
```

*Pas un ennemi qu'on combat au fusil — un puzzle tactique. Les PJ doivent survivre aux tourelles et aux drones pendant que le Hacker cherche le noyau. Le Tech et l'Infiltrator brillent ici. Le Grounder couvre.*

---

## 6. CONSTRUCTION DE RENCONTRES

### Budget de difficulté

Le système utilise un budget simple basé sur le **ratio ennemis/PJ**.

| Difficulté | Description | Budget |
|---|---|---|
| **Facile** | Échauffement, les PJ dominent | 0.5 Adversaire par PJ OU 2-3 Minions par PJ |
| **Moyenne** | Combat standard, coûte des ressources | 1 Adversaire par PJ OU 4-5 Minions par PJ |
| **Difficile** | Quelqu'un risque de tomber | 1.5 Adversaire par PJ OU 1 Adversaire + 3 Minions par PJ |
| **Mortelle** | Probable TPK si mal joué | 2 Adversaires par PJ OU 1 Boss + Minions |
| **Boss fight** | Combat narratif majeur | 1 Boss + 2-4 Minions par PJ |

> **Exemple :** 4 PJ niv 3. Combat moyen = 4 Adversaires niv 3, OU 1 Adversaire niv 3 + 12 Minions. Boss fight = 1 Boss niv 5 + 8-16 Minions.

### Ajustements

| Facteur | Ajustement |
|---|---|
| **Ennemis de niveau supérieur aux PJ** | +1 niveau ennemi = environ +50% difficulté |
| **Terrain favorable aux ennemis** | +1 cran de difficulté (couverture ennemie, hauteur, espace clos) |
| **PJ bien équipés** (loot +2/+3) | -1 cran de difficulté |
| **PJ épuisés** (surges bas, conditions actives) | +1 cran de difficulté |
| **Surprise** | +1 cran si les ennemis surprennent, -1 si les PJ surprennent |

### Combien de combats par Shift ?

| Nombre | Effet sur les ressources |
|---|---|
| 1 combat/Shift | Les PJ peuvent tout dépenser — pas de gestion de surges. OK pour boss fights. |
| 2 combats/Shift | Les PJ doivent gérer un peu — les surges commencent à compter. Rythme standard. |
| 3-4 combats/Shift | **Attrition.** Les surges deviennent précieux. Le Medic est indispensable. Les conditions s'accumulent. Le 4e combat est un cauchemar même contre des Minions. C'est ici que le système brille. |

### Composition d'une bonne rencontre

1. **Variété de rôles.** Pas 6 gardes identiques — 4 Minions + 1 Adversaire sniper + 1 Adversaire leader.
2. **Au moins un ennemi avec un pouvoir de contrôle.** Suppression, Couverture de Feu, Terreur — quelque chose qui empêche les PJ de juste spammer les attaques.
3. **Un ennemi prioritaire.** Le leader, le hacker, le sniper — quelqu'un que les PJ doivent éliminer en premier. Ça force des choix tactiques.
4. **Du terrain.** Couvertures, élévations, zones dangereuses (explosion imminente, champ de mines, tir croisé).
5. **Un objectif autre que "tuez tout".** Protéger un VIP, atteindre la porte, hacker le terminal, survivre X rounds.

---

## 7. CONVERSION DEPUIS D&D 5e

Tu as un monstre D&D 5e et tu veux l'utiliser ? Voici la conversion rapide.

### Stats

| D&D 5e | Notre système |
|---|---|
| Ability Score (ex: STR 16, mod +3) | **Valeur = 8 + mod D&D** (STR 16 → STR 11) |
| Armor Class (ex: AC 15) | **Armure = AC - 10** (AC 15 → Armure 5) |
| Hit Points (ex: HP 52) | **PV = HP × 0.8** (HP 52 → PV 42) |
| Saving Throws | Proficient saves → **saves avantagés** |
| Attack bonus (ex: +5 to hit) | **Score Att. = 8 + bonus d'attaque ÷ 2** (arrondi sup) (+5 → Score 11) |
| Damage (ex: 2d6+3) | **Garder tel quel** |
| Challenge Rating | **Niveau PNJ ≈ CR** (CR 1 = niv 1, CR 5 = niv 5, CR 10+ = niv 10, max niv 15) |

### Catégorie

| CR D&D | Notre catégorie |
|---|---|
| CR ⅛ à ¼ | Minion |
| CR ½ à 4 | Adversaire niv ½ à 4 |
| CR 5 à 10 | Adversaire niv 5-10 OU Boss niv 3-7 |
| CR 11 à 20 | Boss niv 8-12 |
| CR 21+ | Boss niv 13-15 (compresser) |

### Pouvoirs

| Capacité D&D | Conversion |
|---|---|
| Multiattack | → **Multiattaque** (pouvoir Boss) |
| Legendary Actions | → **Cartes d'initiative multiples** (2-4 cartes) |
| Legendary Resistance | → **Immunité (condition)** ou **Esquive Réflexe** |
| Tactique de Meute | → **Tactique de Meute** (identique) |
| Frightful Presence | → **Terreur** |
| Regeneration | → **Régénération (X)** |
| Spellcasting | → **1-2 effets pré-choisis** au lieu d'une liste complète de sorts |
| Damage Resistance | → **Résistance (type)** |
| Damage Immunity | → **Immunité (type)** |

### Exemple de conversion

**D&D 5e :** Gladiator (CR 5), AC 16, HP 112, STR 18(+4), DEX 15(+2), CON 16(+3), saves STR +7 CON +6, Multiattack (3 attacks), +7 to hit, 2d6+4 damage.

**Conversion :**

```
GLADIATEUR — Adversaire, Niv 5
PV: 90 (112 × 0.8) | Blessures: 12 | Speed: 6 | Armure: 6 (AC 16 - 10)
Saves: STR 12 (avantagé), DEX 10, WIT 8, EMP 8

ATTAQUE:
  Épée large — Score 12 (8 + 7÷2 arrondi) | 2d6+4 (reach 1)

POUVOIRS:
• Multiattaque — Peut faire 2 attaques différentes avec 2 actions.
• Charge — +1d6 dégâts si déplacement de 4+ cases en ligne droite.
• Parade (réaction mêlée) — Jet d'arme pour annuler une attaque.
```

---

## 8. STAT BLOCK FORMAT — Le standard

Chaque stat block suit ce format. Un MJ doit pouvoir le lire en 5 secondes.

```
NOM — [Catégorie], Niv [X]
PV: [X] | Blessures: [X] | Speed: [X] | Armure: [X] ([source])
Initiative: [X carte(s)] | Saves: STR [X], DEX [X], WIT [X], EMP [X]

ATTAQUE:
  [Nom arme] — Score [X] | [dégâts] ([range/reach], [propriétés])
  [Nom arme 2] — Score [X] | [dégâts] ([range/reach], [propriétés])

POUVOIRS:
• [Nom] — [Effet en 1 ligne]
• [Nom] — [Effet en 1 ligne]
[Immunité/Vulnérabilité si applicable]
```

**Règles de rédaction :**
- Maximum **6 lignes** pour un Adversaire, **10 lignes** pour un Boss.
- Chaque pouvoir s'explique en **1 phrase**.
- Si tu as besoin de plus de 2 phrases pour un pouvoir, c'est trop complexe — simplifie.
- Les Minions tiennent sur **2 lignes**.

---

## ANNEXE — Table de référence rapide

### Armure par type d'équipement

| Type | Armure | Exemples |
|---|---|---|
| Aucune | 0 | Civil, animal |
| Cuir / textile renforcé | 2-3 | Veste en cuir, uniforme de sécurité |
| Gilet balistique léger | 3-4 | Gilet kevlar, armure discrète |
| Gilet tactique | 5-6 | Armure militaire standard |
| Armure lourde | 7-9 | Armure composite, plaques céramiques |
| Exo-armure | 10-12 | Exosquelette blindé, armure assistée |
| Blindage véhicule | 12-16 | Transport blindé, mech |
| Carapace naturelle | 2-8 | Variable selon la créature |

### Score d'attaque — Ce que ça signifie

| Score | % toucher (vs PJ sans couverture) | Niveau approximatif |
|---|---|---|
| 8 | 40% | Recrue, civil |
| 9 | 45% | Garde de base |
| 10 | 50% | Soldat entraîné |
| 11 | 55% | Vétéran |
| 12 | 60% | Spécialiste |
| 13 | 65% | Expert |
| 14 | 70% | Élite |
| 15 | 75% | Maître |
| 16 | 80% | Légende |

### Dégâts — Ce que ça signifie

| Dégâts moyens/action | Danger |
|---|---|
| 3-5 | Piqûre de moustique (Minion) |
| 6-8 | Dangereux (Adversaire faible) |
| 9-12 | Sérieux (Adversaire standard) |
| 13-16 | Douloureux (Adversaire fort / Boss faible) |
| 17-20 | Dévastateur (Boss) |
| 21+ | Potentiellement létal en 1-2 coups (Boss extrême) |
