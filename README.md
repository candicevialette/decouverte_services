# 🛡️ **Configuration des Services Réseau**

![Banner](image/background.png)

## 📄 **Description**
Ce dépôt contient des ressources pour apprendre à configurer des services réseau comme FTP, HTTP, DNS, messagerie, NTP et AAA. Vous y trouverez des guides détaillés et des exercices pour pratiquer la gestion et la sécurisation des services réseau.

Cet atelier est conçu pour renforcer vos compétences dans l'administration réseau et la cybersécurité.

---

## 📚 **Qu'est-ce que ces services ?**

### **FTP (File Transfer Protocol)**
Permet le transfert de fichiers entre machines sur un réseau. Idéal pour centraliser et partager des documents au sein d'une entreprise.

### **HTTP/HTTPS**
Utilisé pour héberger et accéder à des sites web. HTTPS garantit la sécurité grâce au chiffrement des données échangées.

### **DNS (Domain Name System)**
Traduit les noms de domaine en adresses IP pour faciliter la navigation sur Internet.

### **Messagerie (SMTP, POP3)**
Gère l'envoi (SMTP) et la réception (POP3) d'e-mails.

### **NTP (Network Time Protocol)**
Synchronise l'heure entre les appareils d'un réseau pour garantir une précision temporelle.

### **AAA (Authentication, Authorization, Accounting)**
Fournit des services de sécurité pour contrôler l'accès utilisateur et auditer les activités.

---

## 🔗 **Fonctionnalités Principales**

- **Activation et configuration des services réseau**.
- **Création de comptes utilisateurs** avec gestion des permissions (RWDNL).
- **Configuration de réseaux sans fil sécurisés** : WEP, WPA2 PSK, WPA2 RADIUS.
- **Analyse de trafic réseau** pour détecter et corriger les vulnérabilités.
- **Utilisation d'outils de vérification d'intégrité** comme le HMAC.

---
## 📂 **Structure du Dépôt**

```
📂 decouverte_services/
|
├── 📂 Documents/
│   ├── Bloc1_sem1_tp00_decouverte_des_services_VIALETTE_Candice.docx
│   └── Bloc1_sem1_tp00_decouverte_des_services_VIALETTE_Candice.pdf
|
├── 📂 Réseaux/
│   ├── Bloc1_sem1_tp00_decouverte_des_services_01__VIALETTE_Candice
│   ├── Bloc1_sem1_tp00_decouverte_des_services_02__VIALETTE_Candice
│   ├──Bloc1_sem1_tp00_decouverte_des_services_03__VIALETTE_Candice
│   ├──Bloc1_sem1_tp00_decouverte_des_services_04__VIALETTE_Candice
│   ├──Bloc1_sem1_tp00_decouverte_des_services_05__VIALETTE_Candice
│   └── Bloc1_sem1_tp00_decouverte_des_services_06__VIALETTE_Candice
|
├── 📂 image/
│   └── background.png
|
└── README.md


## ⚙️ **Prérequis**

- **Cisco Packet Tracer** installé sur votre machine.
- Connaissances de base en réseau : IP, sous-réseaux, et protocoles comme **ICMP**, **TCP**, **UDP**.

---

## 🚀 **Mise en Œuvre**

### 1. **Cloner le Dépôt**

```bash
git clone https://github.com/votre_nom_utilisateur/tp-services-reseau.git
cd tp-services-reseau
```

### 2. **Suivre les Étapes de Configuration**

1. Ouvrez **Cisco Packet Tracer**.
2. Importez les fichiers `.pka` disponibles dans le dossier `Réseaux/`.
3. Configurez chaque service selon les instructions fournies.

---

## 💡 **Bonnes Pratiques**

- **Sauvegardez régulièrement vos configurations** pour éviter toute perte.
- **Documentez vos topologies réseau** avec des annotations.
- **Testez divers scénarios d'erreurs** pour améliorer vos compétences en dépannage.
- **Préférez HTTPS et SFTP** pour des communications sécurisées.

---

## 📚 **Ressources Utiles**

- [Tutoriels sur les permissions NTFS](https://www.it-connect.fr/serveur-de-fichiers-les-permissions-ntfs-et-de-partage/)
- [Cours Packet Tracer sur NetAcad](https://contenthub.netacad.com/legacy/CyberEss/)

---

## 🌍 **Licence**

Ce projet est sous licence MIT. Consultez le fichier [LICENSE](LICENSE) pour plus d'informations.

---

### 🗓 **Date de Création**
Janvier 2024
