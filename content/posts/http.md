---
title: "Http"
date: 2026-10-10
draft: false
hiddenInHomeList: true
---

# Protocol de transferència d'hipertext (HTTP)

El protocol de transferència d'hipertext o HTTP (HyperText Transfer Protocol) estableix el protocol per a l'intercanvi de documents d'hipertext i multimèdia al web. HTTP disposa d'una variant xifrada mitjançant SSL anomenada HTTPS.

## Codi's d'estat HTTP

La primera línia d'una resposta HTTP s'anomena 'status line'. Aquesta línia conté un codi numèric anomenat 'status code' i va acompanyat d'un petit text que descriu el codi retornat. El primer dígit de l'status code indica de quin tipus de resposta es tracta. Si un client no reconeix un status code concret, almenys pot utilitzar el primer digit per conèixer la seva família.

## Versions

HTTP ha passat per múltiples versions del protocol, moltes de les quals són compatibles amb les anteriors. El RFC 2145 descriu l'ús dels números de versió d'HTTP. El client diu al servidor al principi de la petició la versió que utilitza, i el servidor utilitza la mateixa o una anterior en la resposta.

0.9 (llançada el 1991)
Obsoleta. Suporta només una ordre, GET, i a més no especifica el número de versió HTTP. No suporta capçaleres. Com que aquesta versió no suporta POST, el client no pot enviar molta informació al servidor.

HTTP/1.0 (maig de 1996)
Aquesta és la primera revisió del protocol que especifica la seva versió a les comunicacions, i encara s'usa àmpliament, sobretot en servidors intermediaris. Permet els mètodes de petició GET, HEAD i POST.

HTTP/1.1 (juny de 1999)
Versió més usada actualment; les connexions persistents estan activades per defecte i funcionen bé amb els proxies. També permet al client enviar múltiples peticions alhora per la mateixa connexió (pipelining) el que fa possible eliminar el temps de Round-Trip delay per cada petició.

HTTP/1.2 (febrer de 2000)
Els primers esborranys de 1995 del document PEP — an Extension Mechanism for HTTP (el qual proposa el Protocol d'Extensió de Protocol, abreujat PEP) els va fer el World Wide Web Consortium i es va enviar a l'Internet Engineering Task Force. El PEP inicialment estava destinat a convertir-se en un rang distintiu de HTTP/1.2. En esborranys posteriors, però, es va eliminar la referència a HTTP/1.2. El RFC 2774 (experimental), HTTP Extension Framework, inclou en gran manera PEP. Es va publicar al febrer de 2000.

HTTP/2 (maig de 2015)
L'any 2012 apareixen els primers esborranys de la nova versió de HTTP (HTTP/2). Aquesta nova versió no modifica la semàntica d'aplicació de http (tots els conceptes bàsics continuen sense canvis). Les seves millores s'enfoquen com s'empaqueten les dades i el transport. Per exemple, afegeix l'ús d'una única connexió, la compressió de capçaleres o el servei 'server push'. Els exploradors més importants només suporten HTTP 2.0 sobre TLS usant l'extensió ALPN[12] que requereix TLSv1.2 o superior.

HTTP/3 (Octubre de 2018)
HTTP/3 és el successor proposat de HTTP/2, que ja està en ús a la web, utilitzant UDP en lloc de TCP per al protocol de transport subjacent. Igual que l'HTTP/2, no és obsolet a les versions principals anteriors del protocol. El suport per a HTTP/3 es va afegir a Cloudflare i Google Chrome al setembre de 2019, i pot ser habilitat en les versions estables de Chrome i Firefox.
