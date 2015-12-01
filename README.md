# klindev
Mon environnement de dev Vagrant

Basé sur la vagrant box Scotchbox

#### Installation :
* Installer _Virtualbox_
* Installer _Vagrant_
* Faire un "git clone https://github.com/quentinbarb/klindev.git" pour obtenir un folder contenant l'environnement
* En console, se placer dans le folder klindev fraîchement créé (sous Windows, mieux vaut utiliser la console _Cmder_)
* "vagrant init"
* "vagrant up"
* Page web accessible à l'adresse "http://scotchbox.local/"
* Coder dans le dossier "public", son contenu sera répercuté dans le folder "/var/www/public/" de la VM
* Pour accéder à la VM, exécuter "vagrant ssh"