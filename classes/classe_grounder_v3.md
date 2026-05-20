# GROUNDER v3 — Soldat de première ligne

> *Tu es le premier déployé et le dernier à partir. Que tu te considères comme un simple fantassin ou un opérateur d'élite, tes talents au combat font de toi l'allié le plus fiable sous le feu. Tu maîtrises presque toutes les armes à feu — rafale ou tir posé, pistolets ou armes lourdes. Tu n'es pas le plus flashy, mais tu es celui sur qui tout le monde compte quand les balles sifflent.*

---

## Fiche technique

| | |
|---|---|
| **Stat principale** | STR ou DEX (choix à la création, permanent) |
| **Vigueur** | 10 |
| **PV niveau 1** | Vigueur + bonus STR = **12** (STR 10) |
| **PV par niveau (2+)** | ⌈Vig/2⌉ + 1 + bonus STR = **8/niv** (STR 10) |
| **Blessures** | Vigueur + bonus STR = **12** (STR 10). Fixe. |
| **Saves proficients** | STR, DEX |
| **Armures** | Toutes armures, boucliers balistiques |
| **Armes** | Toutes armes à feu, armes simples de mêlée |
| **Compétences** | 2 parmi : Athlétisme, Intimidation, Perception, Survie, Tactique★, Connaissance (militaire) |
| **Surges/jour** | 7 + bonus STR = **9** (STR 10) |
| **Valeur de Surge** | Vigueur + bonus STR = **12 PV** (fixe) |

### Score de Tir — Courbe sur 15 niveaux

| Niv | DEX | Prof | Loot attendu | Score | % toucher |
|---|---|---|---|---|---|
| 1 | 10 | +1 | +0 | 11 | 55% |
| 5 | 11 | +1 | +1 | 13 | 65% |
| 6 | 11 | +2 | +1 | 14 | 70% |
| 10 | 12 | +2 | +2 | 16 | 80% |
| 11 | 12 | +3 | +2 | 17 | 85% |
| 15 | 13 | +3 | +3 | 19 | 95% |

*Sans loot, niv 15 : DEX 13 + prof +3 = 16 (80%). Le loot est la deuxième jambe.*

### Équipement de départ

- 2 armes à feu (valeur ≤ $300 chacune)
- 2 grenades à concussion
- 1 armure (valeur ≤ $300)
- Kit de terrain basique + radio tactique

---

## Mécanique signature : Doctrine de Tir

Au niveau 1, tu choisis une doctrine. Tu peux changer de doctrine pendant un Shift Rest (6h).

### Assaut

Tu favorises les armes automatiques — rafales, suppression, volume de feu.

- **Suppression améliorée.** Quand tu touches avec une arme en mode tir auto, la cible subit automatiquement **Secoué +1 niveau** (en plus du Secoué normal du tir auto).
- **Tir de Saturation.** Quand tu utilises le tir auto, tu peux cibler une **zone de 2×2 cases** au lieu de 3 cibles individuelles. Toutes les créatures dans la zone font un save DEX. Échec = dégâts auto complets.

### Précision

Tu gardes ton arme en tir unique — chaque balle compte.

- **Tir ajusté.** Tes attaques avec des armes en tir unique infligent **+2 dégâts** (+3 au niv. 5, +4 au niv. 9, +5 au niv. 13).
- **Critique amélioré.** Quand tu fais une Réussite critique (Nat 1) avec une arme en tir unique, lance les dés de dégâts **trois fois** au lieu de deux.

> **Design :** Assaut = contrôle de zone, suppression (Secoué). Précision = dégât par balle, élimination ciblée. Les deux sont viables, aucun n'est supérieur. La Doctrine est changeable par Shift Rest — un soldat s'adapte à la mission.

---

## Mécanique de ressource : Élan de Combat

À partir du niveau 2, tu accumules de l'**Élan** pendant un combat. L'Élan alimente tes capacités de Fraternité d'Armes.

**Maximum d'Élan = bonus de proficiency :** 1 (niv 1–5), 2 (niv 6–10), 3 (niv 11–15).

**Tu gagnes 1 Élan quand :**

- Tu touches un ennemi avec une attaque à distance.
- Un allié que tu peux voir tombe à 0 PV.
- Tu réussis un jet de Parade (réaction mêlée).

**Règles :**

- L'Élan non dépensé disparaît à la fin du combat.
- Tu ne peux pas dépasser ton maximum.
- Gagner de l'Élan ne coûte pas d'action.

> **Note :** Élan max 1 aux niveaux 1–5 signifie que tu utilises une capacité Élan 1, puis tu dois retoucher un ennemi avant d'en utiliser une autre. Les capacités Élan 2 sont naturellement verrouillées jusqu'au niveau 6. C'est un gate organique.

---

## Fraternité d'Armes (Arsenal à choix)

Tu choisis des capacités dans cette liste aux niveaux indiqués (6 choix au total sur 15 niveaux). Tu ne peux pas choisir la même capacité deux fois sauf au niv. 14 (Améliorations).

### Élan 0 (passif / gratuit)

**Cadre Solide.** Quand tu utilises une arme à feu à deux mains, tu ne subis aucun Désavantage pour tirer en mouvement.

**Membre de l'Équipe.** 1×/round : quand tu te déplaces, tu peux tirer un allié adjacent avec toi (il se déplace avec toi gratuitement, même distance, même direction).

**Sentinelle.** Tu peux faire des attaques d'opportunité **à distance** (portée courte) quand un ennemi quitte la portée d'un allié adjacent à toi.

### Élan 1

**Feu de Couverture.** Réaction (quand un allié à portée de vue est attaqué) : dépense 1 Élan. L'attaquant subit un **Désavantage** sur son jet d'attaque.

**Spotter.** 1 action : dépense 1 Élan. Désigne un ennemi en ligne de vue. Le prochain allié qui attaque cette cible avant la fin de ton prochain tour a un **Avantage** sur son jet.

**Snap Out Of It.** 1 action : dépense 1 Élan. Retire **1 niveau de Secoué** d'un allié à portée (2 cases). Inutilisable si tu es toi-même Secoué 2+.

**Tir d'Aggro.** 1 action : dépense 1 Élan. Attaque un ennemi. S'il est touché, cet ennemi a un **Désavantage** à toutes ses attaques qui ne t'incluent pas comme cible, jusqu'à la fin de ton prochain tour. Cesse si tu brises la ligne de vue.

**Cauterize.** 1 action : dépense 1 Élan. Un allié adjacent dépense **1 de ses Surges** et récupère sa Valeur de Surge en PV. Ne compte pas comme Second Souffle. 1×/combat par allié.

### Élan 2 (accessibles à partir du niv 6)

**Interception de Tir.** Réaction (quand un allié adjacent subit une attaque à distance) : dépense 2 Élan. Tu prends l'attaque à sa place **et** ton Armure compte double pour cette attaque.

**Tir Coordonné.** 1 action : dépense 2 Élan. Toi et un allié en ligne de vue faites chacun une attaque gratuite contre la même cible. L'allié utilise sa réaction.

**En Avant.** Action libre au début de ton tour : dépense 2 Élan. Toi et tous les alliés à 6 cases peuvent se déplacer de la moitié de leur vitesse gratuitement. 1×/combat.

---

## Progression par niveau

### NIVEAU 1 — Doctrine de Tir, Fraternité d'Armes (1)

**Doctrine de Tir.** Choisis Assaut ou Précision. Changeable pendant un Shift Rest.

**Fraternité d'Armes (1).** Choisis **1** capacité.

**Entraînement Polyvalent.** Tu es proficient avec **toutes les armes à feu**.

---

### NIVEAU 2 — Élan de Combat, Genou à Terre

**Élan de Combat.** Tu gagnes la mécanique d'Élan (max 1).

**Genou à Terre.** Si tu n'as pas bougé ce tour et qu'aucun ennemi n'est en mêlée avec toi, dépense 1 action pour prendre une position stabilisée. Jusqu'au début de ton prochain tour :

- **Avantage** sur toutes tes attaques à distance.
- **+2 Armure** supplémentaire.
- Tu ne peux pas bouger.

---

### NIVEAU 3 — Sous-classe, Fraternité (2)

**Sous-classe.** Choisis entre **Tête de Pont** (tank, aggro) et **Éclaireur** (mobilité, frappes chirurgicales).

**Fraternité d'Armes (2).** Choisis **1** capacité supplémentaire.

---

### NIVEAU 4 — Stat +1, Doctrine améliorée

**Augmentation de stat.** +1 à une stat au choix.

**Doctrine améliorée :**

- *Assaut :* Tir de Saturation amélioré — les cibles qui **réussissent** leur save DEX dans la zone subissent quand même **la moitié des dégâts auto**.
- *Précision :* Quand tu rates un tir d'**1 point** (d20 = Seuil + 1), c'est un touché. Marge d'erreur de 1.

---

### NIVEAU 5 — Double Tap

**Double Tap.** 1×/tour : quand tu touches un ennemi avec une attaque à distance, tu peux immédiatement faire **une attaque gratuite** contre la même cible. Cette attaque a un **Désavantage**.

---

### NIVEAU 6 — Fraternité (3), Vétéran du Terrain

**Fraternité d'Armes (3).** Choisis **1** capacité. Les capacités **Élan 2** sont maintenant accessibles (Élan max passe à 2).

**Vétéran du Terrain.** Tu ignores le terrain difficile. Ton bonus d'Armure de couverture passe de +2 à **+3**.

---

### NIVEAU 7 — Sous-classe capacité

Gain de la capacité de sous-classe de niveau 7.

---

### NIVEAU 8 — Stat +1, Fraternité (4)

**Augmentation de stat.** +1 à une stat au choix.

**Fraternité d'Armes (4).** Choisis **1** capacité.

---

### NIVEAU 9 — Triple Tap

**Triple Tap.** Ton Double Tap s'améliore : l'attaque gratuite n'a **plus de Désavantage**. Si les deux attaques (originale + Double Tap) touchent la même cible, **+1d6 dégâts bonus** sur la deuxième.

---

### NIVEAU 10 — Bouclier Humain, Fraternité (5)

**Bouclier Humain.** Réaction (quand une créature à 1 case est tuée/incapacitée) : tu attrapes le corps comme couverture. Tu bénéficies de **couverture partielle** (+2 Armure, +3 avec Vétéran du Terrain) tant que tu ne bouges pas. Incompatible avec les armes lourdes.

**Fraternité d'Armes (5).** Choisis **1** capacité.

---

### NIVEAU 11 — Sous-classe capacité

Gain de la capacité de sous-classe de niveau 11.

---

### NIVEAU 12 — Stat +1, Doctrine maîtrisée

**Augmentation de stat.** +1 à une stat au choix.

**Doctrine maîtrisée :**

- *Assaut :* Tir de Saturation passe à une **zone de 3×3 cases**. Le bonus de Suppression améliorée passe à **Secoué +2 niveaux**.
- *Précision :* Marge d'erreur passe à **2**. De plus, 1×/Stretch Rest, tu peux transformer un tir raté en **Réussite critique** (critique automatique).

---

### NIVEAU 13 — Quadruple Tap

**Quadruple Tap.** Double Tap peut se déclencher **2×/tour** (sur deux attaques différentes ou la même cible). Les dégâts bonus de Triple Tap s'appliquent à chaque paire.

---

### NIVEAU 14 — Fraternité (6), Améliorations

**Fraternité d'Armes (6).** Choisis **1** capacité. Tu peux aussi reprendre une capacité déjà choisie pour la rendre **améliorée** :

- **Feu de Couverture+** — L'attaquant subit Désavantage **et** −2 dégâts s'il touche quand même.
- **Spotter+** — L'allié bénéficiant de l'Avantage inflige aussi **+1d6 dégâts**.
- **Snap Out Of It+** — Retire **2 niveaux de Secoué**. Portée étendue à 4 cases.
- **Tir d'Aggro+** — Désavantage sur toutes les **actions** (pas seulement attaques). Dure **2 tours**.
- **Cauterize+** — L'allié récupère Valeur de Surge **+½ de ta Valeur de Surge**. 2×/combat par allié.
- **Tir Coordonné+** — Tu peux désigner **2 alliés**. Coûte toujours 2 Élan.

---

### NIVEAU 15 — Soldat Imparable + All In

**Soldat Imparable.** Au début de chaque combat, tu commences avec **Élan = maximum** (pas besoin de le construire). La première fois que tu es réduit à 0 PV dans un combat, tu dépenses automatiquement jusqu'à **3 Surges** (pas d'action). Si tu remontes au-dessus de 0, tu continues normalement. 1×/Shift Rest.

**All In.** 1×/Shift Rest : quand tu touches un ennemi, déclare All In. **Triple les dégâts** de l'attaque (après Armure). L'arme doit être rechargée ensuite (1 action). Si la cible survit, elle est automatiquement **Secoué 3** et subit un jet forcé sur la Table de Blessures Critiques.

> *Niv 15 c'est le couronnement — les deux facettes du Grounder. Soldat Imparable te rend presque impossible à abattre. All In te rend capable de finir n'importe qui. Tu es le point final d'une campagne.*

---

## Sous-classes

### Tête de Pont (Banner Head)

*Tu es le premier à avancer. Les ennemis te voient, te ciblent — c'est exactement ce que tu veux.*

**NIVEAU 3 — Cri de Guerre.**
1×/combat, action libre : tous les ennemis à 6 cases doivent te cibler en priorité jusqu'à la fin de ton prochain tour. Tu gagnes **+2 Armure** pendant l'effet. Bonus permanent : **+5 PV maximum**.

**NIVEAU 7 — Bouclier Vivant.**
Quand tu utilises Interception de Tir (Fraternité), tu ne subis que **la moitié des dégâts**. Ta réaction d'interception ne coûte qu'**une demi-action**.

**NIVEAU 11 — Rempart.**
Aura passive. Alliés à 3 cases : **+1 Armure**. Si tu es en Genou à Terre, le bonus passe à **+2 Armure**.

**NIVEAU 15 — Dernier Debout.**
Quand tu es réduit à 0 PV, tu peux dépenser **toutes tes Surges restantes** d'un coup (pas d'action). Si tu remontes au-dessus de 0, tu continues. 1×/Shift Rest.

> *Combiné avec Soldat Imparable : d'abord les 3 surges automatiques, puis si tu retombes, Dernier Debout vide le reste. Le tank ultime.*

---

### Éclaireur (Pathfinder)

*Tu es en avant du groupe, toujours. Soldat d'abord, fantôme ensuite.*

**NIVEAU 3 — Reconnaissance Avancée.**
Quand tu tires ta carte d'initiative, regarde-la puis décide de la garder ou d'en repiocher une (tu gardes la nouvelle). Tu gagnes proficiency en **Discrétion** et **Survie** (si déjà formé, Avantage permanent sur ces jets).

**NIVEAU 7 — Tir en Mouvement.**
Quand tu te déplaces d'au moins 3 cases avant d'attaquer, ta première attaque ce tour **ignore la couverture partielle** de la cible. Ce déplacement ne provoque pas d'attaques d'opportunité.

**NIVEAU 11 — Fantôme du Terrain.**
Après avoir fait une attaque à distance, tu peux te déplacer de **la moitié de ta vitesse** gratuitement. Pas d'attaque d'opportunité. 1×/tour.

**NIVEAU 15 — Frappe Chirurgicale.**
1×/combat : déclare avant le jet d'attaque. L'attaque a un **Avantage**, ignore **toute l'Armure**, et si elle touche, elle est un **critique automatique** (dégâts normaux + 1 Blessure de Blessures Critiques). Tu dois avoir observé la cible pendant au moins **1 round complet**.

---

## Tableau récapitulatif

| Niv | Prof | Élan Max | Fraternité | Spécial |
|---|---|---|---|---|
| 1 | +1 | — | 1 | Doctrine de Tir, Entraînement Polyvalent |
| 2 | +1 | 1 | 1 | Élan de Combat, Genou à Terre |
| 3 | +1 | 1 | 2 | **Sous-classe** |
| 4 | +1 | 1 | 2 | Stat +1, Doctrine améliorée |
| 5 | +1 | 1 | 2 | **Double Tap** |
| 6 | +2 | 2 | 3 | Vétéran du Terrain, Élan 2 débloqué |
| 7 | +2 | 2 | 3 | **Sous-classe capacité** |
| 8 | +2 | 2 | 4 | Stat +1 |
| 9 | +2 | 2 | 4 | **Triple Tap** |
| 10 | +2 | 2 | 5 | Bouclier Humain |
| 11 | +3 | 3 | 5 | **Sous-classe capacité** |
| 12 | +3 | 3 | 5 | Stat +1, Doctrine maîtrisée |
| 13 | +3 | 3 | 5 | **Quadruple Tap** |
| 14 | +3 | 3 | 6 | Améliorations Fraternité |
| 15 | +3 | 3 | 6 | **Soldat Imparable + All In**, sous-classe couronnement |

---

## Exemple de jeu — Niveau 5 Grounder Assaut

**SGT. VASQUEZ** — Grounder 5, Tête de Pont. STR 10, DEX 11 (après +1 au niv. 4). Prof +1. Fusil d'assaut TL2 +1 (loot). Score de Tir = 11 + 1 + 1 = **13 (65%)**. Doctrine : Assaut. Dégâts fusil 1d8+2, tir auto 1d10+2. Bonus dégâts DEX 11 = +1d4. Armure 5 (gilet balistique). Élan max : 1.

PV : 12 + 4×8 = **44 PV.** Blessures : 12. Surges : 9/jour. Valeur de Surge : 12.

**Round 1 — Ouverture :**
Vasquez utilise **Cri de Guerre** (action libre) → ennemis la ciblent, +2 Armure (total 7).

- Action 1 : tir sur mercenaire (couvert, Armure 5 + 3 couverture = 8). d20 = 5 ≤ 13 → touché. Dégâts 1d8+2+1d4 = 10, − 8 Armure = 2 PV. +1 Secoué (Assaut). **+1 Élan (max atteint).**
- Action 2 : tir. d20 = 9 ≤ 13 → touché. Dégâts 1d8+2+1d4 = 8, − 8 = minimum 1 PV. +1 Secoué (total 2). Élan déjà au max.
- **Double Tap** se déclenche → attaque gratuite avec Désavantage. d20 (2d20 garde haut) = 11 ≤ 13 → touché. Dégâts 1d8+2+1d4 = 7, minimum 1 PV.
- Action 3 : elle dépense 1 Élan → **Spotter** sur l'officier ennemi (Avantage au prochain allié).

**Bilan :** 4+ PV infligés au mercenaire (Secoué 2), Spotter posé sur l'officier, +2 Armure du Cri. Élan revient à 0, il faut retoucher pour recharger.

**Round 2 — Pression :**
Vasquez rate son premier tir (d20 = 15 > 13). Elle choisit de **pousser le jet**. Elle prend la condition **Déstabilisée** (Désavantage sur tous les jets DEX). Relance : d20 = 8 ≤ 13 → touché ! Mais elle a maintenant Désavantage sur ses prochains tirs DEX...

> **C'est la boucle Grounder :** tirer → Élan → soutenir → pousser si nécessaire → payer le prix → continuer.

---

## Interaction avec le loot

Le Grounder est la classe qui profite le plus de la deuxième jambe. Son Score de Tir nu (stat + prof) est modeste — 55% au niv 1, 80% au niv 15. C'est le loot qui le pousse vers l'excellence :

| Loot | Effet sur le Grounder |
|---|---|
| Fusil +1/+2/+3 | Augmente directement le Score de Tir |
| Viseur holographique | +1 Score ou Avantage en conditions spécifiques |
| Armure renforcée | Survie → plus de rounds → plus d'Élan accumulé |
| Stim packs | Déclencheurs de surge supplémentaires en combat |
| Implant cybernétique STR | +1-3 STR → PV, Blessures, Surges, Valeur de Surge augmentent |

Et le Grounder **souffre** quand son loot est dégradé. Un fusil +2 Endommagé tombe à +1. Un implant STR +2 Endommagé tombe à +1 — ça réduit ses PV max, ses Blessures, ses surges, sa Valeur de Surge d'un coup. La rotation du loot crée un cycle de puissance dynamique que la proficiency seule ne peut pas fournir.

---

## Notes de design — v2 → v3

### Ce qui a changé

| Élément | v2 (20 niveaux) | v3 (15 niveaux) | Raison |
|---|---|---|---|
| Niveaux | 20 | **15** | Courbe plus saine, moins de niveaux morts |
| Proficiency | +2 à +6 | **+1 / +2 / +3** | Loot = deuxième jambe de progression |
| Élan max | 2 à 6 | **1 / 2 / 3** | Aligné sur prof. Gate naturelle pour Élan 2 |
| Fraternité picks | 7 | **6** | Ratio préservé (40% vs 35% des niveaux) |
| Augmentations de stat | 4 principales + 4 secondaires | **3 au choix** | Limiter la courbe naturelle, le loot complète |
| Couronnement | Soldat Imparable (17) + All In (20) | **Les deux au niv 15** | Condensé — le couronnement doit être épique |
| Score Tir niv 1 | 12 (60%) | **11 (55%)** | Prof +1 au lieu de +2 — le loot compense |

### Ce qui est identique

Doctrine (Assaut/Précision), Élan comme mécanique de ressource, Fraternité d'Armes comme arsenal à choix, Genou à Terre, progression Double→Triple→Quadruple Tap, 2 sous-classes (Tête de Pont / Éclaireur) avec capacités à 3/7/11/15, Cauterize comme déclencheur de surge, Bouclier Humain, Vétéran du Terrain.

### Interaction avec les 4 autres classes

- **Medic :** Cauterize et les pouvoirs Medic sont tous deux des déclencheurs de surge. Complémentaires.
- **Marshal :** Marshal donne des ordres + déclenche les surges. Grounder fait feu de couverture + spotting. Combo Spotter + ordre Marshal = dévastatrice.
- **Infiltrator :** L'Éclaireur chevauche en mobilité, mais l'Infiltrator a stealth + burst damage. L'Éclaireur est un soldat mobile, pas un fantôme.
- **Tech :** Tech contrôle le terrain avec gadgets/drones, Grounder avec balles/suppression. Le Spotter aide le drone du Tech.
