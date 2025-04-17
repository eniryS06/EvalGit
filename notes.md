(BRUNO DOS SANTOS)
# Notes GIT (Evaluation)

## Début

Pour commencer j'ai crée un fichier comportants les pages, images et puis j'ai crée un index.html puis une page1.html et page2.html et j'ai envoyé le reste à mes camarades pour qu'ils puissent faire le css et mobile.

Ensuite, j'ai installé https://gitforwindows.org/ pour pouvoir accéder au bash et j'ai pu commencer à taper les commandes après que notre camarade Syrine est crée un nouveau repository

```bash
cd Documents/
mkdir EvalGit
cd EvalGit
```

Une fois dans le document EvalGit j'ai pu initialiser le dépôt Git

```bash
git init
ls -a
```

## Connexion au Dépôt

Ensuite, j'ai pu me connecter au Dépôt.

```bash
git remote add origin https://github.com/eniryS06/EvalGit.git
git config user.name "dsfabruno"
git config user.email "bruno.dos-santos-failde-alves@efrei.net"
```

## Finalisation

Enfin, pour la dernière étape j'ai cloné et ajouter les 3 pages d'html.

```bash
git clone https://github.com/enirys06/EvalGit.git
nano index.html
git add index.html
git commit -m "version 1 du html"
nano page1.html
git add page1.html
git commit -m "version 1 du html"
nano page2.html
git add page2.html
git commit -m "page 2.html"
```

Après je me suis connecté et push dans le GitHub en ayant mis le token par la suite après avoir rentré mon pseudo dans la page qui s'affiche juste après avoir rentré la commande.

```bash
git config user.name "dsfabruno"
git config user.email "bruno.dos-santos-failde-alves@efrei.net"
git push -u origin master
```
