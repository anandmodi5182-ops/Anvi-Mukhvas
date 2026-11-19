# Anvi Mukhvas – Order Book

Mobile-friendly order book (Gujarati / English, dark / light, PIN lock, A4 print / PDF).
Data browser ma j save thay che (localStorage) – regular "બેકઅપ કોપી" karo.

## GitHub Pages par chalu karvani rit
1. github.com par **New repository** banavo (name: `anvi-order-book`, Public ya Private).
2. **Add file → Upload files** ma aa folder ni badhi files (`index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`, `.nojekyll`, `README.md`) draw karo → **Commit changes**.
3. **Settings → Pages → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**.
4. 1-2 minute pachhi link malshe: `https://<tamaru-username>.github.io/anvi-order-book/`
5. Phone ma e link kholo → browser menu → **Add to Home screen** (app jevu install thase, offline pan chalshe).

## Update karvu hoy to
`index.html` ne navi file thi replace karo ane `sw.js` ma `const V='anvi-v1'` ma number vadharo (`anvi-v2`) jethi phone ma navu version aave.

## Note
- PIN lock browser-side che (sada deterrent). Public repo ma code koi pan jai shake che.
- Data darek phone/browser ma alag save thay che.
