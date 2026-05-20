# FORMULES CANONIQUES — v2

> **Ce document est la référence unique pour toutes les formules du système.** En cas de conflit entre ce document et un autre (Grounder v1/v2, design doc v3, guérison v2, playtest kit v1), **ce document fait foi**. Intègre les décisions du 27 février 2026.

---

## Décisions verrouillées

| Question | Décision | Ancienne version remplacée |
|---|---|---|
| Nombre de niveaux | **15** | Design doc v3 (20 implicite), Grounder v2 précédent (20) |
| Proficiency | **+1 / +2 / +3** (paliers à 1-5 / 6-10 / 11-15) | Design doc v3 (+2 à +6) |
| Progression du toucher | **Deux jambes : prof (stable) + loot (volatile)** | Prof seule (design doc v3) |
| Bonus loot | **+0 à +3** sur armes, viseurs, implants, etc. | Pas formalisé |
| Ennemis difficiles | **Uniquement via Désavantage** (pouvoirs de monstre, conditions) | Difficulté variable envisagée puis rejetée |
| Augmentations de stat | **3 augmentations** : niv 4, 8, 12 (stat au choix) | 4 principales + 4 secondaires (v1) |
| Valeur de Surge | **Fixe** (Vigueur + bonus STR). Pas de dé. | Grounder v1 "1d10 + bonus STR" |
| Surges/jour | **Base classe + bonus STR** | Grounder v1 "3 + bonus STR" |
| Blessures | **Vigueur + bonus STR** | Grounder v1 "STR score complet" |
| Marshal Vigueur | **8** (leader cerveau, pas tank) | Design doc v3 (Vig 10) |
| Repos / Surges | **Restrictif** (guérison v2) | Playtest kit "D&D 5e style" |
| Push de jet | **Oui** (Dragonbane-style, 4 conditions sur 4 stats) | Pas de push dans le système précédent |
| Dégradation du loot | **3 états : Neuf → Endommagé → Détruit** | Pas formalisé |

---

## 1. ROSTER — 5 CLASSES

| Classe | Vigueur | Rôle | Verbe |
|---|---|---|---|
| **Grounder** | 10 | Soldat polyvalent, front-line | Tenir et frapper |
| **Infiltrator** | 8 | Ops clandestines, dégâts burst | Frapper et disparaître |
| **Medic** | 8 | Soins, déclencheur de surges allié | Maintenir en vie |
| **Marshal** | 8 | Ordres tactiques, leader de terrain | Diriger et galvaniser |
| **Tech** | 6 | Drones, hacking, gadgets, contrôle | Contrôler le terrain |

---

## 2. LES 4 STATS

| Stat | Bonus | Rôle dans les formules |
|---|---|---|
| **STR** | valeur − 8 | PV, Blessures, Surges/jour, Valeur de Surge, save corporel, mêlée |
| **DEX** | valeur − 8 | Tir, réflexes, esquive, initiative bonus |
| **WIT** | valeur − 8 | Hacking, médecine, sciences, perception environnement |
| **EMP** | valeur − 8 | Social, leadership, perception des gens |

**Arrays de création :**

| Array | Valeurs (à distribuer sur STR/DEX/WIT/EMP) |
|---|---|
| Standard | 10, 10, 8, 7 |
| Balanced | 10, 9, 9, 8 |
| Min-Max | 11, 9, 7, 7 |

**Augmentations de stats :** +1 à une stat au choix aux niveaux **4, 8, 12** (3 augmentations totales). Pas de plafond fixe — le jeu gère naturellement (max 11 au départ + 3 augmentations = max 14 organique). La cybernétique, les mutations, et les objets spéciaux peuvent pousser au-delà.

---

## 3. POINTS DE VIE (PV)

Les PV sont le pool unique de points de vie. Ils représentent la chance, la fatigue, l'endurance et la capacité à encaisser. Ils augmentent avec le niveau.

### Formule

| Niveau | PV |
|---|---|
| **Niveau 1** | 2 × (Vigueur + bonus STR) |
| **Niveaux 2+** | + (Vigueur ÷ 2 + bonus STR + 1) par niveau. Minimum +3/niv. |

| Classe | Vigueur | PV gain/niv (STR 10, +2) | PV gain/niv (STR 8, 0) | PV gain/niv (STR 7, -1) |
|---|---|---|---|---|
| **Grounder** | 10 | 8/niv | 6/niv | 4/niv |
| **Infiltrator** | 8 | 6/niv | 5/niv | 4/niv |
| **Medic** | 8 | 6/niv | 5/niv | 4/niv |
| **Marshal** | 8 | 7/niv | 5/niv | 4/niv |
| **Tech** | 6 | 5/niv | 4/niv | 3/niv |

> *Note : la Vigueur n'affecte plus le gain de PV par niveau — seulement les PV niv 1, les Blessures, les Surges, et la Valeur de Surge. Le gain/niv dépend uniquement du bonus STR.*

### Exemples complets (STR 10, bonus +2)

| Classe | Niv 1 | Niv 5 | Niv 10 | Niv 15 |
|---|---|---|---|---|
| **Grounder** (Vig 10) | 24 | 56 | 96 | 136 |
| **Infiltrator** (Vig 8) | 20 | 44 | 74 | 104 |
| **Marshal** (Vig 8) | 20 | 48 | 83 | 118 |
| **Tech** (Vig 6) | 10 | 30 | 55 | 80 |

### Exemples complets (STR 8, bonus 0)

| Classe | Niv 1 | Niv 5 | Niv 10 | Niv 15 |
|---|---|---|---|---|
| **Grounder** (Vig 10) | 20 | 44 | 74 | 104 |
| **Infiltrator** (Vig 8) | 16 | 36 | 61 | 86 |
| **Tech** (Vig 6) | 12 | 28 | 48 | 68 |

### Exemples complets (STR 7, bonus -1)

| Classe | Niv 1 | Niv 5 | Niv 10 | Niv 15 |
|---|---|---|---|---|
| **Infiltrator** (Vig 8) | 14 | 30 | 50 | 70 |
| **Tech** (Vig 6) | 10 | 22 | 37 | 52 |

---

## 4. BLESSURES (Système de mort)

Les Blessures remplacent les Blessures et les PV. C'est un compteur de 0 à 6.

**6 Blessures = mort.**

### Quand gagne-t-on des Blessures ?

| Événement | Blessures |
|---|---|
| **PV tombent à 0** | +1 Blessure → Mourant (1 action/tour) |
| **Réussite critique ennemie (Nat 1)** | Dégâts normaux sur PV + **1 Blessure** |
| **Subir des dégâts pendant Mourant** | **+2 Blessures** |
| **Subir un crit pendant Mourant** | **+3 Blessures** |
| **Agir agressivement pendant Mourant** | +1 Blessure (sauf save STR réussi) |

### Mourant

À 0 PV, tu es **Mourant**. Tu restes conscient mais tu n'as que **1 action par tour** (au lieu de 3). Ta Concentration est brisée. Tu peux ramper, tirer, parler, utiliser un objet — mais chaque action agressive (attaquer, lancer) coûte +1 Blessure sauf save STR réussi.

### Stabiliser

Un allié adjacent peut te stabiliser avec **1 action + jet de Médecine** (pas de difficulté). Une fois stabilisé, tu restes inconscient à 0 PV mais tu ne gagnes plus de Blessures.

### Récupération des Blessures

- **1 Blessure** guérie par **Shift Rest** (6h de repos sûr)
- Le Medic peut en soigner **1 de plus** par Shift avec un jet de Médecine
- Certains objets légendaires ou capacités de haut niveau peuvent soigner des Blessures

### Mourant et Surges

Un allié peut utiliser Premiers Soins (Medic) ou un Stim pack sur toi pour te remonter au-dessus de 0 PV → tu n'es plus Mourant. **Mais tes Blessures restent** jusqu'au repos.

## 5. SURGES

### Surges par jour

**Formule : base classe + bonus STR**

| Classe | Base Surges | Avec STR 10 (+2) | Avec STR 8 (0) |
|---|---|---|---|
| **Grounder** | 7 | 9 | 7 |
| **Marshal** | 6 | 8 | 6 |
| **Medic** | 6 | 8 | 6 |
| **Infiltrator** | 5 | 7 | 5 |
| **Tech** | 4 | 6 | 4 |

### Valeur de Surge

**Formule : Vigueur + bonus STR** (fixe, pas de dé)

| Classe | Valeur de Surge (STR 10, +2) | Valeur de Surge (STR 8, 0) |
|---|---|---|
| **Grounder** | 12 | 10 |
| **Marshal/Medic** | 10 | 8 |
| **Infiltrator** | 10 | 8 |
| **Tech** | 8 | 6 |

---

## 6. ÉCONOMIE DES SURGES — MODÈLE RESTRICTIF

> **Principe :** Les surges sont finis et précieux. Il faut un **déclencheur**. C'est ce qui rend le Medic et le Marshal indispensables.

| Déclencheur | Quand | Coût | Effet |
|---|---|---|---|
| **Second Souffle** | Combat (1 action) | 1 Surge perso | Récupère Valeur de Surge en PV. **1×/combat.** |
| **Stretch Rest** | Hors combat (~15 min) | 1 Surge | Récupère Valeur de Surge en PV. **1×/Stretch.** |
| **Stim Pack** | Combat ou hors combat | 1 Surge + consomme le stim | Récupère Valeur de Surge en PV. |
| **Pouvoir Medic** | Combat ou Stretch | 1 Surge du patient | Le Medic active le surge d'un allié. Bonus possibles. |
| **Pouvoir Marshal** | Combat | 1 Surge de l'allié ciblé | Galvanise un allié. |

**Contraintes :** Max 2 Stretch Rests entre chaque Shift. Surges ne se régénèrent que sur Shift Rest (6-8h). Les surges ne soignent PAS les PV.

**Shift Rest (6-8h) :** PV au max. Tous les surges reviennent. Secoué/conditions effacés. **1 Blessure guérie** (+1 avec Medic). Critiques mineurs guérissent. Équipement Endommagé peut être réparé (voir section 10).

---

## 7. PROGRESSION — 15 NIVEAUX

### Proficiency

| Niveaux | Proficiency |
|---|---|
| 1–5 | +1 |
| 6–10 | +2 |
| 11–15 | +3 |

### Score de Compétence

**Score = Stat + Proficiency (si formé) + Bonus Loot (si applicable)**

En combat, difficulté pour toucher = **toujours 0**. La protection vient de l'Armure. Les ennemis difficiles à toucher utilisent des **pouvoirs qui imposent Désavantage**, pas une difficulté numérique.

### Courbe du toucher — Les deux jambes

La progression du personnage repose sur deux sources parallèles :

**Jambe 1 — Proficiency (stable, prévisible) :** Monte avec le niveau, jamais perdue.

**Jambe 2 — Loot (dynamique, volatile) :** Bonus de +0 à +3 via armes, viseurs, implants, etc. Sujet à rotation — le loot se casse, se perd, se fait voler ou détruire.

### Courbe complète — Grounder DEX principale

| Niv | DEX | Prof | Loot attendu | Score total | % toucher | Avec Désavantage | Avec Avantage |
|---|---|---|---|---|---|---|---|
| 1 | 10 | +1 | +0 | 11 | 55% | 30% | 80% |
| 3 | 10 | +1 | +0/+1 | 11-12 | 55-60% | 30-36% | 80-84% |
| 5 | 11 | +1 | +1 | 13 | 65% | 42% | 88% |
| 6 | 11 | +2 | +1 | 14 | 70% | 49% | 91% |
| 8 | 12 | +2 | +1/+2 | 15-16 | 75-80% | 56-64% | 94-96% |
| 10 | 12 | +2 | +2 | 16 | 80% | 64% | 96% |
| 11 | 12 | +3 | +2 | 17 | 85% | 72% | 98% |
| 13 | 13 | +3 | +2/+3 | 18-19 | 90-95% | 81-90% | 99% |
| 15 | 13 | +3 | +3 | 19 | 95% | 90% | 99% |

### Courbe NUE (sans loot) — Le plancher

| Niv | DEX | Prof | Score (nu) | % toucher | Commentaire |
|---|---|---|---|---|---|
| 1 | 10 | +1 | 11 | 55% | Recrue compétente |
| 5 | 11 | +1 | 12 | 60% | Soldat expérimenté |
| 6 | 11 | +2 | 13 | 65% | Vétéran |
| 10 | 12 | +2 | 14 | 70% | Spécialiste |
| 11 | 12 | +3 | 15 | 75% | Élite |
| 15 | 13 | +3 | 16 | 80% | Légende — mais rate encore 1 coup sur 5 |

> **Observation clé :** Sans loot, un personnage niv 15 touche à 80%. Le loot pousse à 95%, mais ce bonus est volatile. Un personnage dépouillé de son équipement reste compétent — pas surpuissant. La rotation du loot crée la tension.

### Impact de Désavantage / Double Désavantage

| Score | Normal | Désavantage (2d20 haut) | Double Désavantage (3d20 haut) |
|---|---|---|---|
| 11 | 55% | 30% | 17% |
| 14 | 70% | 49% | 34% |
| 16 | 80% | 64% | 51% |
| 19 | 95% | 90% | 86% |

> **Design :** Désavantage est le principal levier pour rendre les ennemis difficiles à toucher. Un boss avec "Champ de distorsion — impose Désavantage" réduit un héros niv 15 de 95% à 90%, ou de 80% (nu) à 64%. Double Désavantage (rare, réservé aux boss) est dévastateur — Score 14 tombe à 34%.

### Structure de progression commune

| Niveau | Contenu type |
|---|---|
| **1** | Capacités de base + mécanique signature |
| **2** | Capacité secondaire ou mécanique de ressource |
| **3** | **Sous-classe** (choix entre 2–3 options) + capacité de sous-classe |
| **4** | **Stat +1** (au choix) |
| **5** | Capacité majeure de classe |
| **6** | Capacité de classe ou liste de choix |
| **7** | **Sous-classe capacité** |
| **8** | **Stat +1** (au choix) |
| **9** | Capacité majeure de classe |
| **10** | Capacité de classe ou liste de choix |
| **11** | **Sous-classe capacité** |
| **12** | **Stat +1** (au choix) |
| **13** | Capacité majeure de classe |
| **14** | Capacité de classe ou liste de choix |
| **15** | **Couronnement** de classe + sous-classe couronnement |

### Trois arcs narratifs

| Arc | Niveaux | Prof | Loot attendu | Moment |
|---|---|---|---|---|
| **Recrue** | 1–5 | +1 | +0 à +1 | Apprendre, survivre, premier loot marquant |
| **Vétéran** | 6–10 | +2 | +1 à +2 | Maîtriser, s'équiper, former une identité |
| **Élite** | 11–15 | +3 | +2 à +3 | Dominer, loot légendaire, couronnement |

---

## 8. PUSH DE JET — MÉCANIQUE

> **Inspiration :** Dragonbane. Quand tu rates un jet, tu peux tenter à nouveau — mais à un coût.

### Règle

Quand tu **rates** un jet de compétence, d'attaque, ou de save, tu peux choisir de **pousser le jet** (push). Tu relances le d20. Le nouveau résultat s'applique, quel qu'il soit. Tu ne peux pas pousser un Échec critique (Nat 20).

**Coût immédiat (choisir UN des deux) :**

**Option A — Condition.** Tu subis immédiatement une **condition** liée à une des 4 stats (voir ci-dessous). Tu choisis laquelle, mais tu dois pouvoir la justifier narrativement.

**Option B — Dégradation d'équipement.** Une pièce d'équipement de ton choix passe à l'état **Endommagé** (si déjà endommagé, elle est **Détruite**). Tu décris comment ça arrive.

> **Philosophie :** Pousser un jet, c'est forcer le destin. Soit ton corps paie (condition), soit ton matériel paie (dégradation). Le joueur choisit ce qu'il est prêt à sacrifier. C'est un choix tactique profond — est-ce que tu risques ta cybernétique à +2 pour réussir ce hack, ou tu préfères devenir Stressé ?

### Restrictions

- Tu ne peux pas pousser un Échec critique (Nat 20).
- Tu ne peux pas pousser un jet déjà poussé.
- Pousser un jet est volontaire — personne ne t'y oblige.
- Tous les dés sont relancés (y compris Avantage/Désavantage).

---

## 9. CONDITIONS (4 stats, 4 conditions)

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

---

## 10. DÉGRADATION DU LOOT — 3 ÉTATS

Chaque pièce d'équipement notable (armes, armures, implants, gadgets — pas les consommables) a un état :

| État | Effet | Visuel fiche |
|---|---|---|
| **Neuf** (✓) | Fonctionne normalement. Bonus plein. | Case vide |
| **Endommagé** (⚠) | **Le bonus numérique est réduit de moitié** (arrondi inf). Les qualités spéciales fonctionnent encore. | Case cochée 1× |
| **Détruit** (✗) | L'objet est **inutilisable**. Plus aucun bonus ni qualité. Doit être réparé ou remplacé. | Case cochée 2× |

### Exemples

| Objet | Neuf | Endommagé | Détruit |
|---|---|---|---|
| Fusil d'assaut +2, Perforant 1 | +2 au Score, Perforant 1 | +1 au Score, Perforant 1 | Inutilisable |
| Viseur holographique +1 | +1 au Score | +0 au Score (pas de bonus, mais encore attaché) | Grillé, à remplacer |
| Implant cybernétique +3 STR | +3 STR | +1 STR | Dysfonctionnel, risque de rejet |
| Armure tactique (Armure 5) | Armure 5 | Armure 2 | Ne protège plus |

### Sources de dégradation

**Volontaire (push de jet) :** Le joueur choisit de dégrader une pièce d'équipement au lieu de prendre une condition.

**Ennemis :**
- **Critique ennemi (Nat 1 / Réussite critique) :** Le MJ peut choisir de dégrader une pièce d'équipement de la cible au lieu d'infliger des dégâts bonus.
- **Pouvoirs spéciaux :** Certains adversaires ont des capacités qui visent l'équipement — EMP (grille l'électronique), acide (ronge l'armure), hacker (jam une cybernétique), etc.
- **Jam temporaire :** Certaines attaques ennemies peuvent "jammer" un équipement pour X tours (il fonctionne comme Endommagé pendant la durée) sans le dégrader réellement.

**Environnement :** Explosions, chutes, conditions extrêmes (chaleur, froid, radiation) peuvent dégrader l'équipement selon le contexte narratif.

**Fumble (Nat 20 / Échec critique) :** Une table de fumble peut inclure "ton arme est endommagée" comme résultat possible.

### Réparation

| Action | Durée | Résultat |
|---|---|---|
| **Réparation de terrain** (Ingénierie, diff 2) | 1 Stretch | Endommagé → Neuf |
| **Réparation d'atelier** (Ingénierie, diff 1) | 1 Shift | Endommagé → Neuf |
| **Reconstruction** (Ingénierie, diff 4, pièces nécessaires) | 1 Shift | Détruit → Endommagé |
| **Remplacement** | Variable (loot, achat, craft) | Détruit → nouvel objet |

> **Boucle de gameplay :** Acquérir du loot → l'utiliser → le perdre/casser → en acquérir du nouveau. La rotation est constante. Un personnage niv 15 avec un fusil +3 légendaire tient à ce fusil — mais un critique ennemi peut l'endommager et réduire le bonus à +1. Il doit trouver un atelier, un Tech allié, ou un nouveau fusil. C'est la tension.

---

## 11. BONUS DE DÉGÂTS (rappel)

Le bonus de dégâts d'arme utilise la stat d'arme (DEX pour tir, STR pour mêlée). **Ce bonus s'applique uniquement aux PJ** — les monstres/adversaires utilisent leurs dégâts fixes.

| Valeur de stat d'arme | Bonus dégâts |
|---|---|
| 7 | Aucun |
| 8–9 | +1d4 |
| 10–12 | +1d6 |
| 13+ | +1d8 |

---

## 12. FORMULES RÉSUMÉES — FICHE DE CALCUL

```
1. Choisir une classe → Vigueur
2. Distribuer un array de stats → STR, DEX, WIT, EMP
3. Bonus STR = STR − 8

PV (niv 1)  = Vigueur + bonus STR
Blessures          = Vigueur + bonus STR (fixe)
Surges/j    = base classe + bonus STR
Surge Val   = Vigueur + bonus STR (fixe)

Score attaque = stat d'arme + proficiency + bonus loot
Save          = stat + proficiency (si formé)
Skill check   = stat + proficiency (si formé) + bonus loot (si applicable)
```

### Tableau de synthèse — Personnages typiques (niv 1, pas de loot)

| Personnage | Classe | STR | DEX | Vig | PV niv1 | Blessures | Surges/j | Surge Val | Score Tir |
|---|---|---|---|---|---|---|---|---|---|
| Soldat STR 10 | Grounder | 10 | 10 | 10 | 12 | 12 | 9 | 12 | 11 (55%) |
| Soldat DEX 10 | Grounder | 10 | 10 | 10 | 12 | 12 | 9 | 12 | 11 (55%) |
| Espion DEX 11 | Infiltrator | 7 | 11 | 10 | 7 | 7 | 4 | 7 | 12 (60%) |
| Médecin WIT 10 | Medic | 8 | 9 | 8 | 8 | 8 | 6 | 8 | 10 (50%) |
| Commandant EMP 10 | Marshal | 9 | 8 | 8 | 9 | 9 | 7 | 9 | 9 (45%) |
| Hacker WIT 11 | Tech | 7 | 8 | 6 | 5 | 5 | 3 | 5 | 9 (45%) |

> **Note :** Le Marshal et le Tech sont mauvais tireurs au niv 1 (45%). C'est voulu — ce ne sont pas des combattants. Le loot (+1 arme) les pousse à 50-55%, ce qui reste modeste. Leurs forces sont ailleurs (ordres, drones, hacking).

---

## 13. INCOHÉRENCES RÉSOLUES — LOG

| # | Sujet | Ancienne valeur | **Résolution canonique** | Date |
|---|---|---|---|---|
| 1 | Surges/jour Grounder | 3 + STR (v1) | **7 + STR** | 27/02 |
| 2 | Valeur de Surge | 1d10 + STR (v1) | **Fixe : Vig + STR** | 27/02 |
| 3 | Blessures Grounder | STR score (v1) | **Vig + bonus STR** | 27/02 |
| 4 | Marshal Vigueur | 10 (design doc) | **8** | 27/02 |
| 5 | Repos / Surges | D&D 5e style (playtest kit) | **Restrictif (guérison v2)** | 27/02 |
| 6 | Niveaux max | 20 (design doc, v1) | **15** | 27/02 |
| 7 | Secoué | Vague (v1) | **Niveaux 1/2/3** (conditions v1) | 27/02 |
| 8 | Proficiency | +2 à +6 (design doc) | **+1 / +2 / +3** | 27/02 |
| 9 | Loot dans progression | Pas formalisé | **+0 à +3, deuxième jambe** | 27/02 |
| 10 | Push de jet | Pas de push | **Dragonbane-style, condition OU dégradation loot** | 27/02 |
| 11 | Augmentations de stat | 4 principales + 4 secondaires | **3 au choix (niv 4/8/12)** | 27/02 |
| 12 | Dégradation loot | Pas formalisé | **Neuf → Endommagé → Détruit** | 27/02 |

---

## PROCHAINE ÉTAPE

Avec ces formules verrouillées, réécrire les classes sur 15 niveaux. Le Grounder v2 (actuellement sur 20 niveaux) doit être recompressé sur 15, et la proficiency/les chiffres doivent être recalculés.

Ordre proposé :
1. **Grounder v3** — recompresser de 20 à 15 niveaux avec prof +1/+2/+3
2. **Infiltrator** — le deuxième pilier combat
3. **Medic** — le déclencheur de surges
4. **Marshal** — le cerveau tactique
5. **Tech** — le contrôleur de terrain
