<h2 align="center">🚀 RECHERCHE ALTERNANCE — SEPTEMBRE 2026</h2>
<p align="center">🗓️ Rythme : 3 semaines en entreprise / 1 semaine d'école</p>

<p align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=26&duration=3000&pause=1000&color=00F7FF&center=true&vCenter=true&width=800&lines=Ingénieur+Infrastructure+%26+Sécurité;Zero+Trust+%7C+Network+Security;SOC+Analyst+%7C+SIEM+Builder;Haute+Disponibilité+%26+Cloud" alt="Typing SVG" /></a>
</p>

<p align="center">
<img src="https://github.com/Yemah/Yemah/blob/main/gitProfile.jpeg" width="180"/>
</p>

<h1 align="center">Hello Bienvenu, je suis Steeve WOMO TCHINDA, Je construis et sécurise des infrastructures qui ne tombent pas en panne et quand elles sont attaquées, je le sais avant que ça fasse mal.</h1>

<p align="center">
🛡️ Cybersécurité | Réseaux & Systèmes | Maintien en Condition Opérationnelle (MCO)<br>
🔐 Passionné par la sécurisation des infrastructures complexes, le Zero Trust et la détection des menaces.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Admin_Systèmes_&_Réseaux-Expert-green?style=for-the-badge" alt="Admin Sys">
  <img src="https://img.shields.io/badge/Sécurité_Infrastructure-Avancé-blue?style=for-the-badge" alt="Sec Infra">
  <img src="https://img.shields.io/badge/SOC_&_SIEM-Intermédiaire-red?style=for-the-badge" alt="SOC">
  <img src="https://img.shields.io/badge/Zero_Trust_Architecture-Avancé-purple?style=for-the-badge" alt="Zero Trust">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/steeve-womo"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:womo.steeven@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="tel:+33605975113"><img src="https://img.shields.io/badge/Téléphone-+33%206%2005%2097%2051%2013-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="Phone"></a>
</p>

---

## 🚀 À propos de moi

Actuellement en fin de cycle **Mastère Cybersécurité et Cloud (Titre RNCP Niveau 7)** à l'IMIE Paris, je poursuis un Master Sécurité Informatique au CNAM Angers à la prochaine rentrée. Fort de **2 ans d'expérience terrain**, je conçois, administre et sécurise des environnements hybrides hautement disponibles.

Je suis à la recherche active d'un **Stage de fin d'étude immédiatement** et d'une **alternance de 24 mois à la prochaine rentrée 2026** pour consolider mon expertise opérationnelle en cybersécurité au sein d'une entreprise dynamique et innovante.

| 🛡️ Sécurité & SOC | 🌐 Réseaux & Firewalling | 💻 Systèmes & Virtualisation | ⚙️ Automatisation & MCO |
|---|---|---|---|
| SIEM Wazuh & Splunk | OPNsense (CARP/HA) & Mikrotik | VMware ESXi & vCenter | Bash, Python, PowerShell |
| Détection d'intrusions | VLAN 802.1Q, VPN (WireGuard) | Windows Server 2022 (AD, GPO) | Zabbix, IPAM/DCIM (NetBox) |
| IAM, Authelia, MFA | Cisco (CCNA en cours) | Ubuntu, Oracle Linux, FreeBSD | Plan de Reprise d'Activité |
| Zero Trust Architecture | Filtrage, NAT, Routage | Veeam Backup & Replication | CI/CD & Kubernetes (Notions) |

---

## 👑 Projet Phare : Le Projet Résilience (Infrastructure HDS)

Ce portfolio documente la conception de A à Z d'une **infrastructure de santé fictive (Clinique Le Châtelet)** répondant aux exigences réglementaires HDS, NIS2 et RGPD. Ce n'est pas un simple laboratoire, c'est une architecture d'entreprise micro-segmentée, durcie et hautement résiliente. Vous pouvez explorer chaque brique technique via les liens ci-dessous :

> **Visualisation de l'architecture :**
<p align="center">
  <a href="https://github.com/Yemah/resilience-infrastructure-portfolio"><img src="https://raw.githubusercontent.com/Yemah/resilience-infrastructure-portfolio/main/architecture/diagrams/clinique_chatelet_architecture.png" width="800" alt="Schéma d'architecture"></a>
</p>



### 🖥️ 1. Infrastructure Core & Identité (Tier 0)
L'épine dorsale du système est un Active Directory hautement disponible (DC1/DC2). Il centralise les identités et sécurise les postes de travail via des GPOs restrictives (SMBv1 désactivé, LAPS, Audit strict). L'authentification LDAP est chiffrée (LDAPS).

---
🔗 **[Voir la documentation : Durcissement Active Directory & GPO](https://github.com/Yemah/resilience-infrastructure-portfolio/blob/main/configs/systems/active-directory-hardening.md)**
---

### 🌐 2. Haute Disponibilité Réseau (HA)
Cluster de pare-feux OPNsense en mode Actif/Passif (CARP + pfSync). Le réseau est micro-segmenté en 6 VLANs hermétiques pour empêcher les mouvements latéraux des ransomwares.

---
🔗 **[Voir la documentation : Cluster OPNsense & Segmentation VLAN](https://github.com/Yemah/resilience-infrastructure-portfolio/blob/main/configs/firewall/opnsense-ha-vlan-proof.md)**
---

### 🔐 3. Architecture Zero-Trust & Application Web
L'application médicale (Node.js + Oracle) n'est jamais exposée sur Internet. L'accès passe par un Reverse Proxy Nginx couplé à Authelia qui impose un MFA (TOTP) validé via l'Active Directory.

---
🔗 **[Voir la documentation : Portail Captif & MFA Authelia](https://github.com/Yemah/resilience-infrastructure-portfolio/blob/main/configs/proxy/authelia-zero-trust-gateway.md)**
---
---
🔗 **[Voir la documentation : Déploiement App Node.js (RBAC)](https://github.com/Yemah/resilience-infrastructure-portfolio/blob/main/app/srv-web-deployment.md)**
---

### 🕵️ 4. SOC Interne & Détection (Wazuh)
Déploiement centralisé de 10 agents Wazuh couvrant Windows, Linux et FreeBSD. Configuration du FIM (File Integrity Monitoring) et mise en place d'une *Active Response* (SOAR) pour bannir automatiquement les IP attaquantes au niveau du pare-feu.

---
🔗 **[Voir la documentation : SOC Wazuh & Remédiation SOAR](https://github.com/Yemah/resilience-infrastructure-portfolio/blob/main/configs/siem/wazuh-advanced-architecture.md)**
---

### 📊 5. Continuité : PRA & MCO (Veeam + Zabbix)
La sauvegarde des VM est gérée par Veeam dans un VLAN sanctuarisé. La supervision applicative est assurée par Zabbix, avec remontée d'alertes SMTP (Mailpit) en temps réel.

---
🔗 **[Voir la documentation : Plan de Reprise d'Activité (Veeam)](https://github.com/Yemah/resilience-infrastructure-portfolio/blob/main/configs/backup/veeam-resilience-pra.md)**
---
---
🔗 **[Voir la documentation : Stratégie d'Alerte SMTP Zabbix](https://github.com/Yemah/resilience-infrastructure-portfolio/blob/main/configs/monitoring/zabbix-alerting-strategy.md)**
---

---


## 💼 Expériences Professionnelles

### 🌐 Administrateur Système et Réseau (Alternance)
**BSRQ.MEDIA** | *Sept 2024 – Oct 2025*
* Refonte et administration d'une infrastructure réseau hybride (Cisco, Mikrotik, Aruba, OPNsense) garantissant un SLA de 99,9%.
* Déploiement d'une architecture Zero Trust : tunnels OpenVPN-AS/WireGuard avec authentification MFA (Azure AD).
* Réduction du temps de résolution des incidents à < 2h grâce à un monitoring proactif (Zabbix) et à l'automatisation (scripts Bash/Python).

### 🛡️ Analyste Infrastructure et Sécurité (Stage)
**ACS'IT** | *Mai 2023 – Août 2023*
* Déploiement de la plateforme SIEM Wazuh sur un parc de plus de 80 terminaux.
* Analyse et corrélation de logs multi-sources, diminuant le délai de détection des incidents de 40%.
* Affinage des règles de détection sur plus de 120 alertes hebdomadaires, réduisant les faux positifs de 35%.

### 🖥️ Administrateur Système (Stage)
**CAMTEL** | *Juil 2022 – Oct 2022*
* Administration d'un environnement Active Directory (50+ comptes, GPO, RBAC).
* Surveillance des journaux système et gestion des incidents de sécurité N1/N2.

---

## 🛠️ Stack Technique & Outils

### Réseaux & Firewalling
![OPNsense](https://img.shields.io/badge/OPNsense-FF7D00?style=for-the-badge&logo=opnsense&logoColor=white)
![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-881798?style=for-the-badge&logo=wireguard&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Mikrotik](https://img.shields.io/badge/Mikrotik-1699AZ?style=for-the-badge&logo=mikrotik&logoColor=white)

### Cybersécurité (Blue Team)
![Wazuh](https://img.shields.io/badge/Wazuh-00A9E0?style=for-the-badge&logo=wazuh&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![Authelia](https://img.shields.io/badge/Authelia-181818?style=for-the-badge&logo=authelia&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)

### Infrastructures & Systèmes
![VMware](https://img.shields.io/badge/VMware-607078?style=for-the-badge&logo=vmware&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Veeam](https://img.shields.io/badge/Veeam-00B336?style=for-the-badge&logo=veeam&logoColor=white)

### MCO & Automatisation
![Zabbix](https://img.shields.io/badge/Zabbix-D40000?style=for-the-badge&logo=zabbix&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

---

## 📜 Certifications & Formations
* **Az-900 Microsoft Azure Fundamentals**
* **Scrum Fundamentals Certified**
* **Cisco CCNA 200-301** *(En cours)*

---

## 📊 Statistiques GitHub


![GitHub Streak](https://streak-stats.demolab.com?user=Yemah&theme=tokyonight)

---

## 🤝 Connectons-nous & Collaborons !
## Let's Connect & Collaborate !

### 📬 Informations de Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/steeve-womo/)

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:womo.steeven@gmail.com)

[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Yemah)


---

<p align="center">
  <em>"Sécuriser l'architecture d'aujourd'hui pour anticiper les menaces de demain."</em>
</p>

># ⭐ Support

Si vous trouvez mon travail intéressant,  
n'hésitez pas à **donner une étoile ⭐ au repository** !
