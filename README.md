# 🐦 Flappy Sky – Guide de déploiement et monétisation

## Présentation

**Flappy Sky** est un jeu de type Flappy Bird développé en HTML5/CSS3/JavaScript pur, sans dépendances externes. Il est prêt à être mis en ligne et monétisé via Google AdSense.

---

## Mise en ligne sur GitHub Pages (gratuit)

### Étape 1 – Créer un compte GitHub
Rendez-vous sur [github.com](https://github.com) et créez un compte gratuit.

### Étape 2 – Créer un dépôt
1. Cliquez sur **New repository**
2. Nommez-le `flappy-sky` (ou tout autre nom)
3. Cochez **Public**
4. Cliquez **Create repository**

### Étape 3 – Uploader les fichiers
1. Cliquez sur **uploading an existing file**
2. Glissez-déposez `index.html` et `privacy.html`
3. Cliquez **Commit changes**

### Étape 4 – Activer GitHub Pages
1. Allez dans **Settings** → **Pages**
2. Source : **Deploy from a branch** → branche **main** → dossier **/ (root)**
3. Cliquez **Save**

Votre jeu sera accessible à l'adresse :
`https://VOTRE_PSEUDO.github.io/flappy-sky/`

---

## Monétisation avec Google AdSense

### Étape 1 – Créer un compte AdSense
Rendez-vous sur [adsense.google.com](https://adsense.google.com) et inscrivez-vous.

### Étape 2 – Ajouter votre site
Entrez l'URL de votre jeu GitHub Pages et attendez la validation (24–72h).

### Étape 3 – Remplacer les placeholders dans index.html
Ouvrez `index.html` et remplacez **toutes** les occurrences de :
- `ca-pub-XXXXXXXXXXXXXXXX` → votre ID éditeur AdSense (ex: `ca-pub-1234567890123456`)
- `1111111111` → ID de votre bloc d'annonce haut de page
- `2222222222` → ID de votre bloc d'annonce latéral gauche
- `3333333333` → ID de votre bloc d'annonce latéral droit
- `4444444444` → ID de votre bloc d'annonce bas de page

### Emplacements publicitaires intégrés

| Position | Format | Taille |
|---|---|---|
| Haut de page | Leaderboard | 728×90 |
| Latéral gauche | Wide Skyscraper | 160×600 |
| Latéral droit | Wide Skyscraper | 160×600 |
| Bas de page | Leaderboard | 728×90 |

---

## Estimation des revenus

| Trafic mensuel | RPM estimé | Revenus estimés |
|---|---|---|
| 1 000 visiteurs | 0,50–2 € | 0,50–2 €/mois |
| 10 000 visiteurs | 0,50–2 € | 5–20 €/mois |
| 100 000 visiteurs | 0,50–2 € | 50–200 €/mois |

> **Conseil** : Partagez le lien sur Reddit (r/WebGames), itch.io, et les réseaux sociaux pour augmenter le trafic.

---

## Autres plateformes de monétisation

- **[itch.io](https://itch.io)** : Publiez le jeu gratuitement, activez les dons volontaires
- **[Newgrounds](https://newgrounds.com)** : Communauté de jeux flash/HTML5
- **[GameMonetize](https://gamemonetize.com)** : Plateforme spécialisée jeux HTML5 avec partage de revenus

---

## Améliorations possibles pour augmenter les revenus

1. Ajouter un système de **skins d'oiseaux** (personnages à débloquer)
2. Intégrer un **classement en ligne** (leaderboard)
3. Ajouter une **publicité interstitielle** entre les parties
4. Traduire le jeu en anglais pour toucher un public mondial
5. Créer une **version mobile** (PWA) installable sur smartphone
