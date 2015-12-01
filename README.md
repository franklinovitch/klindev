# klindev

Mon environnement de dev __Vagrant__

Basé sur la vagrant box __Scotchbox__ : _https://atlas.hashicorp.com/scotch/boxes/box_

#### Installation :
* Installer __Virtualbox__ ainsi que son _Extension Pack_
* Installer __Vagrant__
* En console, exécuter _git clone https://github.com/quentinbarb/klindev.git_ pour obtenir un folder _klindev_ contenant l'environnement (sous Windows, mieux vaut utiliser la console __Cmder__)
* Se placer dans le répertoire _klindev_ fraîchement créé
* Installer le plugin __Hostmanager__ : _vagrant plugin install vagrant-hostmanager_
* _vagrant up_ (si message d'erreur, il faut peut-être autoriser la virtualisation dans le BIOS : "VTX-machinchose")

#### Utilisation :
* Page web accessible à l'adresse _http://scotchbox.local/_
* PHPmyAdmin à l'adresse _http://scotchbox.local/phpmyadmin_
* Coder dans le dossier _public_, son contenu sera répercuté dans le folder _/var/www/public/_ de la VM
* Pour accéder à la VM, exécuter _vagrant ssh_

#### Cheat sheet :
* _vagrant up_ : lancer la VM
* _vagrant ssh_ : connexion SSH à la VM
* _vagrant reload_ : redémarrer la VM
* _vagrant suspend_ : suspendre l'exécution (RAM de la VM stockée sur le DD)
* _vagrant halt_ : arrêter la VM
* _vagrant destroy_ : détruire complètement la VM (elle sera reconstruite au prochain _vagrant up_

Accès par défaut : _vagrant_, _vagrant_

