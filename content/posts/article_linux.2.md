---
title: "Curiositats sobre Linux 2"
date: 2026-10-11
draft: false
summary: "Descobreix curiositats, ordres bàsiques i projectes d'automatització amb Linux."
---

# **Com funcionen els usuàris, grups i els permisos d'aquests al accedir arxius en Linux?**

En aquest article aprendrem ha com funcionen l'estrucutura d'usuàris i gestió de permisos,
per tal de saber com funcionen la compartició d'arxius, com modificar permisos dels usuàris. 
És a dir com podem gestionar una estrucutura d'active directory amb Linux.

## ***Com funcionen els usuàris?***

En Linux, els usuaris són comptes que permeten identificar i controlar les persones que utilitzen el sistema. Cada usuari té un nom d'usuari, una contrasenya i un UID (User ID) que l'identifica internament. Els usuaris poden pertànyer a un o més grups, que serveixen per gestionar permisos de manera conjunta. La informació dels usuaris es desa principalment al fitxer /etc/passwd, mentre que les contrasenyes xifrades es gestionen al fitxer /etc/shadow.

Els usuaris tenen diferents permisos segons el seu tipus i els grups als quals pertanyen. El sistema diferencia principalment entre usuaris normals i l'usuari root, que té permisos d'administrador i pot realitzar pràcticament qualsevol acció sobre el sistema. Per gestionar els usuaris es poden utilitzar ordres com useradd, usermod, passwd i userdel. Els permisos sobre fitxers i directoris es controlen mitjançant els permisos de lectura (r), escriptura (w) i execució (x).

![Esquema dels usuaris de Linux](/imatges/usuaris-linux.png)

## ***Com funcionen els permisos?***

A Linux, els permisos serveixen per controlar **qui pot accedir, modificar o executar un fitxer**. Cada fitxer té tres tipus de permisos: **lectura (`r`)**, que permet veure el contingut; **escriptura (`w`)**, que permet modificar-lo; i **execució (`x`)**, que permet executar-lo. Aquests permisos s'apliquen a tres tipus d'usuaris: el **propietari**, el **grup** i la resta d'usuaris. Per exemple, els permisos `rwxr-xr--` indiquen que el propietari pot llegir, modificar i executar el fitxer, mentre que el grup només el pot llegir i executar.

Per compartir fitxers amb altres usuaris, podem utilitzar els **grups de Linux**. Si diversos usuaris pertanyen al mateix grup, podem donar permisos al grup perquè tots els seus membres puguin accedir als fitxers compartits. Les ordres `chmod` i `chown` permeten modificar els permisos i el propietari d'un fitxer, mentre que `chgrp` permet canviar el grup associat. D'aquesta manera, podem controlar de forma segura quins usuaris poden **llegir, modificar o executar** els fitxers compartits.

![Esquema de permisos de Linux](/imatges/permisos-linux.png)