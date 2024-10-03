# FR-ALGO Librairie Standard

Une librairie standard pour **ALGO**.

En cours de développement.

## Contenu

### estalpha

`estalpha(c en Caractère) en Booléen`
Retourne VRAI si `c` est un caractère alphabétique.

### estnum
`estnum(c en Caractère) en Booléen`
Retourne VRAI si `c` est un chiffre.

### chaîne_estnum

`chaîne_estnum(chaîne en Chaîne) en Booléen`
Retourne VRAI si `chaîne` est un nombre.

### majus

`majus(chaîne en Chaîne) en Chaîne`
Convertit une chaîne de caractères en majuscules.

### minus

`minus(chaîne en Chaîne) en Chaîne`
Convertit une chaîne de caractères en minuscules.

### rvb

`rvb(r, v, b en Entier) en Chaîne`
Retourne une `séquence d'échappement` qui modifie la couleur du texte dans un terminal.

### frvb

`frvb(r, v, b en Entier) en Chaîne`
Retourne une `séquence d'échappement` qui modifie la couleur de fond dans un terminal.

### attr

`attr(a en Chaîne) en Chaîne`
Retourne une `séquence d'échappement` qui modifie un attribut du texte dans un terminal.
`a` consiste en un code de deux lettres qui peut avoir l'une des valeurs suivantes :

*  **gr**(as)
*  **it**(alique)
*  **so**(uligné)
*  **cl**(ignotant)
*  **in**(verse)

Si la valeur de `a` n'est pas l'une des valeurs citées plus haut, `attr`

### fina

`fina()`
Annule tous les attributs/couleurs en cours.

### base

`base(nombre, base en Entier) en Chaîne`
Convertit un nombre entier positif en la base donnée.

*Exemple* :

```
# Convertir le nombre 48879 en base 16.
base(48879, 16)
# BEEF
```

`base` doit être un entier compris entre 2 et 36 inclus.
En cas d'erreur, `base` retourne la valeur `"-1"`

### base10

`base10(nombre en Chaîne, base en Entier) en Entier`
Convertit en base 10 un nombre exprimé dans une base donnée.

*Exemple* :

```
base10("BEEF", 16)
# 48879
```

En cas d'erreur, `base10` retourne la valeur `"-1"`

### Scinder

`Scinder(chaine, separateur, &elements[] en Chaîne)`
Scinde une chaîne de caractères en éléments d'un tableau selon un séparateur.

*Exemple* :

```
Tableau t[] en Chaîne
Variable c en Chaîne
c <- "A,B,C,D,1,2,3,4"
Scinder(c, ",", t)
# t = ["A", "B", "C", "D", "1", "2", "3", "4"]
# VRAI
```

### efface_ecran

