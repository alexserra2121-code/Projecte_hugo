---
title: "Curiositats sobre Linux"
date: 2026-10-11
draft: false
summary: "Descobreix curiositats, ordres bàsiques i projectes d'automatització amb Linux."
---

# **Curiostiats sobre Linux**

En aquest article especific tractarem moltes curiositats sobre Linux com ara la historia, comandes bàsiques d'administració, posibles projectes d'automatizació de procesos que podem realizar en aquests entorns i posibles aplicacions rellevants de codi lliure.


## ***Com va començar Linux?***

Linux va començar com a un projecte universitari de l'estudiant d'enginyeria Linux Torbald, un estudiant de Ciencies de la computació de la Universitat de Helsinki, aquest va començar per demostrar que els sistemes operatius revolucionaris en la época podien ser lliures hi ha l'abast de qualsevol persona, i va aprofitar l'escussa d'un treball escolar per tal de desenvolupar el primer nucli lliure de tota la historia.

Un cop després que Linus Tovald dissenyes el nucli del sistema, el projecte va pasar a mans de Ken Thompson i Dennis Ritchie on el qual van aprofitar el kernel desenvolupat per crear el primer sistema operatiu lliure portátil, modificant el codi per poder-lo incloure en dispositius portables. Un cop fet aixó les diferents universitats dels Estats Units van començar a distribuir versions de Unix implementades en estacions de treball.

Més endevant durant la década dels 80, Richard Stallman va iniciar el projecte GNU, que és tractava de aprofitar part del codi de Unix per desenvolupar un nou sistema operatiu lliure, amb un kernel diferente anomenat Hurd. Aquest implementava arquitectura modular i total llibertat per part dels usuàris per tal de modificar el codi i crear diferents sistemes independents, amb la obligació de compartir tots els resultats amb la comunitat per fer que el sistema lliure s'expangues.

Aquests dos sistemes Unix van ser els precausors per tal que és poguessin crear els diferents sistemes futurs que coneixem ara com: 
- Ubuntu 
- Debian 
- Cache OS 
- Kali Linux
...


## ***Com podem administrar Linux?***

Per tal de poder administrar Linux, ho podem fer amb comandes de terminal, un bon exemple de comandes bàsiques poden ser les seguents:

|-------------|----------------------------------------------------|
| Comandes    | Descripció                                         | 
|-------------|----------------------------------------------------|
|     ls      | Llista el contingut d'un directori                 |
|     cd      | Cambiar el directori de treball                    |
|    mkdir    | Crear nous directoris                              |
|     rm      | Eliminar arxius o directoris                       |
|   cp/mv     | Copia/mou/renombra directoris                      |  
| chmod/chown | Gestiona permisos i propietaris d'arxius           |
|  systemctl  | Controla serveis (Start/Stop/Status/Enable)        |
| apt update  | Actualitza la llista de paquets                    |
| apt upgrade | Reinstal·la tota la llista de paquets i actualitza |
|------------------------------------------------------------------|

## ***Quins projectes d'automatització podem fer?***

Per tal d'organitzar les idees dividirem el bloc de projectes en tres grans apartats senzills, mitjà, complexes, aquestes ón:

###  *Projectes Senzills*

- Copies de seguretat automatiques.
- Neteja automática del sistema com ara eliminar fitxers temporals, eliminar logs antics…
- Monitoritzar l'espai del disc.

### *Projectes Mitjans*

- Script que comprova que servidors instal·lats están funcionant correctament.
- Monitorització d'un servidor web com ports, connexions…
- Sistema automatic d'usuaris.

### *Projectes Complexos*

- Sistema de copies de seguretat amb la implementació d'informes diaris i eliminación automática cada 30 dies.
- Creació d'un servidor web automatic.
- Sistema de monitorització de servidors.