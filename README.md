# tonystech-charte

Charte graphique **Tony's Tech** — logo, palette, typographie, règles d'usage.

> Le document qui fait autorité : [`CHARTE_GRAPHIQUE_TONYS_TECH.md`](CHARTE_GRAPHIQUE_TONYS_TECH.md)

## Fichiers

| Fichier | Rôle |
|---|---|
| `CHARTE_GRAPHIQUE_TONYS_TECH.md` | la charte complète : couleurs, typo, règles, interdits |
| `project-tonys-tech.webp` | logo original de référence (ne pas retoucher) |
| `logo.svg` | recréation vectorielle éditable du logo |
| `logo.png` | export bitmap transparent 960×640 (web + documents) |

## Palette en un coup d'œil

| | Hex | |
|---|---|---|
| 🟡 Or profond | `#7a5a13` | contours, titres |
| 🟡 Or principal | `#c9962b` | lettrage, accents |
| 🟡 Or clair | `#f6e27a` | cœur de dégradé, surlignages |
| ⚪ Or filet | `#fdf3c4` | filets du globe, reflets |
| ⚫ Encre | `#1d1a16` | texte |
| ⬜ Fond clair | `#faf7f2` | page |
| ⬛ Fond sombre | `#15130f` | page sombre (logo or recommandé) |

L'or = la marque (logo, papeterie, documents commerciaux). L'orange `#d9481e` = l'interface du site `tonys-tech-ia`. Ne pas mélanger.

## Régénérer le PNG après modification du SVG

```powershell
& "C:\Program Files\Google\Chrome\Application\chrome.exe" --headless=new --disable-gpu `
  --hide-scrollbars --default-background-color=00000000 `
  --screenshot="$PWD\logo.png" --window-size=1360,940 `
  "file:///$PWD/logo.svg"
```

---

© 2026 Tony's Tech (Tony Duong) — Licence MIT, voir [LICENSE](LICENSE).
