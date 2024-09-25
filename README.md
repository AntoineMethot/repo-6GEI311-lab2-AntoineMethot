Antoine Méthot
META13060104
amethot@etu.uqac.ca

1. Ce que j'ai appris dans ce laboratoire:
  - La création d'un environnement virtuel python à l'aide de "python -m venv 6GEI311_Lab2_AntoineMethot"
  - Activer l'environnement en utilisant activate.bat dans scripts
  - Comment installer flask à l'aide de "pip install flask" dans un environnement virtuel
  - Créer un fichier requirements.txt qui contient toute les dépendances de l'environnement avec "pip freeze > "requirements.txt"
  - Installer des dépendances à partir d'un fichier requirements.txt avec "pip install -r requirements.txt"
  - prix connaissance de l'existance de nginx et qu'il fait du "Load distribution"
  - Que le réseau eduroam de l'UQAC est très sécurisé


2. Les réponses aux questions posées avec les instructions de la manip:
   - Arrêtez l’application python, testez avec la même adresse sur votre navigateur. Qu’estce que vous remarquez?
       Maintenant qu'il n'y a plus rien à l'adresse à laquelle on se connecte on a une erreure "This site can't be reached/refused to connect" qui est normal puisqu'on a étient l'application.

   - Ouvrez le navigateur sur une machine quelconque, et naviguez vers l’adresse faites des refresh plusieurs fois, qu’est-ce que vous remarquez?
       On remarque que la page alterne entre l'application du Membre A et celui du Membre B.

   - Arrêtez l’application du membre A sur la machine du membre A, est ce que l’application est toujours accessible via:
      a. http://IP_MACHINE_A:3000/ ?
         l'application du Membre A n'est plus accessible via l'ip du Membre A
     
      b. http://IP_MEMBRE_A:8181/ ?
         l'application est toujours accessible et cest celle du Membre B. Ceci est possible à l'aide de nginx
