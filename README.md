VERHOEST Arthur 

URL : https://github.com/Zillixxx/IPL-social/

Ce module permet de valider un mot de passe en fonction de quatre critères de sécurité :

    Longueur minimale : Le mot de passe doit avoir au moins 8 caractères.
    Caractère spécial : Le mot de passe doit contenir au moins un caractère spécial parmi les suivants : !@#$%^&*(),.?":{}|<>.
    Chiffre : Le mot de passe doit contenir au moins un chiffre (0-9).
    Séquence interdite : Le mot de passe ne doit pas contenir la séquence "ipl" en minuscules.

La fonction validatePassword(password) retourne true si toutes les conditions sont remplies, sinon elle retourne false  


Testez tous les test avec la commande "npm run test"


