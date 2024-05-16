![[Screenshot from 2024-05-16 14-30-37.png]]
## Feladat

## Megnevezések
-  $\overline{LO}$ : kapu (7.35 m)
- $\overline{JK}$ : a focipálya szélességének a fele (25 m)
- P : illeszkedik a focipálya hosszabbik oldalára, ebből a pontból nézünk a $\overline{JK}$-ra
- a = |PJ| = |QO|
- $\alpha$ : QPO$\measuredangle$ 
- $\beta$ : OPL$\measuredangle$ 
- $\gamma$ : LPJ$\measuredangle$ 
## Megoldás

$\beta = 90\degree - (\alpha + \gamma$)
Tehát ahhoz, hogy $\beta$-t maximalizájuk $\alpha + \gamma$ minimalizálnunk kell.
Belátható, hogy $0\degree \leq \alpha + \gamma \lt 90\degree$
$x \in [0\degree, 90\degree[$ tartományban $\tan(x)$ szigorúan monoton növekvő $\Rightarrow$
$\alpha + \beta$ minimalizálása $\Leftrightarrow$ $\tan(\alpha + \beta)$ minimalizálása
# $\tan(\alpha + \beta) = \frac {\tan(\alpha) + \tan(\beta)} {1-\tan(\alpha)*\tan(\beta)}$
# $|JL| =|JK| - |LK| = |JK| - \frac {|LO|} {2} = 21.375$
# $|PQ| =|JK| + |KO| = |JK| + \frac {|LO|} {2} = 28,675$
# $\tan(\alpha) = \frac {|JL|} {a} = \frac {21,325} {a}$
# $\tan(\beta) = \frac {a} {|PQ|} = \frac {a} {28,675}$
# $\frac {\tan(\alpha) + \tan(\beta)} {1-\tan(\alpha)*\tan(\beta)} = \frac {\frac {21,325} {a} + \frac {a} {28,675}} {1-\frac {21,325} {a}*\frac {a} {28,675}} = \frac {\frac {21,325} {a} + \frac {a} {28,675}} {0,256320837}$
Ahhoz, hogy ez a tört minél kisebb legyen úgy kell megválasztani $a$-t, hogy a számláló a lehető legkisebb legyen. Ehhez kihasználhatjuk, hogy két szám számtani közepe mindig nagyobb egyenlő annak a két számnak a mértani közepével. Tehát:
# $\frac {{\frac {21,325} {a} + \frac {a} {28,675}}} {2} \geq \sqrt{{\frac {21,325} {a} * \frac {a} {28,675}}}$
# ${\frac {21,325} {a} + \frac {a} {28,675}} \geq 2*\sqrt{{\frac {21,325} {a} * \frac {a} {28,675}}}$
Tehát a számlálóban szereplő összeg, akkor a lehető legkisebb amikor megegyezik a mértani közép kétszeresével. (Ez a helyzet akkor kés csak akkor áll fenn, amikor az összgebe a két tört egyenlő)
# $2*\sqrt{{\frac {21,325} {a} * \frac {a} {28,675}}} = 2*\sqrt{{\frac {21,325} {28,675}}}$
Így:
# $\frac {\frac {21,325} {a} + \frac {a} {28,675}} {0,256320837} = \frac {2*\sqrt{\frac {21,325} {28,675}}} {0,256320837}$

