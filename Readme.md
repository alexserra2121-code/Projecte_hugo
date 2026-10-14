# Explicació #

### Nom del projecte ###
TecnoCat S.L

### Eina utilitzada i versió ###
Hugo ( v0.167.0)

### Motiu de l'eleccio de l'eina ###
Vam escollir aqueta eina degut a que ens sonava de alguna cosa i vam pensar que era amb la que estavem una mica mes familiaritzats que la resta, ja que en la presentacio de la eina que va fer la Carme a classe la vam veure mes intuitiva.

### Procés d’instal·lació ###
1. Desde powershell fem us de la seguent comanda: winget install --id Gohugo.Hugo.Extended
2. Comprovem la versio per tal de assegurar-nos que s'ha instalat correctament: hugo version

### Com executar la web localment ###
- Dins de la carpeta del nostre projecte executem: hugo server
- Compeim l'enllaç local que ens proporciona normalment es: http://localhost:1313/

### Com executar la web localment ###
- Per crear una web fem servir la comanda: hugo new sites nom_del_lloc_web

### Com publicar-la ###
1. Creem un repositori github
2. Copiem el link de el repo de github
3. Ens dirigim a l'arrel del nostre projecte i inicialitzem git 
4. Fem servir la seguent comanda per vincular el nostre git amb github git remote add origin link_repo_github
5. Fem un push de la branca determinada  git push -u origin main (primera vegada) git push (habitualment)


### Estructura del projecte ###
Quan s'utilitza hugo i creem la web amb la comanda explicada anteriorment es genera una estrctura predefinida la qual facilita la configuracio i creacio de aquets lloc web, dins l'arrel:
    -archetypes
    -assets 
    -content (les pagines web.md, artciles... que componen el nostre lloc web)
    -data
    -i18n
    layouts
    -public (es on es genere la web en html, tambe comte la pagina error 404, les imatges que s'utilitzaran en la generacio del html,)
    -static (emagatzem fitxers estatic que coponen les webs com per exemple imatges... es a dir aqui es hi ha tot el que es publicara en la web)
    -themes (es on es guarden les plantilles descarregades y utilitzades)

### URL URL de la web publicada ###
https://alexserra2121-code.github.io/Projecte_hugo/ 