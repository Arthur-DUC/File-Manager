# File-Manager

## Simulation d’un système de gestion de fichiers
Le but de ce projet est de simuler un système de gestion de fichiers (SGF ou SF) en mettant en
œuvre les principes vus en CTD et TP. Le système de fichiers simulé sera une simplification du type
de SF utilisé sous Unix/Linux

## Qu’est-ce qu’un Système de Gestion de Fichiers?
Un système de fichiers (SF) – ou système de gestion de fichiers (SGF) – de type Linux permet de
stocker et d’organiser des informations dans des fichiers en mémoire secondaire, notamment sur un
disque dur. Il assure ainsi plusieurs fonctions : sécuriser les fichiers, leur allouer de la place (blocs) en
mémoire secondaire, les localiser et retrouver les données, proposer des opérations qui permettent aux
programmes d’application de manipuler les fichiers, etc.
Un fichier (Unix) est une suite finie d’octets. Un fichier est stocké dans un certain nombre de blocs
(d’un nombre fixé d’octets, historiquement multiple de 512 octets) sur un disque.
Un inode (ou nœud d’index) est une structure de données contenant des informations à propos d’un
fichier ou d’un répertoire stocké dans un système de fichiers. Chaque inode est repéré dans la table
des inodes par son numéro (indice) dans cette table.

<img width="664" height="631" alt="Screenshot 2026-03-17 at 14 11 59" src="https://github.com/user-attachments/assets/ff9ea0ba-a7b1-4b75-b297-5c048e6008a6" />

