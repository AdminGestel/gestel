# 📞 GESTEL — Gestion de la téléphonie d’entreprise

**GESTEL** est une application web sécurisée, développée avec **Lovable**, destinée à la gestion complète des équipements télécom d’une entreprise : fiches salariés, lignes mobiles et internet, et contacts de dépannage.

---

## 🔐 Fonctionnalités principales

### 👥 Gestion des salariés
- Nom, Prénom, Société
- Code salarié (4 chiffres)
- Téléphone professionnel :
  - IMEI
  - Numéro
  - Carte SIM
  - Opérateur (Orange, Bouygues, SFR)
- Tablette professionnelle :
  - IMEI
  - Numéro
  - Carte SIM
  - Opérateur

### 🌐 Lignes Internet
- Adresse d’installation
- Type de ligne : ADSL ou Fibre
- Fournisseur d’accès
- Référence du contrat
- Numéro de ligne
- Débit prévu / mesuré
- Contact opérateur
- N° de dépannage

### ☎️ Répertoire de dépannage
- Contacts techniques et commerciaux par opérateur
- Informations centralisées pour : Orange, Bouygues, SFR

---

## 🛡️ Sécurité
- Connexion utilisateur sécurisée
- Authentification à double facteur (2FA)
- Gestion des rôles : Administrateur, RH, IT, Lecture seule

---

## 🛠️ Développement

- **Plateforme principale** : [Lovable.so](https://www.lovable.so)
- **Version actuelle** : `v1.0.0 - Nouvelle base propre`
- **Dépôt GitHub** : à venir

---

## 🧾 Structure future du dépôt

| Dossier               | Description                                           |
|------------------------|-------------------------------------------------------|
| `/exports/`            | Fichiers CSV/JSON exportés depuis l’app              |
| `/docs/`               | Captures, guides d’utilisation, documentation interne|
| `/specs/`              | Spécifications fonctionnelles et techniques          |
| `journal_exports.md`   | Journal des exports de données                       |

---

## 👤 Auteur

Projet initié par : [contact.gestel.pmc@gmail.com](mailto:contact.gestel.pmc@gmail.com)  
Créé avec Lovable, hébergé sur GitHub Pages

---

## 📅 Journal de versions

Voir le fichier [`CHANGELOG.md`](./CHANGELOG.md) pour le suivi des modifications.

