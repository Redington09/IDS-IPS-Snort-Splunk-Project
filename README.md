# IDS-IPS-Snort-Splunk-Project
il s'agit de notre projet etudiant pour le compte de notre formation en Licence Administration Securiter Resaux (ASR))

# Projet IDS/IPS Snort avec centralisation des alertes via Splunk

## 📌 Présentation
Ce projet consiste à mettre en place un système de détection et de prévention d'intrusions (IDS/IPS) basé sur **Snort**, avec une **centralisation des alertes** sur une plateforme de monitoring **Splunk**.  
L'objectif du projet est de proposer une solution de cybersécurité **commercialisable**, adaptée aux entreprises camerounaises.

---

## 🎯 Objectifs du projet
- Déployer et configurer un IDS/IPS Snort fonctionnel (mode IDS puis mode IPS).
- Collecter et centraliser les logs/alertes vers Splunk.
- Mettre en place des tableaux de bord dynamiques pour visualiser les menaces.
- Tester différentes attaques (scan, brute force, exfiltration, etc.) pour valider le système.
- Étudier la possibilité de proposer cette solution comme un produit commercialisable.

---

## 🏗️ Architecture du projet
Le laboratoire repose sur trois machines (VM ou serveurs physiques) :

1. **Snort Sensor** (IDS/IPS) – Ubuntu Server  
2. **Splunk Server** – Ubuntu Server  
3. **Attacker / Client Machine** – Kali Linux ou Ubuntu Desktop  

Les alertes générées par Snort sont envoyées vers Splunk via un **Universal Forwarder** ou via **Syslog**.

---

## 🛠️ Technologies utilisées
- **Snort 3** (IDS/IPS open-source)
- **Splunk Enterprise / Splunk Free**
- **Universal Forwarder Splunk**
- **Ubuntu Server 20.04+**
- **Kali Linux / Ubuntu Desktop**
- **Nmap**, **Hydra**, **Metasploit** (pour les tests de sécurité)

---

## 📚 Fonctionnalités principales
- Détection en temps réel :
  - scans de ports  
  - brute force SSH  
  - attaques réseau courantes  
- Génération d’alertes Snort
- Envoi des alertes vers Splunk
- Dashboard Splunk permettant :
  - Top des signatures d’attaque
  - Top IP sources
  - Timeline des alertes
  - Statistiques filtrables

---

## 📂 Structure du dépôt
