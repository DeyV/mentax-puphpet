

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
