---
layout: bare
title: Extension Furigana Reader - Guide utilisateur
lang: fr
---

# Furigana Reader - Guide utilisateur

> Version : v2.0.0

## Introduction

Furigana Reader est une extension de navigateur destinée aux apprenants du japonais. Grâce à un analyseur morphologique WASM (Lindera) avec repli JavaScript, elle ajoute avec précision des furigana (annotations de lecture) aux kanji sur les pages web, pour faciliter l’apprentissage de la prononciation.

---

## Fonctionnalités principales

- **Annotation par sélection de texte** — Sélectionnez du texte japonais sur une page pour afficher automatiquement les furigana et les boutons de lecture
- **Mode furigana sur toute la page** — Ajoutez des furigana à tous les kanji de la page en un clic
- **Synthèse vocale** — Cliquez sur le bouton haut-parleur pour entendre la prononciation
- **Lecture de la sélection** — Sélectionnez du texte japonais, utilisez le bouton flottant ou le clic droit « Lire la sélection à voix haute »
- **Infobulles au survol** — Survolez les caractères annotés pour voir les furigana et les boutons de prononciation
- **Plusieurs styles de furigana** — Hiragana, katakana et rōmaji
- **Interface multilingue** — 38 langues d’interface

---

## Mode d’emploi

### Étape 1 : Installer l’extension

Installez **Furigana Reader** depuis le [Chrome Web Store](https://chromewebstore.google.com/), ou chargez-la localement en mode développeur.

### Étape 2 : Ouvrir une page web

Ouvrez une page contenant du contenu en japonais.

### Étape 3 : Sélectionner du texte ou utiliser le bouton flottant

Sélectionnez le texte japonais à annoter, ou cliquez sur le bouton flottant en bas à droite pour activer le mode furigana sur toute la page.

### Étape 4 : Consulter les furigana

Survolez les caractères pour afficher les infobulles ; cliquez sur l’icône haut-parleur pour entendre la prononciation.

### Étape 5 : Lire la sélection à voix haute

Sélectionnez du texte japonais, cliquez sur le bouton haut-parleur flottant, ou faites un clic droit puis « Lire la sélection à voix haute ».

> **Astuce :** Cliquez sur l’icône de l’extension dans la barre d’outils pour ouvrir les réglages (style des furigana, débit de parole, etc.).

---

## Guide des paramètres

| Paramètre | Description |
|---------|-------------|
| **Activer les furigana** | Interrupteur principal pour activer ou désactiver les furigana |
| **Furigana sur toute la page** | Affiche les furigana pour tous les kanji (peut modifier la mise en page) |
| **Style des furigana** | Choisir hiragana, katakana ou rōmaji |
| **Débit de parole** | Régler la vitesse de lecture |
| **Infobulles au survol** | Afficher une infobulle de furigana au survol de la souris |

---

## FAQ

**Q : Pourquoi cela ne fonctionne pas sur certaines pages ?**  
R : Pour des raisons de sécurité, les extensions ne s’exécutent pas sur les pages spéciales (`chrome://`), les paramètres du navigateur ou le Chrome Web Store.

**Q : Et si les furigana sont imprécis ?**  
R : Certains mots rares ou lectures spéciales (jukujikun) peuvent être erronés. Nous améliorons continuellement le moteur ; vos exemples nous aident.

**Q : Pas de son pour la synthèse vocale ?**  
R : Vérifiez le volume système et l’installation des voix japonaises. La prise en charge varie selon le navigateur et le système d’exploitation.

**Q : Le mode pleine page modifie la mise en page ?**  
R : Les furigana nécessitent de l’espace supplémentaire. Si la lecture en pâtit, désactivez le mode pleine page et utilisez les infobulles au survol.

---

## Liens utiles

- [Politique de confidentialité](../privacy-policy)
- [Assistance et commentaires](../support)

---
