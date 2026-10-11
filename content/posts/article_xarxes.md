---
title: "Curiositats sobre xarxes"
date: 2026-10-11
draft: false
summary: "Descobreix curiositats, ordres bàsiques i projectes d'automatització amb Linux."
---

# **Curiositats sobre Xarxes TCP/IP**

En aquest apartat aprendrem que són els protocols TCP/IP s'aplica.

## ***Què és el protocol TCP/IP? Què és la capa OSI?***

Les **xarxes a Linux** permeten connectar l'ordinador amb altres dispositius per compartir informació i recursos. Cada dispositiu de la xarxa disposa d'una **adreça IP**, que serveix per identificar-lo, i d'altres elements com la **màscara de xarxa**, la **porta d'enllaç** i els **servidors DNS**. Linux permet configurar i consultar aquests paràmetres mitjançant diferents eines i ordres, com `ip`, `ping` o `nmcli`.

Les xarxes també permeten **compartir fitxers, carpetes i serveis** entre diferents ordinadors. Per exemple, podem utilitzar protocols com **SSH, Samba o NFS** per permetre que altres equips accedeixin als recursos del nostre sistema. Perquè la comunicació funcioni correctament, els dispositius han d'estar connectats a la mateixa xarxa o disposar d'una ruta adequada, i els permisos i el tallafoc han d'estar configurats correctament.

### *Què és la capa OSI?*

| Capa | Nom | Funció principal | Exemple |
|---|---|---|---|
| 7 | Aplicació | Proporciona serveis de xarxa a les aplicacions | HTTP, FTP, DNS |
| 6 | Presentació | S'encarrega del format, xifratge i compressió de les dades | SSL/TLS, JPEG |
| 5 | Sessió | Estableix, manté i finalitza les sessions de comunicació | RPC |
| 4 | Transport | Garanteix la comunicació entre dispositius i controla el flux de dades | TCP, UDP |
| 3 | Xarxa | Gestiona l'adreçament i l'encaminament dels paquets | IP, routers |
| 2 | Enllaç de dades | Controla la comunicació dins de la xarxa local | Ethernet, MAC |
| 1 | Física | Transmet els bits físicament pel mitjà de comunicació | Cables, fibra, Wi-Fi |