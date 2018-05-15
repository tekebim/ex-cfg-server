# ex-cfg-server

## Ajout clé ssh vers le serveur distant

    ssh-copy-id -i ~/.ssh/id_rsa.pub user@domaine.net

## Ajouter un utilisateur

    adduser git
    
## Créer deux dossiers ( repertoire git / www )

* Droits sur le dossier
    
        chown -R root:git-users /var/www/
    
## Droits dans le dossier
