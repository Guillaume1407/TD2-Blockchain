# TD2-Blockchain

import secrets                  //utilisé pour créer un entier aléatoire
import hashlib		        //Fonction de hashage
from ecdsa import SigningKey    //Obtenir la clé publique avec la clé privée


Fonctions utilisées:
-hex2bin            //Convert hex in bin 
-split              //Découpe un tableau en 12 morceaux 
-Creer_seed	    //Génère une graine 
-Seed_mnemonic      //Permet l’import d’une seed mnémonique
-Private_key	    //Afficher la clé publique/privée et le chaincode 
-Kid_key	    //Affiche les infos pour une clé enfant
-Menu		    //Interface avec l'utilisateur