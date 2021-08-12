# Orange-Arcane-Automatisation

Automatisation du projet Arcane avec l'outil Ansible

C'est quoi le projet Arcane ?

Arcane (Applications et Ressources CArtographique pour Navigation Externe) est le nom de la plateforme de service dédiée à la diffusion d'informations géographique
et plus particulièrement d'informations sur la couverture des réseaux d'Orange. Le nom du groupement de services associé est Cartographie (de la) Couverture Réseaux.
Ces services proposent des cartes de couverture réseau (mobile, fixe, fibre, WIFI) sur le portail internet et sur l'application mobile Mon Réseau. 
Suite au déploiement de la 5G en décembre 2020, les cartes de couverture réseau d’Orange doivent être actualisées à chaque fois que la 5G est déployée dans une certaine région
en France.

ansible-playbook -i inventory/test copy.yml

ansible-playbook -i inventory/test arcmepwas.yml -e "date=20210319 numDT=164"
