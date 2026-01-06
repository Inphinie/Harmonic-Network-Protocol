<div align="center">

# 🌐 H.N.P. (Holographic Network Protocol)
**Lichen Universe Network Layer**

> **"Ne routez pas l'information. Laissez-la résonner."**

[![Protocol](https://img.shields.io/badge/Protocol-Holographic-purple?style=for-the-badge&logo=tor-browser)](./whitepapper.md)
[![Math](https://img.shields.io/badge/Geometry-E8_Lattice-blue?style=for-the-badge&logo=wolframmathematica)](./e8_encoding.py)
[![Lang](https://img.shields.io/badge/Written_In-Python-yellow?style=for-the-badge&logo=python)](https://python.org)
[![Status](https://img.shields.io/badge/Status-Experimental_Alpha-red?style=for-the-badge)](./lichen_demo.py)

---

## 🎮 LIVE DEMO
### Experience the Harmonic Architecture in Real-Time

[![Streamlit App](https://img.shields.io/badge/🌊_LAUNCH_LIVE_DASHBOARD-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://lichen-universe-unified-v2-wehhhdik2aznw4eh7xf7ay.streamlit.app/)

</div>

---
## 📡 Vision & Rupture

Le **Holographic Network Protocol (HNP)** propose un changement de paradigme radical par rapport aux modèles OSI classiques (TCP/IP). Au lieu de diriger des paquets via des tables de routage statiques, le HNP traite l'information comme une **onde**.

Le réseau n'est plus une carte routière, c'est un milieu de propagation où le chemin optimal est déterminé par **Interférence Constructive**.

---

## ⚙️ Architecture Technique

Le protocole repose sur trois piliers implémentés dans ce dépôt :

### 1. Le Paquet Holographique (`hnp_packet.py`)
Contrairement à un paquet binaire standard, un paquet HNP possède des propriétés physiques simulées :
* **Amplitude & Phase :** Déterminent la force et l'état du signal.
* **Fréquence :** Permet le multiplexage naturel.
* **Comportement :** Le paquet ne "s'arrête" pas, il traverse le réseau jusqu'à trouver une résonance.

### 2. Routage par Interférence (`hnp_router.py` & `hnp_flow.py`)
Le routeur n'inspecte pas une adresse IP de destination de manière classique.
* Il agit comme un **nœud de réfraction**.
* Si la "phase" du paquet s'aligne avec la "phase" du destinataire (ou du nœud suivant), il y a **Amplification** (le message passe).
* Sinon, il y a **Dissipation** (le message s'ignore).
* *Résultat :* Latence minimale, auto-guérison du réseau.

### 3. Encodage E8 (`e8_encoding.py`)
Pour densifier l'information, nous utilisons la géométrie du **Groupe de Lie E8**.
* Les données ne sont pas justes des 0 et des 1, mais des coordonnées dans un réseau (lattice) à 8 dimensions (ou 248 dimensions pour l'algèbre complète).
* Cela permet une compression et une sécurité intrinsèque (topologique).

---

## 📂 Structure du Code

| Fichier | Rôle |
| :--- | :--- |
| `hnp_packet.py` | Définition de la classe `WavePacket` (Structure de l'onde). |
| `hnp_router.py` | Logique de nœud : calcul des interférences et propagation. |
| `hnp_flow.py` | Gestionnaire de flux (Flow Orchestrator) pour le réseau. |
| `e8_encoding.py` | Moteur mathématique de projection des données sur le Lattice E8. |
| `BAD.py` | **Binary Acoustic Data** : Module de formatage des données brutes. |
| `lichen_demo.py` | Script de démonstration : simulation d'un mini-réseau HNP. |
| `app_hnp.py` | Interface / Visualisation du trafic holographique. |

---

## 🚀 Démarrage Rapide

Pour observer la propagation d'un paquet holographique dans le simulateur :

```bash
# Lancer la démo du réseau Lichen
python lichen_demo.py

# Visualiser l'encodage E8
python e8_encoding.py

```

## 📚 Documentation Théorique

Les fondements mathématiques (Interférences, E8, Équations de flux) sont détaillés dans :

* 📄 **[Whitepaper](https://www.google.com/search?q=./whitepapper.md)** : Philosophie et architecture globale.
* 🧮 **[Formulas](https://www.google.com/search?q=./Formulas.md)** : Équations physiques du routage.

---

*"Le chemin le plus court n'est pas une ligne droite, c'est une onde stationnaire."*
