# PLAYTEST KIT v2 — Opération Blacksite

> **Version :** v2 (mise à jour complète). 5 pré-tirés niv 3, 6 types d'ennemis, scénario mis à jour, résumé des règles v4.
> **Joueurs :** 3-5 | **Durée :** 2-3h | **Niveau :** 3

---

# PARTIE 1 — RÈGLES RÉSUMÉES POUR LES JOUEURS

## Résolution — Roll-Under d20

**Roule d20. Fais ÉGAL OU INFÉRIEUR au seuil.**

```
Score = Valeur de stat + Proficiency (+1 aux niveaux 1-5)
Seuil = Score - Difficulté (0 en combat)
d20 ≤ Seuil = RÉUSSITE
```

- **Nat 1 = Réussite critique (Critique).** Réussite auto. Attaque → dégâts infligent 1 Blessure + Table de Blessures Critiques.
- **Nat 20 = Échec critique (Fumble).** Échec auto.
- **Avantage :** 2d20, garde le **plus bas** (mieux).
- **Désavantage :** 2d20, garde le **plus haut** (pire).

## Attaque

1. Note ton **Score d'attaque** (stat + prof + bonus d'arme)
2. Difficulté = 0 en combat (pas de défense passive)
3. Roule d20 ≤ Score → Touché
4. Lance les dégâts de l'arme
5. L'**Armure** de la cible réduit les dégâts
6. Le reste frappe les **PV** (ou Blessures si Réussite critique)
7. **Minimum 1 dégât** sur toute attaque réussie, même si l'Armure dépasse

## 3 Actions par tour

Chaque tour = **3 actions.** Exemples :

| Action | Coût |
|---|---|
| Attaquer | 1 action |
| Se déplacer (6 cases) | 1 action |
| Viser (Avantage au prochain tir) | 1 action |
| Sprint (12 cases) | 2 actions |
| Premiers soins | 1 action (Medic) |
| Second Souffle (auto-guérison) | 1 action, 1×/combat |
| Se relever (prone → debout) | 1 action |
| Tir automatique (save DEX des cibles) | 2 actions |
| Hacking — Intrusion | 2 actions |
| Hacking — Contrôle | 1 action |

**Réactions (hors tour) :** Coûtent **1 action de ton prochain tour.** 1×/round par type.

| Réaction | Déclencheur |
|---|---|
| Attaque d'opportunité | Un ennemi quitte ta zone de mêlée |
| Parade (mêlée) | Tu es attaqué en mêlée |
| Interposition | Un allié adjacent est attaqué |

## PV et Blessures

- **PV (Points de Vie)** = Chance, fatigue, éraflures. Se récupèrent via Surges.
- **Blessures** = Blessures réelles. Fixes. Récupération lente.

**Dégâts normaux → PV d'abord.** PV à 0 → **les dégâts restants le personnage est Mourant + 1 Blessure.**
*Exemple : Tu as 14 PV. Tu prends 16 dégâts (après Armure). Tes PV tombent à 0. Tu es Mourant + 1 Blessure.*
**Réussite critique (Nat 1) → infligent 1 Blessure → Blessures direct** + Table de Blessures Critiques.
**PV à 0 → Mourant.** 6 Blessures = mort si pas de soins.

### Mourant (0 Blessures)

Inconscient. Au début de chaque tour, fais un **Blessure (d20 roll-under, seuil 10)** :
- **d20 ≤ 10 :** Réussite. Accumule 1 réussite.
- **d20 > 10 :** Échec. Accumule 1 échec.
- **Nat 1 (Réussite critique) :** Tu te relèves avec **1 PV** et Secoué 2.
- **Nat 20 (Échec critique) :** Compte comme **2 échecs.**
- **3 réussites** = stabilisé (inconscient, 0 Blessures, plus Mourant).
- **3 échecs** = mort.
- Subir des dégâts pendant Mourant = 1 échec auto (réussite critique = 2 échecs).

## Surges

| Méthode | Quand | PV récupérés |
|---|---|---|
| **Second Souffle** | 1 action, 1×/combat | Valeur de Surge |
| **Premiers Soins** (par le Medic) | 1 action | Valeur de Surge + bonus WIT du Medic |
| **Repos court** (1 Stretch = 15 min) | Hors combat | Autant de surges que voulu |
| **Repos long** (1 Shift = 6h) | Hors combat | PV au max, tous les surges reviennent |

**Blessures :** 1 Blessures/jour naturellement. Le Medic peut soigner +1d4 Blessures/patient par Shift.

**Limite :** Max **2 Stretch Rests** entre chaque Shift Rest. Les surges sont précieux — gérez-les.

## Push de jet

Tu rates un jet ? Tu peux **pousser** — relancer le d20 entier.

**Coût (choisis un) :**
- **Condition :** Tu gagnes une condition (Épuisé, Déstabilisé, Confus ou Stressé). Désavantage sur tous les jets de cette stat.
- **Dégradation :** Un de tes équipements se dégrade d'un cran (Neuf → Endommagé → Détruit).

Tu ne peux push **qu'une seule fois** par jet.

## Secoué

**Quand tu es touché** par une attaque (même si l'Armure absorbe tout) → tu gagnes **+1 niveau de Secoué** (max 3). Pas de save pour résister — c'est automatique.

**Au début de ton tour**, si tu es Secoué, fais un **save de sang-froid (STR ou WIT, au choix du joueur).** Pas de difficulté.
- **Réussite :** Tu n'es plus Secoué. Agis normalement.
- **Échec :** Tu subis les effets de ton niveau de Secoué pour ce tour.

**Secoué ne dure jamais plus d'un round.** À la fin de ton tour, ton Secoué se réinitialise à 0, quel que soit le résultat du save. Le compteur repart de zéro à chaque round — seuls les hits reçus **depuis ton dernier tour** comptent.

| Niveau | Effet (si save raté) |
|---|---|
| **Secoué 1** | Désavantage sur tous les jets ce tour |
| **Secoué 2** | Double Désavantage sur tous les jets ce tour |
| **Secoué 3** | Double Désavantage + **1 action en moins** (2 au lieu de 3) |

## Conditions

| Condition | Stat touchée | Effet | Récupération |
|---|---|---|---|
| **Épuisé** | STR | Désavantage sur tous les jets STR | Stretch Rest (1) ou Shift Rest (toutes) |
| **Déstabilisé** | DEX | Désavantage sur tous les jets DEX | Stretch Rest (1) ou Shift Rest (toutes) |
| **Confus** | WIT | Désavantage sur tous les jets WIT | Stretch Rest (1) ou Shift Rest (toutes) |
| **Stressé** | EMP | Désavantage sur tous les jets EMP | Stretch Rest (1) ou Shift Rest (toutes) |

Les conditions se cumulent entre elles et avec Secoué.
**Stretch Rest (15 min) :** Soigne **1 condition** au choix.
**Shift Rest (6h) :** Soigne **toutes** les conditions.

## Couverture

| Type | Effet |
|---|---|
| **Couverture partielle** (muret, voiture) | +2 Armure |
| **Couverture totale** (mur complet) | Pas de ligne de tir (intouchable) |
| **Obscurité / fumée** | Désavantage aux attaques à distance |

## Dégradation d'équipement

| État | Bonus | Effet |
|---|---|---|
| **Neuf** ✓ | Plein | Normal |
| **Endommagé** ⚠ | ÷ 2 (arrondi inf) | Échec critique = enrayage (1 action pour débloquer) |
| **Détruit** ✗ | 0 | Inutilisable |

## Initiative — Cartes

Chaque round : tire une carte numérotée (1-10). Ordre croissant (1 = premier). **Retirage chaque round.**

| Type | Cartes |
|---|---|
| Minion (groupe) | 1 carte pour tous |
| Adversaire | 1 carte chacun |
| Boss | 2+ cartes |

**Surprise :** Tu choisis ta carte au lieu de la tirer.
**Attendre :** Échange ta carte avec quelqu'un qui n'a pas encore agi.

## Hacking (résumé)

**Score Hacking = WIT + prof + bonus deck.** Seuil = Score - Firewall. Même roll-under.

| Action | Coût | Effet |
|---|---|---|
| Scanner | 1 action | Révèle le Firewall et les défenses du système |
| Intrusion | 2 actions | Pénètre le système (jet vs Firewall) |
| Contrôle | 1 action | Ouvrir porte, couper alarme, boucler caméras |
| Sabotage | 2 actions | Détruire données, planter virus, surcharger |
| Prise de contrôle | 2 actions | Prendre le contrôle d'un drone, tourelle, etc. |

---

# PARTIE 2 — LES 5 PRÉ-TIRÉS (Niveau 3)

> **Proficiency :** +1 (niveaux 1-5).
> **Subclass :** Choisie au niveau 3.
> **Ressource :** Max 1 point (niveaux 1-5).
> Chaque personnage a 2 picks d'arsenal.

---

## 1. SGT. ELENA VASQUEZ — Grounder (Tête de Pont)

*"On avance, on sécurise, on survit."*

| STR | DEX | WIT | EMP |
|---|---|---|---|
| **10** | **10** | 8 | 7 |

| Donnée | Valeur |
|---|---|
| PV | **45** (40 base + 5 Tête de Pont) |
| Armure | **8** (armure lourde tactique) |
| Speed | 6 cases |
| Surges | **9/jour** |
| Valeur de Surge | **12 PV** |
| Saves proficients | STR, DEX |

**Score d'attaque :**

| Arme | Stat + Prof + Arme | Score | Dégâts |
|---|---|---|---|
| Fusil d'assaut +1 | DEX 10 + 1 + 1 | **12** (60%) | 1d8 +1d6, Auto 1d10 +1d6. Portée 30. |
| Pistolet | DEX 10 + 1 | **11** (55%) | 1d6 +1d6. Portée 10. |
| Couteau | STR 10 + 1 | **11** (55%) | 1d4 +1d6. Reach 1. |

> *+1d6 = bonus de dégâts (DEX et STR à 10).*

**Capacités de classe :**
- **Élan** (ressource, max 1) — Gagné quand tu touches un ennemi, un allié tombe à 0 PV, ou tu Pares une attaque.
- **Cadre Solide** — Pas de Désavantage pour tirer en mouvement avec arme à 2 mains.
- **Arsenal (2 picks) :**
  - **Feu de Couverture** (1 Élan, réaction) — Quand un allié est attaqué : l'attaquant a Désavantage.
  - **Spotter** (1 Élan, 1 action) — Désigne un ennemi. Le prochain allié qui l'attaque a Avantage.
- **Sous-classe : Tête de Pont** —
  - **Cri de Guerre** (1×/combat, action libre) — Tous les ennemis à 6 cases doivent te cibler en priorité jusqu'à fin de ton prochain tour. Tu gagnes **+2 Armure** pendant l'effet.
  - **+5 PV maximum** (permanent, déjà inclus dans les PV ci-dessus).

**Équipement :**
- Fusil d'assaut TL1 +1 (✓ Neuf) — 1d8 / Auto 1d10, portée 30, HP 2
- Pistolet semi-auto TL1 — 1d6, portée 10
- Couteau de combat — 1d4, reach 1
- Armure lourde tactique (Armure 8)
- Grenades frag ×2 (Zone 4, 2d6, save DEX)
- Kit de premiers soins basique
- Radio tactique

**En combat :** Vasquez est le tank de l'équipe. Cri de Guerre force les ennemis à la cibler (+2 Armure = 10 total), protégeant les alliés fragiles. Feu de Couverture impose Désavantage aux attaquants. 33 PV + Armure 8 = elle encaisse longtemps. Son rôle : absorber l'aggro et permettre aux autres de travailler.

---

## 2. KOFI "GHOST" ASANTE — Infiltrator (Nettoyeur)

*"S'ils m'ont vu, c'est que j'ai voulu qu'ils me voient."*

| STR | DEX | WIT | EMP |
|---|---|---|---|
| 7 | **11** | 9 | 8 |

| Donnée | Valeur |
|---|---|
| PV | **16** |
| Blessures | **7** |
| Armure | **3** (armure légère furtive) |
| Speed | 6 cases |
| Surges | **4/jour** |
| Valeur de Surge | **7 PV** |
| Saves proficients | DEX, WIT |

**Score d'attaque :**

| Arme | Stat + Prof + Arme | Score | Dégâts |
|---|---|---|---|
| Pistolet silencieux | DEX 11 + 1 | **12** (60%) | 1d6 +1d6. Portée 8. Silencieux. |
| Lame de combat | DEX 11 + 1 | **12** (60%) | 1d6 +1d6. Reach 1. Finesse. |

> *+1d6 = bonus de dégâts (DEX 11, Finesse sur la lame).*

**Capacités de classe :**
- **Frappe Ciblée** — +1d6 dégâts bonus quand tu as Avantage, es Caché, agis en premier, ou un allié est adjacent à ta cible.
- **Ombre** (ressource, max 1) — Gagné quand tu élimines un ennemi depuis la furtivité, réussis un jet de Discrétion diff 3+, ou réussis un jet d'Escamotage critique.
- **Arsenal (2 picks) :**
  - **Disparition** (1 Ombre, action bonus) — Deviens Caché même si les ennemis te voient. Dure jusqu'à ta prochaine attaque ou fin du round.
  - **Frappe Paralysante** (1 Ombre, sur touche mêlée) — La cible est Chancelant 1 round (ne peut pas agir, seulement se déplacer). Save STR pour annuler.
- **Sous-classe : Nettoyeur** —
  - **Frappe Létale** — Quand Frappe Ciblée s'active : reroll les 1 et 2 sur les dés de Frappe Ciblée.
  - **Dissimulation de cadavre** — Après une élimination, jet de Discrétion gratuit pour rester caché.

**Équipement :**
- Pistolet silencieux TL1 (✓ Neuf) — 1d6, portée 8, Silencieux
- Lame de combat TL1 — 1d6, reach 1, Finesse
- Armure légère furtive (Armure 3)
- Kit de crochetage électronique
- Fumigènes ×2 (bloque ligne de vue, zone 3×3)
- Corde d'escalade (15m)
- Détecteur de mouvement

**En combat :** Ghost est le plus fragile mais le plus létal en dégâts burst. Frappe Ciblée + Nettoyeur = gros dégâts quand les conditions sont réunies. Disparition lui permet de se cacher en plein combat. Son rôle : éliminer les cibles prioritaires (snipers, hackers, leaders) et flanquer. Il NE DOIT PAS prendre les coups — 15 PV avec Armure 3, c'est papier.

---

## 3. DR. INES PARK — Medic (Chirurgien de Terrain)

*"Garde-le en vie, je m'occupe du reste."*

| STR | DEX | WIT | EMP |
|---|---|---|---|
| 8 | 8 | **11** | 8 |

| Donnée | Valeur |
|---|---|
| PV | **26** |
| Armure | **3** (armure légère) |
| Speed | 6 cases |
| Surges | **6/jour** |
| Valeur de Surge | **8 PV** |
| Saves proficients | WIT, EMP |

**Score d'attaque :**

| Arme | Stat + Prof | Score | Dégâts |
|---|---|---|---|
| Pistolet semi-auto | DEX 8 + 1 | **9** (45%) | 1d6 +1d4. Portée 10. |

**Scores de compétence clés :**

| Compétence | Score |
|---|---|
| Médecine★ | WIT 11 + 1 = **12** |
| Sciences★ | WIT 11 + 1 = **12** |
| Perception | WIT 11 = **11** |
| Persuasion | EMP 8 + 1 = **9** |

**Capacités de classe :**
- **Premiers Soins** (signature, 1 action) — Déclenche le surge d'un allié + bonus WIT (+3) en guérison. L'allié récupère **Valeur de Surge + 3 PV**.
- **Triage** (ressource, max 1) — Gagné quand tu soignes un allié, stabilises quelqu'un à 0 Blessures, ou retires une condition d'un allié.
- **Arsenal (2 picks) :**
  - **Injection d'Adrénaline** (1 Triage, 1 action) — L'allié ciblé gagne +2 actions ce tour et Avantage sur son prochain jet.
  - **Purge Médicale** (1 Triage, 1 action) — Retire 1 condition (Épuisé, Déstabilisé, Confus, Stressé) d'un allié.
- **Sous-classe : Chirurgien de Terrain** —
  - **Opération de Terrain** — Pendant un Stretch, peut soigner Blessures : 1d6 Blessures + bonus WIT par patient. 1×/Shift par patient.
  - **Diagnostic Avancé** — 1 action, gratuit : identifie les PV/Blessures/conditions d'un allié ou ennemi.

**Équipement :**
- Pistolet semi-auto TL1 — 1d6, portée 10
- Armure légère (Armure 3)
- Kit médical de terrain +1 (✓ Neuf) — +1 au Score Médecine = **13** total
- Stim packs ×3 (consommable : déclenche 1 surge immédiatement, sans action)
- Anti-toxine ×2 (consommable : retire poison/infection)
- Radio tactique

**En combat :** Park ne tire pas bien (Score 9). Son rôle est de **maintenir l'équipe en vie**. Premiers Soins (8+3 = 11 PV par surge) est puissant. Injection d'Adrénaline transforme un allié en machine de guerre pendant un tour. En dehors du combat, Opération de Terrain restaure les Blessures — crucial entre les rencontres. Protégez votre Medic.

---

## 4. CPL. YOUSSEF DIALLO — Marshal (Stratège)

*"Tout le monde a un plan jusqu'à ce qu'on se fasse tirer dessus. Moi, j'en ai trois."*

| STR | DEX | WIT | EMP |
|---|---|---|---|
| 9 | 8 | 8 | **11** |

| Donnée | Valeur |
|---|---|
| PV | **30** |
| Armure | **5** (armure moyenne) |
| Speed | 6 cases |
| Surges | **7/jour** |
| Valeur de Surge | **9 PV** |
| Saves proficients | STR, EMP |

**Score d'attaque :**

| Arme | Stat + Prof | Score | Dégâts |
|---|---|---|---|
| Fusil d'assaut | DEX 8 + 1 | **9** (45%) | 1d8 +1d4, Auto 1d10 +1d4. Portée 30. |
| Pistolet lourd | DEX 8 + 1 | **9** (45%) | 1d8 +1d4. Portée 8. |

**Scores de compétence clés :**

| Compétence | Score |
|---|---|
| Tactique★ | EMP 11 + 1 = **12** |
| Persuasion | EMP 11 + 1 = **12** |
| Intimidation | EMP 11 + 1 = **12** |
| Perception | WIT 8 = **8** |

**Capacités de classe :**
- **Ordres Tactiques** (signature, 1 action) — Donne 1 ordre à 1 allié à 6 cases :
  - *"Bouge !"* — L'allié se déplace de 4 cases gratuitement (hors de son tour).
  - *"Concentre ton tir !"* — L'allié a Avantage à sa prochaine attaque.
  - *"Tiens bon !"* — L'allié a Avantage à son prochain save.
  - *"Relève-toi !"* — L'allié à 0 PV peut dépenser 1 surge immédiatement.
  - *"Couvre-le !"* — L'allié peut faire 1 attaque d'opportunité gratuite la prochaine fois qu'un ennemi bouge à portée.
- **Autorité** (ressource, max 1) — Gagné quand un ordre est suivi avec succès (l'allié touche, réussit le save, etc.), quand tu réussis un jet EMP diff 3+, ou quand un allié élimine un ennemi que tu as désigné.
- **Arsenal (2 picks) :**
  - **Galvanisation** (1 Autorité, 1 action) — Tous les alliés à 6 cases récupèrent **1d6 PV** et retirent Secoué 1.
  - **Plan B** (1 Autorité, réaction) — Quand un allié rate un jet : il peut immédiatement relancer (c'est un push gratuit sans coût).
- **Sous-classe : Stratège** —
  - **Embuscade Planifiée** — Au premier round de combat, si le groupe n'est pas surpris : tous les alliés ont Avantage à leur première action.
  - **Lire la Carte** — 1×/combat, réaction : échange la carte d'initiative d'un allié avec celle d'un ennemi.

**Équipement :**
- Fusil d'assaut TL1 — 1d8 / Auto 1d10, portée 30
- Pistolet lourd TL1 — 1d8, portée 8
- Armure moyenne (Armure 5)
- Radio tactique longue portée
- Jumelles tactiques (Avantage Perception à distance)
- Grenades fumigènes ×2 (bloque ligne de vue)
- Balises de marquage ×2 (marque un point pour l'équipe)

**En combat :** Diallo ne tire pas bien (Score 9). Son pouvoir est de **rendre les autres meilleurs**. "Concentre ton tir !" donne Avantage à Vasquez ou Ghost. "Bouge !" repositionne Park hors de danger. Embuscade Planifiée au premier round est dévastateur. Plan B sauve les jets ratés critiques. C'est le cerveau tactique.

---

## 5. MIKA "ZERO" CHEN — Tech (Hacker)

*"Le fusil, c'est TL0. Donne-moi un terminal et 30 secondes."*

| STR | DEX | WIT | EMP |
|---|---|---|---|
| 7 | 8 | **11** | 8 |

| Donnée | Valeur |
|---|---|
| PV | **9** |
| Blessures | **5** |
| Armure | **3** (armure légère) |
| Speed | 6 cases |
| Surges | **3/jour** |
| Valeur de Surge | **5 PV** |
| Saves proficients | WIT, DEX |

**Score d'attaque :**

| Arme | Stat + Prof | Score | Dégâts |
|---|---|---|---|
| Pistolet compact | DEX 8 + 1 | **9** (45%) | 1d6 +1d4. Portée 8. |

**Scores de compétence clés :**

| Compétence | Score |
|---|---|
| Informatique★ | WIT 11 + 1 + 1 (deck) = **13** |
| Ingénierie★ | WIT 11 + 1 = **12** |
| Perception | WIT 11 = **11** |
| Investigation | WIT 11 = **11** |

**Capacités de classe :**
- **Drone Compagnon** — Drone Scout (PV 5, Armure 0, Speed Vol 8, portée contrôle 100 cases). Peut observer, marquer des cibles (Avantage pour le prochain allié), et relayer un lien de hacking.
- **Tech Points** (ressource, pool/Shift = 3 + bonus WIT = **6 TP**) — Ne se regagnent pas en combat. Rechargés au Shift Rest.
- **Arsenal (2 picks) :**
  - **Tir de Drone** (2 TP, 1 action) — Le drone tire : Score WIT 12, dégâts 1d6. Portée 10.
  - **Hack Rapide** (2 TP, 1 action) — Enraye une arme connectée ennemie à 6 cases. Save WIT pour l'ennemi. Échec = arme inutilisable 1 round.
- **Sous-classe : Hacker** —
  - **Intrusion Profonde** — Quand tu réussis une Intrusion : tu peux faire 1 action de Contrôle gratuite immédiatement (en plus des 3 actions du tour).
  - **Virus Dormant** — Quand tu Sabotas un système : tu peux choisir un déclencheur retardé (minuteur, mot-clé, événement) au lieu de l'effet immédiat.

**Équipement :**
- Pistolet compact TL1 — 1d6, portée 8
- Armure légère (Armure 3)
- Deck de hacking amélioré TL3 +1 (✓ Neuf) — Anti-ICE Blanche
- Kit d'ingénierie TL3
- Drone Scout "Pixel" (PV 5, Vol 8, caméra)
- EMP grenade ×1 (Zone 3, désactive électronique 2 rounds)
- Logiciel : Exploit Kit ×1 (Avantage sur 1 jet d'Intrusion)

**Score Hacking effectif : 13** (WIT 11 + prof 1 + deck +1)

**En combat :** Zero est le plus fragile de l'équipe (11 PV, Armure 3, 3 surges). Il DOIT rester en retrait. Son pouvoir : hacker les systèmes ennemis (tourelles, drones, portes), utiliser son drone pour le repérage et le marquage, et fournir du support technique. Intrusion Profonde le rend rapide en hacking (Intrusion + Contrôle gratuit en 2 actions). En urgence, Hack Rapide enraye une arme ennemie. Protégez-le.

---

# PARTIE 3 — ANTAGONISTES

## Catégories d'ennemis — Rappel

| Catégorie | PV/Blessures | Initiative | Danger |
|---|---|---|---|
| **Minion** | 1 touche = mort | 1 carte/groupe | Le nombre |
| **Adversaire** | PV/Blessures normaux | 1 carte chacun | Stats + pouvoirs |
| **Boss** | PV/Blessures ×1.5 | 2+ cartes | Multi-tours + capacités |

---

### GARDE DE SÉCURITÉ — Minion (Recrue)

*Employés sous-payés d'une corpo privée. Pas des héros.*

```
Score Att: 8 | Dégâts: 1d4 (pistolet léger, range 8) | Armure: 2 (gilet de sécurité)
Saves: tous 8 | Speed: 6
Pouvoir: Formation (+1 Armure par allié adjacent, max +3)
```

**Attaque groupée :** 3 gardes sur une cible = 1 attaque à 3d4.

---

### SOLDAT PMC — Minion (Vétéran)

*Soldats privés entraînés. Professionnels mais pas invincibles.*

```
Score Att: 9 | Dégâts: 1d6 (fusil d'assaut, range 12, auto 1d8) | Armure: 4 (gilet tactique)
Saves: tous 8 | Speed: 6
Pouvoir: Tactique de Meute (Avantage si allié adjacent à la cible)
```

---

### MERCENAIRE — Adversaire, Niv 3

*Professionnel. Fiable. Cher.*

```
PV: 13 | 6 | Speed: 6 | Armure: 5 (gilet balistique)
Initiative: 1 carte | Saves: STR 10, DEX 9, WIT 8, EMP 8

ATTAQUE:
  Fusil d'assaut — Score 10 | 1d10+2 (range 12, auto 1d12+2)
  Couteau — Score 10 | 1d4+2 (reach 1)

POUVOIRS:
• Tactique de Meute — Avantage si un allié est adjacent à la cible.
• Retraite Tactique — Fuit sous couvert si PV < 5.
```

---

### SNIPER — Adversaire, Niv 3

*Un tir, une cible. Pas de bavardage.*

```
PV: 11 | 5 | Speed: 6 | Armure: 3 (veste tactique)
Initiative: 1 carte | Saves: STR 8, DEX 11, WIT 9, EMP 8

ATTAQUE:
  Fusil de précision — Score 11 | 1d10+2 (range 20, Précis 1, Perforant 1)

POUVOIRS:
• Tireur Embusqué — Invisible tant qu'il n'a pas tiré. Jet de Discrétion gratuit après chaque tir.
• Repositionnement — Après avoir tiré, se déplace de 3 cases gratuitement.
```

---

### DRONE DE COMBAT — Adversaire (Construct), Niv 2

*Petit, rapide, sans pitié.*

```
PV: 5 | — | Speed: Vol 8 | Armure: 2 (châssis léger)
Initiative: 1 carte | Saves: — (immunisé aux conditions mentales)
Firewall: 3

ATTAQUE:
  Mitrailleuse légère — Score 9 | 1d6 (range 10)

POUVOIRS:
• Vol — Ignore le terrain.
• Piratable — Hacking vs Firewall 3. Succès = drone change de camp.
Vulnérabilité: EMP (détruit automatiquement)
```

---

### TOURELLE AUTOMATIQUE — Adversaire (Construct), Niv 3

*Ne dort pas. Ne rate pas souvent.*

```
PV: 8 | — | Speed: 0 (immobile) | Armure: 6 (blindage)
Initiative: 1 carte | Saves: — (immunisé aux conditions)
Firewall: 4

ATTAQUE:
  Mitrailleuse lourde — Score 10 | 2d6 (range 15, auto 2d8)

POUVOIRS:
• Champ de tir — Cône de 90°. Ne peut tirer que dans son arc.
• Piratable — Hacking vs Firewall 4. Succès = désactivée OU retournée contre les ennemis.
Vulnérabilité: EMP (désactivée 2 rounds)
```

---

### COMMANDANT HARADA — Boss, Niv 4

*Chef de la sécurité de Nexagen BioLab. Ex-militaire. Implant neural de commandement.*

```
PV: 24 | 8 | Speed: 6 | Armure: 6 (armure tactique renforcée)
Initiative: 2 cartes (agit 2×/round) | Saves: STR 10, DEX 9, WIT 9, EMP 12

ATTAQUE:
  Pistolet lourd — Score 11 | 1d8+3 (range 8)
  Matraque électrique — Score 10 | 1d6+3 + Étourdissement 1 (reach 1, Lightning)

POUVOIRS:
• Commandement (1 action) — Tous les alliés à 6 cases gagnent Avantage pendant 1 round.
• Appel de renforts (2 actions, 1×/combat) — 1d4 soldats PMC arrivent en 2 rounds.
• Nerfs d'acier — Avantage aux jets de Secoué.
• Réaction : Riposte — Quand un PJ le rate en mêlée, contre-attaque gratuite.

PHASE 2 (quand PV = 0):
Regagne 15 PV. Sort un fusil d'assaut (Score 11, 1d10+3 auto 1d12+3).
Perd Commandement. Gagne Frénésie (+3 dégâts).

IMPLANT NEURAL: Firewall 5. Si le Tech le hack, l'implant peut être désactivé
(perd Commandement + Appel de renforts). Ou feedback : 1d6 dégâts Lightning.
```

---

# PARTIE 4 — SCÉNARIO : OPÉRATION BLACKSITE

## Briefing

L'escouade est envoyée pour extraire un scientifique retenu dans un laboratoire corporatif clandestin : **Nexagen BioLab**. Le Dr. Yuki Tanaka détient des informations critiques sur un programme d'armes biologiques.

**Objectif principal :** Extraire le Dr. Tanaka vivant.
**Objectif secondaire :** Récupérer les données de recherche depuis le serveur central.

## Le site — Nexagen BioLab

Bâtiment de 2 étages dans une zone industrielle abandonnée.

### Rez-de-chaussée

```
┌─────────────────────────────────────┐
│                                     │
│   PARKING        ENTRÉE             │
│   (sniper a      (porte blindée)    │
│   ligne de tir)      │              │
│                 ┌────┴────┐         │
│                 │ HALL    │         │
│                 │ 2 gardes│         │
│                 │ 1 tourelle        │
│                 └────┬────┘         │
│        ┌─────────────┼──────┐       │
│        │             │      │       │
│   SALLE DES    COULOIR  ENTRÉE      │
│   SERVEURS     (1 merc   SERVICE    │
│   (2 drones)    patrouille)(verrouillée)
│   Terminal FW4         │            │
│        │        ESCALIERS           │
│        └─────────────┘              │
└─────────────────────────────────────┘
```

**Hall d'entrée :** 2 gardes de sécurité (Minions) + 1 tourelle automatique. Terminal de sécurité (Firewall 2) contrôle la tourelle et les portes.

**Couloir principal :** 1 mercenaire en patrouille. Accès aux escaliers.

**Salle des serveurs :** Données de recherche ici. Terminal principal (Firewall 4, Sentinelle Force 3, Porte Force 2). 2 drones de combat.

**Entrée de service :** Porte verrouillée (Discrétion diff 2 pour approcher + Ingénierie diff 2 ou Hacking vs FW 2).

### Premier étage

```
┌─────────────────────────────────────┐
│                                     │
│   POSTE DE         TOIT             │
│   SURVEILLANCE     (accès échelle)  │
│   (caméras)                         │
│        │                            │
│   ┌────┴────────────────────┐       │
│   │ COULOIR 1er ÉTAGE       │       │
│   │ (3 soldats PMC)         │       │
│   └────┬───────┬────────────┘       │
│        │       │                    │
│   LABORATOIRE  BUREAU HARADA        │
│   (Dr. Tanaka) (coffre-fort)        │
│   (Harada +    (système ventilation)│
│    2 gardes)                        │
│                                     │
└─────────────────────────────────────┘
```

**Couloir 1er étage :** 3 soldats PMC (Minions vétérans) en patrouille.

**Laboratoire :** Dr. Tanaka est ici, gardé par le Commandant Harada + 2 gardes de sécurité.

**Bureau de Harada :** Coffre-fort (Ingénierie diff 4 ou Escamotage diff 3). Accès au système de ventilation (passage alternatif vers le labo).

**Toit :** 1 sniper couvre l'entrée principale et le parking. Visible depuis les fenêtres du 1er étage.

## Déroulement

### Phase 1 — Approche (exploration / infiltration)

Les joueurs choisissent comment entrer :

| Approche | Difficulté | Résultat |
|---|---|---|
| Porte principale | Combat direct (hall) | Fort, bruyant |
| Entrée de service | Discrétion diff 2 + Ingénierie diff 2 | Discret, accès couloir |
| Hacking (ouvrir porte service à distance) | Hacking vs Firewall 2 | Discret, à distance |
| Ventilation (depuis le toit) | Athlétisme diff 2 + Discrétion diff 2 | Très discret, accès 1er étage direct |
| Neutraliser le sniper d'abord | Discrétion diff 3 + combat | Élimine la menace du toit |

> **Tip MJ :** Laissez les joueurs planifier. Le Marshal peut utiliser Tactique pour analyser le bâtiment. Le Tech peut scanner les systèmes à distance. L'Infiltrator peut partir en reconnaissance. C'est ici que le jeu d'équipe commence.

### Phase 2 — Rez-de-chaussée (1-2 combats possibles)

**Combat du hall (si approche frontale) :**
- 2 gardes de sécurité (Minions) + 1 tourelle automatique
- La tourelle couvre l'entrée (cône 90°). Contourner par les côtés = hors de l'arc.
- Le Tech peut pirater la tourelle (Hacking vs FW 4) pour la retourner ou la désactiver.
- Si l'alarme sonne → Phase 4 commence plus tôt.

**Le couloir :**
- 1 mercenaire en patrouille. Si l'approche est discrète, l'Infiltrator peut l'éliminer silencieusement (Discrétion vs Perception 8 du merc, puis Frappe Ciblée).

**Salle des serveurs (objectif secondaire) :**
- 2 drones de combat. Le Tech peut hacker (FW 3 chacun) au lieu de combattre.
- Terminal principal FW 4 avec Sentinelle (Force 3) + Porte (Force 2).
- Données de recherche derrière la Porte. Le Tech doit Intrusion (Score 13 vs FW 4 = Seuil 9 → 45%) puis désactiver la Sentinelle (Score 13 vs Force 3 = Seuil 10 → 50%) et la Porte (Score 13 vs Force 2 = Seuil 11 → 55%).
- **Piège :** Les données contiennent un Virus Dormant (Force 3). Si le Tech ne le détecte pas (Hacking vs Force 3), le terminal surcharge (2d6 Lightning, save DEX).

### Phase 3 — Premier étage (combat principal)

**Le couloir du 1er étage :**
- 3 soldats PMC (Minions vétérans). Tactique de Meute = dangereux si les PJ arrivent un par un.
- Le Marshal peut Embuscade Planifiée (Avantage au premier tour pour tous).

**Le laboratoire — Combat du Boss :**
- **Commandant Harada** (Boss niv 4, 2 cartes) + 2 gardes de sécurité (Minions).
- Harada ouvre avec Commandement (Avantage à tous ses alliés).
- Au round 2-3, il Appelle des renforts (1d4 soldats PMC en 2 rounds).
- Si PV tombent à 0 → **Phase 2** : 15 PV, fusil d'assaut, Frénésie. Plus de Commandement — il est devenu un combattant enragé.
- **Option hacking :** Le Tech peut hacker l'implant neural de Harada (FW 5, Score 13 vs FW 5 = Seuil 8 → 40%). Succès = désactive Commandement et Appel de renforts, ou envoie un feedback (1d6 dégâts Lightning).

**Dr. Tanaka :**
- Refuse de partir (veut finir ses recherches). Persuasion diff 3 OU Intimidation diff 4 pour le convaincre.
- Alternative : le Marshal peut utiliser Ordres Tactiques pour le guider ("Bouge !").
- Si les PJ sont sympas + Persuasion réussie : Tanaka donne le code du serveur (objectif secondaire automatique).

### Phase 4 — Exfiltration (sous pression)

L'alarme est déclenchée (automatiquement après Phase 3, ou plus tôt si bruyant).

**Renforts :** 2d4 soldats PMC arrivent par l'entrée principale en 3 rounds.
**Le sniper** (s'il est vivant) couvre le parking — les PJ doivent traverser à découvert.
**Véhicule d'extraction** à 200m au parking.

| Option exfil | Difficulté |
|---|---|
| Sprinter vers le véhicule (sous le feu) | Sprint 2 actions + saves vs sniper |
| Fumigènes (bloquer la ligne de vue du sniper) | Placement tactique (1 action) |
| Hacker le système pour verrouiller les portes derrière eux | Hacking vs FW 2 (ralentit les renforts de 2 rounds) |
| L'Infiltrator élimine le sniper pendant que les autres couvrent | Discrétion diff 3 + attaque |
| Utiliser un drone pour distraire le sniper | Tech Points (2 TP) |

## Twists optionnels

1. **Tanaka ne veut vraiment pas partir** — Il a un plan de fuite propre (cache d'armes dans le labo). Il propose un deal : il vient avec les PJ s'ils détruisent le labo (Sabotage du Tech ou grenades). Dilemme moral : les données sont dans le labo aussi.

2. **Les données sont piégées** — Le virus dans le serveur est un traqueur. Si les PJ copient les données sans le neutraliser, Nexagen peut les tracer. Le Tech doit faire un 2e jet de Hacking pour nettoyer les données (Score 13 vs Force 3).

3. **L'implant de Harada envoie un SOS** — Même si Harada est KO, son implant envoie sa position en continu. Les PJ ont 1 Shift avant qu'une équipe d'extraction corpo arrive (beaucoup plus dangereuse que ce qu'ils ont affronté ici).

## Budget d'ennemis — Résumé

| Phase | Ennemis | Difficulté |
|---|---|---|
| Hall (optionnel) | 2 gardes Minions + 1 tourelle | Facile |
| Serveurs (optionnel) | 2 drones de combat | Facile-Moyen |
| Couloir 1er | 3 soldats PMC Minions | Moyen |
| Labo (boss fight) | Harada (Boss) + 2 gardes + renforts | Difficile |
| Exfil | Sniper + 2d4 soldats PMC Minions | Moyen-Difficile |

**Total si tout combat :** 1 Boss + 1 Adversaire (sniper) + 1 Adversaire (merc) + 2 Adversaires (drones) + 1 Construct (tourelle) + ~12-16 Minions. C'est beaucoup — l'infiltration réduit le nombre de combats.

---

# PARTIE 5 — TABLE DE BLESSURES CRITIQUES (résumée)

Jet : **d100** + 10 par crit déjà subi + Vicieux bonus.

| d100 | Sévérité | Effet rapide |
|---|---|---|
| 01-10 | Mineure | Stress / lâche objet / perd 1 action |
| 11-20 | Mineure | Sonné / Secoué automatique |
| 21-30 | Mineure | Chancelant 1 tour / Désavantage 1 tour |
| 31-40 | Mineure | Douleur vive (diff +2 prochain jet) |
| 41-60 | Modérée | Blessure persistante : Désavantage à 1 stat jusqu'à soins |
| 61-80 | Modérée | Hémorragie (1 Blessures/round, 3 rounds) ou entravé |
| 81-90 | Modérée | Compromis (diff +2 à tout) ou plus de surges |
| 91-100 | Grave | Membre estropié ou 2 Blessures/round jusqu'à soins |
| 101-110 | Grave | Mutilé (perte permanente) ou stat -1 |
| 111-125 | Grave | Aveuglé ou paralysé |
| 126-140 | Dévastatrice | Stat -1 permanent ou hémorragie critique |
| 141-150 | Dévastatrice | Mort en 1 round sans soins (Médecine diff 5) |
| 151+ | Fatale | Mort |

---

# PARTIE 6 — FICHE DE FEEDBACK

Après la session :

1. **Clarté :** Le roll-under était-il intuitif ? Les joueurs ont-ils compris le seuil ?
2. **Rythme du combat :** Combien de rounds en moyenne ? Trop long, trop court ?
3. **PV/Blessures :** La double barre de vie était-elle claire ?
4. **Secoué :** Le mécanisme a-t-il fonctionné ? Trop punitif ? Pas assez ?
5. **Surges :** Les joueurs ont-ils manqué de surges ? Le Medic était-il sollicité ?
6. **Push :** Les joueurs ont-ils pushé ? Le coût (condition/dégradation) semblait-il juste ?
7. **Dégradation :** L'équipement s'est-il dégradé ? Les joueurs ont-ils ressenti la perte ?
8. **Conditions :** Les 4 conditions ont-elles été utilisées ? Claires ?
9. **Hacking :** Le Tech a-t-il hacké ? Fluide ou mini-jeu séparé ?
10. **Ordres du Marshal :** Le joueur du Marshal s'est-il amusé ou s'est-il ennuyé ?
11. **Infiltration :** Le scénario permettait-il des approches variées ?
12. **Équilibre des pré-tirés :** Un personnage trop fort ? Trop faible ?
13. **Boss fight :** Harada était-il mémorable ? Phase 2 a-t-elle fonctionné ?
14. **Le moment le plus fun :** Quelle mécanique a brillé ?
15. **Le moment le moins fun :** Quelle mécanique devrait être retravaillée ?
