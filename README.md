# BURGA koncepcija – mokomasis HTML prototipas

Neoficialus vieno puslapio svetainės prototipas, skirtas PD4 užduočiai. Nesusijęs su oficialia BURGA parduotuve.

## Failai
- `index.html` – septyni svetainės blokai, SEO, 8 DUK ir FAQPage JSON-LD.
- `styles.css` – mobiliesiems pritaikytas stilius, be išorinių bibliotekų.
- `script.js` – demonstracinė kontaktų forma, nieko nesiunčianti.
- `assets/*.svg` – 7 laikinos scheminės iliustracijos, **ne tikros produktų nuotraukos**.

## Peržiūra
Atidarykite `index.html` naršyklėje. Visi failai turi likti toje pačioje aplankų struktūroje.

## GitHub Pages
1. Sukurkite viešą GitHub saugyklą, pvz., `burga-aksesuarai`.
2. Įkelkite `index.html`, `styles.css`, `script.js` ir visą `assets` aplanką į saugyklos šaknį.
3. Saugyklos Settings → Pages → Build and deployment: Deploy from a branch → `main` / `(root)` → Save.
4. Patikrinkite viešą nuorodą ir mobiliąją versiją.

## Svarbios ribos
- `robots` nustatyta `noindex, nofollow`, kad mokomasis, neoficialus prototipas nebūtų indeksuojamas kaip oficiali parduotuvė. SEO vertinimui galima parodyti HTML title, meta description, antraštes, ALT ir FAQPage JSON-LD, tačiau realiai indeksacijai `noindex` trukdo.
- Pavyzdinės kainos ir pristatymo sąlygos nėra oficialūs BURGA pasiūlymai.
- DUK minimi suderinamumo sąrašai dar nesukurti. Prieš realų naudojimą reikia suderinti tekstą su faktine funkcija.
- Kontaktų forma yra tik demonstracinė; nėra klientų aptarnavimo kanalo.
- Naudojami sisteminiai atsarginiai šriftai (Georgia ir Arial), nes „Playfair Display“ ir „Raleway“ failai nepateikti, o užduotis draudžia išorines bibliotekas. Galima vėliau pridėti teisėtai įgytus vietinius šriftų failus.
- Nėra svetimų logotipų ar trečiųjų šalių produktų fotografijų. Tekstinis BURGA pavadinimas naudojamas tik mokomojo projekto kontekstui, su aiškiu neoficialumo įspėjimu.
- FAQPage schema techniškai įdėta, bet paieškos sistemos neprivalo rodyti išplėstinių rezultatų.

## Dizaino atnaujinimas (P5 v2)
- Modernesnis minimalistinis pirmasis ekranas, lipni navigacija ir ryškesni CTA.
- Produktų kortelėse parodytos visos penkios P3 patvirtintos **pavyzdinės** kainos.
- Atnaujinti DUK išskleidimo indikatoriai ir kontaktų forma.
- P1–P4 tekstai, SEO meta duomenys ir FAQPage JSON-LD išsaugoti.
- Kontaktų forma demonstracinė; produktų modelių sąrašai dar neįgyvendinti.
