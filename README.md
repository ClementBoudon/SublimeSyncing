## Dossier de paramètres personnalisés

### Utilisation

* Installer Sublime Text 3

http://www.sublimetext.com/3

* Installer PackageControl

https://sublime.wbond.net/installation

* Cloner le repository

    cd "C:\Users\[Username]\AppData\Roaming\Sublime Text 3\Packages\User"
    git clone -b master https://github.com/ClementBoudon/SublimeSyncing.git

### Configurations diverses

#### LiveReload

	cd "C:\Users\[Username]\AppData\Roaming\Sublime Text 3\Packages"
	rm -rf LiveReload
	git clone -b master https://github.com/Grafikart/ST3-LiveReload.git LiveReload

#### SublimeLinter (PHP, JS, CSS)

* Installer Node (http://nodejs.org/)

* Exécuter 
	
	npm install jshint
	npm install cssslint

* Installer PHP (http://windows.php.net/download/, unzip dans C:\php, ajout au PATH)