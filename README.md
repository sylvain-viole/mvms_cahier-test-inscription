# mvms_cahier-test-inscription
Ce repository héberge un projet de CAHIER de test pour un parcours utilisateur d'inscription sur le site mavillemonshopping.fr

---

## in scope :
- les parcours d'inscriptions nominaux et erreurs pour les CLIENTS et COMMERCANT pour DESKTOP et MOBILE

## out scope :
- les autres tests (nr, autres parcours, ...)

# Mode d'emploi :
Le cahier est un classeur excel, il comprend :
- Un sommaire redirigeant vers les feuilles de tests
- Un feuille par parcours de test
- Une feuille "TESTS" constituant la base de données de tests qui alimente les parcours

Chaque test renseigne :

**Non modifiable par l'opérateur :**
- la step selon une nomenclature précise
- le SUT (ce qui est testé)
- le JDD (le jeu de donnée)
- le résultat attendu
- le screenshot attendu

**A remplir par l'opérateur :**
- l'état (NON FAIT, OK, KO)
- le résultat obtenu
- le screenshot obtenu
- commentaires
