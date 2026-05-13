# CLASSES CORE — Niveaux 1 à 5 (v1)

> **Référence :** Design document v4, formules canoniques v2, classe_grounder_v3.md (template).
> **Scope :** Infiltrator, Medic, Marshal, Tech. Le Grounder est déjà complet (voir classe_grounder_v3.md).
> **Structure commune :** Niv 1 (signature + 1 pick arsenal + passif), Niv 2 (ressource + feature secondaire), Niv 3 (sous-classe + 2e pick), Niv 4 (stat +1 + signature améliorée), Niv 5 (feature majeure).

---
---

# INFILTRATOR — Opérateur clandestin

> *Tu passes où personne ne peut aller. Derrière les lignes ennemies, dans les systèmes de ventilation, entre les faisceaux laser. Tu es un agent de renseignement spécialisé dans l'espionnage, le contre-terrorisme et l'élimination. Ta force, c'est de ne jamais être là où on te cherche. Et quand tu frappes, c'est terminé avant que la cible comprenne ce qui s'est passé.*

---

## Fiche technique

| | |
|---|---|
| **Stat principale** | DEX |
| **Vigueur** | 8 |
| **PV niveau 1** | Vigueur + bonus STR = **7** (STR 7) |
| **PV par niveau (2+)** | ⌈Vig/2⌉ + 1 + bonus STR = **4/niv** (STR 7) |
| **Blessures** | Vigueur + bonus STR = **7** (STR 7). Fixe. |
| **Saves proficients** | DEX, WIT |
| **Armures** | Légères uniquement |
| **Armes** | Armes légères (pistolets, SMG), armes simples de mêlée, 2 armes de mêlée martiales au choix |
| **Compétences** | Discrétion (obligatoire) + 3 parmi : Acrobatie, Athlétisme, Escamotage★, Informatique★, Perception, Intuition, Tromperie |
| **Healing Surges/jour** | 5 + bonus STR = **4** (STR 7) |
| **Surge Value** | Vigueur + bonus STR = **7 PV** (fixe) |

### Score de Tir — Courbe niveaux 1-5

| Niv | DEX | Prof | Loot | Score | % toucher |
|---|---|---|---|---|---|
| 1 | 10 | +1 | +0 | 11 | 55% |
| 3 | 10 | +1 | +0 | 11 | 55% |
| 5 | 11 | +1 | +1 | 13 | 65% |

*L'Infiltrator ne touche pas mieux que les autres — il touche au bon moment.*

### Équipement de départ

- 2 armes légères (valeur ≤ $300 chacune) OU 1 arme légère + 1 arme de mêlée
- 1 armure légère (valeur ≤ $400)
- Kit de crochetage OU kit de déguisement
- Micro-espion + communicateur chiffré

---

## Mécanique signature : Frappe Ciblée

Quand tu attaques un ennemi et que tu remplis **au moins une** des conditions suivantes, tu infliges des **dégâts supplémentaires** :

- Tu as un **Avantage** sur le jet d'attaque (quelle que soit la source).
- La cible n'a **pas encore agi** ce combat (premier round, avant son tour).
- Tu es **Caché** (Hidden) au moment de l'attaque.
- Un allié est **adjacent** à la cible (prise en tenaille).

| Niveau | Dégâts bonus |
|---|---|
| 1-4 | +1d6 |
| 5-8 | +2d6 |
| 9-12 | +3d6 |
| 13-15 | +4d6 |

**Restrictions :**
- 1×/tour uniquement.
- Fonctionne avec les armes à distance ET de mêlée.
- Fonctionne avec les armes légères et les armes de mêlée martiales dans lesquelles tu es proficient.
- Ne fonctionne PAS avec les armes lourdes, fusils d'assaut, ou armes à deux mains (sauf armes légères à 1-2 mains comme les SMG).

> **Design :** C'est le Intended Target d'UM5 + le Sneak Attack classique, unifié. L'Infiltrator ne fait pas beaucoup de dégâts en combat frontal — il fait des dégâts monstrueux au bon moment. La condition "allié adjacent" permet de jouer en mêlée avec le Martial Artist legacy sans forcer le stealth.

---

## Mécanique de ressource : Ombre

À partir du niveau 2, tu accumules des points d'**Ombre** pendant un combat ou une scène d'infiltration. L'Ombre alimente tes Techniques de l'Ombre.

**Maximum d'Ombre = bonus de proficiency :** 1 (niv 1–5), 2 (niv 6–10), 3 (niv 11–15).

**Tu gagnes 1 Ombre quand :**

- Tu **élimines** un ennemi (réduit à 0 PV) avec une Frappe Ciblée.
- Tu réussis un jet de **Discrétion** pour te cacher en combat ou dans une scène tendue.
- Tu réussis un jet d'**Escamotage** sous pression (crochetage en combat, pickpocket, désarmorçage).

**Règles :**

- L'Ombre non dépensée disparaît à la fin du combat/scène.
- Tu ne peux pas dépasser ton maximum.
- Gagner de l'Ombre ne coûte pas d'action.

> **Note :** Ombre max 1 aux niveaux 1–5 signifie que tu tues un ennemi depuis les ombres, dépenses 1 Ombre pour disparaître, puis tu dois tuer ou te cacher à nouveau. Boucle d'embuscade naturelle.

---

## Techniques de l'Ombre (Arsenal à choix)

Tu choisis des techniques dans cette liste aux niveaux indiqués. Tu ne peux pas choisir la même technique deux fois.

### Ombre 0 (passif / gratuit)

**Pas de Loup.** Tu ne subis aucun Désavantage aux jets de Discrétion pour te cacher pendant un combat, même si des ennemis te cherchent activement.

**Ambidextre.** Quand tu attaques avec une arme légère dans chaque main, la deuxième attaque n'a pas de Désavantage (normalement les attaques à deux armes ont Désavantage sur la seconde).

**Sixième Sens.** Tu ne peux pas être surpris. De plus, tu as Avantage sur les jets d'Initiative.

### Ombre 1

**Disparition.** Action libre (après avoir touché ou éliminé un ennemi) : dépense 1 Ombre. Tu fais immédiatement un jet de Discrétion pour te cacher (même en plein combat). Si tu réussis, tu es Caché jusqu'à ton prochain tour.

**Esquive Roulée.** Réaction (quand tu es touché par une attaque) : dépense 1 Ombre. Réduis les dégâts de **1d8 + bonus DEX**. Tu te déplaces de 1 case dans n'importe quelle direction (ne provoque pas d'attaque d'opportunité).

**Frappe Paralysante.** Quand tu touches avec une Frappe Ciblée : dépense 1 Ombre. La cible doit réussir un **save STR** ou être **Staggered** jusqu'à la fin de son prochain tour (perd 1 action).

**Lecture du Terrain.** 1 action : dépense 1 Ombre. Tu identifies la cible la plus dangereuse de la scène (le MJ doit te dire qui a le Score d'attaque le plus élevé). De plus, tu as Avantage sur ta prochaine attaque contre cette cible.

### Ombre 2 (accessibles à partir du niv 6)

*Non détaillées dans cette version — voir extension niv 6-15.*

---

## Progression par niveau

### NIVEAU 1 — Frappe Ciblée, Techniques de l'Ombre (1)

**Frappe Ciblée.** Voir section ci-dessus. +1d6 dégâts bonus.

**Techniques de l'Ombre (1).** Choisis **1** technique.

**Expertise Furtive.** Tu es proficient en Discrétion (déjà inclus), et tes jets de Discrétion bénéficient d'un bonus de **+2** permanent (ceci est un bonus d'expertise, pas un Avantage — il se cumule avec tout).

---

### NIVEAU 2 — Ombre, Esquive Instinctive

**Ombre.** Tu gagnes la mécanique d'Ombre (max 1).

**Esquive Instinctive.** Quand tu ne portes pas d'armure lourde, tu ajoutes la **moitié de ton bonus DEX** (arrondi inf, min 0) à ta valeur d'Armure. Cela représente ton instinct d'esquive.

> *Exemple : DEX 10 (bonus +2). Armure légère 3 + 1 (moitié de +2) = Armure effective 4. Ce n'est pas énorme, mais ça compense la fragilité de l'Infiltrator.*

---

### NIVEAU 3 — Sous-classe, Techniques (2)

**Sous-classe.** Choisis entre **Nettoyeur** (élimination, close-range) et **Fantôme** (infiltration pure, évasion).

**Techniques de l'Ombre (2).** Choisis **1** technique supplémentaire.

#### Sous-classe : Nettoyeur

> *Tu es un tueur professionnel. Chaque élimination est propre, rapide, silencieuse. Tu te spécialises dans l'engagement au contact — pistolet contre la tempe, lame dans le dos. Tu ne laisses pas de témoins.*

**Exécution.** Quand tu touches un ennemi à **2 cases ou moins** avec une Frappe Ciblée, tu peux relancer les dés de dégâts bonus (les d6 de Frappe Ciblée) et garder le meilleur résultat de chaque dé.

**Outils du métier.** Tu es proficient avec les kits de déguisement et les kits d'empoisonneur. Tu peux appliquer un poison sur une arme en 1 action (au lieu d'un Stretch normalement).

#### Sous-classe : Fantôme

> *Tu n'existes pas. Tu ne laisses pas de trace, pas de caméra ne te voit, pas de détecteur ne te repère. Ton objectif est d'entrer et sortir sans que personne ne sache que tu étais là. Et si quelqu'un te repère… tu disparais.*

**Insaisissable.** Quand tu es Caché et qu'un ennemi réussit un jet de Perception pour te repérer, tu peux dépenser ta réaction pour faire un jet de **Discrétion opposé** immédiat. Si tu réussis, tu restes Caché. 1×/round.

**Passe-Partout.** Tu peux traverser l'espace occupé par une créature ennemie sans pénalité de mouvement. De plus, les attaques d'opportunité contre toi ont un **Désavantage**.

---

### NIVEAU 4 — Stat +1, Frappe Ciblée améliorée

**Augmentation de stat.** +1 à une stat au choix.

**Frappe améliorée :**

- *Nettoyeur :* Ta Frappe Ciblée inflige **Shaken +1 niveau** en plus des dégâts bonus (le choc de l'embuscade).
- *Fantôme :* Ta Frappe Ciblée depuis l'état Caché ne te révèle **pas** si tu es à portée longue (au-delà de la portée normale de l'arme). Tu restes Caché après le tir.

---

### NIVEAU 5 — Premier Sang

**Premier Sang.** Au premier round de chaque combat, si tu agis avant ta cible (ta carte d'initiative est inférieure), tu gagnes **1 action supplémentaire** ce tour. Cette action ne peut être utilisée que pour attaquer, se déplacer, ou se cacher.

De plus, ta Frappe Ciblée passe à **+2d6 dégâts bonus**.

> *C'est le Ghost d'UM5 — l'Infiltrator est dévastateur dans les 6 premières secondes d'un combat. Après, il doit se cacher ou mourir.*

---
---

# MEDIC — Soignant de terrain

> *Tu n'es pas un docteur qui pointe au bureau. Tu es le genre de médecin qui rampe sous les tirs pour atteindre un blessé, qui suture une artère sectionnée avec des mains steady au milieu d'une explosion, qui décide en deux secondes qui peut être sauvé et qui ne peut pas. Tu gardes les gens en vie. C'est ton job, et personne d'autre ne peut le faire.*

---

## Fiche technique

| | |
|---|---|
| **Stat principale** | WIT |
| **Vigueur** | 8 |
| **PV niveau 1** | Vigueur + bonus STR = **8** (STR 8) |
| **PV par niveau (2+)** | ⌈Vig/2⌉ + 1 + bonus STR = **5/niv** (STR 8) |
| **Blessures** | Vigueur + bonus STR = **8** (STR 8). Fixe. |
| **Saves proficients** | WIT, EMP |
| **Armures** | Légères uniquement |
| **Armes** | Armes simples, armes légères (pistolets) |
| **Compétences** | Médecine★ (obligatoire) + 3 parmi : Informatique★, Intuition, Investigation, Perception, Persuasion, Sciences★, Survie |
| **Healing Surges/jour** | 6 + bonus STR = **6** (STR 8) |
| **Surge Value** | Vigueur + bonus STR = **8 PV** (fixe) |

### Équipement de départ

- 1 arme légère (valeur ≤ $300)
- 1 armure légère (valeur ≤ $300)
- Kit médical du TL du setting
- Kit pharmaceutique (Drug Kit)
- $200 en équipement non-militaire

---

## Mécanique signature : Premiers Soins

Tu es le **déclencheur de surges** du groupe. Là où les autres classes ne peuvent dépenser leurs surges que via Second Wind ou Stretch Rest, toi tu les actives directement.

**Premiers Soins (1 action) :** Tu touches un allié adjacent. Cet allié dépense **1 de ses Healing Surges** et récupère sa Surge Value en PV **+ ton bonus WIT** en PV supplémentaires.

| Niveau | Bonus du Medic |
|---|---|
| 1-4 | + bonus WIT |
| 5-8 | + bonus WIT + prof |
| 9-12 | + bonus WIT + prof × 2 |
| 13-15 | + bonus WIT + prof × 3 |

**Restrictions :**
- L'allié doit avoir des surges restantes.
- 1 allié par action (pas de soin de zone au niv 1).
- Ne fonctionne pas sur toi-même (tu ne déclenches que les surges des *autres*). Pour te soigner, tu utilises Second Wind comme tout le monde.
- Nécessite un **kit médical** en main ou accessible.

> **Exemple :** Medic niv 1, WIT 10 (bonus +2). Allié Grounder avec Surge Value 12. Le Medic dépense 1 action → le Grounder récupère 12 + 2 = **14 PV**. C'est plus que le Second Wind du Grounder (12 PV, 1×/combat). Et le Medic peut le refaire au prochain tour.

> **Design :** Le Medic rend les surges des autres plus efficaces. Sans Medic, chaque héros ne peut dépenser qu'1 surge par combat (Second Wind) + 1 surge par Stretch. Avec un Medic, les surges coulent. C'est ce qui rend le Medic **indispensable** sans lui donner de pouvoir de combat.

---

## Mécanique de ressource : Triage

À partir du niveau 2, tu accumules des points de **Triage** pendant un combat. Le Triage alimente tes Pratiques Médicales avancées.

**Maximum de Triage = bonus de proficiency :** 1 (niv 1–5), 2 (niv 6–10), 3 (niv 11–15).

**Tu gagnes 1 Triage quand :**

- Tu utilises **Premiers Soins** sur un allié (soigner = Triage).
- Tu **stabilises** un allié Mourant (save Médecine réussi).
- Tu retires une **condition** d'un allié (via soin, médicament ou pouvoir de classe).

**Règles :**

- Le Triage non dépensé disparaît à la fin du combat.
- Tu ne peux pas dépasser ton maximum.
- Gagner du Triage ne coûte pas d'action supplémentaire.

---

## Pratiques Médicales (Arsenal à choix)

### Triage 0 (passif / gratuit)

**Diagnostic Rapide.** Action libre (début de ton tour) : tu connais le pourcentage exact de PV restants de tous les alliés que tu peux voir, et si l'un d'eux est Empoisonné, En Feu, ou infecté.

**Évitement Médical.** Si tu n'as fait **aucune attaque** ce tour, tu gagnes **+2 Armure** jusqu'au début de ton prochain tour. Tu cours, tu esquives, tu soignes — mais tu ne tires pas.

**Mots de Réconfort.** 1 action : tu retires **1 niveau de Shaken** d'un allié adjacent. Pas besoin de Triage, pas besoin de kit. C'est ton calme sous le feu qui rassure.

### Triage 1

**Injection d'Adrénaline.** 1 action : dépense 1 Triage + 1 stim pack. Un allié adjacent récupère sa Surge Value en PV **sans dépenser de Surge**. C'est un soin gratuit, mais ça consomme un stim. 1×/combat par allié.

**Purge Médicale.** 1 action : dépense 1 Triage. Retire **1 condition** (Épuisé, Déstabilisé, Confus, ou Stressé) d'un allié adjacent. Nécessite kit médical.

**Prescription Tactique.** 1 action : dépense 1 Triage. Un allié adjacent gagne **Avantage** sur son prochain save (n'importe lequel) avant la fin de ton prochain tour. Tu l'as préparé — un anti-douleur, un stimulant, un conseil.

**Analyse de Vulnérabilité.** 1 action : dépense 1 Triage. Tu examines un ennemi que tu peux voir. Le MJ doit te révéler **une** de ces informations au choix : PV restants (approximatif), résistances/faiblesses, ou le pouvoir le plus dangereux de la créature.

### Triage 2 (accessibles à partir du niv 6)

*Non détaillées dans cette version.*

---

## Progression par niveau

### NIVEAU 1 — Premiers Soins, Pratiques Médicales (1)

**Premiers Soins.** Voir section ci-dessus.

**Pratiques Médicales (1).** Choisis **1** pratique.

**Formation Scientifique.** Tu es proficient en Médecine (déjà inclus) et en **une compétence★** supplémentaire au choix parmi : Informatique, Sciences, ou Ingénierie. De plus, ton bonus de proficiency est **doublé** pour les jets de Médecine.

---

### NIVEAU 2 — Triage, Évitement

**Triage.** Tu gagnes la mécanique de Triage (max 1).

**Évitement de Terrain.** Quand tu utilises ta **réaction** pour te déplacer (suite à un tir allié, une explosion, un effondrement), tu peux te déplacer de **ta vitesse complète** au lieu de la moitié. De plus, quand tu te déplaces vers un allié à 0 PV ou moins, ce mouvement ne provoque **pas d'attaque d'opportunité**.

> *C'est le Target Avoidance d'UM5 — le Medic est insaisissable non pas parce qu'il combat bien, mais parce qu'il est désespérément nécessaire ailleurs.*

---

### NIVEAU 3 — Sous-classe, Pratiques (2)

**Sous-classe.** Choisis entre **Chirurgien de Terrain** (soins lourds, Blessures) et **Médic de Combat** (soins rapides, peut se battre).

**Pratiques Médicales (2).** Choisis **1** pratique supplémentaire.

#### Sous-classe : Chirurgien de Terrain

> *Tu es un médecin avant tout. La chirurgie de terrain, c'est ton expertise — tu peux refermer une plaie ouverte avec un scalpel improvisé, stabiliser un polytraumatisé avec trois garrots et une prière, et reconnaître un empoisonnement au premier regard.*

**Chirurgie de Terrain.** Pendant un Stretch Rest, tu peux faire un jet de Médecine (diff 3) sur un allié. Succès : l'allié récupère **1d4 Blessures** en plus de sa surge de Stretch. 1×/allié/Shift.

**Diagnostic Avancé.** Quand tu utilises Premiers Soins, tu identifies automatiquement toutes les conditions, poisons et maladies affectant le patient.

#### Sous-classe : Médic de Combat

> *Tu n'es pas le genre à rester à l'arrière. Tu soignes d'une main et tu tires de l'autre. Tu as fait tes classes au milieu des balles, et tu sais que parfois la meilleure façon de sauver un allié, c'est d'abattre celui qui lui tire dessus.*

**Tir de Soutien.** Quand tu utilises Premiers Soins (1 action), tu peux immédiatement faire **1 attaque à distance** gratuite (avec Désavantage) contre un ennemi que tu peux voir. C'est une seule action qui fait les deux.

**Armure de Terrain.** Tu gagnes la proficiency en armure **moyenne**. De plus, ta capacité Évitement Médical (Triage 0) fonctionne même si tu as fait 1 attaque ce tour (au lieu de zéro).

---

### NIVEAU 4 — Stat +1, Premiers Soins améliorés

**Augmentation de stat.** +1 à une stat au choix.

**Soins améliorés :**

- *Chirurgien :* Quand tu utilises Premiers Soins, l'allié soigné gagne **+2 Armure temporaire** pendant 1 round (les bandages tiennent, l'adrénaline stabilise).
- *Médic de Combat :* Quand tu utilises Premiers Soins sur un allié à 0 PV ou moins (Mourant), l'allié se relève avec un **Avantage** sur sa prochaine action (la rage de revenir).

---

### NIVEAU 5 — Protocole d'Urgence

**Protocole d'Urgence.** 1×/combat. Quand un allié que tu peux voir tombe à **0 PV** : tu peux utiliser ta **réaction** pour te déplacer vers lui (jusqu'à ta vitesse complète, pas d'attaque d'opportunité) ET utiliser Premiers Soins immédiatement. Ce soin est **gratuit** — il ne consomme pas l'action de l'allié et ne compte pas comme Second Wind.

De plus, le bonus WIT de tes Premiers Soins passe à **bonus WIT + prof**.

> *C'est LE moment du Medic. Le Grounder s'effondre, le Medic traverse le champ de bataille en sprint, le relève. La table applaudit. C'est pour ça qu'on joue un Medic.*

---
---

# MARSHAL — Commandant de terrain

> *Tu n'es pas le meilleur tireur. Tu n'es pas le plus discret. Mais quand tu parles, les gens écoutent — et quand tu donnes un ordre, l'escouade exécute. Tu es celui qui transforme cinq individus paniqués en une unité de combat. Tu vois le champ de bataille comme un échiquier, tu anticipes les mouvements ennemis avant qu'ils ne se produisent, et tu places tes pièces là où elles seront les plus mortelles.*

---

## Fiche technique

| | |
|---|---|
| **Stat principale** | EMP |
| **Vigueur** | 8 |
| **PV niveau 1** | Vigueur + bonus STR = **9** (STR 9) |
| **PV par niveau (2+)** | ⌈Vig/2⌉ + 1 + bonus STR = **6/niv** (STR 9) |
| **Blessures** | Vigueur + bonus STR = **9** (STR 9). Fixe. |
| **Saves proficients** | STR, EMP |
| **Armures** | Légères, moyennes |
| **Armes** | Armes simples, armes légères (pistolets, SMG), armes longues (fusils) |
| **Compétences** | Tactique★ (obligatoire) + 3 parmi : Athlétisme, Intimidation, Intuition, Perception, Intuition, Persuasion, Tromperie |
| **Healing Surges/jour** | 6 + bonus STR = **7** (STR 9) |
| **Surge Value** | Vigueur + bonus STR = **9 PV** (fixe) |

### Équipement de départ

- 1 arme longue (valeur ≤ $350) OU 1 arme légère + 1 arme de mêlée
- 1 armure moyenne (valeur ≤ $500)
- Radio militaire + jumelles
- Kit de terrain basique

---

## Mécanique signature : Ordre Tactique

Tu donnes des **ordres** à tes alliés en combat. Un Ordre Tactique coûte **1 action** et affecte **1 allié** que tu peux voir et qui peut t'entendre.

Au niveau 1, tu connais **2 ordres** parmi les suivants et tu en apprends de nouveaux au fil des niveaux.

### Ordres de base

**"Bouge !"** L'allié peut immédiatement se déplacer de **la moitié de sa vitesse** (mouvement gratuit, pas d'action de l'allié). Ce déplacement ne provoque pas d'attaque d'opportunité.

**"Concentre ton tir !"** L'allié gagne **Avantage** sur sa prochaine attaque avant la fin de ton prochain tour. Si l'attaque touche, elle inflige **+2 dégâts**.

**"Tiens bon !"** L'allié gagne **+2 Armure** jusqu'au début de ton prochain tour.

**"Relève-toi !"** Si l'allié est Prone, Staggered, ou souffre d'1 niveau de Shaken : il peut immédiatement se relever (gratuit) OU retirer 1 niveau de Shaken. De plus, il gagne **Avantage** sur son prochain save.

**"Couvre-le !"** Désigne un allié. Le prochain ennemi qui attaque cet allié avant la fin de ton prochain tour subit un **Désavantage** sur son attaque. (Tu coordonnes les lignes de feu, pas besoin de tirer toi-même.)

> **Design :** Les ordres sont le cœur du Marshal. 1 action = 1 ordre = 1 allié boosté. Le Marshal ne se bat pas lui-même — il rend tous les autres meilleurs. Avec 3 actions par tour, un Marshal peut donner 3 ordres, ou 2 ordres + 1 tir, ou 1 ordre + 2 tirs. C'est le choix tactique permanent.

---

## Mécanique de ressource : Autorité

À partir du niveau 2, tu accumules de l'**Autorité** pendant un combat. L'Autorité alimente tes Commandements avancés.

**Maximum d'Autorité = bonus de proficiency :** 1 (niv 1–5), 2 (niv 6–10), 3 (niv 11–15).

**Tu gagnes 1 Autorité quand :**

- Un allié **touche** un ennemi suite à un de tes Ordres Tactiques (ton plan a fonctionné).
- Tu réussis un jet d'**EMP** (Persuasion, Intimidation, Intuition) sous pression en scène.
- Un allié que tu peux voir **élimine** un ennemi (tu coordonnes la victoire).

**Règles :**

- L'Autorité non dépensée disparaît à la fin du combat/scène.
- Tu ne peux pas dépasser ton maximum.
- Gagner de l'Autorité ne coûte pas d'action.

---

## Commandements (Arsenal à choix)

### Autorité 0 (passif / gratuit)

**Présence de Commandement.** Tes alliés à 6 cases de toi ont **Avantage** aux jets de sang-froid (Shaken). Tant que le leader est debout, l'escouade tient.

**Évaluation Tactique.** Au début de chaque combat (avant l'initiative), tu peux poser au MJ **une question tactique** à laquelle il doit répondre honnêtement : nombre d'ennemis, position du plus dangereux, meilleure couverture, piège visible.

**Voix qui Porte.** Tes Ordres Tactiques fonctionnent à **12 cases** au lieu de la portée normale de la voix. De plus, tu peux donner des ordres même si un allié ne te voit pas (radio, cri, signal).

### Autorité 1

**Galvanisation.** 1 action : dépense 1 Autorité. Un allié que tu peux voir dépense **1 de ses Healing Surges** et récupère sa Surge Value en PV. C'est le deuxième déclencheur de surges du jeu (avec le Medic). Le Marshal ne soigne pas — il galvanise.

**Ordre Coordonné.** 1 action : dépense 1 Autorité. Donne un Ordre Tactique à **2 alliés** au lieu d'un. Le même ordre s'applique aux deux.

**Repli Tactique.** Réaction (quand un allié à portée est touché par une attaque) : dépense 1 Autorité. L'allié peut immédiatement se déplacer de **sa vitesse complète** sans provoquer d'attaque d'opportunité. Il doit finir son mouvement derrière une couverture ou à plus de 6 cases de l'attaquant.

**Plan B.** 1 action : dépense 1 Autorité. Tous les alliés à 6 cases peuvent immédiatement **relancer** leur jet d'Initiative (en gardant le meilleur résultat). 1×/combat.

### Autorité 2 (accessibles à partir du niv 6)

*Non détaillées dans cette version.*

---

## Progression par niveau

### NIVEAU 1 — Ordres Tactiques, Commandements (1)

**Ordres Tactiques.** Choisis **2 ordres** parmi les ordres de base. Tu en apprendras d'autres en progressant.

**Commandements (1).** Choisis **1** commandement.

**Présence.** Les alliés à 6 cases de toi qui peuvent te voir ou t'entendre ont **+1 au moral** : ils ne fuient pas automatiquement en cas de débandade (PNJ alliés), et les PJ ont Avantage sur les jets contre la peur ou la panique.

---

### NIVEAU 2 — Autorité, Regard de Commandant

**Autorité.** Tu gagnes la mécanique d'Autorité (max 1).

**Regard de Commandant.** 1×/tour, action libre : quand tu regardes un ennemi, tu peux évaluer sa **dangerosité relative** (plus faible, comparable, ou plus fort que ton groupe). Ce n'est pas un jet — c'est ton instinct de commandant.

De plus, tu apprends **1 ordre supplémentaire** de la liste de base.

---

### NIVEAU 3 — Sous-classe, Commandements (2)

**Sous-classe.** Choisis entre **Stratège** (plans, positionnement, contrôle) et **Meneur** (inspiration, morale, galvanisation).

**Commandements (2).** Choisis **1** commandement supplémentaire.

#### Sous-classe : Stratège

> *Tu es un penseur du champ de bataille. Tu vois les angles, les lignes de feu, les zones de danger. Là où d'autres voient le chaos, tu vois des patterns. Ton escouade ne gagne pas parce qu'elle est la plus forte — elle gagne parce qu'elle est au bon endroit au bon moment.*

**Embuscade Planifiée.** Quand tu agis en premier au premier round d'un combat (ta carte d'initiative est la plus basse), tous tes alliés ont **Avantage** sur leur première attaque de ce combat. Tu as planifié ça.

**Lire la Carte.** Tu as Avantage permanent sur les jets de Tactique. De plus, 1×/Stretch, tu peux demander au MJ un **plan tactique** du lieu (sorties, couvertures, angles morts) — même si ton personnage n'a pas physiquement exploré.

#### Sous-classe : Meneur

> *Tu ne diriges pas par la stratégie — tu diriges par l'exemple et par la parole. Quand tu cries un ordre, les gens se surpassent. Quand tu les regardes dans les yeux, ils retrouvent leur courage. Tu es le cœur de l'escouade, pas le cerveau.*

**Cri de Ralliement.** 1 action (pas d'Autorité) : tous les alliés à 6 cases retirent **1 niveau de Shaken**. 1×/combat.

**Galvanisation naturelle.** Quand tu utilises Galvanisation (Autorité 1), l'allié récupère sa Surge Value **+ ton bonus EMP** en PV supplémentaires (comme le bonus du Medic, mais alimenté par le charisme, pas la médecine).

---

### NIVEAU 4 — Stat +1, Ordres améliorés

**Augmentation de stat.** +1 à une stat au choix.

**Ordres améliorés :**

- *Stratège :* Tes Ordres Tactiques ont une portée de **12 cases** (même sans Voix qui Porte). De plus, "Concentre ton tir !" inflige +4 dégâts au lieu de +2.
- *Meneur :* Quand tu donnes un Ordre Tactique, l'allié ciblé gagne aussi **+1 Armure** jusqu'au début de ton prochain tour (en plus de l'effet normal de l'ordre). Ton charisme protège.

Tu apprends **1 ordre supplémentaire** de la liste de base.

---

### NIVEAU 5 — Ordre Décisif

**Ordre Décisif.** 1×/combat. **Action libre** au début de ton tour : tu donnes un ordre spécial. Choisis un allié que tu peux voir. Cet allié peut immédiatement jouer **un tour complet** (3 actions) hors séquence d'initiative. Ce tour est en plus de son tour normal.

Après l'Ordre Décisif, tu ne peux pas donner d'Ordre Tactique ce tour (tu as tout donné dans cet ordre).

> *"MAINTENANT !" Le sniper prend son tir. Le Grounder lance l'assaut. Le Medic sprint vers le blessé. L'Ordre Décisif est le moment où le Marshal transforme la bataille en une seconde. C'est la feature la plus puissante du jeu au niveau 5 — et c'est 1×/combat. Usage wisely.*

---
---

# TECH — Ingénieur de terrain

> *Tu ne tires pas bien. Tu ne te bats pas bien. Mais tu fais voler des drones, tu pirate des systèmes en 30 secondes, tu transformes un grille-pain en détonateur, et tu peux réparer n'importe quoi avec du fil de fer et de la bonne volonté. Le monde moderne est fait de technologie — et la technologie, c'est toi.*

---

## Fiche technique

| | |
|---|---|
| **Stat principale** | WIT |
| **Vigueur** | 6 |
| **PV niveau 1** | Vigueur + bonus STR = **5** (STR 7) |
| **PV par niveau (2+)** | ⌈Vig/2⌉ + 1 + bonus STR = **3/niv** (STR 7) |
| **Blessures** | Vigueur + bonus STR = **5** (STR 7). Fixe. |
| **Saves proficients** | WIT, DEX |
| **Armures** | Légères uniquement |
| **Armes** | Armes simples, armes légères (pistolets) |
| **Compétences** | Ingénierie★ (obligatoire) + 3 parmi : Informatique★, Démolitions★, Investigation, Perception, Pilotage, Sciences★, Survie |
| **Healing Surges/jour** | 4 + bonus STR = **3** (STR 7) |
| **Surge Value** | Vigueur + bonus STR = **5 PV** (fixe) |

### Score d'Ingénierie/Informatique — Courbe niveaux 1-5

| Niv | WIT | Prof | Loot (outil) | Score | % réussite (diff 3) |
|---|---|---|---|---|---|
| 1 | 10 | +1 | +0 | 11 | 40% |
| 3 | 10 | +1 | +1 | 12 | 45% |
| 5 | 11 | +1 | +1 | 13 | 50% |

*Le Tech est meilleur que quiconque dans ses domaines — mais ses domaines sont tous "trained only".*

### Équipement de départ

- 1 arme légère (valeur ≤ $300)
- 1 armure légère (valeur ≤ $300)
- Kit d'ingénierie du TL du setting
- Drone éclaireur (TL2, PV 3, Armure 0)
- $200 en composants divers

---

## Mécanique signature : Drone Compagnon

Tu commences le jeu avec un **drone** que tu as construit ou modifié toi-même. Le drone agit sur tes ordres — il ne pense pas seul.

### Profil du drone de base (niveau 1)

| | |
|---|---|
| **Type** | Éclaireur volant |
| **PV** | 3 + ton bonus WIT par niveau = **5** (WIT 10, niv 1) |
| **Armure** | 0 |
| **Vitesse** | Vol 8 cases |
| **Score d'attaque** | — (pas armé par défaut) |
| **Portée de contrôle** | 100 cases |
| **Capteurs** | Caméra vidéo/audio standard |

### Commandes de drone

Commander ton drone coûte **1 action**. Sans commande, le drone maintient sa dernière instruction (survol, observation, etc.).

**Déplacer.** Le drone se déplace jusqu'à sa vitesse.

**Observer.** Le drone transmet ce qu'il voit/entend. Tu peux utiliser ses capteurs à la place des tiens pour les jets de Perception (tu vois ce que le drone voit).

**Marquer.** Le drone marque une cible visible. Tous tes alliés ont **Avantage** contre la cible marquée jusqu'à la fin de ton prochain tour. 1 cible à la fois.

**Revenir.** Le drone retourne à ta position et se pose sur toi (occupant 0 case).

### Destruction et réparation

- Le drone est un **Minion** : toute blessure critique (Nat 1 d'un ennemi) le détruit.
- Le drone est vulnérable aux **EMP** (détruit automatiquement, sauf upgrade).
- **Réparation (Endommagé → Neuf) :** 1 Stretch + jet d'Ingénierie diff 2 + composants.
- **Reconstruction (Détruit → Endommagé) :** 1 Shift + jet d'Ingénierie diff 4 + composants.
- Si le drone est **définitivement perdu**, tu peux en construire un nouveau avec 1 Shift + matériaux + jet d'Ingénierie diff 3.

> **Design :** Le drone est l'extension du Tech sur le champ de bataille. C'est lui qui donne au Tech de l'utilité en combat sans le mettre en danger. Marquer une cible (Avantage pour tout le groupe) est extrêmement puissant — c'est l'équivalent du Spotter du Grounder, mais sans dépenser de ressource, et à 100 cases de distance.

---

## Mécanique de ressource : Tech Points

Contrairement aux autres classes (ressource gagnée en combat), le Tech a un **pool de Tech Points par Shift**. Tu prépares tes gadgets et solutions à l'avance — en combat, tu les dépenses.

**Tech Points par Shift = 3 + bonus WIT.** (WIT 10 → 5 Tech Points par Shift.)

Les Tech Points se régénèrent sur un **Shift Rest** uniquement.

**Dépenses :**

Les Tech Points alimentent tes **Innovations** (arsenal à choix) et certaines améliorations de ton drone. Chaque Innovation indique son coût en Tech Points.

> **Note design :** Le pool par Shift différencie le Tech des combattants. Le Grounder gagne de l'Élan en se battant — il est meilleur en combat long. Le Tech arrive en combat avec ses points prêts — il est fort dès le début mais s'épuise. Gestion de ressource différente, feeling différent.

---

## Innovations (Arsenal à choix)

### Coût 0 (passif / gratuit)

**Bidouilleur.** Tu peux tenter de **réparer** un objet Endommagé en plein combat (1 action + jet d'Ingénierie diff 3). Succès : l'objet repasse à Neuf. Échec : rien, mais tu peux réessayer au prochain tour.

**Analyse Technologique.** 1 action : tu scannes un objet ou un appareil. Le MJ doit te révéler : son TL, ses qualités/propriétés, son état de dégradation, et son Firewall s'il a un système informatique.

**Interface Drone.** Tu peux utiliser les capteurs de ton drone pour les jets d'Investigation, d'Informatique et d'Ingénierie à distance (le drone doit être sur place).

### Coût en Tech Points

**Tir de Drone (1 TP).** Tu armes temporairement ton drone avec un pistolet intégré pour le combat en cours. Statistiques : 1d4 dégâts, portée 8. Le drone attaque avec **ton Score de WIT** au lieu de DEX. Dure jusqu'à la fin du combat.

**Bouclier Énergétique (1 TP).** 1 action : tu actives un champ de force sur toi ou un allié adjacent. **+3 Armure temporaire**, dure 3 rounds. Le bouclier se brise s'il absorbe plus de 10 dégâts au total.

**Hack Rapide (1 TP).** 1 action : tu piratas un système électronique à portée (terminal, serrure, caméra, communicateur). Jet d'Informatique vs Firewall du système. En combat, tu peux aussi cibler un ennemi avec des cybernétiques — en cas de succès, ses implants dysfonctionnent 1 round (perd les bonus d'implants).

**Surcharge d'Arme (1 TP).** 1 action : tu modifies l'arme d'un allié (ou la tienne) pour le combat en cours. L'arme gagne **+1 au bonus numérique** (temporaire, dure jusqu'à la fin du combat). Ne peut pas dépasser +3 au total.

**Champ de Brouillage (2 TP).** 1 action : tu actives un brouilleur. Toute communication sans fil dans un rayon de 10 cases est coupée pendant 3 rounds. Les drones ennemis dans la zone perdent le contact avec leur contrôleur et maintiennent leur dernière instruction.

---

## Progression par niveau

### NIVEAU 1 — Drone Compagnon, Innovations (1)

**Drone Compagnon.** Tu gagnes ton drone de base (voir section ci-dessus).

**Innovations (1).** Choisis **1** innovation.

**Compétences Techniques.** Tu es proficient en Ingénierie (déjà inclus). Ton bonus de proficiency est **doublé** pour les jets d'Ingénierie. De plus, tes réparations de terrain prennent **moitié moins de temps** (1 Stretch → demi-Stretch, 1 Shift → demi-Shift).

---

### NIVEAU 2 — Tech Points, Bouton Rouge

**Tech Points.** Tu gagnes ta réserve de Tech Points (3 + bonus WIT par Shift).

**Bouton Rouge.** Tu peux **modifier une arme** que tu tiens pendant un Stretch. Choisis un effet parmi :

- L'arme gagne **+2 dégâts** jusqu'au prochain Shift.
- L'arme gagne la propriété **Silencieux** jusqu'au prochain Shift.
- L'arme change de **type de dégâts** (Piercing → Lightning, Fire, etc.) jusqu'au prochain Shift.

1 modification active à la fois par arme. Shift Rest = la modification disparaît.

> *C'est le Shiny Red Button d'UM5 — le Tech bricole un truc sur ton fusil, et maintenant il tire des éclairs. Temporaire, mais cool.*

---

### NIVEAU 3 — Sous-classe, Innovations (2)

**Sous-classe.** Choisis entre **Hacker** (guerre électronique, infiltration numérique) et **Ingénieur** (drones, réparation, crafting).

**Innovations (2).** Choisis **1** innovation supplémentaire.

#### Sous-classe : Hacker

> *Le monde est fait de données. Chaque serrure a un code, chaque caméra a une fréquence, chaque implant a une backdoor. Tu le sais parce que tu les as écrites. Pour toi, le champ de bataille n'est pas un lieu physique — c'est un réseau, et tu en contrôles les nœuds.*

**Intrusion Profonde.** Quand tu réussis un Hack Rapide, tu obtiens un bonus supplémentaire : tu peux **maintenir l'accès** au système pendant 1 Stretch (au lieu d'un effet instantané). Pendant ce temps, tu peux interagir avec le système à distance sans nouveau jet.

**Virus Dormant.** 1×/Shift : quand tu hack un système, tu peux y laisser un **virus dormant**. Tu choisis un déclencheur (timer, présence d'une cible, signal radio). Quand le déclencheur s'active, le système plante pendant 1d4 rounds.

#### Sous-classe : Ingénieur

> *Tu construis des choses. Des drones, des gadgets, des pièges, des bombes, des trucs qui n'ont pas de nom parce que tu viens de les inventer. Donne-toi un tas de ferraille et 15 minutes, et tu en sors quelque chose d'utile. Ou d'explosif. Parfois les deux.*

**Drone Amélioré.** Ton drone de base gagne **+3 PV** et **+1 Armure**. De plus, il résiste aux EMP (save WIT au lieu de destruction automatique).

**Réparation Express.** Tes réparations de terrain (Endommagé → Neuf) ne coûtent plus de composants (tu improvises) et la difficulté est réduite de 1 (diff 2 → diff 1 en atelier, diff 3 → diff 2 sur le terrain).

---

### NIVEAU 4 — Stat +1, Drone/Hack amélioré

**Augmentation de stat.** +1 à une stat au choix.

**Spécialisation :**

- *Hacker :* Ton Score d'Informatique gagne un bonus de **+2** permanent (expertise, comme le Medic en Médecine et l'Infiltrator en Discrétion). De plus, tu réduis le Firewall de toute cible de **1** sur ta première intrusion par Shift.
- *Ingénieur :* Ton drone peut maintenant porter **2 commandes simultanées** (ex: Déplacer + Observer en une seule commande). De plus, tu peux avoir **2 drones actifs** simultanément (le second est un drone de base sans améliorations).

---

### NIVEAU 5 — Innovation Majeure

**Innovation Majeure.** Choisis **une** des innovations majeures suivantes (permanente) :

**Essaim (Ingénieur).** Tu peux fragmenter ton drone en un **essaim de micro-drones** (1 action). L'essaim occupe une zone de Blast 2, dure 3 rounds. Les créatures dans la zone ont **Désavantage** sur les jets de Perception (visuel). Tu peux utiliser l'essaim pour Observer toute la zone. L'essaim a 1 PV total — une attaque de zone le détruit. Après, ton drone est détruit (nécessite reconstruction).

**Intrusion Zero-Day (Hacker).** 1×/Shift, tu peux pirater un système **sans jet**. Tu réussis automatiquement, quel que soit le Firewall. Le MJ décrit les conséquences de l'intrusion comme si tu avais roulé un Réussite critique (Nat 1). C'est ton exploit signature — la porte dérobée que tu as préparée depuis des mois.

**Tourelle Improvisée (Ingénieur).** 1 action + 2 TP : tu déploies une **tourelle automatique** à ta position. La tourelle tire sur l'ennemi le plus proche à chaque round (automatique, pas besoin de commande). Score d'attaque = ton Score WIT. Dégâts : 1d6. PV : 8. Armure : 2. Dure jusqu'à destruction ou fin du combat.

**Contre-mesures Électroniques (Hacker).** Passif : tous les alliés à 6 cases de toi sont **immunisés** aux effets de hacking et de brouillage ennemis. De plus, les drones ennemis dans cette zone ont **Désavantage** sur toutes leurs actions.

> *Le Tech au niveau 5 choisit sa spécialisation définitive. L'Ingénieur contrôle le terrain avec des machines. Le Hacker contrôle le terrain avec de l'information. Les deux sont redoutables — dans leur domaine.*

---
---

# RÉSUMÉ COMPARATIF — Les 5 classes, niveaux 1-5

## Identité de chaque classe

| Classe | Tu es... | En combat, tu... | Ton "moment" |
|---|---|---|---|
| **Grounder** | Le soldat | Tires, supprimes, encaisses | Double Tap — 4e tir gratuit |
| **Infiltrator** | L'ombre | Frappes fort depuis le secret, disparais | Premier Sang — dévastateur au round 1 |
| **Medic** | Le sauveur | Soignes, actives les surges des alliés | Protocole d'Urgence — sprint + soin sur un allié tombé |
| **Marshal** | Le chef | Donnes des ordres, booste tout le monde | Ordre Décisif — un allié joue un tour supplémentaire |
| **Tech** | Le cerveau | Drone, hack, modifie l'équipement | Innovation Majeure — tourelle, essaim ou zero-day |

## Chiffres comparatifs (niveau 5, stats typiques)

| | Grounder | Infiltrator | Medic | Marshal | Tech |
|---|---|---|---|---|---|
| **Vig** | 10 | 8 | 8 | 8 | 6 |
| **PV niv 5** | 44 | 23 | 28 | 33 | 17 |
| **Blessures** | 12 | 7 | 8 | 9 | 5 |
| **Armure typique** | Lourde (8-10) | Légère (3-4) | Légère (3-4) | Moyenne (5-7) | Légère (3) |
| **Surges** | 9 | 4 | 6 | 7 | 3 |
| **Surge Value** | 12 | 7 | 8 | 9 | 5 |
| **DPR solo** | Élevé (Double Tap) | Burst (2d6 Frappe) | Faible | Faible (ordres) | Faible (drone) |
| **Utilité groupe** | Suppression, aggro | Éclairage, élimination | Soins, surge trigger | Ordres, Avantage team | Drone, hack, repair |

## Structure commune 1-5

| Niveau | Ce qui se passe |
|---|---|
| **1** | Mécanique signature + 1 pick d'arsenal + compétence d'expertise |
| **2** | Mécanique de ressource + feature secondaire |
| **3** | Sous-classe (2 choix) + 2e pick d'arsenal |
| **4** | Stat +1 + signature améliorée (selon sous-classe) |
| **5** | Feature majeure de classe (le "moment" iconique) |

## Ressources comparées

| Classe | Ressource | Modèle | Max niv 1-5 | Déclencheurs |
|---|---|---|---|---|
| **Grounder** | Élan | Combat | 1 | Toucher, allié tombe, Parade |
| **Infiltrator** | Ombre | Combat/stealth | 1 | Kill furtif, Discrétion, Escamotage |
| **Medic** | Triage | Combat/soin | 1 | Premiers Soins, stabiliser, retirer condition |
| **Marshal** | Autorité | Combat/social | 1 | Ordre réussi, jet EMP, allié élimine |
| **Tech** | Tech Points | Pool / Shift | 5 (3+WIT) | Shift Rest (rechargement) |

## Sous-classes

| Classe | Option A | Option B |
|---|---|---|
| **Grounder** | Tête de Pont (tank, aggro) | Éclaireur (mobilité, frappes) |
| **Infiltrator** | Nettoyeur (assassin, close-range) | Fantôme (infiltration, évasion) |
| **Medic** | Chirurgien de Terrain (Blessures, soins lourds) | Médic de Combat (tir + soin) |
| **Marshal** | Stratège (plans, positionnement) | Meneur (inspiration, morale) |
| **Tech** | Hacker (guerre électronique) | Ingénieur (drones, crafting) |

## Interaction des rôles — L'escouade idéale

Le système est conçu pour que chaque classe ait besoin des autres :

- Le **Grounder** encaisse et supprime → il a besoin du **Medic** pour régénérer ses surges et du **Marshal** pour le positionner.
- L'**Infiltrator** frappe et disparaît → il a besoin du **Marshal** pour créer des ouvertures et du **Tech** pour désactiver les alarmes.
- Le **Medic** soigne mais ne combat pas → il a besoin du **Grounder** pour le protéger et du **Marshal** pour coordonner les mouvements.
- Le **Marshal** coordonne mais ne produit pas de dégâts → il a besoin du **Grounder** et de l'**Infiltrator** pour exécuter ses ordres.
- Le **Tech** contrôle mais est fragile → il a besoin de **tout le monde** pour le couvrir pendant qu'il hack ou déploie.

> **Le jeu ne marche pas en solo.** C'est voulu. Chaque classe est incomplète seule — c'est l'escouade qui est le personnage.
