---
title: "Samba"
date: 2026-10-10
draft: false
hiddenInHomeList: true
---
# Samba

Samba és una reimplementació en programari lliure del protocol de xarxa SMB/CIFS de Microsoft. Des de la versió 3, Samba no només proveeix de serveis d'impressió i fitxers per diversos clients de Microsoft Windows, sinó que també es pot integrar amb un domini de Windows Server, sigui un PDC o un Domain Member. També pot ser part d'un domini Active Directory.

## Història

Samba va ser originalment desenvolupat per UNIX per Andrew Tridgell a l'Australian National University, usant enginyeria inversa al protocol usat pel servidor DEC PATHWORKS utilitzant un sniffer. Més tard, Tridgell va descobrir que el protocol era gairebé idèntic als usats en altres sistemes de servidor per xarxa, incloent el de Microsoft anomenat LAN Manager, i va decidir centrar-se amb la compatibilitat amb servidors Windows.

## Característiques

Samba també pot compartir directoris d'UNIX per xarxa (incloent tots els subdirectoris). Aquests apareixen als usuaris de Microsoft Windows com a directoris accessibles per la xarxa. Els usuaris d'UNIX poden muntar els directoris compartits com si fossin part de la seva estructura de fitxers o, alternativament, usar la utilitat smbclient instal·lada junt amb Samba per llegir els directoris compartits d'una manera similar a un programa de FTP.