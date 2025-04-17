### Se placer au bon endroit et initier
```bash
Cd Documents/
Mkdir EvalGit
Cd EvalGit
Git init
Ls -a
```
### relier mon pc a github
```bash
Git remote add origin https ://github.com/madok06/EvalGit.git
Git config user.name “madok06”
Git config user.email “Mounia.dja-daouadji@efrei.net”
```
### Se connecter au git commun (celui de Syrine)
```bash
Git clone https://github.com/enirys06/EvalGit.git
```
### Remplir le github
```bash
Nano sstyle.css ## créer le css
Git add style.css 
Git commit -m  "version 1 du css"
Git config user.name “madok06”
Git config user.email "Mounia.dja-daouadji@efrei.net"
git push -u origin main ## mettre sur la branche main
git checkout master
git pull origin master 
git branch version2
nano index.html
nano page1.html
nano page2.html
git checkout version2
git add index.html
git commit -m "version2(correction)"
git push -u origin version2
git checkout main
nano style.css
git add style.css
git commit -m "version3 css"
git push -u origin verssion3
```
### merger la derniere version sur master
```bash
git checkout master
git merge version-4
## nous avons des erreurs lorsque nous voulons merger sur la branche
```
