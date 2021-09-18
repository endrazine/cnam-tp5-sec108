# CNAM TP5 : Generation d'un exploit pour Microsoft WORD (CVE-2021-40444)

Le but de ce TP est de se familiariser avec l'exploitation des corruptions mémoire, via l'exploitation d'un stack overflow simple.

En passant, nous allons apprendre à utiliser git, docker, et un debugger : gdb.

## Prérequis

Utiliser la commande "git clone" pour cloner le repertoire git de ce TP sur cette machine.

        jonathan@blackbox:~$ mkdir tp
        jonathan@blackbox:~$ cd tp
        jonathan@blackbox:~/tp$ git clone git@github.com:endrazine/cnam-tp5-sec108.git
        Cloning into 'cnam-tp2-sec108'...
        remote: Enumerating objects: 15, done.
        remote: Counting objects: 100% (15/15), done.
        remote: Compressing objects: 100% (13/13), done.
        remote: Total 15 (delta 1), reused 12 (delta 1), pack-reused 0
        Receiving objects: 100% (15/15), 24.13 KiB | 4.83 MiB/s, done.
        Resolving deltas: 100% (1/1), done.
        jonathan@blackbox:~/tp$ ls
        cnam-tp5-sec108
        jonathan@blackbox:~/tp$ 

## Background

La vulnérabilité CVE-2021-40444 a été découverte dans la nature (0day).
Lire les détails ici: https://www.kaspersky.fr/blog/cve-2021-40444-vulnerability-mshtml/17575/

## Intitulé

Suivre les instructions (en Anglais) ici: https://github.com/lockedbyte/CVE-2021-40444

## Verification

Vérifier que l'exploit ouvre bien la calculatrice (calc.exe) à l'ouverture du fichier .docx généré. Pourquoi utilise t'on calc.exe ?


