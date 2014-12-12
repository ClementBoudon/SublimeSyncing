# Dossier de paramètres personnalisés perso

## Utilisation

* Installer Sublime Text 3

http://www.sublimetext.com/3

* Installer PackageControl

https://sublime.wbond.net/installation

* Cloner le repository

Le dossier utilisateur peut changer.

    cd "C:\Users\Username\AppData\Roaming\Sublime Text 3\Packages\User"
    git init
    git remote add origin https://github.com/ClementBoudon/SublimeSyncing.git
    git fetch
    git checkout -t origin/master


## Configurations diverses

### LiveReload
Intégration d'une version compatible Sublime Text 3

    cd "C:\Users\Username\AppData\Roaming\Sublime Text 3\Packages"
    rm -rf LiveReload
    git clone -b master https://github.com/Grafikart/ST3-LiveReload.git LiveReload

### SublimeLinter (PHP, JS, CSS)

* Installer Node (http://nodejs.org/)

* Exécuter

jslint peut être préféré à jshint.

    npm install jshint 
    npm install cssslint

* Installer PHP (http://windows.php.net/download/, unzip dans C:\php, ajout au PATH)

### Git

* Installer git (http://git-scm.com/)
