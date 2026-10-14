---
title: "SSH"
date: 2026-10-10
draft: false
hiddenInHomeList: true
---

# SSH

Secure Shell (abreujat SSH) és un protocol de xarxa criptogràfica i un paquet de programes per accedir a màquines remotes de manera segura a través xarxes insegures. Permet gestionar l'ordinador distant. Gairebé tots els sistemes operatius inclouen clients del protocol basats en la implementació OpenSSH com ara Linux, macOS i Windows 10.

## Utilitat de SSH

SSH treballa de forma similar al telnet. La diferència principal és que SSH fa servir tècniques de xifrat que transmet la informació per la xarxa de manera il·legible. Cap persona pot descobrir l'usuari i la contrasenya de la connexió ni el que s'escriu durant la sessió. Tot i que és possible atacar aquest tipus de sistema mitjançant un atac de replay i manipular d'aquesta manera la informació entre destinacions.

## Programes

ssh: per accedir a màquines remotes i executar-hi programes.
scp: per copiar fitxers entre màquines remotes.
ssh-keygen: per generar claus d'autenticació.
ssh-copy-id: per copiar claus entre màquines.
ssh-agent: per gestionar l'autenticació amb clau.
ssh-add: per afegir claus a l'agent d'autenticació.