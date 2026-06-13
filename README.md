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
  <img src="https://img.shields.io/badge/Admin_Systèmes_&_Réseaux-Avancé-green?style=for-the-badge" alt="Admin Sys">
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

Actuellement en fin de formation **Expert Réseau Infrastructure et Sécurité (Titre RNCP Niveau 7)** à l'IMIE Paris, je poursuis un Master universitaire en Sécurité Informatique au CNAM Angers à la prochaine rentrée. Fort de **2 ans d'expérience terrain**, je conçois, administre et sécurise des environnements hybrides hautement disponibles.

Je suis à la recherche active d'un **Stage de fin d'étude immédiatement** et d'une **alternance de 24 mois à la prochaine rentrée 2026** pour consolider mon expertise opérationnelle en cybersécurité au sein d'une entreprise dynamique et innovante.

| 🛡️ Sécurité & SOC | 🌐 Réseaux & Firewalling | 💻 Systèmes & Virtualisation | ⚙️ Automatisation & MCO |
|---|---|---|---|
| SIEM Wazuh & Splunk | OPNsense (CARP/HA), Fortigate & Mikrotik | VMware ESXi/vCenter, Proxmox | Bash, Python, PowerShell |
| Détection d'intrusions | VLAN 802.1Q, VPN (WireGuard/IPSec) | Windows Server 2022 (AD, GPO) | Zabbix, IPAM/DCIM (NetBox) |
| IAM, Authelia, MFA | Cisco (CCNA en cours) | Ubuntu, Oracle Linux, Red hat, FreeBSD | Plan de Reprise d'Activité |
| Zero Trust Architecture | Filtrage, ACL, NAT, Routage/Switching | Veeam Backup & Replication | CI/CD & Kubernetes, Ansible & Terraform (Notions) |

---

## 👑 Projet Phare : Le Projet Résilience (Infrastructure HDS)

Ce portfolio documente la conception de A à Z d'une **infrastructure de santé fictive (Clinique Le Châtelet)** répondant aux exigences réglementaires HDS, NIS2 et RGPD. Ce n'est pas un simple laboratoire, c'est une architecture d'entreprise micro-segmentée, durcie et hautement résiliente. 

> **Visualisation de l'architecture :**
<p align="center">
  <a href="https://github.com/Yemah/clinique-chatelet-secure-infra"><img src="https://raw.githubusercontent.com/Yemah/clinique-chatelet-secure-infra/main/docs/assets/diagrams/clinique-chatelet-architecture.png" width="800" alt="Schéma d'architecture"></a>
</p>

➡️ **[Voir le repo](https://github.com/Yemah/clinique-chatelet-secure-infra)** · **[Voir la documentation](https://yemah.github.io/clinique-chatelet-secure-infra/)**

---

## Projet Terraform complet déployant une infra hybride : • vSphere 8 (Paris) – VM AD, Web interne • AWS (Abidjan) – EC2 + RDS MySQL • Azure – VM Zabbix + stockage • Terraform Cloud (backend) + Ansibl…

**📖 Description**

Ce dépôt contient le code **Infrastructure as Code (IaC)** permettant de déployer et configurer l'infrastructure hybride de l'entreprise fictif **NTIC CENTER CORPORATION**, répartie sur trois plans de contrôle :

| Site | Plateforme | Rôle |
|---|---|---|
| **Paris** | VMware vSphere 8 (on-premise) | Intranet d'entreprise (clone de template + cloud-init) |
| **Abidjan** | AWS (`eu-west-1`) | Services publics : EC2 (Nginx) + RDS MySQL |
| **Supervision** | Azure (`swedencentral`) | VM Zabbix pour la supervision globale |

Le provisioning est assuré par **Terraform** (modules dédiés par provider), et la configuration applicative (Nginx) par **Ansible**, appliquée de manière homogène sur les trois environnements.

>**Architecture simplifier**

```mermaid
graph TD
    Paris["🏢 Paris (On-Premise)<br/>VM web-paris<br/>1 vCPU / 1 Go RAM<br/>IP: 192.168.1.17"]
    AWS["☁️ Abidjan (AWS eu-west-1)<br/>EC2 web-abidjan t3.micro<br/>IP: 3.252.52.40 (Nginx)<br/>RDS MySQL db.t3.micro"]
    Azure["📊 Supervision (Azure swedencentral)<br/>VM zabbix-monitor Standard_D2s_v3<br/>IP: 4.223.71.179 (Zabbix)"]
    TFC["Terraform Cloud<br/>État centralisé (AWS+Azure)"]
    Local["État local (vSphere)"]
    Ansible["Ansible<br/>Playbook Nginx"]
    SSH["SSH (même clé partout)"]

    TFC --> AWS
    TFC --> Azure
    Local --> Paris
    Ansible --> SSH
    SSH --> Paris
    SSH --> AWS
    SSH --> Azure

    classDef aws fill:#ff9900,stroke:#232f3e,color:white;
    classDef azure fill:#0078d4,stroke:#00188f,color:white;
    classDef onprem fill:#607078,stroke:#39424a,color:white;
    classDef tool fill:#844fba,stroke:#4a148c,color:white;

    class AWS aws;
    class Azure azure;
    class Paris onprem;
    class TFC,Local,Ansible,SSH tool;
```

---

➡️ **[Voir le repo](https://github.com/Yemah/ntic-center-infra)** 

Le document d'architecture complet (DAT) décrivant les choix de conception, les matrices de flux, la sécurité et les incidents rencontrés est disponible dans [DAT Complet](https://github.com/Yemah/ntic-center-infra/blob/main/docs/DAT_NTIC_CENTER_CORPORATION.md).

---



## 💼 Expériences Professionnelles

### 🌐 Administrateur Système et Réseau (Alternance)
**BSRQ.MEDIA** | *Sept 2024 – Oct 2025*
* Refonte Architecturale & Segmentation : Conception et déploiement en autonomie d'une architecture réseau sécurisée (passage d'un réseau plat à une infrastructure segmentée VLANs), intégrant un firewall MikroTik et une redondance Dual-WAN (Orange/SFR) pour un site de production critique.
* Administration Hybride & MCO : Gestion complète d'une infrastructure bi-sites hétérogène (Windows Server AD/DNS/DHCP/GPO, Linux, Proxmox) et d'équipements réseaux (Cisco, Aruba, OPNsense en HA), assurant la continuité de service et la résolution d'incidents N1 à N3.
* Sécurisation Zero Trust : Implémentation d'une stratégie Zero Trust sur un périmètre ранее non protégé : déploiement de VPN inter-sites (WireGuard, OpenVPN-AS), authentification forte (MFA, SSO Azure AD/Entra ID) et contrôle d'accès via bastion Apache Guacamole.
Automatisation & Documentation : Automatisation des tâches d'exploitation récurrentes via scripts Python et Bash, et maintien d'une documentation technique à jour (IPAM/DCIM) via NetBox pour une traçabilité totale.
* Support & Gestion de Parc : Pilotage du support IT interne, gestion du cycle de vie des équipements et coordination technique avec les prestataires externes.

### 🛡️ Analyste Infrastructure et Sécurité (Stage)
**ACS'IT** | *Mai 2023 – Août 2023*
* Déploiement SIEM Wazuh : Installation et configuration d'une plateforme SIEM Wazuh sur 80+ terminaux, centralisant la supervision des événements de sécurité en temps réel.
* Détection & Réponse (MTTD) : Analyse et corrélation de logs multi-sources pour identifier les anomalies, réduisant le délai moyen de détection (MTTD) de 40 %.
* Optimisation SOC : Qualification et tri de 120+ alertes/semaine par l'affinement continu des règles de détection, diminuant les faux positifs de 35 % et optimisant le temps de réponse des analystes.

### 🖥️ Administrateur Système (Stage)
**CAMTEL** | *Juil 2022 – Oct 2022*
* Administration Active Directory : Gestion de l'identité et des accès pour 35+ utilisateurs (création de 50+ comptes, déploiement de GPO de sécurité, audit des privilèges), garantissant la conformité du SI.
* Sécurité Opérationnelle : Surveillance proactive des journaux système, contribution à la résolution d'incidents de sécurité (N1/N2) et mise en œuvre d'actions correctives pour réduire la surface d'attaque.

---

## 💼 Parcours

| Période | Formation | Entreprise |
|---      | ---       |---         |
|     2026 – 2028     | Master Sécurité informatique et cybermenaces | **CNAM** Angers |
|     2024 – 2026     | Mastère Expert Réseau Infrastructure et Sécurité (RNCP N7) | **IMIE Paris** Levallois-Perret |
|     2024 – 2025     | Mastère Expert Réseau Infrastructure et Sécurité | **IMIE Paris** Levallois-Perret |
|     2023 – 2024     | Cycle Ingénieur Informatique et Réseau Année 3 | **ESAIP Ecole d'Ingénieurs** Saint Barthélémy d'Anjou |
|     2022 – 2023     | Bachelor Conception des Systèmes de l'Information | **3IL Ingénieurs** Limoges |

**Certifications** : CCNA 200-301 (en cours) · Az-900 Azure Fundamentals · Scrum Fundamentals

---

## 🛠️ Stack technique

**Réseaux & Sécurité**

![OPNsense](https://img.shields.io/badge/OPNsense-D94F00?style=flat-square&logo=opnsense&logoColor=white)
![MikroTik](https://img.shields.io/badge/MikroTik-293239?style=flat-square&logo=mikrotik&logoColor=white)
![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=flat-square&logo=cisco&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white)
![OpenVPN](https://img.shields.io/badge/OpenVPN-EA7E20?style=flat-square&logo=openvpn&logoColor=white)

**SIEM / Monitoring**

![Wazuh](https://img.shields.io/badge/Wazuh-3CBCB4?style=flat-square&logo=wazuh&logoColor=white)
![Zabbix](https://img.shields.io/badge/Zabbix-D40000?style=flat-square&logo=zabbix&logoColor=white)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)

**Systèmes & Virtualisation**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Windows Server](https://img.shields.io/badge/Windows_Server-0078D4?style=flat-square&logo=windows&logoColor=white)
![VMware](https://img.shields.io/badge/VMware_ESXi-607078?style=flat-square&logo=vmware&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory-0078D4?style=flat-square&logo=microsoft&logoColor=white)

**Scripting & Cloud**

![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)


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
