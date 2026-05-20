# Steeve WOMO TCHINDA

**Administrateur & Ingénieur Infrastructure et Sécurité**

Passionné par la sécurisation des infrastructures (Zero Trust, SIEM, Firewalling), j'ai 2 ans d'expérience terrain en administration systèmes, réseaux et MCO. Actuellement en Mastère Cybersécurité et Cloud (RNCP N7), Je construis et sécurise des infrastructures qui ne tombent pas en panne et quand elles sont attaquées, je le sais avant que ça fasse mal. 

[![LinkedIn](https://img.shields.io/badge/LinkedIn-steeve--womo-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/steeve-womo)
[![Portfolio](https://img.shields.io/badge/Portfolio-Clinique_Le_Châtelet-00A86B?style=flat-square&logo=github-pages)](https://yemah.github.io/clinique-chatelet-secure-infra/)
[![Email](https://img.shields.io/badge/Email-womo.steeven@gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:womo.steeven@gmail.com)

---

## 🏗️ Projet phare

### [Infrastructure Sécurisée — Clinique Le Châtelet](https://yemah.github.io/clinique-chatelet-secure-infra/)

Infrastructure de soins de niveau production déployée sur VMware ESXi, conçue pour protéger des données de santé (HDS/HIPAA).

| Composant | Stack | Résultat |
|---|---|---|
| Pare-feu HA | OPNsense (CARP + pfSync) | 208 règles, 6 VLANs, Default Deny |
| SIEM/XDR | Wazuh v4.14.4 | 35 règles HDS custom, 8 Active Responses |
| Supervision | Zabbix 7.4.9 | 14 hôtes dual-stack, 20K items |
| MFA | Authelia + Nginx | TOTP obligatoire, LDAPS vers AD |
| Backup/PRA | Veeam B&R 13 | 80 Go Oracle en 16 min (CBT), RPO < 24h |
| Pentest | Kali Linux | 0 hôte visible depuis GUEST, XSS détecté par Wazuh |

➡️ **[Voir le repo](https://github.com/Yemah/clinique-chatelet-secure-infra)** · **[Voir la documentation](https://yemah.github.io/clinique-chatelet-secure-infra/)**

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

## 📝 Articles & Retours d'expérience

> *Section en construction — premiers articles à venir*

| # | Sujet prévu | Thème |
|---|---|---|
| 01 | Construire un cluster HA OPNsense avec CARP et pfSync | Firewall |
| 02 | 35 règles Wazuh personnalisées pour un environnement HDS | SIEM |
| 03 | Sécuriser un portail web médical avec Authelia et Nginx | MFA / Zero Trust |
| 04 | Pentester son propre lab : méthodologie et résultats | Pentest |
| 05 | Architecture VLAN et micro-segmentation sur VMware ESXi | Réseau |

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

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Yemah&show_icons=true&theme=default&hide_border=true&count_private=true&locale=fr)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Yemah&layout=compact&theme=default&hide_border=true&locale=fr)

---

*Actuellement à la recherche d'un stage de 4 mois (dès que possible) puis d'une alternance (1 sem école / 3 sem entreprise) à partir de septembre 2026.*
