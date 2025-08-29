---
layout: default
---

# Bienvenue dans mon monde numérique

Ce site est une **chronique de mes explorations** et de mes projets dans le domaine de la **cybersécurité**. Il sert de base de données personnelle pour les outils, les recherches et les exploits que j'ai menés.

---

## Mes Compétences et Mon Arsenal

Je déploie des compétences dans plusieurs domaines de la sécurité informatique :

* **Sécurité offensive** : 
    * Tests d'intrusion et audits de sécurité
    * Ingénierie sociale et `phishing`
* **Sécurité défensive** :
    * Gestion des pare-feu et `IDS/IPS`
    * Analyse de logiciels malveillants (`malware`)
* **Infrastructure et Cloud** :
    * Sécurisation de réseaux (`VPN`, `VLAN`)
    * Configuration de serveurs Linux
* **Programmation** : `Python`, `Go`, `Bash`

---

## Projets Principaux

Découvrez quelques-uns de mes travaux les plus importants. Chaque projet a été un défi unique qui m'a permis de perfectionner mes compétences.

| Nom du Projet | Description | Technologies |
|:--------------|:------------|:-------------|
| **Project-01** | Un outil automatisé pour l'analyse de vulnérabilités sur des serveurs web. | `Python`, `Flask` |
| **Defensive-Sec** | Une série de scripts pour renforcer la sécurité des systèmes Linux. | `Bash`, `Ansible` |
| **CTF-Solution** | Mon write-up détaillé pour le CTF "CaptureTheFlag" de l'année 2024. | `Burp Suite`, `Wireshark` |

---

## Un Aperçu de mon Code

> "Le code est notre meilleur allié dans la guerre numérique."

```python
# Un script simple pour vérifier si un port est ouvert
import socket

def port_scanner(host, port):
    try:
        s = socket.socket(socket.AF_INET, socket.SOCK_STREAM)
        s.settimeout(1)
        s.connect((host, port))
        print(f"Le port {port} est ouvert sur {host}")
    except:
        print(f"Le port {port} est fermé ou protégé")

# Exemple d'utilisation
port_scanner('google.com', 80)
