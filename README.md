# Exo_Algo_Anol_Konan_IGS-IA
Exercice Algo

// ** Exercice 1: vérifier l'égalité entre numerique entre deux nombres données *//

AlgoEgalitéNumerique

var  nbre1: réel;
     nbre2: réel;

DEBUT
    Afficher ("Veuiilez entrer nbre1: ");
    Saisir ("Nbre1: ");
    Afficher ("Veuiilez entrer nbre2: ");
    Saisir ("Nbre2: ");
    
     Si nbre1 + (-nbre2) = 0 alors
     Afficher ("Les deux nombres sont egaux");
     sinon:
        afficher ("Les deux nombres ne sont pas egaux");
     FinSi

FIN

// ** Exercice 2: Calculer le taux de contamination de la CI *//

AlgoCalculdutauxDecontaminationDeLaCi

var NbreDeCasPositif: Réel;
    Population: Réel;
    TauxDeContamination: Réel;
DEBUT

   Afficher (" Veuiller saisir le NbrDecasPositif: ");
   Saisir (" NbrDecasPositif ");
   Afficher (" Veuiller Le totale de la Population: ");
   Saisir (" Population: ");
   
   Si ( NbreDeCasPositif == 0 || Population == 0) alors:
   Afficher ( " Impossible de calculer le nombre de cas positif ");
        Sinon:
             Si (TauxDeContamination = 100000*NbreDeCasPositif/Population);
             Saisir ( " TauxDeContamination du Jour est: ");
             FinSi
   FinSi
FIN

// ** Exercice 3: Montrer qu'une année donnée est non-bissextile *//

AlgoAnnnéeNonBissextile

var  Année: réel;

DEBUT
    
    Afficher ("Veuiilez Saisir une année: ");
    Saisir ("Année: ");
    
     Si (Année%4==0) alors:
      afficher ( "Année non Bissextile );
       Sinon:
            Si (Année%100 > 0) alors:
            Afficher (" L'année saisir est Bissextile ");
               Sinon:
                     Si (Année%400 > 0) alors:
                     Afficher (" L'année saisir est Bissextile ");
                     FinSi
            FinSi

     FinSi

FIN