---
layout: bare
title: Extension Furigana Reader - Guide utilisateur
lang: fr
---

# Furigana Reader - Guide utilisateur

> Version : v1.4.0

## Introduction

Furigana Reader est une extension de navigateur destinée aux apprenants du japonais. Grâce à un analyseur morphologique WASM (Lindera + IPAdic) avec repli JavaScript, elle ajoute avec précision des annotations de lecture furigana aux kanji sur les pages web et les PDF. Elle inclut aussi un dictionnaire japonais intégré, la synthèse vocale et la traduction — pour faciliter l’apprentissage de la prononciation japonaise.

---

## Principales fonctionnalités

- **Mode furigana pour toute la page** — Ajoutez des annotations furigana à tous les kanji de la page en un clic
- **Dictionnaire au survol** — Survolez les caractères annotés pour voir les définitions JMdict (plus de 180 000 entrées), les lectures, les badges de niveau JLPT (N5–N1) et les boutons de prononciation ; choisissez le mode Dictionnaire, Lecture ou Désactivé
- **Lecteur PDF** — Lecteur PDF intégré avec furigana, dictionnaire, parole et traduction ; glisser-déposer, chargement par URL, détection automatique des PDF et redirection intelligente
- **Trois styles de lecture** — Affichage en hiragana, katakana ou rōmaji
- **Séparation de l’okurigana** — Sépare correctement l’okurigana (送り仮名) des radicaux en kanji
- **Prise en charge du jukujikun** — Lectures correctes pour les composés multi-kanji à lecture spéciale (熟字訓)
- **Synthèse vocale** — Cliquez sur le bouton haut-parleur pour entendre la prononciation japonaise
- **Lecture de la sélection avec effet karaoké** — Sélectionnez du texte japonais ; une barre d’outils compacte apparaît avec lecture et traduction ; la voix met en surbrillance mot par mot ou caractère par caractère en temps réel (effet karaoké), synchronisée avec l’audio
- **Traduction de la sélection** — Sélectionnez du texte, cliquez sur traduire dans la barre d’outils pour une traduction instantanée via Bing ou Google Traduction, affichée dans une bulle intégrée
- **Raccourcis clavier** — Accès rapide aux fonctions principales via des raccourcis personnalisables
- **Interface multilingue** — Prend en charge 38 langues d’interface

---

## Mode d’emploi

### Étape 1 : Installer l’extension
Installez **Furigana Reader** depuis le [Chrome Web Store](https://chromewebstore.google.com/), ou chargez-la localement en mode développeur.

### Étape 2 : Ouvrir une page web
Visitez une page contenant du japonais.

### Étape 3 : Activer le furigana
Cliquez sur l’icône de l’extension dans la barre d’outils. Activez « Activer le furigana », puis « Furigana pour toute la page » pour annoter tous les kanji. Vous pouvez aussi utiliser le bouton flottant en bas à droite.

### Étape 4 : Voir le furigana
Survolez les caractères pour voir les infobulles furigana avec lectures et définitions. Cliquez sur l’icône haut-parleur pour la prononciation.

### Étape 5 : Lire et traduire la sélection
Sélectionnez du texte japonais à la souris. Une barre d’outils compacte apparaît près de la sélection avec deux boutons :
- **🔊 Lire** — Lit la sélection à voix haute avec surbrillance type karaoké
- **🌐 Traduire** — Affiche une bulle de traduction sous la barre d’outils

Vous pouvez aussi faire un clic droit et choisir « Furigana Reader > Lire la sélection à voix haute » ou « Furigana Reader > Traduire la sélection ».

> **Astuce :** Cliquez sur l’icône de l’extension pour ouvrir les réglages : style de furigana, mode au survol, débit vocal, moteur de traduction, etc.

---

## Dictionnaire au survol

L’extension inclut un dictionnaire japonais intégré basé sur JMdict (plus de 180 000 entrées). Vous pouvez choisir plusieurs modes de survol dans les paramètres :

| Mode | Comportement |
|------|----------------|
| **Dictionnaire** | Le survol affiche lecture + définition + niveau JLPT + bouton de prononciation |
| **Lecture** | Le survol affiche lecture + bouton de prononciation (sans définitions) |
| **Désactivé** | Aucun effet au survol |

En **mode Dictionnaire**, l’infobulle affiche :
- Le mot et sa lecture (furigana)
- Un bouton de prononciation (clic pour écouter)
- Les définitions japonaises issues de JMdict
- Un badge de niveau JLPT (N5–N1) lorsque disponible

> **Astuce :** Les données du dictionnaire se chargent à la demande lorsque le mode Dictionnaire est activé, et se déchargent sur les autres modes pour économiser la mémoire.

---

## PDF Reader

Furigana Reader inclut un lecteur PDF intégré : furigana, dictionnaire, parole et traduction — les mêmes fonctions que sur le web, pour les PDF.

### Ouvrir un PDF

**Méthode 1 : depuis la fenêtre contextuelle**  
Cliquez sur l’icône de l’extension, puis sur « Ouvrir le lecteur PDF ». Glissez-déposez un fichier PDF ou cliquez sur « Choisir un fichier » pour un PDF local. Vous pouvez aussi coller une URL de PDF.

**Méthode 2 : menu contextuel**  
Clic droit sur un lien `.pdf` et choisissez « Ouvrir le PDF avec Furigana Reader ».

**Méthode 3 : détection automatique**  
Si « Détection intelligente des PDF » est activée, l’extension redirige automatiquement les URL se terminant par `.pdf` vers le lecteur intégré. Si un PDF est détecté sans redirection (ex. visionneuse Chrome intégrée), des notifications vous invitent à l’ouvrir dans Furigana Reader.

### Fonctions du lecteur PDF

- **Annotations furigana** — Toutes les fonctions furigana sur le texte PDF, y compris le mode pleine page et les infobulles au survol
- **Cinq modes furigana** — Hiragana, katakana, rōmaji, survol uniquement et désactivé
- **Dictionnaire au clic** — Cliquez sur un mot pour la définition JMdict (dans le PDF, le clic remplace le survol pour une lecture sans distraction)
- **Barre d’outils de sélection** — Sélectionnez du texte pour lire, traduire ou copier
- **Barre latérale** — Plan du document et miniatures de pages
- **Recherche** — Recherche plein texte dans le PDF
- **Thèmes** — Sombre, clair et sépia
- **Zoom** — Plusieurs niveaux de zoom, dont furigana adaptatif au zoom
- **Raccourcis clavier** — Flèches pour naviguer, +/- pour le zoom, Ctrl/Cmd+F pour la recherche

---

## Lecture de la sélection et karaoké

La lecture de la sélection permet de sélectionner du japonais et de le lire à voix haute en un clic — idéal pour la prononciation en phrase et la lecture.

**Méthode 1 : barre d’outils de sélection**  
Sélectionnez du texte japonais. Une barre compacte avec 🔊 lire et 🌐 traduire apparaît. Cliquez sur lire. Pendant la lecture, chaque mot ou caractère est surligné en temps réel (effet karaoké).

**Méthode 2 : menu contextuel**  
Après sélection : clic droit, « Furigana Reader > Lire la sélection à voix haute ».

**Méthode 3 : raccourci clavier**  
Sélectionnez du texte et appuyez sur `Alt+Shift+S` (Mac : `Ctrl+Shift+S`).

> **Astuce :** L’effet karaoké fonctionne mieux si le navigateur prend en charge les événements de limites de mots TTS. Sinon, l’extension utilise une solution de repli temporelle.

---

## Traduction

Sélectionnez du texte sur la page et utilisez la traduction pour obtenir une traduction instantanée.

**Méthode 1 : barre d’outils de sélection**  
Sélectionnez du texte, puis cliquez sur 🌐 traduire. Une bulle s’affiche en dessous avec le résultat et un bouton copier.

**Méthode 2 : menu contextuel**  
Sélectionnez du texte, clic droit, « Furigana Reader > Traduire la sélection ».

**Méthode 3 : raccourci clavier**  
Sélectionnez du texte et appuyez sur `Alt+Shift+T` (Mac : `Ctrl+Shift+T`).

**Moteurs de traduction :**
- **Bing Traduction** (par défaut) — Microsoft Translator
- **Google Traduction** — Google

Les deux prennent en charge **108 langues cibles**.

Vous pouvez changer le moteur et la langue cible dans les paramètres de l’extension. La langue cible est déduite de la langue du navigateur.

> **Astuce :** Cliquez en dehors de la barre ou de la bulle pour les fermer.

---

## Raccourcis clavier

| Raccourci | Mac | Action |
|-----------|-----|--------|
| `Alt+Shift+F` | `Ctrl+Shift+F` | Activer / désactiver les annotations furigana |
| `Alt+Shift+S` | `Ctrl+Shift+S` | Lire la sélection à voix haute |
| `Alt+Shift+T` | `Ctrl+Shift+T` | Traduire la sélection |

> **Astuce :** Personnalisez ces raccourcis dans Chrome via `chrome://extensions/shortcuts`.

---

## Guide des paramètres

| Paramètre | Description |
|-----------|-------------|
| **Activer le furigana** | Interrupteur principal pour activer ou désactiver les annotations furigana |
| **Furigana pour toute la page** | Affiche le furigana pour tous les kanji (peut modifier la mise en page) |
| **Mode au survol** | Comportement au survol : Dictionnaire (lecture + définitions + JLPT + audio), Lecture (lecture + audio) ou Désactivé |
| **Style de furigana** | Hiragana, katakana ou rōmaji |
| **Débit vocal** | Vitesse de lecture des phrases |
| **Moteur de traduction** | Bing Traduction ou Google Traduction |
| **Langue cible** | Langue cible de la traduction (détectée automatiquement à partir du navigateur) |
| **Détection intelligente des PDF** | Redirige les URL PDF vers le lecteur intégré et affiche des notifications lorsque des PDF sont détectés |

---

## FAQ

**Q : Pourquoi cela ne fonctionne-t-il pas sur certaines pages ?**  
R : Pour des raisons de sécurité, les extensions ne s’exécutent pas sur les pages spéciales (`chrome://`, paramètres du navigateur, Chrome Web Store, etc.).

**Q : Et si le furigana est imprécis ?**  
R : Certains mots rares ou lectures spéciales (熟字訓) peuvent être erronés. Nous améliorons continuellement le produit ; signalez des cas précis pour nous aider.

**Q : Pas de son pour la synthèse vocale ?**  
R : Vérifiez le volume système et l’installation des voix japonaises. La prise en charge varie selon navigateur et système.

**Q : Le mode pleine page modifie la mise en page ?**  
R : Les annotations furigana nécessitent de l’espace et peuvent modifier la page. Si cela gêne, désactivez le mode pleine page et utilisez uniquement les infobulles au survol.

**Q : La traduction ne marche pas ?**  
R : La traduction nécessite Internet. Si Bing échoue, essayez Google dans les paramètres. Certains réseaux bloquent les services de traduction.

**Q : Comment ouvrir un PDF avec Furigana Reader ?**  
R : Via « Ouvrir le lecteur PDF » dans la fenêtre de l’extension, clic droit sur un lien PDF « Ouvrir le PDF avec Furigana Reader », ou activez « Détection intelligente des PDF » pour rediriger automatiquement les URL `.pdf`.

**Q : La détection intelligente est activée mais certains PDF ne redirigent pas ?**  
R : La redirection automatique concerne les URL se terminant par `.pdf`. Pour les PDF sans extension ou ouverts dans la visionneuse Chrome, une notification et un badge vous invitent à ouvrir dans Furigana Reader.

**Q : Puis-je utiliser le dictionnaire hors ligne ?**  
R : Oui. Le dictionnaire JMdict (plus de 180 000 entrées) est entièrement inclus dans l’extension. Toutes les recherches sont locales, sans réseau.

---

## Liens utiles

- [Politique de confidentialité](../privacy-policy)
- [Assistance et commentaires](../support)

---
