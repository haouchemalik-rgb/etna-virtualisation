# Virtualisation avec Proxmox VE — déploiement et retours d'expérience multi-OS

> Projet ETNA — module Virtualisation · Mars – juin 2024 · Projet de groupe (4 personnes)

Mise en place de machines virtuelles sur un hyperviseur **Proxmox VE** et comparaison de systèmes d'exploitation variés. Chaque membre a documenté l'installation de ses VMs sous forme de procédures pas à pas et de retours d'expérience (REX).

**Compétences mises en œuvre :** Proxmox VE · création et dimensionnement de VMs (CPU, RAM, disque, réseau) · installation d'OS Linux, BSD et Windows · dual boot · rédaction de procédures techniques

---

## Étape 1 — Retours d'expérience par OS

Analyse des points forts et points faibles de plusieurs systèmes :

| Document | Système |
|---|---|
| [rex_Kali linux.pdf](etape1/rex_Kali%20linux.pdf) | Kali Linux |
| [rex_Ubuntu.pdf](etape1/rex_Ubuntu.pdf) | Ubuntu |
| [rex_IBM.pdf](etape1/rex_IBM.pdf) | IBM OS/2 Warp |
| [FreeBSD/](etape1/FreeBSD/) | FreeBSD |

## Étape 2 — Procédures de déploiement sur Proxmox

Guides d'installation illustrés, de la création de la VM à la configuration de l'OS :

| Procédure | Contenu |
|---|---|
| [Kali Linux sur Proxmox](etape2/rex-VM%20Kali%20Linux%20sur%20Proxmox.pdf) | Création de la VM, import de l'ISO, installation |
| [Windows en dual boot avec Fedora](etape2/rex-VM%20Windows%20en%20dual%20boot%20Fedora%20sur%20Proxmox.pdf) | Partitionnement et cohabitation de deux OS dans une même VM |
| [FreeBSD sur Proxmox](etape2/rex-VM%20Freebsd%20sur%20Proxmox.pdf) | Installation d'un système BSD |
| [Ubuntu Server 20.04 LTS](etape2/rex-ubuntu20.04LTS-montei_j.pdf) | Installation d'un serveur Ubuntu |

Mes contributions : retours d'expérience Kali Linux et IBM OS/2, procédures Kali Linux et Windows / Fedora en dual boot.
