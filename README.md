# Formulaire-interpellation-bcsoRP
🚔 BCSO - Formulaire d'Interpellation Formulaire web interactif pour la gestion des interpellations du Blaine County Sheriff's Office sur serveurs GTA RP.


# 🚔 BCSO - Formulaire d'Interpellation

Formulaire web interactif pour la gestion des interpellations du Blaine County Sheriff's Office sur serveurs GTA RP.

## ✨ Fonctionnalités

- 📋 **102 infractions** du Code Pénal BCSO (8 catégories)
- 💰 **Calcul automatique** des amendes et temps d'incarcération
- 🔍 **Recherche rapide** d'infractions
- ⚖️ **Sélection illimitée** d'infractions
- 📤 **Envoi automatique** sur Discord via webhook
- 🎨 **Design professionnel** aux couleurs BCSO
- 📱 **Responsive** (mobile, tablette, desktop)

## 🚀 Installation

1. Téléchargez `formulaire_interpellation_bcso.html`
2. Ouvrez le fichier avec un éditeur de texte
3. Remplacez la ligne 624 :
```javascript
const DISCORD_WEBHOOK_URL = "VOTRE_WEBHOOK_ICI";
```
4. Collez votre webhook Discord
5. Sauvegardez et ouvrez dans votre navigateur

## 📖 Utilisation

1. Remplissez les **informations du Deputy** (matricule, nom, date, heure)
2. Remplissez les **informations du Suspect** (nom, prénom, lieu)
3. Sélectionnez les **infractions** (autant que nécessaire)
4. Ajoutez des **observations** si besoin
5. Cliquez sur **"Envoyer sur Discord"**

Le rapport est automatiquement envoyé avec un embed formaté !

## 🎯 Contenu

**CODE 1** - Infractions Routières (23)
**CODE 2** - Atteintes à l'Autorité (12)
**CODE 3** - Atteintes aux Personnes (18)
**CODE 4** - Atteintes aux Biens (14)
**CODE 5** - Armes et Explosifs (15)
**CODE 6** - Stupéfiants (10)
**CODE 7** - Prison (4)
**CODE 8** - Parc et Nature (6)

## 🔗 Webhook Discord

Créez un webhook : Discord → Paramètres salon → Intégrations → Webhooks → Nouveau

## 📸 Aperçu

- Interface moderne avec couleurs BCSO (Or + Bleu marine)
- Badges colorés par type d'infraction (Infraction/Délit/Crime)
- Calcul en temps réel des totaux
- Embed Discord professionnel

## 🛠️ Technologies

- HTML5 / CSS3 / JavaScript Vanilla
- Design responsive
- Aucune dépendance externe

## ⚠️ Important

- Gardez votre webhook Discord privé
- Pas de limite d'infractions sélectionnables
- Compatible avec tous les navigateurs modernes

## 📝 Licence

MIT License - Libre d'utilisation pour serveurs GTA RP

---

**Blaine County Sheriff's Office**
*"To Serve - To Protect - With Honor"*
