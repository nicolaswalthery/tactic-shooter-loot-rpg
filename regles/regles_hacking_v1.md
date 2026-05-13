# RÈGLES DE HACKING — v1

> **Philosophie :** Le hacking utilise les mêmes mécaniques que le combat physique (roll-under, actions, Avantage/Désavantage). Un hacker en pleine intrusion vit la même tension qu'un soldat sous le feu. Les autres PJ ne restent pas les bras croisés pendant que le hacker "fait son truc" — le hacking est intégré au combat et à l'exploration, pas un mini-jeu séparé.
>
> **Sources :** Genesys (FFG) pour la structure actions/programmes/ICE. Shadowrun pour l'ambiance. Notre système roll-under pour la résolution.
>
> **Référence :** Design document v4, formules canoniques v2, classes_core_niv1-5_v1 (Tech/Hacker).

---

## 1. LE PRINCIPE

```
Combat physique : Score d'Attaque vs 0 (difficulté) → Armure absorbe les dégâts
Hacking :          Score de Hacking vs Firewall        → programmes de sécurité bloquent les effets
```

Le **Firewall** est l'équivalent numérique de la difficulté. Le **Score de Hacking** est l'équivalent du Score d'attaque. Le reste fonctionne exactement pareil : roll-under, Réussite critique/Échec critique, Avantage/Désavantage, push.

---

## 2. SCORE DE HACKING

```
Score de Hacking = WIT + proficiency (si proficient en Informatique)
```

**Informatique** est un skill trained-only (★). Un personnage sans formation en Informatique **ne peut pas hacker**. Il peut utiliser un ordinateur normalement (pas de jet), mais toute action de hacking est impossible.

### Modificateurs au Score

| Source | Bonus |
|---|---|
| Bonus de loot (deck/outil de hacking +X) | +X au Score |
| Implant neural (+X WIT ou +X Informatique) | +X au Score |
| Logiciel spécialisé (consommable) | Avantage sur 1 jet |
| Backdoor préinstallée (préparation narrative) | Firewall réduit de 2 |

### Qui peut hacker ?

| Classe | Accès Informatique | Notes |
|---|---|---|
| **Tech** | Oui (proficient dès niv 1) | Classe de hacking par défaut. Sous-classe Hacker = spécialiste. |
| **Infiltrator** | Possible (si Informatique choisi comme skill) | Infiltration numérique secondaire. |
| **Autres classes** | Non (sauf background spécial) | Peuvent utiliser des terminaux déverrouillés, pas hacker. |

---

## 3. FIREWALL — La défense numérique

Le Firewall est un **chiffre fixe** attaché à un système, appareil ou réseau. C'est la difficulté du hacking.

### Table de Firewall

| Niveau de sécurité | Firewall | Exemples |
|---|---|---|
| **Aucune** | 0 | Terminal public, appareil civil non-protégé, IoT bas de gamme |
| **Basique** | 1-2 | Ordinateur personnel, drone commercial, véhicule civil, smartphone |
| **Standard** | 3-4 | Réseau d'entreprise PME, terminal militaire de base, implant standard |
| **Renforcée** | 5-6 | Serveur corpo, drone militaire, système de sécurité d'immeuble |
| **Haute** | 7-8 | Infrastructure critique, réseau militaire classifié, IA défensive |
| **Maximale** | 9-10 | Banque de données top-secret, noyau d'IA souveraine, black-ops |

### Firewall et TL

| TL du système | Firewall typique |
|---|---|
| 0-1 | 0 (pas de systèmes informatiques) |
| 2 | 1-3 |
| 3 | 2-5 |
| 4 | 4-8 |
| 5 | 6-10 |

### Probabilités de succès

Pour référence rapide — Score de Hacking vs Firewall = Seuil :

| Score Hacking | FW 0 | FW 2 | FW 4 | FW 6 | FW 8 |
|---|---|---|---|---|---|
| 10 (niv 1, WIT 9, prof +1) | 50% | 40% | 30% | 20% | 10% |
| 12 (niv 3, WIT 10, prof +1, deck +1) | 60% | 50% | 40% | 30% | 20% |
| 14 (niv 7, WIT 11, prof +2, deck +1) | 70% | 60% | 50% | 40% | 30% |
| 16 (niv 12, WIT 11, prof +3, deck +2) | 80% | 70% | 60% | 50% | 40% |
| 18 (niv 15, WIT 12, prof +3, deck +3) | 90% | 80% | 70% | 60% | 50% |

> **Design :** Un hacker niv 1 peut pénétrer un système basique (FW 2) à 40%. Un hacker niv 15 avec un deck légendaire (+3) peut pénétrer un système haute sécurité (FW 8) à 50%. Les systèmes maximaux (FW 10) restent un défi même pour les meilleurs — c'est voulu.

---

## 4. ACTIONS DE HACKING

Le hacking utilise le même budget de **3 actions par tour** que le combat. Chaque action de hacking a un coût en actions et une résolution.

### Prérequis : Lien au système

Avant toute action de hacking, le personnage doit avoir un **lien** vers le système cible :

| Type de lien | Portée | Coût |
|---|---|---|
| **Filaire** (câble, port USB, terminal) | Contact physique | 1 action pour se brancher |
| **Sans fil** (Wi-Fi, réseau local) | 10 cases (intérieur) / 30 cases (extérieur) | Automatique si à portée |
| **Réseau global** (Internet, satellite) | Illimitée | Nécessite connexion réseau active |
| **Via drone** (drone relais du Tech) | Portée du drone | Le drone doit être à portée filaire ou sans fil du système |

> **Note :** Un Brouilleur (pouvoir ennemi ou gadget) bloque les liens sans fil à 6 cases. En zone brouillée, seul le lien filaire fonctionne.

### Les 7 actions

---

#### SCANNER — 1 action

**Jet :** Aucun (automatique si lié au système).

**Effet :** Le hacker apprend :
- Le **Firewall** du système.
- Le nombre et le type de **programmes de sécurité** actifs (Sentinelle, Porte, ICE — voir section 5).
- Les **nœuds** accessibles (caméras, portes, données, sous-systèmes).
- Si un **opérateur humain** (sysop) surveille le système en temps réel.

> **Le Scanner est gratuit mais essentiel.** Ne pas scanner avant d'intruder, c'est comme charger une pièce sans vérifier les angles. Le MJ révèle la "carte" du système.

---

#### INTRUSION — 2 actions

**Jet :** d20 ≤ (Score de Hacking - Firewall)

**Succès :** Le hacker pénètre le système. Il a maintenant accès aux nœuds non-protégés et peut utiliser les actions Contrôle, Sabotage, Prise de Contrôle.

**Échec :** Le hacker ne pénètre pas. Il peut **réessayer** au tour suivant, mais chaque échec augmente le risque de détection (voir section 6).

**Réussite critique (Nat 1) :** Intrusion parfaite. Le hacker entre sans déclencher aucune alerte. Toutes les Sentinelles sont contournées pour 3 rounds.

**Échec critique (Nat 20) :** Intrusion catastrophique. Le système détecte immédiatement le hacker. Toutes les contre-mesures s'activent. Si un sysop est présent, il connaît la localisation approximative du hacker.

**Push :** Le hacker peut push son jet d'Intrusion. Coût standard : condition (Confus = Désavantage sur WIT) OU dégradation du deck de hacking.

---

#### CONTRÔLE — 1 action (nécessite Intrusion réussie)

**Jet :** Aucun pour les nœuds non-protégés. Jet de Hacking vs Firewall du nœud si protégé par un programme de sécurité.

**Effet :** Le hacker exécute **une commande** sur le système :

| Commande | Effet | Exemples |
|---|---|---|
| **Ouvrir/Fermer** | Active/désactive un élément physique | Porte, écluse, ascenseur, ventilation |
| **Lire** | Accède à des données | Fichiers, emails, plans, caméras de sécurité |
| **Modifier** | Change une donnée ou un paramètre | Faux badge d'accès, effacer un log, modifier un manifeste |
| **Boucler** | Fait tourner un système en boucle | Boucler les caméras (30 secondes de faux feed) |
| **Activer/Désactiver** | Allume/éteint un sous-système | Alarme, éclairage, système d'arrosage, chauffage |

> **1 action = 1 commande.** Le hacker peut dépenser ses 3 actions du tour sur 3 commandes différentes une fois l'Intrusion réussie.

---

#### SABOTAGE — 2 actions (nécessite Intrusion réussie)

**Jet :** d20 ≤ (Score de Hacking - Firewall)

**Succès :** Le hacker détruit, corrompt, ou surcharge un sous-système. L'effet est **permanent** (ou jusqu'à réparation physique).

| Sabotage | Effet |
|---|---|
| **Effacement** | Détruit des données (irréversible sans backup physique) |
| **Virus** | Plante un logiciel malveillant — effet retardé au choix du hacker (bombe logique) |
| **Surcharge** | Force un système à surcharger — dégâts physiques (1d6 Lightning par niv du système) dans un Blast 2 autour de l'appareil |
| **Briquage** | Rend un appareil inutilisable de façon permanente (drone, implant, terminal) |

**Échec :** Le sabotage échoue et le hacker est automatiquement détecté.

**Réussite critique (Nat 1) :** Sabotage propre — aucune trace. Le système ne sait même pas qu'il a été compromis.

---

#### PRISE DE CONTRÔLE — 2 actions (nécessite Intrusion réussie)

**Jet :** d20 ≤ (Score de Hacking - Firewall). Si un **opérateur** contrôle activement l'appareil : **jet opposé** (Score de Hacking du hacker vs Score de Hacking du sysop/opérateur).

**Succès :** Le hacker prend le contrôle total d'un appareil connecté :

| Cible | Ce que le hacker peut faire |
|---|---|
| **Drone** | Le piloter, le faire tirer, le faire se crasher |
| **Tourelle** | Choisir ses cibles (y compris les alliés de l'ennemi) |
| **Véhicule** | Diriger, accélérer, freiner, verrouiller les portes |
| **Implant** | Désactiver ses fonctions, envoyer un feedback douloureux (1d6 dégâts Lightning) |
| **Système de sécurité** | Ouvrir toutes les portes, couper les alarmes, activer le confinement |
| **Exo-armure** | Verrouiller les servos (cible Immobilisée), ou forcer l'éjection |

**Durée :** La prise de contrôle dure tant que le hacker **maintient le lien** (pas besoin de jet supplémentaire). Si le lien est coupé (brouilleur, câble arraché, hacker assommé), le contrôle est perdu. L'appareil revient à son opérateur d'origine ou en mode par défaut.

**Jet opposé :** Si l'appareil a un opérateur actif, les deux font un jet de Hacking. Le plus bas gagne (roll-under). En cas d'égalité, le défenseur (opérateur d'origine) garde le contrôle.

---

#### MASQUER — 1 action (nécessite Intrusion réussie)

**Jet :** d20 ≤ (Score de Hacking - Firewall ÷ 2, arrondi sup)

**Succès :** Le hacker efface ses traces dans le système. Il ne peut plus être détecté par les programmes de sécurité Sentinelle jusqu'à sa prochaine action de hacking.

**Échec :** L'action est gaspillée et la tentative de masquage est elle-même détectée (le système sait que quelqu'un essaie de se cacher).

> **Masquer est l'équivalent numérique de se cacher en combat.** Un bon hacker alterne entre actions offensives et Masquer pour éviter le lockout.

---

#### DÉFENDRE — 1 action (sysop uniquement)

**Jet :** Automatique.

**Effet :** Le sysop (gardien du système) peut effectuer **une** des actions défensives suivantes :

| Défense | Effet |
|---|---|
| **Tracer** | Jet opposé Hacking vs Hacking. Succès = le sysop apprend un échelon de localisation du hacker (pays → région → ville → adresse exacte). Chaque trace réussie réduit la difficulté du Lockout de 1. |
| **Lockout** | Jet de Hacking diff = 8 - nombre de traces réussies (min 1). Succès = le hacker est éjecté du système. Le Firewall augmente de +2 pour la prochaine tentative d'intrusion. |
| **Activer ICE** | Active un programme ICE inactif (voir section 5). |
| **Réparer** | Restaure un programme de sécurité désactivé par le hacker. |

> **Le sysop est l'ennemi du hacker.** Dans une rencontre de hacking, le sysop a son propre tour d'initiative et dépense ses actions pour tracer, verrouiller, et activer les défenses. C'est un duel.

---

## 5. PROGRAMMES DE SÉCURITÉ

Les programmes de sécurité sont les défenses automatiques d'un système. Ils fonctionnent sans sysop (bien qu'un sysop puisse les réactiver s'ils sont désactivés).

Chaque programme a une **Force** (difficulté pour le désactiver) et un **effet** (ce qui arrive si le hacker ne le désactive pas ou échoue).

### Désactiver un programme

**Jet :** d20 ≤ (Score de Hacking - Force du programme)

**Succès :** Le programme est désactivé pendant **3 rounds**. Le hacker (ou un sysop) peut le réactiver ensuite.

**Échec :** L'effet du programme s'active contre le hacker.

### Programmes standards

---

#### PORTE (Gate) — Force 2

**Fonction :** Authentification. Protège l'accès à une zone du système (données classifiées, contrôle physique, sous-réseau).

**Effet si échec de désactivation :** Le hacker est **éjecté de la zone protégée** (pas du système entier). Il doit réessayer au tour suivant.

**Effet si ignoré :** Le hacker ne peut tout simplement pas accéder à la zone protégée.

---

#### SENTINELLE (Sentry) — Force 3

**Fonction :** Détection. Surveille les activités suspectes dans le système.

**Effet si échec de désactivation :** Le sysop (ou le système automatisé) est **immédiatement alerté** de la présence du hacker. Le sysop gagne automatiquement **1 trace** gratuite.

**Effet si ignoré :** Chaque action de hacking dans la zone surveillée déclenche un **jet de détection** automatique (voir section 6).

> **Design :** La Sentinelle est le programme le plus courant. La plupart des systèmes en ont au moins une. La désactiver est la première priorité d'un hacker discret.

---

#### PARE-FEU INTERNE (Firewall) — Force 3-5

**Fonction :** Barrière interne. Sépare les zones du système — le hacker doit le traverser pour atteindre les zones sensibles.

**Effet si échec de désactivation :** Le hacker est **repoussé** à la zone précédente. Pas de dégâts, mais il perd ses actions.

**Effet si ignoré :** Le sous-réseau protégé est inaccessible.

> **Note :** Le Firewall interne a une Force séparée du Firewall principal du système. Un système peut avoir Firewall 4 à l'entrée et un Pare-feu interne de Force 5 protégeant les données les plus sensibles.

---

#### ICE (Intrusion Countermeasure Electronics) — Force 4-6

**Fonction :** Contre-attaque offensive. L'ICE **attaque le hacker** (dégâts au deck) ou le **paralyse** (perd des actions).

**Variantes d'ICE :**

| Type | Force | Effet si échec |
|---|---|---|
| **ICE Blanche** | 4 | Le hacker perd **2 actions** au prochain tour (système ralenti, lag). |
| **ICE Grise** | 5 | Le deck du hacker subit une **dégradation** (Neuf → Endommagé ou Endommagé → Détruit). |
| **ICE Noire** (Black ICE) | 6 | **Feedback neural** : le hacker subit **2d6 dégâts Lightning** directement (PV). Si le hacker a un implant neural, les dégâts touchent les PV. Save WIT pour demi-dégâts. |

**Effet si ignoré :** L'ICE attaque **automatiquement** le hacker chaque round tant qu'il reste dans le système et que l'ICE est active.

> **Black ICE est mortelle.** C'est l'équivalent numérique d'un champ de mines. Les systèmes maximaux (FW 9-10) ont presque toujours du Black ICE. Un hacker non-préparé peut mourir face à un Black ICE — littéralement, si son implant neural prend le feedback.

---

#### VIRUS DORMANT — Force 3

**Fonction :** Piège offensif. Ne s'active que quand le hacker effectue une action spécifique (ouvrir un fichier piégé, accéder à un nœud leurre).

**Effet si déclenché :** Au choix du MJ :
- **Traqueur :** Installe un mouchard sur le deck du hacker. Le sysop connaît toujours sa localisation.
- **Corrupteur :** Le prochain jet de Hacking du hacker est fait avec Désavantage.
- **Bombe logique :** Le deck subit une dégradation.

**Détection :** Un hacker qui a Scanné la zone peut faire un jet de Hacking vs Force du Virus pour le repérer avant de le déclencher.

---

### Combien de programmes par système ?

| Firewall du système | Programmes typiques |
|---|---|
| 0-2 | 0-1 (souvent aucun) |
| 3-4 | 1-2 (1 Sentinelle + 1 Porte) |
| 5-6 | 2-3 (Sentinelle + Porte + ICE Blanche ou Pare-feu interne) |
| 7-8 | 3-4 (Sentinelle + Porte + Pare-feu interne + ICE Grise) |
| 9-10 | 4-5 (Sentinelle × 2 + Porte + Pare-feu interne + Black ICE) |

---

## 6. DÉTECTION ET ALERTE

### Niveaux d'alerte

Le système a un **niveau d'alerte** qui monte au fil des actions du hacker. C'est l'équivalent numérique du Shaken — une escalade progressive.

| Niveau | Nom | Effet |
|---|---|---|
| 0 | **Calme** | Aucune alerte. Le système fonctionne normalement. |
| 1 | **Suspicion** | Le système fait des vérifications de routine. +1 à la Force de toutes les Sentinelles. |
| 2 | **Alerte** | Un sysop est notifié (s'il existe). Les programmes ICE s'activent automatiquement. Toutes les actions de hacking ont Désavantage. |
| 3 | **Lockdown** | Le système se verrouille. Le Firewall augmente de +3. Le sysop tente un Lockout automatique chaque round. Les gardes physiques sont appelés (1d4 rounds). |

### Ce qui fait monter l'alerte

| Événement | Augmentation |
|---|---|
| Échec d'un jet d'Intrusion | +1 |
| Échec de désactivation d'un programme | +1 |
| Échec critique (Nat 20) sur n'importe quel jet de hacking | +2 |
| Le hacker est détecté par une Sentinelle | +1 |
| Action de Sabotage (réussie ou non) | +1 |
| Prise de contrôle d'un appareil critique | +1 |

### Ce qui fait baisser l'alerte

| Événement | Réduction |
|---|---|
| Action Masquer réussie | -1 |
| Le hacker se déconnecte et attend 1 Stretch (15 min) | Reset à 0 |
| Réussite critique (Nat 1) sur un jet de hacking | -1 |
| Sabotage réussi sur le module d'alerte lui-même | Reset à 0 (mais nécessite de trouver le nœud d'alerte) |

> **Design :** Le système d'alerte crée une **horloge narrative**. Le hacker sent la pression monter — est-ce qu'il pousse pour finir le job, ou est-ce qu'il se masque et prend son temps ? C'est exactement la même tension que le combat avec Shaken qui monte.

---

## 7. LE DUEL HACKER vs SYSOP

Quand un système est activement surveillé par un opérateur humain (sysop), le hacking devient un **duel** en temps réel.

### Le sysop comme PNJ

Le sysop est un PNJ avec son propre Score de Hacking et ses actions. Il utilise les mêmes règles que le hacker, mais en défense.

```
SYSOP D'ENTREPRISE — PNJ, Niv 3
Score Hacking: 10 (WIT 9, prof +1) | Poste: Terminal du centre de sécurité

ACTIONS DÉFENSIVES:
• Tracer (1 action) — Jet opposé vs hacker. Succès = +1 trace.
• Lockout (2 actions) — Jet diff 8 - traces. Succès = éjecte le hacker.
• Activer ICE (1 action) — Active un programme ICE inactif.
• Réparer (1 action) — Restaure un programme désactivé.
```

### Déroulement du duel

1. **Initiative :** Le sysop et le hacker tirent chacun une carte d'initiative (comme en combat).
2. **Chaque tour :** Chacun a 3 actions. Le hacker essaie de progresser dans le système. Le sysop essaie de le tracer et de l'éjecter.
3. **En parallèle :** Le combat physique continue. Les autres PJ doivent empêcher les gardes d'atteindre le hacker, ou trouver et neutraliser le sysop physiquement.

### Exemples de sysops

| Sysop | Score | Actions typiques |
|---|---|---|
| **Admin réseau de base** | 9-10 | Tracer, Lockout. Pas d'ICE. Paniqué si alerté. |
| **Opérateur sécurité corpo** | 11-12 | Tracer, Activer ICE, Lockout. Méthodique. |
| **Spécialiste cyber-défense** | 13-14 | Tracer (rapide), ICE Grise/Noire, Lockout. Dangereux. Peut contre-hacker. |
| **IA défensive** | 15-16 | Toutes les actions. Pas de panique, pas de fatigue. Agit 2×/round. |

> **Le meilleur plan pour les PJ :** Pendant que le Tech hack, l'Infiltrator se glisse dans le centre de sécurité et assomme le sysop. Ou le Marshal donne un Ordre Tactique pour couvrir le Tech. Le hacking est un **sport d'équipe**.

---

## 8. OUTILS DE HACKING

### Decks de hacking

Le **deck de hacking** est l'outil principal du hacker. C'est un ordinateur portable, un terminal, un implant neural, ou un appareil dédié. Le deck détermine le **bonus au Score de Hacking** et subit la **dégradation**.

| Deck | TL | Bonus | Prix | Propriétés |
|---|---|---|---|---|
| Terminal civil | 2 | +0 | 500 | Lien sans fil uniquement. Pas de protection anti-ICE. |
| Deck de hacking basique | 2 | +0 | 2 000 | Filaire + sans fil. 1 HP. |
| Deck de hacking amélioré | 3 | +1 | 8 000 | Filaire + sans fil. 2 HP. Protection anti-ICE Blanche (ignore ICE Blanche). |
| Deck militaire | 3 | +1 | 15 000 | Filaire + sans fil + satellite. 2 HP. Protection anti-ICE Blanche + Grise (ignore les deux). |
| Deck corpo avancé | 4 | +2 | 30 000 | Tous liens. 3 HP. Anti-ICE Blanche + Grise. Masquage passif (+1 au jet de Masquer). |
| Deck légendaire | 4-5 | +2 à +3 | Loot uniquement | Tous liens. 3 HP. Propriétés spéciales (voir loot). |
| Implant neural (interface directe) | 3-4 | +0 à +2 | Variable | Lien neural direct. Actions de hacking coûtent 1 action de moins (min 1). Vulnérable au Black ICE (dégâts normaux + 1 Blessure). |

### Dégradation des decks

Les decks suivent les mêmes règles de dégradation que les armes :

| État | Bonus | Effet |
|---|---|---|
| **Neuf** ✓ | Plein (+X) | Normal |
| **Endommagé** ⚠ | ÷ 2 (arrondi inf) | Échec critique (Nat 20) = le deck crash. 1 action pour reboot. Lien au système coupé pendant le reboot. |
| **Détruit** ✗ | 0 | Inutilisable. Le hacker ne peut plus hacker sans un nouveau deck. |

### Logiciels (consommables)

| Logiciel | Prix | Effet | Charges |
|---|---|---|---|
| **Exploit kit** | 500 | Avantage sur le prochain jet d'Intrusion. | 1 |
| **Spoofeur d'identité** | 300 | Réduit le Firewall effectif de 1 pour 1 Intrusion. | 1 |
| **Effaceur de traces** | 400 | Réduit l'alerte de 1 automatiquement (pas d'action). | 1 |
| **ICE Breaker** | 1 000 | Avantage pour désactiver un programme ICE (n'importe lequel). | 1 |
| **Virus préparé** | 800 | Le Sabotage "Virus" ne nécessite que 1 action au lieu de 2. | 1 |
| **Backdoor kit** | 2 000 | Après une Intrusion réussie : installe une backdoor permanente. Les futures Intrusions sur ce système ont Firewall -2. | 1 |

---

## 9. HACKING EN COMBAT — Intégration

Le hacking n'est pas un mini-jeu séparé. Il se déroule **pendant le combat**, sur la même timeline d'initiative.

### Actions de hacking dans l'économie de combat

Le hacker a 3 actions par tour. Il peut mélanger actions de combat et actions de hacking :

| Tour exemple (Tech Hacker niv 5) |
|---|
| **Action 1 :** Intrusion sur le réseau de sécurité (2 actions) |
| **Action 3 :** Tirer avec son pistolet sur le garde qui s'approche |

Ou :

| Tour exemple (Tech Hacker niv 5, déjà dans le système) |
|---|
| **Action 1 :** Contrôle — ouvrir la porte blindée pour l'équipe |
| **Action 2 :** Contrôle — boucler les caméras du couloir |
| **Action 3 :** Contrôle — éteindre les lumières (Désavantage aux gardes) |

### Hacking offensif en combat

Le hacker peut cibler les **équipements ennemis** en combat :

| Cible | Action | Effet si réussi |
|---|---|---|
| Drone ennemi | Prise de contrôle (2 actions) | Le drone passe sous contrôle du hacker |
| Implant ennemi | Sabotage (2 actions) | L'implant dysfonctionne 1 round (perd son bonus) |
| Arme connectée | Hack rapide (1 action, sous-classe Hacker) | L'arme s'enraye (1 action pour débloquer) |
| Exo-armure ennemie | Sabotage (2 actions) | Servos verrouillés (cible Immobilisée 1 round) |
| Comms ennemies | Contrôle (1 action) | Coupe les communications. L'ennemi perd les pouvoirs qui nécessitent de parler (Commandement, Appel de Renforts). |

> **Le Firewall de l'équipement ennemi** est déterminé par le MJ (typiquement 2-4 pour du matériel standard, 5-7 pour du matériel militaire). Les PNJ Hacker ont aussi leur propre deck et peuvent hacker les PJ.

### Quand le Tech n'est pas un Hacker

Le Tech sous-classe **Ingénieur** ne hack pas aussi bien, mais peut :
- Utiliser Hack Rapide (feature de classe) pour des effets mineurs (1 action, diff +2).
- Se concentrer sur ses drones et ses réparations.
- Scanner les systèmes pour donner des infos à l'équipe.

Le hacking offensif lourd (Intrusion + Sabotage + Prise de contrôle de systèmes critiques) est le territoire de la sous-classe **Hacker**.

---

## 10. EXEMPLES DE SYSTÈMES

### Système simple — Réseau de sécurité d'entrepôt

```
RÉSEAU DE SÉCURITÉ — Entrepôt corpo, TL 2
Firewall: 3 | Sysop: Non (automatisé)
Programmes: Sentinelle (Force 2), Porte (Force 2)

NŒUDS ACCESSIBLES APRÈS INTRUSION:
• Caméras (4) — Voir les flux / Boucler
• Portes (3) — Ouvrir / Fermer / Verrouiller
• Alarme — Activer / Désactiver
• Logs — Lire / Effacer

ZONE PROTÉGÉE (derrière la Porte):
• Coffre-fort électronique — Ouvrir
• Registres financiers — Lire / Copier
```

### Système moyen — Serveur corpo régional

```
SERVEUR CORPO "NEXAGEN RÉGIONAL" — TL 3
Firewall: 5 | Sysop: Oui (Admin réseau, Score 10)
Programmes: Sentinelle (Force 3), Porte (Force 3), ICE Blanche (Force 4)

NŒUDS ACCESSIBLES APRÈS INTRUSION:
• Réseau interne — Emails, planning, annuaire employés
• Système de sécurité bâtiment — Caméras, portes, ascenseurs
• Terminal RH — Dossiers employés, accès badges

ZONE PROTÉGÉE (derrière la Porte):
• Base de données R&D — Brevets, prototypes, formules
• Comptes financiers — Transactions, fournisseurs, clients
• Communications dirigeants — Emails cryptés, mémos internes

ZONE HAUTE SÉCURITÉ (derrière ICE Blanche + Porte secondaire Force 4):
• Projet classifié "FENRIR" — Données sur le programme cybernétique
```

### Système complexe — Infrastructure militaire

```
RÉSEAU MILITAIRE "BASE THETA-7" — TL 4
Firewall: 8 | Sysop: Oui (Spécialiste cyber-défense, Score 14)
Programmes: Sentinelle × 2 (Force 4), Porte (Force 4),
             Pare-feu interne (Force 5), ICE Grise (Force 5), Black ICE (Force 6)

NŒUDS ACCESSIBLES APRÈS INTRUSION:
• Système de surveillance — Caméras (20+), détecteurs mouvement
• Communications — Fréquences radio, messages internes
• Registre de personnel — Gardes, rotations, codes d'accès

ZONE PROTÉGÉE (derrière Pare-feu interne + Sentinelle):
• Contrôle armement — Tourelles, drones de patrouille, mines
• Réseau logistique — Approvisionnement, véhicules, inventaire

ZONE HAUTE SÉCURITÉ (derrière Black ICE + Porte):
• Ordres de mission classifiés
• Système de lancement orbital
• Noyau de l'IA défensive "AEGIS"
```

---

## 11. SCÉNARIOS DE HACKING

### Scénario 1 : "Ouvre-moi cette porte"

> Le groupe est devant une porte blindée électronique. Le Tech se branche.

- **Tour 1 :** Scanner (1 action) → Firewall 2, pas de programmes. Intrusion (2 actions) → Score 12 vs FW 2 = Seuil 10. Roule 7. Succès.
- **Tour 2 :** Contrôle "Ouvrir la porte" (1 action). Fait. Le Tech a encore 2 actions pour tirer ou se déplacer.

**Temps total :** 2 tours (20 secondes en jeu). Pas de mini-jeu, intégré au flot du combat.

### Scénario 2 : "Désactive les caméras discrètement"

> Le groupe prépare une infiltration. Le Tech hack le réseau de sécurité depuis une planque.

- **Tour 1 :** Scanner (1 action) → FW 3, Sentinelle (Force 2). Intrusion (2 actions) → Seuil 9. Roule 5. Succès.
- **Tour 2 :** Désactiver Sentinelle (1 action) → Score 12 vs Force 2 = Seuil 10. Roule 3. Succès (désactivée 3 rounds). Contrôle "Boucler caméras couloir A" (1 action). Contrôle "Boucler caméras couloir B" (1 action).
- **Tour 3 :** Les 3 rounds de Sentinelle désactivée commencent. L'équipe a ~30 secondes pour traverser les couloirs sans être vue. Le Tech Masque (1 action) pour rester indétecté.

### Scénario 3 : "Duel avec un sysop corpo"

> Le Tech tente de voler des données R&D pendant que l'équipe combat la sécurité.

- **Tour 1 (Tech) :** Intrusion (2 actions) → Score 14 vs FW 5 = Seuil 9. Roule 11. Échec. Alerte +1 → Suspicion.
- **Tour 1 (Sysop) :** Alerté par la Sentinelle. Tracer (1 action) → Jet opposé 10 vs 14. Sysop roule 8, Tech roule 12. Les deux réussissent mais 8 < 12, sysop gagne. Trace 1 (pays). Activer ICE Blanche (1 action). Défense passive (1 action restante).
- **Tour 2 (Tech) :** Push l'Intrusion. Prend Confus (Désavantage WIT). Relance → roule 6. Succès ! Mais maintenant il a Désavantage sur tous les jets WIT (y compris le hacking). Désactiver ICE Blanche (1 action) → Seuil 10 avec Désavantage (2d20 garde le plus haut). Roule 8 et 14 → garde 14. Échec. ICE Blanche s'active : perd 2 actions au prochain tour.
- **Tour 2 (Sysop) :** Tracer (1 action) → Trace 2 (ville). Lockout (2 actions) → Diff 8 - 2 traces = 6. Sysop Score 10, Seuil 4. Roule 3. Lockout ! Le Tech est éjecté.
- **Turn 3 :** Le Tech doit soit se rebrancher et réessayer (FW +2 maintenant), soit l'Infiltrator doit trouver et neutraliser le sysop physiquement.

> **Ce scénario montre pourquoi le hacking est un sport d'équipe.** Le Tech seul se fait éjecter. Mais si le Marshal avait ordonné "Couvre-le !" (donnant +2 rounds avant le lockout), ou si l'Infiltrator avait trouvé le sysop et l'avait assommé, le résultat serait différent.

---

## 12. TABLE DE RÉFÉRENCE RAPIDE

### Actions de hacking — Résumé

| Action | Coût | Jet | Prérequis |
|---|---|---|---|
| **Scanner** | 1 action | Aucun | Lien au système |
| **Intrusion** | 2 actions | Hacking vs Firewall | Lien au système |
| **Contrôle** | 1 action | Aucun (ou vs programme) | Intrusion réussie |
| **Sabotage** | 2 actions | Hacking vs Firewall | Intrusion réussie |
| **Prise de contrôle** | 2 actions | Hacking vs Firewall (ou opposé) | Intrusion réussie |
| **Masquer** | 1 action | Hacking vs Firewall ÷ 2 | Intrusion réussie |
| **Défendre** (sysop) | 1 action | Variable | Accès au système |

### Alerte — Résumé

| Niveau | Nom | Effet clé |
|---|---|---|
| 0 | Calme | Normal |
| 1 | Suspicion | Sentinelles +1 Force |
| 2 | Alerte | Désavantage sur le hacking. ICE s'active. Sysop notifié. |
| 3 | Lockdown | FW +3. Lockout auto chaque round. Gardes physiques en route. |

### ICE — Résumé

| Type | Force | Effet si échec |
|---|---|---|
| Blanche | 4 | Perd 2 actions |
| Grise | 5 | Dégradation du deck |
| Noire | 6 | 2d6 dégâts Lightning (Blessures si implant neural) |

### Firewall — Résumé

| Sécurité | FW | Programmes typiques |
|---|---|---|
| Aucune | 0 | — |
| Basique | 1-2 | 0-1 |
| Standard | 3-4 | 1-2 |
| Renforcée | 5-6 | 2-3 |
| Haute | 7-8 | 3-4 |
| Maximale | 9-10 | 4-5 |
