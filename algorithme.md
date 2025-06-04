Procédure estUnPalindrome(m)
    Début
        Lire mot
        mot_inverse <- ""

        Pour i de longueur(mot)-1 à 0 pas -1
            mot_inverse <- mot_inverse + mot[i]
        FinPour

        Si mot = mot_inverse Alors
            Afficher ("Ce mot" + mot + " est un palindrome")
        Sinon
            Afficher ("Ce mot" + mot + " n'est pas un palindrome")
        FinSi
    Fin     
Fin de Precédure

