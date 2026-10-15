# Përgjigjet — Varianti B

## P1.7

Shpjego box-sizing: border-box me width, padding dhe border nga kodi yt.

Përgjigjja ime: 
    Ndryshe nga content-bo, border-box detyron qe kontenti bashke me padding dhe border 
    te jete saktesisht sa width, i caktuar, 
    .offers { 
        width: 100%; 
        padding: 2rem; 
        border: 2px solid navy; 
        box-sizing: border-box; 
    }
    Pasi elementi parent i klases offers ka width 320p, atehere edhe ky element do te kete width
    320px, duke perfshire 2px per secilen ane nga border (4px) dhe 2 rem padding nga secila ane (4rem),
    320px - 4px - 4rem = gjeresia e mbetur per kontentin. Nese do kishim perdorur content-box atehere 
    gjeresia e marre per elementin do te ishte 320px + 4px + 4rem;

## P1.8

Pse “Më shumë” është lidhje dhe jo button? Kur do të përdorje button? Nuk kërkohet implementim butoni ose JS.

Përgjigjja ime: …
    Ne kete rasti elementi "Me shume" perdoret per navigimin ne faqe(ngjashem edhe nese jashte faqes), pra 
    lidh nje element me nje tjeter duke mundesuar lundrimin nga nje pike ne tjetren.
    . Butonin do te perdorja nese do te doja qe ai te kryente nje funksion, jo lidhje, si p.sh. submit i nje forme.
