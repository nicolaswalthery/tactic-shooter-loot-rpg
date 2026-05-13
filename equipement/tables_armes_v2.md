# TABLES D'ARMES — v2

> **Changements v2 :** Intégration du système de bonus numériques (+0 à +3), états de dégradation (Neuf/Endommagé/Détruit), ajout des armes de mêlée, clarification des interactions bonus/attachments/dégradation. Toutes les armes à feu de la v1 sont conservées telles quelles.
>
> **Référence :** Formules canoniques v2, tables de loot v1, design document v4.

---

## 1. BONUS NUMÉRIQUES SUR LES ARMES

### Comment ça marche

Une arme peut avoir un **bonus numérique de +0 à +3**. Ce bonus s'ajoute au **Score d'attaque** du personnage quand il utilise cette arme.

| Arme | Effet du bonus |
|---|---|
| Fusil d'assaut +0 | Score d'attaque normal |
| Fusil d'assaut +1 | Score d'attaque **+1** |
| Fusil d'assaut +2 | Score d'attaque **+2** |
| Fusil d'assaut +3 | Score d'attaque **+3** |

**Le bonus ne modifie PAS les dégâts.** Les dés de dégâts restent ceux de l'arme. Le bonus améliore uniquement la précision (% de toucher). C'est la deuxième jambe de progression — la proficiency monte le Score par paliers, le loot le monte par unités.

### Exemple concret

Grounder niv 5, DEX 11, proficiency +1, fusil d'assaut +1 :
- Score de Tir = DEX (11) + prof (+1) + arme (+1) = **13** → 65% de toucher.
- Sans le fusil +1 : Score = 12 → 60%. Le loot a donné +5% de précision.

### D'où vient le bonus ?

| Source | Bonus typique |
|---|---|
| Arme achetée en magasin | +0 (toujours) |
| Arme trouvée (loot standard) | +0 |
| Arme trouvée (loot rare) | +1 à +2 |
| Arme trouvée (loot légendaire) | +2 à +3 |
| Arme craftée/modifiée par un Tech | +0 à +1 (jet d'Ingénierie) |
| Arme de boss (prise sur le cadavre) | +1 à +2 (au choix du MJ) |

**Le bonus ne se cumule PAS avec les attachments qui donnent un bonus au Score** (ex: Crosse tactique +1). Si tu as un fusil +2 avec une Crosse tactique +1, le Score d'attaque gagne +2 (pas +3). On prend le **plus élevé** entre le bonus de l'arme et le bonus de l'attachment, pas la somme.

> **Pourquoi ?** Pour éviter l'inflation. Le plafond de loot est +3 — si les attachments se cumulent avec le bonus d'arme, un PJ pourrait atteindre +5 ou +6 et trivialiser le jeu. Le bonus d'arme **remplace** le bonus d'attachment au Score.

### Interaction bonus d'arme et attachments

| Attachment | Se cumule avec le bonus d'arme ? |
|---|---|
| **Crosse tactique** (+1 Score) | **Non.** Le plus élevé des deux s'applique. |
| **Lunette** (portée longue sans Désavantage) | **Oui.** C'est un effet de portée, pas un bonus au Score. |
| **Silencieux** (furtivité) | **Oui.** Pas un bonus au Score. |
| **Munitions perforantes** (Pierce +1) | **Oui.** Pierce affecte l'Armure, pas le Score. |
| **Stabilisateur de recul** (Désavantage au save DEX en auto) | **Oui.** Pas un bonus au Score. |
| Tous les autres | **Oui** sauf s'ils donnent explicitement un bonus au Score. |

---

## 2. DÉGRADATION DES ARMES

### Les 3 états

| État | Bonus de l'arme | Propriétés | Effet en jeu |
|---|---|---|---|
| **Neuf** ✓ | Plein (+X) | Fonctionnent | Normal |
| **Endommagé** ⚠ | **÷ 2** (arrondi inf) | Fonctionnent | Échec critique (Nat 20) = l'arme s'enraye. 1 action pour la dégager. |
| **Détruit** ✗ | **0** | Ne fonctionnent plus | Inutilisable. Tirer est impossible. |

**Exemples de bonus dégradés :**

| Arme | Neuf | Endommagé | Détruit |
|---|---|---|---|
| Fusil +0 | +0 | +0 | Inutilisable |
| Fusil +1 | +1 | +0 | Inutilisable |
| Fusil +2 | +2 | +1 | Inutilisable |
| Fusil +3 | +3 | +1 | Inutilisable |

### Comment une arme se dégrade

| Cause | Fréquence | Résultat |
|---|---|---|
| **Push de jet** (joueur choisit) | Chaque session (choix du joueur) | Neuf → Endommagé OU Endommagé → Détruit |
| **Critique ennemi** (Réussite critique) | 1-2× par arc | MJ peut dégrader l'arme au lieu du bonus dégâts |
| **Pouvoir de monstre** (EMP, acide, hack) | Variable | Selon le pouvoir |
| **Environnement** (explosion, chute, submersion) | Rare | Save DEX ou l'arme se dégrade |

### Comment une arme se répare

| Transition | Conditions | Durée | Difficulté |
|---|---|---|---|
| Endommagé → Neuf | Kit d'ingénierie + composants | 1 Stretch | Ingénierie diff 2 |
| Détruit → Endommagé | Kit d'ingénierie + composants + pièces de rechange | 1 Shift | Ingénierie diff 4 |
| Détruit → Neuf | Atelier complet + composants + pièces | 1 Shift + 1 Stretch | Ingénierie diff 5 |

> **Le Tech** réduit ces difficultés de 1 (sous-classe Ingénieur : -1 supplémentaire). Un Tech Ingénieur avec un bon kit peut réparer une arme Endommagée en plein combat (diff 1 au lieu de 2).

### Enrayage (arme Endommagée)

Quand tu tires avec une arme **Endommagée** et que tu fais un **Échec critique (Nat 20)** : l'arme s'**enraye**. Elle est temporairement inutilisable. Débloquer l'arme coûte **1 action** (pas de jet).

Ce n'est pas une dégradation supplémentaire — l'arme reste Endommagée après le déblocage. C'est une pénalité de fiabilité qui rend les armes Endommagées risquées en situation critique.

---

## 3. ARMES À FEU — Tables complètes

> Les tables ci-dessous sont identiques à la v1 pour les armes à feu. Les colonnes Prix et HP restent inchangées.

### PISTOLETS (1 main)

| Nom | TL | Dégâts | Auto | Portée | Prix | HP | Propriétés |
|---|---|---|---|---|---|---|---|
| Revolver | 0 | 1d6 | — | 8 | 150 | 1 | — |
| Pistolet à silex | 0 | 1d8 | — | 5 | 100 | 0 | Lent (1 action pour recharger) |
| Pistolet semi-auto | 1 | 1d6 | — | 10 | 200 | 1 | — |
| Pistolet lourd | 1 | 1d8 | — | 8 | 350 | 1 | — |
| Machine pistol | 1 | 1d4 | 1d6 | 6 | 300 | 1 | Auto-fire |
| Pistolet caseless | 2 | 1d8 | — | 10 | 500 | 2 | — |
| Coil pistol | 3 | 2d4 | — | 12 | 5 000 | 2 | Magnétique |
| Laser pistol | 3 | 1d8 | — | 10 | 6 000 | 2 | Burn 1, Precise 1 |
| Pistolet plasma | 4 | 2d6 | — | 8 | 15 000 | 2 | Burn 2 |
| Rail pistol | 4 | 2d6 | — | 15 | 16 000 | 2 | Magnétique, Pierce 2 |

### SMG (1-2 mains)

| Nom | TL | Dégâts | Auto | Portée | Prix | HP | Propriétés |
|---|---|---|---|---|---|---|---|
| SMG basique | 1 | 1d6 | 1d8 | 10 | 300 | 2 | Auto-fire |
| SMG compact | 1 | 1d4 | 1d6 | 8 | 250 | 1 | Auto-fire, Léger |
| SMG tactique | 2 | 1d6 | 1d8 | 12 | 450 | 2 | Auto-fire, Precise 1 |
| SMG caseless | 2 | 1d8 | 1d10 | 12 | 800 | 2 | Auto-fire |
| Chain SMG | 3 | 2d4 | 2d6 | 10 | 3 000 | 2 | Auto-fire, Magnétique |
| Laser SMG | 4 | 2d6 | 2d8 | 12 | 12 000 | 3 | Auto-fire, Burn 1 |

### FUSILS (2 mains)

| Nom | TL | Dégâts | Auto | Portée | Prix | HP | Propriétés |
|---|---|---|---|---|---|---|---|
| Mousquet | 0 | 1d10 | — | 10 | 100 | 0 | Lent (1 action pour recharger) |
| Fusil à verrou | 0 | 1d8 | — | 30 | 200 | 1 | — |
| Fusil à levier | 1 | 1d8 | — | 30 | 250 | 1 | — |
| Fusil semi-auto | 1 | 1d8 | — | 30 | 300 | 2 | — |
| Fusil d'assaut | 1 | 1d8 | 1d10 | 30 | 350 | 2 | Auto-fire |
| Carabine | 1 | 1d8 | 1d10 | 20 | 300 | 2 | Auto-fire, Compact |
| Fusil caseless | 2 | 1d8 | 1d10 | 30 | 500 | 3 | Auto-fire |
| Fusil de combat avancé | 2 | 1d10 | 1d12 | 30 | 800 | 3 | Auto-fire |
| Fusil magnétique léger | 3 | 2d6 | 2d8 | 30 | 9 000 | 3 | Auto-fire, Magnétique |
| Fusil laser | 3 | 2d6 | — | 30 | 10 000 | 3 | Burn 1, Precise 1 |
| Fusil plasma | 4 | 2d8 | 2d10 | 25 | 25 000 | 3 | Auto-fire, Burn 2 |
| Fusil gauss | 4 | 2d8 | 2d10 | 35 | 28 000 | 3 | Auto-fire, Magnétique, Pierce 2 |
| Fusil à disruption | 5 | 3d6 | — | 20 | 45 000 | 3 | Pierce 3, Vicious 2 |

### FUSILS DE PRÉCISION (2 mains)

| Nom | TL | Dégâts | Auto | Portée | Prix | HP | Propriétés |
|---|---|---|---|---|---|---|---|
| Fusil de chasse | 0 | 1d8 | — | 30 | 200 | 1 | Precise 1 |
| Fusil de sniper basique | 1 | 1d10 | — | 50 | 500 | 2 | Precise 1 |
| Fusil de sniper lourd | 1 | 1d10 | — | 60 | 800 | 2 | Precise 2, Cumbersome 1 |
| Sniper semi-auto | 2 | 1d10 | — | 50 | 1 200 | 3 | Precise 1 |
| Sniper caseless | 2 | 1d12 | — | 60 | 2 000 | 3 | Precise 2 |
| Sniper magnétique | 3 | 2d8 | — | 70 | 15 000 | 3 | Magnétique, Precise 2, Pierce 1 |
| Sniper railgun | 4 | 2d10 | — | 80 | 25 000 | 3 | Magnétique, Precise 2, Pierce 3 |
| Sniper laser longue portée | 4 | 2d8 | — | 100 | 20 000 | 3 | Burn 1, Precise 2, Pierce 1 |

### SHOTGUNS (2 mains)

| Nom | TL | Dégâts | Auto | Portée | Prix | HP | Propriétés |
|---|---|---|---|---|---|---|---|
| Fusil à canon scié | 0 | 1d10 | — | 3 | 150 | 0 | Blast 2, Knockdown |
| Shotgun à pompe | 0 | 1d10 | — | 5 | 300 | 1 | Blast 3, Knockdown |
| Shotgun semi-auto | 1 | 1d10 | — | 6 | 500 | 2 | Blast 3, Knockdown |
| Shotgun de combat | 1 | 1d10 | 1d12 | 6 | 700 | 2 | Auto-fire, Blast 3, Knockdown |
| Shotgun fléchettes | 2 | 1d8 | — | 8 | 900 | 2 | Pierce 2, Vicious 2 |
| Shotgun magnétique | 3 | 2d6 | 2d8 | 8 | 6 000 | 3 | Auto-fire, Blast 3, Magnétique |

### ARMES LOURDES (2 mains, trépied/montée)

| Nom | TL | Dégâts | Auto | Portée | Prix | HP | Propriétés |
|---|---|---|---|---|---|---|---|
| Crankgun (Gatling primitif) | 0 | 1d8 | 1d10 | 20 | 1 000 | 1 | Auto-fire, Cumbersome 2, Lourde |
| Mitrailleuse légère (LMG) | 1 | 1d8 | 1d10 | 30 | 1 500 | 2 | Auto-fire, Cumbersome 1, Lourde, Pierce 1 |
| Mitrailleuse moyenne (MMG) | 1 | 1d10 | 1d12 | 40 | 2 500 | 2 | Auto-fire, Cumbersome 2, Lourde, Pierce 1 |
| Lance-grenades | 1 | Spécial | — | 20 | 1 000 | 1 | Blast 6, Explosive, Lourde |
| Lance-roquettes | 1 | 4d6 | — | 40 | 3 000 | 0 | Breach 1, Lourde, Limited Ammo 1 |
| Mitrailleuse lourde (HMG) | 2 | 1d12 | 2d8 | 50 | 4 000 | 2 | Auto-fire, Cumbersome 3, Lourde, Pierce 2 |
| Laser lourd | 3 | 2d8 | 2d10 | 40 | 15 000 | 3 | Auto-fire, Burn 1, Lourde, Pierce 1 |
| Canon gauss portable | 4 | 2d10 | 2d12 | 60 | 30 000 | 3 | Auto-fire, Cumbersome 3, Lourde, Magnétique, Pierce 3 |
| Canon plasma | 4 | 3d6 | — | 30 | 40 000 | 3 | Blast 6, Breach 2, Burn 2, Lourde |
| Lance-missiles guidé | 3 | 4d8 | — | 80 | 10 000 | 1 | Breach 2, Guided 3, Limited Ammo 1, Lourde |

---

## 4. ARMES DE MÊLÉE — Nouvelle section v2

> **Stat utilisée :** STR pour les armes de mêlée standard. DEX pour les armes avec la propriété **Finesse**.
> **Score de mêlée :** Stat (STR ou DEX) + proficiency + bonus d'arme.
> **Portée :** En cases. "Reach 1" = cases adjacentes. "Reach 2" = 2 cases (armes longues, fouets, etc.).

### Catégories de mêlée

| Catégorie | Mains | Proficiency requise |
|---|---|---|
| **Arme simple de mêlée** | 1 | Armes simples (toutes les classes) |
| **Arme martiale de mêlée** | 1-2 | Armes martiales (Grounder, Infiltrator : 2 au choix, Marshal) |
| **Arme improvisée** | 1-2 | Aucune proficiency (Désavantage si non-proficient) |

### ARMES SIMPLES DE MÊLÉE

| Nom | TL | Dégâts | Reach | Prix | HP | Propriétés |
|---|---|---|---|---|---|---|
| Poing / Bras | — | 1d4 + STR | 1 | — | 0 | — |
| Couteau | 0 | 1d4 | 1 | 50 | 0 | Finesse, Léger |
| Matraque | 0 | 1d4 | 1 | 30 | 0 | Stun 1 (save STR) |
| Batte / Gourdin | 0 | 1d6 | 1 | 20 | 0 | Knockdown |
| Machette | 0 | 1d6 | 1 | 80 | 1 | — |
| Lance / Javelot | 0 | 1d6 | 2 | 60 | 0 | Lancé (portée 6 en lancé) |
| Matraque tactique | 1 | 1d6 | 1 | 150 | 1 | Stun 1 (save STR) |
| Matraque électrique | 2 | 1d6 | 1 | 400 | 1 | Stun 2 (save STR), Lightning |
| Poing cybernétique | 2-4 | 1d6+STR | 1 | Implant | 0 | (bonus selon implant) |

### ARMES MARTIALES DE MÊLÉE

| Nom | TL | Dégâts | Reach | Prix | HP | Propriétés |
|---|---|---|---|---|---|---|
| Lame de combat | 1 | 1d6 | 1 | 200 | 1 | Finesse |
| Épée large / Machete lourde | 0 | 1d8 | 1 | 300 | 1 | — |
| Hache tactique | 1 | 1d8 | 1 | 250 | 1 | Vicious 1 |
| Lame monofilament | 2 | 1d6 | 1 | 2 000 | 1 | Finesse, Pierce 2 |
| Lame vibrante | 3 | 1d8 | 1 | 5 000 | 2 | Pierce 2, Vicious 1 |
| Lame énergétique | 4 | 2d6 | 1 | 15 000 | 2 | Pierce 3, Burn 1 |
| Bouclier anti-émeute | 1 | 1d4 | 1 | 200 | 1 | Bouclier (+2 Armure en mêlée si équipé) |
| Bouclier balistique | 2 | 1d4 | 1 | 600 | 2 | Bouclier (+2 Armure en mêlée, +1 Armure vs tir frontal) |
| Maul / Marteau lourd | 0 | 1d10 | 1 | 250 | 1 | 2 mains, Knockdown, Cumbersome 1 |
| Lance de mêlée longue | 0 | 1d8 | 2 | 150 | 1 | 2 mains |
| Naginata / Hallebarde | 0 | 1d10 | 2 | 400 | 1 | 2 mains, Cumbersome 1 |

### ARMES IMPROVISÉES

| Nom | Dégâts | Reach | Propriétés |
|---|---|---|---|
| Objet léger (bouteille, outil) | 1d4 | 1 | Se brise sur un Échec critique (Nat 20) |
| Objet lourd (chaise, extincteur) | 1d6 | 1 | 2 mains, Knockdown, se brise sur Échec critique |
| Objet tranchant (verre, métal) | 1d4 | 1 | Vicious 1, se brise sur Échec critique |
| Véhicule en mouvement | Spécial | — | Voir règles véhicules |

> **Note :** Les armes improvisées n'ont **pas de bonus numérique** et **0 Hard Points**. Elles se brisent sur un Échec critique et ne peuvent pas être réparées. C'est du jetable.

---

## 5. PROPRIÉTÉS D'ARMES — Référence complète

### Propriétés passives (toujours actives)

| Propriété | Effet |
|---|---|
| **Auto-fire** | L'arme peut tirer en mode automatique (2 actions, save DEX des cibles, Shaken garanti). Utilise la colonne "Auto" pour les dégâts. |
| **Blast X** | Sur un touché, les créatures dans un rayon de X cases de la cible subissent les dégâts de l'arme (save DEX pour annuler). |
| **Bouclier** | Quand équipé dans une main, donne +2 Armure en mêlée. Certains boucliers donnent aussi +1 Armure vs tir frontal. Occupe une main. |
| **Breach X** | Ignore X × 5 points d'Armure. Principalement anti-véhicule. |
| **Burn X** | Sur un touché, la cible prend 1d6 dégâts de feu supplémentaires pendant X rounds (save DEX en début de tour pour éteindre). |
| **Compact** | L'arme est plus courte que la normale. Portée réduite mais pas de Désavantage si un ennemi est adjacent. |
| **Cumbersome X** | Nécessite STR X+8 pour utiliser sans Désavantage. (Cumbersome 1 = STR 9, Cumbersome 2 = STR 10, Cumbersome 3 = STR 11.) |
| **Explosive** | Cible une case, pas une créature. Toutes les créatures dans la zone d'effet font un save DEX. |
| **Finesse** | L'attaquant peut utiliser DEX au lieu de STR pour le Score d'attaque ET le bonus de dégâts. |
| **Guided X** | Si l'attaque rate, l'arme peut retenter au round suivant avec un bonus de +X au jet. |
| **Knockdown** | Sur un touché, la cible fait un save STR ou tombe prone. |
| **Léger** | Peut être utilisé dans chaque main pour le combat à deux armes. |
| **Lent** | Recharger coûte 1 action (au lieu d'être gratuit/inclus). |
| **Limited Ammo X** | L'arme ne contient que X tirs. Recharger coûte 2 actions. |
| **Lourde** | Nécessite trépied/montée ou STR 11+. Désavantage si déplacement ce tour. |
| **Magnétique** | Accélération électromagnétique. Ignore 1 point d'Armure non-métallique (tissus, cuir). |
| **Pierce X** | Les touchés ignorent X points d'Armure de la cible. |
| **Precise X** | Donne +X au Score d'attaque quand on utilise l'action Viser (cumule avec l'Avantage de Viser). |
| **Stun X** | Sur un touché, la cible fait un save STR ou est Staggered pendant **X rounds**. |
| **Vicious X** | Sur un Réussite critique (Nat 1), ajoute +X×10 au jet sur la Table de Blessures Critiques. |

### Types de dégâts

| Type | Description |
|---|---|
| **Piercing** (défaut) | Dégâts balistiques standard. Type par défaut si non spécifié. |
| **Force** | Dégâts énergétiques (laser). |
| **Fire** | Dégâts de feu (plasma, incendiaire). |
| **Lightning** | Dégâts électriques (arc, ion). |
| **Radiant** | Dégâts nucléaires/particules. |
| **Cold** | Dégâts cryogéniques. |
| **Psychic** | Dégâts psychiques (bio-armes). |

---

## 6. HARD POINTS & ATTACHMENTS

Chaque arme a un nombre de **Hard Points (HP)** qui détermine combien de modifications elle peut recevoir. Installer un attachment coûte **1 action hors combat + jet d'Ingénierie (difficulté 2)**.

> **Rappel v2 :** Les attachments qui donnent un bonus au Score d'attaque (ex: Crosse tactique +1) **ne se cumulent pas** avec le bonus numérique de l'arme. On prend le plus élevé des deux.

### Attachments d'armes à feu

| Attachment | HP requis | Prix | Effet |
|---|---|---|---|
| **Bipied** | 1 | 250 | Si prone ou appuyé : annule Cumbersome de l'arme. |
| **Trépied** | 2 | 400 | Annule Cumbersome. L'arme ne peut plus bouger (1 action pour installer/démonter). |
| **Lunette** | 1 | 200 | Tir au-delà de la portée normale sans Désavantage (jusqu'au double de la portée). |
| **Canon rallongé** | 2 | 500 | Portée +10 cases. Ajoute Cumbersome 1. |
| **Canon scié** | 1 | 100 | Portée -50%. L'arme devient Compact. |
| **Silencieux** | 1 | 300 | Les tirs ne révèlent pas automatiquement ta position. Jet de Perception (diff 3) pour localiser le tireur. |
| **Chargeur étendu** | 1 | 150 | Pour les armes Limited Ammo : +50% de capacité (arrondi sup). |
| **Crosse tactique** | 1 | 200 | +1 au Score d'attaque en tir simple (ne cumule pas avec le bonus d'arme). |
| **Stabilisateur de recul** | 1 | 400 | Auto-fire : cibles ont -1 supplémentaire au save DEX. |
| **Munitions perforantes** | 1 | 500 | Ajoute Pierce 1 (ou augmente Pierce existant de 1). |
| **Conversion énergétique** | 2 | Variable | Change le type de dégâts (nécessite TL 3+). |
| **Lance-grenades sous-canon** | 2 | 1 500 | Ajoute un tir de grenade secondaire (Blast 4, 1 action, Limited Ammo 1). |
| **Viseur holographique** | 1 | 500 | Annule le Désavantage pour tirer en mouvement (armes à 2 mains uniquement). |
| **Bayonnette** | 1 | 100 | L'arme peut être utilisée en mêlée : 1d4 dégâts, reach 1. |

### Attachments de mêlée

| Attachment | HP requis | Prix | Effet |
|---|---|---|---|
| **Lame vibro** | 1 | 2 000 | Ajoute Pierce 1 (ou augmente Pierce existant de 1). TL 3+. |
| **Champ énergétique** | 2 | 8 000 | Ajoute Burn 1. TL 4+. |
| **Poignée ergonomique** | 1 | 150 | +1 au Score d'attaque (ne cumule pas avec le bonus d'arme). |
| **Contrepoids** | 1 | 200 | Réduit Cumbersome de 1 (min 0). |
| **Revêtement empoisonné** | 1 | 500 | 3 charges. Sur un touché : cible fait save STR ou empoisonnée 3 rounds. |

---

## 7. EXEMPLES DE FICHES D'ARMES

Voici comment une arme apparaît sur la fiche d'un personnage, avec état de dégradation.

### Exemple 1 : Arme standard de départ

```
FUSIL D'ASSAUT                   +0    ✓ Neuf
TL 1 | 1d8 / Auto 1d10 | Portée 30 | HP: 2
Propriétés: Auto-fire
Attachments: —
→ Score de Tir: DEX + prof + 0
```

### Exemple 2 : Arme rare trouvée en mission

```
FUSIL D'ASSAUT "WRAITH"          +1    ✓ Neuf
TL 2 | 1d10 / Auto 1d12 | Portée 30 | HP: 3
Propriétés: Auto-fire, Silencieux
Attachments: Lunette (portée longue sans Désavantage)
→ Score de Tir: DEX + prof + 1 | Portée effective 60
```

### Exemple 3 : Arme endommagée après un push

```
FUSIL MAGNÉTIQUE "TEMPEST"       +1→+0  ⚠ Endommagé
TL 3 | 2d6 / Auto 2d8 | Portée 30 | HP: 3
Propriétés: Auto-fire, Magnétique
Attachments: Bipied
→ Score de Tir: DEX + prof + 0 (était +1)
→ Sur un Échec critique (Nat 20): s'enraye (1 action pour débloquer)
```

### Exemple 4 : Arme légendaire de boss

```
RAILGUN SNIPER "JUDGMENT"        +2    ✓ Neuf
TL 4 | 2d10 | Portée 80 | HP: 3
Propriétés: Magnétique, Precise 2, Pierce 3, Cumbersome 2
Attachments: —
→ Score de Tir: DEX + prof + 2 (+2 supplémentaire si Viser)
→ Les touchés ignorent 3 points d'Armure + 1 Armure non-métallique
```

### Exemple 5 : Arme de mêlée avec bonus

```
LAME MONOFILAMENT               +1    ✓ Neuf
TL 2 | 1d6 | Reach 1 | HP: 1
Propriétés: Finesse, Pierce 2
Attachments: —
→ Score de Mêlée: DEX + prof + 1 (Finesse)
→ Ignore 2 points d'Armure
```

---

## 8. PROGRESSION DES DÉS PAR TL — Résumé

| TL | Dés typiques (simple) | Dés typiques (auto) | Pénétration d'Armure | Philosophie |
|---|---|---|---|---|
| **0** | 1d6 – 1d10 | 1d8 – 1d10 | Basse | Poudre noire, mécanique simple |
| **1** | 1d6 – 1d10 | 1d8 – 1d12 | Moyenne-basse | Cartouches modernes, semi/auto |
| **2** | 1d8 – 1d12 | 1d10 – 2d8 | Moyenne | Caseless, calibres avancés |
| **3** | 2d4 – 2d8 | 2d6 – 2d10 | Haute (courbe en cloche) | Magnétique, laser, premier plasma |
| **4** | 2d6 – 2d10 | 2d8 – 2d12 | Très haute | Gauss, plasma, rail |
| **5** | 2d8 – 3d6 | 2d10+ | Extrême | Disruption, désintégration |

> **Principe clé :** Le TL augmente la **fiabilité** de la pénétration d'armure (courbe en cloche vs distribution plate), pas un bonus numérique. Un fusil d'assaut TL1 (1d8, moy 4.5) et un fusil magnétique TL3 (2d6, moy 7) n'ont pas le même profil contre une Armure de 5. Le TL1 inflige 0 net ~55% du temps. Le TL3 perce presque toujours. Le bonus numérique (+0 à +3) est séparé et s'ajoute au Score, pas aux dégâts.

---

## 9. ARMES PAR NIVEAU RECOMMANDÉ

Pour faciliter le choix du MJ : quelles armes les PJ devraient-ils avoir à chaque arc ?

### Arc Recrue (niv 1-5)

| Type | Armes typiques | Bonus typique | TL |
|---|---|---|---|
| Arme principale | Fusil d'assaut, carabine, SMG tactique | +0 à +1 | 1-2 |
| Arme secondaire | Pistolet semi-auto, pistolet lourd | +0 | 1 |
| Mêlée | Couteau, matraque, lame de combat | +0 | 0-1 |
| Loot rare (session 3-5) | Fusil caseless +1, pistolet caseless +1 | +1 | 2 |

### Arc Vétéran (niv 6-10)

| Type | Armes typiques | Bonus typique | TL |
|---|---|---|---|
| Arme principale | Fusil de combat avancé, fusil magnétique léger | +1 à +2 | 2-3 |
| Arme secondaire | Pistolet caseless, coil pistol | +0 à +1 | 2-3 |
| Mêlée | Lame monofilament, hache tactique | +1 | 2 |
| Loot rare | Fusil laser +2, sniper magnétique +1 | +2 | 3 |

### Arc Élite (niv 11-15)

| Type | Armes typiques | Bonus typique | TL |
|---|---|---|---|
| Arme principale | Fusil plasma, fusil gauss, fusil à disruption | +2 à +3 | 4-5 |
| Arme secondaire | Rail pistol, laser pistol | +1 à +2 | 3-4 |
| Mêlée | Lame vibrante, lame énergétique | +2 | 3-4 |
| Loot légendaire | Sniper railgun +3, canon gauss +2 | +3 | 4 |

---

## 10. RÉSUMÉ DES INTERACTIONS

### Ce qui s'additionne (cumul)

- Bonus d'arme + proficiency + stat → Score d'attaque total
- Pierce (arme) + Pierce (munitions perforantes attachment) → Pierce total
- Precise (arme) + action Viser (Avantage) → les deux s'appliquent
- Bonus d'arme + Lunette (pas un bonus au Score, c'est un effet de portée)

### Ce qui ne s'additionne PAS (prend le plus élevé)

- Bonus d'arme + Crosse tactique → prend le plus élevé
- Bonus d'arme + Poignée ergonomique → prend le plus élevé
- Bonus d'arme + bonus d'implant DEX → **ça se cumule** (l'implant augmente la stat, pas le bonus d'arme)

### Plafonds

| Donnée | Plafond |
|---|---|
| Bonus d'arme | +3 (maximum absolu) |
| Score d'attaque total | 19 (stat 13 + prof +3 + arme +3) |
| Pierce total | Pas de plafond (mais l'Armure la plus haute du jeu est ~12) |
| Hard Points par arme | Défini par l'arme (0-3) |
