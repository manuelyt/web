
 

## 11/3/2019 
 
subi mis marcadores
 
  
 <br>
<br>
<br>

## 17/3/2019 
 <br>
se me ocurrio hacerlo con bootstrap<br>
valla infierno hasta que consigo que funcione<br>
 
hay que bajarse los js y css de bootstrap y jquery, y ponerlos bien, que las paginas html los pillen bien<br>
estuve un rato toqueteando hasta que me di cuenta del problema de los js s y los css s<br>
y para dejarlo fino, lo bueno fue depurar con el chrome<br>
y cuando ya lo tenia, y funcionaba, lo subo<br>
 
pero, claro, en el github las url s relativas no funcionan, porque tienen este formato :<br>
http://htmlpreview.github.io/?https://github.com/manuelyt/web/blob/master/index.html<br>
el index se ve de puta madre, se ve chulo, y se ve bien en el movil<br>
pero claro, cuando se navega no funciona, se ve el codigo html, no se ven bien las paginas<br>
 
dir       archivo           comentarios
 
00manu                ----> aqui he dejado los html de los marcadores<br>
css                   ----> el ejemplito de bootstrap del blog usaba un css que puse aqui<br>
dist                  ----> el bootstrap y el jquery<br>
html                  ----> mis paginas<br>
js                    ----> un js del ejemplito de bootstrap<br>
         README.md
 
  
<br>
<br>
<br>

## 6/10/2020 
<br>
para acceder al indice :
 
http://htmlpreview.github.io/?https://github.com/manuelyt/web/blog/master/html/index.html
 
  <br>
 
hay paginas staticas subidas :
 
http://htmlpreview.github.io/?https://github.com/manuelyt/web/blog/master/html/doc/cal-lab-2019.html
 
http://htmlpreview.github.io/?https://github.com/manuelyt/web/blog/master/html/doc/prog/gen-imei/imei-22.html
 
 
<br>
<br>
<br>

## 21/12/2021 

<br>

cuando se mira el debug en el chrome es norma que salgan 2 warnings y 2 errores  :
<br>
<br>
```
Error with Permissions-Policy header: Unrecognized feature: 'interest-cohort'.

Refused to apply style from 'https://raw.githubusercontent.com/manuelyt/web/master/dist/css/bootstrap.min.css' because its MIME type ('text/plain') is not a supported stylesheet MIME type, and strict MIME checking is enabled.

Refused to apply style from 'https://raw.githubusercontent.com/manuelyt/web/master/html/pers/css/blog.css' because its MIME type ('text/plain') is not a supported stylesheet MIME type, and strict MIME checking is enabled.

DevTools failed to load source map: Could not load content for http://htmlpreview.github.io/bootstrap.min.css.map: HTTP error: status code 404, net::ERR_HTTP_RESPONSE_CODE_FAILURE
```
<br>

esos errores y warnings de momento los estoy ignorando, cuando salen otros errores conviene echarles un vistazo

<br>

ademas, tener en cuenta que aunque se modifique ( haciendo commit ) no se refresca
es un poco coñazo trabajar asi

