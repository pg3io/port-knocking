Port Knocking
===
[![langage](https://img.shields.io/badge/Langage-ansible-green.svg)](https://www.ansible.com/)
[![pg3.io](https://img.shields.io/badge/made%20by-PG3-orange.svg)](https://twitter.com/pg3io/)
[![Apache 2.0 Licence](https://img.shields.io/hexpm/l/plug.svg)](LICENCE)


# Prérequis

* [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

# Utilisation
MAJ fichie ``hosts`` avec la list de serveurs et list de ports (uniquement compatible port TCP port le moment).

```
ansible-playbook portKnocking.yaml -i hosts
``` 

# License
Ce projet est sous licence [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0) consulter le fichier [LICENSE](LICENSE) pour plus de détails.

# Informations sur l'auteur
Ce projet a été créé par [PG3](https://pg3.io) en novembre 2020.
