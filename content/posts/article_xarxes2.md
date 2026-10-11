---
title: "Curiositats sobre xarxes 2"
date: 2026-10-10
draft: false
summary: "Descobreix curiositats, ordres bàsiques i projectes d'automatització amb Linux."
---
# **Curiositats sobre Xarxes DNS**

En aquest apartat aprendrem que és el protocol DNS i com s'aplica.

## ***Què és el protocol DNS?***

El DNS (Domain Name System) és el protocol que permet convertir els noms de domini que utilitzem habitualment, com www.google.com, en adreces IP que els ordinadors poden entendre, com 142.250.184.4. D'aquesta manera, no cal memoritzar les adreces IP dels servidors. Quan un usuari introdueix un domini al navegador, l'ordinador consulta un servidor DNS per saber quina adreça IP correspon a aquell nom.

Per exemple, quan escrivim www.exemple.com al navegador, l'ordinador envia una consulta al servidor DNS configurat. El servidor DNS busca l'adreça IP associada al domini i la retorna a l'ordinador. Amb aquesta IP, el navegador ja pot establir una connexió amb el servidor web i obtenir la pàgina sol·licitada. Aquest procés es realitza normalment mitjançant el port 53 i pot utilitzar UDP o TCP segons el tipus de comunicació.

## ***Com funciona un procés DNS?***

1. L'usuari introdueix un **nom de domini** al navegador.
2. L'ordinador envia una **consulta DNS** al servidor DNS.
3. El servidor DNS busca l'**adreça IP** associada al domini.
4. El servidor DNS retorna l'**adreça IP** a l'ordinador.
5. El navegador utilitza aquesta IP per **connectar-se al servidor web**.
6. El servidor web respon i el navegador mostra la **pàgina web**.

![Imatge com funciona un DNS](/imatges/funciona-dns.png)