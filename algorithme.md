Fonction palindrome(m)

        Lire mot
        mot_inverse <- ""

        Pour i de longueur(mot)-1 à 0 pas -1
            mot_inverse <- mot_inverse + mot[i]
        FinPour

        Si mot = mot_inverse Alors
            Retourner "Vrai"
        Sinon
            Retourner "Faux"
        FinSi
        Retourner mot_inverse
Fin de Fonction

