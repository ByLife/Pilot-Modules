## 📖 COURS DÉTAILLÉ

### LEÇON 6.1 : CARTES AÉRONAUTIQUES ET REPÉRAGE

#### Types de Cartes Aéronautiques

**CARTE OACI 1/500 000 :**

- **Échelle :** 1 cm = 5 km
- **Usage :** Navigation VFR (vol à vue)
- **Contenu :** Relief, obstacles, aérodromes, espaces aériens
- **Mise à jour :** Régulière (cycles AIRAC)

**CARTE D'APPROCHE À VUE :**

- **Échelle :** Variable selon aérodrome
- **Usage :** Arrivée et départ des aérodromes
- **Contenu :** Circuits, points de report, obstacles locaux

#### Symboles et Conventions

**RELIEF ET OBSTACLES :**

- **Courbes de niveau :** Lignes continues (altitude identique)
- **Points cotés :** Altitude maximale d'une zone
- **Obstacles artificiels :** Tours, antennes, lignes électriques
- **Altitude de sécurité :** Hauteur minimale dans chaque zone

**AÉRODROMES :**

- **Contrôlé :** Cercle bleu avec tours de contrôle
- **Non contrôlé :** Cercle magenta sans services
- **Militaire :** Symboles spécifiques selon restrictions
- **Hélistation :** Symbole H dans carré

**ESPACES AÉRIENS :**

- **Zone contrôlée :** Contours bleus avec limites verticales
- **Zone réglementée :** Contours rouges (R)
- **Zone dangereuse :** Contours rouges (D)
- **Zone interdite :** Contours rouges (P pour Prohibited)

#### Navigation par Repères Visuels

**LIGNES DE REPÈRE :**

- **Littoraux :** Côtes, plages, falaises
- **Cours d'eau :** Rivières, fleuves, canaux
- **Voies de communication :** Autoroutes, voies ferrées
- **Relief :** Montagnes, collines, vallées distinctives

**POINTS DE REPÈRE :**

- **Villes et agglomérations :** Facilement identifiables de haut
- **Installations industrielles :** Centrales, usines, tours de refroidissement
- **Ouvrages d'art :** Ponts caractéristiques, viaducs
- **Plans d'eau :** Lacs, étangs, retenues

**RÈGLES DE REPÉRAGE :**

1. **Trianguler :** Utiliser au moins 2 repères pour se positionner
2. **Anticiper :** Préparer le repère suivant avant de perdre le précédent
3. **Confirmer :** Vérifier avec les instruments (cap, temps, distance)

### LEÇON 6.2 : CALCULS DE NAVIGATION

#### Le Triangle des Vitesses

**LES TROIS VITESSES :**

**1. VITESSE VRAIE (TAS - True Airspeed) :**

- Vitesse réelle de l'avion dans la masse d'air
- Calculée à partir de la vitesse indiquée + corrections altitude/température
- Utilisée pour tous les calculs de navigation

**2. VITESSE PROPRE (GS - Ground Speed) :**

- Vitesse de l'avion par rapport au sol
- TAS corrigée du vent (favorable ou défavorable)
- Détermine le temps de parcours réel

**3. VITESSE DU VENT (Wind Speed) :**

- Vitesse et direction du vent
- Influence directement la vitesse sol et la dérive

#### Cap et Dérive

**DÉFINITIONS :**

**CAP VRAI (True Heading) :**

- Direction où pointe le nez de l'avion (par rapport au nord géographique)
- Ce que maintient le pilote au manche

**ROUTE VRAIE (True Track) :**

- Direction réelle de déplacement au sol
- Objectif de navigation (relier point A au point B)

**DÉRIVE :**

- Angle entre le cap et la route
- Causée par le vent de travers
- **Vent de droite → dérive à gauche (angle négatif)**
- **Vent de gauche → dérive à droite (angle positif)**

#### Formules de Base

**CALCUL DE DÉRIVE :**

```
Dérive = arcsin (Vitesse vent × sin(angle vent) / TAS)
```

**CALCUL DE VITESSE SOL :**

```
GS = TAS × cos(dérive) + Vent × cos(angle vent - dérive)
```

**CALCUL DE TEMPS DE VOL :**

```
Temps = Distance / Vitesse sol
```

**CALCUL DE CONSOMMATION :**

```
Carburant = Débit horaire × Temps de vol
```

### LEÇON 6.3 : INSTRUMENTS DE NAVIGATION

#### Le Compas Magnétique

**UTILISATION EN NAVIGATION :**

- Instrument de base, fonctionne sans énergie
- Référence pour caler le directionnel
- Secours en cas de panne électrique

**CORRECTIONS NÉCESSAIRES :**

**1. DÉCLINAISON MAGNÉTIQUE :**

- Différence entre nord magnétique et nord géographique
- Varie selon la position géographique
- À ajouter ou soustraire selon la région

**2. DÉVIATION :**

- Erreur due aux masses métalliques de l'avion
- Varie selon le cap
- Corrigée par table de déviation spécifique à l'avion

**PASSAGE DES CAPS :**

- **Cap compas → Cap magnétique :** Corriger déviation
- **Cap magnétique → Cap vrai :** Corriger déclinaison
- **Mnémotechnique :** "De Cadix à Magnésie, on Va Toujours" (Déviation-Cadix-Magnétique-Vrai-Toujours)

#### Radionavigation VOR

**PRINCIPE VOR (VHF Omnidirectional Range) :**

- Station au sol émettant des signaux directionnels
- 360 radiales numérotées à partir du nord magnétique
- Réception par équipement de bord

**UTILISATION :**

**1. RELÈVEMENT :**

- Déterminer sa position par rapport à la station
- Tourner le sélecteur jusqu'à aiguille centrée
- Lire la radiale sous l'index

**2. NAVIGATION :**

- Sélectionner la radiale désirée
- Suivre l'aiguille (gauche/droite) pour rester sur la radiale
- CDI (Course Deviation Indicator) indique les écarts

**INTERCEPTION DE RADIALE :**

1. Identifier la radiale à intercepter
2. Prendre un cap d'interception (30-45° avec la radiale)
3. Surveiller l'aiguille CDI
4. Quand l'aiguille commence à bouger, virer sur la radiale

#### Navigation GPS

**AVANTAGES DU GPS :**

- Précision élevée (quelques mètres)
- Couverture mondiale
- Informations multiples (position, cap, vitesse, ETA)
- Base de données complète

**FONCTIONS PRINCIPALES :**

**DIRECT TO :**

- Navigation directe vers un point
- Calcul automatique cap et distance
- Mise à jour continue

**FLIGHT PLAN :**

- Navigation sur route programmée
- Guidage de point en point
- Alertes de virage

**INFORMATIONS AFFICHÉES :**

- Position actuelle (latitude/longitude)
- Cap et route suivis
- Vitesse sol actuelle
- Distance et temps restants
- ETA (Estimated Time of Arrival)

### LEÇON 6.4 : ESPACES AÉRIENS

#### Classification des Espaces Aériens

**ESPACE AÉRIEN CONTRÔLÉ :**

**CLASSE D :**

- **Altitudes :** Surface → altitude spécifiée
- **Équipement :** Radio obligatoire
- **Contact :** Autorisation requise pour entrer
- **Séparation :** IFR/IFR et IFR/VFR assurée

**CLASSE E :**

- **Altitudes :** Généralement à partir de 1000 ft sol
- **Équipement :** Aucun requis en VFR
- **Contact :** Aucune autorisation requise
- **Séparation :** IFR/IFR seulement

**ESPACE AÉRIEN NON CONTRÔLÉ :**

**CLASSE G :**

- **Altitudes :** Surface → base espace contrôlé
- **Équipement :** Aucun requis
- **Contact :** Aucune autorisation requise
- **Responsabilité :** Pilote assure sa propre séparation

#### Zones Particulières

**ZONES RÉGLEMENTÉES (R) :**

- **Définition :** Activités dangereuses pour l'aviation
- **Exemples :** Tirs militaires, parachutage, acrobatie
- **Usage :** Éviter ou obtenir autorisation

**ZONES DANGEREUSES (D) :**

- **Définition :** Dangers potentiels sans interdiction formelle
- **Exemples :** Activités industrielles, obstacles
- **Usage :** Prudence, éviter si possible

**ZONES INTERDITES (P) :**

- **Définition :** Survol absolument interdit
- **Exemples :** Installations sensibles, résidences officielles
- **Usage :** Contournement obligatoire

#### Règles de Vol à Vue (VFR)

**CONDITIONS MÉTÉOROLOGIQUES VFR :**

**ESPACE AÉRIEN CONTRÔLÉ :**

- **Visibilité :** ≥ 8 km (≥ 5 km si < 3000 ft AMSL)
- **Distance nuages :** 1500 m horizontalement, 1000 ft verticalement
- **Plafond :** ≥ 1500 ft

**ESPACE AÉRIEN NON CONTRÔLÉ :**

- **Visibilité :** ≥ 5 km (≥ 1,5 km si < 3000 ft AMSL)
- **Distance nuages :** Hors des nuages et en vue du sol
- **Plafond :** Variable selon altitude

**RÈGLES DE PRIORITÉ :**

1. **Aéronef en détresse :** Priorité absolue
2. **Planeurs et ballons :** Priorité sur avions motorisés
3. **Avion plus lourd :** Priorité sur plus léger
4. **Convergence :** Priorité à droite
5. **Dépassement :** Par la droite
6. **Face à face :** Chacun vire à droite

## 📋 FICHE MÉMO - MODULE 6

### CARTES NAVIGATION

- **OACI 1/500 000 :** Navigation VFR (1 cm = 5 km)
- **Symboles :** Relief, obstacles, aérodromes, espaces aériens
- **Repères :** Lignes (côtes, rivières, routes) + Points (villes, lacs)

### TRIANGLE DES VITESSES

- **TAS :** Vitesse vraie dans l'air (calculs navigation)
- **GS :** Vitesse sol (détermine temps de vol)
- **Vent :** Influence GS et crée dérive

### DÉRIVE

- **Cause :** Vent de travers
- **Effet :** Écart entre cap (direction avion) et route (trajet sol)
- **Vent de droite → dérive gauche, vent de gauche → dérive droite**

### NAVIGATION

- **Compas :** Corrections déviation + déclinaison magnétique
- **VOR :** Radiales (0-360°) depuis station
- **GPS :** Précision élevée, direct to, flight plan

### ESPACES AÉRIENS

- **Classe D :** Contrôlé, radio + autorisation obligatoire
- **Classe E :** Contrôlé, séparation IFR seulement
- **Classe G :** Non contrôlé, pilote responsable séparation

### CONDITIONS VFR MINIMALES

- **Contrôlé :** Visibilité 8 km, distance nuages 1500m/1000 ft
- **Non contrôlé :** Visibilité 5 km, hors nuages

## 🔧 EXERCICES PRATIQUES

### QCM

**1. Sur une carte au 1/500 000, 1 cm représente :** a) 500 m b) 5 km c) 50 km d) 500 km

**2. La dérive est causée par :** a) Les erreurs de compas b) Le vent de travers c) La déclinaison magnétique d) Les erreurs de pilotage

**3. En espace aérien de classe D, il faut :** a) Seulement une radio b) Une autorisation pour entrer c) Aucun équipement particulier d) Seulement un transpondeur

**4. Un vent de droite crée une dérive :** a) À droite b) À gauche c) Nulle d) Variable

**5. Les conditions VFR en espace contrôlé exigent une visibilité minimale de :** a) 1,5 km b) 5 km c) 8 km d) 10 km

### VRAI/FAUX

**6. La vitesse sol est toujours égale à la vitesse vraie (V/F)** **7. Une zone interdite (P) peut être traversée avec autorisation (V/F)** **8. Le GPS remplace complètement le compas magnétique (V/F)** **9. En classe G, le pilote assure sa propre séparation (V/F)** **10. La déclinaison magnétique est identique partout dans le monde (V/F)**

### DÉFINITIONS

**11. La _______ est l'angle entre le cap et la route causé par le vent.**

**12. Une _______ VOR est une ligne magnétique partant de la station.**

**13. L'espace aérien de classe __ est non contrôlé.**

**14. La _______ _______ est la vitesse de l'avion par rapport au sol.**

**15. La _______ magnétique est la différence entre nord géographique et nord magnétique.**

## 🖼️ SCHÉMAS EXPLICATIFS

### SCHÉMA 1 : Triangle des Vitesses

```
Description : Triangle vectoriel
- Vecteur TAS : vitesse vraie de l'avion (direction du cap)
- Vecteur vent : vitesse et direction du vent
- Vecteur résultant GS : vitesse sol (direction de la route)
- Angle de dérive entre cap et route
- Exemple : TAS 100 kt, vent 20 kt travers → GS et dérive résultants
```

### SCHÉMA 2 : Navigation VOR

```
Description : Station VOR au centre avec radiales
- Cercle avec 360 radiales numérotées tous les 10°
- Radiale 090 (Est), 180 (Sud), 270 (Ouest), 360 (Nord)
- Avion sur radiale 045 avec indicateur CDI
- Aiguille CDI centrée = sur radiale sélectionnée
- Aiguille droite = avion à gauche de la radiale
```

### SCHÉMA 3 : Espaces Aériens

```
Description : Coupe verticale des espaces aériens
- Sol (0 ft) : base classe G
- 1000 ft : base classe E (généralement)
- Zone de contrôle classe D autour aérodrome (surface → altitude)
- Limites verticales et horizontales clairement marquées
- Zones spéciales (P, R, D) superposées
```

## ⭐ POINTS CLÉS À RETENIR

1. **Navigation = triangulation :** Toujours utiliser plusieurs repères pour se positionner
2. **Vent = ami ou ennemi :** Comprendre son effet sur cap, route et temps de vol
3. **Espaces aériens = règles :** Connaître les règles d'utilisation de chaque classe
4. **Redondance navigation :** Compas + GPS + repères visuels = sécurité
5. **Conditions VFR = limites :** Respecter les minimas météo pour voler légalement

## ✅ AUTO-ÉVALUATION MODULE 6

### QUESTIONS

**Question 1 (5 points) :** Expliquez le phénomène de dérive. Un avion vole cap 090° avec un vent de 030° pour 20 kt. Dans quel sens sera la dérive et pourquoi ?

**Question 2 (4 points) :** Décrivez les trois étapes pour corriger les indications du compas magnétique et obtenir un cap vrai.

**Question 3 (4 points) :** Quelles sont les conditions météorologiques minimales pour le vol VFR en espace aérien contrôlé ?

**Question 4 (3 points) :** Différenciez les zones P, R et D. Laquelle est la plus restrictive ?

**Question 5 (4 points) :** Comment utilise-t-on un VOR pour : a) déterminer sa position, b) naviguer vers une station ?

### CORRIGÉ

**Réponse 1 :** La dérive est l'angle entre le cap (direction du nez de l'avion) et la route (trajet réel au sol) causé par le vent de travers.

Avec cap 090° et vent 030°/20 kt :

- Le vent vient de 030° (du nord-est)
- Il frappe l'avion sur le côté droit avant
- L'avion sera poussé vers la gauche (sud) de sa route
- **Dérive à gauche (négative)**
- Pour maintenir route 090°, il faudra prendre un cap légèrement nord (ex: 095°)

**Réponse 2 :**

1. **Cap compas → Cap magnétique :** Corriger la déviation (erreur due aux masses métalliques, table de déviation)
2. **Cap magnétique → Cap vrai :** Corriger la déclinaison magnétique (différence nord magnétique/géographique)
3. **Formule :** Cap vrai = Cap compas + Déviation + Déclinaison (Les corrections peuvent être positives ou négatives selon les valeurs)

**Réponse 3 :** **Conditions VFR minimales en espace contrôlé :**

- **Visibilité :** ≥ 8 km (≥ 5 km si altitude < 3000 ft AMSL)
- **Distance des nuages :** 1500 m horizontalement, 1000 ft verticalement
- **Plafond :** ≥ 1500 ft au-dessus du sol
- **Références visuelles :** Contact visuel permanent avec le sol

**Réponse 4 :**

- **Zone P (Prohibited) :** Survol **INTERDIT** en permanence, contournement obligatoire
- **Zone R (Restricted) :** Activité **RÉGLEMENTÉE**, éviter ou demander autorisation
- **Zone D (Dangerous) :** Activité **DANGEREUSE** mais pas interdite, prudence recommandée

**Zone P est la plus restrictive** (interdiction absolue).

**Réponse 5 :** **a) Déterminer sa position :**

- Tourner le sélecteur de radiale jusqu'à ce que l'aiguille CDI soit centrée avec indication "FROM"
- Lire la radiale sous l'index → on est SUR cette radiale
- Croiser avec une autre radiale VOR ou repère pour position exacte

**b) Naviguer vers la station :**

- Sélectionner 360° (ou 000°)
- Suivre l'aiguille CDI : aiguille à gauche → virer à gauche, aiguille à droite → virer à droite
- Quand aiguille centrée avec "TO" → cap direct vers la station

---
