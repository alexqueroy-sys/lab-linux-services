# 🐧 Lab Linux — Services Réseau Ubuntu Server

## 📋 Description
Déploiement d'un serveur Ubuntu Server 24.04 sous VirtualBox avec 
configuration de services réseau essentiels en entreprise.

## 🏗️ Architecture
| Machine | OS | IP |
|---|---|---|
| UBUNTU-SRV | Ubuntu Server 24.04 | 192.168.10.1 |

## ✅ Services configurés
- **SSH** — Connexion à distance sécurisée (port 22)
- **DHCP** — Distribution automatique d'adresses IP (plage 192.168.10.100-200)
- **DNS** — Résolution de noms (BIND9)
- **Apache** — Serveur web HTTP

## 🛠️ Technologies utilisées
- Ubuntu Server 24.04 LTS
- OpenSSH Server
- ISC DHCP Server
- BIND9
- Apache2
- VirtualBox 7.x

## 📸 Screenshots
(à ajouter)

## 📚 Ce que j'ai appris
- Naviguer et configurer un serveur Linux en ligne de commande
- Installer et configurer des services réseau
- Gérer des services avec systemctl
- Configurer une adresse IP fixe avec Netplan
