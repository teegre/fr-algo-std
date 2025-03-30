# FR-ALGO Librairie Standard

Une librairie standard pour **FR-ALGO**.

En cours de développement.

## Installation

Copier les fichiers présents dans `src` vers le répertoire `$HOME/.local/lib/fralgo/`.

## STDLIB

### Fonctions et Procédures

* `Abs` : Fonction Abs(n en Quelconque) en Quelconque
* `AléaP` : Fonction AléaP(poids[] en Numérique) en Entier
* `Arrondir` : Fonction Arrondir(n en Numérique, p en Entier) en Numérique
* `Base` : Fonction Base(nombre en Entier, base en Entier) en Chaîne
* `Base10` : Fonction Base10(nombre en Quelconque, base en Entier) en Entier
* `Capitaliser` : Fonction Capitaliser(ch en Chaîne) en Chaîne
* `CommencePar` : Fonction CommencePar(ch en Chaîne, v en Chaîne) en Booléen
* `Compter` : Fonction Compter(T[] en Quelconque, valeur en Quelconque) en Entier
* `Contient` : Fonction Contient(ch en Chaîne, v en Chaîne) en Booléen
* `EstAlpha` : Fonction EstAlpha(ch en Chaîne) en Booléen
* `EstNum` : Fonction EstNum(ch en Chaîne) en Booléen
* `FinitPar` : Fonction FinitPar(ch en Chaîne, v en Chaîne) en Booléen
* `Grouper` : Procédure Grouper(T[] en Quelconque, &G[] en Quelconque)
* `Index` : Fonction Index(T[] en Quelconque, valeur en Quelconque) en Entier
* `IndexSC` : Fonction IndexSC(T[] en Chaîne, valeur en Chaîne) en Entier
* `Insérer` : Procédure Insérer(&T[] en Quelconque, valeur en Quelconque, index en Entier)
* `Inverser` : Procédure Inverser(&T[] en Quelconque)
* `Majus` : Fonction Majus(ch en Chaîne) en Chaîne
* `Max` : Fonction Max(a en Quelconque, b en Quelconque) en Quelconque
* `Min` : Fonction Min(a en Quelconque, b en Quelconque) en Quelconque
* `Minus` : Fonction Minus(ch en Chaîne) en Chaîne
* `Mélanger` : Procédure Mélanger(&T[] en Quelconque)
* `Pop` : Fonction Pop(&T[] en Quelconque) en Quelconque
* `Remplacer` : Fonction Remplacer(ch en Chaîne, oc en Chaîne, rp en Chaîne) en Chaîne
* `RemplirGauche` : Fonction RemplirGauche(ch en Quelconque, oc en Quelconque, long en Entier) en Chaîne
* `Scinder` : Procédure Scinder(chaine en Chaîne, separateur en Chaîne, &elements[] en Chaîne)
* `Somme` : Fonction Somme(T[] en Quelconque) en Quelconque
* `Supprimer` : Procédure Supprimer(&T[] en Quelconque, index en Entier)
* `Séparer` : Procédure Séparer(chaîne en Chaîne, &elements[] en Chaîne)
* `TContient` : Fonction TContient(T[] en Quelconque, v en Quelconque) en Booléen
* `TConvertir` : Procédure TConvertir(source[] en Quelconque, &cible[] en Quelconque)
* `TEstMulti` : Fonction TEstMulti(T[] en Quelconque) en Booléen
* `TMax` : Fonction TMax(T[] en Quelconque) en Quelconque
* `TMin` : Fonction TMin(T[] en Quelconque) en Quelconque
* `Trancher` : Procédure Trancher(T[] en Quelconque, idx1 en Entier, idx2 en Entier, &U[] en Quelconque)
* `Trier` : Procédure Trier(&T[] en Quelconque)
* `TrierD` : Procédure TrierD(&T[] en Quelconque)

## DATELIB

### Structures

* `TDate` → A en Entier, d en Entier, m en Entier, Y en Entier
* `THeure` → H en Entier, M en Entier, S en Entier, N en Entier
* `TDateHeure` → j en Entier, V en Entier, date en TDate, heure en THeure

---

### Fonctions et Procédures

* `Format` : Fonction Format(horodatage en Numérique, format en Chaîne) en Chaîne
* `LocalversUNIX` : Fonction LocalversUNIX(date en Chaîne) en Numérique
* `UNIXversLocal` : Procédure UNIXversLocal(horodatage en Numérique, &tdh en TDateHeure)

## TERMLIB

### Variables locales termlib

* `Constante ANN` = '\x1b[0m'
* `Constante FBC` = '\x1b[47m'
* `Constante FBL` = '\x1b[44m'
* `Constante FCY` = '\x1b[46m'
* `Constante FJA` = '\x1b[43m'
* `Constante FMA` = '\x1b[45m'
* `Constante FNO` = '\x1b[40m'
* `Constante FRO` = '\x1b[41m'
* `Constante FVE` = '\x1b[42m'
* `Constante TAT` = '\x1b[2m'
* `Constante TBC` = '\x1b[37m'
* `Constante TBL` = '\x1b[34m'
* `Constante TCL` = '\x1b[5m'
* `Constante TCY` = '\x1b[36m'
* `Constante TGR` = '\x1b[1m'
* `Constante TIN` = '\x1b[7m'
* `Constante TIT` = '\x1b[3m'
* `Constante TJA` = '\x1b[33m'
* `Constante TMA` = '\x1b[35m'
* `Constante TNO` = '\x1b[30m'
* `Constante TRO` = '\x1b[31m'
* `Constante TSO` = '\x1b[4m'
* `Constante TVE` = '\x1b[32m'

---

### Fonctions et Procédures

* `CacheCur` : Procédure CacheCur()
* `CurPosX` : Fonction CurPosX() en Entier
* `CurPosY` : Fonction CurPosY() en Entier
* `EffaceBE` : Procédure EffaceBE()
* `EffaceEcran` : Procédure EffaceEcran()
* `EffaceFL` : Procédure EffaceFL()
* `EffaceL` : Procédure EffaceL()
* `FRVB` : Fonction FRVB(r en Entier, v en Entier, b en Entier) en Chaîne
* `Hauteur` : Fonction Hauteur() en Entier
* `Largeur` : Fonction Largeur() en Entier
* `MontreCur` : Procédure MontreCur()
* `PosCol` : Procédure PosCol(col en Entier)
* `PosCur` : Procédure PosCur(lgn en Entier, col en Entier)
* `PosCurG` : Procédure PosCurG(col en Entier)
* `PosCurH` : Procédure PosCurH(lgn en Entier)
* `PosEcrire` : Procédure PosEcrire(lgn en Entier, col en Entier, texte en Chaîne)
* `RVB` : Fonction RVB(r en Entier, v en Entier, b en Entier) en Chaîne
* `RappelCur` : Procédure RappelCur()
* `SauveCur` : Procédure SauveCur()

En cours de développement.
