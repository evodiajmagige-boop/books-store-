# SomaVitabu - Online Books Store

SomaVitabu ni mradi wa tovuti (website) rahisi inayowakilisha duka la kuuza vitabu mtandaoni. Mradi huu umetengenezwa kwa kutumia HTML rahisi na CSS iliyoboreshwa ili kutoa muonekano wa kisasa (premium) na unaovutia, lakini ukiwa rahisi kueleweka.

## 🚀 Teknolojia Zilizotumika
* **HTML5:** Kwa ajili ya kutengeneza muundo wa kurasa zote za tovuti. Nimetumia 'Semantic HTML' (kama vile `<header>`, `<nav>`, `<section>`, `<footer>`) ili kurahisisha usomaji wa kodi.
* **CSS3:** Kwa ajili ya kupendezesha tovuti (Styling). Nimetumia *Vanilla CSS* (Bila mfumo kama Bootstrap) lakini imeboreshwa kuwa na muonekano wa kisasa.
* **Google Fonts (Poppins):** Ili kufanya maandishi yawe safi na ya kisasa.

## 📂 Muundo wa Kurasa
Mradi huu una kurasa kuu sita (6):

1. `index.html` - **Ukurasa Mkuu (Home)**
   * Ina "Hero Section" yenye picha kubwa inayoleta mvuto (Background image with gradient overlay).
   * Inaorodhesha baadhi ya vitabu maarufu katika muundo wa "Grid" unaovutia.

2. `vitabu.html` - **Orodha ya Vitabu (Books Shop)**
   * Inaonyesha vitabu vyote vinavyopatikana dukani vikiwa na picha, jina la kitabu, bei, na kitufe cha "Ongeza Kikapu".
   * Kadi za vitabu (Book Cards) zina "Micro-animations" pale unapopeleka mouse (Hover effects) ambapo kitabu kinasogea juu kidogo na picha inajivuta.

3. `kikapu.html` - **Kikapu cha Manunuzi (Shopping Cart)**
   * Ina jedwali (Table) safi na la kisasa linaloonyesha vitabu ambavyo mteja amechagua kununua, idadi, bei, na jumla kuu.

4. `kuhusu.html` - **Kuhusu Sisi (About Us)**
   * Inaelezea historia, dira, na sababu za kwanini wateja wanapaswa kununua vitabu kwenye duka la SomaVitabu.

5. `mawasiliano.html` - **Mawasiliano (Contact Us)**
   * Ina fomu safi iliyotengenezwa vizuri yenye muonekano mzuri (shadows and rounded corners) inayomruhusu mteja kutuma ujumbe au kuuliza maswali. Pia inaonyesha taarifa zingine za mawasiliano.

6. `akaunti.html` - **Akaunti (Login/Register)**
   * Ukurasa maalum wa mteja kuingia (Login) kwenye akaunti yake, uliobuniwa kwa umakini ili kuvutia macho ya mtumiaji.

## ✨ Vipengele vya Muonekano (Design Highlights)
* **Glassmorphism Header:** Sehemu ya juu (Menyu) ina muonekano kama kioo kinachopitisha mwanga (blur effect), inakaa juu (sticky) mtumiaji anaposhusha ukurasa chini.
* **Smooth Animations:** Hover effects kwenye buttons, links, na kadi za vitabu hufanya tovuti iwe "hai" na yenye kuvutia mwingiliano (Interaction).
* **Color Palette:** Matumizi mazuri ya rangi ya 'Emerald Green' na 'Dark Slate' yanaleta hisia ya uaminifu na uchangamfu wa duka.

## 🛠️ Jinsi ya Kutumia (Jinsi ya Kuona Website)
1. Hakikisha mafaili yote (`style.css` na mafaili yote sita ya `.html`) yapo kwenye folder moja.
2. Nenda kwenye folda hilo, kisha bofya mara mbili (Double click) faili la `index.html`.
3. Faili hilo litafunguka kwenye kivinjari chako (Browser kama Chrome au Firefox) na utaweza kuona na kutumia website yako yote.

## ✍️ Kuhusu Kodi (Code Maintainability)
Kodi zimeandikwa zikiwa zimetenganishwa vizuri. Ukitaka kubadilisha rangi kuu au fonts, unahitaji tu kwenda kwenye faili la `style.css` na kubadilisha vipengele vilivyo chini ya `:root`. Kila sehemu ina "comments" kuelekeza inachofanya.
