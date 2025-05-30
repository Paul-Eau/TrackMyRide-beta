# Changelog - TrackMyRide
---

## Version beta-0.9.0 - 30 mai 2025

### 🎉 Nouvelles fonctionnalités

#### 🚴‍♂️ Suivi et enregistrement
- **Enregistrement automatique** : Détection intelligente des déplacements à vélo
- **Suivi en arrière-plan** : Continuité d'enregistrement même quand l'app est fermée
- **Géofencing** : Zones de détection pour l'activation automatique
- **BackgroundFetch** : Optimisation pour iOS avec gestion des événements en arrière-plan pour maintenir le service actif
- **Modes de suivi** : Manuel et automatique avec basculement intelligent

#### 📊 Statistiques et analyses
- **Tableau de bord complet** : Vue d'ensemble avec statistiques jour/semaine/mois/année
- **Graphiques détaillés** : Vitesse, altitude, distance avec visualisations interactives
- **Comparaisons temporelles** : Évolution des performances sur différentes périodes
- **Records personnels** : Suivi des meilleures performances (distance, vitesse, dénivelé)
- **Statistiques hebdomadaires** : Graphiques en barres avec données de progression

#### 🗺️ Cartes et navigation
- **Multiples fournisseurs de cartes** : OpenStreetMap, Thunderforest, Cycling, Topo
- **Points d'intérêt** : Points d'eau, parkings vélo, stations de réparation
- **Itinéraires** : Planification et suivi de parcours
- **Visualisation des trajets** : Affichage détaillé avec profil d'altitude
- **Navigation en temps réel** : Guidage turn-by-turn

#### 🏆 Gamification et progression
- **Système de niveaux** : 100 niveaux avec titres et émojis uniques (à finir)
- **Séquences d'activité** : Suivi des jours consécutifs d'activité (à finir)
- **Achievements** : Badges et récompenses pour différents accomplissements (à finir)
- **Classements** : Comparaison avec amis par distance, vitesse, dénivelé (à finir)
- **Défis** : Objectifs personnalisables (distance, durée, sorties) (à finir)

#### 👥 Social et communauté
- **Profils utilisateur** : Informations personnelles et statistiques publiques
- **Feed social** : Partage d'activités, records et achievements (à finir)
- **Classement des amis** : Leaderboard hebdomadaire avec tendances
- **Stories** : Partage d'moments forts de vos sorties (à finir)
- **Groupes** : Communautés de cyclistes (à venir)

#### ⚙️ Paramètres et personnalisation
- **Thème sombre/clair** : Interface adaptative (à finir)
- **Notifications** : Alertes configurables pour fin de trajets (à finir)
- **Gestion des données** : Export/import de base de données (à finir)
- **Mode économie d'énergie** : Optimisation de la batterie (à finir)
- **Paramètres de localisation** : Contrôle précis des permissions

### 🔧 Améliorations techniques

#### 📱 Interface utilisateur
- **Navigation par onglets** : Home, Cartes, Trajets, Social, Profil
- **Animations fluides** : Transitions et micro-interactions optimisées (à finir)
- **Responsive design** : Adaptation automatique aux différentes tailles d'écran
- **Accessibilité** : Support des lecteurs d'écran et navigation au clavier
- **Gestion d'état** : Contextes React pour la localisation et les thèmes

#### 🔋 Performance et optimisation
- **Base de données SQLite** : Stockage local optimisé
- **Cache intelligent** : Réduction des requêtes réseau
- **Lazy loading** : Chargement progressif des composants
- **Memory management** : Gestion optimisée de la mémoire Android
- **Background processing** : Traitement en arrière-plan efficace

#### 🛠️ Développeur et debugging
- **Système de logs** : Traçabilité complète des événements
- **Screen de logs** : Interface de debug intégrée
- **Export de données** : Sauvegarde complète pour support technique
- **Gestion d'erreurs** : Capture et reporting des erreurs
- **Version de développement** : Outils de debug avancés

### 🐛 Corrections de bugs

#### 🗺️ Géolocalisation
- Correction des permissions de localisation en arrière-plan
- Amélioration de la précision GPS
- Fix des problèmes de géofencing
- Optimisation de la consommation batterie pour le tracking

#### 📊 Interface et navigation
- Correction des animations saccadées sur Android
- Fix du scroll horizontal dans les graphiques
- Amélioration de la responsive design sur petits écrans

#### 💾 Stockage et synchronisation
- Fix des problèmes de sauvegarde des trajets
- Correction des erreurs de base de données
- Amélioration de la synchronisation des statistiques
- Fix des fuites mémoire lors des opérations de stockage

### 🔒 Sécurité et confidentialité

#### 🛡️ Protection des données
- Chiffrement local des données sensibles
- Gestion sécurisée des tokens d'authentification
- Anonymisation des données de localisation

#### 🔐 Authentification
- Authentification Firebase sécurisée
- Gestion des sessions utilisateur
- Protection contre les attaques CSRF
- Validation côté client et serveur

### 📋 Notes techniques

#### 🔧 Dépendances principales
- React Native 0.76.9
- Expo SDK 52
- Firebase 11.8.1
- React Navigation 6.x
- SQLite pour le stockage local
- Background Geolocation pour le suivi

#### 📱 Compatibilité
- iOS 15.0+
- Android 9.0+ (API level 28+)
- Support des dernières versions d'iOS et Android

#### 🌐 Services externes
- Firebase pour l'authentification et le stockage cloud
- OpenStreetMap pour les cartes
- Thunderforest pour les cartes spécialisées cyclisme
- Services de géocodage pour les adresses

### 📝 Notes pour les développeurs

#### 🔄 Architecture
- Architecture modulaire avec séparation des services
- Patterns Repository pour l'accès aux données
- Context providers pour la gestion d'état globale
- Hooks personnalisés pour la logique métier

#### 🧪 Testing
- Tests unitaires pour les fonctions critiques
- Tests d'intégration pour les services
- Tests de performance pour les opérations coûteuses
- Tests de régression automatisés

---


## Version alpha-0.1.0 - 11 avril 2025

### 🎉 Première version - Fonctionnalités de base

#### 🚴‍♂️ Suivi GPS fondamental
- **Enregistrement manuel** : Bouton start/stop pour commencer et arrêter l'enregistrement
- **Géolocalisation en temps réel** : Suivi de position avec GPS natif
- **Calcul de distance** : Mesure basique de la distance parcourue
- **Chronomètre** : Temps de trajet avec affichage en temps réel
- **Vitesse instantanée** : Calcul de la vitesse actuelle en km/h

#### 📊 Statistiques simples
- **Données de base** : Distance, durée, vitesse moyenne par trajet
- **Liste des trajets** : Historique simple avec date et statistiques
- **Visualisation basique** : Affichage des métriques principales

#### 🗺️ Carte simple
- **Carte OpenStreetMap** : Affichage de la position actuelle
- **Zoom automatique** : Adaptation de la vue selon le trajet

#### 💾 Stockage local
- **Base de données SQLite** : Sauvegarde locale des trajets
- **Persistance des données** : Conservation des trajets entre les sessions
- **Gestion basique** : Possibilité de supprimer les trajets individuellement

### 🔧 Architecture initiale

#### 📱 Interface de base
- **Écran principal** : Carte avec boutons start/stop
- **Écran trajets** : Liste simple des trajets enregistrés
- **Navigation basique** : Tabs simples entre les écrans principaux
- **Design minimaliste** : Interface claire et fonctionnelle

#### ⚙️ Paramètres essentiels
- **Permissions** : Gestion des autorisations de géolocalisation
- **Préférences de base** : Unités (km/h, mph), format de temps
- **À propos** : Informations sur l'application et version

### 🐛 Limitations connues (Version Alpha)

#### 🔋 Performance
- **Consommation batterie** : Optimisation basique du GPS
- **Enregistrement auto** : Ne fonctionne pas quand l'app est kill mais uniquement en background et foreground
- **Stockage** : Pas de limite sur l'espace de stockage utilisé

#### 📱 Compatibilité
- **Test limité** : Testé sur un nombre restreint d'appareils (iOS)
- **Fonctionnalités manquantes** : Pas de suivi en arrière-plan (broken)
- **Export de données** : Pas encore implémenté

### 📋 Technologies utilisées

#### 🔧 Stack technique
- **React Native** : Framework principal (version 0.72)
- **Expo** : Plateforme de développement (SDK 49)
- **SQLite** : Base de données locale
- **React Navigation** : Navigation entre écrans
- **React Native Maps** : Affichage des cartes

#### 📍 Services
- **Expo Location** : Service de géolocalisation
- **OpenStreetMap** : Fournisseur de cartes par défaut
- **Calculs géospatial** : Algorithmes de distance basiques

### 🎯 Objectifs de cette version alpha

#### ✅ Proof of Concept
- Validation du concept de base : enregistrement de trajets vélo manuel et automatique
- Test de la géolocalisation en temps réel
- Interface utilisateur fonctionnelle minimale
- Stockage et récupération des données

#### 🧪 Tests et feedback
- Identification des bugs critiques
- Validation de l'architecture technique
- Test de performance sur différents appareils (iOS)

### 📝 Notes de développement

#### 🔄 Processus
- Développement en mode Expo managed workflow
- Tests sur simulateur iOS et émulateur Android
- Déploiement via Expo Developement Build pour les tests
- Version de développement avec logs étendus

#### 🚧 En cours de développement
- Interface plus polie prévue pour la beta
- Optimisations de performance à venir
- Fonctionnalités avancées en cours de planification
- Tests sur plus d'appareils réels

---

**Note Alpha** : Cette version alpha représente la première implémentation fonctionnelle de TrackMyRide (Vélo!). Elle contient les fonctionnalités essentielles pour enregistrer et visualiser des trajets à vélo, servant de base pour les développements futurs.

---

## 🚀 Prochaines versions

### Version 0.9.5 (prévue pour juin 2025)
- Détection d'activité automatique pour seulement enresitré les trajets à vélo
- Intégration complète des groupes et défis communautaires
- Import/export GPX complet avec métadonnées

### Version 1.0.0 (prévue pour juillet / août 2025)
- Navigation GPS avancée avec BRouter (setup local server for GeoJson queries)
- Version stable complète
- Support des capteurs Bluetooth (cardio, vitesse, cadence)

### Version 1.1.0 (prévue pour juillet / août 2025)
- Analytics avancées avec IA
- Synchronisation multi-appareils


---

# ToDo - TrackMyRide

## To Fix
- Si appuis sur bouton pour terminer tracking manuel, ne rien faire si moins de 5 positions enregistrées dans la base de données cache
- Ajoute d'une note aux trajets sauvegardées (après la fin de l'enregistrement ou la vue TripDetails)
- Récupérer la dernière position pour avoir le trajet depuis le point de départ et non pas depuis le lancement du service de BGLOC
- GPX import / export : il faut les bons timestamps, le vitesse et l'élévation

## To Add
- Détection d'activité pour enregistrement auto
- Changer le système d'itinéraire par BRouter
- "Ajouter un POI" depuis LongPressBottomSheet


## Idées

- Peut être mieux pour la batterie de : `await switchToFilterProvider();` quand sur pause ? 


---

**Copyright © 2025 Vélo! - TrackMyRide**

*Pour signaler un bug ou suggérer une amélioration, utilisez la fonction "Support" dans les paramètres de l'application.* (pas encore implémentée)