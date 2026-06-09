# Henry-Tech Network Solutions - Site Web Complet

## 📁 Contenu du ZIP

Ce dossier contient le site web complet de **Henry-Tech Network Solutions** avec back-end fonctionnel pour le formulaire d'inscription.

### Fichiers inclus :
- `index.html` - Page d'accueil
- `services.html` - Page des services
- `apropos.html` - Page À propos
- `inscription.html` - Formulaire d'inscription (AVEC BACK-END)
- `contact.html` - Page de contact
- `merci.html` - Page de confirmation après inscription
- `IMG-20260609-WA0035.jpg` - Photo de profil (utilisée partout)

---

## ⚙️ CONFIGURATION DU BACK-END (IMPORTANT !)

Le formulaire d'inscription utilise **Formspree** pour envoyer les données par email.

### Étape 1 : Créer un compte Formspree
1. Allez sur https://formspree.io
2. Cliquez sur "Sign Up" et créez un compte GRATUIT
3. Vérifiez votre email (henrkabeya26@gmail.com)

### Étape 2 : Créer un formulaire
1. Connectez-vous à votre compte Formspree
2. Cliquez sur "New Form"
3. Donnez un nom : "Inscription Henry-Tech"
4. Cliquez sur "Create Form"

### Étape 3 : Récupérer l'ID
1. Vous verrez une URL comme : `https://formspree.io/f/xrgjwbzy`
2. Copiez l'ID (la partie après `/f/`) : `xrgjwbzy`

### Étape 4 : Modifier le fichier
1. Ouvrez `inscription.html` dans un éditeur de texte (Notepad, VS Code, etc.)
2. Cherchez cette ligne :
   ```html
   <form id="inscriptionForm" action="https://formspree.io/f/VOTRE_ID_FORMSPREE" method="POST">
   ```
3. Remplacez `VOTRE_ID_FORMSPREE` par votre vrai ID
   Exemple : `https://formspree.io/f/xrgjwbzy`
4. Sauvegardez le fichier

### Étape 5 : Tester
1. Ouvrez `inscription.html` dans votre navigateur
2. Remplissez le formulaire
3. Cliquez sur "ENVOYER MON INSCRIPTION"
4. Vérifiez votre email henrykabeya26@gmail.com

---

## ✅ Fonctionnalités du back-end

- ✅ Envoi automatique des données à henrykabeya26@gmail.com
- ✅ Sujet personnalisé : "Nouvelle inscription - Henry-Tech Network Solutions"
- ✅ Réponse automatique envoyée à l'apprenant
- ✅ Redirection vers merci.html après envoi réussi
- ✅ Indicateur de chargement pendant l'envoi
- ✅ Messages de confirmation/erreur en français
- ✅ Validation des champs obligatoires

---

## 🚀 Hébergement

Pour mettre le site en ligne, uploadez tous les fichiers sur votre hébergeur web (Hostinger, InfinityFree, 000webhost, etc.).

---

## 📞 Contact

**Henry-Tech Network Solutions**
- Email : henrykabeya26@gmail.com
- Téléphone : +243 970 710 710 / +243 892 326 705
- WhatsApp : https://wa.me/243970710710

---

*"La fiabilité au cœur du réseau"*
