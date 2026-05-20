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

Actuellement en fin de formation **Expert Réseau Infrastructure et Sécurité (Titre RNCP Niveau 7)** à l'IMIE Paris, je poursuis un Master Sécurité Informatique au CNAM Angers à la prochaine rentrée. Fort de **2 ans d'expérience terrain**, je conçois, administre et sécurise des environnements hybrides hautement disponibles.

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

### >🏗️ Architecture

```
                         ┌──────────────┐
                         │   INTERNET   │
                         └──────┬───────┘
                                │
                    ┌───────────┴───────────┐
                    │   Cluster HA OPNsense  │
                    │   FW1 ◄──pfSync──► FW2 │
                    │   6 VIPs CARP (.254)   │
                    └───────────┬───────────┘
                        Trunk 802.1Q (VGT 4095)
                                │
     ┌─────────┬────────────┬───┴───┬────────────┬──────────┐
     │         │            │       │            │          │
┌────┴─────┐┌──┴─────┐┌────┴───┐┌──┴───────┐┌───┴────┐┌───┴─────┐
│ VLAN 111 ││VLAN 222││VLAN 333││ VLAN 444 ││VLAN 555││VLAN 999 │
│   SRV    ││ CLIENT ││  DMZ   ││  BACKUP  ││ GUEST  ││  MGMT   │
│──────────││────────││────────││──────────││────────││─────────│
│DC1+DC2   ││Postes  ││Nginx   ││Veeam B&R ││Internet││Bastion  │
│Oracle 21c││travail ││+MFA    ││300Go repo││  seul  ││BitLocker│
│Zabbix    ││soignant││Portail ││15 VMs    ││        ││9 GPOs   │
│Wazuh     ││        ││Mailpit ││protégées ││        ││         │
│GLPI      ││        ││        ││          ││        ││         │
└──────────┘└────────┘└────────┘└──────────┘└────────┘└─────────┘
172.16.11.0 172.16.22.0 172.16.33.0 172.16.44.0 172.16.55.0 172.16.99.0
```


➡️ **[Voir le repo](https://github.com/Yemah/clinique-chatelet-secure-infra)** · **[Voir la documentation](https://yemah.github.io/clinique-chatelet-secure-infra/)**



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

## 💼 Parcours

| Période | Poste | Entreprise |
|---|---|---|
| 2026 – 2028 | Master Sécurité informatique et cybermenaces | **CNAM** Angers |
| 2024 – 2026 | Mastère Cybersécurité et Cloud (RNCP N7) | **IMIE** Paris |
| 2024 – 2025 | Admin Système et Réseau (alternance) | **BSRQ.MEDIA** Issy-les-Moulineaux |
| 2023 | Analyst Infrastructure et Sécurité (stage) | **ACS'IT** Limoges |
| 2022 | Administrateur Système (stage) | **CAMTEL** Douala |

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
