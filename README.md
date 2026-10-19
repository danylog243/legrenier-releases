# Application de gestion financière d'une église — publications

Ce dépôt ne contient **aucun code source**. Il ne sert qu'à distribuer les versions publiées de l'application :

- les binaires pour Windows, Linux et Raspberry Pi, et l'installeur Windows ;
- `SHA256SUMS`, les empreintes SHA-256 de chaque fichier ;
- `SHA256SUMS.sig`, la signature Ed25519 de ces empreintes ;
- `manifest.json`, la liste des fichiers d'une version avec leur taille et leur empreinte ;
- `grenier-vX.Y.Z-mise-a-jour.zip`, le paquet de mise à jour hors ligne (clé USB).

Les installations de l'application lisent ce dépôt pour proposer les mises à jour. Elles n'installent un fichier que si sa signature correspond à une clé de confiance intégrée au programme : un fichier modifié ou non signé est toujours refusé.

Pour installer ou mettre à jour, téléchargez la dernière version dans l'onglet **Releases**, ou utilisez *Paramètres > Mises à jour* dans l'application.

Conçu par Danylog – danylog.com
