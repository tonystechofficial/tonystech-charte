# CHARTE GRAPHIQUE TONY'S TECH

**Version 1.0 — 6 novembre 2026** — Établie à partir du logo original `project-tonys-tech.webp` (rétro-ingénierie visuelle) et de l'identité en ligne du site `tonys-tech-ia`. Ce document fait autorité pour tout support Tony's Tech.

---

## 1. L'identité

**Tony's Tech** — entreprise individuelle de Tony Duong. Services IA : agents vocaux (réceptionniste IA), assistants sur site, bots messageries, audit sécurité d'agents IA. Positionnement : agents IA conçus comme des surfaces d'attaque, différencié par le passé cybersécurité (TEHTRIS) et la gouvernance IA (AI Act).

Le logo exprime la marque par l'**or** (premium, confiance, exigence) traité en lettrage serif à fort contraste, et par le **globe** qui remplace le O de « TONY'S » (portée internationale, monde connecté).

## 2. Le logo

### 2.1 Construction

- Un très grand **T** serif vertical à gauche, dont la hampe descend sur toute la hauteur du bloc.
- Première ligne : ce T + **globe** (le O) + « **NY'S** ».
- Deuxième ligne : « **ECH** » aligné à droite sous « NY'S » — le T du haut sert donc les deux lignes : **T-ONY'S / T-ECH**.
- Ombre portée grise.SystemFont décalée vers le bas-droite.
- Fonds : transparent ou blanc.

### 2.2 Palette du logo (échantillonnée sur l'original)

| Jeton | Hex | Usage |
|---|---|---|
| `or-profond` | `#7a5a13` | contours, extrémités des lettres, serifs embossés |
| `or-principal` | `#c9962b` | masse principale du lettrage et du globe |
| `or-clair` | `#f6e27a` | cœur de dégradé, faces supérieures |
| `or-filet` | `#fdf3c4` | filets du globe (méridiens, parallèles), reflets |
| `ombre-neutre` | `#9a9b9c` @ 55 % | ombre portée grise, unique |

Le dégradé est **vertical** : profond en haut → clair au centre → moyen en bas.

### 2.3 Fichiers

| Fichier | Rôle |
|---|---|
| `project-tonys-tech.webp` | **Original de référence** — ne jamais retoucher, ne jamais redistribuer |
| `logo.svg` | Recréation vectorielle éditable (gradués, globe tracé) — source de travail |
| `logo.png` | Export bitmap transparent 960×640, généré du SVG — usage web/documents |

### 2.4 Règles d'usage

- **Marge de protection** : sur au moins un diamètre de globe de chaque côté, aucun autre élément.
- **Taille minimale** : 24 px de hauteur à l'écran, 8 mm en impression.
- **Fond recommandé : sombre.** L'or s'y détache le mieux (`#15130f`, `#1d1a16`, ou un noir profond). Sur fond clair, autorisé à condition qu'il soit uni et clair (`#ffffff`, `#faf7f2`).
- Le logo se place toujours **au-dessus ou à gauche** du contenu, jamais noyé dans du texte.

### 2.5 Interdits

Ne jamais : recolorer l'or en une autre teinte, redessiner le globe, étirer/aplatir, remplacer le dégradé par une couleur plate, ajouter un effet (extrusion, néon, relief), poser sur une photo chargée sans voile sombre à 60 % minimum, séparer le globe du lettrage, réutiliser l'ombre portée sur autre chose que le logo.

## 3. Les couleurs de marque

Deux palettes aux rôles distincts — **ne pas mélanger** :

### 3.1 Or de marque (papeterie, documents, supports de communication)

| Jeton | Hex | Usage |
|---|---|---|
| `or-profond` | `#7a5a13` | titres principaux sur fond clair |
| `or-principal` | `#c9962b` | accents, filets, icônes |
| `or-clair` | `#f6e27a` | surlignages, badges |
| `or-filet` | `#fdf3c4` | fonds de module très légers |
| `encre` | `#1d1a16` | corps de texte |
| `fond-clair` | `#faf7f2` | fond page clair |
| `fond-sombre` | `#15130f` | fond page sombre (logo or recommandé ici) |

### 3.2 Palette d'interface du site `tonys-tech-ia` (extrait de `assets/styles.css`)

Jetons à conserver tels quels pour le web applicatif : accent orange `#d9481e` (clair) / `#ff7a50` (sombre), fond `#faf7f2`/`#f2ece3`, surface `#ffffff`, lignes `#e4dccf`, encre `#1d1a16`, corps `#3d3830`, tondu `#7a7166`, et sémantiques : ok `#1f8a5b`, bad `#c0392b`, warn `#b7791f`, proto `#6d5bd0`. Mode sombre : cf. le bloc `@media (prefers-color-scheme: dark)` du fichier.

**Règle** : l'or est la voix de la **marque** (logo, devis, factures, pitch, réseaux). L'orange est la voix de l'**produit** (site web, dashboards). Un document commercial peut utiliser l'or en accent et l'orange pour un bandeau d'appel à l'action, jamais l'inverse généralisé.

## 4. Typographie

| Usage | Police | Graisse | Remarque |
|---|---|---|---|
| Logo (reconstruction SVG) | Georgia / Times New Roman bold | 700 | approximation du serif de l'original ; ne pas substituer une sans-serif |
| Titres de documents (devis, factures, rapports) | Arial, Calibri ou Times New Roman | gras | 16–18 pt Titres, 13–14 pt sous-titres |
| Corps de texte imprimé | Arial ou Calibri | 400 | 11–12 pt, interligne 1,15–1,3 |
| Interface web | Segoe UI / système | 400 | selon `--font` du site |
| Code / chiffrage | Consolas / ui-monospace | 400 | selon `--mono` du site |

Poppins n'est **pas** une police Tony's Tech — elle appartient à la charte ECONUMERICA (autre contexte), ne l'utiliser que sur des documents ECONUMERICA.

## 5. Déclinaison monochrome

Pour impression N&B, gravure, fax, ou contexte où la couleur est interdite : tout le logo en **noir pur `#000000`** (l'or devient du noir, le globe devient du noir à filets blancs, l'ombre portée disparaît). Une version « blanc pur `#ffffff` » sert sur fond photo sombre ou fond noir.

## 6. Application aux documents types

### Devis et factures

- En-tête : logo (border `logo.png` transparent), hauteur 18–25 mm, à gauche.
- Numéro et date du document en `or-profond` gras.
- Tableaux : en-tête de colonne sur fond `or-principal`, texte blanc gras — **mais vérifier le contraste** : blanc sur `#c9962b` ≈ 2,3:1, insuffisant ; utiliser du texte `#1d1a16` sur fond `or-clair` à la place (≈ 9:1), ou fond `or-profond` avec texte blanc (≈ 5,4:1).
- Pied de page : coordonnées + mentions légales en 9–10 pt gris `#7a7166`.

### Présentation / pitch

Fond sombre `#15130f`, logo or en ouverture, titres en `or-clair`, corps en `#d8cfc3` — même relation claire/sombre que le site en mode dark.

## 7. Ce qui n'est pas couvert

- Pas de déclinaison animée, favicon officiel de la marque (le `favicon.svg` actuel du site est orange, il relève de la palette produit — à réviser si on veut l'aligner sur l'or).
- Pas de version horizontale/sticker du logo ; une seule construction existe.
- Échantillonnage des couleurs fait visuellement sur le webp : valeurs fiables à ± 5 %, à ajuster avec une pipette si un support exige une précision supérieure.
- Aucun test d'impression réelle (Pantone/RAL non définis) ; l'or reste un ton direct numérique.

## 8. Régénérer `logo.png` après modification du SVG

```powershell
& "C:\Program Files\Google\Chrome\Application\chrome.exe" --headless=new --disable-gpu `
  --hide-scrollbars --default-background-color=00000000 `
  --screenshot="C:\Users\tony9\Documents\Code\tonystech\logo.png" `
  --window-size=1360,940 `
  "file:///C:/Users/tony9/Documents/Code/tonystech/logo.svg"
```

Si échec silencieux : relancer avec `--virtual-time-budget=10000`, puis `--user-data-dir=<dossier temporaire>`.

---

Charte Tony's Tech — Tony Duong — @astowny
