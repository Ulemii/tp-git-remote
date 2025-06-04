Fonction nbCar(m)

        return longueur de m

FinFonction

Lire mot

nb <- nbCar(mot)

isEqual <- false

Pour i de 0 à nb div 2

    Si nb[i] = nb[nb - i - 1]

        isEqual <- true

    Sinon

        isEqual <- false
        break

    FinSi

FinPour

Si isEqual = true

    Afficher "C'est un palindrome"

Sinon

    Afficher "Ce n'est pas un palindrome"
        
FinSi
 
// il n'y a plus de commentaire