# Testet — Varianti B

Plotëso pasi ta testosh faqen.

| Testi | Pritja | Rezultati real |
|---|---|---|
| 360 px | Tri oferta njëra poshtë tjetrës; çdo ofertë ka titullin, nivelin dhe lidhjen në rreshta të veçantë. Pa scroll horizontal. | Plotëso |
| 1000 px | Dy oferta në rreshtin e parë; oferta e tretë shtrihet në të gjithë rreshtin e dytë. | Plotëso |
| Menuja dhe Më shumë | ID-të ekzistojnë dhe lidhjet arrijnë te seksioni përkatës | Elementit nav i eshte vene
ID menu, seksionit te kurseve ID kurset, ndersa atij te me shume ID regjishtrimi. Lidhjet perkatese dergojne ne keto seksion duke perdorur #ID ne href te elementit <a> |
| Tab / Enter | Fokusi shihet, lidhja aktivizohet | Pasi kam nderruar stilin per pseudo-klasen
a:focus qe te mos kete outline: none, por outline: 3px solid #0066cc, fokusi shihet me prekjen e Tab |
| Tekst i gjatë te paragrafi i parë | Teksti thyhet brenda kutisë, pa scroll horizontal në 360 px | Duke
perdorur overflow-wrap: break-word; kur kemi nje paragraf te gjate atehere ai do te thuhet brena gjeresise se parapare|
