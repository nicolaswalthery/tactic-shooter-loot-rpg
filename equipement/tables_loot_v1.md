# TABLES DE LOOT — v1

> **Référence :** Formules canoniques v2 (15 niveaux, prof +1/+2/+3, loot +0 à +3).
> **Principe :** Le loot est la **deuxième jambe de progression** du système. Chaque objet a un **bonus numérique** qui s'ajoute au Score, et un **état de dégradation** (Neuf/Endommagé/Détruit). Le loot est volatile — il se casse, se perd, se fait voler. C'est la boucle de gameplay centrale.

---

## Comment lire les tables

### Colonnes

| Colonne | Description |
|---|---|
| **d20** | Résultat du dé. Le MJ roule 1d20 sur la table appropriée au contexte. |
| **Objet** | Nom de l'objet + description courte. |
| **Type** | Arme / Armure / Gadget / Implant / Consommable / Outil. |
| **Rareté** | ◻ Standard / 🔷 Rare / 🔶 Légendaire. |
| **Bonus** | **Le bonus numérique** qui s'ajoute au Score pertinent. C'est LA colonne clé. |
| **Qualités** | Qualités Genesys et/ou effets spéciaux. |
| **TL** | Tech Level de l'objet. |

### Le bonus numérique — Comment il s'applique

Le bonus s'ajoute **selon le type d'objet** :

| Type d'objet | Le bonus s'ajoute à... | Exemple |
|---|---|---|
| **Arme** | Score d'attaque (tir ou mêlée) | Fusil +2 → Score de Tir + 2 |
| **Armure** | Valeur d'Armure | Gilet +1 → Armure de base +1 |
| **Viseur / Lunette** | Score d'attaque de l'arme associée | Lunette +1 → Score de Tir +1 (attachment) |
| **Implant (stat)** | Valeur de la stat indiquée | Implant +1 DEX → DEX +1 (affecte Score, saves, etc.) |
| **Implant (skill)** | Score d'une compétence spécifique | Implant +1 Hacking → Score Informatique +1 |
| **Outil (skill)** | Score d'une compétence spécifique | Kit médical +1 → Score Médecine +1 |
| **Gadget** | Effet spécial (pas de bonus numérique au Score) | Drone, grenade, consommable → voir qualités |
| **Consommable** | Usage unique, pas de bonus permanent | Stim pack, grenade → effet puis consommé |

### Dégradation — 3 états

Chaque objet durable (pas les consommables) a un état inscrit sur la fiche :

| État | Bonus | Qualités | Notation fiche |
|---|---|---|---|
| **Neuf** ✓ | Plein | Fonctionnent | Case vide |
| **Endommagé** ⚠ | **÷ 2** (arrondi inf) | Fonctionnent encore | 1 croix |
| **Détruit** ✗ | **0** — inutilisable | Ne fonctionnent plus | 2 croix |

**Exemples :**
- Fusil +2 Endommagé → +1 au Score. Fusil +1 Endommagé → +0.
- Armure +2 Endommagée → +1 Armure bonus. Les qualités marchent encore.
- Implant +3 STR Endommagé → +1 STR (affecte PV, Blessures, Surges instantanément).

### Rareté et distribution de bonus

| Rareté | Bonus typique | Qualités | Fréquence de drop |
|---|---|---|---|
| ◻ **Standard** | +0 | 0–1 qualité | d20 résultats 1-10 (50%) |
| 🔷 **Rare** | +1 à +2 | 1–2 qualités | d20 résultats 11-18 (40%) |
| 🔶 **Légendaire** | +2 à +3 | 2–3 qualités | d20 résultats 19-20 (10%) |

### Rythme de loot recommandé

| Arc | Niveaux | Loot attendu par session | Bonus max en circulation |
|---|---|---|---|
| **Recrue** | 1-5 | 1 pièce intéressante | +0 à +1 |
| **Vétéran** | 6-10 | 1-2 pièces | +1 à +2 |
| **Élite** | 11-15 | 1-2 pièces, dont upgrade | +2 à +3 |

> **Le MJ ajuste la rareté disponible selon l'arc.** Au niveau 1, on roule sur 1-15 de la table (pas de légendaires). Au niveau 10+, on peut ajouter +2 ou +4 au d20 pour pousser vers le haut.

---

## TABLE 1 — LOOT MILITAIRE

> Bases, convois, champs de bataille, armureries, camps retranchés, postes de garde.

| d20 | Objet | Type | Rareté | Bonus | Qualités | TL |
|---|---|---|---|---|---|---|
| 1 | **Chargeurs en vrac.** Munitions standard empilées dans une caisse. | Consommable | ◻ | — | Réapprovisionne les munitions du groupe pour 1 Shift. | 1 |
| 2 | **Gilet tactique usagé.** Armure balistique de surplus. Fonctionnel mais fatigué. | Armure (M) | ◻ | +0 | Armure 5. | 1 |
| 3 | **Fusil d'assaut standard.** L'arme de base de l'infanterie. Fiable, sans surprise. | Arme | ◻ | +0 | 1d8 / Auto 1d10. Portée 30. | 1 |
| 4 | **Kit de premiers soins militaire.** Bandages, morphine auto, garrots. | Outil | ◻ | +0 | Déclenche 1 Healing Surge (allié adjacent). Usage unique par Stretch. | 1 |
| 5 | **Grenades frag (×3).** Lot de trois grenades standard. | Consommable | ◻ | — | 2d6, Blast 2, Knockdown. Save DEX. | 1 |
| 6 | **Casque balistique.** Protège la tête. Réduit les crits. | Armure (L) | ◻ | +0 | +1 Armure (tête). -10 au jet de Blessures Critiques. | 1 |
| 7 | **Radio militaire cryptée.** Communication sécurisée, portée 50 km. | Gadget | ◻ | +0 | Communication cryptée. Impossible à intercepter sans Informatique diff 4. | 2 |
| 8 | **Couteau de combat.** Lame utilitaire à double usage. | Arme | ◻ | +0 | 1d4, Reach 1. Peut être lancé (portée 4). | 0 |
| 9 | **Fumigènes (×4).** Lot de quatre fumigènes screening. | Consommable | ◻ | — | Zone opaque Blast 3, 1d4 rounds. Bloque la ligne de vue. | 0 |
| 10 | **Armure de combat modulaire.** Plaques interchangeables, bien entretenue. | Armure (M) | ◻ | +0 | Armure 7. Modulaire (+1 HP). | 2 |
| 11 | **Fusil de combat avancé "Wraith".** Caseless, silencieux d'origine, précis. | Arme | 🔷 | **+1** | 1d10 / Auto 1d12. Portée 30. Silencieux (inclus). | 2 |
| 12 | **Gilet lourd "Iron Wall".** Plaques céramique de qualité supérieure. | Armure (H) | 🔷 | **+1** | Armure 8. Résistance (balistique). | 2 |
| 13 | **Lunette ACOG améliorée.** Optique de précision, reticule holographique. | Attachment | 🔷 | **+1** | S'installe sur un fusil (1 HP). Le bonus s'ajoute au Score de Tir de l'arme. | 2 |
| 14 | **Grenade EMP.** Prototype confisqué au labo d'ingénierie. | Consommable | 🔷 | — | Désactive électronique Blast 3, 1d4 rounds. Drones détruits. Cybernétiques off. | 3 |
| 15 | **Stimulant de combat "Surge-9".** Injection d'adrénaline militaire. | Consommable | 🔷 | — | Déclenche 1 Healing Surge (1 action). Avantage sur STR/DEX pendant 3 rounds. Puis Épuisé. | 2 |
| 16 | **Fusil magnétique léger "Tempest".** Accélération électromagnétique, fiable. | Arme | 🔷 | **+1** | 2d6 / Auto 2d8. Portée 30. Magnétique, Pierce 1. | 3 |
| 17 | **Exo-bras droit "Goliath Grip".** Servomoteur militaire, monté sur l'épaule. | Implant | 🔷 | **+2 STR** | Mêlée uniquement : +2 dégâts mêlée. Réduit Cumbersome armes de 1. 1 slot. | 3 |
| 18 | **Armure composite "Sentinel".** Nanoplaques auto-ajustantes, couverture intégrale. | Armure (H) | 🔷 | **+2** | Armure 10. Scellée (partiel). Stabilisée (Avantage au sang-froid Shaken). | 3 |
| 19 | **Sniper railgun "Judgment".** Canon magnétique longue portée, dévastateur. | Arme | 🔶 | **+2** | 2d10. Portée 80. Magnétique, Precise 2, Pierce 3. Cumbersome 2. | 4 |
| 20 | **Exo-armure d'infanterie "Titan Mk.II".** Armure assistée complète, trouvée dans un coffre de commandement. | Armure (E) | 🔶 | **+3** | Armure 12. Servos. Scellée. STR augmentée (+2). Avantage sang-froid. | 3 |

---

## TABLE 2 — LOOT URBAIN

> Rues, appartements, marchés noirs, clubs, entrepôts, commerces, véhicules abandonnés.

| d20 | Objet | Type | Rareté | Bonus | Qualités | TL |
|---|---|---|---|---|---|---|
| 1 | **Téléphone jetable.** Prépayé, non-traçable. 48h d'autonomie. | Gadget | ◻ | — | Communication basique. Détruit après usage = aucune trace. | 1 |
| 2 | **Veste en cuir renforcée.** Blindage artisanal dans la doublure. | Armure (L) | ◻ | +0 | Armure 2. Discret. | 0 |
| 3 | **Pistolet semi-auto.** Arme de poing commune, fiable. | Arme | ◻ | +0 | 1d6. Portée 10. | 1 |
| 4 | **Kit de crochetage.** Rossignols et tenseurs dans un étui. | Outil | ◻ | +0 | Nécessaire pour Escamotage (serrures mécaniques). | 0 |
| 5 | **Batte de baseball cloutée.** Arme de mêlée improvisée mais efficace. | Arme | ◻ | +0 | 1d6, Reach 1. Knockdown. | 0 |
| 6 | **Sac de survie urbaine.** Lampe, rations, gourde, carte, couverture. | Gadget | ◻ | — | Kit aventurier. Survie en milieu urbain pour 3 jours. | 0 |
| 7 | **Faux papiers.** Identité forgée, qualité moyenne. | Gadget | ◻ | +0 | Avantage sur Tromperie pour se faire passer pour quelqu'un d'autre. Perception diff 2 pour détecter. | 1 |
| 8 | **Gilet pare-balles souple.** Porté sous une chemise, invisible. | Armure (L) | ◻ | +0 | Armure 3. Discret. | 1 |
| 9 | **Flask d'alcool frelaté.** Dangereux mais utile en négociation. | Consommable | ◻ | — | Avantage sur Persuasion/Tromperie (1 scène). Puis Confus 1h si bu par le PJ. | 0 |
| 10 | **Pistolet lourd "Black King".** Canon de 12mm, finition noire mate. Impressionnant. | Arme | ◻ | +0 | 1d8. Portée 8. Intimidation : Avantage si arme visible. | 1 |
| 11 | **Pistolet caseless "Whisper".** Compact, silencieux, idéal pour l'infiltration. | Arme | 🔷 | **+1** | 1d8. Portée 10. Silencieux intégré. Discret (dissimulable, Perception diff 3). | 2 |
| 12 | **Faux papiers premium.** Identité complète — biométrie, historique de crédit, casier vierge. | Gadget | 🔷 | **+1** | +1 à Tromperie pour identité. Perception diff 4 pour détecter. Résiste aux scans TL2. | 2 |
| 13 | **Contact au marché noir.** Pas un objet — un accès. Le vendeur offre un choix. | Spécial | 🔷 | — | Le joueur peut **acheter** 1 objet 🔷 de n'importe quelle table, au double du prix. | — |
| 14 | **Veste balistique "Shadow Line".** Coupe civile, protection militaire. | Armure (L) | 🔷 | **+1** | Armure 4. Discret. Pas de pénalité de Discrétion. | 2 |
| 15 | **Couteau monofilament.** Lame à fil unique, coupe tout. | Arme | 🔷 | **+1** | 1d6, Reach 1. Pierce 3. Vicious 1. | 3 |
| 16 | **Lunettes infrarouges "Nightcrawler".** Vision nocturne 30 cases, look civil. | Gadget | 🔷 | +0 | Vision nocturne 30 cases (dim → bright, dark → dim). Discret (ressemble à des lunettes normales). | 3 |
| 17 | **Implant communicateur sous-cutané.** Radio dans la mâchoire, activation par pression. | Implant | 🔷 | **+1** | +1 aux jets de Persuasion et Tromperie (micro-feedback vocal). Comm cryptée 20 km. 1 slot. | 3 |
| 18 | **SMG caseless "Viper".** Dissimulable dans un sac, rafale dévastatrice. | Arme | 🔷 | **+2** | 1d8 / Auto 1d10. Portée 12. Compact (dissimulable). | 2 |
| 19 | **Armure sous-cutanée nanofibre.** Implantée chirurgicalement, invisible de l'extérieur. | Implant | 🔶 | **+2** | +2 Armure permanent. Invisible (pas détectable visuellement). Ne cumule pas avec armure > 5. 1 slot. | 3 |
| 20 | **Pistolet plasma "Sunburn".** Arme de collection d'un crime lord. Gravée, unique. | Arme | 🔶 | **+3** | 2d6. Portée 8. Burn 2. Vicious 1. Le posséder attire l'attention (le crime lord le veut). | 4 |

---

## TABLE 3 — LOOT CORPORATIF

> Bureaux, labos, coffres-forts d'entreprise, salles serveur, appartements de cadres, centres de recherche.

| d20 | Objet | Type | Rareté | Bonus | Qualités | TL |
|---|---|---|---|---|---|---|
| 1 | **Badge d'accès niveau 1.** Ouvre les portes publiques du complexe. | Gadget | ◻ | — | Accès aux zones niveau 1 (couloirs, cafétéria, sanitaires). | 2 |
| 2 | **Tablette de données.** Terminal d'entreprise verrouillé. Informatique diff 2 pour déchiffrer. | Gadget | ◻ | +0 | Contient des données internes (MJ détermine le contenu). | 2 |
| 3 | **Pistolet taser.** Arme non-létale, standard sécurité corpo. | Arme | ◻ | +0 | 1d4 Lightning. Stun 2 (Staggered 2 rounds si touché). Portée 4. | 2 |
| 4 | **Tenue de sécurité corpo.** Uniforme avec gilet léger intégré. | Armure (L) | ◻ | +0 | Armure 3. Passe pour un agent de sécurité (Avantage Tromperie dans le complexe). | 1 |
| 5 | **Stimpack corporatif (×2).** Injecteurs d'urgence de qualité pharmaceutique. | Consommable | ◻ | — | Déclenche 1 Healing Surge (1 action) par stim. | 2 |
| 6 | **Détecteur de mensonges portable.** Micro-capteurs biométriques dans une montre. | Outil | ◻ | +0 | Avantage aux jets d'Intuition (1 cible à la fois). La cible ne sait pas. | 3 |
| 7 | **Brouilleur de fréquences portable.** Coupe les communications sans fil dans 20 cases. | Gadget | ◻ | — | Bloque radio/wifi/cellulaire pendant 20 minutes. 1 charge par Shift. | 2 |
| 8 | **Mallette blindée.** Conteneur de transport sécurisé, Armure 8 sur le contenu. | Gadget | ◻ | — | Protège 1 objet à l'intérieur (Armure 8). Résiste à la plupart des scanners TL2. | 2 |
| 9 | **Sédatifs (×3).** Seringues auto-injectantes, effet immédiat. | Consommable | ◻ | — | Cible inconsciente 1d4 heures (save STR pour résister). Usage mêlée uniquement. | 2 |
| 10 | **Gilet de protection exécutive.** Kevlar haut de gamme, coupe sur mesure. | Armure (M) | ◻ | +0 | Armure 6. Discret (sous un costume). | 2 |
| 11 | **Badge d'accès niveau 3.** Ouvre les zones sensibles — labos, serveurs, direction. | Gadget | 🔷 | — | Accès aux zones niveau 3. Désactive certaines alarmes. Chronométré (8h). | 2 |
| 12 | **Deck de hacking "Razor".** Terminal offensif, interface neurale optionnelle. | Outil | 🔷 | **+1** | +1 au Score d'Informatique (hacking). Réduit Firewall de 1 sur la première intrusion. | 3 |
| 13 | **Prototype de recherche (arme).** Fusil laser compact en phase de test. | Arme | 🔷 | **+1** | 2d6 Force. Portée 30. Burn 1, Precise 1. Marqué "PROTOTYPE" — traçable. | 3 |
| 14 | **Données compromettantes.** Fichiers décryptés — corruption, comptes offshore, black ops. | Gadget | 🔷 | — | Levier narratif. Peut être monnayé, échangé, ou utilisé comme chantage. Valeur = scénario. | — |
| 15 | **Implant oculaire "Eagle Eye".** Augmentation rétinienne corpo, vision augmentée. | Implant | 🔷 | **+1** | +1 WIT (affecte Perception, Investigation, etc.). Vision nocturne 20 cases. 1 slot. | 3 |
| 16 | **Drone tactique corpo "Sentinel".** Petit drone de surveillance avec marquage de cibles. | Gadget | 🔷 | +0 | Vol 6 cases. Caméra 360° + IR. Marque 1 cible : alliés ont Avantage vs cible marquée (1 round). PV 5, Armure 1. | 3 |
| 17 | **Armure nanoplaque "Executive Shield".** Protection invisible, auto-réparation. | Armure (M) | 🔷 | **+2** | Armure 7. Discret. Auto-réparation (récupère 1 Armure perdue par Stretch). | 4 |
| 18 | **Pistolet rail "Apex".** Arme de poing magnétique, bijou de technologie. | Arme | 🔷 | **+2** | 2d6. Portée 15. Magnétique, Pierce 2. | 4 |
| 19 | **Cadre neural amélioré "Cortex".** Implant cérébral de cadre supérieur, boost cognitif. | Implant | 🔶 | **+2** | +2 WIT. Avantage aux jets d'Investigation et d'Informatique. 2 slots. Risque de cyberpsychose. | 4 |
| 20 | **Exo-armure furtive "Phantom".** Prototype d'infiltration corpo, camouflage actif. | Armure (E) | 🔶 | **+3** | Armure 11. Servos. Scellée. Camouflage optique (Avantage Discrétion, invisible si immobile). Pas de Désav. Discrétion. | 4 |

---

## TABLE 4 — LOOT TECH / HACKER

> Serveurs, ateliers de réparation, épaves de drones, marchés du darknet, squats de hackers.

| d20 | Objet | Type | Rareté | Bonus | Qualités | TL |
|---|---|---|---|---|---|---|
| 1 | **Câbles et composants.** Pièces de récupération, utiles pour réparer. | Consommable | ◻ | — | Matériaux pour 1 réparation de terrain (Endommagé → Neuf). Consommé à l'usage. | 2 |
| 2 | **Drone éclaireur bricolé.** Petit quadricoptère avec caméra, fait maison. | Gadget | ◻ | +0 | Vol 8 cases. Caméra vidéo, portée 100 cases. PV 3, Armure 0. Fragile. | 2 |
| 3 | **Kit d'ingénierie basique.** Tournevis, multimètre, fer à souder, composants. | Outil | ◻ | +0 | Nécessaire pour les jets d'Ingénierie (réparation, crafting). | 1 |
| 4 | **Clé USB cryptée.** Contient des données — schémas, codes d'accès, programmes. | Gadget | ◻ | — | Informatique diff 2 pour déchiffrer. Contenu = MJ (plans, mots de passe, virus). | 2 |
| 5 | **Détecteur de métaux portable.** Détecte mines, armes cachées, objets métalliques. | Gadget | ◻ | +0 | Détecte métal à 6 cases. Avantage aux jets de Perception pour trouver des objets cachés. | 3 |
| 6 | **Communicateur chiffré de poche.** Radio indétectable, réseau mesh. | Gadget | ◻ | +0 | Communication cryptée 50 km. Impossible à intercepter TL2, Informatique diff 4 au TL3. | 3 |
| 7 | **Filament caméra.** Fil-caméra de 10 cases, passe sous les portes. | Gadget | ◻ | +0 | Espionnage. Perception diff 4 pour repérer. | 2 |
| 8 | **Grenade EMP artisanale.** Fabrication maison, instable mais fonctionnelle. | Consommable | ◻ | — | Blast 2 (réduit). Désactive électronique 1d4 rounds. 20% de chance de dysfonction (ne détone pas). | 2 |
| 9 | **Machine pistol modifié.** Arme de poing avec auto-fire bricolé. | Arme | ◻ | +0 | 1d4 / Auto 1d6. Portée 6. Auto-fire. Risque de jam sur Échec critique (arme Endommagée). | 1 |
| 10 | **Pièces de drone (×3).** Moteurs, hélices, capteurs — récupérables. | Consommable | ◻ | — | Matériaux pour réparer OU reconstruire 1 drone Détruit → Endommagé (Ingénierie diff 4). | 3 |
| 11 | **Kit d'ingénierie avancé "Forge".** Outils de précision, diagnostic automatique. | Outil | 🔷 | **+1** | +1 aux jets d'Ingénierie. Réduit la difficulté de réparation de 1. | 3 |
| 12 | **Deck de hacking "Specter".** Terminal haute performance, interface haptique. | Outil | 🔷 | **+1** | +1 au Score d'Informatique. Première intrusion par Shift : réduit Firewall de 1. | 3 |
| 13 | **Drone de combat "Hornet".** Quadricoptère armé, piloté par télécommande. | Gadget | 🔷 | +0 | Vol 6 cases. Pistolet intégré (1d6, portée 10). DEX drone = 11. PV 10, Armure 2. | 3 |
| 14 | **Implant de poignet "MultiTool".** Couteau suisse cybernétique intégré au bras. | Implant | 🔷 | **+1** | +1 Ingénierie. Inclut tournevis, cutter, soudeur, analyseur. 1 slot. | 3 |
| 15 | **Virus "Blackout".** Programme offensif prêt à l'emploi, stocké sur puce. | Consommable | 🔷 | — | Si injecté dans un système (hacking réussi) : désactive le système pendant 1 Stretch. Antivirus diff 5. | 3 |
| 16 | **Caméra-bille volante "Pixie".** Micro-drone d'espionnage, quasi-indétectable. | Gadget | 🔷 | +0 | Vol 4 cases. Discrétion diff 4 pour repérer. Vidéo/audio 360°. 500 cases de portée. PV 1. | 4 |
| 17 | **Bras cybernétique "Artisan".** Prothèse de précision, servomoteurs de chirurgien. | Implant | 🔷 | **+2** | +2 DEX (mains uniquement : Escamotage, Ingénierie, tir de précision). 1 slot. | 3 |
| 18 | **Fusil gauss portable "Decimator".** Arme magnétique lourde, trouvée dans un atelier de contrebande. | Arme | 🔷 | **+2** | 2d8 / Auto 2d10. Portée 35. Magnétique, Pierce 2. Cumbersome 1. | 4 |
| 19 | **Drone lourd "War Wasp".** Drone de combat avancé, SMG intégré, résistant aux EMP. | Gadget | 🔶 | **+2** | Vol 4 cases. SMG intégré (1d8, auto 1d10, portée 12). DEX drone = 12. PV 15, Armure 3. Résiste EMP (save). | 4 |
| 20 | **Deck de hacking légendaire "Pandora".** Chef-d'œuvre d'un hacker mythique. Circuiterie quantique. | Outil | 🔶 | **+3** | +3 au Score d'Informatique. Réduit Firewall de 2 sur toute intrusion. Première intrusion par Shift : Avantage automatique. Recherché par 3 corps et 2 gouvernements. | 5 |

---

## TABLE 5 — LOOT MÉDICAL

> Hôpitaux, cliniques de campagne, ambulances, laboratoires pharmaceutiques, épaves de vaisseaux médicaux.

| d20 | Objet | Type | Rareté | Bonus | Qualités | TL |
|---|---|---|---|---|---|---|
| 1 | **Bandages compressifs (×6).** Premiers soins basiques. | Consommable | ◻ | — | Stabilise un Mourant sans jet de Médecine. | 0 |
| 2 | **Kit de suture portable.** Aiguilles, fil résorbable, désinfectant. | Outil | ◻ | +0 | Permet les jets de Médecine. Soigne 1 Blessure supplémentaire par Shift. | 1 |
| 3 | **Analgésiques (×4).** Doses injectables, effet immédiat. | Consommable | ◻ | — | Supprime 1 condition (Épuisé ou Confus) pendant 1 Shift. Ne soigne pas. | 1 |
| 4 | **Attelle autobloquante.** Mousse expansive rigidifiante. | Outil | ◻ | +0 | Soigne la blessure critique "Fracture" en 1 Stretch au lieu de 1 Shift. | 1 |
| 5 | **Sacoche médicale militaire.** Kit complet de premiers soins avancés. | Outil | ◻ | +0 | Kit médical. +1 PV par Premiers Soins (bonus au Medic). | 1 |
| 6 | **Ration nutritive concentrée (×8).** Barres protéinées haute densité. | Consommable | ◻ | — | 1 ration = 1d4 PV (1 action). Max 2 par Stretch. | 1 |
| 7 | **Plasma sanguin synthétique (×2).** Poches de perfusion universelles. | Consommable | ◻ | — | Soigne 1 Blessure (1 action, Médecine requis). Usage unique par poche. | 2 |
| 8 | **Défibrillateur portable.** Compact, rechargeable. | Outil | ◻ | +0 | Un Mourant stabilisé revient à 1 PV (1 action + Médecine). 3 charges/Shift. | 1 |
| 9 | **Anti-toxines large spectre (×3).** Neutralisent la plupart des poisons. | Consommable | ◻ | — | Soigne immédiatement la condition Empoisonné. | 2 |
| 10 | **Scanner médical "Vitascan".** Diagnostic holographique portable. | Outil | 🔷 | **+1** | +1 Médecine. Diagnostique toutes les blessures/conditions (1 action). | 2 |
| 11 | **Kit chirurgical "Scalpel".** Instruments miniaturisés de qualité. | Outil | 🔷 | **+1** | +1 Médecine. Réduit diff blessures critiques Graves de 1. | 2 |
| 12 | **Stim pack "Vanguard" (×3).** Stimulants militaires améliorés. | Consommable | 🔷 | — | Active 1 Healing Surge + supprime Shaken (même Shaken 3). | 2 |
| 13 | **Nano-bandage régénérant (×2).** Tissu imprégné de nanites. | Consommable | 🔷 | — | Soigne 2d6 PV + soigne 1 Blessure sur 1 Stretch. | 3 |
| 14 | **Implant médical "Medulla".** Monitoring vital sous-cutané. | Implant | 🔷 | **+1 WIT** | +1 WIT. Alerte auto si PV < 50%. 1 slot. | 3 |
| 15 | **Injecteur "Phoenix".** Ramène un Mourant à la conscience. | Consommable | 🔷 | — | Mourant → 1 PV + Shaken 2. Sans Médecine. Usage unique. | 2 |
| 16 | **Autogreffe tissulaire.** Biomatériaux de réparation compatibles. | Consommable | 🔷 | — | Soigne 1 blessure critique (Mineure ou Grave) en 1 Stretch. | 3 |
| 17 | **Bras prothétique "Mender Mk.III".** Prothèse médicale avancée. | Implant | 🔷 | **+1 STR** | Remplace un bras perdu. STR +1 (bras uniquement). 1 slot. | 3 |
| 18 | **Caisson de stase portable.** Cryostase d'urgence, transportable. | Gadget | 🔷 | — | Mourant en stase (plus de Blessures). 4h d'autonomie. | 3 |
| 19 | **Nano-injecteur "Lazarus".** Nanites de dernière génération. | Consommable | 🔶 | — | Cible à 0 Blessures → restaure **toutes les Blessures**. Usage unique. | 4 |
| 20 | **Kit chirurgical "Asklepios".** IA médicale + outils robotisés. | Outil | 🔶 | **+3** | +3 Médecine. Soigne 1 blessure critique/Shift automatiquement. | 4 |

---

## TABLE 6 — LOOT ALIEN / ANOMALIE

> Artefacts extraterrestres, ruines abandonnées, épaves de vaisseaux inconnus, zones d'anomalie, reliques pré-humaines.

| d20 | Objet | Type | Rareté | Bonus | Qualités | TL |
|---|---|---|---|---|---|---|
| 1 | **Fragment cristallin.** Éclat luminescent d'une structure inconnue. | Composant | ◻ | — | Vaut $500 à un collecteur. Aucun effet connu. | ? |
| 2 | **Fluide bioluminescent (×3).** Liquide qui émet une lumière douce. | Consommable | ◻ | — | Éclairage 6 cases, 4h. Comestible : restaure 1d4 PV (goût amer). | ? |
| 3 | **Carapace chitineuse.** Plaque d'armure biologique arrachée à une créature. | Armure (L) | ◻ | +0 | Armure 3. Ne gêne pas la Discrétion. Organique (indétectable aux scanners métal). | ? |
| 4 | **Lame d'os vitreux.** Tranchant moléculaire naturel. | Arme | ◻ | +0 | 1d6. Reach 1. Finesse. Pierce 1. | ? |
| 5 | **Relique magnétique.** Sphère métallique lisse. Flotte à 1 cm du sol. | Gadget | ◻ | — | Attire les petits objets métalliques à 2 cases. Vaut $1000. | ? |
| 6 | **Spore cicatrisante (×5).** Champignons séchés trouvés dans une serre xéno. | Consommable | ◻ | — | Soigne 1d6 PV. Effet secondaire : Confus (1 chance sur 6). | ? |
| 7 | **Lichen adaptatif.** Organisme qui épouse les surfaces. | Consommable | 🔷 | — | Appliqué sur un objet : répare Endommagé → Neuf. 1 Stretch. | ? |
| 8 | **Drone fossile.** Petit automate minéral qui s'anime à la chaleur. | Gadget | 🔷 | +0 | Drone éclaireur. PV 2, Vol 4, capteur thermique 10 cases. | ? |
| 9 | **Tissu membranaire.** Matériau souple, quasi-transparent, résistant. | Armure (L) | 🔷 | **+1** | Armure 4. Invisible sous les vêtements. Résistance acide. | ? |
| 10 | **Cristal résonnant.** Vibre en présence de champs électriques. | Gadget | 🔷 | — | Détecte tout appareil électronique actif dans 20 cases. | ? |
| 11 | **Sérum d'accélération.** Liquide ambré, injection. | Consommable | 🔷 | — | +2 Speed + Avantage DEX, 3 rounds. Puis Déstabilisé 1 Stretch. | ? |
| 12 | **Écharpe gravitationnelle.** Bande de tissu qui altère la gravité locale. | Gadget | 🔷 | — | Chute de n'importe quelle hauteur sans dégât. 3 charges/Shift. | ? |
| 13 | **Implant cortical "Écho".** Puce xénotech trouvée dans un crâne momifié. | Implant | 🔷 | **+1 WIT** | +1 WIT. Visions : le MJ fournit 1 indice cryptique par Shift. 1 slot. | ? |
| 14 | **Projecteur de bouclier.** Bracelet, champ de force partiel. | Gadget | 🔷 | — | Réaction : annule 1 attaque. 1 charge/Shift. | ? |
| 15 | **Lame de phase.** Existe partiellement dans une autre dimension. | Arme | 🔷 | **+1** | 1d8. Reach 1. Finesse. Pierce 2. | ? |
| 16 | **Greffe symbiotique.** Organisme vivant qui fusionne avec la peau. | Implant | 🔷 | **+2** | +2 à un save au choix (permanent). Se nourrit : -1 PV/Shift. 1 slot. | ? |
| 17 | **Armure de croissance.** Carapace vivante, s'adapte au porteur. | Armure (M) | 🔶 | **+2** | Armure 7. +1/semaine portée (max +3). Auto-répare Endommagé en 1 Shift. | ? |
| 18 | **Sphère de téléportation courte.** Déplace l'utilisateur instantanément. | Gadget | 🔶 | — | Action libre : téléportation ≤ 10 cases (point visible). 1 charge/Shift. | ? |
| 19 | **Canon à singularité "Collapse".** Micro-trous noirs. | Arme | 🔶 | **+2** | 2d8. Portée 15. Blast 1. Ignore Armure. Attire cibles de 2 cases. | ? |
| 20 | **Symbiote tactique "Aegis".** Organisme-armure vivant, fusion neurale. | Armure (E) | 🔶 | **+3** | Armure 10. Régénère 1d6 PV/round. Immunité poisons. Empathie. 2 slots. | ? |

---

## TABLE 7 — LOOT VÉHICULE

> Garages, hangars, stations-service, dépôts de flotte, épaves de véhicules, convois abandonnés.

| d20 | Objet | Type | Rareté | Bonus | Qualités | TL |
|---|---|---|---|---|---|---|
| 1 | **Bidon de carburant.** 20 litres, standard. | Consommable | ◻ | — | Ravitaillement partiel. Inflammable (2d6 si bombe improvisée). | 1 |
| 2 | **Kit de réparation véhicule.** Outils mécaniques, pièces basiques. | Outil | ◻ | +0 | Permet Ingénierie sur véhicules. 3 utilisations. | 1 |
| 3 | **Pneus de rechange (×2).** Pneumatiques blindés, compatibles multi-véhicules. | Composant | ◻ | — | Répare un véhicule immobilisé par pneu crevé. | 1 |
| 4 | **GPS militaire.** Navigation par satellite + cartes tactiques. | Gadget | ◻ | +0 | Avantage sur Survie/Pilotage en navigation. | 2 |
| 5 | **Extincteur industriel.** Mousse chimique, haute capacité. | Outil | ◻ | +0 | Éteint feu zone 2×2 (1 action). Arme improvisée (Aveuglé 1 round). | 0 |
| 6 | **Blindage de portière (×2).** Plaques d'acier à boulonner. | Attachment | ◻ | +0 | +2 Armure véhicule. Installation 1 Stretch + Ingénierie. | 1 |
| 7 | **Turbo-compresseur.** Boosteur mécanique, installation simple. | Attachment | ◻ | +0 | +2 Speed véhicule. 1 HP véhicule. | 2 |
| 8 | **Phares anti-émeute.** Projecteurs stroboscopiques. | Attachment | 🔷 | — | Cône 6 cases : save WIT ou Aveuglé 1 round. 3 charges/Shift. 1 HP. | 2 |
| 9 | **Mitrailleuse montée "Rampart".** Tourelle légère. | Arme (véhicule) | 🔷 | **+1** | 2d6, Auto 2d8. Portée 20. Arc 180°. 1 HP. | 2 |
| 10 | **Blindage composite.** Plaques céramique-acier professionnelles. | Attachment | 🔷 | **+1** | +3 Armure véhicule. 2 HP. | 2 |
| 11 | **Moto "Hornet".** Deux roues léger, rapide, silencieux. | Véhicule | 🔷 | — | Speed 16. Armure 2. PV 15. 1 passager. Discret. 1 HP. | 2 |
| 12 | **4×4 blindé "Warthog".** Tout-terrain militarisé. | Véhicule | 🔷 | — | Speed 10. Armure 8. PV 30. 4 passagers. 2 HP. | 2 |
| 13 | **Drone cargo aérien.** Quadricoptère de transport lourd. | Véhicule | 🔷 | — | Speed 12 (vol). Armure 2. PV 10. 200 kg. Pilotable à distance. | 2 |
| 14 | **Système ECM véhiculaire.** Contre-mesures électroniques. | Gadget | 🔷 | — | Désavantage sur attaques guidées/missiles ciblant le véhicule. 1 HP. | 3 |
| 15 | **Moteur hybride "Spectre".** Propulsion silencieuse + boost. | Attachment | 🔷 | **+1** | +4 Speed + mode silencieux (Avantage Discrétion). 2 HP. | 3 |
| 16 | **Tourelle auto "Sentry".** Arme autonome montée. | Arme (véhicule) | 🔷 | **+1** | 1d10. Portée 15. IA Score 9 (pas besoin d'opérateur). 2 HP. | 3 |
| 17 | **Navette "Kestrel".** Petit transport aérien, ailes repliables. | Véhicule | 🔷 | — | Speed 20 (vol). Armure 5. PV 25. 6 passagers. 3 HP. Portée planétaire. | 3 |
| 18 | **APC "Rhino".** Transport de troupes blindé lourd. | Véhicule | 🔶 | — | Speed 8. Armure 12. PV 50. 8 passagers. Tourelle 2d8. 4 HP. | 3 |
| 19 | **Intercepteur "Barracuda".** Vaisseau monoplace de combat. | Véhicule | 🔶 | — | Speed 25 (espace). Armure 8. PV 30. Canons 2d10. 3 HP. | 4 |
| 20 | **Corvette "Stormbreaker".** Vaisseau multi-rôle. | Véhicule | 🔶 | — | Speed 18 (espace). Armure 14. PV 60. 12 passagers. Tourelle 3d8 + missiles 4d10. 5 HP. | 4 |

---

## TABLE 8 — LOOT CONTREBANDE

> Marchés noirs, planques de gang, caches de trafiquants, vaisseaux de contrebandiers, arrière-boutiques de Neon.

| d20 | Objet | Type | Rareté | Bonus | Qualités | TL |
|---|---|---|---|---|---|---|
| 1 | **Fausse identité (basique).** Passe un contrôle visuel, pas biométrique. | Gadget | ◻ | — | Avantage en Tromperie pour se faire passer pour quelqu'un d'autre. | 1 |
| 2 | **Alcool de contrebande (caisse).** Whisky de qualité. Vaut $300. | Consommable | ◻ | — | Monnaie d'échange. 1 dose = +1d4 PV récupérés sur Stretch Rest. | 0 |
| 3 | **Munitions perforantes (×20).** Sous-calibrées, illégales. | Consommable | ◻ | — | Pierce 1 pendant 1 combat (1 arme). Puis épuisées. | 2 |
| 4 | **Brouilleur de communications.** Compact, rayon 30 cases. | Gadget | ◻ | +0 | Bloque toutes les radios/comms dans la zone. 1 Shift d'autonomie. | 2 |
| 5 | **Serrure piratée "Skeleton".** Passe-partout électronique. | Outil | ◻ | +0 | Avantage Escamotage/Informatique pour serrures électroniques civiles. | 2 |
| 6 | **Drogue "Boost" (×4).** Stimulant illégal, populaire sur Neon. | Consommable | ◻ | — | +2 à 1 Score de compétence, 1 Stretch. Ensuite : Épuisé + Stressé. | 2 |
| 7 | **Pistolet "Ghost".** Compact, pas de pièces métalliques. | Arme | 🔷 | +0 | 1d4. Portée 6. Indétectable aux scanners. Fragile. | 2 |
| 8 | **Gilet discret "Whisper".** Se porte sous une chemise. | Armure (L) | 🔷 | **+1** | Armure 4. Invisible sous vêtements. Résiste à 1 scan. | 2 |
| 9 | **Scrambler facial.** Brouille les caméras de reconnaissance. | Gadget | 🔷 | — | Immunisé à l'identification par caméra/IA. Personnel. 1 Shift. | 3 |
| 10 | **Implant "Poker Face".** Régulation émotionnelle. | Implant | 🔷 | **+1 EMP** | +1 EMP. Immunisé à Intuition (intentions illisibles). 1 slot. | 3 |
| 11 | **Kit de déguisement pro.** Maquillage, prothèses, modulateur vocal. | Outil | 🔷 | **+1** | +1 Tromperie. Déguisement complet en 1 Stretch. | 1 |
| 12 | **Nano-poison "Silent" (×2).** Action lente, indétectable. | Consommable | 🔷 | — | 1d6 PV/heure, 6h. Save STR chaque heure. Indétectable sans Sciences diff 3. | 3 |
| 13 | **Coffre-fort "Vault".** Anti-scan, anti-EMP. | Gadget | 🔷 | — | Contenu invisible aux scanners. Résiste à Informatique diff 4. 10 kg max. | 2 |
| 14 | **Fausse identité (premium).** Biométrie clonée, passeport interstellaire. | Gadget | 🔷 | — | Passe les scans biométriques civils. Avantage Tromperie. | 3 |
| 15 | **Pistolet "Keelhauler".** Arme de contrebandier légendaire. | Arme | 🔷 | **+2** | 1d8. Portée 10. Dissimulable. 1 HP libre. | 2 |
| 16 | **Implant de traduction universelle.** Traducteur neuronal. | Implant | 🔷 | **+1 EMP** | Toutes les langues connues. +1 EMP (social). 1 slot. | 3 |
| 17 | **Drogue "Clarity" (×2).** Nootropique de pointe, très rare. | Consommable | 🔶 | — | Avantage sur TOUS les jets WIT, 1 Shift. Puis : Confus + Stressé 1 Shift. Addictif. | 3 |
| 18 | **Armure "Shade".** Exo-armure furtive, camouflage actif. | Armure (M) | 🔶 | **+2** | Armure 6. Avantage permanent Discrétion. Silencieuse. | 3 |
| 19 | **Lame monofilament "Razorwire".** Un seul atome d'épaisseur. | Arme | 🔶 | **+2** | 1d10. Reach 1. Finesse. Pierce 3. Fragile. | 4 |
| 20 | **Kit de contrefaçon "Mint".** Imprimante moléculaire portable. | Outil | 🔶 | **+3** | Crée copies d'objets ≤ TL 2, ≤ 30 cm. 1 objet/Shift. Durent 1 semaine. | 4 |

---

## GUIDE DU MJ — Gestion du loot en jeu

### Quand rouler sur les tables

| Moment | Action |
|---|---|
| **Après un combat** | 1 jet par ennemi significatif éliminé (Adversaire ou Boss, pas les Minions). |
| **Exploration d'un lieu** | 1 jet par zone intéressante fouillée (Stretch de fouille). |
| **Récompense de mission** | Le donneur d'ordre offre 1-2 objets choisis (MJ sélectionne, pas de jet). |
| **Marché noir / commerce** | Le joueur peut acheter des objets Standard au prix normal. Les Rares coûtent 2-3× plus. Les Légendaires ne s'achètent pas — ils se trouvent ou se gagnent. |

### Ajuster la rareté

| Modificateur | Quand l'appliquer | Effet |
|---|---|---|
| **-2 au d20** | Zone pauvre, pillée, ou dangereuse | Plus d'objets Standard, moins de Rare |
| **Normal** | Zone standard | Distribution 50/40/10 |
| **+2 au d20** | Base ennemie importante, coffre-fort, boss loot | Plus de Rare, légendaires possibles sur 17+ |
| **+4 au d20** | Trésor de campagne, récompense finale d'arc | Rare garanti, légendaire sur 19+ |

> **Résultats >20 :** Si le d20 modifié dépasse 20, le MJ roule deux fois sur la table et le joueur choisit un des deux résultats, OU le MJ donne l'objet 20 (Légendaire) de la table.

### Rotation du loot — Garder la boucle vivante

La boucle **Acquérir → Utiliser → Perdre → Remplacer** est le cœur du système. Voici les leviers du MJ :

| Levier | Fréquence recommandée | Exemple |
|---|---|---|
| **Push de jet** | Chaque session (choix du joueur) | "Je pousse mon jet de Tir — mon fusil est Endommagé (+2 → +1)." |
| **Critique ennemi (Réussite critique)** | 1-2× par arc | Le boss place un crit, le MJ dégrade l'armure du PJ. |
| **Pouvoir de monstre** | Variable | EMP frit l'implant. L'acide ronge l'armure. Le hacker jam le drone. |
| **Perte narrative** | 1× par arc | Capturés, dépouillés. L'équipement est dans le coffre ennemi — la session devient "le récupérer". |
| **Environnement** | Rare | L'explosion effondre le bâtiment — 1 objet par PJ risque d'être Endommagé (save DEX). |

> **Règle d'or :** Ne jamais détruire l'objet favori d'un joueur sans lui donner une chance de le sauver ou de le remplacer par quelque chose d'aussi intéressant. L'objectif est la tension et le renouvellement, pas la frustration.

### Exemple de session type

**Début de session :** L'équipe a été embauchée pour infiltrer un labo corpo. Le Grounder a un fusil +1, l'Infiltrator un pistolet +1 et des faux papiers +1, le Tech a un deck de hacking +1.

**Milieu de session :** Combat dans le labo. Le Grounder pousse un jet raté — son fusil passe de +1 à Endommagé (+0). L'Infiltrator prend un crit ennemi — le MJ dégrade son gilet balistique. Le Tech hack un terminal (table Corporatif, résultat 12 : Deck "Razor" +1). Il upgraderait son deck actuel — mais il a déjà un +1. Il le garde comme backup.

**Fin de session :** La mission réussie. Le patron offre un objet au choix dans la table Militaire (résultat 16 : Fusil magnétique "Tempest" +1). Le Grounder remplace son fusil Endommagé. L'Infiltrator fouille le labo (table Corporatif, résultat 15 : Implant oculaire "Eagle Eye" +1 WIT). Nouveau jouet.

**Bilan :** Un objet perdu (fusil dégradé), un objet remplacé (nouveau fusil), un objet gagné (implant). La boucle tourne. Les Scores bougent. Le jeu vit.

---

## RÉFÉRENCE RAPIDE — Bonus par rareté

| | ◻ Standard | 🔷 Rare | 🔶 Légendaire |
|---|---|---|---|
| **Bonus** | +0 | +1 à +2 | +2 à +3 |
| **Qualités** | 0-1 | 1-2 | 2-3 |
| **d20** | 1-10 | 11-18 | 19-20 |
| **Endommagé** | +0 | +0 à +1 | +1 |
| **Détruit** | Inutilisable | Inutilisable | Inutilisable |
| **Se trouve** | Partout | Zones spécifiques, missions | Événements narratifs majeurs |
| **S'achète** | Oui (prix normal) | Oui (2-3× prix) | Non (se gagne) |
