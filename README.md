# 🩺 MédFlash by H0cine

Application de révision médicale pour la L1 — Université Paris-Est Créteil (UPEC).

## ✨ Fonctionnalités

- **Flashcards** avec retournement animé (recto = question, verso = réponse + explication)
- **Mode Quiz** avec cases à cocher (QCM à réponses multiples type concours)
- **Annales Concours** 2012→2026 — 110 QCM officiels
- **Suivi de progression** par matière
- **Lecteur musical** intégré (fichier MP3 séparé)
- **Shame Mode** 💀 pour les mauvaises réponses

## 📚 Matières disponibles (Semestre 2)

| Matière | Fiches | Type |
|---|---|---|
| Bioinformatique | 38 | Flashcards + Quiz |
| Circulation & Respiration | 125 | Flashcards + Quiz |
| Pharmacologie | 60 | Flashcards + Quiz |
| Régulation Neuro-Endocrinienne | 84 | Flashcards + Quiz |
| SHS (Anthropo, Psycho, Cognition) | 99 | Flashcards + Quiz |
| Squelette & Motricité | 8 cours | Flashcards + Quiz |
| **Annales Concours** | **110 QCM** | **Quiz uniquement** |

### 🎯 Annales Concours
- **Biostats** : 25 QCM (probabilités, tests, épidémio, survie)
- **Imagerie** : 30 QCM (OEM, ultrasons, radioactivité, rayons X, IRM)
- SN Neurones, SNA, Potentiel d'action, Fonction digestive, Axe hypothalamo-hypophysaire, Bioinformatique, Colle anatomie digestif

## 🚀 Utilisation

### Option 1 — Directement dans le navigateur
1. Téléchargez `medflash.html`
2. Ouvrez-le dans votre navigateur (double-clic)
3. C'est tout ! Aucune installation requise.

### Option 2 — Avec la musique
1. Téléchargez `medflash.html` **ET** `calm_humming.mp3`
2. Placez les deux fichiers **dans le même dossier**
3. Ouvrez `medflash.html`

> ℹ️ Sans le fichier MP3, l'application fonctionne parfaitement — le lecteur musical sera simplement silencieux.

### Option 3 — GitHub Pages
1. Forkez ce dépôt
2. Activez GitHub Pages (Settings → Pages → Branch: main)
3. Accédez à `https://votre-username.github.io/medflash`

## 🛠 Structure du projet

```
medflash/
├── medflash.html        # Application complète (2.6 MB)
├── al_kahf.mp3              # سورة الكهف — Al-Kahf
├── ya_sin.mp3               # سورة يس — Ya-Sin
├── maryam_omar_hisham.mp3   # سورة مريم — Omar Hisham Al Arabi
├── luqman_yasser_dosari.mp3 # سورة لقمان — Yasser Al-Dosari
└── al_mulk_feysal.mp3       # سورة الملك — Imam Feysal
└── README.md
```

## 📖 Technologies

- HTML/CSS/JS vanilla — aucune dépendance externe
- Stockage local (localStorage) pour la progression
- Compatible mobile et desktop

---
*Fait avec ❤️ pour les étudiants en médecine de Paris-Est Créteil*
