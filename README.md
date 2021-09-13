# tpFinalPermis
Tp final du cours de programmation transactionnel et mobile, Pascal Bourgoin 2021


Résumé de l'application mobile:

1.Ouvre l'application et nous amène à une page de login ou on peut soit login ou clicker un bouton pour subscribe

Login: Nous amène à une activité qui montre les infos du citoyen ainsi que son qrCode si le citoyen à un permis, sinon il avise le citoyen qu'il n'a pas de permis.

Sign Up: Nous amène à une activité qui fait la vérification du numAssMal pour vérifier la validité avec le Ministère Web Service, si il est valide il nous amène à l'activité pour subscribe sinon il nous avise que le numAssMal n'est pas valide avec un Toast.

Subcribe Activity: Donne des champs à remplir pour subscribe en tant que citoyen et garde le numAssMal valide entré précédemment. Une fois fini de remplir le formulaire et clicker sur le bouton create account, il nous ramène à l'activité main pour login et accéder à notre compte.

