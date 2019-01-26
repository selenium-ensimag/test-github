TODO:
=====

Atteignabilité 
*Atteignabilité : Capacité du système à permettre à l'utilisateur de naviguer dans l’ensemble des états observables du système. Propriété non vérifiée si analyse de tâche ou analyse fonctionnelle défectueuse. Métrique : longueur de la trajectoire d'interaction entre p et q.*
- [x] test 1 : login
- [x] test 2 : logout
- [ ] test impossible (création de compte à cause du capcha)

adaptivité  http://iihm.imag.fr/nigay/VERBATIM/L3.1.pdf):
- [x] test 1 (changer le status, et vérifier qu'il est bien mis)
- [x] test 2 (créer un repo, à gauche avec new, et le plus en haut à droite creer repo)
- [ ] test impossible (
  - évaluer une atmosphère génrale, par example si on choisit un thème sombre, sélénium n'est pas capable de nous dire que oui l'ambinace du site est sombre
  - 
)

Homogénéité /cohérence:
- [ ] test 1 (ouverture d'issue/ouverture de PR)
- [x] test 2 (readme.md ouvert sur tout les projets)
- [x] test 3 (tout les boutons d'action sont des boutons verts)
- [ ] test impossible (
  - tester la cohérence sur un navigateur pour une personne aveugle
  - tester qu'il valide bien l'email mais on peut pas à cause du capcha
)

Protection contre les erreurs:
- [x] test 1 (le fait de devoir taper le nom d'un projet pour le supprimer)
- [ ] test 2 (le stay on page lors qu'on quitte un document sans avoir sauvegarder)
- [x] test 3 (on ne peut pas créer un repo sans nom)
- [ ] test impossible (l'authentification à 2 facteur, qui s'assure que la personne qui à rentrer le login et le password n'a pas réussi par erreur !)
