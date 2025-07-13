# 📊 Analyse des ventes – Projet Excel Data Analytics

## 🟦 1. Introduction

Ce projet a été réalisé dans le cadre de la pratique des compétences en **analyse de données avec Excel**.  
Il s'agit d’une **analyse des ventes** à partir d’un fichier de commandes clients, comprenant des informations sur les produits, les clients, les prix, les quantités, les villes et les méthodes de paiement.

**Objectifs principaux :**
- Nettoyer et enrichir les données
- Créer des indicateurs clés (KPIs)
- Analyser les ventes avec des **tableaux croisés dynamiques (TCD)**
- Construire un **dashboard interactif**

---

## 🟧 2. Jeu de données

**Colonnes principales :**
- `Order_ID` : identifiant de commande  
- `Date_Commande` : date de la commande  
- `Client`, `Produit`, `Catégorie`  
- `Prix_Unitaire`, `Quantité`  
- `Ville`, `Pays`  
- `Paiement` : méthode de paiement  

**Qualité des données :**
- ✅ Pas de valeurs manquantes
- ✅ Pas de doublons
- ✅ Pas d’incohérences (prix ou quantité négative, erreurs de frappe)
- ✅ Formats corrigés (dates, nombres)

---

## 🟨 3. Préparation et enrichissement

**Colonnes ajoutées :**
- `CA` (Chiffre d’affaires) = Prix_Unitaire × Quantité  
- `Mois_Année` = Mois de la commande (format AAAA-MM)

**Calculs effectués :**
- Total des ventes  
- Nombre de commandes  
- Quantité totale vendue  
- Nombre de clients uniques  

---

## 🟩 4. Analyses et visualisations

Création de **tableaux croisés dynamiques (TCD)** et de **graphiques** pour explorer les données :

- **CA par ville** (barres verticales)
- **Top 5 produits** (barres horizontales)
- **Répartition des paiements** (camembert)
- **Évolution mensuelle du CA** (courbe)

---

## ℹ️ Qu’est-ce qu’un TCD ?

Un **Tableau Croisé Dynamique (TCD)** est une fonctionnalité d’Excel qui permet de :
- Résumer et agréger des données (somme, moyenne, nombre, etc.)
- Regrouper les résultats par catégories (ex : par ville, produit, mois)
- Créer des rapports dynamiques sans formules complexes
- Ajouter des **segments** pour filtrer les données de manière interactive

C’est un outil très puissant pour l’analyse de données !

---

## 🟪 5. Dashboard final

- Zone KPI avec :
  - 💰 CA total
  - 📦 Nombre de commandes
  - 👥 Clients uniques
  - 🛍️ Quantité vendue
- Graphiques intégrés :
  - Barres : CA par ville
  - Colonnes : Top 5 produits
  - Camembert : Paiement
  - Courbe : CA mensuel
- Segments (Slicers) pour filtrer : Ville, Mois_Année, Catégorie

---

## 🟫 6. Conclusion

Ce projet m’a permis de :

✅ Nettoyer et structurer un jeu de données  
✅ Utiliser des formules Excel pour créer des indicateurs  
✅ Explorer les données avec des **TCD** et des **graphes**  
✅ Construire un **dashboard clair et interactif**

---

## 🔄 Prochaines étapes

- Reproduire l’analyse avec **Power BI** et **Python**
- Ajouter une **analyse prédictive**
- Travailler sur des datasets plus volumineux

---
