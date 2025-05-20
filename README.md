# 📱 Arka Mobile – Companion App pour Arka Desktop

**Arka Mobile** est l’application mobile compagnon de **Arka**, la solution desktop de gestion familiale de fichiers.  
Elle permet aux membres d’une famille de **consulter leurs espaces de stockage**, **scanner des documents**, **gérer des tâches personnelles ou familiales**, et **recevoir des alertes** contextuelles.

Développée en **Kotlin** avec **Jetpack Compose**, elle est pensée pour un usage terrain : rapide, pratique, et synchronisée avec le serveur local d’Arka Desktop via API REST.

---

## 🎯 Objectif du projet

- Permettre à chaque membre d’une famille de suivre et gérer son espace de fichiers personnel et familial depuis son smartphone.
- Offrir des fonctionnalités complémentaires : tâches, scan de documents, rappels.
- Fournir une expérience mobile fluide, connectée et respectueuse de la structure familiale.

---

## 🚀 Fonctionnalités principales

- 📊 **Visualisation** des espaces personnels et communs
- ✅ **Gestion de tâches** personnelles ou familiales
- 🧾 **Scan de documents** avec enregistrement automatique
- 🔔 **Système d’alertes intelligentes** selon l’espace ciblé (individuel ou collectif)
- 🔗 **Connexion sécurisée** avec le serveur Arka Desktop via API REST
- 🔒 Authentification locale et sécurisation des accès

---

## 🧱 Stack technique

| Type | Outils |
|------|--------|
| **Langage** | Kotlin |
| **UI** | Jetpack Compose |
| **Navigation** | Compose Navigation |
| **Base locale** | Room (SQLite) |
| **Scanner** | ML Kit / Intents natifs |
| **Connexion API** | Ktor Client / Retrofit |
| **Architecture** | MVVM avec ViewModels |
| **Persistance** | SharedPreferences + Room |
| **Synchronisation** | API REST Arka (serveur local)

---

## ⚙️ Installation locale

### Prérequis

- Android Studio (Hedgehog+ recommandé)
- SDK Android minimum : 24+
- Accès réseau au serveur Arka Desktop pour les tests (localhost ou IP LAN)
- Permissions nécessaires : fichiers, caméra

### Lancer l’application

```bash
git clone https://github.com/jeanauryel/ArkaMobile.git
# Ouvrir le projet dans Android Studio
# Lancer sur un simulateur ou appareil physique
