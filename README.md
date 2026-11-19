# Anvi Mukhvas – ઓર્ડર બુક

Anvi Mukhvas (તાજપુરા, પાલનપુર) માટે ઓર્ડર બુક. એક જ HTML ફાઇલ – કોઈ સર્વર કે ડેટાબેઝ નહીં, બધું બ્રાઉઝરમાં ચાલે છે.

*A single-file offline order book (Gujarati / English) for Anvi Mukhvas. No server, no database – runs entirely in the browser.*

## સુવિધાઓ
- ઓર્ડર ઉમેરો / ફેરફાર / કાઢો, એક પાર્ટીના 3 ઓર્ડર સુધી
- ભાવ પ્રમાણે રકમ, ટ્રાન્સપોર્ટ, એડવાન્સ અને બાકી રકમની આપોઆપ ગણતરી
- A4 બિલ પ્રિન્ટ / PDF, સહી સાથે
- માસિક અને વાર્ષિક રિપોર્ટ (ચાર્ટ સાથે)
- 6 અંકનો પિન લોક
- ગુજરાતી / English
- બેકઅપ ફાઇલ (.json) સેવ અને રીસ્ટોર: બધું બદલો / ફક્ત નવા ઉમેરો / પાછું લો

## વાપરવાની રીત
લિંક ખોલો: `https://<તમારું-યુઝરનેમ>.github.io/<રિપોઝિટરી-નામ>/`

- **મોબાઇલ:** બ્રાઉઝર મેનુ → “Add to Home screen”
- **કમ્પ્યુટર (Edge/Chrome):** મેનુ → Apps → “Install this site as an app”

## ડેટા ક્યાં રહે છે?
ડેટા ફક્ત **તમારા પોતાના બ્રાઉઝર** (localStorage) માં સેવ થાય છે. GitHub પર કોઈ ગ્રાહકનો ડેટા અપલોડ થતો નથી.
તેથી:
- જે ફોન/કમ્પ્યુટર પર ઓર્ડર ભર્યા ત્યાં જ દેખાશે. બીજા ડિવાઇસ પર લઈ જવા બેકઅપ ફાઇલ → રીસ્ટોર વાપરો.
- બ્રાઉઝરનો ડેટા (Clear browsing data) ભૂંસશો તો ઓર્ડર જશે. **રિપોર્ટ ટૅબ → બેકઅપ ફાઇલ સેવ કરો** નિયમિત કરો અને ફાઇલ પેન ડ્રાઇવ / WhatsApp માં રાખો.
- બેકઅપ ફાઇલો (`ANVI_BACKUP_*.json`) માં ગ્રાહકોની વિગત હોય છે – તેને GitHub પર અપલોડ ન કરો (`.gitignore` માં બાકાત છે).

## GitHub Pages પર મૂકવાની રીત
1. GitHub પર **New repository** બનાવો (જેમ કે `anvi-order-book`).
2. “uploading an existing file” પર ક્લિક કરી આ ફોલ્ડરની બધી ફાઇલો (`index.html`, `README.md`, `.gitignore`, `.nojekyll`) ખેંચીને મૂકો → **Commit changes**.
3. **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**.
4. 1-2 મિનિટ પછી ઉપરની લિંક ચાલુ થશે.

## અપડેટ કરવાની રીત
રિપોઝિટરીમાં `index.html` ખોલી ✏ (Edit) કે Upload files થી નવી ફાઇલ મૂકી Commit કરો. ગ્રાહકોનો ડેટા બ્રાઉઝરમાં હોવાથી અપડેટથી ભૂંસાતો નથી.

---
© Anvi Mukhvas. All rights reserved.
