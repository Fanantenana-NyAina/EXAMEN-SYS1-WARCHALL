# EXAMEN-SYS1-WARCHALL-STD23044
## Training: Warchall - The Beginning :
    - creation d'un compte ssh 
    - entrer dans le login via ssh dans le port mentionner
    - on nous demande un mots de passe,
    - on a saisis le mots de passe de notre compte ssh definis au tout debuts
    - on est maintenant dans le linux de warchall
#### 1-level 0 :
    - pour obtenir le mots de passe, on va nous diriger dans ce directory :
```bash
cd /home/level/00_welcome

    - ouvrir le fichier present par la commande :

cat
```
#### 2-level 1 : 
````bash
    - se dirige dans ce directory : 
cd /home/level/01_choice_tree
    - puis : ls -R [pour voir où aller]
    - apres on a pris se chemin :  cd ./blue/hats/grey/solution/patience
    - un fichier SOLUTION.txt est dedans qui contient notre mots de passe
    - on la ouvert avec la commande : cat
````
#### 3-level 2 : 
````bash
    - se dirige vers ce directory directement :
cd /home/level/02/.porb
    - on a vu un fichier au nom de ".solution"
    - ouvrir ce fichier avec : cat
    - solution obtenus
````
#### 4-level 3
````bash
    - se dirige vers ce directory :
cd /home/level/03
    - on a eu possibilite dedans, soit ouvrir ".bash_history" soit allé dans ".shared"
    - notre solution s'est trouvé dans ".bash_history"
    - grace au commande : cat (pour affichier le contenu du fichier)
````

#### 5-level 4
````bash
    - notre premier reflexe a été de nous diriger vers :
cd /home/level/04_kwisatz
    - on a trouve un README dedans qui nous a dit de nous dirigé dan notre "~",
      c'est à dire notre repertoire personnelle
    - on don taper la commande suivante : cd ~
    - puis : ls -R pour voir tous les existants d'abords
    - ensuite, on a changé de directory en tapant : cd /level/04_kwisatz
    - deux (02) etaient dedans, des fichiers readme, c'est la deuxieme qui nous interesse
    - apres avoir tenté d'ouvrir la fichier avec la commande : cat, on a eu un "permission denied"
    - pour contourner celà, on a changé la permission, par la commande :
      chmod +751 README2.md [qui est le nom du fichier]
    - apres ca, on a re-tenté d'ouvrir le fichier par la commande : cat
    - enfin, le fichier s'est ouvert est on a eu notre "flag".
````
#### 6-level 5 
````bash
    - il s'est dirigé dans ce directory par la commande  : cd
    /home/level/05_privacy
    - puis on a affichier ce qui y avait dans ce directory par la commande :
    ls -al
    - on a vu un fichier README
    - on l'a ouvert avec la commande : cat
    - notre solution se trouvait bien dedans.
````


## 	Warchall: Live LFI :

## 	Warchall: Live RFI :
