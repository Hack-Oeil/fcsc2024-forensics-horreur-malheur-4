# FCSC 2024 Horreur, malheur 4/5 - Pas si simple persistance

Vous venez d’être embauché en tant que Responsable de la Sécurité des Systèmes d’Information (RSSI) d’une entreprise stratégique.

En arrivant à votre bureau le premier jour, vous vous rendez compte que votre prédécesseur vous a laissé une clé USB avec une note dessus : ```VPN compromis (intégrité). Version 22.3R1 b1647```.

Vous remarquez qu’une fonctionnalité built-in de votre équipement ne fonctionne plus et vous vous demandez si l’attaquant n’a pas utilisé la première persistance pour en installer une seconde, moins “visible”…

Vous cherchez les caractéristiques de cette seconde persistance : protocole utilisé, port utilisé, chemin vers le fichier de configuration qui a été modifié, chemin vers le fichier qui a été modifié afin d’établir la persistance.

Le flag est au format : ```FCSC{<protocole>:<port>:<chemin_absolu>:<chemin_absolu>}```.


Cette épreuve a été découpée en cinq parties :

- Horreur, malheur 1/5 - Archive chiffrée.
- Horreur, malheur 2/5 - Accès initial.
- Horreur, malheur 3/5 - Simple persistance.
- **Horreur, malheur 4/5 - Pas si simple persistance**.
- Horreur, malheur 5/5 - Un peu de CTI.

Auteur : \E

Origine : [Horreur, malheur 4/5 - Pas si simple persistance](https://hackropole.fr/fr/challenges/forensics/fcsc2024-forensics-horreur-malheur-4/)


Fichiers :
- [archive.encrypted](archive.encrypted)
- [horreur-malheur.tar.xz](horreur-malheur.tar.xz)

-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2024-forensics-horreur-malheur-4.git

> cd fcsc2024-forensics-horreur-malheur-4


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/forensics/fcsc2024-forensics-horreur-malheur-4/