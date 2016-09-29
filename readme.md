

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



Potem

    vagrant up
    vagrant ssh  

i mozesz cieszyć się swoją wirtualką.    
