# 🛡️ Anti-Fraud System

**Plateforme avancée de détection de fraude**

[![Go](https://img.shields.io/badge/Go-1.22-00ADD8?logo=go)](https://golang.org)
[![Python](https://img.shields.io/badge/Python-3.11-3776AB?logo=python)](https://python.org)
[![Flutter](https://img.shields.io/badge/Flutter-3.24-02569B?logo=flutter)](https://flutter.dev)
![License](https://img.shields.io/badge/License-Proprietary-red.svg)
[![Status](https://img.shields.io/badge/Status-Production_Ready-1f883d)](https://github.com/elmahdichakor/anti-fraud-system)---

## 📌 Description

**Anti-Fraud System** est une plateforme complète de détection de fraude qui combine **17 couches de protection** pour identifier et bloquer les activités frauduleuses en temps réel.

### 🎯 Objectifs

- **Taux de détection** > 95%
- **Faux positifs** < 2%
- **Latence API** < 100ms
- **Disponibilité** > 99.9%---

## ✨ Fonctionnalités Clés

| # | Fonctionnalité | Technologie |
|---|----------------|-------------|
| 1 | Hardware Fingerprinting | Flutter + DeviceDNA |
| 2 | Détection IA | LightGBM (99.85%) |
| 3 | Zero-Trust Architecture | Vérification continue |
| 4 | Post-Quantum Cryptography | Kyber + Dilithium |
| 5 | Behavioral Biometrics | Analyse patterns |
| 6 | Federated Learning | FedAvg + FedProx |
| 7 | Threat Intelligence | 3 sources externes |
| 8 | Deception Technology | Honeypots |
| 9 | Proof-of-Work | Anti-DDoS |
| 10 | Dashboard | Temps réel |---

## ⚡ Installation

### Prérequis

- Go 1.22+
- Python 3.11+
- Redis 7.x
- SQLite 3.x

### Étapes

```bash
# 1. Cloner le projet
git clone https://github.com/elmahdichakor/anti-fraud-system.git
cd anti-fraud-system

# 2. Installer les dépendances Go
cd go
go mod download

# 3. Installer les dépendances Python
cd ../ml
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

# 4. Démarrer le serveur
cd ../go
go run main.go
```
🌐 Accès: http://localhost:8080/dashboard
## 📊 API Endpoints

### Device Management

| Méthode | Endpoint | Description |
|---------|----------|-------------|
| POST | `/api/register` | Enregistrer un device |
| POST | `/api/verify` | Vérifier un device |
| POST | `/api/license` | Gestion licence |

### Dashboard

| Méthode | Endpoint | Description |
|---------|----------|-------------|
| GET | `/api/dashboard/stats` | Statistiques globales |
| GET | `/api/dashboard/devices` | Liste des devices |
| GET | `/api/dashboard/licenses` | Liste des licences |
| GET | `/api/dashboard/fraud-timeline` | Timeline des fraudes |

### Security

| Méthode | Endpoint | Description |
|---------|----------|-------------|
| POST | `/api/challenge/new` | Générer challenge PoW |
| POST | `/api/challenge/verify` | Vérifier preuve PoW |
| GET | `/api/threat/check` | Vérifier IP |

### Quantum

| Méthode | Endpoint | Description |
|---------|----------|-------------|
| POST | `/api/quantum/kyber/generate` | Générer clés Kyber |
| POST | `/api/quantum/dilithium/sign` | Signer avec Dilithium |
| POST | `/api/quantum/hybrid/encrypt` | Chiffrement hybride |

### Federated Learning

| Méthode | Endpoint | Description |
|---------|----------|-------------|
| POST | `/api/fl/start` | Démarrer training |
| GET | `/api/fl/stats` | Statistiques FL |
| GET | `/api/fl/clients` | Liste clients |
---

## 🔒 Sécurité

### Couches de Protection

| Couche | Technologie |
|--------|-------------|
| Chiffrement | AES-256-GCM |
| Intégrité | HMAC-SHA256 |
| Authentification | JWT + MFA (TOTP) |
| Anti-DDoS | Proof-of-Work (SHA-256) |
| Post-Quantum | Kyber KEM + Dilithium |
| Rate Limiting | 100 req/min/IP |
| Token Rotation | JWT avec rotation automatique |---

## 📊 Performance

| Métrique | Objectif | Réalisé |
|----------|----------|---------|
| Taux de détection | > 95% | **99.85%** ✅ |
| Faux positifs | < 2% | **< 1%** ✅ |
| Latence API | < 100ms | **65ms** ✅ |
| Disponibilité | 99.9% | **99.95%** ✅ |

### Modèles ML

| Modèle | Accuracy | F1-Score | ROC-AUC |
|--------|----------|----------|---------|
| LightGBM | 99.85% | 99.37% | 99.86% |
| IsolationForest | 98.45% | 93.58% | 98.95% |
| Fusion | 99.80% | 99.16% | 99.84% |---

## 🛠️ Technologies Utilisées

| Catégorie | Technologies |
|-----------|--------------|
| **Backend** | Go 1.22, Fiber 2.52, SQLite, Redis, Neo4j |
| **Machine Learning** | Python 3.11, LightGBM 4.1, scikit-learn 1.3, ONNX 1.16 |
| **Frontend** | Flutter 3.24, TailwindCSS 3.4, Chart.js 4.4 |
| **Sécurité** | AES-256-GCM, HMAC-SHA256, Kyber, Dilithium, Argon2 |
| **Monitoring** | Logrus, Glances, Prometheus |
| **Base de données** | SQLite 3.x, Redis 7.x, Neo4j 5.x |
## 📄 Licence

**Tous droits réservés** - © 2026 El Mahdi Chakor

Ce projet est protégé par le droit d'auteur. Tous droits réservés.

Aucune partie de ce logiciel ne peut être reproduite, distribuée ou transmise
sous quelque forme ou par quelque moyen que ce soit, sans l'autorisation
préalable écrite de l'auteur.

Permission is NOT granted to:

    Copy, modify, or distribute this software

    Use this software for commercial purposes

    Sublicense or sell this software

    Remove any copyright notices

For licensing inquiries, contact: elmahdichakor0@gmail.com

