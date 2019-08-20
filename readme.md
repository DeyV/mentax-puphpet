

Wymnagane:
 - virtualbox
 - vagrant


Zalecam zainstalowanie dodatku plikunącego aktualność vbguest

    vagrant plugin install vagrant-vbguest


Następnie nalezy skopiować plik

    puphpet/config-custom.yaml.dist

jako

    puphpet/config-custom.yaml  

i poprawnie ustawic swoje ściezki ktore będą mapowane do wirtualki.


Dodaj nazwy hostów z pliku config do 
  %SystemRoot%\system32\drivers\etc\hosts

W tej chwili domyślne to: 
 -  192.168.56.101 mentax.developer
 
Można dodać też inne.


Potem

    vagrant up
    vagrant ssh  

i mozesz cieszyć się swoją wirtualką.    


PROBLEMY
------------

1. Failed to open/create the internal network

https://stackoverflow.com/questions/43580778/failed-to-create-the-host-only-adapter-windows-10-docker-virtualbox/48227842#48227842
https://stackoverflow.com/questions/33725779/failed-to-open-create-the-internal-network-vagrant-on-windows10